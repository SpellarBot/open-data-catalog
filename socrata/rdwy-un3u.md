# 2007 State Employee Pay

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2007-state-employee-pay-c99f3) |
| Metadata | [Link](https://data.mo.gov/api/views/rdwy-un3u) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/rdwy-un3u/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/rdwy-un3u/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | rdwy-un3u |
| Name | 2007 State Employee Pay |
| Attribution | Office of Administration |
| Category | Government |
| Created | 2012-05-15T15:50:57Z |
| Publication Date | 2012-05-15T16:38:31Z |

## Description

Pay Information for calendar year 2007 for the employees of the State of Missouri by their Agency of employment, Position Title or Employee name.

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
series e:rdwy-un3u d:2007-01-01T00:00:00.000Z t:position_title="ACCOUNT CLERK II" t:agency_name=AGRICULTURE t:employee_name="FRANKEN, RITA I." m:ytd_gross_pay=6994.16

series e:rdwy-un3u d:2007-01-01T00:00:00.000Z t:position_title="ACCOUNT CLERK II" t:agency_name=AGRICULTURE t:employee_name="PHILLIPS, ROBERT T." m:ytd_gross_pay=24647.5

series e:rdwy-un3u d:2007-01-01T00:00:00.000Z t:position_title="ACCOUNT CLERK II" t:agency_name=AGRICULTURE t:employee_name="VANHOOSER, BARBARA J" m:ytd_gross_pay=19753.19
```

## Meta Commands

```ls
metric m:ytd_gross_pay p:double l:"YTD Gross Pay" t:dataTypeName=money

entity e:rdwy-un3u l:"2007 State Employee Pay" t:attribution="Office of Administration" t:url=https://data.mo.gov/api/views/rdwy-un3u

property e:rdwy-un3u t:meta.view v:id=rdwy-un3u v:category=Government v:attributionLink=http://www.mapyourtaxes.mo.gov v:averageRating=0 v:name="2007 State Employee Pay" v:attribution="Office of Administration"

property e:rdwy-un3u t:meta.view.owner v:id=29n3-s86h v:screenName="Carolyn Aggeler" v:displayName="Carolyn Aggeler"

property e:rdwy-un3u t:meta.view.tableauthor v:id=29n3-s86h v:screenName="Carolyn Aggeler" v:roleName=editor v:displayName="Carolyn Aggeler"
```

## Top Records

```ls
| calendar_year | agency_name | position_title                 | employee_name            | ytd_gross_pay | 
| ============= | =========== | ============================== | ======================== | ============= | 
| 2007          | AGRICULTURE | ACCOUNT CLERK II               | FRANKEN, RITA I.         | 6994.16       | 
| 2007          | AGRICULTURE | ACCOUNT CLERK II               | PHILLIPS, ROBERT T.      | 24647.50      | 
| 2007          | AGRICULTURE | ACCOUNT CLERK II               | VANHOOSER, BARBARA J     | 19753.19      | 
| 2007          | AGRICULTURE | ACCOUNTANT I                   | ARNOLD, CAROL ANN        | 31934.50      | 
| 2007          | AGRICULTURE | ACCOUNTANT II                  | KLIETHERMES, DANA M      | 36285.50      | 
| 2007          | AGRICULTURE | ACCOUNTANT II                  | WALKER, JOE E.           | 43063.00      | 
| 2007          | AGRICULTURE | ACCOUNTANT II                  | WOOD, KAREN M.           | 35632.00      | 
| 2007          | AGRICULTURE | ADMIN OFFICE SUPPORT ASSISTANT | BOUSE, NANCY LEE         | 33955.05      | 
| 2007          | AGRICULTURE | ADMIN OFFICE SUPPORT ASSISTANT | HAGENHOFF, JACQUELINE A. | 28261.00      | 
| 2007          | AGRICULTURE | ADMIN OFFICE SUPPORT ASSISTANT | KEMPKER, PATRICIA M.     | 27758.00      | 
```