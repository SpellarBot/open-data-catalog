# ENERGY STAR Certified Dehumidifiers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/energy-star-certified-dehumidifiers) |
| Metadata | [Link](https://data.energystar.gov/api/views/mvyi-jgae) |
| Data: JSON | [100 Rows](https://data.energystar.gov/api/views/mvyi-jgae/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.energystar.gov/api/views/mvyi-jgae/rows.csv?max_rows=100) |
| Host | data.energystar.gov |
| Id | mvyi-jgae |
| Name | ENERGY STAR Certified Dehumidifiers |
| Category | Active Specifications |
| Tags | certified dehumidifiers |
| Created | 2013-05-03T20:56:10Z |
| Publication Date | 2016-08-19T16:28:09Z |

## Description

Certified models meet all ENERGY STAR requirements as listed in the Version 3.0 ENERGY STAR Program Requirements for Dehumidifiers that are effective as of October 1, 2012. A detailed listing of key efficiency criteria are available at http://www.energystar.gov/index.cfm?c=dehumid.pr_crit_dehumidifiers

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                               | Data Type     | Render Type   |
| ======== | ============== | ============================ | ================================== | ============= | ============= |
| Yes      | series tag     | pd_id                        | ENERGY STAR Unique ID              | text          | number        |
| Yes      | series tag     | energy_star_partner          | ENERGY STAR Partner                | text          | text          |
| Yes      | series tag     | brand_name                   | Brand Name                         | text          | text          |
| Yes      | series tag     | model_name                   | Model Name                         | text          | text          |
| Yes      | series tag     | model_number                 | Model Number                       | text          | text          |
| Yes      | series tag     | additional_model_information | Additional Model Information       | text          | text          |
| Yes      | numeric metric | energy_factor_l_kwh          | Efficiency (Energy Factor) (L/kWh) | number        | number        |
| Yes      | numeric metric | product_capacity_pints_day   | Water Removal Capacity (pints/day) | number        | number        |
| Yes      | series tag     | fan_continuously_operates    | Fan Continuously Operates?         | text          | text          |
| Yes      | time           | date_available_on_market     | Date Available on Market           | calendar_date | calendar_date |
| No       |                | date_qualified               | Date Qualified                     | calendar_date | calendar_date |
| Yes      | series tag     | markets                      | Markets                            | text          | text          |
| Yes      | series tag     | energy_star_model_identifier | CB Model Identifier                | text          | text          |
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
series e:mvyi-jgae d:2017-03-07T00:00:00.000Z t:additional_model_information=,BHD-701-H, t:energy_star_partner="Heat Controller Inc." t:model_number=BHDP-701-H t:markets="United States" t:energy_star_model_identifier=ES_17771_BHDP-701-H_04182014144137_2097957 t:fan_continuously_operates=Yes t:model_name=Dehumidifier t:brand_name="Comfort Aire" t:pd_id=2292138 m:product_capacity_pints_day=70 m:energy_factor_l_kwh=2

series e:mvyi-jgae d:2013-06-01T00:00:00.000Z t:energy_star_partner="Heat Controller Inc." t:model_number=BHD-301-H t:markets="United States" t:energy_star_model_identifier="ES_1105798_HEAT CONTROLLER INC (75963) | BHD-301-H_05152013162801_5281072" t:fan_continuously_operates=Yes t:model_name=Dehumidifier t:brand_name=Comfort-Aire t:pd_id=2290403 m:product_capacity_pints_day=30 m:energy_factor_l_kwh=2

series e:mvyi-jgae d:2013-06-01T00:00:00.000Z t:additional_model_information=Dehumidifier,BHDP-501-H, t:energy_star_partner="Heat Controller Inc." t:model_number=BHD-501-H t:markets="United States" t:energy_star_model_identifier="ES_1105798_HEAT CONTROLLER INC (75963) | BHD-501-H_05152013162911_5351480" t:fan_continuously_operates=Yes t:model_name=Dehumidifier t:brand_name=Comfort-Aire t:pd_id=2290402 m:product_capacity_pints_day=50 m:energy_factor_l_kwh=2
```

## Meta Commands

```ls
metric m:energy_factor_l_kwh p:float l:"Efficiency (Energy Factor) (L/kWh)" d:"A measure of energy efficiency of a dehumidifier calculated by dividing the water removed from the air by the energy consumed, measured in liters per kilowatt hour (L/kWh)." t:dataTypeName=number

metric m:product_capacity_pints_day p:float l:"Water Removal Capacity (pints/day)" d:"A measure of the ability of a dehumidifier to remove moisture from its surrounding atmosphere, measured in pints collected per 24 hours of continuous operation." t:dataTypeName=number

entity e:mvyi-jgae l:"ENERGY STAR Certified Dehumidifiers" t:url=https://data.energystar.gov/api/views/mvyi-jgae

property e:mvyi-jgae t:meta.view v:id=mvyi-jgae v:category="Active Specifications" v:averageRating=0 v:name="ENERGY STAR Certified Dehumidifiers"

property e:mvyi-jgae t:meta.view.owner v:id=guxy-scz5 v:screenName=ESddas v:lastNotificationSeenAt=1491492552 v:displayName=ESddas

property e:mvyi-jgae t:meta.view.tableauthor v:id=guxy-scz5 v:screenName=ESddas v:roleName=publisher v:lastNotificationSeenAt=1491492552 v:displayName=ESddas

property e:mvyi-jgae t:meta.view.metadata.custom_fields.common_core v:Publisher="U.S. Environmental Protection Agency" v:License=https://edg.epa.gov/EPA_Data_License.html v:Contact_Name="Kathleen Vokes" v:Bureau_Code=020:00 v:Program_Code=020:033
```

## Top Records

```ls
| pd_id   | energy_star_partner          | brand_name         | model_name   | model_number | additional_model_information | energy_factor_l_kwh | product_capacity_pints_day | fan_continuously_operates | date_available_on_market | date_qualified      | markets               | energy_star_model_identifier                                              | 
| ======= | ============================ | ================== | ============ | ============ | ============================ | =================== | ========================== | ========================= | ======================== | =================== | ===================== | ========================================================================= | 
| 2292138 | Heat Controller Inc.         | Comfort Aire       | Dehumidifier | BHDP-701-H   | ,BHD-701-H,                  | 2.0                 | 70.0                       | Yes                       | 2017-03-07T00:00:00      | 2017-03-07T00:00:00 | United States         | ES_17771_BHDP-701-H_04182014144137_2097957                                | 
| 2290403 | Heat Controller Inc.         | Comfort-Aire       | Dehumidifier | BHD-301-H    |                              | 2.0                 | 30.0                       | Yes                       | 2013-06-01T00:00:00      | 2017-02-09T00:00:00 | United States         | ES_1105798_HEAT CONTROLLER INC (75963) | BHD-301-H_05152013162801_5281072 | 
| 2290402 | Heat Controller Inc.         | Comfort-Aire       | Dehumidifier | BHD-501-H    | Dehumidifier,BHDP-501-H,     | 2.0                 | 50.0                       | Yes                       | 2013-06-01T00:00:00      | 2017-02-09T00:00:00 | United States         | ES_1105798_HEAT CONTROLLER INC (75963) | BHD-501-H_05152013162911_5351480 | 
| 2290404 | Heat Controller Inc.         | Comfort-Aire       | Dehumidifier | BHDP-951-H   |                              | 2.8                 | 95.0                       | Yes                       | 2017-01-25T00:00:00      | 2017-02-09T00:00:00 | United States         | ES_17771_BHDP-951-H_02102017083700_5820621                                | 
| 2287584 | Homeeasy Industrial Co., Ltd | Emerson            | Dehumidifier | EAD30E1      |                              | 2.0                 | 30.0                       | Yes                       | 2016-11-30T00:00:00      | 2016-12-26T00:00:00 | United States, Canada | ES_1138039_EAD30E1_12262016112502_1502644                                 | 
| 2287585 | Homeeasy Industrial Co., Ltd | Emerson            | Dehumidifier | EAD50E1      |                              | 2.0                 | 50.0                       | Yes                       | 2016-11-30T00:00:00      | 2016-12-26T00:00:00 | United States, Canada | ES_1138039_EAD50E1_12262016112514_1514047                                 | 
| 2287586 | Homeeasy Industrial Co., Ltd | Emerson            | Dehumidifier | EAD70EP1     | ,EAD70E1,                    | 2.0                 | 70.0                       | Yes                       | 2016-11-30T00:00:00      | 2016-12-26T00:00:00 | United States, Canada | ES_1138039_EAD70EP1_12262016112533_1533475                                | 
| 2294268 | Homeeasy Industrial Co., Ltd | Emerson Quiet Kool | Dehumidifier | E*D30E1      |                              | 2.0                 | 30.0                       | Yes                       | 2017-04-12T00:00:00      | 2017-04-12T00:00:00 | United States, Canada | ES_1138039_E*D30E1_04132017074030_9230914                                 | 
| 2294267 | Homeeasy Industrial Co., Ltd | Emerson Quiet Kool | Dehumidifier | E*D50E1      |                              | 2.0                 | 50.0                       | Yes                       | 2017-04-12T00:00:00      | 2017-04-12T00:00:00 | United States, Canada | ES_1138039_E*D50E1_04132017074044_9244553                                 | 
| 2294265 | Homeeasy Industrial Co., Ltd | Emerson Quiet Kool | Dehumidifier | E*D70EP1     | ,E*D70E1,                    | 2.0                 | 73.0                       | Yes                       | 2017-04-12T00:00:00      | 2017-04-12T00:00:00 | United States, Canada | ES_1138039_E*D70EP1_04132017074059_9259315                                | 
```