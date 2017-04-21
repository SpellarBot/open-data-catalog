# Charles County Full and Part Time Jobs By Industry: 2001-2040

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/charles-county-full-and-part-time-jobs-by-industry-2001-2040) |
| Metadata | [Link](https://data.maryland.gov/api/views/bkkj-fb5g) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/bkkj-fb5g/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/bkkj-fb5g/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | bkkj-fb5g |
| Name | Charles County Full and Part Time Jobs By Industry: 2001-2040 |
| Attribution | Maryland Department of Planning |
| Category | Planning |
| Tags | full and part time jobs in maryland by industry and by place of work from 2001 to 2040. |
| Created | 2015-02-19T15:37:37Z |
| Publication Date | 2015-02-19T15:41:41Z |

## Description

Full and Part Time Jobs in Charles County by Industry and by Place of Work from 2001 to 2040.

## Columns

```ls
| Included | Schema Type    | Field Name                                    | Name                                             | Data Type     | Render Type   |
| ======== | ============== | ============================================= | ================================================ | ============= | ============= |
| Yes      | time           | date_created                                  | Date created                                     | calendar_date | calendar_date |
| No       |                | year                                          | Year                                             | number        | text          |
| Yes      | numeric metric | total_employment                              | Total Employment                                 | number        | number        |
| Yes      | numeric metric | farm_employment                               | Farm employment                                  | number        | number        |
| Yes      | numeric metric | forestry_fishing_related_activities_and_other | Forestry, fishing, related activities, and other | number        | number        |
| Yes      | numeric metric | mining                                        | Mining                                           | number        | number        |
| Yes      | numeric metric | utilities                                     | Utilities                                        | number        | number        |
| Yes      | numeric metric | construction                                  | Construction                                     | number        | number        |
| Yes      | numeric metric | manufacturing                                 | Manufacturing                                    | number        | number        |
| Yes      | numeric metric | wholesale_trade                               | Wholesale trade                                  | number        | number        |
| Yes      | numeric metric | retail_trade                                  | Retail trade                                     | number        | number        |
| Yes      | numeric metric | transportation_and_warehousing                | Transportation and warehousing                   | number        | number        |
| Yes      | numeric metric | information                                   | Information                                      | number        | number        |
| Yes      | numeric metric | finance_and_insurance                         | Finance and insurance                            | number        | number        |
| Yes      | numeric metric | real_estate_and_rental_and_leasing            | Real estate and rental and leasing               | number        | number        |
| Yes      | numeric metric | professional_and_technical_services           | Professional and technical services              | number        | number        |
| Yes      | numeric metric | management_of_companies_and_enterprises       | Management of companies and enterprises          | number        | number        |
| Yes      | numeric metric | administrative_and_waste_services             | Administrative and waste services                | number        | number        |
| Yes      | numeric metric | educational_services                          | Educational services                             | number        | number        |
| Yes      | numeric metric | health_care_and_social_assistance             | Health care and social assistance                | number        | number        |
| Yes      | numeric metric | arts_entertainment_and_recreation             | Arts, entertainment, and recreation              | number        | number        |
| Yes      | numeric metric | accommodation_and_food_services               | Accommodation and food services                  | number        | number        |
| Yes      | numeric metric | other_services_except_public_administration   | Other services, except public administration     | number        | number        |
| Yes      | numeric metric | government_and_government_enterprises         | Government and government enterprises            | number        | number        |
| Yes      | numeric metric | federal_civilian                              | Federal, civilian                                | number        | number        |
| Yes      | numeric metric | military                                      | Military                                         | number        | number        |
| Yes      | numeric metric | state_and_local                               | State and local                                  | number        | number        |
| Yes      | numeric metric | employment_state                              | Employment State                                 | number        | number        |
| Yes      | numeric metric | local                                         | Local                                            | number        | number        |
```

## Time Field

```ls
Value = date_created
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = year
```

## Data Commands

```ls
series e:bkkj-fb5g d:2015-02-18T00:00:00.000Z m:arts_entertainment_and_recreation=783 m:mining=73 m:manufacturing=1502 m:other_services_except_public_administration=3168 m:administrative_and_waste_services=1989 m:employment_state=652 m:retail_trade=9416 m:government_and_government_enterprises=8865 m:military=925 m:wholesale_trade=997 m:total_employment=51914 m:utilities=758 m:state_and_local=5772 m:construction=5536 m:health_care_and_social_assistance=4546 m:transportation_and_warehousing=1489 m:information=630 m:management_of_companies_and_enterprises=83 m:finance_and_insurance=1382 m:federal_civilian=2168 m:accommodation_and_food_services=4905 m:real_estate_and_rental_and_leasing=2216 m:professional_and_technical_services=2514 m:farm_employment=458 m:educational_services=440 m:forestry_fishing_related_activities_and_other=164 m:local=5120

series e:bkkj-fb5g d:2015-02-18T00:00:00.000Z m:arts_entertainment_and_recreation=825 m:mining=72 m:manufacturing=1506 m:other_services_except_public_administration=3518 m:administrative_and_waste_services=2090 m:employment_state=656 m:retail_trade=9572 m:government_and_government_enterprises=9159 m:military=957 m:wholesale_trade=937 m:total_employment=53324 m:utilities=713 m:state_and_local=5927 m:construction=5706 m:health_care_and_social_assistance=4692 m:transportation_and_warehousing=1453 m:information=575 m:management_of_companies_and_enterprises=116 m:finance_and_insurance=1301 m:federal_civilian=2275 m:accommodation_and_food_services=4815 m:real_estate_and_rental_and_leasing=2347 m:professional_and_technical_services=2766 m:farm_employment=425 m:educational_services=513 m:forestry_fishing_related_activities_and_other=223 m:local=5271

series e:bkkj-fb5g d:2015-02-18T00:00:00.000Z m:arts_entertainment_and_recreation=798 m:mining=64 m:manufacturing=1407 m:other_services_except_public_administration=3506 m:administrative_and_waste_services=2444 m:employment_state=661 m:retail_trade=9905 m:government_and_government_enterprises=9389 m:military=993 m:wholesale_trade=1306 m:total_employment=54717 m:utilities=555 m:state_and_local=6108 m:construction=5414 m:health_care_and_social_assistance=4861 m:transportation_and_warehousing=1477 m:information=675 m:management_of_companies_and_enterprises=86 m:finance_and_insurance=1497 m:federal_civilian=2288 m:accommodation_and_food_services=4866 m:real_estate_and_rental_and_leasing=2587 m:professional_and_technical_services=2695 m:farm_employment=413 m:educational_services=624 m:forestry_fishing_related_activities_and_other=148 m:local=5447
```

## Meta Commands

```ls
metric m:total_employment p:integer l:"Total Employment" t:dataTypeName=number

metric m:farm_employment p:integer l:"Farm employment" t:dataTypeName=number

metric m:forestry_fishing_related_activities_and_other p:integer l:"Forestry, fishing, related activities, and other" t:dataTypeName=number

metric m:mining p:integer l:Mining t:dataTypeName=number

metric m:utilities p:integer l:Utilities t:dataTypeName=number

metric m:construction p:integer l:Construction t:dataTypeName=number

metric m:manufacturing p:integer l:Manufacturing t:dataTypeName=number

metric m:wholesale_trade p:integer l:"Wholesale trade" t:dataTypeName=number

metric m:retail_trade p:integer l:"Retail trade" t:dataTypeName=number

metric m:transportation_and_warehousing p:integer l:"Transportation and warehousing" t:dataTypeName=number

metric m:information p:integer l:Information t:dataTypeName=number

metric m:finance_and_insurance p:integer l:"Finance and insurance" t:dataTypeName=number

metric m:real_estate_and_rental_and_leasing p:integer l:"Real estate and rental and leasing" t:dataTypeName=number

metric m:professional_and_technical_services p:integer l:"Professional and technical services" t:dataTypeName=number

metric m:management_of_companies_and_enterprises p:integer l:"Management of companies and enterprises" t:dataTypeName=number

metric m:administrative_and_waste_services p:integer l:"Administrative and waste services" t:dataTypeName=number

metric m:educational_services p:integer l:"Educational services" t:dataTypeName=number

metric m:health_care_and_social_assistance p:integer l:"Health care and social assistance" t:dataTypeName=number

metric m:arts_entertainment_and_recreation p:integer l:"Arts, entertainment, and recreation" t:dataTypeName=number

metric m:accommodation_and_food_services p:integer l:"Accommodation and food services" t:dataTypeName=number

metric m:other_services_except_public_administration p:integer l:"Other services, except public administration" t:dataTypeName=number

metric m:government_and_government_enterprises p:integer l:"Government and government enterprises" t:dataTypeName=number

metric m:federal_civilian p:integer l:"Federal, civilian" t:dataTypeName=number

metric m:military p:integer l:Military t:dataTypeName=number

metric m:state_and_local p:integer l:"State and local" t:dataTypeName=number

metric m:employment_state p:integer l:"Employment State" t:dataTypeName=number

metric m:local p:integer l:Local t:dataTypeName=number

entity e:bkkj-fb5g l:"Charles County Full and Part Time Jobs By Industry: 2001-2040" t:attribution="Maryland Department of Planning" t:url=https://data.maryland.gov/api/views/bkkj-fb5g

property e:bkkj-fb5g t:meta.view v:id=bkkj-fb5g v:category=Planning v:attributionLink=http://planning.maryland.gov/msdc/projection/employment/NAICS_Jobs.shtml v:averageRating=0 v:name="Charles County Full and Part Time Jobs By Industry: 2001-2040" v:attribution="Maryland Department of Planning"

property e:bkkj-fb5g t:meta.view.license v:name="Public Domain"

property e:bkkj-fb5g t:meta.view.owner v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:displayName=MDP

property e:bkkj-fb5g t:meta.view.tableauthor v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:roleName=editor v:displayName=MDP
```

## Top Records

```ls
| date_created        | year | total_employment | farm_employment | forestry_fishing_related_activities_and_other | mining | utilities | construction | manufacturing | wholesale_trade | retail_trade | transportation_and_warehousing | information | finance_and_insurance | real_estate_and_rental_and_leasing | professional_and_technical_services | management_of_companies_and_enterprises | administrative_and_waste_services | educational_services | health_care_and_social_assistance | arts_entertainment_and_recreation | accommodation_and_food_services | other_services_except_public_administration | government_and_government_enterprises | federal_civilian | military | state_and_local | employment_state | local | 
| =================== | ==== | ================ | =============== | ============================================= | ====== | ========= | ============ | ============= | =============== | ============ | ============================== | =========== | ===================== | ================================== | =================================== | ======================================= | ================================= | ==================== | ================================= | ================================= | =============================== | =========================================== | ===================================== | ================ | ======== | =============== | ================ | ===== | 
| 2015-02-18T00:00:00 | 2001 | 51914            | 458             | 164                                           | 73     | 758       | 5536         | 1502          | 997             | 9416         | 1489                           | 630         | 1382                  | 2216                               | 2514                                | 83                                      | 1989                              | 440                  | 4546                              | 783                               | 4905                            | 3168                                        | 8865                                  | 2168             | 925      | 5772            | 652              | 5120  | 
| 2015-02-18T00:00:00 | 2002 | 53324            | 425             | 223                                           | 72     | 713       | 5706         | 1506          | 937             | 9572         | 1453                           | 575         | 1301                  | 2347                               | 2766                                | 116                                     | 2090                              | 513                  | 4692                              | 825                               | 4815                            | 3518                                        | 9159                                  | 2275             | 957      | 5927            | 656              | 5271  | 
| 2015-02-18T00:00:00 | 2003 | 54717            | 413             | 148                                           | 64     | 555       | 5414         | 1407          | 1306            | 9905         | 1477                           | 675         | 1497                  | 2587                               | 2695                                | 86                                      | 2444                              | 624                  | 4861                              | 798                               | 4866                            | 3506                                        | 9389                                  | 2288             | 993      | 6108            | 661              | 5447  | 
| 2015-02-18T00:00:00 | 2004 | 56773            | 407             | 154                                           | 74     | 550       | 5736         | 1410          | 1214            | 10097        | 1511                           | 661         | 1475                  | 2967                               | 3134                                | 85                                      | 2671                              | 648                  | 4935                              | 867                               | 5167                            | 3566                                        | 9444                                  | 2251             | 972      | 6221            | 659              | 5562  | 
| 2015-02-18T00:00:00 | 2005 | 58624            | 410             | 147                                           | 81     | 491       | 5878         | 1396          | 1244            | 10538        | 1648                           | 739         | 1558                  | 3348                               | 3319                                | 75                                      | 2662                              | 670                  | 4995                              | 983                               | 5164                            | 3702                                        | 9576                                  | 2172             | 996      | 6408            | 662              | 5746  | 
| 2015-02-18T00:00:00 | 2006 | 60296            | 404             | 170                                           | 76     | 512       | 6180         | 1229          | 1245            | 10741        | 1708                           | 714         | 1615                  | 3415                               | 3479                                | 74                                      | 2776                              | 711                  | 5027                              | 1035                              | 5434                            | 3781                                        | 9970                                  | 2183             | 1013     | 6774            | 659              | 6115  | 
| 2015-02-18T00:00:00 | 2007 | 61283            | 427             | 165                                           | 84     | 532       | 6374         | 1174          | 1074            | 10865        | 1752                           | 712         | 1725                  | 3374                               | 3491                                | 74                                      | 2592                              | 683                  | 5294                              | 1136                              | 5404                            | 4085                                        | 10266                                 | 2175             | 1059     | 7032            | 658              | 6374  | 
| 2015-02-18T00:00:00 | 2008 | 62076            | 420             | 156                                           | 106    | 566       | 6279         | 1041          | 947             | 10898        | 1801                           | 733         | 1725                  | 3375                               | 3563                                | 212                                     | 2871                              | 690                  | 5333                              | 1103                              | 5549                            | 4126                                        | 10583                                 | 2194             | 1103     | 7286            | 665              | 6621  | 
| 2015-02-18T00:00:00 | 2009 | 60450            | 415             | 159                                           | 64     | 539       | 5372         | 1030          | 898             | 10156        | 1723                           | 716         | 1940                  | 3261                               | 3659                                | 215                                     | 2977                              | 670                  | 5617                              | 1061                              | 5243                            | 4136                                        | 10598                                 | 2235             | 1066     | 7297            | 664              | 6633  | 
| 2015-02-18T00:00:00 | 2010 | 60281            | 421             | 184                                           | 19     | 516       | 4709         | 937           | 904             | 10320        | 1630                           | 622         | 1907                  | 3552                               | 3663                                | 315                                     | 2943                              | 687                  | 5805                              | 1141                              | 5203                            | 4169                                        | 10634                                 | 2357             | 1007     | 7270            | 644              | 6626  | 
```