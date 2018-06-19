# Community-Wide Greenhouse Gas Emissions

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/greenhouse-gas-emissions) |
| Metadata | [Link](https://data.lacity.org/api/views/y3m9-i8tg) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/y3m9-i8tg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/y3m9-i8tg/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | y3m9-i8tg |
| Name | Community-Wide Greenhouse Gas Emissions |
| Category | A Livable and Sustainable City |
| Tags | climate, sustainability, carbon, environment |
| Created | 2017-01-17T21:08:50Z |
| Publication Date | 2017-01-17T21:30:08Z |

## Description

This greenhouse gas inventory is based on the Global Protocol for Community-Scale Greenhouse Gas Emissions (pdf attached). The City of LA collects and publicly reports these metrics in order to manage and reduce our GHG impact. 

Data is from 2013. Learn more about the Mayor's Office of Sustainability and our roadmap for a cleaner environment and stronger economy at https://www.lamayor.org/plan

## Columns

```ls
| Included | Schema Type    | Field Name                           | Name                                  | Data Type | Render Type |
| ======== | ============== | ==================================== | ===================================== | ========= | =========== |
| No       | time           | :updated_at                          | updated_at                            | meta_data | meta_data   |
| Yes      | series tag     | gpc_ref_no                           | GPC ref No.                           | text      | text        |
| Yes      | numeric metric | scope                                | Scope                                 | number    | number      |
| Yes      | series tag     | ghg_emissions_source                 | GHG Emissions Source                  | text      | text        |
| Yes      | series tag     | sector                               | Sector                                | text      | text        |
| Yes      | series tag     | sub_sector                           | Sub-Sector                            | text      | text        |
| Yes      | series tag     | notation_keys                        | Notation keys                         | text      | text        |
| Yes      | numeric metric | co2                                  | CO2                                   | number    | number      |
| Yes      | numeric metric | ch4                                  | CH4                                   | number    | number      |
| Yes      | numeric metric | n2o                                  | N2O                                   | number    | number      |
| Yes      | numeric metric | total_tco2e                          | Total tCO2e                           | number    | number      |
| Yes      | numeric metric | co2_b                                | CO2(b)                                | number    | number      |
| Yes      | series tag     | explanation_for_using_notation_key_s | Explanation for using notation key(s) | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:y3m9-i8tg d:2017-01-17T21:09:02.000Z t:sector="Stationary Energy" t:gpc_ref_no=I.1.1 t:ghg_emissions_source="Emissions from fuel combustion within the city boundary" t:sub_sector="Residential buildings" m:n2o=1343 m:ch4=1419 m:total_tco2e=2691921 m:scope=1 m:co2=2689158 m:co2_b=0

series e:y3m9-i8tg d:2017-01-17T21:09:02.000Z t:sector="Stationary Energy" t:gpc_ref_no=I.1.2 t:ghg_emissions_source="Emissions from grid-supplied energy consumed within the city boundary" t:sub_sector="Residential buildings" m:n2o=4388 m:ch4=2545 m:total_tco2e=3321786 m:scope=2 m:co2=3314853 m:co2_b=0

series e:y3m9-i8tg d:2017-01-17T21:09:02.000Z t:sector="Stationary Energy" t:gpc_ref_no=I.1.3 t:ghg_emissions_source="Transmission and distribution losses from grid-supplied energy" t:sub_sector="Residential buildings" m:n2o=527 m:ch4=305 m:total_tco2e=398614 m:scope=3 m:co2=397782 m:co2_b=0
```

## Meta Commands

```ls
metric m:scope p:integer l:Scope d:"Scope 1: All direct emissions from sources within the geopolitical boundary of the community. // Scope 2: Energy-related indirect emissions that occur outside the community boundary as a consequence of consumption/use of grid-supplied electricity, heating and/or cooling within the community boundary. // Scope 3: All other indirect emissions that occur outside the boundary as a result of activities within the community?s geopolitical boundary, as well as trans-boundary emissions due to exchange/use/consumption of goods and services" t:dataTypeName=number

metric m:co2 p:integer l:CO2 d:"in metric tons" t:dataTypeName=number

metric m:ch4 p:integer l:CH4 d:"in metric tons" t:dataTypeName=number

metric m:n2o p:integer l:N2O d:"in metric tons" t:dataTypeName=number

metric m:total_tco2e p:integer l:"Total tCO2e" d:"in metric tons" t:dataTypeName=number

metric m:co2_b p:integer l:CO2(b) d:"in metric tons" t:dataTypeName=number

entity e:y3m9-i8tg l:"Community-Wide Greenhouse Gas Emissions" t:url=https://data.lacity.org/api/views/y3m9-i8tg

property e:y3m9-i8tg t:meta.view v:id=y3m9-i8tg v:category="A Livable and Sustainable City" v:averageRating=0 v:name="Community-Wide Greenhouse Gas Emissions"

property e:y3m9-i8tg t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:y3m9-i8tg t:meta.view.owner v:id=95pg-i79k v:profileImageUrlMedium=/api/users/95pg-i79k/profile_images/THUMB v:profileImageUrlLarge=/api/users/95pg-i79k/profile_images/LARGE v:screenName=ChelseaU v:profileImageUrlSmall=/api/users/95pg-i79k/profile_images/TINY v:displayName=ChelseaU

property e:y3m9-i8tg t:meta.view.tableauthor v:id=95pg-i79k v:profileImageUrlMedium=/api/users/95pg-i79k/profile_images/THUMB v:profileImageUrlLarge=/api/users/95pg-i79k/profile_images/LARGE v:screenName=ChelseaU v:profileImageUrlSmall=/api/users/95pg-i79k/profile_images/TINY v:roleName=administrator v:displayName=ChelseaU
```

## Top Records

```ls
| :updated_at | gpc_ref_no | scope | ghg_emissions_source                                                                      | sector            | sub_sector                                            | notation_keys | co2     | ch4  | n2o  | total_tco2e | co2_b  | explanation_for_using_notation_key_s | 
| =========== | ========== | ===== | ========================================================================================= | ================= | ===================================================== | ============= | ======= | ==== | ==== | =========== | ====== | ==================================== | 
| 1484687342  | I.1.1      | 1     | Emissions from fuel combustion within the city boundary                                   | Stationary Energy | Residential buildings                                 |               | 2689158 | 1419 | 1343 | 2691921     | 0      |                                      | 
| 1484687342  | I.1.2      | 2     | Emissions from grid-supplied energy consumed within the city boundary                     | Stationary Energy | Residential buildings                                 |               | 3314853 | 2545 | 4388 | 3321786     | 0      |                                      | 
| 1484687342  | I.1.3      | 3     | Transmission and distribution losses from grid-supplied energy                            | Stationary Energy | Residential buildings                                 |               | 397782  | 305  | 527  | 398614      | 0      |                                      | 
| 1484687342  | I.2.1      | 1     | Emissions from fuel combustion within the city boundary                                   | Stationary Energy | Commercial and institutional buildings and facilities |               | 1415354 | 747  | 707  | 1416807     | 0      |                                      | 
| 1484687342  | I.2.2      | 2     | Emissions from grid-supplied energy consumed within the city boundary                     | Stationary Energy | Commercial and institutional buildings and facilities |               | 5291479 | 4062 | 7005 | 5302546     | 0      |                                      | 
| 1484687342  | I.2.3      | 3     | Transmission and distribution losses from grid-supplied energy                            | Stationary Energy | Commercial and institutional buildings and facilities |               | 634977  | 487  | 841  | 636306      | 0      |                                      | 
| 1484687342  | I.3.1      | 1     | Emissions from fuel combustion within the city boundary                                   | Stationary Energy | Manufacturing industries and construction             |               | 2996486 | 1905 | 2192 | 3000583     | 282968 |                                      | 
| 1484687342  | I.3.2      | 2     | Emissions from grid-supplied energy consumed within the city boundary                     | Stationary Energy | Manufacturing industries and construction             |               | 814089  | 625  | 1078 | 815792      | 0      |                                      | 
| 1484687342  | I.3.3      | 3     | Transmission and distribution losses from grid-supplied energy                            | Stationary Energy | Manufacturing industries and construction             |               | 97691   | 75   | 129  | 97895       | 0      |                                      | 
| 1484687342  | I.4.1      | 1     | Emissions from energy production used in power plant auxiliary operations within the city | Stationary Energy | Energy industries                                     |               | 784229  | 314  | 286  | 784829      | 0      |                                      | 
```