# Energy Efficiency Portfolio Standard (EEPS) Program Estimated Energy Savings Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/energy-efficiency-programs-and-estimated-energy-savings) |
| Metadata | [Link](https://data.ny.gov/api/views/vqmi-95p7) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/vqmi-95p7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/vqmi-95p7/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | vqmi-95p7 |
| Name | Energy Efficiency Portfolio Standard (EEPS) Program Estimated Energy Savings Data |
| Attribution | New York State Public Service Commission |
| Category | Energy & Environment |
| Tags | energy efficiency portfolio standard, energy efficiency programs, energy savings, eeps |
| Created | 2013-02-26T17:07:14Z |
| Publication Date | 2016-07-19T22:04:06Z |

## Description

The Energy Efficiency Portfolio Standard (EEPS) Program encourages cost-effective electric and natural gas energy efficiency across New York State.  New York State?s utilities and the New York State Energy Research and Development Authority (NYSERDA) administer energy efficiency programs to achieve energy efficiency savings. EEPS energy efficiency programs provide technical services, information and customer incentives to encourage customers in implementing energy efficiency measures.  This data includes the list of energy efficiency programs and the estimated energy savings reported for each program.

## Columns

```ls
| Included | Schema Type    | Field Name                    | Name                                              | Data Type     | Render Type   |
| ======== | ============== | ============================= | ================================================= | ============= | ============= |
| Yes      | series tag     | program_administrator         | Program Administrator                             | text          | text          |
| Yes      | series tag     | program                       | Program Name                                      | text          | text          |
| Yes      | series tag     | primary_fuel                  | Fuel Type                                         | text          | text          |
| Yes      | series tag     | sector                        | Sector                                            | text          | text          |
| Yes      | numeric metric | total_electricity_savings_mwh | Net Fuel Savings Acquired                         | number        | number        |
| Yes      | series tag     | total_natural_gas_dth_savings | Fuel Savings Unit                                 | text          | text          |
| Yes      | time           | savings_as_of_date            | Cumulative Net Energy Savings Acquired as of Date | calendar_date | calendar_date |
```

## Time Field

```ls
Value = savings_as_of_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:vqmi-95p7 d:2014-09-30T00:00:00.000Z t:sector=Commercial t:program="C&I Custom Efficiency Program" t:primary_fuel=Electric t:program_administrator="Consolidated Edison Company of New York, Inc." t:total_natural_gas_dth_savings=MWh m:total_electricity_savings_mwh=94630.25

series e:vqmi-95p7 d:2014-09-30T00:00:00.000Z t:sector=Commercial t:program="C&I Equipment Rebate Program" t:primary_fuel=Electric t:program_administrator="Consolidated Edison Company of New York, Inc." t:total_natural_gas_dth_savings=MWh m:total_electricity_savings_mwh=151220.35

series e:vqmi-95p7 d:2014-09-30T00:00:00.000Z t:sector=Commercial t:program="Small Business Direct Install Program" t:primary_fuel=Electric t:program_administrator="Consolidated Edison Company of New York, Inc." t:total_natural_gas_dth_savings=MWh m:total_electricity_savings_mwh=370283.04
```

## Meta Commands

```ls
metric m:total_electricity_savings_mwh p:double l:"Net Fuel Savings Acquired" d:"Estimated number of units of fuel savings; includes savings acquired through EEPS 1 and EEPS 2, including ancillary savings from the companion gas or electric programs, as appropriate." t:dataTypeName=number

entity e:vqmi-95p7 l:"Energy Efficiency Portfolio Standard (EEPS) Program Estimated Energy Savings Data" t:attribution="New York State Public Service Commission" t:url=https://data.ny.gov/api/views/vqmi-95p7

property e:vqmi-95p7 t:meta.view v:id=vqmi-95p7 v:category="Energy & Environment" v:attributionLink=http://www3.dps.ny.gov/W/PSCWeb.nsf/All/06F2FEE55575BD8A852576E4006F9AF7?OpenDocument v:averageRating=0 v:name="Energy Efficiency Portfolio Standard (EEPS) Program Estimated Energy Savings Data" v:attribution="New York State Public Service Commission"

property e:vqmi-95p7 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:vqmi-95p7 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:vqmi-95p7 t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| program_administrator                         | program                                   | primary_fuel | sector      | total_electricity_savings_mwh | total_natural_gas_dth_savings | savings_as_of_date  | 
| ============================================= | ========================================= | ============ | =========== | ============================= | ============================= | =================== | 
| Consolidated Edison Company of New York, Inc. | C&I Custom Efficiency Program             | Electric     | Commercial  | 94630.25                      | MWh                           | 2014-09-30T00:00:00 | 
| Consolidated Edison Company of New York, Inc. | C&I Equipment Rebate Program              | Electric     | Commercial  | 151220.35                     | MWh                           | 2014-09-30T00:00:00 | 
| Consolidated Edison Company of New York, Inc. | Small Business Direct Install Program     | Electric     | Commercial  | 370283.04                     | MWh                           | 2014-09-30T00:00:00 | 
| Consolidated Edison Company of New York, Inc. | Multifamily Energy Efficiency Program     | Electric     | Multifamily | 46345.60                      | MWh                           | 2014-09-30T00:00:00 | 
| Consolidated Edison Company of New York, Inc. | * Residential HVAC Program                | Electric     | Residential | 390.32299999999998            | MWh                           | 2014-09-30T00:00:00 | 
| Consolidated Edison Company of New York, Inc. | Appliance Bounty Program                  | Electric     | Residential | 17402.20                      | MWh                           | 2014-09-30T00:00:00 | 
| Consolidated Edison Company of New York, Inc. | Residential Direct Installation Program   | Electric     | Residential | 2663.10                       | MWh                           | 2014-09-30T00:00:00 | 
| Consolidated Edison Company of New York, Inc. | Residential Electric Program              | Electric     | Residential | 22690.17                      | MWh                           | 2014-09-30T00:00:00 | 
| Consolidated Edison Company of New York, Inc. | Residential HVAC Program                  | Electric     | Residential | 6443.58                       | MWh                           | 2014-09-30T00:00:00 | 
| Consolidated Edison Company of New York, Inc. | Residential Room Air Conditioning Program | Electric     | Residential | 3213.46                       | MWh                           | 2014-09-30T00:00:00 | 
```