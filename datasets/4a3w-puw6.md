# Queen Anne's County Full and Part Time Jobs By Industry: 2001-2040

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/queen-annes-county-full-and-part-time-jobs-by-industry-2001-2040) |
| Metadata | [Link](https://data.maryland.gov/api/views/4a3w-puw6) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/4a3w-puw6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/4a3w-puw6/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | 4a3w-puw6 |
| Name | Queen Anne's County Full and Part Time Jobs By Industry: 2001-2040 |
| Attribution | Maryland Department of Planning |
| Category | Planning |
| Tags | full and part time jobs in maryland by industry and by place of work from 2001 to 2040. |
| Created | 2015-02-23T21:08:02Z |
| Publication Date | 2015-02-23T21:11:13Z |

## Description

Full and Part Time Jobs in Queen Anne's County by Industry and by Place of Work from 2001 to 2040.

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
series e:4a3w-puw6 d:2015-02-18T00:00:00.000Z m:arts_entertainment_and_recreation=477 m:mining=10 m:manufacturing=1085 m:other_services_except_public_administration=1142 m:administrative_and_waste_services=673 m:employment_state=369 m:retail_trade=2654 m:government_and_government_enterprises=2417 m:military=143 m:wholesale_trade=724 m:total_employment=18189 m:utilities=83 m:state_and_local=2191 m:construction=1790 m:health_care_and_social_assistance=596 m:transportation_and_warehousing=563 m:information=169 m:management_of_companies_and_enterprises=124 m:finance_and_insurance=499 m:federal_civilian=83 m:accommodation_and_food_services=1749 m:real_estate_and_rental_and_leasing=1259 m:professional_and_technical_services=1071 m:farm_employment=714 m:educational_services=60 m:forestry_fishing_related_activities_and_other=330 m:local=1822

series e:4a3w-puw6 d:2015-02-18T00:00:00.000Z m:arts_entertainment_and_recreation=641 m:mining=6 m:manufacturing=1093 m:other_services_except_public_administration=1216 m:administrative_and_waste_services=730 m:employment_state=372 m:retail_trade=2715 m:government_and_government_enterprises=2552 m:military=147 m:wholesale_trade=728 m:total_employment=18961 m:utilities=53 m:state_and_local=2311 m:construction=1822 m:health_care_and_social_assistance=809 m:transportation_and_warehousing=415 m:information=167 m:management_of_companies_and_enterprises=137 m:finance_and_insurance=492 m:federal_civilian=94 m:accommodation_and_food_services=1835 m:real_estate_and_rental_and_leasing=1197 m:professional_and_technical_services=1090 m:farm_employment=707 m:educational_services=156 m:forestry_fishing_related_activities_and_other=400 m:local=1939

series e:4a3w-puw6 d:2015-02-18T00:00:00.000Z m:arts_entertainment_and_recreation=638 m:mining=10 m:manufacturing=1005 m:other_services_except_public_administration=1291 m:administrative_and_waste_services=870 m:employment_state=371 m:retail_trade=2790 m:government_and_government_enterprises=2623 m:military=151 m:wholesale_trade=821 m:total_employment=19895 m:utilities=57 m:state_and_local=2381 m:construction=1994 m:health_care_and_social_assistance=842 m:transportation_and_warehousing=474 m:information=220 m:management_of_companies_and_enterprises=122 m:finance_and_insurance=504 m:federal_civilian=91 m:accommodation_and_food_services=1982 m:real_estate_and_rental_and_leasing=1362 m:professional_and_technical_services=1148 m:farm_employment=643 m:educational_services=170 m:forestry_fishing_related_activities_and_other=329 m:local=2010
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

entity e:4a3w-puw6 l:"Queen Anne's County Full and Part Time Jobs By Industry: 2001-2040" t:attribution="Maryland Department of Planning" t:url=https://data.maryland.gov/api/views/4a3w-puw6

property e:4a3w-puw6 t:meta.view v:id=4a3w-puw6 v:category=Planning v:attributionLink=http://planning.maryland.gov/msdc/projection/employment/NAICS_Jobs.shtml v:averageRating=0 v:name="Queen Anne's County Full and Part Time Jobs By Industry: 2001-2040" v:attribution="Maryland Department of Planning"

property e:4a3w-puw6 t:meta.view.license v:name="Public Domain"

property e:4a3w-puw6 t:meta.view.owner v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:displayName=MDP

property e:4a3w-puw6 t:meta.view.tableauthor v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:roleName=editor v:displayName=MDP
```

## Top Records

```ls
| date_created        | year | total_employment | farm_employment | forestry_fishing_related_activities_and_other | mining | utilities | construction | manufacturing | wholesale_trade | retail_trade | transportation_and_warehousing | information | finance_and_insurance | real_estate_and_rental_and_leasing | professional_and_technical_services | management_of_companies_and_enterprises | administrative_and_waste_services | educational_services | health_care_and_social_assistance | arts_entertainment_and_recreation | accommodation_and_food_services | other_services_except_public_administration | government_and_government_enterprises | federal_civilian | military | state_and_local | employment_state | local | 
| =================== | ==== | ================ | =============== | ============================================= | ====== | ========= | ============ | ============= | =============== | ============ | ============================== | =========== | ===================== | ================================== | =================================== | ======================================= | ================================= | ==================== | ================================= | ================================= | =============================== | =========================================== | ===================================== | ================ | ======== | =============== | ================ | ===== | 
| 2015-02-18T00:00:00 | 2001 | 18189            | 714             | 330                                           | 10     | 83        | 1790         | 1085          | 724             | 2654         | 563                            | 169         | 499                   | 1259                               | 1071                                | 124                                     | 673                               | 60                   | 596                               | 477                               | 1749                            | 1142                                        | 2417                                  | 83               | 143      | 2191            | 369              | 1822  | 
| 2015-02-18T00:00:00 | 2002 | 18961            | 707             | 400                                           | 6      | 53        | 1822         | 1093          | 728             | 2715         | 415                            | 167         | 492                   | 1197                               | 1090                                | 137                                     | 730                               | 156                  | 809                               | 641                               | 1835                            | 1216                                        | 2552                                  | 94               | 147      | 2311            | 372              | 1939  | 
| 2015-02-18T00:00:00 | 2003 | 19895            | 643             | 329                                           | 10     | 57        | 1994         | 1005          | 821             | 2790         | 474                            | 220         | 504                   | 1362                               | 1148                                | 122                                     | 870                               | 170                  | 842                               | 638                               | 1982                            | 1291                                        | 2623                                  | 91               | 151      | 2381            | 371              | 2010  | 
| 2015-02-18T00:00:00 | 2004 | 20664            | 628             | 368                                           | 8      | 57        | 2258         | 912           | 923             | 2773         | 519                            | 215         | 539                   | 1348                               | 1256                                | 129                                     | 883                               | 152                  | 912                               | 623                               | 2196                            | 1329                                        | 2636                                  | 89               | 137      | 2410            | 370              | 2040  | 
| 2015-02-18T00:00:00 | 2005 | 21232            | 619             | 392                                           | 8      | 57        | 2421         | 956           | 918             | 2583         | 498                            | 200         | 605                   | 1581                               | 1335                                | 107                                     | 883                               | 164                  | 1100                              | 576                               | 2111                            | 1400                                        | 2717                                  | 88               | 136      | 2493            | 369              | 2124  | 
| 2015-02-18T00:00:00 | 2006 | 22064            | 615             | 358                                           | 27     | 64        | 2438         | 965           | 939             | 2779         | 566                            | 200         | 615                   | 1682                               | 1377                                | 127                                     | 862                               | 181                  | 1211                              | 598                               | 2156                            | 1532                                        | 2772                                  | 92               | 133      | 2547            | 367              | 2180  | 
| 2015-02-18T00:00:00 | 2007 | 23113            | 625             | 364                                           | 19     | 51        | 2384         | 946           | 963             | 3166         | 477                            | 237         | 692                   | 1855                               | 1509                                | 100                                     | 1116                              | 184                  | 1221                              | 715                               | 2114                            | 1504                                        | 2872                                  | 94               | 136      | 2642            | 369              | 2273  | 
| 2015-02-18T00:00:00 | 2008 | 22927            | 608             | 372                                           | 25     | 50        | 2222         | 882           | 1017            | 3030         | 472                            | 244         | 785                   | 1697                               | 1534                                | 174                                     | 1094                              | 198                  | 1273                              | 682                               | 2195                            | 1470                                        | 2899                                  | 97               | 139      | 2663            | 371              | 2292  | 
| 2015-02-18T00:00:00 | 2009 | 22095            | 599             | 389                                           | 26     | 51        | 1938         | 856           | 965             | 2739         | 399                            | 234         | 878                   | 1506                               | 1461                                | 169                                     | 1073                              | 206                  | 1317                              | 713                               | 2172                            | 1426                                        | 2978                                  | 97               | 140      | 2741            | 365              | 2376  | 
| 2015-02-18T00:00:00 | 2010 | 21964            | 617             | 376                                           | 58     | 54        | 1842         | 832           | 960             | 2691         | 425                            | 190         | 818                   | 1537                               | 1454                                | 240                                     | 1038                              | 217                  | 1352                              | 731                               | 2169                            | 1421                                        | 2942                                  | 107              | 141      | 2694            | 354              | 2340  | 
```