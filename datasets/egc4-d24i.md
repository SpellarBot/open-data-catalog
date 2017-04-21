# Road Weather Information Stations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/road-weather-information-stations-788f8) |
| Metadata | [Link](https://data.seattle.gov/api/views/egc4-d24i) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/egc4-d24i/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/egc4-d24i/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | egc4-d24i |
| Name | Road Weather Information Stations |
| Attribution | Department of Transportation |
| Category | Transportation |
| Tags | road, weather, street, temperature, seattle, transportation |
| Created | 2014-03-04T15:24:22Z |
| Publication Date | 2014-05-19T16:29:45Z |

## Description

This data is derived from sensor stations placed on bridges and surface streets within city limits.  Each station has a temperature sensor that measures the temperature of the street surface and a sensor that measures the ambient air temperature at the station each second.  Those values are averaged into temperature readings that are recorded by the station every minute.  The dataset is updated every fifteen minutes with new data.

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type     | Render Type   |
| ======== | ============== | ====================== | ====================== | ============= | ============= |
| Yes      | series tag     | stationname            | StationName            | text          | text          |
| Yes      | time           | datetime               | DateTime               | calendar_date | calendar_date |
| Yes      | series tag     | recordid               | RecordId               | text          | number        |
| Yes      | numeric metric | roadsurfacetemperature | RoadSurfaceTemperature | number        | number        |
| Yes      | numeric metric | airtemperature         | AirTemperature         | number        | number        |
```

## Time Field

```ls
Value = datetime
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:egc4-d24i d:2014-03-03T12:42:00.000Z t:stationname=35thAveSW_SWMyrtleSt t:recordid=672560 m:roadsurfacetemperature=53.88 m:airtemperature=53.88

series e:egc4-d24i d:2014-03-03T12:43:00.000Z t:stationname=35thAveSW_SWMyrtleSt t:recordid=672561 m:roadsurfacetemperature=54.05 m:airtemperature=54.05

series e:egc4-d24i d:2014-03-03T12:44:00.000Z t:stationname=35thAveSW_SWMyrtleSt t:recordid=672562 m:roadsurfacetemperature=54.21 m:airtemperature=54.21
```

## Meta Commands

```ls
metric m:roadsurfacetemperature p:float l:RoadSurfaceTemperature t:dataTypeName=number

metric m:airtemperature p:float l:AirTemperature t:dataTypeName=number

entity e:egc4-d24i l:"Road Weather Information Stations" t:attribution="Department of Transportation" t:url=https://data.seattle.gov/api/views/egc4-d24i

property e:egc4-d24i t:meta.view v:id=egc4-d24i v:category=Transportation v:averageRating=0 v:name="Road Weather Information Stations" v:attribution="Department of Transportation"

property e:egc4-d24i t:meta.view.license v:name="Public Domain"

property e:egc4-d24i t:meta.view.owner v:id=cq6b-km4i v:screenName="Road Weather" v:displayName="Road Weather"

property e:egc4-d24i t:meta.view.tableauthor v:id=cq6b-km4i v:screenName="Road Weather" v:roleName=publisher v:displayName="Road Weather"
```

## Top Records

```ls
| stationname          | datetime            | recordid | roadsurfacetemperature | airtemperature | 
| ==================== | =================== | ======== | ====================== | ============== | 
| 35thAveSW_SWMyrtleSt | 2014-03-03T12:42:00 | 672560   | 53.88                  | 53.88          | 
| 35thAveSW_SWMyrtleSt | 2014-03-03T12:43:00 | 672561   | 54.05                  | 54.05          | 
| 35thAveSW_SWMyrtleSt | 2014-03-03T12:44:00 | 672562   | 54.21                  | 54.21          | 
| 35thAveSW_SWMyrtleSt | 2014-03-03T12:45:00 | 672563   | 54.38                  | 54.38          | 
| 35thAveSW_SWMyrtleSt | 2014-03-03T12:46:00 | 672564   | 54.54                  | 54.54          | 
| 35thAveSW_SWMyrtleSt | 2014-03-03T12:47:00 | 672565   | 54.69                  | 54.69          | 
| 35thAveSW_SWMyrtleSt | 2014-03-03T12:48:00 | 672566   | 54.85                  | 54.85          | 
| 35thAveSW_SWMyrtleSt | 2014-03-03T12:49:00 | 672567   | 54.98                  | 54.98          | 
| 35thAveSW_SWMyrtleSt | 2014-03-03T12:50:00 | 672568   | 55.11                  | 55.11          | 
| 35thAveSW_SWMyrtleSt | 2014-03-03T12:51:00 | 672569   | 55.24                  | 55.24          | 
```