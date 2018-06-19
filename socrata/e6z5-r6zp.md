# Artificial Reef Aerial Survey Boat Count: Beginning 1995

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/artificial-reef-aerial-survey-boat-count-beginning-1995) |
| Metadata | [Link](https://data.ny.gov/api/views/e6z5-r6zp) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/e6z5-r6zp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/e6z5-r6zp/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | e6z5-r6zp |
| Name | Artificial Reef Aerial Survey Boat Count: Beginning 1995 |
| Attribution | NYSDEC Division of Marine Resources |
| Category | Recreation |
| Tags | artificial reefs, fishing, boating, diving, marine habitat |
| Created | 2016-11-22T19:52:22Z |
| Publication Date | 2016-11-22T20:34:17Z |

## Description

This file provides the boat count information resulting from the Artificial Reef Aerial Survey including the date of flight, reef observed, number of small boats observed, and number of large boats observed. Large boats are defined as party and charter boats.

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type     | Render Type   |
| ======== | ============== | =============== | =============== | ============= | ============= |
| Yes      | series tag     | reef            | Reef            | text          | text          |
| Yes      | time           | date            | Date            | calendar_date | calendar_date |
| Yes      | series tag     | boat_type       | Boat Type       | text          | text          |
| Yes      | numeric metric | number_of_boats | Number of Boats | number        | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:e6z5-r6zp d:1995-04-07T00:00:00.000Z t:reef="Atlantic Beach" t:boat_type=Small m:number_of_boats=0

series e:e6z5-r6zp d:1995-04-07T00:00:00.000Z t:reef="Atlantic Beach" t:boat_type=Large m:number_of_boats=0

series e:e6z5-r6zp d:1995-05-14T00:00:00.000Z t:reef="Atlantic Beach" t:boat_type=Small m:number_of_boats=7
```

## Meta Commands

```ls
metric m:number_of_boats p:integer l:"Number of Boats" d:"Number of boats counted on reef." t:dataTypeName=number

entity e:e6z5-r6zp l:"Artificial Reef Aerial Survey Boat Count: Beginning 1995" t:attribution="NYSDEC Division of Marine Resources" t:url=https://data.ny.gov/api/views/e6z5-r6zp

property e:e6z5-r6zp t:meta.view v:id=e6z5-r6zp v:category=Recreation v:attributionLink=http://www.dec.ny.gov/outdoor/7896.html v:averageRating=0 v:name="Artificial Reef Aerial Survey Boat Count: Beginning 1995" v:attribution="NYSDEC Division of Marine Resources"

property e:e6z5-r6zp t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:e6z5-r6zp t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| reef           | date                | boat_type | number_of_boats | 
| ============== | =================== | ========= | =============== | 
| Atlantic Beach | 1995-04-07T00:00:00 | Small     | 0               | 
| Atlantic Beach | 1995-04-07T00:00:00 | Large     | 0               | 
| Atlantic Beach | 1995-05-14T00:00:00 | Small     | 7               | 
| Atlantic Beach | 1995-05-14T00:00:00 | Large     | 0               | 
| Atlantic Beach | 1995-06-10T00:00:00 | Small     | 4               | 
| Atlantic Beach | 1995-06-10T00:00:00 | Large     | 0               | 
| Atlantic Beach | 1995-07-09T00:00:00 | Small     | 3               | 
| Atlantic Beach | 1995-07-09T00:00:00 | Large     | 0               | 
| Atlantic Beach | 1995-08-19T00:00:00 | Small     | 0               | 
| Atlantic Beach | 1995-08-19T00:00:00 | Large     | 0               | 
```