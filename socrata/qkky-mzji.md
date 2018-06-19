# 2011 State Employee Pay

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2011-state-employee-pay-2ce0e) |
| Metadata | [Link](https://data.mo.gov/api/views/qkky-mzji) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/qkky-mzji/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/qkky-mzji/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | qkky-mzji |
| Name | 2011 State Employee Pay |
| Attribution | Office of Administration |
| Category | Government |
| Created | 2012-05-15T17:08:28Z |
| Publication Date | 2012-05-15T17:12:58Z |

## Description

Pay information for calendar year 2011 for the employees of the State of Missouri by their Agency of Employment, Position Title or Employee Name.

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
series e:qkky-mzji d:2011-01-01T00:00:00.000Z t:position_title="ACCOUNT CLERK II" t:agency_name=AGRICULTURE t:employee_name="PHILLIPS, ROBERT T." m:ytd_gross_pay=26718.5

series e:qkky-mzji d:2011-01-01T00:00:00.000Z t:position_title="ACCOUNTANT I" t:agency_name=AGRICULTURE t:employee_name="ARNOLD, CAROL ANN" m:ytd_gross_pay=33420

series e:qkky-mzji d:2011-01-01T00:00:00.000Z t:position_title="ACCOUNTANT II" t:agency_name=AGRICULTURE t:employee_name="BENNETT, SUSAN S." m:ytd_gross_pay=16478
```

## Meta Commands

```ls
metric m:ytd_gross_pay p:double l:"YTD Gross Pay" t:dataTypeName=money

entity e:qkky-mzji l:"2011 State Employee Pay" t:attribution="Office of Administration" t:url=https://data.mo.gov/api/views/qkky-mzji

property e:qkky-mzji t:meta.view v:id=qkky-mzji v:category=Government v:attributionLink=http://www.mapyourtaxes.mo.gov v:averageRating=0 v:name="2011 State Employee Pay" v:attribution="Office of Administration"

property e:qkky-mzji t:meta.view.owner v:id=29n3-s86h v:screenName="Carolyn Aggeler" v:displayName="Carolyn Aggeler"

property e:qkky-mzji t:meta.view.tableauthor v:id=29n3-s86h v:screenName="Carolyn Aggeler" v:roleName=editor v:displayName="Carolyn Aggeler"
```

## Top Records

```ls
| calendar_year | agency_name | position_title                 | employee_name         | ytd_gross_pay | 
| ============= | =========== | ============================== | ===================== | ============= | 
| 2011          | AGRICULTURE | ACCOUNT CLERK II               | PHILLIPS, ROBERT T.   | 26718.50      | 
| 2011          | AGRICULTURE | ACCOUNTANT I                   | ARNOLD, CAROL ANN     | 33420.00      | 
| 2011          | AGRICULTURE | ACCOUNTANT II                  | BENNETT, SUSAN S.     | 16478.00      | 
| 2011          | AGRICULTURE | ACCOUNTANT II                  | KLEINDIENST, ANGELA F | 35952.00      | 
| 2011          | AGRICULTURE | ACCOUNTANT II                  | WALKER, JOE E.        | 45060.00      | 
| 2011          | AGRICULTURE | ACCOUNTANT II                  | WOOD, KAREN M.        | 37296.02      | 
| 2011          | AGRICULTURE | ADMIN OFFICE SUPPORT ASSISTANT | BOUSE, NANCY LEE      | 33420.00      | 
| 2011          | AGRICULTURE | ADMIN OFFICE SUPPORT ASSISTANT | HEIMERICKS, RACHEL E. | 15878.50      | 
| 2011          | AGRICULTURE | ADMIN OFFICE SUPPORT ASSISTANT | KEMPKER, PATRICIA M.  | 20421.06      | 
| 2011          | AGRICULTURE | ADMIN OFFICE SUPPORT ASSISTANT | KLIETHERMES, JEAN     | 31198.50      | 
```