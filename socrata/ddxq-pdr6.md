# Nearby Independent Cook County Grocery Stores

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nearby-independent-cook-county-grocery-stores-180c9) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/ddxq-pdr6) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/ddxq-pdr6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/ddxq-pdr6/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | ddxq-pdr6 |
| Name | Nearby Independent Cook County Grocery Stores |
| Attribution | Danny Block, Chicago State University, and Frederick Blum Neighborhood Assistance Center |
| Category | Community & Economic Development |
| Tags | food, food desert |
| Created | 2013-08-26T20:13:55Z |
| Publication Date | 2013-08-26T23:34:15Z |

## Description

A list of independently owned- and operated grocery stores which are located at or within 1 mile of Chicago's city limits. In addition, this dataset contains additional information about the size and type of food offered by the grocery store. This dataset was provided to the City of Chicago by Chicago State University.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| No       | time           | :updated_at       | updated_at        | meta_data | meta_data   |
| Yes      | series tag     | store_name        | STORE NAME        | text      | text        |
| No       |                | address           | ADDRESS           | text      | text        |
| Yes      | series tag     | city              | CITY              | text      | text        |
| Yes      | series tag     | state             | STATE             | text      | text        |
| Yes      | series tag     | zip_code          | ZIP CODE          | text      | number      |
| Yes      | series tag     | size              | SIZE              | text      | text        |
| Yes      | numeric metric | registers         | REGISTERS         | number    | number      |
| Yes      | series tag     | produce           | PRODUCE           | checkbox  | checkbox    |
| Yes      | series tag     | meat              | MEAT              | checkbox  | checkbox    |
| Yes      | series tag     | general           | GENERAL           | checkbox  | checkbox    |
| Yes      | series tag     | meat_counter      | MEAT COUNTER      | checkbox  | checkbox    |
| Yes      | series tag     | deli_counter      | DELI COUNTER      | checkbox  | checkbox    |
| Yes      | series tag     | bakery            | BAKERY            | checkbox  | checkbox    |
| Yes      | series tag     | fish_counter      | FISH COUNTER      | checkbox  | checkbox    |
| Yes      | series tag     | alcohol           | ALCOHOL           | checkbox  | checkbox    |
| Yes      | series tag     | fresh_produce     | FRESH PRODUCE     | checkbox  | checkbox    |
| Yes      | series tag     | safetyconc        | SAFETYCONC        | checkbox  | checkbox    |
| Yes      | series tag     | cleanconce        | CLEANCONCE        | checkbox  | checkbox    |
| Yes      | series tag     | orientedet        | ORIENTEDET        | checkbox  | checkbox    |
| Yes      | series tag     | ethnic_speciality | ETHNIC SPECIALITY | text      | text        |
| Yes      | numeric metric | latitude          | LATITUDE          | number    | number      |
| Yes      | numeric metric | longitude         | LONGITUDE         | number    | number      |
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
series e:ddxq-pdr6 d:2013-08-26T16:33:43.000Z t:zip_code=60419 t:deli_counter=true t:cleanconce=false t:fresh_produce=true t:state=IL t:fish_counter=true t:general=true t:safetyconc=false t:size=Supermarket t:city=Dolton t:orientedet=false t:alcohol=false t:meat_counter=true t:store_name="Fairway Finer Foods" m:registers=4

series e:ddxq-pdr6 d:2013-08-26T16:33:43.000Z t:zip_code=60827 t:deli_counter=true t:cleanconce=false t:fresh_produce=true t:state=IL t:fish_counter=true t:general=true t:safetyconc=false t:size=Supermarket t:city="Calumet Park" t:orientedet=false t:bakery=true t:alcohol=true t:meat_counter=true t:store_name="Ultra Foods" m:registers=15

series e:ddxq-pdr6 d:2013-08-26T16:33:43.000Z t:zip_code=60805 t:deli_counter=true t:cleanconce=false t:fresh_produce=true t:state=IL t:fish_counter=true t:general=true t:safetyconc=false t:size=Supermarket t:city="Evergreen Park" t:bakery=true t:alcohol=false t:meat_counter=true t:store_name="Pete's Fresh Market" m:registers=9
```

## Meta Commands

```ls
metric m:registers p:float l:REGISTERS t:dataTypeName=number

metric m:latitude p:long l:LATITUDE t:dataTypeName=number

metric m:longitude p:long l:LONGITUDE t:dataTypeName=number

entity e:ddxq-pdr6 l:"Nearby Independent Cook County Grocery Stores" t:attribution="Danny Block, Chicago State University, and Frederick Blum Neighborhood Assistance Center" t:url=https://data.cityofchicago.org/api/views/ddxq-pdr6

