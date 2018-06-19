# DHS Daily Report

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dhs-daily-report-6287f) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/k46n-sa2m) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/k46n-sa2m/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/k46n-sa2m/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | k46n-sa2m |
| Name | DHS Daily Report |
| Attribution | Department of Homeless Services (DHS) |
| Category | Social Services |
| Tags | dhs, homeless, daily, report |
| Created | 2013-08-22T19:20:30Z |
| Publication Date | 2016-10-31T21:00:29Z |

## Description

This dataset includes the daily number of families and individuals residing in the Department of Homeless Services (DHS) shelter system and the daily number of families applying to the DHS shelter system.

## Columns

```ls
| Included | Schema Type    | Field Name                                              | Name                                                   | Data Type     | Render Type   |
| ======== | ============== | ======================================================= | ====================================================== | ============= | ============= |
| Yes      | time           | date_of_census                                          | Date of Census                                         | calendar_date | calendar_date |
| Yes      | numeric metric | total_adults_in_shelter                                 | Total Adults in Shelter                                | number        | number        |
| Yes      | numeric metric | total_children_in_shelter                               | Total Children in Shelter                              | number        | number        |
| Yes      | numeric metric | total_individuals_in_shelter                            | Total Individuals in Shelter                           | number        | number        |
| Yes      | numeric metric | single_adult_men_in_shelter                             | Single Adult Men in Shelter                            | number        | number        |
| Yes      | numeric metric | single_adult_women_in_shelter                           | Single Adult Women in Shelter                          | number        | number        |
| Yes      | numeric metric | total_single_adults_in_shelter                          | Total Single Adults in Shelter                         | number        | number        |
| Yes      | numeric metric | families_with_children_in_shelter                       | Families with Children in Shelter                      | number        | number        |
| Yes      | numeric metric | adults_in_families_with_children_in_shelter             | Adults in Families with Children in Shelter            | number        | number        |
| Yes      | numeric metric | children_in_families_with_children_in_shelter           | Children in Families with Children in Shelter          | number        | number        |
| Yes      | numeric metric | total_individuals_in_families_with_children_in_shelter_ | Total Individuals in Families with Children in Shelter | number        | number        |
| Yes      | numeric metric | adult_families_in_shelter                               | Adult Families in Shelter                              | number        | number        |
| Yes      | numeric metric | individuals_in_adult_families_in_shelter                | Individuals in Adult Families in Shelter               | number        | number        |
```

## Time Field

```ls
Value = date_of_census
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:k46n-sa2m d:2013-08-21T00:00:00.000Z m:total_single_adults_in_shelter=9941 m:single_adult_men_in_shelter=7231 m:individuals_in_adult_families_in_shelter=3811 m:total_adults_in_shelter=28359 m:children_in_families_with_children_in_shelter=21314 m:adults_in_families_with_children_in_shelter=14607 m:families_with_children_in_shelter=10261 m:single_adult_women_in_shelter=2710 m:total_individuals_in_shelter=49673 m:adult_families_in_shelter=1796 m:total_individuals_in_families_with_children_in_shelter_=35921 m:total_children_in_shelter=21314

series e:k46n-sa2m d:2013-08-22T00:00:00.000Z m:total_single_adults_in_shelter=9917 m:single_adult_men_in_shelter=7201 m:individuals_in_adult_families_in_shelter=3827 m:total_adults_in_shelter=28366 m:children_in_families_with_children_in_shelter=21324 m:adults_in_families_with_children_in_shelter=14622 m:families_with_children_in_shelter=10274 m:single_adult_women_in_shelter=2716 m:total_individuals_in_shelter=49690 m:adult_families_in_shelter=1803 m:total_individuals_in_families_with_children_in_shelter_=35946 m:total_children_in_shelter=21324

series e:k46n-sa2m d:2013-08-23T00:00:00.000Z m:total_single_adults_in_shelter=9820 m:single_adult_men_in_shelter=7149 m:individuals_in_adult_families_in_shelter=3826 m:total_adults_in_shelter=28257 m:children_in_families_with_children_in_shelter=21291 m:adults_in_families_with_children_in_shelter=14611 m:families_with_children_in_shelter=10266 m:single_adult_women_in_shelter=2671 m:total_individuals_in_shelter=49548 m:adult_families_in_shelter=1802 m:total_individuals_in_families_with_children_in_shelter_=35902 m:total_children_in_shelter=21291
```

## Meta Commands

