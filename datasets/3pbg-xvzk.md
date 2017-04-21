# Contracts: ESD: Harney: Fiscal Year 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/contracts-esd-harney-fiscal-year-2013-001bc) |
| Metadata | [Link](https://data.oregon.gov/api/views/3pbg-xvzk) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/3pbg-xvzk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/3pbg-xvzk/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | 3pbg-xvzk |
| Name | Contracts: ESD: Harney: Fiscal Year 2013 |
| Category | Revenue & Expense |
| Tags | contracts, esd, harney, fiscal year 2013 |
| Created | 2013-11-04T19:53:56Z |
| Publication Date | 2013-11-04T19:56:47Z |

## Description

Contracts for Harney ESD for Fiscal Year 2013

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type | Render Type |
| ======== | ============== | ==================== | ==================== | ========= | =========== |
| Yes      | series tag     | esd                  | ESD #                | text      | text        |
| Yes      | series tag     | esd_name             | ESD NAME             | text      | text        |
| Yes      | series tag     | award                | AWARD #              | text      | text        |
| Yes      | series tag     | award_title          | AWARD TITLE          | text      | text        |
| Yes      | series tag     | award_type           | AWARD TYPE           | text      | text        |
| Yes      | series tag     | contractor           | CONTRACTOR           | text      | text        |
| No       |                | start_amend_exp_date | START/AMEND/EXP DATE | text      | text        |
| Yes      | series tag     | original_value       | ORIGINAL VALUE       | text      | text        |
| Yes      | series tag     | amendment_value      | AMENDMENT VALUE      | text      | text        |
| Yes      | numeric metric | total_value          | TOTAL VALUE          | money     | money       |
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
series e:3pbg-xvzk d:2013-01-01T00:00:00.000Z t:esd_name="Harney ESD" t:contractor="Susan Swank" t:award=2012-13 t:esd="ESD #17" t:award_type="Custodial Service" t:award_title="Custodial Service" t:original_value=1150/mth m:total_value=14400

series e:3pbg-xvzk d:2013-01-01T00:00:00.000Z t:esd_name="Harney ESD" t:contractor="Belcher's Janitorial" t:award=2012-13 t:esd="ESD #17" t:award_type="Custodial Service" t:award_title="Custodial Service" t:original_value=$112/visit m:total_value=22947

series e:3pbg-xvzk d:2013-01-01T00:00:00.000Z t:esd_name="Harney ESD" t:contractor=HDESD t:award=2012-13 t:esd="ESD #17" t:award_type="Student Assessment" t:award_title=DataWarehouse t:original_value=$3,030.00 m:total_value=3030
```

## Meta Commands

```ls
metric m:total_value p:double l:"TOTAL VALUE" t:dataTypeName=money

entity e:3pbg-xvzk l:"Contracts: ESD: Harney: Fiscal Year 2013" t:url=https://data.oregon.gov/api/views/3pbg-xvzk

property e:3pbg-xvzk t:meta.view v:id=3pbg-xvzk v:category="Revenue & Expense" v:averageRating=0 v:name="Contracts: ESD: Harney: Fiscal Year 2013"

property e:3pbg-xvzk t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:3pbg-xvzk t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| esd     | esd_name   | award   | award_title                | award_type                 | contractor           | start_amend_exp_date | original_value | amendment_value | total_value | 
| ======= | ========== | ======= | ========================== | ========================== | ==================== | ==================== | ============== | =============== | =========== | 
| ESD #17 | Harney ESD | 2012-13 | Custodial Service          | Custodial Service          | Susan Swank          | 7-1-2012/6-30-2013   | 1150/mth       |                 | 14400.00    | 
| ESD #17 | Harney ESD | 2012-13 | Custodial Service          | Custodial Service          | Belcher's Janitorial | 7-1-2012/6-30-2013   | $112/visit     |                 | 22947.00    | 
| ESD #17 | Harney ESD | 2012-13 | DataWarehouse              | Student Assessment         | HDESD                | 7-1-2012/6-30-2013   | $3,030.00      |                 | 3030.00     | 
| ESD #17 | Harney ESD | 2012-13 | SLP                        | Speech Services            | Hello Foundation     | 7-1-2012/6-30-2013   | $64,500.00     |                 | 64500.00    | 
| ESD #17 | Harney ESD | 2012-13 | Auditors                   | Auditors                   | Osters               | 7-1-2012/6-30-2013   | $11,356.00     |                 | 11356.00    | 
| ESD #17 | Harney ESD | 2012-13 | SPED Records Mgmt Software | SPED Records Mgmt Software | LBL ESD              | 7-1-2012/6-30-2013   | $341.11        |                 | 341.11      | 
```