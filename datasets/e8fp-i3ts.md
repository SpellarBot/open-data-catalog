# CIVIC Projects List

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/civic-projects-list) |
| Metadata | [Link](https://data.austintexas.gov/api/views/e8fp-i3ts) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/e8fp-i3ts/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/e8fp-i3ts/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | e8fp-i3ts |
| Name | CIVIC Projects List |
| Attribution | City of Austin |
| Category | Capital Planning |
| Tags | civic, projects, go, general obligation, capital, improvement, visualization, information, communication, planning |
| Created | 2013-10-17T15:25:11Z |
| Publication Date | 2017-01-11T09:30:33Z |

## Description

This dataset includes information for projects that appear on the City of Austin?s Capital Improvement Visualization Information and Communication (CIVIC) Map Viewer, www.austintexas.gov/GIS/CIVIC/.  These projects, also known as Capital Improvements Program (CIP) projects, implement the construction, replacement, or renovation of city assets that are useful to the community. Data is currently available for most CIP projects funded in full or in part by voter-approved bond programs from 2013, 2012, 2010, 2006, 2000, and 1998.   The dataset below is subject to change at any time, and does not represent a comprehensive list of capital improvement projects. For more information about the City of Austin?s Capital Improvement Program, please visit www.austintexas.gov/department/civic. The City of Austin has produced CIVIC, a web application to search Capital Improvement Projects, for informational purposes only. The data and information available at this web site is provided "As is", and "As Available" and without any warranties of any kind either express or implied. The City makes no warranty regarding the accuracy or completeness of this site and the information provided. By accessing or using CIVIC, you agree to these terms of use. The City of Austin may change the terms of use at any time at its sole discretion and without notice.?

## Columns

```ls
| Included | Schema Type | Field Name               | Name               | Data Type | Render Type |
| ======== | =========== | ======================== | ================== | ========= | =========== |
| No       | time        | :updated_at              | updated_at         | meta_data | meta_data   |
| Yes      | series tag  | subproject_id            | Project ID         | text      | text        |
| Yes      | series tag  | subproject_name          | Name               | text      | text        |
| Yes      | series tag  | status_code              | Status             | text      | text        |
| Yes      | series tag  | subproject_type_category | Category           | text      | text        |
| Yes      | series tag  | sponsor_department       | Sponsor Department | text      | text        |
| Yes      | series tag  | subproject_description   | Description        | text      | text        |
| Yes      | series tag  | subproject_manager       | Project Manager    | text      | text        |
| Yes      | series tag  | manager_phone            | Phone Number       | phone     | phone       |
| Yes      | series tag  | manager_email            | Email              | email     | email       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:e8fp-i3ts d:2017-01-11T09:30:22.000Z t:subproject_description="Fund 8181 High Level - Parent FDUs to be allocated to Corridor Improvements." t:status_code=Active t:subproject_name="Fund 8181 High Level - Parent FDUs" t:phone_number="(512) 974-1150" t:sponsor_department="Austin Transportation" t:subproject_id=11280.002 t:subproject_type_category=Other t:subproject_manager="Segura, Anthony" t:manager_email=Anthony.Segura@austintexas.gov m:row_number.e8fp-i3ts=1

series e:e8fp-i3ts d:2017-01-11T09:30:22.000Z t:subproject_description="Upgrade and expand the City's traffic signal system including the central software, fiber optic communications network, CCTV system, and install traffic count and travel time sensors." t:status_code=Active t:subproject_name="Citywide, Intelligent Transportation System Expansion" t:phone_number="(512) 974-4061" t:sponsor_department="Austin Transportation" t:subproject_id=5828.013 t:subproject_type_category="Mobility Infrastructure" t:subproject_manager="Craig, Brian" t:manager_email=Brian.Craig@austintexas.gov m:row_number.e8fp-i3ts=2

series e:e8fp-i3ts d:2017-01-11T09:30:22.000Z t:subproject_description="Conduct preliminary engineering to widen, reconstruct, and add bicycle lanes on Manchaca Road between William Cannon Drive and South Lamar Boulevard." t:status_code=Active t:subproject_name="Manchaca Rd from William Cannon Dr to S Lamar Blvd" t:phone_number="(512) 974-7016" t:sponsor_department="Austin Transportation" t:subproject_id=5771.068 t:subproject_type_category="Mobility Infrastructure" t:subproject_manager="Wilkes, Nathan" t:manager_email=Nathan.Wilkes@austintexas.gov m:row_number.e8fp-i3ts=3
```

## Meta Commands

```ls
metric m:row_number.e8fp-i3ts p:long l:"Row Number"

entity e:e8fp-i3ts l:"CIVIC Projects List" t:attribution="City of Austin" t:url=https://data.austintexas.gov/api/views/e8fp-i3ts

property e:e8fp-i3ts t:meta.view v:id=e8fp-i3ts v:category="Capital Planning" v:attributionLink=http://www.austintexas.gov v:averageRating=0 v:name="CIVIC Projects List" v:attribution="City of Austin"

property e:e8fp-i3ts t:meta.view.owner v:id=k6xj-wrjq v:screenName="Ashley Parsons" v:displayName="Ashley Parsons"

property e:e8fp-i3ts t:meta.view.tableauthor v:id=k6xj-wrjq v:screenName="Ashley Parsons" v:roleName=editor v:displayName="Ashley Parsons"
```

## Top Records

```ls
| :updated_at | subproject_id | subproject_name                                                         | status_code | subproject_type_category | sponsor_department                           | subproject_description                                                                                                                                                                                                                 | subproject_manager        | manager_phone          | manager_email                  | 
| =========== | ============= | ======================================================================= | =========== | ======================== | ============================================ | ====================================================================================================================================================================================================================================== | ========================= | ====================== | ============================== | 
| 1484127022  | 11280.002     | Fund 8181 High Level - Parent FDUs                                      | Active      | Other                    | Austin Transportation                        | Fund 8181 High Level - Parent FDUs to be allocated to Corridor Improvements.                                                                                                                                                           | Segura, Anthony           | [(512) 974-1150, null] | Anthony.Segura@austintexas.gov | 
| 1484127022  | 5828.013      | Citywide, Intelligent Transportation System Expansion                   | Active      | Mobility Infrastructure  | Austin Transportation                        | Upgrade and expand the City's traffic signal system including the central software, fiber optic communications network, CCTV system, and install traffic count and travel time sensors.                                                | Craig, Brian              | [(512) 974-4061, null] | Brian.Craig@austintexas.gov    | 
| 1484127022  | 5771.068      | Manchaca Rd from William Cannon Dr to S Lamar Blvd                      | Active      | Mobility Infrastructure  | Austin Transportation                        | Conduct preliminary engineering to widen, reconstruct, and add bicycle lanes on Manchaca Road between William Cannon Drive and South Lamar Boulevard.                                                                                  | Wilkes, Nathan            | [(512) 974-7016, null] | Nathan.Wilkes@austintexas.gov  | 
| 1484127022  | 7067.006      | 2000 & Older Bond Parent FDUs                                           | Active      | Mobility Infrastructure  | Public Works                                 | Subproject houses Bond Parent and Sub-Parent FDUs. No Expenses or actual capital projects are occuring within the subproject. Only expenses, if any, to occur will be Bond Cost Of Issuance (COI) within Parent FDUs                   | Stipan, Ryan              | [(512) 974-1482, null] | Ryan.Stipan@austintexas.gov    | 
| 1484127022  | 6055.024      | Second Street District Streetscape Street Recon. & Utility Adj. Phase 3 | Completed   | Mobility Infrastructure  | Planning and Zoning                          | Street reconstruction, streetscape, utility, & pedestrian improvements from Congress to Trinity. Improvements including new wide sidewalks, street trees, street lights, bike racks, benches, and landscaping.                         | Harvey, Randy             | [(512) 974-1585, null] | Randy.Harvey@austintexas.gov   | 
| 1484127022  | 6055.015      | Second Street Phase 2, Colorado to Congress                             | Completed   | Mobility Infrastructure  | Planning and Zoning                          | Street reconstruction, streetscape, utility, and pedestrian improvements from Colorado to Congress. Improvements including new wide sidewalks, street trees, street lights, bike racks, benches, and landscaping.                      | Harvey, Randy             | [(512) 974-1585, null] | Randy.Harvey@austintexas.gov   | 
| 1484127022  | 5769.096      | Citywide Sidewalk Asset Management                                      | Completed   | Mobility Infrastructure  | Public Works                                 | This project will develop improved asset management requirements related to the Sidewalk Improvement Program and ADA Sidewalk Transition Plan, and include updates to the absent sidewalk prioritization map.                          | Eastman, John             | [(512) 974-7025, null] | John.Eastman@austintexas.gov   | 
| 1484127022  | 10553.025     | EM Franklin Green Street Project                                        | Active      | Mobility Infrastructure  | Public Works                                 | In partnership with the JJ Seabrook Neighborhood Association, the project is to turn a 44 foot wide street into a green street that incorporates traffic calming, rain gardens, street trees, street art, bicycle lanes and sidewalks. | Ryan, Janae               | [(512) 974-3159, null] | Janae.Ryan@austintexas.gov     | 
| 1484127022  | 5401.004      | E. 51st Street Improvements                                             | Active      | Mobility Infrastructure  | Austin Transportation                        | This project provides improvements on East 51st Street adjacent to the Mueller Development from IH-35 to Berkman Drive, including Complete Street improvements to enhance mobility and safety in the corridor.                         | Jones, Burton             | [(512) 974-7278, null] | Burton.Jones@austintexas.gov   | 
| 1484127022  | 10573.01      | GO Repair Habitat for Humanity - 2013 Bonds                             | Active      | Housing                  | Neighborhood Housing & Community Development | Provides financial assistance to Habitat for Humanity to make repairs that will eliminate health and safety hazards and / or provide improved accessibility.                                                                           | Hernandez-Garza, Fernando | [(512) 974-3114, null] |                                | 
```