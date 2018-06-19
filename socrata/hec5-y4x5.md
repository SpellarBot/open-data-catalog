# 311 Service Requests - Graffiti Removal

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/311-service-requests-graffiti-removal-5072e) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/hec5-y4x5) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/hec5-y4x5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/hec5-y4x5/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | hec5-y4x5 |
| Name | 311 Service Requests - Graffiti Removal |
| Attribution | City of Chicago |
| Category | Service Requests |
| Tags | graffiti |
| Created | 2011-09-30T09:01:32Z |
| Publication Date | 2017-04-21T08:49:59Z |

## Description

All open graffiti removal requests made to 311 and all requests completed since January 1, 2011. The Department of Streets & Sanitation's Graffiti Blasters crews offer a vandalism removal service to private property owners. Graffiti Blasters employ "blast" trucks that use baking soda under high water pressure to erase painted graffiti from brick, stone and other mineral surfaces. They also use paint trucks to cover graffiti on the remaining surfaces. Organizations and residents may report graffiti and request its removal.
311 sometimes receives duplicate requests for graffiti removal. Requests that have been labeled as Duplicates are in the same geographic area and have been entered into 311?s Customer Service Requests (CSR) system at around the same time as a previous request. Duplicate reports/requests are labeled as such in the Status field, as either "Open - Dup" or "Completed - Dup." Data is updated daily.

## Columns

```ls
| Included | Schema Type    | Field Name                               | Name                                     | Data Type     | Render Type   |
| ======== | ============== | ======================================== | ======================================== | ============= | ============= |
| Yes      | time           | creation_date                            | Creation Date                            | calendar_date | calendar_date |
| Yes      | series tag     | status                                   | Status                                   | text          | text          |
| No       |                | completion_date                          | Completion Date                          | calendar_date | calendar_date |
| Yes      | series tag     | service_request_number                   | Service Request Number                   | text          | text          |
| Yes      | series tag     | type_of_service_request                  | Type of Service Request                  | text          | text          |
| Yes      | series tag     | what_type_of_surface_is_the_graffiti_on_ | What Type of Surface is the Graffiti on? | text          | text          |
| Yes      | series tag     | where_is_the_graffiti_located_           | Where is the Graffiti located?           | text          | text          |
| Yes      | series tag     | street_address                           | Street Address                           | text          | text          |
| Yes      | series tag     | zip_code                                 | ZIP Code                                 | text          | number        |
| No       |                | x_coordinate                             | X Coordinate                             | number        | number        |
| No       |                | y_coordinate                             | Y Coordinate                             | number        | number        |
| Yes      | series tag     | ward                                     | Ward                                     | text          | number        |
| Yes      | series tag     | police_district                          | Police District                          | text          | number        |
| Yes      | series tag     | community_area                           | Community Area                           | text          | number        |
| Yes      | series tag     | ssa                                      | SSA                                      | text          | text          |
| Yes      | numeric metric | latitude                                 | Latitude                                 | number        | number        |
| Yes      | numeric metric | longitude                                | Longitude                                | number        | number        |
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
series e:hec5-y4x5 d:2011-01-01T00:00:00.000Z t:what_type_of_surface_is_the_graffiti_on_="Brick - Unpainted" t:ward=11 t:police_district=9 t:zip_code=60609 t:status="Completed - Dup" t:where_is_the_graffiti_located_=Front t:service_request_number=11-00002268 t:community_area=59 t:type_of_service_request="Graffiti Removal" t:street_address="3701 S WOLCOTT AVE" m:longitude=-87.67258908007462 m:latitude=41.82667996575031

series e:hec5-y4x5 d:2011-01-01T00:00:00.000Z t:what_type_of_surface_is_the_graffiti_on_="Aluminum Siding" t:ward=30 t:police_district=25 t:zip_code=60639 t:status="Completed - Dup" t:where_is_the_graffiti_located_=Garage t:service_request_number=11-00002378 t:community_area=20 t:type_of_service_request="Graffiti Removal" t:street_address="1802 N TRIPP AVE" m:longitude=-87.73269978462665 m:latitude=41.913654239126494

series e:hec5-y4x5 d:2011-01-01T00:00:00.000Z t:what_type_of_surface_is_the_graffiti_on_="Other / Unknown Surface" t:ward=46 t:police_district=23 t:zip_code=60613 t:status="Completed - Dup" t:where_is_the_graffiti_located_=Front t:ssa=34 t:service_request_number=11-00002391 t:community_area=3 t:type_of_service_request="Graffiti Removal" t:street_address="4150 N KENMORE AVE" m:longitude=-87.65637593433681 m:latitude=41.95817637208573
```

## Meta Commands

