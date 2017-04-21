# Transportation Fuels Production and Demand: Beginning 1993

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/transportation-fuels-production-and-demand-beginning-1993) |
| Metadata | [Link](https://data.ny.gov/api/views/atwy-2trf) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/atwy-2trf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/atwy-2trf/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | atwy-2trf |
| Name | Transportation Fuels Production and Demand: Beginning 1993 |
| Attribution | New York State Energy Research and Development Authority Performance Management and Evaluation Services Group |
| Category | Energy & Environment |
| Tags | gasoline, demand, production |
| Created | 2014-08-27T21:05:28Z |
| Publication Date | 2017-04-07T22:03:16Z |

## Description

Transportation Fuels Production and Demand dataset provides the weekly volumes of gasoline demand for the U.S. and production of finished gasoline for both the East Coast and the U.S. in terms of thousand barrels per day. Data is reported weekly starting in July 1993 through current.

## Columns

```ls
| Included | Schema Type    | Field Name                                                 | Name                                                         | Data Type     | Render Type   |
| ======== | ============== | ========================================================== | ============================================================ | ============= | ============= |
| Yes      | time           | date                                                       | Date                                                         | calendar_date | calendar_date |
| Yes      | numeric metric | east_coast_production_of_gasoline_thousand_barrels_per_day | East Coast Production of Gasoline (Thousand Barrels per Day) | number        | number        |
| Yes      | numeric metric | u_s_production_of_gasoline_thousand_barrels_per_day        | U.S. Production of Gasoline (Thousand Barrels per Day)       | number        | number        |
| Yes      | numeric metric | u_s_gasoline_demand_thousand_barrels_per_day               | U.S. Gasoline Demand (Thousand Barrels per Day)              | number        | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:atwy-2trf d:2017-03-31T00:00:00.000Z m:u_s_gasoline_demand_thousand_barrels_per_day=9245 m:u_s_production_of_gasoline_thousand_barrels_per_day=9515 m:east_coast_production_of_gasoline_thousand_barrels_per_day=3112

series e:atwy-2trf d:2017-03-24T00:00:00.000Z m:u_s_gasoline_demand_thousand_barrels_per_day=9524 m:u_s_production_of_gasoline_thousand_barrels_per_day=10028 m:east_coast_production_of_gasoline_thousand_barrels_per_day=3107

series e:atwy-2trf d:2017-03-17T00:00:00.000Z m:u_s_gasoline_demand_thousand_barrels_per_day=9200 m:u_s_production_of_gasoline_thousand_barrels_per_day=9771 m:east_coast_production_of_gasoline_thousand_barrels_per_day=3097
```

## Meta Commands

```ls
metric m:east_coast_production_of_gasoline_thousand_barrels_per_day p:integer l:"East Coast Production of Gasoline (Thousand Barrels per Day)" d:"Weekly amount of refiner and blender net production of finished gasoline for PADD 1: East Coast Region (ME, VT, NH, MA, CT, RI, NY, NJ, PA, DE, MD, MV, VA, NC, SC, GA, FL) (Thousand Barrels/Day)" t:dataTypeName=number

metric m:u_s_production_of_gasoline_thousand_barrels_per_day p:integer l:"U.S. Production of Gasoline (Thousand Barrels per Day)" d:"Weekly amount of refiner and blender net production of finished gasoline for the U.S. (Thousand Barrels/Day)" t:dataTypeName=number

metric m:u_s_gasoline_demand_thousand_barrels_per_day p:integer l:"U.S. Gasoline Demand (Thousand Barrels per Day)" d:"Weekly U.S. amount supplied of finished gasoline. (Thousand Barrels/Day)" t:dataTypeName=number

entity e:atwy-2trf l:"Transportation Fuels Production and Demand: Beginning 1993" t:attribution="New York State Energy Research and Development Authority Performance Management and Evaluation Services Group" t:url=https://data.ny.gov/api/views/atwy-2trf

property e:atwy-2trf t:meta.view v:id=atwy-2trf v:category="Energy & Environment" v:attributionLink=http://www.nyserda.ny.gov/Energy-Data-and-Prices-Planning-and-Policy/Energy-Prices-Data-and-Reports/EA-Reports-and-Studies/Weekly-Transportation-Fuels-Report.aspx. v:averageRating=0 v:name="Transportation Fuels Production and Demand: Beginning 1993" v:attribution="New York State Energy Research and Development Authority Performance Management and Evaluation Services Group"

property e:atwy-2trf t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:atwy-2trf t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| date                | east_coast_production_of_gasoline_thousand_barrels_per_day | u_s_production_of_gasoline_thousand_barrels_per_day | u_s_gasoline_demand_thousand_barrels_per_day | 
| =================== | ========================================================== | =================================================== | ============================================ | 
| 2017-03-31T00:00:00 | 3112                                                       | 9515                                                | 9245                                         | 
| 2017-03-24T00:00:00 | 3107                                                       | 10028                                               | 9524                                         | 
| 2017-03-17T00:00:00 | 3097                                                       | 9771                                                | 9200                                         | 
| 2017-03-10T00:00:00 | 3244                                                       | 9540                                                | 9254                                         | 
| 2017-03-03T00:00:00 | 3018                                                       | 9844                                                | 9268                                         | 
| 2017-02-24T00:00:00 | 3129                                                       | 9456                                                | 8686                                         | 
| 2017-02-17T00:00:00 | 3014                                                       | 9429                                                | 8663                                         | 
| 2017-02-10T00:00:00 | 2927                                                       | 8950                                                | 8433                                         | 
| 2017-02-03T00:00:00 | 3004                                                       | 9804                                                | 8941                                         | 
| 2017-01-27T00:00:00 | 2886                                                       | 9101                                                | 8310                                         | 
```