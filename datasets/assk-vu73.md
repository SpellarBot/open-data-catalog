# The One- to Four-Family Home Performance with ENERGY STAR? Program: Beginning 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/the-one-to-four-family-home-performance-with-energy-star-program) |
| Metadata | [Link](https://data.ny.gov/api/views/assk-vu73) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/assk-vu73/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/assk-vu73/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | assk-vu73 |
| Name | The One- to Four-Family Home Performance with ENERGY STAR? Program: Beginning 2010 |
| Attribution | The New York State Energy Research and Development Authority Home Performance with ENERGY STAR Program |
| Category | Energy & Environment |
| Tags | home performance, incentives, green jobs green-ny, financing, audit, kwh, mmbtu, energy efficiency, residential |
| Created | 2016-05-23T20:47:50Z |
| Publication Date | 2017-03-15T22:04:05Z |

## Description

IMPORTANT! PLEASE READ DISCLAIMER BEFORE USING DATA. The One- to Four-Family Home Performance with ENERGY STAR? Program is a market transformation program that uses Building Performance Institute (BPI) Goldstar contractors to install comprehensive energy-efficient improvements.  The program is designed to use building science and a whole-house approach to reduce energy use in the State?s existing one-to-four family and low-rise multifamily residential buildings and capture heating fuel and electricity-related savings.  The Program provides incentives on eligible energy efficiency improvements including building shell measures, high efficiency heating and cooling measures, ENERGY STAR appliances and lighting. 

D I S C L A I M E R: Estimated Annual kWh Savings, Estimated Annual MMBtu Savings, and First Year Energy Savings $ Estimate represent contractor reported savings derived from energy modeling software calculations and not actual realized energy savings. The accuracy of the Estimated Annual kWh Savings and Estimated Annual MMBtu Savings for projects has been evaluated by an independent third party. The results of the impact analysis indicate that, on average, actual savings amount to 35 percent of the Estimated Annual kWh Savings and 65 percent of the Estimated Annual MMBtu Savings. The analysis did not evaluate every single project, but rather a sample of projects from 2007 and 2008, so the results are applicable to the population on average but not necessarily to any individual project which could have over or under achieved in comparison to the evaluated savings. The results from the impact analysis will be updated when more recent information is available. While many factors influence the degree to which estimated savings are realized, including the use of the modeling software itself, some reasons individual households may realize savings different from those projected include, but are not limited to, changes in the number or needs of members of a household, changes in occupancy schedules, changes in energy usage behaviors or appliances and electronics installed in the home, or beginning or ending a home business. In addition, the program has evolved since the last impact analysis, introducing a change in the mix of measures that are installed, and use of additional modeling software tools and protocols.  Further, with the current technology improvements and regulatory changes being considered we are actively working toward a more accurate future. For more information, please refer to the Evaluation Report published on NYSERDA?s website at http://www.nyserda.ny.gov/-/media/Files/Publications/PPSER/Program-Evaluation/2012ContractorReports/2012-HPwES-Impact-Report-with-Appendices.pdf.

Statewide Home Performance with ENERGY STAR Program dataset includes the following data points for projects completed during Green Jobs Green-NY, beginning November 15, 2010 through March 31, 2016: Home Performance Project ID, Home Performance Site ID, Project County, Project City, Project Zip, Gas Utility, Electric Utility, Project Completion, Date, Customer Type, Low-Rise or Home Performance Indicator, Total Project Cost (USD), Total Incentives (USD), Type of Program Financing, Amount Financed Through Program (USD), Pre-Retrofit Home Heating Fuel Type, Estimated Annual kWh Savings, Estimated Annual MMBtu Savings, First Year Energy Savings $ Estimate (USD), Homeowner Received Green Jobs-Green NY Free/Reduced Cost Audit (Y/N).

## Columns

```ls
| Included | Schema Type    | Field Name                                                         | Name                                                                 | Data Type     | Render Type   |
| ======== | ============== | ================================================================== | ==================================================================== | ============= | ============= |
| Yes      | time           | reporting_period                                                   | Reporting Period                                                     | calendar_date | calendar_date |
| Yes      | series tag     | home_performance_project_id                                        | Home Performance Project ID                                          | text          | text          |
| Yes      | series tag     | home_performance_site_id                                           | Home Performance Site ID                                             | text          | text          |
| Yes      | series tag     | project_county                                                     | Project County                                                       | text          | text          |
| Yes      | series tag     | project_city                                                       | Project City                                                         | text          | text          |
| Yes      | series tag     | project_zip                                                        | Project Zip                                                          | text          | text          |
| Yes      | series tag     | gas_utility                                                        | Gas Utility                                                          | text          | text          |
| Yes      | series tag     | electric_utility                                                   | Electric Utility                                                     | text          | text          |
| No       |                | project_completion_date                                            | Project Completion Date                                              | calendar_date | calendar_date |
| Yes      | series tag     | customer_type                                                      | Customer Type                                                        | text          | text          |
| Yes      | series tag     | low_rise_or_home_performance_indicator                             | Low-Rise or Home Performance Indicator                               | text          | text          |
| Yes      | numeric metric | total_project_cost_usd                                             | Total Project Cost (USD)                                             | number        | number        |
| Yes      | numeric metric | total_incentives_usd                                               | Total Incentives (USD)                                               | number        | number        |
| Yes      | series tag     | type_of_program_financing                                          | Type of Program Financing                                            | text          | text          |
| Yes      | numeric metric | amount_financed_through_program_usd                                | Amount Financed Through Program (USD)                                | number        | number        |
| Yes      | series tag     | pre_retrofit_home_heating_fuel_type                                | Pre-Retrofit Home Heating Fuel Type                                  | text          | text          |
| Yes      | numeric metric | estimated_annual_kwh_savings                                       | Estimated Annual kWh Savings                                         | number        | number        |
| Yes      | numeric metric | estimated_annual_mmbtu_savings                                     | Estimated Annual MMBtu Savings                                       | number        | number        |
| Yes      | numeric metric | first_year_energy_savings_estimate_usd                             | First Year Energy Savings $ Estimate (USD)                           | number        | number        |
| Yes      | series tag     | homeowner_received_green_jobs_green_ny_free_reduced_cost_audit_y_n | Homeowner Received Green Jobs-Green NY Free/Reduced Cost Audit (Y/N) | text          | text          |
```

## Time Field

```ls
Value = reporting_period
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = project_completion_date
```

## Data Commands

```ls
series e:assk-vu73 d:2016-10-31T00:00:00.000Z t:home_performance_site_id=S00000149146 t:homeowner_received_green_jobs_green_ny_free_reduced_cost_audit_y_n=No t:electric_utility="National Grid" t:project_county=Onondaga t:low_rise_or_home_performance_indicator="1-4 Family Home Performance Program" t:project_city=Fabius t:pre_retrofit_home_heating_fuel_type=Oil t:project_zip=13063 t:home_performance_project_id=P00000754076 t:customer_type=Market m:estimated_annual_kwh_savings=0 m:total_incentives_usd=4000 m:first_year_energy_savings_estimate_usd=1844.93 m:amount_financed_through_program_usd=0 m:total_project_cost_usd=21150 m:estimated_annual_mmbtu_savings=74.762788

series e:assk-vu73 d:2016-10-31T00:00:00.000Z t:home_performance_site_id=S00000155306 t:homeowner_received_green_jobs_green_ny_free_reduced_cost_audit_y_n=Yes t:electric_utility="National Grid" t:project_county=Erie t:low_rise_or_home_performance_indicator="1-4 Family Home Performance Program" t:project_city=Akron t:pre_retrofit_home_heating_fuel_type=Oil t:project_zip=14001 t:home_performance_project_id=P00000762852 t:customer_type=Market m:estimated_annual_kwh_savings=0 m:total_incentives_usd=1540 m:first_year_energy_savings_estimate_usd=591.02 m:amount_financed_through_program_usd=0 m:total_project_cost_usd=5600 m:estimated_annual_mmbtu_savings=35.391103

series e:assk-vu73 d:2016-10-31T00:00:00.000Z t:home_performance_site_id=S00000143667 t:homeowner_received_green_jobs_green_ny_free_reduced_cost_audit_y_n=No t:electric_utility="National Grid" t:project_county=Rensselaer t:low_rise_or_home_performance_indicator="1-4 Family Home Performance Program" t:project_city=Troy t:pre_retrofit_home_heating_fuel_type=Oil t:project_zip=12180 t:home_performance_project_id=P00000746648 t:customer_type=Market m:estimated_annual_kwh_savings=0 m:total_incentives_usd=1780 m:first_year_energy_savings_estimate_usd=1109.06 m:amount_financed_through_program_usd=0 m:total_project_cost_usd=6586 m:estimated_annual_mmbtu_savings=44.942896
```

## Meta Commands

```ls
metric m:total_project_cost_usd p:double l:"Total Project Cost (USD)" d:"Cost of project in US dollars (USD)" t:dataTypeName=number

metric m:total_incentives_usd p:double l:"Total Incentives (USD)" d:"Amount of homeowner incentive (USD)" t:dataTypeName=number

metric m:amount_financed_through_program_usd p:float l:"Amount Financed Through Program (USD)" d:"Project loan amount in USD" t:dataTypeName=number

metric m:estimated_annual_kwh_savings p:integer l:"Estimated Annual kWh Savings" d:"Annual post-retrofit electric savings estimate in kWh" t:dataTypeName=number

metric m:estimated_annual_mmbtu_savings p:double l:"Estimated Annual MMBtu Savings" d:"Annual post-retrofit MMBtu savings based on primary fuel type" t:dataTypeName=number

metric m:first_year_energy_savings_estimate_usd p:float l:"First Year Energy Savings $ Estimate (USD)" d:"Estimated post-retrofit first year dollar savings (USD)" t:dataTypeName=number

entity e:assk-vu73 l:"The One- to Four-Family Home Performance with ENERGY STAR? Program: Beginning 2010" t:attribution="The New York State Energy Research and Development Authority Home Performance with ENERGY STAR Program" t:url=https://data.ny.gov/api/views/assk-vu73

property e:assk-vu73 t:meta.view v:id=assk-vu73 v:category="Energy & Environment" v:attributionLink=http://www.nyserda.ny.gov/All-Programs/Programs/Home-Performance-With-ENERGY-STAR v:averageRating=0 v:name="The One- to Four-Family Home Performance with ENERGY STAR? Program: Beginning 2010" v:attribution="The New York State Energy Research and Development Authority Home Performance with ENERGY STAR Program"

property e:assk-vu73 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:assk-vu73 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| reporting_period    | home_performance_project_id | home_performance_site_id | project_county | project_city   | project_zip | gas_utility | electric_utility | project_completion_date | customer_type | low_rise_or_home_performance_indicator | total_project_cost_usd | total_incentives_usd | type_of_program_financing | amount_financed_through_program_usd | pre_retrofit_home_heating_fuel_type | estimated_annual_kwh_savings | estimated_annual_mmbtu_savings | first_year_energy_savings_estimate_usd | homeowner_received_green_jobs_green_ny_free_reduced_cost_audit_y_n | 
| =================== | =========================== | ======================== | ============== | ============== | =========== | =========== | ================ | ======================= | ============= | ====================================== | ====================== | ==================== | ========================= | =================================== | =================================== | ============================ | ============================== | ====================================== | ================================================================== | 
| 2016-10-31T00:00:00 | P00000754076                | S00000149146             | Onondaga       | Fabius         | 13063       |             | National Grid    | 2012-01-17T00:00:00     | Market        | 1-4 Family Home Performance Program    | 21150                  | 4000                 |                           | 0                                   | Oil                                 | 0                            | 74.762788                      | 1844.93                                | No                                                                 | 
| 2016-10-31T00:00:00 | P00000762852                | S00000155306             | Erie           | Akron          | 14001       |             | National Grid    | 2012-01-27T00:00:00     | Market        | 1-4 Family Home Performance Program    | 5600                   | 1540                 |                           | 0                                   | Oil                                 | 0                            | 35.391103                      | 591.02                                 | Yes                                                                | 
| 2016-10-31T00:00:00 | P00000746648                | S00000143667             | Rensselaer     | Troy           | 12180       |             | National Grid    | 2011-12-01T00:00:00     | Market        | 1-4 Family Home Performance Program    | 6586                   | 1780                 |                           | 0                                   | Oil                                 | 0                            | 44.942896                      | 1109.06                                | No                                                                 | 
| 2016-10-31T00:00:00 | P00000765685                | S00000157282             | Oneida         | Utica          | 13502       |             | National Grid    | 2012-02-27T00:00:00     | Market        | 1-4 Family Home Performance Program    | 5100                   | 1020                 |                           | 0                                   | Oil                                 | 0                            | 30.602052                      | 755.18                                 | Yes                                                                | 
| 2016-10-31T00:00:00 | P00000780513                | S00000167844             | Jefferson      | Three Mile Bay | 13693       |             | National Grid    | 2012-07-06T00:00:00     | Assisted      | 1-4 Family Home Performance Program    | 10000                  | 5000                 |                           | 0                                   | Propane                             | 0                            | 18.664981                      | 688.95                                 | Yes                                                                | 
| 2016-10-31T00:00:00 | P00000780963                | S00000168086             | Oneida         | Rome           | 13440       |             | National Grid    | 2012-06-19T00:00:00     | Market        | 1-4 Family Home Performance Program    | 6570                   | 657                  |                           | 0                                   | Oil                                 | 0                            | 73.209116                      | 1927.38                                | Yes                                                                | 
| 2016-10-31T00:00:00 | P00000803412                | S00000026218             | Erie           | Buffalo        | 14217       |             | National Grid    | 2012-11-06T00:00:00     | Assisted      | 1-4 Family Home Performance Program    | 2425                   | 1212.5               |                           | 0                                   | Oil                                 | 0                            | 16.785868                      | 1499.68                                | No                                                                 | 
| 2016-10-31T00:00:00 | P00000798660                | S00000180465             | Genesee        | Corfu          | 14036       |             | National Grid    | 2012-11-19T00:00:00     | Market        | 1-4 Family Home Performance Program    | 4810                   | 461                  |                           | 0                                   | Propane                             | 0                            | 14.993255                      | 441.75                                 | Yes                                                                | 
| 2016-10-31T00:00:00 | P00000804706                | S00000184626             | Jefferson      | Adams          | 13605       |             | National Grid    | 2012-12-12T00:00:00     | Assisted      | 1-4 Family Home Performance Program    | 3275                   | 1637.5               |                           | 0                                   | Oil                                 | 0                            | 25.26486                       | 338.59                                 | Yes                                                                | 
| 2016-10-31T00:00:00 | P00000805657                | S00000185358             | Oneida         | Utica          | 13502       |             | National Grid    | 2012-11-23T00:00:00     | Assisted      | 1-4 Family Home Performance Program    | 2000                   | 1000                 |                           | 0                                   | Oil                                 | 0                            | 25.469595                      | 670.54                                 | Yes                                                                | 
```