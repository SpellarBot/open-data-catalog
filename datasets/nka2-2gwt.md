# 2012 State Employee Pay As Of COB July 31, 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2012-state-employee-pay-as-of-cob-july-31-2012-fe807) |
| Metadata | [Link](https://data.mo.gov/api/views/nka2-2gwt) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/nka2-2gwt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/nka2-2gwt/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | nka2-2gwt |
| Name | 2012 State Employee Pay As Of COB July 31, 2012 |
| Attribution | Office of Administration |
| Category | Government |
| Created | 2012-08-07T16:03:19Z |
| Publication Date | 2012-08-07T16:07:59Z |

## Description

Pay information for calendar year 2012 (Januray 1 - close of business July 31) for the employees of the State of Missouri by their Agency of Employment, Position Title or Employee Name.

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
series e:nka2-2gwt d:2012-01-01T00:00:00.000Z t:position_title="ACCOUNT CLERK II" t:agency_name=AGRICULTURE t:employee_name="PHILLIPS, ROBERT T." m:ytd_gross_pay=16663

series e:nka2-2gwt d:2012-01-01T00:00:00.000Z t:position_title="ACCOUNTANT I" t:agency_name=AGRICULTURE t:employee_name="ARNOLD, CAROL ANN" m:ytd_gross_pay=19983

series e:nka2-2gwt d:2012-01-01T00:00:00.000Z t:position_title="ACCOUNTANT II" t:agency_name=AGRICULTURE t:employee_name="BENNETT, SUSAN S." m:ytd_gross_pay=21002
```

## Meta Commands

```ls
metric m:ytd_gross_pay p:double l:"YTD Gross Pay" t:dataTypeName=money

entity e:nka2-2gwt l:"2012 State Employee Pay As Of COB July 31, 2012" t:attribution="Office of Administration" t:url=https://data.mo.gov/api/views/nka2-2gwt

property e:nka2-2gwt t:meta.view v:id=nka2-2gwt v:category=Government v:averageRating=0 v:name="2012 State Employee Pay As Of COB July 31, 2012" v:attribution="Office of Administration"

property e:nka2-2gwt t:meta.view.owner v:id=wzcj-jrcg v:screenName=John v:displayName=John

property e:nka2-2gwt t:meta.view.tableauthor v:id=wzcj-jrcg v:screenName=John v:roleName=editor v:displayName=John
```

## Top Records

```ls
| calendar_year | agency_name | position_title                 | employee_name         | ytd_gross_pay | 
| ============= | =========== | ============================== | ===================== | ============= | 
| 2012          | AGRICULTURE | ACCOUNT CLERK II               | PHILLIPS, ROBERT T.   | 16663         | 
| 2012          | AGRICULTURE | ACCOUNTANT I                   | ARNOLD, CAROL ANN     | 19983         | 
| 2012          | AGRICULTURE | ACCOUNTANT II                  | BENNETT, SUSAN S.     | 21002         | 
| 2012          | AGRICULTURE | ACCOUNTANT II                  | KLEINDIENST, ANGELA F | 21002         | 
| 2012          | AGRICULTURE | ACCOUNTANT II                  | KLIETHERMES, DANA M   | 1645          | 
| 2012          | AGRICULTURE | ACCOUNTANT II                  | WALKER, JOE E.        | 26322.5       | 
| 2012          | AGRICULTURE | ACCOUNTANT II                  | WOOD, KAREN M.        | 17120.90      | 
| 2012          | AGRICULTURE | ADMIN OFFICE SUPPORT ASSISTANT | BOUSE, NANCY LEE      | 19677         | 
| 2012          | AGRICULTURE | ADMIN OFFICE SUPPORT ASSISTANT | HEIMERICKS, RACHEL E. | 20238         | 
| 2012          | AGRICULTURE | ADMIN OFFICE SUPPORT ASSISTANT | KLIETHERMES, JEAN     | 18527.5       | 
```