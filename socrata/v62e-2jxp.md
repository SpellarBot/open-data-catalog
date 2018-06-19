# Estimated Yearly Pedestrian Volume at Intersections

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/estimated-yearly-pedestrian-volume-at-intersections) |
| Metadata | [Link](https://data.sfgov.org/api/views/v62e-2jxp) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/v62e-2jxp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/v62e-2jxp/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | v62e-2jxp |
| Name | Estimated Yearly Pedestrian Volume at Intersections |
| Attribution | City and County of San Francisco |
| Category | Transportation |
| Tags | pedal volume |
| Created | 2016-08-18T20:46:06Z |
| Publication Date | 2016-10-12T00:51:50Z |

## Description

This dataset is created to show the estimated yearly pedestrian volume at each intersection.

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type | Render Type |
| ======== | ============== | ======================== | ======================== | ========= | =========== |
| No       | time           | :updated_at              | updated_at               | meta_data | meta_data   |
| Yes      | series tag     | object_id                | Object ID                | text      | number      |
| Yes      | series tag     | street_name              | Street Name              | text      | text        |
| Yes      | series tag     | street_type              | Street Type              | text      | text        |
| Yes      | series tag     | cnn_id                   | CNN ID                   | text      | text        |
| Yes      | series tag     | street_name_2            | Street Name 2            | text      | text        |
| Yes      | series tag     | street_type_2            | Street Type 2            | text      | text        |
| Yes      | series tag     | street_name_3            | Street Name 3            | text      | text        |
| Yes      | series tag     | street_type_3            | Street Type 3            | text      | text        |
| Yes      | series tag     | street_name_4            | Street Name 4            | text      | text        |
| Yes      | series tag     | street_type_4            | Street Type 4            | text      | text        |
| Yes      | numeric metric | annual_pedestrian_volume | Annual Pedestrian Volume | number    | number      |
| No       |                | last_edited_date         | Last Edited Date         | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = last_edited_date
```

## Data Commands

```ls
series e:v62e-2jxp d:2017-04-15T16:39:50.000Z t:street_name_2=SUNNYDALE t:object_id=1 t:street_name=REY t:cnn_id=20370000 t:street_type_2=AVE t:street_type=ST m:annual_pedestrian_volume=336571

series e:v62e-2jxp d:2017-04-15T16:39:50.000Z t:street_name_2=LAWRENCE t:object_id=2 t:street_name=HURON t:cnn_id=21553000 t:street_type_2=AVE t:street_type=AVE m:annual_pedestrian_volume=230736

series e:v62e-2jxp d:2017-04-15T16:39:50.000Z t:street_name_2=SICKLES t:object_id=3 t:street_name=CAYUGA t:cnn_id=21582000 t:street_type_2=AVE t:street_type=AVE m:annual_pedestrian_volume=303043
```

## Meta Commands

```ls
metric m:annual_pedestrian_volume p:integer l:"Annual Pedestrian Volume" t:dataTypeName=number

entity e:v62e-2jxp l:"Estimated Yearly Pedestrian Volume at Intersections" t:attribution="City and County of San Francisco" t:url=https://data.sfgov.org/api/views/v62e-2jxp

property e:v62e-2jxp t:meta.view v:id=v62e-2jxp v:category=Transportation v:attributionLink=http://www.sfgov.org v:averageRating=0 v:name="Estimated Yearly Pedestrian Volume at Intersections" v:attribution="City and County of San Francisco"

property e:v62e-2jxp t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:v62e-2jxp t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:displayName=OpenData

property e:v62e-2jxp t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```

## Top Records

```ls
| :updated_at | object_id | street_name  | street_type | cnn_id   | street_name_2 | street_type_2 | street_name_3 | street_type_3 | street_name_4 | street_type_4 | annual_pedestrian_volume | last_edited_date | 
| =========== | ========= | ============ | =========== | ======== | ============= | ============= | ============= | ============= | ============= | ============= | ======================== | ================ | 
| 1492274390  | 1         | REY          | ST          | 20370000 | SUNNYDALE     | AVE           |               |               |               |               | 336571                   |                  | 
| 1492274390  | 2         | HURON        | AVE         | 21553000 | LAWRENCE      | AVE           |               |               |               |               | 230736                   |                  | 
| 1492274390  | 3         | CAYUGA       | AVE         | 21582000 | SICKLES       | AVE           |               |               |               |               | 303043                   |                  | 
| 1492274390  | 4         | EXECUTIVE PA | BLVD        | 20262000 | THOMAS MELLO  | DR            | SANDPIPER CO  | WAY           |               |               | 237005                   |                  | 
| 1492274390  | 5         | NUEVA        | AVE         | 20271000 | BLANKEN       | AVE           |               |               |               |               | 190378                   |                  | 
| 1492274390  | 6         | UNNAMED PRIV | 0           | 54114000 | CRESCENT      | CT            | CRESCENT      | WAY           |               |               | 159589                   |                  | 
| 1492274390  | 7         | CHICAGO      | WAY         | 21384000 | SOUTH HILL    | BLVD          |               |               |               |               | 222618                   |                  | 
| 1492274390  | 8         | GARRISON     | AVE         | 20377000 | SUNNYDALE     | AVE           |               |               |               |               | 373177                   |                  | 
| 1492274390  | 9         | LELAND       | AVE         | 20313000 | BAY SHORE     | BLVD          |               |               |               |               | 3396426                  |                  | 
| 1492274390  | 10        | EXECUTIVE PA | BLVD        | 54206000 | CANDLESTICK   | WAY           |               |               |               |               | 409867                   |                  | 
```