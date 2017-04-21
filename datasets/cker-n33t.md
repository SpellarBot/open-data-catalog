# ENERGY STAR Certified Non-AHRI Central Air Conditioner Equipment and Air Source Heat Pump

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/energy-star-certified-non-ahri-central-air-conditioner-equipment-and-air-source-heat-pump) |
| Metadata | [Link](https://data.energystar.gov/api/views/cker-n33t) |
| Data: JSON | [100 Rows](https://data.energystar.gov/api/views/cker-n33t/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.energystar.gov/api/views/cker-n33t/rows.csv?max_rows=100) |
| Host | data.energystar.gov |
| Id | cker-n33t |
| Name | ENERGY STAR Certified Non-AHRI Central Air Conditioner Equipment and Air Source Heat Pump |
| Category | Active Specifications |
| Tags | non-ahri central air conditioner equipment and air source heat pumps |
| Created | 2013-07-18T15:37:49Z |
| Publication Date | 2016-08-19T17:46:53Z |

## Description

Certified models meet all ENERGY STAR requirements as listed in the Version 5.0 ENERGY STAR Program Requirements for Air Source Heat Pump and Central Air Conditioner Equipment that are effective as of September 15, 2015. A detailed listing of key efficiency criteria are available at http://www.energystar.gov/index.cfm?c=airsrc_heat.pr_crit_as_heat_pumps Listed products have been submitted to EPA by ENERGY STAR partners that do not participate in the AHRI certification program. EPA will continue to update this list with products that are certified by EPA-recognized certification bodies other than AHRI. The majority of ENERGY STAR products, certified by AHRI, can be found on the CEE/AHRI Verified Directory at http://www.ceedirectory.org/

## Columns

```ls
| Included | Schema Type    | Field Name                    | Name                                           | Data Type     | Render Type   |
| ======== | ============== | ============================= | ============================================== | ============= | ============= |
| Yes      | series tag     | pd_id                         | ENERGY STAR Unique ID                          | text          | number        |
| Yes      | series tag     | manufacturer_type             | Manufacturer Type                              | text          | text          |
| Yes      | series tag     | energy_star_partner           | ENERGY STAR Partner                            | text          | text          |
| Yes      | series tag     | brand_name                    | Brand Name                                     | text          | text          |
| Yes      | series tag     | outdoor_unit_manufacturer     | Outdoor Unit Manufacturer                      | text          | text          |
| Yes      | series tag     | outdoor_model_name            | Outdoor Model Name                             | text          | text          |
| Yes      | series tag     | model_number                  | Outdoor Unit Model Number                      | text          | text          |
| Yes      | series tag     | model_name                    | Indoor Model Name                              | text          | text          |
| Yes      | series tag     | indoor_unit_model_number      | Indoor Unit Model Number                       | text          | text          |
| Yes      | series tag     | additional_model_information  | Additional Model Information                   | text          | text          |
| Yes      | series tag     | product_type                  | Product Type                                   | text          | text          |
| Yes      | numeric metric | seer_btu_wh                   | SEER (Btu/Wh)                                  | number        | number        |
| Yes      | numeric metric | eer_btu_wh                    | EER (Btu/Wh)                                   | number        | number        |
| Yes      | numeric metric | hspf_btu_wh                   | HSPF (Btu/Wh)                                  | number        | number        |
| Yes      | numeric metric | capacity_btu_h                | Capacity (Btu/h)                               | number        | number        |
| Yes      | time           | date_available_on_market      | Date Available on Market                       | calendar_date | calendar_date |
| No       |                | date_qualified                | Date Qualified                                 | calendar_date | calendar_date |
| Yes      | series tag     | markets                       | Markets                                        | text          | text          |
| Yes      | series tag     | energy_star_model_identifier  | CB Model Identifier                            | text          | text          |
| Yes      | series tag     | meets_most_efficient_criteria | Meets ENERGY STAR Most Efficient 2016 Criteria | text          | text          |
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
series e:cker-n33t d:2015-03-01T00:00:00.000Z t:energy_star_partner=Panasonic t:model_number=CS-E12RKUAW/CU-E12RKUA t:markets="United States, Canada" t:energy_star_model_identifier=ES_0031845_CS-E12RKUAW/CU-E12RKUA_10012015105451_2741067 t:product_type="ASHP - Split System" t:indoor_unit_model_number=CS-E12RKUAW t:meets_most_efficient_criteria=No t:manufacturer_type="System Manufacturer" t:brand_name=Panasonic t:model_name=CS-E12RKUAW/CU-E12RKUA t:pd_id=2248992 m:eer_btu_wh=12.5 m:hspf_btu_wh=11 m:seer_btu_wh=22.5 m:capacity_btu_h=12000

series e:cker-n33t d:2012-05-10T00:00:00.000Z t:energy_star_partner=Panasonic t:model_number="CS-E18NKUA / CU-E18NKUA" t:markets="United States" t:energy_star_model_identifier="ES_0031845_CS-E18NKUA / CU-E18NKUA_10012015105451_205454-2510320" t:product_type="ASHP - Split System" t:indoor_unit_model_number=CS-E18NKUA t:meets_most_efficient_criteria=No t:manufacturer_type="System Manufacturer" t:brand_name=Panasonic t:model_name="CS-E18NKUA / CU-E18NKUA" t:pd_id=2248988 m:eer_btu_wh=13.15 m:hspf_btu_wh=8.5 m:seer_btu_wh=18 m:capacity_btu_h=17100

series e:cker-n33t d:2015-03-01T00:00:00.000Z t:energy_star_partner=Panasonic t:model_number=CS-E18RKUAW/CU-E18RKUA t:markets="United States, Canada" t:energy_star_model_identifier=ES_0031845_CS-E18RKUAW/CU-E18RKUA_10012015105451_2741067 t:product_type="ASHP - Split System" t:indoor_unit_model_number=CS-E18RKUAW t:meets_most_efficient_criteria=No t:manufacturer_type="System Manufacturer" t:brand_name=Panasonic t:model_name=CS-E18RKUAW/CU-E18RKUA t:pd_id=2248993 m:eer_btu_wh=13.2 m:hspf_btu_wh=10 m:seer_btu_wh=19.5 m:capacity_btu_h=18000
```

## Meta Commands

```ls
metric m:seer_btu_wh p:float l:"SEER (Btu/Wh)" d:"This is a measure of equipment energy efficiency over the cooling season. It represents the total cooling of a central air conditioner or heat pump (in Btu) during the normal cooling season as compared to the total electric energy input (in watt-hours) consumed during the same period." t:dataTypeName=number

metric m:eer_btu_wh p:float l:"EER (Btu/Wh)" d:"This is a measure of the instantaneous energy efficiency of cooling equipment. EER is the steady-state rate of heat energy removal (e.g., cooling capacity) by the equipment in Btu/h divided by the steady-state rate of energy input to the equipment in watts. This ratio is expressed in Btus per watt-hour (Btu/Wh)." t:dataTypeName=number

metric m:hspf_btu_wh p:double l:"HSPF (Btu/Wh)" d:"This is a measure of a heat pump's energy efficiency over one heating season. It represents the total heating output of a heat pump (including supplementary electric heat) during the normal heating season (in Btu) as compared to the total electricity consumed (in watt-hours) during the same period." t:dataTypeName=number

metric m:capacity_btu_h p:integer l:"Capacity (Btu/h)" d:"Capacity is defined as the quantity of heat required to raise 1 pound of water by 1 degree Fahrenheit in one hour." t:dataTypeName=number

entity e:cker-n33t l:"ENERGY STAR Certified Non-AHRI Central Air Conditioner Equipment and Air Source Heat Pump" t:url=https://data.energystar.gov/api/views/cker-n33t

property e:cker-n33t t:meta.view v:id=cker-n33t v:category="Active Specifications" v:averageRating=0 v:name="ENERGY STAR Certified Non-AHRI Central Air Conditioner Equipment and Air Source Heat Pump"

property e:cker-n33t t:meta.view.owner v:id=guxy-scz5 v:screenName=ESddas v:lastNotificationSeenAt=1491492552 v:displayName=ESddas

property e:cker-n33t t:meta.view.tableauthor v:id=guxy-scz5 v:screenName=ESddas v:roleName=publisher v:lastNotificationSeenAt=1491492552 v:displayName=ESddas

property e:cker-n33t t:meta.view.metadata.custom_fields.common_core v:Publisher="U.S. Environmental Protection Agency" v:License=https://edg.epa.gov/EPA_Data_License.html v:Contact_Name="Kathleen Vokes" v:Bureau_Code=020:00 v:Program_Code=020:033
```

## Top Records

```ls
| pd_id   | manufacturer_type   | energy_star_partner | brand_name | outdoor_unit_manufacturer | outdoor_model_name | model_number              | model_name                | indoor_unit_model_number | additional_model_information | product_type        | seer_btu_wh | eer_btu_wh | hspf_btu_wh | capacity_btu_h | date_available_on_market | date_qualified      | markets               | energy_star_model_identifier                                     | meets_most_efficient_criteria | 
| ======= | =================== | =================== | ========== | ========================= | ================== | ========================= | ========================= | ======================== | ============================ | =================== | =========== | ========== | =========== | ============== | ======================== | =================== | ===================== | ================================================================ | ============================= | 
| 2248992 | System Manufacturer | Panasonic           | Panasonic  |                           |                    | CS-E12RKUAW/CU-E12RKUA    | CS-E12RKUAW/CU-E12RKUA    | CS-E12RKUAW              |                              | ASHP - Split System | 22.5        | 12.5       | 11          | 12000          | 2015-03-01T00:00:00      | 2015-10-01T00:00:00 | United States, Canada | ES_0031845_CS-E12RKUAW/CU-E12RKUA_10012015105451_2741067         | No                            | 
| 2248988 | System Manufacturer | Panasonic           | Panasonic  |                           |                    | CS-E18NKUA / CU-E18NKUA   | CS-E18NKUA / CU-E18NKUA   | CS-E18NKUA               |                              | ASHP - Split System | 18          | 13.15      | 8.5         | 17100          | 2012-05-10T00:00:00      | 2015-10-01T00:00:00 | United States         | ES_0031845_CS-E18NKUA / CU-E18NKUA_10012015105451_205454-2510320 | No                            | 
| 2248993 | System Manufacturer | Panasonic           | Panasonic  |                           |                    | CS-E18RKUAW/CU-E18RKUA    | CS-E18RKUAW/CU-E18RKUA    | CS-E18RKUAW              |                              | ASHP - Split System | 19.5        | 13.2       | 10          | 18000          | 2015-03-01T00:00:00      | 2015-10-01T00:00:00 | United States, Canada | ES_0031845_CS-E18RKUAW/CU-E18RKUA_10012015105451_2741067         | No                            | 
| 2248985 | System Manufacturer | Panasonic           | Panasonic  |                           |                    | CS-E9NKUAW / CU-E9NKUA    | CS-E9NKUAW / CU-E9NKUA    | CS-E9NKUAW               |                              | ASHP - Split System | 21          | 13.05      | 10.5        | 8500           | 2011-12-01T00:00:00      | 2015-10-01T00:00:00 | United States         | ES_0031845_CS-E9NKUAW / CU-E9NKUA_10012015105451_254487-2473041  | No                            | 
| 2248991 | System Manufacturer | Panasonic           | Panasonic  |                           |                    | CS-E9RKUAW/CU-E9RKUA      | CS-E9RKUAW/CU-E9RKUA      | CS-E9RKUAW               |                              | ASHP - Split System | 23          | 13         | 11          | 9000           | 2015-03-01T00:00:00      | 2015-10-01T00:00:00 | United States, Canada | ES_0031845_CS-E9RKUAW/CU-E9RKUA_10012015105451_2741067           | No                            | 
| 2248987 | System Manufacturer | Panasonic           | Panasonic  |                           |                    | CS-S18NKUA / CU-S18NKUA   | CS-S18NKUA / CU-S18NKUA   | CS-S18NKUA               |                              | CAC - Split System  | 18          | 13.15      |             | 17100          | 2012-05-10T00:00:00      | 2015-10-01T00:00:00 | United States         | ES_0031845_CS-S18NKUA / CU-S18NKUA_10012015105451_205454-2510320 | No                            | 
| 2248986 | System Manufacturer | Panasonic           | Panasonic  |                           |                    | CS-S9NKUA / CU-S9NKUA     | CS-S9NKUA / CU-S9NKUA     | CS-S9NKUA                |                              | CAC - Split System  | 21          | 13.05      |             | 8500           | 2011-12-01T00:00:00      | 2015-10-01T00:00:00 | United States         | ES_0031845_CS-S9NKUA / CU-S9NKUA_10012015105451_254487-2473041   | No                            | 
| 2248984 | System Manufacturer | Panasonic           | Panasonic  |                           |                    | CS-XE12PKUA / CU-XE12PKUA | CS-XE12PKUA / CU-XE12PKUA | CS-XE12PKUA              |                              | ASHP - Split System | 25.5        | 14.35      | 12          | 11500          | 2013-06-01T00:00:00      | 2015-10-01T00:00:00 | United States, Canada | ES_0031845_CS-XE12PKUA / CU-XE12PKUA_10012015105451_2604004      | No                            | 
| 2257232 | System Manufacturer | Panasonic           | Panasonic  |                           |                    | CS-XE12SKUA / CU-XE12SKUA | CS-XE12SKUA / CU-XE12SKUA | CS-XE12SKUA              |                              | ASHP - Split System | 26.2        | 14.7       | 12.5        | 11500          | 2016-01-15T00:00:00      | 2015-12-16T00:00:00 | United States, Canada | ES_0031845_CS-XE12SKUA / CU-XE12SKUA_01222016070412_70057345     | No                            | 
| 2248983 | System Manufacturer | Panasonic           | Panasonic  |                           |                    | CS-XE9PKUA / CU-XE9PKUA   | CS-XE9PKUA / CU-XE9PKUA   | CS-XE9PKUA               |                              | ASHP - Split System | 28.5        | 16.1       | 12.5        | 8700           | 2013-06-01T00:00:00      | 2015-10-01T00:00:00 | United States, Canada | ES_0031845_CS-XE9PKUA / CU-XE9PKUA_10012015105451_2604004        | No                            | 
```