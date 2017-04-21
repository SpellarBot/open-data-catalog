# Contracts: ESD: High Desert: Fiscal Year 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/contracts-esd-high-desert-fiscal-year-2013-68c98) |
| Metadata | [Link](https://data.oregon.gov/api/views/5syf-bcdm) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/5syf-bcdm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/5syf-bcdm/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | 5syf-bcdm |
| Name | Contracts: ESD: High Desert: Fiscal Year 2013 |
| Category | Revenue & Expense |
| Tags | contracts, esd, high desert, fiscal year 2013 |
| Created | 2013-10-31T17:51:05Z |
| Publication Date | 2013-10-31T17:56:13Z |

## Description

Contracts for High Desert ESD for Fiscal Year 2013

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
| No       |                | start_amend_exp_date | START/AMEND/EXP DATE | text      | text        |
| Yes      | series tag     | original_value       | ORIGINAL VALUE       | text      | text        |
| Yes      | series tag     | amendment_value      | AMENDMENT VALUE      | text      | text        |
| Yes      | series tag     | total_value          | TOTAL VALUE          | text      | text        |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = start_amend_exp_date
```

## Data Commands

```ls
series e:5syf-bcdm d:2013-01-01T00:00:00.000Z t:esd_name="High Desert Education Service District" t:contract_type=Professional t:contractor_name="INDEPENDENT ACTUARIES, INC" t:award=N/A t:award_type="One Time" t:award_title="Actuarial Service" t:original_value="* 9,100" t:total_value="* 9,100" m:esd=1975

series e:5syf-bcdm d:2013-01-01T00:00:00.000Z t:esd_name="High Desert Education Service District" t:contract_type=Professional t:contractor_name="INTERMOUNTAIN ESD" t:award=N/A t:award_type="Price Agreement" t:award_title="Administrative Service" t:original_value="* 9,415" t:total_value="* 9,415" m:esd=1975

series e:5syf-bcdm d:2013-01-01T00:00:00.000Z t:esd_name="High Desert Education Service District" t:contract_type=Professional t:contractor_name="COIC*CENTRAL OREGON INTERGOVERNMENTAL CO" t:award=N/A t:award_type="Price Agreement" t:award_title="Alternative Ed Services" t:original_value="* 164,994" t:total_value="* 164,994" m:esd=1975
```

## Meta Commands

```ls
metric m:esd p:integer l:"ESD #" t:dataTypeName=number

entity e:5syf-bcdm l:"Contracts: ESD: High Desert: Fiscal Year 2013" t:url=https://data.oregon.gov/api/views/5syf-bcdm

property e:5syf-bcdm t:meta.view v:id=5syf-bcdm v:category="Revenue & Expense" v:averageRating=0 v:name="Contracts: ESD: High Desert: Fiscal Year 2013"

property e:5syf-bcdm t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:5syf-bcdm t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| esd  | esd_name                               | award | award_title             | award_type      | contract_type | contractor_name                          | start_amend_exp_date | original_value | amendment_value | total_value | 
| ==== | ====================================== | ===== | ======================= | =============== | ============= | ======================================== | ==================== | ============== | =============== | =========== | 
| 1975 | High Desert Education Service District | N/A   | Actuarial Service       | One Time        | Professional  | INDEPENDENT ACTUARIES, INC               | 07/01/12-06/30/13    | * 9,100        |                 | * 9,100     | 
| 1975 | High Desert Education Service District | N/A   | Administrative Service  | Price Agreement | Professional  | INTERMOUNTAIN ESD                        | 07/01/12-06/30/13    | * 9,415        |                 | * 9,415     | 
| 1975 | High Desert Education Service District | N/A   | Alternative Ed Services | Price Agreement | Professional  | COIC*CENTRAL OREGON INTERGOVERNMENTAL CO | 07/01/12-06/30/13    | * 164,994      |                 | * 164,994   | 
| 1975 | High Desert Education Service District | N/A   | Auditing Services       | Price Agreement | Professional  | HARRIGAN PRICE FRONK CO LLP              | 07/01/12-06/30/13    | * 32,650       |                 | * 32,650    | 
| 1975 | High Desert Education Service District | N/A   | Building Rent           | Price Agreement | Material      | ALYCE HATCH CENTER                       | 07/01/12-06/30/13    | * 2,000        |                 | * 2,000     | 
| 1975 | High Desert Education Service District | N/A   | Building Rent           | Price Agreement | Material      | BEND LAPINE SCHOOL DISTRICT              | 07/01/12-06/30/13    | * 50,005       |                 | * 50,005    | 
| 1975 | High Desert Education Service District | N/A   | Building Rent           | Price Agreement | Material      | DESCHUTES CHILDRENS FOUNDATION           | 07/01/12-06/30/13    | * 19,186       |                 | * 19,186    | 
| 1975 | High Desert Education Service District | N/A   | Building Rent           | Price Agreement | Material      | FIRST & PENN INDUSTRIAL ACCT             | 07/01/12-06/30/13    | * 12,904       |                 | * 12,904    | 
| 1975 | High Desert Education Service District | N/A   | Building Rent           | Price Agreement | Material      | JEFFERSON CO SD 509-J                    | 07/01/12-06/30/13    | * 25,000       |                 | * 25,000    | 
| 1975 | High Desert Education Service District | N/A   | Building Rent           | Price Agreement | Material      | NORRIS & STEVENS/JUNGERS PROP            | 07/01/12-06/30/13    | * 170,683      |                 | * 170,683   | 
```