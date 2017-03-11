# SDOT Road Temperature Stations

## Dataset

* [Dataset URL](https://data.seattle.gov/api/views/wd5q-q35v/rows.json?accessType=DOWNLOAD)
* [Catalog URL](https://catalog.data.gov/dataset/sdot-road-temperature-stations-2afd8)
* Id = wd5q-q35v
* Name = SDOT Road Temperature Stations
* Tags = [storm response]
* Created = 2016-12-08T22:55:45Z
* Publication Date = 2016-12-14T16:05:31Z
* Rows Updated = 2016-12-08T22:55:45Z

## Description

Displays the location and data being collected from road temperature stations in the City of Seattle. This data shows the road temperature and the air temperature at the location of the sensor and maintains records of temperature data collected up to 2 hours beforehand.

## Columns

```ls
| Name              | Field Name        | Data Type | Render Type | Schema Type    | Included | 
| ================= | ================= | ========= | =========== | ============== | ======== | 
| updated_at        | :updated_at       | meta_data | meta_data   | time           | Yes      | 
| OBJECTID          | objectid          | text      | number      | series tag     | Yes      | 
| RWIS_STATION_NAME | rwis_station_name | text      | text        | series tag     | Yes      | 
| RWIS_DISPLAY_NAME | rwis_display_name | text      | text        | series tag     | Yes      | 
| RWIS_DATETIME     | rwis_datetime     | text      | text        | series tag     | Yes      | 
| RSTEMP_CURRENT    | rstemp_current    | number    | number      | numeric metric | Yes      | 
| AIRTEMP_CURRENT   | airtemp_current   | number    | number      | numeric metric | Yes      | 
| RSTEMP_15MIN      | rstemp_15min      | number    | number      | numeric metric | Yes      | 
| AIRTEMP_15MIN     | airtemp_15min     | number    | number      | numeric metric | Yes      | 
| RSTEMP_30MIN      | rstemp_30min      | number    | number      | numeric metric | Yes      | 
| AIRTEMP_30MIN     | airtemp_30min     | number    | number      | numeric metric | Yes      | 
| RSTEMP_45MIN      | rstemp_45min      | number    | number      | numeric metric | Yes      | 
| AIRTEMP_45MIN     | airtemp_45min     | number    | number      | numeric metric | Yes      | 
| RSTEMP_60MIN      | rstemp_60min      | number    | number      | numeric metric | Yes      | 
| AIRTEMP_60MIN     | airtemp_60min     | number    | number      | numeric metric | Yes      | 
| RSTEMP_75MIN      | rstemp_75min      | number    | number      | numeric metric | Yes      | 
| AIRTEMP_75MIN     | airtemp_75min     | number    | number      | numeric metric | Yes      | 
| RSTEMP_90MIN      | rstemp_90min      | number    | number      | numeric metric | Yes      | 
| AIRTEMP_90MIN     | airtemp_90min     | number    | number      | numeric metric | Yes      | 
| RSTEMP_105MIN     | rstemp_105min     | number    | number      | numeric metric | Yes      | 
| AIRTEMP_105MIN    | airtemp_105min    | number    | number      | numeric metric | Yes      | 
| RSTEMP_120MIN     | rstemp_120min     | number    | number      | numeric metric | Yes      | 
| AIRTEMP_120MIN    | airtemp_120min    | number    | number      | numeric metric | Yes      | 
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = 
Annotation Fields = 
```

## Data Commands

```ls
series e:wd5q-q35v d:1970-01-01T00:00:00.000Z t:rwis_datetime="2017-03-03 05:30:00" t:objectid=1 t:rwis_station_name=35thAveSW_SWMyrtleSt t:rwis_display_name="35th Ave SW at SW Myrtle St" m:airtemp_120min=43.24 m:airtemp_60min=43.3 m:rstemp_75min=43.28 m:rstemp_30min=43.31 m:airtemp_105min=43.25 m:airtemp_45min=43.3 m:airtemp_15min=43.32 m:rstemp_105min=43.25 m:airtemp_30min=43.31 m:rstemp_current=43.32 m:rstemp_15min=43.32 m:airtemp_75min=43.28 m:airtemp_current=43.32 m:rstemp_90min=43.26 m:rstemp_120min=43.24 m:rstemp_45min=43.3 m:rstemp_60min=43.3 m:airtemp_90min=43.26

series e:wd5q-q35v d:1970-01-01T00:00:00.000Z t:rwis_datetime="2017-03-03 05:30:00" t:objectid=2 t:rwis_station_name=AlaskanWayViaduct_KingSt t:rwis_display_name="Alaskan Way Viaduct at King St" m:airtemp_120min=45.32 m:airtemp_60min=45.4 m:rstemp_75min=44.56 m:rstemp_30min=44.91 m:airtemp_105min=45.32 m:airtemp_45min=45.44 m:airtemp_15min=45.53 m:rstemp_105min=44.4 m:airtemp_30min=45.49 m:rstemp_current=45.13 m:rstemp_15min=45.04 m:airtemp_75min=45.39 m:airtemp_current=45.57 m:rstemp_90min=44.5 m:rstemp_120min=44.43 m:rstemp_45min=44.76 m:rstemp_60min=44.63 m:airtemp_90min=45.36

series e:wd5q-q35v d:1970-01-01T00:00:00.000Z t:rwis_datetime="2017-03-03 05:29:00" t:objectid=3 t:rwis_station_name=AlbroPlaceAirportWay t:rwis_display_name="Albro Place at Airport Way" m:airtemp_120min=47.74 m:airtemp_60min=48.28 m:rstemp_75min=44.17 m:rstemp_30min=44.26 m:airtemp_105min=47.71 m:airtemp_45min=48.48 m:airtemp_15min=48.53 m:rstemp_105min=44.08 m:airtemp_30min=48.45 m:rstemp_current=44.3 m:rstemp_15min=44.28 m:airtemp_75min=48.18 m:airtemp_current=48.53 m:rstemp_90min=44.13 m:rstemp_120min=44.08 m:rstemp_45min=44.23 m:rstemp_60min=44.2 m:airtemp_90min=47.9
```

## Meta Commands

```ls
metric m:rstemp_current l:RSTEMP_CURRENT d:RSTEMP_CURRENT t:dataTypeName=number

metric m:airtemp_current l:AIRTEMP_CURRENT d:AIRTEMP_CURRENT t:dataTypeName=number

metric m:rstemp_15min l:RSTEMP_15MIN d:RSTEMP_15MIN t:dataTypeName=number

metric m:airtemp_15min l:AIRTEMP_15MIN d:AIRTEMP_15MIN t:dataTypeName=number

metric m:rstemp_30min l:RSTEMP_30MIN d:RSTEMP_30MIN t:dataTypeName=number

metric m:airtemp_30min l:AIRTEMP_30MIN d:AIRTEMP_30MIN t:dataTypeName=number

metric m:rstemp_45min l:RSTEMP_45MIN d:RSTEMP_45MIN t:dataTypeName=number

metric m:airtemp_45min l:AIRTEMP_45MIN d:AIRTEMP_45MIN t:dataTypeName=number

metric m:rstemp_60min l:RSTEMP_60MIN d:RSTEMP_60MIN t:dataTypeName=number

metric m:airtemp_60min l:AIRTEMP_60MIN d:AIRTEMP_60MIN t:dataTypeName=number

metric m:rstemp_75min l:RSTEMP_75MIN d:RSTEMP_75MIN t:dataTypeName=number

metric m:airtemp_75min l:AIRTEMP_75MIN d:AIRTEMP_75MIN t:dataTypeName=number

metric m:rstemp_90min l:RSTEMP_90MIN d:RSTEMP_90MIN t:dataTypeName=number

metric m:airtemp_90min l:AIRTEMP_90MIN d:AIRTEMP_90MIN t:dataTypeName=number

metric m:rstemp_105min l:RSTEMP_105MIN d:RSTEMP_105MIN t:dataTypeName=number

metric m:airtemp_105min l:AIRTEMP_105MIN d:AIRTEMP_105MIN t:dataTypeName=number

metric m:rstemp_120min l:RSTEMP_120MIN d:RSTEMP_120MIN t:dataTypeName=number

metric m:airtemp_120min l:AIRTEMP_120MIN d:AIRTEMP_120MIN t:dataTypeName=number

entity e:wd5q-q35v l:"SDOT Road Temperature Stations" t:url=https://data.seattle.gov/api/views/wd5q-q35v

property e:wd5q-q35v t:meta.view d:2017-03-03T13:52:29.291Z v:id=wd5q-q35v v:averageRating=0 v:name="SDOT Road Temperature Stations"

property e:wd5q-q35v t:meta.view.owner d:2017-03-03T13:52:29.291Z v:id=geh9-fb2x v:screenName="SDOT GIS" v:roleName=publisher v:displayName="SDOT GIS"

property e:wd5q-q35v t:meta.view.tableauthor d:2017-03-03T13:52:29.291Z v:id=geh9-fb2x v:screenName="SDOT GIS" v:roleName=publisher v:displayName="SDOT GIS"
```