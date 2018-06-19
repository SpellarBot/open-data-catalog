# Contracts: ESD: Wallowa: Fiscal Year 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/contracts-esd-wallowa-fiscal-year-2014-cb62e) |
| Metadata | [Link](https://data.oregon.gov/api/views/vsy7-psrh) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/vsy7-psrh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/vsy7-psrh/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | vsy7-psrh |
| Name | Contracts: ESD: Wallowa: Fiscal Year 2014 |
| Category | Revenue & Expense |
| Tags | contracts, esd, wallowa, fiscal year 2014 |
| Created | 2014-12-15T02:41:16Z |
| Publication Date | 2014-12-29T05:53:43Z |

## Description

Contracts for Wallowa ESD for Fiscal Year 2014

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
Excluded Fields = start_amend_exp_date
```

## Data Commands

```ls
series e:vsy7-psrh d:2014-01-01T00:00:00.000Z t:esd_name="Wallowa County ESD" t:contractor="Jerry Raedeke" t:award=N/A t:esd="ESD #18" t:award_type="Custodial Service" t:award_title="Custodial Service" m:original_value=5990 m:total_value=5990

series e:vsy7-psrh d:2014-01-01T00:00:00.000Z t:esd_name="Wallowa County ESD" t:contractor=EONI t:award=N/A t:esd="ESD #18" t:award_type="Network Services" t:award_title="Network Services" m:original_value=23546.4 m:total_value=23546.4

series e:vsy7-psrh d:2014-01-01T00:00:00.000Z t:esd_name="Wallowa County ESD" t:contractor="R.E. Myers & Assoc." t:award=N/A t:esd="ESD #18" t:award_type="Legislative Consult. Serv." t:award_title="Legislative Consult. Serv." m:original_value=10833.3 m:total_value=10833.3
```

## Meta Commands

```ls
metric m:original_value p:double l:"ORIGINAL VALUE" t:dataTypeName=money

metric m:total_value p:double l:"TOTAL VALUE" t:dataTypeName=money

entity e:vsy7-psrh l:"Contracts: ESD: Wallowa: Fiscal Year 2014" t:url=https://data.oregon.gov/api/views/vsy7-psrh

property e:vsy7-psrh t:meta.view v:id=vsy7-psrh v:category="Revenue & Expense" v:averageRating=0 v:name="Contracts: ESD: Wallowa: Fiscal Year 2014"

property e:vsy7-psrh t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:vsy7-psrh t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| esd     | esd_name           | award | award_title                | award_type                 | contractor          | start_amend_exp_date  | original_value | amendment_value | total_value | 
| ======= | ================== | ===== | ========================== | ========================== | =================== | ===================== | ============== | =============== | =========== | 
| ESD #18 | Wallowa County ESD | N/A   | Custodial Service          | Custodial Service          | Jerry Raedeke       | 07/01/2013-06/30/2014 | 5990.00        |                 | 5990.00     | 
| ESD #18 | Wallowa County ESD | N/A   | Network Services           | Network Services           | EONI                | 07/01/2013-06/30/2014 | 23546.40       |                 | 23546.40    | 
| ESD #18 | Wallowa County ESD | N/A   | Legislative Consult. Serv. | Legislative Consult. Serv. | R.E. Myers & Assoc. | 07/01/2013-06/30/2014 | 10833.30       |                 | 10833.30    | 
| ESD #18 | Wallowa County ESD | N/A   | Audit Services             | Audit Services             | Edison & Hurly PC   | 07/01/2013-06/30/2014 | 7800.00        |                 | 7800.00     | 
| ESD #18 | Wallowa County ESD | N/A   | Telecommunications         | Telecommunications         | Priority One        | 07/01/2013-06/30/2014 | 10451.35       |                 | 10451.35    | 
```