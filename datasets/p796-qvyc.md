# Truck Parking Utilization - Full Service

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/truck-parking-utilization-full-service-5c3bb) |
| Metadata | [Link](https://data.iowa.gov/api/views/p796-qvyc) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/p796-qvyc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/p796-qvyc/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | p796-qvyc |
| Name | Truck Parking Utilization - Full Service |
| Attribution | Iowa DOT, HDR Engineering |
| Category | Transportation & Utilities |
| Tags | asset, classification, rest, area, truck, parking, iowa dot, iowa department of transportation |
| Created | 2016-08-19T20:31:24Z |
| Publication Date | 2016-08-19T20:35:04Z |

## Description

Iowa Department of Transportation statewide rest area data. This layer displays full service locations with truck parking utilization.

## Columns

```ls
| Included | Schema Type    | Field Name                              | Name                                    | Data Type | Render Type |
| ======== | ============== | ======================================= | ======================================= | ========= | =========== |
| Yes      | series tag     | objectid                                | OBJECTID                                | text      | number      |
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
series e:p796-qvyc d:2001-01-01T00:00:00.000Z t:upstream_rest_area_1="Great Sauk Trail, IL - WB" t:truck_perc_group="? 200%" t:car_pickup_trailer=Yes t:inventory_=826D63 t:traveler_information=Yes t:phone_numb=5633325727 t:corridor=I-80 t:family_restroom_facilities=Yes t:vending_machines=Yes t:rest_area="Davenport WB" t:tdd=Yes t:near_city=Davenport t:telephone_services=Yes t:picnic_facilities=Yes t:wi_fi=Yes t:downstream_rest_area_1="Wilton WB" t:age_group="Rest Area Building in Second Half of Design Life" t:restroom_facilities=Yes t:uniqueness=Highly t:month_of_data_collection=July t:active=YES t:pet_exercise_area=Yes t:handicap_accessible_facilities=Yes t:objectid=4 t:orig_fid=23 m:approx_number_truck_space=20 m:number_of_spaces_lessthanequal_30miles=190 m:minimun_distance_downstream_1=30 m:mainline_aadt_directional=22700 m:handi_parking=4 m:visitor_estimate_2010=699682 m:mainline_truck_aadt_directional_12=9030 m:truck_percent_utili=210 m:visitor_estimate_2011=699682 m:ukey=9 m:cost_cente=550714 m:mainline_aadt_directional_1=34725 m:square_foo=4900 m:density_of_24h_asl_5to15_miles=3 m:mile_post=300 m:car_parking_nonhandi=46 m:distance_to_nearest_24h=5 m:mainline_truck_aadt_directional=5540 m:density_of_24h_asl_15to30_miles=4 m:mainline_truck_aadt_directional_1=5540 m:mainline_aadt_growth_2010_2035=0.529735683 m:daily_volume=960 m:truck_parking=20 m:density_of_24h_asl_lessthanequal_5miles=1 m:mainline_aadt_growth_2012_2035=0.529735683 m:daily_volume_june_equivalent=960 m:minimun_distance_upstream_1=57

series e:p796-qvyc d:1966-01-01T00:00:00.000Z t:upstream_rest_area_1="Wilton EB" t:truck_perc_group=100-149% t:car_pickup_trailer=Yes t:inventory_=826D61 t:traveler_information=Yes t:phone_numb=5633326377 t:corridor=I-80 t:vending_machines=Yes t:rest_area="Davenport EB" t:tdd=Yes t:near_city=Davenport t:telephone_services=Yes t:picnic_facilities=Yes t:wi_fi=Yes t:downstream_rest_area_1="Mississippi Rapids, IL - EB" t:age_group="Rest Area Building Exceeded Design Life" t:restroom_facilities=Yes t:uniqueness=None t:month_of_data_collection=July t:active=YES t:pet_exercise_area=Yes t:handicap_accessible_facilities=Yes t:objectid=5 t:orig_fid=22 m:approx_number_truck_space=14 m:number_of_spaces_lessthanequal_30miles=190 m:minimun_distance_downstream_1=7 m:mainline_aadt_directional=22700 m:handi_parking=2 m:visitor_estimate_2010=282818 m:mainline_truck_aadt_directional_12=9030 m:truck_percent_utili=100 m:visitor_estimate_2011=282818 m:ukey=8 m:cost_cente=550713 m:mainline_aadt_directional_1=34725 m:square_foo=1020 m:density_of_24h_asl_5to15_miles=3 m:mile_post=300 m:car_parking_nonhandi=39 m:distance_to_nearest_24h=5 m:mainline_truck_aadt_directional=5540 m:density_of_24h_asl_15to30_miles=4 m:mainline_truck_aadt_directional_1=5540 m:mainline_aadt_growth_2010_2035=0.529735683 m:daily_volume=499 m:truck_parking=14 m:density_of_24h_asl_lessthanequal_5miles=1 m:mainline_aadt_growth_2012_2035=0.529735683 m:daily_volume_june_equivalent=499 m:minimun_distance_upstream_1=30

series e:p796-qvyc d:1999-01-01T00:00:00.000Z t:upstream_rest_area_1="Davenport WB" t:inventory_=166T63 t:phone_numb=5637323145 t:corridor=I-80 t:family_restroom_facilities=Yes t:rest_area="Wilton WB" t:wi_fi=Yes t:picnic_facilities=Yes t:uniqueness=Highly t:handicap_accessible_facilities=Yes t:month_of_data_collection=July t:orig_fid=33 t:car_pickup_trailer=Yes t:truck_perc_group=100-149% t:rv_dump_station=Yes t:traveler_information=Yes t:vending_machines=Yes t:tdd=Yes t:telephone_services=Yes t:near_city=Wilton t:downstream_rest_area_1="Tiffin WB" t:restroom_facilities=Yes t:age_group="Rest Area Building in Second Half of Design Life" t:pet_exercise_area=Yes t:active=YES t:objectid=6 m:approx_number_truck_space=15 m:number_of_spaces_lessthanequal_30miles=196 m:minimun_distance_downstream_1=33 m:mainline_aadt_directional=16650 m:handi_parking=2 m:visitor_estimate_2010=418045 m:mainline_truck_aadt_directional_12=10920 m:truck_percent_utili=140 m:visitor_estimate_2011=418045 m:ukey=16 m:cost_cente=550704 m:mainline_aadt_directional_1=29500 m:square_foo=4900 m:density_of_24h_asl_5to15_miles=4 m:mile_post=270 m:car_parking_nonhandi=40 m:distance_to_nearest_24h=3 m:mainline_truck_aadt_directional=5830 m:density_of_24h_asl_15to30_miles=9 m:mainline_truck_aadt_directional_1=5830 m:mainline_aadt_growth_2010_2035=0.771771772 m:daily_volume=924 m:truck_parking=15 m:density_of_24h_asl_lessthanequal_5miles=2 m:mainline_aadt_growth_2012_2035=0.771771772 m:daily_volume_june_equivalent=924 m:minimun_distance_upstream_1=30
```

## Meta Commands

```ls
metric m:mile_post p:integer l:Mile_Post d:"Mile Post" t:dataTypeName=number

metric m:car_parking_nonhandi p:integer l:Car_Parking_NonHandi d:"Car Parking Non-Handicap" t:dataTypeName=number

metric m:handi_parking p:integer l:Handi_Parking d:"Handicap Parking" t:dataTypeName=number

metric m:truck_parking p:integer l:Truck_Parking d:"Truck Parking" t:dataTypeName=number

metric m:approx_number_truck_space p:integer l:Approx_Number_Truck_Space d:"Approximate Number of Truck Spaces" t:dataTypeName=number

metric m:truck_percent_utili p:integer l:Truck_Percent_Utili d:"Truck Utilization Percent" t:dataTypeName=number

metric m:daily_volume p:integer l:Daily_Volume d:"Daily Volume" t:dataTypeName=number

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

entity e:p796-qvyc l:"Truck Parking Utilization - Full Service" t:attribution="Iowa DOT, HDR Engineering" t:url=https://data.iowa.gov/api/views/p796-qvyc

property e:p796-qvyc t:meta.view v:id=p796-qvyc v:category="Transportation & Utilities" v:averageRating=0 v:name="Truck Parking Utilization - Full Service" v:attribution="Iowa DOT, HDR Engineering"

property e:p796-qvyc t:meta.view.owner v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:displayName="Iowa Department of Transportation"

property e:p796-qvyc t:meta.view.tableauthor v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:roleName=administrator v:displayName="Iowa Department of Transportation"
```

## Top Records

```ls
| objectid | rest_area       | corridor | mile_post | year_built | car_parking_nonhandi | handi_parking | truck_parking | car_pickup_trailer | restroom_facilities | family_restroom_facilities | handicap_accessible_facilities | picnic_facilities | pet_exercise_area | telephone_services | tdd | traveler_information | rv_dump_station | vending_machines | wi_fi | approx_number_truck_space | truck_percent_utili | truck_perc_group | age_group                                        | daily_volume | month_of_data_collection | year_of_data_collection | daily_volume_june_equivalent | visitor_estimate_2010 | visitor_estimate_2011 | mainline_aadt_directional | mainline_truck_aadt_directional | mainline_truck_aadt_directional_1 | mainline_aadt_directional_1 | mainline_truck_aadt_directional_12 | mainline_aadt_growth_2010_2035                           | mainline_aadt_growth_2012_2035                           | ukey | inventory_ | address1                                | near_city    | phone_numb | cost_cente | square_foo | orig_fid | distance_to_nearest_24h | density_of_24h_asl_lessthanequal_5miles | density_of_24h_asl_5to15_miles | density_of_24h_asl_15to30_miles | number_of_spaces_lessthanequal_30miles | uniqueness | active | downstream_rest_area_1      | downstream_rest_area_2 | upstream_rest_area_1      | upstream_rest_area_2 | minimun_distance_downstream_1 | minimun_distance_downstream_2 | minimun_distance_upstream_1 | minimun_distance_upstream_2 | 
| ======== | =============== | ======== | ========= | ========== | ==================== | ============= | ============= | ================== | =================== | ========================== | ============================== | ================= | ================= | ================== | === | ==================== | =============== | ================ | ===== | ========================= | =================== | ================ | ================================================ | ============ | ======================== | ======================= | ============================ | ===================== | ===================== | ========================= | =============================== | ================================= | =========================== | ================================== | ======================================================== | ======================================================== | ==== | ========== | ======================================= | ============ | ========== | ========== | ========== | ======== | ======================= | ======================================= | ============================== | =============================== | ====================================== | ========== | ====== | =========================== | ====================== | ========================= | ==================== | ============================= | ============================= | =========================== | =========================== | 
| 4        | Davenport WB    | I-80     | 300       | 2001       | 46                   | 4             | 20            | Yes                | Yes                 | Yes                        | Yes                            | Yes               | Yes               | Yes                | Yes | Yes                  |                 | Yes              | Yes   | 20                        | 210                 | ? 200%           | Rest Area Building in Second Half of Design Life | 960          | July                     | 2016                    | 960                          | 699682                | 699682                | 22700                     | 5540                            | 5540                              | 34725                       | 9030                               | 0.5297356829999999572322622043429873883724212646484375   | 0.5297356829999999572322622043429873883724212646484375   | 9    | 826D63     | 300 I-80 West Bound, Bettendorf IA      | Davenport    | 5633325727 | 550714     | 4900       | 23       | 5                       | 1                                       | 3                              | 4                               | 190                                    | Highly     | YES    | Wilton WB                   |                        | Great Sauk Trail, IL - WB |                      | 30                            |                               | 57                          |                             | 
| 5        | Davenport EB    | I-80     | 300       | 1966       | 39                   | 2             | 14            | Yes                | Yes                 |                            | Yes                            | Yes               | Yes               | Yes                | Yes | Yes                  |                 | Yes              | Yes   | 14                        | 100                 | 100-149%         | Rest Area Building Exceeded Design Life          | 499          | July                     | 2016                    | 499                          | 282818                | 282818                | 22700                     | 5540                            | 5540                              | 34725                       | 9030                               | 0.5297356829999999572322622043429873883724212646484375   | 0.5297356829999999572322622043429873883724212646484375   | 8    | 826D61     | 300 I-80 East Bound, Bettendorf IA      | Davenport    | 5633326377 | 550713     | 1020       | 22       | 5                       | 1                                       | 3                              | 4                               | 190                                    | None       | YES    | Mississippi Rapids, IL - EB |                        | Wilton EB                 |                      | 7                             |                               | 30                          |                             | 
| 6        | Wilton WB       | I-80     | 270       | 1999       | 40                   | 2             | 15            | Yes                | Yes                 | Yes                        | Yes                            | Yes               | Yes               | Yes                | Yes | Yes                  | Yes             | Yes              | Yes   | 15                        | 140                 | 100-149%         | Rest Area Building in Second Half of Design Life | 924          | July                     | 2016                    | 924                          | 418045                | 418045                | 16650                     | 5830                            | 5830                              | 29500                       | 10920                              | 0.77177177200000002255109166071633808314800262451171875  | 0.77177177200000002255109166071633808314800262451171875  | 16   | 166T63     | 1450 I-80 West Bound, Wilton IA         | Wilton       | 5637323145 | 550704     | 4900       | 33       | 3                       | 2                                       | 4                              | 9                               | 196                                    | Highly     | YES    | Tiffin WB                   |                        | Davenport WB              |                      | 33                            |                               | 30                          |                             | 
| 7        | Wilton EB       | I-80     | 270       | 2002       | 36                   | 2             | 16            | Yes                | Yes                 | Yes                        | Yes                            | Yes               | Yes               | Yes                | Yes | Yes                  | Yes             | Yes              | Yes   | 16                        | 125                 | 100-149%         | Rest Area Building in Second Half of Design Life | 853          | July                     | 2016                    | 853                          | 657818                | 657818                | 16650                     | 5830                            | 5830                              | 29500                       | 10920                              | 0.77177177200000002255109166071633808314800262451171875  | 0.77177177200000002255109166071633808314800262451171875  | 15   | 166T61     | 1453 I-80 East Bound, Wilton IA         | Wilton       | 5637323145 | 550703     | 4900       | 32       | 3                       | 2                                       | 4                              | 9                               | 196                                    | None       | YES    | Davenport EB                |                        | Tiffin EB                 |                      | 30                            |                               | 33                          |                             | 
| 8        | Cedar Rapids NB | I-380    | 13        | 2012       | 26                   | 2             | 16            | Yes                | Yes                 | Yes                        | Yes                            | Yes               | Yes               | Yes                | Yes | Yes                  | Yes             | Yes              | Yes   | 16                        | 231                 | ? 200%           | Rest Area Building in First Half of Design Life  | 776          | July                     | 2016                    | 776                          | 513648                | 513648                | 24950                     | 4140                            | 4140                              | 42415                       | 7890                               | 0.6999999999999999555910790149937383830547332763671875   | 0.6999999999999999555910790149937383830547332763671875   | 29   | 576C61     | 6848 I-380 South Bound, Cedar Rapids IA | Cedar Rapids | 3198487366 | 550748     | 1020       | 58       | 0                       | 8                                       | 11                             | 3                               | 41                                     | Highly     | YES    | Dows NB/SB                  |                        | Tiffin - WB               |                      | 154                           |                               | 15                          |                             | 
| 9        | Cedar Rapids SB | I-380    | 13        | 1975       | 26                   | 2             | 15            | Yes                | Yes                 |                            | Yes                            | Yes               | Yes               | Yes                | Yes | Yes                  | Yes             | Yes              | Yes   | 15                        | 227                 | ? 200%           | Rest Area Building Exceeded Design Life          | 733          | July                     | 2016                    | 733                          | 339852                | 339852                | 24950                     | 4140                            | 4140                              | 42415                       | 7890                               | 0.6999999999999999555910790149937383830547332763671875   | 0.6999999999999999555910790149937383830547332763671875   | 66   | 16         | Cedar Rapids - Northbound I-380         | Cedar Rapids | 0          | 550749     | 0          | 0        | 0                       | 8                                       | 11                             | 3                               | 41                                     | None       | YES    | Tiffin - WB                 |                        | Dows NB/SB                |                      | 15                            |                               | 154                         |                             | 
| 10       | Tiffin WB       | I-80     | 237       | 2001       | 77                   | 6             | 23            | Yes                | Yes                 | Yes                        | Yes                            | Yes               | Yes               | Yes                | Yes | Yes                  | Yes             | Yes              | Yes   | 23                        | 148                 | 100-149%         | Rest Area Building in Second Half of Design Life | 691          | July                     | 2016                    | 691                          | 694051                | 694051                | 17400                     | 4960                            | 4960                              | 38195                       | 11840                              | 1.19511494300000009616269380785524845123291015625        | 1.19511494300000009616269380785524845123291015625        | 28   | 526T67     | 2520 I-80 West Bound, Tiffin IA         | Tiffin       | 3196452432 | 550710     | 4900       | 57       | 0                       | 5                                       | 0                              | 6                               | 4                                      | None       | YES    | Victor WB                   |                        | Wilton WB                 |                      | 29                            |                               | 33                          |                             | 
| 11       | Tiffin EB       | I-80     | 237       | 2010       | 71                   | 4             | 23            |                    | Yes                 | Yes                        | Yes                            | Yes               | Yes               | Yes                | Yes | Yes                  | Yes             | Yes              | Yes   | 23                        | 100                 | 100-149%         | Rest Area Building in First Half of Design Life  | 833          | July                     | 2016                    | 833                          | 766791                | 766791                | 17400                     | 4960                            | 4960                              | 38195                       | 11840                              | 1.19511494300000009616269380785524845123291015625        | 1.19511494300000009616269380785524845123291015625        | 65   | 13         | Tiffin - Eastbound I-80                 | Tiffin       | 0          | 550709     | 0          | 0        | 0                       | 5                                       | 0                              | 6                               | 4                                      | Highly     | YES    | Wilton EB                   |                        | Victor EB                 |                      | 33                            |                               | 29                          |                             | 
| 12       | Victor WB       | I-80     | 208       | 1967       | 72                   | 3             | 19            | Yes                | Yes                 |                            | Yes                            | Yes               | Yes               | Yes                | Yes | Yes                  | Yes             | Yes              | Yes   | 19                        | 142                 | 100-149%         | Rest Area Building Exceeded Design Life          | 762          | July                     | 2016                    | 762                          | 386035                | 386035                | 13150                     | 4600                            | 4600                              | 19650                       | 7270                               | 0.494296577999999986463564027872052974998950958251953125 | 0.494296577999999986463564027872052974998950958251953125 | 45   | 40         | Victor - Westbound I-80                 | Victor       | 0          | 556606     | 0          | 0        | 7                       | 0                                       | 4                              | 2                               | 30                                     | None       | YES    | Grinnell WB                 |                        | Tiffin WB                 |                      | 28                            |                               | 29                          |                             | 
| 13       | Victor EB       | I-80     | 208       | 1967       | 87                   | 3             | 22            | Yes                | Yes                 |                            | Yes                            | Yes               | Yes               | Yes                | Yes | Yes                  | Yes             | Yes              | Yes   | 22                        | 77                  | 75-99%           | Rest Area Building Exceeded Design Life          | 764          | July                     | 2016                    | 764                          | 401068                | 401068                | 13150                     | 4600                            | 4600                              | 19650                       | 7270                               | 0.494296577999999986463564027872052974998950958251953125 | 0.494296577999999986463564027872052974998950958251953125 | 46   | 39         | Victor - Eastbound I-80                 | Victor       | 0          | 556606     | 0          | 0        | 7                       | 0                                       | 4                              | 2                               | 30                                     | None       | YES    | Tiffin EB                   |                        | Grinnell EB               |                      | 29                            |                               | 28                          |                             | 
```