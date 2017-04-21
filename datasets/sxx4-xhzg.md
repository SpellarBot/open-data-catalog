# Public Recycling Bins

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/public-recycling-bins-eb48e) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/sxx4-xhzg) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/sxx4-xhzg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/sxx4-xhzg/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | sxx4-xhzg |
| Name | Public Recycling Bins |
| Attribution | Department of Sanitation (DSNY) |
| Category | Environment |
| Tags | public recycling bins, environmental sustainability, green, garbage, sanitation, dsny, bins, recycle, dispose, reduce, reuse, clean web |
| Created | 2012-06-29T20:51:12Z |
| Publication Date | 2013-06-21T19:42:37Z |

## Description

Locations of public recycling bins throughout NYC

## Columns

```ls
| Included | Schema Type | Field Name     | Name           | Data Type | Render Type |
| ======== | =========== | ============== | ============== | ========= | =========== |
| No       | time        | :updated_at    | updated_at     | meta_data | meta_data   |
| Yes      | series tag  | borough        | Borough        | text      | text        |
| Yes      | series tag  | site_type      | Site type      | text      | text        |
| Yes      | series tag  | park_site_name | Park/Site Name | text      | text        |
| No       |             | address        | Address        | text      | text        |
| No       |             | latitude       | Latitude       | number    | number      |
| No       |             | longitude      | Longitude      | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address,latitude,longitude
```

## Data Commands

```ls
series e:sxx4-xhzg d:2012-06-29T13:51:13.000Z t:site_type=Subproperty t:borough=Bronx t:park_site_name="227th St. Plgd" m:row_number.sxx4-xhzg=1

series e:sxx4-xhzg d:2012-06-29T13:51:13.000Z t:site_type=Subproperty t:borough=Bronx t:park_site_name="Allerton Ballfields" m:row_number.sxx4-xhzg=2

series e:sxx4-xhzg d:2012-06-29T13:51:13.000Z t:site_type=Outdoor t:borough=Bronx t:park_site_name="Arthur Ave & E 187 St" m:row_number.sxx4-xhzg=3
```

## Meta Commands

```ls
metric m:row_number.sxx4-xhzg p:long l:"Row Number"

entity e:sxx4-xhzg l:"Public Recycling Bins" t:attribution="Department of Sanitation (DSNY)" t:url=https://data.cityofnewyork.us/api/views/sxx4-xhzg

property e:sxx4-xhzg t:meta.view v:id=sxx4-xhzg v:category=Environment v:averageRating=0 v:name="Public Recycling Bins" v:attribution="Department of Sanitation (DSNY)"

property e:sxx4-xhzg t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:sxx4-xhzg t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | borough | site_type   | park_site_name          | address                         | latitude           | longitude           | 
| =========== | ======= | =========== | ======================= | =============================== | ================== | =================== | 
| 1340977873  | Bronx   | Subproperty | 227th St. Plgd          | E 227 St/Bronx River Pkway      | 40.890848989       | -73.864223918       | 
| 1340977873  | Bronx   | Subproperty | Allerton Ballfields     | Allerton Ave & Moshulu Pkway    | 40.8488907878      | -73.8771283938      | 
| 1340977873  | Bronx   | Outdoor     | Arthur Ave & E 187 St   | Arthur Ave & 187 St             | 40.85557           | -73.887564999999995 | 
| 1340977873  | Bronx   | Outdoor     | Barstow Mansion         | 895 Shore Road, Pelham Bay Park | 40.871864          | -73.805549          | 
| 1340977873  | Bronx   | Subproperty | Bradley Playground      | 2001-2017 Bronx Park E          | 40.851889          | -73.868549          | 
| 1340977873  | Bronx   | Outdoor     | Bronx Botanical Gardens | Visitors Service Center         | 40.861525999999998 | -73.880658999999994 | 
| 1340977873  | Bronx   | Outdoor     | Bronx Botanical Gardens | Visitors Service Center         | 40.860754999999997 | -73.880422999999993 | 
| 1340977873  | Bronx   | Outdoor     | Bronx Botanical Gardens | Visitors Service Center         | 40.859644000000003 | -73.880471999999997 | 
| 1340977873  | Bronx   | Outdoor     | Bronx Botanical Gardens | Visitors Service Center         | 40.862602000000003 | -73.880171000000004 | 
| 1340977873  | Bronx   | Outdoor     | Bronx County Courthouse | 161 ST/Grand Concourse          | 40.826939          | -73.922314          | 
```