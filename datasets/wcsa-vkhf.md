# Metropolitan Transportation Authority (MTA) Capital Dashboard Project Locations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/metropolitan-transportation-authority-mta-capital-dashboard-project-locations) |
| Metadata | [Link](https://data.ny.gov/api/views/wcsa-vkhf) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/wcsa-vkhf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/wcsa-vkhf/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | wcsa-vkhf |
| Name | Metropolitan Transportation Authority (MTA) Capital Dashboard Project Locations |
| Attribution | Capital Program Management |
| Category | Transportation |
| Tags | capital program management, capital program dashboard |
| Created | 2016-07-21T14:01:34Z |
| Publication Date | 2016-09-13T15:48:04Z |

## Description

The Capital Dashboard data provides information about the projects in the MTA?s Capital Programs.  The data describes the planned projects and provides information about the status of Project Budgets, Scopes and Schedules. This additional dataset provide the geo-coordinates where applicable for Capital Projects.

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| No       | time           | :updated_at             | updated_at              | meta_data | meta_data   |
| Yes      | series tag     | project_number          | Project Number          | text      | text        |
| Yes      | numeric metric | project_number_sequence | Project Number Sequence | number    | number      |
| Yes      | numeric metric | plan_series             | Plan Series             | number    | number      |
| Yes      | series tag     | capital_plan            | Capital Plan            | text      | text        |
| Yes      | series tag     | agency_name             | Agency Name             | text      | text        |
| Yes      | series tag     | category_description    | Category Description    | text      | text        |
| Yes      | series tag     | element_description     | Element Description     | text      | text        |
| Yes      | series tag     | project_description     | Project Description     | text      | text        |
| No       |                | latitude                | Latitude                | number    | number      |
| No       |                | longitude               | Longitude               | number    | number      |
| Yes      | series tag     | location_indicator      | Location Indicator      | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = latitude,longitude
```

## Data Commands

```ls
series e:wcsa-vkhf d:2016-09-13T15:47:40.000Z t:location_indicator=base t:capital_plan="Capital Plan 2005 - 2009" t:project_number=D501CB08 t:element_description="Cross-Bay Bridge" t:category_description=Structures t:agency_name="Bridges And Tunnels" t:project_description="Deck and structural rehabilitation - Cross Bay Bridge." m:plan_series=5 m:project_number_sequence=1

series e:wcsa-vkhf d:2016-09-13T15:47:40.000Z t:location_indicator=base t:capital_plan="Capital Plan 2005 - 2009" t:project_number=D501TN85 t:element_description="Throgs Neck Bridge" t:category_description=Structures t:agency_name="Bridges And Tunnels" t:project_description="Structural steel repairs at the suspended spans and tower spans of the Throgs Neck Bridge." m:plan_series=5 m:project_number_sequence=1

series e:wcsa-vkhf d:2016-09-13T15:47:40.000Z t:location_indicator=base t:capital_plan="Capital Plan 2005 - 2009" t:project_number=D502BW89 t:element_description="Bronx-Whitestone Bridge" t:category_description="Roadways & Decks" t:agency_name="Bridges And Tunnels" t:project_description="Elevated and on grade approach deck replacement at Whitestone Bridge." m:plan_series=5 m:project_number_sequence=1
```

## Meta Commands

```ls
metric m:project_number_sequence p:integer l:"Project Number Sequence" d:"Projects may have multiple locations. The combination of the Project Number and Project Number Sequence fields create a unique key for each location coordinates record associated with a project." t:dataTypeName=number

metric m:plan_series p:integer l:"Plan Series" d:"This is a code number associated with a specific Capital Plan. 5 = Capital Plan 2005 ? 2009 6 = Capital Plan 2010 ? 2014 7 = Capital Plan 2015 ? 2019" t:dataTypeName=number

entity e:wcsa-vkhf l:"Metropolitan Transportation Authority (MTA) Capital Dashboard Project Locations" t:attribution="Capital Program Management" t:url=https://data.ny.gov/api/views/wcsa-vkhf

property e:wcsa-vkhf t:meta.view v:id=wcsa-vkhf v:category=Transportation v:attributionLink=http://web.mta.info/capitaldashboard/CPDHome.html v:averageRating=0 v:name="Metropolitan Transportation Authority (MTA) Capital Dashboard Project Locations" v:attribution="Capital Program Management"

property e:wcsa-vkhf t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:wcsa-vkhf t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| :updated_at | project_number | project_number_sequence | plan_series | capital_plan             | agency_name         | category_description | element_description     | project_description                                                                                                               | latitude   | longitude   | location_indicator | 
| =========== | ============== | ======================= | =========== | ======================== | =================== | ==================== | ======================= | ================================================================================================================================= | ========== | =========== | ================== | 
| 1473781660  | D501CB08       | 1                       | 5           | Capital Plan 2005 - 2009 | Bridges And Tunnels | Structures           | Cross-Bay Bridge        | Deck and structural rehabilitation - Cross Bay Bridge.                                                                            | 40.5920570 | -73.8197140 | base               | 
| 1473781660  | D501TN85       | 1                       | 5           | Capital Plan 2005 - 2009 | Bridges And Tunnels | Structures           | Throgs Neck Bridge      | Structural steel repairs at the suspended spans and tower spans of the Throgs Neck Bridge.                                        | 40.7999030 | -73.7935420 | base               | 
| 1473781660  | D502BW89       | 1                       | 5           | Capital Plan 2005 - 2009 | Bridges And Tunnels | Roadways & Decks     | Bronx-Whitestone Bridge | Elevated and on grade approach deck replacement at Whitestone Bridge.                                                             | 40.8057680 | -73.8319820 | base               | 
| 1473781660  | D502HH80       | 1                       | 5           | Capital Plan 2005 - 2009 | Bridges And Tunnels | Roadways & Decks     | Henry Hudson Bridge     | Lower level deck replacement at Henry Hudson Bridge.                                                                              | 40.8777880 | -73.9221690 | base               | 
| 1473781660  | D502TB64       | 1                       | 5           | Capital Plan 2005 - 2009 | Bridges And Tunnels | Roadways & Decks     | Triborough Bridge       | Replacement of decks at Randall's Island and Ward's Island Viaduct and new ramps at Robert F. Kennedy Bridge.                     | 40.7904360 | -73.9259510 | base               | 
| 1473781660  | D502TN50       | 1                       | 5           | Capital Plan 2005 - 2009 | Bridges And Tunnels | Roadways & Decks     | Throgs Neck Bridge      | Replacement of concrete deck and rehabilitation of the abutment and retaining walls of the Queens Approach to Throgs Neck Bridge. | 40.8050960 | -73.7935350 | base               | 
| 1473781660  | D502VN80       | 1                       | 5           | Capital Plan 2005 - 2009 | Bridges And Tunnels | Roadways & Decks     | Verazzano Bridge        | Rehabilitate Suspended Decks, Upper Level - Verrazano Narrows Bridge                                                              | 40.6057100 | -74.0485600 | base               | 
| 1473781660  | D601BB28       | 1                       | 6           | Capital Plan 2010 - 2014 | Bridges And Tunnels | Structures           | Brooklyn-Battery Tunnel | Rehabilitation of tunnel walls Roadway drainage and fire line repair at Brooklyn-Battery Tunnel                                   | 40.6806870 | -74.0058700 | base               | 
| 1473781660  | D601BW07       | 1                       | 6           | Capital Plan 2010 - 2014 | Bridges And Tunnels | Structures           | Bronx-Whitestone Bridge | Tower and Pier Fender Protection System - Bronx-Whitestone Bridge                                                                 | 40.8140530 | -73.8377490 | base               | 
| 1473781660  | D601BW14       | 1                       | 6           | Capital Plan 2010 - 2014 | Bridges And Tunnels | Structures           | Bronx-Whitestone Bridge | Miscellaneous structural rehabilitation: steel and concrete repairs - Bronx Whitestone Bridge                                     | 40.8140530 | -73.8377490 | base               | 
```