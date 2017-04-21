# ENERGY STAR Certified Commercial Dishwashers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/energy-star-certified-commercial-dishwashers) |
| Metadata | [Link](https://data.energystar.gov/api/views/pk8q-dim8) |
| Data: JSON | [100 Rows](https://data.energystar.gov/api/views/pk8q-dim8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.energystar.gov/api/views/pk8q-dim8/rows.csv?max_rows=100) |
| Host | data.energystar.gov |
| Id | pk8q-dim8 |
| Name | ENERGY STAR Certified Commercial Dishwashers |
| Category | Active Specifications |
| Tags | comercial dishwashers |
| Created | 2013-03-18T21:02:31Z |
| Publication Date | 2016-08-19T15:58:46Z |

## Description

Certified models meet all ENERGY STAR requirements as listed in the Version 2.0 ENERGY STAR Program Requirements for Commercial Dishwashers that are effective as of February 1, 2013. A detailed listing of key efficiency criteria are available at http://www.energystar.gov/index.cfm?c=comm_dishwashers.pr_crit_comm_dishwashers

## Columns

```ls
| Included | Schema Type    | Field Name                             | Name                                | Data Type     | Render Type   |
| ======== | ============== | ====================================== | =================================== | ============= | ============= |
| Yes      | series tag     | pd_id                                  | ENERGY STAR Unique ID               | text          | number        |
| Yes      | series tag     | energy_star_partner                    | ENERGY STAR Partner                 | text          | text          |
| Yes      | series tag     | brand_name                             | Brand Name                          | text          | text          |
| Yes      | series tag     | model_name                             | Model Name                          | text          | text          |
| Yes      | series tag     | model_number                           | Model Number                        | text          | text          |
| Yes      | series tag     | additional_model_information           | Additional Model Information        | text          | text          |
| Yes      | series tag     | machine_type                           | Type                                | text          | text          |
| Yes      | series tag     | sanitation_method                      | Sanitation Method                   | text          | text          |
| Yes      | numeric metric | idle_energy_rate_for_low_temp_kw       | Idle Energy Rate for Low Temp (kW)  | number        | number        |
| Yes      | numeric metric | idle_energy_rate_for_high_temp_kw      | Idle Energy Rate for High Temp (kW) | number        | number        |
| Yes      | numeric metric | water_use_gallons_per_rack_gpr         | Water Use (gallons/rack)            | number        | number        |
| Yes      | numeric metric | water_use_gallons_per_hour_gph         | Water Use (gallons/hr)              | number        | number        |
| Yes      | numeric metric | water_use_gallons_per_square_foot_gpsf | Water Use (gallons/sq. ft.)         | number        | number        |
| Yes      | time           | date_available_on_market               | Date Available on Market            | calendar_date | calendar_date |
| No       |                | date_qualified                         | Date Certified                      | calendar_date | calendar_date |
| Yes      | series tag     | markets                                | Markets                             | text          | text          |
| Yes      | series tag     | energy_star_model_identifier           | CB Model Identifier                 | text          | text          |
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
series e:pk8q-dim8 d:2010-11-24T00:00:00.000Z t:energy_star_partner="American Dish Service" t:model_number=5AGES t:machine_type="Stationary Single Tank Door" t:sanitation_method="Chemical Sanitizing (Low Temp) Machine" t:markets="United States, Canada" t:energy_star_model_identifier=ES_1027466_5AGES_01312013094134_1000211 t:brand_name=ADS t:model_name=5AGES t:pd_id=2171015 m:water_use_gallons_per_rack_gpr=0.89

series e:pk8q-dim8 d:2013-01-01T00:00:00.000Z t:energy_star_partner="American Dish Service" t:model_number=AF-ES t:machine_type="Stationary Single Tank Door" t:sanitation_method="Chemical Sanitizing (Low Temp) Machine" t:markets="United States" t:energy_star_model_identifier=ES_1027466_AF-ES_03122013170123_1000316 t:brand_name=ADS t:model_name=AF-ES t:pd_id=2175125 m:water_use_gallons_per_rack_gpr=0.93

series e:pk8q-dim8 d:2013-01-01T00:00:00.000Z t:energy_star_partner="American Dish Service" t:model_number=AFC-ES t:machine_type="Stationary Single Tank Door" t:sanitation_method="Chemical Sanitizing (Low Temp) Machine" t:markets="United States" t:energy_star_model_identifier=ES_1027466_AFC-ES_03122013170123_1000317 t:brand_name=ADS t:model_name=AFC-ES t:pd_id=2175126 m:water_use_gallons_per_rack_gpr=0.93
```

## Meta Commands

```ls
metric m:idle_energy_rate_for_low_temp_kw p:float l:"Idle Energy Rate for Low Temp (kW)" d:"For all dishwasher types, the dishwasher is considered ""in idle mode"" when it is not actively running but is still powered on and ready to wash dishes at the required temperature. The idle energy rate is the rate of energy consumed by the dishwasher while ?holding? or maintaining wash tank water at the thermostat(s) set point during the time period specified in the ENERGY STAR Test Method for Commercial Dishwashers." t:dataTypeName=number

metric m:idle_energy_rate_for_high_temp_kw p:float l:"Idle Energy Rate for High Temp (kW)" d:"For all dishwasher types, the dishwasher is considered ""in idle mode"" when it is not actively running but is still powered on and ready to wash dishes at the required temperature. The idle energy rate is the rate of energy consumed by the dishwasher while ?holding? or maintaining wash tank water at the thermostat(s) set point during the time period specified in the ENERGY STAR Test Method for Commercial Dishwashers." t:dataTypeName=number

metric m:water_use_gallons_per_rack_gpr p:float l:"Water Use (gallons/rack)" d:"Metric that represents the amount of water, in gallons, that is consumed while rinsing and sanitizing one rack of dishware. This water consumption metric is used to qualify under counter, single tank door, pot, pan, and utensil, single tank rack conveyor, and multiple tank rack conveyor machines. GPR is specified in the ENERGY STAR Test Method for Commercial Dishwashers." t:dataTypeName=number

metric m:water_use_gallons_per_hour_gph p:float l:"Water Use (gallons/hr)" d:"Metric that represents the amount of water, in gallons, that is consumed while rinsing and sanitizing dishware in one hour by the dishwashing machine. This water consumption metric is used for single tank flight type and multiple tank flight type machines. GPH is specified in the ENERGY STAR Test Method for Commercial Dishwashers." t:dataTypeName=number

metric m:water_use_gallons_per_square_foot_gpsf p:float l:"Water Use (gallons/sq. ft.)" d:"Metric that represents the amount of water, in gallons, that is consumed per one square foot of rack area while rinsing and sanitizing dishware. This water consumption metric is used for pot, pan, and utensil machines. GPSF is specified in the ENERGY STAR Test Method for Commercial Dishwashers." t:dataTypeName=number

entity e:pk8q-dim8 l:"ENERGY STAR Certified Commercial Dishwashers" t:url=https://data.energystar.gov/api/views/pk8q-dim8

property e:pk8q-dim8 t:meta.view v:id=pk8q-dim8 v:category="Active Specifications" v:averageRating=0 v:name="ENERGY STAR Certified Commercial Dishwashers"

property e:pk8q-dim8 t:meta.view.owner v:id=guxy-scz5 v:screenName=ESddas v:lastNotificationSeenAt=1491492552 v:displayName=ESddas

property e:pk8q-dim8 t:meta.view.tableauthor v:id=guxy-scz5 v:screenName=ESddas v:roleName=publisher v:lastNotificationSeenAt=1491492552 v:displayName=ESddas

property e:pk8q-dim8 t:meta.view.metadata.custom_fields.common_core v:Publisher="U.S. Environmental Protection Agency" v:License=https://edg.epa.gov/EPA_Data_License.html v:Contact_Name="Kathleen Vokes" v:Bureau_Code=020:00 v:Program_Code=020:033
```

## Top Records

```ls
| pd_id   | energy_star_partner   | brand_name | model_name | model_number | additional_model_information | machine_type                | sanitation_method                      | idle_energy_rate_for_low_temp_kw | idle_energy_rate_for_high_temp_kw | water_use_gallons_per_rack_gpr | water_use_gallons_per_hour_gph | water_use_gallons_per_square_foot_gpsf | date_available_on_market | date_qualified      | markets               | energy_star_model_identifier             | 
| ======= | ===================== | ========== | ========== | ============ | ============================ | =========================== | ====================================== | ================================ | ================================= | ============================== | ============================== | ====================================== | ======================== | =================== | ===================== | ======================================== | 
| 2171015 | American Dish Service | ADS        | 5AGES      | 5AGES        |                              | Stationary Single Tank Door | Chemical Sanitizing (Low Temp) Machine |                                  |                                   | 0.89                           |                                |                                        | 2010-11-24T00:00:00      | 2011-02-28T00:00:00 | United States, Canada | ES_1027466_5AGES_01312013094134_1000211  | 
| 2175125 | American Dish Service | ADS        | AF-ES      | AF-ES        |                              | Stationary Single Tank Door | Chemical Sanitizing (Low Temp) Machine |                                  |                                   | 0.93                           |                                |                                        | 2013-01-01T00:00:00      | 2013-02-25T00:00:00 | United States         | ES_1027466_AF-ES_03122013170123_1000316  | 
| 2175126 | American Dish Service | ADS        | AFC-ES     | AFC-ES       |                              | Stationary Single Tank Door | Chemical Sanitizing (Low Temp) Machine |                                  |                                   | 0.93                           |                                |                                        | 2013-01-01T00:00:00      | 2013-02-25T00:00:00 | United States         | ES_1027466_AFC-ES_03122013170123_1000317 | 
| 2175127 | American Dish Service | ADS        | ADC-44     | ADC-44       |                              | Multiple Tank Rack Conveyor | Dual Sanitizing Machine                | 0.72                             | 1.65                              | 0.53                           |                                |                                        | 2013-01-01T00:00:00      | 2013-03-07T00:00:00 | United States         | ES_1027466_ADC-44_03122013170123_1000318 | 
| 2175128 | American Dish Service | ADS        | ADC-66     | ADC-66       |                              | Multiple Tank Rack Conveyor | Dual Sanitizing Machine                | 0.72                             | 1.65                              | 0.53                           |                                |                                        | 2013-01-01T00:00:00      | 2013-03-07T00:00:00 | United States         | ES_1027466_ADC-66_03122013170123_1000319 | 
| 2190070 | American Dish Service | ADS        | HT-25      | HT-25        |                              | Stationary Single Tank Door | Dual Sanitizing Machine                | 0.37                             | 0.63                              | 0.65                           |                                |                                        | 2013-07-01T00:00:00      | 2013-08-21T00:00:00 | United States         | ES_1027466_HT-25_09052013141755_1000044  | 
| 2171016 | Auto-Chlor System     | Auto-Chlor | AC         | AC           |                              | Stationary Single Tank Door | Chemical Sanitizing (Low Temp) Machine | 0.22                             |                                   | 1.04                           |                                |                                        | 2012-03-19T00:00:00      | 2012-04-11T00:00:00 | United States, Canada | ES_1027472_AC_01312013094134_1000212     | 
| 2175563 | Auto-Chlor System     | Auto-Chlor | A5         | A5           |                              | Stationary Single Tank Door | Chemical Sanitizing (Low Temp) Machine |                                  |                                   | 1.04                           |                                |                                        | 1993-07-01T00:00:00      | 2013-03-06T00:00:00 | United States, Canada | ES_1027472_A5_03192013101720_1000365     | 
| 2175564 | Auto-Chlor System     | Auto-Chlor | A4V        | A4V          |                              | Stationary Single Tank Door | Chemical Sanitizing (Low Temp) Machine |                                  |                                   | 1.04                           |                                |                                        | 1993-07-01T00:00:00      | 2013-03-06T00:00:00 | United States, Canada | ES_1027472_A4V_03192013101720_1000366    | 
| 2175565 | Auto-Chlor System     | Auto-Chlor | A5V        | A5V          |                              | Stationary Single Tank Door | Chemical Sanitizing (Low Temp) Machine |                                  |                                   | 1.04                           |                                |                                        | 1993-07-01T00:00:00      | 2013-03-06T00:00:00 | United States, Canada | ES_1027472_A5V_03192013101720_1000367    | 
```