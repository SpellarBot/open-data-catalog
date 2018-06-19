# 311 Service Requests - Garbage Carts

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/311-service-requests-garbage-carts-7e8e7) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/9ksk-na4q) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/9ksk-na4q/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/9ksk-na4q/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | 9ksk-na4q |
| Name | 311 Service Requests - Garbage Carts |
| Attribution | City of Chicago |
| Category | Service Requests |
| Tags | garbage |
| Created | 2011-09-30T09:08:45Z |
| Publication Date | 2017-04-20T09:19:51Z |

## Description

All open garbage cart requests made to 311 and all requests completed since January 1, 2011. The City of Chicago provides heavy-duty plastic 96-gallon garbage carts to single-family residences and apartment buildings of four units or less. Residents may request new carts when none are present, or replacement carts for ones which have gone missing or been damaged.     
311 sometimes receives duplicate requests for garbage carts. Requests that have been labeled as Duplicates are in the same geographic area and have been entered into 311?s Customer Service Requests (CSR) system at around the same time as a previous request. Duplicate reports/requests are labeled as such in the Status field, as either "Open - Dup" or "Completed - Dup." Data is updated daily.

## Columns

```ls
| Included | Schema Type    | Field Name                      | Name                            | Data Type     | Render Type   |
| ======== | ============== | =============================== | =============================== | ============= | ============= |
| Yes      | time           | creation_date                   | Creation Date                   | calendar_date | calendar_date |
| Yes      | series tag     | status                          | Status                          | text          | text          |
| No       |                | completion_date                 | Completion Date                 | calendar_date | calendar_date |
| Yes      | series tag     | service_request_number          | Service Request Number          | text          | text          |
| Yes      | series tag     | type_of_service_request         | Type of Service Request         | text          | text          |
| Yes      | numeric metric | number_of_black_carts_delivered | Number of Black Carts Delivered | number        | number        |
| Yes      | series tag     | current_activity                | Current Activity                | text          | text          |
| Yes      | series tag     | most_recent_action              | Most Recent Action              | text          | text          |
| Yes      | series tag     | street_address                  | Street Address                  | text          | text          |
| Yes      | series tag     | zip_code                        | ZIP Code                        | text          | number        |
| No       |                | x_coordinate                    | X Coordinate                    | number        | number        |
| No       |                | y_coordinate                    | Y Coordinate                    | number        | number        |
| Yes      | series tag     | ward                            | Ward                            | text          | number        |
| Yes      | series tag     | police_district                 | Police District                 | text          | number        |
| Yes      | series tag     | community_area                  | Community Area                  | text          | number        |
| Yes      | series tag     | ssa                             | SSA                             | text          | text          |
| Yes      | numeric metric | latitude                        | Latitude                        | number        | number        |
| Yes      | numeric metric | longitude                       | Longitude                       | number        | number        |
```

## Time Field

```ls
Value = creation_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = completion_date,x_coordinate,y_coordinate
```

## Data Commands

```ls
series e:9ksk-na4q d:2012-06-15T00:00:00.000Z t:ward=28 t:police_district=15 t:zip_code=60644 t:status="Completed - Dup" t:service_request_number=12-01089270 t:community_area=25 t:type_of_service_request="Garbage Cart Black Maintenance/Replacement" t:street_address="4942 W KINZIE ST" m:longitude=-87.74961410499051 m:latitude=41.88797829529805

series e:9ksk-na4q d:2012-06-15T00:00:00.000Z t:ward=28 t:police_district=15 t:zip_code=60644 t:status="Completed - Dup" t:service_request_number=12-01089274 t:community_area=25 t:type_of_service_request="Garbage Cart Black Maintenance/Replacement" t:street_address="4944 W KINZIE ST" m:longitude=-87.74968498253848 m:latitude=41.887977628170304

series e:9ksk-na4q d:2012-06-15T00:00:00.000Z t:ward=50 t:police_district=24 t:zip_code=60645 t:status="Completed - Dup" t:service_request_number=12-01089806 t:community_area=2 t:type_of_service_request="Garbage Cart Black Maintenance/Replacement" t:street_address="6605 N RICHMOND ST" m:longitude=-87.7032598225917 m:latitude=42.00134585527876
```

## Meta Commands

