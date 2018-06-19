# Attribution of Complaints to Different Bureaus

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/attribution-of-complaints-to-different-bureaus-bdb58) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/wwsa-q2dq) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/wwsa-q2dq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/wwsa-q2dq/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | wwsa-q2dq |
| Name | Attribution of Complaints to Different Bureaus |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | City Government |
| Tags | ccrb, attribution, complaints, bureau |
| Created | 2013-02-25T21:41:43Z |
| Publication Date | 2013-06-21T20:04:13Z |

## Description

This is the table compiled in one data-set from different bureaus representing the attribution of complaints

## Columns

```ls
| Included | Schema Type    | Field Name                                                        | Name                                    | Data Type | Render Type |
| ======== | ============== | ================================================================= | ======================================= | ========= | =========== |
| Yes      | time           | year_attribution_of_complaint_to_respective_agencies              | Year                                    | number    | text        |
| Yes      | numeric metric | patrol_services_bureau                                            | Patrol Services Bureau                  | number    | text        |
| Yes      | numeric metric | other_commands                                                    | Other Commands                          | number    | text        |
| Yes      | numeric metric | special_operation_division                                        | Special Operation Division              | number    | text        |
| Yes      | numeric metric | other_patrol_services_bureau                                      | Other Patrol Services Bureau            | number    | text        |
| Yes      | numeric metric | special_operations_division                                       | Special Operations Division             | number    | text        |
| Yes      | numeric metric | traffic_control_division                                          | Traffic Control Division                | number    | text        |
| Yes      | numeric metric | transit_bureau                                                    | Transit Bureau                          | number    | text        |
| Yes      | numeric metric | housing_bureau                                                    | Housing Bureau                          | number    | text        |
| Yes      | numeric metric | organizaed_crime_control_bureau                                   | Organized Crime Control Bureau          | number    | text        |
| Yes      | numeric metric | detective_bureau                                                  | Detective Bureau                        | number    | text        |
| Yes      | numeric metric | attribution_of_complaint_to_deputy_comissioners_and_misc_commands | Deputy Commissioners and Misc. Commands | number    | text        |
| Yes      | numeric metric | internal_affairs_bureau                                           | Internal Affairs Bureau                 | number    | number      |
| Yes      | numeric metric | criminal_justice_bureau                                           | Criminal Justice Bureau                 | number    | number      |
| Yes      | numeric metric | support_services_bureau                                           | Support Services Bureau                 | number    | number      |
| Yes      | numeric metric | personnel_bureau                                                  | Personnel Bureau                        | number    | number      |
```

## Time Field

```ls
Value = year_attribution_of_complaint_to_respective_agencies
Format & Zone = yyyy
```

## Data Commands

```ls
series e:wwsa-q2dq d:2009-01-01T00:00:00.000Z m:traffic_control_division=57 m:special_operations_division=16 m:support_services_bureau=0 m:patrol_services_bureau=3111 m:attribution_of_complaint_to_deputy_comissioners_and_misc_commands=26 m:criminal_justice_bureau=61 m:detective_bureau=212 m:special_operation_division=16 m:personnel_bureau=2 m:housing_bureau=289 m:internal_affairs_bureau=3 m:transit_bureau=198 m:other_patrol_services_bureau=3 m:other_commands=8539 m:organizaed_crime_control_bureau=294

series e:wwsa-q2dq d:2010-01-01T00:00:00.000Z m:traffic_control_division=61 m:special_operations_division=18 m:support_services_bureau=4 m:patrol_services_bureau=3289 m:attribution_of_complaint_to_deputy_comissioners_and_misc_commands=21 m:criminal_justice_bureau=50 m:detective_bureau=184 m:special_operation_division=18 m:personnel_bureau=2 m:housing_bureau=301 m:internal_affairs_bureau=0 m:transit_bureau=177 m:other_patrol_services_bureau=3 m:other_commands=7382 m:organizaed_crime_control_bureau=328

series e:wwsa-q2dq d:2011-01-01T00:00:00.000Z m:traffic_control_division=60 m:special_operations_division=21 m:support_services_bureau=4 m:patrol_services_bureau=3166 m:attribution_of_complaint_to_deputy_comissioners_and_misc_commands=45 m:criminal_justice_bureau=36 m:detective_bureau=160 m:special_operation_division=21 m:personnel_bureau=6 m:housing_bureau=243 m:internal_affairs_bureau=4 m:transit_bureau=175 m:other_patrol_services_bureau=0 m:other_commands=7013 m:organizaed_crime_control_bureau=351
```

