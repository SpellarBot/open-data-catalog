# 2016 State Employee Pay As Of COB June 30, 2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2016-state-employee-pay-as-of-cob-june-30-2016) |
| Metadata | [Link](https://data.mo.gov/api/views/fhka-4phk) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/fhka-4phk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/fhka-4phk/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | fhka-4phk |
| Name | 2016 State Employee Pay As Of COB June 30, 2016 |
| Attribution | Office of Administration |
| Category | Government Administration |
| Created | 2016-07-01T14:02:28Z |
| Publication Date | 2016-07-01T14:12:37Z |

## Description

Pay information for calendar year 2016 (January 1 - close of business December 31) for the employees of the State of Missouri by their Agency of Employment, Position Title or Employee Name

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
series e:fhka-4phk d:2016-01-01T00:00:00.000Z t:position_title="ACCOUNTANT I" t:agency_name=AGRICULTURE t:employee_name="ARNOLD, CAROL ANN" m:ytd_gross_pay=19464

series e:fhka-4phk d:2016-01-01T00:00:00.000Z t:position_title="ACCOUNTANT II" t:agency_name=AGRICULTURE t:employee_name="KLEINDIENST, ANGELA F" m:ytd_gross_pay=19645.5

series e:fhka-4phk d:2016-01-01T00:00:00.000Z t:position_title="ACCOUNTANT II" t:agency_name=AGRICULTURE t:employee_name="KLIETHERMES, DANA M" m:ytd_gross_pay=20970
```

## Meta Commands

```ls
metric m:ytd_gross_pay p:double l:"YTD Gross Pay" t:dataTypeName=money

entity e:fhka-4phk l:"2016 State Employee Pay As Of COB June 30, 2016" t:attribution="Office of Administration" t:url=https://data.mo.gov/api/views/fhka-4phk

property e:fhka-4phk t:meta.view v:id=fhka-4phk v:category="Government Administration" v:averageRating=0 v:name="2016 State Employee Pay As Of COB June 30, 2016" v:attribution="Office of Administration"

property e:fhka-4phk t:meta.view.owner v:id=4cdh-4my4 v:screenName=Dwight v:displayName=Dwight

property e:fhka-4phk t:meta.view.tableauthor v:id=4cdh-4my4 v:screenName=Dwight v:roleName=editor v:displayName=Dwight
```

## Top Records

```ls
| calendar_year | agency_name | position_title                 | employee_name               | ytd_gross_pay | 
| ============= | =========== | ============================== | =========================== | ============= | 
| 2016          | AGRICULTURE | ACCOUNTANT I                   | ARNOLD, CAROL ANN           | 19464         | 
| 2016          | AGRICULTURE | ACCOUNTANT II                  | KLEINDIENST, ANGELA F       | 19645.5       | 
| 2016          | AGRICULTURE | ACCOUNTANT II                  | KLIETHERMES, DANA M         | 20970         | 
| 2016          | AGRICULTURE | ACCOUNTANT II                  | WALKER, JOE E.              | 23466         | 
| 2016          | AGRICULTURE | ACCOUNTANT II                  | WOOD, KAREN M.              | 20190         | 
| 2016          | AGRICULTURE | ADMIN OFFICE SUPPORT ASSISTANT | ADKINS, LINDA J             | 16314         | 
| 2016          | AGRICULTURE | ADMIN OFFICE SUPPORT ASSISTANT | BISHOP, TAMMIE L.           | 16314         | 
| 2016          | AGRICULTURE | ADMIN OFFICE SUPPORT ASSISTANT | BOUSE, NANCY LEE            | 18102         | 
| 2016          | AGRICULTURE | ADMIN OFFICE SUPPORT ASSISTANT | DEAL, KIMBERLY K.           | 16314         | 
| 2016          | AGRICULTURE | ADMIN OFFICE SUPPORT ASSISTANT | FREDERICK, ANASTACIA NICOLE | 16314         | 
```