property e:ddxq-pdr6 t:meta.view v:id=ddxq-pdr6 v:category="Community & Economic Development" v:attributionLink=http://www.csu.edu/nac/ v:averageRating=0 v:name="Nearby Independent Cook County Grocery Stores" v:attribution="Danny Block, Chicago State University, and Frederick Blum Neighborhood Assistance Center"

property e:ddxq-pdr6 t:meta.view.owner v:id=3qqc-w7ag v:profileImageUrlMedium=/api/users/3qqc-w7ag/profile_images/THUMB v:profileImageUrlLarge=/api/users/3qqc-w7ag/profile_images/LARGE v:screenName="Tom Schenk Jr" v:profileImageUrlSmall=/api/users/3qqc-w7ag/profile_images/TINY v:lastNotificationSeenAt=1491330280 v:displayName="Tom Schenk Jr"

property e:ddxq-pdr6 t:meta.view.tableauthor v:id=3qqc-w7ag v:profileImageUrlMedium=/api/users/3qqc-w7ag/profile_images/THUMB v:profileImageUrlLarge=/api/users/3qqc-w7ag/profile_images/LARGE v:screenName="Tom Schenk Jr" v:profileImageUrlSmall=/api/users/3qqc-w7ag/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1491330280 v:displayName="Tom Schenk Jr"
```

## Top Records

```ls
| :updated_at | store_name              | address               | city           | state | zip_code | size        | registers | produce | meat | general | meat_counter | deli_counter | bakery | fish_counter | alcohol | fresh_produce | safetyconc | cleanconce | orientedet | ethnic_speciality | latitude | longitude | 
| =========== | ======================= | ===================== | ============== | ===== | ======== | =========== | ========= | ======= | ==== | ======= | ============ | ============ | ====== | ============ | ======= | ============= | ========== | ========== | ========== | ================= | ======== | ========= | 
| 1377534823  | Fairway Finer Foods     | 200 E 144th St        | Dolton         | IL    | 60419    | Supermarket | 4.000000  |         |      | true    | true         | true         |        | true         | false   | true          | false      | false      | false      |                   |          |           | 
| 1377534823  | Ultra Foods             | 13001 Ashland Ave     | Calumet Park   | IL    | 60827    | Supermarket | 15.000000 |         |      | true    | true         | true         | true   | true         | true    | true          | false      | false      | false      |                   |          |           | 
| 1377534823  | Pete's Fresh Market     | 3720 W 95th St        | Evergreen Park | IL    | 60805    | Supermarket | 9.000000  |         |      | true    | true         | true         | true   | true         | false   | true          | false      | false      |            |                   |          |           | 
| 1377534823  | LAGENS SUPERMARKET INC  | 8859 S CALIFORNIA AVE | EVERGREEN PARK | IL    | 60805    | Supermarket | 2.000000  |         |      | true    |              | true         |        |              | true    | true          | false      | false      | false      |                   |          |           | 
| 1377534823  | SUPERMERCADO TORRES INC | 5304 W 25TH ST        | Cicero         | IL    | 60804    | Supermarket | 5.000000  |         |      | true    | true         | true         |        | true         | true    | true          | false      | false      | true       | Hispanic          |          |           | 
| 1377534823  | La Chiquita             | 4926 W Cermak Rd      | Cicero         | IL    | 60804    | Supermarket | 8.000000  |         |      | true    | true         | true         | true   | true         | true    | true          | false      | false      | true       | Hispanic          |          |           | 
| 1377534823  | Cermak Produce          | 4728 W Cermak Rd      | Cicero         | IL    | 60804    | Supermarket | 3.000000  | true    |      |         | true         | true         |        | true         | false   | true          | false      | false      | true       | Hispanic          |          |           | 
| 1377534823  | Carnicerias Jimenez     | 1948 S Cicero Ave     | Cicero         | IL    | 60804    | Supermarket | 2.000000  |         |      | true    | true         | true         |        | true         | true    | true          | false      | false      | true       | Hispanic          |          |           | 
| 1377534823  | Carniceria 5 Hermanos   | 6500 16th St          | Berwyn         | IL    | 60402    | Supermarket | 2.000000  |         |      | true    | true         | true         |        | true         | false   | true          | false      | false      | true       | Hispanic          |          |           | 
| 1377534823  | Torres #3 Supermarket   | 1642 S Cicero Ave     | Cicero         | IL    | 60804    | Supermarket | 2.000000  |         |      | true    | true         | true         |        | true         | true    | true          | false      | false      | true       | Hispanic          |          |           | 
```