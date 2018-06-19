# Suffolk County Budget Expenditures: 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/suffolk-county-budget-expenditures-2013) |
| Metadata | [Link](https://data.ny.gov/api/views/62eq-hqts) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/62eq-hqts/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/62eq-hqts/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 62eq-hqts |
| Name | Suffolk County Budget Expenditures: 2013 |
| Attribution | Suffolk County ? County Executive |
| Category | Government & Finance |
| Tags | suffolk, operating budget, expenditures |
| Created | 2013-03-04T21:37:46Z |
| Publication Date | 2013-03-04T21:59:59Z |

## Description

The Operating Budget details the expenditures for the County's day-today operation. The Operating Budget contains the perating expenses for all County departments and agencies for the fiscal year. These expenses include the costs for personnel, supplies, equipment, and maintenance and repair of equipment and buildings.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| Yes      | numeric metric | bfy              | BFY              | number    | number      |
| Yes      | series tag     | grant            | Grant            | text      | text        |
| Yes      | series tag     | fund_cd          | FUND_CD          | text      | text        |
| Yes      | series tag     | dept_cd          | DEPT_CD          | text      | text        |
| Yes      | series tag     | dept_nm          | DEPT_NM          | text      | text        |
| Yes      | series tag     | unit_cd          | UNIT_CD          | text      | text        |
| Yes      | series tag     | unit_nm          | UNIT_NM          | text      | text        |
| Yes      | numeric metric | obj_cd           | OBJ_CD           | number    | number      |
| Yes      | series tag     | obj_nm           | OBJ_NM           | text      | text        |
| Yes      | series tag     | actv_cd          | ACTV_CD          | text      | text        |
| Yes      | series tag     | actv_nm          | ACTV_NM          | text      | text        |
| Yes      | series tag     | appr_cd          | APPR_CD          | text      | text        |
| Yes      | numeric metric | 2010_actuals     | 2010 Actuals     | money     | money       |
| Yes      | numeric metric | 2011_actuals     | 2011 Actuals     | money     | money       |
| Yes      | numeric metric | 2012_modified    | 2012 Modified    | money     | money       |
| Yes      | numeric metric | 2012_adopted     | 2012 Adopted     | money     | money       |
| Yes      | numeric metric | 2012_estimated   | 2012 Estimated   | money     | money       |
| Yes      | numeric metric | 2013_requested   | 2013 Requested   | money     | money       |
| Yes      | numeric metric | 2013_recommended | 2013 Recommended | money     | money       |
| Yes      | numeric metric | 2013_adopted     | 2013 Adopted     | money     | money       |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:62eq-hqts d:2013-01-01T00:00:00.000Z t:actv_cd=0000 t:fund_cd=001 t:dept_cd=AAC t:dept_nm="Audit & Control" t:unit_cd=1315 t:obj_nm="Terminal Vacation Pay" t:appr_cd=DE t:actv_nm="Non-Contract Agency" t:unit_nm="Audit & Control" m:bfy=2013 m:2013_adopted=0 m:2013_recommended=0 m:2012_estimated=13905 m:2012_modified=13905 m:2012_adopted=0 m:obj_cd=1020 m:2013_requested=0 m:2011_actuals=0 m:2010_actuals=283245.35

series e:62eq-hqts d:2013-01-01T00:00:00.000Z t:actv_cd=0000 t:fund_cd=001 t:dept_cd=AAC t:dept_nm="Audit & Control" t:unit_cd=1315 t:obj_nm="Longevity Pay" t:appr_cd=DE t:actv_nm="Non-Contract Agency" t:unit_nm="Audit & Control" m:bfy=2013 m:2013_adopted=80650 m:2013_recommended=80650 m:2012_estimated=77200 m:2012_modified=77200 m:2012_adopted=77200 m:obj_cd=1060 m:2013_requested=80650 m:2011_actuals=66275 m:2010_actuals=88450

series e:62eq-hqts d:2013-01-01T00:00:00.000Z t:actv_cd=0000 t:fund_cd=001 t:dept_cd=AAC t:dept_nm="Audit & Control" t:unit_cd=1315 t:obj_nm="Retro & Vacation Pay" t:appr_cd=DE t:actv_nm="Non-Contract Agency" t:unit_nm="Audit & Control" m:bfy=2013 m:2013_adopted=0 m:2013_recommended=0 m:2012_estimated=0 m:2012_modified=0 m:2012_adopted=0 m:obj_cd=1080 m:2013_requested=0 m:2011_actuals=39672 m:2010_actuals=7046
```

## Meta Commands

```ls
metric m:bfy p:integer l:BFY t:dataTypeName=number

metric m:obj_cd p:integer l:OBJ_CD t:dataTypeName=number

metric m:2010_actuals p:double l:"2010 Actuals" t:dataTypeName=money

metric m:2011_actuals p:double l:"2011 Actuals" t:dataTypeName=money

metric m:2012_modified p:double l:"2012 Modified" t:dataTypeName=money

metric m:2012_adopted p:double l:"2012 Adopted" t:dataTypeName=money

metric m:2012_estimated p:double l:"2012 Estimated" t:dataTypeName=money

metric m:2013_requested p:double l:"2013 Requested" t:dataTypeName=money

metric m:2013_recommended p:double l:"2013 Recommended" t:dataTypeName=money

metric m:2013_adopted p:double l:"2013 Adopted" t:dataTypeName=money

entity e:62eq-hqts l:"Suffolk County Budget Expenditures: 2013" t:attribution="Suffolk County ? County Executive" t:url=https://data.ny.gov/api/views/62eq-hqts

property e:62eq-hqts t:meta.view v:id=62eq-hqts v:category="Government & Finance" v:averageRating=0 v:name="Suffolk County Budget Expenditures: 2013" v:attribution="Suffolk County ? County Executive"

property e:62eq-hqts t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:62eq-hqts t:meta.view.tableauthor v:id=mwxm-zess v:profileImageUrlMedium=/api/users/mwxm-zess/profile_images/THUMB v:profileImageUrlLarge=/api/users/mwxm-zess/profile_images/LARGE v:screenName="Lindsey Krough" v:profileImageUrlSmall=/api/users/mwxm-zess/profile_images/TINY v:roleName=administrator v:displayName="Lindsey Krough"

property e:62eq-hqts t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| bfy  | grant | fund_cd | dept_cd | dept_nm         | unit_cd | unit_nm         | obj_cd | obj_nm                         | actv_cd | actv_nm             | appr_cd | 2010_actuals | 2011_actuals | 2012_modified | 2012_adopted | 2012_estimated | 2013_requested | 2013_recommended | 2013_adopted | 
| ==== | ===== | ======= | ======= | =============== | ======= | =============== | ====== | ============================== | ======= | =================== | ======= | ============ | ============ | ============= | ============ | ============== | ============== | ================ | ============ | 
| 2013 |       | 001     | AAC     | Audit & Control | 1315    | Audit & Control | 1020   | Terminal Vacation Pay          | 0000    | Non-Contract Agency | DE      | 283245.35    | 0.00         | 13905.00      | 0.00         | 13905.00       | 0.00           | 0.00             | 0.00         | 
| 2013 |       | 001     | AAC     | Audit & Control | 1315    | Audit & Control | 1060   | Longevity Pay                  | 0000    | Non-Contract Agency | DE      | 88450.00     | 66275.00     | 77200.00      | 77200.00     | 77200.00       | 80650.00       | 80650.00         | 80650.00     | 
| 2013 |       | 001     | AAC     | Audit & Control | 1315    | Audit & Control | 1080   | Retro & Vacation Pay           | 0000    | Non-Contract Agency | DE      | 7046.00      | 39672.00     | 0.00          | 0.00         | 0.00           | 0.00           | 0.00             | 0.00         | 
| 2013 |       | 001     | AAC     | Audit & Control | 1315    | Audit & Control | 1100   | Permanent Salaries             | 0000    | Non-Contract Agency | DE      | 5273334.18   | 4809743.75   | 4891570.00    | 4719166.66   | 5021447.00     | 5018247.00     | 5021016.00       | 5021016.00   | 
| 2013 |       | 001     | AAC     | Audit & Control | 1315    | Audit & Control | 1120   | Overtime Salaries              | 0000    | Non-Contract Agency | DE      | 6029.88      | 14747.83     | 10000.00      | 10000.00     | 10000.00       | 10000.00       | 10000.00         | 10000.00     | 
| 2013 |       | 001     | AAC     | Audit & Control | 1315    | Audit & Control | 1130   | Temporary Salaries - No Fringe | 0000    | Non-Contract Agency | DE      | 6906.01      | 9478.37      | 10000.00      | 10000.00     | 10000.00       | 10000.00       | 10000.00         | 10000.00     | 
| 2013 |       | 001     | AAC     | Audit & Control | 1315    | Audit & Control | 1380   | DEFERRED PAY                   | 0000    | Non-Contract Agency | DE      | 50681.00     | 0.00         | 0.00          | 0.00         | -4220.00       | 0.00           | 0.00             | 0.00         | 
| 2013 |       | 001     | AAC     | Audit & Control | 1315    | Audit & Control | 1620   | OT - Straight Time             | 0000    | Non-Contract Agency | DE      | 0.00         | 0.00         | 268.00        | 0.00         | 268.00         | 0.00           | 0.00             | 0.00         | 
| 2013 |       | 001     | AAC     | Audit & Control | 1315    | Audit & Control | 2010   | Furniture & Furnishings        | 0000    | Non-Contract Agency | DE      | 819.12       | 0.00         | 0.00          | 0.00         | 0.00           | 1100.00        | 0.00             | 0.00         | 
| 2013 |       | 001     | AAC     | Audit & Control | 1315    | Audit & Control | 2020   | Office Machines                | 0000    | Non-Contract Agency | DE      | 1951.02      | 990.27       | 19000.00      | 19000.00     | 6500.00        | 24110.00       | 22000.00         | 22000.00     | 
```