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
series e:acvd-5wvz d:2016-04-13T00:00:00.000Z t:energy_star_partner="Carrier Corporation" t:model_number=HB048H/V* t:markets="United States, Canada" t:energy_star_model_identifier=ES_1020846_08122016172439_9952294 t:product_type="Closed Loop Water-to-Air" t:meets_most_efficient_criteria=No t:model_name=HB t:brand_name=Arcoaire t:pd_id=2274962 m:cop_rating=3.7 m:eer_rating=20

series e:acvd-5wvz d:2016-04-13T00:00:00.000Z t:energy_star_partner="Carrier Corporation" t:model_number=HB060H/V* t:markets="United States, Canada" t:energy_star_model_identifier=ES_1020846_08122016172440_7907956 t:product_type="Open Loop Water-to-Air" t:meets_most_efficient_criteria=No t:model_name=HB t:brand_name=Arcoaire t:pd_id=2274973 m:cop_rating=4.9 m:eer_rating=24.1

series e:acvd-5wvz d:2016-04-13T00:00:00.000Z t:energy_star_partner="Carrier Corporation" t:model_number=HB060H/V* t:markets="United States, Canada" t:energy_star_model_identifier=ES_1020846_08122016172440_8549659 t:product_type="Closed Loop Water-to-Air" t:meets_most_efficient_criteria=No t:model_name=HB t:brand_name=Arcoaire t:pd_id=2274974 m:cop_rating=4.2 m:eer_rating=18.5
```

## Meta Commands

```ls
metric m:cop_rating p:float l:"COP Rating" d:"A measure of efficiency in the heating mode that represents the ratio of total heating capacity to electrical energy input." t:dataTypeName=number

metric m:eer_rating p:float l:"Energy Efficiency (EER)" d:"A measure of efficiency in the cooling mode that represents the ratio of total cooling capacity to electrical energy input." t:dataTypeName=number

entity e:acvd-5wvz l:"ENERGY STAR Certified Geothermal Heat Pumps" t:url=https://data.energystar.gov/api/views/acvd-5wvz

property e:acvd-5wvz t:meta.view v:id=acvd-5wvz v:category="Active Specifications" v:averageRating=0 v:name="ENERGY STAR Certified Geothermal Heat Pumps"

property e:acvd-5wvz t:meta.view.owner v:id=guxy-scz5 v:screenName=ESddas v:displayName=ESddas

property e:acvd-5wvz t:meta.view.tableauthor v:id=guxy-scz5 v:screenName=ESddas v:roleName=publisher v:displayName=ESddas

property e:acvd-5wvz t:meta.view.metadata.custom_fields.common_core v:Publisher="U.S. Environmental Protection Agency" v:License=https://edg.epa.gov/EPA_Data_License.html v:Contact_Name="Kathleen Vokes" v:Bureau_Code=020:00 v:Program_Code=020:033
```

## Top Records

```ls
| pd_id   | energy_star_partner | brand_name | model_name | model_number | additional_model_information | product_type             | cop_rating | eer_rating | date_available_on_market | date_qualified      | markets               | energy_star_model_identifier      | meets_most_efficient_criteria | 
| ======= | =================== | ========== | ========== | ============ | ============================ | ======================== | ========== | ========== | ======================== | =================== | ===================== | ================================= | ============================= | 
| 2274962 | Carrier Corporation | Arcoaire   | HB         | HB048H/V*    |                              | Closed Loop Water-to-Air | 3.7        | 20         | 2016-04-13T00:00:00      | 2016-08-12T00:00:00 | United States, Canada | ES_1020846_08122016172439_9952294 | No                            | 
| 2274973 | Carrier Corporation | Arcoaire   | HB         | HB060H/V*    |                              | Open Loop Water-to-Air   | 4.9        | 24.1       | 2016-04-13T00:00:00      | 2016-08-12T00:00:00 | United States, Canada | ES_1020846_08122016172440_7907956 | No                            | 
| 2274974 | Carrier Corporation | Arcoaire   | HB         | HB060H/V*    |                              | Closed Loop Water-to-Air | 4.2        | 18.5       | 2016-04-13T00:00:00      | 2016-08-12T00:00:00 | United States, Canada | ES_1020846_08122016172440_8549659 | No                            | 
| 2274985 | Carrier Corporation | Arcoaire   | HB         | HB072H/V*    |                              | Open Loop Water-to-Air   | 5          | 22.4       | 2016-04-13T00:00:00      | 2016-08-12T00:00:00 | United States, Canada | ES_1020846_08122016172440_5544160 | No                            | 
| 2274986 | Carrier Corporation | Arcoaire   | HB         | HB072H/V*    |                              | Closed Loop Water-to-Air | 4.2        | 18.5       | 2016-04-13T00:00:00      | 2016-08-12T00:00:00 | United States, Canada | ES_1020846_08122016172440_7250497 | No                            | 
| 2275017 | Carrier Corporation | Arcoaire   | HP         | HP024D/H/V   |                              | Open Loop Water-to-Air   | 4.6        | 27         | 2016-04-13T00:00:00      | 2016-08-12T00:00:00 | United States, Canada | ES_1020846_08122016172441_8112898 | No                            | 
| 2275018 | Carrier Corporation | Arcoaire   | HP         | HP024D/H/V   |                              | Closed Loop Water-to-Air | 3.9        | 21.6       | 2016-04-13T00:00:00      | 2016-08-12T00:00:00 | United States, Canada | ES_1020846_08122016172441_1423517 | No                            | 
| 2275029 | Carrier Corporation | Arcoaire   | HP         | HP036D/H/V   |                              | Open Loop Water-to-Air   | 4.3        | 24.8       | 2016-04-13T00:00:00      | 2016-08-12T00:00:00 | United States, Canada | ES_1020846_08122016172442_9121293 | No                            | 
| 2275030 | Carrier Corporation | Arcoaire   | HP         | HP036D/H/V   |                              | Closed Loop Water-to-Air | 3.9        | 20.8       | 2016-04-13T00:00:00      | 2016-08-12T00:00:00 | United States, Canada | ES_1020846_08122016172442_3497749 | No                            | 
| 2275041 | Carrier Corporation | Arcoaire   | HP         | HP048D/H/V   |                              | Open Loop Water-to-Air   | 4.4        | 21.5       | 2016-04-13T00:00:00      | 2016-08-12T00:00:00 | United States, Canada | ES_1020846_08122016172442_4333309 | No                            | 
```