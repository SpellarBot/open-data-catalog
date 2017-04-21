# 2012 State Employee Pay as of COB May 31, 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2012-state-employee-pay-as-of-cob-may-31-2012-e5495) |
| Metadata | [Link](https://data.mo.gov/api/views/x2ty-4azc) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/x2ty-4azc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/x2ty-4azc/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | x2ty-4azc |
| Name | 2012 State Employee Pay as of COB May 31, 2012 |
| Category | Government |
| Created | 2012-06-01T15:50:08Z |
| Publication Date | 2012-06-01T15:58:27Z |

## Description

Pay information for calendar year 2012 (Januray 1 - close of business May 31) for the employees of the State of Missouri by their Agency of Employment, Position Title or Employee Name.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| Yes      | time           | calendar_year  | Calendar Year  | number    | number      |
| Yes      | series tag     | agency_name    | Agency Name    | text      | text        |
| Yes      | series tag     | position_title | Position Title | text      | text        |
| Yes      | series tag     | employee_name  | Employee Name  | text      | text        |
| Yes      | numeric metric | ytd_gross_pay  | YTD Gross Pay  | money     | money       |
```

## Time Field

```ls
Value = calendar_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:x2ty-4azc d:2012-01-01T00:00:00.000Z t:position_title="ACCOUNT CLERK II" t:agency_name=AGRICULTURE t:employee_name="PHILLIPS, ROBERT T." m:ytd_gross_pay=11885

series e:x2ty-4azc d:2012-01-01T00:00:00.000Z t:position_title="ACCOUNTANT I" t:agency_name=AGRICULTURE t:employee_name="ARNOLD, CAROL ANN" m:ytd_gross_pay=14180

series e:x2ty-4azc d:2012-01-01T00:00:00.000Z t:position_title="ACCOUNTANT II" t:agency_name=AGRICULTURE t:employee_name="BENNETT, SUSAN S." m:ytd_gross_pay=14980
```

## Meta Commands

```ls
metric m:ytd_gross_pay p:double l:"YTD Gross Pay" t:dataTypeName=money

entity e:x2ty-4azc l:"2012 State Employee Pay as of COB May 31, 2012" t:url=https://data.mo.gov/api/views/x2ty-4azc

property e:x2ty-4azc t:meta.view v:id=x2ty-4azc v:category=Government v:averageRating=0 v:name="2012 State Employee Pay as of COB May 31, 2012"

property e:x2ty-4azc t:meta.view.owner v:id=29n3-s86h v:screenName="Carolyn Aggeler" v:displayName="Carolyn Aggeler"

property e:x2ty-4azc t:meta.view.tableauthor v:id=29n3-s86h v:screenName="Carolyn Aggeler" v:roleName=editor v:displayName="Carolyn Aggeler"
```

## Top Records

```ls
| calendar_year | agency_name | position_title                 | employee_name         | ytd_gross_pay | 
| ============= | =========== | ============================== | ===================== | ============= | 
| 2012          | AGRICULTURE | ACCOUNT CLERK II               | PHILLIPS, ROBERT T.   | 11885.00      | 
| 2012          | AGRICULTURE | ACCOUNTANT I                   | ARNOLD, CAROL ANN     | 14180.00      | 
| 2012          | AGRICULTURE | ACCOUNTANT II                  | BENNETT, SUSAN S.     | 14980.00      | 
| 2012          | AGRICULTURE | ACCOUNTANT II                  | KLEINDIENST, ANGELA F | 14980.00      | 
| 2012          | AGRICULTURE | ACCOUNTANT II                  | WALKER, JOE E.        | 18775.00      | 
| 2012          | AGRICULTURE | ACCOUNTANT II                  | WOOD, KAREN M.        | 15540.00      | 
| 2012          | AGRICULTURE | ADMIN OFFICE SUPPORT ASSISTANT | BOUSE, NANCY LEE      | 13925.00      | 
| 2012          | AGRICULTURE | ADMIN OFFICE SUPPORT ASSISTANT | HEIMERICKS, RACHEL E. | 14435.00      | 
| 2012          | AGRICULTURE | ADMIN OFFICE SUPPORT ASSISTANT | KLIETHERMES, JEAN     | 13215.00      | 
| 2012          | AGRICULTURE | ADMIN OFFICE SUPPORT ASSISTANT | RUSSELL, BONNIE F     | 13215.00      | 
```