# TIF Balance Sheets

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/tif-balance-sheets-fe2c7) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/hezc-e4be) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/hezc-e4be/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/hezc-e4be/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | hezc-e4be |
| Name | TIF Balance Sheets |
| Attribution | City of Chicago |
| Category | Community & Economic Development |
| Tags | tif |
| Created | 2011-05-18T18:35:58Z |
| Publication Date | 2011-05-18T18:35:58Z |

## Description

Combined statements of revenues, expenditures, and changes in fund balances for the year ending December 31, 2009.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| No       | time           | :updated_at        | updated_at         | meta_data | meta_data   |
| Yes      | series tag     | tif_id             | TIF ID             | text      | text        |
| Yes      | series tag     | tif_name           | TIF NAME           | text      | text        |
| Yes      | series tag     | reporting_category | REPORTING CATEGORY | text      | text        |
| Yes      | series tag     | description        | DESCRIPTION        | text      | text        |
| Yes      | numeric metric | amount             | AMOUNT             | money     | money       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:hezc-e4be d:2011-08-30T07:00:01.000Z t:description="Property tax" t:reporting_category=Revenues t:tif_id=T-072 t:tif_name=24th/Michigan m:amount=1109711

series e:hezc-e4be d:2011-08-30T07:00:01.000Z t:description="Sales tax" t:reporting_category=Revenues t:tif_id=T-072 t:tif_name=24th/Michigan m:amount=0

series e:hezc-e4be d:2011-08-30T07:00:01.000Z t:description=Interest t:reporting_category=Revenues t:tif_id=T-072 t:tif_name=24th/Michigan m:amount=8115
```

## Meta Commands

```ls
metric m:amount p:double l:AMOUNT t:dataTypeName=money

entity e:hezc-e4be l:"TIF Balance Sheets" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/hezc-e4be

property e:hezc-e4be t:meta.view v:id=hezc-e4be v:category="Community & Economic Development" v:attributionLink=http://www.cityofchicago.org/city/en/depts/dcd/provdrs/tif.html v:averageRating=0 v:name="TIF Balance Sheets" v:attribution="City of Chicago"

property e:hezc-e4be t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:hezc-e4be t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| :updated_at | tif_id | tif_name      | reporting_category | description                                                                                      | amount     | 
| =========== | ====== | ============= | ================== | ================================================================================================ | ========== | 
| 1314687601  | T-072  | 24th/Michigan | Revenues           | Property tax                                                                                     | 1109711.00 | 
| 1314687601  | T-072  | 24th/Michigan | Revenues           | Sales tax                                                                                        | 0.00       | 
| 1314687601  | T-072  | 24th/Michigan | Revenues           | Interest                                                                                         | 8115.00    | 
| 1314687601  | T-072  | 24th/Michigan | Revenues           | Total revenues                                                                                   | 1117826.00 | 
| 1314687601  | T-072  | 24th/Michigan | Expenditures       | Costs of studies, admin., and professional services. (q)(1)                                      | 20154.00   | 
| 1314687601  | T-072  | 24th/Michigan | Expenditures       | Marketing costs. (q)(1.6)                                                                        | 0.00       | 
| 1314687601  | T-072  | 24th/Michigan | Expenditures       | Property assembly, demolition, site preparation and environmental site improvement costs. (q)(2) | 0.00       | 
| 1314687601  | T-072  | 24th/Michigan | Expenditures       | Costs of rehabilitation, reconstruction, repair or remodeling and of existing buildings. (q)(3)  | 0.00       | 
| 1314687601  | T-072  | 24th/Michigan | Expenditures       | Costs of construction of public works and improvements. (q)(4)                                   | 4640384.00 | 
| 1314687601  | T-072  | 24th/Michigan | Expenditures       | Cost of job training and retraining. (q)(5)                                                      | 0.00       | 
```