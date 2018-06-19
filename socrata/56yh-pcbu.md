# ENERGY STAR Certified Commercial Water Heaters

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/energy-star-certified-commercial-water-heaters) |
| Metadata | [Link](https://data.energystar.gov/api/views/56yh-pcbu) |
| Data: JSON | [100 Rows](https://data.energystar.gov/api/views/56yh-pcbu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.energystar.gov/api/views/56yh-pcbu/rows.csv?max_rows=100) |
| Host | data.energystar.gov |
| Id | 56yh-pcbu |
| Name | ENERGY STAR Certified Commercial Water Heaters |
| Category | Active Specifications |
| Tags | commercial water heaters |
| Created | 2013-06-05T19:09:44Z |
| Publication Date | 2016-08-19T16:01:40Z |

## Description

Certified models meet all ENERGY STAR requirements as listed in the Version 1.0 ENERGY STAR Program Requirements for Commercial Water Heaters that are effective as of February 18, 2013. A detailed listing of key efficiency criteria are available at http://www.energystar.gov/index.cfm?fuseaction=find_a_product.showProductGroup&pgw_code=CWH#specs

## Columns

```ls
| Included | Schema Type    | Field Name                       | Name                         | Data Type     | Render Type   |
| ======== | ============== | ================================ | ============================ | ============= | ============= |
| Yes      | series tag     | pd_id                            | ENERGY STAR Unique ID        | text          | number        |
| Yes      | series tag     | energy_star_partner              | ENERGY STAR Partner          | text          | text          |
| Yes      | series tag     | brand_name                       | Brand Name                   | text          | text          |
| Yes      | series tag     | model_name                       | Model Name                   | text          | text          |
| Yes      | series tag     | model_number                     | Model Number                 | text          | text          |
| Yes      | series tag     | additional_model_information     | Additional Model Information | text          | text          |
| Yes      | series tag     | type                             | Type                         | text          | text          |
| Yes      | series tag     | fuel                             | Fuel                         | text          | text          |
| Yes      | series tag     | vent_type                        | Vent Type                    | text          | text          |
| Yes      | numeric metric | storage_volume_gallons           | Storage Volume (gallons)     | number        | number        |
| Yes      | numeric metric | tank_height_inches               | Tank Height (in.)            | number        | number        |
| Yes      | numeric metric | height_to_vent_inches            | Height to Vent (in.)         | number        | number        |
| Yes      | numeric metric | tank_diameter_inches             | Tank Diameter (in.)          | number        | number        |
| Yes      | numeric metric | vent_size_inches                 | Vent Size (in.)              | number        | number        |
| Yes      | numeric metric | vent_size_2_inches               | Vent Size 2 (in.)            | number        | number        |
| Yes      | numeric metric | input_rate_thousand_btu_per_hour | Input Rate (kBtu/hr)         | number        | number        |
| Yes      | numeric metric | thermal_efficiency_te            | Thermal Efficiency (TE)      | number        | number        |
| Yes      | numeric metric | standby_loss                     | Standby Loss                 | number        | number        |
| Yes      | series tag     | energy_factor_ef                 | Energy Factor (EF)           | text          | text          |
| Yes      | numeric metric | therms_year_for_natural_gas      | Therms/year for Natural Gas  | number        | text          |
| Yes      | time           | date_available_on_market         | Date Available On Market     | calendar_date | calendar_date |
| No       |                | date_qualified                   | Date Qualified               | calendar_date | calendar_date |
| Yes      | series tag     | markets                          | Markets                      | text          | text          |
| Yes      | series tag     | energy_star_model_identifier     | CB Model Identifier          | text          | text          |
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
series e:56yh-pcbu d:2007-02-12T00:00:00.000Z t:energy_star_partner="A.O. Smith Corporation" t:model_number="HCG3130T3003N *" t:vent_type="Power Vent" t:markets="United States, Canada" t:energy_star_model_identifier=ES_92897_05062013103758_3099260 t:fuel=Gas t:type="Gas Storage" t:brand_name=American t:model_name="HCG3130T3003N *" t:pd_id=2180681 m:tank_diameter_inches=30 m:height_to_vent_inches=12 m:vent_size_2_inches=6 m:storage_volume_gallons=119 m:tank_height_inches=63.5 m:standby_loss=1084 m:input_rate_thousand_btu_per_hour=300 m:vent_size_inches=4 m:thermal_efficiency_te=0.96

series e:56yh-pcbu d:2007-02-12T00:00:00.000Z t:energy_star_partner="A.O. Smith Corporation" t:model_number="HCG3130T3003P *" t:vent_type="Power Vent" t:markets="United States, Canada" t:energy_star_model_identifier=ES_92897_05062013103758_9447596 t:fuel=Propane t:type="Gas Storage" t:brand_name=American t:model_name="HCG3130T3003P *" t:pd_id=2180682 m:tank_diameter_inches=30 m:height_to_vent_inches=12 m:vent_size_2_inches=6 m:storage_volume_gallons=119 m:tank_height_inches=63.5 m:standby_loss=1084 m:input_rate_thousand_btu_per_hour=300 m:vent_size_inches=4 m:thermal_efficiency_te=0.96

series e:56yh-pcbu d:2007-02-12T00:00:00.000Z t:energy_star_partner="A.O. Smith Corporation" t:model_number="SUF 130 300 NE *" t:vent_type="Power Vent" t:markets="United States, Canada" t:energy_star_model_identifier=ES_92897_05062013103758_9001636 t:fuel=Gas t:type="Gas Storage" t:brand_name=State t:model_name="SUF 130 300 NE *" t:pd_id=2180683 m:tank_diameter_inches=30 m:height_to_vent_inches=12 m:vent_size_2_inches=6 m:storage_volume_gallons=119 m:tank_height_inches=63.5 m:standby_loss=1084 m:input_rate_thousand_btu_per_hour=300 m:vent_size_inches=4 m:thermal_efficiency_te=0.96
```

## Meta Commands

```ls
metric m:storage_volume_gallons p:integer l:"Storage Volume (gallons)" d:"Volume is the capacity of the tank, in gallons. Volume is not applicable to gas tankless water heaters." t:dataTypeName=number

metric m:tank_height_inches p:double l:"Tank Height (in.)" d:"Tank height is the distance from the bottom of the water heater's tank to the top of its tank." t:dataTypeName=number

metric m:height_to_vent_inches p:double l:"Height to Vent (in.)" d:"Height to vent is the distance from the bottom of the water heater's tank to its vent." t:dataTypeName=number

metric m:tank_diameter_inches p:double l:"Tank Diameter (in.)" d:"Tank diameter is the width or diameter of the water heater?s tank." t:dataTypeName=number

metric m:vent_size_inches p:double l:"Vent Size (in.)" d:"Vent size is the width or diameter of the vent opening." t:dataTypeName=number

metric m:vent_size_2_inches p:integer l:"Vent Size 2 (in.)" d:"Vent size 2 is the width or diameter of a second vent opening." t:dataTypeName=number

metric m:input_rate_thousand_btu_per_hour p:double l:"Input Rate (kBtu/hr)" d:"Input refers to the burner size of the water heater, in thousand BTU per hour." t:dataTypeName=number

metric m:thermal_efficiency_te p:double l:"Thermal Efficiency (TE)" d:"The ratio of the heat transferred to the water flowing through the water heater to the amount of energy consumed by the water heater." t:dataTypeName=number

metric m:standby_loss p:integer l:"Standby Loss" d:"The ratio of useful energy output from the water heater to the total amount of energy delivered to the water heater." t:dataTypeName=number

metric m:therms_year_for_natural_gas p:integer l:"Therms/year for Natural Gas" d:"Therms/year refers to the amount of natural gas consumed by the water heater according to its Energy Factor determined by the DOE test procedure, Code of Federal Regulations, Title 10, Section 430." t:dataTypeName=number

entity e:56yh-pcbu l:"ENERGY STAR Certified Commercial Water Heaters" t:url=https://data.energystar.gov/api/views/56yh-pcbu

property e:56yh-pcbu t:meta.view v:id=56yh-pcbu v:category="Active Specifications" v:averageRating=0 v:name="ENERGY STAR Certified Commercial Water Heaters"

property e:56yh-pcbu t:meta.view.owner v:id=guxy-scz5 v:screenName=ESddas v:lastNotificationSeenAt=1491492552 v:displayName=ESddas

property e:56yh-pcbu t:meta.view.tableauthor v:id=guxy-scz5 v:screenName=ESddas v:roleName=publisher v:lastNotificationSeenAt=1491492552 v:displayName=ESddas

property e:56yh-pcbu t:meta.view.metadata.custom_fields.common_core v:Publisher="U.S. Environmental Protection Agency" v:License=https://edg.epa.gov/EPA_Data_License.html v:Contact_Name="Kathleen Vokes" v:Bureau_Code=020:00 v:Program_Code=020:033
```

## Top Records

```ls
| pd_id   | energy_star_partner    | brand_name | model_name       | model_number     | additional_model_information | type        | fuel    | vent_type  | storage_volume_gallons | tank_height_inches | height_to_vent_inches | tank_diameter_inches | vent_size_inches | vent_size_2_inches | input_rate_thousand_btu_per_hour | thermal_efficiency_te | standby_loss | energy_factor_ef | therms_year_for_natural_gas | date_available_on_market | date_qualified      | markets               | energy_star_model_identifier    | 
| ======= | ====================== | ========== | ================ | ================ | ============================ | =========== | ======= | ========== | ====================== | ================== | ===================== | ==================== | ================ | ================== | ================================ | ===================== | ============ | ================ | =========================== | ======================== | =================== | ===================== | =============================== | 
| 2180681 | A.O. Smith Corporation | American   | HCG3130T3003N *  | HCG3130T3003N *  |                              | Gas Storage | Gas     | Power Vent | 119                    | 63.5               | 12                    | 30                   | 4                | 6                  | 300                              | 0.96                  | 1084         |                  |                             | 2007-02-12T00:00:00      | 2013-05-06T00:00:00 | United States, Canada | ES_92897_05062013103758_3099260 | 
| 2180682 | A.O. Smith Corporation | American   | HCG3130T3003P *  | HCG3130T3003P *  |                              | Gas Storage | Propane | Power Vent | 119                    | 63.5               | 12                    | 30                   | 4                | 6                  | 300                              | 0.96                  | 1084         |                  |                             | 2007-02-12T00:00:00      | 2013-05-06T00:00:00 | United States, Canada | ES_92897_05062013103758_9447596 | 
| 2180683 | A.O. Smith Corporation | State      | SUF 130 300 NE * | SUF 130 300 NE * |                              | Gas Storage | Gas     | Power Vent | 119                    | 63.5               | 12                    | 30                   | 4                | 6                  | 300                              | 0.96                  | 1084         |                  |                             | 2007-02-12T00:00:00      | 2013-05-06T00:00:00 | United States, Canada | ES_92897_05062013103758_9001636 | 
| 2180684 | A.O. Smith Corporation | State      | SUF 130 300 PE * | SUF 130 300 PE * |                              | Gas Storage | Propane | Power Vent | 119                    | 63.5               | 12                    | 30                   | 4                | 6                  | 300                              | 0.96                  | 1084         |                  |                             | 2007-02-12T00:00:00      | 2013-05-06T00:00:00 | United States, Canada | ES_92897_05062013103758_7113840 | 
| 2180689 | A.O. Smith Corporation | American   | HCG3130T4003N *  | HCG3130T4003N *  |                              | Gas Storage | Gas     | Power Vent | 119                    | 63.5               | 12                    | 30                   | 4                | 6                  | 399.9                            | 0.95                  | 1100         |                  |                             | 2007-02-12T00:00:00      | 2013-05-06T00:00:00 | United States, Canada | ES_92897_05062013103758_4703831 | 
| 2180690 | A.O. Smith Corporation | American   | HCG3130T4003P *  | HCG3130T4003P *  |                              | Gas Storage | Propane | Power Vent | 119                    | 63.5               | 12                    | 30                   | 4                | 6                  | 399.9                            | 0.95                  | 1100         |                  |                             | 2007-02-12T00:00:00      | 2013-05-06T00:00:00 | United States, Canada | ES_92897_05062013103758_3742367 | 
| 2180691 | A.O. Smith Corporation | State      | SUF 130 400 NE * | SUF 130 400 NE * |                              | Gas Storage | Gas     | Power Vent | 119                    | 63.5               | 12                    | 30                   | 4                | 6                  | 399.9                            | 0.95                  | 1100         |                  |                             | 2007-02-12T00:00:00      | 2013-05-06T00:00:00 | United States, Canada | ES_92897_05062013103758_1608009 | 
| 2180692 | A.O. Smith Corporation | State      | SUF 130 400 PE * | SUF 130 400 PE * |                              | Gas Storage | Propane | Power Vent | 119                    | 63.5               | 12                    | 30                   | 4                | 6                  | 399.9                            | 0.95                  | 1100         |                  |                             | 2007-02-12T00:00:00      | 2013-05-06T00:00:00 | United States, Canada | ES_92897_05062013103758_7244694 | 
| 2180695 | A.O. Smith Corporation | American   | AHCG3130T4003N * | AHCG3130T4003N * |                              | Gas Storage | Gas     | Power Vent | 130                    | 63.5               | 12                    | 30                   | 4                | 6                  | 399.9                            | 0.95                  | 1100         |                  |                             | 2007-02-12T00:00:00      | 2013-05-06T00:00:00 | United States, Canada | ES_92897_05062013103758_3917797 | 
| 2180696 | A.O. Smith Corporation | American   | AHCG3130T4003P * | AHCG3130T4003P * |                              | Gas Storage | Propane | Power Vent | 130                    | 63.5               | 12                    | 30                   | 4                | 6                  | 399.9                            | 0.95                  | 1100         |                  |                             | 2007-02-12T00:00:00      | 2013-05-06T00:00:00 | United States, Canada | ES_92897_05062013103758_6924748 | 
```