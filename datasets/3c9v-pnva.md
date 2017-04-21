# 311 Service Requests - Abandoned Vehicles

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/311-service-requests-abandoned-vehicles-beefc) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/3c9v-pnva) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/3c9v-pnva/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/3c9v-pnva/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | 3c9v-pnva |
| Name | 311 Service Requests - Abandoned Vehicles |
| Attribution | City of Chicago |
| Category | Service Requests |
| Tags | streets, vehicles |
| Created | 2011-09-30T09:09:40Z |
| Publication Date | 2017-04-20T09:36:03Z |

## Description

All open abandoned vehicle complaints made to 311 and all requests completed since January 1, 2011. A vehicle can be classified as abandoned if it meets one or more of the following criteria:All open abandoned vehicle complaints made to 311 and all requests completed since January 1, 2011.

A vehicle can be classified as abandoned if it meets one or more of the following criteria: 1) On a public way in a state of disrepair as to be incapable of being driven in its present condition. 2) Has not been moved or used for more than seven consecutive days and is apparently deserted. 3) Has been left on the public way without state registration or a temporary state registration placard for two or more days. 4) Is a hazardous dilapidated vehicle left in full view of the general public, whether on public or private property.

For some Open service requests, the vehicle has been towed but further action is required before the request may be closed. 311 sometimes receives duplicate abandoned vehicle complaints. 

If a vehicle is towed it remains as open, work in progress until it is redeemed, transferred or disposed of. The service request is not closed until there is a final disposition for the vehicle.

Requests that have been labeled as Duplicates are in the same geographic area and have been entered into 311 Customer Service Requests (CSR) system at around the same time as a previous request. Duplicate reports/requests are labeled as such in the Status field, as either "Open - Dup" or "Completed - Dup." Data is updated daily.

## Columns

```ls
| Included | Schema Type    | Field Name                                             | Name                                                   | Data Type     | Render Type   |
| ======== | ============== | ====================================================== | ====================================================== | ============= | ============= |
| Yes      | time           | creation_date                                          | Creation Date                                          | calendar_date | calendar_date |
| Yes      | series tag     | status                                                 | Status                                                 | text          | text          |
| No       |                | completion_date                                        | Completion Date                                        | calendar_date | calendar_date |
| Yes      | series tag     | service_request_number                                 | Service Request Number                                 | text          | text          |
| Yes      | series tag     | type_of_service_request                                | Type of Service Request                                | text          | text          |
| Yes      | series tag     | license_plate                                          | License Plate                                          | text          | text          |
| Yes      | series tag     | vehicle_make_model                                     | Vehicle Make/Model                                     | text          | text          |
| Yes      | series tag     | vehicle_color                                          | Vehicle Color                                          | text          | text          |
| Yes      | series tag     | current_activity                                       | Current Activity                                       | text          | text          |
| Yes      | series tag     | most_recent_action                                     | Most Recent Action                                     | text          | text          |
| Yes      | numeric metric | how_many_days_has_the_vehicle_been_reported_as_parked_ | How Many Days Has the Vehicle Been Reported as Parked? | number        | number        |
| Yes      | series tag     | street_address                                         | Street Address                                         | text          | text          |
| Yes      | series tag     | zip_code                                               | ZIP Code                                               | text          | number        |
| No       |                | x_coordinate                                           | X Coordinate                                           | number        | number        |
| No       |                | y_coordinate                                           | Y Coordinate                                           | number        | number        |
| Yes      | series tag     | ward                                                   | Ward                                                   | text          | number        |
| Yes      | series tag     | police_district                                        | Police District                                        | text          | number        |
| Yes      | series tag     | community_area                                         | Community Area                                         | text          | number        |
| Yes      | series tag     | ssa                                                    | SSA                                                    | text          | text          |
| Yes      | numeric metric | latitude                                               | Latitude                                               | number        | number        |
| Yes      | numeric metric | longitude                                              | Longitude                                              | number        | number        |
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
series e:3c9v-pnva d:2011-01-01T00:00:00.000Z t:license_plate=0000000000 t:vehicle_make_model=Jeep/Cherokee t:vehicle_color=Red t:ward=39 t:police_district=17 t:zip_code=60646 t:status="Completed - Dup" t:service_request_number=11-00002767 t:community_area=13 t:type_of_service_request="Abandoned Vehicle Complaint" t:street_address="5629 N KEDVALE AVE" m:how_many_days_has_the_vehicle_been_reported_as_parked_=20 m:longitude=-87.7319663736746 m:latitude=41.983680361597564

series e:3c9v-pnva d:2011-01-01T00:00:00.000Z t:license_plate="REAR PLATE STARTS W/848 AND FRONT PLATE STARTS W/ K" t:vehicle_make_model=Isuzu t:vehicle_color=Red t:ward=39 t:police_district=17 t:zip_code=60646 t:status="Completed - Dup" t:service_request_number=11-00002779 t:community_area=13 t:type_of_service_request="Abandoned Vehicle Complaint" t:street_address="5629 N KEDVALE AVE" m:how_many_days_has_the_vehicle_been_reported_as_parked_=24 m:longitude=-87.7319663736746 m:latitude=41.983680361597564

series e:3c9v-pnva d:2011-01-01T00:00:00.000Z t:license_plate=9381880 t:vehicle_make_model=Toyota t:vehicle_color=Silver t:ward=31 t:police_district=25 t:zip_code=60639 t:status="Completed - Dup" t:service_request_number=11-00003001 t:community_area=20 t:type_of_service_request="Abandoned Vehicle Complaint" t:street_address="2053 N KILBOURN AVE" m:longitude=-87.73868431751842 m:latitude=41.91858774162382
```

## Meta Commands

