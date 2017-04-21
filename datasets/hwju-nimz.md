# Dashboard Template - Maryland Energy Administration

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dashboard-template-maryland-energy-administration) |
| Metadata | [Link](https://data.maryland.gov/api/views/hwju-nimz) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/hwju-nimz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/hwju-nimz/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | hwju-nimz |
| Name | Dashboard Template - Maryland Energy Administration |
| Attribution | Maryland Energy Administration (MEA) |
| Category | Energy and Environment |
| Tags | maryland energy administration, mea, hybrid, renewable energy, energy savings, consumption |
| Created | 2016-09-26T21:30:46Z |
| Publication Date | 2016-10-20T19:02:32Z |

## Description

This dataset includes data from the Maryland Energy Administration (MEA) about statewide energy consumption, energy savings programs, renewable energy, and electric and hybrid vehicles

## Columns

```ls
| Included | Schema Type    | Field Name                                                                                            | Name                                                                                                    | Data Type     | Render Type   |
| ======== | ============== | ===================================================================================================== | ======================================================================================================= | ============= | ============= |
| Yes      | time           | date                                                                                                  | Date for Fiscal Year                                                                                    | calendar_date | calendar_date |
| No       |                | year                                                                                                  | Year                                                                                                    | number        | text          |
| Yes      | numeric metric | annual_energy_savings_estimates_from_state_agency_loan_program_projects_mmbtu_yr                      | Annual Energy Savings Estimates from State Agency Loan Program Projects (MMBTU/yr)                      | number        | number        |
| Yes      | numeric metric | annual_energy_savings_estimates_from_energy_efficiency_grant_programs_mmbtu_yr                        | Annual Energy Savings Estimates from Energy Efficiency Grant Programs (MMBTU/yr)                        | number        | number        |
| Yes      | numeric metric | number_of_electric_vehicles_registered_in_state                                                       | Number of Electric Vehicles Registered in State                                                         | number        | number        |
| Yes      | numeric metric | number_of_hybrid_vehicles_registered_in_state                                                         | Number of Hybrid Vehicles Registered in State                                                           | number        | number        |
| No       |                | date_for_calendar_year                                                                                | Date for Calendar Year                                                                                  | calendar_date | calendar_date |
| Yes      | numeric metric | statewide_per_capita_electricity_consumption_mwh_person                                               | Statewide Per Capita Electricity Consumption (MWh/person)                                               | number        | number        |
| Yes      | numeric metric | estimated_megawatt_hours_mwh_of_in_state_commercial_and_residential_scale_renewable_energy_generation | Estimated Megawatt Hours (MWh) of In-state Commercial and Residential Scale Renewable Energy Generation | number        | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = date_for_calendar_year,year
```

## Data Commands

```ls
series e:hwju-nimz d:2011-06-30T00:00:00.000Z m:estimated_megawatt_hours_mwh_of_in_state_commercial_and_residential_scale_renewable_energy_generation=3929552 m:annual_energy_savings_estimates_from_state_agency_loan_program_projects_mmbtu_yr=32039 m:number_of_electric_vehicles_registered_in_state=75 m:statewide_per_capita_electricity_consumption_mwh_person=11.7 m:number_of_hybrid_vehicles_registered_in_state=73923

series e:hwju-nimz d:2012-06-30T00:00:00.000Z m:estimated_megawatt_hours_mwh_of_in_state_commercial_and_residential_scale_renewable_energy_generation=3030144 m:annual_energy_savings_estimates_from_state_agency_loan_program_projects_mmbtu_yr=12920 m:number_of_electric_vehicles_registered_in_state=439 m:statewide_per_capita_electricity_consumption_mwh_person=11.21 m:number_of_hybrid_vehicles_registered_in_state=76851

series e:hwju-nimz d:2013-06-30T00:00:00.000Z m:estimated_megawatt_hours_mwh_of_in_state_commercial_and_residential_scale_renewable_energy_generation=3126954 m:annual_energy_savings_estimates_from_state_agency_loan_program_projects_mmbtu_yr=6094 m:number_of_electric_vehicles_registered_in_state=1567 m:statewide_per_capita_electricity_consumption_mwh_person=11.13 m:number_of_hybrid_vehicles_registered_in_state=99953
```

## Meta Commands

```ls
metric m:annual_energy_savings_estimates_from_state_agency_loan_program_projects_mmbtu_yr p:integer l:"Annual Energy Savings Estimates from State Agency Loan Program Projects (MMBTU/yr)" d:"Estimated amount of energy saved annually as a result of projects funded by the State Agency Loan Program (SALP)" t:dataTypeName=number

metric m:annual_energy_savings_estimates_from_energy_efficiency_grant_programs_mmbtu_yr p:integer l:"Annual Energy Savings Estimates from Energy Efficiency Grant Programs (MMBTU/yr)" d:"Estimated amount of energy saved annually as a result of projects funded by the energy efficiency grants" t:dataTypeName=number

metric m:number_of_electric_vehicles_registered_in_state p:integer l:"Number of Electric Vehicles Registered in State" t:dataTypeName=number

metric m:number_of_hybrid_vehicles_registered_in_state p:integer l:"Number of Hybrid Vehicles Registered in State" t:dataTypeName=number

metric m:statewide_per_capita_electricity_consumption_mwh_person p:float l:"Statewide Per Capita Electricity Consumption (MWh/person)" d:"Megawatt hours of electricity consumption per person statewide. Reported annually (calendar year)" t:dataTypeName=number

metric m:estimated_megawatt_hours_mwh_of_in_state_commercial_and_residential_scale_renewable_energy_generation p:integer l:"Estimated Megawatt Hours (MWh) of In-state Commercial and Residential Scale Renewable Energy Generation" d:"Estimated amount of energy generated annually from commercial and residential customers using renewable energy technologies. Reported annually (calendar year)" t:dataTypeName=number

entity e:hwju-nimz l:"Dashboard Template - Maryland Energy Administration" t:attribution="Maryland Energy Administration (MEA)" t:url=https://data.maryland.gov/api/views/hwju-nimz

property e:hwju-nimz t:meta.view v:id=hwju-nimz v:category="Energy and Environment" v:attributionLink=http://energy.maryland.gov/ v:averageRating=0 v:name="Dashboard Template - Maryland Energy Administration" v:attribution="Maryland Energy Administration (MEA)"

property e:hwju-nimz t:meta.view.license v:name="Public Domain"

property e:hwju-nimz t:meta.view.owner v:id=9ei4-2q5c v:screenName="Pat Pscherer" v:displayName="Pat Pscherer"

property e:hwju-nimz t:meta.view.tableauthor v:id=9ei4-2q5c v:screenName="Pat Pscherer" v:roleName=administrator v:displayName="Pat Pscherer"
```

## Top Records

```ls
| date                | year | annual_energy_savings_estimates_from_state_agency_loan_program_projects_mmbtu_yr | annual_energy_savings_estimates_from_energy_efficiency_grant_programs_mmbtu_yr | number_of_electric_vehicles_registered_in_state | number_of_hybrid_vehicles_registered_in_state | date_for_calendar_year | statewide_per_capita_electricity_consumption_mwh_person | estimated_megawatt_hours_mwh_of_in_state_commercial_and_residential_scale_renewable_energy_generation | 
| =================== | ==== | ================================================================================ | ============================================================================== | =============================================== | ============================================= | ====================== | ======================================================= | ===================================================================================================== | 
| 2011-06-30T00:00:00 | 2011 | 32039                                                                            |                                                                                | 75                                              | 73923                                         | 2011-12-31T00:00:00    | 11.70                                                   | 3929552                                                                                               | 
| 2012-06-30T00:00:00 | 2012 | 12920                                                                            |                                                                                | 439                                             | 76851                                         | 2012-12-31T00:00:00    | 11.21                                                   | 3030144                                                                                               | 
| 2013-06-30T00:00:00 | 2013 | 6094                                                                             |                                                                                | 1567                                            | 99953                                         | 2013-12-31T00:00:00    | 11.13                                                   | 3126954                                                                                               | 
| 2014-06-30T00:00:00 | 2014 | 8434                                                                             | 117501                                                                         | 2296                                            | 77454                                         | 2014-12-31T00:00:00    | 10.91                                                   | 3138084                                                                                               | 
| 2016-06-30T00:00:00 | 2016 | 10916                                                                            | 407295                                                                         | 6788                                            | 82598                                         | 2016-12-31T00:00:00    |                                                         |                                                                                                       | 
| 2015-06-30T00:00:00 | 2015 | 3774                                                                             | 89525                                                                          | 3069                                            | 79513                                         | 2015-12-31T00:00:00    | 10.96                                                   | 3280637                                                                                               | 
```