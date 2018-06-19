# Kent County Full and Part Time Jobs By Industry: 2001-2040

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/kent-county-full-and-part-time-jobs-by-industry-2001-2040) |
| Metadata | [Link](https://data.maryland.gov/api/views/hkze-bsv4) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/hkze-bsv4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/hkze-bsv4/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | hkze-bsv4 |
| Name | Kent County Full and Part Time Jobs By Industry: 2001-2040 |
| Attribution | Maryland Department of Planning |
| Category | Planning |
| Tags | full and part time jobs in maryland by industry and by place of work from 2001 to 2040. |
| Created | 2015-02-23T20:51:18Z |
| Publication Date | 2015-02-23T20:53:29Z |

## Description

Full and Part Time Jobs in Kent County by Industry and by Place of Work from 2001 to 2040.

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
series e:hkze-bsv4 d:2015-02-18T00:00:00.000Z m:arts_entertainment_and_recreation=442 m:mining=41 m:manufacturing=1028 m:other_services_except_public_administration=647 m:administrative_and_waste_services=457 m:employment_state=561 m:retail_trade=1144 m:government_and_government_enterprises=1435 m:military=64 m:wholesale_trade=322 m:total_employment=12005 m:utilities=69 m:state_and_local=1297 m:construction=672 m:health_care_and_social_assistance=1429 m:transportation_and_warehousing=196 m:information=116 m:management_of_companies_and_enterprises=117 m:finance_and_insurance=364 m:federal_civilian=74 m:accommodation_and_food_services=899 m:real_estate_and_rental_and_leasing=478 m:professional_and_technical_services=506 m:farm_employment=728 m:educational_services=674 m:forestry_fishing_related_activities_and_other=241 m:local=736

series e:hkze-bsv4 d:2015-02-18T00:00:00.000Z m:arts_entertainment_and_recreation=465 m:mining=31 m:manufacturing=874 m:other_services_except_public_administration=682 m:administrative_and_waste_services=474 m:employment_state=582 m:retail_trade=1108 m:government_and_government_enterprises=1512 m:military=64 m:wholesale_trade=338 m:total_employment=12071 m:utilities=48 m:state_and_local=1367 m:construction=643 m:health_care_and_social_assistance=1496 m:transportation_and_warehousing=172 m:information=100 m:management_of_companies_and_enterprises=102 m:finance_and_insurance=377 m:federal_civilian=81 m:accommodation_and_food_services=829 m:real_estate_and_rental_and_leasing=542 m:professional_and_technical_services=523 m:farm_employment=723 m:educational_services=750 m:forestry_fishing_related_activities_and_other=282 m:local=785

series e:hkze-bsv4 d:2015-02-18T00:00:00.000Z m:arts_entertainment_and_recreation=482 m:mining=26 m:manufacturing=856 m:other_services_except_public_administration=684 m:administrative_and_waste_services=480 m:employment_state=579 m:retail_trade=1098 m:government_and_government_enterprises=1504 m:military=62 m:wholesale_trade=295 m:total_employment=12034 m:utilities=33 m:state_and_local=1363 m:construction=711 m:health_care_and_social_assistance=1520 m:transportation_and_warehousing=138 m:information=99 m:management_of_companies_and_enterprises=77 m:finance_and_insurance=374 m:federal_civilian=79 m:accommodation_and_food_services=807 m:real_estate_and_rental_and_leasing=599 m:professional_and_technical_services=548 m:farm_employment=650 m:educational_services=741 m:forestry_fishing_related_activities_and_other=311 m:local=784
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

entity e:hkze-bsv4 l:"Kent County  Full and Part Time Jobs By Industry: 2001-2040" t:attribution="Maryland Department of Planning" t:url=https://data.maryland.gov/api/views/hkze-bsv4

property e:hkze-bsv4 t:meta.view v:id=hkze-bsv4 v:category=Planning v:attributionLink=http://planning.maryland.gov/msdc/projection/employment/NAICS_Jobs.shtml v:averageRating=0 v:name="Kent County  Full and Part Time Jobs By Industry: 2001-2040" v:attribution="Maryland Department of Planning"

property e:hkze-bsv4 t:meta.view.license v:name="Public Domain"

property e:hkze-bsv4 t:meta.view.owner v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:displayName=MDP

property e:hkze-bsv4 t:meta.view.tableauthor v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:roleName=editor v:displayName=MDP
```

## Top Records

```ls
| date_created        | year | total_employment | farm_employment | forestry_fishing_related_activities_and_other | mining | utilities | construction | manufacturing | wholesale_trade | retail_trade | transportation_and_warehousing | information | finance_and_insurance | real_estate_and_rental_and_leasing | professional_and_technical_services | management_of_companies_and_enterprises | administrative_and_waste_services | educational_services | health_care_and_social_assistance | arts_entertainment_and_recreation | accommodation_and_food_services | other_services_except_public_administration | government_and_government_enterprises | federal_civilian | military | state_and_local | employment_state | local | 
| =================== | ==== | ================ | =============== | ============================================= | ====== | ========= | ============ | ============= | =============== | ============ | ============================== | =========== | ===================== | ================================== | =================================== | ======================================= | ================================= | ==================== | ================================= | ================================= | =============================== | =========================================== | ===================================== | ================ | ======== | =============== | ================ | ===== | 
| 2015-02-18T00:00:00 | 2001 | 12005            | 728             | 241                                           | 41     | 69        | 672          | 1028          | 322             | 1144         | 196                            | 116         | 364                   | 478                                | 506                                 | 117                                     | 457                               | 674                  | 1429                              | 442                               | 899                             | 647                                         | 1435                                  | 74               | 64       | 1297            | 561              | 736   | 
| 2015-02-18T00:00:00 | 2002 | 12071            | 723             | 282                                           | 31     | 48        | 643          | 874           | 338             | 1108         | 172                            | 100         | 377                   | 542                                | 523                                 | 102                                     | 474                               | 750                  | 1496                              | 465                               | 829                             | 682                                         | 1512                                  | 81               | 64       | 1367            | 582              | 785   | 
| 2015-02-18T00:00:00 | 2003 | 12034            | 650             | 311                                           | 26     | 33        | 711          | 856           | 295             | 1098         | 138                            | 99          | 374                   | 599                                | 548                                 | 77                                      | 480                               | 741                  | 1520                              | 482                               | 807                             | 684                                         | 1504                                  | 79               | 62       | 1363            | 579              | 784   | 
| 2015-02-18T00:00:00 | 2004 | 12611            | 642             | 329                                           | 31     | 34        | 758          | 893           | 288             | 1201         | 145                            | 98          | 410                   | 749                                | 579                                 | 85                                      | 506                               | 694                  | 1524                              | 523                               | 913                             | 736                                         | 1473                                  | 80               | 56       | 1337            | 576              | 761   | 
| 2015-02-18T00:00:00 | 2005 | 12974            | 633             | 331                                           | 35     | 38        | 817          | 911           | 342             | 1189         | 159                            | 97          | 441                   | 824                                | 571                                 | 80                                      | 578                               | 695                  | 1602                              | 587                               | 815                             | 786                                         | 1443                                  | 80               | 56       | 1307            | 552              | 755   | 
| 2015-02-18T00:00:00 | 2006 | 13317            | 648             | 374                                           | 31     | 38        | 895          | 942           | 373             | 1194         | 167                            | 97          | 449                   | 817                                | 639                                 | 88                                      | 518                               | 727                  | 1667                              | 577                               | 804                             | 782                                         | 1490                                  | 83               | 54       | 1353            | 562              | 791   | 
| 2015-02-18T00:00:00 | 2007 | 13706            | 650             | 380                                           | 33     | 38        | 907          | 978           | 439             | 1299         | 171                            | 91          | 452                   | 793                                | 672                                 | 88                                      | 489                               | 733                  | 1714                              | 584                               | 899                             | 778                                         | 1518                                  | 82               | 54       | 1382            | 555              | 827   | 
| 2015-02-18T00:00:00 | 2008 | 13262            | 613             | 326                                           | 42     | 31        | 875          | 851           | 468             | 1246         | 154                            | 96          | 434                   | 743                                | 639                                 | 85                                      | 517                               | 737                  | 1711                              | 582                               | 831                             | 769                                         | 1514                                  | 81               | 56       | 1377            | 563              | 814   | 
| 2015-02-18T00:00:00 | 2009 | 12961            | 602             | 307                                           | 41     | 31        | 833          | 781           | 384             | 1191         | 141                            | 113         | 480                   | 715                                | 623                                 | 87                                      | 566                               | 763                  | 1696                              | 569                               | 816                             | 756                                         | 1466                                  | 80               | 55       | 1331            | 543              | 788   | 
| 2015-02-18T00:00:00 | 2010 | 12705            | 636             | 371                                           | 50     | 40        | 725          | 800           | 376             | 1129         | 199                            | 104         | 439                   | 725                                | 620                                 | 113                                     | 441                               | 779                  | 1624                              | 534                               | 866                             | 733                                         | 1401                                  | 87               | 56       | 1258            | 496              | 762   | 
```