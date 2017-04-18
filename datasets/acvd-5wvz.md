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
series e:acvd-5wvz d:2014-05-12T00:00:00.000Z t:energy_star_partner="Carrier Corporation" t:model_number=GS060**1*X1 t:markets="United States, Canada" t:energy_star_model_identifier=ES_1020846_12082014152247_1620760 t:product_type="Open Loop Water-to-Air" t:meets_most_efficient_criteria=No t:model_name=GS t:brand_name=Bryant t:pd_id=2226833 m:cop_rating=4.1 m:eer_rating=22.3

series e:acvd-5wvz d:2014-05-12T00:00:00.000Z t:energy_star_partner="Carrier Corporation" t:model_number=GS060**1*X1 t:markets="United States, Canada" t:energy_star_model_identifier=ES_1020846_12082014152247_7584783 t:product_type="Open Loop Water-to-Air" t:meets_most_efficient_criteria=No t:model_name=GS t:brand_name=Bryant t:pd_id=2226835 m:cop_rating=4.5 m:eer_rating=23.8

series e:acvd-5wvz d:2014-05-12T00:00:00.000Z t:energy_star_partner="Carrier Corporation" t:model_number=GS060**1*X1 t:markets="United States, Canada" t:energy_star_model_identifier=ES_1020846_12082014152246_8380148 t:product_type="Closed Loop Water-to-Air" t:meets_most_efficient_criteria=No t:model_name=GS t:brand_name=Bryant t:pd_id=2226855 m:cop_rating=3.6 m:eer_rating=18.9
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
| pd_id   | energy_star_partner | brand_name | model_name | model_number         | additional_model_information | product_type             | cop_rating | eer_rating | date_available_on_market | date_qualified      | markets               | energy_star_model_identifier      | meets_most_efficient_criteria | 
| ======= | =================== | ========== | ========== | ==================== | ============================ | ======================== | ========== | ========== | ======================== | =================== | ===================== | ================================= | ============================= | 
| 2226833 | Carrier Corporation | Bryant     | GS         | GS060**1*X1          |                              | Open Loop Water-to-Air   | 4.1        | 22.3       | 2014-05-12T00:00:00      | 2014-12-08T00:00:00 | United States, Canada | ES_1020846_12082014152247_1620760 | No                            | 
| 2226835 | Carrier Corporation | Bryant     | GS         | GS060**1*X1          |                              | Open Loop Water-to-Air   | 4.5        | 23.8       | 2014-05-12T00:00:00      | 2014-12-08T00:00:00 | United States, Canada | ES_1020846_12082014152247_7584783 | No                            | 
| 2226855 | Carrier Corporation | Bryant     | GS         | GS060**1*X1          |                              | Closed Loop Water-to-Air | 3.6        | 18.9       | 2014-05-12T00:00:00      | 2014-12-08T00:00:00 | United States, Canada | ES_1020846_12082014152246_8380148 | No                            | 
| 2226857 | Carrier Corporation | Bryant     | GS         | GS060**1*X1          |                              | Closed Loop Water-to-Air | 3.9        | 20.2       | 2014-05-12T00:00:00      | 2014-12-08T00:00:00 | United States, Canada | ES_1020846_12082014152246_4742569 | No                            | 
| 2226831 | Carrier Corporation | Bryant     | GS         | GS072**1*X1          |                              | Open Loop Water-to-Air   | 4.3        | 22.2       | 2014-05-12T00:00:00      | 2014-12-08T00:00:00 | United States, Canada | ES_1020846_12082014152247_2341833 | No                            | 
| 2226851 | Carrier Corporation | Bryant     | GS         | GS072**1*X1          |                              | Closed Loop Water-to-Air | 3.6        | 17.1       | 2014-05-12T00:00:00      | 2014-12-08T00:00:00 | United States, Canada | ES_1020846_12082014152246_1498934 | No                            | 
| 2226853 | Carrier Corporation | Bryant     | GS         | GS072**1*X1          |                              | Closed Loop Water-to-Air | 3.8        | 18.6       | 2014-05-12T00:00:00      | 2014-12-08T00:00:00 | United States, Canada | ES_1020846_12082014152246_8407526 | No                            | 
| 2226061 | Carrier Corporation | Bryant     | GT         | GT024C/H/V******1*X1 |                              | Closed Loop Water-to-Air | 4.2        | 24         | 2014-05-12T00:00:00      | 2014-11-26T00:00:00 | United States, Canada | ES_1020846_11262014121038_8669771 | No                            | 
| 2226081 | Carrier Corporation | Bryant     | GT         | GT024C/H/V******1*X1 |                              | Open Loop Water-to-Air   | 5          | 30         | 2014-05-12T00:00:00      | 2014-11-26T00:00:00 | United States, Canada | ES_1020846_11262014121038_5893607 | No                            | 
| 2226075 | Carrier Corporation | Bryant     | GT         | GT036C/H/V******1*X1 |                              | Closed Loop Water-to-Air | 4.5        | 27         | 2014-05-12T00:00:00      | 2014-11-26T00:00:00 | United States, Canada | ES_1020846_11262014121038_7458687 | No                            | 
```