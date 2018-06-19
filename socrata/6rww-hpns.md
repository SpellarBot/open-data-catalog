# ENERGY STAR Certified Boilers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/energy-star-certified-boilers) |
| Metadata | [Link](https://data.energystar.gov/api/views/6rww-hpns) |
| Data: JSON | [100 Rows](https://data.energystar.gov/api/views/6rww-hpns/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.energystar.gov/api/views/6rww-hpns/rows.csv?max_rows=100) |
| Host | data.energystar.gov |
| Id | 6rww-hpns |
| Name | ENERGY STAR Certified Boilers |
| Category | Active Specifications |
| Tags | boilers |
| Created | 2013-05-07T16:16:39Z |
| Publication Date | 2016-12-29T15:29:58Z |

## Description

Certified models meet all ENERGY STAR requirements as listed in the Version 3.0 ENERGY STAR Program Requirements for Boilers that are effective as of October 1, 2014. A detailed listing of key efficiency criteria are available at http://www.energystar.gov/index.cfm?fuseaction=find_a_product.showProductGroup&pgw_code=BO

## Columns

```ls
| Included | Schema Type    | Field Name                      | Name                                           | Data Type     | Render Type   |
| ======== | ============== | =============================== | ============================================== | ============= | ============= |
| Yes      | series tag     | pd_id                           | ENERGY STAR Unique ID                          | text          | number        |
| Yes      | series tag     | energy_star_partner             | ENERGY STAR Partner                            | text          | text          |
| Yes      | series tag     | brand_name                      | Brand Name                                     | text          | text          |
| Yes      | series tag     | model_name                      | Model Name                                     | text          | text          |
| Yes      | series tag     | model_number                    | Model Number                                   | text          | text          |
| Yes      | series tag     | additional_model_information    | Additional Model Information                   | text          | text          |
| Yes      | series tag     | product_type                    | Product Type                                   | text          | text          |
| Yes      | series tag     | fuel_type                       | Fuel Type                                      | text          | text          |
| Yes      | numeric metric | efficiency_afue                 | Efficiency (AFUE)                              | number        | text          |
| Yes      | time           | date_available_on_market        | Date Available On Market                       | calendar_date | calendar_date |
| No       |                | date_qualified                  | Date Certified                                 | calendar_date | calendar_date |
| Yes      | series tag     | markets                         | Markets                                        | text          | text          |
| Yes      | series tag     | energy_star_model_identifier    | CB Model Identifier                            | text          | text          |
| Yes      | series tag     | can_integrate_hot_water_heating | Can Integrate Hot Water Heating                | text          | text          |
| Yes      | series tag     | meets_most_efficient_criteria   | Meets ENERGY STAR Most Efficient 2017 Criteria | text          | text          |
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
series e:6rww-hpns d:2006-05-01T00:00:00.000Z t:energy_star_partner="Bosch Thermotechnology Corporation" t:model_number=GB142/60 t:fuel_type="Natural Gas,Propane Gas" t:markets="United States, Canada" t:energy_star_model_identifier=ES_16809_09262014121811_2306870 t:product_type=Boiler t:meets_most_efficient_criteria=Yes t:can_integrate_hot_water_heating=No t:brand_name=Buderus t:model_name="GB142 series" t:pd_id=2220386 m:efficiency_afue=95

series e:6rww-hpns d:2011-07-01T00:00:00.000Z t:energy_star_partner="Bosch Thermotechnology Corporation" t:model_number=GB162-80 t:fuel_type="Natural Gas" t:markets="United States, Canada" t:energy_star_model_identifier=ES_16809_09262014121811_7683742 t:product_type=Boiler t:meets_most_efficient_criteria=No t:can_integrate_hot_water_heating=No t:brand_name=Buderus t:model_name="GB162 series" t:pd_id=2220388 m:efficiency_afue=92

series e:6rww-hpns d:2011-07-01T00:00:00.000Z t:energy_star_partner="Bosch Thermotechnology Corporation" t:model_number=GB162/80 t:fuel_type="Propane Gas" t:markets="United States, Canada" t:energy_star_model_identifier=ES_16809_09262014121811_9307122 t:product_type=Boiler t:meets_most_efficient_criteria=No t:can_integrate_hot_water_heating=No t:brand_name=Buderus t:model_name="GB162 series" t:pd_id=2220387 m:efficiency_afue=92
```

## Meta Commands

```ls
metric m:efficiency_afue p:integer l:"Efficiency (AFUE)" d:"AFUE: The Annual Fuel Utilization Efficiency (""AFUE"") measures the amount of fuel converted to space heat in proportion to the amount of fuel entering the boiler. This is commonly expressed as a percentage. CAafue: The Combined Appliance Annual Fuel Utilization Efficiency (?CAafue?) is the effective efficiency of the combined appliance in performing the function of space heating." t:dataTypeName=number

entity e:6rww-hpns l:"ENERGY STAR Certified Boilers" t:url=https://data.energystar.gov/api/views/6rww-hpns

property e:6rww-hpns t:meta.view v:id=6rww-hpns v:category="Active Specifications" v:averageRating=0 v:name="ENERGY STAR Certified Boilers"

property e:6rww-hpns t:meta.view.owner v:id=guxy-scz5 v:screenName=ESddas v:lastNotificationSeenAt=1491492552 v:displayName=ESddas

property e:6rww-hpns t:meta.view.tableauthor v:id=guxy-scz5 v:screenName=ESddas v:roleName=publisher v:lastNotificationSeenAt=1491492552 v:displayName=ESddas

property e:6rww-hpns t:meta.view.metadata.custom_fields.common_core v:Publisher="U.S. Environmental Protection Agency" v:License=https://edg.epa.gov/EPA_Data_License.html v:Contact_Name="Kathleen Vokes" v:Bureau_Code=020:00 v:Program_Code=020:033
```

## Top Records

```ls
| pd_id   | energy_star_partner                | brand_name     | model_name   | model_number | additional_model_information | product_type | fuel_type               | efficiency_afue | date_available_on_market | date_qualified      | markets               | energy_star_model_identifier      | can_integrate_hot_water_heating | meets_most_efficient_criteria | 
| ======= | ================================== | ============== | ============ | ============ | ============================ | ============ | ======================= | =============== | ======================== | =================== | ===================== | ================================= | =============================== | ============================= | 
| 2220386 | Bosch Thermotechnology Corporation | Buderus        | GB142 series | GB142/60     |                              | Boiler       | Natural Gas,Propane Gas | 95              | 2006-05-01T00:00:00      | 2014-09-26T00:00:00 | United States, Canada | ES_16809_09262014121811_2306870   | No                              | Yes                           | 
| 2220388 | Bosch Thermotechnology Corporation | Buderus        | GB162 series | GB162-80     |                              | Boiler       | Natural Gas             | 92              | 2011-07-01T00:00:00      | 2014-09-26T00:00:00 | United States, Canada | ES_16809_09262014121811_7683742   | No                              | No                            | 
| 2220387 | Bosch Thermotechnology Corporation | Buderus        | GB162 series | GB162/80     |                              | Boiler       | Propane Gas             | 92              | 2011-07-01T00:00:00      | 2014-09-26T00:00:00 | United States, Canada | ES_16809_09262014121811_9307122   | No                              | No                            | 
| 2238609 | Boyertown Furnace Company          | Solaia         | SL375ES      | SL375ES      |                              | Boiler       | Oil                     | 87              | 2015-04-12T00:00:00      | 2015-05-04T00:00:00 | United States         | ES_1043515_05042015111600_9663587 | No                              | No                            | 
| 2238610 | Boyertown Furnace Company          | Solaia         | SL4100ES     | SL4100ES     |                              | Boiler       | Oil                     | 87              | 2015-04-12T00:00:00      | 2015-05-04T00:00:00 | United States         | ES_1043515_05042015111600_2008259 | No                              | No                            | 
| 2238611 | Boyertown Furnace Company          | Solaia         | SL5125ES     | SL5125ES     |                              | Boiler       | Oil                     | 87              | 2015-04-12T00:00:00      | 2015-05-04T00:00:00 | United States         | ES_1043515_05042015111601_4564572 | No                              | No                            | 
| 2220426 | Bradford White Corporation         | Bradford White | Brute Elite  | BLMC125      |                              | Boiler       | Natural Gas,Propane Gas | 95              | 2010-07-19T00:00:00      | 2014-09-26T00:00:00 | United States, Canada | ES_92896_09262014121811_3363822   | No                              | Yes                           | 
| 2220427 | Bradford White Corporation         | Bradford White | Brute Elite  | BLMH125      |                              | Boiler       | Natural Gas,Propane Gas | 95              | 2010-07-19T00:00:00      | 2014-09-26T00:00:00 | United States, Canada | ES_92896_09262014121811_6428233   | No                              | Yes                           | 
| 2220433 | Bradford White Corporation         | Bradford White | Brute Elite  | BNTH080      |                              | Boiler       | Natural Gas,Propane Gas | 95              | 2008-08-05T00:00:00      | 2014-09-26T00:00:00 | United States, Canada | ES_92896_09262014121811_5155482   | No                              | Yes                           | 
| 2220434 | Bradford White Corporation         | Bradford White | Brute Elite  | BNTH105      |                              | Boiler       | Natural Gas,Propane Gas | 95              | 2008-08-05T00:00:00      | 2014-09-26T00:00:00 | United States, Canada | ES_92896_09262014121811_9056837   | No                              | Yes                           | 
```