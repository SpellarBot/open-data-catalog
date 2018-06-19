# 2010 State Employee Pay

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2010-state-employee-pay-e1342) |
| Metadata | [Link](https://data.mo.gov/api/views/wij9-qu7c) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/wij9-qu7c/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/wij9-qu7c/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | wij9-qu7c |
| Name | 2010 State Employee Pay |
| Attribution | Office of Administration |
| Category | Government |
| Created | 2012-05-15T17:03:25Z |
| Publication Date | 2012-05-15T17:06:34Z |

## Description

Pay information for calendar year 2010 for the employees of the State of Missouri by their Agency of Employment, Position Title or Employee Name.

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
series e:wij9-qu7c d:2010-01-01T00:00:00.000Z t:position_title="ACCOUNT CLERK II" t:agency_name=AGRICULTURE t:employee_name="PHILLIPS, ROBERT T." m:ytd_gross_pay=26640

series e:wij9-qu7c d:2010-01-01T00:00:00.000Z t:position_title="ACCOUNTANT I" t:agency_name=AGRICULTURE t:employee_name="ARNOLD, CAROL ANN" m:ytd_gross_pay=33420

series e:wij9-qu7c d:2010-01-01T00:00:00.000Z t:position_title="ACCOUNTANT II" t:agency_name=AGRICULTURE t:employee_name="KLEINDIENST, ANGELA F" m:ytd_gross_pay=19474
```

## Meta Commands

```ls
metric m:ytd_gross_pay p:double l:"YTD Gross Pay" t:dataTypeName=money

entity e:wij9-qu7c l:"2010 State Employee Pay" t:attribution="Office of Administration" t:url=https://data.mo.gov/api/views/wij9-qu7c

property e:wij9-qu7c t:meta.view v:id=wij9-qu7c v:category=Government v:attributionLink=http://mapyourtaxes.mo.gov v:averageRating=0 v:name="2010 State Employee Pay" v:attribution="Office of Administration"

property e:wij9-qu7c t:meta.view.owner v:id=29n3-s86h v:screenName="Carolyn Aggeler" v:displayName="Carolyn Aggeler"

property e:wij9-qu7c t:meta.view.tableauthor v:id=29n3-s86h v:screenName="Carolyn Aggeler" v:roleName=editor v:displayName="Carolyn Aggeler"
```

## Top Records

```ls
| calendar_year | agency_name | position_title                 | employee_name         | ytd_gross_pay | 
| ============= | =========== | ============================== | ===================== | ============= | 
| 2010          | AGRICULTURE | ACCOUNT CLERK II               | PHILLIPS, ROBERT T.   | 26640.00      | 
| 2010          | AGRICULTURE | ACCOUNTANT I                   | ARNOLD, CAROL ANN     | 33420.00      | 
| 2010          | AGRICULTURE | ACCOUNTANT II                  | KLEINDIENST, ANGELA F | 19474.00      | 
| 2010          | AGRICULTURE | ACCOUNTANT II                  | KLIETHERMES, DANA M   | 15820.00      | 
| 2010          | AGRICULTURE | ACCOUNTANT II                  | WALKER, JOE E.        | 45060.00      | 
| 2010          | AGRICULTURE | ACCOUNTANT II                  | WOOD, KAREN M.        | 37296.00      | 
| 2010          | AGRICULTURE | ADMIN OFFICE SUPPORT ASSISTANT | BOUSE, NANCY LEE      | 33420.00      | 
| 2010          | AGRICULTURE | ADMIN OFFICE SUPPORT ASSISTANT | KEMPKER, PATRICIA M.  | 29039.99      | 
| 2010          | AGRICULTURE | ADMIN OFFICE SUPPORT ASSISTANT | KLEINDIENST, ANGELA F | 14036.00      | 
| 2010          | AGRICULTURE | ADMIN OFFICE SUPPORT ASSISTANT | KLIETHERMES, JEAN     | 31176.00      | 
```