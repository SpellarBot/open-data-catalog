# 2014 State Budget Restrictions As of June 30, 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2014-state-budget-restrictions-as-of-june-30-2014-7d2ff) |
| Metadata | [Link](https://data.mo.gov/api/views/pfgn-6b4z) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/pfgn-6b4z/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/pfgn-6b4z/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | pfgn-6b4z |
| Name | 2014 State Budget Restrictions As of June 30, 2014 |
| Category | Government Administration |
| Created | 2014-07-02T18:42:54Z |
| Publication Date | 2014-07-02T18:43:34Z |

## Description

2014 State Budget Restrictions As of June 30, 2014

## Columns

```ls
| Included | Schema Type    | Field Name                    | Name                          | Data Type     | Render Type   |
| ======== | ============== | ============================= | ============================= | ============= | ============= |
| Yes      | series tag     | political_subdivision_name    | Political Subdivision Name    | text          | text          |
| Yes      | time           | date_of_issuance              | Date of Issuance              | calendar_date | calendar_date |
| Yes      | series tag     | bond_name                     | Bond Name                     | text          | text          |
| Yes      | series tag     | description_of_revenue_stream | Description of Revenue Stream | text          | text          |
| Yes      | numeric metric | face_amount                   | Face Amount                   | money         | money         |
| Yes      | series tag     | outstanding_balance           | Outstanding Balance           | text          | text          |
| Yes      | series tag     | description_of_project        | Description of Project        | text          | text          |
| Yes      | series tag     | interest_rate                 | Interest Rate                 | text          | text          |
```

## Time Field

```ls
Value = date_of_issuance
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:pfgn-6b4z d:2004-02-01T00:00:00.000Z t:outstanding_balance="NOT PROVIDED" t:description_of_revenue_stream="STATE AND LOCAL FUNDS" t:bond_name=BOA t:political_subdivision_name="ACADEMIE LAFAYETTE" t:interest_rate=1.63 t:description_of_project="NOT PROVIDED" m:face_amount=2310000

series e:pfgn-6b4z d:2014-05-01T00:00:00.000Z t:outstanding_balance=1000000 t:description_of_revenue_stream="STATE AND LOCAL FUNDS" t:bond_name="COUNTRY CLUB CHERRY REFI" t:political_subdivision_name="ACADEMIE LAFAYETTE" t:interest_rate=4.3499999999999996 t:description_of_project="CHERRY REFI" m:face_amount=1000000

series e:pfgn-6b4z d:2014-05-01T00:00:00.000Z t:outstanding_balance=3035000 t:description_of_revenue_stream="STATE AND LOCAL FUNDS" t:bond_name="COUNTRY CLUB OAK REFI" t:political_subdivision_name="ACADEMIE LAFAYETTE" t:interest_rate=4.3499999999999996 t:description_of_project="OAK REFI" m:face_amount=3035000
```

## Meta Commands

```ls
metric m:face_amount p:double l:"Face Amount" t:dataTypeName=money

entity e:pfgn-6b4z l:"2014 State Budget Restrictions As of June 30, 2014" t:url=https://data.mo.gov/api/views/pfgn-6b4z

property e:pfgn-6b4z t:meta.view v:id=pfgn-6b4z v:category="Government Administration" v:averageRating=0 v:name="2014 State Budget Restrictions As of June 30, 2014"

property e:pfgn-6b4z t:meta.view.owner v:id=4cdh-4my4 v:screenName=Dwight v:displayName=Dwight

property e:pfgn-6b4z t:meta.view.tableauthor v:id=4cdh-4my4 v:screenName=Dwight v:roleName=editor v:displayName=Dwight
```

## Top Records

```ls
| political_subdivision_name                               | date_of_issuance    | bond_name                                      | description_of_revenue_stream | face_amount | outstanding_balance | description_of_project | interest_rate      | 
| ======================================================== | =================== | ============================================== | ============================= | =========== | =================== | ====================== | ================== | 
| ACADEMIE LAFAYETTE                                       | 2004-02-01T00:00:00 | BOA                                            | STATE AND LOCAL FUNDS         | 2310000.00  | NOT PROVIDED        | NOT PROVIDED           | 1.63               | 
| ACADEMIE LAFAYETTE                                       | 2014-05-01T00:00:00 | COUNTRY CLUB CHERRY REFI                       | STATE AND LOCAL FUNDS         | 1000000.00  | 1000000             | CHERRY REFI            | 4.3499999999999996 | 
| ACADEMIE LAFAYETTE                                       | 2014-05-01T00:00:00 | COUNTRY CLUB OAK REFI                          | STATE AND LOCAL FUNDS         | 3035000.00  | 3035000             | OAK REFI               | 4.3499999999999996 | 
| ACADEMIE LAFAYETTE                                       | 2009-06-24T00:00:00 | IFF                                            | STATE AND LOCAL FUNDS         | 250000.00   | NOT PROVIDED        | NOT PROVIDED           | 5.875              | 
| ACADEMIE LAFAYETTE                                       | 2013-07-25T00:00:00 | LEASE                                          | STATE AND LOCAL FUNDS         | 85840.00    | 66012               | APPLE LEASE 007        | 8.625              | 
| ACADEMIE LAFAYETTE                                       | 2012-09-01T00:00:00 | LEASE                                          | STATE AND LOCAL FUNDS         | 64783.00    | 30809               | APPLE LEASE 006        | 8.9860000000000007 | 
| ACADEMIE LAFAYETTE                                       | 2011-09-20T00:00:00 | LEASE                                          | STATE AND LOCAL FUNDS         | 94934.00    | 10385               | APPLE LEASE 005        | 8.6780000000000008 | 
| ACADEMIE LAFAYETTE                                       | 2012-11-02T00:00:00 | IFF                                            | STATE AND LOCAL FUNDS         | 1425000.00  | 930928              | CHERRY ST BUILDING     | 5.5                | 
| ADAIR COUNTY R-II SCHOOL DISTRICT                        | 2010-03-30T00:00:00 | GENERAL OBLIGATION REFUNDING BONDS SERIES 2010 | REVENUE FROM LEVY             | 560000.00   | 365000              | BUILDING PROJECT       | 1.75               | 
| ADRIAN REORGANIZED SCHOOL DISTRICT R-III OF BATES COUNTY | 2006-10-01T00:00:00 | GENERAL OBLIGATION SCHOOL BLDG BONDS           | MOHEFA                        | 4900000.00  | NOT PROVIDED        | NOT PROVIDED           | NOT PROVIDED       | 
```