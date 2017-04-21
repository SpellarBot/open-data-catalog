# 2015 State Employee Pay As Of COB June 30, 2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2015-state-employee-pay-as-of-cob-june-30-2015) |
| Metadata | [Link](https://data.mo.gov/api/views/5fzr-99vz) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/5fzr-99vz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/5fzr-99vz/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | 5fzr-99vz |
| Name | 2015 State Employee Pay As Of COB June 30, 2015 |
| Category | Government Administration |
| Created | 2015-07-02T15:16:39Z |
| Publication Date | 2015-07-02T15:18:52Z |

## Description

Pay information for calendar year 2015(January 1 - close of business December 31) for the employees of the State of Missouri by their Agency of Employment, Position Title or Employee Name

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| Yes      | time           | calendar_year  | Calendar Year  | number    | text        |
| Yes      | series tag     | agency_name    | Agency Name    | text      | text        |
| Yes      | series tag     | position_title | Position Title | text      | text        |
| Yes      | series tag     | employee_name  | Employee Name  | text      | text        |
| Yes      | numeric metric | ytd_gross_pay  | YTD Gross Pay  | number    | number      |
```

## Time Field

```ls
Value = calendar_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:5fzr-99vz d:2015-01-01T00:00:00.000Z t:position_title="ACCOUNTANT I" t:agency_name=AGRICULTURE t:employee_name="ARNOLD, CAROL ANN" m:ytd_gross_pay=18087

series e:5fzr-99vz d:2015-01-01T00:00:00.000Z t:position_title="ACCOUNTANT II" t:agency_name=AGRICULTURE t:employee_name="KLEINDIENST, ANGELA F" m:ytd_gross_pay=18873.5

series e:5fzr-99vz d:2015-01-01T00:00:00.000Z t:position_title="ACCOUNTANT II" t:agency_name=AGRICULTURE t:employee_name="KLIETHERMES, DANA M" m:ytd_gross_pay=20303.5
```

## Meta Commands

```ls
metric m:ytd_gross_pay p:double l:"YTD Gross Pay" t:dataTypeName=number

entity e:5fzr-99vz l:"2015 State Employee Pay As Of COB June 30, 2015" t:url=https://data.mo.gov/api/views/5fzr-99vz

property e:5fzr-99vz t:meta.view v:id=5fzr-99vz v:category="Government Administration" v:averageRating=0 v:name="2015 State Employee Pay As Of COB June 30, 2015"

property e:5fzr-99vz t:meta.view.license v:name="Public Domain"

property e:5fzr-99vz t:meta.view.owner v:id=4cdh-4my4 v:screenName=Dwight v:displayName=Dwight

property e:5fzr-99vz t:meta.view.tableauthor v:id=4cdh-4my4 v:screenName=Dwight v:roleName=editor v:displayName=Dwight
```

## Top Records

```ls
| calendar_year | agency_name | position_title                 | employee_name         | ytd_gross_pay | 
| ============= | =========== | ============================== | ===================== | ============= | 
| 2015          | AGRICULTURE | ACCOUNTANT I                   | ARNOLD, CAROL ANN     | 18087         | 
| 2015          | AGRICULTURE | ACCOUNTANT II                  | KLEINDIENST, ANGELA F | 18873.5       | 
| 2015          | AGRICULTURE | ACCOUNTANT II                  | KLIETHERMES, DANA M   | 20303.5       | 
| 2015          | AGRICULTURE | ACCOUNTANT II                  | WALKER, JOE E.        | 23446.5       | 
| 2015          | AGRICULTURE | ACCOUNTANT II                  | WOOD, KAREN M.        | 19569         | 
| 2015          | AGRICULTURE | ADMIN OFFICE SUPPORT ASSISTANT | ADKINS, LINDA J       | 16300.5       | 
| 2015          | AGRICULTURE | ADMIN OFFICE SUPPORT ASSISTANT | BISHOP, TAMMIE L.     | 1359.5        | 
| 2015          | AGRICULTURE | ADMIN OFFICE SUPPORT ASSISTANT | BOUSE, NANCY LEE      | 18087         | 
| 2015          | AGRICULTURE | ADMIN OFFICE SUPPORT ASSISTANT | FORSYTHE, AMY D.      | 16300.5       | 
| 2015          | AGRICULTURE | ADMIN OFFICE SUPPORT ASSISTANT | HEIMERICKS, RACHEL E. | 18087         | 
```