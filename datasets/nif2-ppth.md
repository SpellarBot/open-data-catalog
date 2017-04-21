# Frederick County Full and Part Time Jobs By Industry: 2001-2040

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/frederick-county-full-and-part-time-jobs-by-industry-2001-2040) |
| Metadata | [Link](https://data.maryland.gov/api/views/nif2-ppth) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/nif2-ppth/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/nif2-ppth/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | nif2-ppth |
| Name | Frederick County Full and Part Time Jobs By Industry: 2001-2040 |
| Attribution | Maryland Department of Planning |
| Category | Planning |
| Tags | full and part time jobs in maryland by industry and by place of work from 2001 to 2040. |
| Created | 2015-02-19T16:12:50Z |
| Publication Date | 2015-02-19T16:17:06Z |

## Description

Full and Part Time Jobs in Frederick County by Industry and by Place of Work from 2001 to 2040.

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
series e:nif2-ppth d:2015-02-18T00:00:00.000Z m:arts_entertainment_and_recreation=1893 m:mining=28 m:manufacturing=7545 m:other_services_except_public_administration=5946 m:administrative_and_waste_services=5377 m:employment_state=784 m:retail_trade=14092 m:government_and_government_enterprises=14570 m:military=2068 m:wholesale_trade=3260 m:total_employment=108132 m:utilities=197 m:state_and_local=9522 m:construction=11607 m:health_care_and_social_assistance=9417 m:transportation_and_warehousing=1946 m:information=1892 m:management_of_companies_and_enterprises=71 m:finance_and_insurance=6012 m:federal_civilian=2980 m:accommodation_and_food_services=6544 m:real_estate_and_rental_and_leasing=3600 m:professional_and_technical_services=9890 m:farm_employment=1865 m:educational_services=2115 m:forestry_fishing_related_activities_and_other=265 m:local=8738

series e:nif2-ppth d:2015-02-18T00:00:00.000Z m:arts_entertainment_and_recreation=1717 m:mining=24 m:manufacturing=6837 m:other_services_except_public_administration=6262 m:administrative_and_waste_services=5962 m:employment_state=795 m:retail_trade=14400 m:government_and_government_enterprises=15172 m:military=2094 m:wholesale_trade=3316 m:total_employment=112825 m:utilities=187 m:state_and_local=9914 m:construction=11828 m:health_care_and_social_assistance=9741 m:transportation_and_warehousing=1823 m:information=2178 m:management_of_companies_and_enterprises=95 m:finance_and_insurance=8323 m:federal_civilian=3164 m:accommodation_and_food_services=6842 m:real_estate_and_rental_and_leasing=3799 m:professional_and_technical_services=9911 m:farm_employment=1812 m:educational_services=2306 m:forestry_fishing_related_activities_and_other=290 m:local=9119

series e:nif2-ppth d:2015-02-18T00:00:00.000Z m:arts_entertainment_and_recreation=1828 m:mining=30 m:manufacturing=6331 m:other_services_except_public_administration=6565 m:administrative_and_waste_services=6580 m:employment_state=791 m:retail_trade=14711 m:government_and_government_enterprises=15524 m:military=2164 m:wholesale_trade=3488 m:total_employment=117088 m:utilities=200 m:state_and_local=10157 m:construction=12345 m:health_care_and_social_assistance=10259 m:transportation_and_warehousing=1761 m:information=2233 m:management_of_companies_and_enterprises=69 m:finance_and_insurance=8613 m:federal_civilian=3203 m:accommodation_and_food_services=7525 m:real_estate_and_rental_and_leasing=4257 m:professional_and_technical_services=10475 m:farm_employment=1683 m:educational_services=2349 m:forestry_fishing_related_activities_and_other=262 m:local=9366
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

entity e:nif2-ppth l:"Frederick County Full and Part Time Jobs By Industry: 2001-2040" t:attribution="Maryland Department of Planning" t:url=https://data.maryland.gov/api/views/nif2-ppth

property e:nif2-ppth t:meta.view v:id=nif2-ppth v:category=Planning v:attributionLink=http://planning.maryland.gov/msdc/projection/employment/NAICS_Jobs.shtml v:averageRating=0 v:name="Frederick County Full and Part Time Jobs By Industry: 2001-2040" v:attribution="Maryland Department of Planning"

property e:nif2-ppth t:meta.view.license v:name="Public Domain"

property e:nif2-ppth t:meta.view.owner v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:displayName=MDP

property e:nif2-ppth t:meta.view.tableauthor v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:roleName=editor v:displayName=MDP
```

## Top Records

```ls
| date_created        | year | total_employment | farm_employment | forestry_fishing_related_activities_and_other | mining | utilities | construction | manufacturing | wholesale_trade | retail_trade | transportation_and_warehousing | information | finance_and_insurance | real_estate_and_rental_and_leasing | professional_and_technical_services | management_of_companies_and_enterprises | administrative_and_waste_services | educational_services | health_care_and_social_assistance | arts_entertainment_and_recreation | accommodation_and_food_services | other_services_except_public_administration | government_and_government_enterprises | federal_civilian | military | state_and_local | employment_state | local | 
| =================== | ==== | ================ | =============== | ============================================= | ====== | ========= | ============ | ============= | =============== | ============ | ============================== | =========== | ===================== | ================================== | =================================== | ======================================= | ================================= | ==================== | ================================= | ================================= | =============================== | =========================================== | ===================================== | ================ | ======== | =============== | ================ | ===== | 
| 2015-02-18T00:00:00 | 2001 | 108132           | 1865            | 265                                           | 28     | 197       | 11607        | 7545          | 3260            | 14092        | 1946                           | 1892        | 6012                  | 3600                               | 9890                                | 71                                      | 5377                              | 2115                 | 9417                              | 1893                              | 6544                            | 5946                                        | 14570                                 | 2980             | 2068     | 9522            | 784              | 8738  | 
| 2015-02-18T00:00:00 | 2002 | 112825           | 1812            | 290                                           | 24     | 187       | 11828        | 6837          | 3316            | 14400        | 1823                           | 2178        | 8323                  | 3799                               | 9911                                | 95                                      | 5962                              | 2306                 | 9741                              | 1717                              | 6842                            | 6262                                        | 15172                                 | 3164             | 2094     | 9914            | 795              | 9119  | 
| 2015-02-18T00:00:00 | 2003 | 117088           | 1683            | 262                                           | 30     | 200       | 12345        | 6331          | 3488            | 14711        | 1761                           | 2233        | 8613                  | 4257                               | 10475                               | 69                                      | 6580                              | 2349                 | 10259                             | 1828                              | 7525                            | 6565                                        | 15524                                 | 3203             | 2164     | 10157           | 791              | 9366  | 
| 2015-02-18T00:00:00 | 2004 | 121159           | 1657            | 320                                           | 18     | 200       | 13312        | 6628          | 3667            | 14888        | 1919                           | 2152        | 8216                  | 4809                               | 10837                               | 141                                     | 7033                              | 2514                 | 10572                             | 1945                              | 7895                            | 6853                                        | 15583                                 | 3191             | 2055     | 10337           | 784              | 9553  | 
| 2015-02-18T00:00:00 | 2005 | 124905           | 1656            | 306                                           | 72     | 209       | 14565        | 6538          | 3807            | 15454        | 2127                           | 2154        | 8253                  | 5331                               | 11325                               | 168                                     | 6969                              | 2559                 | 10459                             | 2118                              | 8074                            | 6974                                        | 15787                                 | 3240             | 2007     | 10540           | 762              | 9778  | 
| 2015-02-18T00:00:00 | 2006 | 126873           | 1658            | 330                                           | 45     | 194       | 14579        | 5756          | 3832            | 15936        | 2305                           | 2146        | 8187                  | 5343                               | 12133                               | 165                                     | 6953                              | 2733                 | 10644                             | 2164                              | 8541                            | 7027                                        | 16202                                 | 3311             | 1995     | 10896           | 762              | 10134 | 
| 2015-02-18T00:00:00 | 2007 | 131037           | 1720            | 333                                           | 54     | 206       | 14492        | 5625          | 3650            | 16676        | 2374                           | 2094        | 8345                  | 5163                               | 13655                               | 140                                     | 7138                              | 2810                 | 11300                             | 2396                              | 9052                            | 7302                                        | 16512                                 | 3395             | 1909     | 11208           | 775              | 10433 | 
| 2015-02-18T00:00:00 | 2008 | 130605           | 1667            | 325                                           | 68     | 209       | 13231        | 6049          | 3439            | 15112        | 2505                           | 2063        | 8558                  | 5689                               | 14180                               | 235                                     | 6959                              | 2930                 | 11622                             | 2496                              | 8643                            | 7245                                        | 17377                                 | 3537             | 1868     | 11972           | 783              | 11189 | 
| 2015-02-18T00:00:00 | 2009 | 128851           | 1644            | 327                                           | 89     | 177       | 11293        | 5494          | 3333            | 14070        | 2319                           | 1925        | 9720                  | 5669                               | 14476                               | 399                                     | 6758                              | 3305                 | 11830                             | 2551                              | 8606                            | 7144                                        | 17722                                 | 3773             | 1796     | 12153           | 793              | 11360 | 
| 2015-02-18T00:00:00 | 2010 | 128113           | 1691            | 341                                           | 78     | 149       | 10545        | 5108          | 3117            | 13942        | 2265                           | 1879        | 9668                  | 5623                               | 14761                               | 558                                     | 7187                              | 3337                 | 11961                             | 2660                              | 8408                            | 7003                                        | 17832                                 | 4040             | 1801     | 11991           | 778              | 11213 | 
```