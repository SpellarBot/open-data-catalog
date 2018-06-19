# Energy Efficiency Completed Projects: Beginning 1987

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/energy-efficiency-completed-projects-beginning-1987) |
| Metadata | [Link](https://data.ny.gov/api/views/erjw-j2zx) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/erjw-j2zx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/erjw-j2zx/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | erjw-j2zx |
| Name | Energy Efficiency Completed Projects: Beginning 1987 |
| Attribution | New York Power Authority |
| Category | Energy & Environment |
| Tags | energy, efficiency, renewables |
| Created | 2013-02-25T15:12:17Z |
| Publication Date | 2016-08-02T22:05:11Z |

## Description

The Energy Efficiency programs of the New York Power Authority provide energy-efficiency improvements, with no up-front costs, to public schools and other government facilities. From start to finish, the Power Authority works with facility managers to identify, design and install new lighting and motors, as well as upgrades to heating, ventilation and air-conditioning systems. We try to address all energy efficiency improvements in a single, comprehensive effort.  This data set contains information on energy efficiency projects completed since 1987. The data set is updated in a quarterly basis to reflect new data as projects are implemented. The information includes project location, customer name, project name, total cost, and energy efficiency benefits, including energy reduction (electric, natural gas, oil) and greenhouse gas emissions reductions.

## Columns

```ls
| Included | Schema Type    | Field Name                                 | Name                                         | Data Type     | Render Type   |
| ======== | ============== | ========================================== | ============================================ | ============= | ============= |
| No       |                | year_completed                             | Year completed                               | number        | number        |
| Yes      | time           | date_completed                             | Date Completed                               | calendar_date | calendar_date |
| Yes      | series tag     | project_code                               | Project Code                                 | text          | text          |
| Yes      | series tag     | project_name                               | Project Name                                 | text          | text          |
| Yes      | series tag     | regional_economic_development_council      | Regional Economic Development Council        | text          | text          |
| Yes      | series tag     | nyiso_zone                                 | NYISO Zone                                   | text          | text          |
| Yes      | series tag     | ny_state_county                            | NY State County                              | text          | text          |
| Yes      | series tag     | ny_region                                  | NY Region                                    | text          | text          |
| Yes      | series tag     | customer                                   | Customer                                     | text          | text          |
| Yes      | series tag     | agency                                     | Agency                                       | text          | text          |
| Yes      | series tag     | project_category                           | Project category                             | text          | text          |
| Yes      | series tag     | facility_description                       | Facility Description                         | text          | text          |
| Yes      | numeric metric | number_of_facilities                       | Number of Facilities                         | number        | number        |
| Yes      | numeric metric | total_project_cost                         | Total Project Cost                           | money         | money         |
| Yes      | numeric metric | first_year_bill_savings                    | First Year Bill Savings                      | money         | money         |
| Yes      | numeric metric | demand_reduction_kw                        | Demand Reduction (KW)                        | number        | number        |
| Yes      | numeric metric | electric_energy_reduction_kwh              | Electric Energy Reduction (kWh)              | number        | number        |
| Yes      | numeric metric | gas_savings_therms                         | Gas Savings (Therms)                         | number        | number        |
| Yes      | numeric metric | oil_savings_gallons                        | Oil Savings (Gallons)                        | number        | number        |
| Yes      | numeric metric | steam_savings_m_lbs                        | Steam Savings (M Lbs)                        | number        | number        |
| Yes      | numeric metric | digester_gas_savings_ccf                   | Digester Gas Savings (CCF)                   | number        | number        |
| Yes      | numeric metric | coal_savings_tons                          | Coal Savings (Tons)                          | number        | number        |
| Yes      | numeric metric | equivalent_barrels_of_oil_saved            | Equivalent Barrels of Oil Saved              | number        | number        |
| Yes      | numeric metric | reduction_in_greenhouse_gas_emissions_tons | Reduction in Greenhouse Gas Emissions (Tons) | number        | number        |
| Yes      | numeric metric | renewable_energy_kw                        | Renewable Energy (KW)                        | number        | number        |
| No       |                | address                                    | Address                                      | text          | text          |
| No       |                | address_ext                                | Address Ext                                  | text          | text          |
| Yes      | series tag     | city                                       | City                                         | text          | text          |
| Yes      | series tag     | state                                      | State                                        | text          | text          |
| Yes      | series tag     | zip                                        | Zip                                          | text          | text          |
| Yes      | series tag     | project_or_program_description             | Project or Program description               | text          | text          |
```

## Time Field

```ls
Value = date_completed
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address,address_ext,year_completed
```

## Data Commands

```ls
series e:erjw-j2zx d:1987-12-31T00:00:00.000Z t:facility_description="Municipal Utility" t:project_name="Watt Busters - SKANEATELES" t:ny_state_county=ONONDAGA t:project_or_program_description="Home energy audits and weatherization services were provided to residential customers served by NYPA?s municipal and cooperative system customers. This program was funded by NYPA financing." t:state=NY t:project_category="Energy Efficiency" t:ny_region=Central t:regional_economic_development_council="Central New York" t:project_code=CH79001 t:customer="SKANEATELES, TOWN OF" t:nyiso_zone="C - Central" m:gas_savings_therms=0 m:number_of_facilities=1 m:equivalent_barrels_of_oil_saved=27.58621 m:electric_energy_reduction_kwh=16000 m:coal_savings_tons=0 m:steam_savings_m_lbs=0 m:total_project_cost=17396 m:oil_savings_gallons=0 m:demand_reduction_kw=7 m:renewable_energy_kw=0 m:reduction_in_greenhouse_gas_emissions_tons=8 m:first_year_bill_savings=632.93

series e:erjw-j2zx d:1987-12-31T00:00:00.000Z t:facility_description="Municipal Utility" t:project_name="Watt Busters - SHERRILL" t:ny_state_county=ONEIDA t:project_or_program_description="Home energy audits and weatherization services were provided to residential customers served by NYPA?s municipal and cooperative system customers. This program was funded by NYPA financing." t:state=NY t:project_category="Energy Efficiency" t:ny_region=Central t:regional_economic_development_council="Mohawk Valley" t:project_code=CH79002 t:customer="SHERRILL, CITY OF" t:nyiso_zone="E - Mohawk Valley" m:gas_savings_therms=0 m:number_of_facilities=1 m:equivalent_barrels_of_oil_saved=132.7586 m:electric_energy_reduction_kwh=77000 m:coal_savings_tons=0 m:steam_savings_m_lbs=0 m:total_project_cost=41098 m:oil_savings_gallons=0 m:demand_reduction_kw=30 m:renewable_energy_kw=0 m:reduction_in_greenhouse_gas_emissions_tons=40 m:first_year_bill_savings=1728.68

series e:erjw-j2zx d:1987-12-31T00:00:00.000Z t:facility_description="Municipal Utility" t:project_name="Watt Busters - GROTON" t:ny_state_county=TOMPKINS t:project_or_program_description="Home energy audits and weatherization services were provided to residential customers served by NYPA?s municipal and cooperative system customers. This program was funded by NYPA financing." t:state=NY t:project_category="Energy Efficiency" t:ny_region=Central t:regional_economic_development_council="Southern Tier" t:project_code=CH10725 t:customer="GROTON, VILLAGE OF" t:nyiso_zone="C - Central" m:gas_savings_therms=0 m:number_of_facilities=1 m:equivalent_barrels_of_oil_saved=456.8966 m:electric_energy_reduction_kwh=265000 m:coal_savings_tons=0 m:steam_savings_m_lbs=0 m:total_project_cost=65284 m:oil_savings_gallons=0 m:demand_reduction_kw=101 m:renewable_energy_kw=0 m:reduction_in_greenhouse_gas_emissions_tons=136 m:first_year_bill_savings=9175.02
```

## Meta Commands

```ls
metric m:number_of_facilities p:integer l:"Number of Facilities" t:dataTypeName=number

metric m:total_project_cost p:double l:"Total Project Cost" t:dataTypeName=money

metric m:first_year_bill_savings p:double l:"First Year Bill Savings" t:dataTypeName=money

metric m:demand_reduction_kw p:double l:"Demand Reduction (KW)" t:dataTypeName=number

metric m:electric_energy_reduction_kwh p:double l:"Electric Energy Reduction (kWh)" t:dataTypeName=number

metric m:gas_savings_therms p:integer l:"Gas Savings (Therms)" t:dataTypeName=number

metric m:oil_savings_gallons p:integer l:"Oil Savings (Gallons)" t:dataTypeName=number

metric m:steam_savings_m_lbs p:integer l:"Steam Savings (M Lbs)" t:dataTypeName=number

metric m:digester_gas_savings_ccf p:float l:"Digester Gas Savings (CCF)" t:dataTypeName=number

metric m:coal_savings_tons p:integer l:"Coal Savings (Tons)" t:dataTypeName=number

metric m:equivalent_barrels_of_oil_saved p:float l:"Equivalent Barrels of Oil Saved" t:dataTypeName=number

metric m:reduction_in_greenhouse_gas_emissions_tons p:integer l:"Reduction in Greenhouse Gas Emissions (Tons)" t:dataTypeName=number

metric m:renewable_energy_kw p:double l:"Renewable Energy (KW)" t:dataTypeName=number

entity e:erjw-j2zx l:"Energy Efficiency Completed Projects: Beginning 1987" t:attribution="New York Power Authority" t:url=https://data.ny.gov/api/views/erjw-j2zx

property e:erjw-j2zx t:meta.view v:id=erjw-j2zx v:category="Energy & Environment" v:attributionLink=http://www.nypa.gov/services/esp.htm v:averageRating=0 v:name="Energy Efficiency Completed Projects: Beginning 1987" v:attribution="New York Power Authority"

property e:erjw-j2zx t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:erjw-j2zx t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:erjw-j2zx t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| year_completed | date_completed      | project_code | project_name               | regional_economic_development_council | nyiso_zone        | ny_state_county | ny_region | customer                | agency | project_category  | facility_description | number_of_facilities | total_project_cost | first_year_bill_savings | demand_reduction_kw | electric_energy_reduction_kwh | gas_savings_therms | oil_savings_gallons | steam_savings_m_lbs | digester_gas_savings_ccf | coal_savings_tons | equivalent_barrels_of_oil_saved | reduction_in_greenhouse_gas_emissions_tons | renewable_energy_kw | address | address_ext | city | state | zip | project_or_program_description                                                                                                                                                                | 
| ============== | =================== | ============ | ========================== | ===================================== | ================= | =============== | ========= | ======================= | ====== | ================= | ==================== | ==================== | ================== | ======================= | =================== | ============================= | ================== | =================== | =================== | ======================== | ================= | =============================== | ========================================== | =================== | ======= | =========== | ==== | ===== | === | ============================================================================================================================================================================================= | 
| 1987           | 1987-12-31T00:00:00 | CH79001      | Watt Busters - SKANEATELES | Central New York                      | C - Central       | ONONDAGA        | Central   | SKANEATELES, TOWN OF    |        | Energy Efficiency | Municipal Utility    | 1                    | 17396.00           | 632.93                  | 7                   | 16000                         | 0                  | 0                   | 0                   |                          | 0                 | 27.58621                        | 8                                          | 0                   |         |             |      | NY    |     | Home energy audits and weatherization services were provided to residential customers served by NYPA?s municipal and cooperative system customers. This program was funded by NYPA financing. | 
| 1987           | 1987-12-31T00:00:00 | CH79002      | Watt Busters - SHERRILL    | Mohawk Valley                         | E - Mohawk Valley | ONEIDA          | Central   | SHERRILL, CITY OF       |        | Energy Efficiency | Municipal Utility    | 1                    | 41098.00           | 1728.68                 | 30                  | 77000                         | 0                  | 0                   | 0                   |                          | 0                 | 132.7586                        | 40                                         | 0                   |         |             |      | NY    |     | Home energy audits and weatherization services were provided to residential customers served by NYPA?s municipal and cooperative system customers. This program was funded by NYPA financing. | 
| 1987           | 1987-12-31T00:00:00 | CH10725      | Watt Busters - GROTON      | Southern Tier                         | C - Central       | TOMPKINS        | Central   | GROTON, VILLAGE OF      |        | Energy Efficiency | Municipal Utility    | 1                    | 65284.00           | 9175.02                 | 101                 | 265000                        | 0                  | 0                   | 0                   |                          | 0                 | 456.8966                        | 136                                        | 0                   |         |             |      | NY    |     | Home energy audits and weatherization services were provided to residential customers served by NYPA?s municipal and cooperative system customers. This program was funded by NYPA financing. | 
| 1988           | 1988-12-31T00:00:00 | CH79003      | Watt Busters - BERGEN      | Finger Lakes                          | A - West          | GENESEE         | Western   | BERGEN, VILLAGE OF      |        | Energy Efficiency | Municipal Utility    | 1                    | 20049.00           | 1182.27                 | 9                   | 21000                         | 0                  | 0                   | 0                   |                          | 0                 | 36.2069                         | 11                                         | 0                   |         |             |      | NY    |     | Home energy audits and weatherization services were provided to residential customers served by NYPA?s municipal and cooperative system customers. This program was funded by NYPA financing. | 
| 1988           | 1988-12-31T00:00:00 | CH10723      | Watt Busters - SPENCERPORT | Finger Lakes                          | B - Genesee       | MONROE          | Central   | SPENCERPORT, VILLAGE OF |        | Energy Efficiency | Municipal Utility    | 1                    | 174264.00          | 26128.01                | 346                 | 880000                        | 0                  | 0                   | 0                   |                          | 0                 | 1517.241                        | 452                                        | 0                   |         |             |      | NY    |     | Home energy audits and weatherization services were provided to residential customers served by NYPA?s municipal and cooperative system customers. This program was funded by NYPA financing. | 
| 1988           | 1988-12-31T00:00:00 | CH10727      | Watt Busters - ENDICOTT    | Southern Tier                         | C - Central       | BROOME          | Central   | ENDICOTT, VILLAGE OF    |        | Energy Efficiency | Municipal Utility    | 1                    | 51234.00           | 3791.74                 | 37                  | 94000                         | 0                  | 0                   | 0                   |                          | 0                 | 162.069                         | 48                                         | 0                   |         |             |      | NY    |     | Home energy audits and weatherization services were provided to residential customers served by NYPA?s municipal and cooperative system customers. This program was funded by NYPA financing. | 
| 1988           | 1988-12-31T00:00:00 | CH10726      | Watt Busters - DELAWARE    | Southern Tier                         | E - Mohawk Valley | DELAWARE        | Central   | DELAWARE, TOWN OF       |        | Energy Efficiency | Municipal Utility    | 1                    | 129645.00          | 35581.51                | 210                 | 547000                        | 0                  | 0                   | 0                   |                          | 0                 | 943.1035                        | 281                                        | 0                   |         |             |      | NY    |     | Home energy audits and weatherization services were provided to residential customers served by NYPA?s municipal and cooperative system customers. This program was funded by NYPA financing. | 
| 1988           | 1988-12-31T00:00:00 | CH10724      | Watt Busters - BATH        | Southern Tier                         | C - Central       | STEUBEN         | Central   | BATH, VILLAGE OF        |        | Energy Efficiency | Municipal Utility    | 1                    | 181377.00          | 15978.38                | 188                 | 486000                        | 0                  | 0                   | 0                   |                          | 0                 | 837.931                         | 250                                        | 0                   |         |             |      | NY    |     | Home energy audits and weatherization services were provided to residential customers served by NYPA?s municipal and cooperative system customers. This program was funded by NYPA financing. | 
| 1989           | 1989-12-31T00:00:00 | CH10231      | Watt Busters - ARCADE      | Finger Lakes                          | A - West          | WYOMING         | Western   | ARCADE, VILLAGE OF      |        | Energy Efficiency | Municipal Utility    | 1                    | 212381.00          | 36235.98                | 614                 | 1421000                       | 0                  | 0                   | 0                   |                          | 0                 | 2450                            | 730                                        | 0                   |         |             |      | NY    |     | Home energy audits and weatherization services were provided to residential customers served by NYPA?s municipal and cooperative system customers. This program was funded by NYPA financing. | 
| 1989           | 1989-12-31T00:00:00 | CH10232      | Watt Busters - PLATTSBURGH | North Country                         | D - North         | CLINTON         | Northern  | PLATTSBURGH, CITY OF    |        | Energy Efficiency | Municipal Utility    | 1                    | 716402.00          | 126106.56               | 2465                | 5706000                       | 0                  | 0                   | 0                   |                          | 0                 | 9837.932                        | 2933                                       | 0                   |         |             |      | NY    |     | Home energy audits and weatherization services were provided to residential customers served by NYPA?s municipal and cooperative system customers. This program was funded by NYPA financing. | 
```