# IHDA - Illinois Housing Dev Auth - FY2011 MultiFamily Rental Activity

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ihda-illinois-housing-dev-auth-fy2011-multifamily-rental-activity-1d30f) |
| Metadata | [Link](https://data.illinois.gov/api/views/r5cp-54ty) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/r5cp-54ty/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/r5cp-54ty/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | r5cp-54ty |
| Name | IHDA - Illinois Housing Dev Auth - FY2011 MultiFamily Rental Activity |
| Category | Housing |
| Tags | ihda, illinois housing development authority |
| Created | 2011-11-21T21:00:10Z |
| Publication Date | 2011-12-02T17:23:25Z |

## Description

FY2011 MultiFamily Rental Activity

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type | Render Type |
| ======== | ============== | ====================== | ====================== | ========= | =========== |
| Yes      | series tag     | development_name       | DEVELOPMENT NAME       | text      | text        |
| Yes      | series tag     | city                   | CITY                   | text      | text        |
| Yes      | series tag     | county                 | COUNTY                 | text      | text        |
| Yes      | time           | board_date             | BOARD DATE             | text      | text        |
| Yes      | numeric metric | total_units            | TOTAL UNITS            | number    | number      |
| Yes      | series tag     | tenant_type            | TENANT TYPE            | text      | text        |
| Yes      | numeric metric | total_ihda_dollars     | TOTAL IHDA DOLLARS     | money     | money       |
| Yes      | numeric metric | leveraged_dollars      | LEVERAGED DOLLARS      | money     | money       |
| Yes      | numeric metric | total_project_cost     | TOTAL PROJECT COST     | money     | money       |
| Yes      | numeric metric | rental_housing_support | RENTAL HOUSING SUPPORT | money     | money       |
| No       |                | fiscal_year            | FISCAL YEAR            | number    | text        |
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
series e:r5cp-54ty d:2011-04-15T00:00:00.000Z t:tenant_type=FAMILY t:county=COOK t:development_name="PARKWAY GARDENS HOMES" t:city=CHICAGO m:total_project_cost=104910458 m:leveraged_dollars=13278354 m:rental_housing_support=0 m:total_ihda_dollars=91632104 m:total_units=694

series e:r5cp-54ty d:2010-08-19T00:00:00.000Z t:tenant_type=FAMILY t:county=COOK t:development_name="COURTS OF CICERO II" t:city=CICERO m:total_project_cost=5998600 m:leveraged_dollars=110500 m:rental_housing_support=0 m:total_ihda_dollars=5888100 m:total_units=54

series e:r5cp-54ty d:2010-09-17T00:00:00.000Z t:tenant_type=FAMILY t:county=KANKAKEE t:development_name="CRESTVIEW VILLAGE APTS." t:city=KANKAKEE m:total_project_cost=2805236 m:leveraged_dollars=250000 m:rental_housing_support=0 m:total_ihda_dollars=2555236 m:total_units=132
```

## Meta Commands

```ls
metric m:total_units p:integer l:"TOTAL UNITS" t:dataTypeName=number

metric m:total_ihda_dollars p:integer l:"TOTAL IHDA DOLLARS" t:dataTypeName=money

metric m:leveraged_dollars p:integer l:"LEVERAGED DOLLARS" t:dataTypeName=money

metric m:total_project_cost p:integer l:"TOTAL PROJECT COST" t:dataTypeName=money

metric m:rental_housing_support p:integer l:"RENTAL HOUSING SUPPORT" t:dataTypeName=money

entity e:r5cp-54ty l:"IHDA - Illinois Housing Dev Auth - FY2011 MultiFamily Rental Activity" t:url=https://data.illinois.gov/api/views/r5cp-54ty

property e:r5cp-54ty t:meta.view v:id=r5cp-54ty v:category=Housing v:averageRating=0 v:name="IHDA - Illinois Housing Dev Auth - FY2011 MultiFamily Rental Activity"

property e:r5cp-54ty t:meta.view.owner v:id=i46z-zq8e v:screenName="Larry Michalski" v:displayName="Larry Michalski"

property e:r5cp-54ty t:meta.view.tableauthor v:id=i46z-zq8e v:screenName="Larry Michalski" v:roleName=publisher v:displayName="Larry Michalski"
```

## Top Records

```ls
| development_name        | city         | county      | board_date | total_units | tenant_type | total_ihda_dollars | leveraged_dollars | total_project_cost | rental_housing_support | fiscal_year | 
| ======================= | ============ | =========== | ========== | =========== | =========== | ================== | ================= | ================== | ====================== | =========== | 
| PARKWAY GARDENS HOMES   | CHICAGO      | COOK        | 20110415   | 694         | FAMILY      | 91632104           | 13278354          | 104910458          | 0                      | 2011        | 
| COURTS OF CICERO II     | CICERO       | COOK        | 20100819   | 54          | FAMILY      | 5888100            | 110500            | 5998600            | 0                      | 2011        | 
| CRESTVIEW VILLAGE APTS. | KANKAKEE     | KANKAKEE    | 20100917   | 132         | FAMILY      | 2555236            | 250000            | 2805236            | 0                      | 2011        | 
| PARK APTS.              | CHICAGO      | COOK        | 20100802   | 120         | FAMILY      | 13190272           | 331331            | 13521603           | 0                      | 2011        | 
| FAIRVIEW RIDGE APTS.    | NORMAL       | MCLEAN      | 20100917   | 136         | FAMILY      | 4720000            | 3795309           | 8515309            | 0                      | 2011        | 
| RIVER RUN               | MACOMB       | MCDONOUGH   | 20100917   | 100         | FAMILY      | 4800000            | 1662028           | 6462028            | 0                      | 2011        | 
| TOWN AND COUNTRY        | GRANITE CITY | MADISON     | 20100802   | 121         | FAMILY      | 10652182           | 238491            | 10890673           | 0                      | 2011        | 
| PORT BYRON HEIGHTS      | PORT BYRON   | ROCK ISLAND | 20100917   | 72          | FAMILY      | 4221717            | 3226988           | 7448705            | 0                      | 2011        | 
| CARLINVILLE APTS        | CARLINVILLE  | MACOUPIN    | 20100917   | 20          | FAMILY      | 1228379            | 537496            | 1765875            | 0                      | 2011        | 
| WESTWIND TOWER          | ELGIN        | KANE        | 20100917   | 150         | ELDERLY     | 2520000            | 3124950           | 5644950            | 0                      | 2011        | 
```