# SSMA Employment Centers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ssma-employment-centers-9c749) |
| Metadata | [Link](https://data.illinois.gov/api/views/xwzt-wcgs) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/xwzt-wcgs/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/xwzt-wcgs/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | xwzt-wcgs |
| Name | SSMA Employment Centers |
| Attribution | South Suburban Mayors and Managers Association |
| Category | Municipality |
| Tags | employment, economic development, planning |
| Created | 2012-11-27T20:38:32Z |
| Publication Date | 2012-11-27T20:39:43Z |

## Description

This dataset details key employment centers in the Chicago Southland communities.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | objectid    | OBJECTID   | text      | number      |
| Yes      | series tag     | districtna  | DistrictNa | text      | text        |
| Yes      | series tag     | districtty  | DistrictTy | text      | text        |
| Yes      | series tag     | jobs        | Jobs       | text      | text        |
| Yes      | series tag     | municipali  | Municipali | text      | text        |
| Yes      | series tag     | county      | County     | text      | text        |
| Yes      | series tag     | zipcode     | ZipCode    | text      | text        |
| Yes      | series tag     | editor      | Editor     | text      | text        |
| Yes      | numeric metric | propreitar  | Propreitar | number    | number      |
| Yes      | series tag     | urnumber    | URNumber   | text      | text        |
| Yes      | numeric metric | shape_leng  | SHAPE_Leng | number    | number      |
| Yes      | numeric metric | shape_area  | SHAPE_Area | number    | number      |
| Yes      | series tag     | acres       | ACRES      | text      | text        |
| Yes      | series tag     | owner_name  | Owner_Name | text      | text        |
| Yes      | series tag     | owner_addr  | Owner_Addr | text      | text        |
| Yes      | series tag     | owner_phon  | Owner_Phon | text      | text        |
| Yes      | series tag     | owner_emai  | Owner_Emai | text      | text        |
| No       |                | location_1  | Location 1 | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = location_1
```

## Data Commands

```ls
series e:xwzt-wcgs d:2012-11-27T12:38:34.000Z t:editor=MJR t:county=Will t:urnumber=UR50 t:districtna="Corporate Corridors Office Park" t:districtty=Office t:objectid=50 t:municipali=Mokena m:shape_area=11931495.1595 m:shape_leng=17374.5534145 m:propreitar=50

series e:xwzt-wcgs d:2012-11-27T12:38:34.000Z t:editor=MJR t:county=Will t:urnumber=UR51 t:districtna="Hickory Creek Plaza" t:districtty=Commercial t:objectid=51 t:municipali=Mokena m:shape_area=1213499.18088 m:shape_leng=4448.93572889 m:propreitar=51

series e:xwzt-wcgs d:2012-11-27T12:38:34.000Z t:editor=MJR t:county=Will t:urnumber=UR52 t:districtna="Mokena Marketplace" t:districtty=Retail t:objectid=52 t:municipali=Mokena m:shape_area=2448555.32841 m:shape_leng=6367.68896862 m:propreitar=52
```

## Meta Commands

```ls
metric m:propreitar p:integer l:Propreitar t:dataTypeName=number

metric m:shape_leng p:double l:SHAPE_Leng t:dataTypeName=number

metric m:shape_area p:double l:SHAPE_Area t:dataTypeName=number

entity e:xwzt-wcgs l:"SSMA Employment Centers" t:attribution="South Suburban Mayors and Managers Association" t:url=https://data.illinois.gov/api/views/xwzt-wcgs

property e:xwzt-wcgs t:meta.view v:id=xwzt-wcgs v:category=Municipality v:attributionLink=http://www.ssmma.org v:averageRating=0 v:name="SSMA Employment Centers" v:attribution="South Suburban Mayors and Managers Association"

property e:xwzt-wcgs t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:xwzt-wcgs t:meta.view.owner v:id=p88s-rkzf v:profileImageUrlMedium=/api/users/p88s-rkzf/profile_images/THUMB v:profileImageUrlLarge=/api/users/p88s-rkzf/profile_images/LARGE v:screenName=mrizzitiello v:profileImageUrlSmall=/api/users/p88s-rkzf/profile_images/TINY v:displayName=mrizzitiello

property e:xwzt-wcgs t:meta.view.tableauthor v:id=74c3-ka9x v:profileImageUrlMedium=/api/users/74c3-ka9x/profile_images/THUMB v:profileImageUrlLarge=/api/users/74c3-ka9x/profile_images/LARGE v:screenName="Rey de Castro" v:profileImageUrlSmall=/api/users/74c3-ka9x/profile_images/TINY v:roleName=publisher v:displayName="Rey de Castro"
```

## Top Records

```ls
| :updated_at | objectid | districtna                        | districtty | jobs | municipali  | county | zipcode | editor | propreitar | urnumber | shape_leng    | shape_area    | acres | owner_name | owner_addr | owner_phon | owner_emai | location_1 | 
| =========== | ======== | ================================= | ========== | ==== | =========== | ====== | ======= | ====== | ========== | ======== | ============= | ============= | ===== | ========== | ========== | ========== | ========== | ========== | 
| 1354019914  | 50       | Corporate Corridors Office Park   | Office     |      | Mokena      | Will   |         | MJR    | 50         | UR50     | 17374.5534145 | 11931495.1595 |       |            |            |            |            |            | 
| 1354019914  | 51       | Hickory Creek Plaza               | Commercial |      | Mokena      | Will   |         | MJR    | 51         | UR51     | 4448.93572889 | 1213499.18088 |       |            |            |            |            |            | 
| 1354019914  | 52       | Mokena Marketplace                | Retail     |      | Mokena      | Will   |         | MJR    | 52         | UR52     | 6367.68896862 | 2448555.32841 |       |            |            |            |            |            | 
| 1354019914  | 53       | Orland Park Business Center       | Industrial |      | Orland Park | Will   |         | MJR    | 53         | UR53     | 9589.51891706 | 5052727.52073 |       |            |            |            |            |            | 
| 1354019914  | 54       | Brookside Marketplace             | Retail     |      | Tinley Park | Will   |         | MJR    | 54         | UR54     | 9022.33100854 | 5176082.40393 |       |            |            |            |            |            | 
| 1354019914  | 55       | North Creek Business Park         | Office     |      | Tinley Park | Will   |         | MJR    | 55         | UR55     | 9792.70336932 | 6093130.55318 |       |            |            |            |            |            | 
| 1354019914  | 56       | Hickory Creek Corporate Center #2 | Office     |      | Tinley Park | Will   |         | MJR    | 56         | UR56     | 7912.44344524 | 3467116.62911 |       |            |            |            |            |            | 
| 1354019914  | 57       | Hickory Creek Corporate Center #1 | Office     |      | Tinley Park | Will   |         | MJR    | 57         | UR57     | 7987.42218563 | 3532884.96992 |       |            |            |            |            |            | 
| 1354019914  | 58       | Tinley Crossings Corporate Center | Industrial |      | Tinley Park | Will   |         | MJR    | 58         | UR58     | 15534.2348824 | 11721690.9771 |       |            |            |            |            |            | 
| 1354019914  | 59       | Tinley Park Convention Center     | Commercial |      | Tinley Park | Cook   |         | MJR    | 59         | UR59     | 5847.38749509 | 1813107.12167 |       |            |            |            |            |            | 
```