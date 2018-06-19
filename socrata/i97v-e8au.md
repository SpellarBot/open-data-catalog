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
series e:i97v-e8au d:2012-04-27T00:00:00.000Z t:energy_star_model_identifier=ES_1102531_02012013151616_2923130 t:markets="United States, Canada" t:meets_most_efficient_criteria=Yes t:model_name="A97USMV Series" t:furnace_is_energy_star_certified_in=All t:energy_star_partner="Allied Air Enterprises" t:capable_of_two_way_communication=Other/Proprietary t:brand_name="Armstrong/Air Ease" t:model_number=A97USMV090C16S-* t:fuel_type="Natural Gas" t:can_integrate_hot_water_heating=No t:pd_id=2171657 m:efficiency_afue=97

series e:i97v-e8au d:2012-04-27T00:00:00.000Z t:energy_star_model_identifier=ES_1102531_02012013151616_3019280 t:markets="United States, Canada" t:meets_most_efficient_criteria=Yes t:model_name="A97USMV Series" t:furnace_is_energy_star_certified_in=All t:energy_star_partner="Allied Air Enterprises" t:capable_of_two_way_communication=Other/Proprietary t:brand_name="Armstrong/Air Ease" t:model_number=A97USMV090C20S-* t:fuel_type="Natural Gas" t:can_integrate_hot_water_heating=No t:pd_id=2171658 m:efficiency_afue=97

series e:i97v-e8au d:2012-04-27T00:00:00.000Z t:energy_star_model_identifier=ES_1102531_02012013151616_9471760 t:markets="United States, Canada" t:meets_most_efficient_criteria=Yes t:model_name="A97USMV Series" t:furnace_is_energy_star_certified_in=All t:energy_star_partner="Allied Air Enterprises" t:capable_of_two_way_communication=Other/Proprietary t:brand_name="Armstrong/Air Ease" t:model_number=A97USMV110C20S-* t:fuel_type="Natural Gas" t:can_integrate_hot_water_heating=No t:pd_id=2171659 m:efficiency_afue=97
```

## Meta Commands

```ls
metric m:efficiency_afue p:float l:"Efficiency (AFUE)" d:"The percentage of the heat in the incoming fuel which is converted to space heat instead of being lost." t:dataTypeName=number

entity e:i97v-e8au l:"ENERGY STAR Certified Furnaces" t:url=https://data.energystar.gov/api/views/i97v-e8au

property e:i97v-e8au t:meta.view d:2017-09-25T07:22:28.942Z v:averageRating=0 v:name="ENERGY STAR Certified Furnaces" v:id=i97v-e8au v:category="Active Specifications"

property e:i97v-e8au t:meta.view.owner d:2017-09-25T07:22:28.942Z v:displayName=ESddas v:lastNotificationSeenAt=1493126780 v:id=guxy-scz5 v:screenName=ESddas

property e:i97v-e8au t:meta.view.tableauthor d:2017-09-25T07:22:28.942Z v:displayName=ESddas v:lastNotificationSeenAt=1493126780 v:roleName=publisher v:id=guxy-scz5 v:screenName=ESddas

property e:i97v-e8au t:meta.view.metadata.custom_fields.common_core d:2017-09-25T07:22:28.942Z v:Contact_Name="Kathleen Vokes" v:License=https://edg.epa.gov/EPA_Data_License.html v:Program_Code=020:033 v:Publisher="U.S. Environmental Protection Agency" v:Bureau_Code=020:00
```

## Top Records

```ls
| pd_id   | energy_star_partner    | brand_name         | model_name     | model_number     | additional_model_information | fuel_type   | furnace_is_energy_star_certified_in | efficiency_afue | capable_of_two_way_communication | date_available_on_market | date_qualified      | markets               | energy_star_model_identifier      | can_integrate_hot_water_heating | meets_most_efficient_criteria | 
| ======= | ====================== | ================== | ============== | ================ | ============================ | =========== | =================================== | =============== | ================================ | ======================== | =================== | ===================== | ================================= | =============================== | ============================= | 
| 2171657 | Allied Air Enterprises | Armstrong/Air Ease | A97USMV Series | A97USMV090C16S-* |                              | Natural Gas | All                                 | 97              | Other/Proprietary                | 2012-04-27T00:00:00      | 2013-02-01T00:00:00 | United States, Canada | ES_1102531_02012013151616_2923130 | No                              | Yes                           | 
| 2171658 | Allied Air Enterprises | Armstrong/Air Ease | A97USMV Series | A97USMV090C20S-* |                              | Natural Gas | All                                 | 97              | Other/Proprietary                | 2012-04-27T00:00:00      | 2013-02-01T00:00:00 | United States, Canada | ES_1102531_02012013151616_3019280 | No                              | Yes                           | 
| 2171659 | Allied Air Enterprises | Armstrong/Air Ease | A97USMV Series | A97USMV110C20S-* |                              | Natural Gas | All                                 | 97              | Other/Proprietary                | 2012-04-27T00:00:00      | 2013-02-01T00:00:00 | United States, Canada | ES_1102531_02012013151616_9471760 | No                              | Yes                           | 
| 2171633 | Allied Air Enterprises | Concord,Ducane     | 95G2 Series    | 95G2UH045BV12-*  |                              | Natural Gas | All                                 | 95              | Other/Proprietary                | 2011-09-01T00:00:00      | 2013-02-01T00:00:00 | United States, Canada | ES_1102531_02012013151615_4242608 | No                              | No                            | 
| 2171634 | Allied Air Enterprises | Concord,Ducane     | 95G2 Series    | 95G2UH070BV12-*  |                              | Natural Gas | All                                 | 95              | Other/Proprietary                | 2011-09-01T00:00:00      | 2013-02-01T00:00:00 | United States, Canada | ES_1102531_02012013151615_4006211 | No                              | No                            | 
| 2171635 | Allied Air Enterprises | Concord,Ducane     | 95G2 Series    | 95G2UH090CV12-*  |                              | Natural Gas | All                                 | 95              | Other/Proprietary                | 2011-09-01T00:00:00      | 2013-02-01T00:00:00 | United States, Canada | ES_1102531_02012013151615_4242738 | No                              | No                            | 
| 2171636 | Allied Air Enterprises | Concord,Ducane     | 95G2 Series    | 95G2UH090CV20-*  |                              | Natural Gas | All                                 | 95              | Other/Proprietary                | 2011-09-01T00:00:00      | 2013-02-01T00:00:00 | United States, Canada | ES_1102531_02012013151615_6466802 | No                              | No                            | 
| 2171637 | Allied Air Enterprises | Concord,Ducane     | 95G2 Series    | 95G2UH110CV20-*  |                              | Natural Gas | All                                 | 95              | Other/Proprietary                | 2011-09-01T00:00:00      | 2013-02-01T00:00:00 | United States, Canada | ES_1102531_02012013151615_7691816 | No                              | No                            | 
| 2171638 | Allied Air Enterprises | Concord,Ducane     | 95G2 Series    | 95G2UH135DV20-*  |                              | Natural Gas | All                                 | 95              | Other/Proprietary                | 2011-09-01T00:00:00      | 2013-02-01T00:00:00 | United States, Canada | ES_1102531_02012013151615_5476041 | No                              | No                            | 
| 2203730 | Allied Air Enterprises | Concord,Ducane     | 95G1E Series   | 95G1UH070BE12-*  |                              | Natural Gas | All                                 | 95              | Not Applicable                   | 2014-01-02T00:00:00      | 2014-02-07T00:00:00 | United States, Canada | ES_1102531_02072014124050_2273331 | No                              | No                            | 
```