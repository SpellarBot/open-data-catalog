# Montgomery County Full and Part Time Jobs By Industry: 2001-2040

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/montgomery-county-full-and-part-time-jobs-by-industry-2001-2040) |
| Metadata | [Link](https://data.maryland.gov/api/views/qgsn-md8q) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/qgsn-md8q/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/qgsn-md8q/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | qgsn-md8q |
| Name | Montgomery County Full and Part Time Jobs By Industry: 2001-2040 |
| Attribution | Maryland Department of Planning |
| Category | Planning |
| Tags | full and part time jobs in maryland by industry and by place of work from 2001 to 2040. |
| Created | 2015-02-23T20:54:25Z |
| Publication Date | 2015-02-23T20:59:10Z |

## Description

Full and Part Time Jobs in Montgomery County by Industry and by Place of Work from 2001 to 2040.

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
series e:qgsn-md8q d:2015-02-18T00:00:00.000Z m:arts_entertainment_and_recreation=13684 m:mining=660 m:manufacturing=19913 m:other_services_except_public_administration=41233 m:administrative_and_waste_services=42573 m:employment_state=1351 m:retail_trade=59927 m:government_and_government_enterprises=86613 m:military=6855 m:wholesale_trade=13143 m:total_employment=601896 m:utilities=1105 m:state_and_local=37782 m:construction=37171 m:health_care_and_social_assistance=55951 m:transportation_and_warehousing=7819 m:information=21817 m:management_of_companies_and_enterprises=1886 m:finance_and_insurance=31084 m:federal_civilian=41976 m:accommodation_and_food_services=33945 m:real_estate_and_rental_and_leasing=29124 m:professional_and_technical_services=91249 m:farm_employment=965 m:educational_services=11686 m:forestry_fishing_related_activities_and_other=348 m:local=36431

series e:qgsn-md8q d:2015-02-18T00:00:00.000Z m:arts_entertainment_and_recreation=14315 m:mining=585 m:manufacturing=18590 m:other_services_except_public_administration=42296 m:administrative_and_waste_services=41602 m:employment_state=1398 m:retail_trade=58516 m:government_and_government_enterprises=91335 m:military=6909 m:wholesale_trade=13176 m:total_employment=605950 m:utilities=1346 m:state_and_local=40218 m:construction=37898 m:health_care_and_social_assistance=58460 m:transportation_and_warehousing=7930 m:information=19699 m:management_of_companies_and_enterprises=1980 m:finance_and_insurance=30489 m:federal_civilian=44208 m:accommodation_and_food_services=33152 m:real_estate_and_rental_and_leasing=29254 m:professional_and_technical_services=90903 m:farm_employment=970 m:educational_services=13053 m:forestry_fishing_related_activities_and_other=401 m:local=38820

series e:qgsn-md8q d:2015-02-18T00:00:00.000Z m:arts_entertainment_and_recreation=14472 m:mining=701 m:manufacturing=17339 m:other_services_except_public_administration=43375 m:administrative_and_waste_services=43759 m:employment_state=1365 m:retail_trade=58280 m:government_and_government_enterprises=91308 m:military=6940 m:wholesale_trade=13085 m:total_employment=615397 m:utilities=903 m:state_and_local=40104 m:construction=38827 m:health_care_and_social_assistance=59836 m:transportation_and_warehousing=8025 m:information=19267 m:management_of_companies_and_enterprises=1937 m:finance_and_insurance=31917 m:federal_civilian=44264 m:accommodation_and_food_services=34094 m:real_estate_and_rental_and_leasing=31757 m:professional_and_technical_services=91574 m:farm_employment=877 m:educational_services=13748 m:forestry_fishing_related_activities_and_other=316 m:local=38739
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

entity e:qgsn-md8q l:"Montgomery County Full and Part Time Jobs By Industry: 2001-2040" t:attribution="Maryland Department of Planning" t:url=https://data.maryland.gov/api/views/qgsn-md8q

property e:qgsn-md8q t:meta.view v:id=qgsn-md8q v:category=Planning v:attributionLink=http://planning.maryland.gov/msdc/projection/employment/NAICS_Jobs.shtml v:averageRating=0 v:name="Montgomery County Full and Part Time Jobs By Industry: 2001-2040" v:attribution="Maryland Department of Planning"

property e:qgsn-md8q t:meta.view.license v:name="Public Domain"

property e:qgsn-md8q t:meta.view.owner v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:displayName=MDP

property e:qgsn-md8q t:meta.view.tableauthor v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:roleName=editor v:displayName=MDP
```

## Top Records

```ls
| date_created        | year | total_employment | farm_employment | forestry_fishing_related_activities_and_other | mining | utilities | construction | manufacturing | wholesale_trade | retail_trade | transportation_and_warehousing | information | finance_and_insurance | real_estate_and_rental_and_leasing | professional_and_technical_services | management_of_companies_and_enterprises | administrative_and_waste_services | educational_services | health_care_and_social_assistance | arts_entertainment_and_recreation | accommodation_and_food_services | other_services_except_public_administration | government_and_government_enterprises | federal_civilian | military | state_and_local | employment_state | local | 
| =================== | ==== | ================ | =============== | ============================================= | ====== | ========= | ============ | ============= | =============== | ============ | ============================== | =========== | ===================== | ================================== | =================================== | ======================================= | ================================= | ==================== | ================================= | ================================= | =============================== | =========================================== | ===================================== | ================ | ======== | =============== | ================ | ===== | 
| 2015-02-18T00:00:00 | 2001 | 601896           | 965             | 348                                           | 660    | 1105      | 37171        | 19913         | 13143           | 59927        | 7819                           | 21817       | 31084                 | 29124                              | 91249                               | 1886                                    | 42573                             | 11686                | 55951                             | 13684                             | 33945                           | 41233                                       | 86613                                 | 41976            | 6855     | 37782           | 1351             | 36431 | 
| 2015-02-18T00:00:00 | 2002 | 605950           | 970             | 401                                           | 585    | 1346      | 37898        | 18590         | 13176           | 58516        | 7930                           | 19699       | 30489                 | 29254                              | 90903                               | 1980                                    | 41602                             | 13053                | 58460                             | 14315                             | 33152                           | 42296                                       | 91335                                 | 44208            | 6909     | 40218           | 1398             | 38820 | 
| 2015-02-18T00:00:00 | 2003 | 615397           | 877             | 316                                           | 701    | 903       | 38827        | 17339         | 13085           | 58280        | 8025                           | 19267       | 31917                 | 31757                              | 91574                               | 1937                                    | 43759                             | 13748                | 59836                             | 14472                             | 34094                           | 43375                                       | 91308                                 | 44264            | 6940     | 40104           | 1365             | 38739 | 
| 2015-02-18T00:00:00 | 2004 | 623235           | 845             | 319                                           | 692    | 825       | 39365        | 16567         | 13319           | 57663        | 8515                           | 18934       | 31891                 | 35004                              | 93656                               | 6760                                    | 44279                             | 14471                | 61098                             | 14761                             | 30732                           | 43350                                       | 90189                                 | 43742            | 6545     | 39902           | 1310             | 38592 | 
| 2015-02-18T00:00:00 | 2005 | 638423           | 821             | 416                                           | 666    | 841       | 40377        | 15851         | 13473           | 59374        | 8454                           | 19673       | 32761                 | 39318                              | 95487                               | 7098                                    | 45838                             | 15014                | 62340                             | 14864                             | 31989                           | 43732                                       | 90036                                 | 43044            | 6463     | 40529           | 1286             | 39243 | 
| 2015-02-18T00:00:00 | 2006 | 651942           | 815             | 309                                           | 885    | 849       | 42914        | 15519         | 13622           | 58709        | 8728                           | 19740       | 33291                 | 41138                              | 97654                               | 7560                                    | 47108                             | 15994                | 63766                             | 16052                             | 33194                           | 44905                                       | 89190                                 | 42859            | 6317     | 40014           | 1310             | 38704 | 
| 2015-02-18T00:00:00 | 2007 | 658581           | 811             | 303                                           | 1036   | 867       | 43282        | 15660         | 13565           | 58029        | 8552                           | 18780       | 35131                 | 42935                              | 98535                               | 8245                                    | 46991                             | 15992                | 65009                             | 16225                             | 33373                           | 46474                                       | 88786                                 | 43434            | 6303     | 39049           | 1311             | 37738 | 
| 2015-02-18T00:00:00 | 2008 | 657133           | 771             | 343                                           | 1110   | 861       | 40991        | 14718         | 13411           | 55189        | 8166                           | 19064       | 36212                 | 41730                              | 99724                               | 8409                                    | 45412                             | 16202                | 66951                             | 16471                             | 34180                           | 46585                                       | 90633                                 | 44615            | 6447     | 39571           | 1329             | 38242 | 
| 2015-02-18T00:00:00 | 2009 | 647819           | 759             | 342                                           | 909    | 792       | 36604        | 14244         | 12678           | 51706        | 8407                           | 18174       | 37520                 | 40411                              | 100377                              | 8318                                    | 43238                             | 16414                | 68879                             | 16358                             | 33384                           | 46154                                       | 92151                                 | 46262            | 6452     | 39437           | 1326             | 38111 | 
| 2015-02-18T00:00:00 | 2010 | 644992           | 793             | 324                                           | 812    | 616       | 33905        | 13634         | 12724           | 51911        | 8656                           | 17368       | 36043                 | 40851                              | 99939                               | 7636                                    | 45724                             | 16786                | 70643                             | 16033                             | 33267                           | 44037                                       | 93290                                 | 48139            | 6469     | 38682           | 1282             | 37400 | 
```