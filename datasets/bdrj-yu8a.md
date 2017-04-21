# Electric System Equipment

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/electric-system-equipment) |
| Metadata | [Link](https://data.austintexas.gov/api/views/bdrj-yu8a) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/bdrj-yu8a/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/bdrj-yu8a/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | bdrj-yu8a |
| Name | Electric System Equipment |
| Attribution | Austin Energy |
| Category | Utility |
| Tags | electric system, equipment, poles, man holes, service boxes, transmission lines, distributions |
| Created | 2016-07-12T21:24:23Z |
| Publication Date | 2016-11-01T15:45:26Z |

## Description

Browse the number of substations, miles of transmission lines, and more by year.

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                          | Data Type     | Render Type   |
| ======== | ============== | =========================== | ============================= | ============= | ============= |
| Yes      | time           | fiscal_year                 | Fiscal Year                   | calendar_date | calendar_date |
| Yes      | numeric metric | overhead_primary_miles      | Overhead Primary (miles)      | number        | number        |
| Yes      | numeric metric | overhead_secondary_miles    | Overhead Secondary (miles)    | number        | number        |
| Yes      | numeric metric | underground_primary_miles   | Underground Primary (miles)   | number        | number        |
| Yes      | numeric metric | underground_secondary_miles | Underground Secondary (miles) | number        | number        |
| Yes      | numeric metric | poles                       | Poles                         | number        | number        |
| Yes      | numeric metric | overhead_transformers       | Overhead Transformers         | number        | number        |
| Yes      | numeric metric | underground_transformers    | Underground Transformers      | number        | number        |
| Yes      | numeric metric | switch_gear                 | Switch Gear                   | number        | number        |
| Yes      | numeric metric | risers                      | Risers                        | number        | number        |
| Yes      | numeric metric | man_holes                   | Man Holes                     | number        | number        |
| Yes      | numeric metric | pull_boxes                  | Pull Boxes                    | number        | number        |
| Yes      | numeric metric | service_boxes               | Service Boxes                 | number        | number        |
| Yes      | numeric metric | transmission_lines_miles    | Transmission Lines (miles)    | number        | number        |
| Yes      | numeric metric | distribution_substations    | Distribution Substations      | number        | number        |
| Yes      | numeric metric | transmission_substations    | Transmission Substations      | number        | number        |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:bdrj-yu8a d:2000-01-01T00:00:00.000Z m:man_holes=802 m:pull_boxes=22881 m:risers=9458 m:underground_transformers=25095 m:overhead_primary_miles=2334 m:overhead_transformers=40566 m:overhead_secondary_miles=3139 m:underground_secondary_miles=1855 m:switch_gear=175 m:service_boxes=30246 m:poles=127441 m:underground_primary_miles=1968

series e:bdrj-yu8a d:2001-01-01T00:00:00.000Z m:man_holes=897 m:pull_boxes=24295 m:risers=10114 m:underground_transformers=26257 m:overhead_primary_miles=2345 m:overhead_transformers=40913 m:overhead_secondary_miles=3144 m:underground_secondary_miles=1906 m:switch_gear=195 m:service_boxes=31787 m:poles=129742 m:underground_primary_miles=2037

series e:bdrj-yu8a d:2002-01-01T00:00:00.000Z m:man_holes=1049 m:pull_boxes=25573 m:risers=10569 m:underground_transformers=27462 m:overhead_primary_miles=2349 m:overhead_transformers=41333 m:overhead_secondary_miles=3150 m:underground_secondary_miles=1937 m:switch_gear=219 m:service_boxes=34663 m:poles=131800 m:underground_primary_miles=2203
```

## Meta Commands

```ls
metric m:overhead_primary_miles p:integer l:"Overhead Primary (miles)" t:dataTypeName=number

metric m:overhead_secondary_miles p:integer l:"Overhead Secondary (miles)" t:dataTypeName=number

metric m:underground_primary_miles p:integer l:"Underground Primary (miles)" t:dataTypeName=number

metric m:underground_secondary_miles p:integer l:"Underground Secondary (miles)" t:dataTypeName=number

metric m:poles p:integer l:Poles t:dataTypeName=number

metric m:overhead_transformers p:integer l:"Overhead Transformers" t:dataTypeName=number

metric m:underground_transformers p:integer l:"Underground Transformers" t:dataTypeName=number

metric m:switch_gear p:integer l:"Switch Gear" t:dataTypeName=number

metric m:risers p:integer l:Risers t:dataTypeName=number

metric m:man_holes p:integer l:"Man Holes" t:dataTypeName=number

metric m:pull_boxes p:integer l:"Pull Boxes" t:dataTypeName=number

metric m:service_boxes p:integer l:"Service Boxes" t:dataTypeName=number

metric m:transmission_lines_miles p:integer l:"Transmission Lines (miles)" t:dataTypeName=number

metric m:distribution_substations p:integer l:"Distribution Substations" t:dataTypeName=number

metric m:transmission_substations p:integer l:"Transmission Substations" t:dataTypeName=number

entity e:bdrj-yu8a l:"Electric System Equipment" t:attribution="Austin Energy" t:url=https://data.austintexas.gov/api/views/bdrj-yu8a

property e:bdrj-yu8a t:meta.view v:id=bdrj-yu8a v:category=Utility v:averageRating=0 v:name="Electric System Equipment" v:attribution="Austin Energy"

property e:bdrj-yu8a t:meta.view.license v:name="Public Domain"

property e:bdrj-yu8a t:meta.view.owner v:id=c433-zrb5 v:profileImageUrlMedium=/api/users/c433-zrb5/profile_images/THUMB v:profileImageUrlLarge=/api/users/c433-zrb5/profile_images/LARGE v:screenName="Sarah Lambert" v:profileImageUrlSmall=/api/users/c433-zrb5/profile_images/TINY v:displayName="Sarah Lambert"

property e:bdrj-yu8a t:meta.view.tableauthor v:id=c433-zrb5 v:profileImageUrlMedium=/api/users/c433-zrb5/profile_images/THUMB v:profileImageUrlLarge=/api/users/c433-zrb5/profile_images/LARGE v:screenName="Sarah Lambert" v:profileImageUrlSmall=/api/users/c433-zrb5/profile_images/TINY v:roleName=publisher v:displayName="Sarah Lambert"
```

## Top Records

```ls
| fiscal_year         | overhead_primary_miles | overhead_secondary_miles | underground_primary_miles | underground_secondary_miles | poles  | overhead_transformers | underground_transformers | switch_gear | risers | man_holes | pull_boxes | service_boxes | transmission_lines_miles | distribution_substations | transmission_substations | 
| =================== | ====================== | ======================== | ========================= | =========================== | ====== | ===================== | ======================== | =========== | ====== | ========= | ========== | ============= | ======================== | ======================== | ======================== | 
| 2000-01-01T00:00:00 | 2334                   | 3139                     | 1968                      | 1855                        | 127441 | 40566                 | 25095                    | 175         | 9458   | 802       | 22881      | 30246         |                          |                          |                          | 
| 2001-01-01T00:00:00 | 2345                   | 3144                     | 2037                      | 1906                        | 129742 | 40913                 | 26257                    | 195         | 10114  | 897       | 24295      | 31787         |                          |                          |                          | 
| 2002-01-01T00:00:00 | 2349                   | 3150                     | 2203                      | 1937                        | 131800 | 41333                 | 27462                    | 219         | 10569  | 1049      | 25573      | 34663         |                          |                          |                          | 
| 2003-01-01T00:00:00 | 2360                   | 3172                     | 2284                      | 2233                        | 134027 | 41473                 | 28945                    | 225         | 10950  | 1109      | 26523      | 36737         |                          |                          |                          | 
| 2004-01-01T00:00:00 | 2363                   | 3183                     | 2356                      | 2406                        | 136393 | 41609                 | 29082                    | 246         | 11316  | 1414      | 27471      | 39331         |                          |                          |                          | 
| 2005-01-01T00:00:00 | 2364                   | 3185                     | 2443                      | 2568                        | 139423 | 41834                 | 30153                    | 272         | 11723  | 1862      | 28696      | 41891         |                          |                          |                          | 
| 2006-01-01T00:00:00 | 2368                   | 3172                     | 2534                      | 2702                        | 141466 | 42117                 | 31120                    | 290         | 12260  | 1952      | 29764      | 44276         | 608                      | 54                       | 9                        | 
| 2007-01-01T00:00:00 | 2363                   | 3164                     | 2621                      | 2808                        | 142939 | 42268                 | 32052                    | 315         | 12810  | 2070      | 30833      | 46081         | 619                      | 56                       | 11                       | 
| 2008-01-01T00:00:00 | 2362                   | 3127                     | 2832                      | 2868                        | 145535 | 42475                 | 33539                    | 281         | 13536  | 2173      | 32640      | 48683         | 619                      | 56                       | 11                       | 
| 2009-01-01T00:00:00 | 2366                   | 3127                     | 2866                      | 2920                        | 148025 | 42633                 | 34144                    | 306         | 14004  | 2341      | 33577      | 51009         | 619                      | 56                       | 11                       | 
```