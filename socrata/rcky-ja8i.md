# SSMMA Fair Housing

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ssmma-fair-housing-4d96e) |
| Metadata | [Link](https://data.illinois.gov/api/views/rcky-ja8i) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/rcky-ja8i/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/rcky-ja8i/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | rcky-ja8i |
| Name | SSMMA Fair Housing |
| Attribution | South Suburban Mayors and Managers Association |
| Category | Municipality |
| Tags | housing, statistical, planning |
| Created | 2012-11-27T18:09:53Z |
| Publication Date | 2012-11-27T19:03:53Z |

## Description

This dataset details communities which have a Fair Housing Ordinance. This was put together by South Suburban Atlas staff.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | objectid    | OBJECTID   | text      | number      |
| Yes      | series tag     | municipali  | MUNICIPALI | text      | text        |
| Yes      | series tag     | county      | COUNTY     | text      | text        |
| Yes      | series tag     | fho_enacte  | FHO_Enacte | text      | text        |
| No       |                | fho_date    | FHO_Date   | text      | text        |
| Yes      | series tag     | fho_link    | FHO_Link   | text      | text        |
| Yes      | series tag     | fho_staff_1 | FHO_Staff  | text      | text        |
| Yes      | series tag     | fho_staff_2 | FHO_Staff_ | text      | text        |
| Yes      | series tag     | fho_staff1  | FHO_Staff1 | text      | text        |
| Yes      | series tag     | editor      | Editor     | text      | text        |
| Yes      | numeric metric | propreitar  | Propreitar | number    | number      |
| Yes      | series tag     | universali  | UniversalI | text      | text        |
| Yes      | numeric metric | shape_leng  | SHAPE_Leng | number    | number      |
| Yes      | numeric metric | shape_area  | SHAPE_Area | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = fho_date
```

## Data Commands

```ls
series e:rcky-ja8i d:2012-11-27T10:09:55.000Z t:editor=MJR t:county=Cook t:fho_enacte=Yes t:objectid=1 t:universali=UR1 t:municipali=Homewood t:fho_link="https://docs.google.com/open?id=0B0zIlzp6v4g1S193ZkJoelJTdVdpQnctLXhsWkdqdw" m:shape_area=147228317.032 m:shape_leng=73388.0626195 m:propreitar=1

series e:rcky-ja8i d:2012-11-27T10:09:55.000Z t:county=Cook t:fho_enacte=No t:objectid=2 t:universali=UR t:municipali=Flossmoor m:shape_area=101139509.05 m:shape_leng=93368.9037482

series e:rcky-ja8i d:2012-11-27T10:09:55.000Z t:editor=MJR t:county=Cook t:fho_enacte=Yes t:objectid=3 t:universali=UR3 t:municipali="Olympia Fields" t:fho_link="https://docs.google.com/open?id=0B0zIlzp6v4g1NVBHWkxhSXdTbC1oVlZhOE5rZGx4dw" m:shape_area=79538995.9458 m:shape_leng=69537.6219866 m:propreitar=3
```

## Meta Commands

```ls
metric m:propreitar p:integer l:Propreitar t:dataTypeName=number

metric m:shape_leng p:double l:SHAPE_Leng t:dataTypeName=number

metric m:shape_area p:double l:SHAPE_Area t:dataTypeName=number

entity e:rcky-ja8i l:"SSMMA Fair Housing" t:attribution="South Suburban Mayors and Managers Association" t:url=https://data.illinois.gov/api/views/rcky-ja8i

property e:rcky-ja8i t:meta.view v:id=rcky-ja8i v:category=Municipality v:attributionLink=http://www.ssmma.org v:averageRating=0 v:name="SSMMA Fair Housing" v:attribution="South Suburban Mayors and Managers Association"

property e:rcky-ja8i t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:rcky-ja8i t:meta.view.owner v:id=p88s-rkzf v:profileImageUrlMedium=/api/users/p88s-rkzf/profile_images/THUMB v:profileImageUrlLarge=/api/users/p88s-rkzf/profile_images/LARGE v:screenName=mrizzitiello v:profileImageUrlSmall=/api/users/p88s-rkzf/profile_images/TINY v:displayName=mrizzitiello

property e:rcky-ja8i t:meta.view.tableauthor v:id=74c3-ka9x v:profileImageUrlMedium=/api/users/74c3-ka9x/profile_images/THUMB v:profileImageUrlLarge=/api/users/74c3-ka9x/profile_images/LARGE v:screenName="Rey de Castro" v:profileImageUrlSmall=/api/users/74c3-ka9x/profile_images/TINY v:roleName=publisher v:displayName="Rey de Castro"
```

## Top Records

```ls
| :updated_at | objectid | municipali         | county | fho_enacte | fho_date | fho_link                                                                    | fho_staff_1 | fho_staff_2 | fho_staff1 | editor | propreitar | universali | shape_leng    | shape_area    | 
| =========== | ======== | ================== | ====== | ========== | ======== | =========================================================================== | =========== | =========== | ========== | ====== | ========== | ========== | ============= | ============= | 
| 1354010995  | 1        | Homewood           | Cook   | Yes        |          | https://docs.google.com/open?id=0B0zIlzp6v4g1S193ZkJoelJTdVdpQnctLXhsWkdqdw |             |             |            | MJR    | 1          | UR1        | 73388.0626195 | 147228317.032 | 
| 1354010995  | 2        | Flossmoor          | Cook   | No         |          |                                                                             |             |             |            |        |            | UR         | 93368.9037482 | 101139509.05  | 
| 1354010995  | 3        | Olympia Fields     | Cook   | Yes        |          | https://docs.google.com/open?id=0B0zIlzp6v4g1NVBHWkxhSXdTbC1oVlZhOE5rZGx4dw |             |             |            | MJR    | 3          | UR3        | 69537.6219866 | 79538995.9458 | 
| 1354010995  | 4        | Country Club Hills | Cook   | Yes        |          | https://docs.google.com/open?id=0B0zIlzp6v4g1bTYxdHpsZGpRSjIzZ2pPSWRxQjg1QQ |             |             |            | MJR    | 4          | UR4        | 77819.513342  | 131526346.171 | 
| 1354010995  | 5        | Thornton           | Cook   | Yes        |          | https://docs.google.com/open?id=0B0zIlzp6v4g1T2RTMkJBcUdRWVNuT2tSclFSdmFPQQ |             |             |            | MJR    | 5          | UR5        | 47526.0463823 | 66158504.2681 | 
| 1354010995  | 6        | Calumet City       | Cook   | No         |          |                                                                             |             |             |            |        |            | UR         | 118855.004397 | 205291311.845 | 
| 1354010995  | 7        | Dixmoor            | Cook   | Yes        |          |                                                                             |             |             |            |        |            | UR         | 25818.0895707 | 35230112.2731 | 
| 1354010995  | 8        | Dolton             | Cook   | Yes        |          | https://docs.google.com/open?id=0B0zIlzp6v4g1VnQ5ZVJXMmdTMHFybW5nOHl1REd5dw |             |             |            | MJR    | 8          | UR8        | 75222.5152121 | 129177579.301 | 
| 1354010995  | 9        | East Hazel Crest   | Cook   | Yes        |          |                                                                             |             |             |            |        |            | UR         | 25177.6016821 | 21834493.4708 | 
| 1354010995  | 10       | Richton Park       | Cook   | Yes        |          |                                                                             |             |             |            |        |            | UR         | 85701.3299538 | 102509534.008 | 
```