```ls
metric m:number_of_black_carts_delivered p:long l:"Number of Black Carts Delivered" t:dataTypeName=number

metric m:latitude p:long l:Latitude t:dataTypeName=number

metric m:longitude p:long l:Longitude t:dataTypeName=number

entity e:9ksk-na4q l:"311 Service Requests - Garbage Carts" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/9ksk-na4q

property e:9ksk-na4q t:meta.view v:id=9ksk-na4q v:category="Service Requests" v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="311 Service Requests - Garbage Carts" v:attribution="City of Chicago"

property e:9ksk-na4q t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:9ksk-na4q t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| creation_date       | status          | completion_date     | service_request_number | type_of_service_request                    | number_of_black_carts_delivered | current_activity | most_recent_action | street_address     | zip_code | x_coordinate     | y_coordinate     | ward | police_district | community_area | ssa | latitude           | longitude          | 
| =================== | =============== | =================== | ====================== | ========================================== | =============================== | ================ | ================== | ================== | ======== | ================ | ================ | ==== | =============== | ============== | === | ================== | ================== | 
| 2012-06-15T00:00:00 | Completed - Dup | 2012-08-27T00:00:00 | 12-01089270            | Garbage Cart Black Maintenance/Replacement |                                 |                  |                    | 4942 W KINZIE ST   | 60644    | 1143347.84997003 | 1902273.92031755 | 28   | 15              | 25             |     | 41.88797829529805  | -87.74961410499051 | 
| 2012-06-15T00:00:00 | Completed - Dup | 2012-08-27T00:00:00 | 12-01089274            | Garbage Cart Black Maintenance/Replacement |                                 |                  |                    | 4944 W KINZIE ST   | 60644    | 1143334.44997003 | 1902273.72031755 | 28   | 15              | 25             |     | 41.887977628170304 | -87.74968498253848 | 
| 2012-06-15T00:00:00 | Completed - Dup | 2012-09-04T00:00:00 | 12-01089806            | Garbage Cart Black Maintenance/Replacement |                                 |                  |                    | 6605 N RICHMOND ST | 60645    | 1155469.78750935 | 1943669.1146214  | 50   | 24              | 2              |     | 42.00134585527876  | -87.7032598225917  | 
| 2012-06-15T00:00:00 | Completed - Dup | 2012-09-10T00:00:00 | 12-01087592            | Garbage Cart Black Maintenance/Replacement |                                 |                  |                    | 9011 S UNION AVE   | 60620    | 1173219.5733661  | 1845129.71457723 | 21   | 22              | 71             |     | 41.73046647733934  | -87.6408812697374  | 
| 2012-06-15T00:00:00 | Completed - Dup | 2012-09-14T00:00:00 | 12-01085648            | Garbage Cart Black Maintenance/Replacement | 0                               |                  |                    | 4739 W HARRISON ST | 60644    | 1144886.09970577 | 1896927.87388335 | 24   | 11              | 25             |     | 41.87306660013028  | -87.74411488435801 | 
| 2012-06-15T00:00:00 | Completed - Dup | 2012-09-14T00:00:00 | 12-01089188            | Garbage Cart Black Maintenance/Replacement | 0                               |                  |                    | 6435 S HONORE ST   | 60636    | 1165118.28670437 | 1862001.16381228 | 15   | 7               | 67             |     | 41.77652411740357  | -87.67007180208135 | 
| 2012-06-15T00:00:00 | Completed - Dup | 2012-09-20T00:00:00 | 12-01090134            | Garbage Cart Black Maintenance/Replacement |                                 |                  |                    | 6904 N RIDGE BLVD  | 60645    | 1161601.55777207 | 1945652.66171025 | 50   | 24              | 2              |     | 42.00657188481648  | -87.68095726888417 | 
| 2012-06-15T00:00:00 | Completed - Dup | 2012-09-25T00:00:00 | 12-01088582            | Garbage Cart Black Maintenance/Replacement |                                 |                  |                    | 1031 S MONITOR AVE | 60644    | 1137534.62917371 | 1895209.02489295 | 29   | 15              | 25             |     | 41.86822961263133  | -87.77039720701389 | 
| 2012-06-15T00:00:00 | Completed - Dup | 2012-10-05T00:00:00 | 12-01086537            | Garbage Cart Black Maintenance/Replacement |                                 |                  |                    | 6508 S OAKLEY AVE  | 60636    | 1162192.12190332 | 1861445.47131512 | 15   | 8               | 66             |     | 41.77529475216878  | -87.68111536374053 | 
| 2012-06-15T00:00:00 | Completed - Dup | 2012-10-10T00:00:00 | 12-01085496            | Garbage Cart Black Maintenance/Replacement |                                 |                  |                    | 6140 S DAMEN AVE   | 60636    | 1164080.64247093 | 1863931.0001263  | 15   | 7               | 67             |     | 41.78175959765556  | -87.6741134782751  | 
```