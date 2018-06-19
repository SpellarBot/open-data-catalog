# Contracts: ESD: Douglas: Fiscal Year 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/contracts-esd-douglas-fiscal-year-2013-caea4) |
| Metadata | [Link](https://data.oregon.gov/api/views/ppmi-cu2y) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/ppmi-cu2y/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/ppmi-cu2y/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | ppmi-cu2y |
| Name | Contracts: ESD: Douglas: Fiscal Year 2013 |
| Category | Revenue & Expense |
| Tags | contracts, esd, douglas, fiscal year 2013 |
| Created | 2013-10-31T20:41:57Z |
| Publication Date | 2013-10-31T20:46:21Z |

## Description

Contracts for Douglas ESD for Fiscal Year 2013

## Columns

```ls
| Included | Schema Type    | Field Name                     | Name                           | Data Type     | Render Type   |
| ======== | ============== | ============================== | ============================== | ============= | ============= |
| Yes      | numeric metric | esd                            | ESD #                          | number        | number        |
| Yes      | series tag     | esd_name                       | ESD NAME                       | text          | text          |
| Yes      | series tag     | award_number_w_amendments      | Award Number w/Amendments      | text          | text          |
| Yes      | series tag     | award_title                    | Award Title                    | text          | text          |
| Yes      | series tag     | award_type                     | Award Type                     | text          | text          |
| Yes      | series tag     | contractor_information         | Contractor Information         | text          | text          |
| Yes      | time           | original_start                 | Original Start                 | calendar_date | calendar_date |
| No       |                | amendment_date                 | Amendment Date                 | text          | text          |
| No       |                | expiration_date                | Expiration Date                | calendar_date | calendar_date |
| Yes      | numeric metric | original_award_value           | Original Award Value           | number        | number        |
| Yes      | numeric metric | amendment_value                | Amendment Value                | number        | number        |
| Yes      | numeric metric | total_award_value_w_amendments | Total Award Value w/Amendments | number        | number        |
```

## Time Field

```ls
Value = original_start
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = amendment_date,expiration_date
```

## Data Commands

```ls
series e:ppmi-cu2y d:2013-01-28T00:00:00.000Z t:esd_name="Douglas Education Service District" t:award_type=CONTRACT t:award_title="ANNUAL SUBSCRIPTION" t:contractor_information="ABC SIGNUP" m:total_award_value_w_amendments=2990 m:esd=1980 m:original_award_value=2990

series e:ppmi-cu2y d:2013-05-14T00:00:00.000Z t:esd_name="Douglas Education Service District" t:award_type=CONTRACT t:award_title=SERVICES t:contractor_information="Arrow Pavement Maintenance" m:total_award_value_w_amendments=6644 m:esd=1980 m:original_award_value=6644

series e:ppmi-cu2y d:2012-08-24T00:00:00.000Z t:esd_name="Douglas Education Service District" t:award_type=RENTAL t:award_title=RENTAL t:contractor_information="Berry's OaK Grove Storage" m:amendment_value=280 m:total_award_value_w_amendments=1840 m:esd=1980 m:original_award_value=1560
```

## Meta Commands

```ls
metric m:esd p:integer l:"ESD #" t:dataTypeName=number

metric m:original_award_value p:double l:"Original Award Value" t:dataTypeName=number

metric m:amendment_value p:double l:"Amendment Value" t:dataTypeName=number

metric m:total_award_value_w_amendments p:double l:"Total Award Value w/Amendments" t:dataTypeName=number

entity e:ppmi-cu2y l:"Contracts: ESD: Douglas: Fiscal Year 2013" t:url=https://data.oregon.gov/api/views/ppmi-cu2y

property e:ppmi-cu2y t:meta.view v:id=ppmi-cu2y v:category="Revenue & Expense" v:averageRating=0 v:name="Contracts: ESD: Douglas: Fiscal Year 2013"

property e:ppmi-cu2y t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:ppmi-cu2y t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| esd  | esd_name                           | award_number_w_amendments | award_title              | award_type                      | contractor_information                | original_start      | amendment_date | expiration_date     | original_award_value | amendment_value | total_award_value_w_amendments | 
| ==== | ================================== | ========================= | ======================== | =============================== | ===================================== | =================== | ============== | =================== | ==================== | =============== | ============================== | 
| 1980 | Douglas Education Service District |                           | ANNUAL SUBSCRIPTION      | CONTRACT                        | ABC SIGNUP                            | 2013-01-28T00:00:00 |                |                     | 2990                 |                 | 2990                           | 
| 1980 | Douglas Education Service District |                           | SERVICES                 | CONTRACT                        | Arrow Pavement Maintenance            | 2013-05-14T00:00:00 |                | 2013-05-16T00:00:00 | 6644                 |                 | 6644                           | 
| 1980 | Douglas Education Service District |                           | RENTAL                   | RENTAL                          | Berry's OaK Grove Storage             | 2012-08-24T00:00:00 |                |                     | 1560                 | 280             | 1840                           | 
| 1980 | Douglas Education Service District |                           | PRESCHOOL SERVICES       | PROFESSIONAL SERVICES AGREEMENT | Butterfly House Early Learning Center | 2012-07-01T00:00:00 |                | 2013-06-30T00:00:00 | 11356.5              |                 | 11356.5                        | 
| 1980 | Douglas Education Service District |                           | CONSULTANT FEE           | INDEPENDENT CONTRACTOR          | Catherine Lynn Cole                   | 2013-02-07T00:00:00 |                |                     | 1000                 |                 | 1000                           | 
| 1980 | Douglas Education Service District |                           | SLP SERVICES             | SERVICE AGREEMENT               | COMPHEALTH                            | 2013-01-16T00:00:00 |                | 2013-06-07T00:00:00 | 54720                |                 | 54720                          | 
| 1980 | Douglas Education Service District |                           | SLP SERVICES             | SERVICE AGREEMENT               | CUMBERLAND THERAPY SERVICES           | 2012-07-01T00:00:00 |                | 2013-05-03T00:00:00 | 74520                | 2038.11         | 76558.11                       | 
| 1980 | Douglas Education Service District |                           | SLP SERVICES             | SERVICE AGREEMENT               | CUMBERLAND THERAPY SERVICES           | 2013-06-26T00:00:00 |                |                     | 72312                |                 | 72312                          | 
| 1980 | Douglas Education Service District |                           | COMPUTER NETWORK SUBSIDY | INTERAGENCY AGREEMENT           | DAYS CREEK SD                         | 2012-07-01T00:00:00 |                | 2013-06-30T00:00:00 | 17029                |                 | 17029                          | 
| 1980 | Douglas Education Service District |                           | EQUIPMENT                | CAPITAL LEASE                   | De Large Landen                       | 2012-09-07T00:00:00 |                |                     | 29377.48             |                 | 29377.48                       | 
```