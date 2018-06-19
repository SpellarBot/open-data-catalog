# SSMMA Natural Areas

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ssmma-natural-areas-7c229) |
| Metadata | [Link](https://data.illinois.gov/api/views/tkef-fgt6) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/tkef-fgt6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/tkef-fgt6/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | tkef-fgt6 |
| Name | SSMMA Natural Areas |
| Attribution | South Suburban Mayors and Managers Association |
| Category | Municipality |
| Tags | natural resources, planning, chicago southland |
| Created | 2012-11-27T19:47:46Z |
| Publication Date | 2013-02-21T16:24:30Z |

## Description

This dataset details natural areas in the Chicago Southland region

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type | Render Type |
| ======== | ============== | ============ | ============ | ========= | =========== |
| No       | time           | :updated_at  | updated_at   | meta_data | meta_data   |
| Yes      | series tag     | name         | Name         | text      | text        |
| Yes      | series tag     | ownership    | Ownership    | text      | text        |
| Yes      | series tag     | type         | Type         | text      | text        |
| Yes      | numeric metric | acres        | Acres        | number    | number      |
| Yes      | series tag     | description  | Description  | text      | text        |
| Yes      | series tag     | municipality | Municipality | text      | text        |
| Yes      | series tag     | county       | County       | text      | text        |
| Yes      | series tag     | contact_na   | Contact_Na   | text      | text        |
| Yes      | series tag     | contact_ph   | Contact_Ph   | text      | text        |
| Yes      | series tag     | contact_em   | Contact_Em   | text      | text        |
| Yes      | series tag     | contaminan   | Contaminan   | text      | text        |
| Yes      | series tag     | editor       | Editor       | text      | text        |
| Yes      | numeric metric | propreitar   | Propreitar   | number    | number      |
| Yes      | series tag     | universali   | UniversalI   | text      | text        |
| Yes      | numeric metric | shape_leng   | SHAPE_Leng   | number    | number      |
| Yes      | numeric metric | shape_area   | SHAPE_Area   | number    | number      |
| No       |                | id           | ID           | text      | number      |
| No       |                | point_x      | POINT_X      | number    | number      |
| No       |                | point_y      | POINT_Y      | number    | number      |
| Yes      | series tag     | location_1   | Location 1   | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = id,point_x,point_y
```

## Data Commands

```ls
series e:tkef-fgt6 d:2012-11-27T11:47:49.000Z t:editor=MJR t:ownership="Forest Preserve District of Cook County" t:county=Cook t:name="Jurgenson Woods" t:municipality=Matteson t:universali=UR1793 t:type="Forest Preserve" m:shape_area=19674718.0724 m:shape_leng=17764.3843065 m:propreitar=1793

series e:tkef-fgt6 d:2012-11-27T11:47:49.000Z t:editor=MJR t:ownership="Forest Preserve District of Cook County" t:county=Cook t:name="Lansing Woods" t:municipality=Lansing t:universali=UR1794 t:type="Forest Preserve" m:shape_area=5801093.52811 m:shape_leng=12845.3493948 m:propreitar=1794

series e:tkef-fgt6 d:2012-11-27T11:47:49.000Z t:editor=MJR t:ownership="Forest Preserve District of Cook County" t:county=Cook t:name="Lansing Woods" t:municipality=Lansing t:universali=UR1795 t:type="Forest Preserve" m:shape_area=27830158.4185 m:shape_leng=21087.2045528 m:propreitar=1795
```

## Meta Commands

```ls
metric m:acres p:integer l:Acres t:dataTypeName=number

metric m:propreitar p:integer l:Propreitar t:dataTypeName=number

metric m:shape_leng p:double l:SHAPE_Leng t:dataTypeName=number

metric m:shape_area p:double l:SHAPE_Area t:dataTypeName=number

entity e:tkef-fgt6 l:"SSMMA Natural Areas" t:attribution="South Suburban Mayors and Managers Association" t:url=https://data.illinois.gov/api/views/tkef-fgt6

property e:tkef-fgt6 t:meta.view v:id=tkef-fgt6 v:category=Municipality v:attributionLink=http://www.ssmma.org v:averageRating=0 v:name="SSMMA Natural Areas" v:attribution="South Suburban Mayors and Managers Association"

property e:tkef-fgt6 t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:tkef-fgt6 t:meta.view.owner v:id=p88s-rkzf v:profileImageUrlMedium=/api/users/p88s-rkzf/profile_images/THUMB v:profileImageUrlLarge=/api/users/p88s-rkzf/profile_images/LARGE v:screenName=mrizzitiello v:profileImageUrlSmall=/api/users/p88s-rkzf/profile_images/TINY v:displayName=mrizzitiello

property e:tkef-fgt6 t:meta.view.tableauthor v:id=p88s-rkzf v:profileImageUrlMedium=/api/users/p88s-rkzf/profile_images/THUMB v:profileImageUrlLarge=/api/users/p88s-rkzf/profile_images/LARGE v:screenName=mrizzitiello v:profileImageUrlSmall=/api/users/p88s-rkzf/profile_images/TINY v:displayName=mrizzitiello
```

## Top Records

```ls
| :updated_at | name                           | ownership                               | type            | acres | description | municipality | county | contact_na | contact_ph | contact_em | contaminan | editor | propreitar | universali | shape_leng    | shape_area    | id   | point_x | point_y | location_1 | 
| =========== | ============================== | ======================================= | =============== | ===== | =========== | ============ | ====== | ========== | ========== | ========== | ========== | ====== | ========== | ========== | ============= | ============= | ==== | ======= | ======= | ========== | 
| 1354016869  | Jurgenson Woods                | Forest Preserve District of Cook County | Forest Preserve |       |             | Matteson     | Cook   |            |            |            |            | MJR    | 1793       | UR1793     | 17764.3843065 | 19674718.0724 | 1793 | 1189680 | 1776950 |            | 
| 1354016869  | Lansing Woods                  | Forest Preserve District of Cook County | Forest Preserve |       |             | Lansing      | Cook   |            |            |            |            | MJR    | 1794       | UR1794     | 12845.3493948 | 5801093.52811 | 1794 | 1189910 | 1776940 |            | 
| 1354016869  | Lansing Woods                  | Forest Preserve District of Cook County | Forest Preserve |       |             | Lansing      | Cook   |            |            |            |            | MJR    | 1795       | UR1795     | 21087.2045528 | 27830158.4185 | 1795 | 1191060 | 1776830 |            | 
| 1354016869  | Lansing Woods                  | Forest Preserve District of Cook County | Forest Preserve |       |             | Lansing      | Cook   |            |            |            |            | MJR    | 1796       | UR1796     | 15786.5049839 | 12299103.695  | 1796 | 1196360 | 1777000 |            | 
| 1354016869  | Erfert Park                    | Lan Oak Park District                   | Local Park      |       |             | Lansing      | Cook   |            |            |            |            | MJR    | 1797       | UR1797     | 4350.91636954 | 777233.226276 | 1797 | 1200250 | 1781340 |            | 
| 1354016869  | Lan Oak Park                   | Lan Oak Park District                   | Local Park      |       |             | Lansing      | Cook   |            |            |            |            | MJR    | 1798       | UR1798     | 3803.59625504 | 801409.15557  | 1798 | 1196850 | 1787520 |            | 
| 1354016869  | Winterhoff Park                | Lan Oak Park District                   | Local Park      |       |             | Lansing      | Cook   |            |            |            |            | MJR    | 1799       | UR1799     | 1395.06155213 | 81155.6496267 | 1799 | 1201730 | 1786470 |            | 
| 1354016869  | Potts Park                     | Lan Oak Park District                   | Local Park      |       |             | Lansing      | Cook   |            |            |            |            | MJR    | 1800       | UR1800     | 1458.15102949 | 126021.21418  | 1800 | 1198820 | 1791290 |            | 
| 1354016869  | Veterans Park                  | Memorial Park District                  | Local Park      |       |             | Calumet City |        |            |            |            |            | MJR    | 1801       | UR1801     | 3927.09074752 | 661346.036715 | 1801 | 1201240 | 1793180 |            | 
| 1354016869  | Shabbona Woods Forest Preserve | Forest Preserve District of Cook County | Forest Preserve |       |             | Calumet City | Cook   |            |            |            |            | MJR    | 1802       | UR1802     | 14565.8753427 | 11791521.5071 | 1802 | 1195990 | 1798200 |            | 
```