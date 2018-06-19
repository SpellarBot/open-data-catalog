# Spending Disclosure - Fiscal Year 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/spending-disclosure-fiscal-year-2012-c8308) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/ask7-28ii) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/ask7-28ii/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/ask7-28ii/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | ask7-28ii |
| Name | Spending Disclosure - Fiscal Year 2012 |
| Attribution | Montgomery County Department of Finance |
| Category | Finance/Tax/Property |
| Tags | financial, fiscal year 12, 2012, spending, $25, 000 or more |
| Created | 2013-08-30T20:02:00Z |
| Publication Date | 2013-09-03T19:45:08Z |

## Description

The purpose of this Spending Disclosure Fiscal Year 12 dataset is to allow the public to search and view summary information on payments made to recipients (referred to as suppliers) that received $25,000 or more in a fiscal year. Note that salary and benefit payments to employees, pension payments to retirees, and any information that is confidential under State or Federal law is excluded from disclosure.

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| Yes      | series tag     | supplier_name | Supplier Name | text      | text        |
| Yes      | series tag     | zip_code      | Zip Code      | text      | text        |
| Yes      | series tag     | department    | Department    | text      | text        |
| Yes      | numeric metric | amount        | Amount        | money     | money       |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ask7-28ii d:2012-01-01T00:00:00.000Z t:zip_code=20817 t:department=Finance t:supplier_name="EEPEX INC" m:amount=9315

series e:ask7-28ii d:2012-01-01T00:00:00.000Z t:zip_code=20850 t:department=Transportation t:supplier_name="G&C GULF INC" m:amount=190

series e:ask7-28ii d:2012-01-01T00:00:00.000Z t:zip_code=21279 t:department="Non-Departmental Accounts" t:supplier_name="1109 SPRING HOLDINGS LLC" m:amount=40241.5
```

## Meta Commands

```ls
metric m:amount p:double l:Amount d:"Dollar amount paid to the supplier." t:dataTypeName=money

entity e:ask7-28ii l:"Spending Disclosure - Fiscal Year 2012" t:attribution="Montgomery County Department of Finance" t:url=https://data.montgomerycountymd.gov/api/views/ask7-28ii

property e:ask7-28ii t:meta.view v:id=ask7-28ii v:category=Finance/Tax/Property v:averageRating=0 v:name="Spending Disclosure - Fiscal Year 2012" v:attribution="Montgomery County Department of Finance"

property e:ask7-28ii t:meta.view.owner v:id=qzhb-tftn v:screenName="Kathy Luh" v:displayName="Kathy Luh"

property e:ask7-28ii t:meta.view.tableauthor v:id=qzhb-tftn v:screenName="Kathy Luh" v:roleName=administrator v:displayName="Kathy Luh"
```

## Top Records

```ls
| supplier_name                             | zip_code | department                    | amount    | 
| ========================================= | ======== | ============================= | ========= | 
| EEPEX INC                                 | 20817    | Finance                       | 9315      | 
| G&C GULF INC                              | 20850    | Transportation                | 190       | 
| 1109 SPRING HOLDINGS LLC                  | 21279    | Non-Departmental Accounts     | 40241.5   | 
| 1109 SPRING HOLDINGS LLC                  | 21279    | Transportation                | 26122.38  | 
| 1335 PICCARD LLC                          | 22192    | Non-Departmental Accounts     | 661341.49 | 
| 15498-15508 OLD COLUMBIA PIKE PARTNERSHIP | 20814    | Housing and Community Affairs | 200000    | 
| 1ST CHOICE STAFFING AGENCY                | 20910    | Board of Elections            | 9413.89   | 
| 1ST CHOICE STAFFING AGENCY                | 20910    | Non-Departmental Accounts     | 14647.5   | 
| 1ST CHOICE STAFFING AGENCY                | 20910    | Transportation                | 1669.26   | 
| 1ST CHOICE STAFFING LLC                   | 20910    | Correction and Rehabilitation | 6395.6    | 
```