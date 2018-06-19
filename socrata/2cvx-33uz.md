# FDNY Fire Department Fee

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fdny-fire-department-fee-8f15b) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/2cvx-33uz) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/2cvx-33uz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/2cvx-33uz/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 2cvx-33uz |
| Name | FDNY Fire Department Fee |
| Attribution | Fire Department of New York City (FDNY) |
| Category | Public Safety |
| Tags | fdny, fire department, permit fee, fire safety |
| Created | 2013-01-23T18:22:25Z |
| Publication Date | 2013-01-23T18:28:53Z |

## Description

All accreditation fees are per year, unless otherwise indicated.

## Columns

```ls
| Included | Schema Type | Field Name           | Name                 | Data Type | Render Type |
| ======== | =========== | ==================== | ==================== | ========= | =========== |
| No       | time        | :updated_at          | updated_at           | meta_data | meta_data   |
| Yes      | series tag  | fee_type_name        | Fee Type Name        | text      | text        |
| Yes      | series tag  | certificate_name     | Certificate Name     | text      | text        |
| Yes      | series tag  | fee_application_name | Fee Application Name | text      | text        |
| Yes      | series tag  | fee_amount           | Fee Amount           | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:2cvx-33uz d:2013-01-23T10:22:26.000Z t:fee_amount=$105.00 t:fee_type_name=Certificate t:certificate_name="1. Blasting contractor certificate" t:fee_application_name="Original application" m:row_number.2cvx-33uz=1

series e:2cvx-33uz d:2013-01-23T10:22:26.000Z t:fee_amount=$50.00 t:fee_type_name=Certificate t:certificate_name="1. Blasting contractor certificate" t:fee_application_name="Renewal application" m:row_number.2cvx-33uz=2

series e:2cvx-33uz d:2013-01-23T10:22:26.000Z t:fee_amount=$625.00 t:fee_type_name=Certificate t:certificate_name="2. Certificate of approval (per application)" t:fee_application_name="Original application" m:row_number.2cvx-33uz=3
```

## Meta Commands

```ls
metric m:row_number.2cvx-33uz p:long l:"Row Number"

entity e:2cvx-33uz l:"FDNY Fire Department Fee" t:attribution="Fire Department of New York City (FDNY)" t:url=https://data.cityofnewyork.us/api/views/2cvx-33uz

property e:2cvx-33uz t:meta.view v:id=2cvx-33uz v:category="Public Safety" v:attributionLink="http://www.nyc.gov/html/fdny/pdf/firecode/2013/fire_code_ll26_2008_amended_ll37_39_41_64_2009_ll2_2013.pdf#page=622" v:averageRating=0 v:name="FDNY Fire Department Fee" v:attribution="Fire Department of New York City (FDNY)"

property e:2cvx-33uz t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:2cvx-33uz t:meta.view.tableauthor v:id=syvn-4vgv v:screenName="Sudhir Vasudeva" v:displayName="Sudhir Vasudeva"
```

## Top Records

```ls
| :updated_at | fee_type_name | certificate_name                             | fee_application_name                                                                                | fee_amount | 
| =========== | ============= | ============================================ | =================================================================================================== | ========== | 
| 1358936546  | Certificate   | 1. Blasting contractor certificate           | Original application                                                                                | $105.00    | 
| 1358936546  | Certificate   | 1. Blasting contractor certificate           | Renewal application                                                                                 | $50.00     | 
| 1358936546  | Certificate   | 2. Certificate of approval (per application) | Original application                                                                                | $625.00    | 
| 1358936546  | Certificate   | 2. Certificate of approval (per application) | Amended application                                                                                 | $625.00    | 
| 1358936546  | Certificate   | 2. Certificate of approval (per application) | Change of ownership                                                                                 | $625.00    | 
| 1358936546  | Certificate   | 2. Certificate of approval (per application) | Change in manufacturing process, chemical composition or design                                     | $625.00    | 
| 1358936546  | Certificate   | 2. Certificate of approval (per application) | Renewal application                                                                                 | $50.00     | 
| 1358936546  | Certificate   | 2. Certificate of approval (per application) | Change of identification, including change in name of article, model number or name of manufacturer | $210.00    | 
| 1358936546  | Certificate   | 3. Certificate of fitness                    | Original application (including written examination) (for 3 years)                                  | $25.00     | 
| 1358936546  | Certificate   | 3. Certificate of fitness                    | Practical (on-site) examination for fire safety director                                            | $445.00    | 
```