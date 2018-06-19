# UFund Data FY 2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ufund-data-fy-2015) |
| Metadata | [Link](https://data.hawaii.gov/api/views/fhy9-kajz) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/fhy9-kajz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/fhy9-kajz/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | fhy9-kajz |
| Name | UFund Data FY 2015 |
| Created | 2015-02-09T20:20:21Z |
| Publication Date | 2015-02-10T20:43:27Z |

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| Yes      | time           | fiscal_year      | FISCAL YEAR      | number    | text        |
| Yes      | series tag     | service          | SERVICE          | text      | text        |
| Yes      | series tag     | department       | DEPARTMENT       | text      | text        |
| Yes      | series tag     | program          | PROGRAM          | text      | text        |
| Yes      | series tag     | expense_category | EXPENSE CATEGORY | text      | text        |
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
series e:fhy9-kajz d:2015-01-01T00:00:00.000Z t:fund_type=U t:description="TURNOVER SAVINGS" t:program="LEGAL SERVICES" t:department="LEGAL SERVICES" t:service="DEPT OF THE ATTORNEY GENERAL" t:expense_category="PERSONAL EXPENSES" t:fund="INTERDEPARTMENTAL TRANSFER" m:approved_amount=-898335

series e:fhy9-kajz d:2015-01-01T00:00:00.000Z t:fund_type=U t:description=REIMBURSEMENTS t:program="LEGAL SERVICES" t:department="LEGAL SERVICES" t:service="DEPT OF THE ATTORNEY GENERAL" t:expense_category="PERSONAL EXPENSES" t:fund="INTERDEPARTMENTAL TRANSFER" m:approved_amount=-737518

series e:fhy9-kajz d:2015-01-01T00:00:00.000Z t:fund_type=U t:description="FURLOUGH SAVINGS" t:program="LEGAL SERVICES" t:department="LEGAL SERVICES" t:service="DEPT OF THE ATTORNEY GENERAL" t:expense_category="PERSONAL EXPENSES" t:fund="INTERDEPARTMENTAL TRANSFER" m:approved_amount=-668745
```

## Meta Commands

```ls
metric m:approved_amount p:double l:"APPROVED AMOUNT" t:dataTypeName=money

entity e:fhy9-kajz l:"UFund Data FY 2015" t:url=https://data.hawaii.gov/api/views/fhy9-kajz

property e:fhy9-kajz t:meta.view v:id=fhy9-kajz v:averageRating=0 v:name="UFund Data FY 2015"

property e:fhy9-kajz t:meta.view.owner v:id=q99n-k47h v:screenName="Open Data Portal Administrator" v:displayName="Open Data Portal Administrator"

property e:fhy9-kajz t:meta.view.tableauthor v:id=q99n-k47h v:screenName="Open Data Portal Administrator" v:roleName=administrator v:displayName="Open Data Portal Administrator"
```

## Top Records

```ls
| fiscal_year | service                            | department                                 | program                                 | expense_category       | approved_amount | fund                       | fund_type | description                            | 
| =========== | ================================== | ========================================== | ======================================= | ====================== | =============== | ========================== | ========= | ====================================== | 
| 2015        | DEPT OF THE ATTORNEY GENERAL       | LEGAL SERVICES                             | LEGAL SERVICES                          | PERSONAL EXPENSES      | -898335.00      | INTERDEPARTMENTAL TRANSFER | U         | TURNOVER SAVINGS                       | 
| 2015        | DEPT OF THE ATTORNEY GENERAL       | LEGAL SERVICES                             | LEGAL SERVICES                          | PERSONAL EXPENSES      | -737518.00      | INTERDEPARTMENTAL TRANSFER | U         | REIMBURSEMENTS                         | 
| 2015        | DEPT OF THE ATTORNEY GENERAL       | LEGAL SERVICES                             | LEGAL SERVICES                          | PERSONAL EXPENSES      | -668745.00      | INTERDEPARTMENTAL TRANSFER | U         | FURLOUGH SAVINGS                       | 
| 2015        | DEPT OF THE ATTORNEY GENERAL       | LEGAL SERVICES                             | LEGAL SERVICES                          | PERSONAL EXPENSES      | -261195.00      | INTERDEPARTMENTAL TRANSFER | U         | REDUCTION TO MEET TARGET               | 
| 2015        | DEPT OF THE ATTORNEY GENERAL       | LEGAL SERVICES                             | LEGAL SERVICES                          | PERSONAL EXPENSES      | -31050.00       | INTERDEPARTMENTAL TRANSFER | U         | FRINGE BENEFITS - PR 6C & 13           | 
| 2015        | DEPT OF LAND AND NATURAL RESOURCES | NATIVE RESOURCES & FIRE PROTECTION PROGRAM | FORESTRY DIVISION                       | PERSONAL EXPENSES      | -26268.00       | INTERDEPARTMENTAL TRANSFER | U         | FUND ADJUSTMENT                        | 
| 2015        | DEPT OF EDUCATION                  | INSTRUCTIONAL SUPPORT                      | INSTRUCTIONAL SERVICES BRANCH           | OTHER CURRENT EXPENSES | -16913.00       | INTERDEPARTMENTAL TRANSFER | U         | FB1315B LEG ADJ B - ALIGN TO STRATEGIC | 
| 2015        | DEPT OF THE ATTORNEY GENERAL       | LEGAL SERVICES                             | LEGAL SERVICES                          | PERSONAL EXPENSES      | -6301.00        | INTERDEPARTMENTAL TRANSFER | U         | DEPUTY ATTORNEY GENERAL                | 
| 2015        | DEPT OF HEALTH                     | CHILD & ADOLESCENT MENTAL HEALTH           | CHILDREN & ADOLESCENT MH ADMINISTRATION | OTHER CURRENT EXPENSES | 50.00           | INTERDEPARTMENTAL TRANSFER | U         | TRAINING COSTS & REGISTRATION FEES     | 
| 2015        | DEPT OF HEALTH                     | CHILD & ADOLESCENT MENTAL HEALTH           | CHILDREN & ADOLESCENT MH ADMINISTRATION | OTHER CURRENT EXPENSES | 93.00           | INTERDEPARTMENTAL TRANSFER | U         | OTHER SUPPLIES                         | 
```