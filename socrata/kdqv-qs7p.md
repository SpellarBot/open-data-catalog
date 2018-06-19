# LCR 90th percentile dataset

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/lcr-90th-percentile-dataset) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/kdqv-qs7p) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/kdqv-qs7p/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/kdqv-qs7p/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | kdqv-qs7p |
| Name | LCR 90th percentile dataset |
| Attribution | Department of Environmental Protection (DEP) |
| Category | Environment |
| Tags | lcr |
| Created | 2015-02-19T19:22:08Z |
| Publication Date | 2016-04-07T19:11:08Z |

## Description

At-the-tap LCR compliance 1st draw 90th percentile data.

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                     | Data Type     | Render Type   |
| ======== | ============== | ====================== | ======================== | ============= | ============= |
| Yes      | series tag     | kit_id                 | Kit ID                   | text          | number        |
| Yes      | series tag     | borough                | Borough                  | text          | text          |
| Yes      | series tag     | zipcode                | Zipcode                  | text          | number        |
| Yes      | time           | date_collected         | Date Collected           | calendar_date | calendar_date |
| Yes      | numeric metric | lead_first_draw_mg_l   | Lead First Draw (mg/L)   | number        | number        |
| Yes      | numeric metric | copper_first_draw_mg_l | Copper First Draw (mg/L) | number        | number        |
```

## Time Field

```ls
Value = date_collected
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:kdqv-qs7p d:2014-06-16T00:00:00.000Z t:kit_id=1410001 t:zipcode=11378 t:borough=Queens m:copper_first_draw_mg_l=0.114 m:lead_first_draw_mg_l=0.008

series e:kdqv-qs7p d:2014-06-16T00:00:00.000Z t:kit_id=1410002 t:zipcode=11354 t:borough=Queens m:copper_first_draw_mg_l=0.134 m:lead_first_draw_mg_l=0.014

series e:kdqv-qs7p d:2014-06-10T00:00:00.000Z t:kit_id=1410004 t:zipcode=11223 t:borough=Brooklyn m:copper_first_draw_mg_l=0.126 m:lead_first_draw_mg_l=0.009
```

## Meta Commands

```ls
metric m:lead_first_draw_mg_l p:double l:"Lead First Draw (mg/L)" t:dataTypeName=number

metric m:copper_first_draw_mg_l p:float l:"Copper First Draw (mg/L)" t:dataTypeName=number

entity e:kdqv-qs7p l:"LCR 90th percentile dataset" t:attribution="Department of Environmental Protection (DEP)" t:url=https://data.cityofnewyork.us/api/views/kdqv-qs7p

property e:kdqv-qs7p t:meta.view v:id=kdqv-qs7p v:category=Environment v:averageRating=0 v:name="LCR 90th percentile dataset" v:attribution="Department of Environmental Protection (DEP)"

property e:kdqv-qs7p t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:kdqv-qs7p t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| kit_id  | borough       | zipcode | date_collected      | lead_first_draw_mg_l | copper_first_draw_mg_l | 
| ======= | ============= | ======= | =================== | ==================== | ====================== | 
| 1410001 | Queens        | 11378   | 2014-06-16T00:00:00 | 0.008                | 0.114                  | 
| 1410002 | Queens        | 11354   | 2014-06-16T00:00:00 | 0.014                | 0.134                  | 
| 1410004 | Brooklyn      | 11223   | 2014-06-10T00:00:00 | 0.009                | 0.126                  | 
| 1410005 | Brooklyn      | 11215   | 2014-06-12T00:00:00 | 0.005                | 0.153                  | 
| 1410006 | Queens        | 11361   | 2014-06-08T00:00:00 | 0.002                | 0.203                  | 
| 1410007 | New York      | 10010   | 2014-06-07T00:00:00 | 0.000                | 0.143                  | 
| 1410008 | Staten Island | 10308   | 2014-06-09T00:00:00 | 0.001                | 0.113                  | 
| 1410009 | Staten Island | 10306   | 2014-06-16T00:00:00 | 0.000                | 0.082                  | 
| 1410010 | Brooklyn      | 11224   | 2014-06-13T00:00:00 | 0.000                | 0.136                  | 
| 1410011 | Bronx         | 10457   | 2014-06-09T00:00:00 | 0.000                | 0.156                  | 
```