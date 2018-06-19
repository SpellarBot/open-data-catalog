# Census Tracts with Town Names (2010)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/census-tracts-with-town-names-2010) |
| Metadata | [Link](https://data.ct.gov/api/views/f43y-uvqp) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/f43y-uvqp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/f43y-uvqp/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | f43y-uvqp |
| Name | Census Tracts with Town Names (2010) |
| Category | Government |
| Tags | census, tract, town |
| Created | 2017-01-30T14:50:42Z |
| Publication Date | 2017-01-30T14:55:23Z |

## Description

A listing of Census Tracts including the names of towns in which they fall for CT. In 2010, the Census tract data no longer contained information necessary to associate tracts with towns (Minor Civil Division in Census terms). This file was generated to allow data users in CT to summarize census data to the town level in Connecticut

## Columns

```ls
| Included | Schema Type    | Field Name | Name       | Data Type | Render Type |
| ======== | ============== | ========== | ========== | ========= | =========== |
| Yes      | series tag     | fid        | FID        | text      | number      |
| Yes      | numeric metric | statefp10  | STATEFP10  | number    | number      |
| Yes      | numeric metric | countyfp10 | COUNTYFP10 | number    | number      |
| Yes      | numeric metric | tractce10  | TRACTCE10  | number    | number      |
| Yes      | numeric metric | name10     | NAME10     | number    | number      |
| Yes      | series tag     | namelsad10 | NAMELSAD10 | text      | text        |
| Yes      | series tag     | mtfcc10    | MTFCC10    | text      | text        |
| Yes      | series tag     | funcstat10 | FUNCSTAT10 | text      | text        |
| Yes      | numeric metric | aland10    | ALAND10    | number    | number      |
| Yes      | numeric metric | awater10   | AWATER10   | number    | number      |
| Yes      | numeric metric | intptlat10 | INTPTLAT10 | number    | number      |
| Yes      | numeric metric | intptlon10 | INTPTLON10 | number    | number      |
| Yes      | series tag     | geoid      | GEOID      | text      | number      |
| Yes      | series tag     | full_geoid | Full_GEOID | text      | text        |
| Yes      | series tag     | town       | Town       | text      | text        |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:f43y-uvqp d:2010-01-01T00:00:00.000Z t:fid=0 t:namelsad10="Census Tract 303" t:funcstat10=S t:full_geoid=1400000US09001030300 t:town=Darien t:mtfcc10=G5020 t:geoid=9001030300 m:countyfp10=1 m:tractce10=30300 m:name10=303 m:intptlat10=41.0563491 m:aland10=8268946 m:statefp10=9 m:intptlon10=-73.473651 m:awater10=5919424

series e:f43y-uvqp d:2010-01-01T00:00:00.000Z t:fid=1 t:namelsad10="Census Tract 353" t:funcstat10=S t:full_geoid=1400000US09001035300 t:town="New Canaan" t:mtfcc10=G5020 t:geoid=9001035300 m:countyfp10=1 m:tractce10=35300 m:name10=353 m:intptlat10=41.1215292 m:aland10=13442741 m:statefp10=9 m:intptlon10=-73.4784315 m:awater10=46233

series e:f43y-uvqp d:2010-01-01T00:00:00.000Z t:fid=2 t:namelsad10="Census Tract 110" t:funcstat10=S t:full_geoid=1400000US09001011000 t:town=Greenwich t:mtfcc10=G5020 t:geoid=9001011000 m:countyfp10=1 m:tractce10=11000 m:name10=110 m:intptlat10=41.0122609 m:aland10=4449326 m:statefp10=9 m:intptlon10=-73.5766968 m:awater10=3865378
```

## Meta Commands

```ls
metric m:statefp10 p:integer l:STATEFP10 t:dataTypeName=number

metric m:countyfp10 p:integer l:COUNTYFP10 t:dataTypeName=number

metric m:tractce10 p:integer l:TRACTCE10 t:dataTypeName=number

metric m:name10 p:double l:NAME10 t:dataTypeName=number

metric m:aland10 p:integer l:ALAND10 t:dataTypeName=number

metric m:awater10 p:integer l:AWATER10 t:dataTypeName=number

metric m:intptlat10 p:double l:INTPTLAT10 t:dataTypeName=number

metric m:intptlon10 p:double l:INTPTLON10 t:dataTypeName=number

entity e:f43y-uvqp l:"Census Tracts with Town Names (2010)" t:url=https://data.ct.gov/api/views/f43y-uvqp

property e:f43y-uvqp t:meta.view v:id=f43y-uvqp v:category=Government v:averageRating=0 v:name="Census Tracts with Town Names (2010)"

property e:f43y-uvqp t:meta.view.license v:name="Public Domain"

property e:f43y-uvqp t:meta.view.owner v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"

property e:f43y-uvqp t:meta.view.tableauthor v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"
```

## Top Records

```ls
| fid | statefp10 | countyfp10 | tractce10 | name10 | namelsad10        | mtfcc10 | funcstat10 | aland10  | awater10 | intptlat10 | intptlon10  | geoid      | full_geoid           | town       | 
| === | ========= | ========== | ========= | ====== | ================= | ======= | ========== | ======== | ======== | ========== | =========== | ========== | ==================== | ========== | 
| 0   | 9         | 1          | 30300     | 303    | Census Tract 303  | G5020   | S          | 8268946  | 5919424  | 41.0563491 | -73.4736510 | 9001030300 | 1400000US09001030300 | Darien     | 
| 1   | 9         | 1          | 35300     | 353    | Census Tract 353  | G5020   | S          | 13442741 | 46233    | 41.1215292 | -73.4784315 | 9001035300 | 1400000US09001035300 | New Canaan | 
| 2   | 9         | 1          | 11000     | 110    | Census Tract 110  | G5020   | S          | 4449326  | 3865378  | 41.0122609 | -73.5766968 | 9001011000 | 1400000US09001011000 | Greenwich  | 
| 3   | 9         | 1          | 30100     | 301    | Census Tract 301  | G5020   | S          | 11024824 | 27898    | 41.1006634 | -73.4881986 | 9001030100 | 1400000US09001030100 | Darien     | 
| 4   | 9         | 1          | 30200     | 302    | Census Tract 302  | G5020   | S          | 4579450  | 45867    | 41.0854982 | -73.4644649 | 9001030200 | 1400000US09001030200 | Darien     | 
| 5   | 9         | 1          | 30400     | 304    | Census Tract 304  | G5020   | S          | 3552882  | 0        | 41.0670034 | -73.4899354 | 9001030400 | 1400000US09001030400 | Darien     | 
| 6   | 9         | 1          | 30500     | 305    | Census Tract 305  | G5020   | S          | 5351221  | 5422     | 41.0808098 | -73.5000669 | 9001030500 | 1400000US09001030500 | Darien     | 
| 7   | 9         | 1          | 105100    | 1051   | Census Tract 1051 | G5020   | S          | 31837542 | 1272596  | 41.2338658 | -73.3085559 | 9001105100 | 1400000US09001105100 | Easton     | 
| 8   | 9         | 1          | 105200    | 1052   | Census Tract 1052 | G5020   | S          | 39176156 | 1945200  | 41.2806799 | -73.2995681 | 9001105200 | 1400000US09001105200 | Easton     | 
| 9   | 9         | 1          | 60100     | 601    | Census Tract 601  | G5020   | S          | 3985964  | 0        | 41.2140780 | -73.2415497 | 9001060100 | 1400000US09001060100 | Fairfield  | 
```