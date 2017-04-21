# Parks - Public Art

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/parks-public-art-eb35f) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/sj6t-9cju) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/sj6t-9cju/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/sj6t-9cju/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | sj6t-9cju |
| Name | Parks - Public Art |
| Attribution | Chicago Park District |
| Category | Parks & Recreation |
| Tags | public art |
| Created | 2012-02-08T20:40:33Z |
| Publication Date | 2013-03-13T22:30:52Z |

## Description

Public art located in Chicago parks. To download KML, go to https://data.cityofchicago.org/Parks-Recreation/Parks-Public-Art-KML/pmh6-gzg6. To download Shapefiles, go to https://data.cityofchicago.org/Parks-Recreation/Parks-Public-Art-Shapefiles/gfnu-w3q6.

## Columns

```ls
| Included | Schema Type | Field Name   | Name         | Data Type | Render Type |
| ======== | =========== | ============ | ============ | ========= | =========== |
| No       | time        | :updated_at  | updated_at   | meta_data | meta_data   |
| Yes      | series tag  | park_name    | PARK NAME    | text      | text        |
| Yes      | series tag  | park_number  | PARK NUMBER  | text      | number      |
| Yes      | series tag  | art          | ART          | text      | text        |
| Yes      | series tag  | artist       | ARTIST       | text      | text        |
| Yes      | series tag  | owner        | OWNER        | text      | text        |
| No       |             | x_coordinate | X COORDINATE | number    | number      |
| No       |             | y_coordinate | Y COORDINATE | number    | number      |
| No       |             | latitude     | LATITUDE     | number    | number      |
| No       |             | longitude    | LONGITUDE    | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = x_coordinate,y_coordinate,latitude,longitude
```

## Data Commands

```ls
series e:sj6t-9cju d:2012-09-18T12:19:44.000Z t:art="Christopher Columbus and Fountain" t:owner=CPD t:park_number=215 t:park_name="ARRIGO (VICTOR)" t:artist="Moses Ezekiel" m:row_number.sj6t-9cju=1

series e:sj6t-9cju d:2012-09-18T12:19:44.000Z t:art="Bixler Playlot Park Fountain" t:owner=CPD t:park_number=1083 t:park_name="BIXLER (RAY)" m:row_number.sj6t-9cju=2

series e:sj6t-9cju d:2012-09-18T12:19:44.000Z t:art="American Doughboy (Spirit of the American Doughboy)" t:owner=CPD t:park_number=27 t:park_name="BURNHAM (DANIEL)" t:artist="Ernest Moore Viquesney" m:row_number.sj6t-9cju=3
```

## Meta Commands

```ls
metric m:row_number.sj6t-9cju p:long l:"Row Number"

entity e:sj6t-9cju l:"Parks - Public Art" t:attribution="Chicago Park District" t:url=https://data.cityofchicago.org/api/views/sj6t-9cju

property e:sj6t-9cju t:meta.view v:id=sj6t-9cju v:category="Parks & Recreation" v:attributionLink=http://www.chicagoparkdistrict.com/facilities/search/ v:averageRating=0 v:name="Parks - Public Art" v:attribution="Chicago Park District"

property e:sj6t-9cju t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:sj6t-9cju t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| :updated_at | park_name        | park_number | art                                                 | artist                   | owner | x_coordinate       | y_coordinate       | latitude           | longitude           | 
| =========== | ================ | =========== | =================================================== | ======================== | ===== | ================== | ================== | ================== | =================== | 
| 1347970784  | ARRIGO (VICTOR)  | 215         | Christopher Columbus and Fountain                   | Moses Ezekiel            | CPD   | 1167268.04553      | 1896559.5281       | 41.871715999999999 | -87.661359000000004 | 
| 1347970784  | BIXLER (RAY)     | 1083        | Bixler Playlot Park Fountain                        |                          | CPD   | 1186198.7589799999 | 1867548.40699      | 41.791679999999999 | -87.592776000000001 | 
| 1347970784  | BURNHAM (DANIEL) | 27          | American Doughboy (Spirit of the American Doughboy) | Ernest Moore Viquesney   | CPD   | 1179513.2483999999 | 1892682.8114499999 | 41.860805999999997 | -87.616521000000006 | 
| 1347970784  | BURNHAM (DANIEL) | 27          | Mermaid (La Sirena)                                 | Jose Moreno              | CPD   | 1184902.8317799999 | 1878095.0509200001 | 41.820650999999998 | -87.597196999999994 | 
| 1347970784  | BURNHAM (DANIEL) | 27          | Gold Star Families Memorial                         | David Woodhouse & Assoc. | CPD   | 1180132.7990000001 | 1893284.0399       | 41.862440999999997 | -87.614228999999995 | 
| 1347970784  | BURNHAM (DANIEL) | 27          | Chicago Firefighter/Paramedic Memorial              | John Alaniz              | CPD   | 1181382.6344300001 | 1889015.1888600001 | 41.850698999999999 | -87.609773000000004 | 
| 1347970784  | BURNHAM (DANIEL) | 27          | Soldier Field Children's Garden                     | Peter Lindsay Schaudt    |       | 1179959.0234300001 | 1894059.32969      | 41.864573          | -87.614842999999993 | 
| 1347970784  | BURNHAM (DANIEL) | 27          | Special Olympics Memorial                           | Richard Hunt             | CPD   | 1179793.13794      | 1893184.32947      | 41.862175999999998 | -87.615478999999993 | 
| 1347970784  | BURNHAM (DANIEL) | 27          | Tribute to Freedom                                  | Anna Koh Varilla         | CPD   | 1179259.28369      | 1893647.8711999999 | 41.863460000000003 | -87.617424          | 
| 1347970784  | BURNHAM (DANIEL) | 27          | Tribute to George Halas                             | Julie Rotblatt-Amrany    |       | 1179782.72129      | 1893314.5378699999 | 41.862532999999999 | -87.615513000000007 | 
```