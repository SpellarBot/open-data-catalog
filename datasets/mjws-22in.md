# Washington County Full and Part Time Jobs By Industry: 2001-2040

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/washington-county-full-and-part-time-jobs-by-industry-2001-2040) |
| Metadata | [Link](https://data.maryland.gov/api/views/mjws-22in) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/mjws-22in/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/mjws-22in/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | mjws-22in |
| Name | Washington County Full and Part Time Jobs By Industry: 2001-2040 |
| Attribution | Maryland Department of Planning |
| Category | Planning |
| Tags | full and part time jobs in maryland by industry and by place of work from 2001 to 2040. |
| Created | 2015-02-23T21:42:58Z |
| Publication Date | 2015-02-23T21:49:46Z |

## Description

Full and Part Time Jobs in Washington County by Industry and by Place of Work from 2001 to 2040.

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
series e:mjws-22in d:2015-02-18T00:00:00.000Z m:arts_entertainment_and_recreation=919 m:mining=88 m:manufacturing=10127 m:other_services_except_public_administration=3956 m:administrative_and_waste_services=2595 m:employment_state=2860 m:retail_trade=10314 m:government_and_government_enterprises=8511 m:military=467 m:wholesale_trade=2666 m:total_employment=76089 m:utilities=527 m:state_and_local=7474 m:construction=4836 m:health_care_and_social_assistance=8931 m:transportation_and_warehousing=3827 m:information=1111 m:management_of_companies_and_enterprises=351 m:finance_and_insurance=6702 m:federal_civilian=570 m:accommodation_and_food_services=4712 m:real_estate_and_rental_and_leasing=1198 m:professional_and_technical_services=2748 m:farm_employment=1124 m:educational_services=630 m:forestry_fishing_related_activities_and_other=216 m:local=4614

series e:mjws-22in d:2015-02-18T00:00:00.000Z m:arts_entertainment_and_recreation=938 m:mining=69 m:manufacturing=9601 m:other_services_except_public_administration=4025 m:administrative_and_waste_services=2519 m:employment_state=2883 m:retail_trade=10776 m:government_and_government_enterprises=8727 m:military=461 m:wholesale_trade=2363 m:total_employment=75711 m:utilities=468 m:state_and_local=7630 m:construction=4866 m:health_care_and_social_assistance=9346 m:transportation_and_warehousing=3660 m:information=1431 m:management_of_companies_and_enterprises=327 m:finance_and_insurance=6168 m:federal_civilian=636 m:accommodation_and_food_services=4555 m:real_estate_and_rental_and_leasing=1320 m:professional_and_technical_services=2455 m:farm_employment=1088 m:educational_services=728 m:forestry_fishing_related_activities_and_other=281 m:local=4747

series e:mjws-22in d:2015-02-18T00:00:00.000Z m:arts_entertainment_and_recreation=1010 m:mining=72 m:manufacturing=9273 m:other_services_except_public_administration=4129 m:administrative_and_waste_services=2603 m:employment_state=2846 m:retail_trade=10971 m:government_and_government_enterprises=8667 m:military=464 m:wholesale_trade=2310 m:total_employment=75932 m:utilities=324 m:state_and_local=7587 m:construction=5013 m:health_care_and_social_assistance=9536 m:transportation_and_warehousing=3520 m:information=1470 m:management_of_companies_and_enterprises=318 m:finance_and_insurance=6131 m:federal_civilian=616 m:accommodation_and_food_services=4689 m:real_estate_and_rental_and_leasing=1423 m:professional_and_technical_services=2506 m:farm_employment=1019 m:educational_services=772 m:forestry_fishing_related_activities_and_other=176 m:local=4741
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

entity e:mjws-22in l:"Washington County Full and Part Time Jobs By Industry: 2001-2040" t:attribution="Maryland Department of Planning" t:url=https://data.maryland.gov/api/views/mjws-22in

property e:mjws-22in t:meta.view v:id=mjws-22in v:category=Planning v:attributionLink=http://planning.maryland.gov/msdc/projection/employment/NAICS_Jobs.shtml v:averageRating=0 v:name="Washington County Full and Part Time Jobs By Industry: 2001-2040" v:attribution="Maryland Department of Planning"

property e:mjws-22in t:meta.view.license v:name="Public Domain"

property e:mjws-22in t:meta.view.owner v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:displayName=MDP

property e:mjws-22in t:meta.view.tableauthor v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:roleName=editor v:displayName=MDP
```

## Top Records

```ls
| date_created        | year | total_employment | farm_employment | forestry_fishing_related_activities_and_other | mining | utilities | construction | manufacturing | wholesale_trade | retail_trade | transportation_and_warehousing | information | finance_and_insurance | real_estate_and_rental_and_leasing | professional_and_technical_services | management_of_companies_and_enterprises | administrative_and_waste_services | educational_services | health_care_and_social_assistance | arts_entertainment_and_recreation | accommodation_and_food_services | other_services_except_public_administration | government_and_government_enterprises | federal_civilian | military | state_and_local | employment_state | local | 
| =================== | ==== | ================ | =============== | ============================================= | ====== | ========= | ============ | ============= | =============== | ============ | ============================== | =========== | ===================== | ================================== | =================================== | ======================================= | ================================= | ==================== | ================================= | ================================= | =============================== | =========================================== | ===================================== | ================ | ======== | =============== | ================ | ===== | 
| 2015-02-18T00:00:00 | 2001 | 76089            | 1124            | 216                                           | 88     | 527       | 4836         | 10127         | 2666            | 10314        | 3827                           | 1111        | 6702                  | 1198                               | 2748                                | 351                                     | 2595                              | 630                  | 8931                              | 919                               | 4712                            | 3956                                        | 8511                                  | 570              | 467      | 7474            | 2860             | 4614  | 
| 2015-02-18T00:00:00 | 2002 | 75711            | 1088            | 281                                           | 69     | 468       | 4866         | 9601          | 2363            | 10776        | 3660                           | 1431        | 6168                  | 1320                               | 2455                                | 327                                     | 2519                              | 728                  | 9346                              | 938                               | 4555                            | 4025                                        | 8727                                  | 636              | 461      | 7630            | 2883             | 4747  | 
| 2015-02-18T00:00:00 | 2003 | 75932            | 1019            | 176                                           | 72     | 324       | 5013         | 9273          | 2310            | 10971        | 3520                           | 1470        | 6131                  | 1423                               | 2506                                | 318                                     | 2603                              | 772                  | 9536                              | 1010                              | 4689                            | 4129                                        | 8667                                  | 616              | 464      | 7587            | 2846             | 4741  | 
| 2015-02-18T00:00:00 | 2004 | 76267            | 1002            | 159                                           | 72     | 274       | 5359         | 9474          | 2089            | 10504        | 3535                           | 1571        | 6148                  | 1535                               | 2615                                | 341                                     | 2683                              | 777                  | 9402                              | 1183                              | 4926                            | 3969                                        | 8649                                  | 614              | 424      | 7611            | 2681             | 4930  | 
| 2015-02-18T00:00:00 | 2005 | 78543            | 999             | 125                                           | 65     | 235       | 5801         | 9076          | 2147            | 11343        | 3927                           | 1625        | 6382                  | 1700                               | 2423                                | 354                                     | 3081                              | 770                  | 9329                              | 1210                              | 5209                            | 3958                                        | 8785                                  | 653              | 428      | 7704            | 2570             | 5134  | 
| 2015-02-18T00:00:00 | 2006 | 79823            | 1002            | 148                                           | 81     | 258       | 6067         | 8342          | 2203            | 11943        | 4149                           | 1690        | 6403                  | 1706                               | 2639                                | 362                                     | 3010                              | 788                  | 9610                              | 1248                              | 5152                            | 4012                                        | 9010                                  | 641              | 417      | 7952            | 2643             | 5309  | 
| 2015-02-18T00:00:00 | 2007 | 80372            | 1040            | 102                                           | 86     | 280       | 5711         | 7672          | 2268            | 11976        | 4213                           | 1685        | 6501                  | 1642                               | 2848                                | 351                                     | 3137                              | 827                  | 9865                              | 1224                              | 5456                            | 4196                                        | 9292                                  | 641              | 420      | 8231            | 2670             | 5561  | 
| 2015-02-18T00:00:00 | 2008 | 80472            | 1003            | 157                                           | 123    | 267       | 5225         | 7546          | 1941            | 12195        | 4111                           | 1716        | 6561                  | 1817                               | 2959                                | 355                                     | 3152                              | 827                  | 10309                             | 1293                              | 5408                            | 4008                                        | 9500                                  | 688              | 428      | 8384            | 2703             | 5681  | 
| 2015-02-18T00:00:00 | 2009 | 77876            | 990             | 94                                            | 87     | 224       | 4637         | 6876          | 1887            | 11886        | 3793                           | 1658        | 6149                  | 1778                               | 2911                                | 318                                     | 3067                              | 884                  | 10294                             | 1324                              | 5444                            | 3925                                        | 9650                                  | 721              | 426      | 8503            | 2664             | 5839  | 
| 2015-02-18T00:00:00 | 2010 | 77353            | 1018            | 98                                            | 82     | 231       | 4161         | 6612          | 2093            | 11828        | 3787                           | 1052        | 6191                  | 1798                               | 2592                                | 326                                     | 3785                              | 859                  | 10401                             | 1380                              | 5471                            | 3815                                        | 9773                                  | 769              | 433      | 8571            | 2663             | 5908  | 
```