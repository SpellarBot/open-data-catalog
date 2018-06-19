# IDPH Licensed Youth Camps

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idph-licensed-youth-camps-554a4) |
| Metadata | [Link](https://data.illinois.gov/api/views/2r3c-zkbc) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/2r3c-zkbc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/2r3c-zkbc/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 2r3c-zkbc |
| Name | IDPH Licensed Youth Camps |
| Attribution | Division of Environmental Health |
| Category | Public Health |
| Tags | youth, camps |
| Created | 2012-03-23T17:45:36Z |
| Publication Date | 2017-03-01T21:10:33Z |

## Description

List of Licensed Youth Camps in Illinois. Updated March 2017

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| No       | time           | :updated_at   | updated_at    | meta_data | meta_data   |
| Yes      | series tag     | camp_name     | Camp Name     | text      | text        |
| No       |                | address       | Address       | text      | text        |
| Yes      | series tag     | city_d        | City          | text      | text        |
| Yes      | series tag     | state         | State         | text      | text        |
| Yes      | series tag     | zip_code_d    | Zip Code      | text      | text        |
| Yes      | series tag     | phone         | Phone         | phone     | phone       |
| Yes      | series tag     | county_r      | County        | text      | text        |
| Yes      | numeric metric | occupant_load | Occupant Load | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:2r3c-zkbc d:2017-03-01T21:04:59.000Z t:camp_name="CAMP EMMAUS" t:phone_number="(815) 734-4268" t:county_r=OGLE t:zip_code_d=61054 t:state=IL t:city_d="MT MORRIS" m:occupant_load=200

series e:2r3c-zkbc d:2017-03-01T21:04:59.000Z t:camp_name="REHOBOTH BAPTIST CAMP" t:phone_number="(618) 423-2649" t:county_r=FAYETTE t:zip_code_d=62080 t:state=IL t:city_d=RAMSEY m:occupant_load=100

series e:2r3c-zkbc d:2017-03-01T21:04:59.000Z t:camp_name="MISSISSIPPI VALLEY CHRISTIAN CAMP" t:phone_number="(217) 723-4337" t:county_r=PIKE t:zip_code_d=62363 t:state=IL t:city_d=PITTSFIELD m:occupant_load=160
```

## Meta Commands

```ls
metric m:occupant_load p:integer l:"Occupant Load" t:dataTypeName=number

entity e:2r3c-zkbc l:"IDPH Licensed Youth Camps" t:attribution="Division of Environmental Health" t:url=https://data.illinois.gov/api/views/2r3c-zkbc

property e:2r3c-zkbc t:meta.view v:id=2r3c-zkbc v:category="Public Health" v:attributionLink=http://www.dph.illinois.gov/topics-services/environmental-health-protection/recreation/campgrounds-youth-camps v:averageRating=0 v:name="IDPH Licensed Youth Camps" v:attribution="Division of Environmental Health"

property e:2r3c-zkbc t:meta.view.owner v:id=vice-rsdw v:profileImageUrlMedium=/api/users/vice-rsdw/profile_images/THUMB v:profileImageUrlLarge=/api/users/vice-rsdw/profile_images/LARGE v:screenName="IDPH Staff" v:profileImageUrlSmall=/api/users/vice-rsdw/profile_images/TINY v:displayName="IDPH Staff"

property e:2r3c-zkbc t:meta.view.tableauthor v:id=vice-rsdw v:profileImageUrlMedium=/api/users/vice-rsdw/profile_images/THUMB v:profileImageUrlLarge=/api/users/vice-rsdw/profile_images/LARGE v:screenName="IDPH Staff" v:profileImageUrlSmall=/api/users/vice-rsdw/profile_images/TINY v:roleName=publisher v:displayName="IDPH Staff"
```

## Top Records

```ls
| :updated_at | camp_name                         | address                      | city_d       | state | zip_code_d | phone                  | county_r | occupant_load | 
| =========== | ================================= | ============================ | ============ | ===== | ========== | ====================== | ======== | ============= | 
| 1488402299  | CAMP EMMAUS                       | 3011 WEST CAMP RD BOX 128    | MT MORRIS    | IL    | 61054      | [(815) 734-4268, null] | OGLE     | 200           | 
| 1488402299  | REHOBOTH BAPTIST CAMP             | R 1                          | RAMSEY       | IL    | 62080      | [(618) 423-2649, null] | FAYETTE  | 100           | 
| 1488402299  | MISSISSIPPI VALLEY CHRISTIAN CAMP | 24201 STATE ROUTE 100        | PITTSFIELD   | IL    | 62363      | [(217) 723-4337, null] | PIKE     | 160           | 
| 1488402299  | CAMP WIDJIWAGAN                   | #71 WIENOLD LANE             | SPRINGFIELD  | IL    | 62707      | [(217) 529-2212, null] | SANGAMON | 320           | 
| 1488402299  | WEYANAH/BROWN WILDERNESS          | RURAL ROUTE-LAKE CARLINVILLE | CARLINVILLE  | IL    | 62626      | [(217) 313-7045, null] | MACOUPIN | 40            | 
| 1488402299  | UNION GROVE YOUTH CAMP            | 1481 CO HWY 12               | JOHNSONVILLE | IL    | 62850      | [(618) 835-2657, null] | WAYNE    | 212           | 
| 1488402299  | CAMP ILLINEK                      | 65500 IRON BRIDGE ROAD       | CHATHAM      | IL    | 62629      | [(217) 483-2156, null] | SANGAMON | 100           | 
| 1488402299  | CAMP DUNCAN YMCA                  | 32405 N HWY 12               | INGLESIDE    | IL    | 60041      | [(847) 546-8086, null] | LAKE     | 500           | 
| 1488402299  | CAMP POKANOKA                     | 1879 NO 2703 ROAD            | OTTAWA       | IL    | 61350      | [(000) 000-0000, null] | LA SALLE | 292           | 
| 1488402299  | SUNSET HILL CAMPGROUND            | PO BOX 1695                  | GRANITE CITY | IL    | 62040      | [(618) 659-3812, null] | MADISON  | 400           | 
```