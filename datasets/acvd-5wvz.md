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
| Rows Updated | 2017-03-10T14:26:08Z |

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
series e:acvd-5wvz d:2012-10-15T00:00:00.000Z t:energy_star_partner="Bryant Heating and Cooling Systems (Carrier Corporation)" t:model_number=50YGV026 t:markets="United States, Australia, New Zealand, Switzerland, Europe, Taiwan, Japan, Canada" t:energy_star_model_identifier=ES_1019658_11192012172705_5837817 t:product_type="Closed Loop Water-to-Air" t:meets_most_efficient_criteria=No t:model_name=GT-PC t:brand_name=Carrier t:pd_id=2132041 m:cop_rating=4.2 m:eer_rating=23.8

series e:acvd-5wvz d:2016-04-13T00:00:00.000Z t:energy_star_partner="Carrier Corporation" t:model_number=HB018H/V* t:markets="United States, Canada" t:energy_star_model_identifier=ES_1020846_08122016172437_2459551 t:product_type="Open Loop Water-to-Air" t:meets_most_efficient_criteria=No t:model_name=HB t:brand_name=Arcoaire t:pd_id=2274900 m:cop_rating=4.5 m:eer_rating=25.6

series e:acvd-5wvz d:2016-04-13T00:00:00.000Z t:energy_star_partner="Carrier Corporation" t:model_number=HB018H/V* t:markets="United States, Canada" t:energy_star_model_identifier=ES_1020846_08122016172437_9171949 t:product_type="Closed Loop Water-to-Air" t:meets_most_efficient_criteria=No t:model_name=HB t:brand_name=Arcoaire t:pd_id=2274901 m:cop_rating=3.8 m:eer_rating=19
```

## Meta Commands

```ls
metric m:cop_rating l:"COP Rating" d:"A measure of efficiency in the heating mode that represents the ratio of total heating capacity to electrical energy input." t:dataTypeName=number

metric m:eer_rating l:"Energy Efficiency (EER)" d:"A measure of efficiency in the cooling mode that represents the ratio of total cooling capacity to electrical energy input." t:dataTypeName=number

entity e:acvd-5wvz l:"ENERGY STAR Certified Geothermal Heat Pumps" t:url=https://data.energystar.gov/api/views/acvd-5wvz

property e:acvd-5wvz t:meta.view d:2017-03-10T16:17:59.173Z v:id=acvd-5wvz v:category="Active Specifications" v:averageRating=0 v:name="ENERGY STAR Certified Geothermal Heat Pumps"

property e:acvd-5wvz t:meta.view.owner d:2017-03-10T16:17:59.173Z v:id=guxy-scz5 v:screenName=ESddas v:roleName=publisher v:displayName=ESddas

property e:acvd-5wvz t:meta.view.tableauthor d:2017-03-10T16:17:59.173Z v:id=guxy-scz5 v:screenName=ESddas v:roleName=publisher v:displayName=ESddas

property e:acvd-5wvz t:meta.view.metadata.custom_fields.common_core d:2017-03-10T16:17:59.173Z v:Publisher="U.S. Environmental Protection Agency" v:License=https://edg.epa.gov/EPA_Data_License.html v:Contact_Name="Kathleen Vokes" v:Bureau_Code=020:00 v:Program_Code=020:033
```