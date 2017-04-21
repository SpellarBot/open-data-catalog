# Green Building Aggregate Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/green-building-aggregate-data) |
| Metadata | [Link](https://data.austintexas.gov/api/views/dpvb-c5fy) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/dpvb-c5fy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/dpvb-c5fy/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | dpvb-c5fy |
| Name | Green Building Aggregate Data |
| Attribution | Austin Energy |
| Category | Utility |
| Tags | green building, sustainability, energy efficiency, energy, environment, community impact, innovation |
| Created | 2016-09-19T13:32:10Z |
| Publication Date | 2017-01-30T15:31:42Z |

## Description

Austin Energy Green Building (AEGB) ratings apply to new construction and major renovation in three markets: Commercial, Multifamily and Single Family. An AEGB rating evaluates the sustainability of participating buildings on a scale of one to five stars (five stars being the best rating) in the areas of energy efficiency, water efficiency, materials, site, indoor environmental quality, community impact and innovation. AEGB updates rating requirements periodically to stay ahead of advancing building codes and to spur best practices in the building industry.  
The table contains unaudited data that represents Green Building ratings contribution to the goals of the Austin Climate Protection Plan to reach 900 MW of peak demand savings by 2025. Beginning in 2014, Green Building commercial and multifamily ratings MW and MWh savings include a portion of the savings attributed to Customer Energy Solution rebates for AEGB rated projects. Blank data cells indicate information not applicable or not tracked.

## Columns

```ls
| Included | Schema Type    | Field Name                                                              | Name                                                           | Data Type     | Render Type   |
| ======== | ============== | ======================================================================= | ============================================================== | ============= | ============= |
| Yes      | series tag     | class                                                                   | Class                                                          | text          | text          |
| Yes      | time           | fiscal_year                                                             | Fiscal Year                                                    | calendar_date | calendar_date |
| Yes      | numeric metric | number_of_projects_aegb_rated                                           | # of Projects Rated                                            | number        | number        |
| Yes      | numeric metric | number_of_projects_leed_reviewed                                        | # of Projects LEED Reviewed                                    | number        | number        |
| Yes      | numeric metric | total_square_footage_aegb_rated_projects                                | Projects (sq.ft.)                                              | number        | number        |
| Yes      | numeric metric | number_of_residential_units_aegb_rated                                  | # of Residential Units                                         | number        | number        |
| Yes      | numeric metric | number_of_smart_housing_units_aegb_rated                                | # of Rated Units in S.M.A.R.T. developments                    | number        | number        |
| Yes      | numeric metric | estimated_energy_savings_mbtu                                           | Energy Savings (MBTU)?                                         | number        | number        |
| Yes      | numeric metric | estimated_demand_savings_kw                                             | Demand Savings (kW)                                            | number        | number        |
| Yes      | numeric metric | estimated_electric_energy_savings_kwh                                   | Electric Savings (MWh)                                         | number        | number        |
| Yes      | numeric metric | estimated_gas_savings_ccf                                               | Gas Savings (CCF)                                              | number        | number        |
| Yes      | numeric metric | indoor_potable_water_reduction_gallons                                  | Indoor Potable Water Reduction (1000 gallons)                  | number        | number        |
| Yes      | numeric metric | irrigation_potable_water_reduction_gallons_month_of_july                | Irrigation Potable Water Reduction (1000 gallons)              | number        | number        |
| Yes      | numeric metric | construction_waste_diverted_from_landfill_tons                          | Construction Waste Diverted from Landfill (tons)               | number        | number        |
| Yes      | numeric metric | number_of_aegb_rated_residential_units_outside_ae_service               | # of Rated Residential Units outside AE Service                | number        | number        |
| Yes      | numeric metric | number_of_aegb_rated_units_in_s_m_a_r_t_developments_outside_ae_service | # of Rated Units in S.M.A.R.T. developments outside AE Service | number        | number        |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:dpvb-c5fy d:2016-01-01T00:00:00.000Z t:class=Commercial m:estimated_electric_energy_savings_kwh=9396.284 m:indoor_potable_water_reduction_gallons=11551.447 m:irrigation_potable_water_reduction_gallons_month_of_july=491 m:number_of_projects_leed_reviewed=2 m:estimated_demand_savings_kw=2677 m:total_square_footage_aegb_rated_projects=3000045 m:number_of_residential_units_aegb_rated=824 m:number_of_projects_aegb_rated=14 m:estimated_gas_savings_ccf=205211 m:estimated_energy_savings_mbtu=59672 m:number_of_smart_housing_units_aegb_rated=125 m:construction_waste_diverted_from_landfill_tons=15756

series e:dpvb-c5fy d:2015-01-01T00:00:00.000Z t:class=Commercial m:estimated_electric_energy_savings_kwh=11782.5 m:indoor_potable_water_reduction_gallons=6822.938 m:irrigation_potable_water_reduction_gallons_month_of_july=3330 m:number_of_projects_leed_reviewed=2 m:estimated_demand_savings_kw=4046 m:total_square_footage_aegb_rated_projects=2938440 m:number_of_residential_units_aegb_rated=358 m:number_of_projects_aegb_rated=18 m:estimated_gas_savings_ccf=119396 m:estimated_energy_savings_mbtu=50023 m:number_of_smart_housing_units_aegb_rated=0 m:construction_waste_diverted_from_landfill_tons=29745

series e:dpvb-c5fy d:2014-01-01T00:00:00.000Z t:class=Commercial m:estimated_electric_energy_savings_kwh=9419.404 m:indoor_potable_water_reduction_gallons=19719.725 m:irrigation_potable_water_reduction_gallons_month_of_july=2270 m:number_of_projects_leed_reviewed=3 m:estimated_demand_savings_kw=3419 m:total_square_footage_aegb_rated_projects=3779462 m:number_of_residential_units_aegb_rated=1618 m:number_of_projects_aegb_rated=19 m:estimated_gas_savings_ccf=75572 m:estimated_energy_savings_mbtu=61898 m:number_of_smart_housing_units_aegb_rated=824 m:construction_waste_diverted_from_landfill_tons=23444
```

## Meta Commands

```ls
metric m:number_of_projects_aegb_rated p:integer l:"# of Projects Rated" t:dataTypeName=number

metric m:number_of_projects_leed_reviewed p:integer l:"# of Projects LEED Reviewed" t:dataTypeName=number

metric m:total_square_footage_aegb_rated_projects p:integer l:"Projects (sq.ft.)" t:dataTypeName=number

metric m:number_of_residential_units_aegb_rated p:integer l:"# of Residential Units" t:dataTypeName=number

metric m:number_of_smart_housing_units_aegb_rated p:integer l:"# of Rated Units in S.M.A.R.T. developments" t:dataTypeName=number

metric m:estimated_energy_savings_mbtu p:integer l:"Energy Savings (MBTU)?" d:"MBTU = millions of British Thermal Units or 1,000,000 BTU" t:dataTypeName=number

metric m:estimated_demand_savings_kw p:integer l:"Demand Savings (kW)" t:dataTypeName=number

metric m:estimated_electric_energy_savings_kwh p:float l:"Electric Savings (MWh)" t:dataTypeName=number

metric m:estimated_gas_savings_ccf p:integer l:"Gas Savings (CCF)" t:dataTypeName=number

metric m:indoor_potable_water_reduction_gallons p:decimal l:"Indoor Potable Water Reduction (1000 gallons)" t:dataTypeName=number

metric m:irrigation_potable_water_reduction_gallons_month_of_july p:integer l:"Irrigation Potable Water Reduction (1000 gallons)" t:dataTypeName=number

metric m:construction_waste_diverted_from_landfill_tons p:integer l:"Construction Waste Diverted from Landfill (tons)" t:dataTypeName=number

metric m:number_of_aegb_rated_residential_units_outside_ae_service p:integer l:"# of Rated Residential Units outside AE Service" t:dataTypeName=number

metric m:number_of_aegb_rated_units_in_s_m_a_r_t_developments_outside_ae_service p:long l:"# of Rated Units in S.M.A.R.T. developments outside AE Service" t:dataTypeName=number

entity e:dpvb-c5fy l:"Green Building Aggregate Data" t:attribution="Austin Energy" t:url=https://data.austintexas.gov/api/views/dpvb-c5fy

property e:dpvb-c5fy t:meta.view v:id=dpvb-c5fy v:category=Utility v:averageRating=0 v:name="Green Building Aggregate Data" v:attribution="Austin Energy"

property e:dpvb-c5fy t:meta.view.license v:name="Public Domain"

property e:dpvb-c5fy t:meta.view.owner v:id=c433-zrb5 v:profileImageUrlMedium=/api/users/c433-zrb5/profile_images/THUMB v:profileImageUrlLarge=/api/users/c433-zrb5/profile_images/LARGE v:screenName="Sarah Lambert" v:profileImageUrlSmall=/api/users/c433-zrb5/profile_images/TINY v:displayName="Sarah Lambert"

property e:dpvb-c5fy t:meta.view.tableauthor v:id=3qbr-w2gj v:screenName="Elaine Lee" v:roleName=editor v:displayName="Elaine Lee"
```

## Top Records

```ls
| class      | fiscal_year         | number_of_projects_aegb_rated | number_of_projects_leed_reviewed | total_square_footage_aegb_rated_projects | number_of_residential_units_aegb_rated | number_of_smart_housing_units_aegb_rated | estimated_energy_savings_mbtu | estimated_demand_savings_kw | estimated_electric_energy_savings_kwh | estimated_gas_savings_ccf | indoor_potable_water_reduction_gallons | irrigation_potable_water_reduction_gallons_month_of_july | construction_waste_diverted_from_landfill_tons | number_of_aegb_rated_residential_units_outside_ae_service | number_of_aegb_rated_units_in_s_m_a_r_t_developments_outside_ae_service | 
| ========== | =================== | ============================= | ================================ | ======================================== | ====================================== | ======================================== | ============================= | =========================== | ===================================== | ========================= | ====================================== | ======================================================== | ============================================== | ========================================================= | ======================================================================= | 
| Commercial | 2016-01-01T00:00:00 | 14                            | 2                                | 3000045                                  | 824                                    | 125                                      | 59672                         | 2677                        | 9396.2839999999997                    | 205211                    | 11551.447                              | 491                                                      | 15756                                          |                                                           |                                                                         | 
| Commercial | 2015-01-01T00:00:00 | 18                            | 2                                | 2938440                                  | 358                                    | 0                                        | 50023                         | 4046                        | 11782.5                               | 119396                    | 6822.9380000000001                     | 3330                                                     | 29745                                          |                                                           |                                                                         | 
| Commercial | 2014-01-01T00:00:00 | 19                            | 3                                | 3779462                                  | 1618                                   | 824                                      | 61898                         | 3419                        | 9419.4040000000005                    | 75572                     | 19719.724999999999                     | 2270                                                     | 23444                                          |                                                           |                                                                         | 
| Commercial | 2013-01-01T00:00:00 | 14                            | 1                                | 2035035                                  | 300                                    | 0                                        | 53580                         | 3019                        | 10427.879999999999                    | 185912                    | 5950.15                                | 1255                                                     | 14192                                          |                                                           |                                                                         | 
| Commercial | 2012-01-01T00:00:00 | 12                            | 0                                | 2091517                                  | 341                                    | 0                                        | 8009                          | 1382                        | 1746.66                               | 24379                     | 4034.43                                | 125                                                      | 10590                                          |                                                           |                                                                         | 
| Commercial | 2011-01-01T00:00:00 | 20                            | 0                                | 1641929                                  | 291                                    | 0                                        | 25703                         | 1714                        | 7503.48                               | 18568                     | 5819.1329999999998                     | 5126                                                     | 11518                                          |                                                           |                                                                         | 
| Commercial | 2010-01-01T00:00:00 | 19                            | 0                                | 2649697                                  | 1225                                   | 433                                      | 15873                         | 1650                        | 5298.8                                | 28682                     | 9217.2999999999993                     | 13024                                                    | 13057                                          |                                                           |                                                                         | 
| Commercial | 2009-01-01T00:00:00 | 30                            | 3                                | 2309470                                  | 1205                                   | 191                                      | 9494                          | 4813                        | 11933.71                              | 175094                    | 17573.026000000002                     | 12947                                                    | 31029                                          |                                                           |                                                                         | 
| Commercial | 2008-01-01T00:00:00 | 28                            | 0                                | 3088208                                  | 988                                    | 0                                        | 14710                         | 4774                        | 13377.47                              | 275855                    | 12838.1                                | 47097                                                    | 64840                                          |                                                           |                                                                         | 
| Commercial | 2007-01-01T00:00:00 | 19                            | 0                                | 632378                                   | 0                                      | 0                                        |                               | 1479                        | 3716.32                               |                           | 2037.4                                 | 3442                                                     | 3327                                           |                                                           |                                                                         | 
```