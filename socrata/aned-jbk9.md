# Post-Katrina Damage Assessment

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/post-katrina-damage-assessment) |
| Metadata | [Link](https://data.nola.gov/api/views/aned-jbk9) |
| Data: JSON | [100 Rows](https://data.nola.gov/api/views/aned-jbk9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.nola.gov/api/views/aned-jbk9/rows.csv?max_rows=100) |
| Host | data.nola.gov |
| Id | aned-jbk9 |
| Name | Post-Katrina Damage Assessment |
| Attribution | City of New Orleans ? Office of Information Technology & Innovation, Enterprise Information Team |
| Category | Archived |
| Tags | new orleans, damage, katrina |
| Created | 2013-04-03T16:03:12Z |
| Publication Date | 2013-04-03T17:58:17Z |

## Description

Post-Katrina damage assessment conducted by City inspectors, published by address with breakdown by category. These data formerly supported the "Damage Assessment Wizard" web tool. Also see attachment 'DA_Categories' for insight as to how damage was assessed.

## Columns

```ls
| Included | Schema Type    | Field Name                               | Name                                     | Data Type | Render Type |
| ======== | ============== | ======================================== | ======================================== | ========= | =========== |
| No       | time           | :updated_at                              | updated_at                               | meta_data | meta_data   |
| No       |                | address                                  | Address                                  | text      | text        |
| Yes      | numeric metric | percentage                               | Percentage                               | number    | number      |
| Yes      | numeric metric | foundations_basements                    | Foundations_Basements                    | number    | number      |
| Yes      | numeric metric | superstructure_framing_masonry           | Superstructure_Framing_Masonry           | number    | number      |
| Yes      | numeric metric | roofing                                  | Roofing                                  | number    | number      |
| Yes      | numeric metric | insulationandweatherstripping            | InsulationandWeatherStripping            | number    | number      |
| Yes      | numeric metric | exteriorfinish                           | ExteriorFinish                           | number    | number      |
| Yes      | numeric metric | interiorfinish_plaster_drywall           | InteriorFinish_Plaster_Drywall           | number    | number      |
| Yes      | numeric metric | doors_windows_shutters                   | Doors_Windows_Shutters                   | number    | number      |
| Yes      | numeric metric | lumberfinished                           | LumberFinished                           | number    | number      |
| Yes      | numeric metric | hardware                                 | Hardware                                 | number    | number      |
| Yes      | numeric metric | cabinets_countertops                     | Cabinets_Countertops                     | number    | number      |
| Yes      | numeric metric | floor_covering                           | Floor_Covering                           | number    | number      |
| Yes      | numeric metric | plumbing                                 | Plumbing                                 | number    | number      |
| Yes      | numeric metric | electrical                               | Electrical                               | number    | number      |
| Yes      | numeric metric | builtin_appliances                       | Builtin_Appliances                       | number    | number      |
| Yes      | numeric metric | heating_cooling                          | Heating_Cooling                          | number    | number      |
| Yes      | numeric metric | painting                                 | Painting                                 | number    | number      |
| Yes      | numeric metric | foundations_basements_damageper          | Foundations_Basements_DamagePer          | number    | number      |
| Yes      | numeric metric | superstructure_framing_masonry_damageper | Superstructure_Framing_Masonry_DamagePer | number    | number      |
| Yes      | numeric metric | roofing_damageper                        | Roofing_DamagePer                        | number    | number      |
| Yes      | numeric metric | insulationandweatherstripping_damageper  | InsulationandWeatherStripping_DamagePer  | number    | number      |
| Yes      | numeric metric | exteriorfinish_damageper                 | ExteriorFinish_DamagePer                 | number    | number      |
| Yes      | numeric metric | interiorfinish_plaster_drywall_damageper | InteriorFinish_Plaster_Drywall_DamagePer | number    | number      |
| Yes      | numeric metric | doors_windows_shutters_damageper         | Doors_Windows_Shutters_DamagePer         | number    | number      |
| Yes      | numeric metric | lumberfinished_damageper                 | LumberFinished_DamagePer                 | number    | number      |
| Yes      | numeric metric | hardware_damageper                       | Hardware_DamagePer                       | number    | number      |
| Yes      | numeric metric | cabinets_countertops_damageper           | Cabinets_Countertops_DamagePer           | number    | number      |
| Yes      | numeric metric | floor_covering_damageper                 | Floor_Covering_DamagePer                 | number    | number      |
| Yes      | numeric metric | plumbing_damageper                       | Plumbing_DamagePer                       | number    | number      |
| Yes      | numeric metric | electrical_damageper                     | Electrical_DamagePer                     | number    | number      |
| Yes      | numeric metric | builtin_appliances_damageper             | Builtin_Appliances_DamagePer             | number    | number      |
| Yes      | numeric metric | heating_cooling_damageper                | Heating_Cooling_DamagePer                | number    | number      |
| Yes      | numeric metric | painting_damageper                       | Painting_DamagePer                       | number    | number      |
| Yes      | numeric metric | flooddepth                               | FloodDepth                               | number    | number      |
| Yes      | numeric metric | floodduration                            | FloodDuration                            | number    | number      |
| Yes      | series tag     | floodzone                                | FloodZone                                | text      | text        |
| Yes      | series tag     | propertydescription                      | PropertyDescription                      | text      | text        |
| Yes      | series tag     | owner                                    | Owner                                    | text      | text        |
| Yes      | series tag     | taxbill                                  | TaxBill                                  | text      | text        |
| Yes      | series tag     | add1                                     | Add1                                     | text      | text        |
| Yes      | series tag     | add2                                     | Add2                                     | text      | text        |
| Yes      | series tag     | add3                                     | Add3                                     | text      | text        |
| Yes      | series tag     | add4                                     | Add4                                     | text      | text        |
| Yes      | series tag     | add5                                     | Add5                                     | text      | text        |
| Yes      | series tag     | add6                                     | Add6                                     | text      | text        |
| Yes      | series tag     | add7                                     | Add7                                     | text      | text        |
| Yes      | series tag     | add8                                     | Add8                                     | text      | text        |
| Yes      | series tag     | add9                                     | Add9                                     | text      | text        |
| Yes      | series tag     | add10                                    | Add10                                    | text      | text        |
| Yes      | series tag     | add11                                    | Add11                                    | text      | text        |
| Yes      | series tag     | add12                                    | Add12                                    | text      | text        |
| Yes      | numeric metric | add13                                    | Add13                                    | number    | text        |
| Yes      | numeric metric | add14                                    | Add14                                    | number    | text        |
| Yes      | numeric metric | add15                                    | Add15                                    | number    | text        |
| Yes      | numeric metric | add16                                    | Add16                                    | number    | text        |
| Yes      | series tag     | add17                                    | Add17                                    | text      | text        |
| Yes      | series tag     | add18                                    | Add18                                    | text      | text        |
| Yes      | numeric metric | add19                                    | Add19                                    | number    | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:aned-jbk9 d:2013-04-03T10:53:27.000Z t:propertydescription="Sq 2421 Lot 22 Andry 31 X 120 Vacant" t:taxbill=39W722901 t:owner="E Pieaville" m:percentage=-1

series e:aned-jbk9 d:2013-04-03T10:53:27.000Z t:propertydescription="Sq 7 Bloomingdale 6037-39 Annunciation St 6040 Laurel St See Sq 16 Bv" t:taxbill=615100041 t:owner=Footnote m:percentage=-1

series e:aned-jbk9 d:2013-04-03T10:53:27.000Z t:propertydescription="Square 155 Burtheville Rear Pt X 27 Over 23 X 66 Over 63 See Sq A Aud Ct 3211 Audubon Ct" t:taxbill=615200047 t:owner=Footnote m:percentage=-1
```

## Meta Commands

```ls
metric m:percentage p:float l:Percentage t:dataTypeName=number

metric m:foundations_basements p:float l:Foundations_Basements t:dataTypeName=number

metric m:superstructure_framing_masonry p:float l:Superstructure_Framing_Masonry t:dataTypeName=number

metric m:roofing p:float l:Roofing t:dataTypeName=number

metric m:insulationandweatherstripping p:float l:InsulationandWeatherStripping t:dataTypeName=number

metric m:exteriorfinish p:float l:ExteriorFinish t:dataTypeName=number

metric m:interiorfinish_plaster_drywall p:float l:InteriorFinish_Plaster_Drywall t:dataTypeName=number

metric m:doors_windows_shutters p:float l:Doors_Windows_Shutters t:dataTypeName=number

metric m:lumberfinished p:float l:LumberFinished t:dataTypeName=number

metric m:hardware p:float l:Hardware t:dataTypeName=number

metric m:cabinets_countertops p:float l:Cabinets_Countertops t:dataTypeName=number

metric m:floor_covering p:float l:Floor_Covering t:dataTypeName=number

metric m:plumbing p:float l:Plumbing t:dataTypeName=number

metric m:electrical p:float l:Electrical t:dataTypeName=number

metric m:builtin_appliances p:float l:Builtin_Appliances t:dataTypeName=number

metric m:heating_cooling p:float l:Heating_Cooling t:dataTypeName=number

metric m:painting p:float l:Painting t:dataTypeName=number

metric m:foundations_basements_damageper p:integer l:Foundations_Basements_DamagePer t:dataTypeName=number

metric m:superstructure_framing_masonry_damageper p:integer l:Superstructure_Framing_Masonry_DamagePer t:dataTypeName=number

metric m:roofing_damageper p:integer l:Roofing_DamagePer t:dataTypeName=number

metric m:insulationandweatherstripping_damageper p:integer l:InsulationandWeatherStripping_DamagePer t:dataTypeName=number

metric m:exteriorfinish_damageper p:integer l:ExteriorFinish_DamagePer t:dataTypeName=number

metric m:interiorfinish_plaster_drywall_damageper p:integer l:InteriorFinish_Plaster_Drywall_DamagePer t:dataTypeName=number

metric m:doors_windows_shutters_damageper p:integer l:Doors_Windows_Shutters_DamagePer t:dataTypeName=number

metric m:lumberfinished_damageper p:integer l:LumberFinished_DamagePer t:dataTypeName=number

metric m:hardware_damageper p:integer l:Hardware_DamagePer t:dataTypeName=number

metric m:cabinets_countertops_damageper p:integer l:Cabinets_Countertops_DamagePer t:dataTypeName=number

metric m:floor_covering_damageper p:integer l:Floor_Covering_DamagePer t:dataTypeName=number

metric m:plumbing_damageper p:integer l:Plumbing_DamagePer t:dataTypeName=number

metric m:electrical_damageper p:integer l:Electrical_DamagePer t:dataTypeName=number

metric m:builtin_appliances_damageper p:integer l:Builtin_Appliances_DamagePer t:dataTypeName=number

metric m:heating_cooling_damageper p:integer l:Heating_Cooling_DamagePer t:dataTypeName=number

metric m:painting_damageper p:integer l:Painting_DamagePer t:dataTypeName=number

metric m:flooddepth p:float l:FloodDepth t:dataTypeName=number

metric m:floodduration p:integer l:FloodDuration t:dataTypeName=number

metric m:add13 p:integer l:Add13 t:dataTypeName=number

metric m:add14 p:integer l:Add14 t:dataTypeName=number

metric m:add15 p:integer l:Add15 t:dataTypeName=number

metric m:add16 p:integer l:Add16 t:dataTypeName=number

metric m:add19 p:integer l:Add19 t:dataTypeName=number

entity e:aned-jbk9 l:"Post-Katrina Damage Assessment" t:attribution="City of New Orleans ? Office of Information Technology & Innovation, Enterprise Information Team" t:url=https://data.nola.gov/api/views/aned-jbk9

property e:aned-jbk9 t:meta.view v:id=aned-jbk9 v:category=Archived v:averageRating=0 v:name="Post-Katrina Damage Assessment" v:attribution="City of New Orleans ? Office of Information Technology & Innovation, Enterprise Information Team"

property e:aned-jbk9 t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:aned-jbk9 t:meta.view.owner v:id=guap-8ddq v:profileImageUrlMedium=/api/users/guap-8ddq/profile_images/THUMB v:profileImageUrlLarge=/api/users/guap-8ddq/profile_images/LARGE v:screenName="City of New Orleans GIS Department" v:profileImageUrlSmall=/api/users/guap-8ddq/profile_images/TINY v:displayName="City of New Orleans GIS Department" v:privilegesDisabled=false

property e:aned-jbk9 t:meta.view.tableauthor v:id=guap-8ddq v:profileImageUrlMedium=/api/users/guap-8ddq/profile_images/THUMB v:profileImageUrlLarge=/api/users/guap-8ddq/profile_images/LARGE v:screenName="City of New Orleans GIS Department" v:profileImageUrlSmall=/api/users/guap-8ddq/profile_images/TINY v:roleName=administrator v:displayName="City of New Orleans GIS Department" v:privilegesDisabled=false

property e:aned-jbk9 t:meta.view.metadata.custom_fields.common_core v:Contact_Email=data@nola.gov
```

## Top Records

```ls
| :updated_at | address            | percentage | foundations_basements | superstructure_framing_masonry | roofing | insulationandweatherstripping | exteriorfinish | interiorfinish_plaster_drywall | doors_windows_shutters | lumberfinished | hardware | cabinets_countertops | floor_covering | plumbing | electrical | builtin_appliances | heating_cooling | painting | foundations_basements_damageper | superstructure_framing_masonry_damageper | roofing_damageper | insulationandweatherstripping_damageper | exteriorfinish_damageper | interiorfinish_plaster_drywall_damageper | doors_windows_shutters_damageper | lumberfinished_damageper | hardware_damageper | cabinets_countertops_damageper | floor_covering_damageper | plumbing_damageper | electrical_damageper | builtin_appliances_damageper | heating_cooling_damageper | painting_damageper | flooddepth | floodduration | floodzone | propertydescription                                                                                         | owner       | taxbill     | add1 | add2 | add3 | add4 | add5 | add6 | add7 | add8 | add9 | add10 | add11 | add12 | add13 | add14 | add15 | add16 | add17 | add18 | add19 | 
| =========== | ================== | ========== | ===================== | ============================== | ======= | ============================= | ============== | ============================== | ====================== | ============== | ======== | ==================== | ============== | ======== | ========== | ================== | =============== | ======== | =============================== | ======================================== | ================= | ======================================= | ======================== | ======================================== | ================================ | ======================== | ================== | ============================== | ======================== | ================== | ==================== | ============================ | ========================= | ================== | ========== | ============= | ========= | =========================================================================================================== | =========== | =========== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ===== | ===== | ===== | ===== | ===== | ===== | ===== | ===== | ===== | ===== | 
| 1364986407  | ANDRY ST           | -1.00      |                       |                                |         |                               |                |                                |                        |                |          |                      |                |          |            |                    |                 |          |                                 |                                          |                   |                                         |                          |                                          |                                  |                          |                    |                                |                          |                    |                      |                              |                           |                    |            |               |           | Sq 2421 Lot 22 Andry 31 X 120 Vacant                                                                        | E Pieaville | 39W722901   |      |      |      |      |      |      |      |      |      |       |       |       |       |       |       |       |       |       |       | 
| 1364986407  | ANNUNCIATION ST    | -1.00      |                       |                                |         |                               |                |                                |                        |                |          |                      |                |          |            |                    |                 |          |                                 |                                          |                   |                                         |                          |                                          |                                  |                          |                    |                                |                          |                    |                      |                              |                           |                    |            |               |           | Sq 7 Bloomingdale 6037-39 Annunciation St 6040 Laurel St See Sq 16 Bv                                       | Footnote    | 615100041   |      |      |      |      |      |      |      |      |      |       |       |       |       |       |       |       |       |       |       | 
| 1364986407  | AUDUBON CT         | -1.00      |                       |                                |         |                               |                |                                |                        |                |          |                      |                |          |            |                    |                 |          |                                 |                                          |                   |                                         |                          |                                          |                                  |                          |                    |                                |                          |                    |                      |                              |                           |                    |            |               |           | Square 155 Burtheville Rear Pt X 27 Over 23 X 66 Over 63 See Sq A Aud Ct 3211 Audubon Ct                    | Footnote    | 615200047   |      |      |      |      |      |      |      |      |      |       |       |       |       |       |       |       |       |       |       | 
| 1364986407  | AUDUBON ST         | -1.00      |                       |                                |         |                               |                |                                |                        |                |          |                      |                |          |            |                    |                 |          |                                 |                                          |                   |                                         |                          |                                          |                                  |                          |                    |                                |                          |                    |                      |                              |                           |                    |            |               |           | Square A Audubon Ct-Burthevi Lle Center Pt 6 11 Over 13 X 30 Audubon Court See Sq 28B Mv 3439-41 Audubon St | Footnote    | 615200048   |      |      |      |      |      |      |      |      |      |       |       |       |       |       |       |       |       |       |       | 
| 1364986407  | BELMONT PL         | -1.00      |                       |                                |         |                               |                |                                |                        |                |          |                      |                |          |            |                    |                 |          |                                 |                                          |                   |                                         |                          |                                          |                                  |                          |                    |                                |                          |                    |                      |                              |                           |                    |            |               |           | Sq E Belmont Place Lot X 50 X 180/205 Belmont Place Closed Part Of A-1-A-2-3-A Thru 7-A                     | Footnote    | 614300042   |      |      |      |      |      |      |      |      |      |       |       |       |       |       |       |       |       |       |       | 
| 1364986407  | BENJAMIN ST        | -1.00      |                       |                                |         |                               |                |                                |                        |                |          |                      |                |          |            |                    |                 |          |                                 |                                          |                   |                                         |                          |                                          |                                  |                          |                    |                                |                          |                    |                      |                              |                           |                    |            |               |           | Square 65 Burtheville S-2 65 Over 63 X 162 See Square 34 Bloomingdale                                       | Footnote    | 615200016   |      |      |      |      |      |      |      |      |      |       |       |       |       |       |       |       |       |       |       | 
| 1364986407  | BENTON ST          | -1.00      |                       |                                |         |                               |                |                                |                        |                |          |                      |                |          |            |                    |                 |          |                                 |                                          |                   |                                         |                          |                                          |                                  |                          |                    |                                |                          |                    |                      |                              |                           |                    |            |               |           | Sq 2600 Lot 19 Benton 30 X 124 Vacant                                                                       | A Caldwell  | 39W726014   |      |      |      |      |      |      |      |      |      |       |       |       |       |       |       |       |       |       |       | 
| 1364986407  | BLOOMINGDALE CT    | -1.00      |                       |                                |         |                               |                |                                |                        |                |          |                      |                |          |            |                    |                 |          |                                 |                                          |                   |                                         |                          |                                          |                                  |                          |                    |                                |                          |                    |                      |                              |                           |                    |            |               |           | Sq Lower Side Bd Court Lot 8 8 30/53 X 71/69 Bloomingdale Ct & Earhart Blvd Now Part O F Lot Y Sq 118 Hv    | Footnote    | 615100074   |      |      |      |      |      |      |      |      |      |       |       |       |       |       |       |       |       |       |       | 
| 1364986407  | BRIARWOOD DR ELTER | -1.00      |                       |                                |         |                               |                |                                |                        |                |          |                      |                |          |            |                    |                 |          |                                 |                                          |                   |                                         |                          |                                          |                                  |                          |                    |                                |                          |                    |                      |                              |                           |                    |            |               |           | Unavailable                                                                                                 | Unavailable | Unavailable |      |      |      |      |      |      |      |      |      |       |       |       |       |       |       |       |       |       |       | 
| 1364986407  | BROADWAY ST        | -1.00      |                       |                                |         |                               |                |                                |                        |                |          |                      |                |          |            |                    |                 |          |                                 |                                          |                   |                                         |                          |                                          |                                  |                          |                    |                                |                          |                    |                      |                              |                           |                    |            |               |           | Sq 23 Greenville Lot See 200 Broadway For Assessment                                                        | Footnote    | 615300001   |      |      |      |      |      |      |      |      |      |       |       |       |       |       |       |       |       |       |       | 
```