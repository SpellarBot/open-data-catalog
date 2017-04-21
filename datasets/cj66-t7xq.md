# Missouri Monthly Unemployment Claims By Industry

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/missouri-monthly-unemployment-claims-by-industry-80e86) |
| Metadata | [Link](https://data.mo.gov/api/views/cj66-t7xq) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/cj66-t7xq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/cj66-t7xq/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | cj66-t7xq |
| Name | Missouri Monthly Unemployment Claims By Industry |
| Category | Labor |
| Tags | unemployment, labor, employment |
| Created | 2012-08-30T14:34:59Z |
| Publication Date | 2017-04-10T13:02:01Z |

## Description

Demographic data of Missouri Unemployment claims by industry

## Columns

```ls
| Included | Schema Type    | Field Name                                  | Name                                          | Data Type     | Render Type   |
| ======== | ============== | =========================================== | ============================================= | ============= | ============= |
| Yes      | series tag     | record_id                                   | Record ID                                     | text          | text          |
| Yes      | time           | date                                        | Date                                          | calendar_date | calendar_date |
| Yes      | numeric metric | ina                                         | INA                                           | number        | number        |
| Yes      | numeric metric | wholesale_trade                             | Wholesale Trade                               | number        | number        |
| Yes      | numeric metric | transportation_warehouse                    | Transportation & Warehouse                    | number        | number        |
| Yes      | numeric metric | construction                                | Construction                                  | number        | number        |
| Yes      | numeric metric | finance_insurance                           | Finance & Insurance                           | number        | number        |
| Yes      | numeric metric | manufacturing                               | Manufacturing                                 | number        | number        |
| Yes      | numeric metric | agricult_forestry_fishing_hunting           | Agricult./Forestry/Fishing/Hunting            | number        | number        |
| Yes      | numeric metric | public_administration                       | Public Administration                         | number        | number        |
| Yes      | numeric metric | utilities                                   | Utilities                                     | number        | number        |
| Yes      | numeric metric | accomodation_food_services                  | Accomodation & Food Services                  | number        | number        |
| Yes      | numeric metric | information                                 | Information                                   | number        | number        |
| Yes      | numeric metric | professional_scientific_tech_services       | Professional/Scientific/Tech. Services        | number        | number        |
| Yes      | numeric metric | real_estate_rental_leasing                  | Real Estate & Rental & Leasing                | number        | number        |
| Yes      | numeric metric | other_services_except_public_administration | Other Services (except Public Administration) | number        | number        |
| Yes      | numeric metric | management_of_companies_enterprises         | Management of Companies & Enterprises         | number        | number        |
| Yes      | numeric metric | educational_services                        | Educational Services                          | number        | number        |
| Yes      | numeric metric | mining                                      | Mining                                        | number        | number        |
| Yes      | numeric metric | health_care_social_assistance               | Health Care & Social Assistance               | number        | number        |
| Yes      | numeric metric | arts_entertainment_recreation               | Arts, Entertainment & Recreation              | number        | number        |
| Yes      | numeric metric | admin_support_waste_mgmt_remedia_serv       | Admin. & Support/Waste Mgmt./Remedia. Serv.   | number        | number        |
| Yes      | numeric metric | retail_trade                                | Retail Trade                                  | number        | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:cj66-t7xq d:2011-08-01T00:00:00.000Z t:record_id=08012011 m:manufacturing=5736 m:information=1380 m:mining=143 m:other_services_except_public_administration=2172 m:health_care_social_assistance=7484 m:arts_entertainment_recreation=997 m:accomodation_food_services=6737 m:retail_trade=6393 m:wholesale_trade=2371 m:finance_insurance=1981 m:real_estate_rental_leasing=1145 m:admin_support_waste_mgmt_remedia_serv=7110 m:ina=2206 m:utilities=49 m:professional_scientific_tech_services=2632 m:educational_services=2360 m:management_of_companies_enterprises=278 m:construction=5696 m:transportation_warehouse=4281 m:public_administration=622 m:agricult_forestry_fishing_hunting=291

series e:cj66-t7xq d:2011-07-01T00:00:00.000Z t:record_id=07012011 m:manufacturing=6696 m:information=1387 m:mining=116 m:other_services_except_public_administration=2287 m:health_care_social_assistance=7895 m:arts_entertainment_recreation=896 m:accomodation_food_services=7334 m:retail_trade=6744 m:wholesale_trade=2595 m:finance_insurance=2114 m:real_estate_rental_leasing=1248 m:admin_support_waste_mgmt_remedia_serv=7594 m:ina=2251 m:utilities=77 m:professional_scientific_tech_services=2977 m:educational_services=2624 m:management_of_companies_enterprises=250 m:construction=6234 m:transportation_warehouse=4595 m:public_administration=661 m:agricult_forestry_fishing_hunting=246

series e:cj66-t7xq d:2011-09-01T00:00:00.000Z t:record_id=09012011 m:manufacturing=5722 m:information=1201 m:mining=126 m:other_services_except_public_administration=1803 m:health_care_social_assistance=6555 m:arts_entertainment_recreation=937 m:accomodation_food_services=4439 m:retail_trade=6012 m:wholesale_trade=2246 m:finance_insurance=1760 m:real_estate_rental_leasing=869 m:admin_support_waste_mgmt_remedia_serv=6400 m:ina=2057 m:utilities=58 m:professional_scientific_tech_services=2456 m:educational_services=1956 m:management_of_companies_enterprises=218 m:construction=6027 m:transportation_warehouse=1805 m:public_administration=605 m:agricult_forestry_fishing_hunting=229
```

## Meta Commands

```ls
metric m:ina p:integer l:INA d:"Information Not Available" t:dataTypeName=number

metric m:wholesale_trade p:integer l:"Wholesale Trade" t:dataTypeName=number

metric m:transportation_warehouse p:integer l:"Transportation & Warehouse" t:dataTypeName=number

metric m:construction p:integer l:Construction t:dataTypeName=number

metric m:finance_insurance p:integer l:"Finance & Insurance" t:dataTypeName=number

metric m:manufacturing p:integer l:Manufacturing t:dataTypeName=number

metric m:agricult_forestry_fishing_hunting p:integer l:Agricult./Forestry/Fishing/Hunting t:dataTypeName=number

metric m:public_administration p:integer l:"Public Administration" t:dataTypeName=number

metric m:utilities p:integer l:Utilities t:dataTypeName=number

metric m:accomodation_food_services p:integer l:"Accomodation & Food Services" t:dataTypeName=number

metric m:information p:integer l:Information t:dataTypeName=number

metric m:professional_scientific_tech_services p:integer l:"Professional/Scientific/Tech. Services" t:dataTypeName=number

metric m:real_estate_rental_leasing p:integer l:"Real Estate & Rental & Leasing" t:dataTypeName=number

metric m:other_services_except_public_administration p:integer l:"Other Services (except Public Administration)" t:dataTypeName=number

metric m:management_of_companies_enterprises p:integer l:"Management of Companies & Enterprises" t:dataTypeName=number

metric m:educational_services p:integer l:"Educational Services" t:dataTypeName=number

metric m:mining p:integer l:Mining t:dataTypeName=number

metric m:health_care_social_assistance p:integer l:"Health Care & Social Assistance" t:dataTypeName=number

metric m:arts_entertainment_recreation p:integer l:"Arts, Entertainment & Recreation" t:dataTypeName=number

metric m:admin_support_waste_mgmt_remedia_serv p:integer l:"Admin. & Support/Waste Mgmt./Remedia. Serv." t:dataTypeName=number

metric m:retail_trade p:integer l:"Retail Trade" t:dataTypeName=number

entity e:cj66-t7xq l:"Missouri Monthly Unemployment Claims By Industry" t:url=https://data.mo.gov/api/views/cj66-t7xq

property e:cj66-t7xq t:meta.view v:id=cj66-t7xq v:category=Labor v:averageRating=0 v:name="Missouri Monthly Unemployment Claims By Industry"

property e:cj66-t7xq t:meta.view.owner v:id=eb88-upz2 v:screenName=DOLIR v:displayName=DOLIR

property e:cj66-t7xq t:meta.view.tableauthor v:id=eb88-upz2 v:screenName=DOLIR v:roleName=editor v:displayName=DOLIR
```

## Top Records

```ls
| record_id | date                | ina  | wholesale_trade | transportation_warehouse | construction | finance_insurance | manufacturing | agricult_forestry_fishing_hunting | public_administration | utilities | accomodation_food_services | information | professional_scientific_tech_services | real_estate_rental_leasing | other_services_except_public_administration | management_of_companies_enterprises | educational_services | mining | health_care_social_assistance | arts_entertainment_recreation | admin_support_waste_mgmt_remedia_serv | retail_trade | 
| ========= | =================== | ==== | =============== | ======================== | ============ | ================= | ============= | ================================= | ===================== | ========= | ========================== | =========== | ===================================== | ========================== | =========================================== | =================================== | ==================== | ====== | ============================= | ============================= | ===================================== | ============ | 
| 08012011  | 2011-08-01T00:00:00 | 2206 | 2371            | 4281                     | 5696         | 1981              | 5736          | 291                               | 622                   | 49        | 6737                       | 1380        | 2632                                  | 1145                       | 2172                                        | 278                                 | 2360                 | 143    | 7484                          | 997                           | 7110                                  | 6393         | 
| 07012011  | 2011-07-01T00:00:00 | 2251 | 2595            | 4595                     | 6234         | 2114              | 6696          | 246                               | 661                   | 77        | 7334                       | 1387        | 2977                                  | 1248                       | 2287                                        | 250                                 | 2624                 | 116    | 7895                          | 896                           | 7594                                  | 6744         | 
| 09012011  | 2011-09-01T00:00:00 | 2057 | 2246            | 1805                     | 6027         | 1760              | 5722          | 229                               | 605                   | 58        | 4439                       | 1201        | 2456                                  | 869                        | 1803                                        | 218                                 | 1956                 | 126    | 6555                          | 937                           | 6400                                  | 6012         | 
| 02012012  | 2012-02-01T00:00:00 | 2100 | 2017            | 2783                     | 13213        | 1274              | 6134          | 549                               | 691                   | 45        | 6192                       | 1004        | 1820                                  | 1123                       | 1850                                        | 294                                 | 1099                 | 474    | 4971                          | 1978                          | 8222                                  | 6132         | 
| 10012011  | 2011-10-01T00:00:00 | 2196 | 2120            | 1775                     | 5790         | 1548              | 5735          | 214                               | 633                   | 57        | 4279                       | 1108        | 2143                                  | 838                        | 1709                                        | 206                                 | 1793                 | 143    | 5970                          | 728                           | 6047                                  | 5322         | 
| 11012011  | 2011-11-01T00:00:00 | 2295 | 2208            | 2045                     | 7782         | 1600              | 7014          | 261                               | 714                   | 49        | 5035                       | 1214        | 2230                                  | 1043                       | 1919                                        | 259                                 | 1692                 | 191    | 6456                          | 1011                          | 7174                                  | 6144         | 
| 12012011  | 2011-12-01T00:00:00 | 2180 | 2024            | 1992                     | 10175        | 1289              | 6874          | 497                               | 641                   | 50        | 5326                       | 994         | 1938                                  | 990                        | 1896                                        | 242                                 | 1305                 | 384    | 5337                          | 1341                          | 7125                                  | 5325         | 
| 01012012  | 2012-01-01T00:00:00 | 2405 | 2043            | 3271                     | 12854        | 1268              | 7017          | 625                               | 686                   | 49        | 7368                       | 1053        | 1946                                  | 1114                       | 1974                                        | 280                                 | 1265                 | 479    | 5122                          | 2313                          | 8647                                  | 6202         | 
| 03012012  | 2012-03-01T00:00:00 | 2006 | 1911            | 2432                     | 10447        | 1308              | 5468          | 355                               | 553                   | 63        | 5238                       | 915         | 1698                                  | 1000                       | 1792                                        | 273                                 | 1091                 | 253    | 5041                          | 1320                          | 6799                                  | 5682         | 
| 06012012  | 2012-06-01T00:00:00 | 1728 | 2062            | 3278                     | 4947         | 1392              | 5935          | 155                               | 479                   | 55        | 5359                       | 1028        | 2073                                  | 1060                       | 1790                                        | 256                                 | 1772                 | 94     | 5946                          | 555                           | 5340                                  | 4856         | 
```