# FY15 Spending Disclosure

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fy15-spending-disclosure-f6834) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/fk7w-kxjz) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/fk7w-kxjz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/fk7w-kxjz/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | fk7w-kxjz |
| Name | FY15 Spending Disclosure |
| Category | Finance/Tax/Property |
| Tags | financial, fiscal year 14, 2015, spending, $25, 000 or more |
| Created | 2014-11-07T12:43:21Z |
| Publication Date | 2014-11-07T12:59:36Z |

## Description

The purpose of this Spending Disclosure FY15 dataset is to allow the public to search and view summary information on payments made to recipients (referred to as suppliers) that received $25,000 or more in a fiscal year. Note that salary and benefit payments to employees, pension payments to retirees, and any information that is confidential under State or Federal law is excluded from disclosure.

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| No       | time           | :updated_at   | updated_at    | meta_data | meta_data   |
| Yes      | series tag     | supplier_name | Supplier Name | text      | text        |
| Yes      | series tag     | department    | Department    | text      | text        |
| Yes      | numeric metric | amount        | Amount        | number    | number      |
| Yes      | series tag     | zip           | Zip Code      | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:fk7w-kxjz d:2014-11-07T04:43:24.000Z t:zip=22192 t:department="Non-Departmental Accounts" t:supplier_name="1335 PICCARD LLC" m:amount=235391.64

series e:fk7w-kxjz d:2014-11-07T04:43:24.000Z t:zip=20814 t:department="Housing and Community Affairs" t:supplier_name="15498-15508 OLD COLUMBIA PIKE PARTNERSHIP" m:amount=65000

series e:fk7w-kxjz d:2014-11-07T04:43:24.000Z t:zip=20910 t:department="Board of Elections" t:supplier_name="1ST CHOICE STAFFING LLC" m:amount=363.24
```

## Meta Commands

```ls
metric m:amount p:double l:Amount d:"Dollar amount paid to the supplier" t:dataTypeName=number

entity e:fk7w-kxjz l:"FY15 Spending Disclosure" t:url=https://data.montgomerycountymd.gov/api/views/fk7w-kxjz

property e:fk7w-kxjz t:meta.view v:id=fk7w-kxjz v:category=Finance/Tax/Property v:averageRating=0 v:name="FY15 Spending Disclosure"

property e:fk7w-kxjz t:meta.view.owner v:id=6ide-p8eb v:screenName="Ted Bowser" v:displayName="Ted Bowser"

property e:fk7w-kxjz t:meta.view.tableauthor v:id=6ide-p8eb v:screenName="Ted Bowser" v:roleName=viewer v:displayName="Ted Bowser"
```

## Top Records

```ls
| :updated_at | supplier_name                             | department                                 | amount    | zip   | 
| =========== | ========================================= | ========================================== | ========= | ===== | 
| 1415335404  | 1335 PICCARD LLC                          | Non-Departmental Accounts                  | 235391.64 | 22192 | 
| 1415335404  | 15498-15508 OLD COLUMBIA PIKE PARTNERSHIP | Housing and Community Affairs              | 65000     | 20814 | 
| 1415335404  | 1ST CHOICE STAFFING LLC                   | Board of Elections                         | 363.24    | 20910 | 
| 1415335404  | 1ST CHOICE STAFFING LLC                   | Community Use of Public Facilities         | 12749.76  | 20910 | 
| 1415335404  | 1ST CHOICE STAFFING LLC                   | Consumer Protection                        | 7897.26   | 20910 | 
| 1415335404  | 1ST CHOICE STAFFING LLC                   | County Executive                           | 1352.06   | 20910 | 
| 1415335404  | 1ST CHOICE STAFFING LLC                   | Emergency Management and Homeland Security | 3229.36   | 20910 | 
| 1415335404  | 1ST CHOICE STAFFING LLC                   | Environmental Protection                   | 5782.3    | 20910 | 
| 1415335404  | 1ST CHOICE STAFFING LLC                   | General Services                           | 20911.72  | 20910 | 
| 1415335404  | 1ST CHOICE STAFFING LLC                   | Health and Human Services                  | 103175.97 | 20910 | 
```