# Airport Monthly Operational Report

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/airport-monthly-operational-report) |
| Metadata | [Link](https://data.austintexas.gov/api/views/67kt-ykxh) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/67kt-ykxh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/67kt-ykxh/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | 67kt-ykxh |
| Name | Airport Monthly Operational Report |
| Attribution | Austin-Bergstrom International Airport |
| Category | Business |
| Tags | airport, operations, flights, statistics, mail, cargo, freight |
| Created | 2015-07-06T18:03:33Z |
| Publication Date | 2017-03-21T17:45:26Z |

## Description

Flight statistics from Austin-Bergstrom International Airport including passenger, mail, and cargo flights. Updated monthly. Note: enplaned = departure, deplaned = arrival

## Columns

```ls
| Included | Schema Type    | Field Name                                                | Name                                                       | Data Type     | Render Type   |
| ======== | ============== | ========================================================= | ========================================================== | ============= | ============= |
| Yes      | time           | month                                                     | Month                                                      | calendar_date | calendar_date |
| Yes      | numeric metric | domestic_enplaned_passengers_revenue                      | Domestic Enplaned Passengers: Revenue                      | number        | number        |
| Yes      | numeric metric | domestic_deplaned_passengers_revenue                      | Domestic Deplaned Passengers: Revenue                      | number        | number        |
| Yes      | numeric metric | international_enplaned_passengers_revenue                 | International Enplaned Passengers: Revenue                 | number        | number        |
| Yes      | numeric metric | international_deplaned_passengers_revenue                 | International Deplaned Passengers: Revenue                 | number        | number        |
| Yes      | numeric metric | domestic_enplaned_passengers_non_revenue                  | Domestic Enplaned Passengers: Non-Revenue                  | number        | number        |
| Yes      | numeric metric | domestic_deplaned_passengers_non_revenue                  | Domestic Deplaned Passengers: Non-Revenue                  | number        | number        |
| Yes      | numeric metric | international_enplaned_passengers_non_revenue             | International Enplaned Passengers: Non-Revenue             | number        | number        |
| Yes      | numeric metric | international_deplaned_passengers_non_revenue             | International Deplaned Passengers: Non-Revenue             | number        | number        |
| Yes      | numeric metric | international_enplaned_pre_cleared_passengers_revenue     | International Enplaned Pre-Cleared Passengers: Revenue     | number        | number        |
| Yes      | numeric metric | international_deplaned_pre_cleared_passengers_revenue     | International Deplaned Pre-Cleared Passengers: Revenue     | number        | number        |
| Yes      | numeric metric | international_enplaned_pre_cleared_passengers_non_revenue | International Enplaned Pre-Cleared Passengers: Non-Revenue | number        | number        |
| Yes      | numeric metric | international_deplaned_pre_cleared_passengers_non_revenue | International Deplaned Pre-Cleared Passengers: Non-Revenue | number        | number        |
| Yes      | numeric metric | total_passengers                                          | Total Passengers                                           | number        | number        |
| Yes      | numeric metric | air_carrier_operations                                    | Air Carrier Operations                                     | number        | number        |
| Yes      | numeric metric | commuter_and_air_taxi_operations                          | Commuter and Air Taxi Operations                           | number        | number        |
| Yes      | numeric metric | military_operations                                       | Military Operations                                        | number        | number        |
| Yes      | numeric metric | general_aviation_itinerant_operations                     | General Aviation: Itinerant Operations                     | number        | number        |
| Yes      | numeric metric | general_aviation_local_operations                         | General Aviation: Local Operations                         | number        | number        |
| Yes      | numeric metric | general_aviation_total_operations                         | General Aviation: Total Operations                         | number        | number        |
| Yes      | numeric metric | total_operations                                          | Total Operations                                           | number        | number        |
| Yes      | numeric metric | domestic_enplaned_mail                                    | Domestic Enplaned Mail                                     | number        | number        |
| Yes      | numeric metric | domestic_deplaned_mail                                    | Domestic Deplaned Mail                                     | number        | number        |
| Yes      | numeric metric | international_enplaned_mail                               | International Enplaned Mail                                | number        | number        |
| Yes      | numeric metric | international_deplaned_mail                               | International Deplaned Mail                                | number        | number        |
| Yes      | numeric metric | mail_totals                                               | Mail Totals                                                | number        | number        |
| Yes      | numeric metric | domestic_enplaned_cargo                                   | Domestic Enplaned Cargo                                    | number        | number        |
| Yes      | numeric metric | domestic_deplaned_cargo                                   | Domestic Deplaned Cargo                                    | number        | number        |
| Yes      | numeric metric | international_enplaned_cargo                              | International Enplaned Cargo                               | number        | number        |
| Yes      | numeric metric | international_deplaned_cargo                              | International Deplaned Cargo                               | number        | number        |
| Yes      | numeric metric | cargo_totals                                              | Cargo Totals                                               | number        | number        |
| Yes      | numeric metric | domestic_enplaned_belly_freight                           | Domestic Enplaned Belly Freight                            | number        | number        |
| Yes      | numeric metric | domestic_deplaned_belly_freight                           | Domestic Deplaned Belly Freight                            | number        | number        |
| Yes      | numeric metric | international_enplaned_belly_freight                      | International Enplaned Belly Freight                       | number        | number        |
| Yes      | numeric metric | international_deplaned_belly_freight                      | International Deplaned Belly Freight                       | number        | number        |
| Yes      | numeric metric | belly_freight_totals                                      | Belly Freight Totals                                       | number        | number        |
| Yes      | numeric metric | cargo_totals_cargo_mail_belly_freight                     | Cargo Totals (Cargo + Mail + Belly Freight)                | number        | number        |
| Yes      | numeric metric | landing_totals                                            | Landing Totals                                             | number        | number        |
| Yes      | numeric metric | weight_totals                                             | Weight Totals                                              | number        | number        |
```

## Time Field

```ls
Value = month
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:67kt-ykxh d:2017-02-01T00:00:00.000Z m:cargo_totals_cargo_mail_belly_freight=13540149 m:domestic_enplaned_belly_freight=194125 m:mail_totals=445334 m:commuter_and_air_taxi_operations=1220 m:domestic_deplaned_mail=272751 m:international_enplaned_passengers_non_revenue=69 m:international_deplaned_cargo=220929 m:domestic_enplaned_passengers_non_revenue=10423 m:international_deplaned_pre_cleared_passengers_revenue=1572 m:general_aviation_local_operations=184 m:total_operations=14812 m:international_enplaned_passengers_revenue=8487 m:belly_freight_totals=1823268 m:international_deplaned_mail=0 m:domestic_deplaned_passengers_revenue=422699 m:cargo_totals=11271547 m:international_enplaned_belly_freight=299684 m:landing_totals=4357 m:general_aviation_itinerant_operations=4038 m:international_enplaned_pre_cleared_passengers_non_revenue=21 m:domestic_deplaned_belly_freight=423275 m:domestic_enplaned_cargo=4503768 m:international_deplaned_passengers_non_revenue=81 m:general_aviation_total_operations=4222 m:domestic_enplaned_mail=172583 m:international_enplaned_pre_cleared_passengers_revenue=1384 m:total_passengers=885325 m:domestic_deplaned_cargo=5932332 m:international_deplaned_passengers_revenue=8517 m:international_deplaned_belly_freight=906184 m:international_deplaned_pre_cleared_passengers_non_revenue=28 m:weight_totals=552711639 m:international_enplaned_cargo=614518 m:international_enplaned_mail=0 m:air_carrier_operations=8542 m:domestic_enplaned_passengers_revenue=421805 m:military_operations=828 m:domestic_deplaned_passengers_non_revenue=10239

series e:67kt-ykxh d:2017-01-01T00:00:00.000Z m:cargo_totals_cargo_mail_belly_freight=13583548 m:domestic_enplaned_belly_freight=197923 m:mail_totals=452562 m:commuter_and_air_taxi_operations=1095 m:domestic_deplaned_mail=275618 m:international_enplaned_passengers_non_revenue=60 m:international_deplaned_cargo=318802 m:domestic_enplaned_passengers_non_revenue=11946 m:international_deplaned_pre_cleared_passengers_revenue=1711 m:general_aviation_local_operations=134 m:total_operations=15661 m:international_enplaned_passengers_revenue=9922 m:belly_freight_totals=1278598 m:international_deplaned_mail=0 m:domestic_deplaned_passengers_revenue=442731 m:cargo_totals=11852388 m:international_enplaned_belly_freight=146456 m:landing_totals=4768 m:general_aviation_itinerant_operations=4206 m:international_enplaned_pre_cleared_passengers_non_revenue=25 m:domestic_deplaned_belly_freight=379146 m:domestic_enplaned_cargo=4471203 m:international_deplaned_passengers_non_revenue=54 m:general_aviation_total_operations=4340 m:domestic_enplaned_mail=176944 m:international_enplaned_pre_cleared_passengers_revenue=1640 m:total_passengers=920946 m:domestic_deplaned_cargo=6438966 m:international_deplaned_passengers_revenue=11068 m:international_deplaned_belly_freight=555073 m:international_deplaned_pre_cleared_passengers_non_revenue=18 m:weight_totals=612688871 m:international_enplaned_cargo=623417 m:international_enplaned_mail=0 m:air_carrier_operations=9322 m:domestic_enplaned_passengers_revenue=430615 m:military_operations=904 m:domestic_deplaned_passengers_non_revenue=11156

series e:67kt-ykxh d:2016-12-01T00:00:00.000Z m:cargo_totals_cargo_mail_belly_freight=16358357 m:domestic_enplaned_belly_freight=252270 m:mail_totals=535964 m:commuter_and_air_taxi_operations=1258 m:domestic_deplaned_mail=325370 m:international_enplaned_passengers_non_revenue=66 m:international_deplaned_cargo=321953 m:domestic_enplaned_passengers_non_revenue=11074 m:international_deplaned_pre_cleared_passengers_revenue=1834 m:general_aviation_local_operations=150 m:total_operations=14980 m:international_enplaned_passengers_revenue=12072 m:belly_freight_totals=1763389 m:international_deplaned_mail=0 m:domestic_deplaned_passengers_revenue=483986 m:cargo_totals=14059004 m:international_enplaned_belly_freight=194104 m:landing_totals=4893 m:general_aviation_itinerant_operations=3429 m:international_enplaned_pre_cleared_passengers_non_revenue=29 m:domestic_deplaned_belly_freight=459994 m:domestic_enplaned_cargo=5382879 m:international_deplaned_passengers_non_revenue=64 m:general_aviation_total_operations=3579 m:domestic_enplaned_mail=210594 m:international_enplaned_pre_cleared_passengers_revenue=1557 m:total_passengers=1034067 m:domestic_deplaned_cargo=7826890 m:international_deplaned_passengers_revenue=10915 m:international_deplaned_belly_freight=857021 m:international_deplaned_pre_cleared_passengers_non_revenue=37 m:weight_totals=629611090 m:international_enplaned_cargo=527282 m:international_enplaned_mail=0 m:air_carrier_operations=9540 m:domestic_enplaned_passengers_revenue=501413 m:military_operations=603 m:domestic_deplaned_passengers_non_revenue=11020
```

## Meta Commands

```ls
metric m:domestic_enplaned_passengers_revenue p:integer l:"Domestic Enplaned Passengers: Revenue" t:dataTypeName=number

metric m:domestic_deplaned_passengers_revenue p:integer l:"Domestic Deplaned Passengers: Revenue" t:dataTypeName=number

metric m:international_enplaned_passengers_revenue p:integer l:"International Enplaned Passengers: Revenue" t:dataTypeName=number

metric m:international_deplaned_passengers_revenue p:integer l:"International Deplaned Passengers: Revenue" t:dataTypeName=number

metric m:domestic_enplaned_passengers_non_revenue p:integer l:"Domestic Enplaned Passengers: Non-Revenue" t:dataTypeName=number

metric m:domestic_deplaned_passengers_non_revenue p:integer l:"Domestic Deplaned Passengers: Non-Revenue" t:dataTypeName=number

metric m:international_enplaned_passengers_non_revenue p:integer l:"International Enplaned Passengers: Non-Revenue" t:dataTypeName=number

metric m:international_deplaned_passengers_non_revenue p:integer l:"International Deplaned Passengers: Non-Revenue" t:dataTypeName=number

metric m:international_enplaned_pre_cleared_passengers_revenue p:integer l:"International Enplaned Pre-Cleared Passengers: Revenue" t:dataTypeName=number

metric m:international_deplaned_pre_cleared_passengers_revenue p:integer l:"International Deplaned Pre-Cleared Passengers: Revenue" t:dataTypeName=number

metric m:international_enplaned_pre_cleared_passengers_non_revenue p:integer l:"International Enplaned Pre-Cleared Passengers: Non-Revenue" t:dataTypeName=number

metric m:international_deplaned_pre_cleared_passengers_non_revenue p:integer l:"International Deplaned Pre-Cleared Passengers: Non-Revenue" t:dataTypeName=number

metric m:total_passengers p:integer l:"Total Passengers" t:dataTypeName=number

metric m:air_carrier_operations p:integer l:"Air Carrier Operations" t:dataTypeName=number

metric m:commuter_and_air_taxi_operations p:integer l:"Commuter and Air Taxi Operations" t:dataTypeName=number

metric m:military_operations p:integer l:"Military Operations" t:dataTypeName=number

metric m:general_aviation_itinerant_operations p:integer l:"General Aviation: Itinerant Operations" t:dataTypeName=number

metric m:general_aviation_local_operations p:integer l:"General Aviation: Local Operations" t:dataTypeName=number

metric m:general_aviation_total_operations p:integer l:"General Aviation: Total Operations" t:dataTypeName=number

metric m:total_operations p:integer l:"Total Operations" t:dataTypeName=number

metric m:domestic_enplaned_mail p:integer l:"Domestic Enplaned Mail" t:dataTypeName=number

metric m:domestic_deplaned_mail p:integer l:"Domestic Deplaned Mail" t:dataTypeName=number

metric m:international_enplaned_mail p:integer l:"International Enplaned Mail" t:dataTypeName=number

metric m:international_deplaned_mail p:integer l:"International Deplaned Mail" t:dataTypeName=number

metric m:mail_totals p:integer l:"Mail Totals" t:dataTypeName=number

metric m:domestic_enplaned_cargo p:integer l:"Domestic Enplaned Cargo" t:dataTypeName=number

metric m:domestic_deplaned_cargo p:integer l:"Domestic Deplaned Cargo" t:dataTypeName=number

metric m:international_enplaned_cargo p:integer l:"International Enplaned Cargo" t:dataTypeName=number

metric m:international_deplaned_cargo p:integer l:"International Deplaned Cargo" t:dataTypeName=number

metric m:cargo_totals p:integer l:"Cargo Totals" t:dataTypeName=number

metric m:domestic_enplaned_belly_freight p:integer l:"Domestic Enplaned Belly Freight" t:dataTypeName=number

metric m:domestic_deplaned_belly_freight p:integer l:"Domestic Deplaned Belly Freight" t:dataTypeName=number

metric m:international_enplaned_belly_freight p:integer l:"International Enplaned Belly Freight" t:dataTypeName=number

metric m:international_deplaned_belly_freight p:integer l:"International Deplaned Belly Freight" t:dataTypeName=number

metric m:belly_freight_totals p:integer l:"Belly Freight Totals" t:dataTypeName=number

metric m:cargo_totals_cargo_mail_belly_freight p:integer l:"Cargo Totals (Cargo + Mail + Belly Freight)" t:dataTypeName=number

metric m:landing_totals p:integer l:"Landing Totals" t:dataTypeName=number

metric m:weight_totals p:integer l:"Weight Totals" t:dataTypeName=number

entity e:67kt-ykxh l:"Airport Monthly Operational Report" t:attribution="Austin-Bergstrom International Airport" t:url=https://data.austintexas.gov/api/views/67kt-ykxh

property e:67kt-ykxh t:meta.view v:id=67kt-ykxh v:category=Business v:averageRating=0 v:name="Airport Monthly Operational Report" v:attribution="Austin-Bergstrom International Airport"

property e:67kt-ykxh t:meta.view.license v:name="Public Domain"

property e:67kt-ykxh t:meta.view.owner v:id=ra8t-tbn2 v:screenName=Holly v:displayName=Holly

property e:67kt-ykxh t:meta.view.tableauthor v:id=ra8t-tbn2 v:screenName=Holly v:roleName=editor v:displayName=Holly
```

## Top Records

```ls
| month               | domestic_enplaned_passengers_revenue | domestic_deplaned_passengers_revenue | international_enplaned_passengers_revenue | international_deplaned_passengers_revenue | domestic_enplaned_passengers_non_revenue | domestic_deplaned_passengers_non_revenue | international_enplaned_passengers_non_revenue | international_deplaned_passengers_non_revenue | international_enplaned_pre_cleared_passengers_revenue | international_deplaned_pre_cleared_passengers_revenue | international_enplaned_pre_cleared_passengers_non_revenue | international_deplaned_pre_cleared_passengers_non_revenue | total_passengers | air_carrier_operations | commuter_and_air_taxi_operations | military_operations | general_aviation_itinerant_operations | general_aviation_local_operations | general_aviation_total_operations | total_operations | domestic_enplaned_mail | domestic_deplaned_mail | international_enplaned_mail | international_deplaned_mail | mail_totals | domestic_enplaned_cargo | domestic_deplaned_cargo | international_enplaned_cargo | international_deplaned_cargo | cargo_totals | domestic_enplaned_belly_freight | domestic_deplaned_belly_freight | international_enplaned_belly_freight | international_deplaned_belly_freight | belly_freight_totals | cargo_totals_cargo_mail_belly_freight | landing_totals | weight_totals | 
| =================== | ==================================== | ==================================== | ========================================= | ========================================= | ======================================== | ======================================== | ============================================= | ============================================= | ===================================================== | ===================================================== | ========================================================= | ========================================================= | ================ | ====================== | ================================ | =================== | ===================================== | ================================= | ================================= | ================ | ====================== | ====================== | =========================== | =========================== | =========== | ======================= | ======================= | ============================ | ============================ | ============ | =============================== | =============================== | ==================================== | ==================================== | ==================== | ===================================== | ============== | ============= | 
| 2017-02-01T00:00:00 | 421805                               | 422699                               | 8487                                      | 8517                                      | 10423                                    | 10239                                    | 69                                            | 81                                            | 1384                                                  | 1572                                                  | 21                                                        | 28                                                        | 885325           | 8542                   | 1220                             | 828                 | 4038                                  | 184                               | 4222                              | 14812            | 172583                 | 272751                 | 0                           | 0                           | 445334      | 4503768                 | 5932332                 | 614518                       | 220929                       | 11271547     | 194125                          | 423275                          | 299684                               | 906184                               | 1823268              | 13540149                              | 4357           | 552711639     | 
| 2017-01-01T00:00:00 | 430615                               | 442731                               | 9922                                      | 11068                                     | 11946                                    | 11156                                    | 60                                            | 54                                            | 1640                                                  | 1711                                                  | 25                                                        | 18                                                        | 920946           | 9322                   | 1095                             | 904                 | 4206                                  | 134                               | 4340                              | 15661            | 176944                 | 275618                 | 0                           | 0                           | 452562      | 4471203                 | 6438966                 | 623417                       | 318802                       | 11852388     | 197923                          | 379146                          | 146456                               | 555073                               | 1278598              | 13583548                              | 4768           | 612688871     | 
| 2016-12-01T00:00:00 | 501413                               | 483986                               | 12072                                     | 10915                                     | 11074                                    | 11020                                    | 66                                            | 64                                            | 1557                                                  | 1834                                                  | 29                                                        | 37                                                        | 1034067          | 9540                   | 1258                             | 603                 | 3429                                  | 150                               | 3579                              | 14980            | 210594                 | 325370                 | 0                           | 0                           | 535964      | 5382879                 | 7826890                 | 527282                       | 321953                       | 14059004     | 252270                          | 459994                          | 194104                               | 857021                               | 1763389              | 16358357                              | 4893           | 629611090     | 
| 2016-11-01T00:00:00 | 515809                               | 512054                               | 9733                                      | 9553                                      | 9921                                     | 9668                                     | 88                                            | 62                                            | 1747                                                  | 1910                                                  | 20                                                        | 2                                                         | 1070567          | 9325                   | 1402                             | 741                 | 4546                                  | 322                               | 4868                              | 16336            | 164473                 | 344481                 | 0                           | 0                           | 508954      | 5732847                 | 6764319                 | 417437                       | 248204                       | 13162807     | 257885                          | 425791                          | 156015                               | 248204                               | 1636346              | 15308107                              | 4775           | 624303554     | 
| 2016-10-01T00:00:00 | 533081                               | 529815                               | 6333                                      | 7017                                      | 10621                                    | 10055                                    | 49                                            | 63                                            | 2014                                                  | 2198                                                  | 20                                                        | 18                                                        | 1101284          | 9612                   | 1507                             | 911                 | 5085                                  | 278                               | 5363                              | 17393            | 153359                 | 355353                 | 0                           | 0                           | 475712      | 5132008                 | 7610130                 | 1698107                      | 579758                       | 15020003     | 258811                          | 432811                          | 49903                                | 617472                               | 1359067              | 16854782                              | 4923           | 649182343     | 
| 2016-09-01T00:00:00 | 485437                               | 494179                               | 6405                                      | 8064                                      | 10371                                    | 9980                                     | 66                                            | 59                                            | 1688                                                  | 2014                                                  | 14                                                        | 15                                                        | 1018292          | 8904                   | 1550                             | 980                 | 4470                                  | 204                               | 4674                              | 16108            | 152644                 | 283359                 | 0                           | 0                           | 436003      | 6233823                 | 6743432                 | 304656                       | 1072591                      | 14354502     | 232816                          | 447695                          | 106311                               | 574226                               | 1361048              | 16151553                              | 4738           | 623397035     | 
| 2016-08-01T00:00:00 | 489422                               | 517505                               | 8620                                      | 10810                                     | 12581                                    | 12074                                    | 92                                            | 123                                           | 1395                                                  | 1811                                                  | 31                                                        | 32                                                        | 1054496          | 9223                   | 1953                             | 991                 | 3484                                  | 168                               | 3652                              | 15819            | 141804                 | 286354                 | 0                           | 0                           | 428158      | 4962333                 | 6965728                 | 417013                       | 179091                       | 12524165     | 237143                          | 447257                          | 91740                                | 472562                               | 1248702              | 14201025                              | 5181           | 660099361     | 
| 2016-07-01T00:00:00 | 541111                               | 533215                               | 13940                                     | 14792                                     | 13634                                    | 13033                                    | 99                                            | 86                                            | 1619                                                  | 2024                                                  | 41                                                        | 47                                                        | 1133641          | 9935                   | 1301                             | 990                 | 3760                                  | 216                               | 3976                              | 16202            | 152168                 | 301525                 | 0                           | 2                           | 453695      | 4742471                 | 6542258                 | 273263                       | 263738                       | 11821730     | 234134                          | 421923                          | 102865                               | 422222                               | 1181144              | 13456569                              | 5233           | 663015597     | 
| 2016-06-01T00:00:00 |                                      |                                      |                                           |                                           |                                          |                                          |                                               |                                               |                                                       |                                                       |                                                           |                                                           |                  |                        |                                  |                     |                                       |                                   |                                   |                  |                        |                        |                             |                             |             |                         |                         |                              |                              |              |                                 |                                 |                                      |                                      |                      |                                       | 5179           | 651537449     | 
| 2016-05-01T00:00:00 | 526854                               | 509829                               | 10195                                     | 10094                                     | 10169                                    | 10430                                    | 42                                            | 53                                            | 1891                                                  | 1836                                                  | 33                                                        | 24                                                        | 1081450          | 9880                   | 1248                             | 795                 | 4132                                  | 160                               | 4292                              | 16215            |                        |                        |                             |                             |             |                         |                         |                              |                              |              |                                 |                                 |                                      |                                      |                      |                                       | 5096           | 630853941     | 
```