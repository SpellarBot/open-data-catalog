# ENERGY STAR Certified Geothermal Heat Pumps

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/energy-star-certified-geothermal-heat-pumps) |
| Metadata | [Link](https://data.energystar.gov/api/views/acvd-5wvz) |
| Data: JSON | [100 Rows](https://data.energystar.gov/api/views/acvd-5wvz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.energystar.gov/api/views/acvd-5wvz/rows.csv?max_rows=100) |
| Host | data.energystar.gov |
| Id | acvd-5wvz |
| Name | ENERGY STAR Certified Geothermal Heat Pumps |
| Category | Active Specifications |
| Tags | geothermal heat pumps |
| Created | 2013-02-14T15:58:11Z |
| Publication Date | 2016-12-29T15:47:36Z |

## Description

Certified models meet all ENERGY STAR requirements as listed in the Version 3.0 ENERGY STAR Program Requirements for Geothermal Heat Pumps that are effective as of January 1, 2012. A detailed listing of key efficiency criteria are available at http://www.energystar.gov/index.cfm?c=geo_heat.pr_crit_geo_heat_pumps

## Columns

```ls
| Included | Schema Type    | Field Name                    | Name                                           | Data Type     | Render Type   |
| ======== | ============== | ============================= | ============================================== | ============= | ============= |
| Yes      | series tag     | pd_id                         | ENERGY STAR Unique ID                          | text          | number        |
| Yes      | series tag     | energy_star_partner           | ENERGY STAR Partner                            | text          | text          |
| Yes      | series tag     | brand_name                    | Brand Name                                     | text          | text          |
| Yes      | series tag     | model_name                    | Model Name                                     | text          | text          |
| Yes      | series tag     | model_number                  | Model Number                                   | text          | text          |
| Yes      | series tag     | additional_model_information  | Additional Model Information                   | text          | text          |
| Yes      | series tag     | product_type                  | Type                                           | text          | text          |
| Yes      | numeric metric | cop_rating                    | COP Rating                                     | number        | number        |
| Yes      | numeric metric | eer_rating                    | Energy Efficiency (EER)                        | number        | number        |
| Yes      | time           | date_available_on_market      | Date Available On Market                       | calendar_date | calendar_date |
| No       |                | date_qualified                | Date Qualified                                 | calendar_date | calendar_date |
| Yes      | series tag     | markets                       | Markets                                        | text          | text          |
| Yes      | series tag     | energy_star_model_identifier  | CB Model Identifier                            | text          | text          |
| Yes      | series tag     | meets_most_efficient_criteria | Meets ENERGY STAR Most Efficient 2017 Criteria | text          | text          |
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
series e:acvd-5wvz d:2005-01-01T00:00:00.000Z t:energy_star_partner="Advanced Geothermal Technology" t:model_number=GC-24-XXXXX-DW t:markets="United States" t:energy_star_model_identifier=ES_1071110_GC-24-XXXXX-DW_05012013143335_7734797 t:product_type=DGX t:meets_most_efficient_criteria=No t:model_name=GC-24-XXXXX-DW t:brand_name="Advanced Geothermal Technology" t:pd_id=2179335 m:cop_rating=3.6 m:eer_rating=16.6

series e:acvd-5wvz d:2005-01-01T00:00:00.000Z t:energy_star_partner="Advanced Geothermal Technology" t:model_number=GC-24-XXXXX-NW t:markets="United States" t:energy_star_model_identifier=ES_1071110_GC-24-XXXXX-NW_05012013143335_3698083 t:product_type=DGX t:meets_most_efficient_criteria=No t:model_name=GC-24-XXXXX-NW t:brand_name="Advanced Geothermal Technology" t:pd_id=2180086 m:cop_rating=3.6 m:eer_rating=16.6

series e:acvd-5wvz d:2005-01-01T00:00:00.000Z t:energy_star_partner="Advanced Geothermal Technology" t:model_number=GC-24-XXXXX-WH t:markets="United States" t:energy_star_model_identifier=ES_1071110_GC-24-XXXXX-WH_05012013143335_6150308 t:product_type=DGX t:meets_most_efficient_criteria=No t:model_name=GC-24-XXXXX-WH t:brand_name="Advanced Geothermal Technology" t:pd_id=2179336 m:cop_rating=3.6 m:eer_rating=16.6
```

## Meta Commands

```ls
metric m:cop_rating p:float l:"COP Rating" d:"A measure of efficiency in the heating mode that represents the ratio of total heating capacity to electrical energy input." t:dataTypeName=number

metric m:eer_rating p:float l:"Energy Efficiency (EER)" d:"A measure of efficiency in the cooling mode that represents the ratio of total cooling capacity to electrical energy input." t:dataTypeName=number

entity e:acvd-5wvz l:"ENERGY STAR Certified Geothermal Heat Pumps" t:url=https://data.energystar.gov/api/views/acvd-5wvz

property e:acvd-5wvz t:meta.view v:id=acvd-5wvz v:category="Active Specifications" v:averageRating=0 v:name="ENERGY STAR Certified Geothermal Heat Pumps"

property e:acvd-5wvz t:meta.view.owner v:id=guxy-scz5 v:screenName=ESddas v:lastNotificationSeenAt=1491492552 v:displayName=ESddas

property e:acvd-5wvz t:meta.view.tableauthor v:id=guxy-scz5 v:screenName=ESddas v:roleName=publisher v:lastNotificationSeenAt=1491492552 v:displayName=ESddas

property e:acvd-5wvz t:meta.view.metadata.custom_fields.common_core v:Publisher="U.S. Environmental Protection Agency" v:License=https://edg.epa.gov/EPA_Data_License.html v:Contact_Name="Kathleen Vokes" v:Bureau_Code=020:00 v:Program_Code=020:033
```

## Top Records

```ls
| pd_id   | energy_star_partner            | brand_name                     | model_name     | model_number   | additional_model_information | product_type | cop_rating | eer_rating | date_available_on_market | date_qualified      | markets       | energy_star_model_identifier                     | meets_most_efficient_criteria | 
| ======= | ============================== | ============================== | ============== | ============== | ============================ | ============ | ========== | ========== | ======================== | =================== | ============= | ================================================ | ============================= | 
| 2179335 | Advanced Geothermal Technology | Advanced Geothermal Technology | GC-24-XXXXX-DW | GC-24-XXXXX-DW |                              | DGX          | 3.6        | 16.6       | 2005-01-01T00:00:00      | 2013-04-11T00:00:00 | United States | ES_1071110_GC-24-XXXXX-DW_05012013143335_7734797 | No                            | 
| 2180086 | Advanced Geothermal Technology | Advanced Geothermal Technology | GC-24-XXXXX-NW | GC-24-XXXXX-NW |                              | DGX          | 3.6        | 16.6       | 2005-01-01T00:00:00      | 2013-04-11T00:00:00 | United States | ES_1071110_GC-24-XXXXX-NW_05012013143335_3698083 | No                            | 
| 2179336 | Advanced Geothermal Technology | Advanced Geothermal Technology | GC-24-XXXXX-WH | GC-24-XXXXX-WH |                              | DGX          | 3.6        | 16.6       | 2005-01-01T00:00:00      | 2013-04-11T00:00:00 | United States | ES_1071110_GC-24-XXXXX-WH_05012013143335_6150308 | No                            | 
| 2179337 | Advanced Geothermal Technology | Advanced Geothermal Technology | GC-30-XXXXX-DW | GC-30-XXXXX-DW |                              | DGX          | 3.6        | 16.6       | 2005-01-01T00:00:00      | 2013-04-11T00:00:00 | United States | ES_1071110_GC-30-XXXXX-DW_05012013143845_7778131 | No                            | 
| 2180088 | Advanced Geothermal Technology | Advanced Geothermal Technology | GC-30-XXXXX-NW | GC-30-XXXXX-NW |                              | DGX          | 3.6        | 16.6       | 2005-01-01T00:00:00      | 2013-04-11T00:00:00 | United States | ES_1071110_GC-30-XXXXX-NW_05012013143845_7480432 | No                            | 
| 2179338 | Advanced Geothermal Technology | Advanced Geothermal Technology | GC-30-XXXXX-WH | GC-30-XXXXX-WH |                              | DGX          | 3.6        | 16.6       | 2005-01-01T00:00:00      | 2013-04-11T00:00:00 | United States | ES_1071110_GC-30-XXXXX-WH_05012013143846_1354776 | No                            | 
| 2180091 | Advanced Geothermal Technology | Advanced Geothermal Technology | GC-36-XXXXX-DW | GC-36-XXXXX-DW |                              | DGX          | 3.9        | 16.7       | 2005-01-01T00:00:00      | 2013-04-11T00:00:00 | United States | ES_1071110_GC-36-XXXXX-DW_05012013152304_776331  | No                            | 
| 2180090 | Advanced Geothermal Technology | Advanced Geothermal Technology | GC-36-XXXXX-NW | GC-36-XXXXX-NW |                              | DGX          | 3.9        | 16.7       | 2005-01-01T00:00:00      | 2013-04-11T00:00:00 | United States | ES_1071110_GC-36-XXXXX-NW_05012013152304_9232293 | No                            | 
| 2180092 | Advanced Geothermal Technology | Advanced Geothermal Technology | GC-36-XXXXX-WH | GC-36-XXXXX-WH |                              | DGX          | 3.9        | 16.7       | 2005-01-01T00:00:00      | 2013-04-11T00:00:00 | United States | ES_1071110_GC-36-XXXXX-WH_05012013152304_7916207 | No                            | 
| 2180094 | Advanced Geothermal Technology | Advanced Geothermal Technology | GC-42-XXXXX-DW | GC-42-XXXXX-DW |                              | DGX          | 3.9        | 17.9       | 2005-01-01T00:00:00      | 2013-04-11T00:00:00 | United States | ES_1071110_GC-42-XXXXX-DW_05012013153018_6038172 | No                            | 
```