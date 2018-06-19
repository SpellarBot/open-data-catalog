# Sample DataSet

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/sample-dataset-9d5f3) |
| Metadata | [Link](https://data.hawaii.gov/api/views/usep-nua7) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/usep-nua7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/usep-nua7/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | usep-nua7 |
| Name | Sample DataSet |
| Created | 2015-01-08T20:21:19Z |
| Publication Date | 2015-01-08T20:35:34Z |

## Description

For testing purposes only

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| Yes      | time           | fiscal_year      | FISCAL YEAR      | number    | text        |
| Yes      | series tag     | service          | SERVICE          | text      | text        |
| Yes      | series tag     | department       | DEPARTMENT       | text      | text        |
| Yes      | series tag     | program          | PROGRAM          | text      | text        |
| Yes      | series tag     | expense_category | EXPENSE CATEGORY | text      | text        |
| Yes      | series tag     | received_amount  | RECEIVED AMOUNT  | text      | text        |
| Yes      | numeric metric | approved_amount  | APPROVED AMOUNT  | money     | money       |
| Yes      | series tag     | fund             | FUND             | text      | text        |
| Yes      | series tag     | fund_type        | FUND TYPE        | text      | text        |
| Yes      | series tag     | description      | DESCRIPTION      | text      | text        |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:usep-nua7 d:2015-01-01T00:00:00.000Z t:description=VEHICLE t:program="AGRICULTURAL LOAN DIVISION" t:department="FINANCIAL ASSISTANCE FOR AGRICULTURE" t:service="FINANCIAL ASSISTANCE FOR AGRICULTURE" t:expense_category="OTHER CURRENT EXPENSES" t:fund="SPECIAL FUND" m:approved_amount=0

series e:usep-nua7 d:2015-01-01T00:00:00.000Z t:description=VEHICLES t:program="PLANT QUARANTINE BRANCH" t:department="PLANT PEST AND DISEASE CONTROL" t:service="PLANT PEST AND DISEASE CONTROL" t:expense_category="OTHER CURRENT EXPENSES" t:fund="GENERAL FUND" m:approved_amount=0

series e:usep-nua7 d:2015-01-01T00:00:00.000Z t:description=VEHICLE t:program="PLANT QUARANTINE BRANCH" t:department="PLANT PEST AND DISEASE CONTROL" t:service="PLANT PEST AND DISEASE CONTROL" t:expense_category="OTHER CURRENT EXPENSES" t:fund="GENERAL FUND" m:approved_amount=0
```

## Meta Commands

```ls
metric m:approved_amount p:double l:"APPROVED AMOUNT" t:dataTypeName=money

entity e:usep-nua7 l:"Sample DataSet" t:url=https://data.hawaii.gov/api/views/usep-nua7

property e:usep-nua7 t:meta.view v:id=usep-nua7 v:averageRating=0 v:name="Sample DataSet"

property e:usep-nua7 t:meta.view.owner v:id=nczc-usar v:screenName="Darryl Lajola" v:displayName="Darryl Lajola"

property e:usep-nua7 t:meta.view.tableauthor v:id=nczc-usar v:screenName="Darryl Lajola" v:roleName=publisher v:displayName="Darryl Lajola"
```

## Top Records

```ls
| fiscal_year | service                              | department                           | program                                | expense_category       | received_amount | approved_amount | fund         | fund_type | description                | 
| =========== | ==================================== | ==================================== | ====================================== | ====================== | =============== | =============== | ============ | ========= | ========================== | 
| 2015        | FINANCIAL ASSISTANCE FOR AGRICULTURE | FINANCIAL ASSISTANCE FOR AGRICULTURE | AGRICULTURAL LOAN DIVISION             | OTHER CURRENT EXPENSES |                 | 0.00            | SPECIAL FUND |           | VEHICLE                    | 
| 2015        | PLANT PEST AND DISEASE CONTROL       | PLANT PEST AND DISEASE CONTROL       | PLANT QUARANTINE BRANCH                | OTHER CURRENT EXPENSES |                 | 0.00            | GENERAL FUND |           | VEHICLES                   | 
| 2015        | PLANT PEST AND DISEASE CONTROL       | PLANT PEST AND DISEASE CONTROL       | PLANT QUARANTINE BRANCH                | OTHER CURRENT EXPENSES |                 | 0.00            | GENERAL FUND |           | VEHICLE                    | 
| 2015        | PLANT PEST AND DISEASE CONTROL       | PLANT PEST AND DISEASE CONTROL       | PLANT QUARANTINE BRANCH                | OTHER CURRENT EXPENSES |                 | 0.00            | GENERAL FUND |           | VEHICLE                    | 
| 2015        | PLANT PEST AND DISEASE CONTROL       | PLANT PEST AND DISEASE CONTROL       | PLANT QUARANTINE BRANCH                | OTHER CURRENT EXPENSES |                 | 0.00            | GENERAL FUND |           | SPORT UTILITY VEHICLE, 4WD | 
| 2015        | PLANT PEST AND DISEASE CONTROL       | PLANT PEST AND DISEASE CONTROL       | PLANT QUARANTINE BRANCH                | OTHER CURRENT EXPENSES |                 | 0.00            | GENERAL FUND |           | SPORT UTILITY VEHICLE, 4WD | 
| 2015        | PLANT PEST AND DISEASE CONTROL       | PLANT PEST AND DISEASE CONTROL       | PLANT QUARANTINE BRANCH                | OTHER CURRENT EXPENSES |                 | 0.00            | GENERAL FUND |           | SPORT UTILITY VEHICLE, 4WD | 
| 2015        | PLANT PEST AND DISEASE CONTROL       | PLANT PEST AND DISEASE CONTROL       | PLANT QUARANTINE BRANCH                | OTHER CURRENT EXPENSES |                 | 0.00            | GENERAL FUND |           | VAN                        | 
| 2015        | PLANT PEST AND DISEASE CONTROL       | PLANT PEST AND DISEASE CONTROL       | PLANT QUARANTINE BRANCH                | OTHER CURRENT EXPENSES |                 | 0.00            | GENERAL FUND |           | VAN                        | 
| 2015        | PLANT PEST AND DISEASE CONTROL       | PLANT PEST AND DISEASE CONTROL       | PLANT PEST CONTROL BRANCH - BIOCONTROL | OTHER CURRENT EXPENSES |                 | 0.00            | GENERAL FUND |           | VEHICLE                    | 
```