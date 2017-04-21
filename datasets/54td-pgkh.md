# Carroll County Full and Part Time Jobs By Industry: 2001-2040

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/carroll-county-full-and-part-time-jobs-by-industry-2001-2040) |
| Metadata | [Link](https://data.maryland.gov/api/views/54td-pgkh) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/54td-pgkh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/54td-pgkh/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | 54td-pgkh |
| Name | Carroll County Full and Part Time Jobs By Industry: 2001-2040 |
| Attribution | Maryland Department of Planning |
| Category | Planning |
| Tags | full and part time jobs in maryland by industry and by place of work from 2001 to 2040. |
| Created | 2015-02-18T21:18:40Z |
| Publication Date | 2015-02-18T23:00:07Z |

## Description

Full and Part Time Jobs in Carroll County by Industry and by Place of Work from 2001 to 2040.

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
series e:54td-pgkh d:2015-02-18T00:00:00.000Z m:arts_entertainment_and_recreation=1386 m:mining=90 m:manufacturing=5559 m:other_services_except_public_administration=4802 m:administrative_and_waste_services=3676 m:employment_state=1274 m:retail_trade=9038 m:government_and_government_enterprises=7579 m:military=533 m:wholesale_trade=3249 m:total_employment=70528 m:utilities=88 m:state_and_local=6737 m:construction=9386 m:health_care_and_social_assistance=7119 m:transportation_and_warehousing=1713 m:information=862 m:management_of_companies_and_enterprises=167 m:finance_and_insurance=2259 m:federal_civilian=309 m:accommodation_and_food_services=4372 m:real_estate_and_rental_and_leasing=2613 m:professional_and_technical_services=3540 m:farm_employment=1561 m:educational_services=1267 m:forestry_fishing_related_activities_and_other=202 m:local=5463

series e:54td-pgkh d:2015-02-18T00:00:00.000Z m:arts_entertainment_and_recreation=1522 m:mining=95 m:manufacturing=5072 m:other_services_except_public_administration=5040 m:administrative_and_waste_services=3810 m:employment_state=1256 m:retail_trade=9674 m:government_and_government_enterprises=7738 m:military=548 m:wholesale_trade=3235 m:total_employment=72451 m:utilities=82 m:state_and_local=6869 m:construction=9282 m:health_care_and_social_assistance=7487 m:transportation_and_warehousing=1840 m:information=771 m:management_of_companies_and_enterprises=184 m:finance_and_insurance=2292 m:federal_civilian=321 m:accommodation_and_food_services=4685 m:real_estate_and_rental_and_leasing=2733 m:professional_and_technical_services=3755 m:farm_employment=1524 m:educational_services=1346 m:forestry_fishing_related_activities_and_other=284 m:local=5613

series e:54td-pgkh d:2015-02-18T00:00:00.000Z m:arts_entertainment_and_recreation=1594 m:mining=100 m:manufacturing=4922 m:other_services_except_public_administration=5151 m:administrative_and_waste_services=4124 m:employment_state=1277 m:retail_trade=9703 m:government_and_government_enterprises=8002 m:military=554 m:wholesale_trade=2983 m:total_employment=74034 m:utilities=73 m:state_and_local=7132 m:construction=9426 m:health_care_and_social_assistance=7782 m:transportation_and_warehousing=1777 m:information=865 m:management_of_companies_and_enterprises=167 m:finance_and_insurance=2377 m:federal_civilian=316 m:accommodation_and_food_services=4935 m:real_estate_and_rental_and_leasing=3027 m:professional_and_technical_services=3975 m:farm_employment=1414 m:educational_services=1406 m:forestry_fishing_related_activities_and_other=231 m:local=5855
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

entity e:54td-pgkh l:"Carroll County Full and Part Time Jobs By Industry: 2001-2040" t:attribution="Maryland Department of Planning" t:url=https://data.maryland.gov/api/views/54td-pgkh

property e:54td-pgkh t:meta.view v:id=54td-pgkh v:category=Planning v:attributionLink=http://planning.maryland.gov/msdc/projection/employment/NAICS_Jobs.shtml v:averageRating=0 v:name="Carroll County Full and Part Time Jobs By Industry: 2001-2040" v:attribution="Maryland Department of Planning"

property e:54td-pgkh t:meta.view.license v:name="Public Domain"

property e:54td-pgkh t:meta.view.owner v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:displayName=MDP

property e:54td-pgkh t:meta.view.tableauthor v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:roleName=editor v:displayName=MDP
```

## Top Records

```ls
| date_created        | year | total_employment | farm_employment | forestry_fishing_related_activities_and_other | mining | utilities | construction | manufacturing | wholesale_trade | retail_trade | transportation_and_warehousing | information | finance_and_insurance | real_estate_and_rental_and_leasing | professional_and_technical_services | management_of_companies_and_enterprises | administrative_and_waste_services | educational_services | health_care_and_social_assistance | arts_entertainment_and_recreation | accommodation_and_food_services | other_services_except_public_administration | government_and_government_enterprises | federal_civilian | military | state_and_local | employment_state | local | 
| =================== | ==== | ================ | =============== | ============================================= | ====== | ========= | ============ | ============= | =============== | ============ | ============================== | =========== | ===================== | ================================== | =================================== | ======================================= | ================================= | ==================== | ================================= | ================================= | =============================== | =========================================== | ===================================== | ================ | ======== | =============== | ================ | ===== | 
| 2015-02-18T00:00:00 | 2001 | 70528            | 1561            | 202                                           | 90     | 88        | 9386         | 5559          | 3249            | 9038         | 1713                           | 862         | 2259                  | 2613                               | 3540                                | 167                                     | 3676                              | 1267                 | 7119                              | 1386                              | 4372                            | 4802                                        | 7579                                  | 309              | 533      | 6737            | 1274             | 5463  | 
| 2015-02-18T00:00:00 | 2002 | 72451            | 1524            | 284                                           | 95     | 82        | 9282         | 5072          | 3235            | 9674         | 1840                           | 771         | 2292                  | 2733                               | 3755                                | 184                                     | 3810                              | 1346                 | 7487                              | 1522                              | 4685                            | 5040                                        | 7738                                  | 321              | 548      | 6869            | 1256             | 5613  | 
| 2015-02-18T00:00:00 | 2003 | 74034            | 1414            | 231                                           | 100    | 73        | 9426         | 4922          | 2983            | 9703         | 1777                           | 865         | 2377                  | 3027                               | 3975                                | 167                                     | 4124                              | 1406                 | 7782                              | 1594                              | 4935                            | 5151                                        | 8002                                  | 316              | 554      | 7132            | 1277             | 5855  | 
| 2015-02-18T00:00:00 | 2004 | 76985            | 1381            | 269                                           | 130    | 74        | 10092        | 4889          | 2963            | 9847         | 1740                           | 933         | 2381                  | 3412                               | 4412                                | 161                                     | 4553                              | 1424                 | 7944                              | 1769                              | 5081                            | 5371                                        | 8159                                  | 315              | 503      | 7341            | 1313             | 6028  | 
| 2015-02-18T00:00:00 | 2005 | 80574            | 1369            | 260                                           | 143    | 77        | 10758        | 5041          | 3178            | 10199        | 1772                           | 913         | 2457                  | 3882                               | 4452                                | 439                                     | 4681                              | 1514                 | 8324                              | 1863                              | 5216                            | 5591                                        | 8445                                  | 320              | 502      | 7623            | 1345             | 6278  | 
| 2015-02-18T00:00:00 | 2006 | 82742            | 1361            | 296                                           | 133    | 66        | 11090        | 5180          | 3224            | 10255        | 1881                           | 893         | 2514                  | 4205                               | 4528                                | 403                                     | 4799                              | 1583                 | 8829                              | 1896                              | 5338                            | 5623                                        | 8645                                  | 323              | 486      | 7836            | 1341             | 6495  | 
| 2015-02-18T00:00:00 | 2007 | 84816            | 1403            | 299                                           | 154    | 82        | 10239        | 5094          | 3168            | 11015        | 2009                           | 910         | 2666                  | 4463                               | 4814                                | 413                                     | 5140                              | 1597                 | 9391                              | 1945                              | 5514                            | 5664                                        | 8836                                  | 327              | 488      | 8021            | 1352             | 6669  | 
| 2015-02-18T00:00:00 | 2008 | 85419            | 1356            | 287                                           | 193    | 100       | 9576         | 5119          | 3011            | 11066        | 1914                           | 908         | 2771                  | 4366                               | 5157                                | 473                                     | 5652                              | 1717                 | 9458                              | 2011                              | 5635                            | 5570                                        | 9084                                  | 326              | 494      | 8264            | 1348             | 6916  | 
| 2015-02-18T00:00:00 | 2009 | 82611            | 1340            | 365                                           | 243    | 89        | 8357         | 4671          | 2836            | 10715        | 1926                           | 874         | 3109                  | 4200                               | 5048                                | 470                                     | 5466                              | 1720                 | 9420                              | 1825                              | 5551                            | 5392                                        | 8994                                  | 318              | 488      | 8188            | 1308             | 6880  | 
| 2015-02-18T00:00:00 | 2010 | 81611            | 1376            | 291                                           | 484    | 69        | 8085         | 4437          | 2785            | 10141        | 1858                           | 876         | 2927                  | 4327                               | 5744                                | 527                                     | 5226                              | 1733                 | 9601                              | 1780                              | 5363                            | 5189                                        | 8792                                  | 344              | 493      | 7955            | 1278             | 6677  | 
```