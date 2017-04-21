# Port of Los Angeles - Public Safety and Law Enforcement

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/port-of-los-angeles-public-safety-and-law-enforcement) |
| Metadata | [Link](https://data.lacity.org/api/views/r5zp-atgu) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/r5zp-atgu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/r5zp-atgu/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | r5zp-atgu |
| Name | Port of Los Angeles - Public Safety and Law Enforcement |
| Attribution | Port of Los Angeles |
| Category | A Safe City |
| Tags | public safety, lapp, pola |
| Created | 2014-04-23T20:18:51Z |
| Publication Date | 2017-04-07T16:27:19Z |

## Description

Port of Los Angeles - Public Safety and Law Enforcement

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                      | Data Type | Render Type |
| ======== | ============== | ======================= | ========================= | ========= | =========== |
| No       | time           | :updated_at             | updated_at                | meta_data | meta_data   |
| Yes      | series tag     | reporting_period        | Reporting Period          | text      | text        |
| Yes      | numeric metric | arrests_all             | Arrests (all)             | number    | number      |
| Yes      | numeric metric | article_sniffs_k9       | Article Sniffs (K9)       | number    | number      |
| Yes      | numeric metric | boardings               | Boardings                 | number    | number      |
| Yes      | numeric metric | calls_for_service       | Calls for Service         | number    | number      |
| Yes      | numeric metric | container_terminal      | Container Terminal        | number    | number      |
| Yes      | numeric metric | dangerous_cargo         | Dangerous Cargo           | number    | number      |
| Yes      | numeric metric | dive_operations         | Dive Operations           | number    | number      |
| Yes      | numeric metric | fi_s                    | FI's                      | number    | number      |
| Yes      | numeric metric | hfir                    | HFIR                      | number    | number      |
| Yes      | numeric metric | hot_works_insp          | Hot Works Insp.           | number    | number      |
| Yes      | numeric metric | marina_s                | Marina(s)                 | number    | number      |
| Yes      | numeric metric | oil_terminals           | Oil Terminals             | number    | number      |
| Yes      | numeric metric | parking_citations       | Parking Citations         | number    | number      |
| Yes      | numeric metric | per_service_citations   | Per. Service Citations    | number    | number      |
| Yes      | numeric metric | pir_ir_s                | PIR (IR's)                | number    | number      |
| Yes      | numeric metric | security_sweeps_k9      | Security Sweeps (K9)      | number    | number      |
| Yes      | numeric metric | small_craft             | Small Craft               | number    | number      |
| Yes      | numeric metric | tank_vessel_insp        | Tank Vessel Insp.         | number    | number      |
| Yes      | numeric metric | tariff_port_citations   | Tariff/Port Citations     | number    | number      |
| Yes      | numeric metric | traffic_control         | Traffic Control           | number    | number      |
| Yes      | numeric metric | transit_shed            | Transit Shed              | number    | number      |
| Yes      | numeric metric | truck_inspections       | Truck Inspections         | number    | number      |
| Yes      | numeric metric | unattended_luggage_k9   | Unattended Luggage (K9)   | number    | number      |
| Yes      | numeric metric | vehicle_sweeps_k9       | Vehicle Sweeps (K9)       | number    | number      |
| Yes      | numeric metric | vehicles_impounded      | Vehicles Impounded        | number    | number      |
| Yes      | numeric metric | vehicles_recovered      | Vehicles Recovered        | number    | number      |
| Yes      | numeric metric | vehicles_stolen         | Vehicles Stolen           | number    | number      |
| Yes      | numeric metric | vessel_escorts          | Vessel Escorts            | number    | number      |
| Yes      | numeric metric | vessel_safety_insp      | Vessel Safety Insp.       | number    | number      |
| Yes      | numeric metric | vessels_impounded       | Vessels Impounded         | number    | number      |
| Yes      | numeric metric | vessels_stolen          | Vessels Stolen            | number    | number      |
| Yes      | numeric metric | warehouse_inspections   | Warehouse Inspections     | number    | number      |
| Yes      | numeric metric | xtra_patrol_req_area_ck | Xtra Patrol Req (Area Ck) | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:r5zp-atgu d:2014-10-08T15:01:03.000Z t:reporting_period=14-Jan m:unattended_luggage_k9=176 m:small_craft=6 m:marina_s=609 m:warehouse_inspections=128 m:container_terminal=268 m:arrests_all=28 m:hot_works_insp=56 m:tank_vessel_insp=19 m:truck_inspections=289 m:pir_ir_s=17 m:hfir=220 m:vessel_safety_insp=28 m:vehicles_impounded=13 m:xtra_patrol_req_area_ck=566 m:oil_terminals=130 m:vehicles_recovered=2 m:security_sweeps_k9=233 m:dive_operations=10 m:tariff_port_citations=11 m:per_service_citations=302 m:dangerous_cargo=326 m:vehicle_sweeps_k9=527 m:vessel_escorts=48 m:parking_citations=94 m:article_sniffs_k9=89 m:transit_shed=88 m:vehicles_stolen=0 m:boardings=17 m:traffic_control=21 m:vessels_stolen=0 m:fi_s=174 m:vessels_impounded=0 m:calls_for_service=473

series e:r5zp-atgu d:2014-10-08T15:01:04.000Z t:reporting_period=14-Feb m:unattended_luggage_k9=22 m:small_craft=10 m:marina_s=468 m:warehouse_inspections=65 m:container_terminal=212 m:arrests_all=35 m:hot_works_insp=52 m:tank_vessel_insp=12 m:truck_inspections=304 m:pir_ir_s=16 m:hfir=187 m:vessel_safety_insp=26 m:vehicles_impounded=18 m:xtra_patrol_req_area_ck=481 m:oil_terminals=73 m:vehicles_recovered=6 m:security_sweeps_k9=287 m:dive_operations=22 m:tariff_port_citations=1 m:per_service_citations=329 m:dangerous_cargo=263 m:vehicle_sweeps_k9=129 m:vessel_escorts=25 m:parking_citations=71 m:article_sniffs_k9=89 m:transit_shed=37 m:vehicles_stolen=3 m:boardings=15 m:traffic_control=18 m:vessels_stolen=0 m:fi_s=115 m:vessels_impounded=3 m:calls_for_service=402

series e:r5zp-atgu d:2014-10-08T15:01:04.000Z t:reporting_period=14-Mar m:unattended_luggage_k9=90 m:small_craft=65 m:marina_s=491 m:warehouse_inspections=30 m:container_terminal=212 m:arrests_all=32 m:hot_works_insp=49 m:tank_vessel_insp=9 m:truck_inspections=272 m:pir_ir_s=18 m:hfir=187 m:vessel_safety_insp=44 m:vehicles_impounded=15 m:xtra_patrol_req_area_ck=367 m:oil_terminals=74 m:vehicles_recovered=4 m:security_sweeps_k9=256 m:dive_operations=23 m:tariff_port_citations=15 m:per_service_citations=296 m:dangerous_cargo=244 m:vehicle_sweeps_k9=270 m:vessel_escorts=36 m:parking_citations=68 m:article_sniffs_k9=50 m:transit_shed=17 m:vehicles_stolen=0 m:boardings=6 m:traffic_control=15 m:vessels_stolen=0 m:fi_s=93 m:vessels_impounded=0 m:calls_for_service=458
```

## Meta Commands

```ls
metric m:arrests_all p:integer l:"Arrests (all)" t:dataTypeName=number

metric m:article_sniffs_k9 p:integer l:"Article Sniffs (K9)" t:dataTypeName=number

metric m:boardings p:integer l:Boardings t:dataTypeName=number

metric m:calls_for_service p:integer l:"Calls for Service" t:dataTypeName=number

metric m:container_terminal p:integer l:"Container Terminal" t:dataTypeName=number

metric m:dangerous_cargo p:integer l:"Dangerous Cargo" t:dataTypeName=number

metric m:dive_operations p:integer l:"Dive Operations" t:dataTypeName=number

metric m:fi_s p:integer l:FI's d:"Field Interview" t:dataTypeName=number

metric m:hfir p:integer l:HFIR d:"Harbor Facility Inspection Report" t:dataTypeName=number

metric m:hot_works_insp p:integer l:"Hot Works Insp." t:dataTypeName=number

metric m:marina_s p:integer l:Marina(s) d:"Marina Inspection" t:dataTypeName=number

metric m:oil_terminals p:integer l:"Oil Terminals" d:"Oil Terminal Inspection" t:dataTypeName=number

metric m:parking_citations p:integer l:"Parking Citations" t:dataTypeName=number

metric m:per_service_citations p:integer l:"Per. Service Citations" t:dataTypeName=number

metric m:pir_ir_s p:integer l:"PIR (IR's)" d:"Preliminary Investigative Report" t:dataTypeName=number

metric m:security_sweeps_k9 p:integer l:"Security Sweeps (K9)" t:dataTypeName=number

metric m:small_craft p:integer l:"Small Craft" t:dataTypeName=number

metric m:tank_vessel_insp p:integer l:"Tank Vessel Insp." t:dataTypeName=number

metric m:tariff_port_citations p:integer l:"Tariff/Port Citations" t:dataTypeName=number

metric m:traffic_control p:integer l:"Traffic Control" t:dataTypeName=number

metric m:transit_shed p:integer l:"Transit Shed" t:dataTypeName=number

metric m:truck_inspections p:integer l:"Truck Inspections" t:dataTypeName=number

metric m:unattended_luggage_k9 p:integer l:"Unattended Luggage (K9)" t:dataTypeName=number

metric m:vehicle_sweeps_k9 p:integer l:"Vehicle Sweeps (K9)" t:dataTypeName=number

metric m:vehicles_impounded p:integer l:"Vehicles Impounded" t:dataTypeName=number

metric m:vehicles_recovered p:integer l:"Vehicles Recovered" t:dataTypeName=number

metric m:vehicles_stolen p:integer l:"Vehicles Stolen" t:dataTypeName=number

metric m:vessel_escorts p:integer l:"Vessel Escorts" t:dataTypeName=number

metric m:vessel_safety_insp p:integer l:"Vessel Safety Insp." t:dataTypeName=number

metric m:vessels_impounded p:integer l:"Vessels Impounded" t:dataTypeName=number

metric m:vessels_stolen p:integer l:"Vessels Stolen" t:dataTypeName=number

metric m:warehouse_inspections p:integer l:"Warehouse Inspections" t:dataTypeName=number

metric m:xtra_patrol_req_area_ck p:integer l:"Xtra Patrol Req (Area Ck)" t:dataTypeName=number

entity e:r5zp-atgu l:"Port of Los Angeles - Public Safety and Law Enforcement" t:attribution="Port of Los Angeles" t:url=https://data.lacity.org/api/views/r5zp-atgu

property e:r5zp-atgu t:meta.view v:id=r5zp-atgu v:category="A Safe City" v:averageRating=0 v:name="Port of Los Angeles - Public Safety and Law Enforcement" v:attribution="Port of Los Angeles"

property e:r5zp-atgu t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:r5zp-atgu t:meta.view.owner v:id=2ib6-ssvz v:profileImageUrlMedium=/api/users/2ib6-ssvz/profile_images/THUMB v:profileImageUrlLarge=/api/users/2ib6-ssvz/profile_images/LARGE v:screenName="Port of Los Angeles" v:profileImageUrlSmall=/api/users/2ib6-ssvz/profile_images/TINY v:displayName="Port of Los Angeles"

property e:r5zp-atgu t:meta.view.tableauthor v:id=2ib6-ssvz v:profileImageUrlMedium=/api/users/2ib6-ssvz/profile_images/THUMB v:profileImageUrlLarge=/api/users/2ib6-ssvz/profile_images/LARGE v:screenName="Port of Los Angeles" v:profileImageUrlSmall=/api/users/2ib6-ssvz/profile_images/TINY v:roleName=publisher v:displayName="Port of Los Angeles"
```

## Top Records

```ls
| :updated_at | reporting_period | arrests_all | article_sniffs_k9 | boardings | calls_for_service | container_terminal | dangerous_cargo | dive_operations | fi_s | hfir | hot_works_insp | marina_s | oil_terminals | parking_citations | per_service_citations | pir_ir_s | security_sweeps_k9 | small_craft | tank_vessel_insp | tariff_port_citations | traffic_control | transit_shed | truck_inspections | unattended_luggage_k9 | vehicle_sweeps_k9 | vehicles_impounded | vehicles_recovered | vehicles_stolen | vessel_escorts | vessel_safety_insp | vessels_impounded | vessels_stolen | warehouse_inspections | xtra_patrol_req_area_ck | 
| =========== | ================ | =========== | ================= | ========= | ================= | ================== | =============== | =============== | ==== | ==== | ============== | ======== | ============= | ================= | ===================== | ======== | ================== | =========== | ================ | ===================== | =============== | ============ | ================= | ===================== | ================= | ================== | ================== | =============== | ============== | ================== | ================= | ============== | ===================== | ======================= | 
| 1412780463  | 14-Jan           | 28          | 89                | 17        | 473               | 268                | 326             | 10              | 174  | 220  | 56             | 609      | 130           | 94                | 302                   | 17       | 233                | 6           | 19               | 11                    | 21              | 88           | 289               | 176                   | 527               | 13                 | 2                  | 0               | 48             | 28                 | 0                 | 0              | 128                   | 566                     | 
| 1412780464  | 14-Feb           | 35          | 89                | 15        | 402               | 212                | 263             | 22              | 115  | 187  | 52             | 468      | 73            | 71                | 329                   | 16       | 287                | 10          | 12               | 1                     | 18              | 37           | 304               | 22                    | 129               | 18                 | 6                  | 3               | 25             | 26                 | 3                 | 0              | 65                    | 481                     | 
| 1412780464  | 14-Mar           | 32          | 50                | 6         | 458               | 212                | 244             | 23              | 93   | 187  | 49             | 491      | 74            | 68                | 296                   | 18       | 256                | 65          | 9                | 15                    | 15              | 17           | 272               | 90                    | 270               | 15                 | 4                  | 0               | 36             | 44                 | 0                 | 0              | 30                    | 367                     | 
| 1412780464  | 14-Apr           | 30          | 536               | 10        | 428               | 211                | 251             | 8               | 100  | 187  | 48             | 554      | 67            | 60                | 272                   | 27       | 174                | 16          | 10               | 5                     | 15              | 11           | 256               | 210                   | 61                | 8                  | 0                  | 2               | 33             | 32                 | 1                 | 0              | 55                    | 458                     | 
| 1412780464  | 14-May           | 23          | 119               | 0         | 499               | 237                | 262             | 15              | 129  | 222  | 47             | 582      | 85            | 90                | 370                   | 21       | 202                | 34          | 15               | 14                    | 16              | 21           | 263               | 36                    | 49                | 13                 | 4                  | 1               | 20             | 41                 | 2                 | 0              | 54                    | 491                     | 
| 1412780464  | 14-Jun           | 45          | 1                 | 0         | 471               | 177                | 217             | 8               | 117  | 190  | 54             | 545      | 31            | 80                | 244                   | 17       | 162                | 22          | 13               | 3                     | 18              | 33           | 143               | 1                     | 67                | 18                 | 2                  | 2               | 0              | 32                 | 0                 | 0              | 36                    | 450                     | 
| 1412780464  | 14-Jul           | 58          | 0                 | 0         | 544               | 174                | 263             | 12              | 169  | 175  | 40             | 605      | 51            | 69                | 323                   | 14       | 241                | 11          | 13               | 11                    | 21              | 25           | 138               | 3                     | 169               | 21                 | 2                  | 1               | 1              | 19                 | 2                 | 1              | 38                    | 370                     | 
| 1412780464  | 14-Aug           | 92          | 1                 | 0         | 560               | 195                | 247             | 10              | 145  | 197  | 30             | 539      | 49            | 131               | 378                   | 14       | 184                | 18          | 8                | 7                     | 18              | 5            | 149               | 4                     | 155               | 13                 | 5                  | 5               | 15             | 14                 | 1                 | 1              | 26                    | 280                     | 
| 1421059296  | 14-Oct           | 41          | 250               | 0         | 526               | 199                | 220             | 19              | 144  | 199  | 46             | 403      | 63            | 102               | 317                   | 10       | 371                | 24          | 6                | 3                     | 33              | 8            | 129               | 125                   | 269               | 8                  | 4                  | 1               | 30             | 25                 | 0                 | 0              | 44                    | 214                     | 
| 1421059301  | 14-Nov           | 42          | 2                 | 15        | 491               | 256                | 251             | 13              | 166  | 227  | 49             | 606      | 51            | 118               | 329                   | 13       | 310                | 8           | 9                | 16                    | 21              | 5            | 97                | 265                   | 13                | 10                 | 4                  | 1               | 44             | 20                 | 0                 | 0              | 56                    | 281                     | 
```