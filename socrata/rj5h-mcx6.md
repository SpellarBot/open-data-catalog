# Rest Area Aging Infrastructure - Building in Second Half of Design Life

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/rest-area-aging-infrastructure-building-in-second-half-of-design-life) |
| Metadata | [Link](https://data.iowa.gov/api/views/rj5h-mcx6) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/rj5h-mcx6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/rj5h-mcx6/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | rj5h-mcx6 |
| Name | Rest Area Aging Infrastructure - Building in Second Half of Design Life |
| Attribution | Iowa DOT, HDR Engineering |
| Category | Transportation & Utilities |
| Tags | asset, classification, rest, area, infrastructure, iowa dot, iowa department of transportation |
| Created | 2016-08-19T20:38:37Z |
| Publication Date | 2016-08-19T20:40:35Z |

## Description

Iowa Department of Transportation statewide rest area data. This layer displays aging rest area infrastructure where a building is in the second half of its design life.

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
series e:rj5h-mcx6 d:2001-01-01T00:00:00.000Z t:upstream_rest_area_1="Great Sauk Trail, IL - WB" t:truck_perc_group="? 200%" t:car_pickup_trailer=Yes t:inventory_=826D63 t:traveler_information=Yes t:phone_numb=5633325727 t:corridor=I-80 t:family_restroom_facilities=Yes t:vending_machines=Yes t:rest_area="Davenport WB" t:tdd=Yes t:near_city=Davenport t:telephone_services=Yes t:picnic_facilities=Yes t:wi_fi=Yes t:downstream_rest_area_1="Wilton WB" t:age_group="Rest Area Building in Second Half of Design Life" t:restroom_facilities=Yes t:uniqueness=Highly t:month_of_data_collection=July t:active=YES t:pet_exercise_area=Yes t:handicap_accessible_facilities=Yes t:objectid=4 t:orig_fid=23 m:approx_number_truck_space=20 m:number_of_spaces_lessthanequal_30miles=190 m:minimun_distance_downstream_1=30 m:mainline_aadt_directional=22700 m:handi_parking=4 m:visitor_estimate_2010=699682 m:mainline_truck_aadt_directional_12=9030 m:truck_percent_utili=210 m:visitor_estimate_2011=699682 m:ukey=9 m:cost_cente=550714 m:mainline_aadt_directional_1=34725 m:square_foo=4900 m:density_of_24h_asl_5to15_miles=3 m:mile_post=300 m:car_parking_nonhandi=46 m:distance_to_nearest_24h=5 m:mainline_truck_aadt_directional=5540 m:density_of_24h_asl_15to30_miles=4 m:mainline_truck_aadt_directional_1=5540 m:mainline_aadt_growth_2010_2035=0.529735683 m:daily_volume=960 m:truck_parking=20 m:density_of_24h_asl_lessthanequal_5miles=1 m:mainline_aadt_growth_2012_2035=0.529735683 m:daily_volume_june_equivalent=960 m:minimun_distance_upstream_1=57

series e:rj5h-mcx6 d:1999-01-01T00:00:00.000Z t:upstream_rest_area_1="Davenport WB" t:inventory_=166T63 t:phone_numb=5637323145 t:corridor=I-80 t:family_restroom_facilities=Yes t:rest_area="Wilton WB" t:wi_fi=Yes t:picnic_facilities=Yes t:uniqueness=Highly t:handicap_accessible_facilities=Yes t:month_of_data_collection=July t:orig_fid=33 t:car_pickup_trailer=Yes t:truck_perc_group=100-149% t:rv_dump_station=Yes t:traveler_information=Yes t:vending_machines=Yes t:tdd=Yes t:telephone_services=Yes t:near_city=Wilton t:downstream_rest_area_1="Tiffin WB" t:restroom_facilities=Yes t:age_group="Rest Area Building in Second Half of Design Life" t:pet_exercise_area=Yes t:active=YES t:objectid=6 m:approx_number_truck_space=15 m:number_of_spaces_lessthanequal_30miles=196 m:minimun_distance_downstream_1=33 m:mainline_aadt_directional=16650 m:handi_parking=2 m:visitor_estimate_2010=418045 m:mainline_truck_aadt_directional_12=10920 m:truck_percent_utili=140 m:visitor_estimate_2011=418045 m:ukey=16 m:cost_cente=550704 m:mainline_aadt_directional_1=29500 m:square_foo=4900 m:density_of_24h_asl_5to15_miles=4 m:mile_post=270 m:car_parking_nonhandi=40 m:distance_to_nearest_24h=3 m:mainline_truck_aadt_directional=5830 m:density_of_24h_asl_15to30_miles=9 m:mainline_truck_aadt_directional_1=5830 m:mainline_aadt_growth_2010_2035=0.771771772 m:daily_volume=924 m:truck_parking=15 m:density_of_24h_asl_lessthanequal_5miles=2 m:mainline_aadt_growth_2012_2035=0.771771772 m:daily_volume_june_equivalent=924 m:minimun_distance_upstream_1=30

series e:rj5h-mcx6 d:2002-01-01T00:00:00.000Z t:upstream_rest_area_1="Tiffin EB" t:inventory_=166T61 t:phone_numb=5637323145 t:corridor=I-80 t:family_restroom_facilities=Yes t:rest_area="Wilton EB" t:wi_fi=Yes t:picnic_facilities=Yes t:uniqueness=None t:handicap_accessible_facilities=Yes t:month_of_data_collection=July t:orig_fid=32 t:car_pickup_trailer=Yes t:truck_perc_group=100-149% t:rv_dump_station=Yes t:traveler_information=Yes t:vending_machines=Yes t:tdd=Yes t:telephone_services=Yes t:near_city=Wilton t:downstream_rest_area_1="Davenport EB" t:restroom_facilities=Yes t:age_group="Rest Area Building in Second Half of Design Life" t:pet_exercise_area=Yes t:active=YES t:objectid=7 m:approx_number_truck_space=16 m:number_of_spaces_lessthanequal_30miles=196 m:minimun_distance_downstream_1=30 m:mainline_aadt_directional=16650 m:handi_parking=2 m:visitor_estimate_2010=657818 m:mainline_truck_aadt_directional_12=10920 m:truck_percent_utili=125 m:visitor_estimate_2011=657818 m:ukey=15 m:cost_cente=550703 m:mainline_aadt_directional_1=29500 m:square_foo=4900 m:density_of_24h_asl_5to15_miles=4 m:mile_post=270 m:car_parking_nonhandi=36 m:distance_to_nearest_24h=3 m:mainline_truck_aadt_directional=5830 m:density_of_24h_asl_15to30_miles=9 m:mainline_truck_aadt_directional_1=5830 m:mainline_aadt_growth_2010_2035=0.771771772 m:daily_volume=853 m:truck_parking=16 m:density_of_24h_asl_lessthanequal_5miles=2 m:mainline_aadt_growth_2012_2035=0.771771772 m:daily_volume_june_equivalent=853 m:minimun_distance_upstream_1=33
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

entity e:rj5h-mcx6 l:"Rest Area Aging Infrastructure - Building in Second Half of Design Life" t:attribution="Iowa DOT, HDR Engineering" t:url=https://data.iowa.gov/api/views/rj5h-mcx6

property e:rj5h-mcx6 t:meta.view v:id=rj5h-mcx6 v:category="Transportation & Utilities" v:averageRating=0 v:name="Rest Area Aging Infrastructure - Building in Second Half of Design Life" v:attribution="Iowa DOT, HDR Engineering"

property e:rj5h-mcx6 t:meta.view.owner v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:displayName="Iowa Department of Transportation"

property e:rj5h-mcx6 t:meta.view.tableauthor v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:roleName=administrator v:displayName="Iowa Department of Transportation"
```

## Top Records

```ls
| objectid | rest_area        | corridor | mile_post | year_built | car_parking_nonhandi | handi_parking | truck_parking | car_pickup_trailer | restroom_facilities | family_restroom_facilities | handicap_accessible_facilities | picnic_facilities | pet_exercise_area | telephone_services | tdd | traveler_information | rv_dump_station | vending_machines | wi_fi | approx_number_truck_space | truck_percent_utili | truck_perc_group | age_group                                        | daily_volume | month_of_data_collection | year_of_data_collection | daily_volume_june_equivalent | visitor_estimate_2010 | visitor_estimate_2011 | mainline_aadt_directional | mainline_truck_aadt_directional | mainline_truck_aadt_directional_1 | mainline_aadt_directional_1 | mainline_truck_aadt_directional_12 | mainline_aadt_growth_2010_2035                           | mainline_aadt_growth_2012_2035                           | ukey | inventory_ | address1                           | near_city     | phone_numb | cost_cente | square_foo | orig_fid | distance_to_nearest_24h | density_of_24h_asl_lessthanequal_5miles | density_of_24h_asl_5to15_miles | density_of_24h_asl_15to30_miles | number_of_spaces_lessthanequal_30miles | uniqueness | active | downstream_rest_area_1 | downstream_rest_area_2 | upstream_rest_area_1      | upstream_rest_area_2    | minimun_distance_downstream_1 | minimun_distance_downstream_2 | minimun_distance_upstream_1 | minimun_distance_upstream_2 | 
| ======== | ================ | ======== | ========= | ========== | ==================== | ============= | ============= | ================== | =================== | ========================== | ============================== | ================= | ================= | ================== | === | ==================== | =============== | ================ | ===== | ========================= | =================== | ================ | ================================================ | ============ | ======================== | ======================= | ============================ | ===================== | ===================== | ========================= | =============================== | ================================= | =========================== | ================================== | ======================================================== | ======================================================== | ==== | ========== | ================================== | ============= | ========== | ========== | ========== | ======== | ======================= | ======================================= | ============================== | =============================== | ====================================== | ========== | ====== | ====================== | ====================== | ========================= | ======================= | ============================= | ============================= | =========================== | =========================== | 
| 4        | Davenport WB     | I-80     | 300       | 2001       | 46                   | 4             | 20            | Yes                | Yes                 | Yes                        | Yes                            | Yes               | Yes               | Yes                | Yes | Yes                  |                 | Yes              | Yes   | 20                        | 210                 | ? 200%           | Rest Area Building in Second Half of Design Life | 960          | July                     | 2016                    | 960                          | 699682                | 699682                | 22700                     | 5540                            | 5540                              | 34725                       | 9030                               | 0.5297356829999999572322622043429873883724212646484375   | 0.5297356829999999572322622043429873883724212646484375   | 9    | 826D63     | 300 I-80 West Bound, Bettendorf IA | Davenport     | 5633325727 | 550714     | 4900       | 23       | 5                       | 1                                       | 3                              | 4                               | 190                                    | Highly     | YES    | Wilton WB              |                        | Great Sauk Trail, IL - WB |                         | 30                            |                               | 57                          |                             | 
| 6        | Wilton WB        | I-80     | 270       | 1999       | 40                   | 2             | 15            | Yes                | Yes                 | Yes                        | Yes                            | Yes               | Yes               | Yes                | Yes | Yes                  | Yes             | Yes              | Yes   | 15                        | 140                 | 100-149%         | Rest Area Building in Second Half of Design Life | 924          | July                     | 2016                    | 924                          | 418045                | 418045                | 16650                     | 5830                            | 5830                              | 29500                       | 10920                              | 0.77177177200000002255109166071633808314800262451171875  | 0.77177177200000002255109166071633808314800262451171875  | 16   | 166T63     | 1450 I-80 West Bound, Wilton IA    | Wilton        | 5637323145 | 550704     | 4900       | 33       | 3                       | 2                                       | 4                              | 9                               | 196                                    | Highly     | YES    | Tiffin WB              |                        | Davenport WB              |                         | 33                            |                               | 30                          |                             | 
| 7        | Wilton EB        | I-80     | 270       | 2002       | 36                   | 2             | 16            | Yes                | Yes                 | Yes                        | Yes                            | Yes               | Yes               | Yes                | Yes | Yes                  | Yes             | Yes              | Yes   | 16                        | 125                 | 100-149%         | Rest Area Building in Second Half of Design Life | 853          | July                     | 2016                    | 853                          | 657818                | 657818                | 16650                     | 5830                            | 5830                              | 29500                       | 10920                              | 0.77177177200000002255109166071633808314800262451171875  | 0.77177177200000002255109166071633808314800262451171875  | 15   | 166T61     | 1453 I-80 East Bound, Wilton IA    | Wilton        | 5637323145 | 550703     | 4900       | 32       | 3                       | 2                                       | 4                              | 9                               | 196                                    | None       | YES    | Davenport EB           |                        | Tiffin EB                 |                         | 30                            |                               | 33                          |                             | 
| 10       | Tiffin WB        | I-80     | 237       | 2001       | 77                   | 6             | 23            | Yes                | Yes                 | Yes                        | Yes                            | Yes               | Yes               | Yes                | Yes | Yes                  | Yes             | Yes              | Yes   | 23                        | 148                 | 100-149%         | Rest Area Building in Second Half of Design Life | 691          | July                     | 2016                    | 691                          | 694051                | 694051                | 17400                     | 4960                            | 4960                              | 38195                       | 11840                              | 1.19511494300000009616269380785524845123291015625        | 1.19511494300000009616269380785524845123291015625        | 28   | 526T67     | 2520 I-80 West Bound, Tiffin IA    | Tiffin        | 3196452432 | 550710     | 4900       | 57       | 0                       | 5                                       | 0                              | 6                               | 4                                      | None       | YES    | Victor WB              |                        | Wilton WB                 |                         | 29                            |                               | 33                          |                             | 
| 15       | Grinnell EB      | I-80     | 180       | 1999       | 30                   | 2             | 25            | Yes                | Yes                 | Yes                        | Yes                            | Yes               | Yes               | Yes                | Yes | Yes                  | Yes             | Yes              | Yes   | 25                        | 108                 | 100-149%         | Rest Area Building in Second Half of Design Life | 822          | July                     | 2016                    | 822                          | 601273                | 601273                | 13900                     | 4660                            | 4660                              | 20775                       | 7270                               | 0.494604317000000015536187447651172988116741180419921875 | 0.494604317000000015536187447651172988116741180419921875 | 26   | 506G61     | 180 I-80 East Bound, Grinnell IA   | Grinnell      | 6412366322 | 550707     | 4900       | 53       | 2                       | 1                                       | 1                              | 5                               | 38                                     | None       | YES    | Victor EB              |                        | Mitchellville EB          |                         | 28                            |                               | 33                          |                             | 
| 17       | Northwood NB/SB  | I-35     | 214       | 1998       | 95                   | 5             | 34            | Yes                | Yes                 | Yes                        | Yes                            | Yes               | Yes               | Yes                | Yes | Yes                  | Yes             | Yes              | Yes   | 34                        | 103                 | 100-149%         | Rest Area Building in Second Half of Design Life | 963          | July                     | 2016                    | 963                          | 701364                | 701364                | 9650                      | 6210                            | 6210                              | 14475                       | 9900                               | 0.5                                                      | 0.5                                                      | 14   | 986N21     | 4705 Wheelerwood Rd, Northwood IA  | Northwood     | 6413243184 | 550739     | 4248       | 31       | 20                      | 0                                       | 0                              | 4                               | 29                                     | Highly     | YES    | Albert Lea, MN ? NB    | Dows NB/SB             | Dows NB/SB                | Straight River, MN - SB | 5                             | 55                            | 55                          | 39                          | 
| 19       | Mitchellville WB | I-80     | 147       | 2002       | 54                   | 3             | 22            |                    | Yes                 | Yes                        | Yes                            | Yes               | Yes               | Yes                | Yes | Yes                  | Yes             | Yes              | Yes   | 22                        | 150                 | 150-199%         | Rest Area Building in Second Half of Design Life | 983          | July                     | 2016                    | 983                          | 474682                | 474682                | 17350                     | 4790                            | 4790                              | 26375                       | 7910                               | 0.520172910999999960068862492335028946399688720703125    | 0.520172910999999960068862492335028946399688720703125    | 64   | 24         | Mitchellville - Westbound I-80     | Mitchellville | 0          | 550712     | 0          | 0        | 4                       | 2                                       | 6                              | 17                              | 76                                     | None       | YES    | Waukee WB              |                        | Grinnell WB               |                         | 28                            |                               | 33                          |                             | 
| 21       | Dows NB/SB       | I-35     | 159       | 2003       | 95                   | 4             | 50            | Yes                | Yes                 | Yes                        | Yes                            | Yes               | Yes               | Yes                | Yes | Yes                  | Yes             | Yes              | Yes   | 50                        | 72                  | 0-74%            | Rest Area Building in Second Half of Design Life | 607          | July                     | 2016                    | 607                          | 493385                | 493385                | 7650                      | 4670                            | 4670                              | 11250                       | 7310                               | 0.47058823500000002137966248483280651271343231201171875  | 0.47058823500000002137966248483280651271343231201171875  | 44   | 38         | Dows - North/Southbound I-35       | Dows          | 0          | 551609     | 0          | 0        | 0                       | 2                                       | 2                              | 1                               | 58                                     | None       | YES    | Northwood NB/SB        | Story City SB          | Story City NB             | Northwood NB/SB         | 55                            | 40                            | 39                          | 55                          | 
| 30       | Lamoni NB/SB     | I-35     | 7         | 2000       | 31                   | 2             | 16            | Yes                | Yes                 | Yes                        | Yes                            | Yes               | Yes               | Yes                | Yes | Yes                  | Yes             | Yes              | Yes   | 16                        | 131                 | 100-149%         | Rest Area Building in Second Half of Design Life | 808          | July                     | 2016                    | 808                          | 502636                | 502636                | 6500                      | 4640                            | 4640                              | 9165                        | 6910                               | 0.409999999999999975575093458246556110680103302001953125 | 0.409999999999999975575093458246556110680103302001953125 | 23   | 276D63     | 26696 I-35, Davis City IA          | Lamoni        | 6414422555 | 550734     | 6496       | 49       | 3                       | 1                                       | 0                              | 3                               | 19                                     | Moderate   | YES    | Osceola NB             | Eagleville, MO ? SB    | Lathrop, MO - NB          | Osceola SB              | 26                            | 9                             | 87                          | 26                          | 
| 32       | Adair EB         | I-80     | 81        | 2002       | 33                   | 4             | 12            | Yes                | Yes                 | Yes                        | Yes                            | Yes               | Yes               | Yes                | Yes | Yes                  | Yes             | Yes              | Yes   | 12                        | 217                 | ? 200%           | Rest Area Building in Second Half of Design Life | 1065         | July                     | 2016                    | 1065                         | 582168                | 582168                | 10050                     | 3920                            | 3920                              | 14475                       | 5790                               | 0.440298507000000005628947974400944076478481292724609375 | 0.440298507000000005628947974400944076478481292724609375 | 1    | 016A61     | 1720 I-80 East Bound, Casey IA     | Adair         | 6417462502 | 550701     | 4900       | 1        | 2                       | 3                                       | 2                              | 2                               | 0                                      | Highly     | YES    | Waukee EB              |                        | Underwood EB              |                         | 38                            |                               | 62                          |                             | 
```