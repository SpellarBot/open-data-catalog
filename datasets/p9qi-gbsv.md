# Dorchester County Full and Part Time Jobs By Industry: 2001-2040

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dorchester-county-full-and-part-time-jobs-by-industry-2001-2040) |
| Metadata | [Link](https://data.maryland.gov/api/views/p9qi-gbsv) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/p9qi-gbsv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/p9qi-gbsv/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | p9qi-gbsv |
| Name | Dorchester County Full and Part Time Jobs By Industry: 2001-2040 |
| Attribution | Maryland Department of Planning |
| Category | Planning |
| Tags | full and part time jobs in maryland by industry and by place of work from 2001 to 2040. |
| Created | 2015-02-19T15:49:51Z |
| Publication Date | 2015-02-19T15:52:54Z |

## Description

Full and Part Time Jobs in Dorchester County by Industry and by Place of Work from 2001 to 2040.

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
series e:p9qi-gbsv d:2015-02-18T00:00:00.000Z m:arts_entertainment_and_recreation=211 m:mining=10 m:manufacturing=3210 m:other_services_except_public_administration=915 m:administrative_and_waste_services=462 m:employment_state=887 m:retail_trade=1615 m:government_and_government_enterprises=2381 m:military=116 m:wholesale_trade=496 m:total_employment=16205 m:utilities=49 m:state_and_local=2136 m:construction=925 m:health_care_and_social_assistance=1670 m:transportation_and_warehousing=649 m:information=110 m:management_of_companies_and_enterprises=0 m:finance_and_insurance=408 m:federal_civilian=129 m:accommodation_and_food_services=766 m:real_estate_and_rental_and_leasing=468 m:professional_and_technical_services=385 m:farm_employment=543 m:educational_services=38 m:forestry_fishing_related_activities_and_other=894 m:local=1249

series e:p9qi-gbsv d:2015-02-18T00:00:00.000Z m:arts_entertainment_and_recreation=224 m:mining=7 m:manufacturing=2928 m:other_services_except_public_administration=975 m:administrative_and_waste_services=456 m:employment_state=907 m:retail_trade=1551 m:government_and_government_enterprises=2394 m:military=114 m:wholesale_trade=603 m:total_employment=16019 m:utilities=39 m:state_and_local=2149 m:construction=954 m:health_care_and_social_assistance=1812 m:transportation_and_warehousing=582 m:information=83 m:management_of_companies_and_enterprises=0 m:finance_and_insurance=406 m:federal_civilian=131 m:accommodation_and_food_services=956 m:real_estate_and_rental_and_leasing=454 m:professional_and_technical_services=399 m:farm_employment=530 m:educational_services=79 m:forestry_fishing_related_activities_and_other=587 m:local=1242

series e:p9qi-gbsv d:2015-02-18T00:00:00.000Z m:arts_entertainment_and_recreation=344 m:mining=7 m:manufacturing=2860 m:other_services_except_public_administration=989 m:administrative_and_waste_services=566 m:employment_state=869 m:retail_trade=1542 m:government_and_government_enterprises=2323 m:military=104 m:wholesale_trade=616 m:total_employment=16522 m:utilities=26 m:state_and_local=2088 m:construction=969 m:health_care_and_social_assistance=1895 m:transportation_and_warehousing=464 m:information=94 m:management_of_companies_and_enterprises=0 m:finance_and_insurance=421 m:federal_civilian=131 m:accommodation_and_food_services=1187 m:real_estate_and_rental_and_leasing=511 m:professional_and_technical_services=444 m:farm_employment=495 m:educational_services=83 m:forestry_fishing_related_activities_and_other=686 m:local=1219
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

entity e:p9qi-gbsv l:"Dorchester County Full and Part Time Jobs By Industry: 2001-2040" t:attribution="Maryland Department of Planning" t:url=https://data.maryland.gov/api/views/p9qi-gbsv

property e:p9qi-gbsv t:meta.view v:id=p9qi-gbsv v:category=Planning v:attributionLink=http://planning.maryland.gov/msdc/projection/employment/NAICS_Jobs.shtml v:averageRating=0 v:name="Dorchester County Full and Part Time Jobs By Industry: 2001-2040" v:attribution="Maryland Department of Planning"

property e:p9qi-gbsv t:meta.view.license v:name="Public Domain"

property e:p9qi-gbsv t:meta.view.owner v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:displayName=MDP

property e:p9qi-gbsv t:meta.view.tableauthor v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:roleName=editor v:displayName=MDP
```

## Top Records

```ls
| date_created        | year | total_employment | farm_employment | forestry_fishing_related_activities_and_other | mining | utilities | construction | manufacturing | wholesale_trade | retail_trade | transportation_and_warehousing | information | finance_and_insurance | real_estate_and_rental_and_leasing | professional_and_technical_services | management_of_companies_and_enterprises | administrative_and_waste_services | educational_services | health_care_and_social_assistance | arts_entertainment_and_recreation | accommodation_and_food_services | other_services_except_public_administration | government_and_government_enterprises | federal_civilian | military | state_and_local | employment_state | local | 
| =================== | ==== | ================ | =============== | ============================================= | ====== | ========= | ============ | ============= | =============== | ============ | ============================== | =========== | ===================== | ================================== | =================================== | ======================================= | ================================= | ==================== | ================================= | ================================= | =============================== | =========================================== | ===================================== | ================ | ======== | =============== | ================ | ===== | 
| 2015-02-18T00:00:00 | 2001 | 16205            | 543             | 894                                           | 10     | 49        | 925          | 3210          | 496             | 1615         | 649                            | 110         | 408                   | 468                                | 385                                 | 0                                       | 462                               | 38                   | 1670                              | 211                               | 766                             | 915                                         | 2381                                  | 129              | 116      | 2136            | 887              | 1249  | 
| 2015-02-18T00:00:00 | 2002 | 16019            | 530             | 587                                           | 7      | 39        | 954          | 2928          | 603             | 1551         | 582                            | 83          | 406                   | 454                                | 399                                 | 0                                       | 456                               | 79                   | 1812                              | 224                               | 956                             | 975                                         | 2394                                  | 131              | 114      | 2149            | 907              | 1242  | 
| 2015-02-18T00:00:00 | 2003 | 16522            | 495             | 686                                           | 7      | 26        | 969          | 2860          | 616             | 1542         | 464                            | 94          | 421                   | 511                                | 444                                 | 0                                       | 566                               | 83                   | 1895                              | 344                               | 1187                            | 989                                         | 2323                                  | 131              | 104      | 2088            | 869              | 1219  | 
| 2015-02-18T00:00:00 | 2004 | 16987            | 489             | 762                                           | 9      | 31        | 1090         | 2922          | 567             | 1606         | 539                            | 118         | 451                   | 587                                | 468                                 | 0                                       | 685                               | 69                   | 1718                              | 313                               | 1213                            | 1041                                        | 2308                                  | 130              | 95       | 2083            | 855              | 1228  | 
| 2015-02-18T00:00:00 | 2005 | 17249            | 490             | 739                                           | 9      | 34        | 1131         | 2998          | 520             | 1635         | 537                            | 136         | 482                   | 647                                | 494                                 | 0                                       | 790                               | 72                   | 1695                              | 316                               | 1200                            | 1014                                        | 2310                                  | 132              | 95       | 2083            | 826              | 1257  | 
| 2015-02-18T00:00:00 | 2006 | 17103            | 494             | 705                                           | 6      | 40        | 1192         | 2932          | 510             | 1617         | 577                            | 128         | 486                   | 662                                | 495                                 | 0                                       | 717                               | 69                   | 1514                              | 318                               | 1249                            | 1011                                        | 2381                                  | 133              | 92       | 2156            | 814              | 1342  | 
| 2015-02-18T00:00:00 | 2007 | 17188            | 511             | 682                                           | 8      | 34        | 1227         | 2646          | 544             | 1726         | 586                            | 136         | 450                   | 666                                | 510                                 | 0                                       | 686                               | 97                   | 1655                              | 299                               | 1230                            | 1050                                        | 2444                                  | 137              | 93       | 2214            | 824              | 1390  | 
| 2015-02-18T00:00:00 | 2008 | 16548            | 495             | 783                                           | 12     | 30        | 1145         | 2415          | 389             | 1464         | 608                            | 136         | 495                   | 578                                | 528                                 | 0                                       | 794                               | 105                  | 1423                              | 318                               | 1301                            | 1029                                        | 2510                                  | 185              | 95       | 2230            | 818              | 1412  | 
| 2015-02-18T00:00:00 | 2009 | 16251            | 486             | 816                                           | 13     | 31        | 1015         | 2419          | 543             | 1389         | 524                            | 119         | 538                   | 553                                | 640                                 | 0                                       | 586                               | 94                   | 1523                              | 279                               | 1244                            | 985                                         | 2455                                  | 189              | 95       | 2171            | 783              | 1388  | 
| 2015-02-18T00:00:00 | 2010 | 16033            | 502             | 740                                           | 27     | 31        | 911          | 2328          | 560             | 1363         | 565                            | 104         | 533                   | 571                                | 484                                 | 0                                       | 435                               | 129                  | 1818                              | 236                               | 1244                            | 983                                         | 2470                                  | 213              | 96       | 2161            | 806              | 1355  | 
```