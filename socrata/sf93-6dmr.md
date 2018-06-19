# Envista Projects for Utility Excavation and Paving

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/envista-projects-for-utility-excavation-and-paving-679e2) |
| Metadata | [Link](https://data.sfgov.org/api/views/sf93-6dmr) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/sf93-6dmr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/sf93-6dmr/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | sf93-6dmr |
| Name | Envista Projects for Utility Excavation and Paving |
| Attribution | San Francisco Department of Public Works |
| Category | City Infrastructure |
| Tags | utility, excavation, paving, envista, utilities, construction, noi, five, 5, year, plan |
| Created | 2013-04-11T05:34:11Z |
| Publication Date | 2015-09-11T18:08:07Z |

## Description

Envista Projects for Utility Excavation and Paving. Envista is used by city agencies and private utilities to coordinate utility and paving work in public right of way.

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                      | Data Type     | Render Type   |
| ======== | ============== | ========================= | ========================= | ============= | ============= |
| Yes      | series tag     | project_id                | project_id                | text          | text          |
| Yes      | series tag     | project_name_full         | project_name_full         | text          | text          |
| Yes      | series tag     | owner                     | owner                     | text          | text          |
| Yes      | series tag     | description_full          | description_full          | text          | text          |
| Yes      | series tag     | dpw_project_class         | dpw_project_class         | text          | text          |
| Yes      | series tag     | facility_type             | facility_type             | text          | text          |
| Yes      | series tag     | project_status            | project_status            | text          | text          |
| Yes      | time           | start_date                | start_date                | calendar_date | calendar_date |
| No       |                | end_date                  | end_date                  | calendar_date | calendar_date |
| Yes      | numeric metric | duration                  | duration                  | number        | number        |
| Yes      | series tag     | facility_indicator        | facility_indicator        | text          | text          |
| Yes      | series tag     | facility_subindicator     | facility_subindicator     | text          | text          |
| Yes      | series tag     | group_code                | group_code                | text          | text          |
| Yes      | series tag     | facility_type_description | facility_type_description | text          | text          |
| No       |                | create_date               | create_date               | calendar_date | calendar_date |
| No       |                | modify_date               | modify_date               | calendar_date | calendar_date |
| Yes      | series tag     | project_type              | project_type              | text          | text          |
| Yes      | series tag     | project_url               | project_url               | text          | text          |
| Yes      | numeric metric | cnn                       | cnn                       | number        | number        |
| Yes      | series tag     | street_name               | street_name               | text          | text          |
| Yes      | series tag     | limits                    | limits                    | text          | text          |
| No       |                | x                         | X                         | number        | number        |
| No       |                | y                         | Y                         | number        | number        |
| No       |                | latitude                  | Latitude                  | number        | number        |
| No       |                | longitude                 | Longitude                 | number        | number        |
```

## Time Field

```ls
Value = start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = end_date,create_date,modify_date,x,y,latitude,longitude
```

## Data Commands

```ls
series e:sf93-6dmr d:2018-04-02T00:00:00.000Z t:limits="CALIFORNIA ST to CLEMENT ST (300 - 399)" t:project_name_full="RO Streetlight Loop 149" t:project_status=Planned t:facility_type_description="Street Lighting" t:project_id="RO Streetlight Loop 149" t:street_name="26TH AVE" t:owner=PG&E t:facility_type=Electric t:facility_indicator="Street Lighting" t:dpw_project_class=Electric m:duration=120 m:cnn=1471000

series e:sf93-6dmr d:2017-01-01T00:00:00.000Z t:project_name_full="Intersection Modifications" t:project_status=Planned t:project_id=SSD_UPI_2015.071 t:owner="SF MTA SS - Transportation Engineering (Capital)" t:facility_type=Roadway t:dpw_project_class=Roadway t:description_full="Project Description: Reconfigure the intersection by removing the southwest leg of Crisp Avenue and creating limited access for the eastern block of Palou Avenue. Restripe the Crisp Avenue westbound approach to provide two approach lanes, a left turn lane and a shared through, left- and right-turn lane. Reconfigure the northbound Griffith Street approach to provide two lanes, a shared left/through/right turn lane and a dedicated right turn lane. Reconfigure the eastbound approach on Palou Avenue to provide two approach lanes, a left-turn lane and a shared through/right-turn lane.[Funding and Implementation Strategy: Project Sponsor shall fund and implement.] [Development Project: Candlestick Point - Hunters Point Shipyard Phase II] [Case Number: 2007.0946] [Commitment Reference: Table 6.1.1] [SFMTA Role: N/A]" m:duration=1095 m:cnn=19072000

series e:sf93-6dmr d:2017-01-01T00:00:00.000Z t:limits="TARAVAL ST intersection" t:project_name_full="Santiago 2" t:project_status=Started t:group_code="2017 Confirmed" t:facility_type_description="Main-Distribution / Replacement" t:project_id=31192823 t:street_name="25TH AVE" t:owner=PG&E t:facility_type=Gas t:facility_subindicator=Main-Distribution t:project_type=Replacement t:facility_indicator=Gas t:dpw_project_class=Gas m:duration=364 m:cnn=23263000
```

## Meta Commands

```ls
metric m:duration p:integer l:duration t:dataTypeName=number

metric m:cnn p:integer l:cnn t:dataTypeName=number

entity e:sf93-6dmr l:"Envista Projects for Utility Excavation and Paving" t:attribution="San Francisco Department of Public Works" t:url=https://data.sfgov.org/api/views/sf93-6dmr

property e:sf93-6dmr t:meta.view v:id=sf93-6dmr v:category="City Infrastructure" v:attributionLink=http://www.sfdpw.org v:averageRating=0 v:name="Envista Projects for Utility Excavation and Paving" v:attribution="San Francisco Department of Public Works"

property e:sf93-6dmr t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:sf93-6dmr t:meta.view.owner v:id=rcpp-nrjq v:profileImageUrlMedium=/api/users/rcpp-nrjq/profile_images/THUMB v:profileImageUrlLarge=/api/users/rcpp-nrjq/profile_images/LARGE v:screenName="Public Works" v:profileImageUrlSmall=/api/users/rcpp-nrjq/profile_images/TINY v:displayName="Public Works"

property e:sf93-6dmr t:meta.view.tableauthor v:id=rcpp-nrjq v:profileImageUrlMedium=/api/users/rcpp-nrjq/profile_images/THUMB v:profileImageUrlLarge=/api/users/rcpp-nrjq/profile_images/LARGE v:screenName="Public Works" v:profileImageUrlSmall=/api/users/rcpp-nrjq/profile_images/TINY v:roleName=editor v:displayName="Public Works"
```

## Top Records

```ls
| project_id              | project_name_full                                                                                    | owner                                            | description_full                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | dpw_project_class | facility_type | project_status | start_date          | end_date            | duration | facility_indicator | facility_subindicator | group_code     | facility_type_description       | create_date         | modify_date         | project_type | project_url | cnn      | street_name   | limits                                         | x             | y             | latitude         | longitude         | 
| ======================= | ==================================================================================================== | ================================================ | ==================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================== | ================= | ============= | ============== | =================== | =================== | ======== | ================== | ===================== | ============== | =============================== | =================== | =================== | ============ | =========== | ======== | ============= | ============================================== | ============= | ============= | ================ | ================= | 
| RO Streetlight Loop 149 | RO Streetlight Loop 149                                                                              | PG&E                                             |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | Electric          | Electric      | Planned        | 2018-04-02T00:00:00 | 2018-07-31T23:59:00 | 120      | Street Lighting    |                       |                | Street Lighting                 | 2015-01-21T17:41:00 | 2016-07-01T11:32:00 |              |             | 1471000  | 26TH AVE      | CALIFORNIA ST to CLEMENT ST (300 - 399)        | 5987769.36338 | 2113624.68381 | 37.7829040365153 | -122.486017016442 | 
| SSD_UPI_2015.071        | Intersection Modifications                                                                           | SF MTA SS - Transportation Engineering (Capital) | Project Description: Reconfigure the intersection by removing the southwest leg of Crisp Avenue and creating limited access for the eastern block of Palou Avenue. Restripe the Crisp Avenue westbound approach to provide two approach lanes, a left turn lane and a shared through, left- and right-turn lane. Reconfigure the northbound Griffith Street approach to provide two lanes, a shared left/through/right turn lane and a dedicated right turn lane. Reconfigure the eastbound approach on Palou Avenue to provide two approach lanes, a left-turn lane and a shared through/right-turn lane.[Funding and Implementation Strategy: Project Sponsor shall fund and implement.] [Development Project: Candlestick Point - Hunters Point Shipyard Phase II] [Case Number: 2007.0946] [Commitment Reference: Table 6.1.1] [SFMTA Role: N/A] | Roadway           | Roadway       | Planned        | 2017-01-01T00:00:00 | 2020-01-01T23:59:00 | 1095     |                    |                       |                |                                 | 2015-10-08T12:07:00 | 2017-02-23T18:16:00 |              |             | 19072000 |               |                                                | 6019494.14094 | 2092427.56981 | 37.7264988356332 | -122.374791855973 | 
| 31192823                | Santiago 2                                                                                           | PG&E                                             |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | Gas               | Gas           | Started        | 2017-01-01T00:00:00 | 2017-12-31T23:59:00 | 364      | Gas                | Main-Distribution     | 2017 Confirmed | Main-Distribution / Replacement | 2015-10-19T13:46:00 | 2017-01-01T01:04:00 | Replacement  |             | 23263000 | 25TH AVE      | TARAVAL ST intersection                        | 5988585.32248 | 2098989.47907 | 37.7427672688711 | -122.482121648487 | 
| 2491                    | 1516-007 60-inch CSPL2 Replacement from South County Line to University Mound Reservoir              | SF PUC Water                                     | ?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | Water             | Water         | Planned        | 2021-07-01T00:00:00 | 2023-07-01T23:59:00 | 730      |                    |                       |                |                                 | 2013-03-30T13:17:00 | 2017-02-23T18:18:00 |              |             | 10410000 | PHELPS ST     | CARROLL AVE to DONNER AVE (2600 - 2699)        | 6011900.7163  | 2093454.50907 | 37.7288979283616 | -122.40111430248  | 
| 1415-028                | Cathodic Protection for 36-, 30- & 24-inch Steel Sutro Reservoir Outlet Pipes from pump to reservoir | SF PUC Water                                     | NTP unknown                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | Water             | Water         | Planned        | 2025-08-01T00:00:00 | 2026-08-31T23:59:00 | 395      |                    |                       |                |                                 | 2015-01-28T10:47:00 | 2017-02-23T18:16:00 |              |             | 33504000 | EUCALYPTUS DR | MEADOWBROOK DR intersection                    | 5987829.20107 | 2094724.59747 | 37.7310130116061 | -122.484423328859 | 
| GSPBVL201802            | LE CONTE 2 - 14D                                                                                     | PG&E                                             |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | Gas               | Gas           | Planned        | 2018-01-01T00:00:00 | 2018-12-31T23:59:00 | 364      |                    |                       |                |                                 | 2014-02-27T16:35:00 | 2015-05-27T14:50:00 |              |             | 20460000 | 03RD ST       | HWY 101 S ON RAMP \ JAMESTOWN AVE intersection | 6013137.11221 | 2090272.94658 | 37.7202308985929 | -122.396617026085 | 
| 5041                    | 19-001 Lake Street                                                                                   | SF PUC Water                                     | ?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | Water             | Water         | Planned        | 2022-05-22T00:00:00 | 2023-05-01T23:59:00 | 344      |                    |                       |                |                                 | 2013-03-30T13:36:00 | 2017-02-23T18:18:00 |              |             | 8019000  | LAKE ST       | 11TH AVE to 12TH AVE (1000 - 1099)             | 5992256.65394 | 2114807.49072 | 37.7864121823544 | -122.470579175882 | 
| Leland Phase 2          | Leland Phase 2                                                                                       | PG&E                                             |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | Gas               | Gas           | Planned        | 2018-03-01T00:00:00 | 2018-12-31T23:59:00 | 305      | Gas                | Main-Distribution     |                | Main-Distribution / Replacement | 2013-05-06T19:51:00 | 2015-05-27T14:50:00 | Replacement  |             | 8295000  | LELAND AVE    | PEABODY ST to RUTLAND ST (150 - 199)           | 6010097.12523 | 2087495.56833 | 37.7124351289855 | -122.406929650031 | 
| 2249                    | 1314-020 8-inch Water Main Replacement on Filbert Street from Baker to Van Ness Streets              | SF PUC Water                                     | ...?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | Water             | Water         | Planned        | 2023-10-01T00:00:00 | 2024-08-01T23:59:00 | 305      |                    |                       |                |                                 | 2013-03-30T13:13:00 | 2017-02-23T18:19:00 |              |             | 26676000 | FILBERT ST    | FILLMORE ST intersection                       | 6002427.4588  | 2118823.18463 | 37.7980211088007 | -122.435678212222 | 
| 2427                    | 14-011 Bryant/Federal/Shipley/Morris                                                                 | SF PUC Water                                     | ?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | Water             | Water         | Planned        | 2025-02-01T00:00:00 | 2026-02-01T23:59:00 | 365      |                    |                       |                |                                 | 2013-03-30T13:16:00 | 2017-02-23T18:16:00 |              |             | 23876000 | BRYANT ST     | LANGTON ST intersection                        | 6011027.82112 | 2109845.87627 | 37.7738562907028 | -122.405285801542 | 
```