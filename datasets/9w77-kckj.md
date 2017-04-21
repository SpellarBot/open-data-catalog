# Spending Disclosure - Fiscal Year 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/spending-disclosure-fiscal-year-2014-4aac4) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/9w77-kckj) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/9w77-kckj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/9w77-kckj/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | 9w77-kckj |
| Name | Spending Disclosure - Fiscal Year 2014 |
| Attribution | Montgomery County Department of Finance |
| Category | Finance/Tax/Property |
| Tags | financial, fiscal year 14, 2014, spending, $25, 000 or more |
| Created | 2013-08-29T20:58:50Z |
| Publication Date | 2014-07-21T18:08:04Z |

## Description

The purpose of this Spending Disclosure FY14 dataset is to allow the public to search and view summary information on payments made to recipients (referred to as suppliers) that received $25,000 or more in a fiscal year. Note that salary and benefit payments to employees, pension payments to retirees, and any information that is confidential under State or Federal law is excluded from disclosure.

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| Yes      | series tag     | supplier_name | Supplier Name | text      | text        |
| Yes      | series tag     | zip_code      | Zip Code      | text      | number      |
| Yes      | series tag     | department    | Department    | text      | text        |
| Yes      | numeric metric | amount        | Amount        | money     | money       |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:9w77-kckj d:2014-01-01T00:00:00.000Z t:zip_code=20910 t:department=Transportation t:supplier_name="1109 SPRING HOLDINGS LLC" m:amount=53812.08

series e:9w77-kckj d:2014-01-01T00:00:00.000Z t:zip_code=21401 t:department="Health and Human Services" t:supplier_name="1335 PICCARD LLC" m:amount=172.07

series e:9w77-kckj d:2014-01-01T00:00:00.000Z t:zip_code=22192 t:department="Non-Departmental Accounts" t:supplier_name="1335 PICCARD LLC" m:amount=699318.84
```

## Meta Commands

```ls
metric m:amount p:double l:Amount d:"Dollar amount paid to the supplier" t:dataTypeName=money

entity e:9w77-kckj l:"Spending Disclosure - Fiscal Year 2014" t:attribution="Montgomery County Department of Finance" t:url=https://data.montgomerycountymd.gov/api/views/9w77-kckj

property e:9w77-kckj t:meta.view v:id=9w77-kckj v:category=Finance/Tax/Property v:averageRating=0 v:name="Spending Disclosure - Fiscal Year 2014" v:attribution="Montgomery County Department of Finance"

property e:9w77-kckj t:meta.view.owner v:id=qzhb-tftn v:screenName="Kathy Luh" v:displayName="Kathy Luh"

property e:9w77-kckj t:meta.view.tableauthor v:id=qzhb-tftn v:screenName="Kathy Luh" v:roleName=administrator v:displayName="Kathy Luh"
```

## Top Records

```ls
| supplier_name                              | zip_code | department                         | amount    | 
| ========================================== | ======== | ================================== | ========= | 
| 1109 SPRING HOLDINGS LLC                   | 20910    | Transportation                     | 53812.08  | 
| 1335 PICCARD LLC                           | 21401    | Health and Human Services          | 172.07    | 
| 1335 PICCARD LLC                           | 22192    | Non-Departmental Accounts          | 699318.84 | 
| 1CALL4HELP LLC DBA PUSHBUTTONEMERGENCYHELP | 20878    | Health and Human Services          | 42793.27  | 
| 1ST CHOICE STAFFING LLC                    | 20910    | Board of Elections                 | 5802.11   | 
| 1ST CHOICE STAFFING LLC                    | 20910    | Community Use of Public Facilities | 5630.45   | 
| 1ST CHOICE STAFFING LLC                    | 20910    | Consumer Protection                | 30505.9   | 
| 1ST CHOICE STAFFING LLC                    | 20910    | Correction and Rehabilitation      | 2296.8    | 
| 1ST CHOICE STAFFING LLC                    | 20910    | County Executive                   | 35.7      | 
| 1ST CHOICE STAFFING LLC                    | 20910    | Environmental Protection           | 839.6     | 
```