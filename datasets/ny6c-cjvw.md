# Suffolk County Budget Revenue: 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/suffolk-county-budget-revenue-2013) |
| Metadata | [Link](https://data.ny.gov/api/views/ny6c-cjvw) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/ny6c-cjvw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/ny6c-cjvw/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | ny6c-cjvw |
| Name | Suffolk County Budget Revenue: 2013 |
| Attribution | Suffolk County ? County Executive |
| Category | Government & Finance |
| Tags | suffolk, operating budget, revenue |
| Created | 2013-03-04T21:41:31Z |
| Publication Date | 2013-03-04T21:57:38Z |

## Description

The funds that the County receives as income, including tax payments, services fees, receipts from other governments, fines, forfeitures, grants and interest income.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| Yes      | numeric metric | bfy              | BFY              | number    | number      |
| Yes      | series tag     | fund_cd          | FUND_CD          | text      | text        |
| Yes      | series tag     | dept_cd          | DEPT_CD          | text      | text        |
| Yes      | series tag     | unit_cd          | UNIT_CD          | text      | text        |
| Yes      | series tag     | rsrc_cd          | RSRC_CD          | text      | text        |
| Yes      | series tag     | rsrc_nm          | RSRC_NM          | text      | text        |
| Yes      | series tag     | mand_cd          | MAND_CD          | text      | text        |
| Yes      | series tag     | grant            | Grant            | text      | text        |
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
series e:ny6c-cjvw d:2013-01-01T00:00:00.000Z t:fund_cd=001 t:dept_cd=AAC t:unit_cd=1315 t:rsrc_cd=2451 t:rsrc_nm="Atm Commissions" m:bfy=2013 m:2013_adopted=9925 m:2013_recommended=9925 m:2012_estimated=9925 m:2012_adopted=13325 m:2012_modified=13325 m:2013_requested=9925 m:2011_actuals=8591.4 m:2010_actuals=9792.3

series e:ny6c-cjvw d:2013-01-01T00:00:00.000Z t:fund_cd=001 t:dept_cd=AAC t:unit_cd=1315 t:rsrc_cd=2702 t:rsrc_nm="Audit Recoveries" m:bfy=2013 m:2013_adopted=750000 m:2013_recommended=750000 m:2012_estimated=590000 m:2012_adopted=800000 m:2012_modified=800000 m:2013_requested=800000 m:2011_actuals=432012.67 m:2010_actuals=756546.15

series e:ny6c-cjvw d:2013-01-01T00:00:00.000Z t:mand_cd=M t:fund_cd=001 t:dept_cd=AAC t:unit_cd=1315 t:rsrc_cd=2703 t:rsrc_nm="Mortgage Interest & Principal" m:bfy=2013 m:2013_adopted=210036 m:2013_recommended=210036 m:2012_estimated=210036 m:2012_adopted=340000 m:2012_modified=340000 m:2013_requested=210036 m:2011_actuals=262029.89 m:2010_actuals=316257.18
```

## Meta Commands

```ls
metric m:bfy p:integer l:BFY t:dataTypeName=number

metric m:2010_actuals p:double l:"2010 Actuals" t:dataTypeName=money

metric m:2011_actuals p:double l:"2011 Actuals" t:dataTypeName=money

metric m:2012_modified p:double l:"2012 Modified" t:dataTypeName=money

metric m:2012_adopted p:double l:"2012 Adopted" t:dataTypeName=money

metric m:2012_estimated p:double l:"2012 Estimated" t:dataTypeName=money

metric m:2013_requested p:double l:"2013 Requested" t:dataTypeName=money

metric m:2013_recommended p:double l:"2013 Recommended" t:dataTypeName=money

metric m:2013_adopted p:double l:"2013 Adopted" t:dataTypeName=money

entity e:ny6c-cjvw l:"Suffolk County Budget Revenue: 2013" t:attribution="Suffolk County ? County Executive" t:url=https://data.ny.gov/api/views/ny6c-cjvw

property e:ny6c-cjvw t:meta.view v:id=ny6c-cjvw v:category="Government & Finance" v:averageRating=0 v:name="Suffolk County Budget Revenue: 2013" v:attribution="Suffolk County ? County Executive"

property e:ny6c-cjvw t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:ny6c-cjvw t:meta.view.tableauthor v:id=mwxm-zess v:profileImageUrlMedium=/api/users/mwxm-zess/profile_images/THUMB v:profileImageUrlLarge=/api/users/mwxm-zess/profile_images/LARGE v:screenName="Lindsey Krough" v:profileImageUrlSmall=/api/users/mwxm-zess/profile_images/TINY v:roleName=administrator v:displayName="Lindsey Krough"

property e:ny6c-cjvw t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| bfy  | fund_cd | dept_cd | unit_cd | rsrc_cd | rsrc_nm                        | mand_cd | grant | 2010_actuals | 2011_actuals | 2012_modified | 2012_adopted | 2012_estimated | 2013_requested | 2013_recommended | 2013_adopted | 
| ==== | ======= | ======= | ======= | ======= | ============================== | ======= | ===== | ============ | ============ | ============= | ============ | ============== | ============== | ================ | ============ | 
| 2013 | 001     | AAC     | 1315    | 2451    | Atm Commissions                |         |       | 9792.30      | 8591.40      | 13325.00      | 13325.00     | 9925.00        | 9925.00        | 9925.00          | 9925.00      | 
| 2013 | 001     | AAC     | 1315    | 2702    | Audit Recoveries               |         |       | 756546.15    | 432012.67    | 800000.00     | 800000.00    | 590000.00      | 800000.00      | 750000.00        | 750000.00    | 
| 2013 | 001     | AAC     | 1315    | 2703    | Mortgage Interest & Principal  | M       |       | 316257.18    | 262029.89    | 340000.00     | 340000.00    | 210036.00      | 210036.00      | 210036.00        | 210036.00    | 
| 2013 | 001     | AAC     | 1315    | 2770    | Other Unclassified Revenues    |         |       | 0.00         | 0.00         | 200.00        | 200.00       | 0.00           | 0.00           | 0.00             | 6000.00      | 
| 2013 | 001     | BOE     | 1450    | 2403    | Department Interest & Earnings | S       |       | 0.00         | 35.00        | 0.00          | 0.00         | 0.00           | 0.00           | 0.00             | 0.00         | 
| 2013 | 001     | BOE     | 1450    | 2403    | Department Interest & Earnings |         |       | 0.00         | 28.00        | 50.00         | 50.00        | 63.00          | 63.00          | 63.00            | 63.00        | 
| 2013 | 001     | BOE     | 1450    | 2416    | Rental Equipment - Other Govt  |         |       | 85123.34     | 94527.93     | 100000.00     | 100000.00    | 118111.00      | 94528.00       | 100000.00        | 100000.00    | 
| 2013 | 001     | BOE     | 1450    | 2655    | Minor Sales - Other            |         |       | 30132.95     | 25406.01     | 47000.00      | 47000.00     | 25406.00       | 25406.00       | 25406.00         | 25406.00     | 
| 2013 | 001     | BOE     | 1450    | 2701    | Refunds Of Prior Year Expenses |         |       | 0.00         | 888.71       | 100.00        | 100.00       | 100.00         | 100.00         | 100.00           | 100.00       | 
| 2013 | 001     | BOE     | 1455    | 3070    | STATE AID: BOE - HAVA          |         |       | 510031.15    | 39504.61     | 0.00          | 0.00         | 0.00           | 0.00           | 0.00             | 0.00         | 
```