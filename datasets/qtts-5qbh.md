# Calvert County Full and Part Time Jobs By Industry: 2001-2040

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/calvert-county-full-and-part-time-jobs-by-industry-2001-2040) |
| Metadata | [Link](https://data.maryland.gov/api/views/qtts-5qbh) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/qtts-5qbh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/qtts-5qbh/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | qtts-5qbh |
| Name | Calvert County Full and Part Time Jobs By Industry: 2001-2040 |
| Attribution | Maryland Department of Planning |
| Category | Planning |
| Tags | full and part time jobs in maryland by industry and by place of work from 2001 to 2040. |
| Created | 2015-02-18T20:42:02Z |
| Publication Date | 2015-02-18T20:47:52Z |

## Description

Full and Part Time Jobs in Calvert County by Industry and by Place of Work from 2001 to 2040.

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
series e:qtts-5qbh d:2015-02-18T00:00:00.000Z m:arts_entertainment_and_recreation=598 m:mining=10 m:manufacturing=869 m:other_services_except_public_administration=2065 m:administrative_and_waste_services=1139 m:employment_state=248 m:retail_trade=3341 m:government_and_government_enterprises=3637 m:military=319 m:wholesale_trade=251 m:total_employment=27312 m:utilities=1429 m:state_and_local=3203 m:construction=3025 m:health_care_and_social_assistance=3297 m:transportation_and_warehousing=770 m:information=223 m:management_of_companies_and_enterprises=222 m:finance_and_insurance=451 m:federal_civilian=115 m:accommodation_and_food_services=2341 m:real_estate_and_rental_and_leasing=1285 m:professional_and_technical_services=1627 m:farm_employment=387 m:educational_services=219 m:forestry_fishing_related_activities_and_other=126 m:local=2955

series e:qtts-5qbh d:2015-02-18T00:00:00.000Z m:arts_entertainment_and_recreation=633 m:mining=8 m:manufacturing=828 m:other_services_except_public_administration=2347 m:administrative_and_waste_services=1538 m:employment_state=215 m:retail_trade=3438 m:government_and_government_enterprises=3819 m:military=324 m:wholesale_trade=229 m:total_employment=28960 m:utilities=1273 m:state_and_local=3379 m:construction=3247 m:health_care_and_social_assistance=3365 m:transportation_and_warehousing=810 m:information=171 m:management_of_companies_and_enterprises=255 m:finance_and_insurance=497 m:federal_civilian=116 m:accommodation_and_food_services=2522 m:real_estate_and_rental_and_leasing=1372 m:professional_and_technical_services=1827 m:farm_employment=360 m:educational_services=235 m:forestry_fishing_related_activities_and_other=186 m:local=3164

series e:qtts-5qbh d:2015-02-18T00:00:00.000Z m:arts_entertainment_and_recreation=724 m:mining=10 m:manufacturing=828 m:other_services_except_public_administration=2484 m:administrative_and_waste_services=1826 m:employment_state=224 m:retail_trade=3447 m:government_and_government_enterprises=3984 m:military=334 m:wholesale_trade=272 m:total_employment=30252 m:utilities=1086 m:state_and_local=3528 m:construction=3606 m:health_care_and_social_assistance=3476 m:transportation_and_warehousing=829 m:information=259 m:management_of_companies_and_enterprises=225 m:finance_and_insurance=539 m:federal_civilian=122 m:accommodation_and_food_services=2598 m:real_estate_and_rental_and_leasing=1522 m:professional_and_technical_services=1822 m:farm_employment=328 m:educational_services=254 m:forestry_fishing_related_activities_and_other=132 m:local=3304
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

entity e:qtts-5qbh l:"Calvert County Full and Part Time Jobs By Industry: 2001-2040" t:attribution="Maryland Department of Planning" t:url=https://data.maryland.gov/api/views/qtts-5qbh

property e:qtts-5qbh t:meta.view v:id=qtts-5qbh v:category=Planning v:attributionLink=http://planning.maryland.gov/msdc/projection/employment/NAICS_Jobs.shtml v:averageRating=0 v:name="Calvert County Full and Part Time Jobs By Industry: 2001-2040" v:attribution="Maryland Department of Planning"

property e:qtts-5qbh t:meta.view.license v:name="Public Domain"

property e:qtts-5qbh t:meta.view.owner v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:displayName=MDP

property e:qtts-5qbh t:meta.view.tableauthor v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:roleName=editor v:displayName=MDP
```

## Top Records

```ls
| date_created        | year | total_employment | farm_employment | forestry_fishing_related_activities_and_other | mining | utilities | construction | manufacturing | wholesale_trade | retail_trade | transportation_and_warehousing | information | finance_and_insurance | real_estate_and_rental_and_leasing | professional_and_technical_services | management_of_companies_and_enterprises | administrative_and_waste_services | educational_services | health_care_and_social_assistance | arts_entertainment_and_recreation | accommodation_and_food_services | other_services_except_public_administration | government_and_government_enterprises | federal_civilian | military | state_and_local | employment_state | local | 
| =================== | ==== | ================ | =============== | ============================================= | ====== | ========= | ============ | ============= | =============== | ============ | ============================== | =========== | ===================== | ================================== | =================================== | ======================================= | ================================= | ==================== | ================================= | ================================= | =============================== | =========================================== | ===================================== | ================ | ======== | =============== | ================ | ===== | 
| 2015-02-18T00:00:00 | 2001 | 27312            | 387             | 126                                           | 10     | 1429      | 3025         | 869           | 251             | 3341         | 770                            | 223         | 451                   | 1285                               | 1627                                | 222                                     | 1139                              | 219                  | 3297                              | 598                               | 2341                            | 2065                                        | 3637                                  | 115              | 319      | 3203            | 248              | 2955  | 
| 2015-02-18T00:00:00 | 2002 | 28960            | 360             | 186                                           | 8      | 1273      | 3247         | 828           | 229             | 3438         | 810                            | 171         | 497                   | 1372                               | 1827                                | 255                                     | 1538                              | 235                  | 3365                              | 633                               | 2522                            | 2347                                        | 3819                                  | 116              | 324      | 3379            | 215              | 3164  | 
| 2015-02-18T00:00:00 | 2003 | 30252            | 328             | 132                                           | 10     | 1086      | 3606         | 828           | 272             | 3447         | 829                            | 259         | 539                   | 1522                               | 1822                                | 225                                     | 1826                              | 254                  | 3476                              | 724                               | 2598                            | 2484                                        | 3984                                  | 122              | 334      | 3528            | 224              | 3304  | 
| 2015-02-18T00:00:00 | 2004 | 31592            | 310             | 128                                           | 7      | 1216      | 3810         | 849           | 383             | 3712         | 957                            | 421         | 617                   | 1770                               | 1846                                | 194                                     | 1519                              | 270                  | 3588                              | 837                               | 2683                            | 2442                                        | 4034                                  | 124              | 310      | 3600            | 252              | 3348  | 
| 2015-02-18T00:00:00 | 2005 | 32194            | 299             | 115                                           | 7      | 1164      | 3843         | 857           | 451             | 3833         | 872                            | 458         | 743                   | 1987                               | 1844                                | 166                                     | 1563                              | 293                  | 3642                              | 839                               | 2596                            | 2461                                        | 4161                                  | 139              | 306      | 3716            | 252              | 3464  | 
| 2015-02-18T00:00:00 | 2006 | 33356            | 283             | 149                                           | 7      | 1086      | 4012         | 884           | 484             | 4008         | 846                            | 453         | 720                   | 2161                               | 1953                                | 207                                     | 1601                              | 336                  | 3805                              | 843                               | 2619                            | 2649                                        | 4250                                  | 149              | 297      | 3804            | 274              | 3530  | 
| 2015-02-18T00:00:00 | 2007 | 34525            | 286             | 182                                           | 10     | 1049      | 3935         | 935           | 478             | 4162         | 818                            | 450         | 794                   | 2272                               | 2095                                | 258                                     | 1599                              | 345                  | 4030                              | 862                               | 2785                            | 2849                                        | 4332                                  | 156              | 299      | 3877            | 281              | 3596  | 
| 2015-02-18T00:00:00 | 2008 | 34191            | 282             | 134                                           | 30     | 1016      | 3760         | 868           | 455             | 3993         | 755                            | 293         | 863                   | 2150                               | 2223                                | 208                                     | 1642                              | 356                  | 4115                              | 931                               | 2909                            | 2735                                        | 4460                                  | 154              | 302      | 4004            | 279              | 3725  | 
| 2015-02-18T00:00:00 | 2009 | 33164            | 279             | 128                                           | 52     | 1075      | 3207         | 770           | 461             | 3878         | 672                            | 257         | 879                   | 2145                               | 2174                                | 97                                      | 1756                              | 331                  | 4249                              | 857                               | 2823                            | 2573                                        | 4501                                  | 150              | 301      | 4050            | 278              | 3772  | 
| 2015-02-18T00:00:00 | 2010 | 32649            | 284             | 135                                           | 19     | 1018      | 3116         | 744           | 566             | 3711         | 602                            | 246         | 805                   | 2121                               | 2194                                | 114                                     | 1840                              | 339                  | 4202                              | 823                               | 2848                            | 2380                                        | 4543                                  | 170              | 302      | 4071            | 261              | 3810  | 
```