# State of Iowa Executive Branch Full Time Equivalents by Month and Department

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-of-iowa-full-time-equivalents-by-month-and-department) |
| Metadata | [Link](https://data.iowa.gov/api/views/rejw-2ccf) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/rejw-2ccf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/rejw-2ccf/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | rejw-2ccf |
| Name | State of Iowa Executive Branch Full Time Equivalents by Month and Department |
| Attribution | Iowa Department of Management |
| Category | Government |
| Tags | fte, full time equivalents, state employees, executive branch, community based corrections |
| Created | 2015-04-23T19:15:47Z |
| Publication Date | 2015-04-23T19:27:50Z |

## Description

The dataset provides information on total full-time equivalents (FTE) for the State of Iowa - Executive Branch (including community based corrections), and those supported by the general fund, federal funds and other state funds starting with the pay period ending 12/23/2010. Counts are shown for the last pay period ending in the month. Two week long pay periods end every other Thursday.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type     | Render Type   |
| ======== | ============== | ================== | ================== | ============= | ============= |
| Yes      | series tag     | function           | Function           | text          | text          |
| Yes      | series tag     | special_department | Special Department | text          | text          |
| Yes      | series tag     | department_number  | Department Number  | text          | text          |
| Yes      | series tag     | department         | Department         | text          | text          |
| Yes      | numeric metric | general_fund_fte   | General Fund FTE   | number        | number        |
| Yes      | numeric metric | federal_funds_fte  | Federal Funds FTE  | number        | number        |
| Yes      | numeric metric | other_funds_fte    | Other Funds FTE    | number        | number        |
| Yes      | numeric metric | total_fte          | Total FTE          | number        | number        |
| Yes      | time           | count_date         | Count Date         | calendar_date | calendar_date |
```

## Time Field

```ls
Value = count_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:rejw-2ccf d:2015-03-26T00:00:00.000Z t:department="Consumer Advocate" t:department_number=114 t:special_department="Attorney General" t:function="Justice System" m:federal_funds_fte=0 m:general_fund_fte=0 m:other_funds_fte=17 m:total_fte=17

series e:rejw-2ccf d:2015-03-26T00:00:00.000Z t:department="Campaign Finance Disclosure Commission" t:department_number=140 t:special_department="Iowa Ethics & Campaign Disclosure Board" t:function="Administration and Regulation" m:federal_funds_fte=0 m:general_fund_fte=6 m:other_funds_fte=0 m:total_fte=6

series e:rejw-2ccf d:2015-03-26T00:00:00.000Z t:department="Civil Rights Commission" t:department_number=167 t:special_department="Civil Rights Commission" t:function="Justice System" m:federal_funds_fte=18 m:general_fund_fte=11 m:other_funds_fte=0 m:total_fte=29
```

## Meta Commands

```ls
metric m:general_fund_fte p:float l:"General Fund FTE" d:"FTE supported by the general fund" t:dataTypeName=number

metric m:federal_funds_fte p:float l:"Federal Funds FTE" d:"FTE supported by federal funding" t:dataTypeName=number

metric m:other_funds_fte p:float l:"Other Funds FTE" d:"FTE suppored by other state funds (e.g. road use, etc.)" t:dataTypeName=number

metric m:total_fte p:float l:"Total FTE" d:"Total FTE for the agency" t:dataTypeName=number

entity e:rejw-2ccf l:"State of Iowa Executive Branch Full Time Equivalents by Month and Department" t:attribution="Iowa Department of Management" t:url=https://data.iowa.gov/api/views/rejw-2ccf

property e:rejw-2ccf t:meta.view v:id=rejw-2ccf v:category=Government v:averageRating=0 v:name="State of Iowa Executive Branch Full Time Equivalents by Month and Department" v:attribution="Iowa Department of Management"

property e:rejw-2ccf t:meta.view.license v:name="Public Domain"

property e:rejw-2ccf t:meta.view.owner v:id=bnfb-vany v:profileImageUrlMedium=/api/users/bnfb-vany/profile_images/THUMB v:profileImageUrlLarge=/api/users/bnfb-vany/profile_images/LARGE v:screenName="IDOM, State Budget" v:profileImageUrlSmall=/api/users/bnfb-vany/profile_images/TINY v:displayName="IDOM, State Budget"

property e:rejw-2ccf t:meta.view.tableauthor v:id=bnfb-vany v:profileImageUrlMedium=/api/users/bnfb-vany/profile_images/THUMB v:profileImageUrlLarge=/api/users/bnfb-vany/profile_images/LARGE v:screenName="IDOM, State Budget" v:profileImageUrlSmall=/api/users/bnfb-vany/profile_images/TINY v:roleName=editor v:displayName="IDOM, State Budget"
```

## Top Records

```ls
| function                      | special_department                       | department_number | department                               | general_fund_fte | federal_funds_fte | other_funds_fte | total_fte | count_date          | 
| ============================= | ======================================== | ================= | ======================================== | ================ | ================= | =============== | ========= | =================== | 
| Justice System                | Attorney General                         | 114               | Consumer Advocate                        | 0.00             | 0.00              | 17.00           | 17.00     | 2015-03-26T00:00:00 | 
| Administration and Regulation | Iowa Ethics & Campaign Disclosure Board  | 140               | Campaign Finance Disclosure Commission   | 6.00             | 0.00              | 0.00            | 6.00      | 2015-03-26T00:00:00 | 
| Justice System                | Civil Rights Commission                  | 167               | Civil Rights Commission                  | 11.00            | 18.00             | 0.00            | 29.00     | 2015-03-26T00:00:00 | 
| Administration and Regulation | Chief Information Officer, Office of the | 185               | Chief Information Officer, Office of the | 0.00             | 0.00              | 114.25          | 114.25    | 2015-03-26T00:00:00 | 
| Administration and Regulation | Commerce, Department of                  | 213               | Banking Division                         | 0.00             | 0.00              | 68.00           | 68.00     | 2015-03-26T00:00:00 | 
| Administration and Regulation | Commerce, Department of                  | 214               | Credit Union Division                    | 0.00             | 0.00              | 13.00           | 13.00     | 2015-03-26T00:00:00 | 
| Administration and Regulation | Commerce, Department of                  | 216               | Insurance Division                       | 0.00             | 7.50              | 86.00           | 93.50     | 2015-03-26T00:00:00 | 
| Administration and Regulation | Commerce, Department of                  | 217               | Professional Licensing & Regulation      | 8.30             | 0.00              | 1.70            | 10.00     | 2015-03-26T00:00:00 | 
| Administration and Regulation | Commerce, Department of                  | 219               | Utilities Division                       | 0.00             | 0.00              | 62.50           | 62.50     | 2015-03-26T00:00:00 | 
| Justice System                | Corrections, Department of               | 221               | Community Based Corrections District 1   | 168.13           | 0.00              | 20.00           | 188.13    | 2015-03-26T00:00:00 | 
```