# EMS - Ambulance Responses by Month

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ems-ambulance-responses-by-month) |
| Metadata | [Link](https://data.austintexas.gov/api/views/bptg-ndvw) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/bptg-ndvw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/bptg-ndvw/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | bptg-ndvw |
| Name | EMS - Ambulance Responses by Month |
| Attribution | Austin-Travis County EMS |
| Category | Public Safety |
| Tags | ems, responses, ambulance, atcems, workload, city, county, coa |
| Created | 2014-10-16T13:49:17Z |
| Publication Date | 2014-11-05T18:13:41Z |

## Description

This table contains data related to responses by regularly scheduled ambulances. Units that are not ambulances or are deployed on an irregular basis are excluded from this table.

## Columns

```ls
| Included | Schema Type    | Field Name                              | Name                                    | Data Type     | Render Type   |
| ======== | ============== | ======================================= | ======================================= | ============= | ============= |
| Yes      | numeric metric | month_key                               | Month Key                               | number        | number        |
| Yes      | time           | month_start_date                        | Month-Year                              | calendar_date | calendar_date |
| Yes      | numeric metric | count_responses_all                     | Total System Responses                  | number        | number        |
| Yes      | numeric metric | count_responses_into_coa                | Total Austin Responses                  | number        | number        |
| Yes      | numeric metric | count_responses_into_tc                 | Total Travis County Responses           | number        | number        |
| Yes      | numeric metric | count_responses_into_other              | Other Area Responses                    | number        | number        |
| Yes      | numeric metric | count_responses_into_coa_or_tc          | Combined City and County Responses      | number        | number        |
| Yes      | numeric metric | count_responses_into_tc_by_coa          | COA Unit Responses into TC              | number        | number        |
| Yes      | numeric metric | count_responses_into_coa_by_tc          | TC Unit Responses into COA              | number        | number        |
| Yes      | numeric metric | percent_responses_into_coa_by_tc        | Percent COA Responses by TC             | percent       | percent       |
| Yes      | numeric metric | percent_responses_into_tc_by_coa        | Percent TC Responses by COA             | percent       | percent       |
| Yes      | numeric metric | count_responses_into_other_by_coa       | count_responses_into_other_by_coa       | number        | number        |
| Yes      | numeric metric | count_responses_into_other_by_tc        | count_responses_into_other_by_tc        | number        | number        |
| Yes      | numeric metric | count_responses_into_coa_or_tc_by_coa   | count_responses_into_coa_or_tc_by_coa   | number        | number        |
| Yes      | numeric metric | count_responses_into_coa_or_tc_by_tc    | count_responses_into_coa_or_tc_by_tc    | number        | number        |
| Yes      | numeric metric | percent_responses_into_coa_by_coa       | percent_responses_into_coa_by_coa       | percent       | percent       |
| Yes      | numeric metric | percent_responses_into_tc_by_tc         | percent_responses_into_tc_by_tc         | percent       | percent       |
| Yes      | numeric metric | percent_responses_into_other_by_coa     | percent_responses_into_other_by_coa     | percent       | percent       |
| Yes      | numeric metric | percent_responses_into_other_by_tc      | percent_responses_into_other_by_tc      | percent       | percent       |
| Yes      | numeric metric | percent_responses_into_coa_or_tc_by_coa | percent_responses_into_coa_or_tc_by_coa | percent       | percent       |
| Yes      | numeric metric | percent_responses_into_coa_or_tc_by_tc  | percent_responses_into_coa_or_tc_by_tc  | percent       | percent       |
```

## Time Field

```ls
Value = month_start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:bptg-ndvw d:2010-10-01T00:00:00.000Z m:count_responses_into_other_by_coa=16 m:count_responses_into_coa_or_tc_by_coa=8532 m:count_responses_into_coa_or_tc_by_tc=1012 m:count_responses_into_coa_or_tc=9544 m:percent_responses_into_coa_or_tc_by_tc=10.60352053646 m:percent_responses_into_tc_by_tc=49.33239634574 m:count_responses_into_coa_by_tc=310 m:count_responses_into_tc=1423 m:percent_responses_into_coa_by_tc=3.81726388375 m:percent_responses_into_tc_by_coa=50.66760365425 m:count_responses_into_coa=8121 m:month_key=201010 m:percent_responses_into_other_by_tc=5.88235294117 m:count_responses_all=9561 m:percent_responses_into_other_by_coa=94.11764705882 m:percent_responses_into_coa_by_coa=96.18273611624 m:count_responses_into_tc_by_coa=721 m:count_responses_into_other=17 m:percent_responses_into_coa_or_tc_by_coa=89.39647946353 m:count_responses_into_other_by_tc=1

series e:bptg-ndvw d:2010-11-01T00:00:00.000Z m:count_responses_into_other_by_coa=22 m:count_responses_into_coa_or_tc_by_coa=7365 m:count_responses_into_coa_or_tc_by_tc=922 m:count_responses_into_coa_or_tc=8287 m:percent_responses_into_coa_or_tc_by_tc=11.12585978037 m:percent_responses_into_tc_by_tc=52.45022970903 m:count_responses_into_coa_by_tc=237 m:count_responses_into_tc=1306 m:percent_responses_into_coa_by_tc=3.39492909325 m:percent_responses_into_tc_by_coa=47.54977029096 m:count_responses_into_coa=6981 m:month_key=201011 m:percent_responses_into_other_by_tc=15.38461538461 m:count_responses_all=8313 m:percent_responses_into_other_by_coa=84.61538461538 m:percent_responses_into_coa_by_coa=96.60507090674 m:count_responses_into_tc_by_coa=621 m:count_responses_into_other=26 m:percent_responses_into_coa_or_tc_by_coa=88.87414021962 m:count_responses_into_other_by_tc=4

series e:bptg-ndvw d:2010-12-01T00:00:00.000Z m:count_responses_into_other_by_coa=31 m:count_responses_into_coa_or_tc_by_coa=7705 m:count_responses_into_coa_or_tc_by_tc=963 m:count_responses_into_coa_or_tc=8668 m:percent_responses_into_coa_or_tc_by_tc=11.10982925703 m:percent_responses_into_tc_by_tc=53.46968590211 m:count_responses_into_coa_by_tc=231 m:count_responses_into_tc=1369 m:percent_responses_into_coa_by_tc=3.16481709823 m:percent_responses_into_tc_by_coa=46.53031409788 m:count_responses_into_coa=7299 m:month_key=201012 m:percent_responses_into_other_by_tc=8.82352941176 m:count_responses_all=8702 m:percent_responses_into_other_by_coa=91.17647058823 m:percent_responses_into_coa_by_coa=96.83518290176 m:count_responses_into_tc_by_coa=637 m:count_responses_into_other=34 m:percent_responses_into_coa_or_tc_by_coa=88.89017074296 m:count_responses_into_other_by_tc=3
```

## Meta Commands

```ls
metric m:month_key p:integer l:"Month Key" d:"Key field containing year and month in <yyyymm> format." t:dataTypeName=number

metric m:count_responses_all p:integer l:"Total System Responses" d:"Count of all responses by regularly scheduled ATCEMS ambulances" t:dataTypeName=number

metric m:count_responses_into_coa p:integer l:"Total Austin Responses" d:"Count of all responses by regularly scheduled ATCEMS ambulances into the City of Austin." t:dataTypeName=number

metric m:count_responses_into_tc p:integer l:"Total Travis County Responses" d:"Count of all responses by regularly scheduled ATCEMS ambulances into Travis County." t:dataTypeName=number

metric m:count_responses_into_other p:integer l:"Other Area Responses" d:"Count of all responses by regularly scheduled ATCEMS ambulances outside the ATCEMS service area." t:dataTypeName=number

metric m:count_responses_into_coa_or_tc p:integer l:"Combined City and County Responses" d:"Count of all responses by regularly scheduled ATCEMS ambulances into City of Austin or Travis County." t:dataTypeName=number

metric m:count_responses_into_tc_by_coa p:integer l:"COA Unit Responses into TC" d:"Count of responses by ATCEMS ambulances stationed in the City of Austin into Travis County." t:dataTypeName=number

metric m:count_responses_into_coa_by_tc p:integer l:"TC Unit Responses into COA" d:"Count of responses by ATCEMS ambulances stationed in Travis County into the City of Austin." t:dataTypeName=number

metric m:percent_responses_into_coa_by_tc p:double l:"Percent COA Responses by TC" d:"Percent of responses into the City of Austin performed by ambulances stationed in Travis County." t:dataTypeName=percent

metric m:percent_responses_into_tc_by_coa p:double l:"Percent TC Responses by COA" d:"Percent of responses into Travis County performed by ambulances stationed in the City of Austin." t:dataTypeName=percent

metric m:count_responses_into_other_by_coa p:integer l:count_responses_into_other_by_coa t:dataTypeName=number

metric m:count_responses_into_other_by_tc p:integer l:count_responses_into_other_by_tc t:dataTypeName=number

metric m:count_responses_into_coa_or_tc_by_coa p:integer l:count_responses_into_coa_or_tc_by_coa t:dataTypeName=number

metric m:count_responses_into_coa_or_tc_by_tc p:integer l:count_responses_into_coa_or_tc_by_tc t:dataTypeName=number

metric m:percent_responses_into_coa_by_coa p:double l:percent_responses_into_coa_by_coa t:dataTypeName=percent

metric m:percent_responses_into_tc_by_tc p:double l:percent_responses_into_tc_by_tc t:dataTypeName=percent

metric m:percent_responses_into_other_by_coa p:float l:percent_responses_into_other_by_coa t:dataTypeName=percent

metric m:percent_responses_into_other_by_tc p:float l:percent_responses_into_other_by_tc t:dataTypeName=percent

metric m:percent_responses_into_coa_or_tc_by_coa p:double l:percent_responses_into_coa_or_tc_by_coa t:dataTypeName=percent

metric m:percent_responses_into_coa_or_tc_by_tc p:double l:percent_responses_into_coa_or_tc_by_tc t:dataTypeName=percent

entity e:bptg-ndvw l:"EMS - Ambulance Responses by Month" t:attribution="Austin-Travis County EMS" t:url=https://data.austintexas.gov/api/views/bptg-ndvw

property e:bptg-ndvw t:meta.view v:id=bptg-ndvw v:category="Public Safety" v:attributionLink=http://www.austintexas.gov/department/ems v:averageRating=0 v:name="EMS - Ambulance Responses by Month" v:attribution="Austin-Travis County EMS"

property e:bptg-ndvw t:meta.view.owner v:id=4zcf-8die v:profileImageUrlMedium=/api/users/4zcf-8die/profile_images/THUMB v:profileImageUrlLarge=/api/users/4zcf-8die/profile_images/LARGE v:screenName="Austin-Travis County EMS" v:profileImageUrlSmall=/api/users/4zcf-8die/profile_images/TINY v:displayName="Austin-Travis County EMS"

property e:bptg-ndvw t:meta.view.tableauthor v:id=4zcf-8die v:profileImageUrlMedium=/api/users/4zcf-8die/profile_images/THUMB v:profileImageUrlLarge=/api/users/4zcf-8die/profile_images/LARGE v:screenName="Austin-Travis County EMS" v:profileImageUrlSmall=/api/users/4zcf-8die/profile_images/TINY v:roleName=publisher_stories v:displayName="Austin-Travis County EMS"
```

## Top Records

```ls
| month_key | month_start_date    | count_responses_all | count_responses_into_coa | count_responses_into_tc | count_responses_into_other | count_responses_into_coa_or_tc | count_responses_into_tc_by_coa | count_responses_into_coa_by_tc | percent_responses_into_coa_by_tc | percent_responses_into_tc_by_coa | count_responses_into_other_by_coa | count_responses_into_other_by_tc | count_responses_into_coa_or_tc_by_coa | count_responses_into_coa_or_tc_by_tc | percent_responses_into_coa_by_coa | percent_responses_into_tc_by_tc | percent_responses_into_other_by_coa | percent_responses_into_other_by_tc | percent_responses_into_coa_or_tc_by_coa | percent_responses_into_coa_or_tc_by_tc | 
| ========= | =================== | =================== | ======================== | ======================= | ========================== | ============================== | ============================== | ============================== | ================================ | ================================ | ================================= | ================================ | ===================================== | ==================================== | ================================= | =============================== | =================================== | ================================== | ======================================= | ====================================== | 
| 201010    | 2010-10-01T00:00:00 | 9561                | 8121                     | 1423                    | 17                         | 9544                           | 721                            | 310                            | 3.8172638837500                  | 50.6676036542500                 | 16                                | 1                                | 8532                                  | 1012                                 | 96.1827361162400                  | 49.3323963457400                | 94.1176470588200                    | 5.8823529411700                    | 89.3964794635300                        | 10.6035205364600                       | 
| 201011    | 2010-11-01T00:00:00 | 8313                | 6981                     | 1306                    | 26                         | 8287                           | 621                            | 237                            | 3.3949290932500                  | 47.5497702909600                 | 22                                | 4                                | 7365                                  | 922                                  | 96.6050709067400                  | 52.4502297090300                | 84.6153846153800                    | 15.3846153846100                   | 88.8741402196200                        | 11.1258597803700                       | 
| 201012    | 2010-12-01T00:00:00 | 8702                | 7299                     | 1369                    | 34                         | 8668                           | 637                            | 231                            | 3.1648170982300                  | 46.5303140978800                 | 31                                | 3                                | 7705                                  | 963                                  | 96.8351829017600                  | 53.4696859021100                | 91.1764705882300                    | 8.8235294117600                    | 88.8901707429600                        | 11.1098292570300                       | 
| 201101    | 2011-01-01T00:00:00 | 8823                | 7553                     | 1250                    | 20                         | 8803                           | 601                            | 272                            | 3.6012180590400                  | 48.0800000000000                 | 16                                | 4                                | 7882                                  | 921                                  | 96.3987819409500                  | 51.9200000000000                | 80.0000000000000                    | 20.0000000000000                   | 89.5376576167200                        | 10.4623423832700                       | 
| 201102    | 2011-02-01T00:00:00 | 8839                | 7469                     | 1352                    | 18                         | 8821                           | 686                            | 274                            | 3.6684964520000                  | 50.7396449704100                 | 16                                | 2                                | 7881                                  | 940                                  | 96.3315035479900                  | 49.2603550295800                | 88.8888888888800                    | 11.1111111111100                   | 89.3436118353900                        | 10.6563881646000                       | 
| 201103    | 2011-03-01T00:00:00 | 9331                | 7938                     | 1378                    | 15                         | 9316                           | 669                            | 274                            | 3.4517510707900                  | 48.5486211901300                 | 11                                | 4                                | 8333                                  | 983                                  | 96.5482489292000                  | 51.4513788098600                | 73.3333333333300                    | 26.6666666666600                   | 89.4482610562400                        | 10.5517389437500                       | 
| 201104    | 2011-04-01T00:00:00 | 9478                | 8068                     | 1390                    | 20                         | 9458                           | 609                            | 271                            | 3.3589489340600                  | 43.8129496402800                 | 15                                | 5                                | 8406                                  | 1052                                 | 96.6410510659300                  | 56.1870503597100                | 75.0000000000000                    | 25.0000000000000                   | 88.8771410446100                        | 11.1228589553800                       | 
| 201105    | 2011-05-01T00:00:00 | 9902                | 8352                     | 1524                    | 26                         | 9876                           | 687                            | 248                            | 2.9693486590000                  | 45.0787401574800                 | 21                                | 5                                | 8791                                  | 1085                                 | 97.0306513409900                  | 54.9212598425100                | 80.7692307692300                    | 19.2307692307600                   | 89.0137707573900                        | 10.9862292426000                       | 
| 201106    | 2011-06-01T00:00:00 | 9915                | 8485                     | 1413                    | 17                         | 9898                           | 621                            | 301                            | 3.5474366529100                  | 43.9490445859800                 | 13                                | 4                                | 8805                                  | 1093                                 | 96.4525633470800                  | 56.0509554140100                | 76.4705882352900                    | 23.5294117647000                   | 88.9573651242600                        | 11.0426348757300                       | 
| 201107    | 2011-07-01T00:00:00 | 9890                | 8418                     | 1463                    | 9                          | 9881                           | 634                            | 279                            | 3.3143264433300                  | 43.3356117566600                 | 6                                 | 3                                | 8773                                  | 1108                                 | 96.6856735566600                  | 56.6643882433300                | 66.6666666666600                    | 33.3333333333300                   | 88.7865600647700                        | 11.2134399352200                       | 
```