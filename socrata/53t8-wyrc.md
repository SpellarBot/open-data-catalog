# Grocery Stores - 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/grocery-stores-2013-1836b) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/53t8-wyrc) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/53t8-wyrc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/53t8-wyrc/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | 53t8-wyrc |
| Name | Grocery Stores - 2013 |
| Attribution | City of Chicago |
| Category | Community & Economic Development |
| Tags | food, food desert |
| Created | 2013-08-23T04:26:07Z |
| Publication Date | 2013-08-26T20:39:15Z |

## Description

Contains a list of grocery stores which was used by the city to calculate the estimates of Chicagoans living in food deserts in 2011. Data in this file can be cross-referenced with the city's business license data (http://bit.ly/sMFZdN).

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| Yes      | series tag     | store_name          | STORE NAME          | text      | text        |
| Yes      | series tag     | license_id          | LICENSE ID          | text      | number      |
| Yes      | series tag     | account_number      | ACCOUNT NUMBER      | text      | number      |
| Yes      | numeric metric | square_feet         | SQUARE FEET         | number    | number      |
| Yes      | series tag     | buffer_size         | BUFFER SIZE         | text      | text        |
| No       |                | address             | ADDRESS             | text      | text        |
| Yes      | series tag     | zip_code            | ZIP CODE            | text      | number      |
| Yes      | series tag     | community_area_name | COMMUNITY AREA NAME | text      | text        |
| Yes      | series tag     | community_area      | COMMUNITY AREA      | text      | number      |
| Yes      | series tag     | ward                | WARD                | text      | number      |
| Yes      | numeric metric | census_tract        | CENSUS TRACT        | number    | number      |
| Yes      | numeric metric | census_block        | CENSUS BLOCK        | number    | number      |
| No       |                | x_coordinate        | X COORDINATE        | number    | number      |
| No       |                | y_coordinate        | Y COORDINATE        | number    | number      |
| No       |                | latitude            | LATITUDE            | number    | number      |
| No       |                | longitude           | LONGITUDE           | number    | number      |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = address,x_coordinate,y_coordinate,latitude,longitude
```

## Data Commands

```ls
series e:53t8-wyrc d:2013-01-01T00:00:00.000Z t:ward=3 t:account_number=17055 t:zip_code=60653 t:buffer_size=B t:community_area_name="GRAND BOULEVARD" t:license_id=48663 t:community_area=38 t:store_name="200 LIQUORS" m:census_block=170313815001007 m:census_tract=17031381500 m:square_feet=5000

series e:53t8-wyrc d:2013-01-01T00:00:00.000Z t:ward=46 t:account_number=9830 t:zip_code=60613 t:buffer_size=B t:community_area_name="LAKE VIEW" t:license_id=24279 t:community_area=6 t:store_name="3600 COMMISSARY" m:census_block=170310609004001 m:census_tract=17031060900 m:square_feet=3800

series e:53t8-wyrc d:2013-01-01T00:00:00.000Z t:ward=14 t:account_number=260303 t:zip_code=60632 t:buffer_size=A t:community_area_name="ARCHER HEIGHTS" t:license_id=1336669 t:community_area=57 t:store_name="4343 PETES FRESH MARKET" m:census_block=170315701001015 m:census_tract=17031570100 m:square_feet=57000
```

## Meta Commands

```ls
metric m:square_feet p:integer l:"SQUARE FEET" t:dataTypeName=number

metric m:census_tract p:long l:"CENSUS TRACT" t:dataTypeName=number

metric m:census_block p:long l:"CENSUS BLOCK" t:dataTypeName=number

entity e:53t8-wyrc l:"Grocery Stores - 2013" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/53t8-wyrc

property e:53t8-wyrc t:meta.view v:id=53t8-wyrc v:category="Community & Economic Development" v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Grocery Stores - 2013" v:attribution="City of Chicago"

property e:53t8-wyrc t:meta.view.owner v:id=3qqc-w7ag v:profileImageUrlMedium=/api/users/3qqc-w7ag/profile_images/THUMB v:profileImageUrlLarge=/api/users/3qqc-w7ag/profile_images/LARGE v:screenName="Tom Schenk Jr" v:profileImageUrlSmall=/api/users/3qqc-w7ag/profile_images/TINY v:lastNotificationSeenAt=1491330280 v:displayName="Tom Schenk Jr"

