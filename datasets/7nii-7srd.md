# 311 Service Requests - Vacant and Abandoned Buildings Reported

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/311-service-requests-vacant-and-abandoned-buildings-reported-13f8e) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/7nii-7srd) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/7nii-7srd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/7nii-7srd/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | 7nii-7srd |
| Name | 311 Service Requests - Vacant and Abandoned Buildings Reported |
| Attribution | City of Chicago |
| Category | Service Requests |
| Tags | buildings |
| Created | 2011-09-30T09:10:12Z |
| Publication Date | 2017-04-20T09:39:45Z |

## Description

All 311 calls for open and vacant buildings reported to the City of Chicago since January 1, 2010. The information is updated daily with the previous day's calls added to the records. The data set provides the date of the 311 service request and the unique Service Request # attached to each request. For each request, the following information (as reported by the 311 caller) is available: address location of building; whether building is vacant or occupied; whether the building is open or boarded; entry point if building is open; whether non-residents are occupying or using the building, if the building appears dangerous or hazardous and if the building is vacant due to a fire.

## Columns

```ls
| Included | Schema Type    | Field Name                                                         | Name                                                                  | Data Type     | Render Type   |
| ======== | ============== | ================================================================== | ===================================================================== | ============= | ============= |
| Yes      | series tag     | service_request_type                                               | SERVICE REQUEST TYPE                                                  | text          | text          |
| Yes      | series tag     | service_request_number                                             | SERVICE REQUEST NUMBER                                                | text          | text          |
| Yes      | time           | date_service_request_was_received                                  | DATE SERVICE REQUEST WAS RECEIVED                                     | calendar_date | calendar_date |
| Yes      | series tag     | location_of_building_on_the_lot_if_garage_change_type_code_to_bgd_ | LOCATION OF BUILDING ON THE LOT (IF GARAGE, CHANGE TYPE CODE TO BGD). | text          | text          |
| Yes      | series tag     | is_the_building_dangerous_or_hazardous_                            | IS THE BUILDING DANGEROUS OR HAZARDOUS?                               | text          | text          |
| Yes      | series tag     | is_building_open_or_boarded_                                       | IS BUILDING OPEN OR BOARDED?                                          | text          | text          |
| Yes      | series tag     | if_the_building_is_open_where_is_the_entry_point_                  | IF THE BUILDING IS OPEN, WHERE IS THE ENTRY POINT?                    | text          | text          |
| Yes      | series tag     | is_the_building_currently_vacant_or_occupied_                      | IS THE BUILDING CURRENTLY VACANT OR OCCUPIED?                         | text          | text          |
| Yes      | series tag     | is_the_building_vacant_due_to_fire_                                | IS THE BUILDING VACANT DUE TO FIRE?                                   | checkbox      | checkbox      |
| Yes      | series tag     | any_people_using_property_homeless_childen_gangs_                  | ANY PEOPLE USING PROPERTY? (HOMELESS, CHILDEN, GANGS)                 | checkbox      | checkbox      |
| Yes      | series tag     | address_street_number                                              | ADDRESS STREET NUMBER                                                 | text          | text          |
| Yes      | series tag     | address_street_direction                                           | ADDRESS STREET DIRECTION                                              | text          | text          |
| Yes      | series tag     | address_street_name                                                | ADDRESS STREET NAME                                                   | text          | text          |
| Yes      | series tag     | address_street_suffix                                              | ADDRESS STREET SUFFIX                                                 | text          | text          |
| Yes      | series tag     | zip_code                                                           | ZIP CODE                                                              | text          | number        |
| No       |                | x_coordinate                                                       | X COORDINATE                                                          | number        | number        |
| No       |                | y_coordinate                                                       | Y COORDINATE                                                          | number        | number        |
| Yes      | series tag     | ward                                                               | Ward                                                                  | text          | number        |
| Yes      | series tag     | police_district                                                    | Police District                                                       | text          | number        |
| Yes      | series tag     | community_area                                                     | Community Area                                                        | text          | number        |
| Yes      | numeric metric | latitude                                                           | LATITUDE                                                              | number        | number        |
| Yes      | numeric metric | longitude                                                          | LONGITUDE                                                             | number        | number        |
```

