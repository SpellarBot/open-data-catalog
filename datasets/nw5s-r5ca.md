# ENERGY STAR Certified Commercial Griddles

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/energy-star-certified-commercial-griddles) |
| Metadata | [Link](https://data.energystar.gov/api/views/nw5s-r5ca) |
| Data: JSON | [100 Rows](https://data.energystar.gov/api/views/nw5s-r5ca/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.energystar.gov/api/views/nw5s-r5ca/rows.csv?max_rows=100) |
| Host | data.energystar.gov |
| Id | nw5s-r5ca |
| Name | ENERGY STAR Certified Commercial Griddles |
| Category | Active Specifications |
| Tags | commercial griddles |
| Created | 2013-06-03T20:10:14Z |
| Publication Date | 2016-08-19T14:37:07Z |

## Description

Certified models meet all ENERGY STAR requirements as listed in the Version 1.1 ENERGY STAR Program Requirements for Commercial Griddles that are effective as of May 8, 2009 or January 1, 2011. A detailed listing of key efficiency criteria are available at http://www.energystar.gov/index.cfm?c=griddles.pr_crit_comm_griddles

## Columns

```ls
| Included | Schema Type    | Field Name                               | Name                                                | Data Type     | Render Type   |
| ======== | ============== | ======================================== | =================================================== | ============= | ============= |
| Yes      | series tag     | pd_id                                    | ENERGY STAR Unique ID                               | text          | number        |
| Yes      | series tag     | energy_star_partner                      | ENERGY STAR Partner                                 | text          | text          |
| Yes      | series tag     | brand_name                               | Brand Name                                          | text          | text          |
| Yes      | series tag     | model_name                               | Model Name                                          | text          | text          |
| Yes      | series tag     | model_number                             | Model Number                                        | text          | text          |
| Yes      | series tag     | additional_model_information             | Additional Model Information                        | text          | text          |
| Yes      | series tag     | product_type                             | Type                                                | text          | text          |
| Yes      | series tag     | fuel_type                                | Fuel Type                                           | text          | text          |
| Yes      | series tag     | tested_configuration                     | Tested Configuration                                | text          | text          |
| Yes      | series tag     | griddle_plate_type_description           | Griddle Plate Type Description                      | text          | text          |
| Yes      | numeric metric | width_ft                                 | Width (ft.)                                         | number        | number        |
| Yes      | numeric metric | depth_ft                                 | Depth (ft.)                                         | number        | number        |
| Yes      | numeric metric | cooking_surface_sq_ft                    | Cooking Surface (sq. ft.)                           | number        | number        |
| Yes      | numeric metric | cooking_energy_efficiency                | Cooking Energy Efficiency (%)                       | number        | number        |
| Yes      | numeric metric | production_capacity_lbs_hr               | Production Capacity (lbs/hr)                        | number        | number        |
| Yes      | numeric metric | normalized_idle_energy_rate_btu_h_per_ft | Energy Use (Normalized Idle Energy) (Btu/h/sq. ft.) | number        | number        |
| Yes      | numeric metric | normalized_idle_energy_rate_watts_per_ft | Energy Use (Normalized Idle Energy) (Watts/sq. ft.) | number        | number        |
| Yes      | series tag     | top_platen_type                          | Top Platen Type                                     | text          | text          |
| Yes      | time           | date_available_on_market                 | Date Available on Market                            | calendar_date | calendar_date |
| No       |                | date_qualified                           | Date Qualified                                      | calendar_date | calendar_date |
| Yes      | series tag     | markets                                  | Markets                                             | text          | text          |
| Yes      | series tag     | energy_star_model_identifier             | CB Model Identifier                                 | text          | text          |
```

## Time Field

```ls
Value = date_available_on_market
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = date_qualified
```

## Data Commands

```ls
series e:nw5s-r5ca d:2011-06-01T00:00:00.000Z t:energy_star_partner="MagiKitch'n Inc." t:model_number="MKH48 (Chrome Top)" t:fuel_type=Gas t:markets="United States" t:energy_star_model_identifier="ES_1105798_PITCO FRIALATOR INC (181040) | MKH48 (Chrome Top)_11132012155329_2009083" t:griddle_plate_type_description="Chrome Top/flat finish" t:tested_configuration=Single-Sided t:product_type=Single-Sided t:brand_name=Magikitch'n t:model_name="MKH48 (Chrome Top)" t:pd_id=2123230 m:normalized_idle_energy_rate_btu_h_per_ft=1879 m:width_ft=3 m:production_capacity_lbs_hr=45 m:cooking_surface_sq_ft=6 m:depth_ft=2 m:cooking_energy_efficiency=45.1

series e:nw5s-r5ca d:2007-01-01T00:00:00.000Z t:energy_star_partner="Imperial Commercial Cooking Equipment" t:additional_model_information=",ITG-48-E, ITG-60-E, ITG-72-E," t:model_number=ITG-36-E t:fuel_type=Electric t:markets="United States" t:energy_star_model_identifier=ES_1084100_ITG-36-E_08092013131939_4745984 t:griddle_plate_type_description="stainless steel/chrome" t:tested_configuration=Single-Sided t:product_type=Single-Sided t:brand_name=Imperial t:model_name="No name found" t:pd_id=2187664 m:width_ft=3 m:production_capacity_lbs_hr=30 m:cooking_surface_sq_ft=3 m:normalized_idle_energy_rate_watts_per_ft=210 m:depth_ft=2.5 m:cooking_energy_efficiency=0.77

series e:nw5s-r5ca d:2007-01-01T00:00:00.000Z t:energy_star_partner="Imperial Commercial Cooking Equipment" t:additional_model_information=",ITG-48-E, ITG-60-E, ITG-72-E," t:model_number=ITG-48-E t:fuel_type=Electric t:markets="United States" t:energy_star_model_identifier=ES_1084100_ITG-48-E_08092013131939_4745984 t:griddle_plate_type_description="stainless steel/chrome" t:tested_configuration=Single-Sided t:product_type=Single-Sided t:brand_name=Imperial t:model_name="No name found" t:pd_id=2187665 m:width_ft=4 m:production_capacity_lbs_hr=30 m:cooking_surface_sq_ft=4 m:normalized_idle_energy_rate_watts_per_ft=210 m:depth_ft=2.5 m:cooking_energy_efficiency=0.77
```

## Meta Commands

```ls
metric m:width_ft p:integer l:"Width (ft.)" d:"Designates the width of the griddle in ft. For qualification of a product family, the 3 ft. model within the product family can serve as the representative model. (If product family includes units smaller than 3 ft.; however, each additional unit shall be tested and qualified separately from its product family.)" t:dataTypeName=number

metric m:depth_ft p:float l:"Depth (ft.)" d:"Designates the depth of the griddle in ft." t:dataTypeName=number

metric m:cooking_surface_sq_ft p:double l:"Cooking Surface (sq. ft.)" d:"Represents the surface area of the commercial griddle (width multiplied by the depth)." t:dataTypeName=number

metric m:cooking_energy_efficiency p:double l:"Cooking Energy Efficiency (%)" d:"The ratio of energy absorbed by the food product to the total energy supplied to the griddle during cooking." t:dataTypeName=number

metric m:production_capacity_lbs_hr p:integer l:"Production Capacity (lbs/hr)" d:"The maximum production rate of the griddle while cooking a specified food product in accordance with the heavy-load cooking-energy efficiency test, expressed in pounds per hour. The production rate is the average rate at which the griddle brings a specified food product to a specified final temperature." t:dataTypeName=number

metric m:normalized_idle_energy_rate_btu_h_per_ft p:integer l:"Energy Use (Normalized Idle Energy) (Btu/h/sq. ft.)" d:"For gas griddles, this field expresses the rate of griddle energy consumption while it is maintaining or holding at a stabilized operating condition or temperature. The idle rate is normalized based on the area of the (bottom) cooking surface." t:dataTypeName=number

metric m:normalized_idle_energy_rate_watts_per_ft p:integer l:"Energy Use (Normalized Idle Energy) (Watts/sq. ft.)" d:"For electric griddles, this field expresses the rate of griddle energy consumption while it is maintaining or holding at a stabilized operating condition or temperature. The idle rate is normalized based on the area of the (bottom) cooking surface." t:dataTypeName=number

entity e:nw5s-r5ca l:"ENERGY STAR Certified Commercial Griddles" t:url=https://data.energystar.gov/api/views/nw5s-r5ca

property e:nw5s-r5ca t:meta.view v:id=nw5s-r5ca v:category="Active Specifications" v:averageRating=0 v:name="ENERGY STAR Certified Commercial Griddles"

property e:nw5s-r5ca t:meta.view.owner v:id=guxy-scz5 v:screenName=ESddas v:lastNotificationSeenAt=1491492552 v:displayName=ESddas

property e:nw5s-r5ca t:meta.view.tableauthor v:id=guxy-scz5 v:screenName=ESddas v:roleName=publisher v:lastNotificationSeenAt=1491492552 v:displayName=ESddas

property e:nw5s-r5ca t:meta.view.metadata.custom_fields.common_core v:Publisher="U.S. Environmental Protection Agency" v:License=https://edg.epa.gov/EPA_Data_License.html v:Contact_Name="Kathleen Vokes" v:Bureau_Code=020:00 v:Program_Code=020:033
```

## Top Records

```ls
| pd_id   | energy_star_partner                   | brand_name     | model_name           | model_number       | additional_model_information   | product_type | fuel_type | tested_configuration | griddle_plate_type_description | width_ft | depth_ft | cooking_surface_sq_ft | cooking_energy_efficiency | production_capacity_lbs_hr | normalized_idle_energy_rate_btu_h_per_ft | normalized_idle_energy_rate_watts_per_ft | top_platen_type | date_available_on_market | date_qualified      | markets               | energy_star_model_identifier                                                        | 
| ======= | ===================================== | ============== | ==================== | ================== | ============================== | ============ | ========= | ==================== | ============================== | ======== | ======== | ===================== | ========================= | ========================== | ======================================== | ======================================== | =============== | ======================== | =================== | ===================== | =================================================================================== | 
| 2123230 | MagiKitch'n Inc.                      | Magikitch'n    | MKH48 (Chrome Top)   | MKH48 (Chrome Top) |                                | Single-Sided | Gas       | Single-Sided         | Chrome Top/flat finish         | 3        | 2        | 6                     | 45.1                      | 45                         | 1879                                     |                                          |                 | 2011-06-01T00:00:00      | 2011-05-27T00:00:00 | United States         | ES_1105798_PITCO FRIALATOR INC (181040) | MKH48 (Chrome Top)_11132012155329_2009083 | 
| 2187664 | Imperial Commercial Cooking Equipment | Imperial       | No name found        | ITG-36-E           | ,ITG-48-E, ITG-60-E, ITG-72-E, | Single-Sided | Electric  | Single-Sided         | stainless steel/chrome         | 3        | 2.5      | 3                     | 0.77                      | 30                         |                                          | 210                                      |                 | 2007-01-01T00:00:00      | 2012-10-26T00:00:00 | United States         | ES_1084100_ITG-36-E_08092013131939_4745984                                          | 
| 2187665 | Imperial Commercial Cooking Equipment | Imperial       | No name found        | ITG-48-E           | ,ITG-48-E, ITG-60-E, ITG-72-E, | Single-Sided | Electric  | Single-Sided         | stainless steel/chrome         | 4        | 2.5      | 4                     | 0.77                      | 30                         |                                          | 210                                      |                 | 2007-01-01T00:00:00      | 2012-10-26T00:00:00 | United States         | ES_1084100_ITG-48-E_08092013131939_4745984                                          | 
| 2187666 | Imperial Commercial Cooking Equipment | Imperial       | No name found        | ITG-60-E           | ,ITG-48-E, ITG-60-E, ITG-72-E, | Single-Sided | Electric  | Single-Sided         | stainless steel/chrome         | 5        | 2.5      | 5                     | 0.77                      | 30                         |                                          | 210                                      |                 | 2007-01-01T00:00:00      | 2012-10-26T00:00:00 | United States         | ES_1084100_ITG-60-E_08092013131939_4745984                                          | 
| 2187667 | Imperial Commercial Cooking Equipment | Imperial       | No name found        | ITG-72-E           | ,ITG-48-E, ITG-60-E, ITG-72-E, | Single-Sided | Electric  | Single-Sided         | stainless steel/chrome         | 6        | 2.5      | 6                     | 0.77                      | 30                         |                                          | 210                                      |                 | 2007-01-01T00:00:00      | 2012-10-26T00:00:00 | United States         | ES_1084100_ITG-72-E_08092013131939_4745984                                          | 
| 2210186 | Taylor Company                        | Taylor Company | Electric Griddle     | L812-23            |                                | Double-Sided | Electric  | Double-Sided         | Steel T-1                      | 3        | 2        | 6                     | 84                        | 50                         | 0                                        | 0                                        |                 | 2013-11-14T00:00:00      | 2014-05-02T00:00:00 | United States, Canada | ES_1084409_L812-23_05082014143530_1000092                                           | 
| 2210187 | Taylor Company                        | Taylor Company | Electric Griddle     | L812-28            |                                | Double-Sided | Electric  | Double-Sided         | Steel T-1                      | 3        | 2        | 6                     | 84                        | 50                         | 0                                        | 0                                        |                 | 2013-03-20T00:00:00      | 2014-05-02T00:00:00 | United States, Canada | ES_1084409_L812-28_05082014143530_1000093                                           | 
| 2210188 | Taylor Company                        | Taylor Company | Gas/Electric Griddle | L811-22            |                                | Double-Sided | Gas       | Double-Sided         | Steel T-1                      | 3        | 2        | 6                     | 69                        | 99                         | 0                                        | 0                                        |                 | 2014-05-01T00:00:00      | 2014-05-02T00:00:00 | United States, Canada | ES_1084409_L811-22_05082014143530_1000096                                           | 
| 2210189 | Taylor Company                        | Taylor Company | Gas/Electric Griddle | L811-23            |                                | Double-Sided | Gas       | Double-Sided         | Steel T-1                      | 3        | 2        | 6                     | 69                        | 99                         | 0                                        | 0                                        |                 | 2013-01-28T00:00:00      | 2014-05-02T00:00:00 | United States, Canada | ES_1084409_L811-23_05082014143530_1000097                                           | 
| 2210190 | Taylor Company                        | Taylor Company | Gas/Electric Griddle | L811-28            |                                | Double-Sided | Gas       | Double-Sided         | Steel T-1                      | 3        | 2        | 6                     | 69                        | 99                         | 0                                        | 0                                        |                 | 2013-07-22T00:00:00      | 2014-05-02T00:00:00 | United States, Canada | ES_1084409_L811-28_05082014143530_1000098                                           | 
```