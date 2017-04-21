# Rest Area Aging Infrastructure - Building Exceeded Design Life

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/rest-area-aging-infrastructure-building-exceeded-design-life) |
| Metadata | [Link](https://data.iowa.gov/api/views/kyxf-mwrn) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/kyxf-mwrn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/kyxf-mwrn/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | kyxf-mwrn |
| Name | Rest Area Aging Infrastructure - Building Exceeded Design Life |
| Attribution | Iowa DOT, HDR Engineering |
| Category | Transportation & Utilities |
| Tags | asset, classification, rest, area, infrastructure, iowa dot, iowa department of transportation |
| Created | 2016-08-19T20:35:38Z |
| Publication Date | 2016-08-19T20:38:19Z |

## Description

Iowa Department of Transportation statewide rest area data. This layer displays aging rest area infrastructure where a building has exceeded its design life.

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
series e:kyxf-mwrn d:1966-01-01T00:00:00.000Z t:upstream_rest_area_1="Wilton EB" t:truck_perc_group=100-149% t:car_pickup_trailer=Yes t:inventory_=826D61 t:traveler_information=Yes t:phone_numb=5633326377 t:corridor=I-80 t:vending_machines=Yes t:rest_area="Davenport EB" t:tdd=Yes t:near_city=Davenport t:telephone_services=Yes t:picnic_facilities=Yes t:wi_fi=Yes t:downstream_rest_area_1="Mississippi Rapids, IL - EB" t:age_group="Rest Area Building Exceeded Design Life" t:restroom_facilities=Yes t:uniqueness=None t:month_of_data_collection=July t:active=YES t:pet_exercise_area=Yes t:handicap_accessible_facilities=Yes t:objectid=5 t:orig_fid=22 m:approx_number_truck_space=14 m:number_of_spaces_lessthanequal_30miles=190 m:minimun_distance_downstream_1=7 m:mainline_aadt_directional=22700 m:handi_parking=2 m:visitor_estimate_2010=282818 m:mainline_truck_aadt_directional_12=9030 m:truck_percent_utili=100 m:visitor_estimate_2011=282818 m:ukey=8 m:cost_cente=550713 m:mainline_aadt_directional_1=34725 m:square_foo=1020 m:density_of_24h_asl_5to15_miles=3 m:mile_post=300 m:car_parking_nonhandi=39 m:distance_to_nearest_24h=5 m:mainline_truck_aadt_directional=5540 m:density_of_24h_asl_15to30_miles=4 m:mainline_truck_aadt_directional_1=5540 m:mainline_aadt_growth_2010_2035=0.529735683 m:daily_volume=499 m:truck_parking=14 m:density_of_24h_asl_lessthanequal_5miles=1 m:mainline_aadt_growth_2012_2035=0.529735683 m:daily_volume_june_equivalent=499 m:minimun_distance_upstream_1=30

series e:kyxf-mwrn d:1975-01-01T00:00:00.000Z t:upstream_rest_area_1="Dows NB/SB" t:truck_perc_group="? 200%" t:car_pickup_trailer=Yes t:inventory_=16 t:rv_dump_station=Yes t:traveler_information=Yes t:phone_numb=0 t:corridor=I-380 t:vending_machines=Yes t:rest_area="Cedar Rapids SB" t:tdd=Yes t:near_city="Cedar Rapids" t:telephone_services=Yes t:picnic_facilities=Yes t:wi_fi=Yes t:downstream_rest_area_1="Tiffin - WB" t:age_group="Rest Area Building Exceeded Design Life" t:restroom_facilities=Yes t:uniqueness=None t:month_of_data_collection=July t:active=YES t:pet_exercise_area=Yes t:handicap_accessible_facilities=Yes t:objectid=9 t:orig_fid=0 m:approx_number_truck_space=15 m:number_of_spaces_lessthanequal_30miles=41 m:minimun_distance_downstream_1=15 m:mainline_aadt_directional=24950 m:handi_parking=2 m:visitor_estimate_2010=339852 m:mainline_truck_aadt_directional_12=7890 m:truck_percent_utili=227 m:visitor_estimate_2011=339852 m:ukey=66 m:cost_cente=550749 m:mainline_aadt_directional_1=42415 m:square_foo=0 m:density_of_24h_asl_5to15_miles=11 m:mile_post=13 m:car_parking_nonhandi=26 m:distance_to_nearest_24h=0 m:mainline_truck_aadt_directional=4140 m:density_of_24h_asl_15to30_miles=3 m:mainline_truck_aadt_directional_1=4140 m:mainline_aadt_growth_2010_2035=0.7 m:daily_volume=733 m:truck_parking=15 m:density_of_24h_asl_lessthanequal_5miles=8 m:mainline_aadt_growth_2012_2035=0.7 m:daily_volume_june_equivalent=733 m:minimun_distance_upstream_1=154

series e:kyxf-mwrn d:1967-01-01T00:00:00.000Z t:upstream_rest_area_1="Tiffin WB" t:truck_perc_group=100-149% t:car_pickup_trailer=Yes t:inventory_=40 t:rv_dump_station=Yes t:traveler_information=Yes t:phone_numb=0 t:corridor=I-80 t:vending_machines=Yes t:rest_area="Victor WB" t:tdd=Yes t:near_city=Victor t:telephone_services=Yes t:picnic_facilities=Yes t:wi_fi=Yes t:downstream_rest_area_1="Grinnell WB" t:age_group="Rest Area Building Exceeded Design Life" t:restroom_facilities=Yes t:uniqueness=None t:month_of_data_collection=July t:active=YES t:pet_exercise_area=Yes t:handicap_accessible_facilities=Yes t:objectid=12 t:orig_fid=0 m:approx_number_truck_space=19 m:number_of_spaces_lessthanequal_30miles=30 m:minimun_distance_downstream_1=28 m:mainline_aadt_directional=13150 m:handi_parking=3 m:visitor_estimate_2010=386035 m:mainline_truck_aadt_directional_12=7270 m:truck_percent_utili=142 m:visitor_estimate_2011=386035 m:ukey=45 m:cost_cente=556606 m:mainline_aadt_directional_1=19650 m:square_foo=0 m:density_of_24h_asl_5to15_miles=4 m:mile_post=208 m:car_parking_nonhandi=72 m:distance_to_nearest_24h=7 m:mainline_truck_aadt_directional=4600 m:density_of_24h_asl_15to30_miles=2 m:mainline_truck_aadt_directional_1=4600 m:mainline_aadt_growth_2010_2035=0.494296578 m:daily_volume=762 m:truck_parking=19 m:density_of_24h_asl_lessthanequal_5miles=0 m:mainline_aadt_growth_2012_2035=0.494296578 m:daily_volume_june_equivalent=762 m:minimun_distance_upstream_1=29
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

metric m:mainline_aadt_growth_2010_2035 p:float l:Mainline_AADT_Growth_2010_2035 d:Mainline_AADT_Growth_2010_2035 t:dataTypeName=number

metric m:mainline_aadt_growth_2012_2035 p:float l:Mainline_AADT_Growth_2012_2035 d:Mainline_AADT_Growth_2012_2035 t:dataTypeName=number

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

entity e:kyxf-mwrn l:"Rest Area Aging Infrastructure - Building Exceeded Design Life" t:attribution="Iowa DOT, HDR Engineering" t:url=https://data.iowa.gov/api/views/kyxf-mwrn

property e:kyxf-mwrn t:meta.view v:id=kyxf-mwrn v:category="Transportation & Utilities" v:averageRating=0 v:name="Rest Area Aging Infrastructure - Building Exceeded Design Life" v:attribution="Iowa DOT, HDR Engineering"

property e:kyxf-mwrn t:meta.view.owner v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:displayName="Iowa Department of Transportation"

property e:kyxf-mwrn t:meta.view.tableauthor v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:roleName=administrator v:displayName="Iowa Department of Transportation"
```

## Top Records

```ls
| objectid | rest_area        | corridor | mile_post | year_built | car_parking_nonhandi | handi_parking | truck_parking | car_pickup_trailer | restroom_facilities | family_restroom_facilities | handicap_accessible_facilities | picnic_facilities | pet_exercise_area | telephone_services | tdd | traveler_information | rv_dump_station | vending_machines | wi_fi | approx_number_truck_space | truck_percent_utili | truck_perc_group | age_group                               | daily_volume | month_of_data_collection | year_of_data_collection | daily_volume_june_equivalent | visitor_estimate_2010 | visitor_estimate_2011 | mainline_aadt_directional | mainline_truck_aadt_directional | mainline_truck_aadt_directional_1 | mainline_aadt_directional_1 | mainline_truck_aadt_directional_12 | mainline_aadt_growth_2010_2035                           | mainline_aadt_growth_2012_2035                           | ukey | inventory_ | address1                              | near_city     | phone_numb | cost_cente | square_foo | orig_fid | distance_to_nearest_24h | density_of_24h_asl_lessthanequal_5miles | density_of_24h_asl_5to15_miles | density_of_24h_asl_15to30_miles | number_of_spaces_lessthanequal_30miles | uniqueness | active | downstream_rest_area_1      | downstream_rest_area_2 | upstream_rest_area_1 | upstream_rest_area_2 | minimun_distance_downstream_1 | minimun_distance_downstream_2 | minimun_distance_upstream_1 | minimun_distance_upstream_2 | 
| ======== | ================ | ======== | ========= | ========== | ==================== | ============= | ============= | ================== | =================== | ========================== | ============================== | ================= | ================= | ================== | === | ==================== | =============== | ================ | ===== | ========================= | =================== | ================ | ======================================= | ============ | ======================== | ======================= | ============================ | ===================== | ===================== | ========================= | =============================== | ================================= | =========================== | ================================== | ======================================================== | ======================================================== | ==== | ========== | ===================================== | ============= | ========== | ========== | ========== | ======== | ======================= | ======================================= | ============================== | =============================== | ====================================== | ========== | ====== | =========================== | ====================== | ==================== | ==================== | ============================= | ============================= | =========================== | =========================== | 
| 5        | Davenport EB     | I-80     | 300       | 1966       | 39                   | 2             | 14            | Yes                | Yes                 |                            | Yes                            | Yes               | Yes               | Yes                | Yes | Yes                  |                 | Yes              | Yes   | 14                        | 100                 | 100-149%         | Rest Area Building Exceeded Design Life | 499          | July                     | 2016                    | 499                          | 282818                | 282818                | 22700                     | 5540                            | 5540                              | 34725                       | 9030                               | 0.5297356829999999572322622043429873883724212646484375   | 0.5297356829999999572322622043429873883724212646484375   | 8    | 826D61     | 300 I-80 East Bound, Bettendorf IA    | Davenport     | 5633326377 | 550713     | 1020       | 22       | 5                       | 1                                       | 3                              | 4                               | 190                                    | None       | YES    | Mississippi Rapids, IL - EB |                        | Wilton EB            |                      | 7                             |                               | 30                          |                             | 
| 9        | Cedar Rapids SB  | I-380    | 13        | 1975       | 26                   | 2             | 15            | Yes                | Yes                 |                            | Yes                            | Yes               | Yes               | Yes                | Yes | Yes                  | Yes             | Yes              | Yes   | 15                        | 227                 | ? 200%           | Rest Area Building Exceeded Design Life | 733          | July                     | 2016                    | 733                          | 339852                | 339852                | 24950                     | 4140                            | 4140                              | 42415                       | 7890                               | 0.6999999999999999555910790149937383830547332763671875   | 0.6999999999999999555910790149937383830547332763671875   | 66   | 16         | Cedar Rapids - Northbound I-380       | Cedar Rapids  | 0          | 550749     | 0          | 0        | 0                       | 8                                       | 11                             | 3                               | 41                                     | None       | YES    | Tiffin - WB                 |                        | Dows NB/SB           |                      | 15                            |                               | 154                         |                             | 
| 12       | Victor WB        | I-80     | 208       | 1967       | 72                   | 3             | 19            | Yes                | Yes                 |                            | Yes                            | Yes               | Yes               | Yes                | Yes | Yes                  | Yes             | Yes              | Yes   | 19                        | 142                 | 100-149%         | Rest Area Building Exceeded Design Life | 762          | July                     | 2016                    | 762                          | 386035                | 386035                | 13150                     | 4600                            | 4600                              | 19650                       | 7270                               | 0.494296577999999986463564027872052974998950958251953125 | 0.494296577999999986463564027872052974998950958251953125 | 45   | 40         | Victor - Westbound I-80               | Victor        | 0          | 556606     | 0          | 0        | 7                       | 0                                       | 4                              | 2                               | 30                                     | None       | YES    | Grinnell WB                 |                        | Tiffin WB            |                      | 28                            |                               | 29                          |                             | 
| 13       | Victor EB        | I-80     | 208       | 1967       | 87                   | 3             | 22            | Yes                | Yes                 |                            | Yes                            | Yes               | Yes               | Yes                | Yes | Yes                  | Yes             | Yes              | Yes   | 22                        | 77                  | 75-99%           | Rest Area Building Exceeded Design Life | 764          | July                     | 2016                    | 764                          | 401068                | 401068                | 13150                     | 4600                            | 4600                              | 19650                       | 7270                               | 0.494296577999999986463564027872052974998950958251953125 | 0.494296577999999986463564027872052974998950958251953125 | 46   | 39         | Victor - Eastbound I-80               | Victor        | 0          | 556606     | 0          | 0        | 7                       | 0                                       | 4                              | 2                               | 30                                     | None       | YES    | Tiffin EB                   |                        | Grinnell EB          |                      | 29                            |                               | 28                          |                             | 
| 20       | Mitchellville EB | I-80     | 147       | 1966       | 47                   | 2             | 24            | Yes                | Yes                 |                            | Yes                            | Yes               | Yes               | Yes                | Yes | Yes                  | Yes             | Yes              | Yes   | 24                        | 138                 | 100-149%         | Rest Area Building Exceeded Design Life | 749          | July                     | 2016                    | 749                          | 350818                | 350818                | 17350                     | 4790                            | 4790                              | 26375                       | 7910                               | 0.520172910999999960068862492335028946399688720703125    | 0.520172910999999960068862492335028946399688720703125    | 4    | 776M61     | 147 I-80 East Bound, Mitchellville IA | Mitchellville | 5159672162 | 550711     | 1020       | 12       | 4                       | 2                                       | 6                              | 17                              | 67                                     | None       | YES    | Grinnell EB                 |                        | Waukee EB            |                      | 33                            |                               | 28                          |                             | 
| 22       | Story City NB    | I-35     | 120       | 1969       | 27                   | 2             | 16            | Yes                | Yes                 |                            | Yes                            | Yes               | Yes               | Yes                | Yes | Yes                  | Yes             | Yes              | Yes   | 16                        | 94                  | 75-99%           | Rest Area Building Exceeded Design Life | 486          | July                     | 2016                    | 486                          | 233227                | 233227                | 13800                     | 3220                            | 3220                              | 22220                       | 5620                               | 0.610144927999999975298806020873598754405975341796875    | 0.610144927999999975298806020873598754405975341796875    | 10   | 856S63     | I-35 North Bound, Story City IA       | Story City    | 5157332694 | 550720     | 1020       | 25       | 4                       | 1                                       | 2                              | 6                               | 26                                     | None       | YES    | Dows NB/SB                  |                        | Ankeny NB            |                      | 39                            |                               | 21                          |                             | 
| 26       | Osceola SB       | I-35     | 33        | 1971       | 37                   | 2             | 11            | Yes                | Yes                 |                            | Yes                            | Yes               | Yes               | Yes                | Yes | Yes                  | Yes             | Yes              | Yes   | 11                        | 200                 | ? 200%           | Rest Area Building Exceeded Design Life | 634          | July                     | 2016                    | 634                          | 361545                | 361545                | 8500                      | 2540                            | 2540                              | 12325                       | 3930                               | 0.450000000000000011102230246251565404236316680908203125 | 0.450000000000000011102230246251565404236316680908203125 | 18   | 206S61     | 2001 I-35 South Bound, Osceola IA     | Osceola       | 6413422052 | 550731     | 1020       | 40       | 0                       | 5                                       | 1                              | 2                               | 19                                     | None       | YES    | Lamoni NB/SB                |                        | Ankeny SB            |                      | 26                            |                               | 66                          |                             | 
| 27       | Osceola NB       | I-35     | 33        | 1971       | 35                   | 2             | 11            | Yes                | Yes                 |                            | Yes                            | Yes               | Yes               | Yes                | Yes | Yes                  | Yes             | Yes              | Yes   | 11                        | 191                 | 150-199%         | Rest Area Building Exceeded Design Life | 524          | July                     | 2016                    | 524                          | 437864                | 437864                | 8500                      | 2540                            | 2540                              | 12325                       | 3930                               | 0.450000000000000011102230246251565404236316680908203125 | 0.450000000000000011102230246251565404236316680908203125 | 19   | 206S63     | 2050 I-35 North Bound, Osceola IA     | Osceola       | 6413422424 | 550732     | 1020       | 41       | 0                       | 5                                       | 1                              | 2                               | 20                                     | None       | YES    | Ankeny NB                   |                        | Lamoni NB/SB         |                      | 66                            |                               | 26                          |                             | 
| 35       | Underwood WB     | I-80     | 19        | 1969       | 26                   | 2             | 16            | Yes                | Yes                 |                            | Yes                            | Yes               | Yes               | Yes                | Yes | Yes                  | Yes             | Yes              | Yes   | 16                        | 125                 | 100-149%         | Rest Area Building Exceeded Design Life | 771          | July                     | 2016                    | 771                          | 300864                | 300864                | 10550                     | 3600                            | 3600                              | 15825                       | 5710                               | 0.5                                                      | 0.5                                                      | 7    | 786U87     | I-80 West Bound, Underwood IA         | Underwood     | 7125662118 | 550729     | 1020       | 20       | 4                       | 1                                       | 4                              | 9                               | 152                                    | None       | YES    | Melia Hill, NE ? WB         |                        | Adair WB             |                      | 42                            |                               | 61                          |                             | 
| 36       | Loveland EB      | I-680    | 16        | 1970       | 16                   | 2             | 10            | Yes                | Yes                 |                            | Yes                            | Yes               | Yes               | Yes                |     | Yes                  |                 |                  | Yes   | 10                        | 80                  | 75-99%           | Rest Area Building Exceeded Design Life | 189          | July                     | 2016                    | 189                          | 185091                | 185091                | 3000                      | 850                             | 850                               | 3875                        | 1160                               | 0.29166666699999999057268951219157315790653228759765625  | 0.29166666699999999057268951219157315790653228759765625  | 5    | 786L81     | I-680 East Bound, Loveland IA         | Loveland      | 7126423613 | 550723     | 1020       | 16       | 20                      | 0                                       | 0                              | 0                               | 0                                      | None       | YES    | Adair EB                    |                        | Missouri Valley SB   |                      | 67                            |                               | 11                          |                             | 
```