## Time Field

```ls
Value = date_service_request_was_received
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = x_coordinate,y_coordinate
```

## Data Commands

```ls
series e:7nii-7srd d:2008-04-03T00:00:00.000Z t:service_request_type="Vacant/Abandoned Building" t:is_building_open_or_boarded_="Building is Open / Unsecure" t:ward=17 t:police_district=7 t:zip_code=60621 t:address_street_name=ABERDEEN t:service_request_number=08-00577896 t:community_area=68 t:address_street_suffix=ST t:address_street_direction=S t:address_street_number=6929 t:is_the_building_currently_vacant_or_occupied_=Vacant m:longitude=-87.65177097869127 m:latitude=41.76819814695611

series e:7nii-7srd d:2008-04-05T00:00:00.000Z t:any_people_using_property_homeless_childen_gangs_=true t:is_building_open_or_boarded_="Building is Open / Unsecure" t:zip_code=60619 t:police_district=6 t:service_request_number=08-00588295 t:if_the_building_is_open_where_is_the_entry_point_="GARAGE, VAGRANTS BROKE INTO GARAGE AND USE IT TO GAIN ENTRY INTO BLDG." t:address_street_direction=S t:is_the_building_currently_vacant_or_occupied_=Vacant t:service_request_type="Vacant/Abandoned Building" t:ward=6 t:address_street_name=EVANS t:community_area=44 t:address_street_suffix=AVE t:address_street_number=8216 m:longitude=-87.60628681474407 m:latitude=41.745482414802325

series e:7nii-7srd d:2008-07-30T00:00:00.000Z t:is_building_open_or_boarded_="Building is Open / Unsecure" t:zip_code=60621 t:police_district=7 t:service_request_number=08-01476976 t:if_the_building_is_open_where_is_the_entry_point_=REAR t:address_street_direction=S t:is_the_building_currently_vacant_or_occupied_=Vacant t:service_request_type="Vacant/Abandoned Building" t:ward=6 t:address_street_name=EGGLESTON t:community_area=68 t:address_street_suffix=AVE t:address_street_number=7136 m:longitude=-87.63588403606937 m:latitude=41.764673747551555
```

## Meta Commands

