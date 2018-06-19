# IHDA - Illinois Housing Dev Auth - FY2011 Technical Assistance

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ihda-illinois-housing-dev-auth-fy2011-technical-assistance-af303) |
| Metadata | [Link](https://data.illinois.gov/api/views/gzwh-nakt) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/gzwh-nakt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/gzwh-nakt/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | gzwh-nakt |
| Name | IHDA - Illinois Housing Dev Auth - FY2011 Technical Assistance |
| Category | Housing |
| Tags | ihda, illinois housing development authority |
| Created | 2011-11-21T21:37:16Z |
| Publication Date | 2011-12-02T17:36:31Z |

## Description

FY2011 Technical Assistance

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| Yes      | series tag     | development_name   | DEVELOPMENT NAME   | text      | text        |
| Yes      | series tag     | city               | CITY               | text      | text        |
| Yes      | series tag     | county             | COUNTY             | text      | text        |
| Yes      | time           | board_date         | BOARD DATE         | text      | text        |
| Yes      | numeric metric | total_units        | TOTAL UNITS        | number    | number      |
| Yes      | series tag     | tenant_type        | TENANT TYPE        | text      | text        |
| Yes      | numeric metric | total_ihda_dollars | TOTAL IHDA DOLLARS | money     | money       |
| Yes      | numeric metric | leveraged_dollars  | LEVERAGED DOLLARS  | money     | money       |
| Yes      | numeric metric | total_project_cost | TOTAL PROJECT COST | money     | money       |
| No       |                | fiscal_year        | FISCAL YEAR        | number    | text        |
```

## Time Field

```ls
Value = board_date
Format & Zone = yyyyMMdd
```

## Series Fields

```ls
Excluded Fields = fiscal_year
```

## Data Commands

```ls
series e:gzwh-nakt d:2010-10-15T00:00:00.000Z t:tenant_type=FAMILY t:county=COOK t:development_name="HOMES FOR A CHANGING REGION" t:city=CHICAGO m:total_project_cost=314029 m:leveraged_dollars=175000 m:total_ihda_dollars=139029 m:total_units=0

series e:gzwh-nakt d:2011-04-15T00:00:00.000Z t:tenant_type=FAMILY t:county=COOK t:development_name="COOK COUNTY FORECLOSURE MEDIATION PROGRAM" t:city="MULTIPLE CITIES" m:total_project_cost=400000 m:leveraged_dollars=0 m:total_ihda_dollars=400000 m:total_units=0
```

## Meta Commands

```ls
metric m:total_units p:integer l:"TOTAL UNITS" t:dataTypeName=number

metric m:total_ihda_dollars p:integer l:"TOTAL IHDA DOLLARS" t:dataTypeName=money

metric m:leveraged_dollars p:integer l:"LEVERAGED DOLLARS" t:dataTypeName=money

metric m:total_project_cost p:integer l:"TOTAL PROJECT COST" t:dataTypeName=money

entity e:gzwh-nakt l:"IHDA - Illinois Housing Dev Auth - FY2011 Technical Assistance" t:url=https://data.illinois.gov/api/views/gzwh-nakt

property e:gzwh-nakt t:meta.view v:id=gzwh-nakt v:category=Housing v:averageRating=0 v:name="IHDA - Illinois Housing Dev Auth - FY2011 Technical Assistance"

property e:gzwh-nakt t:meta.view.owner v:id=i46z-zq8e v:screenName="Larry Michalski" v:displayName="Larry Michalski"

property e:gzwh-nakt t:meta.view.tableauthor v:id=i46z-zq8e v:screenName="Larry Michalski" v:roleName=publisher v:displayName="Larry Michalski"
```

## Top Records

```ls
| development_name                          | city            | county | board_date | total_units | tenant_type | total_ihda_dollars | leveraged_dollars | total_project_cost | fiscal_year | 
| ========================================= | =============== | ====== | ========== | =========== | =========== | ================== | ================= | ================== | =========== | 
| HOMES FOR A CHANGING REGION               | CHICAGO         | COOK   | 20101015   | 0           | FAMILY      | 139029             | 175000            | 314029             | 2011        | 
| COOK COUNTY FORECLOSURE MEDIATION PROGRAM | MULTIPLE CITIES | COOK   | 20110415   | 0           | FAMILY      | 400000             | 0                 | 400000             | 2011        | 
```