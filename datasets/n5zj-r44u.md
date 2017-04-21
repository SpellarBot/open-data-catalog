# Problem Landlord List

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/problem-landlord-list-5e49c) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/n5zj-r44u) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/n5zj-r44u/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/n5zj-r44u/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | n5zj-r44u |
| Name | Problem Landlord List |
| Attribution | City of Chicago |
| Category | Buildings |
| Tags | buildings, violations |
| Created | 2015-01-26T05:02:01Z |
| Publication Date | 2016-07-11T02:41:12Z |

## Description

This list describes landlords and property owners who are designated  "problem landlords". Landlords on this list have had two or more administrative hearing causes brought against them and were found liable or defaulted to one or more serious building violations.

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type | Render Type |
| ======== | ============== | ===================== | ===================== | ========= | =========== |
| No       | time           | :updated_at           | updated_at            | meta_data | meta_data   |
| No       |                | address               | ADDRESS               | text      | text        |
| No       |                | secondary_address     | SECONDARY ADDRESS     | text      | text        |
| Yes      | series tag     | zip_code              | ZIP Code              | text      | text        |
| Yes      | series tag     | respondent            | RESPONDENT            | text      | text        |
| Yes      | series tag     | community_area        | COMMUNITY AREA        | text      | text        |
| Yes      | series tag     | community_area_number | COMMUNITY AREA NUMBER | text      | text        |
| Yes      | series tag     | ward                  | WARD                  | text      | text        |
| Yes      | numeric metric | census_tracts         | CENSUS TRACTS         | number    | text        |
| Yes      | numeric metric | census_blocks         | CENSUS BLOCKS         | number    | text        |
| Yes      | series tag     | street_block_id       | STREET BLOCK ID       | text      | text        |
| No       |                | x_coordinate          | X_COORDINATE          | number    | number      |
| No       |                | y_coordinate          | Y_COORDINATE          | number    | number      |
| No       |                | longitude             | LONGITUDE             | number    | number      |
| No       |                | latitude              | LATITUDE              | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address,secondary_address,x_coordinate,y_coordinate,longitude,latitude
```

## Data Commands

```ls
series e:n5zj-r44u d:2016-07-10T19:35:54.000Z t:respondent="Woo S Chung; Eun Y Sakanashi" t:street_block_id=52291 t:ward=34 t:zip_code=60628-4813 t:community_area=ROSELAND t:community_area_number=49 m:census_tracts=17031491300 m:census_blocks=170314913002003

series e:n5zj-r44u d:2016-07-10T19:35:54.000Z t:respondent="Felice's Investments, Inc" t:street_block_id=40920 t:ward=34 t:zip_code=60643 t:community_area="MORGAN PARK" t:community_area_number=75 m:census_tracts=17031750100 m:census_blocks=170317501004031

series e:n5zj-r44u d:2016-07-10T19:35:54.000Z t:respondent="Hameed O Andu" t:street_block_id=36994 t:ward=23 t:zip_code=60629-3825 t:community_area="WEST ELSDON" t:community_area_number=62 m:census_tracts=17031620400 m:census_blocks=170316204001011
```

## Meta Commands

```ls
metric m:census_tracts p:long l:"CENSUS TRACTS" d:"Census tract number based on the 2010 census tracts. For more information, see https://www.census.gov/geo/reference/gtc/gtc_ct.html" t:dataTypeName=number

metric m:census_blocks p:long l:"CENSUS BLOCKS" d:"Census blocks based on the 2010 census blocks. For more information, see: https://www.census.gov/geo/maps-data/maps/block/2010/" t:dataTypeName=number

entity e:n5zj-r44u l:"Problem Landlord List" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/n5zj-r44u

property e:n5zj-r44u t:meta.view v:id=n5zj-r44u v:category=Buildings v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Problem Landlord List" v:attribution="City of Chicago"

property e:n5zj-r44u t:meta.view.owner v:id=3qqc-w7ag v:profileImageUrlMedium=/api/users/3qqc-w7ag/profile_images/THUMB v:profileImageUrlLarge=/api/users/3qqc-w7ag/profile_images/LARGE v:screenName="Tom Schenk Jr" v:profileImageUrlSmall=/api/users/3qqc-w7ag/profile_images/TINY v:lastNotificationSeenAt=1491330280 v:displayName="Tom Schenk Jr"

