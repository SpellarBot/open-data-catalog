# DOE High School Programs 2014-2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/doe-high-school-programs-2014-2015-5a3ce) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/by6m-6zpb) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/by6m-6zpb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/by6m-6zpb/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | by6m-6zpb |
| Name | DOE High School Programs 2014-2015 |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | doe high school programs 2014-2015, education |
| Created | 2014-10-29T21:08:45Z |
| Publication Date | 2014-11-21T21:09:49Z |

## Description

Directory of NYC High School programs

## Columns

```ls
| Included | Schema Type    | Field Name | Name      | Data Type | Render Type |
| ======== | ============== | ========== | ========= | ========= | =========== |
| Yes      | series tag     | dbn        | dbn       | text      | text        |
| Yes      | series tag     | program    | program   | text      | text        |
| Yes      | series tag     | prgdesc    | prgdesc   | text      | text        |
| Yes      | series tag     | code       | code      | text      | text        |
| Yes      | series tag     | interest   | interest  | text      | text        |
| Yes      | series tag     | method     | method    | text      | text        |
| Yes      | series tag     | eng        | eng       | text      | text        |
| Yes      | series tag     | math       | math      | text      | text        |
| Yes      | series tag     | soc        | soc       | text      | text        |
| Yes      | series tag     | sci        | sci       | text      | text        |
| Yes      | series tag     | stm        | stm       | text      | text        |
| Yes      | series tag     | ela        | ela       | text      | text        |
| Yes      | series tag     | aud        | aud       | text      | text        |
| Yes      | numeric metric | seat_gr09  | seat_gr09 | number    | number      |
| Yes      | numeric metric | app_gr09   | app_gr09  | number    | number      |
| Yes      | series tag     | seat_gr10  | seat_gr10 | text      | text        |
| Yes      | series tag     | app_gr10   | app_gr10  | text      | text        |
| Yes      | series tag     | req1       | req1      | text      | text        |
| Yes      | series tag     | req2       | req2      | text      | text        |
| Yes      | series tag     | req3       | req3      | text      | text        |
| Yes      | series tag     | req4       | req4      | text      | text        |
| Yes      | series tag     | req5       | req5      | text      | text        |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:by6m-6zpb d:2014-01-01T00:00:00.000Z t:app_gr10=None t:dbn=29Q272 t:program="Carver Research Institute" t:interest="Science & Math" t:method="Limited Unscreened" t:seat_gr10=None t:code=Q45C m:seat_gr09=54 m:app_gr09=183

series e:by6m-6zpb d:2014-01-01T00:00:00.000Z t:app_gr10=None t:dbn=24Q585 t:program="Maspeth High School" t:interest="Humanities & Interdisciplinary" t:method="Limited Unscreened" t:seat_gr10=None t:code=Q47A m:seat_gr09=250 m:app_gr09=2609

series e:by6m-6zpb d:2014-01-01T00:00:00.000Z t:app_gr10=None t:dbn=08X348 t:program="Schuylerville Preparatory High School" t:interest="Humanities & Interdisciplinary" t:method="Limited Unscreened" t:seat_gr10=None t:code=X57A m:seat_gr09=108 m:app_gr09=428
```

## Meta Commands

```ls
metric m:seat_gr09 p:integer l:seat_gr09 t:dataTypeName=number

metric m:app_gr09 p:integer l:app_gr09 t:dataTypeName=number

entity e:by6m-6zpb l:"DOE High School Programs 2014-2015" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/by6m-6zpb

property e:by6m-6zpb t:meta.view v:id=by6m-6zpb v:category=Education v:averageRating=0 v:name="DOE High School Programs 2014-2015" v:attribution="Department of Education (DOE)"

property e:by6m-6zpb t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:by6m-6zpb t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| dbn    | program                                         | prgdesc | code | interest                       | method             | eng | math | soc | sci | stm | ela | aud | seat_gr09 | app_gr09 | seat_gr10 | app_gr10 | req1 | req2 | req3 | req4 | req5 | 
| ====== | =============================================== | ======= | ==== | ============================== | ================== | === | ==== | === | === | === | === | === | ========= | ======== | ========= | ======== | ==== | ==== | ==== | ==== | ==== | 
| 29Q272 | Carver Research Institute                       |         | Q45C | Science & Math                 | Limited Unscreened |     |      |     |     |     |     |     | 54        | 183      | None      | None     |      |      |      |      |      | 
| 24Q585 | Maspeth High School                             |         | Q47A | Humanities & Interdisciplinary | Limited Unscreened |     |      |     |     |     |     |     | 250       | 2609     | None      | None     |      |      |      |      |      | 
| 08X348 | Schuylerville Preparatory High School           |         | X57A | Humanities & Interdisciplinary | Limited Unscreened |     |      |     |     |     |     |     | 108       | 428      | None      | None     |      |      |      |      |      | 
| 08X332 | Holcombe L. Rucker School of Community Research |         | Y22A | Humanities & Interdisciplinary | Limited Unscreened |     |      |     |     |     |     |     | 95        | 97       | 10        | 10       |      |      |      |      |      | 
| 26Q415 | School of Journalism and Media Studies          |         | Q16B | Communications                 | Limited Unscreened |     |      |     |     |     |     |     | 60        | 1531     | None      | None     |      |      |      |      |      | 
| 07X522 | Architecture and Design                         |         | Y51B | Architecture                   | Limited Unscreened |     |      |     |     |     |     |     | 27        | 361      | None      | None     |      |      |      |      |      | 
| 08X349 | Bronx River High School                         |         | X24A | Humanities & Interdisciplinary | Limited Unscreened |     |      |     |     |     |     |     | 108       | 1061     | None      | None     |      |      |      |      |      | 
| 25Q460 | Zoned                                           |         | Q18Z | Zoned                          | Zoned              |     |      |     |     |     |     |     | 161       |          | Zoned     | Zoned    |      |      |      |      |      | 
| 28Q440 | Zoned                                           |         | Q19Z | Zoned                          | Zoned              |     |      |     |     |     |     |     | 402       |          | Zoned     | Zoned    |      |      |      |      |      | 
| 02M392 | Manhattan Business Academy                      |         | A12A | Business                       | Limited Unscreened |     |      |     |     |     |     |     | 108       | 988      | None      | None     |      |      |      |      |      | 
```