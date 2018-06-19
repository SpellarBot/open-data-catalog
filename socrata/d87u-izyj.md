# Rest Areas - Full Service

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/rest-areas-full-service) |
| Metadata | [Link](https://data.iowa.gov/api/views/d87u-izyj) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/d87u-izyj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/d87u-izyj/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | d87u-izyj |
| Name | Rest Areas - Full Service |
| Attribution | Iowa DOT, HDR Engineering |
| Category | Transportation & Utilities |
| Tags | asset, classification, rest, area, iowa dot, iowa department of transportation |
| Created | 2016-08-19T20:12:40Z |
| Publication Date | 2016-08-19T20:15:22Z |

## Description

Iowa Department of Transportation statewide rest area data. This layer displays full service rest areas in Iowa and outside of Iowa.

## Columns

```ls
| Included | Schema Type    | Field Name                              | Name                                    | Data Type | Render Type |
| ======== | ============== | ======================================= | ======================================= | ========= | =========== |
| Yes      | series tag     | objectid                                | OBJECTID                                | text      | number      |
| Yes      | series tag     | location_1                              | Location_1                              | text      | text        |
| Yes      | series tag     | restareaname                            | RestAreaName                            | text      | text        |
| Yes      | series tag     | rest_area_type                          | Rest_Area_Type                          | text      | text        |
| Yes      | series tag     | rest_area                               | Rest_Area                               | text      | text        |
| Yes      | series tag     | corridor                                | Corridor                                | text      | text        |
| Yes      | numeric metric | mile_post                               | Mile_Post                               | number    | number      |
| Yes      | time           | year_built                              | Year_Built                              | number    | number      |
| Yes      | numeric metric | car_parking_nonhandi                    | Car_Parking_NonHandi                    | number    | text        |
| Yes      | numeric metric | handi_parking                           | Handi_Parking                           | number    | text        |
| Yes      | numeric metric | truck_parking                           | Truck_Parking                           | number    | text        |
| Yes      | series tag     | car_pickup_trailer                      | Car_Pickup_Trailer                      | text      | text        |
| Yes      | series tag     | restroom_facilities                     | Restroom_Facilities                     | text      | text        |
| Yes      | series tag     | family_restroom_facilities              | Family_Restroom_Facilities              | text      | text        |
| Yes      | series tag     | handicap_accessible_facilities          | Handicap_Accessible_Facilities          | text      | text        |
| Yes      | series tag     | picnic_facilities                       | Picnic_Facilities                       | text      | text        |
| Yes      | series tag     | pet_exercise_area                       | Pet_Exercise_Area                       | text      | text        |
| Yes      | series tag     | telephone_services                      | Telephone_Services                      | text      | text        |
| Yes      | series tag     | tdd                                     | TDD                                     | text      | text        |
| Yes      | series tag     | traveler_information                    | Traveler_Information                    | text      | text        |
| Yes      | series tag     | rv_dump_station                         | RV_Dump_Station                         | text      | text        |
| Yes      | series tag     | vending_machines                        | Vending_Machines                        | text      | text        |
| Yes      | series tag     | wi_fi                                   | Wi_Fi                                   | text      | text        |
| Yes      | numeric metric | approx_number_truck_space               | Approx_Number_Truck_Space               | number    | number      |
| Yes      | numeric metric | truck_percent_utili                     | Truck_Percent_Utili                     | number    | number      |
| Yes      | series tag     | truck_perc_group                        | Truck_Perc_Group                        | text      | text        |
| Yes      | series tag     | age_group                               | Age_Group                               | text      | text        |
| Yes      | numeric metric | daily_volume                            | Daily_Volume                            | number    | number      |
| Yes      | series tag     | month_of_data_collection                | Month_of_Data_Collection                | text      | text        |
| No       |                | year_of_data_collection                 | Year_of_Data_Collection                 | number    | number      |
| Yes      | numeric metric | daily_volume_june_equivalent            | Daily_Volume_June_Equivalent            | number    | number      |
| Yes      | numeric metric | visitor_estimate_2010                   | Visitor_Estimate_2010                   | number    | number      |
| Yes      | numeric metric | visitor_estimate_2011                   | Visitor_Estimate_2011                   | number    | number      |
| Yes      | numeric metric | mainline_aadt_directional               | _Mainline_AADT_Directional              | number    | number      |
| Yes      | numeric metric | mainline_truck_aadt_directional         | _Mainline_Truck_AADT_Directional        | number    | number      |
| Yes      | numeric metric | mainline_truck_aadt_directional_1       | _Mainline_Truck_AADT_Directional_1      | number    | number      |
| Yes      | numeric metric | mainline_aadt_directional_1             | _Mainline_AADT_Directional_1            | number    | number      |
| Yes      | numeric metric | mainline_truck_aadt_directional_12      | _Mainline_Truck_AADT_Directional_12     | number    | number      |
| Yes      | numeric metric | mainline_aadt_growth_2010_2035          | Mainline_AADT_Growth_2010_2035          | number    | number      |
| Yes      | numeric metric | mainline_aadt_growth_2012_2035          | Mainline_AADT_Growth_2012_2035          | number    | number      |
| Yes      | numeric metric | ukey                                    | UKEY                                    | number    | number      |
| Yes      | series tag     | inventory_                              | INVENTORY_                              | text      | text        |
| No       |                | address1                                | ADDRESS1                                | text      | text        |
| Yes      | series tag     | near_city                               | NEAR_CITY                               | text      | text        |
| Yes      | series tag     | phone_numb                              | PHONE_NUMB                              | text      | text        |
| Yes      | numeric metric | cost_cente                              | COST_CENTE                              | number    | text        |
| Yes      | numeric metric | square_foo                              | SQUARE_FOO                              | number    | number      |
| Yes      | series tag     | orig_fid                                | ORIG_FID                                | text      | number      |
| Yes      | numeric metric | distance_to_nearest_24h                 | distance_to_nearest_24h                 | number    | number      |
| Yes      | numeric metric | density_of_24h_asl_lessthanequal_5miles | density_of_24h_asl_lessthanequal_5miles | number    | number      |
| Yes      | numeric metric | density_of_24h_asl_5to15_miles          | density_of_24H_asl_5to15_miles          | number    | number      |
| Yes      | numeric metric | density_of_24h_asl_15to30_miles         | density_of_24h_asl_15to30_miles         | number    | number      |
| Yes      | numeric metric | number_of_spaces_lessthanequal_30miles  | number_of_spaces_lessthanequal_30miles  | number    | number      |
| Yes      | series tag     | uniqueness                              | uniqueness                              | text      | text        |
| Yes      | series tag     | active                                  | Active                                  | text      | text        |
| Yes      | series tag     | downstream_rest_area_1                  | Downstream_Rest_Area_1                  | text      | text        |
| Yes      | series tag     | downstream_rest_area_2                  | Downstream_Rest_Area_2                  | text      | text        |
| Yes      | series tag     | upstream_rest_area_1                    | Upstream_Rest_Area_1                    | text      | text        |
| Yes      | series tag     | upstream_rest_area_2                    | Upstream_Rest_Area_2                    | text      | text        |
| Yes      | numeric metric | minimun_distance_downstream_1           | minimun_distance_downstream_1           | number    | number      |
| Yes      | numeric metric | minimun_distance_downstream_2           | minimun_distance_downstream_2           | number    | text        |
| Yes      | numeric metric | minimun_distance_upstream_1             | minimun_distance_upstream_1             | number    | number      |
| Yes      | numeric metric | minimun_distance_upstream_2             | minimun_distance_upstream_2             | number    | text        |
```

## Time Field

```ls
Value = year_built
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = year_of_data_collection,address1
```

## Data Commands

```ls
series e:d87u-izyj d:2017-04-21T07:38:43.106Z t:traveler_information=Yes t:corridor=I-80 t:vending_machines=Yes t:rest_area="Great Sauk Trail, IL - WB" t:tdd=Yes t:telephone_services=Yes t:picnic_facilities=Yes t:rest_area_type="Full Service" t:uniqueness=None t:restroom_facilities=Yes t:restareaname="Great Sauk Trail, IL - WB" t:handicap_accessible_facilities=Yes t:pet_exercise_area=Yes t:active=YES t:location_1=Outside-Iowa t:objectid=1 m:truck_parking=46 m:handi_parking=5 m:mile_post=51 m:car_parking_nonhandi=54

series e:d87u-izyj d:2017-04-21T07:38:43.106Z t:traveler_information=Yes t:corridor=I-74 t:vending_machines=Yes t:rest_area="Krisdala Baka, IL - EB" t:tdd=Yes t:telephone_services=Yes t:picnic_facilities=Yes t:rest_area_type="Full Service" t:uniqueness=None t:restroom_facilities=Yes t:restareaname="Krisdala Baka, IL - EB" t:handicap_accessible_facilities=Yes t:pet_exercise_area=Yes t:active=YES t:location_1=Outside-Iowa t:objectid=2 m:truck_parking=14 m:handi_parking=2 m:mile_post=28 m:car_parking_nonhandi=24

series e:d87u-izyj d:2017-04-21T07:38:43.106Z t:traveler_information=Yes t:corridor=I-74 t:vending_machines=Yes t:rest_area="Krisdala Baka, IL - WB" t:tdd=Yes t:telephone_services=Yes t:picnic_facilities=Yes t:rest_area_type="Full Service" t:uniqueness=None t:restroom_facilities=Yes t:restareaname="Krisdala Baka, IL - WB" t:handicap_accessible_facilities=Yes t:pet_exercise_area=Yes t:active=YES t:location_1=Outside-Iowa t:objectid=3 m:truck_parking=14 m:handi_parking=2 m:mile_post=28 m:car_parking_nonhandi=24
```

## Meta Commands

```ls
metric m:mile_post p:integer l:Mile_Post d:"Mile Post" t:dataTypeName=number

metric m:car_parking_nonhandi p:integer l:Car_Parking_NonHandi d:"Car Parking Non-Handicap" t:dataTypeName=number

metric m:handi_parking p:integer l:Handi_Parking d:"Handicap Parking" t:dataTypeName=number

metric m:truck_parking p:integer l:Truck_Parking d:"Truck Parking" t:dataTypeName=number

metric m:approx_number_truck_space p:integer l:Approx_Number_Truck_Space d:"Approximate Number of Truck Spaces" t:dataTypeName=number

metric m:truck_percent_utili p:integer l:Truck_Percent_Utili d:"Truck Utilization Percent" t:dataTypeName=number

metric m:daily_volume p:integer l:Daily_Volume d:Daily_Volume t:dataTypeName=number

metric m:daily_volume_june_equivalent p:integer l:Daily_Volume_June_Equivalent d:Daily_Volume_June_Equivalent t:dataTypeName=number

metric m:visitor_estimate_2010 p:integer l:Visitor_Estimate_2010 d:Visitor_Estimate_2010 t:dataTypeName=number

metric m:visitor_estimate_2011 p:integer l:Visitor_Estimate_2011 d:Visitor_Estimate_2011 t:dataTypeName=number

metric m:mainline_aadt_directional p:integer l:_Mainline_AADT_Directional d:_Mainline_AADT_Directional t:dataTypeName=number

metric m:mainline_truck_aadt_directional p:integer l:_Mainline_Truck_AADT_Directional d:_Mainline_Truck_AADT_Directional t:dataTypeName=number

metric m:mainline_truck_aadt_directional_1 p:integer l:_Mainline_Truck_AADT_Directional_1 d:_Mainline_Truck_AADT_Directional_1 t:dataTypeName=number

metric m:mainline_aadt_directional_1 p:integer l:_Mainline_AADT_Directional_1 d:_Mainline_AADT_Directional_1 t:dataTypeName=number

metric m:mainline_truck_aadt_directional_12 p:integer l:_Mainline_Truck_AADT_Directional_12 d:_Mainline_Truck_AADT_Directional_12 t:dataTypeName=number

metric m:mainline_aadt_growth_2010_2035 p:decimal l:Mainline_AADT_Growth_2010_2035 d:Mainline_AADT_Growth_2010_2035 t:dataTypeName=number

metric m:mainline_aadt_growth_2012_2035 p:decimal l:Mainline_AADT_Growth_2012_2035 d:Mainline_AADT_Growth_2012_2035 t:dataTypeName=number

metric m:ukey p:integer l:UKEY d:UKEY t:dataTypeName=number

metric m:cost_cente p:integer l:COST_CENTE d:COST_CENTE t:dataTypeName=number

metric m:square_foo p:integer l:SQUARE_FOO d:SQUARE_FOO t:dataTypeName=number

metric m:distance_to_nearest_24h p:integer l:distance_to_nearest_24h d:distance_to_nearest_24h t:dataTypeName=number

metric m:density_of_24h_asl_lessthanequal_5miles p:integer l:density_of_24h_asl_lessthanequal_5miles d:density_of_24h_asl_lessthanequal_5miles t:dataTypeName=number

metric m:density_of_24h_asl_5to15_miles p:integer l:density_of_24H_asl_5to15_miles d:density_of_24H_asl_5to15_miles t:dataTypeName=number

metric m:density_of_24h_asl_15to30_miles p:integer l:density_of_24h_asl_15to30_miles d:density_of_24h_asl_15to30_miles t:dataTypeName=number

metric m:number_of_spaces_lessthanequal_30miles p:integer l:number_of_spaces_lessthanequal_30miles d:number_of_spaces_lessthanequal_30miles t:dataTypeName=number

metric m:minimun_distance_downstream_1 p:integer l:minimun_distance_downstream_1 d:minimun_distance_downstream_1 t:dataTypeName=number

metric m:minimun_distance_downstream_2 p:integer l:minimun_distance_downstream_2 d:minimun_distance_downstream_2 t:dataTypeName=number

metric m:minimun_distance_upstream_1 p:integer l:minimun_distance_upstream_1 d:minimun_distance_upstream_1 t:dataTypeName=number

metric m:minimun_distance_upstream_2 p:integer l:minimun_distance_upstream_2 d:minimun_distance_upstream_2 t:dataTypeName=number

entity e:d87u-izyj l:"Rest Areas - Full Service" t:attribution="Iowa DOT, HDR Engineering" t:url=https://data.iowa.gov/api/views/d87u-izyj

property e:d87u-izyj t:meta.view v:id=d87u-izyj v:category="Transportation & Utilities" v:averageRating=0 v:name="Rest Areas - Full Service" v:attribution="Iowa DOT, HDR Engineering"

property e:d87u-izyj t:meta.view.owner v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:displayName="Iowa Department of Transportation"

property e:d87u-izyj t:meta.view.tableauthor v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:roleName=administrator v:displayName="Iowa Department of Transportation"
```

## Top Records

```ls
| objectid | location_1   | restareaname              | rest_area_type | rest_area                 | corridor | mile_post | year_built | car_parking_nonhandi | handi_parking | truck_parking | car_pickup_trailer | restroom_facilities | family_restroom_facilities | handicap_accessible_facilities | picnic_facilities | pet_exercise_area | telephone_services | tdd | traveler_information | rv_dump_station | vending_machines | wi_fi | approx_number_truck_space | truck_percent_utili | truck_perc_group | age_group                                        | daily_volume | month_of_data_collection | year_of_data_collection | daily_volume_june_equivalent | visitor_estimate_2010 | visitor_estimate_2011 | mainline_aadt_directional | mainline_truck_aadt_directional | mainline_truck_aadt_directional_1 | mainline_aadt_directional_1 | mainline_truck_aadt_directional_12 | mainline_aadt_growth_2010_2035                          | mainline_aadt_growth_2012_2035                          | ukey | inventory_ | address1                                | near_city    | phone_numb | cost_cente | square_foo | orig_fid | distance_to_nearest_24h | density_of_24h_asl_lessthanequal_5miles | density_of_24h_asl_5to15_miles | density_of_24h_asl_15to30_miles | number_of_spaces_lessthanequal_30miles | uniqueness | active | downstream_rest_area_1      | downstream_rest_area_2 | upstream_rest_area_1      | upstream_rest_area_2 | minimun_distance_downstream_1 | minimun_distance_downstream_2 | minimun_distance_upstream_1 | minimun_distance_upstream_2 | 
| ======== | ============ | ========================= | ============== | ========================= | ======== | ========= | ========== | ==================== | ============= | ============= | ================== | =================== | ========================== | ============================== | ================= | ================= | ================== | === | ==================== | =============== | ================ | ===== | ========================= | =================== | ================ | ================================================ | ============ | ======================== | ======================= | ============================ | ===================== | ===================== | ========================= | =============================== | ================================= | =========================== | ================================== | ======================================================= | ======================================================= | ==== | ========== | ======================================= | ============ | ========== | ========== | ========== | ======== | ======================= | ======================================= | ============================== | =============================== | ====================================== | ========== | ====== | =========================== | ====================== | ========================= | ==================== | ============================= | ============================= | =========================== | =========================== | 
| 1        | Outside-Iowa | Great Sauk Trail, IL - WB | Full Service   | Great Sauk Trail, IL - WB | I-80     | 51        |            | 54                   | 5             | 46            |                    | Yes                 |                            | Yes                            | Yes               | Yes               | Yes                | Yes | Yes                  |                 | Yes              |       |                           |                     |                  |                                                  |              |                          |                         |                              |                       |                       |                           |                                 |                                   |                             |                                    |                                                         |                                                         |      |            |                                         |              |            |            |            |          |                         |                                         |                                |                                 |                                        | None       | YES    |                             |                        |                           |                      |                               |                               |                             |                             | 
| 2        | Outside-Iowa | Krisdala Baka, IL - EB    | Full Service   | Krisdala Baka, IL - EB    | I-74     | 28        |            | 24                   | 2             | 14            |                    | Yes                 |                            | Yes                            | Yes               | Yes               | Yes                | Yes | Yes                  |                 | Yes              |       |                           |                     |                  |                                                  |              |                          |                         |                              |                       |                       |                           |                                 |                                   |                             |                                    |                                                         |                                                         |      |            |                                         |              |            |            |            |          |                         |                                         |                                |                                 |                                        | None       | YES    |                             |                        |                           |                      |                               |                               |                             |                             | 
| 3        | Outside-Iowa | Krisdala Baka, IL - WB    | Full Service   | Krisdala Baka, IL - WB    | I-74     | 28        |            | 24                   | 2             | 14            |                    | Yes                 |                            | Yes                            | Yes               | Yes               | Yes                | Yes | Yes                  |                 | Yes              |       |                           |                     |                  |                                                  |              |                          |                         |                              |                       |                       |                           |                                 |                                   |                             |                                    |                                                         |                                                         |      |            |                                         |              |            |            |            |          |                         |                                         |                                |                                 |                                        | None       | YES    |                             |                        |                           |                      |                               |                               |                             |                             | 
| 4        | In-Iowa      | Davenport WB              | Full Service   | Davenport WB              | I-80     | 300       | 2001       | 46                   | 4             | 20            | Yes                | Yes                 | Yes                        | Yes                            | Yes               | Yes               | Yes                | Yes | Yes                  |                 | Yes              | Yes   | 20                        | 210                 | ? 200%           | Rest Area Building in Second Half of Design Life | 960          | July                     | 2016                    | 960                          | 699682                | 699682                | 22700                     | 5540                            | 5540                              | 34725                       | 9030                               | 0.5297356829999999572322622043429873883724212646484375  | 0.5297356829999999572322622043429873883724212646484375  | 9    | 826D63     | 300 I-80 West Bound, Bettendorf IA      | Davenport    | 5633325727 | 550714     | 4900       | 23       | 5                       | 1                                       | 3                              | 4                               | 190                                    | Highly     | YES    | Wilton WB                   |                        | Great Sauk Trail, IL - WB |                      | 30                            |                               | 57                          |                             | 
| 5        | In-Iowa      | Davenport EB              | Full Service   | Davenport EB              | I-80     | 300       | 1966       | 39                   | 2             | 14            | Yes                | Yes                 |                            | Yes                            | Yes               | Yes               | Yes                | Yes | Yes                  |                 | Yes              | Yes   | 14                        | 100                 | 100-149%         | Rest Area Building Exceeded Design Life          | 499          | July                     | 2016                    | 499                          | 282818                | 282818                | 22700                     | 5540                            | 5540                              | 34725                       | 9030                               | 0.5297356829999999572322622043429873883724212646484375  | 0.5297356829999999572322622043429873883724212646484375  | 8    | 826D61     | 300 I-80 East Bound, Bettendorf IA      | Davenport    | 5633326377 | 550713     | 1020       | 22       | 5                       | 1                                       | 3                              | 4                               | 190                                    | None       | YES    | Mississippi Rapids, IL - EB |                        | Wilton EB                 |                      | 7                             |                               | 30                          |                             | 
| 6        | In-Iowa      | Wilton WB                 | Full Service   | Wilton WB                 | I-80     | 270       | 1999       | 40                   | 2             | 15            | Yes                | Yes                 | Yes                        | Yes                            | Yes               | Yes               | Yes                | Yes | Yes                  | Yes             | Yes              | Yes   | 15                        | 140                 | 100-149%         | Rest Area Building in Second Half of Design Life | 924          | July                     | 2016                    | 924                          | 418045                | 418045                | 16650                     | 5830                            | 5830                              | 29500                       | 10920                              | 0.77177177200000002255109166071633808314800262451171875 | 0.77177177200000002255109166071633808314800262451171875 | 16   | 166T63     | 1450 I-80 West Bound, Wilton IA         | Wilton       | 5637323145 | 550704     | 4900       | 33       | 3                       | 2                                       | 4                              | 9                               | 196                                    | Highly     | YES    | Tiffin WB                   |                        | Davenport WB              |                      | 33                            |                               | 30                          |                             | 
| 7        | In-Iowa      | Wilton EB                 | Full Service   | Wilton EB                 | I-80     | 270       | 2002       | 36                   | 2             | 16            | Yes                | Yes                 | Yes                        | Yes                            | Yes               | Yes               | Yes                | Yes | Yes                  | Yes             | Yes              | Yes   | 16                        | 125                 | 100-149%         | Rest Area Building in Second Half of Design Life | 853          | July                     | 2016                    | 853                          | 657818                | 657818                | 16650                     | 5830                            | 5830                              | 29500                       | 10920                              | 0.77177177200000002255109166071633808314800262451171875 | 0.77177177200000002255109166071633808314800262451171875 | 15   | 166T61     | 1453 I-80 East Bound, Wilton IA         | Wilton       | 5637323145 | 550703     | 4900       | 32       | 3                       | 2                                       | 4                              | 9                               | 196                                    | None       | YES    | Davenport EB                |                        | Tiffin EB                 |                      | 30                            |                               | 33                          |                             | 
| 8        | In-Iowa      | Cedar Rapids NB           | Full Service   | Cedar Rapids NB           | I-380    | 13        | 2012       | 26                   | 2             | 16            | Yes                | Yes                 | Yes                        | Yes                            | Yes               | Yes               | Yes                | Yes | Yes                  | Yes             | Yes              | Yes   | 16                        | 231                 | ? 200%           | Rest Area Building in First Half of Design Life  | 776          | July                     | 2016                    | 776                          | 513648                | 513648                | 24950                     | 4140                            | 4140                              | 42415                       | 7890                               | 0.6999999999999999555910790149937383830547332763671875  | 0.6999999999999999555910790149937383830547332763671875  | 29   | 576C61     | 6848 I-380 South Bound, Cedar Rapids IA | Cedar Rapids | 3198487366 | 550748     | 1020       | 58       | 0                       | 8                                       | 11                             | 3                               | 41                                     | Highly     | YES    | Dows NB/SB                  |                        | Tiffin - WB               |                      | 154                           |                               | 15                          |                             | 
| 9        | In-Iowa      | Cedar Rapids SB           | Full Service   | Cedar Rapids SB           | I-380    | 13        | 1975       | 26                   | 2             | 15            | Yes                | Yes                 |                            | Yes                            | Yes               | Yes               | Yes                | Yes | Yes                  | Yes             | Yes              | Yes   | 15                        | 227                 | ? 200%           | Rest Area Building Exceeded Design Life          | 733          | July                     | 2016                    | 733                          | 339852                | 339852                | 24950                     | 4140                            | 4140                              | 42415                       | 7890                               | 0.6999999999999999555910790149937383830547332763671875  | 0.6999999999999999555910790149937383830547332763671875  | 66   | 16         | Cedar Rapids - Northbound I-380         | Cedar Rapids | 0          | 550749     | 0          | 0        | 0                       | 8                                       | 11                             | 3                               | 41                                     | None       | YES    | Tiffin - WB                 |                        | Dows NB/SB                |                      | 15                            |                               | 154                         |                             | 
| 10       | In-Iowa      | Tiffin WB                 | Full Service   | Tiffin WB                 | I-80     | 237       | 2001       | 77                   | 6             | 23            | Yes                | Yes                 | Yes                        | Yes                            | Yes               | Yes               | Yes                | Yes | Yes                  | Yes             | Yes              | Yes   | 23                        | 148                 | 100-149%         | Rest Area Building in Second Half of Design Life | 691          | July                     | 2016                    | 691                          | 694051                | 694051                | 17400                     | 4960                            | 4960                              | 38195                       | 11840                              | 1.19511494300000009616269380785524845123291015625       | 1.19511494300000009616269380785524845123291015625       | 28   | 526T67     | 2520 I-80 West Bound, Tiffin IA         | Tiffin       | 3196452432 | 550710     | 4900       | 57       | 0                       | 5                                       | 0                              | 6                               | 4                                      | None       | YES    | Victor WB                   |                        | Wilton WB                 |                      | 29                            |                               | 33                          |                             | 
```