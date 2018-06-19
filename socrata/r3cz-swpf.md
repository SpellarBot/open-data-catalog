# Prince George's County Full and Part Time Jobs By Industry: 2001-2040

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/prince-georges-county-full-and-part-time-jobs-by-industry-2001-2040) |
| Metadata | [Link](https://data.maryland.gov/api/views/r3cz-swpf) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/r3cz-swpf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/r3cz-swpf/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | r3cz-swpf |
| Name | Prince George's County Full and Part Time Jobs By Industry: 2001-2040 |
| Attribution | Maryland Department of Planning |
| Category | Planning |
| Tags | full and part time jobs in maryland by industry and by place of work from 2001 to 2040. |
| Created | 2015-02-23T21:00:55Z |
| Publication Date | 2015-02-23T21:05:44Z |

## Description

Full and Part Time Jobs in Prince George's County by Industry and by Place of Work from 2001 to 2040.

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
series e:r3cz-swpf d:2015-02-18T00:00:00.000Z m:arts_entertainment_and_recreation=6873 m:mining=241 m:manufacturing=13166 m:other_services_except_public_administration=24458 m:administrative_and_waste_services=24645 m:employment_state=19570 m:retail_trade=48511 m:government_and_government_enterprises=87532 m:military=8943 m:wholesale_trade=13996 m:total_employment=401139 m:utilities=715 m:state_and_local=53395 m:construction=37155 m:health_care_and_social_assistance=30889 m:transportation_and_warehousing=17272 m:information=10726 m:management_of_companies_and_enterprises=2421 m:finance_and_insurance=11796 m:federal_civilian=25194 m:accommodation_and_food_services=20173 m:real_estate_and_rental_and_leasing=12967 m:professional_and_technical_services=31561 m:farm_employment=741 m:educational_services=5084 m:forestry_fishing_related_activities_and_other=217 m:local=33825

series e:r3cz-swpf d:2015-02-18T00:00:00.000Z m:arts_entertainment_and_recreation=7282 m:mining=172 m:manufacturing=12596 m:other_services_except_public_administration=25294 m:administrative_and_waste_services=26086 m:employment_state=19904 m:retail_trade=48592 m:government_and_government_enterprises=89400 m:military=8785 m:wholesale_trade=14616 m:total_employment=407367 m:utilities=578 m:state_and_local=54292 m:construction=36929 m:health_care_and_social_assistance=32361 m:transportation_and_warehousing=16717 m:information=10320 m:management_of_companies_and_enterprises=2211 m:finance_and_insurance=11251 m:federal_civilian=26323 m:accommodation_and_food_services=21697 m:real_estate_and_rental_and_leasing=13927 m:professional_and_technical_services=30592 m:farm_employment=722 m:educational_services=5820 m:forestry_fishing_related_activities_and_other=204 m:local=34388

series e:r3cz-swpf d:2015-02-18T00:00:00.000Z m:arts_entertainment_and_recreation=7239 m:mining=227 m:manufacturing=11948 m:other_services_except_public_administration=25319 m:administrative_and_waste_services=27580 m:employment_state=19538 m:retail_trade=49472 m:government_and_government_enterprises=90438 m:military=8659 m:wholesale_trade=13439 m:total_employment=412277 m:utilities=720 m:state_and_local=55377 m:construction=38481 m:health_care_and_social_assistance=33136 m:transportation_and_warehousing=15557 m:information=9510 m:management_of_companies_and_enterprises=2796 m:finance_and_insurance=10996 m:federal_civilian=26402 m:accommodation_and_food_services=22335 m:real_estate_and_rental_and_leasing=14935 m:professional_and_technical_services=31484 m:farm_employment=614 m:educational_services=5872 m:forestry_fishing_related_activities_and_other=179 m:local=35839
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

entity e:r3cz-swpf l:"Prince George's County Full and Part Time Jobs By Industry: 2001-2040" t:attribution="Maryland Department of Planning" t:url=https://data.maryland.gov/api/views/r3cz-swpf

property e:r3cz-swpf t:meta.view v:id=r3cz-swpf v:category=Planning v:attributionLink=http://planning.maryland.gov/msdc/projection/employment/NAICS_Jobs.shtml v:averageRating=0 v:name="Prince George's County Full and Part Time Jobs By Industry: 2001-2040" v:attribution="Maryland Department of Planning"

property e:r3cz-swpf t:meta.view.license v:name="Public Domain"

property e:r3cz-swpf t:meta.view.owner v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:displayName=MDP

property e:r3cz-swpf t:meta.view.tableauthor v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:roleName=editor v:displayName=MDP
```

## Top Records

```ls
| date_created        | year | total_employment | farm_employment | forestry_fishing_related_activities_and_other | mining | utilities | construction | manufacturing | wholesale_trade | retail_trade | transportation_and_warehousing | information | finance_and_insurance | real_estate_and_rental_and_leasing | professional_and_technical_services | management_of_companies_and_enterprises | administrative_and_waste_services | educational_services | health_care_and_social_assistance | arts_entertainment_and_recreation | accommodation_and_food_services | other_services_except_public_administration | government_and_government_enterprises | federal_civilian | military | state_and_local | employment_state | local | 
| =================== | ==== | ================ | =============== | ============================================= | ====== | ========= | ============ | ============= | =============== | ============ | ============================== | =========== | ===================== | ================================== | =================================== | ======================================= | ================================= | ==================== | ================================= | ================================= | =============================== | =========================================== | ===================================== | ================ | ======== | =============== | ================ | ===== | 
| 2015-02-18T00:00:00 | 2001 | 401139           | 741             | 217                                           | 241    | 715       | 37155        | 13166         | 13996           | 48511        | 17272                          | 10726       | 11796                 | 12967                              | 31561                               | 2421                                    | 24645                             | 5084                 | 30889                             | 6873                              | 20173                           | 24458                                       | 87532                                 | 25194            | 8943     | 53395           | 19570            | 33825 | 
| 2015-02-18T00:00:00 | 2002 | 407367           | 722             | 204                                           | 172    | 578       | 36929        | 12596         | 14616           | 48592        | 16717                          | 10320       | 11251                 | 13927                              | 30592                               | 2211                                    | 26086                             | 5820                 | 32361                             | 7282                              | 21697                           | 25294                                       | 89400                                 | 26323            | 8785     | 54292           | 19904            | 34388 | 
| 2015-02-18T00:00:00 | 2003 | 412277           | 614             | 179                                           | 227    | 720       | 38481        | 11948         | 13439           | 49472        | 15557                          | 9510        | 10996                 | 14935                              | 31484                               | 2796                                    | 27580                             | 5872                 | 33136                             | 7239                              | 22335                           | 25319                                       | 90438                                 | 26402            | 8659     | 55377           | 19538            | 35839 | 
| 2015-02-18T00:00:00 | 2004 | 420989           | 553             | 186                                           | 196    | 716       | 39796        | 12066         | 14008           | 49812        | 15543                          | 8704        | 11116                 | 16815                              | 33406                               | 2991                                    | 30255                             | 6145                 | 32559                             | 7655                              | 22572                           | 26062                                       | 89833                                 | 26475            | 8337     | 55021           | 19605            | 35416 | 
| 2015-02-18T00:00:00 | 2005 | 423028           | 501             | 198                                           | 211    | 715       | 40651        | 11775         | 14429           | 49936        | 15247                          | 7466        | 11697                 | 18155                              | 33575                               | 3103                                    | 28620                             | 6587                 | 32298                             | 7748                              | 23820                           | 25817                                       | 90479                                 | 26327            | 8163     | 55989           | 19880            | 36109 | 
| 2015-02-18T00:00:00 | 2006 | 427633           | 456             | 207                                           | 259    | 712       | 41988        | 11212         | 13633           | 49650        | 15573                          | 7700        | 12008                 | 18032                              | 32624                               | 2847                                    | 30030                             | 7074                 | 33596                             | 8027                              | 23376                           | 25995                                       | 92634                                 | 25926            | 7869     | 58839           | 20078            | 38761 | 
| 2015-02-18T00:00:00 | 2007 | 441367           | 425             | 218                                           | 262    | 769       | 43862        | 11301         | 14123           | 50212        | 16141                          | 7736        | 12625                 | 17979                              | 33433                               | 2520                                    | 32821                             | 7365                 | 34908                             | 8054                              | 24025                           | 26990                                       | 95598                                 | 25319            | 7804     | 62475           | 20643            | 41832 | 
| 2015-02-18T00:00:00 | 2008 | 438835           | 411             | 206                                           | 263    | 761       | 41714        | 11077         | 13868           | 47291        | 15378                          | 7822        | 12586                 | 18378                              | 33546                               | 2712                                    | 30970                             | 7541                 | 35403                             | 8479                              | 26008                           | 26420                                       | 98001                                 | 25481            | 8030     | 64490           | 20933            | 43557 | 
| 2015-02-18T00:00:00 | 2009 | 429739           | 405             | 170                                           | 226    | 745       | 37665        | 10963         | 12858           | 46128        | 14958                          | 6131        | 12833                 | 17651                              | 33537                               | 2074                                    | 29714                             | 7934                 | 36587                             | 8708                              | 26212                           | 26022                                       | 98218                                 | 26085            | 7700     | 64433           | 21437            | 42996 | 
| 2015-02-18T00:00:00 | 2010 | 423654           | 416             | 178                                           | 289    | 730       | 34493        | 10071         | 12074           | 45892        | 14581                          | 6272        | 11795                 | 18879                              | 33015                               | 1994                                    | 29403                             | 7835                 | 37000                             | 8646                              | 26151                           | 25496                                       | 98444                                 | 27429            | 7650     | 63365           | 21952            | 41413 | 
```