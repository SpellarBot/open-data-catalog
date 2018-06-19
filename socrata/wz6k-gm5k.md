# Capital Investment Plan Projects FY16-26

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/capital-investment-plan-projects-fy16-26) |
| Metadata | [Link](https://data.somervillema.gov/api/views/wz6k-gm5k) |
| Data: JSON | [100 Rows](https://data.somervillema.gov/api/views/wz6k-gm5k/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.somervillema.gov/api/views/wz6k-gm5k/rows.csv?max_rows=100) |
| Host | data.somervillema.gov |
| Id | wz6k-gm5k |
| Name | Capital Investment Plan Projects FY16-26 |
| Attribution | City of Somerville Capital Projects Committee |
| Category | Finance |
| Tags | capital plan, budget |
| Created | 2015-11-04T14:52:09Z |
| Publication Date | 2016-02-09T20:04:36Z |

## Description

The City develops annually a Capital Investment Plan (CIP), which is a document that outlines capital projects for the next ten years, including infrastructure projects, building improvements, park redesigns, and equipment purchases. It also provides a proposed schedule and identifies financing options.

This version was submitted to the Board of Aldermen in January of 2016 and will be updated in late 2016.

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type | Render Type |
| ======== | ============== | ===================== | ===================== | ========= | =========== |
| No       | time           | :updated_at           | updated_at            | meta_data | meta_data   |
| Yes      | series tag     | project               | Project               | text      | text        |
| Yes      | series tag     | department            | Department            | text      | text        |
| Yes      | series tag     | type                  | Type                  | text      | text        |
| Yes      | series tag     | funding_source        | Funding Source        | text      | text        |
| Yes      | series tag     | status                | Status                | text      | text        |
| Yes      | numeric metric | total                 | TOTAL                 | money     | money       |
| Yes      | numeric metric | 2016                  | 2016                  | money     | money       |
| Yes      | numeric metric | 2017                  | 2017                  | money     | money       |
| Yes      | numeric metric | 2018                  | 2018                  | money     | money       |
| Yes      | numeric metric | 2019                  | 2019                  | money     | money       |
| Yes      | numeric metric | 2020                  | 2020                  | money     | money       |
| Yes      | numeric metric | 2021                  | 2021                  | money     | money       |
| Yes      | numeric metric | 2022                  | 2022                  | money     | money       |
| Yes      | numeric metric | 2023                  | 2023                  | money     | money       |
| Yes      | numeric metric | 2024                  | 2024                  | money     | money       |
| Yes      | numeric metric | 2025                  | 2025                  | money     | money       |
| Yes      | series tag     | project_description   | Project Description   | text      | text        |
| Yes      | series tag     | project_justification | Project Justification | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:wz6k-gm5k d:2015-11-23T08:50:05.000Z t:project="Decorative Barrels & Benches" t:project_justification="These elegant but durable benches and barrels will improve the aesthetics of the city?s streetscapes, decrease litter on city streets, and encourage pedestrian traffic. There are currently 600 decorative trash barrels in our streets and parks; the City aspires to accompany each with a recycling barrel." t:status=Approved t:department=DPW t:funding_source="Debt Service, Capital Stabilization" t:type=Recurring t:project_description="Purchase decorative recycling and trash barrels and benches to be installed throughout the city. These items are built to withstand the elements, are easily cleanable (i.e. graffiti, gum), and require very little maintenance." m:2017=100000 m:total=1000000 m:2018=100000 m:2019=100000 m:2016=100000 m:2021=100000 m:2025=100000 m:2020=100000 m:2024=100000 m:2023=100000 m:2022=100000

series e:wz6k-gm5k d:2016-02-09T10:53:14.000Z t:project="ADA Curb Ramps, Sidewalks & Accessible Street Crossing Signals" t:project_justification="Somerville?s aging infrastructure has a significant backlog of ADA concerns which are addressed both as part of the ADA transition plan and on an ongoing basis as they arise. The City plans on making recurring investments to remediate these issues over the coming years. This $1M each year will be used to remediate non-compliant curb ramps, install crosswalks signage, and resolve any compliance issues that arise." t:status=Approved t:department=DPW t:funding_source="Debt Service" t:type=Recurring t:project_description="Funding for ADA curb ramps, sidewalks, and accessibility features throughout the city as outlined in the City?s ADA Transition Plan." m:2017=1000000 m:total=10000000 m:2018=1000000 m:2019=1000000 m:2016=1000000 m:2021=1000000 m:2025=1000000 m:2020=1000000 m:2024=1000000 m:2023=1000000 m:2022=1000000

series e:wz6k-gm5k d:2016-02-09T10:54:21.000Z t:project="Accessibility Improvements - Public Buildings & Communication" t:project_justification="The City owns and maintains several buildings that are not in compliance with current accessibility standards. The 2013 ADA Self-Evaluation identified millions in accessibility improvements at public buildings. The City will bring these buildings into compliance over time with annual capital investments as outlined in the 2015 ADA Transition Plan." t:status=Approved t:department=DPW t:funding_source="Debt Service, CDBG" t:type=Recurring t:project_description="Design, construction, and installation of accessibility improvements to schools and other public buildings." m:2017=500000 m:total=5000000 m:2018=500000 m:2019=500000 m:2016=500000 m:2021=500000 m:2025=500000 m:2020=500000 m:2024=500000 m:2023=500000 m:2022=500000
```

## Meta Commands

```ls
metric m:total p:integer l:TOTAL t:dataTypeName=money

metric m:2016 p:integer l:2016 t:dataTypeName=money

metric m:2017 p:integer l:2017 t:dataTypeName=money

metric m:2018 p:integer l:2018 t:dataTypeName=money

metric m:2019 p:integer l:2019 t:dataTypeName=money

metric m:2020 p:integer l:2020 t:dataTypeName=money

metric m:2021 p:integer l:2021 t:dataTypeName=money

metric m:2022 p:integer l:2022 t:dataTypeName=money

metric m:2023 p:integer l:2023 t:dataTypeName=money

metric m:2024 p:integer l:2024 t:dataTypeName=money

metric m:2025 p:integer l:2025 t:dataTypeName=money

entity e:wz6k-gm5k l:"Capital Investment Plan Projects FY16-26" t:attribution="City of Somerville Capital Projects Committee" t:url=https://data.somervillema.gov/api/views/wz6k-gm5k

property e:wz6k-gm5k t:meta.view v:id=wz6k-gm5k v:category=Finance v:attributionLink=http://www.somervillema.gov/departments/finance v:averageRating=0 v:name="Capital Investment Plan Projects FY16-26" v:attribution="City of Somerville Capital Projects Committee"

property e:wz6k-gm5k t:meta.view.license v:name="Open Data Commons Open Database License" v:termsLink=http://opendatacommons.org/licenses/odbl/1.0/

property e:wz6k-gm5k t:meta.view.owner v:id=j34k-s96t v:screenName="Michael Mastrobuoni" v:displayName="Michael Mastrobuoni"

property e:wz6k-gm5k t:meta.view.tableauthor v:id=j34k-s96t v:screenName="Michael Mastrobuoni" v:roleName=administrator v:displayName="Michael Mastrobuoni"
```

## Top Records

```ls
| :updated_at | project                                                               | department | type           | funding_source                      | status   | total    | 2016    | 2017    | 2018    | 2019    | 2020    | 2021    | 2022    | 2023    | 2024    | 2025    | project_description                                                                                                                                                                                                               | project_justification                                                                                                                                                                                                                                                                                                                                                                                                           | 
| =========== | ===================================================================== | ========== | ============== | =================================== | ======== | ======== | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ================================================================================================================================================================================================================================= | =============================================================================================================================================================================================================================================================================================================================================================================================================================== | 
| 1448268605  | Decorative Barrels & Benches                                          | DPW        | Recurring      | Debt Service, Capital Stabilization | Approved | 1000000  | 100000  | 100000  | 100000  | 100000  | 100000  | 100000  | 100000  | 100000  | 100000  | 100000  | Purchase decorative recycling and trash barrels and benches to be installed throughout the city. These items are built to withstand the elements, are easily cleanable (i.e. graffiti, gum), and require very little maintenance. | These elegant but durable benches and barrels will improve the aesthetics of the city?s streetscapes, decrease litter on city streets, and encourage pedestrian traffic. There are currently 600 decorative trash barrels in our streets and parks; the City aspires to accompany each with a recycling barrel.                                                                                                                 | 
| 1455015194  | ADA Curb Ramps, Sidewalks & Accessible Street Crossing Signals        | DPW        | Recurring      | Debt Service                        | Approved | 10000000 | 1000000 | 1000000 | 1000000 | 1000000 | 1000000 | 1000000 | 1000000 | 1000000 | 1000000 | 1000000 | Funding for ADA curb ramps, sidewalks, and accessibility features throughout the city as outlined in the City?s ADA Transition Plan.                                                                                              | Somerville?s aging infrastructure has a significant backlog of ADA concerns which are addressed both as part of the ADA transition plan and on an ongoing basis as they arise. The City plans on making recurring investments to remediate these issues over the coming years. This $1M each year will be used to remediate non-compliant curb ramps, install crosswalks signage, and resolve any compliance issues that arise. | 
| 1455015261  | Accessibility Improvements - Public Buildings & Communication         | DPW        | Recurring      | Debt Service, CDBG                  | Approved | 5000000  | 500000  | 500000  | 500000  | 500000  | 500000  | 500000  | 500000  | 500000  | 500000  | 500000  | Design, construction, and installation of accessibility improvements to schools and other public buildings.                                                                                                                       | The City owns and maintains several buildings that are not in compliance with current accessibility standards. The 2013 ADA Self-Evaluation identified millions in accessibility improvements at public buildings. The City will bring these buildings into compliance over time with annual capital investments as outlined in the 2015 ADA Transition Plan.                                                                   | 
| 1455015300  | Fire Vehicle Replacement                                              | Fire       | Recurring      | Debt Service                        | Approved | 1073175  | 508800  | 564375  |         |         |         |         |         |         |         |         | Replacement vehicles for the Somerville Fire Department fleet.                                                                                                                                                                    | The City combines National Fire Protection Association recommendations with current vehicle conditions to develop a long-term replacement plan for all departmental vehicles. Properly functioning assets are critical to operations and the safety of residents.                                                                                                                                                               | 
| 1455017138  | Backlog Sidewalk Repairs (Second Contract)                            | DPW        | Infrastructure | Debt Service                        | Approved | 200000   | 200000  |         |         |         |         |         |         |         |         |         | Contract services to remediate a backlog of sidewalk repair issues.                                                                                                                                                               | Due to capacity issues, the Department of Public Works retains a backlog of sidewalk repairs throughout the city which it cannot complete. The use of contractors to remediate this list of projects will allow the DPW to focus on new work orders and ensure their timely completion.                                                                                                                                         | 
| 1455017689  | Citywide Mobility Plan                                                | T&I        | One-Time       | Capital Stabilization               | Approved | 470000   | 470000  |         |         |         |         |         |         |         |         |         | Develop a Citywide Mobility Plan in collaboration with a contractor.                                                                                                                                                              | A Mobility Plan will be employed to guide the planning, design, renovation, and expansion of the city?s transportation-related infrastructure improvements including; streets, walkways, signage, bike paths, parking facilities, and connections to public transit, state highways, waterways, and access to marine and air facilities.                                                                                        | 
| 1455017787  | Hubway Bicycle Share (6 New Stations)                                 | T&I        | One-Time       | Debt Service                        | Approved | 360000   |         | 180000  | 180000  |         |         |         |         |         |         |         | Expansion of the Somerville Hubway bicycle sharing program by adding six new stations over the next two years.                                                                                                                    | The City would like to expand the Hubway bicycle sharing network by adding new stations in East Somerville and other under served locations.                                                                                                                                                                                                                                                                                    | 
| 1455018100  | Big Belly Purchase                                                    | DPW        | One-Time       | Debt Service                        | Approved | 200000   | 200000  |         |         |         |         |         |         |         |         |         | Purchase Big Belly trash receptacles to be installed throughout the city. These trash barrels are able to be remotely monitored by Public Works employees for more efficient clearing.                                            | Big Belly trash receptacles are an improvement over traditional trash barrels. By reporting their current capacity, these barrels inform City staff when they need to be cleared and can therefore increase productivity. Additionally, these barrels can be branded, refurbished, and last longer than traditional refuse containers.                                                                                          | 
| 1455018130  | Hybrid Refuse Trucks (2) Supplemental Request to Replacement Schedule | DPW        | One-Time       | Debt Service                        | Approved | 250000   | 250000  |         |         |         |         |         |         |         |         |         | Purchase of two hybrid refuse trucks to replace aging vehicles in the City?s fleet.                                                                                                                                               | The two hybrid refuse trucks will replace city vehicles that have reached the end of their useful life. Intended to be used to clear trash barrels throughout the city, these hybrid vehicles will also be more energy efficient than the vehicles they will be replacing.                                                                                                                                                      | 
| 1455018189  | New Voting Equipment                                                  | Elections  | One-Time       | Capital Stabilization               | Approved | 160000   | 160000  |         |         |         |         |         |         |         |         |         | Purchase new voting machines in preparation for the 2016 general election.                                                                                                                                                        | The City?s current voting machines have served their useful life and are in need of replacement. Newer models will be less likely to malfunction, require less ongoing maintenance, and can have wireless transmission of election results (when approved by the State). All these factors will provide for a better voting experience for Somerville residents.                                                                | 
```