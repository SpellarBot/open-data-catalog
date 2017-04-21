# Libraries - 2011 Children's Summer Reading Program

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/libraries-2011-childrens-summer-reading-program-79a56) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/vuf2-qfik) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/vuf2-qfik/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/vuf2-qfik/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | vuf2-qfik |
| Name | Libraries - 2011 Children's Summer Reading Program |
| Attribution | Chicago Public Library |
| Category | Education |
| Tags | libraries, programs, summer reading, children |
| Created | 2011-09-15T22:44:59Z |
| Publication Date | 2012-02-23T15:51:11Z |

## Description

The Chicago Public Library Summer Reading Program is an eight-week thematic reading program planned to encourage and instill the love of reading and enjoyment of books in children and teens while promoting the development of their reading interests.

## Columns

```ls
| Included | Schema Type    | Field Name   | Name              | Data Type | Render Type |
| ======== | ============== | ============ | ================= | ========= | =========== |
| Yes      | series tag     | location     | LOCATION          | text      | text        |
| No       |                | address      | ADDRESS           | text      | text        |
| Yes      | series tag     | city         | CITY              | text      | text        |
| Yes      | series tag     | zip_code     | ZIP CODE          | text      | number      |
| Yes      | numeric metric | participants | 2011 PARTICIPANTS | number    | number      |
| Yes      | numeric metric | books_read   | 2011 BOOKS READ   | number    | number      |
```

## Time Field

```ls
Value = 2011
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:vuf2-qfik d:2011-01-01T00:00:00.000Z t:location="Kraft Great Kids" t:city=CHICAGO m:participants=184 m:books_read=3513

series e:vuf2-qfik d:2011-01-01T00:00:00.000Z t:zip_code=60623 t:location=Toman t:city=CHICAGO m:participants=1693 m:books_read=39605

series e:vuf2-qfik d:2011-01-01T00:00:00.000Z t:zip_code=60628 t:location="Woodson Regional" t:city=CHICAGO m:participants=1221 m:books_read=43844
```

## Meta Commands

```ls
metric m:participants p:integer l:"2011 PARTICIPANTS" t:dataTypeName=number

metric m:books_read p:integer l:"2011 BOOKS READ" t:dataTypeName=number

entity e:vuf2-qfik l:"Libraries - 2011 Children's Summer Reading Program" t:attribution="Chicago Public Library" t:url=https://data.cityofchicago.org/api/views/vuf2-qfik

property e:vuf2-qfik t:meta.view v:id=vuf2-qfik v:category=Education v:attributionLink=http://chipublib.org v:averageRating=0 v:name="Libraries - 2011 Children's Summer Reading Program" v:attribution="Chicago Public Library"

property e:vuf2-qfik t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:vuf2-qfik t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| location         | address                             | city    | zip_code | participants | books_read | 
| ================ | =================================== | ======= | ======== | ============ | ========== | 
| Kraft Great Kids | At targeted park district locations | CHICAGO |          | 184          | 3513       | 
| Toman            | 2708 S. Pulaski Road                | CHICAGO | 60623    | 1693         | 39605      | 
| Woodson Regional | 9525 S. Halsted Street              | CHICAGO | 60628    | 1221         | 43844      | 
| Humboldt Park    | 1605 N. Troy Street                 | CHICAGO | 60647    | 581          | 14193      | 
| Lincoln Park     | 1150 W. Fullerton Avenue            | CHICAGO | 60614    | 1142         | 30310      | 
| West Lawn        | 4020 W. 63rd Street                 | CHICAGO | 60629    | 797          | 9733       | 
| Beverly          | 1962 W. 95th Street                 | CHICAGO | 60643    | 1053         | 25803      | 
| Sherman Park     | 5440 S. Racine Avenue               | CHICAGO | 60609    | 492          | 10886      | 
| Edgebrook        | 5331 W. Devon Avenue                | CHICAGO | 60646    | 804          | 19264      | 
| McKinley Park    | 1915 W. 35th Street                 | CHICAGO | 60609    | 286          | 5409       | 
```