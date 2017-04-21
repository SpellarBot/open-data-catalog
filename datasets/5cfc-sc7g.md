# Rest Area Aging Infrastructure - Building in First Half of Design Life

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/rest-area-aging-infrastructure-building-in-first-half-of-design-life) |
| Metadata | [Link](https://data.iowa.gov/api/views/5cfc-sc7g) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/5cfc-sc7g/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/5cfc-sc7g/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | 5cfc-sc7g |
| Name | Rest Area Aging Infrastructure - Building in First Half of Design Life |
| Attribution | Iowa DOT, HDR Engineering |
| Category | Transportation & Utilities |
| Tags | asset, classification, rest, area, infrastructure, iowa dot, iowa department of transportation |
| Created | 2016-08-19T20:40:47Z |
| Publication Date | 2016-08-19T20:42:51Z |

## Description

Iowa Department of Transportation statewide rest area data. This layer displays aging rest area infrastructure where a building is in the first half of its design life.

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
| Yes      | series tag     | minimun_distance_downstream_2           | minimun_distance_downstream_2           | text      | text        |
| Yes      | numeric metric | minimun_distance_upstream_1             | minimun_distance_upstream_1             | number    | number      |
| Yes      | series tag     | minimun_distance_upstream_2             | minimun_distance_upstream_2             | text      | text        |
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
series e:5cfc-sc7g d:2012-01-01T00:00:00.000Z t:upstream_rest_area_1="Tiffin - WB" t:inventory_=576C61 t:phone_numb=3198487366 t:corridor=I-380 t:family_restroom_facilities=Yes t:rest_area="Cedar Rapids NB" t:wi_fi=Yes t:picnic_facilities=Yes t:uniqueness=Highly t:handicap_accessible_facilities=Yes t:month_of_data_collection=July t:orig_fid=58 t:car_pickup_trailer=Yes t:truck_perc_group="? 200%" t:rv_dump_station=Yes t:traveler_information=Yes t:vending_machines=Yes t:tdd=Yes t:telephone_services=Yes t:near_city="Cedar Rapids" t:downstream_rest_area_1="Dows NB/SB" t:restroom_facilities=Yes t:age_group="Rest Area Building in First Half of Design Life" t:pet_exercise_area=Yes t:active=YES t:objectid=8 m:approx_number_truck_space=16 m:number_of_spaces_lessthanequal_30miles=41 m:minimun_distance_downstream_1=154 m:mainline_aadt_directional=24950 m:handi_parking=2 m:visitor_estimate_2010=513648 m:mainline_truck_aadt_directional_12=7890 m:truck_percent_utili=231 m:visitor_estimate_2011=513648 m:ukey=29 m:cost_cente=550748 m:mainline_aadt_directional_1=42415 m:square_foo=1020 m:density_of_24h_asl_5to15_miles=11 m:mile_post=13 m:car_parking_nonhandi=26 m:distance_to_nearest_24h=0 m:mainline_truck_aadt_directional=4140 m:density_of_24h_asl_15to30_miles=3 m:mainline_truck_aadt_directional_1=4140 m:mainline_aadt_growth_2010_2035=0.7 m:daily_volume=776 m:truck_parking=16 m:density_of_24h_asl_lessthanequal_5miles=8 m:mainline_aadt_growth_2012_2035=0.7 m:daily_volume_june_equivalent=776 m:minimun_distance_upstream_1=15

series e:5cfc-sc7g d:2010-01-01T00:00:00.000Z t:upstream_rest_area_1="Victor EB" t:truck_perc_group=100-149% t:inventory_=13 t:rv_dump_station=Yes t:traveler_information=Yes t:phone_numb=0 t:corridor=I-80 t:family_restroom_facilities=Yes t:vending_machines=Yes t:rest_area="Tiffin EB" t:tdd=Yes t:near_city=Tiffin t:telephone_services=Yes t:picnic_facilities=Yes t:wi_fi=Yes t:downstream_rest_area_1="Wilton EB" t:age_group="Rest Area Building in First Half of Design Life" t:restroom_facilities=Yes t:uniqueness=Highly t:month_of_data_collection=July t:active=YES t:pet_exercise_area=Yes t:handicap_accessible_facilities=Yes t:objectid=11 t:orig_fid=0 m:approx_number_truck_space=23 m:number_of_spaces_lessthanequal_30miles=4 m:minimun_distance_downstream_1=33 m:mainline_aadt_directional=17400 m:handi_parking=4 m:visitor_estimate_2010=766791 m:mainline_truck_aadt_directional_12=11840 m:truck_percent_utili=100 m:visitor_estimate_2011=766791 m:ukey=65 m:cost_cente=550709 m:mainline_aadt_directional_1=38195 m:square_foo=0 m:density_of_24h_asl_5to15_miles=0 m:mile_post=237 m:car_parking_nonhandi=71 m:distance_to_nearest_24h=0 m:mainline_truck_aadt_directional=4960 m:density_of_24h_asl_15to30_miles=6 m:mainline_truck_aadt_directional_1=4960 m:mainline_aadt_growth_2010_2035=1.195114943 m:daily_volume=833 m:truck_parking=23 m:density_of_24h_asl_lessthanequal_5miles=5 m:mainline_aadt_growth_2012_2035=1.195114943 m:daily_volume_june_equivalent=833 m:minimun_distance_upstream_1=29

series e:5cfc-sc7g d:2016-01-01T00:00:00.000Z t:upstream_rest_area_1="Victor WB" t:truck_perc_group=100-149% t:car_pickup_trailer=Yes t:inventory_=506G63 t:traveler_information=Yes t:phone_numb=6412366582 t:corridor=I-80 t:family_restroom_facilities=Yes t:vending_machines=Yes t:rest_area="Grinnell WB" t:tdd=Yes t:near_city=Grinnell t:telephone_services=Yes t:picnic_facilities=Yes t:wi_fi=Yes t:downstream_rest_area_1="Mitchellville WB" t:age_group="Rest Area Building in First Half of Design Life" t:restroom_facilities=Yes t:uniqueness=None t:month_of_data_collection=July t:active=YES t:pet_exercise_area=Yes t:handicap_accessible_facilities=Yes t:objectid=14 t:orig_fid=55 m:approx_number_truck_space=10 m:number_of_spaces_lessthanequal_30miles=47 m:minimun_distance_downstream_1=33 m:mainline_aadt_directional=13900 m:handi_parking=2 m:visitor_estimate_2010=361364 m:mainline_truck_aadt_directional_12=7270 m:truck_percent_utili=140 m:visitor_estimate_2011=361364 m:ukey=27 m:cost_cente=550708 m:mainline_aadt_directional_1=20775 m:square_foo=1020 m:density_of_24h_asl_5to15_miles=1 m:mile_post=180 m:car_parking_nonhandi=23 m:distance_to_nearest_24h=2 m:mainline_truck_aadt_directional=4660 m:density_of_24h_asl_15to30_miles=5 m:mainline_truck_aadt_directional_1=4660 m:mainline_aadt_growth_2010_2035=0.494604317 m:daily_volume=747 m:truck_parking=10 m:density_of_24h_asl_lessthanequal_5miles=1 m:mainline_aadt_growth_2012_2035=0.494604317 m:daily_volume_june_equivalent=747 m:minimun_distance_upstream_1=28
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

metric m:minimun_distance_upstream_1 p:integer l:minimun_distance_upstream_1 d:minimun_distance_upstream_1 t:dataTypeName=number

entity e:5cfc-sc7g l:"Rest Area Aging Infrastructure - Building in First Half of Design Life" t:attribution="Iowa DOT, HDR Engineering" t:url=https://data.iowa.gov/api/views/5cfc-sc7g

property e:5cfc-sc7g t:meta.view v:id=5cfc-sc7g v:category="Transportation & Utilities" v:averageRating=0 v:name="Rest Area Aging Infrastructure - Building in First Half of Design Life" v:attribution="Iowa DOT, HDR Engineering"

property e:5cfc-sc7g t:meta.view.owner v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:displayName="Iowa Department of Transportation"

property e:5cfc-sc7g t:meta.view.tableauthor v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:roleName=administrator v:displayName="Iowa Department of Transportation"
```

## Top Records

```ls
| objectid | rest_area       | corridor | mile_post | year_built | car_parking_nonhandi | handi_parking | truck_parking | car_pickup_trailer | restroom_facilities | family_restroom_facilities | handicap_accessible_facilities | picnic_facilities | pet_exercise_area | telephone_services | tdd | traveler_information | rv_dump_station | vending_machines | wi_fi | approx_number_truck_space | truck_percent_utili | truck_perc_group | age_group                                       | daily_volume | month_of_data_collection | year_of_data_collection | daily_volume_june_equivalent | visitor_estimate_2010 | visitor_estimate_2011 | mainline_aadt_directional | mainline_truck_aadt_directional | mainline_truck_aadt_directional_1 | mainline_aadt_directional_1 | mainline_truck_aadt_directional_12 | mainline_aadt_growth_2010_2035                           | mainline_aadt_growth_2012_2035                           | ukey | inventory_ | address1                                | near_city    | phone_numb | cost_cente | square_foo | orig_fid | distance_to_nearest_24h | density_of_24h_asl_lessthanequal_5miles | density_of_24h_asl_5to15_miles | density_of_24h_asl_15to30_miles | number_of_spaces_lessthanequal_30miles | uniqueness | active | downstream_rest_area_1 | downstream_rest_area_2 | upstream_rest_area_1  | upstream_rest_area_2 | minimun_distance_downstream_1 | minimun_distance_downstream_2 | minimun_distance_upstream_1 | minimun_distance_upstream_2 | 
| ======== | =============== | ======== | ========= | ========== | ==================== | ============= | ============= | ================== | =================== | ========================== | ============================== | ================= | ================= | ================== | === | ==================== | =============== | ================ | ===== | ========================= | =================== | ================ | =============================================== | ============ | ======================== | ======================= | ============================ | ===================== | ===================== | ========================= | =============================== | ================================= | =========================== | ================================== | ======================================================== | ======================================================== | ==== | ========== | ======================================= | ============ | ========== | ========== | ========== | ======== | ======================= | ======================================= | ============================== | =============================== | ====================================== | ========== | ====== | ====================== | ====================== | ===================== | ==================== | ============================= | ============================= | =========================== | =========================== | 
| 8        | Cedar Rapids NB | I-380    | 13        | 2012       | 26                   | 2             | 16            | Yes                | Yes                 | Yes                        | Yes                            | Yes               | Yes               | Yes                | Yes | Yes                  | Yes             | Yes              | Yes   | 16                        | 231                 | ? 200%           | Rest Area Building in First Half of Design Life | 776          | July                     | 2016                    | 776                          | 513648                | 513648                | 24950                     | 4140                            | 4140                              | 42415                       | 7890                               | 0.6999999999999999555910790149937383830547332763671875   | 0.6999999999999999555910790149937383830547332763671875   | 29   | 576C61     | 6848 I-380 South Bound, Cedar Rapids IA | Cedar Rapids | 3198487366 | 550748     | 1020       | 58       | 0                       | 8                                       | 11                             | 3                               | 41                                     | Highly     | YES    | Dows NB/SB             |                        | Tiffin - WB           |                      | 154                           |                               | 15                          |                             | 
| 11       | Tiffin EB       | I-80     | 237       | 2010       | 71                   | 4             | 23            |                    | Yes                 | Yes                        | Yes                            | Yes               | Yes               | Yes                | Yes | Yes                  | Yes             | Yes              | Yes   | 23                        | 100                 | 100-149%         | Rest Area Building in First Half of Design Life | 833          | July                     | 2016                    | 833                          | 766791                | 766791                | 17400                     | 4960                            | 4960                              | 38195                       | 11840                              | 1.19511494300000009616269380785524845123291015625        | 1.19511494300000009616269380785524845123291015625        | 65   | 13         | Tiffin - Eastbound I-80                 | Tiffin       | 0          | 550709     | 0          | 0        | 0                       | 5                                       | 0                              | 6                               | 4                                      | Highly     | YES    | Wilton EB              |                        | Victor EB             |                      | 33                            |                               | 29                          |                             | 
| 14       | Grinnell WB     | I-80     | 180       | 2016       | 23                   | 2             | 10            | Yes                | Yes                 | Yes                        | Yes                            | Yes               | Yes               | Yes                | Yes | Yes                  |                 | Yes              | Yes   | 10                        | 140                 | 100-149%         | Rest Area Building in First Half of Design Life | 747          | July                     | 2016                    | 747                          | 361364                | 361364                | 13900                     | 4660                            | 4660                              | 20775                       | 7270                               | 0.494604317000000015536187447651172988116741180419921875 | 0.494604317000000015536187447651172988116741180419921875 | 27   | 506G63     | 180 I-80 West Bound, Grinnell IA        | Grinnell     | 6412366582 | 550708     | 1020       | 55       | 2                       | 1                                       | 1                              | 5                               | 47                                     | None       | YES    | Mitchellville WB       |                        | Victor WB             |                      | 33                            |                               | 28                          |                             | 
| 23       | Story City SB   | I-35     | 119       | 2009       | 28                   | 2             | 15            | Yes                | Yes                 | Yes                        | Yes                            | Yes               | Yes               | Yes                | Yes | Yes                  | Yes             | Yes              | Yes   | 15                        | 120                 | 100-149%         | Rest Area Building in First Half of Design Life | 619          | July                     | 2016                    | 619                          | 323727                | 323727                | 13800                     | 3220                            | 3220                              | 22220                       | 5620                               | 0.610144927999999975298806020873598754405975341796875    | 0.610144927999999975298806020873598754405975341796875    | 69   | 30         | Story City - Southbound I-35            | Story City   | 0          | 550719     | 0          | 0        | 5                       | 1                                       | 2                              | 6                               | 30                                     | Highly     | YES    | Ankeny SB              |                        | Dows NB/SB            |                      | 20                            |                               | 40                          |                             | 
| 33       | Adair WB        | I-80     | 80        | 2011       | 38                   | 2             | 12            | Yes                | Yes                 |                            | Yes                            | Yes               | Yes               | Yes                | Yes | Yes                  | Yes             | Yes              | Yes   | 12                        | 333                 | ? 200%           | Rest Area Building in First Half of Design Life | 1012         | July                     | 2016                    | 1012                         | 540455                | 540455                | 10050                     | 3920                            | 3920                              | 14475                       | 5790                               | 0.440298507000000005628947974400944076478481292724609375 | 0.440298507000000005628947974400944076478481292724609375 | 61   | 2          | Adair - Westbound I-80                  | Adair        | 0          | 550702     | 0          | 0        | 3                       | 3                                       | 2                              | 2                               | 0                                      | Highly     | YES    | Underwood WB           |                        | Waukee WB             |                      | 61                            |                               | 39                          |                             | 
| 34       | Underwood EB    | I-80     | 19        | 2007       | 24                   | 2             | 15            | Yes                | Yes                 | Yes                        | Yes                            | Yes               | Yes               | Yes                | Yes | Yes                  | Yes             | Yes              | Yes   | 15                        | 147                 | 100-149%         | Rest Area Building in First Half of Design Life | 749          | July                     | 2016                    | 749                          | 393141                | 393141                | 10550                     | 3600                            | 3600                              | 15825                       | 5710                               | 0.5                                                      | 0.5                                                      | 58   | 26         | Underwood - Eastbound I-80              | Underwood    | 0          | 550729     | 0          | 0        | 4                       | 1                                       | 4                              | 9                               | 150                                    | Highly     | YES    | Adair EB               |                        | Platte River, NE - EB |                      | 62                            |                               | 49                          |                             | 
```