# Traffic Flow Map Volumes

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/traffic-flow-map-volumes) |
| Metadata | [Link](https://data.seattle.gov/api/views/38vd-gytv) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/38vd-gytv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/38vd-gytv/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | 38vd-gytv |
| Name | Traffic Flow Map Volumes |
| Attribution | SDOT |
| Category | Transportation |
| Tags | transportation, sdot, volume, traffic counts, traffic flow map |
| Created | 2016-01-04T16:42:14Z |
| Publication Date | 2016-01-04T16:53:14Z |

## Description

Average annual weekday traffic volumes used to produce the SDOT Traffic Flow Map

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| No       | time           | :updated_at    | updated_at     | meta_data | meta_data   |
| Yes      | series tag     | objectid       | OBJECTID       | text      | number      |
| Yes      | series tag     | stname         | STNAME         | text      | text        |
| Yes      | series tag     | count_location | COUNT_LOCATION | text      | text        |
| Yes      | numeric metric | year           | YEAR           | number    | number      |
| Yes      | numeric metric | segkey         | SEGKEY         | number    | number      |
| Yes      | numeric metric | aawdt          | AAWDT          | number    | number      |
| Yes      | series tag     | input_study_id | INPUT_STUDY_ID | text      | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:38vd-gytv d:2016-01-04T08:42:16.000Z t:input_study_id=315994 t:stname="RENTON AVE S" t:objectid=1 t:count_location="RENTON AVE S, N/O S CLOVERDALE ST" m:segkey=12522 m:aawdt=9800 m:year=2014

series e:38vd-gytv d:2016-01-04T08:42:16.000Z t:input_study_id=316688 t:stname="AIRPORT WAY S" t:objectid=2 t:count_location="AIRPORT WAY S, N/O S NORFOLK ST" m:segkey=8702 m:aawdt=12300 m:year=2014

series e:38vd-gytv d:2016-01-04T08:42:16.000Z t:input_study_id=314379 t:stname="N 65TH ST" t:objectid=3 t:count_location="N 65TH ST, W/O LINDEN AVE N" m:segkey=15794 m:aawdt=7800 m:year=2014
```

## Meta Commands

```ls
metric m:year p:integer l:YEAR t:dataTypeName=number

metric m:segkey p:integer l:SEGKEY t:dataTypeName=number

metric m:aawdt p:integer l:AAWDT t:dataTypeName=number

entity e:38vd-gytv l:"Traffic Flow Map Volumes" t:attribution=SDOT t:url=https://data.seattle.gov/api/views/38vd-gytv

property e:38vd-gytv t:meta.view v:id=38vd-gytv v:category=Transportation v:attributionLink=http://www.seattle.gov/transportation/tfdmaps.htm v:averageRating=0 v:name="Traffic Flow Map Volumes" v:attribution=SDOT

property e:38vd-gytv t:meta.view.owner v:id=c7xs-eh4s v:screenName="Moore, Craig" v:displayName="Moore, Craig"

property e:38vd-gytv t:meta.view.tableauthor v:id=c7xs-eh4s v:screenName="Moore, Craig" v:roleName=publisher v:displayName="Moore, Craig"
```

## Top Records

```ls
| :updated_at | objectid | stname           | count_location                        | year | segkey | aawdt | input_study_id | 
| =========== | ======== | ================ | ===================================== | ==== | ====== | ===== | ============== | 
| 1451896936  | 1        | RENTON AVE S     | RENTON AVE S, N/O S CLOVERDALE ST     | 2014 | 12522  | 9800  | 315994         | 
| 1451896936  | 2        | AIRPORT WAY S    | AIRPORT WAY S, N/O S NORFOLK ST       | 2014 | 8702   | 12300 | 316688         | 
| 1451896936  | 3        | N 65TH ST        | N 65TH ST, W/O LINDEN AVE N           | 2014 | 15794  | 7800  | 314379         | 
| 1451896936  | 4        | 2ND AVE          | 2ND AVE, NW/O LENORA ST               | 2014 | 2762   | 11900 | 313796         | 
| 1451896936  | 5        | LAKE CITY WAY NE | LAKE CITY WAY NE, S/O NE 145TH ST     | 2014 | 11190  | 40900 | 316269         | 
| 1451896936  | 6        | JAMES ST         | JAMES ST, NE/O 7TH AVE                | 2014 | 11055  | 21100 | 316562         | 
| 1451896936  | 7        | GREENWOOD AVE N  | GREENWOOD AVE N, S/O N 145TH ST       | 2014 | 10795  | 21800 | 315172         | 
| 1451896936  | 8        | RENTON AVE S     | RENTON AVE S, SE/O S HENDERSON ST     | 2014 | 12525  | 7200  | 315996         | 
| 1451896936  | 9        | 4TH AVE          | 4TH AVE, NW/O LENORA ST               | 2014 | 6138   | 14100 | 315087         | 
| 1451896936  | 10       | DELRIDGE WAY SW  | DELRIDGE WAY SW, NW/O SW CAMBRIDGE ST | 2014 | 9992   | 11900 | 315106         | 
```