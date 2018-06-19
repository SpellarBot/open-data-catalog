# Libraries - WiFi Usage (2011-2014)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/libraries-wifi-usage-2011-2014) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/vbts-zqt4) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/vbts-zqt4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/vbts-zqt4/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | vbts-zqt4 |
| Name | Libraries - WiFi Usage (2011-2014) |
| Attribution | Chicago Public Library |
| Category | Education |
| Tags | performance metrics, libraries |
| Created | 2011-09-15T22:52:09Z |
| Publication Date | 2015-01-12T19:43:08Z |

## Description

Number of WiFi sessions per month provided at Chicago Public Library locations.

## Columns

```ls
| Included | Schema Type    | Field Name                    | Name                          | Data Type | Render Type |
| ======== | ============== | ============================= | ============================= | ========= | =========== |
| No       |                | month                         | MONTH                         | text      | text        |
| No       |                | year                          | YEAR                          | number    | number      |
| Yes      | numeric metric | number_of_sessions            | NUMBER OF SESSIONS            | number    | number      |
| Yes      | numeric metric | cumulative_number_of_sessions | CUMULATIVE NUMBER OF SESSIONS | number    | number      |
```

## Time Field

```ls
Value = year-month
Format & Zone = yyyy-MMMM
```

## Series Fields

```ls
Excluded Fields = year,month
```

## Data Commands

```ls
series e:vbts-zqt4 d:2011-01-01T00:00:00.000Z m:number_of_sessions=22263 m:cumulative_number_of_sessions=22263

series e:vbts-zqt4 d:2011-02-01T00:00:00.000Z m:number_of_sessions=19657 m:cumulative_number_of_sessions=41920

series e:vbts-zqt4 d:2011-03-01T00:00:00.000Z m:number_of_sessions=24506 m:cumulative_number_of_sessions=66426
```

## Meta Commands

```ls
metric m:number_of_sessions p:integer l:"NUMBER OF SESSIONS" t:dataTypeName=number

metric m:cumulative_number_of_sessions p:integer l:"CUMULATIVE NUMBER OF SESSIONS" t:dataTypeName=number

entity e:vbts-zqt4 l:"Libraries - WiFi Usage (2011-2014)" t:attribution="Chicago Public Library" t:url=https://data.cityofchicago.org/api/views/vbts-zqt4

property e:vbts-zqt4 t:meta.view v:id=vbts-zqt4 v:category=Education v:attributionLink=http://chipublib.org v:averageRating=0 v:name="Libraries - WiFi Usage (2011-2014)" v:attribution="Chicago Public Library"

property e:vbts-zqt4 t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:vbts-zqt4 t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| month     | year | number_of_sessions | cumulative_number_of_sessions | 
| ========= | ==== | ================== | ============================= | 
| January   | 2011 | 22263              | 22263                         | 
| February  | 2011 | 19657              | 41920                         | 
| March     | 2011 | 24506              | 66426                         | 
| April     | 2011 | 23998              | 90424                         | 
| May       | 2011 | 23242              | 113666                        | 
| June      | 2011 | 26044              | 139710                        | 
| July      | 2011 | 27735              | 167445                        | 
| August    | 2011 | 33934              | 201379                        | 
| September | 2011 | 32714              | 234093                        | 
| October   | 2011 | 34760              | 268853                        | 
```