# Anne Arundel County Full and Part Time Jobs By Industry: 2001-2040

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/anne-arundel-county-full-and-part-time-jobs-by-industry-2001-2040) |
| Metadata | [Link](https://data.maryland.gov/api/views/iyam-4vtd) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/iyam-4vtd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/iyam-4vtd/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | iyam-4vtd |
| Name | Anne Arundel County Full and Part Time Jobs By Industry: 2001-2040 |
| Attribution | Maryland Department of Planning |
| Category | Planning |
| Tags | full and part time jobs in maryland by industry and by place of work from 2001 to 2040. |
| Created | 2015-02-18T17:02:37Z |
| Publication Date | 2015-02-18T17:07:39Z |

## Description

Full and Part Time Jobs in Anne Arundel County by Industry and by Place of Work from 2001 to 2040.

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
series e:iyam-4vtd d:2015-02-18T00:00:00.000Z m:arts_entertainment_and_recreation=6338 m:mining=277 m:manufacturing=16365 m:other_services_except_public_administration=15588 m:administrative_and_waste_services=17410 m:employment_state=10726 m:retail_trade=33051 m:government_and_government_enterprises=76437 m:military=15651 m:wholesale_trade=10278 m:total_employment=306992 m:utilities=584 m:state_and_local=28102 m:construction=18591 m:health_care_and_social_assistance=21153 m:transportation_and_warehousing=14676 m:information=5579 m:management_of_companies_and_enterprises=871 m:finance_and_insurance=8377 m:federal_civilian=32684 m:accommodation_and_food_services=19670 m:real_estate_and_rental_and_leasing=12026 m:professional_and_technical_services=25284 m:farm_employment=527 m:educational_services=3592 m:forestry_fishing_related_activities_and_other=318 m:local=17376

series e:iyam-4vtd d:2015-02-18T00:00:00.000Z m:arts_entertainment_and_recreation=6699 m:mining=274 m:manufacturing=15328 m:other_services_except_public_administration=16537 m:administrative_and_waste_services=17831 m:employment_state=10906 m:retail_trade=33756 m:government_and_government_enterprises=81594 m:military=15865 m:wholesale_trade=9986 m:total_employment=314921 m:utilities=570 m:state_and_local=28815 m:construction=19382 m:health_care_and_social_assistance=21826 m:transportation_and_warehousing=12727 m:information=5165 m:management_of_companies_and_enterprises=922 m:finance_and_insurance=9030 m:federal_civilian=36914 m:accommodation_and_food_services=20512 m:real_estate_and_rental_and_leasing=12223 m:professional_and_technical_services=25865 m:farm_employment=511 m:educational_services=3772 m:forestry_fishing_related_activities_and_other=411 m:local=17909

series e:iyam-4vtd d:2015-02-18T00:00:00.000Z m:arts_entertainment_and_recreation=6944 m:mining=313 m:manufacturing=14242 m:other_services_except_public_administration=17187 m:administrative_and_waste_services=18151 m:employment_state=10700 m:retail_trade=35958 m:government_and_government_enterprises=80722 m:military=15081 m:wholesale_trade=10954 m:total_employment=323153 m:utilities=444 m:state_and_local=28547 m:construction=20273 m:health_care_and_social_assistance=22717 m:transportation_and_warehousing=12381 m:information=5186 m:management_of_companies_and_enterprises=742 m:finance_and_insurance=9962 m:federal_civilian=37094 m:accommodation_and_food_services=21490 m:real_estate_and_rental_and_leasing=13848 m:professional_and_technical_services=26958 m:farm_employment=479 m:educational_services=3867 m:forestry_fishing_related_activities_and_other=336 m:local=17847
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

entity e:iyam-4vtd l:"Anne Arundel County Full and Part Time Jobs By Industry: 2001-2040" t:attribution="Maryland Department of Planning" t:url=https://data.maryland.gov/api/views/iyam-4vtd

property e:iyam-4vtd t:meta.view v:id=iyam-4vtd v:category=Planning v:attributionLink=http://planning.maryland.gov/msdc/projection/employment/NAICS_Jobs.shtml v:averageRating=0 v:name="Anne Arundel County Full and Part Time Jobs By Industry: 2001-2040" v:attribution="Maryland Department of Planning"

property e:iyam-4vtd t:meta.view.license v:name="Public Domain"

property e:iyam-4vtd t:meta.view.owner v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:displayName=MDP

property e:iyam-4vtd t:meta.view.tableauthor v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:roleName=editor v:displayName=MDP
```

## Top Records

```ls
| date_created        | year | total_employment | farm_employment | forestry_fishing_related_activities_and_other | mining | utilities | construction | manufacturing | wholesale_trade | retail_trade | transportation_and_warehousing | information | finance_and_insurance | real_estate_and_rental_and_leasing | professional_and_technical_services | management_of_companies_and_enterprises | administrative_and_waste_services | educational_services | health_care_and_social_assistance | arts_entertainment_and_recreation | accommodation_and_food_services | other_services_except_public_administration | government_and_government_enterprises | federal_civilian | military | state_and_local | employment_state | local | 
| =================== | ==== | ================ | =============== | ============================================= | ====== | ========= | ============ | ============= | =============== | ============ | ============================== | =========== | ===================== | ================================== | =================================== | ======================================= | ================================= | ==================== | ================================= | ================================= | =============================== | =========================================== | ===================================== | ================ | ======== | =============== | ================ | ===== | 
| 2015-02-18T00:00:00 | 2001 | 306992           | 527             | 318                                           | 277    | 584       | 18591        | 16365         | 10278           | 33051        | 14676                          | 5579        | 8377                  | 12026                              | 25284                               | 871                                     | 17410                             | 3592                 | 21153                             | 6338                              | 19670                           | 15588                                       | 76437                                 | 32684            | 15651    | 28102           | 10726            | 17376 | 
| 2015-02-18T00:00:00 | 2002 | 314921           | 511             | 411                                           | 274    | 570       | 19382        | 15328         | 9986            | 33756        | 12727                          | 5165        | 9030                  | 12223                              | 25865                               | 922                                     | 17831                             | 3772                 | 21826                             | 6699                              | 20512                           | 16537                                       | 81594                                 | 36914            | 15865    | 28815           | 10906            | 17909 | 
| 2015-02-18T00:00:00 | 2003 | 323153           | 479             | 336                                           | 313    | 444       | 20273        | 14242         | 10954           | 35958        | 12381                          | 5186        | 9962                  | 13848                              | 26958                               | 742                                     | 18151                             | 3867                 | 22717                             | 6944                              | 21490                           | 17187                                       | 80722                                 | 37094            | 15081    | 28547           | 10700            | 17847 | 
| 2015-02-18T00:00:00 | 2004 | 334872           | 471             | 352                                           | 240    | 442       | 22106        | 14898         | 11732           | 37885        | 12388                          | 5493        | 10700                 | 15415                              | 28922                               | 993                                     | 18944                             | 3943                 | 23263                             | 7548                              | 22210                           | 17817                                       | 79110                                 | 36774            | 14663    | 27673           | 9999             | 17674 | 
| 2015-02-18T00:00:00 | 2005 | 347413           | 466             | 340                                           | 218    | 384       | 24473        | 14780         | 11831           | 38636        | 13464                          | 5903        | 11072                 | 17393                              | 29890                               | 1177                                    | 19728                             | 4081                 | 23973                             | 8116                              | 23352                           | 18154                                       | 79982                                 | 37356            | 14811    | 27815           | 9939             | 17876 | 
| 2015-02-18T00:00:00 | 2006 | 353970           | 467             | 334                                           | 234    | 401       | 25420        | 14490         | 11959           | 40021        | 13487                          | 5482        | 11360                 | 18425                              | 30368                               | 1424                                    | 19601                             | 4324                 | 25097                             | 8320                              | 23427                           | 18114                                       | 81215                                 | 37465            | 14714    | 29036           | 9850             | 19186 | 
| 2015-02-18T00:00:00 | 2007 | 364864           | 481             | 345                                           | 254    | 450       | 25417        | 14907         | 12616           | 40583        | 13909                          | 6301        | 11768                 | 19254                              | 32253                               | 1496                                    | 20046                             | 4381                 | 26229                             | 8891                              | 24833                           | 19104                                       | 81345                                 | 37483            | 14527    | 29335           | 9821             | 19514 | 
| 2015-02-18T00:00:00 | 2008 | 364623           | 461             | 353                                           | 275    | 514       | 23906        | 14812         | 13012           | 39161        | 13149                          | 6278        | 11568                 | 18305                              | 33689                               | 1598                                    | 19869                             | 4598                 | 27609                             | 8827                              | 25058                           | 19215                                       | 82372                                 | 37637            | 14887    | 29848           | 10060            | 19788 | 
| 2015-02-18T00:00:00 | 2009 | 356070           | 453             | 350                                           | 275    | 297       | 21905        | 14104         | 12459           | 37555        | 12028                          | 5345        | 12069                 | 17364                              | 32519                               | 1505                                    | 19056                             | 4701                 | 28364                             | 8293                              | 24933                           | 19437                                       | 83058                                 | 37811            | 15187    | 30060           | 10025            | 20035 | 
| 2015-02-18T00:00:00 | 2010 | 354218           | 470             | 362                                           | 262    | 292       | 20272        | 14965         | 12171           | 36924        | 11810                          | 4723        | 11654                 | 17262                              | 31929                               | 1243                                    | 20396                             | 4828                 | 28785                             | 8356                              | 25107                           | 18416                                       | 83991                                 | 38433            | 15774    | 29784           | 9787             | 19997 | 
```