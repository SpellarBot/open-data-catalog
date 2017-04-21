# Open Budget Application - Capital Project Details

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/open-budget-application-capital-project-details) |
| Metadata | [Link](https://data.seattle.gov/api/views/tq5c-psu6) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/tq5c-psu6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/tq5c-psu6/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | tq5c-psu6 |
| Name | Open Budget Application - Capital Project Details |
| Attribution | Seattle City Budget Office |
| Category | Finance |
| Created | 2016-08-11T20:44:56Z |
| Publication Date | 2016-09-27T19:57:15Z |

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| No       | time           | :updated_at         | updated_at          | meta_data | meta_data   |
| Yes      | series tag     | project_id          | Project_id          | text      | text        |
| Yes      | series tag     | project_name        | Project_name        | text      | text        |
| Yes      | series tag     | project_description | Project_Description | text      | text        |
| No       |                | current_address     | Current Address     | text      | text        |
| Yes      | numeric metric | current_phase       | Current_Phase       | number    | number      |
| Yes      | series tag     | current_phase_type  | Current_Phase_Type  | text      | text        |
| Yes      | series tag     | project_details_url | Project_Details_URL | text      | text        |
| No       |                | latitude            | Latitude            | number    | number      |
| No       |                | longitude           | Longitude           | number    | number      |
| Yes      | numeric metric | regions             | Regions             | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = current_address,latitude,longitude
```

## Data Commands

```ls
```

## Meta Commands

```ls
metric m:current_phase p:long l:Current_Phase t:dataTypeName=number

metric m:regions p:long l:Regions t:dataTypeName=number

entity e:tq5c-psu6 l:"Open Budget Application - Capital Project Details" t:attribution="Seattle City Budget Office" t:url=https://data.seattle.gov/api/views/tq5c-psu6

property e:tq5c-psu6 t:meta.view v:id=tq5c-psu6 v:category=Finance v:averageRating=0 v:name="Open Budget Application - Capital Project Details" v:attribution="Seattle City Budget Office"

property e:tq5c-psu6 t:meta.view.owner v:id=wmx8-e5p7 v:screenName="Kirk, Daniel" v:displayName="Kirk, Daniel"

property e:tq5c-psu6 t:meta.view.tableauthor v:id=wmx8-e5p7 v:screenName="Kirk, Daniel" v:roleName=administrator v:displayName="Kirk, Daniel"
```

## Top Records

```ls
| :updated_at | project_id | project_name                                              | project_description                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       | current_address | current_phase | current_phase_type | project_details_url | latitude | longitude | regions | 
| =========== | ========== | ========================================================= | ========================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================= | =============== | ============= | ================== | =================== | ======== | ========= | ======= | 
| 1475006184  | TC320060   | Debt Service - CRF                                        | This project funds debt service for the following projects: Alaskan Way Viaduct/Tunnel & Seawall and Fremont Bridge Approaches and Electrical Major Maintenance.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | N/A             |               |                    |                     |          |           |         | 
| 1475006184  | TC365440   | Arterial Asphalt and Concrete Program                     | The Arterial Asphalt and Concrete Program maintains Seattle's 1,581 lane miles of arterial streets through resurfacing and reconstruction projects. The Department uses a pavement management system to track the condition of arterial street pavement, to develop maintenance needs and establish priorities, and to select the streets to be rehabilitated each year. This project improves the quality and condition of the City's arterials.                                                                                                                                                                                                         | Various         |               |                    |                     |          |           |         | 
| 1475006184  | TC365940   | Arterial Major Maintenance                                | This ongoing project repairs and/or replaces deteriorated pavement on arterial streets. Arterial Major Maintenance paving work typically spans one to three city blocks. It allows the City to respond quickly and cost effectively to pavement issues that are too large to be addressed with a pothole repair, yet are too small to be efficiently contracted. Project prioritization is based on pavement condition; cost; transit, bicycle, pedestrian and freight use; traffic volume; coordination opportunities; complaints and claims; and geographic balance across the city. The work extends the service life of existing pavement structures. | Citywide        |               |                    |                     |          |           |         | 
| 1475006184  | TC366760   | Bike Master Plan Implementation                           | This ongoing program implements the Seattle Bicycle Master Plan. Typical improvements may include installing bike lanes and sharrows, bicycle route signing, completing key links in the urban trails network, adding bicycle/pedestrian signals to complete the network, and reconstructing key sections of the trails. The goals of the program are to increase bicycle safety and access, while reducing bicycle crashes. This program includes funding for street improvement and trail construction and is consistent with the focus in the City's Transportation Strategic Plan (TSP) on encouraging walking and biking.                            | Citywide        |               |                    |                     |          |           |         | 
| 1475006184  | TC365060   | Bridge Load Rating                                        | This project rates bridges for safe load-carrying capacity, as part of a federally-mandated program. The work on this project, performed by both City staff and consultants, ensures public safety. Additional funding was added to this program as of the 2015-2020 Proposed CIP due to new load rating standards for specialized hauling vehicles that were issued by the Federal Highway Administration on November 13, 2013. These new standards require an additional investment of $300,000 a year for seven years (2015-2021).                                                                                                                     | Citywide        |               |                    |                     |          |           |         | 
| 1475006184  | TC324900   | Bridge Painting Program                                   | This ongoing asset preservation project provides for the periodic painting of each of the City's 20 structural steel bridges. The painting cycle is initially determined by applying Federal Highway Administration standards for coating life, and is supplemented by annual physical inspections to assess the actual rate of deterioration.                                                                                                                                                                                                                                                                                                            |                 |               |                    |                     |          |           |         | 
| 1475006184  | TC366850   | Bridge Rehabilitation and Replacement                     | This project addresses the major maintenance backlog for the City's bridge infrastructure. Rehabilitation or replacement has been completed on Airport Way over Argo, 15th Avenue NE at NE 105th Street, 15th Ave. W Interchange, East Duwamish Waterway, Jose Rizal, East Marginal Way at Horton Street, and NE 45th Street Viaduct. The Yesler Over 4th Avenue bridge maintenance will continue and the Fairview Ave N bridges are scheduled for maintenance in 2017.                                                                                                                                                                                   | Citywide        |               |                    |                     |          |           |         | 
| 1475006184  | TC365480   | Hazard Mitigation Program - Areaways                      | This ongoing program implements inspection and repair of areaways to reduce risks to City facilities and the general public. Areaways are usable space, generally in the street right-of-way, constructed under sidewalks between a building foundation and the street wall. Typical improvements may include, but are not limited to, repairs to the existing areaway and/or filling the areaway with lightweight concrete. Improving these areaways is an action included in the South Downtown Strategic Plan.                                                                                                                                         | Various         |               |                    |                     |          |           |         | 
| 1475006184  | TC365510   | Hazard Mitigation Program - Landslide Mitigation Projects | This project enables SDOT to address and repair landslide concerns that affect the right-of-way. The Landslide Mitigation Program provides SDOT with staff and resources to identify and prioritize landslide concerns, to undertake reconnaissance engineering and geotechnical studies of problem areas, and to make repairs at the highest priority locations, usually where landslide concerns have caused the roadway to be partially or completely closed.                                                                                                                                                                                          | Various         |               |                    |                     |          |           |         | 
| 1475006184  | TC320030   | Miscellaneous, Unforeseen, and Emergencies                | This program provides a financial reserve for work that cannot be anticipated during the annual CIP planning process. The reserve is used on a project-specific basis when emergencies are identified.                                                                                                                                                                                                                                                                                                                                                                                                                                                    | Various         |               |                    |                     |          |           |         | 
```