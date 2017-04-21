# FY13 Payments Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fy13-payments-data-a90d4) |
| Metadata | [Link](https://data.maryland.gov/api/views/v46w-kaxh) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/v46w-kaxh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/v46w-kaxh/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | v46w-kaxh |
| Name | FY13 Payments Data |
| Attribution | Maryland Department of Budget and Management |
| Category | Budget |
| Tags | budget, spending, fiscal, vendors |
| Created | 2014-04-01T17:15:45Z |
| Publication Date | 2014-10-20T19:36:28Z |

## Description

Payments greater than $25,000 made by State Agencies to Vendors in FY13

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type | Render Type |
| ======== | ============== | =========== | =========== | ========= | =========== |
| Yes      | time           | year        | Year        | number    | text        |
| Yes      | series tag     | agency_name | Agency Name | text      | text        |
| Yes      | series tag     | vendor_name | Vendor Name | text      | text        |
| Yes      | series tag     | vendor_zip  | Vendor Zip  | text      | text        |
| Yes      | numeric metric | amount      | Amount      | money     | money       |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:v46w-kaxh d:2013-01-01T00:00:00.000Z t:vendor_zip=21201 t:agency_name="DEPARTMENT OF GENERAL SERVICES- CAPITAL" t:vendor_name="EVERYMAN THEATRE INC" m:amount=139350

series e:v46w-kaxh d:2013-01-01T00:00:00.000Z t:vendor_zip=21228 t:agency_name="DHMH-GENERAL ACCOUNTING" t:vendor_name="MENTOR MARYLAND INC" m:amount=113405.76

series e:v46w-kaxh d:2013-01-01T00:00:00.000Z t:vendor_zip=21215 t:agency_name="DHMH-GENERAL ACCOUNTING" t:vendor_name="BEST CARE" m:amount=32350.58
```

## Meta Commands

```ls
metric m:amount p:double l:Amount t:dataTypeName=money

entity e:v46w-kaxh l:"FY13 Payments Data" t:attribution="Maryland Department of Budget and Management" t:url=https://data.maryland.gov/api/views/v46w-kaxh

property e:v46w-kaxh t:meta.view v:id=v46w-kaxh v:category=Budget v:attributionLink=http://spending.dbm.maryland.gov v:averageRating=0 v:name="FY13 Payments Data" v:attribution="Maryland Department of Budget and Management"

property e:v46w-kaxh t:meta.view.license v:name="Public Domain"

property e:v46w-kaxh t:meta.view.owner v:id=kkuv-jqse v:screenName="Teri Greene" v:displayName="Teri Greene"

property e:v46w-kaxh t:meta.view.tableauthor v:id=kkuv-jqse v:screenName="Teri Greene" v:roleName=editor v:displayName="Teri Greene"
```

## Top Records

```ls
| year | agency_name                             | vendor_name                             | vendor_zip | amount    | 
| ==== | ======================================= | ======================================= | ========== | ========= | 
| 2013 | DEPARTMENT OF GENERAL SERVICES- CAPITAL | EVERYMAN THEATRE INC                    | 21201      | 139350.00 | 
| 2013 | DHMH-GENERAL ACCOUNTING                 | MENTOR MARYLAND INC                     | 21228      | 113405.76 | 
| 2013 | DHMH-GENERAL ACCOUNTING                 | BEST CARE                               | 21215      | 32350.58  | 
| 2013 | DHMH-GENERAL ACCOUNTING                 | OPEN MINDS                              | 17325      | 34970.00  | 
| 2013 | DEPARTMENT OF NATURAL RESOURCES         | QUEEN ANNE'S SOIL CONSERVATION DISTRICT | 21617      | 131.85    | 
| 2013 | MD DEPARTMENT OF AGRICULTURE            | BIOMERIEUX INC                          | 63150      | 2539.68   | 
| 2013 | MARYLAND STADIUM AUTHORITY              | LANGE ELECTRIC COMPANY INC              | 21230      | 3779.82   | 
| 2013 | MD DEPARTMENT OF AGRICULTURE            | OFFICE DEPOT                            | 45263      | 370.99    | 
| 2013 | DEPARTMENT OF NATURAL RESOURCES-CAPITAL | ST MARYS COUNTY COMMISSIONERS           | 20650      | 193460.72 | 
| 2013 | MARYLAND DEPT. OF AGING                 | UJA FEDERATION OF GREATER WASHINGTON    | 20852      | 225000.00 | 
```