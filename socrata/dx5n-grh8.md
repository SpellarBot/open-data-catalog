# Santa Rosa Capital Projects List

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/santa-rosa-capital-projects-list) |
| Metadata | [Link](https://data.srcity.org/api/views/dx5n-grh8) |
| Data: JSON | [100 Rows](https://data.srcity.org/api/views/dx5n-grh8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.srcity.org/api/views/dx5n-grh8/rows.csv?max_rows=100) |
| Host | data.srcity.org |
| Id | dx5n-grh8 |
| Name | Santa Rosa Capital Projects List |
| Created | 2015-11-05T22:34:40Z |
| Publication Date | 2016-12-14T17:00:52Z |

## Columns

```ls
| Included | Schema Type | Field Name          | Name                | Data Type | Render Type |
| ======== | =========== | =================== | =================== | ========= | =========== |
| No       | time        | :updated_at         | updated_at          | meta_data | meta_data   |
| Yes      | series tag  | project_id          | Project ID          | text      | text        |
| Yes      | series tag  | project_name        | Project Name        | text      | text        |
| Yes      | series tag  | project_description | Project Description | text      | text        |
| No       |             | address             | Address             | text      | text        |
| Yes      | series tag  | current_phase       | Current Phase       | text      | text        |
| Yes      | series tag  | current_phase_type  | Current Phase Type  | text      | text        |
| Yes      | series tag  | project_details_url | Project Details URL | text      | text        |
| No       |             | latitude            | Latitude            | number    | number      |
| No       |             | longitude           | Longitude           | number    | number      |
| Yes      | series tag  | regions             | Regions             | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address,latitude,longitude
```

## Data Commands

```ls
series e:dx5n-grh8 d:2016-07-01T16:11:49.000Z t:project_details_url=http://srcity.org/DEPARTMENTS/PUBLICWORKS/CAPITALIMPROVEMENTPROGRAM/Pages/default.aspx t:project_name="Doyle Park Renovation" t:project_id=9532 t:current_phase_type=N/A t:current_phase=N/A t:project_description="Doyle Park Renovation" m:row_number.dx5n-grh8=1

series e:dx5n-grh8 d:2016-07-01T16:11:49.000Z t:project_details_url=http://srcity.org/DEPARTMENTS/PUBLICWORKS/CAPITALIMPROVEMENTPROGRAM/Pages/default.aspx t:project_name="Howarth Park Rehabilitation" t:project_id=9568 t:current_phase_type=N/A t:current_phase=N/A t:project_description="Howarth Park Rehabilitation" m:row_number.dx5n-grh8=2

series e:dx5n-grh8 d:2016-07-01T16:11:49.000Z t:project_details_url=http://srcity.org/DEPARTMENTS/PUBLICWORKS/CAPITALIMPROVEMENTPROGRAM/Pages/default.aspx t:project_name="Juilliard Park Rehabilitation" t:project_id=9581 t:current_phase_type=N/A t:current_phase=N/A t:project_description="Juilliard Park Rehabilitation" m:row_number.dx5n-grh8=3
```

## Meta Commands

```ls
metric m:row_number.dx5n-grh8 p:long l:"Row Number"

entity e:dx5n-grh8 l:"Santa Rosa Capital Projects List" t:url=https://data.srcity.org/api/views/dx5n-grh8

property e:dx5n-grh8 t:meta.view v:id=dx5n-grh8 v:averageRating=0 v:name="Santa Rosa Capital Projects List"

property e:dx5n-grh8 t:meta.view.owner v:id=4jau-mr7g v:profileImageUrlMedium=/api/users/4jau-mr7g/profile_images/THUMB v:profileImageUrlLarge=/api/users/4jau-mr7g/profile_images/LARGE v:screenName="Tickner, Brian" v:profileImageUrlSmall=/api/users/4jau-mr7g/profile_images/TINY v:lastNotificationSeenAt=1492537611 v:displayName="Tickner, Brian"

property e:dx5n-grh8 t:meta.view.tableauthor v:id=4jau-mr7g v:profileImageUrlMedium=/api/users/4jau-mr7g/profile_images/THUMB v:profileImageUrlLarge=/api/users/4jau-mr7g/profile_images/LARGE v:screenName="Tickner, Brian" v:profileImageUrlSmall=/api/users/4jau-mr7g/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1492537611 v:displayName="Tickner, Brian"
```

## Top Records

```ls
| :updated_at | project_id | project_name                                             | project_description                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | address                                       | current_phase | current_phase_type | project_details_url                                                                    | latitude  | longitude   | regions | 
| =========== | ========== | ======================================================== | ============================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================ | ============================================= | ============= | ================== | ====================================================================================== | ========= | =========== | ======= | 
| 1467389509  | 9532       | Doyle Park Renovation                                    | Doyle Park Renovation                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | See Project Name / Description, if applicable | N/A           | N/A                | http://srcity.org/DEPARTMENTS/PUBLICWORKS/CAPITALIMPROVEMENTPROGRAM/Pages/default.aspx | 38.437861 | -122.712322 |         | 
| 1467389509  | 9568       | Howarth Park Rehabilitation                              | Howarth Park Rehabilitation                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | See Project Name / Description, if applicable | N/A           | N/A                | http://srcity.org/DEPARTMENTS/PUBLICWORKS/CAPITALIMPROVEMENTPROGRAM/Pages/default.aspx | 38.437861 | -122.712322 |         | 
| 1467389509  | 9581       | Juilliard Park Rehabilitation                            | Juilliard Park Rehabilitation                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | See Project Name / Description, if applicable | N/A           | N/A                | http://srcity.org/DEPARTMENTS/PUBLICWORKS/CAPITALIMPROVEMENTPROGRAM/Pages/default.aspx | 38.437861 | -122.712322 |         | 
| 1467389509  | 9595       | Zone 4 Play Equipment Rehabilitation                     | Zone 4 Play Equipment Rehabilitation                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | See Project Name / Description, if applicable | N/A           | N/A                | http://srcity.org/DEPARTMENTS/PUBLICWORKS/CAPITALIMPROVEMENTPROGRAM/Pages/default.aspx | 38.437861 | -122.712322 |         | 
| 1467389509  | 9608       | Southeast Community Park                                 | Southeast Community Park                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | See Project Name / Description, if applicable | N/A           | N/A                | http://srcity.org/DEPARTMENTS/PUBLICWORKS/CAPITALIMPROVEMENTPROGRAM/Pages/default.aspx | 38.437861 | -122.712322 |         | 
| 1467389509  | 9632       | Finley Aquatic Center Water Feature                      | Finley Aquatic Center Water Feature                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | See Project Name / Description, if applicable | N/A           | N/A                | http://srcity.org/DEPARTMENTS/PUBLICWORKS/CAPITALIMPROVEMENTPROGRAM/Pages/default.aspx | 38.437861 | -122.712322 |         | 
| 1467389509  | 9708       | Repair/Upgrade City Facilities / ADA Settlement with DOJ | Repair/Upgrade City Facilities / ADA Settlement with DOJ                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | See Project Name / Description, if applicable | N/A           | N/A                | http://srcity.org/DEPARTMENTS/PUBLICWORKS/CAPITALIMPROVEMENTPROGRAM/Pages/default.aspx | 38.437861 | -122.712322 |         | 
| 1467389509  | 1137       | Bridge Repair - Deck Treatment                           | Project provides preventive maintenance for concrete bridge decks ensuring long-term durability and prevention of deterioration due to rebar corrosion. The work involves cleaning the concrete bridge deck, replacing expansion joints, treating the concrete deck with a methacrylate sealer, and replacing all traffic paint, thermoplastic, and raised pavement markers for approximately eight bridges.                                                                                                                                                                 | See Project Name / Description, if applicable | 2015-16       | 2015-16            | http://srcity.org/DEPARTMENTS/PUBLICWORKS/CAPITALIMPROVEMENTPROGRAM/Pages/default.aspx | 38.437861 | -122.712322 |         | 
| 1467389509  | 1165       | Sidewalk Program                                         | Repair damaged sidewalk with various methods such as grinding, asphalt concrete patches, or replacement. This project provides funds for the repair of damaged sidewalks and street tree work. Most sidewalk repairs can be made with asphalt concrete in order to make them accessible to persons with disabilities. These repairs are made by City crews at no cost to the property owner. More extensive concrete repairs are made only at locations that cannot be brought into ADA compliance with asphalt repairs. Property owners pay their share of the repair cost. | See Project Name / Description, if applicable | N/A           | N/A                | http://srcity.org/DEPARTMENTS/PUBLICWORKS/CAPITALIMPROVEMENTPROGRAM/Pages/default.aspx | 38.437861 | -122.712322 |         | 
| 1467389509  | 1166       | Slurry Seal Preparation and Traffic Control              | This project funds the preparatory asphalt work needed prior to the annual slurry seal project 17014 including small dig-outs, overlays, and skin patches. This work is completed by Field Services Streets Section staff. It also funds traffic control needed during the slurry seal application process. Traffic control is also provided by Streets Section staff.                                                                                                                                                                                                       | See Project Name / Description, if applicable | 2010-11       | 2010-11            | http://srcity.org/DEPARTMENTS/PUBLICWORKS/CAPITALIMPROVEMENTPROGRAM/Pages/default.aspx | 38.437861 | -122.712322 |         | 
```