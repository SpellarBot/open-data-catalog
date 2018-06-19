# SSMMA Public Park Properties

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ssmma-public-park-properties-92458) |
| Metadata | [Link](https://data.illinois.gov/api/views/evzh-8p3x) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/evzh-8p3x/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/evzh-8p3x/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | evzh-8p3x |
| Name | SSMMA Public Park Properties |
| Attribution | South Suburban Mayors and Managers Association |
| Category | Municipality |
| Tags | natural resources, parks, economic development, planning |
| Created | 2012-11-27T19:19:46Z |
| Publication Date | 2012-11-27T19:23:14Z |

## Description

This dataset outlines public park properties. This data is an aggregation of SSMMA, municipal, and forest preserve data.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | objectid    | OBJECTID   | text      | number      |
| Yes      | numeric metric | pin         | PIN        | number    | number      |
| Yes      | series tag     | type        | TYPE       | text      | number      |
| Yes      | series tag     | faclty_nam  | FACLTY_NAM | text      | text        |
| Yes      | series tag     | fac_add_1   | FAC_ADD_1  | text      | text        |
| Yes      | series tag     | fac_add_2   | FAC_ADD_2  | text      | text        |
| Yes      | series tag     | owner       | OWNER      | text      | text        |
| Yes      | numeric metric | acres       | ACRES      | number    | number      |
| Yes      | series tag     | openspace   | OpenSpace  | text      | text        |
| Yes      | numeric metric | shape_leng  | Shape_Leng | number    | number      |
| Yes      | numeric metric | shape_area  | Shape_Area | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:evzh-8p3x d:2012-11-27T11:19:48.000Z t:faclty_nam="Springbrook Prairie" t:owner=FPDDC t:openspace=Yes t:type=7 t:objectid=1 m:shape_area=22404968.6352 m:shape_leng=23021.3528402 m:acres=514.34730636

series e:evzh-8p3x d:2012-11-27T11:19:48.000Z t:faclty_nam="Springbrook Prairie" t:owner=FPDDC t:openspace=Yes t:type=7 t:objectid=2 m:shape_area=40558022.7429 m:shape_leng=26169.9260309 m:acres=931.08408542

series e:evzh-8p3x d:2012-11-27T11:19:48.000Z t:faclty_nam=Blackwell t:owner=FPDDC t:openspace=Yes t:type=7 t:objectid=3 m:shape_area=1090069.41776 m:shape_leng=4797.62970822 m:acres=20.75713417
```

## Meta Commands

```ls
metric m:pin p:long l:PIN t:dataTypeName=number

metric m:acres p:double l:ACRES t:dataTypeName=number

metric m:shape_leng p:double l:Shape_Leng t:dataTypeName=number

metric m:shape_area p:double l:Shape_Area t:dataTypeName=number

entity e:evzh-8p3x l:"SSMMA Public Park Properties" t:attribution="South Suburban Mayors and Managers Association" t:url=https://data.illinois.gov/api/views/evzh-8p3x

property e:evzh-8p3x t:meta.view v:id=evzh-8p3x v:category=Municipality v:attributionLink=http://www.ssmma.org v:averageRating=0 v:name="SSMMA Public Park Properties" v:attribution="South Suburban Mayors and Managers Association"

property e:evzh-8p3x t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:evzh-8p3x t:meta.view.owner v:id=p88s-rkzf v:profileImageUrlMedium=/api/users/p88s-rkzf/profile_images/THUMB v:profileImageUrlLarge=/api/users/p88s-rkzf/profile_images/LARGE v:screenName=mrizzitiello v:profileImageUrlSmall=/api/users/p88s-rkzf/profile_images/TINY v:displayName=mrizzitiello

property e:evzh-8p3x t:meta.view.tableauthor v:id=2fjt-8tt3 v:screenName=data.il.admin v:displayName=data.il.admin
```

## Top Records

```ls
| :updated_at | objectid | pin             | type | faclty_nam                     | fac_add_1      | fac_add_2       | owner                             | acres        | openspace | shape_leng    | shape_area    | 
| =========== | ======== | =============== | ==== | ============================== | ============== | =============== | ================================= | ============ | ========= | ============= | ============= | 
| 1354015188  | 1        |                 | 7    | Springbrook Prairie            |                |                 | FPDDC                             | 514.34730636 | Yes       | 23021.3528402 | 22404968.6352 | 
| 1354015188  | 2        |                 | 7    | Springbrook Prairie            |                |                 | FPDDC                             | 931.08408542 | Yes       | 26169.9260309 | 40558022.7429 | 
| 1354015188  | 3        |                 | 7    | Blackwell                      |                |                 | FPDDC                             | 20.75713417  | Yes       | 4797.62970822 | 1090069.41776 | 
| 1354015188  | 4        |                 | 7    | James ?Pate? Philip State Park |                |                 | State of Illinois                 | 453.14108334 | Yes       | 26855.3406426 | 19738828.7566 | 
| 1354015188  | 5        |                 | 7    | Timber Ridge                   |                |                 | FPDDC                             | 4.88320565   | Yes       | 2097.68760625 | 213104.529735 | 
| 1354015188  | 6        |                 | 7    | Silver Creek                   |                |                 | FPDDC                             | 5.45238538   | Yes       | 2596.64611903 | 229709.978981 | 
| 1354015188  | 7        | 603322070010000 | 7    | Aspen Meadows                  | 5905 TIMBER TR | JOLIET IL 60586 | PLAINFIELD TOWNSHIP PARK DISTRICT | 1.66272924   | Yes       | 1589.43341083 | 72428.4858159 | 
| 1354015188  | 8        | 603321090290000 | 7    | Caton Ridge                    |                | JOLIET IL 60586 | PLAINFIELD TOWNSHIP PARK DISTRICT | 1.48209178   | Yes       | 1300.40697348 | 64559.9179966 | 
| 1354015188  | 9        | 603321090270000 | 7    | Caton Ridge                    |                | JOLIET IL 60586 | PLAINFIELD TOWNSHIP PARK DISTRICT | 10.13418196  | Yes       | 4180.49888649 | 441444.966509 | 
| 1354015188  | 10       | 603321090260000 | 7    | Caton Ridge                    |                | JOLIET IL 60586 | PLAINFIELD TOWNSHIP PARK DISTRICT | 0.18437264   | Yes       | 383.325820994 | 8031.27225826 | 
```