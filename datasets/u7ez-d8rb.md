# Water Quality Index Scores

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/water-quality-index-scores-65ea0) |
| Metadata | [Link](https://data.wa.gov/api/views/u7ez-d8rb) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/u7ez-d8rb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/u7ez-d8rb/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | u7ez-d8rb |
| Name | Water Quality Index Scores |
| Attribution | GSRO |
| Category | Natural Resources & Environment |
| Tags | wri, water quality, state-of-the-salmon |
| Created | 2014-11-23T00:11:58Z |
| Publication Date | 2014-11-25T18:23:08Z |

## Description

Water Quality Index scores by station. Used in conjunction with the WRIA_Stations dataset to produce the water quality tables for the bi-annual state of salmon report. (stateofsalmon.wa.gov)

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type | Render Type |
| ======== | ============== | =========== | =========== | ========= | =========== |
| Yes      | series tag     | station     | Station     | text      | text        |
| Yes      | time           | year        | Year        | number    | number      |
| Yes      | numeric metric | temperature | Temperature | number    | number      |
| Yes      | numeric metric | average     | Average     | number    | number      |
| Yes      | series tag     | comment     | Comment     | text      | text        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:u7ez-d8rb d:1995-01-01T00:00:00.000Z t:station=24B090 m:temperature=14

series e:u7ez-d8rb d:1996-01-01T00:00:00.000Z t:station=24B090 m:temperature=47

series e:u7ez-d8rb d:1997-01-01T00:00:00.000Z t:station=24B090 m:temperature=52
```

## Meta Commands

```ls
metric m:temperature p:integer l:Temperature t:dataTypeName=number

metric m:average p:integer l:Average t:dataTypeName=number

entity e:u7ez-d8rb l:"Water Quality Index Scores" t:attribution=GSRO t:url=https://data.wa.gov/api/views/u7ez-d8rb

property e:u7ez-d8rb t:meta.view v:id=u7ez-d8rb v:category="Natural Resources & Environment" v:averageRating=0 v:name="Water Quality Index Scores" v:attribution=GSRO

property e:u7ez-d8rb t:meta.view.license v:name="Public Domain"

property e:u7ez-d8rb t:meta.view.owner v:id=iq8s-snnt v:profileImageUrlMedium=/api/users/iq8s-snnt/profile_images/THUMB v:profileImageUrlLarge=/api/users/iq8s-snnt/profile_images/LARGE v:screenName="Ross Cowman" v:profileImageUrlSmall=/api/users/iq8s-snnt/profile_images/TINY v:displayName="Ross Cowman"

property e:u7ez-d8rb t:meta.view.tableauthor v:id=iq8s-snnt v:profileImageUrlMedium=/api/users/iq8s-snnt/profile_images/THUMB v:profileImageUrlLarge=/api/users/iq8s-snnt/profile_images/LARGE v:screenName="Ross Cowman" v:profileImageUrlSmall=/api/users/iq8s-snnt/profile_images/TINY v:roleName=publisher v:displayName="Ross Cowman"
```

## Top Records

```ls
| station | year | temperature | average | comment | 
| ======= | ==== | =========== | ======= | ======= | 
| 24B090  | 1994 |             |         |         | 
| 24B090  | 1995 | 14          |         |         | 
| 24B090  | 1996 | 47          |         |         | 
| 24B090  | 1997 | 52          |         |         | 
| 24B090  | 1998 | 29          |         |         | 
| 24B090  | 1999 | 33          |         |         | 
| 24B090  | 2000 | 51          |         |         | 
| 24B090  | 2001 | 56          |         |         | 
| 24B090  | 2002 | 32          |         |         | 
| 24B090  | 2003 | 55          |         |         | 
```