# Residential Projects With Inclusionary Requirements

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/residential-projects-with-inclusionary-requirements-as-of-2015-q3) |
| Metadata | [Link](https://data.sfgov.org/api/views/nj3x-rw36) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/nj3x-rw36/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/nj3x-rw36/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | nj3x-rw36 |
| Name | Residential Projects With Inclusionary Requirements |
| Attribution | Mayor's Office of Housing and Community Development |
| Category | Housing and Buildings |
| Tags | inclusionary housing, section 415, planning, affordable housing, bmr |
| Created | 2015-11-30T23:54:38Z |
| Publication Date | 2016-07-13T22:22:04Z |

## Description

Subject to Planning Code Section 415 (http://bit.ly/1ag0AmP), developments of 10 or more units fall under the City's Inclusionary Affordable Housing Program. Data on residential projects are collected through the lifecycle of the projects by the Planning Department and the Department of Building Inspection. On a quarterly basis, the Mayor's Office of Housing and Community Development works with Planning to produce a list for tracking and monitoring of these projects.

## Columns

```ls
| Included | Schema Type    | Field Name                           | Name                                 | Data Type     | Render Type   |
| ======== | ============== | ==================================== | ==================================== | ============= | ============= |
| No       |                | id                                   | ID                                   | text          | number        |
| Yes      | series tag     | project_status                       | Project Status                       | text          | text          |
| Yes      | series tag     | building_name                        | Building Name                        | text          | text          |
| Yes      | series tag     | planning_approval_street_number      | Planning Approval Street Number      | text          | text          |
| Yes      | series tag     | planning_approval_street_name        | Planning Approval Street Name        | text          | text          |
| No       |                | mapping_address                      | Mapping Address                      | text          | text          |
| Yes      | series tag     | section_415_declaration_of_intent    | Section 415 Declaration of Intent    | text          | text          |
| Yes      | series tag     | tenure                               | Tenure                               | text          | text          |
| Yes      | numeric metric | total_units_in_building_or_phase     | Total Units in Building or Phase     | number        | number        |
| Yes      | numeric metric | total_units_subject_to_section_415   | Total Units Subject to Section 415   | number        | number        |
| Yes      | numeric metric | total_bmrs_in_this_building_or_phase | Total BMRs in this Building or Phase | number        | number        |
| Yes      | numeric metric | total_bmrs_on_site                   | Total BMRs On-Site                   | number        | number        |
| Yes      | numeric metric | total_bmrs_off_site                  | Total BMRs Off-Site                  | number        | number        |
| Yes      | numeric metric | off_site_units_at_this_site          | Off-Site Units at this Site          | number        | number        |
| No       |                | principal_project_address            | Principal Project Address            | text          | text          |
| No       |                | off_site_address                     | Off-Site Address                     | text          | text          |
| Yes      | time           | planning_approval_date               | Planning Approval Date               | calendar_date | calendar_date |
| No       |                | completion_date                      | Completion Date                      | calendar_date | calendar_date |
| Yes      | series tag     | neighborhood                         | Neighborhood                         | text          | text          |
| Yes      | series tag     | planning_neighborhood                | Planning Neighborhood                | text          | text          |
| Yes      | series tag     | supervisor_district                  | Supervisor District                  | text          | text          |
| Yes      | series tag     | plan_area                            | Plan Area                            | text          | text          |
```

## Time Field

```ls
Value = planning_approval_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = id,mapping_address,principal_project_address,off_site_address,completion_date
```

## Data Commands

```ls
series e:nj3x-rw36 d:2007-04-19T00:00:00.000Z t:building_name="555 Bartlett" t:project_status=Completed t:planning_approval_street_name="Cesar Chavez Street" t:tenure=Ownership t:neighborhood=Mission t:section_415_declaration_of_intent="On-site BMR Project" t:planning_approval_street_number=3400 t:plan_area="Mission (Eastern Neighborhoods)" t:supervisor_district=9 t:planning_neighborhood=Mission m:total_bmrs_on_site=9 m:total_bmrs_off_site=0 m:total_units_in_building_or_phase=58 m:total_bmrs_in_this_building_or_phase=9 m:total_units_subject_to_section_415=58 m:off_site_units_at_this_site=0

series e:nj3x-rw36 d:2011-06-06T00:00:00.000Z t:building_name="1945 Hyde Street" t:project_status=Completed t:planning_approval_street_name="Hyde Street" t:tenure=Unknown t:neighborhood="Russian Hill" t:section_415_declaration_of_intent="Fee Payment" t:planning_approval_street_number=1945 t:supervisor_district=3 t:planning_neighborhood="Russian Hill" m:total_bmrs_on_site=0 m:total_bmrs_off_site=0 m:total_units_in_building_or_phase=7 m:total_bmrs_in_this_building_or_phase=0 m:total_units_subject_to_section_415=7 m:off_site_units_at_this_site=0

series e:nj3x-rw36 d:2011-01-01T00:00:00.000Z t:building_name="537 Natoma Street" t:project_status=Completed t:planning_approval_street_name="Natoma Street" t:tenure=Ownership t:neighborhood="South of Market" t:section_415_declaration_of_intent="On-site BMR Project" t:planning_approval_street_number=537 t:plan_area="East SoMa (Eastern Neighborhoods)" t:supervisor_district=6 t:planning_neighborhood="South of Market" m:total_bmrs_on_site=1 m:total_bmrs_off_site=0 m:total_units_in_building_or_phase=13 m:total_bmrs_in_this_building_or_phase=1 m:total_units_subject_to_section_415=13 m:off_site_units_at_this_site=0
```

## Meta Commands

```ls
metric m:total_units_in_building_or_phase p:integer l:"Total Units in Building or Phase" t:dataTypeName=number

metric m:total_units_subject_to_section_415 p:integer l:"Total Units Subject to Section 415" t:dataTypeName=number

metric m:total_bmrs_in_this_building_or_phase p:integer l:"Total BMRs in this Building or Phase" t:dataTypeName=number

metric m:total_bmrs_on_site p:integer l:"Total BMRs On-Site" t:dataTypeName=number

metric m:total_bmrs_off_site p:integer l:"Total BMRs Off-Site" t:dataTypeName=number

metric m:off_site_units_at_this_site p:integer l:"Off-Site Units at this Site" t:dataTypeName=number

entity e:nj3x-rw36 l:"Residential Projects With Inclusionary Requirements" t:attribution="Mayor's Office of Housing and Community Development" t:url=https://data.sfgov.org/api/views/nj3x-rw36

property e:nj3x-rw36 t:meta.view v:id=nj3x-rw36 v:category="Housing and Buildings" v:attributionLink=http://sf-moh.org/ v:averageRating=0 v:name="Residential Projects With Inclusionary Requirements" v:attribution="Mayor's Office of Housing and Community Development"

property e:nj3x-rw36 t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:nj3x-rw36 t:meta.view.owner v:id=9wvp-x5mw v:screenName="Charlie MacNulty" v:displayName="Charlie MacNulty"

property e:nj3x-rw36 t:meta.view.tableauthor v:id=9wvp-x5mw v:screenName="Charlie MacNulty" v:roleName=editor v:displayName="Charlie MacNulty"
```

## Top Records

```ls
| id  | project_status                     | building_name           | planning_approval_street_number | planning_approval_street_name                       | mapping_address                                | section_415_declaration_of_intent | tenure    | total_units_in_building_or_phase | total_units_subject_to_section_415 | total_bmrs_in_this_building_or_phase | total_bmrs_on_site | total_bmrs_off_site | off_site_units_at_this_site | principal_project_address             | off_site_address                                                              | planning_approval_date | completion_date     | neighborhood       | planning_neighborhood | supervisor_district | plan_area                         | 
| === | ================================== | ======================= | =============================== | =================================================== | ============================================== | ================================= | ========= | ================================ | ================================== | ==================================== | ================== | =================== | =========================== | ===================================== | ============================================================================= | ====================== | =================== | ================== | ===================== | =================== | ================================= | 
| 188 | Completed                          | 555 Bartlett            | 3400                            | Cesar Chavez Street                                 | 3400 Cesar Chavez St, San Francisco, CA, 94110 | On-site BMR Project               | Ownership | 58                               | 58                                 | 9                                    | 9                  | 0                   | 0                           |                                       |                                                                               | 2007-04-19T00:00:00    | 2010-04-19T00:00:00 | Mission            | Mission               | 9                   | Mission (Eastern Neighborhoods)   | 
| 256 | Completed                          | 1945 Hyde Street        | 1945                            | Hyde Street                                         | 1945 Hyde St, San Francisco, CA, 94109         | Fee Payment                       | Unknown   | 7                                | 7                                  | 0                                    | 0                  | 0                   | 0                           |                                       |                                                                               | 2011-06-06T00:00:00    | 2014-01-01T00:00:00 | Russian Hill       | Russian Hill          | 3                   |                                   | 
| 246 | Completed                          | 537 Natoma Street       | 537                             | Natoma Street                                       | 537 Natoma St, San Francisco, CA, 94103        | On-site BMR Project               | Ownership | 13                               | 13                                 | 1                                    | 1                  | 0                   | 0                           |                                       |                                                                               | 2011-01-01T00:00:00    | 2013-04-12T00:00:00 | South of Market    | South of Market       | 6                   | East SoMa (Eastern Neighborhoods) | 
| 185 | Completed                          | 231 Franklin Street     | 231                             | Franklin Street                                     | 231 Franklin St, San Francisco, CA, 94102      | Fee Payment                       | Unknown   | 32                               | 32                                 | 0                                    | 0                  | 0                   | 0                           |                                       |                                                                               | 2007-04-05T00:00:00    | 2010-07-02T00:00:00 | Hayes Valley       | Downtown/Civic Center | 5                   | Market and Octavia                | 
| 15  | Completed                          | 1099 Mississippi Street | 1099                            | Mississippi Street                                  | 1099 Mississippi St, San Francisco, CA, 94107  | On-site BMR Project               | Ownership | 10                               | 10                                 | 1                                    | 1                  | 0                   | 0                           |                                       |                                                                               | 1995-04-27T00:00:00    | 2004-01-01T00:00:00 | Potrero Hill       | Potrero Hill          | 10                  | Bayview Hunters Point             | 
| 152 | Completed                          | One Rincon, Phase I     | 1                               | Rincon Hill (aka 425 First Street - Tower One Only) | 425 1st St, San Francisco, CA, 94105           | Fee Payment                       | Ownership | 382                              | 382                                | 0                                    | 0                  | 0                   | 0                           |                                       |                                                                               | 2005-08-04T00:00:00    | 2008-01-04T00:00:00 | Financial District | South of Market       | 6                   | Rincon Hill                       | 
| 223 | First Construction Document Issued | 2655 Bush Street        | 2655                            | Bush Street                                         | 2655 Bush St, San Francisco, CA, 94115         | Fee Payment                       | Unknown   | 81                               | 81                                 | 0                                    | 0                  | 0                   | 0                           |                                       |                                                                               | 2009-07-16T00:00:00    |                     | Pacific Heights    | Western Addition      | 2                   |                                   | 
| 13  | Completed                          | Embarcadero Lofts       | 300                             | Beale Street                                        | 300 Beale St, San Francisco, CA, 94105         | On-site BMR Project               | Ownership | 67                               | 67                                 | 6                                    | 6                  | 0                   | 0                           |                                       |                                                                               | 1995-04-06T00:00:00    | 1998-01-01T00:00:00 | Financial District | South of Market       | 6                   | Rincon Hill                       | 
| 143 | Completed                          | Summit 800              | 800                             | Brotherhood Way                                     | 800 Brotherhood Way, San Francisco, CA, 94132  | Off-site BMR Project              | Ownership | 182                              | 182                                | 0                                    | 0                  | 36                  | 0                           |                                       | 833 Jamestown (19 of 196 rental units) & 1 Capitol (17 of 28 ownership units) | 2005-05-19T00:00:00    | 2015-01-01T00:00:00 | Lakeshore          | Lakeshore             | 7                   |                                   | 
| 178 | Completed                          | 125 Mason               | 125                             | Mason Street                                        | 125 Mason St, San Francisco, CA, 94102         | Units for Off-site Project        | Rental    | 81                               | 0                                  | 81                                   | 0                  | 0                   | 81                          | 301 Mission Street (Millennium Tower) |                                                                               | 2006-08-10T00:00:00    | 2008-08-26T00:00:00 | Tenderloin         | Downtown/Civic Center | 6                   | Downtown                          | 
```