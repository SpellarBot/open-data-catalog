# Street Lighting

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/street-lighting) |
| Metadata | [Link](https://data.brla.gov/api/views/2jru-byiu) |
| Data: JSON | [100 Rows](https://data.brla.gov/api/views/2jru-byiu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.brla.gov/api/views/2jru-byiu/rows.csv?max_rows=100) |
| Host | data.brla.gov |
| Id | 2jru-byiu |
| Name | Street Lighting |
| Attribution | Department of Transportation and Drainage Traffic Engineering Division |
| Category | Transportation and Infrastructure |
| Tags | lighting; street; utility; transportation |
| Created | 2015-06-28T00:21:04Z |
| Publication Date | 2016-03-03T03:38:59Z |

## Description

This dataset contains the location and attribute information about all of the street lights in East Baton Rouge Parish, Louisiana. This includes lighting along neighborhood streets and major roads.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name          | Data Type | Render Type |
| ======== | ============== | =========== | ============= | ========= | =========== |
| No       | time           | :updated_at | updated_at    | meta_data | meta_data   |
| Yes      | series tag     | idhighwayl  | LIGHT ID NO   | text      | text        |
| Yes      | series tag     | route       | ROUTE         | text      | text        |
| Yes      | numeric metric | direction   | DIRECTION     | number    | number      |
| Yes      | series tag     | poletype    | POLE TYPE     | text      | text        |
| Yes      | series tag     | lightprese  | LIGHT PRESENT | text      | text        |
| Yes      | series tag     | sideofroad  | SIDE OF ROAD  | text      | text        |
| Yes      | series tag     | image       | IMAGE         | url       | url         |
| Yes      | numeric metric | date        | SURVEY DATE   | number    | text        |
| Yes      | numeric metric | elevation   | ELEVATION     | number    | number      |
| No       |                | latitude    | LATITUDE      | number    | number      |
| No       |                | longitude   | LONGITUDE     | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = latitude,longitude
```

## Data Commands

```ls
series e:2jru-byiu d:2015-06-27T17:21:25.000Z t:route="Picardy Ave" t:poletype=Metal t:idhighwayl=5491-18836 t:image=https://ivision.fugro.com/LouisianaLocals_Video/1734/ROW/138416EV600/000000000002/000000284066.jpg t:sideofroad=Right t:lightprese=Yes m:direction=5 m:elevation=37.864 m:date=20130804

series e:2jru-byiu d:2015-06-27T17:21:25.000Z t:route="Kaylynn Ave" t:poletype=Metal t:idhighwayl=5491-12768 t:image=https://ivision.fugro.com/LouisianaLocals_Video/1734/ROW/13891DEY500/000000000116/000000092060.jpg t:sideofroad=Right t:lightprese=Yes m:direction=6 m:elevation=23.471 m:date=20130809

series e:2jru-byiu d:2015-06-27T17:21:32.000Z t:route="W Trent Jones Ave" t:poletype=Metal t:idhighwayl=5491-28585 t:image=https://ivision.fugro.com/LouisianaLocals_Video/1749/ROW/13AK0YTF800/000000000262/000000080094.jpg t:sideofroad=Right t:lightprese=Yes m:direction=6 m:elevation=32.795 m:date=20131020
```

## Meta Commands

```ls
metric m:direction p:integer l:DIRECTION d:"Direction in which the sign faces" t:dataTypeName=number

metric m:date p:integer l:"SURVEY DATE" d:"Date the street light was surveyed" t:dataTypeName=number

metric m:elevation p:float l:ELEVATION d:"Elevation of the street light in feet" t:dataTypeName=number

entity e:2jru-byiu l:"Street Lighting" t:attribution="Department of Transportation and Drainage Traffic Engineering Division" t:url=https://data.brla.gov/api/views/2jru-byiu

property e:2jru-byiu t:meta.view v:id=2jru-byiu v:category="Transportation and Infrastructure" v:attributionLink=http://brgov.com/dept/dpw/traffic/ v:averageRating=0 v:name="Street Lighting" v:attribution="Department of Transportation and Drainage Traffic Engineering Division"

property e:2jru-byiu t:meta.view.license v:name="Public Domain"

property e:2jru-byiu t:meta.view.owner v:id=mjn2-v86v v:profileImageUrlMedium=/api/users/mjn2-v86v/profile_images/THUMB v:profileImageUrlLarge=/api/users/mjn2-v86v/profile_images/LARGE v:screenName="Open Data BR" v:profileImageUrlSmall=/api/users/mjn2-v86v/profile_images/TINY v:displayName="Open Data BR"

property e:2jru-byiu t:meta.view.tableauthor v:id=mjn2-v86v v:profileImageUrlMedium=/api/users/mjn2-v86v/profile_images/THUMB v:profileImageUrlLarge=/api/users/mjn2-v86v/profile_images/LARGE v:screenName="Open Data BR" v:profileImageUrlSmall=/api/users/mjn2-v86v/profile_images/TINY v:roleName=viewer v:displayName="Open Data BR"
```

## Top Records

```ls
| :updated_at | idhighwayl  | route             | direction | poletype | lightprese | sideofroad | image                                                                                                        | date     | elevation | latitude    | longitude    | 
| =========== | =========== | ================= | ========= | ======== | ========== | ========== | ============================================================================================================ | ======== | ========= | =========== | ============ | 
| 1435425685  | 5491-18836  | Picardy Ave       | 5         | Metal    | Yes        | Right      | [https://ivision.fugro.com/LouisianaLocals_Video/1734/ROW/138416EV600/000000000002/000000284066.jpg, null]   | 20130804 | 37.864    | 30.40004131 | -91.11106652 | 
| 1435425685  | 5491-12768  | Kaylynn Ave       | 6         | Metal    | Yes        | Right      | [https://ivision.fugro.com/LouisianaLocals_Video/1734/ROW/13891DEY500/000000000116/000000092060.jpg, null]   | 20130809 | 23.471    | 30.38793699 | -91.09981147 | 
| 1435425692  | 5491-28585  | W Trent Jones Ave | 6         | Metal    | Yes        | Right      | [https://ivision.fugro.com/LouisianaLocals_Video/1749/ROW/13AK0YTF800/000000000262/000000080094.jpg, null]   | 20131020 | 32.795    | 30.3421506  | -91.01528026 | 
| 1435425693  | 5491-28526  | Winterwood Ct     | 6         | Metal    | Yes        | Right      | [https://ivision.fugro.com/LouisianaLocals_Video/1749/ROW/13B50RTQ000/000000000010/000000088013.jpg, null]   | 20131105 | 41.666    | 30.39410133 | -90.98029905 | 
| 1435425696  | 5491-24164  | S Donmoor Ave     | 6         | Wood     | Yes        | Left       | [https://ivision.fugro.com/LouisianaLocals_Video/1749/ROW/13CB0NTGX00/000000000192/000000212063.jpg, null]   | 20131211 | 55.406    | 30.44747575 | -91.11827211 | 
| 1435425696  | 5491-6196   | Dvwy              | 5         | Wood     | Yes        | Right      | [https://ivision.fugro.com/LouisianaLocals_Video/1749/ROW/13BJ12TTZ00/000000000157/000000068001.jpg, null]   | 20131119 | 50.639    | 30.43281682 | -91.05314755 | 
| 1435425697  | 5491-6252   | Delplaza Dr       | 5         | Wood     | Yes        | Right      | [https://ivision.fugro.com/LouisianaLocals_Video/1749/ROW/13C115TP700/000000000181/000000128159.jpg, null]   | 20131201 | 51.591    | 30.43830591 | -91.08372269 | 
| 1435425702  | 5491-4044   | Cedar Pointe Blvd | 6         | Metal    | Yes        | Right      | [https://ivision.fugro.com/LouisianaLocals_Video/1749/ROW/14290PTAN00/000000000212/000000344164.jpg, null]   | 20140209 | 60.849    | 30.50607469 | -91.09456268 | 
| 1435425714  | 85006-23779 | Snipe St          | 6         | Wood     | Yes        | Right      | [https://ivision.fugro.com/LouisianaLocals13_Video/1731/ROW/143K0MBBL00/000000004096/000000120047.jpg, null] | 20140320 | 65.544    | 30.52310302 | -91.17493389 | 
| 1435425715  | 85006-16157 | N 31st St         | 6         | Wood     | Yes        | Right      | [https://ivision.fugro.com/LouisianaLocals13_Video/1766/ROW/143H13G3X00/000000000089/000000216137.jpg, null] | 20140317 | 62.004    | 30.45892296 | -91.15746178 | 
```