## Meta Commands

```ls
metric m:patrol_services_bureau p:integer l:"Patrol Services Bureau" t:dataTypeName=number

metric m:other_commands p:integer l:"Other Commands" t:dataTypeName=number

metric m:special_operation_division p:integer l:"Special Operation Division" t:dataTypeName=number

metric m:other_patrol_services_bureau p:integer l:"Other Patrol Services Bureau" t:dataTypeName=number

metric m:special_operations_division p:integer l:"Special Operations Division" t:dataTypeName=number

metric m:traffic_control_division p:integer l:"Traffic Control Division" t:dataTypeName=number

metric m:transit_bureau p:integer l:"Transit Bureau" t:dataTypeName=number

metric m:housing_bureau p:integer l:"Housing Bureau" t:dataTypeName=number

metric m:organizaed_crime_control_bureau p:integer l:"Organized Crime Control Bureau" t:dataTypeName=number

metric m:detective_bureau p:integer l:"Detective Bureau" t:dataTypeName=number

metric m:attribution_of_complaint_to_deputy_comissioners_and_misc_commands p:integer l:"Deputy Commissioners and Misc. Commands" t:dataTypeName=number

metric m:internal_affairs_bureau p:integer l:"Internal Affairs Bureau" t:dataTypeName=number

metric m:criminal_justice_bureau p:integer l:"Criminal Justice Bureau" t:dataTypeName=number

metric m:support_services_bureau p:integer l:"Support Services Bureau" t:dataTypeName=number

metric m:personnel_bureau p:integer l:"Personnel Bureau" t:dataTypeName=number

entity e:wwsa-q2dq l:"Attribution of Complaints to Different Bureaus" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/wwsa-q2dq

property e:wwsa-q2dq t:meta.view v:id=wwsa-q2dq v:category="City Government" v:attributionLink=http://www.nyc.gov/html/ccrb/pdf/ccrbappendices2011.pdf v:averageRating=0 v:name="Attribution of Complaints to Different Bureaus" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:wwsa-q2dq t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:wwsa-q2dq t:meta.view.tableauthor v:id=iacr-duv5 v:screenName=Tejas.Patel v:displayName=Tejas.Patel
```

## Top Records

```ls
| year_attribution_of_complaint_to_respective_agencies | patrol_services_bureau | other_commands | special_operation_division | other_patrol_services_bureau | special_operations_division | traffic_control_division | transit_bureau | housing_bureau | organizaed_crime_control_bureau | detective_bureau | attribution_of_complaint_to_deputy_comissioners_and_misc_commands | internal_affairs_bureau | criminal_justice_bureau | support_services_bureau | personnel_bureau | 
| ==================================================== | ====================== | ============== | ========================== | ============================ | =========================== | ======================== | ============== | ============== | =============================== | ================ | ================================================================= | ======================= | ======================= | ======================= | ================ | 
| 2009                                                 | 3111                   | 8539           | 16                         | 3                            | 16                          | 57                       | 198            | 289            | 294                             | 212              | 26                                                                | 3                       | 61                      | 0                       | 2                | 
| 2010                                                 | 3289                   | 7382           | 18                         | 3                            | 18                          | 61                       | 177            | 301            | 328                             | 184              | 21                                                                | 0                       | 50                      | 4                       | 2                | 
| 2011                                                 | 3166                   | 7013           | 21                         | 0                            | 21                          | 60                       | 175            | 243            | 351                             | 160              | 45                                                                | 4                       | 36                      | 4                       | 6                | 
```