```ls
metric m:total_adults_in_shelter p:integer l:"Total Adults in Shelter" d:"The number of single adults, individuals in adult families, and adults in families with children in shelter as of the date of census" t:dataTypeName=number

metric m:total_children_in_shelter p:integer l:"Total Children in Shelter" d:"The number of children in families with children in shelter as of the date of census" t:dataTypeName=number

metric m:total_individuals_in_shelter p:integer l:"Total Individuals in Shelter" d:"The number of single adults, individuals in adult families, and adults and children in families with children in shelter as of the date of census" t:dataTypeName=number

metric m:single_adult_men_in_shelter p:integer l:"Single Adult Men in Shelter" t:dataTypeName=number

metric m:single_adult_women_in_shelter p:integer l:"Single Adult Women in Shelter" t:dataTypeName=number

metric m:total_single_adults_in_shelter p:integer l:"Total Single Adults in Shelter" d:"The number of single adult men and women in shelter as of the date of census" t:dataTypeName=number

metric m:families_with_children_in_shelter p:integer l:"Families with Children in Shelter" t:dataTypeName=number

metric m:adults_in_families_with_children_in_shelter p:integer l:"Adults in Families with Children in Shelter" t:dataTypeName=number

metric m:children_in_families_with_children_in_shelter p:integer l:"Children in Families with Children in Shelter" t:dataTypeName=number

metric m:total_individuals_in_families_with_children_in_shelter_ p:integer l:"Total Individuals in Families with Children in Shelter" d:"The number of adults and children in families with children in shelter as of the date of census" t:dataTypeName=number

metric m:adult_families_in_shelter p:integer l:"Adult Families in Shelter" t:dataTypeName=number

metric m:individuals_in_adult_families_in_shelter p:integer l:"Individuals in Adult Families in Shelter" t:dataTypeName=number

entity e:k46n-sa2m l:"DHS Daily Report" t:attribution="Department of Homeless Services (DHS)" t:url=https://data.cityofnewyork.us/api/views/k46n-sa2m

property e:k46n-sa2m t:meta.view v:id=k46n-sa2m v:category="Social Services" v:attributionLink=http://www.nyc.gov/html/dhs/downloads/pdf/dailyreport.pdf v:averageRating=0 v:name="DHS Daily Report" v:attribution="Department of Homeless Services (DHS)"

property e:k46n-sa2m t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:k46n-sa2m t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| date_of_census      | total_adults_in_shelter | total_children_in_shelter | total_individuals_in_shelter | single_adult_men_in_shelter | single_adult_women_in_shelter | total_single_adults_in_shelter | families_with_children_in_shelter | adults_in_families_with_children_in_shelter | children_in_families_with_children_in_shelter | total_individuals_in_families_with_children_in_shelter_ | adult_families_in_shelter | individuals_in_adult_families_in_shelter | 
| =================== | ======================= | ========================= | ============================ | =========================== | ============================= | ============================== | ================================= | =========================================== | ============================================= | ======================================================= | ========================= | ======================================== | 
| 2013-08-21T00:00:00 | 28359                   | 21314                     | 49673                        | 7231                        | 2710                          | 9941                           | 10261                             | 14607                                       | 21314                                         | 35921                                                   | 1796                      | 3811                                     | 
| 2013-08-22T00:00:00 | 28366                   | 21324                     | 49690                        | 7201                        | 2716                          | 9917                           | 10274                             | 14622                                       | 21324                                         | 35946                                                   | 1803                      | 3827                                     | 
| 2013-08-23T00:00:00 | 28257                   | 21291                     | 49548                        | 7149                        | 2671                          | 9820                           | 10266                             | 14611                                       | 21291                                         | 35902                                                   | 1802                      | 3826                                     | 
| 2013-08-24T00:00:00 | 28274                   | 21343                     | 49617                        | 7110                        | 2690                          | 9800                           | 10291                             | 14650                                       | 21343                                         | 35993                                                   | 1801                      | 3824                                     | 
| 2013-08-25T00:00:00 | 28458                   | 21400                     | 49858                        | 7230                        | 2704                          | 9934                           | 10324                             | 14694                                       | 21400                                         | 36094                                                   | 1804                      | 3830                                     | 
| 2013-08-26T00:00:00 | 28485                   | 21392                     | 49877                        | 7252                        | 2704                          | 9956                           | 10307                             | 14688                                       | 21392                                         | 36080                                                   | 1809                      | 3841                                     | 
| 2013-08-27T00:00:00 | 28414                   | 21322                     | 49736                        | 7209                        | 2713                          | 9922                           | 10277                             | 14640                                       | 21322                                         | 35962                                                   | 1813                      | 3852                                     | 
| 2013-08-28T00:00:00 | 28428                   | 21325                     | 49753                        | 7229                        | 2721                          | 9950                           | 10284                             | 14647                                       | 21325                                         | 35972                                                   | 1803                      | 3831                                     | 
| 2013-08-29T00:00:00 | 28396                   | 21412                     | 49808                        | 7151                        | 2709                          | 9860                           | 10316                             | 14696                                       | 21412                                         | 36108                                                   | 1807                      | 3840                                     | 
| 2013-08-30T00:00:00 | 28182                   | 21343                     | 49525                        | 7032                        | 2653                          | 9685                           | 10281                             | 14651                                       | 21343                                         | 35994                                                   | 1811                      | 3846                                     | 
```