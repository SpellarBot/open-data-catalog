# Expenditures ESD Wallowa Fiscal Year 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/expenditures-esd-wallowa-fiscal-year-2012-f1c9e) |
| Metadata | [Link](https://data.oregon.gov/api/views/jjx9-z4vv) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/jjx9-z4vv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/jjx9-z4vv/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | jjx9-z4vv |
| Name | Expenditures ESD Wallowa Fiscal Year 2012 |
| Attribution | Region 18 ESD |
| Category | Education |
| Tags | expenditures, esd, wallowa, region 18, 2012 |
| Created | 2012-11-28T23:15:36Z |
| Publication Date | 2012-11-28T23:16:56Z |

## Description

Expenditures ESD Wallowa Fiscal Year 2012

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type | Render Type |
| ======== | ============== | ============ | ============ | ========= | =========== |
| Yes      | series tag     | esd          | ESD #        | text      | text        |
| Yes      | series tag     | esd_name     | ESD NAME     | text      | text        |
| Yes      | series tag     | fund_name    | FUND NAME    | text      | text        |
| Yes      | series tag     | compt_obj    | COMPT_OBJ    | text      | text        |
| Yes      | series tag     | vendor_state | VENDOR_STATE | text      | text        |
| Yes      | series tag     | vendor_name  | VENDOR_NAME  | text      | text        |
| Yes      | numeric metric | cash_expense | CASH_EXPENSE | money     | money       |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:jjx9-z4vv d:2012-01-01T00:00:00.000Z t:fund_name="100/General Fund" t:vendor_state=OR t:esd_name="Wallowa County ESD" t:compt_obj=1131-380 t:esd="ESD #18" t:vendor_name="JOSEPH SD #6" m:cash_expense=411236.84

series e:jjx9-z4vv d:2012-01-01T00:00:00.000Z t:fund_name="100/General Fund" t:vendor_state=OR t:esd_name="Wallowa County ESD" t:compt_obj=1131-380 t:esd="ESD #18" t:vendor_name="WALLOWA SD #12" m:cash_expense=371483.94

series e:jjx9-z4vv d:2012-01-01T00:00:00.000Z t:fund_name="100/General Fund" t:vendor_state=OR t:esd_name="Wallowa County ESD" t:compt_obj=1131-380 t:esd="ESD #18" t:vendor_name="ENTERPRISE SD #21" m:cash_expense=560789.97
```

## Meta Commands

```ls
metric m:cash_expense p:double l:CASH_EXPENSE t:dataTypeName=money

entity e:jjx9-z4vv l:"Expenditures  ESD  Wallowa  Fiscal Year 2012" t:attribution="Region 18 ESD" t:url=https://data.oregon.gov/api/views/jjx9-z4vv

property e:jjx9-z4vv t:meta.view v:id=jjx9-z4vv v:category=Education v:averageRating=0 v:name="Expenditures  ESD  Wallowa  Fiscal Year 2012" v:attribution="Region 18 ESD"

property e:jjx9-z4vv t:meta.view.license v:name="Public Domain"

property e:jjx9-z4vv t:meta.view.owner v:id=ku36-3r9m v:screenName="Wallowa ESD Region 18" v:displayName="Wallowa ESD Region 18"

property e:jjx9-z4vv t:meta.view.tableauthor v:id=ku36-3r9m v:screenName="Wallowa ESD Region 18" v:roleName=editor v:displayName="Wallowa ESD Region 18"
```

## Top Records

```ls
| esd     | esd_name           | fund_name        | compt_obj | vendor_state | vendor_name        | cash_expense | 
| ======= | ================== | ================ | ========= | ============ | ================== | ============ | 
| ESD #18 | Wallowa County ESD | 100/General Fund | 1131-380  | OR           | JOSEPH SD #6       | 411236.84    | 
| ESD #18 | Wallowa County ESD | 100/General Fund | 1131-380  | OR           | WALLOWA SD #12     | 371483.94    | 
| ESD #18 | Wallowa County ESD | 100/General Fund | 1131-380  | OR           | ENTERPRISE SD #21  | 560789.97    | 
| ESD #18 | Wallowa County ESD | 100/General Fund | 1131-380  | OR           | TROY SD #54        | 27278.71     | 
| ESD #18 | Wallowa County ESD | 100/General Fund | 1250-310  | OR           | FLINT STEARNS      | 4614.11      | 
| ESD #18 | Wallowa County ESD | 100/General Fund | 1250-310  | OR           | WALLOWA MEM. HOSP. | 520.29       | 
| ESD #18 | Wallowa County ESD | 100/General Fund | 1250-342  | OR           | SARALYN JOHNSON    | 658.79       | 
| ESD #18 | Wallowa County ESD | 100/General Fund | 1250-342  | OR           | DONNA KIRKMAN      | 527.09       | 
| ESD #18 | Wallowa County ESD | 100/General Fund | 1250-342  | OR           | LYNDA WINGO        | 372.96       | 
| ESD #18 | Wallowa County ESD | 100/General Fund | 1250-390  | OR           | DEPT. HUMAN SERV.  | 25313.22     | 
```