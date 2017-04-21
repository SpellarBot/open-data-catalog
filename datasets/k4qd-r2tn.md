# 2009 State Employee Pay

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2009-state-employee-pay-bc968) |
| Metadata | [Link](https://data.mo.gov/api/views/k4qd-r2tn) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/k4qd-r2tn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/k4qd-r2tn/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | k4qd-r2tn |
| Name | 2009 State Employee Pay |
| Attribution | Office of Administration |
| Category | Government |
| Created | 2012-05-15T16:54:31Z |
| Publication Date | 2012-05-15T17:00:16Z |

## Description

Pay information for calendar year 2009 for the employees of the State of Missouri by their Agency of Employment, Position Title or Employee Name.

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
series e:k4qd-r2tn d:2009-01-01T00:00:00.000Z t:position_title="ACCOUNT CLERK II" t:agency_name=AGRICULTURE t:employee_name="PHILLIPS, ROBERT T." m:ytd_gross_pay=26115

series e:k4qd-r2tn d:2009-01-01T00:00:00.000Z t:position_title="ACCOUNT CLERK II" t:agency_name=AGRICULTURE t:employee_name="VANHOOSER, BARBARA J" m:ytd_gross_pay=14681

series e:k4qd-r2tn d:2009-01-01T00:00:00.000Z t:position_title="ACCOUNTANT I" t:agency_name=AGRICULTURE t:employee_name="ARNOLD, CAROL ANN" m:ytd_gross_pay=33487.29
```

## Meta Commands

```ls
metric m:ytd_gross_pay p:double l:"YTD Gross Pay" t:dataTypeName=money

entity e:k4qd-r2tn l:"2009 State Employee Pay" t:attribution="Office of Administration" t:url=https://data.mo.gov/api/views/k4qd-r2tn

property e:k4qd-r2tn t:meta.view v:id=k4qd-r2tn v:category=Government v:attributionLink=http://www.mapyourtaxes.mo.gov v:averageRating=0 v:name="2009 State Employee Pay" v:attribution="Office of Administration"

property e:k4qd-r2tn t:meta.view.owner v:id=29n3-s86h v:screenName="Carolyn Aggeler" v:displayName="Carolyn Aggeler"

property e:k4qd-r2tn t:meta.view.tableauthor v:id=29n3-s86h v:screenName="Carolyn Aggeler" v:roleName=editor v:displayName="Carolyn Aggeler"
```

## Top Records

```ls
| calendar_year | agency_name | position_title                 | employee_name            | ytd_gross_pay | 
| ============= | =========== | ============================== | ======================== | ============= | 
| 2009          | AGRICULTURE | ACCOUNT CLERK II               | PHILLIPS, ROBERT T.      | 26115.00      | 
| 2009          | AGRICULTURE | ACCOUNT CLERK II               | VANHOOSER, BARBARA J     | 14681.00      | 
| 2009          | AGRICULTURE | ACCOUNTANT I                   | ARNOLD, CAROL ANN        | 33487.29      | 
| 2009          | AGRICULTURE | ACCOUNTANT II                  | KLIETHERMES, DANA M      | 37968.00      | 
| 2009          | AGRICULTURE | ACCOUNTANT II                  | WALKER, JOE E.           | 45130.21      | 
| 2009          | AGRICULTURE | ACCOUNTANT II                  | WOOD, KAREN M.           | 37296.00      | 
| 2009          | AGRICULTURE | ADMIN OFFICE SUPPORT ASSISTANT | BOUSE, NANCY LEE         | 33420.00      | 
| 2009          | AGRICULTURE | ADMIN OFFICE SUPPORT ASSISTANT | HAGENHOFF, JACQUELINE A. | 21177.67      | 
| 2009          | AGRICULTURE | ADMIN OFFICE SUPPORT ASSISTANT | KEMPKER, PATRICIA M.     | 29040.00      | 
| 2009          | AGRICULTURE | ADMIN OFFICE SUPPORT ASSISTANT | KLEINDIENST, ANGELA F    | 30624.00      | 
```