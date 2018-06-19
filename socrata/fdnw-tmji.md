# Wicomico County Full and Part Time Jobs By Industry: 2001-2040

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/wicomico-county-full-and-part-time-jobs-by-industry-2001-2040) |
| Metadata | [Link](https://data.maryland.gov/api/views/fdnw-tmji) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/fdnw-tmji/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/fdnw-tmji/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | fdnw-tmji |
| Name | Wicomico County Full and Part Time Jobs By Industry: 2001-2040 |
| Attribution | Maryland Department of Planning |
| Category | Planning |
| Tags | full and part time jobs in maryland by industry and by place of work from 2001 to 2040. |
| Created | 2015-02-23T21:56:53Z |
| Publication Date | 2015-02-23T22:01:12Z |

## Description

Full and Part Time Jobs in Wicomico County by Industry and by Place of Work from 2001 to 2040.

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
series e:fdnw-tmji d:2015-02-18T00:00:00.000Z m:arts_entertainment_and_recreation=607 m:mining=35 m:manufacturing=5535 m:other_services_except_public_administration=3656 m:administrative_and_waste_services=2857 m:employment_state=2421 m:retail_trade=6895 m:government_and_government_enterprises=6645 m:military=293 m:wholesale_trade=1531 m:total_employment=51983 m:utilities=390 m:state_and_local=6021 m:construction=3679 m:health_care_and_social_assistance=6597 m:transportation_and_warehousing=1585 m:information=1129 m:management_of_companies_and_enterprises=865 m:finance_and_insurance=1451 m:federal_civilian=331 m:accommodation_and_food_services=3728 m:real_estate_and_rental_and_leasing=1169 m:professional_and_technical_services=2155 m:farm_employment=995 m:educational_services=351 m:forestry_fishing_related_activities_and_other=127 m:local=3600

series e:fdnw-tmji d:2015-02-18T00:00:00.000Z m:arts_entertainment_and_recreation=632 m:mining=44 m:manufacturing=5047 m:other_services_except_public_administration=3967 m:administrative_and_waste_services=2567 m:employment_state=2401 m:retail_trade=6816 m:government_and_government_enterprises=6754 m:military=297 m:wholesale_trade=1632 m:total_employment=52437 m:utilities=405 m:state_and_local=6114 m:construction=3682 m:health_care_and_social_assistance=6884 m:transportation_and_warehousing=1536 m:information=1019 m:management_of_companies_and_enterprises=796 m:finance_and_insurance=1508 m:federal_civilian=343 m:accommodation_and_food_services=3890 m:real_estate_and_rental_and_leasing=1304 m:professional_and_technical_services=2420 m:farm_employment=976 m:educational_services=425 m:forestry_fishing_related_activities_and_other=133 m:local=3713

series e:fdnw-tmji d:2015-02-18T00:00:00.000Z m:arts_entertainment_and_recreation=668 m:mining=53 m:manufacturing=4447 m:other_services_except_public_administration=4129 m:administrative_and_waste_services=2612 m:employment_state=2358 m:retail_trade=7331 m:government_and_government_enterprises=6817 m:military=300 m:wholesale_trade=1656 m:total_employment=52937 m:utilities=413 m:state_and_local=6164 m:construction=4003 m:health_care_and_social_assistance=6955 m:transportation_and_warehousing=1430 m:information=969 m:management_of_companies_and_enterprises=810 m:finance_and_insurance=1558 m:federal_civilian=353 m:accommodation_and_food_services=3864 m:real_estate_and_rental_and_leasing=1426 m:professional_and_technical_services=2387 m:farm_employment=851 m:educational_services=437 m:forestry_fishing_related_activities_and_other=121 m:local=3806
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

entity e:fdnw-tmji l:"Wicomico County Full and Part Time Jobs By Industry: 2001-2040" t:attribution="Maryland Department of Planning" t:url=https://data.maryland.gov/api/views/fdnw-tmji

property e:fdnw-tmji t:meta.view v:id=fdnw-tmji v:category=Planning v:attributionLink=http://planning.maryland.gov/msdc/projection/employment/NAICS_Jobs.shtml v:averageRating=0 v:name="Wicomico County Full and Part Time Jobs By Industry: 2001-2040" v:attribution="Maryland Department of Planning"

property e:fdnw-tmji t:meta.view.license v:name="Public Domain"

property e:fdnw-tmji t:meta.view.owner v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:displayName=MDP

property e:fdnw-tmji t:meta.view.tableauthor v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:roleName=editor v:displayName=MDP
```

## Top Records

```ls
| date_created        | year | total_employment | farm_employment | forestry_fishing_related_activities_and_other | mining | utilities | construction | manufacturing | wholesale_trade | retail_trade | transportation_and_warehousing | information | finance_and_insurance | real_estate_and_rental_and_leasing | professional_and_technical_services | management_of_companies_and_enterprises | administrative_and_waste_services | educational_services | health_care_and_social_assistance | arts_entertainment_and_recreation | accommodation_and_food_services | other_services_except_public_administration | government_and_government_enterprises | federal_civilian | military | state_and_local | employment_state | local | 
| =================== | ==== | ================ | =============== | ============================================= | ====== | ========= | ============ | ============= | =============== | ============ | ============================== | =========== | ===================== | ================================== | =================================== | ======================================= | ================================= | ==================== | ================================= | ================================= | =============================== | =========================================== | ===================================== | ================ | ======== | =============== | ================ | ===== | 
| 2015-02-18T00:00:00 | 2001 | 51983            | 995             | 127                                           | 35     | 390       | 3679         | 5535          | 1531            | 6895         | 1585                           | 1129        | 1451                  | 1169                               | 2155                                | 865                                     | 2857                              | 351                  | 6597                              | 607                               | 3728                            | 3656                                        | 6645                                  | 331              | 293      | 6021            | 2421             | 3600  | 
| 2015-02-18T00:00:00 | 2002 | 52437            | 976             | 133                                           | 44     | 405       | 3682         | 5047          | 1632            | 6816         | 1536                           | 1019        | 1508                  | 1304                               | 2420                                | 796                                     | 2567                              | 425                  | 6884                              | 632                               | 3890                            | 3967                                        | 6754                                  | 343              | 297      | 6114            | 2401             | 3713  | 
| 2015-02-18T00:00:00 | 2003 | 52937            | 851             | 121                                           | 53     | 413       | 4003         | 4447          | 1656            | 7331         | 1430                           | 969         | 1558                  | 1426                               | 2387                                | 810                                     | 2612                              | 437                  | 6955                              | 668                               | 3864                            | 4129                                        | 6817                                  | 353              | 300      | 6164            | 2358             | 3806  | 
| 2015-02-18T00:00:00 | 2004 | 55483            | 800             | 108                                           | 49     | 379       | 4539         | 4522          | 1811            | 8083         | 1379                           | 955         | 1631                  | 1680                               | 2645                                | 735                                     | 2922                              | 484                  | 7132                              | 697                               | 3788                            | 4280                                        | 6863                                  | 342              | 274      | 6247            | 2327             | 3920  | 
| 2015-02-18T00:00:00 | 2005 | 57754            | 758             | 131                                           | 79     | 375       | 5027         | 4892          | 1950            | 8292         | 1456                           | 942         | 1705                  | 1854                               | 2562                                | 882                                     | 3021                              | 481                  | 7817                              | 737                               | 3901                            | 3921                                        | 6971                                  | 340              | 278      | 6353            | 2326             | 4027  | 
| 2015-02-18T00:00:00 | 2006 | 59323            | 732             | 128                                           | 59     | 375       | 5165         | 4869          | 2027            | 8391         | 1518                           | 960         | 1715                  | 1914                               | 2623                                | 843                                     | 3361                              | 505                  | 8202                              | 768                               | 4170                            | 3905                                        | 7093                                  | 332              | 274      | 6487            | 2328             | 4159  | 
| 2015-02-18T00:00:00 | 2007 | 59851            | 715             | 150                                           | 79     | 376       | 5078         | 4484          | 2019            | 8378         | 1612                           | 1015        | 1764                  | 1831                               | 2718                                | 947                                     | 3343                              | 457                  | 8302                              | 854                               | 4260                            | 3946                                        | 7523                                  | 329              | 277      | 6917            | 2497             | 4420  | 
| 2015-02-18T00:00:00 | 2008 | 58743            | 682             | 160                                           | 108    | 356       | 4397         | 4372          | 1961            | 7772         | 1659                           | 1044        | 1845                  | 1858                               | 2694                                | 967                                     | 3205                              | 474                  | 8436                              | 836                               | 4264                            | 3805                                        | 7834                                  | 330              | 280      | 7224            | 2565             | 4659  | 
| 2015-02-18T00:00:00 | 2009 | 56929            | 671             | 172                                           | 112    | 362       | 3722         | 4295          | 1822            | 7345         | 1543                           | 988         | 1845                  | 1768                               | 2423                                | 966                                     | 3140                              | 494                  | 8500                              | 759                               | 4047                            | 3771                                        | 8183                                  | 339              | 279      | 7565            | 2642             | 4923  | 
| 2015-02-18T00:00:00 | 2010 | 55799            | 698             | 177                                           | 219    | 375       | 3364         | 4210          | 1786            | 7197         | 1357                           | 870         | 1772                  | 1903                               | 2458                                | 1042                                    | 2939                              | 500                  | 8495                              | 973                               | 3931                            | 3451                                        | 8082                                  | 370              | 284      | 7428            | 2669             | 4759  | 
```