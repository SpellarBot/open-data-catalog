# Maryland Total Labor Force Projections: 1970-2040

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/maryland-total-labor-force-projections-1970-2040-af701) |
| Metadata | [Link](https://data.maryland.gov/api/views/fu9m-u32s) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/fu9m-u32s/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/fu9m-u32s/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | fu9m-u32s |
| Name | Maryland Total Labor Force Projections: 1970-2040 |
| Attribution | Maryland Department of Planning |
| Tags | total, labor force, projections, planning, mdp |
| Created | 2014-09-02T19:26:58Z |
| Publication Date | 2014-09-02T19:28:33Z |

## Description

Historical and Projected Labor Force in Maryland and its Jurisdictions, 1970-2040. Projected numbers are rounded to the nearest 10. Prepared by the Maryland Department of Planning, July 2014.

## Columns

```ls
| Included | Schema Type    | Field Name      | Name             | Data Type | Render Type |
| ======== | ============== | =============== | ================ | ========= | =========== |
| Yes      | series tag     | jurisdiction    | Jurisdiction     | text      | text        |
| Yes      | numeric metric | census_1970     | Census, 1970     | number    | number      |
| Yes      | numeric metric | census_1980     | Census, 1980     | number    | number      |
| Yes      | numeric metric | census_1990     | Census, 1990     | number    | number      |
| Yes      | numeric metric | census_2000     | Census, 2000     | number    | number      |
| Yes      | numeric metric | census_2010     | Census, 2010     | number    | number      |
| Yes      | numeric metric | acs_2008_12     | ACS, 2008-12     | number    | number      |
| Yes      | numeric metric | projection_2015 | Projection, 2015 | number    | number      |
| Yes      | numeric metric | projection_2020 | Projection, 2020 | number    | number      |
| Yes      | numeric metric | projection_2025 | Projection, 2025 | number    | number      |
| Yes      | numeric metric | projection_2030 | Projection, 2030 | number    | number      |
| Yes      | numeric metric | projection_2035 | Projection, 2035 | number    | number      |
| Yes      | numeric metric | projection_2040 | Projection, 2040 | number    | number      |
```

## Time Field

```ls
Value = 1970
Format & Zone = yyyy
```

## Data Commands

```ls
series e:fu9m-u32s d:1970-01-01T00:00:00.000Z t:jurisdiction=MARYLAND m:acs_2008_12=3199290 m:projection_2020=3401820 m:projection_2035=3551430 m:census_1980=2108296 m:census_2000=2769525 m:census_1990=2639896 m:census_2010=3188720 m:projection_2040=3617270 m:projection_2030=3506500 m:projection_2025=3461470 m:projection_2015=3313390 m:census_1970=1655695

series e:fu9m-u32s d:1970-01-01T00:00:00.000Z t:jurisdiction="Allegany County" m:acs_2008_12=33860 m:projection_2020=33860 m:projection_2035=34830 m:census_1980=33105 m:census_2000=32996 m:census_1990=32439 m:census_2010=34080 m:projection_2040=35280 m:projection_2030=34560 m:projection_2025=34160 m:projection_2015=33800 m:census_1970=30522

series e:fu9m-u32s d:1970-01-01T00:00:00.000Z t:jurisdiction="Anne Arundel County" m:acs_2008_12=303444 m:projection_2020=317550 m:projection_2035=325420 m:census_1980=191378 m:census_2000=269772 m:census_1990=245789 m:census_2010=302650 m:projection_2040=329980 m:projection_2030=322490 m:projection_2025=319930 m:projection_2015=310710 m:census_1970=127080
```

## Meta Commands

```ls
metric m:census_1970 p:integer l:"Census, 1970" t:dataTypeName=number

metric m:census_1980 p:integer l:"Census, 1980" t:dataTypeName=number

metric m:census_1990 p:integer l:"Census, 1990" t:dataTypeName=number

metric m:census_2000 p:integer l:"Census, 2000" t:dataTypeName=number

metric m:census_2010 p:integer l:"Census, 2010" t:dataTypeName=number

metric m:acs_2008_12 p:integer l:"ACS, 2008-12" t:dataTypeName=number

metric m:projection_2015 p:integer l:"Projection, 2015" t:dataTypeName=number

metric m:projection_2020 p:integer l:"Projection, 2020" t:dataTypeName=number

metric m:projection_2025 p:integer l:"Projection, 2025" t:dataTypeName=number

metric m:projection_2030 p:integer l:"Projection, 2030" t:dataTypeName=number

metric m:projection_2035 p:integer l:"Projection, 2035" t:dataTypeName=number

metric m:projection_2040 p:integer l:"Projection, 2040" t:dataTypeName=number

entity e:fu9m-u32s l:"Maryland Total Labor Force Projections: 1970-2040" t:attribution="Maryland Department of Planning" t:url=https://data.maryland.gov/api/views/fu9m-u32s

property e:fu9m-u32s t:meta.view v:id=fu9m-u32s v:attributionLink=http://planning.maryland.gov/msdc/S3_Projection.shtml v:averageRating=0 v:name="Maryland Total Labor Force Projections: 1970-2040" v:attribution="Maryland Department of Planning"

property e:fu9m-u32s t:meta.view.owner v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:displayName=MDP

property e:fu9m-u32s t:meta.view.tableauthor v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:roleName=editor v:displayName=MDP
```

## Top Records

```ls
| jurisdiction        | census_1970 | census_1980 | census_1990 | census_2000 | census_2010 | acs_2008_12 | projection_2015 | projection_2020 | projection_2025 | projection_2030 | projection_2035 | projection_2040 | 
| =================== | =========== | =========== | =========== | =========== | =========== | =========== | =============== | =============== | =============== | =============== | =============== | =============== | 
| MARYLAND            | 1655695     | 2108296     | 2639896     | 2769525     | 3188720     | 3199290     | 3313390         | 3401820         | 3461470         | 3506500         | 3551430         | 3617270         | 
| Allegany County     | 30522       | 33105       | 32439       | 32996       | 34080       | 33860       | 33800           | 33860           | 34160           | 34560           | 34830           | 35280           | 
| Anne Arundel County | 127080      | 191378      | 245789      | 269772      | 302650      | 303444      | 310710          | 317550          | 319930          | 322490          | 325420          | 329980          | 
| Baltimore City      | 372198      | 344984      | 347593      | 287159      | 315300      | 314932      | 325220          | 332200          | 337100          | 342280          | 348210          | 356270          | 
| Baltimore County    | 268805      | 345198      | 381531      | 396897      | 440380      | 442233      | 451450          | 454830          | 453610          | 451700          | 453150          | 458880          | 
| Calvert County      | 7521        | 15564       | 28047       | 39341       | 48980       | 49063       | 50690           | 52240           | 52220           | 51370           | 50700           | 50920           | 
| Caroline County     | 7746        | 10575       | 13820       | 15045       | 17230       | 17245       | 17550           | 18470           | 19410           | 20190           | 21070           | 22120           | 
| Carroll County      | 27898       | 46998       | 67905       | 80767       | 92050       | 92213       | 93150           | 96310           | 95410           | 93680           | 92660           | 94190           | 
| Cecil County        | 22159       | 26372       | 37030       | 44866       | 52870       | 52900       | 53940           | 55940           | 59370           | 62000           | 64600           | 67670           | 
| Charles County      | 17482       | 33692       | 56587       | 64983       | 81600       | 82244       | 86470           | 94290           | 100670          | 104160          | 107440          | 111080          | 
```