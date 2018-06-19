# ENERGY STAR Certified Roof Products

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/energy-star-certified-roof-products) |
| Metadata | [Link](https://data.energystar.gov/api/views/gp4i-t95q) |
| Data: JSON | [100 Rows](https://data.energystar.gov/api/views/gp4i-t95q/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.energystar.gov/api/views/gp4i-t95q/rows.csv?max_rows=100) |
| Host | data.energystar.gov |
| Id | gp4i-t95q |
| Name | ENERGY STAR Certified Roof Products |
| Category | Active Specifications |
| Tags | roof products |
| Created | 2013-02-27T17:38:14Z |
| Publication Date | 2016-08-19T17:38:54Z |

## Description

Certified models meet all ENERGY STAR requirements as listed in the Version 2.3 ENERGY STAR Program Requirements for Roof Products that are effective as of July 1, 2012 or the Version 3.0 ENERGY STAR Program Requirements for Roof Products that are effective as of July 1, 2017 . A detailed listing of key efficiency criteria are available at http://www.energystar.gov/index.cfm?c=roof_prods.pr_crit_roof_products

## Columns

```ls
| Included | Schema Type    | Field Name                          | Name                                | Data Type     | Render Type   |
| ======== | ============== | =================================== | =================================== | ============= | ============= |
| Yes      | series tag     | pd_id                               | ENERGY STAR Unique ID               | text          | number        |
| Yes      | series tag     | energy_star_partner                 | ENERGY STAR Partner                 | text          | text          |
| Yes      | series tag     | brand_name                          | Brand Name                          | text          | text          |
| Yes      | series tag     | model_name                          | Model Name                          | text          | text          |
| Yes      | series tag     | model_number                        | Model Number                        | text          | text          |
| Yes      | series tag     | additional_model_information        | Additional Model Information        | text          | text          |
| Yes      | series tag     | product_type                        | Product Type                        | text          | text          |
| Yes      | numeric metric | initial_solar_reflectance           | Initial Solar Reflectance           | number        | number        |
| Yes      | numeric metric | solar_reflectance_after_3_years     | Solar Reflectance after 3 years     | number        | number        |
| Yes      | numeric metric | initial_emissivity                  | Initial Emissivity                  | number        | number        |
| Yes      | series tag     | low_slope                           | Low Slope?                          | text          | text          |
| Yes      | series tag     | steep_slope                         | Steep Slope?                        | text          | text          |
| Yes      | series tag     | roof_cleaned_prior_to_3rd_year_test | Roof Cleaned Prior to 3rd Year Test | text          | text          |
| Yes      | series tag     | warranty_period_years               | Warranty Period (yrs)               | text          | text          |
| Yes      | time           | date_available_on_market            | Date Available On Market            | calendar_date | calendar_date |
| No       |                | date_qualified                      | Date Qualified                      | calendar_date | calendar_date |
| Yes      | series tag     | markets                             | Markets                             | text          | text          |
| Yes      | series tag     | energy_star_model_identifier        | CB Model Identifier                 | text          | text          |
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
series e:gp4i-t95q d:2015-01-01T00:00:00.000Z t:energy_star_partner="ACI Buildings Systems" t:steep_slope=Yes t:model_number="Scarlet Red (384A534)" t:warranty_period_years=20 t:low_slope=No t:markets="United States" t:roof_cleaned_prior_to_3rd_year_test=No t:energy_star_model_identifier="ES_1091576_Scarlet Red (384A534)_11232015235949_3189647" t:product_type=Metal t:brand_name="ACI 3000" t:model_name="Scarlet Red (384A534)" t:pd_id=2253211 m:initial_solar_reflectance=0.35 m:solar_reflectance_after_3_years=0.35 m:initial_emissivity=0.83

series e:gp4i-t95q d:2015-01-01T00:00:00.000Z t:energy_star_partner="ACI Buildings Systems" t:steep_slope=Yes t:model_number="Copper Metalic (439RZ1800M)" t:warranty_period_years=20 t:low_slope=No t:markets="United States" t:roof_cleaned_prior_to_3rd_year_test=No t:energy_star_model_identifier="ES_1091576_Copper Metalic (439RZ1800M)_11232015233152_1512969" t:product_type=Metal t:brand_name="ACI 3000" t:model_name="Copper Metalic (439RZ1800M)" t:pd_id=2253233 m:initial_solar_reflectance=0.35 m:solar_reflectance_after_3_years=0.35 m:initial_emissivity=0.75

series e:gp4i-t95q d:2015-01-01T00:00:00.000Z t:energy_star_partner="ACI Buildings Systems" t:steep_slope=Yes t:model_number="Almond (433R593)" t:warranty_period_years=20 t:low_slope=No t:markets="United States" t:roof_cleaned_prior_to_3rd_year_test=No t:energy_star_model_identifier="ES_1105798_ACI BUILDING SYSTEMS INC (24657) | Almond (433R593)_09052012155146_0306026" t:product_type=Metal t:brand_name="ACI 3000" t:model_name="Almond (433R593)" t:pd_id=2253235 m:initial_solar_reflectance=0.55 m:solar_reflectance_after_3_years=0.55 m:initial_emissivity=0.83
```

## Meta Commands

```ls
metric m:initial_solar_reflectance p:float l:"Initial Solar Reflectance" d:"The fraction of direct and diffuse radiation from the sun reflected by a surface expressed as a percent or within the range of 0.00 and 1.00. Typically, the larger the solar reflectance value, the greater the energy savings. Although there are inherent benefits in the use of reflective roofing, before selecting a roofing product based on expected energy savings consumers should explore the expected calculated results that can be found on the Department of Energy's ""Roof Savings Calculator"" website at www.roofcalc.com. Please remember the Energy Savings that can be achieved with reflective roofing is highly dependent on facility design, insulation used, climatic conditions, building location, and building envelope efficiency." t:dataTypeName=number

metric m:solar_reflectance_after_3_years p:float l:"Solar Reflectance after 3 years" d:"The fraction of direct and diffuse radiation from the sun reflected by a surface, weathered for a minimum of three continuous years, expressed as a percent or within the range of 0.00 and 1.00. Typically, the larger the solar reflectance value, the greater the energy savings." t:dataTypeName=number

metric m:initial_emissivity p:float l:"Initial Emissivity" d:"The relative ability of a surface to emit energy by radiation, expressed as a percent or within the range of 0.00 and 1.00. Typically, the larger the emissivity value, the greater the energy savings." t:dataTypeName=number

entity e:gp4i-t95q l:"ENERGY STAR Certified Roof Products" t:url=https://data.energystar.gov/api/views/gp4i-t95q

property e:gp4i-t95q t:meta.view v:id=gp4i-t95q v:category="Active Specifications" v:averageRating=0 v:name="ENERGY STAR Certified Roof Products"

property e:gp4i-t95q t:meta.view.owner v:id=guxy-scz5 v:screenName=ESddas v:lastNotificationSeenAt=1491492552 v:displayName=ESddas

property e:gp4i-t95q t:meta.view.tableauthor v:id=guxy-scz5 v:screenName=ESddas v:roleName=publisher v:lastNotificationSeenAt=1491492552 v:displayName=ESddas

property e:gp4i-t95q t:meta.view.metadata.custom_fields.common_core v:Publisher="U.S. Environmental Protection Agency" v:License=https://edg.epa.gov/EPA_Data_License.html v:Contact_Name="Kathleen Vokes" v:Bureau_Code=020:00 v:Program_Code=020:033
```

## Top Records

```ls
| pd_id   | energy_star_partner            | brand_name           | model_name                  | model_number                  | additional_model_information | product_type | initial_solar_reflectance | solar_reflectance_after_3_years | initial_emissivity | low_slope | steep_slope | roof_cleaned_prior_to_3rd_year_test | warranty_period_years | date_available_on_market | date_qualified      | markets       | energy_star_model_identifier                                                          | 
| ======= | ============================== | ==================== | =========================== | ============================= | ============================ | ============ | ========================= | =============================== | ================== | ========= | =========== | =================================== | ===================== | ======================== | =================== | ============= | ===================================================================================== | 
| 2253211 | ACI Buildings Systems          | ACI 3000             | Scarlet Red (384A534)       | Scarlet Red (384A534)         |                              | Metal        | 0.35                      | 0.35                            | 0.83               | No        | Yes         | No                                  | 20                    | 2015-01-01T00:00:00      | 2015-11-23T00:00:00 | United States | ES_1091576_Scarlet Red (384A534)_11232015235949_3189647                               | 
| 2253233 | ACI Buildings Systems          | ACI 3000             | Copper Metalic (439RZ1800M) | Copper Metalic (439RZ1800M)   |                              | Metal        | 0.35                      | 0.35                            | 0.75               | No        | Yes         | No                                  | 20                    | 2015-01-01T00:00:00      | 2015-11-23T00:00:00 | United States | ES_1091576_Copper Metalic (439RZ1800M)_11232015233152_1512969                         | 
| 2253235 | ACI Buildings Systems          | ACI 3000             | Almond (433R593)            | Almond (433R593)              |                              | Metal        | 0.55                      | 0.55                            | 0.83               | No        | Yes         | No                                  | 20                    | 2015-01-01T00:00:00      | 2015-11-23T00:00:00 | United States | ES_1105798_ACI BUILDING SYSTEMS INC (24657) | Almond (433R593)_09052012155146_0306026 | 
| 2253236 | ACI Buildings Systems          | ACI 3000             | Almond (433R593)            | Almond (433R593)              |                              | Metal        | 0.55                      | 0.55                            | 0.83               | No        | Yes         | No                                  | 20                    | 2015-01-01T00:00:00      | 2015-11-23T00:00:00 | United States | ES_1091576_Almond (433R593)_11242015180428_8268641                                    | 
| 2253237 | ACI Buildings Systems          | ACI 3000             | Brownstone (433R600)        | Brownstone (433R600)          |                              | Metal        | 0.45                      | 0.45                            | 0.83               | No        | Yes         | No                                  | 20                    | 2009-09-23T00:00:00      | 2015-11-23T00:00:00 | United States | ES_1091576_Brownstone (433R600)_11242015180838_8518211                                | 
| 2057074 | Acrymax Technologies, Inc.     | Acrymax              | AF-130                      | AF-130                        |                              | Coating      | 0.85                      | 0.75                            | 0.9                | Yes       | No          | No                                  | 10                    | 1993-01-01T00:00:00      | 2011-04-11T00:00:00 | United States | ES_1020724_AF-130_04112011000000_4960224                                              | 
| 2024203 | Advanced Coating Systems, Inc. | Energy Seal Coatings | Acu-Shield                  | Acu-Shield ES-SH1-05T         |                              | Coating      | 0.89                      | 0.81                            | 0.89               | Yes       | Yes         | No                                  | 10                    | 1994-04-01T00:00:00      | 2011-07-25T00:00:00 | United States | ES_27982_Acu-Shield ES-SH1-05T_07252011000000_6859481                                 | 
| 2024247 | Advanced Coating Systems, Inc. | Energy Seal Coatings | ES-FLH-05T                  | Acu-Flex:70                   |                              | Coating      | 0.84                      | 0.66                            | 0.89               | Yes       | Yes         | No                                  | 10                    | 2011-10-01T00:00:00      | 2011-10-25T00:00:00 | United States | ES_27982_Acu-Flex:70_10252011000000_9929277                                           | 
| 2024612 | Advanced Coating Systems, Inc. | Energy Seal Coatings | Acu-Shield:Ceramic          | Acu-Shield:Ceramic ES-SHC-05T |                              | Coating      | 0.86                      | 0.78                            | 0.89               | Yes       | Yes         | No                                  | 10                    | 1994-04-01T00:00:00      | 2011-07-25T00:00:00 | United States | ES_27982_Acu-Shield:Ceramic ES-SHC-05T_07252011000000_3716231                         | 
| 2024613 | Advanced Coating Systems, Inc. | Energy Seal Coatings | Kool Roof                   | Kool Roof KR-KR-05T           |                              | Coating      | 0.86                      | 0.78                            | 0.89               | Yes       | Yes         | No                                  | 7                     | 1994-04-01T00:00:00      | 2011-07-25T00:00:00 | United States | ES_27982_Kool Roof KR-KR-05T_07252011000000_2301332                                   | 
```