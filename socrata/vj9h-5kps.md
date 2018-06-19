# SSMMA Water System Capacity

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ssmma-water-system-capacity-17166) |
| Metadata | [Link](https://data.illinois.gov/api/views/vj9h-5kps) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/vj9h-5kps/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/vj9h-5kps/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | vj9h-5kps |
| Name | SSMMA Water System Capacity |
| Attribution | South Suburban Mayors and Managers Association |
| Category | Municipality |
| Tags | infrastructure, planning, public works, water |
| Created | 2012-11-27T17:59:23Z |
| Publication Date | 2012-11-27T19:08:52Z |

## Description

This dataset is a municipal aggregation of water system capacity of the respective communities across the Chicago Southland area.

## Columns

```ls
| Included | Schema Type    | Field Name | Name       | Data Type | Render Type |
| ======== | ============== | ========== | ========== | ========= | =========== |
| Yes      | series tag     | objectid   | OBJECTID   | text      | number      |
| Yes      | series tag     | municipali | Municipali | text      | text        |
| Yes      | series tag     | county     | County     | text      | text        |
| Yes      | series tag     | type       | Type       | text      | text        |
| Yes      | series tag     | water_serv | Water_Serv | text      | text        |
| Yes      | series tag     | contact_pe | Contact_Pe | text      | text        |
| Yes      | series tag     | contact_1  | Contact__1 | text      | text        |
| Yes      | series tag     | contact_2  | Contact__2 | text      | text        |
| Yes      | numeric metric | storage_ca | Storage_Ca | number    | number      |
| Yes      | numeric metric | treatment  | Treatment_ | number    | number      |
| Yes      | numeric metric | average_da | Average_Da | number    | number      |
| Yes      | series tag     | water_repo | Water_Repo | text      | text        |
| Yes      | time           | year_updat | Year_Updat | number    | number      |
| Yes      | series tag     | editor     | Editor     | text      | text        |
| Yes      | numeric metric | propreitar | Propreitar | number    | number      |
| Yes      | series tag     | universal  | Universal_ | text      | text        |
| Yes      | numeric metric | future_202 | Future_202 | number    | number      |
| Yes      | numeric metric | future_203 | Future_203 | number    | number      |
```

## Time Field

```ls
Value = year_updat
Format & Zone = yyyy
```

## Data Commands

```ls
series e:vj9h-5kps d:2011-01-01T00:00:00.000Z t:editor=MJR t:county=Cook t:universal=UR1 t:objectid=1 t:type=Lake t:municipali=Burnham t:water_serv=Hammond m:average_da=467000 m:storage_ca=500000 m:propreitar=1

series e:vj9h-5kps d:2011-01-01T00:00:00.000Z t:editor=MJR t:county=Cook t:universal=UR2 t:objectid=2 t:type=Lake t:municipali="Calumet City" t:water_serv=Hammond m:average_da=4902000 m:future_202=5002000 m:future_203=5100000 m:propreitar=2

series e:vj9h-5kps d:2011-01-01T00:00:00.000Z t:editor=MJR t:county=Cook t:universal=UR3 t:objectid=3 t:type=Lake t:municipali="South Holland" t:water_serv=Chicago m:average_da=3845000 m:storage_ca=8000000 m:future_202=3993000 m:future_203=4138000 m:treatment=9000000 m:propreitar=3
```

## Meta Commands

```ls
metric m:storage_ca p:integer l:Storage_Ca t:dataTypeName=number

metric m:treatment p:integer l:Treatment_ t:dataTypeName=number

metric m:average_da p:integer l:Average_Da t:dataTypeName=number

metric m:propreitar p:integer l:Propreitar t:dataTypeName=number

metric m:future_202 p:integer l:Future_202 t:dataTypeName=number

metric m:future_203 p:integer l:Future_203 t:dataTypeName=number

entity e:vj9h-5kps l:"SSMMA Water System Capacity" t:attribution="South Suburban Mayors and Managers Association" t:url=https://data.illinois.gov/api/views/vj9h-5kps

property e:vj9h-5kps t:meta.view v:id=vj9h-5kps v:category=Municipality v:attributionLink=http://www.ssmma.org v:averageRating=0 v:name="SSMMA Water System Capacity" v:attribution="South Suburban Mayors and Managers Association"

property e:vj9h-5kps t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:vj9h-5kps t:meta.view.owner v:id=p88s-rkzf v:profileImageUrlMedium=/api/users/p88s-rkzf/profile_images/THUMB v:profileImageUrlLarge=/api/users/p88s-rkzf/profile_images/LARGE v:screenName=mrizzitiello v:profileImageUrlSmall=/api/users/p88s-rkzf/profile_images/TINY v:displayName=mrizzitiello

property e:vj9h-5kps t:meta.view.tableauthor v:id=74c3-ka9x v:profileImageUrlMedium=/api/users/74c3-ka9x/profile_images/THUMB v:profileImageUrlLarge=/api/users/74c3-ka9x/profile_images/LARGE v:screenName="Rey de Castro" v:profileImageUrlSmall=/api/users/74c3-ka9x/profile_images/TINY v:roleName=publisher v:displayName="Rey de Castro"
```

## Top Records

```ls
| objectid | municipali    | county | type | water_serv | contact_pe | contact_1 | contact_2 | storage_ca | treatment | average_da | water_repo | year_updat | editor | propreitar | universal | future_202 | future_203 | 
| ======== | ============= | ====== | ==== | ========== | ========== | ========= | ========= | ========== | ========= | ========== | ========== | ========== | ====== | ========== | ========= | ========== | ========== | 
| 1        | Burnham       | Cook   | Lake | Hammond    |            |           |           | 500000     |           | 467000     |            | 2011       | MJR    | 1          | UR1       |            |            | 
| 2        | Calumet City  | Cook   | Lake | Hammond    |            |           |           |            |           | 4902000    |            | 2011       | MJR    | 2          | UR2       | 5002000    | 5100000    | 
| 3        | South Holland | Cook   | Lake | Chicago    |            |           |           | 8000000    | 9000000   | 3845000    |            | 2011       | MJR    | 3          | UR3       | 3993000    | 4138000    | 
| 4        | South Holland | Cook   | Lake | Lansing    |            |           |           | 8000000    | 9000000   | 3845000    |            | 2011       | MJR    | 11         | UR11      | 3993000    | 4138000    | 
| 5        | Lansing       | Cook   | Lake | Lansing    |            |           |           | 8650000    | 8000000   | 3925000    |            | 2011       | MJR    | 5          | UR5       | 4094000    | 4257000    | 
| 6        | Lynwood       | Cook   | Lake | Lansing    |            |           |           | 2250000    |           | 806000     |            | 2011       | MJR    | 6          | UR6       | 1014000    | 1222000    | 
| 7        | Burnham       | Cook   | Lake | Hammond    |            |           |           | 500000     |           | 496000     |            | 2011       | MJR    | 7          | UR7       | 512000     | 528000     | 
| 8        | Dolton        | Cook   | Lake | Chicago    |            |           |           |            |           | 3141000    |            | 2011       | MJR    | 8          | UR8       | 3168000    | 3192000    | 
| 9        | Riverdale     | Cook   | Lake | Chicago    |            |           |           |            |           | 2151000    |            | 2011       | MJR    | 9          | UR9       | 2244000    | 2337000    | 
| 10       | Phoenix       | Cook   | Lake | Harvey     |            |           |           | 16300000   |           | 198000     |            | 2011       | MJR    | 10         | UR10      | 211000     | 224000     | 
```