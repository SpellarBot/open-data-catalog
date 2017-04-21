# Beach Water and Weather Sensor Locations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/beach-water-and-weather-sensor-locations) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/g3ip-u8rb) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/g3ip-u8rb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/g3ip-u8rb/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | g3ip-u8rb |
| Name | Beach Water and Weather Sensor Locations |
| Attribution | Chicago Park District |
| Category | Parks & Recreation |
| Tags | beaches, parks, chicago park district, open spaces, parks & recreation, recreation, water, weather |
| Created | 2015-06-04T18:03:15Z |
| Publication Date | 2015-06-04T18:11:05Z |

## Description

The locations of the Chicago Park District water and weather sensors that feed https://data.cityofchicago.org/d/qmqz-2xku and https://data.cityofchicago.org/d/k7hf-8y75.

## Columns

```ls
| Included | Schema Type | Field Name  | Name        | Data Type | Render Type |
| ======== | =========== | =========== | =========== | ========= | =========== |
| No       | time        | :updated_at | updated_at  | meta_data | meta_data   |
| Yes      | series tag  | sensor_name | Sensor Name | text      | text        |
| Yes      | series tag  | sensor_type | Sensor Type | text      | text        |
| No       |             | latitude    | Latitude    | number    | number      |
| No       |             | longitude   | Longitude   | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = latitude,longitude
```

## Data Commands

```ls
series e:g3ip-u8rb d:2015-06-04T11:04:10.000Z t:sensor_name="Calumet Beach" t:sensor_type=Water m:row_number.g3ip-u8rb=1

series e:g3ip-u8rb d:2015-06-04T11:04:10.000Z t:sensor_name="63rd Street Weather Station" t:sensor_type=Weather m:row_number.g3ip-u8rb=2

series e:g3ip-u8rb d:2015-06-04T11:04:10.000Z t:sensor_name="63rd Street Beach" t:sensor_type=Water m:row_number.g3ip-u8rb=3
```

## Meta Commands

```ls
metric m:row_number.g3ip-u8rb p:long l:"Row Number"

entity e:g3ip-u8rb l:"Beach Water and Weather Sensor Locations" t:attribution="Chicago Park District" t:url=https://data.cityofchicago.org/api/views/g3ip-u8rb

property e:g3ip-u8rb t:meta.view v:id=g3ip-u8rb v:category="Parks & Recreation" v:attributionLink=http://www.chicagoparkdistrict.com v:averageRating=0 v:name="Beach Water and Weather Sensor Locations" v:attribution="Chicago Park District"

property e:g3ip-u8rb t:meta.view.owner v:id=vewm-vupz v:screenName="Jonathan Levy" v:displayName="Jonathan Levy"

property e:g3ip-u8rb t:meta.view.tableauthor v:id=vewm-vupz v:screenName="Jonathan Levy" v:roleName=administrator v:displayName="Jonathan Levy"
```

## Top Records

```ls
| :updated_at | sensor_name                 | sensor_type | latitude           | longitude           | 
| =========== | =========================== | =========== | ================== | =================== | 
| 1433415850  | Calumet Beach               | Water       | 41.714739000000002 | -87.527355999999997 | 
| 1433415850  | 63rd Street Weather Station | Weather     | 41.780991999999998 | -87.572619000000003 | 
| 1433415850  | 63rd Street Beach           | Water       | 41.784560999999997 | -87.571453000000005 | 
| 1433415850  | Oak Street Weather Station  | Weather     | 41.901997000000001 | -87.622816999999998 | 
| 1433415850  | Foster Weather Station      | Weather     | 41.976464          | -87.647525000000002 | 
| 1433415850  | Montrose Beach              | Water       | 41.969093999999998 | -87.638002999999998 | 
| 1433415850  | Osterman Beach              | Water       | 41.987675000000003 | -87.651008000000004 | 
| 1433415850  | Ohio Street Beach           | Water       | 41.894328000000002 | -87.613083000000003 | 
| 1433415850  | Rainbow Beach               | Water       | 41.760147000000003 | -87.550081000000006 | 
```