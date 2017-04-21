# Funded Capacity Seats and Additional Needs

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/funded-capacity-seats-and-additional-needs) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/ujdf-5byz) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/ujdf-5byz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/ujdf-5byz/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | ujdf-5byz |
| Name | Funded Capacity Seats and Additional Needs |
| Attribution | School Construction Authority (SCA) |
| Category | Education |
| Tags | sca, capacity, schools, education |
| Created | 2016-06-02T14:47:03Z |
| Publication Date | 2016-06-02T14:56:20Z |

## Description

Funded capacity seats and additional needs by district for elementary, middle school, by borough for high school.

## Columns

```ls
| Included | Schema Type    | Field Name                         | Name                               | Data Type | Render Type |
| ======== | ============== | ================================== | ================================== | ========= | =========== |
| No       | time           | :updated_at                        | updated_at                         | meta_data | meta_data   |
| Yes      | series tag     | district                           | District                           | text      | number      |
| Yes      | series tag     | sub_district                       | Sub-District                       | text      | text        |
| Yes      | numeric metric | total_january_2016_identified_need | Total January 2016 Identified Need | number    | number      |
| Yes      | numeric metric | january_2016_funded_need           | January 2016 Funded Need           | number    | number      |
| Yes      | numeric metric | additional_need_unfunded           | Additional Need (Unfunded)         | number    | number      |
| Yes      | numeric metric | number_of_seats_in_scope_design    | Number of Seats in Scope / Design  | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:ujdf-5byz d:2016-06-02T07:47:20.000Z t:sub_district="Tribeca / Village" t:district=2 m:total_january_2016_identified_need=1970 m:january_2016_funded_need=1928 m:additional_need_unfunded=42 m:number_of_seats_in_scope_design=1492

series e:ujdf-5byz d:2016-06-02T07:47:20.000Z t:sub_district="Chelsea/ Midtown West *" t:district=2 m:total_january_2016_identified_need=1262 m:january_2016_funded_need=1262 m:additional_need_unfunded=0

series e:ujdf-5byz d:2016-06-02T07:47:20.000Z t:sub_district="Upper West Side" t:district=3 m:total_january_2016_identified_need=692 m:january_2016_funded_need=692 m:additional_need_unfunded=0 m:number_of_seats_in_scope_design=692
```

## Meta Commands

```ls
metric m:total_january_2016_identified_need p:integer l:"Total January 2016 Identified Need" t:dataTypeName=number

metric m:january_2016_funded_need p:integer l:"January 2016 Funded Need" t:dataTypeName=number

metric m:additional_need_unfunded p:integer l:"Additional Need (Unfunded)" t:dataTypeName=number

metric m:number_of_seats_in_scope_design p:integer l:"Number of Seats in Scope / Design" t:dataTypeName=number

entity e:ujdf-5byz l:"Funded Capacity Seats and Additional Needs" t:attribution="School Construction Authority (SCA)" t:url=https://data.cityofnewyork.us/api/views/ujdf-5byz

property e:ujdf-5byz t:meta.view v:id=ujdf-5byz v:category=Education v:averageRating=0 v:name="Funded Capacity Seats and Additional Needs" v:attribution="School Construction Authority (SCA)"

property e:ujdf-5byz t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:ujdf-5byz t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | district | sub_district                                             | total_january_2016_identified_need | january_2016_funded_need | additional_need_unfunded | number_of_seats_in_scope_design | 
| =========== | ======== | ======================================================== | ================================== | ======================== | ======================== | =============================== | 
| 1464853640  | 2        | Tribeca / Village                                        | 1970                               | 1928                     | 42                       | 1492                            | 
| 1464853640  | 2        | Chelsea/ Midtown West *                                  | 1262                               | 1262                     | 0                        |                                 | 
| 1464853640  | 3        | Upper West Side                                          | 692                                | 692                      | 0                        | 692                             | 
| 1464853640  | 7        | Concourse                                                | 456                                | 456                      | 0                        |                                 | 
| 1464853640  | 7        | Melrose                                                  | 572                                | 0                        | 572                      |                                 | 
| 1464853640  | 8        | Soundview                                                | 572                                | 0                        | 572                      |                                 | 
| 1464853640  | 8        | Throgs Neck                                              | 456                                | 456                      | 0                        | 344                             | 
| 1464853640  | 9        | Highbridge South                                         | 572                                | 0                        | 572                      |                                 | 
| 1464853640  | 10       | Spuyten Duyvil / Riverdale / Fieldston / North Riverdale | 456                                | 456                      | 0                        |                                 | 
| 1464853640  | 10       | Kingsbridge / Norwood / Bedford Park                     | 3384                               | 2104                     | 1280                     | 500                             | 
```