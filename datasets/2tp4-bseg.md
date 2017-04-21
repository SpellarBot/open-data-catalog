# Howard County Full and Part Time Jobs By Industry: 2001-2040

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/howard-county-full-and-part-time-jobs-by-industry-2001-2040) |
| Metadata | [Link](https://data.maryland.gov/api/views/2tp4-bseg) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/2tp4-bseg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/2tp4-bseg/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | 2tp4-bseg |
| Name | Howard County Full and Part Time Jobs By Industry: 2001-2040 |
| Attribution | Maryland Department of Planning |
| Category | Planning |
| Tags | full and part time jobs in maryland by industry and by place of work from 2001 to 2040. |
| Created | 2015-02-19T16:55:26Z |
| Publication Date | 2015-02-19T17:03:06Z |

## Description

Full and Part Time Jobs in Howard County by Industry and by Place of Work from 2001 to 2040.

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
series e:2tp4-bseg d:2015-02-18T00:00:00.000Z m:arts_entertainment_and_recreation=3918 m:mining=69 m:manufacturing=8650 m:other_services_except_public_administration=7997 m:administrative_and_waste_services=9487 m:employment_state=4325 m:retail_trade=21078 m:government_and_government_enterprises=16972 m:military=884 m:wholesale_trade=13411 m:total_employment=165691 m:utilities=232 m:state_and_local=15353 m:construction=13527 m:health_care_and_social_assistance=13099 m:transportation_and_warehousing=5385 m:information=2877 m:management_of_companies_and_enterprises=310 m:finance_and_insurance=7140 m:federal_civilian=735 m:accommodation_and_food_services=9423 m:real_estate_and_rental_and_leasing=5700 m:professional_and_technical_services=23381 m:farm_employment=581 m:educational_services=2299 m:forestry_fishing_related_activities_and_other=155 m:local=11028

series e:2tp4-bseg d:2015-02-18T00:00:00.000Z m:arts_entertainment_and_recreation=3769 m:mining=59 m:manufacturing=7339 m:other_services_except_public_administration=7685 m:administrative_and_waste_services=10056 m:employment_state=4362 m:retail_trade=21458 m:government_and_government_enterprises=17321 m:military=902 m:wholesale_trade=13655 m:total_employment=168458 m:utilities=201 m:state_and_local=15714 m:construction=12880 m:health_care_and_social_assistance=13444 m:transportation_and_warehousing=5370 m:information=2506 m:management_of_companies_and_enterprises=350 m:finance_and_insurance=7937 m:federal_civilian=705 m:accommodation_and_food_services=9678 m:real_estate_and_rental_and_leasing=6451 m:professional_and_technical_services=24952 m:farm_employment=575 m:educational_services=2595 m:forestry_fishing_related_activities_and_other=177 m:local=11352

series e:2tp4-bseg d:2015-02-18T00:00:00.000Z m:arts_entertainment_and_recreation=3746 m:mining=66 m:manufacturing=6680 m:other_services_except_public_administration=7859 m:administrative_and_waste_services=10301 m:employment_state=4327 m:retail_trade=19751 m:government_and_government_enterprises=17644 m:military=905 m:wholesale_trade=13614 m:total_employment=168918 m:utilities=182 m:state_and_local=16060 m:construction=12899 m:health_care_and_social_assistance=13565 m:transportation_and_warehousing=5086 m:information=2469 m:management_of_companies_and_enterprises=756 m:finance_and_insurance=8128 m:federal_civilian=679 m:accommodation_and_food_services=10051 m:real_estate_and_rental_and_leasing=7149 m:professional_and_technical_services=25459 m:farm_employment=523 m:educational_services=2839 m:forestry_fishing_related_activities_and_other=151 m:local=11733
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

entity e:2tp4-bseg l:"Howard County Full and Part Time Jobs By Industry: 2001-2040" t:attribution="Maryland Department of Planning" t:url=https://data.maryland.gov/api/views/2tp4-bseg

property e:2tp4-bseg t:meta.view v:id=2tp4-bseg v:category=Planning v:attributionLink=http://planning.maryland.gov/msdc/projection/employment/NAICS_Jobs.shtml v:averageRating=0 v:name="Howard County Full and Part Time Jobs By Industry: 2001-2040" v:attribution="Maryland Department of Planning"

property e:2tp4-bseg t:meta.view.license v:name="Public Domain"

property e:2tp4-bseg t:meta.view.owner v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:displayName=MDP

property e:2tp4-bseg t:meta.view.tableauthor v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:roleName=editor v:displayName=MDP
```

## Top Records

```ls
| date_created        | year | total_employment | farm_employment | forestry_fishing_related_activities_and_other | mining | utilities | construction | manufacturing | wholesale_trade | retail_trade | transportation_and_warehousing | information | finance_and_insurance | real_estate_and_rental_and_leasing | professional_and_technical_services | management_of_companies_and_enterprises | administrative_and_waste_services | educational_services | health_care_and_social_assistance | arts_entertainment_and_recreation | accommodation_and_food_services | other_services_except_public_administration | government_and_government_enterprises | federal_civilian | military | state_and_local | employment_state | local | 
| =================== | ==== | ================ | =============== | ============================================= | ====== | ========= | ============ | ============= | =============== | ============ | ============================== | =========== | ===================== | ================================== | =================================== | ======================================= | ================================= | ==================== | ================================= | ================================= | =============================== | =========================================== | ===================================== | ================ | ======== | =============== | ================ | ===== | 
| 2015-02-18T00:00:00 | 2001 | 165691           | 581             | 155                                           | 69     | 232       | 13527        | 8650          | 13411           | 21078        | 5385                           | 2877        | 7140                  | 5700                               | 23381                               | 310                                     | 9487                              | 2299                 | 13099                             | 3918                              | 9423                            | 7997                                        | 16972                                 | 735              | 884      | 15353           | 4325             | 11028 | 
| 2015-02-18T00:00:00 | 2002 | 168458           | 575             | 177                                           | 59     | 201       | 12880        | 7339          | 13655           | 21458        | 5370                           | 2506        | 7937                  | 6451                               | 24952                               | 350                                     | 10056                             | 2595                 | 13444                             | 3769                              | 9678                            | 7685                                        | 17321                                 | 705              | 902      | 15714           | 4362             | 11352 | 
| 2015-02-18T00:00:00 | 2003 | 168918           | 523             | 151                                           | 66     | 182       | 12899        | 6680          | 13614           | 19751        | 5086                           | 2469        | 8128                  | 7149                               | 25459                               | 756                                     | 10301                             | 2839                 | 13565                             | 3746                              | 10051                           | 7859                                        | 17644                                 | 679              | 905      | 16060           | 4327             | 11733 | 
| 2015-02-18T00:00:00 | 2004 | 173641           | 510             | 133                                           | 64     | 185       | 13387        | 6808          | 14132           | 21059        | 5035                           | 2480        | 8494                  | 7636                               | 25663                               | 916                                     | 10449                             | 3157                 | 13604                             | 3912                              | 10446                           | 7962                                        | 17609                                 | 635              | 821      | 16153           | 4319             | 11834 | 
| 2015-02-18T00:00:00 | 2005 | 178718           | 500             | 138                                           | 75     | 191       | 13203        | 7035          | 15437           | 20885        | 5165                           | 3713        | 8158                  | 8554                               | 26196                               | 954                                     | 10610                             | 3225                 | 13983                             | 3896                              | 11262                           | 8074                                        | 17464                                 | 632              | 821      | 16011           | 3875             | 12136 | 
| 2015-02-18T00:00:00 | 2006 | 186766           | 502             | 148                                           | 68     | 212       | 13582        | 7114          | 16152           | 21059        | 5008                           | 4356        | 8299                  | 9043                               | 28055                               | 1445                                    | 12165                             | 3401                 | 14058                             | 3680                              | 12290                           | 8412                                        | 17717                                 | 633              | 798      | 16286           | 3771             | 12515 | 
| 2015-02-18T00:00:00 | 2007 | 189021           | 506             | 139                                           | 71     | 214       | 13826        | 6796          | 15983           | 20621        | 4649                           | 4860        | 8813                  | 9426                               | 29235                               | 1579                                    | 12257                             | 3460                 | 14520                             | 3839                              | 11102                           | 8848                                        | 18277                                 | 620              | 804      | 16853           | 3792             | 13061 | 
| 2015-02-18T00:00:00 | 2008 | 190256           | 480             | 135                                           | 92     | 201       | 13443        | 6684          | 15831           | 19043        | 4370                           | 4783        | 8874                  | 9182                               | 30535                               | 1700                                    | 12859                             | 3896                 | 15037                             | 3940                              | 11274                           | 8992                                        | 18915                                 | 622              | 826      | 17467           | 3692             | 13775 | 
| 2015-02-18T00:00:00 | 2009 | 188238           | 472             | 68                                            | 123    | 205       | 12125        | 6355          | 15223           | 17871        | 4369                           | 4432        | 9486                  | 9102                               | 31737                               | 1629                                    | 12558                             | 4328                 | 15250                             | 4060                              | 10702                           | 8949                                        | 19194                                 | 629              | 833      | 17732           | 3723             | 14009 | 
| 2015-02-18T00:00:00 | 2010 | 189573           | 493             | 66                                            | 125    | 169       | 11694        | 6192          | 14327           | 17788        | 4457                           | 4523        | 9310                  | 9088                               | 33628                               | 1627                                    | 12419                             | 4356                 | 15407                             | 4635                              | 10798                           | 8962                                        | 19509                                 | 697              | 854      | 17958           | 3890             | 14068 | 
```