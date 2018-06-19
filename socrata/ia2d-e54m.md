# Water Consumption In The New York City

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/water-consumption-in-the-new-york-city-3d2f0) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/ia2d-e54m) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/ia2d-e54m/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/ia2d-e54m/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | ia2d-e54m |
| Name | Water Consumption In The New York City |
| Attribution | Department of Environmental Protection (DEP) |
| Category | Environment |
| Tags | dep, department of environmental protection, environment, water, consumption, water consumption, water consumption in the new york city, healthy living |
| Created | 2013-01-31T00:21:38Z |
| Publication Date | 2013-06-21T19:44:41Z |

## Description

A brief history of water consumption in the New York City Water Supply System (Based on New York City Census population)

## Columns

```ls
| Included | Schema Type    | Field Name                              | Name                                     | Data Type | Render Type |
| ======== | ============== | ======================================= | ======================================== | ========= | =========== |
| Yes      | time           | year                                    | Year                                     | number    | number      |
| Yes      | numeric metric | nyc_consumption_million_gallons_per_day | NYC Consumption(Million gallons per day) | number    | number      |
| Yes      | numeric metric | per_capita_gallons_per_person_per_day   | Per Capita(Gallons per person per day)   | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ia2d-e54m d:2009-01-01T00:00:00.000Z m:nyc_consumption_million_gallons_per_day=1007.2 m:per_capita_gallons_per_person_per_day=125.8

series e:ia2d-e54m d:2008-01-01T00:00:00.000Z m:nyc_consumption_million_gallons_per_day=1082.9 m:per_capita_gallons_per_person_per_day=135.2

series e:ia2d-e54m d:2007-01-01T00:00:00.000Z m:nyc_consumption_million_gallons_per_day=1113.9 m:per_capita_gallons_per_person_per_day=139.1
```

## Meta Commands

```ls
metric m:nyc_consumption_million_gallons_per_day p:float l:"NYC Consumption(Million gallons per day)" t:dataTypeName=number

metric m:per_capita_gallons_per_person_per_day p:float l:"Per Capita(Gallons per person per day)" t:dataTypeName=number

entity e:ia2d-e54m l:"Water Consumption In The New York City" t:attribution="Department of Environmental Protection (DEP)" t:url=https://data.cityofnewyork.us/api/views/ia2d-e54m

property e:ia2d-e54m t:meta.view v:id=ia2d-e54m v:category=Environment v:attributionLink=http://www.nyc.gov/html/dep/html/drinking_water/droughthist.shtml v:averageRating=0 v:name="Water Consumption In The New York City" v:attribution="Department of Environmental Protection (DEP)"

property e:ia2d-e54m t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:ia2d-e54m t:meta.view.tableauthor v:id=ya7g-926w v:screenName="Aakash Dalwani" v:displayName="Aakash Dalwani"
```

## Top Records

```ls
| year | nyc_consumption_million_gallons_per_day | per_capita_gallons_per_person_per_day | 
| ==== | ======================================= | ===================================== | 
| 2009 | 1007.2                                  | 125.8                                 | 
| 2008 | 1082.9                                  | 135.2                                 | 
| 2007 | 1113.9                                  | 139.1                                 | 
| 2006 | 1068.7                                  | 133.5                                 | 
| 2005 | 1107.4                                  | 138.3                                 | 
| 2004 | 1099.5                                  | 137.3                                 | 
| 2003 | 1093.7                                  | 136.6                                 | 
| 2002 | 1135.6                                  | 141.8                                 | 
| 2001 | 1184.0                                  | 154.6                                 | 
| 2000 | 1240.4                                  | 169.4                                 | 
```