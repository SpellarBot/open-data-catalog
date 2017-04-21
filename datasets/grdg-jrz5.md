# Main Street Investment Fund Applicants

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/main-street-investment-fund-applicants) |
| Metadata | [Link](https://data.ct.gov/api/views/grdg-jrz5) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/grdg-jrz5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/grdg-jrz5/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | grdg-jrz5 |
| Name | Main Street Investment Fund Applicants |
| Category | Housing and Development |
| Tags | main street, investment, msif |
| Created | 2014-05-21T19:12:28Z |
| Publication Date | 2014-05-21T19:16:09Z |

## Description

These are the municipalities that received state funds under the Main Street Investment Fund program (CGS Section 4-66h)

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| No       | time           | :updated_at         | updated_at          | meta_data | meta_data   |
| Yes      | series tag     | town                | Town                | text      | text        |
| Yes      | series tag     | project_description | Project Description | text      | text        |
| Yes      | numeric metric | state_assistance    | State assistance    | money     | money       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:grdg-jrz5 d:2014-05-21T12:12:31.000Z t:town=Ansonia t:project_description="The proposed West Main Street Streetscape project area is between Kingston Drive and Bridge Street.  Activities include new granite curb, brick paver strips, concrete walkway, grass planting strip ornamental rail fencing, street trees, and other street furniture, benches, trash receptacles, new ornamental lights on the west side, resurfacing and new parking layout to accommodate the new access drive and designation of new farmer market area.  The parking lot will provide access points to the retail, office and government services as well as to the multi-modal transportation waiting area in the northerly end of the parking complex.  Reduction is for traffic control time during construction." m:state_assistance=483000

series e:grdg-jrz5 d:2014-05-21T12:12:31.000Z t:town=Berlin t:project_description="The Berlin Main Street Streetscape project will improve the aesthetics and pedestrian friendliness of Main Street and Farmington Avenue in the immediate vicinity of the Berlin Train Station.  The proposed project is part of the Town's comprehensive effort to revitalize its downtown (Farmington Ave/Main Street) commercial area.  The project will include decorative cross walks and roadway median, decorative lights andpoles to match the Train Station renovation project, bump outs and plantings for traffic calming and aesthetics and site furnishings such as benches, trash receptcles and bike racks." m:state_assistance=259270

series e:grdg-jrz5 d:2014-05-21T12:12:31.000Z t:town=Burlington t:project_description="The proposed project funds will be used for pedestrian improvements along approximately 650 lf in the Burlington Town Center.  More specifically, these funds will be used to construct sidewalks and make other pedestrian and streetscaping improvements including lighting, landscaping, lighting which are critical components of the previously adopted Burlington Town Center.  Reduction is for traffic control time during construction & incidentals." m:state_assistance=377000
```

## Meta Commands

```ls
metric m:state_assistance p:integer l:"State assistance" t:dataTypeName=money

entity e:grdg-jrz5 l:"Main Street Investment Fund Applicants" t:url=https://data.ct.gov/api/views/grdg-jrz5

property e:grdg-jrz5 t:meta.view v:id=grdg-jrz5 v:category="Housing and Development" v:averageRating=0 v:name="Main Street Investment Fund Applicants"

property e:grdg-jrz5 t:meta.view.owner v:id=bdhz-s7cj v:screenName="Dimple Desai" v:displayName="Dimple Desai"

property e:grdg-jrz5 t:meta.view.tableauthor v:id=bdhz-s7cj v:screenName="Dimple Desai" v:roleName=editor v:displayName="Dimple Desai"
```

## Top Records

```ls
| :updated_at | town       | project_description                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | state_assistance | 
| =========== | ========== | ================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================== | ================ | 
| 1400674351  | Ansonia    | The proposed West Main Street Streetscape project area is between Kingston Drive and Bridge Street. Activities include new granite curb, brick paver strips, concrete walkway, grass planting strip ornamental rail fencing, street trees, and other street furniture, benches, trash receptacles, new ornamental lights on the west side, resurfacing and new parking layout to accommodate the new access drive and designation of new farmer market area. The parking lot will provide access points to the retail, office and government services as well as to the multi-modal transportation waiting area in the northerly end of the parking complex. Reduction is for traffic control time during construction.            | 483000           | 
| 1400674351  | Berlin     | The Berlin Main Street Streetscape project will improve the aesthetics and pedestrian friendliness of Main Street and Farmington Avenue in the immediate vicinity of the Berlin Train Station. The proposed project is part of the Town's comprehensive effort to revitalize its downtown (Farmington Ave/Main Street) commercial area. The project will include decorative cross walks and roadway median, decorative lights andpoles to match the Train Station renovation project, bump outs and plantings for traffic calming and aesthetics and site furnishings such as benches, trash receptcles and bike racks.                                                                                                            | 259270           | 
| 1400674351  | Burlington | The proposed project funds will be used for pedestrian improvements along approximately 650 lf in the Burlington Town Center. More specifically, these funds will be used to construct sidewalks and make other pedestrian and streetscaping improvements including lighting, landscaping, lighting which are critical components of the previously adopted Burlington Town Center. Reduction is for traffic control time during construction & incidentals.                                                                                                                                                                                                                                                                       | 377000           | 
| 1400674351  | Canaan     | The proposed project funds will be used to construct an attractive, ADA compliant, historically appropriate bluestone sidewalk running from one end of the Main Street to the elementary school at the other end of the Main Street. Funds will also be used to install curbing and bump-outs with landscaping and street trees to help slow traffic, better define parking areas, and make Main St more attractive. Funds will also be used for landscaping and the purchase and planting of trees in the town's main green space, its historic Green. Reduction is for traffic control time during construction and gazebo.                                                                                                      | 450000           | 
| 1400674351  | Canton     | The project proposes the construction of historically appropriate improvements that will provide safe pedestrian access, organized parking, and most importantly create critical linkages between areas with significant activity to areas of businesses. This project will help businesses from current activities due to the location of the State Route, the Farmington River, and the construction of the very successful and well used Farmington River Rail Trail, among other scenic and histroci destinations. Funds will be used to fund Area 1 and 3 as proposed for sidewalk improvements, wayfinding signs, trees, pedestrian lights, crosswalks, etc. Reduction is because funding only two phases rather than three. | 387000           | 
| 1400674351  | Colchester | The Linwood Avenue Streetscape Improvement project is comprised of three major elements: a concrete sidewalk and stamped concrete pathway along the sourthern side of Linwood Ave from the intersection of Linwood Avenue (rt 16) and Rt 85 west from the First Federated Church to the Stop and Shop entrance; solar lighting and other street furniture, landscaping, and a wider stamped concrete section along the frontage of the Cragan Library on the northern side of Linwood Ave. The proposed project would be 6th project completed in the downtown vilage area over the last decade which is built on the concepts and themes created previously. Reduction is for "other" item - no explanation provided.             | 285000           | 
| 1400674351  | Cornwall   | The town proposed 3 components to be funded: burying power and phone lines near the Covered Bridge in West Cornwall; installing 240 feet of sidewalk on the south side of Route 128 in West Cornwall and installation of 250 feet of sidewalk in Cornwall Bridge. Later two components are recommended for funding which will improve pedestrian access and safety in the busy scenic village center. The installation of a sidewalk between the approved senior housing and Cornwall General Store in Cornwall Bridge will provide access for seniors to village center and also provide handicapped access to the adjacent visitor's center. Reduction is because cost of burying power lines is not deemed eligible.            | 70000            | 
| 1400674351  | Essex      | The proposed project activities provides for calming of traffic, creation of an iconic, shared "Village Center" intersection at Main St and Summit St and thus providing a unified "place" to visitors and residents. Project funds will be used for creation of a "shared street" thru the addition of stamped and colored concrete from Summit St at Fire Station to Main St intersection and the along Main St to Ivoryton Library; installing new cross walks, renovation of existing crosswalks, installation of at-grade "Village Seal" in stamped concrete at center of Main St/Summit St intersection.                                                                                                                     | 435000           | 
| 1400674351  | Fairfield  | The project entails the installation of new or replacement concrete walks, curbing, pedestrian ramps, driveway aprons, decorative brick pavers, ornamental street lights, pedestrian benches, bicycle racks and other street furniture. The goal is to create a pedestrian oriented environment that is safe and harmonious with the existing streetscape character found in the downtown core. The proposed project strengthens the connections between commercial and residential neighborhoods and create pedestrian linkage to the train station. Reduction is because the project is recommended to be funded at 50% as it can be phased out.                                                                                 | 250000           | 
| 1400674351  | Griswold   | The town proposed 2 components to be funded: Sidewalk lighting and front yard streetscape improvements at the Town Hall. It is recommended to fund the sidewalk lighting project which will fund the cost of poles, light fixtures, and resurfacing the sidewalk along the electrical path. Total of 44 poles/lights will be installed. Reduction is because the Town Hall improvement project does not have all the funds in place yet.                                                                                                                                                                                                                                                                                           | 265000           | 
```