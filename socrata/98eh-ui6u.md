# SSMMA HUBZones

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ssmma-hubzones-20b87) |
| Metadata | [Link](https://data.illinois.gov/api/views/98eh-ui6u) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/98eh-ui6u/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/98eh-ui6u/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 98eh-ui6u |
| Name | SSMMA HUBZones |
| Attribution | South Suburban Mayors and Managers Association |
| Category | Municipality |
| Tags | hud, housing, economic development, planning |
| Created | 2012-11-27T20:53:02Z |
| Publication Date | 2012-11-27T20:55:00Z |

## Description

This dataset outlines HUB Zones by 2010 Census Tract ID Number in the Chicago Southland.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | objectid    | OBJECTID   | text      | number      |
| Yes      | numeric metric | countyfp10  | COUNTYFP10 | number    | number      |
| Yes      | numeric metric | tractce10   | TRACTCE10  | number    | number      |
| Yes      | numeric metric | geoid10     | GEOID10    | number    | number      |
| Yes      | series tag     | namelsad10  | NAMELSAD10 | text      | text        |
| Yes      | series tag     | mtfcc10     | MTFCC10    | text      | text        |
| Yes      | series tag     | funcstat10  | FUNCSTAT10 | text      | text        |
| Yes      | numeric metric | intptlat10  | INTPTLAT10 | number    | number      |
| Yes      | numeric metric | intptlon10  | INTPTLON10 | number    | number      |
| Yes      | series tag     | hub_zone    | HUB_Zone   | text      | text        |
| Yes      | numeric metric | location_1  | Location 1 | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:98eh-ui6u d:2012-11-27T12:53:04.000Z t:funcstat10=S t:namelsad10="Census Tract 424.03" t:hub_zone=No t:mtfcc10=G5020 t:objectid=1 m:countyfp10=89 m:tractce10=42403 m:geoid10=18089042403 m:intptlat10=42 m:location_1=18 m:intptlon10=-87

series e:98eh-ui6u d:2012-11-27T12:53:04.000Z t:funcstat10=S t:namelsad10="Census Tract 204" t:hub_zone=Yes t:mtfcc10=G5020 t:objectid=2 m:countyfp10=89 m:tractce10=20400 m:geoid10=18089020400 m:intptlat10=42 m:location_1=18 m:intptlon10=-88

series e:98eh-ui6u d:2012-11-27T12:53:04.000Z t:funcstat10=S t:namelsad10="Census Tract 205" t:hub_zone=No t:mtfcc10=G5020 t:objectid=3 m:countyfp10=89 m:tractce10=20500 m:geoid10=18089020500 m:intptlat10=42 m:location_1=18 m:intptlon10=-88
```

## Meta Commands

```ls
metric m:countyfp10 p:integer l:COUNTYFP10 t:dataTypeName=number

metric m:tractce10 p:integer l:TRACTCE10 t:dataTypeName=number

metric m:geoid10 p:long l:GEOID10 t:dataTypeName=number

metric m:intptlat10 p:integer l:INTPTLAT10 t:dataTypeName=number

metric m:intptlon10 p:integer l:INTPTLON10 t:dataTypeName=number

metric m:location_1 p:integer l:"Location 1" t:dataTypeName=number

entity e:98eh-ui6u l:"SSMMA HUBZones" t:attribution="South Suburban Mayors and Managers Association" t:url=https://data.illinois.gov/api/views/98eh-ui6u

property e:98eh-ui6u t:meta.view v:id=98eh-ui6u v:category=Municipality v:attributionLink=http://www.ssmma.org v:averageRating=0 v:name="SSMMA HUBZones" v:attribution="South Suburban Mayors and Managers Association"

property e:98eh-ui6u t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:98eh-ui6u t:meta.view.owner v:id=p88s-rkzf v:profileImageUrlMedium=/api/users/p88s-rkzf/profile_images/THUMB v:profileImageUrlLarge=/api/users/p88s-rkzf/profile_images/LARGE v:screenName=mrizzitiello v:profileImageUrlSmall=/api/users/p88s-rkzf/profile_images/TINY v:displayName=mrizzitiello

property e:98eh-ui6u t:meta.view.tableauthor v:id=74c3-ka9x v:profileImageUrlMedium=/api/users/74c3-ka9x/profile_images/THUMB v:profileImageUrlLarge=/api/users/74c3-ka9x/profile_images/LARGE v:screenName="Rey de Castro" v:profileImageUrlSmall=/api/users/74c3-ka9x/profile_images/TINY v:roleName=publisher v:displayName="Rey de Castro"
```

## Top Records

```ls
| :updated_at | objectid | countyfp10 | tractce10 | geoid10     | namelsad10          | mtfcc10 | funcstat10 | intptlat10 | intptlon10 | hub_zone | location_1 | 
| =========== | ======== | ========== | ========= | =========== | =================== | ======= | ========== | ========== | ========== | ======== | ========== | 
| 1354020784  | 1        | 89         | 42403     | 18089042403 | Census Tract 424.03 | G5020   | S          | 42         | -87        | No       | 18         | 
| 1354020784  | 2        | 89         | 20400     | 18089020400 | Census Tract 204    | G5020   | S          | 42         | -88        | Yes      | 18         | 
| 1354020784  | 3        | 89         | 20500     | 18089020500 | Census Tract 205    | G5020   | S          | 42         | -88        | No       | 18         | 
| 1354020784  | 4        | 89         | 42401     | 18089042401 | Census Tract 424.01 | G5020   | S          | 42         | -87        | No       | 18         | 
| 1354020784  | 5        | 89         | 20600     | 18089020600 | Census Tract 206    | G5020   | S          | 42         | -88        | Yes      | 18         | 
| 1354020784  | 6        | 89         | 20700     | 18089020700 | Census Tract 207    | G5020   | S          | 42         | -88        | Yes      | 18         | 
| 1354020784  | 7        | 89         | 20800     | 18089020800 | Census Tract 208    | G5020   | S          | 42         | -87        | No       | 18         | 
| 1354020784  | 8        | 89         | 20900     | 18089020900 | Census Tract 209    | G5020   | S          | 42         | -87        | No       | 18         | 
| 1354020784  | 9        | 89         | 21000     | 18089021000 | Census Tract 210    | G5020   | S          | 42         | -87        | No       | 18         | 
| 1354020784  | 10       | 89         | 22000     | 18089022000 | Census Tract 220    | G5020   | S          | 42         | -87        | No       | 18         | 
```