```ls
metric m:how_many_days_has_the_vehicle_been_reported_as_parked_ p:long l:"How Many Days Has the Vehicle Been Reported as Parked?" t:dataTypeName=number

metric m:latitude p:long l:Latitude t:dataTypeName=number

metric m:longitude p:long l:Longitude t:dataTypeName=number

entity e:3c9v-pnva l:"311 Service Requests - Abandoned Vehicles" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/3c9v-pnva

property e:3c9v-pnva t:meta.view v:id=3c9v-pnva v:category="Service Requests" v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="311 Service Requests - Abandoned Vehicles" v:attribution="City of Chicago"

property e:3c9v-pnva t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:3c9v-pnva t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| creation_date       | status          | completion_date     | service_request_number | type_of_service_request     | license_plate                                             | vehicle_make_model | vehicle_color | current_activity | most_recent_action | how_many_days_has_the_vehicle_been_reported_as_parked_ | street_address       | zip_code | x_coordinate     | y_coordinate     | ward | police_district | community_area | ssa | latitude           | longitude          | 
| =================== | =============== | =================== | ====================== | =========================== | ========================================================= | ================== | ============= | ================ | ================== | ====================================================== | ==================== | ======== | ================ | ================ | ==== | =============== | ============== | === | ================== | ================== | 
| 2011-01-01T00:00:00 | Completed - Dup | 2011-01-07T00:00:00 | 11-00002767            | Abandoned Vehicle Complaint | 0000000000                                                | Jeep/Cherokee      | Red           |                  |                    | 20                                                     | 5629 N KEDVALE AVE   | 60646    | 1147716.70081754 | 1937054.16743335 | 39   | 17              | 13             |     | 41.983680361597564 | -87.7319663736746  | 
| 2011-01-01T00:00:00 | Completed - Dup | 2011-01-07T00:00:00 | 11-00002779            | Abandoned Vehicle Complaint | REAR PLATE STARTS W/848 AND FRONT PLATE STARTS W/ K       | Isuzu              | Red           |                  |                    | 24                                                     | 5629 N KEDVALE AVE   | 60646    | 1147716.70081754 | 1937054.16743335 | 39   | 17              | 13             |     | 41.983680361597564 | -87.7319663736746  | 
| 2011-01-01T00:00:00 | Completed - Dup | 2011-01-20T00:00:00 | 11-00003001            | Abandoned Vehicle Complaint | 9381880                                                   | Toyota             | Silver        |                  |                    |                                                        | 2053 N KILBOURN AVE  | 60639    | 1146056.03097988 | 1913268.75790263 | 31   | 25              | 20             |     | 41.91858774162382  | -87.73868431751842 | 
| 2011-01-01T00:00:00 | Completed - Dup | 2011-01-21T00:00:00 | 11-00003309            | Abandoned Vehicle Complaint | MI S CS860                                                | Jeep/Cherokee      | Gold          |                  |                    |                                                        | 736 W BUENA AVE      | 60613    | 1170576.48887782 | 1928213.79082563 | 46   | 23              | 3              |     | 41.95860696269331  | -87.64887590959788 | 
| 2011-01-01T00:00:00 | Completed - Dup | 2011-01-21T00:00:00 | 11-00003316            | Abandoned Vehicle Complaint | MI SCS860                                                 |                    | Gold          |                  |                    |                                                        | 736 W BUENA AVE      | 60613    | 1170576.48887782 | 1928213.79082563 | 46   | 23              | 3              |     | 41.95860696269331  | -87.64887590959788 | 
| 2011-01-01T00:00:00 | Completed       | 2011-01-05T00:00:00 | 11-00001976            | Abandoned Vehicle Complaint | H924236                                                   | Ford               | White         |                  |                    | 60                                                     | 6059 S KOMENSKY AVE  | 60629    | 1150407.76690181 | 1864110.04242601 | 13   | 8               | 65             | 3   | 41.78237428405976  | -87.72394038021173 | 
| 2011-01-01T00:00:00 | Completed       | 2011-01-05T00:00:00 | 11-00002291            | Abandoned Vehicle Complaint | 810 LYB WISCONSIN PLATES                                  | Mercury            | Green         |                  |                    |                                                        | 4651 S WASHTENAW AVE | 60632    | 1159150.32010211 | 1873712.02067414 | 12   | 9               | 58             |     | 41.80863500843091  | -87.69162625248853 | 
| 2011-01-01T00:00:00 | Completed       | 2011-01-05T00:00:00 | 11-00002696            | Abandoned Vehicle Complaint | 368M783                                                   | Buick              | Gold          |                  |                    | 10                                                     | 6200 S MASSASOIT AVE | 60638    | 1139136.61010288 | 1862867.57328148 | 13   | 8               | 64             |     | 41.77972261151146  | -87.76560265994306 | 
| 2011-01-01T00:00:00 | Completed       | 2011-01-05T00:00:00 | 11-00003094            | Abandoned Vehicle Complaint | 000000000                                                 | Dodge              | White         |                  |                    | 30                                                     | 5816 S ALBANY AVE    | 60629    | 1156709.11881086 | 1865903.47437797 | 14   | 8               | 63             | 59  | 41.78756085777093  | -87.70109289200148 | 
| 2011-01-01T00:00:00 | Completed       | 2011-01-05T00:00:00 | 11-00003456            | Abandoned Vehicle Complaint | TEXAS PLATE - SMALL FLATBED HITCH TRAILER - MISSING TIRES |                    | Black         |                  |                    |                                                        | 4559 S KEELER AVE    | 60632    | 1149119.58230237 | 1874073.4099702  | 14   | 8               | 57             |     | 41.809735337429046 | -87.72839982934718 | 
```