# School Districts

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/school-districts-8e106) |
| Metadata | [Link](https://data.mo.gov/api/views/ny2h-ckbz) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/ny2h-ckbz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/ny2h-ckbz/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | ny2h-ckbz |
| Name | School Districts |
| Created | 2015-06-16T14:53:04Z |
| Publication Date | 2015-06-16T14:53:41Z |

## Columns

```ls
| Included | Schema Type    | Field Name        | Name               | Data Type    | Render Type  |
| ======== | ============== | ================= | ================== | ============ | ============ |
| No       | time           | :updated_at       | updated_at         | meta_data    | meta_data    |
| Yes      | series tag     | feature_id        | _feature_id        | text         | number       |
| Yes      | series tag     | feature_id_string | _feature_id_string | text         | text         |
| No       |                | the_geom          | the_geom           | multipolygon | multipolygon |
| Yes      | series tag     | statefp10         | statefp10          | text         | text         |
| Yes      | series tag     | elsdlea10         | elsdlea10          | text         | text         |
| Yes      | series tag     | geoid10           | geoid10            | text         | text         |
| Yes      | series tag     | name10            | name10             | text         | text         |
| Yes      | series tag     | dist_name         | dist_name          | text         | text         |
| Yes      | series tag     | dist_code         | dist_code          | text         | text         |
| Yes      | series tag     | codist            | codist             | text         | text         |
| Yes      | series tag     | lsad10            | lsad10             | text         | text         |
| Yes      | series tag     | lograde10         | lograde10          | text         | text         |
| Yes      | series tag     | higrade10         | higrade10          | text         | text         |
| Yes      | series tag     | mtfcc10           | mtfcc10            | text         | text         |
| Yes      | series tag     | sdtyp10           | sdtyp10            | text         | text         |
| Yes      | series tag     | funcstat10        | funcstat10         | text         | text         |
| Yes      | numeric metric | aland10           | aland10            | number       | number       |
| Yes      | numeric metric | awater10          | awater10           | number       | number       |
| Yes      | series tag     | intptlat10        | intptlat10         | text         | text         |
| Yes      | series tag     | intptlon10        | intptlon10         | text         | text         |
| Yes      | numeric metric | pop90             | pop90              | number       | number       |
| Yes      | numeric metric | white90           | white90            | number       | number       |
| Yes      | numeric metric | black90           | black90            | number       | number       |
| Yes      | numeric metric | asian90           | asian90            | number       | number       |
| Yes      | numeric metric | amind90           | amind90            | number       | number       |
| Yes      | numeric metric | other90           | other90            | number       | number       |
| Yes      | numeric metric | hisp90            | hisp90             | number       | number       |
| Yes      | numeric metric | pop00             | pop00              | number       | number       |
| Yes      | numeric metric | white00           | white00            | number       | number       |
| Yes      | numeric metric | black00           | black00            | number       | number       |
| Yes      | numeric metric | asian00           | asian00            | number       | number       |
| Yes      | numeric metric | amind00           | amind00            | number       | number       |
| Yes      | numeric metric | hawnpi00          | hawnpi00           | number       | number       |
| Yes      | numeric metric | other00           | other00            | number       | number       |
| Yes      | numeric metric | multra00          | multra00           | number       | number       |
| Yes      | numeric metric | hisp00            | hisp00             | number       | number       |
| Yes      | numeric metric | pop10             | pop10              | number       | number       |
| Yes      | numeric metric | white10           | white10            | number       | number       |
| Yes      | numeric metric | black10           | black10            | number       | number       |
| Yes      | numeric metric | asian10           | asian10            | number       | number       |
| Yes      | numeric metric | amind10           | amind10            | number       | number       |
| Yes      | numeric metric | hawnpi10          | hawnpi10           | number       | number       |
| Yes      | numeric metric | other10           | other10            | number       | number       |
| Yes      | numeric metric | multra10          | multra10           | number       | number       |
| Yes      | numeric metric | hisp10            | hisp10             | number       | number       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = the_geom
```

## Data Commands

```ls
series e:ny2h-ckbz d:2015-06-16T14:53:35.000Z t:higrade10=12 t:funcstat10=E t:name10="Maryville R-II School District" t:mtfcc10=G5420 t:geoid10=2920490 t:feature_id_string=MO_2013_School_Districts_shp.1 t:statefp10=29 t:lograde10=PK t:feature_id=1 t:lsad10=00 t:dist_code=074201 t:dist_name="Maryville R-II" t:intptlat10=+40.3426688 t:codist=074-201 t:intptlon10=-094.8788717 m:other10=56 m:amind90=28 m:amind00=37 m:black90=164 m:aland10=324365817 m:asian10=349 m:pop00=13968 m:asian00=170 m:multra00=115 m:black10=551 m:hisp10=237 m:hawnpi00=2 m:white00=13320 m:amind10=34 m:hisp90=86 m:white90=12887 m:awater10=612177 m:black00=285 m:white10=14739 m:pop10=15911 m:multra10=179 m:pop90=13262 m:asian90=149 m:hisp00=122 m:other90=34 m:hawnpi10=3 m:other00=39

series e:ny2h-ckbz d:2015-06-16T14:53:35.000Z t:higrade10=12 t:funcstat10=E t:name10="Atlanta C-3 School District" t:mtfcc10=G5420 t:geoid10=2903480 t:feature_id_string=MO_2013_School_Districts_shp.2 t:statefp10=29 t:lograde10=KG t:feature_id=2 t:lsad10=00 t:dist_code=061150 t:dist_name="Atlanta C-3" t:intptlat10=+39.8997878 t:codist=061-150 t:intptlon10=-092.5182534 m:other10=8 m:amind90=0 m:amind00=3 m:black90=1 m:aland10=418773072 m:asian10=0 m:pop00=1374 m:asian00=0 m:multra00=9 m:black10=3 m:hisp10=16 m:hawnpi00=0 m:white00=1359 m:amind10=3 m:hisp90=2 m:white90=1303 m:awater10=7996637 m:black00=1 m:white10=1213 m:pop10=1247 m:multra10=20 m:pop90=1304 m:asian90=0 m:hisp00=2 m:other90=0 m:hawnpi10=0 m:other00=2

series e:ny2h-ckbz d:2015-06-16T14:53:35.000Z t:higrade10=12 t:funcstat10=E t:name10="Liberty 53 School District" t:mtfcc10=G5420 t:geoid10=2918540 t:feature_id_string=MO_2013_School_Districts_shp.3 t:statefp10=29 t:lograde10=PK t:feature_id=3 t:lsad10=00 t:dist_code=024090 t:dist_name="Liberty 53" t:intptlat10=+39.2551406 t:codist=024-090 t:intptlon10=-094.3973310 m:other10=537 m:amind90=86 m:amind00=130 m:black90=621 m:aland10=212701169 m:asian10=880 m:pop00=34584 m:asian00=218 m:multra00=510 m:black10=2026 m:hisp10=2363 m:hawnpi00=18 m:white00=32486 m:amind10=213 m:hisp90=318 m:white90=22805 m:awater10=1418667 m:black00=868 m:white10=48215 m:pop10=53223 m:multra10=1303 m:pop90=23693 m:asian90=96 m:hisp00=941 m:other90=85 m:hawnpi10=49 m:other00=353
```

## Meta Commands

```ls
metric m:aland10 p:long l:aland10 t:dataTypeName=number

metric m:awater10 p:long l:awater10 t:dataTypeName=number

metric m:pop90 p:long l:pop90 t:dataTypeName=number

metric m:white90 p:long l:white90 t:dataTypeName=number

metric m:black90 p:long l:black90 t:dataTypeName=number

metric m:asian90 p:long l:asian90 t:dataTypeName=number

metric m:amind90 p:long l:amind90 t:dataTypeName=number

metric m:other90 p:long l:other90 t:dataTypeName=number

metric m:hisp90 p:long l:hisp90 t:dataTypeName=number

metric m:pop00 p:long l:pop00 t:dataTypeName=number

metric m:white00 p:long l:white00 t:dataTypeName=number

metric m:black00 p:long l:black00 t:dataTypeName=number

metric m:asian00 p:long l:asian00 t:dataTypeName=number

metric m:amind00 p:long l:amind00 t:dataTypeName=number

metric m:hawnpi00 p:long l:hawnpi00 t:dataTypeName=number

metric m:other00 p:long l:other00 t:dataTypeName=number

metric m:multra00 p:long l:multra00 t:dataTypeName=number

metric m:hisp00 p:long l:hisp00 t:dataTypeName=number

metric m:pop10 p:long l:pop10 t:dataTypeName=number

metric m:white10 p:long l:white10 t:dataTypeName=number

metric m:black10 p:long l:black10 t:dataTypeName=number

metric m:asian10 p:long l:asian10 t:dataTypeName=number

metric m:amind10 p:long l:amind10 t:dataTypeName=number

metric m:hawnpi10 p:long l:hawnpi10 t:dataTypeName=number

metric m:other10 p:long l:other10 t:dataTypeName=number

metric m:multra10 p:long l:multra10 t:dataTypeName=number

metric m:hisp10 p:long l:hisp10 t:dataTypeName=number

entity e:ny2h-ckbz l:"School Districts" t:url=https://data.mo.gov/api/views/ny2h-ckbz

property e:ny2h-ckbz t:meta.view v:id=ny2h-ckbz v:averageRating=0 v:name="School Districts"

property e:ny2h-ckbz t:meta.view.owner v:id=y4bj-k9rq v:screenName="Alejandro Escobar" v:displayName="Alejandro Escobar"

property e:ny2h-ckbz t:meta.view.tableauthor v:id=y4bj-k9rq v:screenName="Alejandro Escobar" v:displayName="Alejandro Escobar"
```