```ls
metric m:latitude p:long l:LATITUDE t:dataTypeName=number

metric m:longitude p:long l:LONGITUDE t:dataTypeName=number

entity e:7nii-7srd l:"311 Service Requests - Vacant and Abandoned Buildings Reported" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/7nii-7srd

property e:7nii-7srd t:meta.view v:id=7nii-7srd v:category="Service Requests" v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="311 Service Requests - Vacant and Abandoned Buildings Reported" v:attribution="City of Chicago"

property e:7nii-7srd t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:7nii-7srd t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| service_request_type      | service_request_number | date_service_request_was_received | location_of_building_on_the_lot_if_garage_change_type_code_to_bgd_    | is_the_building_dangerous_or_hazardous_ | is_building_open_or_boarded_ | if_the_building_is_open_where_is_the_entry_point_                      | is_the_building_currently_vacant_or_occupied_ | is_the_building_vacant_due_to_fire_ | any_people_using_property_homeless_childen_gangs_ | address_street_number | address_street_direction | address_street_name | address_street_suffix | zip_code | x_coordinate     | y_coordinate     | ward | police_district | community_area | latitude           | longitude          | 
| ========================= | ====================== | ================================= | ===================================================================== | ======================================= | ============================ | ====================================================================== | ============================================= | =================================== | ================================================= | ===================== | ======================== | =================== | ===================== | ======== | ================ | ================ | ==== | =============== | ============== | ================== | ================== | 
| SERVICE REQUEST TYPE      | SERVICE REQUEST #      |                                   | LOCATION OF BUILDING ON THE LOT (IF GARAGE, CHANGE TYPE CODE TO BGD). | IS THE BUILDING DANGEROUS OR HAZARDOUS? | IS BUILDING OPEN OR BOARDED? | IF THE BUILDING IS OPEN, WHERE IS THE ENTRY POINT?                     | IS THE BUILDING CURRENTLY VACANT OR OCCUPIED? |                                     |                                                   | ADDRESS STREET NUMBER | ADDRESS STREET DIRECTION | ADDRESS STREET NAME | ADDRESS STREET SUFFIX |          |                  |                  |      |                 |                |                    |                    | 
| Vacant/Abandoned Building | 08-00109075            | 2008-01-18T00:00:00               |                                                                       |                                         |                              |                                                                        |                                               |                                     |                                                   | 7905                  | W                        | ADDISON             | ST                    | 60613    |                  |                  |      |                 |                |                    |                    | 
| Vacant/Abandoned Building | 08-00577896            | 2008-04-03T00:00:00               |                                                                       |                                         | Building is Open / Unsecure  |                                                                        | Vacant                                        |                                     |                                                   | 6929                  | S                        | ABERDEEN            | ST                    | 60621    | 1170178.65847317 | 1858858.85797821 | 17   | 7               | 68             | 41.76819814695611  | -87.65177097869127 | 
| Vacant/Abandoned Building | 08-00588295            | 2008-04-05T00:00:00               |                                                                       |                                         | Building is Open / Unsecure  | GARAGE, VAGRANTS BROKE INTO GARAGE AND USE IT TO GAIN ENTRY INTO BLDG. | Vacant                                        |                                     | true                                              | 8216                  | S                        | EVANS               | AVE                   | 60619    | 1182656.66291261 | 1850683.0384131  | 6    | 6               | 44             | 41.745482414802325 | -87.60628681474407 | 
| Vacant/Abandoned Building | 08-01476976            | 2008-07-30T00:00:00               |                                                                       |                                         | Building is Open / Unsecure  | REAR                                                                   | Vacant                                        |                                     |                                                   | 7136                  | S                        | EGGLESTON           | AVE                   | 60621    | 1174523.01813413 | 1857609.33820458 | 6    | 7               | 68             | 41.764673747551555 | -87.63588403606937 | 
| Vacant/Abandoned Building | 08-01559367            | 2008-08-07T00:00:00               |                                                                       |                                         | Building is Open / Unsecure  | FRONT AND REAR                                                         | Vacant                                        |                                     |                                                   | 1265                  | W                        | 74TH                | ST                    | 60636    | 1169023.46491226 | 1855703.41030725 | 17   | 7               | 67             | 41.75956423181548  | -87.65609637199394 | 
| Vacant/Abandoned Building | 08-01602664            | 2008-08-12T00:00:00               |                                                                       |                                         | Building is Boarded Up       |                                                                        | Vacant                                        |                                     | false                                             | 845                   | N                        | HAMLIN              | AVE                   | 60651    | 1150900.68262268 | 1905374.96469974 | 27   | 11              | 23             | 41.8962419581672   | -87.72121957507471 | 
| Vacant/Abandoned Building | 08-01712460            | 2008-08-25T00:00:00               |                                                                       |                                         | Building is Open / Unsecure  | FRONT DOOR                                                             | Vacant                                        |                                     | true                                              | 6821                  | S                        | WASHTENAW           | AVE                   | 60629    | 1159551.45631016 | 1859307.62057577 | 15   | 8               | 66             | 41.769654102393    | -87.69071260005126 | 
| Vacant/Abandoned Building | 08-01774383            | 2008-09-03T00:00:00               |                                                                       |                                         | Building is Open / Unsecure  | FRONT AND REAR                                                         | Vacant                                        |                                     | true                                              | 12230                 | S                        | PRINCETON           | AVE                   | 60628    | 1176489.28228167 | 1823827.41251075 | 34   | 5               | 53             | 41.67192758220667  | -87.62968915134154 | 
| Vacant/Abandoned Building | 08-01777549            | 2008-09-03T00:00:00               |                                                                       |                                         | Building is Open / Unsecure  |                                                                        | Vacant                                        |                                     |                                                   | 6349                  | S                        | MARSHFIELD          | AVE                   | 60636    | 1166418.29747992 | 1862599.71002324 | 16   | 7               | 67             | 41.77854447420601  | -87.66544800947872 | 
```