```ls
metric m:latitude p:long l:Latitude t:dataTypeName=number

metric m:longitude p:long l:Longitude t:dataTypeName=number

entity e:hec5-y4x5 l:"311 Service Requests - Graffiti Removal" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/hec5-y4x5

property e:hec5-y4x5 t:meta.view v:id=hec5-y4x5 v:category="Service Requests" v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="311 Service Requests - Graffiti Removal" v:attribution="City of Chicago"

property e:hec5-y4x5 t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:hec5-y4x5 t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| creation_date       | status          | completion_date     | service_request_number | type_of_service_request | what_type_of_surface_is_the_graffiti_on_ | where_is_the_graffiti_located_ | street_address      | zip_code | x_coordinate     | y_coordinate     | ward | police_district | community_area | ssa | latitude           | longitude          | 
| =================== | =============== | =================== | ====================== | ======================= | ======================================== | ============================== | =================== | ======== | ================ | ================ | ==== | =============== | ============== | === | ================== | ================== | 
| 2011-01-01T00:00:00 | Completed - Dup | 2011-01-03T00:00:00 | 11-00002268            | Graffiti Removal        | Brick - Unpainted                        | Front                          | 3701 S WOLCOTT AVE  | 60609    | 1164294.66131095 | 1880149.94197872 | 11   | 9               | 59             |     | 41.82667996575031  | -87.67258908007462 | 
| 2011-01-01T00:00:00 | Completed - Dup | 2011-01-03T00:00:00 | 11-00002378            | Graffiti Removal        | Aluminum Siding                          | Garage                         | 1802 N TRIPP AVE    | 60639    | 1147771.9745121  | 1911660.5469701  | 30   | 25              | 20             |     | 41.913654239126494 | -87.73269978462665 | 
| 2011-01-01T00:00:00 | Completed - Dup | 2011-01-03T00:00:00 | 11-00002391            | Graffiti Removal        | Other / Unknown Surface                  | Front                          | 4150 N KENMORE AVE  | 60613    | 1168430.50413421 | 1927514.73628624 | 46   | 23              | 3              | 34  | 41.95817637208573  | -87.65637593433681 | 
| 2011-01-01T00:00:00 | Completed - Dup | 2011-01-03T00:00:00 | 11-00002639            | Graffiti Removal        | Cement (Sidewalk, Alley, Wall, Curb)     | Front                          | 3035 N HOYNE AVE    | 60618    | 1161822.25108388 | 1920144.02120117 | 32   | 19              | 5              |     | 41.93695732658053  | -87.68055828418575 | 
| 2011-01-01T00:00:00 | Completed - Dup | 2011-01-04T00:00:00 | 11-00001746            | Graffiti Removal        | Metal                                    | Front                          | 4500 N CENTRAL AVE  | 60630    | 1138195.50189767 | 1929379.95998755 | 38   | 16              | 15             |     | 41.96239659175784  | -87.76745051301677 | 
| 2011-01-01T00:00:00 | Completed - Dup | 2011-01-05T00:00:00 | 11-00003283            | Graffiti Removal        | Brick - Unpainted                        | Front                          | 2221 W BELMONT AVE  | 60618    | 1160992.18419667 | 1921215.9282097  | 32   | 19              | 5              |     | 41.93939324453387  | -87.68407150190562 | 
| 2011-01-01T00:00:00 | Completed - Dup | 2011-01-12T00:00:00 | 11-00002866            | Graffiti Removal        | Brick - Unpainted                        | Front                          | 6969 N WOLCOTT AVE  | 60626    | 1162345.19407229 | 1946287.0295748  | 49   | 24              | 1              |     | 42.008551906656095 | -87.67789885037675 | 
| 2011-01-01T00:00:00 | Completed       | 2011-01-03T00:00:00 | 11-00001286            | Graffiti Removal        | Wood - Painted                           | Garage                         | 1900 W CULLERTON ST | 60608    | 1164016.23422728 | 1890427.82259955 | 25   | 12              | 31             |     | 41.855067394534714 | -87.67359514411345 | 
| 2011-01-01T00:00:00 | Completed       | 2011-01-03T00:00:00 | 11-00001666            | Graffiti Removal        | Vinyl Siding                             | Side                           | 444 W 44TH PL       | 60609    | 1173856.23996796 | 1875425.55008143 | 11   | 9               | 61             |     | 41.813689058704064 | -87.6377357683662  | 
| 2011-01-01T00:00:00 | Completed       | 2011-01-03T00:00:00 | 11-00001751            | Graffiti Removal        | Brick - Unpainted                        | Garage                         | 4759 S KENNETH AVE  | 60632    | 1147494.64999025 | 1872699.54167111 | 23   | 8               | 57             |     | 41.805998271453426 | -87.7344008916481  | 
```