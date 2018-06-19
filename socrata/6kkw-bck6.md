# Police Stations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/police-stations-837be) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/6kkw-bck6) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/6kkw-bck6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/6kkw-bck6/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | 6kkw-bck6 |
| Name | Police Stations |
| Attribution | Baltimore Police Department |
| Category | Public Safety |
| Tags | police |
| Created | 2011-12-14T18:47:49Z |
| Publication Date | 2014-04-03T23:43:27Z |

## Description

The location of the 9 police district stations plus Police Headquarters.

## Columns

```ls
| Included | Schema Type | Field Name      | Name            | Data Type | Render Type |
| ======== | =========== | =============== | =============== | ========= | =========== |
| No       | time        | :updated_at     | updated_at      | meta_data | meta_data   |
| Yes      | series tag  | name            | name            | text      | text        |
| Yes      | series tag  | type            | type            | text      | text        |
| Yes      | series tag  | zipcode         | zipCode         | text      | text        |
| Yes      | series tag  | neighborhood    | neighborhood    | text      | text        |
| Yes      | series tag  | councildistrict | councilDistrict | text      | number      |
| Yes      | series tag  | policedistrict  | policeDistrict  | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:6kkw-bck6 d:2011-12-14T10:48:00.000Z t:councildistrict=11 t:zipcode=21202 t:name=Headquarters t:neighborhood=Downtown t:policedistrict=CENTRAL t:type=Headquarters m:row_number.6kkw-bck6=1

series e:6kkw-bck6 d:2011-12-14T10:48:00.000Z t:councildistrict=11 t:zipcode=21202 t:name=Central t:neighborhood=Downtown t:policedistrict=CENTRAL t:type="Police Station" m:row_number.6kkw-bck6=2

series e:6kkw-bck6 d:2011-12-14T10:48:00.000Z t:councildistrict=6 t:zipcode=21215 t:name=Northern t:neighborhood=Woodberry t:policedistrict=NORTHERN t:type="Police Station" m:row_number.6kkw-bck6=3
```

## Meta Commands

```ls
metric m:row_number.6kkw-bck6 p:long l:"Row Number"

entity e:6kkw-bck6 l:"Police Stations" t:attribution="Baltimore Police Department" t:url=https://data.baltimorecity.gov/api/views/6kkw-bck6

property e:6kkw-bck6 t:meta.view v:id=6kkw-bck6 v:category="Public Safety" v:attributionLink=http://www.baltimorepolice.org/ v:averageRating=0 v:name="Police Stations" v:attribution="Baltimore Police Department"

property e:6kkw-bck6 t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:6kkw-bck6 t:meta.view.owner v:id=dnxm-4h22 v:screenName=MOCS v:displayName=MOCS

property e:6kkw-bck6 t:meta.view.tableauthor v:id=dnxm-4h22 v:screenName=MOCS v:displayName=MOCS
```

## Top Records

```ls
| :updated_at | name         | type           | zipcode | neighborhood                 | councildistrict | policedistrict | 
| =========== | ============ | ============== | ======= | ============================ | =============== | ============== | 
| 1323859680  | Headquarters | Headquarters   | 21202   | Downtown                     | 11              | CENTRAL        | 
| 1323859680  | Central      | Police Station | 21202   | Downtown                     | 11              | CENTRAL        | 
| 1323859680  | Northern     | Police Station | 21215   | Woodberry                    | 6               | NORTHERN       | 
| 1323859680  | Northeastern | Police Station | 21218   | Morgan State University      | 3               | NORTHEASTERN   | 
| 1323859680  | Northwestern | Police Station | 21215   | Woodmere                     | 5               | NORTHWESTERN   | 
| 1323859680  | Eastern      | Police Station | 21213   | Berea                        | 13              | EASTERN        | 
| 1323859680  | Southern     | Police Station | 21225   | Middle Branch/Reedbird Parks | 10              | SOUTHERN       | 
| 1323859680  | Southeastern | Police Station | 21224   | Hopkins Bayview              | 2               | SOUTHEASTERN   | 
| 1323859680  | Southwestern | Police Station | 21223   | Gwynns Falls                 | 8               | SOUTHWESTERN   | 
| 1323859680  | Western      | Police Station | 21217   | Sandtown-Winchester          | 9               | WESTERN        | 
```