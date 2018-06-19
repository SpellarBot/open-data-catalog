# ENERGY STAR Certified Commercial Ice Machines

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/energy-star-certified-commercial-ice-machines) |
| Metadata | [Link](https://data.energystar.gov/api/views/xsaq-9wt3) |
| Data: JSON | [100 Rows](https://data.energystar.gov/api/views/xsaq-9wt3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.energystar.gov/api/views/xsaq-9wt3/rows.csv?max_rows=100) |
| Host | data.energystar.gov |
| Id | xsaq-9wt3 |
| Name | ENERGY STAR Certified Commercial Ice Machines |
| Category | Active Specifications |
| Tags | commercial ice machines |
| Created | 2013-06-04T20:45:27Z |
| Publication Date | 2016-08-19T14:35:57Z |

## Description

Certified models meet all ENERGY STAR requirements as listed in the Version 2.0 ENERGY STAR Program Requirements for Automatic Commercial Ice Makers that are effective as of February 1, 2013. A detailed listing of key efficiency criteria are available at http://www.energystar.gov/index.cfm?c=comm_ice_machines.pr_crit_comm_ice_machines

## Columns

```ls
| Included | Schema Type    | Field Name                                | Name                                                 | Data Type     | Render Type   |
| ======== | ============== | ========================================= | ==================================================== | ============= | ============= |
| Yes      | series tag     | pd_id                                     | ENERGY STAR Unique ID                                | text          | number        |
| Yes      | series tag     | energy_star_partner                       | ENERGY STAR Partner                                  | text          | text          |
| Yes      | series tag     | brand_name                                | Brand Name                                           | text          | text          |
| Yes      | series tag     | model_name                                | Model Name                                           | text          | text          |
| Yes      | series tag     | model_number                              | Model Number                                         | text          | text          |
| Yes      | series tag     | additional_model_information              | Additional Model Information                         | text          | text          |
| Yes      | series tag     | product_type                              | Equipment Type                                       | text          | text          |
| Yes      | series tag     | ice_type                                  | Ice Type                                             | text          | text          |
| Yes      | numeric metric | harvest_rate_lbs_ice_day                  | Harvest Rate (lbs ice/day)                           | number        | number        |
| Yes      | numeric metric | measured_energy_use_kwh_100_lbs_ice       | Measured Energy Use (kWh/100 lbs ice)                | number        | number        |
| Yes      | numeric metric | adjusted_energy_use_kwh_100_lbs_ice       | Adjusted Energy Use for Continuous (kWh/100 lbs ice) | number        | number        |
| Yes      | numeric metric | potable_water_use_gal_100_lbs_ice         | Potable Water Use (gallons/100 lbs ice)              | number        | number        |
| Yes      | numeric metric | ice_hardness_factor                       | Ice Hardness Factor                                  | number        | number        |
| Yes      | series tag     | condenser_unit_model_number_if_applicable | Condenser Unit Model Number (if applicable)          | text          | text          |
| Yes      | time           | date_available_on_market                  | Date Available on Market                             | calendar_date | calendar_date |
| No       |                | date_qualified                            | Date Qualified                                       | calendar_date | calendar_date |
| Yes      | series tag     | markets                                   | Markets                                              | text          | text          |
| Yes      | series tag     | energy_star_model_identifier              | CB Model Identifier                                  | text          | text          |
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
series e:xsaq-9wt3 d:2013-04-01T00:00:00.000Z t:energy_star_partner="Follett Corporation" t:additional_model_information="HCD1000N,HCD1000NBS,; HCD1000N,HCD1000NHS,; HCD1000N,HCD1000NHT,; HCD1000N,HCD1000NJS,; HCD1000N,HCD1000NMS,; HCD1000N,HCD1000NVS,; HCD1000N,HMD1000NBS,; HCD1000N,HMD1000NBT,; HCD1000N,HMD1000NHS,; HCD1000N,HMD1000NHT,; HCD1000N,HMD1000NJS,; HCD1000N,HMD1000NMS,; HCD1000N,HMD1000NVS," t:model_number=HCD1000NBT t:markets="United States" t:condenser_unit_model_number_if_applicable=AJA7490ZXDHN t:energy_star_model_identifier="ES_1045828_HCD1000NBT, HCD1000NBS, HCD1000NVS, HCD1000NHT, HCD1000NHS, HCD1000NJS, HCD1000NMS, HMD1000NBT, HMD1000NBS, HMD1000NVS, HMD1000NHT, HMD1000NHS, HMD1000NJS, HMD1000NMS_01112013111029_5801507" t:product_type="Remote Condensing Unit" t:ice_type=Continuous t:brand_name=Follett t:model_name=HCD1000N t:pd_id=2168550 m:measured_energy_use_kwh_100_lbs_ice=5.2 m:potable_water_use_gal_100_lbs_ice=12 m:ice_hardness_factor=88.1 m:harvest_rate_lbs_ice_day=737 m:adjusted_energy_use_kwh_100_lbs_ice=5.64

series e:xsaq-9wt3 d:2012-11-01T00:00:00.000Z t:energy_star_partner="Follett Corporation" t:additional_model_information="HCC1400A,HCC1400ABS,; HCC1400A,HCC1400AHS,; HCC1400A,HCC1400AHT,; HCC1400A,HCC1400AJS,; HCC1400A,HCC1400AMS,; HCC1400A,HCC1400AVS,; HCC1400A,HMC1400ABS,; HCC1400A,HMC1400ABT,; HCC1400A,HMC1400AHS,; HCC1400A,HMC1400AHT,; HCC1400A,HMC1400AJS,; HCC1400A,HMC1400AMS,; HCC1400A,HMC1400AVS," t:model_number=HCC1400ABT t:markets="United States" t:condenser_unit_model_number_if_applicable=NA t:energy_star_model_identifier="ES_1045828_HCC1400ABT, HCC1400ABS, HCC1400AVS, HCC1400AHT, HCC1400AHS, HCC1400AJS, HCC1400AMS, HMC1400ABT, HMC1400ABS, HMC1400AVS, HMC1400AHT, HMC1400AHS, HMC1400AJS, HMC1400AMS_01112013111603_6043664" t:product_type="Ice Making Head" t:ice_type=Continuous t:brand_name=Follett t:model_name=HCC1400A t:pd_id=2168605 m:measured_energy_use_kwh_100_lbs_ice=5.46 m:potable_water_use_gal_100_lbs_ice=12 m:ice_hardness_factor=86 m:harvest_rate_lbs_ice_day=897 m:adjusted_energy_use_kwh_100_lbs_ice=6.13

series e:xsaq-9wt3 d:2013-04-01T00:00:00.000Z t:energy_star_partner="Follett Corporation" t:additional_model_information="HCD1400R,HCD1400RBS,; HCD1400R,HCD1400RHS,; HCD1400R,HCD1400RHT,; HCD1400R,HCD1400RJS,; HCD1400R,HCD1400RMS,; HCD1400R,HCD1400RVS,; HCD1400R,HMD1400RBS,; HCD1400R,HMD1400RBT,; HCD1400R,HMD1400RHS,; HCD1400R,HMD1400RHT,; HCD1400R,HMD1400RJS,; HCD1400R,HMD1400RMS,; HCD1400R,HMD1400RVS," t:model_number=HCD1400RBT t:markets="United States" t:condenser_unit_model_number_if_applicable=AWA9517ZXNHN t:energy_star_model_identifier="ES_1045828_HCD1400RBT, HCD1400RBS, HCD1400RVS, HCD1400RHT, HCD1400RHS, HCD1400RJS, HCD1400RMS, HMD1400RBT, HMD1400RBS, HMD1400RVS, HMD1400RHT, HMD1400RHS, HMD1400RJS, HMD1400RMS_01112013112732_3948633" t:product_type="Remote Condensing Unit" t:ice_type=Continuous t:brand_name=Follett t:model_name=HCD1400R t:pd_id=2168606 m:measured_energy_use_kwh_100_lbs_ice=4.46 m:potable_water_use_gal_100_lbs_ice=12 m:ice_hardness_factor=89 m:harvest_rate_lbs_ice_day=1184 m:adjusted_energy_use_kwh_100_lbs_ice=4.87
```

## Meta Commands

```ls
metric m:harvest_rate_lbs_ice_day p:integer l:"Harvest Rate (lbs ice/day)" d:"The gross weight of ice harvested, stated in lb/24 h [kg/24 h], stated in multiples of 1." t:dataTypeName=number

metric m:measured_energy_use_kwh_100_lbs_ice p:float l:"Measured Energy Use (kWh/100 lbs ice)" d:"The measured total energy input rate, stated in kWh/100 lb [kWh/45.0 kg] of ice, stated in multiples of 0.01. For remote condensing (but not remote compressor) automatic commercial ice makers and remote condensing and remote compressor automatic commercial ice makers, total energy consumed shall include the energy use of the ice-making mechanism, the compressor, and the remote condenser or condensing unit." t:dataTypeName=number

metric m:adjusted_energy_use_kwh_100_lbs_ice p:float l:"Adjusted Energy Use for Continuous (kWh/100 lbs ice)" d:"The measured energy use of a continuous type system, multiplied by the ice quality adjustment factor, which is defined in 10 CFR Part 431, and stated in kWh/100 lb [kWh/45.0kg] of ice." t:dataTypeName=number

metric m:potable_water_use_gal_100_lbs_ice p:double l:"Potable Water Use (gallons/100 lbs ice)" d:"The amount of potable water used in making ice, which is equal to the sum of the ice harvested, Dump or Purge Water, and the Harvest Water expressed in gal/100 lb [L/45.0 kg] of ice, stated in multiples of 0.1. Alternatively, the amount of water entering the ice maker per cycle can be measured." t:dataTypeName=number

metric m:ice_hardness_factor p:double l:"Ice Hardness Factor" d:"The latent heat capacity of harvested ice (Btu/lb) divided by 144 (Btu/lb) expressed as a percent. Ice Hardness Factor for batch type machines is assumed to be 100%, but must be tested and reported for continuous type machine qualification." t:dataTypeName=number

entity e:xsaq-9wt3 l:"ENERGY STAR Certified Commercial Ice Machines" t:url=https://data.energystar.gov/api/views/xsaq-9wt3

property e:xsaq-9wt3 t:meta.view v:id=xsaq-9wt3 v:category="Active Specifications" v:averageRating=0 v:name="ENERGY STAR Certified Commercial Ice Machines"

property e:xsaq-9wt3 t:meta.view.owner v:id=guxy-scz5 v:screenName=ESddas v:lastNotificationSeenAt=1491492552 v:displayName=ESddas

property e:xsaq-9wt3 t:meta.view.tableauthor v:id=guxy-scz5 v:screenName=ESddas v:roleName=publisher v:lastNotificationSeenAt=1491492552 v:displayName=ESddas

property e:xsaq-9wt3 t:meta.view.metadata.custom_fields.common_core v:Publisher="U.S. Environmental Protection Agency" v:License=https://edg.epa.gov/EPA_Data_License.html v:Contact_Name="Kathleen Vokes" v:Bureau_Code=020:00 v:Program_Code=020:033
```

## Top Records

```ls
| pd_id   | energy_star_partner | brand_name | model_name | model_number | additional_model_information                                                                                                                                                                                                                                                                                                                                  | product_type           | ice_type   | harvest_rate_lbs_ice_day | measured_energy_use_kwh_100_lbs_ice | adjusted_energy_use_kwh_100_lbs_ice | potable_water_use_gal_100_lbs_ice | ice_hardness_factor | condenser_unit_model_number_if_applicable | date_available_on_market | date_qualified      | markets       | energy_star_model_identifier                                                                                                                                                                             | 
| ======= | =================== | ========== | ========== | ============ | ============================================================================================================================================================================================================================================================================================================================================================= | ====================== | ========== | ======================== | =================================== | =================================== | ================================= | =================== | ========================================= | ======================== | =================== | ============= | ======================================================================================================================================================================================================== | 
| 2168550 | Follett Corporation | Follett    | HCD1000N   | HCD1000NBT   | HCD1000N,HCD1000NBS,; HCD1000N,HCD1000NHS,; HCD1000N,HCD1000NHT,; HCD1000N,HCD1000NJS,; HCD1000N,HCD1000NMS,; HCD1000N,HCD1000NVS,; HCD1000N,HMD1000NBS,; HCD1000N,HMD1000NBT,; HCD1000N,HMD1000NHS,; HCD1000N,HMD1000NHT,; HCD1000N,HMD1000NJS,; HCD1000N,HMD1000NMS,; HCD1000N,HMD1000NVS,                                                                  | Remote Condensing Unit | Continuous | 737                      | 5.2                                 | 5.64                                | 12                                | 88.1                | AJA7490ZXDHN                              | 2013-04-01T00:00:00      | 2013-01-11T00:00:00 | United States | ES_1045828_HCD1000NBT, HCD1000NBS, HCD1000NVS, HCD1000NHT, HCD1000NHS, HCD1000NJS, HCD1000NMS, HMD1000NBT, HMD1000NBS, HMD1000NVS, HMD1000NHT, HMD1000NHS, HMD1000NJS, HMD1000NMS_01112013111029_5801507 | 
| 2168605 | Follett Corporation | Follett    | HCC1400A   | HCC1400ABT   | HCC1400A,HCC1400ABS,; HCC1400A,HCC1400AHS,; HCC1400A,HCC1400AHT,; HCC1400A,HCC1400AJS,; HCC1400A,HCC1400AMS,; HCC1400A,HCC1400AVS,; HCC1400A,HMC1400ABS,; HCC1400A,HMC1400ABT,; HCC1400A,HMC1400AHS,; HCC1400A,HMC1400AHT,; HCC1400A,HMC1400AJS,; HCC1400A,HMC1400AMS,; HCC1400A,HMC1400AVS,                                                                  | Ice Making Head        | Continuous | 897                      | 5.46                                | 6.13                                | 12                                | 86                  | NA                                        | 2012-11-01T00:00:00      | 2013-01-11T00:00:00 | United States | ES_1045828_HCC1400ABT, HCC1400ABS, HCC1400AVS, HCC1400AHT, HCC1400AHS, HCC1400AJS, HCC1400AMS, HMC1400ABT, HMC1400ABS, HMC1400AVS, HMC1400AHT, HMC1400AHS, HMC1400AJS, HMC1400AMS_01112013111603_6043664 | 
| 2168606 | Follett Corporation | Follett    | HCD1400R   | HCD1400RBT   | HCD1400R,HCD1400RBS,; HCD1400R,HCD1400RHS,; HCD1400R,HCD1400RHT,; HCD1400R,HCD1400RJS,; HCD1400R,HCD1400RMS,; HCD1400R,HCD1400RVS,; HCD1400R,HMD1400RBS,; HCD1400R,HMD1400RBT,; HCD1400R,HMD1400RHS,; HCD1400R,HMD1400RHT,; HCD1400R,HMD1400RJS,; HCD1400R,HMD1400RMS,; HCD1400R,HMD1400RVS,                                                                  | Remote Condensing Unit | Continuous | 1184                     | 4.46                                | 4.87                                | 12                                | 89                  | AWA9517ZXNHN                              | 2013-04-01T00:00:00      | 2013-01-11T00:00:00 | United States | ES_1045828_HCD1400RBT, HCD1400RBS, HCD1400RVS, HCD1400RHT, HCD1400RHS, HCD1400RJS, HCD1400RMS, HMD1400RBT, HMD1400RBS, HMD1400RVS, HMD1400RHT, HMD1400RHS, HMD1400RJS, HMD1400RMS_01112013112732_3948633 | 
| 2168607 | Follett Corporation | Follett    | HCD1400N   | HCD1400NBT   | HCD1400N,HCD1400NBS,; HCD1400N,HCD1400NHS,; HCD1400N,HCD1400NHT,; HCD1400N,HCD1400NJS,; HCD1400N,HCD1400NMS,; HCD1400N,HCD1400NVS,; HCD1400N,HMD1400NBS,; HCD1400N,HMD1400NBT,; HCD1400N,HMD1400NHS,; HCD1400N,HMD1400NHT,; HCD1400N,HMD1400NJS,; HCD1400N,HMD1400NMS,; HCD1400N,HMD1400NVS,                                                                  | Remote Condensing Unit | Continuous | 1184                     | 4.46                                | 4.87                                | 12                                | 89                  | AWA9517ZXNHN                              | 2013-04-01T00:00:00      | 2013-01-11T00:00:00 | United States | ES_1045828_HCD1400NBT, HCD1400NBS, HCD1400NVS, HCD1400NHT, HCD1400NHS, HCD1400NJS, HCD1400NMS, HMD1400NBT, HMD1400NBS, HMD1400NVS, HMD1400NHT, HMD1400NHS, HMD1400NJS, HMD1400NMS_01112013113548_7203790 | 
| 2168608 | Follett Corporation | Follett    | HCD1650R   | HCD1650RBT   | HCD1650R,HCD1650RBS,; HCD1650R,HCD1650RHS,; HCD1650R,HCD1650RHT,; HCD1650R,HCD1650RJS,; HCD1650R,HCD1650RMS,; HCD1650R,HCD1650RVS,; HCD1650R,HMD1650RBS,; HCD1650R,HMD1650RBT,; HCD1650R,HMD1650RHS,; HCD1650R,HMD1650RHT,; HCD1650R,HMD1650RJS,; HCD1650R,HMD1650RMS,; HCD1650R,HMD1650RVS,                                                                  | Remote Condensing Unit | Continuous | 1284                     | 4.82                                | 5.24                                | 12                                | 90                  | AVA9522ZXNHN                              | 2012-04-01T00:00:00      | 2013-01-11T00:00:00 | United States | ES_1045828_HCD1650RBT, HCD1650RBS, HCD1650RVS, HCD1650RHT, HCD1650RHS, HCD1650RJS, HCD1650RMS, HMD1650RBT, HMD1650RBS, HMD1650RVS, HMD1650RHT, HMD1650RHS, HMD1650RJS, HMD1650RMS_01112013121032_2018243 | 
| 2178806 | Follett Corporation | Follett    | HCD1650N   | HCD1650NBT   | HCD1650N,HCD1650NBS,; HCD1650N,HCD1650NHS,; HCD1650N,HCD1650NHT,; HCD1650N,HCD1650NJS,; HCD1650N,HCD1650NMS,; HCD1650N,HCD1650NVS,; HCD1650N,HMD1650NBS,; HCD1650N,HMD1650NBT,; HCD1650N,HMD1650NHS,; HCD1650N,HMD1650NHT,; HCD1650N,HMD1650NJS,; HCD1650N,HMD1650NMS,; HCD1650N,HMD1650NVS,                                                                  | Remote Condensing Unit | Continuous | 1284                     | 4.82                                | 5.24                                | 12                                | 90                  | AVA9522ZXNHN                              | 2013-04-01T00:00:00      | 2013-01-11T00:00:00 | United States | ES_1045828_HCD1650NBT_04092013105301_8392297                                                                                                                                                             | 
| 2190917 | Follett Corporation | Follett    | HCD700RBT  | HCD700RBT    | ,HCD700NBS,; ,HCD700NBT,; ,HCD700NHS,; ,HCD700NHT,; ,HCD700NJS,; ,HCD700NMS,; ,HCD700NVS,; ,HCD700RBS,; ,HCD700RHS,; ,HCD700RHT,; ,HCD700RJS,; ,HCD700RMS,; ,HCD700RVS,; ,HMD700NBS,; ,HMD700NBT,; ,HMD700NHS,; ,HMD700NHT,; ,HMD700NJS,; ,HMD700NMS,; ,HMD700NVS,; ,HMD700RBS,; ,HMD700RBT,; ,HMD700RHS,; ,HMD700RHT,; ,HMD700RJS,; ,HMD700RMS,; ,HMD700RVS, | Remote Condensing Unit | Continuous | 566                      | 4.92                                | 5.44                                | 12                                | 88                  | AKA9470ZXDHN                              | 2013-03-01T00:00:00      | 2013-09-06T00:00:00 | United States | ES_1045828_HCD700RBT_09062013135832_7227136                                                                                                                                                              | 
| 2193821 | Follett Corporation | Follett    | HCF1000RBT | HCF1000RBT   | ,HCF1000RBS,; ,HCF1000RHS,; ,HCF1000RHT,; ,HCF1000RJS,; ,HCF1000RMS,; ,HCF1000RVS,; ,HMF1000RBS,; ,HMF1000RBT,; ,HMF1000RHS,; ,HMF1000RHT,; ,HMF1000RJS,; ,HMF1000RMS,; ,HMF1000RVS,                                                                                                                                                                          | Remote Condensing Unit | Continuous | 739                      | 5.25                                | 5.95                                | 12                                | 89                  | AWA9490ZXTHN                              | 2013-01-01T00:00:00      | 2014-11-04T00:00:00 | United States | ES_1045828_HCF1000RBT_10222013141627_3689386                                                                                                                                                             | 
| 2193894 | Follett Corporation | Follett    | HCF1400RBT | HCF1400RBT   | ,HCF1400RBS,; ,HCF1400RHS,; ,HCF1400RHT,; ,HCF1400RJS,; ,HCF1400RMS,; ,HCF1400RVS,; ,HMF1400RBS,; ,HMF1400RBT,; ,HMF1400RHS,; ,HMF1400RHT,; ,HMF1400RJS,; ,HMF1400RMS,; ,HMF1400RVS,                                                                                                                                                                          | Remote Condensing Unit | Continuous | 1195                     | 4.13                                | 4.59                                | 12                                | 88                  | AWA9517ZXTHN                              | 2013-01-01T00:00:00      | 2013-10-22T00:00:00 | United States | ES_1045828_HCF1400RBT_10222013151607_2632257                                                                                                                                                             | 
| 2193895 | Follett Corporation | Follett    | HCF1650RBT | HCF1650RBT   | ,HCF1650RBS,; ,HCF1650RHS,; ,HCF1650RHT,; ,HCF1650RJS,; ,HCF1650RMS,; ,HCF1650RVS,; ,HMF1650RBS,; ,HMF1650RBT,; ,HMF1650RHS,; ,HMF1650RHT,; ,HMF1650RJS,; ,HMF1650RMS,; ,HMF1650RVS,                                                                                                                                                                          | Remote Condensing Unit | Continuous | 1441                     | 3.73                                | 4.14                                | 12                                | 89                  | AVA9522ZXTHN                              | 2013-01-01T00:00:00      | 2013-10-22T00:00:00 | United States | ES_1045828_HCF1650RBT_10282013172720_2692682                                                                                                                                                             | 
```