# Customer Survey Responses

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/customer-survey-responses) |
| Metadata | [Link](https://data.lacity.org/api/views/uj6a-ab47) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/uj6a-ab47/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/uj6a-ab47/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | uj6a-ab47 |
| Name | Customer Survey Responses |
| Attribution | El Pueblo Historical Monument |
| Category | A Livable and Sustainable City |
| Tags | tourism, survey |
| Created | 2014-05-30T23:48:25Z |
| Publication Date | 2017-03-20T22:27:10Z |

## Description

Questionnaires are provided to El Pueblo visitors; a minimum of 75 are tabulated each month.

## Columns

```ls
| Included | Schema Type    | Field Name                            | Name                                  | Data Type     | Render Type   |
| ======== | ============== | ===================================== | ===================================== | ============= | ============= |
| Yes      | time           | month                                 | Month                                 | calendar_date | calendar_date |
| Yes      | numeric metric | knew_that_el_pueblo_offers_free_tours | Knew that El Pueblo Offers Free Tours | percent       | percent       |
| Yes      | numeric metric | local_residents                       | Local Residents                       | percent       | percent       |
| Yes      | numeric metric | out_of_state_visitors                 | Out of State Visitors                 | percent       | percent       |
| Yes      | numeric metric | international_visitors                | International Visitors                | percent       | percent       |
| Yes      | numeric metric | visited_a_restaurant                  | Visited a Restaurant                  | percent       | percent       |
| Yes      | numeric metric | purchased_an_item_on_olvera_st        | Purchased an Item on Olvera St        | percent       | percent       |
| Yes      | numeric metric | visited_a_museum                      | Visited a Museum                      | percent       | percent       |
| Yes      | numeric metric | came_for_a_specific_event_exhibit     | Came for a Specific Event/Exhibit     | percent       | percent       |
| Yes      | numeric metric | arrived_on_bus_charter_tour           | Arrived on Bus/Charter Tour           | percent       | percent       |
| Yes      | numeric metric | arrived_by_public_transit             | Arrived by Public Transit             | percent       | percent       |
| Yes      | numeric metric | enjoyed_the_visit                     | Enjoyed the Visit                     | percent       | percent       |
| Yes      | numeric metric | would_recommend_el_pueblo_to_a_friend | Would Recommend El Pueblo to a Friend | percent       | percent       |
```

## Time Field

```ls
Value = month
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:uj6a-ab47 d:2014-01-01T00:00:00.000Z m:knew_that_el_pueblo_offers_free_tours=50 m:arrived_by_public_transit=31 m:local_residents=59 m:enjoyed_the_visit=97 m:international_visitors=15 m:out_of_state_visitors=17 m:visited_a_restaurant=62 m:visited_a_museum=77 m:would_recommend_el_pueblo_to_a_friend=97 m:purchased_an_item_on_olvera_st=62 m:came_for_a_specific_event_exhibit=10 m:arrived_on_bus_charter_tour=11

series e:uj6a-ab47 d:2014-02-01T00:00:00.000Z m:knew_that_el_pueblo_offers_free_tours=35 m:arrived_by_public_transit=35 m:local_residents=49 m:enjoyed_the_visit=94 m:international_visitors=8 m:out_of_state_visitors=26 m:visited_a_restaurant=65 m:visited_a_museum=78 m:would_recommend_el_pueblo_to_a_friend=96 m:purchased_an_item_on_olvera_st=67 m:came_for_a_specific_event_exhibit=13 m:arrived_on_bus_charter_tour=21

series e:uj6a-ab47 d:2014-03-01T00:00:00.000Z m:knew_that_el_pueblo_offers_free_tours=25 m:arrived_by_public_transit=30 m:local_residents=58 m:enjoyed_the_visit=95 m:international_visitors=19 m:out_of_state_visitors=26 m:visited_a_restaurant=77 m:visited_a_museum=70 m:would_recommend_el_pueblo_to_a_friend=96 m:purchased_an_item_on_olvera_st=54 m:came_for_a_specific_event_exhibit=14 m:arrived_on_bus_charter_tour=15
```

## Meta Commands

```ls
metric m:knew_that_el_pueblo_offers_free_tours p:integer l:"Knew that El Pueblo Offers Free Tours" t:dataTypeName=percent

metric m:local_residents p:integer l:"Local Residents" t:dataTypeName=percent

metric m:out_of_state_visitors p:integer l:"Out of State Visitors" t:dataTypeName=percent

metric m:international_visitors p:integer l:"International Visitors" t:dataTypeName=percent

metric m:visited_a_restaurant p:integer l:"Visited a Restaurant" t:dataTypeName=percent

metric m:purchased_an_item_on_olvera_st p:integer l:"Purchased an Item on Olvera St" t:dataTypeName=percent

metric m:visited_a_museum p:integer l:"Visited a Museum" t:dataTypeName=percent

metric m:came_for_a_specific_event_exhibit p:integer l:"Came for a Specific Event/Exhibit" t:dataTypeName=percent

metric m:arrived_on_bus_charter_tour p:integer l:"Arrived on Bus/Charter Tour" t:dataTypeName=percent

metric m:arrived_by_public_transit p:integer l:"Arrived by Public Transit" t:dataTypeName=percent

metric m:enjoyed_the_visit p:integer l:"Enjoyed the Visit" t:dataTypeName=percent

metric m:would_recommend_el_pueblo_to_a_friend p:integer l:"Would Recommend El Pueblo to a Friend" t:dataTypeName=percent

entity e:uj6a-ab47 l:"Customer Survey Responses" t:attribution="El Pueblo Historical Monument" t:url=https://data.lacity.org/api/views/uj6a-ab47

property e:uj6a-ab47 t:meta.view v:id=uj6a-ab47 v:category="A Livable and Sustainable City" v:attributionLink=http://elpueblo.lacity.org/index.htm v:averageRating=0 v:name="Customer Survey Responses" v:attribution="El Pueblo Historical Monument"

property e:uj6a-ab47 t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:uj6a-ab47 t:meta.view.owner v:id=rz8e-rup2 v:profileImageUrlMedium=/api/users/rz8e-rup2/profile_images/THUMB v:profileImageUrlLarge=/api/users/rz8e-rup2/profile_images/LARGE v:screenName="El Pueblo OpenData" v:profileImageUrlSmall=/api/users/rz8e-rup2/profile_images/TINY v:displayName="El Pueblo OpenData"

property e:uj6a-ab47 t:meta.view.tableauthor v:id=rz8e-rup2 v:profileImageUrlMedium=/api/users/rz8e-rup2/profile_images/THUMB v:profileImageUrlLarge=/api/users/rz8e-rup2/profile_images/LARGE v:screenName="El Pueblo OpenData" v:profileImageUrlSmall=/api/users/rz8e-rup2/profile_images/TINY v:roleName=publisher v:displayName="El Pueblo OpenData"
```

## Top Records

```ls
| month               | knew_that_el_pueblo_offers_free_tours | local_residents | out_of_state_visitors | international_visitors | visited_a_restaurant | purchased_an_item_on_olvera_st | visited_a_museum | came_for_a_specific_event_exhibit | arrived_on_bus_charter_tour | arrived_by_public_transit | enjoyed_the_visit | would_recommend_el_pueblo_to_a_friend | 
| =================== | ===================================== | =============== | ===================== | ====================== | ==================== | ============================== | ================ | ================================= | =========================== | ========================= | ================= | ===================================== | 
| 2014-01-01T00:00:00 | 50                                    | 59              | 17                    | 15                     | 62                   | 62                             | 77               | 10                                | 11                          | 31                        | 97                | 97                                    | 
| 2014-02-01T00:00:00 | 35                                    | 49              | 26                    | 8                      | 65                   | 67                             | 78               | 13                                | 21                          | 35                        | 94                | 96                                    | 
| 2014-03-01T00:00:00 | 25                                    | 58              | 26                    | 19                     | 77                   | 54                             | 70               | 14                                | 15                          | 30                        | 95                | 96                                    | 
| 2014-04-01T00:00:00 | 29                                    | 47              | 17                    | 21                     | 69                   | 56                             | 76               | 27                                | 21                          | 28                        | 93                | 83                                    | 
| 2014-05-01T00:00:00 | 22                                    | 49              | 17                    | 7                      | 51                   | 55                             | 85               | 17                                | 19                          | 32                        | 97                | 96                                    | 
| 2014-06-01T00:00:00 | 21                                    | 61              | 13                    | 7                      | 55                   | 65                             | 87               | 9                                 | 13                          | 35                        | 97                | 99                                    | 
| 2014-07-01T00:00:00 | 22                                    | 41              | 28                    | 6                      | 48                   | 72                             | 90               | 9                                 | 9                           | 27                        | 95                | 93                                    | 
| 2014-08-01T00:00:00 | 15                                    | 49              | 17                    | 15                     | 36                   | 49                             | 73               | 1                                 | 16                          | 24                        | 93                | 100                                   | 
| 2014-10-02T00:00:00 | 27                                    | 56              | 12                    | 14                     | 50                   | 44                             | 87               | 45                                | 14                          | 34                        | 100               | 100                                   | 
| 2014-11-01T00:00:00 | 22                                    | 66              | 16                    | 12                     | 52                   | 53                             | 83               | 27                                | 18                          | 41                        | 100               | 100                                   | 
```