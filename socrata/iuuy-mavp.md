# Contracts: ESD: High Desert: Fiscal Year 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/contracts-esd-high-desert-fiscal-year-2014-a5306) |
| Metadata | [Link](https://data.oregon.gov/api/views/iuuy-mavp) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/iuuy-mavp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/iuuy-mavp/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | iuuy-mavp |
| Name | Contracts: ESD: High Desert: Fiscal Year 2014 |
| Category | Revenue & Expense |
| Tags | contracts, esd, high desert, fiscal year 2014 |
| Created | 2014-12-16T21:58:55Z |
| Publication Date | 2014-12-29T06:16:12Z |

## Description

Contracts for High Desert ESD for Fiscal Year 2014

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type | Render Type |
| ======== | ============== | ==================== | ==================== | ========= | =========== |
| Yes      | numeric metric | esd                  | ESD #                | number    | number      |
| Yes      | series tag     | esd_name             | ESD NAME             | text      | text        |
| Yes      | series tag     | award                | AWARD #              | text      | text        |
| Yes      | series tag     | award_title          | AWARD TITLE          | text      | text        |
| Yes      | series tag     | award_type           | AWARD TYPE           | text      | text        |
| Yes      | series tag     | contract_type        | CONTRACT TYPE        | text      | text        |
| Yes      | series tag     | contractor_name      | CONTRACTOR NAME      | text      | text        |
| No       |                | contractor_address   | CONTRACTOR ADDRESS   | text      | text        |
| Yes      | series tag     | contractor_city      | CONTRACTOR CITY      | text      | text        |
| Yes      | series tag     | contractor_state     | CONTRACTOR STATE     | text      | text        |
| Yes      | series tag     | contractor_zip       | CONTRACTOR ZIP       | text      | text        |
| No       |                | start_amend_exp_date | START/AMEND/EXP DATE | text      | text        |
| Yes      | numeric metric | original_value       | ORIGINAL VALUE       | money     | money       |
| Yes      | series tag     | amendment_value      | AMENDMENT VALUE      | text      | text        |
| Yes      | numeric metric | total_value          | TOTAL VALUE          | money     | money       |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = contractor_address,start_amend_exp_date
```

## Data Commands

```ls
series e:iuuy-mavp d:2014-01-01T00:00:00.000Z t:esd_name="High Desert Education Service District" t:contract_type=Service t:contractor_name="TERMINIX, INC." t:award=N/A t:award_type="Price Agreement" t:award_title="Pest Control" m:esd=1975 m:original_value=1112.4 m:total_value=1112.4

series e:iuuy-mavp d:2014-01-01T00:00:00.000Z t:esd_name="High Desert Education Service District" t:contract_type=Service t:contractor_name="TERMINIX, INC." t:award=N/A t:award_type="Price Agreement" t:award_title="Pest Control" m:esd=1975 m:original_value=1030 m:total_value=1030

series e:iuuy-mavp d:2014-01-01T00:00:00.000Z t:esd_name="High Desert Education Service District" t:contract_type=Service t:contractor_name="TERMINIX, INC." t:award=N/A t:award_type="Price Agreement" t:award_title="Pest Control" m:esd=1975 m:original_value=594 m:total_value=594
```

## Meta Commands

```ls
metric m:esd p:integer l:"ESD #" t:dataTypeName=number

metric m:original_value p:double l:"ORIGINAL VALUE" t:dataTypeName=money

metric m:total_value p:double l:"TOTAL VALUE" t:dataTypeName=money

entity e:iuuy-mavp l:"Contracts: ESD: High Desert: Fiscal Year 2014" t:url=https://data.oregon.gov/api/views/iuuy-mavp

property e:iuuy-mavp t:meta.view v:id=iuuy-mavp v:category="Revenue & Expense" v:averageRating=0 v:name="Contracts: ESD: High Desert: Fiscal Year 2014"

property e:iuuy-mavp t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:iuuy-mavp t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| esd  | esd_name                               | award | award_title   | award_type      | contract_type | contractor_name               | contractor_address | contractor_city | contractor_state | contractor_zip | start_amend_exp_date | original_value | amendment_value | total_value | 
| ==== | ====================================== | ===== | ============= | =============== | ============= | ============================= | ================== | =============== | ================ | ============== | ==================== | ============== | =============== | =========== | 
| 1975 | High Desert Education Service District | N/A   | Pest Control  | Price Agreement | Service       | TERMINIX, INC.                |                    |                 |                  |                | 07/01/13-06/30/14    | 1112.40        |                 | 1112.40     | 
| 1975 | High Desert Education Service District | N/A   | Pest Control  | Price Agreement | Service       | TERMINIX, INC.                |                    |                 |                  |                | 07/01/13-06/30/14    | 1030.00        |                 | 1030.00     | 
| 1975 | High Desert Education Service District | N/A   | Pest Control  | Price Agreement | Service       | TERMINIX, INC.                |                    |                 |                  |                | 07/01/13-06/30/14    | 594.00         |                 | 594.00      | 
| 1975 | High Desert Education Service District | N/A   | Pest Control  | Price Agreement | Service       | TERMINIX, INC.                |                    |                 |                  |                | 07/01/13-06/30/14    | 550.00         |                 | 550.00      | 
| 1975 | High Desert Education Service District | N/A   | Pest Control  | Price Agreement | Service       | TERMINIX, INC.                |                    |                 |                  |                | 07/01/13-06/30/14    | 550.80         |                 | 550.80      | 
| 1975 | High Desert Education Service District | N/A   | Pest Control  | Price Agreement | Service       | TERMINIX, INC.                |                    |                 |                  |                | 07/01/13-06/30/14    | 510.00         |                 | 510.00      | 
| 1975 | High Desert Education Service District | N/A   | Pest Control  | Price Agreement | Service       | TERMINIX, INC.                |                    |                 |                  |                | 07/01/13-06/30/14    | 702.00         |                 | 702.00      | 
| 1975 | High Desert Education Service District | N/A   | Pest Control  | Price Agreement | Service       | TERMINIX, INC.                |                    |                 |                  |                | 07/01/13-06/30/14    | 650.00         |                 | 650.00      | 
| 1975 | High Desert Education Service District | N/A   | Pest Control  | Price Agreement | Service       | TERMINIX, INC.                |                    |                 |                  |                | 07/01/13-06/30/14    | 2412.80        |                 | 2412.80     | 
| 1975 | High Desert Education Service District | N/A   | Building Rent | Lease           | Material      | NORRIS & STEVENS/JUNGERS PROP |                    |                 |                  |                | 07/01/13-06/30/14    | 175803.72      |                 | 175803.72   | 
```