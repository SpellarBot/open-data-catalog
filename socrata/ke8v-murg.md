# ENERGY STAR Certified Light Commercial HVAC

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/energy-star-certified-light-commercial-hvac) |
| Metadata | [Link](https://data.energystar.gov/api/views/ke8v-murg) |
| Data: JSON | [100 Rows](https://data.energystar.gov/api/views/ke8v-murg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.energystar.gov/api/views/ke8v-murg/rows.csv?max_rows=100) |
| Host | data.energystar.gov |
| Id | ke8v-murg |
| Name | ENERGY STAR Certified Light Commercial HVAC |
| Category | Active Specifications |
| Tags | light commercial hvac |
| Created | 2013-06-06T18:18:38Z |
| Publication Date | 2017-01-19T21:11:19Z |

## Description

Certified models meet all ENERGY STAR requirements as listed in the Version 2.0 ENERGY STAR Program Requirements for Light Commercial HVAC that are effective as of January 1, 2011. A detailed listing of key efficiency criteria are available at http://www.energystar.gov/index.cfm?c=lchvac.pr_crit_lchvac

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                         | Data Type     | Render Type   |
| ======== | ============== | ============================ | ============================ | ============= | ============= |
| Yes      | series tag     | pd_id                        | ENERGY STAR Unique ID        | text          | number        |
| Yes      | series tag     | energy_star_partner          | ENERGY STAR Partner          | text          | text          |
| Yes      | series tag     | brand_name                   | Brand Name                   | text          | text          |
| Yes      | series tag     | model_name                   | Model Name                   | text          | text          |
| Yes      | series tag     | model_number                 | Model Number                 | text          | text          |
| Yes      | series tag     | additional_model_information | Additional Model Information | text          | text          |
| Yes      | series tag     | type                         | Type                         | text          | text          |
| Yes      | numeric metric | cooling_capacity_kbtu_h      | Cooling Capacity (kBtu/hr)   | number        | number        |
| Yes      | series tag     | heating_section_type         | Heating Section Type         | text          | text          |
| Yes      | numeric metric | seer_rating_btu_wh           | SEER Rating (Btu/Wh)         | number        | number        |
| Yes      | numeric metric | eer_rating_btu_wh            | EER Rating (Btu/Wh)          | number        | number        |
| Yes      | numeric metric | ieer_rating                  | IEER Rating (Btu/Wh)         | number        | number        |
| Yes      | numeric metric | hspf_rating_btu_wh           | HSPF Rating (Btu/Wh)         | number        | number        |
| Yes      | numeric metric | cop_rating                   | COP Rating at 47?F           | number        | number        |
| Yes      | series tag     | indoor_unit_model_number     | Indoor Unit Model Number     | text          | text          |
| Yes      | series tag     | vrf_indoor_model_type        | VRF Indoor Model Type        | text          | text          |
| Yes      | series tag     | vrf_outdoor_model_number_s   | VRF Outdoor Model Number(s)  | text          | text          |
| Yes      | series tag     | furnace_model_number         | Furnace Model Number         | text          | text          |
| Yes      | time           | date_available_on_market     | Date Available On Market     | calendar_date | calendar_date |
| No       |                | date_qualified               | Date Qualified               | calendar_date | calendar_date |
| Yes      | series tag     | markets                      | Markets                      | text          | text          |
| Yes      | series tag     | energy_star_model_identifier | CB Model Identifier          | text          | text          |
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
series e:ke8v-murg d:2010-08-31T00:00:00.000Z t:energy_star_partner="Carrier Air Conditioning - Commercial" t:model_number=549JE04**********A t:markets="United States, Canada" t:energy_star_model_identifier=ES_1106973_09112013104126_7226943 t:type="Single Package HP" t:brand_name="Bryant Heating and Cooling Systems - Commercial" t:model_name="Preferred Line Rooftop" t:pd_id=2190375 m:cooling_capacity_kbtu_h=36.4 m:hspf_rating_btu_wh=8 m:eer_rating_btu_wh=12.7 m:seer_rating_btu_wh=15.6

series e:ke8v-murg d:2010-08-31T00:00:00.000Z t:energy_star_partner="Carrier Air Conditioning - Commercial" t:model_number=549JE05**********A t:markets="United States, Canada" t:energy_star_model_identifier=ES_1106973_09112013104127_8054346 t:type="Single Package HP" t:brand_name="Bryant Heating and Cooling Systems - Commercial" t:model_name="Preferred Line Rooftop" t:pd_id=2190486 m:cooling_capacity_kbtu_h=47 m:hspf_rating_btu_wh=8.1 m:eer_rating_btu_wh=12.8 m:seer_rating_btu_wh=15.8

series e:ke8v-murg d:2010-08-31T00:00:00.000Z t:energy_star_partner="Carrier Air Conditioning - Commercial" t:model_number=549JE06**********A t:markets="United States, Canada" t:energy_star_model_identifier=ES_1106973_09112013104127_6508995 t:type="Single Package HP" t:brand_name="Bryant Heating and Cooling Systems - Commercial" t:model_name="Preferred Line Rooftop" t:pd_id=2190516 m:cooling_capacity_kbtu_h=58.5 m:hspf_rating_btu_wh=8.2 m:eer_rating_btu_wh=12.5 m:seer_rating_btu_wh=15
```

## Meta Commands

```ls
metric m:cooling_capacity_kbtu_h p:double l:"Cooling Capacity (kBtu/hr)" d:"The capacity is the quantity of heat in Btu (British Thermal Units) that an air conditioner or heat pump is able to remove from an enclosed space during a one-hour period." t:dataTypeName=number

metric m:seer_rating_btu_wh p:float l:"SEER Rating (Btu/Wh)" d:"SEER is a measure of equipment energy efficiency over the cooling season. It represents the total cooling of a central air-conditioner or heat pump (in Btu) during the normal cooling season as compared to the total electric energy input (in watt-hours) consumed during the same period." t:dataTypeName=number

metric m:eer_rating_btu_wh p:float l:"EER Rating (Btu/Wh)" d:"EER is a measure of efficiency in the cooling mode that represents the ratio of total cooling capacity (Btu/h) to electrical energy input (Watts)." t:dataTypeName=number

metric m:ieer_rating p:float l:"IEER Rating (Btu/Wh)" d:"IEER is a measure that expresses cooling part-load EER efficiency for commercial unitary air-conditioning and heat pump equipment on the basis of weighted operation at various load capacities." t:dataTypeName=number

metric m:hspf_rating_btu_wh p:float l:"HSPF Rating (Btu/Wh)" d:"HSPF is a measure of a heat pump?s energy efficiency over one heating season. It represents the total heating output of a heat pump (including supplementary electric heat) during the normal heating season (in Btu) as compared to the total electricity consumed (in watt-hours) during the same period." t:dataTypeName=number

metric m:cop_rating p:float l:"COP Rating at 47?F" d:"A measure of efficiency in the heating mode that represents the ratio of total heating capacity to electrical energy input." t:dataTypeName=number

entity e:ke8v-murg l:"ENERGY STAR Certified Light Commercial HVAC" t:url=https://data.energystar.gov/api/views/ke8v-murg

property e:ke8v-murg t:meta.view v:id=ke8v-murg v:category="Active Specifications" v:averageRating=0 v:name="ENERGY STAR Certified Light Commercial HVAC"

property e:ke8v-murg t:meta.view.owner v:id=guxy-scz5 v:screenName=ESddas v:lastNotificationSeenAt=1491492552 v:displayName=ESddas

property e:ke8v-murg t:meta.view.tableauthor v:id=guxy-scz5 v:screenName=ESddas v:roleName=publisher v:lastNotificationSeenAt=1491492552 v:displayName=ESddas

property e:ke8v-murg t:meta.view.metadata.custom_fields.common_core v:Publisher="U.S. Environmental Protection Agency" v:License=https://edg.epa.gov/EPA_Data_License.html v:Contact_Name="Kathleen Vokes" v:Bureau_Code=020:00 v:Program_Code=020:033
```

## Top Records

```ls
| pd_id   | energy_star_partner                   | brand_name                                      | model_name             | model_number                 | additional_model_information           | type              | cooling_capacity_kbtu_h | heating_section_type | seer_rating_btu_wh | eer_rating_btu_wh | ieer_rating | hspf_rating_btu_wh | cop_rating | indoor_unit_model_number | vrf_indoor_model_type | vrf_outdoor_model_number_s | furnace_model_number | date_available_on_market | date_qualified      | markets               | energy_star_model_identifier      | 
| ======= | ===================================== | =============================================== | ====================== | ============================ | ====================================== | ================= | ======================= | ==================== | ================== | ================= | =========== | ================== | ========== | ======================== | ===================== | ========================== | ==================== | ======================== | =================== | ===================== | ================================= | 
| 2190375 | Carrier Air Conditioning - Commercial | Bryant Heating and Cooling Systems - Commercial | Preferred Line Rooftop | 549JE04**********A           |                                        | Single Package HP | 36.4                    |                      | 15.6               | 12.7              |             | 8                  |            |                          |                       |                            |                      | 2010-08-31T00:00:00      | 2013-09-11T00:00:00 | United States, Canada | ES_1106973_09112013104126_7226943 | 
| 2190486 | Carrier Air Conditioning - Commercial | Bryant Heating and Cooling Systems - Commercial | Preferred Line Rooftop | 549JE05**********A           |                                        | Single Package HP | 47                      |                      | 15.8               | 12.8              |             | 8.1                |            |                          |                       |                            |                      | 2010-08-31T00:00:00      | 2013-09-11T00:00:00 | United States, Canada | ES_1106973_09112013104127_8054346 | 
| 2190516 | Carrier Air Conditioning - Commercial | Bryant Heating and Cooling Systems - Commercial | Preferred Line Rooftop | 549JE06**********A           |                                        | Single Package HP | 58.5                    |                      | 15                 | 12.5              |             | 8.2                |            |                          |                       |                            |                      | 2010-08-31T00:00:00      | 2013-09-11T00:00:00 | United States, Canada | ES_1106973_09112013104127_6508995 | 
| 2190365 | Carrier Air Conditioning - Commercial | Bryant Heating and Cooling Systems - Commercial | Preferred Line Rooftop | 549JP04**********A           |                                        | Single Package HP | 36.4                    |                      | 15.6               | 12.7              |             | 8                  |            |                          |                       |                            |                      | 2010-08-31T00:00:00      | 2013-09-11T00:00:00 | United States, Canada | ES_1106973_09112013104126_1261077 | 
| 2190350 | Carrier Air Conditioning - Commercial | Bryant Heating and Cooling Systems - Commercial | Preferred Line Rooftop | 549JP05**********A           |                                        | Single Package HP | 47                      |                      | 15.8               | 12.8              |             | 8.1                |            |                          |                       |                            |                      | 2010-08-31T00:00:00      | 2013-09-11T00:00:00 | United States, Canada | ES_1106973_09112013104127_1778256 | 
| 2190506 | Carrier Air Conditioning - Commercial | Bryant Heating and Cooling Systems - Commercial | Preferred Line Rooftop | 549JP06**********A           | 549JP06**********A,549JP06**********A, | Single Package HP | 58.5                    |                      | 15                 | 12.5              |             | 8.2                |            |                          |                       |                            |                      | 2010-08-31T00:00:00      | 2013-09-11T00:00:00 | United States, Canada | ES_1106973_09112013104127_3840159 | 
| 2190526 | Carrier Air Conditioning - Commercial | Bryant Heating and Cooling Systems - Commercial | Preferred Line Rooftop | 549J(P,E,T)07**********A     |                                        | Single Package HP | 72                      |                      |                    | 12                | 12.8        |                    | 3.4        |                          |                       |                            |                      | 2010-08-31T00:00:00      | 2013-09-11T00:00:00 | United States, Canada | ES_1106973_09112013104505_5704729 | 
| 2190536 | Carrier Air Conditioning - Commercial | Bryant Heating and Cooling Systems - Commercial | Preferred Line Rooftop | 549J(P,E,T)08*********(A,B)A |                                        | Single Package HP | 90                      |                      |                    | 12.1              | 12.9        |                    | 3.5        |                          |                       |                            |                      | 2010-08-31T00:00:00      | 2013-09-11T00:00:00 | United States, Canada | ES_1106973_09112013104505_2196334 | 
| 2190546 | Carrier Air Conditioning - Commercial | Bryant Heating and Cooling Systems - Commercial | Preferred Line Rooftop | 549J(P,E,T)08*********(D,E)A |                                        | Single Package HP | 90                      |                      |                    | 12.1              | 13.7        |                    | 3.5        |                          |                       |                            |                      | 2012-01-27T00:00:00      | 2013-09-11T00:00:00 | United States, Canada | ES_1106973_09112013104506_2666102 | 
| 2190556 | Carrier Air Conditioning - Commercial | Bryant Heating and Cooling Systems - Commercial | Preferred Line Rooftop | 549J(P,E,T)09*********(A,B)A |                                        | Single Package HP | 100                     |                      |                    | 12                | 12.5        |                    | 3.4        |                          |                       |                            |                      | 2010-08-31T00:00:00      | 2013-09-11T00:00:00 | United States, Canada | ES_1106973_09112013104506_3072491 | 
```