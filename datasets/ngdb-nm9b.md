# Spirit of East Austin Project Inventory

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/spirit-of-east-austin-project-inventory) |
| Metadata | [Link](https://data.austintexas.gov/api/views/ngdb-nm9b) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/ngdb-nm9b/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/ngdb-nm9b/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | ngdb-nm9b |
| Name | Spirit of East Austin Project Inventory |
| Tags | spirit of east austin, east austin |
| Created | 2016-06-24T19:33:04Z |
| Publication Date | 2016-06-24T20:00:52Z |

## Description

The Spirit of East Austin Team has identified more than 200 projects that could impact the East Austin Crescent. This list includes project titles with brief descriptions.

## Columns

```ls
| Included | Schema Type | Field Name             | Name                     | Data Type | Render Type |
| ======== | =========== | ====================== | ======================== | ========= | =========== |
| No       | time        | :updated_at            | updated_at               | meta_data | meta_data   |
| Yes      | series tag  | project_resource_title | Project / Resource title | text      | text        |
| Yes      | series tag  | description            | Description              | text      | text        |
| Yes      | series tag  | project_code           | Project Code             | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:ngdb-nm9b d:2016-06-24T12:59:05.000Z t:description="Neighborhood Housing & Community Development is exploring feasibility and possibilities for affordable housing and other uses for six (6) acres of land off of Levander Loop near Animal Services and Health & Human Services offices. The property was deeded to the Austin Housing Finance Corp. and could contribute to the Imagine Austin vision for complete communities. This is not a public project yet. Internal discussions have begun and we have engaged CPIO for a community engagement approach." t:project_resource_title="Gardner Road Exploration Project" m:row_number.ngdb-nm9b=1

series e:ngdb-nm9b d:2016-06-24T12:59:05.000Z t:description="Project is a 3 week summer camp for middle school children to teach community values and expose the children to a diversity people and places that they would otherwise not be exposed to." t:project_resource_title="Summer Camp for Disadvantaged Youth" t:project_code=DP-2 m:row_number.ngdb-nm9b=2

series e:ngdb-nm9b d:2016-06-24T12:59:05.000Z t:description="Project to educate seniors on home security and personal safety to include fraud prevention and theft of personal wealth." t:project_resource_title="Seniors and Law Enforcement Together (SALT)" t:project_code=DP-3 m:row_number.ngdb-nm9b=3
```

## Meta Commands

```ls
metric m:row_number.ngdb-nm9b p:long l:"Row Number"

entity e:ngdb-nm9b l:"Spirit of East Austin Project Inventory" t:url=https://data.austintexas.gov/api/views/ngdb-nm9b

property e:ngdb-nm9b t:meta.view v:id=ngdb-nm9b v:averageRating=0 v:name="Spirit of East Austin Project Inventory"

property e:ngdb-nm9b t:meta.view.owner v:id=czye-wfgc v:profileImageUrlMedium=/api/users/czye-wfgc/profile_images/THUMB v:profileImageUrlLarge=/api/users/czye-wfgc/profile_images/LARGE v:screenName=AustinGo v:profileImageUrlSmall=/api/users/czye-wfgc/profile_images/TINY v:displayName=AustinGo

property e:ngdb-nm9b t:meta.view.tableauthor v:id=czye-wfgc v:profileImageUrlMedium=/api/users/czye-wfgc/profile_images/THUMB v:profileImageUrlLarge=/api/users/czye-wfgc/profile_images/LARGE v:screenName=AustinGo v:profileImageUrlSmall=/api/users/czye-wfgc/profile_images/TINY v:roleName=publisher v:displayName=AustinGo
```

## Top Records

```ls
| :updated_at | project_resource_title                                | description                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | project_code | 
| =========== | ===================================================== | ============================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================== | ============ | 
| 1466773145  | Gardner Road Exploration Project                      | Neighborhood Housing & Community Development is exploring feasibility and possibilities for affordable housing and other uses for six (6) acres of land off of Levander Loop near Animal Services and Health & Human Services offices. The property was deeded to the Austin Housing Finance Corp. and could contribute to the Imagine Austin vision for complete communities. This is not a public project yet. Internal discussions have begun and we have engaged CPIO for a community engagement approach. |              | 
| 1466773145  | Summer Camp for Disadvantaged Youth                   | Project is a 3 week summer camp for middle school children to teach community values and expose the children to a diversity people and places that they would otherwise not be exposed to.                                                                                                                                                                                                                                                                                                                     | DP-2         | 
| 1466773145  | Seniors and Law Enforcement Together (SALT)           | Project to educate seniors on home security and personal safety to include fraud prevention and theft of personal wealth.                                                                                                                                                                                                                                                                                                                                                                                      | DP-3         | 
| 1466773145  | National Night Out                                    | Citizens participate one evening during the year with hosting and participating in a block party with their neighbors to help prevent crime by getting to know their neighbors. In Austin the date is the first Tuesday in October with the Kickoff Party on the Saturday before the first Tuesday.                                                                                                                                                                                                            | DP-4         | 
| 1466773145  | Austin Police Operation Blue Santa                    | Take in toy and cash donations to 501c3 Austin Police Operation Blue Santa and deliver back to primarily the east Austin community toys for children 14 years of age and younger and a Christmas dinner that includes all non-perishable sides and a frozen turkey for each family.                                                                                                                                                                                                                            | DP-5         | 
| 1466773145  | Police Activities League of Austin / Police Explorers | Juvenile delinquency prevention programs                                                                                                                                                                                                                                                                                                                                                                                                                                                                       | DP-8         | 
| 1466773145  | Austin Fire Department Smoke Alarm Canvass            | During the past 20 years the Austin Fire Department has instituted a program that targets areas of the city that lack modern and working smoke alarms.                                                                                                                                                                                                                                                                                                                                                         |              | 
| 1466773145  | Drug Market Intervention initiative (DMI)             | The Drug Market Intervention (DMI) initiative is a strategic, focused, data-driven, problem-solving program aimed at permanently closing down open-air drug markets. The goal of the DMI is to shut down open-air drug markets in targeted neighborhoods, while also reducing the violence associated with these drug markets. The 12th St/Chicon St area was the focus area for this project.                                                                                                                 | PD-6         | 
| 1466773145  | Mother-Friendly Worksite Policy                       | Work with organizations to increase mother-friendly policies                                                                                                                                                                                                                                                                                                                                                                                                                                                   | HHS-22       | 
| 1466773145  | Healthy Food Retail                                   | Project to increase the varieties of healthy products offered in neighborhood food retail stores, train residents in the Healthy Corner Store Model, and develop the leadership capacity of residents to implement healthy corner store model with food retail store owners.                                                                                                                                                                                                                                   | HHS-23       | 
```