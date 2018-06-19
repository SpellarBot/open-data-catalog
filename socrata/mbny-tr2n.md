# Monthly Medicaid Payments and Recipients by Category of Service

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/monthly-medicaid-payments-and-recipients-by-category-of-service) |
| Metadata | [Link](https://data.iowa.gov/api/views/mbny-tr2n) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/mbny-tr2n/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/mbny-tr2n/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | mbny-tr2n |
| Name | Monthly Medicaid Payments and Recipients by Category of Service |
| Attribution | Iowa Department of Human Services, Medicaid Management Information System - Report IAMM2200-R002 |
| Category | Health |
| Tags | medicaid, health care, public assistance |
| Created | 2014-12-01T16:55:22Z |
| Publication Date | 2016-12-30T16:42:12Z |

## Description

This dataset contains aggregate Medicaid payments, and counts for recipients, claims and units of service by month and category, starting with month ending 1/31/2011.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name           | Data Type     | Render Type   |
| ======== | ============== | ================= | ============== | ============= | ============= |
| Yes      | time           | report_as_of_date | Report Date    | calendar_date | calendar_date |
| Yes      | series tag     | svccat            | Category       | text          | text          |
| Yes      | numeric metric | recip             | Recipients     | number        | number        |
| Yes      | numeric metric | claims            | Claims         | number        | number        |
| Yes      | numeric metric | units             | Units          | number        | number        |
| Yes      | numeric metric | totalpmt          | Payments       | money         | money         |
| Yes      | numeric metric | avgunitcost       | Avg Unit Cost  | money         | money         |
| Yes      | numeric metric | avgeligcost       | Avg Elig Cost  | money         | money         |
| Yes      | numeric metric | avgunitrecip      | Avg Unit Recip | number        | number        |
| Yes      | numeric metric | avgcostrecip      | Avg Cost Recip | money         | money         |
```

## Time Field

```ls
Value = report_as_of_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:mbny-tr2n d:2011-08-31T00:00:00.000Z t:svccat="MEP CASE MANAGEMENT" m:claims=0 m:totalpmt=0 m:avgunitcost=0 m:avgunitrecip=0 m:recip=0 m:avgeligcost=0 m:units=0 m:avgcostrecip=0

series e:mbny-tr2n d:2012-04-30T00:00:00.000Z t:svccat="MEP CASE MANAGEMENT" m:claims=0 m:totalpmt=0 m:avgunitcost=0 m:avgunitrecip=0 m:recip=0 m:avgeligcost=0 m:units=0 m:avgcostrecip=0

series e:mbny-tr2n d:2012-09-30T00:00:00.000Z t:svccat="CHILD PART HOSP" m:claims=0 m:totalpmt=0 m:avgunitcost=0 m:avgunitrecip=0 m:recip=0 m:avgeligcost=0 m:units=0 m:avgcostrecip=0
```

## Meta Commands

```ls
metric m:recip p:integer l:Recipients d:"Number of recipients served within the category of service" t:dataTypeName=number

metric m:claims p:integer l:Claims d:"Number of claims paid within the category of service" t:dataTypeName=number

metric m:units p:integer l:Units d:"Total number of units of service for the paid claims." t:dataTypeName=number

metric m:totalpmt p:double l:Payments d:"Total amount of claims paid within the category of service for the month" t:dataTypeName=money

metric m:avgunitcost p:double l:"Avg Unit Cost" d:"Average cost per unit of service for the month by category of service" t:dataTypeName=money

metric m:avgeligcost p:double l:"Avg Elig Cost" d:"Average cost per eligible recipients for the month by category of service" t:dataTypeName=money

metric m:avgunitrecip p:double l:"Avg Unit Recip" d:"Average units per recipient for the month by category of service" t:dataTypeName=number

metric m:avgcostrecip p:double l:"Avg Cost Recip" d:"Average cost per recipients served for the month by category of service" t:dataTypeName=money

entity e:mbny-tr2n l:"Monthly Medicaid Payments and Recipients by Category of Service" t:attribution="Iowa Department of Human Services, Medicaid Management Information System - Report IAMM2200-R002" t:url=https://data.iowa.gov/api/views/mbny-tr2n

property e:mbny-tr2n t:meta.view v:id=mbny-tr2n v:category=Health v:averageRating=0 v:name="Monthly Medicaid Payments and Recipients by Category of Service" v:attribution="Iowa Department of Human Services, Medicaid Management Information System - Report IAMM2200-R002"

property e:mbny-tr2n t:meta.view.license v:name="Public Domain"

property e:mbny-tr2n t:meta.view.owner v:id=grmb-3z9d v:profileImageUrlMedium=/api/users/grmb-3z9d/profile_images/THUMB v:profileImageUrlLarge=/api/users/grmb-3z9d/profile_images/LARGE v:screenName="Iowa Department of Human Services" v:profileImageUrlSmall=/api/users/grmb-3z9d/profile_images/TINY v:displayName="Iowa Department of Human Services"

property e:mbny-tr2n t:meta.view.tableauthor v:id=grmb-3z9d v:profileImageUrlMedium=/api/users/grmb-3z9d/profile_images/THUMB v:profileImageUrlLarge=/api/users/grmb-3z9d/profile_images/LARGE v:screenName="Iowa Department of Human Services" v:profileImageUrlSmall=/api/users/grmb-3z9d/profile_images/TINY v:roleName=editor v:displayName="Iowa Department of Human Services"
```

## Top Records

```ls
| report_as_of_date   | svccat                  | recip | claims | units | totalpmt | avgunitcost | avgeligcost | avgunitrecip | avgcostrecip | 
| =================== | ======================= | ===== | ====== | ===== | ======== | =========== | =========== | ============ | ============ | 
| 2011-08-31T00:00:00 | MEP CASE MANAGEMENT     | 0     | 0      | 0     | 0.00     | 0.00        | 0.00        | 0.00         | 0.00         | 
| 2012-04-30T00:00:00 | MEP CASE MANAGEMENT     | 0     | 0      | 0     | 0.00     | 0.00        | 0.00        | 0.00         | 0.00         | 
| 2012-09-30T00:00:00 | CHILD PART HOSP         | 0     | 0      | 0     | 0.00     | 0.00        | 0.00        | 0.00         | 0.00         | 
| 2013-01-31T00:00:00 | MANAGED SUBSTANCE ABUSE | 0     | 0      | 0     | 0.00     | 0.00        | 0.00        | 0.00         | 0.00         | 
| 2014-06-30T00:00:00 | FAMILY PRESERVATION     | 0     | 0      | 0     | 0.00     | 0.00        | 0.00        | 0.00         | 0.00         | 
| 2014-08-31T00:00:00 | DRUG CAPITATION         | 0     | 0      | 0     | 0.00     | 0.00        | 0.00        | 0.00         | 0.00         | 
| 2014-09-30T00:00:00 | IOWA-PLAN-HAB           | 0     | 0      | 0     | 0.00     | 0.00        | 0.00        | 0.00         | 0.00         | 
| 2011-04-30T00:00:00 | CHILD PART HOSP         | 0     | 0      | 0     | 0.00     | 0.00        | 0.00        | 0.00         | 0.00         | 
| 2011-01-31T00:00:00 | ADULT DAY TREATMENT     | 0     | 0      | 0     | 0.00     | 0.00        | 0.00        | 0.00         | 0.00         | 
| 2011-01-31T00:00:00 | ADULT PART HOSP         | 0     | 0      | 0     | 0.00     | 0.00        | 0.00        | 0.00         | 0.00         | 
```