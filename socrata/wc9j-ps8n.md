# SSMMA TIP Projects

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ssmma-tip-projects-5b293) |
| Metadata | [Link](https://data.illinois.gov/api/views/wc9j-ps8n) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/wc9j-ps8n/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/wc9j-ps8n/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | wc9j-ps8n |
| Name | SSMMA TIP Projects |
| Attribution | South Suburban Mayors and Managers Association |
| Category | Municipality |
| Tags | transportation, tip, infrastructure, economic development |
| Created | 2012-11-27T18:17:58Z |
| Publication Date | 2012-11-27T18:25:35Z |

## Description

This dataset outlines projects funded under the Transportation Improvement Program within the SSMMA Jurisdiction

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type | Render Type |
| ======== | ============== | ============ | ============ | ========= | =========== |
| No       | time           | :updated_at  | updated_at   | meta_data | meta_data   |
| No       |                | fy           | FY           | text      | text        |
| Yes      | series tag     | tip_number   | TIP NUMBER   | text      | text        |
| Yes      | series tag     | municipality | MUNICIPALITY | text      | text        |
| Yes      | series tag     | limits       | LIMITS       | text      | text        |
| Yes      | series tag     | typ_imp      | TYP. IMP.    | text      | text        |
| Yes      | numeric metric | fed          | FED          | number    | number      |
| Yes      | numeric metric | total        | TOTAL        | number    | number      |
| Yes      | series tag     | ratio        | RATIO        | text      | text        |
| Yes      | series tag     | consult      | CONSULT      | text      | text        |
| Yes      | series tag     | target_let   | TARGET LET   | text      | text        |
| Yes      | series tag     | location_1   | Location 1   | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = fy
```

## Data Commands

```ls
series e:wc9j-ps8n d:2012-11-27T10:17:59.000Z t:limits="Lincoln Avenue to Burnham Avenue" t:typ_imp=LAFO t:ratio=80/20 t:target_let=06/14/13 t:municipality="Calumet City" t:location_1="State Street" t:consult=Robinson t:tip_number=07-13-0003 m:total=245 m:fed=180

series e:wc9j-ps8n d:2012-11-27T10:17:59.000Z t:limits="Pulaski Road to Sibley Blvd" t:typ_imp=Lighting t:ratio=50/50 t:target_let=06/14/13 t:municipality="Calumet City" t:location_1="Burnham Avenue" t:consult=Robinson t:tip_number=07-13-0002 m:total=622 m:fed=311

series e:wc9j-ps8n d:2012-11-27T10:17:59.000Z t:limits="East End Avenue to 21st Street" t:typ_imp="Reconstruction E1" t:ratio=70/30 t:target_let=2014 t:municipality="Chicago Heights" t:location_1="Butler/Main Street" t:consult=Robinson t:tip_number=07-11-0036 m:total=195 m:fed=136
```

## Meta Commands

```ls
metric m:fed p:integer l:FED t:dataTypeName=number

metric m:total p:integer l:TOTAL t:dataTypeName=number

entity e:wc9j-ps8n l:"SSMMA TIP Projects" t:attribution="South Suburban Mayors and Managers Association" t:url=https://data.illinois.gov/api/views/wc9j-ps8n

property e:wc9j-ps8n t:meta.view v:id=wc9j-ps8n v:category=Municipality v:averageRating=0 v:name="SSMMA TIP Projects" v:attribution="South Suburban Mayors and Managers Association"

property e:wc9j-ps8n t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:wc9j-ps8n t:meta.view.owner v:id=p88s-rkzf v:profileImageUrlMedium=/api/users/p88s-rkzf/profile_images/THUMB v:profileImageUrlLarge=/api/users/p88s-rkzf/profile_images/LARGE v:screenName=mrizzitiello v:profileImageUrlSmall=/api/users/p88s-rkzf/profile_images/TINY v:displayName=mrizzitiello

property e:wc9j-ps8n t:meta.view.tableauthor v:id=2fjt-8tt3 v:screenName=data.il.admin v:displayName=data.il.admin
```

## Top Records

```ls
| :updated_at | fy | tip_number | municipality       | limits                            | typ_imp           | fed | total | ratio | consult     | target_let | location_1         | 
| =========== | == | ========== | ================== | ================================= | ================= | === | ===== | ===== | =========== | ========== | ================== | 
| 1354011479  | 13 | 07-13-0003 | Calumet City       | Lincoln Avenue to Burnham Avenue  | LAFO              | 180 | 245   | 80/20 | Robinson    | 06/14/13   | State Street       | 
| 1354011479  | 13 | 07-13-0002 | Calumet City       | Pulaski Road to Sibley Blvd       | Lighting          | 311 | 622   | 50/50 | Robinson    | 06/14/13   | Burnham Avenue     | 
| 1354011479  | 13 | 07-11-0036 | Chicago Heights    | East End Avenue to 21st Street    | Reconstruction E1 | 136 | 195   | 70/30 | Robinson    | 2014       | Butler/Main Street | 
| 1354011479  | 13 | 07-10-0033 | Country Club Hills | Pulaski Road Project              | Value Analysis    | 49  | 70    | 70/30 | B&W         |            | Pulaski Road       | 
| 1354011479  | 13 | 07-10-0033 | Country Club Hills | Pulaski Road @ 183rd Street       | ROW Int. Imp.     | 408 | 510   | 80/20 | B&W         | 2013 ?/?   | Pulaski Road       | 
| 1354011479  | 13 | 07-10-0033 | Country Club Hills | Pulaski Road @ 183rd Street       | Int Imp E2        | 296 | 370   | 80/20 | B&W         | 2015       | Pulaski Road       | 
| 1354011479  | 13 | 07-10-0021 | Crete              | Exchange Street/Country Lane      | Intersection E1   | 25  | 35    | 70/30 | Tech 3      | 2014 ?/?   | Exchange Street    | 
| 1354011479  | 13 | 07-12-0031 | Crete              | Rt 1 to East of I 394 1 1/2 miles | Reconstr          | 550 | 6500  | MOD   | WILL COUNTY | 07/05/05   | Exchange Street    | 
| 1354011479  | 13 | 07-13-0004 | Crete              | Steger Road to Berk Lane          | LAFO              | 92  | 115   | 80/20 | Tech 3      |            | State Street       | 
| 1354011479  | 13 | 07-12-0017 | East Hazel Crest   | I-80 Off Ramp to 175th Street     | Construction E1   | 70  | 100   | 70/30 | Burke       | 07/06/05   | Halsted Street     | 
```