# NYS Forest Ranger Wildfires for FireFamily Plus 4.1: 1975-2007

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nys-forest-ranger-wildfires-for-firefamily-plus-4-1-1975-2007) |
| Metadata | [Link](https://data.ny.gov/api/views/4xir-miej) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/4xir-miej/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/4xir-miej/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 4xir-miej |
| Name | NYS Forest Ranger Wildfires for FireFamily Plus 4.1: 1975-2007 |
| Attribution | NYS DEC |
| Category | Energy & Environment |
| Tags | forest fire, brush fire, wildland fire, prescribed fire, grass fire, forest ranger |
| Created | 2016-11-25T21:01:49Z |
| Publication Date | 2016-11-25T22:15:35Z |

## Description

This dataset is the data collected and formatted for use with FireFamily Plus 4.1. It is the collection of available DEC data regarding wildland fires for the period 1975-2007.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type     | Render Type   |
| ======== | ============== | ================ | ================ | ============= | ============= |
| Yes      | series tag     | fireid           | FireID           | text          | number        |
| No       |                | year             | Year             | number        | number        |
| Yes      | series tag     | agencyid         | AgencyID         | text          | number        |
| Yes      | series tag     | regionid         | RegionID         | text          | number        |
| Yes      | series tag     | unitid           | UnitID           | text          | number        |
| Yes      | series tag     | subunitid        | SubunitID        | text          | number        |
| Yes      | series tag     | firenumber       | FireNumber       | text          | number        |
| Yes      | numeric metric | state            | State            | number        | number        |
| Yes      | numeric metric | county           | County           | number        | number        |
| Yes      | numeric metric | total_acres      | Total Acres      | number        | number        |
| Yes      | series tag     | sizeclass        | SizeClass        | text          | text          |
| Yes      | series tag     | firename         | FireName         | text          | text          |
| Yes      | numeric metric | statisticalcause | StatisticalCause | number        | number        |
| Yes      | numeric metric | specificcause    | SpecificCause    | number        | number        |
| Yes      | numeric metric | generalcause     | GeneralCause     | number        | number        |
| Yes      | numeric metric | class_people     | Class People     | number        | number        |
| Yes      | series tag     | causenarr        | CauseNarr        | text          | text          |
| Yes      | series tag     | township         | Township         | text          | text          |
| Yes      | series tag     | range            | Range            | text          | text          |
| Yes      | numeric metric | section          | Section          | number        | number        |
| Yes      | series tag     | subsection       | SubSection       | text          | text          |
| No       |                | latdd            | LatDD            | number        | number        |
| No       |                | latmm            | LatMM            | number        | number        |
| No       |                | latss            | LatSS            | number        | number        |
| Yes      | numeric metric | londd            | LonDD            | number        | number        |
| Yes      | numeric metric | lonmm            | LonMM            | number        | number        |
| Yes      | numeric metric | lonss            | LonSS            | number        | number        |
| Yes      | series tag     | other            | Other            | text          | text          |
| Yes      | numeric metric | wildnum          | WildNum          | number        | number        |
| Yes      | series tag     | notes            | Notes            | text          | text          |
| Yes      | series tag     | ignition         | Ignition         | text          | text          |
| Yes      | time           | discovery        | Discovery        | calendar_date | calendar_date |
```

## Time Field

```ls
Value = discovery
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = latdd,latmm,latss,year
```

## Data Commands

```ls
series e:4xir-miej d:1975-03-06T00:00:00.000Z t:township=CORNI t:unitid=2209 t:agencyid=6 t:subunitid=667 t:regionid=60 t:causenarr=Children t:firenumber=1 t:fireid=1 t:firename=Corning m:specificcause=0 m:class_people=0 m:wildnum=0 m:county=0 m:lonss=11 m:total_acres=2 m:state=0 m:lonmm=1 m:generalcause=0 m:section=0 m:statisticalcause=8 m:londd=-77

series e:4xir-miej d:1975-03-18T00:00:00.000Z t:township=CORNI t:unitid=2209 t:agencyid=6 t:subunitid=667 t:regionid=60 t:causenarr=Children t:firenumber=2 t:fireid=2 t:firename=Corning m:specificcause=0 m:class_people=0 m:wildnum=0 m:county=0 m:lonss=11 m:total_acres=3 m:state=0 m:lonmm=1 m:generalcause=0 m:section=0 m:statisticalcause=8 m:londd=-77

series e:4xir-miej d:1975-03-18T00:00:00.000Z t:township=WATER t:unitid=2210 t:agencyid=6 t:subunitid=668 t:regionid=57 t:causenarr=Children t:firenumber=3 t:fireid=3 t:firename=Waterford m:specificcause=0 m:class_people=0 m:wildnum=0 m:county=0 m:lonss=30 m:total_acres=120 m:state=0 m:lonmm=41 m:generalcause=0 m:section=0 m:statisticalcause=8 m:londd=-73
```

## Meta Commands

```ls
metric m:state p:integer l:State d:"Number assigned to NYS; only valid value is ?0?." t:dataTypeName=number

metric m:county p:integer l:County d:"Number assigned to NYS counties; only valid value is ?0?." t:dataTypeName=number

metric m:total_acres p:double l:"Total Acres" d:"Total size in acres of the fire when extinguished" t:dataTypeName=number

metric m:statisticalcause p:integer l:StatisticalCause d:"One of nine wildfire cause classifications codes: ? 1 = lightning; ? 2 = equipment; ? 3 = smoking; ? 4 = campfire; ? 5 = debris; ? 6 = railroad; ? 7 = incendiary; ? 8 = children; ? 9 = miscellaneous." t:dataTypeName=number

metric m:specificcause p:integer l:SpecificCause d:"Number assigned to specific cause; only valid value is ?0?." t:dataTypeName=number

metric m:generalcause p:integer l:GeneralCause d:"Number assigned to general cause; only valid value is ?0?." t:dataTypeName=number

metric m:class_people p:integer l:"Class People" d:"Number assigned to class people; only valid value is ?0?." t:dataTypeName=number

metric m:section p:integer l:Section d:"Number assigned to section; only valid value is ?0?." t:dataTypeName=number

metric m:londd p:integer l:LonDD d:"Degree of longitude of fire start locality; this is not necessarily the actual fire location." t:dataTypeName=number

metric m:lonmm p:integer l:LonMM d:"Minutes of longitude of fire start locality; this is not necessarily the actual fire location." t:dataTypeName=number

metric m:lonss p:integer l:LonSS d:"Seconds of longitude of fire start locality; this is not necessarily the actual fire location." t:dataTypeName=number

metric m:wildnum p:integer l:WildNum d:"Number assigned to ?WildNum?; only valid value is ?0?." t:dataTypeName=number

entity e:4xir-miej l:"NYS Forest Ranger Wildfires for FireFamily Plus 4.1: 1975-2007" t:attribution="NYS DEC" t:url=https://data.ny.gov/api/views/4xir-miej

property e:4xir-miej t:meta.view v:id=4xir-miej v:category="Energy & Environment" v:attributionLink=http://www.dec.ny.gov/lands/4975.html v:averageRating=0 v:name="NYS Forest Ranger Wildfires for FireFamily Plus 4.1: 1975-2007" v:attribution="NYS DEC"

property e:4xir-miej t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:4xir-miej t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| fireid | year | agencyid | regionid | unitid | subunitid | firenumber | state | county | total_acres | sizeclass | firename   | statisticalcause | specificcause | generalcause | class_people | causenarr      | township | range | section | subsection | latdd | latmm | latss | londd | lonmm | lonss | other | wildnum | notes | ignition | discovery           | 
| ====== | ==== | ======== | ======== | ====== | ========= | ========== | ===== | ====== | =========== | ========= | ========== | ================ | ============= | ============ | ============ | ============== | ======== | ===== | ======= | ========== | ===== | ===== | ===== | ===== | ===== | ===== | ===== | ======= | ===== | ======== | =================== | 
| 1      | 1975 | 6        | 60       | 2209   | 667       | 1          | 0     | 0      | 2           |           | Corning    | 8                | 0             | 0            | 0            | Children       | CORNI    |       | 0       |            | 42    | 8     | 24    | -77   | 1     | 11    |       | 0       |       |          | 1975-03-06T00:00:00 | 
| 2      | 1975 | 6        | 60       | 2209   | 667       | 2          | 0     | 0      | 3           |           | Corning    | 8                | 0             | 0            | 0            | Children       | CORNI    |       | 0       |            | 42    | 8     | 24    | -77   | 1     | 11    |       | 0       |       |          | 1975-03-18T00:00:00 | 
| 3      | 1975 | 6        | 57       | 2210   | 668       | 3          | 0     | 0      | 120         |           | Waterford  | 8                | 0             | 0            | 0            | Children       | WATER    |       | 0       |            | 42    | 48    | 16    | -73   | 41    | 30    |       | 0       |       |          | 1975-03-18T00:00:00 | 
| 4      | 1975 | 6        | 57       | 2210   | 669       | 4          | 0     | 0      | 20          |           | Halfmoon   | 8                | 0             | 0            | 0            | Children       | HALFM    |       | 0       |            | 42    | 51    | 50    | -73   | 43    | 39    |       | 0       |       |          | 1975-03-23T00:00:00 | 
| 5      | 1975 | 6        | 57       | 2210   | 670       | 5          | 0     | 0      | 0.75        |           | Greenfield | 8                | 0             | 0            | 0            | Children       | GREEN    |       | 0       |            | 43    | 8     | 14    | -73   | 52    | 35    |       | 0       |       |          | 1975-03-28T00:00:00 | 
| 6      | 1975 | 6        | 57       | 2210   | 671       | 6          | 0     | 0      | 3           |           | Saratoga   | 8                | 0             | 0            | 0            | Children       | SARAT    |       | 0       |            | 43    | 3     | 37    | -73   | 38    | 51    |       | 0       |       |          | 1975-03-28T00:00:00 | 
| 7      | 1975 | 6        | 57       | 2210   | 672       | 7          | 0     | 0      | 0.1         |           | Wilton     | 5                | 0             | 0            | 0            | Debris burning | WILTO    |       | 0       |            | 43    | 9     | 1     | -73   | 43    | 39    |       | 0       |       |          | 1975-03-28T00:00:00 | 
| 8      | 1975 | 6        | 57       | 2211   | 673       | 8          | 0     | 0      | 1           |           | Johnsburg  | 3                | 0             | 0            | 0            | Smoking        | JOHNS    |       | 0       |            | 43    | 37    | 48    | -74   | 3     | 12    |       | 0       |       |          | 1975-04-01T00:00:00 | 
| 9      | 1975 | 6        | 57       | 2210   | 670       | 9          | 0     | 0      | 1           |           | Greenfield | 3                | 0             | 0            | 0            | Smoking        | GREEN    |       | 0       |            | 43    | 8     | 14    | -73   | 52    | 35    |       | 0       |       |          | 1975-04-10T00:00:00 | 
| 10     | 1975 | 6        | 57       | 2210   | 672       | 10         | 0     | 0      | 1           |           | Wilton     | 5                | 0             | 0            | 0            | Debris burning | WILTO    |       | 0       |            | 43    | 9     | 1     | -73   | 43    | 39    |       | 0       |       |          | 1975-04-10T00:00:00 | 
```