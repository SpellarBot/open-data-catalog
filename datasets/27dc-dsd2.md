# City of Albany Revenues: 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/city-of-albany-revenues-2013) |
| Metadata | [Link](https://data.ny.gov/api/views/27dc-dsd2) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/27dc-dsd2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/27dc-dsd2/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 27dc-dsd2 |
| Name | City of Albany Revenues: 2013 |
| Attribution | City of Albany |
| Category | Government & Finance |
| Tags | albany, revenues, budget, finance |
| Created | 2013-03-02T00:28:44Z |
| Publication Date | 2013-03-05T20:26:03Z |

## Description

In the accompanying data, each type of revenue is listed by category. The categories used are those promulgated by State Comptroller so that reporting among all localities is uniform.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type | Render Type |
| ======== | ============== | =========== | =========== | ========= | =========== |
| Yes      | series tag     | budget_code | Budget Code | text      | number      |
| Yes      | series tag     | source      | Source      | text      | text        |
| Yes      | series tag     | item        | Item        | text      | text        |
| Yes      | numeric metric | 2011_actual | 2011 Actual | money     | money       |
| Yes      | numeric metric | 2012_budget | 2012 Budget | money     | money       |
| Yes      | numeric metric | 2013_budget | 2013 Budget | money     | money       |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:27dc-dsd2 d:2013-01-01T00:00:00.000Z t:source="Local Sources" t:budget_code=1001 t:item="Realty Property Taxes" m:2012_budget=55148000 m:2013_budget=55148000 m:2011_actual=53706541

series e:27dc-dsd2 d:2013-01-01T00:00:00.000Z t:source="Local Sources" t:budget_code=1030 t:item="Special Assessments" m:2012_budget=0 m:2013_budget=0 m:2011_actual=0

series e:27dc-dsd2 d:2013-01-01T00:00:00.000Z t:source="Local Sources" t:budget_code=1081 t:item="Other Payments/PILOTS" m:2012_budget=26942000 m:2013_budget=26032000 m:2011_actual=18948989
```

## Meta Commands

```ls
metric m:2011_actual p:integer l:"2011 Actual" t:dataTypeName=money

metric m:2012_budget p:integer l:"2012 Budget" t:dataTypeName=money

metric m:2013_budget p:integer l:"2013 Budget" t:dataTypeName=money

entity e:27dc-dsd2 l:"City of Albany Revenues: 2013" t:attribution="City of Albany" t:url=https://data.ny.gov/api/views/27dc-dsd2

property e:27dc-dsd2 t:meta.view v:id=27dc-dsd2 v:category="Government & Finance" v:attributionLink=http://albanyny.gov/Government/MayorsOffice/Budget.aspx v:averageRating=0 v:name="City of Albany Revenues: 2013" v:attribution="City of Albany"

property e:27dc-dsd2 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:27dc-dsd2 t:meta.view.tableauthor v:id=mwxm-zess v:profileImageUrlMedium=/api/users/mwxm-zess/profile_images/THUMB v:profileImageUrlLarge=/api/users/mwxm-zess/profile_images/LARGE v:screenName="Lindsey Krough" v:profileImageUrlSmall=/api/users/mwxm-zess/profile_images/TINY v:roleName=administrator v:displayName="Lindsey Krough"

property e:27dc-dsd2 t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| budget_code | source        | item                          | 2011_actual | 2012_budget | 2013_budget | 
| =========== | ============= | ============================= | =========== | =========== | =========== | 
| 1001        | Local Sources | Realty Property Taxes         | 53706541    | 55148000    | 55148000    | 
| 1030        | Local Sources | Special Assessments           | 0           | 0           | 0           | 
| 1081        | Local Sources | Other Payments/PILOTS         | 18948989    | 26942000    | 26032000    | 
| 1090        | Local Sources | Interest/Penalties-Real Prop. | 265073      | 260000      | 260000      | 
| 1120        | Local Sources | Sales and Use Tax             | 29679431    | 28900000    | 32095000    | 
| 1130        | Local Sources | Utilities Gross Rec. Tax      | 1850470     | 2000000     | 1900000     | 
| 1134        | Local Sources | Privilege Tax-Coin Oper.      | 1785        | 4500        | 2500        | 
| 1134.01     | Local Sources | Coin Oper. Amusement Tax      | 1785        | 4500        | 2500        | 
| 1150        | Local Sources | OTB Receipts                  | 200730      | 220000      | 220000      | 
| 1170        | Local Sources | Franchises                    | 1328945     | 1300000     | 1320000     | 
```