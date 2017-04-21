# 2009-2013: ECAD Residential Energy Audit Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2009-2013-ecad-residential-energy-audit-data) |
| Metadata | [Link](https://data.austintexas.gov/api/views/me4f-48mc) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/me4f-48mc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/me4f-48mc/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | me4f-48mc |
| Name | 2009-2013: ECAD Residential Energy Audit Data |
| Attribution | Austin Energy |
| Category | Utility |
| Tags | ecad, residential, audit, ordinance, attic insulation, duct leakage, duct insulation, duct blaster, solar shading austin building stock, 20110421-002, austin, climate protection |
| Created | 2014-05-28T19:12:42Z |
| Publication Date | 2014-05-28T19:54:31Z |

## Description

This report is the result of Austin City Code 6-7?s Energy Conservation Audit and Disclosure Ordinance approved in November 2008 (amended in April 2011) to improve the energy efficiency of homes and buildings that receive electricity from Austin Energy. The ordinance meets one of the goals of the Austin Climate Protection Plan, which is to offset 800 megawatts of peak energy demand by 2020. This report contains information on residential dwellings that have reported the results of the ECAD audit (*) to the City of Austin prior to 2014. For information on ECAD exemptions and other requirements, see Austin City Code Chapter 6-7. 
*Note ? (*) Data reported by Residential Energy Auditors

## Columns

```ls
| Included | Schema Type    | Field Name                          | Name                                  | Data Type     | Render Type   |
| ======== | ============== | =================================== | ===================================== | ============= | ============= |
| Yes      | series tag     | tcad_or_wcad_property_id_s          | TCAD or WCAD Property ID (s)          | text          | text          |
| Yes      | series tag     | auditor                             | Auditor                               | text          | text          |
| Yes      | series tag     | company                             | Company                               | text          | text          |
| Yes      | series tag     | duct_system_1_type                  | Duct System 1 - Type                  | text          | text          |
| Yes      | series tag     | duct_system_2_type                  | Duct System 2 - Type                  | text          | text          |
| Yes      | numeric metric | duct_system_1_rvalue                | Duct System 1 - RValue                | number        | number        |
| Yes      | numeric metric | duct_system_2_rvalue                | Duct System 2 - RValue                | number        | number        |
| Yes      | series tag     | duct_system_1_return_sizing         | Duct System 1 - Return Sizing         | text          | text          |
| Yes      | series tag     | duct_system_2_return_sizing         | Duct System 2 - Return Sizing         | text          | text          |
| Yes      | numeric metric | duct_system_1_leakage               | Duct System 1 - % Leakage             | number        | number        |
| Yes      | numeric metric | duct_system_2_leakage               | Duct System 2 - % Leakage             | number        | number        |
| Yes      | series tag     | system_1_location_air_handler       | System 1 - Location Air Handler       | text          | text          |
| Yes      | series tag     | system_2_location_air_handler       | System 2 - Location Air Handler       | text          | text          |
| Yes      | series tag     | system_1_air_handler_type           | System 1 - Air Handler Type           | text          | text          |
| Yes      | series tag     | system_2_air_handler_type           | System 2 - Air Handler Type           | text          | text          |
| Yes      | numeric metric | system_1_age_years                  | System 1 - Age (years)                | number        | number        |
| Yes      | numeric metric | system_2_age_years                  | System 2 - Age (years)                | number        | number        |
| Yes      | numeric metric | system_1_eer                        | System 1 - EER                        | number        | number        |
| Yes      | numeric metric | system_2_eer                        | System 2 - EER                        | number        | number        |
| Yes      | numeric metric | system_1_sqft_ton                   | System 1 - sqft/ton                   | number        | number        |
| Yes      | numeric metric | system_2_sqft_ton                   | System 2 - sqft/ton                   | number        | number        |
| Yes      | series tag     | water_heater_fuel_type              | Water Heater - Fuel Type              | text          | text          |
| Yes      | series tag     | water_heating_tank_type             | Water Heating - Tank Type             | text          | text          |
| Yes      | series tag     | toilet_type                         | Toilet Type                           | text          | text          |
| Yes      | series tag     | programmable_thermostat_present     | Programmable Thermostat Present       | text          | text          |
| Yes      | numeric metric | window_screen_area_recommended_sqft | Window Screen Area Recommended (sqft) | number        | number        |
| Yes      | series tag     | furnace_fuel_type                   | Furnace - Fuel Type                   | text          | text          |
| Yes      | time           | audit_date                          | Audit Date                            | calendar_date | calendar_date |
| Yes      | numeric metric | attic_r_value                       | Attic R-Value                         | number        | number        |
| Yes      | numeric metric | recommended_additional_r_value      | Recommended Additional R-Value        | number        | number        |
| No       |                | year_built                          | Year Built                            | number        | number        |
| Yes      | numeric metric | bedrooms                            | Bedrooms                              | number        | number        |
| Yes      | numeric metric | conditioned_sqft                    | Conditioned (sqft)                    | number        | number        |
| Yes      | numeric metric | attic_sqft                          | Attic (sqft)                          | number        | number        |
| Yes      | series tag     | home_type                           | Home_Type                             | text          | text          |
| No       |                | as_of                               | As of                                 | calendar_date | calendar_date |
```

## Time Field

```ls
Value = audit_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = as_of,year_built
```

## Data Commands

```ls
series e:me4f-48mc d:2012-11-27T00:00:00.000Z t:system_2_air_handler_type=Horizontal t:duct_system_1_type=Mylar_Flex t:water_heater_fuel_type=Elec t:auditor="Lynn Howden" t:system_2_location_air_handler=Garage t:company="AUSTIN QUALITY GREEN ENERGY AUDITS" t:programmable_thermostat_present=Y t:duct_system_1_return_sizing=Inadequate t:furnace_fuel_type=Elec t:water_heating_tank_type=Tank t:system_1_air_handler_type=Horizontal t:home_type="Single Family" t:system_1_location_air_handler=Attic t:tcad_or_wcad_property_id_s=100182 t:toilet_type=Water_Saving m:system_1_age_years=3 m:recommended_additional_r_value=23 m:attic_sqft=1876 m:duct_system_1_rvalue=4 m:conditioned_sqft=1876 m:attic_r_value=15 m:system_2_sqft_ton=420 m:system_1_eer=13 m:duct_system_1_leakage=24 m:window_screen_area_recommended_sqft=12 m:bedrooms=3 m:system_1_sqft_ton=492

series e:me4f-48mc d:2012-02-09T00:00:00.000Z t:duct_system_1_type=Mylar_Flex t:water_heater_fuel_type=Gas t:auditor="Chad Roesch" t:company="A-1 ENERGY AUDITS" t:programmable_thermostat_present=Y t:duct_system_1_return_sizing=Adequate t:furnace_fuel_type=Gas t:water_heating_tank_type=Tank t:home_type="Single Family" t:tcad_or_wcad_property_id_s=100067 t:toilet_type=Water_Saving m:system_1_age_years=10 m:recommended_additional_r_value=24.8 m:attic_sqft=1598 m:duct_system_1_rvalue=8 m:conditioned_sqft=1598 m:attic_r_value=13.2 m:system_1_eer=13 m:duct_system_1_leakage=15 m:window_screen_area_recommended_sqft=0 m:bedrooms=3 m:system_1_sqft_ton=532

series e:me4f-48mc d:2013-05-21T00:00:00.000Z t:duct_system_1_type=Mylar_Flex t:water_heater_fuel_type=Elec t:auditor="Andy Pell" t:company="1 EARTH ENERGY AUDITS" t:programmable_thermostat_present=N t:duct_system_1_return_sizing=Adequate t:furnace_fuel_type=Elec t:water_heating_tank_type=Tank t:home_type="Single Family" t:tcad_or_wcad_property_id_s=100118 t:toilet_type=Water_Saving m:system_1_age_years=8 m:recommended_additional_r_value=19 m:attic_sqft=520 m:duct_system_1_rvalue=6 m:conditioned_sqft=520 m:attic_r_value=19 m:system_1_eer=12 m:duct_system_1_leakage=21 m:window_screen_area_recommended_sqft=0 m:bedrooms=2 m:system_1_sqft_ton=260
```

## Meta Commands

```ls
metric m:duct_system_1_rvalue p:double l:"Duct System 1 - RValue" t:dataTypeName=number

metric m:duct_system_2_rvalue p:double l:"Duct System 2 - RValue" t:dataTypeName=number

metric m:duct_system_1_leakage p:double l:"Duct System 1 - % Leakage" t:dataTypeName=number

metric m:duct_system_2_leakage p:double l:"Duct System 2 - % Leakage" t:dataTypeName=number

metric m:system_1_age_years p:integer l:"System 1 - Age (years)" t:dataTypeName=number

metric m:system_2_age_years p:integer l:"System 2 - Age (years)" t:dataTypeName=number

metric m:system_1_eer p:double l:"System 1 - EER" t:dataTypeName=number

metric m:system_2_eer p:double l:"System 2 - EER" t:dataTypeName=number

metric m:system_1_sqft_ton p:integer l:"System 1 - sqft/ton" t:dataTypeName=number

metric m:system_2_sqft_ton p:integer l:"System 2 - sqft/ton" t:dataTypeName=number

metric m:window_screen_area_recommended_sqft p:integer l:"Window Screen Area Recommended (sqft)" t:dataTypeName=number

metric m:attic_r_value p:integer l:"Attic R-Value" t:dataTypeName=number

metric m:recommended_additional_r_value p:double l:"Recommended Additional R-Value" t:dataTypeName=number

metric m:bedrooms p:double l:Bedrooms t:dataTypeName=number

metric m:conditioned_sqft p:integer l:"Conditioned (sqft)" t:dataTypeName=number

metric m:attic_sqft p:integer l:"Attic (sqft)" t:dataTypeName=number

entity e:me4f-48mc l:"2009-2013: ECAD Residential Energy Audit Data" t:attribution="Austin Energy" t:url=https://data.austintexas.gov/api/views/me4f-48mc

property e:me4f-48mc t:meta.view v:id=me4f-48mc v:category=Utility v:attributionLink=http://www.Austinenergy.com v:averageRating=0 v:name="2009-2013: ECAD Residential Energy Audit Data" v:attribution="Austin Energy"

property e:me4f-48mc t:meta.view.license v:name="Public Domain"

property e:me4f-48mc t:meta.view.owner v:id=fqy8-r3v8 v:screenName="Michael McCarthy" v:displayName="Michael McCarthy"

property e:me4f-48mc t:meta.view.tableauthor v:id=fqy8-r3v8 v:screenName="Michael McCarthy" v:roleName=editor v:displayName="Michael McCarthy"
```

## Top Records

```ls
| tcad_or_wcad_property_id_s | auditor        | company                            | duct_system_1_type | duct_system_2_type | duct_system_1_rvalue | duct_system_2_rvalue | duct_system_1_return_sizing | duct_system_2_return_sizing | duct_system_1_leakage | duct_system_2_leakage | system_1_location_air_handler | system_2_location_air_handler | system_1_air_handler_type | system_2_air_handler_type | system_1_age_years | system_2_age_years | system_1_eer | system_2_eer | system_1_sqft_ton | system_2_sqft_ton | water_heater_fuel_type | water_heating_tank_type | toilet_type  | programmable_thermostat_present | window_screen_area_recommended_sqft | furnace_fuel_type | audit_date          | attic_r_value | recommended_additional_r_value | year_built | bedrooms | conditioned_sqft | attic_sqft | home_type     | as_of               | 
| ========================== | ============== | ================================== | ================== | ================== | ==================== | ==================== | =========================== | =========================== | ===================== | ===================== | ============================= | ============================= | ========================= | ========================= | ================== | ================== | ============ | ============ | ================= | ================= | ====================== | ======================= | ============ | =============================== | =================================== | ================= | =================== | ============= | ============================== | ========== | ======== | ================ | ========== | ============= | =================== | 
| 100182                     | Lynn Howden    | AUSTIN QUALITY GREEN ENERGY AUDITS | Mylar_Flex         |                    | 4                    |                      | Inadequate                  |                             | 24                    |                       | Attic                         | Garage                        | Horizontal                | Horizontal                | 3                  |                    | 13           |              | 492               | 420               | Elec                   | Tank                    | Water_Saving | Y                               | 12                                  | Elec              | 2012-11-27T00:00:00 | 15            | 23                             | 1995       | 3        | 1876             | 1876       | Single Family | 2014-05-20T00:00:00 | 
| 100067                     | Chad Roesch    | A-1 ENERGY AUDITS                  | Mylar_Flex         |                    | 8                    |                      | Adequate                    |                             | 15                    |                       |                               |                               |                           |                           | 10                 |                    | 13           |              | 532               |                   | Gas                    | Tank                    | Water_Saving | Y                               | 0                                   | Gas               | 2012-02-09T00:00:00 | 13.2          | 24.8                           | 1947       | 3        | 1598             | 1598       | Single Family | 2014-05-20T00:00:00 | 
| 100118                     | Andy Pell      | 1 EARTH ENERGY AUDITS              | Mylar_Flex         |                    | 6                    |                      | Adequate                    |                             | 21                    |                       |                               |                               |                           |                           | 8                  |                    | 12           |              | 260               |                   | Elec                   | Tank                    | Water_Saving | N                               | 0                                   | Elec              | 2013-05-21T00:00:00 | 19            | 19                             | 1946       | 2        | 520              | 520        | Single Family | 2014-05-20T00:00:00 | 
| 100161                     | Vance Acker    | GREEN LEAF ENERGY                  | Grey_Flex          |                    | 6                    |                      | Adequate                    |                             | 23                    |                       | Attic                         |                               | Horizontal                |                           | 15                 |                    |              |              | 400               |                   | Gas                    | Tank                    | Standard     | N                               | 48                                  | Gas               | 2011-04-15T00:00:00 | 30            | 8                              | 1935       | 2        | 864              | 600        | Single Family | 2014-05-20T00:00:00 | 
| 100363                     | Chad Roesch    | A-1 ENERGY AUDITS                  | Duct_Board         |                    | 6                    |                      | Adequate                    |                             | 24                    |                       | Attic                         |                               | Horizontal                |                           | 13                 |                    | 12           |              | 634               |                   | Gas                    | Tank                    | Water_Saving | Y                               | 0                                   | Gas               | 2011-03-11T00:00:00 | 8.8           | 29.2                           | 1942       | 3        | 2538             | 67         | Single Family | 2014-05-20T00:00:00 | 
| 100089                     | James Davis    | ENERGY AUDIT MASTERS               | Mylar_Flex         | Mylar_Flex         | 6                    | 6                    | Adequate                    | Adequate                    | 16                    | 9.1                   | Attic                         | Attic                         | Horizontal                | Horizontal                | 5                  |                    | 9.5          | 10           | 473               | 445               | Gas                    | Tankless                | Water_Saving | Y                               | 0                                   | Gas               | 2012-05-24T00:00:00 |               |                                | 2001       | 3        | 2744             | 1560       | Single Family | 2014-05-20T00:00:00 | 
| 100187                     | Chad Roesch    | A-1 ENERGY AUDITS                  | Mylar_Flex         |                    | 8                    |                      | Adequate                    |                             | 9                     |                       | Attic                         |                               | Horizontal                |                           | 20                 |                    | 10           |              | 516               |                   | Gas                    | Tank                    | Water_Saving | Y                               | 0                                   | Gas               | 2011-06-20T00:00:00 | 24.5          | 13.5                           | 1945       | 3        | 1290             | 1290       | Single Family | 2014-05-20T00:00:00 | 
| 100084                     | Robert Hartung | ENERGY AUDIT MASTERS               | Grey_Flex          |                    | 4                    |                      | Adequate                    |                             | 34.9                  |                       | Attic                         |                               | Horizontal                |                           |                    |                    |              |              | 352               |                   | Gas                    | Tank                    | Water_Saving | Y                               | 63                                  | Gas               | 2011-09-01T00:00:00 | 9             | 29                             | 1959       | 2        | 704              | 704        | Single Family | 2014-05-20T00:00:00 | 
| 100071                     | Amir Faghih    | APPROVED ENERGY AUDITS             | Sheet_Metal        |                    | 5                    |                      | Adequate                    |                             | 18                    |                       | Closet                        |                               | Up Flow                   |                           | 5                  |                    | 10.5         |              |                   |                   | Gas                    | Tank                    | Water_Saving | N                               | 104                                 | Gas               | 2010-03-19T00:00:00 | 19            | 19                             | 1945       | 3        | 1108             | 1108       | Single Family | 2014-05-20T00:00:00 | 
| 100358                     | Andy Pell      | 1 EARTH ENERGY AUDITS              | Mylar_Flex         |                    | 6                    |                      | Adequate                    |                             |                       |                       | Closet                        |                               | Up Flow                   |                           |                    |                    | 7            |              | 389               |                   | Elec                   | Tank                    | Water_Saving | Y                               | 0                                   | Gas               | 2012-02-21T00:00:00 |               | 20                             | 1952       | 3        | 1368             | 1168       | Single Family | 2014-05-20T00:00:00 | 
```