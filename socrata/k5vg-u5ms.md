# JOBCOUNT - STATE OF HAWAII - Monthly - Not Seasonally Adjusted

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/jobcount-state-of-hawaii-monthly-not-seasonally-adjusted-af0ff) |
| Metadata | [Link](https://data.hawaii.gov/api/views/k5vg-u5ms) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/k5vg-u5ms/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/k5vg-u5ms/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | k5vg-u5ms |
| Name | JOBCOUNT - STATE OF HAWAII - Monthly - Not Seasonally Adjusted |
| Attribution | DLIR R&S |
| Category | Employment |
| Tags | jobs, jobcount, job count, state, hawaii, monthly |
| Created | 2013-10-17T01:57:39Z |
| Publication Date | 2014-05-13T20:47:39Z |

## Columns

```ls
| Included | Schema Type    | Field Name                                                                | Name                                                                      | Data Type     | Render Type   |
| ======== | ============== | ========================================================================= | ========================================================================= | ============= | ============= |
| Yes      | time           | month_year                                                                | Month/Year                                                                | calendar_date | calendar_date |
| Yes      | numeric metric | natural_resources_and_mining_and_construction                             | Natural Resources and Mining and Construction                             | number        | number        |
| Yes      | numeric metric | manufacturing                                                             | Manufacturing                                                             | number        | number        |
| Yes      | numeric metric | wholesale_trade                                                           | Wholesale Trade                                                           | number        | number        |
| Yes      | numeric metric | retail_trade                                                              | Retail Trade                                                              | number        | number        |
| Yes      | numeric metric | utilites                                                                  | Utilites                                                                  | number        | number        |
| Yes      | numeric metric | transportation_and_warehousing_1                                          | Transportation and Warehousing (1)                                        | number        | number        |
| Yes      | numeric metric | information                                                               | Information                                                               | number        | number        |
| Yes      | numeric metric | finance_and_insurance                                                     | Finance and Insurance                                                     | number        | number        |
| Yes      | numeric metric | real_estate_and_rental_and_leasing                                        | Real Estate and Rental and Leasing                                        | number        | number        |
| Yes      | numeric metric | professional_scientific_and_technical_services                            | Professional, Scientific and Technical Services                           | number        | number        |
| Yes      | numeric metric | management_of_companies_and_enterprises                                   | Management of Companies and Enterprises                                   | number        | number        |
| Yes      | numeric metric | administrative_and_support_and_waste_and_management_and_remedial_services | Administrative and Support and Waste and Management and Remedial Services | number        | number        |
| Yes      | numeric metric | educational_services                                                      | Educational Services                                                      | number        | number        |
| Yes      | numeric metric | health_care_and_social_assistance                                         | Health Care and Social Assistance                                         | number        | number        |
| Yes      | numeric metric | arts_entertainment_and_recreation                                         | Arts, Entertainment, and Recreation                                       | number        | number        |
| Yes      | numeric metric | accommodation                                                             | Accommodation                                                             | number        | number        |
| Yes      | numeric metric | food_services_and_drinking_places                                         | Food Services and Drinking Places                                         | number        | number        |
| Yes      | numeric metric | other_services                                                            | Other Services                                                            | number        | number        |
| Yes      | numeric metric | federal_government                                                        | Federal Government                                                        | number        | number        |
| Yes      | numeric metric | state_government                                                          | State Government                                                          | number        | number        |
| Yes      | numeric metric | local_government                                                          | Local Government                                                          | number        | number        |
```

## Time Field

```ls
Value = month_year
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:k5vg-u5ms d:1990-01-01T00:00:00.000Z m:administrative_and_support_and_waste_and_management_and_remedial_services=22400 m:information=9500 m:manufacturing=20700 m:arts_entertainment_and_recreation=9100 m:management_of_companies_and_enterprises=4800 m:finance_and_insurance=17800 m:natural_resources_and_mining_and_construction=33900 m:retail_trade=66600 m:utilites=2600 m:federal_government=33900 m:real_estate_and_rental_and_leasing=12700 m:state_government=53500 m:professional_scientific_and_technical_services=21200 m:wholesale_trade=17300 m:food_services_and_drinking_places=46200 m:accommodation=38300 m:educational_services=8700 m:transportation_and_warehousing_1=24800 m:other_services=19200 m:local_government=13800 m:health_care_and_social_assistance=36400

series e:k5vg-u5ms d:1990-02-01T00:00:00.000Z m:administrative_and_support_and_waste_and_management_and_remedial_services=22800 m:information=9600 m:manufacturing=20900 m:arts_entertainment_and_recreation=9200 m:management_of_companies_and_enterprises=4800 m:finance_and_insurance=17900 m:natural_resources_and_mining_and_construction=34500 m:retail_trade=66500 m:utilites=2600 m:federal_government=33800 m:real_estate_and_rental_and_leasing=12800 m:state_government=57200 m:professional_scientific_and_technical_services=21700 m:wholesale_trade=17500 m:food_services_and_drinking_places=46900 m:accommodation=38600 m:educational_services=9100 m:transportation_and_warehousing_1=25400 m:other_services=19300 m:local_government=13900 m:health_care_and_social_assistance=36600

series e:k5vg-u5ms d:1990-03-01T00:00:00.000Z m:administrative_and_support_and_waste_and_management_and_remedial_services=23200 m:information=9700 m:manufacturing=20900 m:arts_entertainment_and_recreation=9100 m:management_of_companies_and_enterprises=4800 m:finance_and_insurance=18100 m:natural_resources_and_mining_and_construction=34800 m:retail_trade=66500 m:utilites=2600 m:federal_government=33900 m:real_estate_and_rental_and_leasing=12900 m:state_government=60000 m:professional_scientific_and_technical_services=22000 m:wholesale_trade=17500 m:food_services_and_drinking_places=47300 m:accommodation=36600 m:educational_services=9200 m:transportation_and_warehousing_1=25400 m:other_services=19700 m:local_government=14000 m:health_care_and_social_assistance=36900
```

## Meta Commands

```ls
metric m:natural_resources_and_mining_and_construction p:integer l:"Natural Resources and Mining and Construction" t:dataTypeName=number

metric m:manufacturing p:integer l:Manufacturing t:dataTypeName=number

metric m:wholesale_trade p:integer l:"Wholesale Trade" t:dataTypeName=number

metric m:retail_trade p:integer l:"Retail Trade" t:dataTypeName=number

metric m:utilites p:integer l:Utilites t:dataTypeName=number

metric m:transportation_and_warehousing_1 p:integer l:"Transportation and Warehousing (1)" t:dataTypeName=number

metric m:information p:integer l:Information t:dataTypeName=number

metric m:finance_and_insurance p:integer l:"Finance and Insurance" t:dataTypeName=number

metric m:real_estate_and_rental_and_leasing p:integer l:"Real Estate and Rental and Leasing" t:dataTypeName=number

metric m:professional_scientific_and_technical_services p:integer l:"Professional, Scientific and Technical Services" t:dataTypeName=number

metric m:management_of_companies_and_enterprises p:integer l:"Management of Companies and Enterprises" t:dataTypeName=number

metric m:administrative_and_support_and_waste_and_management_and_remedial_services p:integer l:"Administrative and Support and Waste and Management and Remedial Services" t:dataTypeName=number

metric m:educational_services p:integer l:"Educational Services" t:dataTypeName=number

metric m:health_care_and_social_assistance p:integer l:"Health Care and Social Assistance" t:dataTypeName=number

metric m:arts_entertainment_and_recreation p:integer l:"Arts, Entertainment, and Recreation" t:dataTypeName=number

metric m:accommodation p:integer l:Accommodation t:dataTypeName=number

metric m:food_services_and_drinking_places p:integer l:"Food Services and Drinking Places" t:dataTypeName=number

metric m:other_services p:integer l:"Other Services" t:dataTypeName=number

metric m:federal_government p:integer l:"Federal Government" t:dataTypeName=number

metric m:state_government p:integer l:"State Government" t:dataTypeName=number

metric m:local_government p:integer l:"Local Government" t:dataTypeName=number

entity e:k5vg-u5ms l:"JOBCOUNT - STATE OF HAWAII - Monthly - Not Seasonally Adjusted" t:attribution="DLIR R&S" t:url=https://data.hawaii.gov/api/views/k5vg-u5ms

property e:k5vg-u5ms t:meta.view v:id=k5vg-u5ms v:category=Employment v:averageRating=0 v:name="JOBCOUNT - STATE OF HAWAII - Monthly - Not Seasonally Adjusted" v:attribution="DLIR R&S"

property e:k5vg-u5ms t:meta.view.owner v:id=5ibs-8u6a v:profileImageUrlMedium=/api/users/5ibs-8u6a/profile_images/THUMB v:profileImageUrlLarge=/api/users/5ibs-8u6a/profile_images/LARGE v:screenName=Bill v:profileImageUrlSmall=/api/users/5ibs-8u6a/profile_images/TINY v:displayName=Bill

property e:k5vg-u5ms t:meta.view.tableauthor v:id=5ibs-8u6a v:profileImageUrlMedium=/api/users/5ibs-8u6a/profile_images/THUMB v:profileImageUrlLarge=/api/users/5ibs-8u6a/profile_images/LARGE v:screenName=Bill v:profileImageUrlSmall=/api/users/5ibs-8u6a/profile_images/TINY v:roleName=editor v:displayName=Bill
```

## Top Records

```ls
| month_year          | natural_resources_and_mining_and_construction | manufacturing | wholesale_trade | retail_trade | utilites | transportation_and_warehousing_1 | information | finance_and_insurance | real_estate_and_rental_and_leasing | professional_scientific_and_technical_services | management_of_companies_and_enterprises | administrative_and_support_and_waste_and_management_and_remedial_services | educational_services | health_care_and_social_assistance | arts_entertainment_and_recreation | accommodation | food_services_and_drinking_places | other_services | federal_government | state_government | local_government | 
| =================== | ============================================= | ============= | =============== | ============ | ======== | ================================ | =========== | ===================== | ================================== | ============================================== | ======================================= | ========================================================================= | ==================== | ================================= | ================================= | ============= | ================================= | ============== | ================== | ================ | ================ | 
| 1990-01-01T00:00:00 | 33900                                         | 20700         | 17300           | 66600        | 2600     | 24800                            | 9500        | 17800                 | 12700                              | 21200                                          | 4800                                    | 22400                                                                     | 8700                 | 36400                             | 9100                              | 38300         | 46200                             | 19200          | 33900              | 53500            | 13800            | 
| 1990-02-01T00:00:00 | 34500                                         | 20900         | 17500           | 66500        | 2600     | 25400                            | 9600        | 17900                 | 12800                              | 21700                                          | 4800                                    | 22800                                                                     | 9100                 | 36600                             | 9200                              | 38600         | 46900                             | 19300          | 33800              | 57200            | 13900            | 
| 1990-03-01T00:00:00 | 34800                                         | 20900         | 17500           | 66500        | 2600     | 25400                            | 9700        | 18100                 | 12900                              | 22000                                          | 4800                                    | 23200                                                                     | 9200                 | 36900                             | 9100                              | 36600         | 47300                             | 19700          | 33900              | 60000            | 14000            | 
| 1990-04-01T00:00:00 | 34300                                         | 20500         | 17400           | 66100        | 2600     | 25300                            | 9800        | 18000                 | 12800                              | 21400                                          | 4800                                    | 23000                                                                     | 8900                 | 37000                             | 9000                              | 39100         | 47200                             | 19600          | 34500              | 60300            | 14000            | 
| 1990-05-01T00:00:00 | 34800                                         | 20300         | 17500           | 66400        | 2600     | 25300                            | 9800        | 18100                 | 13000                              | 21300                                          | 4900                                    | 23000                                                                     | 9000                 | 37300                             | 9100                              | 39000         | 47200                             | 19600          | 35400              | 61000            | 14100            | 
| 1990-06-01T00:00:00 | 35600                                         | 20600         | 17700           | 67300        | 2700     | 25700                            | 9800        | 18300                 | 13300                              | 21500                                          | 5000                                    | 23600                                                                     | 8800                 | 37800                             | 9300                              | 38800         | 47900                             | 20200          | 35000              | 58400            | 14200            | 
| 1990-07-01T00:00:00 | 35800                                         | 20700         | 17800           | 67900        | 2800     | 25700                            | 9800        | 18400                 | 13400                              | 21600                                          | 4900                                    | 23800                                                                     | 8300                 | 39000                             | 9400                              | 38600         | 47500                             | 20000          | 34400              | 52300            | 15700            | 
| 1990-08-01T00:00:00 | 36100                                         | 20600         | 17800           | 67400        | 2600     | 26000                            | 9800        | 18400                 | 13600                              | 21600                                          | 4900                                    | 24000                                                                     | 8000                 | 38900                             | 9600                              | 39000         | 47700                             | 20000          | 34100              | 52200            | 15800            | 
| 1990-09-01T00:00:00 | 36100                                         | 20500         | 17700           | 67100        | 2600     | 26100                            | 9900        | 18300                 | 13500                              | 21500                                          | 4900                                    | 24000                                                                     | 8800                 | 38400                             | 9600                              | 38600         | 47000                             | 19700          | 33700              | 49500            | 14200            | 
| 1990-10-01T00:00:00 | 37000                                         | 20400         | 17800           | 67500        | 2700     | 26200                            | 10000       | 18300                 | 13600                              | 21600                                          | 4700                                    | 24400                                                                     | 9200                 | 38600                             | 9400                              | 38800         | 47100                             | 20000          | 33700              | 57200            | 14200            | 
```