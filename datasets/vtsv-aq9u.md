# ENERGY STAR Certified Commercial Steam Cookers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/energy-star-certified-commercial-steam-cookers) |
| Metadata | [Link](https://data.energystar.gov/api/views/vtsv-aq9u) |
| Data: JSON | [100 Rows](https://data.energystar.gov/api/views/vtsv-aq9u/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.energystar.gov/api/views/vtsv-aq9u/rows.csv?max_rows=100) |
| Host | data.energystar.gov |
| Id | vtsv-aq9u |
| Name | ENERGY STAR Certified Commercial Steam Cookers |
| Category | Active Specifications |
| Tags | commercial steam cookers |
| Created | 2013-06-04T21:38:07Z |
| Publication Date | 2016-08-19T16:18:08Z |

## Description

Certified models meet all ENERGY STAR requirements as listed in the Version 1.2 ENERGY STAR Program Requirements for Commercial Steam Cookers that are effective as of August 1, 2003. A detailed listing of key efficiency criteria are available at  http://www.energystar.gov/index.cfm?c=steamcookers.pr_crit_steamcookers

## Columns

```ls
| Included | Schema Type    | Field Name                             | Name                              | Data Type     | Render Type   |
| ======== | ============== | ====================================== | ================================= | ============= | ============= |
| Yes      | series tag     | pd_id                                  | ENERGY STAR Unique ID             | text          | number        |
| Yes      | series tag     | energy_star_partner                    | ENERGY STAR Partner               | text          | text          |
| Yes      | series tag     | brand_name                             | Brand Name                        | text          | text          |
| Yes      | series tag     | model_name                             | Model Name                        | text          | text          |
| Yes      | series tag     | model_number                           | Model Number                      | text          | text          |
| Yes      | series tag     | additional_model_information           | Additional Model Information      | text          | text          |
| Yes      | series tag     | product_type                           | Product Type                      | text          | text          |
| Yes      | series tag     | method_of_steam_generation             | Method of Steam Generation        | text          | text          |
| Yes      | numeric metric | pan_capacity                           | Pan Capacity                      | number        | number        |
| Yes      | series tag     | primary_fuel_source                    | Primary Fuel Source               | text          | text          |
| Yes      | numeric metric | cooking_energy_efficiency              | Cooking Energy Efficiency (%)     | percent       | percent       |
| Yes      | numeric metric | water_consumption_gallons_per_hour_gph | Water Consumption (gallons/hr)    | number        | number        |
| Yes      | numeric metric | idle_energy_rate_gas_btu_h             | Idle Energy Rate Gas (Btu/hr)     | number        | number        |
| Yes      | numeric metric | idle_energy_rate_electric_watts        | Idle Energy Rate Electric (Watts) | number        | number        |
| Yes      | time           | date_available_on_market               | Date Available on Market          | calendar_date | calendar_date |
| No       |                | date_qualified                         | Date Qualified                    | calendar_date | calendar_date |
| Yes      | series tag     | markets                                | Markets                           | text          | text          |
| Yes      | series tag     | energy_star_model_identifier           | CB Model Identifier               | text          | text          |
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
series e:vtsv-aq9u d:2014-10-21T00:00:00.000Z t:energy_star_partner="Vulcan (A division of ITW Food Equipment Group)" t:model_number=C24EO3 t:primary_fuel_source=Electric t:markets="United States" t:energy_star_model_identifier=ES_1017903_C24EO3_05062015011056_4656371 t:product_type=Pressureless t:method_of_steam_generation=Boilerless t:brand_name=Superior t:model_name=C24EO3 t:pd_id=2238769 m:water_consumption_gallons_per_hour_gph=0.6 m:idle_energy_rate_electric_watts=259 m:pan_capacity=3 m:cooking_energy_efficiency=74

series e:vtsv-aq9u d:2014-10-21T00:00:00.000Z t:energy_star_partner="Vulcan (A division of ITW Food Equipment Group)" t:model_number=C24EO5 t:primary_fuel_source=Electric t:markets="United States" t:energy_star_model_identifier=ES_1017903_C24EO5_05062015011459_4899743 t:product_type=Pressureless t:method_of_steam_generation=Boilerless t:brand_name=Superior t:model_name=C24EO5 t:pd_id=2238770 m:water_consumption_gallons_per_hour_gph=0.7 m:idle_energy_rate_electric_watts=382 m:pan_capacity=5 m:cooking_energy_efficiency=77

series e:vtsv-aq9u d:2015-01-01T00:00:00.000Z t:energy_star_partner="Unified Brands, Inc." t:model_number=XSG-5 t:primary_fuel_source=Gas t:markets="United States, Canada" t:energy_star_model_identifier=ES_1105055_XSG-5_06252015174607_4367823 t:product_type=Pressureless t:method_of_steam_generation=Boilerless t:brand_name=Groen t:model_name=XSG-5 t:pd_id=2242220 m:water_consumption_gallons_per_hour_gph=3 m:pan_capacity=5 m:idle_energy_rate_gas_btu_h=7027 m:cooking_energy_efficiency=49
```

## Meta Commands

```ls
metric m:pan_capacity p:integer l:"Pan Capacity" d:"The maximum number of full-size steam pans the steam cooker can accept in accordance with the heavy-load cooking test." t:dataTypeName=number

metric m:cooking_energy_efficiency p:integer l:"Cooking Energy Efficiency (%)" d:"The quantity of energy input to the food products; expressed as a percentage of the quantity of energy input to the appliance during the heavy-, medium-, and light-load tests." t:dataTypeName=percent

metric m:water_consumption_gallons_per_hour_gph p:float l:"Water Consumption (gallons/hr)" d:"The average water consumption during heavy-load cooking as expressed in gallons per hour (GPH)." t:dataTypeName=number

metric m:idle_energy_rate_gas_btu_h p:integer l:"Idle Energy Rate Gas (Btu/hr)" d:"The rate of appliance energy consumption while it is maintaining or holding at a stabilized operating condition or temperature measured in Btu/h." t:dataTypeName=number

metric m:idle_energy_rate_electric_watts p:double l:"Idle Energy Rate Electric (Watts)" d:"The rate of appliance energy consumption while it is maintaining or holding at a stabilized operating condition or temperature measured in watts." t:dataTypeName=number

entity e:vtsv-aq9u l:"ENERGY STAR Certified Commercial Steam Cookers" t:url=https://data.energystar.gov/api/views/vtsv-aq9u

property e:vtsv-aq9u t:meta.view v:id=vtsv-aq9u v:category="Active Specifications" v:averageRating=0 v:name="ENERGY STAR Certified Commercial Steam Cookers"

property e:vtsv-aq9u t:meta.view.owner v:id=guxy-scz5 v:screenName=ESddas v:lastNotificationSeenAt=1491492552 v:displayName=ESddas

property e:vtsv-aq9u t:meta.view.tableauthor v:id=guxy-scz5 v:screenName=ESddas v:roleName=publisher v:lastNotificationSeenAt=1491492552 v:displayName=ESddas

property e:vtsv-aq9u t:meta.view.metadata.custom_fields.common_core v:Publisher="U.S. Environmental Protection Agency" v:License=https://edg.epa.gov/EPA_Data_License.html v:Contact_Name="Kathleen Vokes" v:Bureau_Code=020:00 v:Program_Code=020:033
```

## Top Records

```ls
| pd_id   | energy_star_partner                             | brand_name | model_name  | model_number | additional_model_information | product_type | method_of_steam_generation | pan_capacity | primary_fuel_source | cooking_energy_efficiency | water_consumption_gallons_per_hour_gph | idle_energy_rate_gas_btu_h | idle_energy_rate_electric_watts | date_available_on_market | date_qualified      | markets               | energy_star_model_identifier                  | 
| ======= | =============================================== | ========== | =========== | ============ | ============================ | ============ | ========================== | ============ | =================== | ========================= | ====================================== | ========================== | =============================== | ======================== | =================== | ===================== | ============================================= | 
| 2238769 | Vulcan (A division of ITW Food Equipment Group) | Superior   | C24EO3      | C24EO3       |                              | Pressureless | Boilerless                 | 3            | Electric            | 74                        | 0.6                                    |                            | 259                             | 2014-10-21T00:00:00      | 2014-10-30T00:00:00 | United States         | ES_1017903_C24EO3_05062015011056_4656371      | 
| 2238770 | Vulcan (A division of ITW Food Equipment Group) | Superior   | C24EO5      | C24EO5       |                              | Pressureless | Boilerless                 | 5            | Electric            | 77                        | 0.7                                    |                            | 382                             | 2014-10-21T00:00:00      | 2014-10-30T00:00:00 | United States         | ES_1017903_C24EO5_05062015011459_4899743      | 
| 2242220 | Unified Brands, Inc.                            | Groen      | XSG-5       | XSG-5        |                              | Pressureless | Boilerless                 | 5            | Gas                 | 49                        | 3                                      | 7027                       |                                 | 2015-01-01T00:00:00      | 2015-06-25T00:00:00 | United States, Canada | ES_1105055_XSG-5_06252015174607_4367823       | 
| 2242221 | Unified Brands, Inc.                            | Groen      | VRC-3E      | VRC-3E       |                              | Pressureless | Boilerless                 | 3            | Electric            | 70                        | 2                                      |                            | 251                             | 2015-01-01T00:00:00      | 2015-06-25T00:00:00 | United States, Canada | ES_1105055_VRC-3E_06252015180324_5404369      | 
| 2242224 | Unified Brands, Inc.                            | Groen      | VRC-6E      | VRC-6E       |                              | Pressureless | Boilerless                 | 6            | Electric            | 76                        | 4.5                                    |                            | 300                             | 2015-01-01T00:00:00      | 2015-06-25T00:00:00 | United States, Canada | ES_1105055_VRC-6E_06252015192911_0551400      | 
| 2242225 | Unified Brands, Inc.                            | Groen      | XS-208-12-3 | XS-208-12-3  |                              | Pressureless | Boilerless                 | 6            | Electric            | 64                        | 3                                      |                            | 200                             | 2015-01-01T00:00:00      | 2015-06-25T00:00:00 | United States, Canada | ES_1105055_XS-208-12-3_06252015200113_2473666 | 
| 2242226 | Unified Brands, Inc.                            | Groen      | XS-208-14-3 | XS-208-14-3  |                              | Pressureless | Boilerless                 | 6            | Electric            | 64                        | 3                                      |                            | 200                             | 2015-01-01T00:00:00      | 2015-06-25T00:00:00 | United States, Canada | ES_1105055_XS-208-14-3_06252015200438_2678869 | 
| 2242227 | Unified Brands, Inc.                            | Groen      | XS-208-18-3 | XS-208-18-3  |                              | Pressureless | Boilerless                 | 6            | Electric            | 64                        | 3                                      |                            | 200                             | 2015-01-01T00:00:00      | 2015-06-25T00:00:00 | United States, Canada | ES_1105055_XS-208-18-3_06252015200340_2620185 | 
| 2242228 | Unified Brands, Inc.                            | Groen      | XS-208-8-1  | XS-208-8-1   |                              | Pressureless | Boilerless                 | 6            | Electric            | 64                        | 3                                      |                            | 200                             | 2015-01-01T00:00:00      | 2015-06-25T00:00:00 | United States, Canada | ES_1105055_XS-208-8-1_06252015200215_2535112  | 
| 2242229 | Unified Brands, Inc.                            | Groen      | XS-208-8-3  | XS-208-8-3   |                              | Pressureless | Boilerless                 | 6            | Electric            | 64                        | 3                                      |                            | 200                             | 2015-01-01T00:00:00      | 2015-06-25T00:00:00 | United States, Canada | ES_1105055_XS-208-8-3_06252015200410_2650307  | 
```