property e:n5zj-r44u t:meta.view.tableauthor v:id=3qqc-w7ag v:profileImageUrlMedium=/api/users/3qqc-w7ag/profile_images/THUMB v:profileImageUrlLarge=/api/users/3qqc-w7ag/profile_images/LARGE v:screenName="Tom Schenk Jr" v:profileImageUrlSmall=/api/users/3qqc-w7ag/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1491330280 v:displayName="Tom Schenk Jr"
```

## Top Records

```ls
| :updated_at | address                | secondary_address | zip_code   | respondent                           | community_area | community_area_number | ward | census_tracts | census_blocks   | street_block_id | x_coordinate       | y_coordinate       | longitude      | latitude      | 
| =========== | ====================== | ================= | ========== | ==================================== | ============== | ===================== | ==== | ============= | =============== | =============== | ================== | ================== | ============== | ============= | 
| 1468179354  | 108 W 113TH PL         |                   | 60628-4813 | Woo S Chung; Eun Y Sakanashi         | ROSELAND       | 49                    | 34   | 17031491300   | 170314913002003 | 52291           | 1177434.4167194641 | 1829735.0594765951 | -87.626052479  | 41.6881178348 | 
| 1468179354  | 1353-55 W 110TH PL     |                   | 60643      | Felice's Investments, Inc            | MORGAN PARK    | 75                    | 34   | 17031750100   | 170317501004031 | 40920           | 1169062.4848081134 | 1831441.8934397784 | -87.6566523483 | 41.6929862058 | 
| 1468179354  | 3758 W 56TH PL         |                   | 60629-3825 | Hameed O Andu                        | WEST ELSDON    | 62                    | 23   | 17031620400   | 170316204001011 | 36994           | 1152036.0221705413 | 1866911.3023172112 | -87.7180617148 | 41.7906705731 | 
| 1468179354  | 4725 W JACKSON BLVD    |                   | 60644-4653 | Danny Wilmington                     | AUSTIN         | 25                    | 28   | 17031252202   | 170312522023002 | 34972           | 1144820.765354329  | 1898230.4865562152 | -87.7437304528 | 41.8767535335 | 
| 1468179354  | 5120 S HERMITAGE AVE   |                   | 60609-5700 | Enos L Vassail; Orni M Vassail       | NEW CITY       | 61                    | 16   | 17031611800   | 170316118001020 | 25209           | 1165507.8009495442 | 1870639.9529089325 | -87.6685580382 | 41.8006272561 | 
| 1468179354  | 5249 W GLADYS AVE      |                   | 60644-4802 | Michael Fort                         | AUSTIN         | 25                    | 29   | 17031252102   | 170312521022007 | 6063            | 1141249.833153729  | 1897793.3002597953 | -87.7568527612 | 41.8756204042 | 
| 1468179354  | 6116 S ST LAWRENCE AVE |                   | 60637-2475 | Greenwood Investment Properties, LLC | WOODLAWN       | 42                    | 20   | 17031420600   | 170314206002000 | 34              | 1181249.4725410563 | 1864497.4496505416 | -87.6110179015 | 41.7834230916 | 
| 1468179354  | 6207 S WOOD ST         |                   | 60636-2205 | Harold Rose                          | WEST ENGLEWOOD | 67                    | 15   | 17031670700   | 170316707002007 | 7021            | 1165454.9543184887 | 1863475.0923129702 | -87.6689548992 | 41.7809671136 | 
| 1468179354  | 6218 S VERNON AVE      |                   | 60637-2320 | Inclined Plane Enterprises LLC       | WOODLAWN       | 42                    | 20   | 17031420600   | 170314206002012 | 7243            | 1180281.7460042322 | 1863782.3618331864 | -87.6145877986 | 41.7814830749 | 
| 1468179354  | 6430 S YALE AVE        |                   | 60621-3832 | Hazel Farley; Samuel Farley          | ENGLEWOOD      | 68                    | 20   | 17031680900   | 170316809002017 | 5183            | 1175574.7055732505 | 1862185.2273310516 | -87.6318925469 | 41.7772070354 | 
```