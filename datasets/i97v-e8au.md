# ENERGY STAR Certified Furnaces

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/energy-star-certified-furnaces) |
| Metadata | [Link](https://data.energystar.gov/api/views/i97v-e8au) |
| Data: JSON | [100 Rows](https://data.energystar.gov/api/views/i97v-e8au/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.energystar.gov/api/views/i97v-e8au/rows.csv?max_rows=100) |
| Host | data.energystar.gov |
| Id | i97v-e8au |
| Name | ENERGY STAR Certified Furnaces |
| Category | Active Specifications |
| Tags | furnaces |
| Created | 2014-08-08T12:06:09Z |
| Publication Date | 2016-12-29T15:39:44Z |

## Description

Certified models meet all ENERGY STAR requirements as listed in the Version 4.0 ENERGY STAR Program Requirements for Furnaces that are effective as of February 1, 2013. A detailed listing of key efficiency criteria are available at http://www.energystar.gov/index.cfm?c=furnaces.pr_crit_furnaces

## Columns

```ls
| Included | Schema Type    | Field Name                          | Name                                           | Data Type     | Render Type   |
| ======== | ============== | =================================== | ============================================== | ============= | ============= |
| Yes      | series tag     | pd_id                               | ENERGY STAR Unique ID                          | text          | number        |
| Yes      | series tag     | energy_star_partner                 | ENERGY STAR Partner                            | text          | text          |
| Yes      | series tag     | brand_name                          | Brand Name                                     | text          | text          |
| Yes      | series tag     | model_name                          | Model Name                                     | text          | text          |
| Yes      | series tag     | model_number                        | Model Number                                   | text          | text          |
| Yes      | series tag     | additional_model_information        | Additional Model Information                   | text          | text          |
| Yes      | series tag     | fuel_type                           | Fuel Type                                      | text          | text          |
| Yes      | series tag     | furnace_is_energy_star_certified_in | Furnace is ENERGY STAR Certified in            | text          | text          |
| Yes      | numeric metric | efficiency_afue                     | Efficiency (AFUE)                              | number        | number        |
| Yes      | series tag     | capable_of_two_way_communication    | Capable of Two Way Communication?              | text          | text          |
| Yes      | time           | date_available_on_market            | Date Available On Market                       | calendar_date | calendar_date |
| No       |                | date_qualified                      | Date Qualified                                 | calendar_date | calendar_date |
| Yes      | series tag     | markets                             | Markets                                        | text          | text          |
| Yes      | series tag     | energy_star_model_identifier        | CB Model Identifier                            | text          | text          |
| Yes      | series tag     | can_integrate_hot_water_heating     | Can Integrate Hot Water Heating                | text          | text          |
| Yes      | series tag     | meets_most_efficient_criteria       | Meets ENERGY STAR Most Efficient 2017 Criteria | text          | text          |
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
series e:i97v-e8au d:2011-09-01T00:00:00.000Z t:energy_star_partner="Allied Air Enterprises" t:capable_of_two_way_communication="Not Applicable" t:model_number=A95DF2V045B12*-* t:fuel_type="Natural Gas" t:markets="United States, Canada" t:energy_star_model_identifier=ES_1102531_02012013151615_7643006 t:furnace_is_energy_star_certified_in=All t:meets_most_efficient_criteria=No t:can_integrate_hot_water_heating=No t:brand_name="AirEase Armstrong" t:model_name="A952V Series" t:pd_id=2171639 m:efficiency_afue=95

series e:i97v-e8au d:2011-09-01T00:00:00.000Z t:energy_star_partner="Allied Air Enterprises" t:capable_of_two_way_communication="Not Applicable" t:model_number=A95DF2V070B16*-* t:fuel_type="Natural Gas" t:markets="United States, Canada" t:energy_star_model_identifier=ES_1102531_02012013151615_9228942 t:furnace_is_energy_star_certified_in=All t:meets_most_efficient_criteria=No t:can_integrate_hot_water_heating=No t:brand_name="AirEase Armstrong" t:model_name="A952V Series" t:pd_id=2171640 m:efficiency_afue=95

series e:i97v-e8au d:2011-09-01T00:00:00.000Z t:energy_star_partner="Allied Air Enterprises" t:capable_of_two_way_communication="Not Applicable" t:model_number=A95DF2V090C20*-* t:fuel_type="Natural Gas" t:markets="United States, Canada" t:energy_star_model_identifier=ES_1102531_02012013151615_6679033 t:furnace_is_energy_star_certified_in=All t:meets_most_efficient_criteria=No t:can_integrate_hot_water_heating=No t:brand_name="AirEase Armstrong" t:model_name="A952V Series" t:pd_id=2171641 m:efficiency_afue=95
```

## Meta Commands

```ls
metric m:efficiency_afue p:float l:"Efficiency (AFUE)" d:"The percentage of the heat in the incoming fuel which is converted to space heat instead of being lost." t:dataTypeName=number

entity e:i97v-e8au l:"ENERGY STAR Certified Furnaces" t:url=https://data.energystar.gov/api/views/i97v-e8au

property e:i97v-e8au t:meta.view v:id=i97v-e8au v:category="Active Specifications" v:averageRating=0 v:name="ENERGY STAR Certified Furnaces"

property e:i97v-e8au t:meta.view.owner v:id=guxy-scz5 v:screenName=ESddas v:displayName=ESddas

property e:i97v-e8au t:meta.view.tableauthor v:id=guxy-scz5 v:screenName=ESddas v:roleName=publisher v:displayName=ESddas

property e:i97v-e8au t:meta.view.metadata.custom_fields.common_core v:Publisher="U.S. Environmental Protection Agency" v:License=https://edg.epa.gov/EPA_Data_License.html v:Contact_Name="Kathleen Vokes" v:Bureau_Code=020:00 v:Program_Code=020:033
```

## Top Records

```ls
| pd_id   | energy_star_partner    | brand_name         | model_name     | model_number     | additional_model_information | fuel_type               | furnace_is_energy_star_certified_in | efficiency_afue | capable_of_two_way_communication | date_available_on_market | date_qualified      | markets               | energy_star_model_identifier      | can_integrate_hot_water_heating | meets_most_efficient_criteria | 
| ======= | ====================== | ================== | ============== | ================ | ============================ | ======================= | =================================== | =============== | ================================ | ======================== | =================== | ===================== | ================================= | =============================== | ============================= | 
| 2171639 | Allied Air Enterprises | AirEase Armstrong  | A952V Series   | A95DF2V045B12*-* |                              | Natural Gas             | All                                 | 95              | Not Applicable                   | 2011-09-01T00:00:00      | 2013-02-01T00:00:00 | United States, Canada | ES_1102531_02012013151615_7643006 | No                              | No                            | 
| 2171640 | Allied Air Enterprises | AirEase Armstrong  | A952V Series   | A95DF2V070B16*-* |                              | Natural Gas             | All                                 | 95              | Not Applicable                   | 2011-09-01T00:00:00      | 2013-02-01T00:00:00 | United States, Canada | ES_1102531_02012013151615_9228942 | No                              | No                            | 
| 2171641 | Allied Air Enterprises | AirEase Armstrong  | A952V Series   | A95DF2V090C20*-* |                              | Natural Gas             | All                                 | 95              | Not Applicable                   | 2011-09-01T00:00:00      | 2013-02-01T00:00:00 | United States, Canada | ES_1102531_02012013151615_6679033 | No                              | No                            | 
| 2171642 | Allied Air Enterprises | AirEase Armstrong  | A952V Series   | A95DF2V110C20*-* |                              | Natural Gas             | All                                 | 95              | Not Applicable                   | 2011-09-01T00:00:00      | 2013-02-01T00:00:00 | United States, Canada | ES_1102531_02012013151615_4694675 | No                              | No                            | 
| 2246402 | Allied Air Enterprises | AirEase, Armstrong | A95 Series     | A95UH1E135D20-*  |                              | Natural Gas,Propane Gas | All                                 | 95              | Not Applicable                   | 2015-08-15T00:00:00      | 2015-08-21T00:00:00 | United States, Canada | ES_1102531_08212015153004_7763655 | No                              | No                            | 
| 2203728 | Allied Air Enterprises | AirEase,Armstrong  | A95 Series     | A95UH1E070B12-*  |                              | Natural Gas,Propane Gas | All                                 | 95              | Not Applicable                   | 2014-01-02T00:00:00      | 2014-02-07T00:00:00 | United States, Canada | ES_1102531_02072014124050_8197748 | No                              | No                            | 
| 2203729 | Allied Air Enterprises | AirEase,Armstrong  | A95 Series     | A95UH1E090C16-*  |                              | Natural Gas,Propane Gas | All                                 | 95              | Not Applicable                   | 2014-01-02T00:00:00      | 2014-02-07T00:00:00 | United States, Canada | ES_1102531_02072014124050_9911485 | No                              | No                            | 
| 2237065 | Allied Air Enterprises | AirEase,Armstrong  | A95 Series     | A95UH1E045B12-*  |                              | Natural Gas,Propane Gas | All                                 | 95              | Not Applicable                   | 2015-05-01T00:00:00      | 2015-04-14T00:00:00 | United States, Canada | ES_1102531_04142015144732_9459796 | No                              | No                            | 
| 2237066 | Allied Air Enterprises | AirEase,Armstrong  | A95 Series     | A95UH1E110C20-*  |                              | Natural Gas,Propane Gas | All                                 | 95              | Not Applicable                   | 2015-05-01T00:00:00      | 2015-04-14T00:00:00 | United States, Canada | ES_1102531_04142015144732_9306656 | No                              | No                            | 
| 2171620 | Allied Air Enterprises | Aire-Flow          | 95AF2DF Series | 95AF2DF045V12B-* |                              | Natural Gas             | All                                 | 95              | Not Applicable                   | 2012-06-01T00:00:00      | 2013-02-01T00:00:00 | United States, Canada | ES_1102531_02012013151615_8292916 | No                              | No                            | 
```