property e:53t8-wyrc t:meta.view.tableauthor v:id=3qqc-w7ag v:profileImageUrlMedium=/api/users/3qqc-w7ag/profile_images/THUMB v:profileImageUrlLarge=/api/users/3qqc-w7ag/profile_images/LARGE v:screenName="Tom Schenk Jr" v:profileImageUrlSmall=/api/users/3qqc-w7ag/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1491330280 v:displayName="Tom Schenk Jr"
```

## Top Records

```ls
| store_name                            | license_id | account_number | square_feet | buffer_size | address              | zip_code | community_area_name    | community_area | ward | census_tract | census_block    | x_coordinate       | y_coordinate       | latitude      | longitude      | 
| ===================================== | ========== | ============== | =========== | =========== | ==================== | ======== | ====================== | ============== | ==== | ============ | =============== | ================== | ================== | ============= | ============== | 
| 200 LIQUORS                           | 48663      | 17055          | 5000        | B           | 204 E 47TH ST        | 60653    | GRAND BOULEVARD        | 38             | 3    | 17031381500  | 170313815001007 | 1178461.6344048942 | 1873949.3843109086 | 41.8094238941 | -87.6209518020 | 
| 3600 COMMISSARY                       | 24279      | 9830           | 3800        | B           | 3600 N LAKE SHORE DR | 60613    | LAKE VIEW              | 6              | 46   | 17031060900  | 170310609004001 | 1171865.8187503873 | 1924645.0382131825 | 41.9486836744 | -87.6436497585 | 
| 4343 PETES FRESH MARKET               | 1336669    | 260303         | 57000       | A           | 4343 S PULASKI RD    | 60632    | ARCHER HEIGHTS         | 57             | 14   | 17031570100  | 170315701001015 | 1150447.9257608664 | 1875370.2855434741 | 41.8139143113 | -87.7236649419 | 
| 4700 PETE'S FRESH MARKET              | 1243125    | 245519         | 45000       | A           | 4700 S KEDZIE AVE    | 60632    | BRIGHTON PARK          | 58             | 14   | 17031842800  | 170318428004023 | 1155791.9493024794 | 1873270.7784828772 | 41.8080472717 | -87.7041188223 | 
| 5659 W. DIVERSEY                      | 1575023    | 277375         | 4000        | B           | 5659 W DIVERSEY AVE  | 60639    | BELMONT CRAGIN         | 19             | 30   | 17031190602  | 170311906022001 | 1137914.0810304238 | 1918001.6539807494 | 41.9311354035 | -87.7686121306 | 
| 7400 S HALSTED FOOD AND LIQUORS, INC. | 980        | 186            | 10001       | A           | 7400 S HALSTED ST    | 60621    | ENGLEWOOD              | 68             | 17   | 17031681300  | 170316813003005 | 1172208.8098604858 | 1855768.9165432698 | 41.7596745819 | -87.6444202389 | 
| 79 FOOD BASKET                        | 1958784    | 341069         | 3000        | B           | 1351 W 79TH ST       | 60620    | AUBURN GRESHAM         | 71             | 21   | 17031710700  | 170317107001012 | 1168478.9380996425 | 1852330.8146064386 | 41.7503211206 | -87.6581890529 | 
| A & B FOOD MARKET INC                 | 43181      | 6483           | 10001       | A           | 5057 W DIVISION ST   | 60651    | AUSTIN                 | 25             | 37   | 17031251100  | 170312511004000 | 1142184.0432471954 | 1907473.3799980525 | 41.9021664421 | -87.7531823487 | 
| A & G LIQUORS                         | 44373      | 35423          | 4800        | B           | 6945 S STATE ST      | 60637    | GREATER GRAND CROSSING | 69             | 6    | 17031690400  | 170316904003005 | 1177546.7151574378 | 1858784.7080415017 | 41.7678312792 | -87.6247659397 | 
| A & R FOOD MART                       | 9125       | 4227           | 2500        | B           | 5952 W GRAND AVE     | 60639    | BELMONT CRAGIN         | 19             | 37   | 17031191302  | 170311913021018 | 1136148.4645573950 | 1914149.5267326030 | 41.9205964582 | -87.7751926809 | 
```