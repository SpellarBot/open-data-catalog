# Worcester County Full and Part Time Jobs By Industry: 2001-2040

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/worcester-county-full-and-part-time-jobs-by-industry-2001-2040) |
| Metadata | [Link](https://data.maryland.gov/api/views/bgpx-bm65) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/bgpx-bm65/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/bgpx-bm65/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | bgpx-bm65 |
| Name | Worcester County Full and Part Time Jobs By Industry: 2001-2040 |
| Attribution | Maryland Department of Planning |
| Category | Planning |
| Tags | full and part time jobs in maryland by industry and by place of work from 2001 to 2040. |
| Created | 2015-02-23T22:02:30Z |
| Publication Date | 2015-02-23T22:07:02Z |

## Description

Full and Part Time Jobs in Worcester County by Industry and by Place of Work from 2001 to 2040.

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
series e:bgpx-bm65 d:2015-02-18T00:00:00.000Z m:arts_entertainment_and_recreation=1191 m:mining=8 m:manufacturing=2032 m:other_services_except_public_administration=1482 m:administrative_and_waste_services=1102 m:employment_state=334 m:retail_trade=4470 m:government_and_government_enterprises=3455 m:military=203 m:wholesale_trade=419 m:total_employment=32033 m:utilities=49 m:state_and_local=3018 m:construction=2406 m:health_care_and_social_assistance=1543 m:transportation_and_warehousing=347 m:information=247 m:management_of_companies_and_enterprises=82 m:finance_and_insurance=780 m:federal_civilian=234 m:accommodation_and_food_services=8083 m:real_estate_and_rental_and_leasing=2238 m:professional_and_technical_services=1125 m:farm_employment=576 m:educational_services=235 m:forestry_fishing_related_activities_and_other=163 m:local=2684

series e:bgpx-bm65 d:2015-02-18T00:00:00.000Z m:arts_entertainment_and_recreation=1268 m:mining=12 m:manufacturing=2184 m:other_services_except_public_administration=1607 m:administrative_and_waste_services=883 m:employment_state=347 m:retail_trade=4658 m:government_and_government_enterprises=3589 m:military=206 m:wholesale_trade=284 m:total_employment=32998 m:utilities=61 m:state_and_local=3139 m:construction=2510 m:health_care_and_social_assistance=1667 m:transportation_and_warehousing=493 m:information=191 m:management_of_companies_and_enterprises=84 m:finance_and_insurance=833 m:federal_civilian=244 m:accommodation_and_food_services=8360 m:real_estate_and_rental_and_leasing=2179 m:professional_and_technical_services=1055 m:farm_employment=526 m:educational_services=262 m:forestry_fishing_related_activities_and_other=292 m:local=2792

series e:bgpx-bm65 d:2015-02-18T00:00:00.000Z m:arts_entertainment_and_recreation=1262 m:mining=13 m:manufacturing=1678 m:other_services_except_public_administration=1655 m:administrative_and_waste_services=1076 m:employment_state=374 m:retail_trade=4521 m:government_and_government_enterprises=3673 m:military=209 m:wholesale_trade=273 m:total_employment=32918 m:utilities=52 m:state_and_local=3236 m:construction=2767 m:health_care_and_social_assistance=1793 m:transportation_and_warehousing=452 m:information=185 m:management_of_companies_and_enterprises=75 m:finance_and_insurance=876 m:federal_civilian=228 m:accommodation_and_food_services=8067 m:real_estate_and_rental_and_leasing=2486 m:professional_and_technical_services=1011 m:farm_employment=490 m:educational_services=283 m:forestry_fishing_related_activities_and_other=229 m:local=2862
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

entity e:bgpx-bm65 l:"Worcester County Full and Part Time Jobs By Industry: 2001-2040" t:attribution="Maryland Department of Planning" t:url=https://data.maryland.gov/api/views/bgpx-bm65

property e:bgpx-bm65 t:meta.view v:id=bgpx-bm65 v:category=Planning v:attributionLink=http://planning.maryland.gov/msdc/projection/employment/NAICS_Jobs.shtml v:averageRating=0 v:name="Worcester County Full and Part Time Jobs By Industry: 2001-2040" v:attribution="Maryland Department of Planning"

property e:bgpx-bm65 t:meta.view.license v:name="Public Domain"

property e:bgpx-bm65 t:meta.view.owner v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:displayName=MDP

property e:bgpx-bm65 t:meta.view.tableauthor v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:roleName=editor v:displayName=MDP
```

## Top Records

```ls
| date_created        | year | total_employment | farm_employment | forestry_fishing_related_activities_and_other | mining | utilities | construction | manufacturing | wholesale_trade | retail_trade | transportation_and_warehousing | information | finance_and_insurance | real_estate_and_rental_and_leasing | professional_and_technical_services | management_of_companies_and_enterprises | administrative_and_waste_services | educational_services | health_care_and_social_assistance | arts_entertainment_and_recreation | accommodation_and_food_services | other_services_except_public_administration | government_and_government_enterprises | federal_civilian | military | state_and_local | employment_state | local | 
| =================== | ==== | ================ | =============== | ============================================= | ====== | ========= | ============ | ============= | =============== | ============ | ============================== | =========== | ===================== | ================================== | =================================== | ======================================= | ================================= | ==================== | ================================= | ================================= | =============================== | =========================================== | ===================================== | ================ | ======== | =============== | ================ | ===== | 
| 2015-02-18T00:00:00 | 2001 | 32033            | 576             | 163                                           | 8      | 49        | 2406         | 2032          | 419             | 4470         | 347                            | 247         | 780                   | 2238                               | 1125                                | 82                                      | 1102                              | 235                  | 1543                              | 1191                              | 8083                            | 1482                                        | 3455                                  | 234              | 203      | 3018            | 334              | 2684  | 
| 2015-02-18T00:00:00 | 2002 | 32998            | 526             | 292                                           | 12     | 61        | 2510         | 2184          | 284             | 4658         | 493                            | 191         | 833                   | 2179                               | 1055                                | 84                                      | 883                               | 262                  | 1667                              | 1268                              | 8360                            | 1607                                        | 3589                                  | 244              | 206      | 3139            | 347              | 2792  | 
| 2015-02-18T00:00:00 | 2003 | 32918            | 490             | 229                                           | 13     | 52        | 2767         | 1678          | 273             | 4521         | 452                            | 185         | 876                   | 2486                               | 1011                                | 75                                      | 1076                              | 283                  | 1793                              | 1262                              | 8067                            | 1655                                        | 3673                                  | 228              | 209      | 3236            | 374              | 2862  | 
| 2015-02-18T00:00:00 | 2004 | 33300            | 482             | 219                                           | 13     | 45        | 2973         | 1179          | 334             | 4273         | 412                            | 192         | 875                   | 2907                               | 1210                                | 77                                      | 1000                              | 288                  | 1808                              | 1368                              | 8064                            | 1790                                        | 3791                                  | 215              | 187      | 3389            | 371              | 3018  | 
| 2015-02-18T00:00:00 | 2005 | 33639            | 478             | 197                                           | 18     | 51        | 3303         | 677           | 308             | 4362         | 525                            | 212         | 822                   | 3339                               | 1164                                | 74                                      | 1169                              | 275                  | 1798                              | 1406                              | 7955                            | 1632                                        | 3873                                  | 200              | 182      | 3491            | 359              | 3132  | 
| 2015-02-18T00:00:00 | 2006 | 34286            | 476             | 178                                           | 19     | 54        | 3345         | 650           | 307             | 4459         | 529                            | 207         | 859                   | 3428                               | 1170                                | 84                                      | 1080                              | 329                  | 1891                              | 1429                              | 8324                            | 1644                                        | 3824                                  | 203              | 184      | 3437            | 364              | 3073  | 
| 2015-02-18T00:00:00 | 2007 | 34412            | 487             | 163                                           | 18     | 69        | 2955         | 682           | 356             | 4587         | 524                            | 216         | 927                   | 3387                               | 1193                                | 107                                     | 1102                              | 336                  | 2057                              | 1342                              | 8229                            | 1721                                        | 3955                                  | 199              | 185      | 3571            | 378              | 3193  | 
| 2015-02-18T00:00:00 | 2008 | 33288            | 470             | 179                                           | 50     | 65        | 2542         | 701           | 336             | 4452         | 459                            | 227         | 976                   | 2877                               | 1201                                | 211                                     | 1001                              | 348                  | 2107                              | 1286                              | 8010                            | 1709                                        | 4081                                  | 199              | 185      | 3697            | 377              | 3320  | 
| 2015-02-18T00:00:00 | 2009 | 32391            | 462             | 180                                           | 55     | 56        | 2174         | 773           | 266             | 4396         | 476                            | 234         | 1083                  | 2657                               | 1154                                | 216                                     | 1138                              | 336                  | 2079                              | 1243                              | 7761                            | 1650                                        | 4002                                  | 205              | 184      | 3613            | 374              | 3239  | 
| 2015-02-18T00:00:00 | 2010 | 32007            | 479             | 189                                           | 123    | 51        | 1969         | 780           | 269             | 4202         | 467                            | 206         | 1121                  | 2640                               | 1188                                | 284                                     | 1167                              | 290                  | 2133                              | 1191                              | 7722                            | 1577                                        | 3958                                  | 264              | 187      | 3507            | 353              | 3154  | 
```