# SDOT Road Temperature Stations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/sdot-road-temperature-stations-2afd8) |
| Metadata | [Link](https://data.seattle.gov/api/views/wd5q-q35v) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/wd5q-q35v/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/wd5q-q35v/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | wd5q-q35v |
| Name | SDOT Road Temperature Stations |
| Tags | storm response |
| Created | 2016-12-08T22:55:45Z |
| Publication Date | 2016-12-14T16:05:31Z |
| Rows Updated | 2016-12-08T22:55:45Z |

## Description

Displays the location and data being collected from road temperature stations in the City of Seattle. This data shows the road temperature and the air temperature at the location of the sensor and maintains records of temperature data collected up to 2 hours beforehand.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| Yes      | series tag     | objectid          | OBJECTID          | text      | number      |
| Yes      | series tag     | rwis_station_name | RWIS_STATION_NAME | text      | text        |
| Yes      | series tag     | rwis_display_name | RWIS_DISPLAY_NAME | text      | text        |
| Yes      | time           | rwis_datetime     | RWIS_DATETIME     | text      | text        |
| Yes      | numeric metric | rstemp_current    | RSTEMP_CURRENT    | number    | number      |
| Yes      | numeric metric | airtemp_current   | AIRTEMP_CURRENT   | number    | number      |
| Yes      | numeric metric | rstemp_15min      | RSTEMP_15MIN      | number    | number      |
| Yes      | numeric metric | airtemp_15min     | AIRTEMP_15MIN     | number    | number      |
| Yes      | numeric metric | rstemp_30min      | RSTEMP_30MIN      | number    | number      |
| Yes      | numeric metric | airtemp_30min     | AIRTEMP_30MIN     | number    | number      |
| Yes      | numeric metric | rstemp_45min      | RSTEMP_45MIN      | number    | number      |
| Yes      | numeric metric | airtemp_45min     | AIRTEMP_45MIN     | number    | number      |
| Yes      | numeric metric | rstemp_60min      | RSTEMP_60MIN      | number    | number      |
| Yes      | numeric metric | airtemp_60min     | AIRTEMP_60MIN     | number    | number      |
| Yes      | numeric metric | rstemp_75min      | RSTEMP_75MIN      | number    | number      |
| Yes      | numeric metric | airtemp_75min     | AIRTEMP_75MIN     | number    | number      |
| Yes      | numeric metric | rstemp_90min      | RSTEMP_90MIN      | number    | number      |
| Yes      | numeric metric | airtemp_90min     | AIRTEMP_90MIN     | number    | number      |
| Yes      | numeric metric | rstemp_105min     | RSTEMP_105MIN     | number    | number      |
| Yes      | numeric metric | airtemp_105min    | AIRTEMP_105MIN    | number    | number      |
| Yes      | numeric metric | rstemp_120min     | RSTEMP_120MIN     | number    | number      |
| Yes      | numeric metric | airtemp_120min    | AIRTEMP_120MIN    | number    | number      |
```

## Time Field

```ls
Value = rwis_datetime
Format & Zone = yyyy-MM-dd HH:mm:ss
```

## Data Commands

```ls
series e:wd5q-q35v d:2017-03-18T23:00:00.000Z t:objectid=1 t:rwis_station_name=AlaskanWayViaduct_KingSt t:rwis_display_name="Alaskan Way Viaduct at King St" m:airtemp_120min=44.800000000000004 m:airtemp_60min=44.37 m:rstemp_30min=44.81 m:rstemp_75min=46.17 m:airtemp_105min=44.730000000000004 m:airtemp_45min=44.21 m:airtemp_15min=44.01 m:airtemp_30min=44.1 m:rstemp_105min=47.37 m:rstemp_15min=44.58 m:rstemp_current=44.46 m:airtemp_75min=44.53 m:airtemp_current=43.980000000000004 m:rstemp_90min=46.85 m:rstemp_120min=47.52 m:rstemp_45min=45.18 m:rstemp_60min=45.61 m:airtemp_90min=44.660000000000004

series e:wd5q-q35v d:2017-03-18T23:00:00.000Z t:objectid=2 t:rwis_station_name=HarborAveUpperNorthBridge t:rwis_display_name="Harbor Ave Upper North Bridge" m:airtemp_120min=42.1 m:airtemp_60min=41.6 m:rstemp_30min=45.43 m:rstemp_75min=46.74 m:airtemp_105min=42.02 m:airtemp_45min=41.59 m:airtemp_15min=41.480000000000004 m:airtemp_30min=41.52 m:rstemp_105min=47.89 m:rstemp_15min=45.22 m:rstemp_current=45.04 m:airtemp_75min=41.64 m:airtemp_current=41.49 m:rstemp_90min=47.38 m:rstemp_120min=48.11 m:rstemp_45min=45.79 m:rstemp_60min=46.21 m:airtemp_90min=41.83

series e:wd5q-q35v d:2017-03-18T23:00:00.000Z t:objectid=3 t:rwis_station_name=SpokaneSwingBridge t:rwis_display_name="Spokane Swing Bridge" m:airtemp_120min=49.32 m:airtemp_60min=49.26 m:rstemp_30min=44 m:rstemp_75min=44.800000000000004 m:airtemp_105min=49.32 m:airtemp_45min=49.11 m:airtemp_15min=48.83 m:airtemp_30min=48.870000000000005 m:rstemp_105min=45.58 m:rstemp_15min=43.87 m:rstemp_current=43.78 m:airtemp_75min=49.32 m:airtemp_current=48.83 m:rstemp_90min=45.25 m:rstemp_120min=45.7 m:rstemp_45min=44.18 m:rstemp_60min=44.42 m:airtemp_90min=49.36
```

## Meta Commands

```ls
metric m:rstemp_current p:float l:RSTEMP_CURRENT d:RSTEMP_CURRENT t:dataTypeName=number

metric m:airtemp_current p:float l:AIRTEMP_CURRENT d:AIRTEMP_CURRENT t:dataTypeName=number

metric m:rstemp_15min p:float l:RSTEMP_15MIN d:RSTEMP_15MIN t:dataTypeName=number

metric m:airtemp_15min p:float l:AIRTEMP_15MIN d:AIRTEMP_15MIN t:dataTypeName=number

metric m:rstemp_30min p:float l:RSTEMP_30MIN d:RSTEMP_30MIN t:dataTypeName=number

metric m:airtemp_30min p:decimal l:AIRTEMP_30MIN d:AIRTEMP_30MIN t:dataTypeName=number

metric m:rstemp_45min p:float l:RSTEMP_45MIN d:RSTEMP_45MIN t:dataTypeName=number

metric m:airtemp_45min p:decimal l:AIRTEMP_45MIN d:AIRTEMP_45MIN t:dataTypeName=number

metric m:rstemp_60min p:float l:RSTEMP_60MIN d:RSTEMP_60MIN t:dataTypeName=number

metric m:airtemp_60min p:decimal l:AIRTEMP_60MIN d:AIRTEMP_60MIN t:dataTypeName=number

metric m:rstemp_75min p:float l:RSTEMP_75MIN d:RSTEMP_75MIN t:dataTypeName=number

metric m:airtemp_75min p:float l:AIRTEMP_75MIN d:AIRTEMP_75MIN t:dataTypeName=number

metric m:rstemp_90min p:float l:RSTEMP_90MIN d:RSTEMP_90MIN t:dataTypeName=number

metric m:airtemp_90min p:float l:AIRTEMP_90MIN d:AIRTEMP_90MIN t:dataTypeName=number

metric m:rstemp_105min p:decimal l:RSTEMP_105MIN d:RSTEMP_105MIN t:dataTypeName=number

metric m:airtemp_105min p:decimal l:AIRTEMP_105MIN d:AIRTEMP_105MIN t:dataTypeName=number

metric m:rstemp_120min p:float l:RSTEMP_120MIN d:RSTEMP_120MIN t:dataTypeName=number

metric m:airtemp_120min p:float l:AIRTEMP_120MIN d:AIRTEMP_120MIN t:dataTypeName=number

entity e:wd5q-q35v l:"SDOT Road Temperature Stations" t:url=https://data.seattle.gov/api/views/wd5q-q35v

property e:wd5q-q35v t:meta.view v:id=wd5q-q35v v:averageRating=0 v:name="SDOT Road Temperature Stations"

property e:wd5q-q35v t:meta.view.owner v:id=geh9-fb2x v:screenName="SDOT GIS" v:displayName="SDOT GIS"

property e:wd5q-q35v t:meta.view.tableauthor v:id=geh9-fb2x v:screenName="SDOT GIS" v:roleName=publisher v:displayName="SDOT GIS"
```