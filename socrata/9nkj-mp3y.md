# 2005 - 2014 Fire Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2005-2014-fire-data) |
| Metadata | [Link](https://data.oregon.gov/api/views/9nkj-mp3y) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/9nkj-mp3y/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/9nkj-mp3y/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | 9nkj-mp3y |
| Name | 2005 - 2014 Fire Data |
| Attribution | Oregon Department of Forestry |
| Category | Natural Resources |
| Tags | fire, wildfire, oregon |
| Created | 2015-05-22T17:24:52Z |
| Publication Date | 2016-04-18T20:25:04Z |

## Description

Wildfire data from 2005-2014 in Oregon.

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type     | Render Type   |
| ======== | ============== | ====================== | ====================== | ============= | ============= |
| Yes      | series tag     | fireyear               | FireYear               | text          | text          |
| Yes      | series tag     | current_district       | Current_District       | text          | number        |
| Yes      | numeric metric | current_unit           | Current_Unit           | number        | number        |
| Yes      | series tag     | firenumber             | FireNumber             | text          | number        |
| Yes      | series tag     | fiscalyear             | FiscalYear             | text          | text          |
| Yes      | series tag     | firename               | FireName               | text          | text          |
| Yes      | series tag     | twn                    | Twn                    | text          | text          |
| Yes      | series tag     | rng                    | Rng                    | text          | text          |
| Yes      | numeric metric | sec                    | Sec                    | number        | number        |
| Yes      | series tag     | subdiv                 | Subdiv                 | text          | text          |
| Yes      | numeric metric | county                 | County                 | number        | number        |
| Yes      | series tag     | causebydesc            | CauseByDesc            | text          | text          |
| Yes      | series tag     | generaldesc            | GeneralDesc            | text          | text          |
| Yes      | series tag     | specificdesc           | SpecificDesc           | text          | text          |
| Yes      | series tag     | cause_comments         | Cause_Comments         | text          | text          |
| Yes      | numeric metric | general_restriction    | General_Restriction    | number        | number        |
| Yes      | numeric metric | industrial_restriction | Industrial_Restriction | number        | number        |
| Yes      | numeric metric | burn_index             | Burn_Index             | number        | number        |
| Yes      | series tag     | regulatedusezone       | RegulatedUseZone       | text          | text          |
| No       |                | ign_datetime           | Ign_DateTime           | calendar_date | calendar_date |
| Yes      | time           | reportdateandtime      | ReportDateAndTime      | calendar_date | calendar_date |
| No       |                | control_datetime       | Control_DateTime       | calendar_date | calendar_date |
| Yes      | numeric metric | flame_length           | Flame_length           | number        | number        |
| Yes      | numeric metric | behavior               | Behavior               | number        | number        |
| Yes      | series tag     | fuel                   | Fuel                   | text          | text          |
| Yes      | numeric metric | topography             | Topography             | number        | number        |
| Yes      | numeric metric | aspect                 | Aspect                 | number        | number        |
| Yes      | numeric metric | slope                  | Slope                  | number        | number        |
| Yes      | numeric metric | elevation              | Elevation              | number        | number        |
| Yes      | numeric metric | size_acres             | Size_acres             | number        | number        |
| Yes      | numeric metric | size_prot              | Size_prot              | number        | number        |
```

## Time Field

```ls
Value = reportdateandtime
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = ign_datetime,control_datetime
```

## Data Commands

```ls
```

## Meta Commands

```ls
metric m:current_unit p:integer l:Current_Unit d:"Unit code by district (District #-Unit#) 51-1 = Tillamook 52-1 = Astoria 53-1 = Forest Grove 53-2 = Columbia 55 -1 = Philomath 55-2 = Dallas 55-3 = Toledo 71-1 = Medford 71-2 = Grants Pass 72-1 = Coos Bay 72-2 = Bridge 72-3 = Gold Beach 73-1 = North 73-2 = South 73-3 = Central 78-1 = Veneta 77-1 = Eastern Lane 77-2 = Sweet Home 58-1 = Molalla 58-2 = Santiam 95-1 = Prineville 95-2 = John Day 95-3 = The Dalles 95-4 = Sisters 97-1 = LaGrande 97-2 = Baker 97-3 = Pendleton 97-4 = Wallowa 98-1 = Klamath 98-2 = Lakeview 99-1 = Crescent" t:dataTypeName=number

metric m:sec p:integer l:Sec d:Section t:dataTypeName=number

metric m:county p:integer l:County d:"1 = Baker 2 = Benton 3 = Clackamas 4 = Clatsop 5 = Columbia 6 = Coos 7 = Crook 8 = Curry 9 = Deschutes 10 = Douglas 11 = Gilliam 12 = Grant 13 = Harney 14 = Hood River 15 = Jackson 16 = Jefferson 17 = Josephine 18 = Klamath 19 = Lake 20 = Lane 21 = Lincoln 22 = Linn 23 = Malheur 24 = Marion 25 = Morrow 26 = Multnomah 27 = Polk 28 = Sherman 29 = Tillamook 30 = Umatilla 31 = Union 32 = Wallowa 33 = Wasco 34 = Washington 35 = Wheeler 36 = Yamhill 37 = Other State" t:dataTypeName=number

metric m:general_restriction p:integer l:General_Restriction d:"0 = Outside closed fire season 1 = Closed fire season only, Level 1 5 = Regulated use closure 6 = Permit closure 7 = Absolute closure" t:dataTypeName=number

metric m:industrial_restriction p:integer l:Industrial_Restriction d:"0 = Outside closed fire season 1 = Level 1 (closed fire season only) 2 = Level 2 (partial hoot owl) 3 = Level 3 (partial shutdown) 4 = Level 4 (general shutdown) 9 = Does not apply (Eastern Oregon)" t:dataTypeName=number

metric m:burn_index p:integer l:Burn_Index t:dataTypeName=number

metric m:flame_length p:integer l:Flame_length t:dataTypeName=number

metric m:behavior p:integer l:Behavior d:"1 = Smoldering 2 = Creeping/spreading 3 = Running 4 = Running/spotting 5 = Crowning 6 = Crowning and spotting 7 = Erratic behavior 9 = Non-forest fuel" t:dataTypeName=number

metric m:topography p:integer l:Topography d:"1 = Ridgetop 2 = Saddle 3 = Upper 1/3 of slope 4 = Middle 1/3 of slope 5 = Lower 1/3 of slope 6 = Canyon bottom 7 = Valley bottom 8 = Mesa or plateau 9 = Flat or rolling" t:dataTypeName=number

metric m:aspect p:integer l:Aspect d:"0 = Flat 1 = North 2 = Northeast 3 = East 4 = Southeast 5 = South 6 = Southwest 7 = West 8 = Northwest 9 = Ridgetop" t:dataTypeName=number

metric m:slope p:integer l:Slope d:"0 = 0-25% 1 = 26-40% 2 = 41-55% 3 = 56-75% 4 = Over 75%" t:dataTypeName=number

metric m:elevation p:integer l:Elevation d:"0 = Below sea level - 500 feet 1 = 501 - 1500 feet 2 = 1501 - 2500 feet 3 = 2501 - 3500 feet 4 = 3501 - 4500 feet 5 = 4501 - 5500 feet 6 = 5501 - 6500 feet 7 = 6501 - 7500 feet 8 = 7501 - 8500 feet 9 = Over 8500 feet" t:dataTypeName=number

metric m:size_acres p:double l:Size_acres t:dataTypeName=number

metric m:size_prot p:double l:Size_prot d:"Protected acres" t:dataTypeName=number

entity e:9nkj-mp3y l:"2005 - 2014 Fire Data" t:attribution="Oregon Department of Forestry" t:url=https://data.oregon.gov/api/views/9nkj-mp3y

property e:9nkj-mp3y t:meta.view v:id=9nkj-mp3y v:category="Natural Resources" v:attributionLink=http://oregon.gov/ODF v:averageRating=0 v:name="2005 - 2014 Fire Data" v:attribution="Oregon Department of Forestry"

property e:9nkj-mp3y t:meta.view.license v:name="Public Domain"

property e:9nkj-mp3y t:meta.view.owner v:id=d6zp-7ggp v:screenName=JeriChase v:displayName=JeriChase

property e:9nkj-mp3y t:meta.view.tableauthor v:id=d6zp-7ggp v:screenName=JeriChase v:roleName=editor v:displayName=JeriChase
```

## Top Records

```ls
| fireyear | current_district | current_unit | firenumber | fiscalyear | firename | twn | rng | sec | subdiv | county | causebydesc | generaldesc | specificdesc | cause_comments | general_restriction | industrial_restriction | burn_index | regulatedusezone | ign_datetime | reportdateandtime | control_datetime | flame_length | behavior | fuel | topography | aspect | slope | elevation | size_acres | size_prot | 
| ======== | ================ | ============ | ========== | ========== | ======== | === | === | === | ====== | ====== | =========== | =========== | ============ | ============== | =================== | ====================== | ========== | ================ | ============ | ================= | ================ | ============ | ======== | ==== | ========== | ====== | ===== | ========= | ========== | ========= | 
|          |                  |              |            |            |          |     |     |     |        |        |             |             |              |                |                     |                        |            |                  |              |                   |                  |              |          |      |            |        |       |           |            |           | 
|          |                  |              |            |            |          |     |     |     |        |        |             |             |              |                |                     |                        |            |                  |              |                   |                  |              |          |      |            |        |       |           |            |           | 
|          |                  |              |            |            |          |     |     |     |        |        |             |             |              |                |                     |                        |            |                  |              |                   |                  |              |          |      |            |        |       |           |            |           | 
|          |                  |              |            |            |          |     |     |     |        |        |             |             |              |                |                     |                        |            |                  |              |                   |                  |              |          |      |            |        |       |           |            |           | 
|          |                  |              |            |            |          |     |     |     |        |        |             |             |              |                |                     |                        |            |                  |              |                   |                  |              |          |      |            |        |       |           |            |           | 
|          |                  |              |            |            |          |     |     |     |        |        |             |             |              |                |                     |                        |            |                  |              |                   |                  |              |          |      |            |        |       |           |            |           | 
|          |                  |              |            |            |          |     |     |     |        |        |             |             |              |                |                     |                        |            |                  |              |                   |                  |              |          |      |            |        |       |           |            |           | 
|          |                  |              |            |            |          |     |     |     |        |        |             |             |              |                |                     |                        |            |                  |              |                   |                  |              |          |      |            |        |       |           |            |           | 
|          |                  |              |            |            |          |     |     |     |        |        |             |             |              |                |                     |                        |            |                  |              |                   |                  |              |          |      |            |        |       |           |            |           | 
|          |                  |              |            |            |          |     |     |     |        |        |             |             |              |                |                     |                        |            |                  |              |                   |                  |              |          |      |            |        |       |           |            |           | 
```