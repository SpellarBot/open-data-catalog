# 2014 State Employee Pay As Of COB June 30, 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2014-state-employee-pay-as-of-cob-june-30-2014-7129a) |
| Metadata | [Link](https://data.mo.gov/api/views/9mgj-s7gs) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/9mgj-s7gs/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/9mgj-s7gs/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | 9mgj-s7gs |
| Name | 2014 State Employee Pay As Of COB June 30, 2014 |
| Category | Government Administration |
| Created | 2014-07-02T18:51:35Z |
| Publication Date | 2014-07-02T19:01:35Z |

## Description

Pay information for calendar year 2014(January 1 - close of business December 31) for the employees of the State of Missouri by their Agency of Employment, Position Title or Employee Name.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| Yes      | time           | calendar_year  | Calendar Year  | number    | text        |
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
series e:9mgj-s7gs d:2014-01-01T00:00:00.000Z t:position_title="ACCOUNT CLERK II" t:agency_name=AGRICULTURE t:employee_name="PHILLIPS, ROBERT T." m:ytd_gross_pay=14781

series e:9mgj-s7gs d:2014-01-01T00:00:00.000Z t:position_title="ACCOUNTANT I" t:agency_name=AGRICULTURE t:employee_name="ARNOLD, CAROL ANN" m:ytd_gross_pay=17901

series e:9mgj-s7gs d:2014-01-01T00:00:00.000Z t:position_title="ACCOUNTANT II" t:agency_name=AGRICULTURE t:employee_name="KLEINDIENST, ANGELA F" m:ytd_gross_pay=18567
```

## Meta Commands

```ls
metric m:ytd_gross_pay p:double l:"YTD Gross Pay" t:dataTypeName=money

entity e:9mgj-s7gs l:"2014 State Employee Pay As Of COB June 30, 2014" t:url=https://data.mo.gov/api/views/9mgj-s7gs

property e:9mgj-s7gs t:meta.view v:id=9mgj-s7gs v:category="Government Administration" v:averageRating=0 v:name="2014 State Employee Pay As Of COB June 30, 2014"

property e:9mgj-s7gs t:meta.view.owner v:id=4cdh-4my4 v:screenName=Dwight v:displayName=Dwight

property e:9mgj-s7gs t:meta.view.tableauthor v:id=4cdh-4my4 v:screenName=Dwight v:roleName=editor v:displayName=Dwight
```

## Top Records

```ls
| calendar_year | agency_name | position_title                 | employee_name         | ytd_gross_pay | 
| ============= | =========== | ============================== | ===================== | ============= | 
| 2014          | AGRICULTURE | ACCOUNT CLERK II               | PHILLIPS, ROBERT T.   | 14781.00      | 
| 2014          | AGRICULTURE | ACCOUNTANT I                   | ARNOLD, CAROL ANN     | 17901.00      | 
| 2014          | AGRICULTURE | ACCOUNTANT II                  | KLEINDIENST, ANGELA F | 18567.00      | 
| 2014          | AGRICULTURE | ACCOUNTANT II                  | KLIETHERMES, DANA M   | 19971.00      | 
| 2014          | AGRICULTURE | ACCOUNTANT II                  | WALKER, JOE E.        | 23211.01      | 
| 2014          | AGRICULTURE | ACCOUNTANT II                  | WOOD, KAREN M.        | 4818.00       | 
| 2014          | AGRICULTURE | ADMIN OFFICE SUPPORT ASSISTANT | BOUSE, NANCY LEE      | 17901.00      | 
| 2014          | AGRICULTURE | ADMIN OFFICE SUPPORT ASSISTANT | HEIMERICKS, RACHEL E. | 17901.00      | 
| 2014          | AGRICULTURE | ADMIN OFFICE SUPPORT ASSISTANT | HOLTSCLAW, EMILY JEAN | 16131.00      | 
| 2014          | AGRICULTURE | ADMIN OFFICE SUPPORT ASSISTANT | OTTO, KAYLA LYNN      | 16131.00      | 
```