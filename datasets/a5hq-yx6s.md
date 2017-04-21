# King County Master Calendar

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/king-county-master-calendar-dev) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/a5hq-yx6s) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/a5hq-yx6s/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/a5hq-yx6s/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | a5hq-yx6s |
| Name | King County Master Calendar |
| Attribution | King County |
| Category | Operations |
| Tags | calendar |
| Created | 2017-01-12T00:53:05Z |
| Publication Date | 2017-04-19T20:32:39Z |

## Description

Master calendar for King County

## Columns

```ls
| Included | Schema Type | Field Name                      | Name                            | Data Type     | Render Type   |
| ======== | =========== | =============================== | =============================== | ============= | ============= |
| Yes      | time        | start_time                      | Start time                      | calendar_date | calendar_date |
| No       |             | end_time                        | End time                        | calendar_date | calendar_date |
| Yes      | series tag  | event_name                      | Event Name                      | html          | html          |
| Yes      | series tag  | event_description_details       | Event description/details       | html          | html          |
| Yes      | series tag  | location_name                   | Location name                   | text          | text          |
| Yes      | series tag  | url                             | URL                             | url           | url           |
| Yes      | series tag  | contact_name                    | Contact name                    | text          | text          |
| Yes      | series tag  | contact_email                   | Contact email                   | email         | email         |
| Yes      | series tag  | contact_phone                   | Contact phone                   | phone         | phone         |
| Yes      | series tag  | host_contact_department         | Host/Contact Department         | text          | text          |
| Yes      | series tag  | feed_keyword_s                  | Feed Keyword(s):                | text          | text          |
| Yes      | series tag  | display_on_kc_home_page         | Display on KC home page         | checkbox      | checkbox      |
| Yes      | series tag  | airport                         | Airport                         | checkbox      | checkbox      |
| Yes      | series tag  | arts_culture                    | arts_culture                    | checkbox      | checkbox      |
| Yes      | series tag  | best_starts_for_kids            | Best Starts for Kids            | checkbox      | checkbox      |
| Yes      | series tag  | business                        | business                        | checkbox      | checkbox      |
| Yes      | series tag  | closure                         | closure                         | checkbox      | checkbox      |
| Yes      | series tag  | council                         | council                         | text          | checkbox      |
| Yes      | series tag  | courts                          | courts                          | checkbox      | checkbox      |
| Yes      | series tag  | elections                       | elections                       | checkbox      | checkbox      |
| Yes      | series tag  | emergency                       | emergency                       | checkbox      | checkbox      |
| Yes      | series tag  | employees                       | employees                       | checkbox      | checkbox      |
| Yes      | series tag  | environment                     | environment                     | checkbox      | checkbox      |
| Yes      | series tag  | events                          | events                          | checkbox      | checkbox      |
| Yes      | series tag  | executive                       | executive                       | checkbox      | checkbox      |
| Yes      | series tag  | fleet_auctions                  | Fleet auctions                  | checkbox      | checkbox      |
| Yes      | series tag  | health                          | health                          | checkbox      | checkbox      |
| Yes      | series tag  | jails                           | jails                           | checkbox      | checkbox      |
| Yes      | series tag  | jobs                            | jobs                            | checkbox      | checkbox      |
| Yes      | series tag  | licenses                        | licenses                        | checkbox      | checkbox      |
| Yes      | series tag  | metro                           | Metro                           | checkbox      | checkbox      |
| Yes      | series tag  | news                            | news                            | checkbox      | checkbox      |
| Yes      | series tag  | operations                      | operations                      | checkbox      | checkbox      |
| Yes      | series tag  | parks                           | parks                           | checkbox      | checkbox      |
| Yes      | series tag  | permits                         | permits                         | checkbox      | checkbox      |
| Yes      | series tag  | pets                            | pets                            | checkbox      | checkbox      |
| Yes      | series tag  | property                        | property                        | checkbox      | checkbox      |
| Yes      | series tag  | recreation                      | recreation                      | checkbox      | checkbox      |
| Yes      | series tag  | recycling_trash                 | recycling_trash                 | checkbox      | checkbox      |
| Yes      | series tag  | swd_home                        | SWD home                        | checkbox      | checkbox      |
| Yes      | series tag  | swd_advisory_committee          | SWD Advisory Committee          | checkbox      | checkbox      |
| Yes      | series tag  | swd_ecoconsumer                 | SWD EcoConsumer                 | checkbox      | checkbox      |
| Yes      | series tag  | swd_facilities                  | SWD Facilities                  | checkbox      | checkbox      |
| Yes      | series tag  | swd_greentools                  | SWD GreenTools                  | checkbox      | checkbox      |
| Yes      | series tag  | swd_recycling_collection_events | SWD Recycling collection events | checkbox      | checkbox      |
| Yes      | series tag  | swd_wastemobile                 | SWD Wastemobile                 | checkbox      | checkbox      |
| Yes      | series tag  | roads                           | roads                           | checkbox      | checkbox      |
| Yes      | series tag  | rural                           | rural                           | checkbox      | checkbox      |
| Yes      | series tag  | safety                          | safety                          | checkbox      | checkbox      |
| Yes      | series tag  | sheriff                         | sheriff                         | checkbox      | checkbox      |
| Yes      | series tag  | socialservices                  | SocialServices                  | checkbox      | checkbox      |
| Yes      | series tag  | transportation                  | transportation                  | checkbox      | checkbox      |
| Yes      | series tag  | volunteer                       | volunteer                       | checkbox      | checkbox      |
| Yes      | series tag  | water_taxi                      | Water taxi                      | checkbox      | checkbox      |
| No       |             | tac_meeting                     | TAC Meeting                     | calendar_date | calendar_date |
```

## Time Field

```ls
Value = start_time
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = end_time,tac_meeting
```

## Data Commands

```ls
series e:a5hq-yx6s d:2018-10-08T00:00:00.000Z t:metro=true t:events=true t:event_name="Columbus Day (regional holiday)" m:row_number.a5hq-yx6s=1

series e:a5hq-yx6s d:2018-12-24T00:00:00.000Z t:metro=true t:events=true t:event_name="Christmas Eve" m:row_number.a5hq-yx6s=2

series e:a5hq-yx6s d:2016-04-04T09:00:00.000Z t:contact_email=orcatogo1@gmail.com t:metro=true t:events=true t:event_name="University of Washington Station - ORCA LIFT" t:host_contact_department="Metro ORCA To-Go" m:row_number.a5hq-yx6s=3
```

## Meta Commands

```ls
metric m:row_number.a5hq-yx6s p:long l:"Row Number"

entity e:a5hq-yx6s l:"King County Master Calendar" t:attribution="King County" t:url=https://data.kingcounty.gov/api/views/a5hq-yx6s

property e:a5hq-yx6s t:meta.view v:id=a5hq-yx6s v:category=Operations v:attributionLink=http://kingcounty.gov v:averageRating=0 v:name="King County Master Calendar" v:attribution="King County"

property e:a5hq-yx6s t:meta.view.license v:name="Public Domain"

property e:a5hq-yx6s t:meta.view.owner v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"

property e:a5hq-yx6s t:meta.view.tableauthor v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"
```

## Top Records

```ls
| start_time          | end_time            | event_name                                   | event_description_details | location_name                        | url                                                                                               | contact_name                   | contact_email               | contact_phone | host_contact_department | feed_keyword_s                                                         | display_on_kc_home_page | airport | arts_culture | best_starts_for_kids | business | closure | council | courts | elections | emergency | employees | environment | events | executive | fleet_auctions | health | jails | jobs | licenses | metro | news | operations | parks | permits | pets | property | recreation | recycling_trash | swd_home | swd_advisory_committee | swd_ecoconsumer | swd_facilities | swd_greentools | swd_recycling_collection_events | swd_wastemobile | roads | rural | safety | sheriff | socialservices | transportation | volunteer | water_taxi | tac_meeting         | 
| =================== | =================== | ============================================ | ========================= | ==================================== | ================================================================================================= | ============================== | =========================== | ============= | ======================= | ====================================================================== | ======================= | ======= | ============ | ==================== | ======== | ======= | ======= | ====== | ========= | ========= | ========= | =========== | ====== | ========= | ============== | ====== | ===== | ==== | ======== | ===== | ==== | ========== | ===== | ======= | ==== | ======== | ========== | =============== | ======== | ====================== | =============== | ============== | ============== | =============================== | =============== | ===== | ===== | ====== | ======= | ============== | ============== | ========= | ========== | =================== | 
| 2018-10-08T00:00:00 | 2018-10-08T23:59:00 | Columbus Day (regional holiday)              |                           |                                      | [null, null]                                                                                      |                                |                             | [null, null]  |                         |                                                                        |                         |         |              |                      |          |         |         |        |           |           |           |             | true   |           |                |        |       |      |          | true  |      |            |       |         |      |          |            |                 |          |                        |                 |                |                |                                 |                 |       |       |        |         |                |                |           |            |                     | 
| 2018-12-24T00:00:00 | 2018-12-24T23:59:00 | Christmas Eve                                |                           |                                      | [null, null]                                                                                      |                                |                             | [null, null]  |                         |                                                                        |                         |         |              |                      |          |         |         |        |           |           |           |             | true   |           |                |        |       |      |          | true  |      |            |       |         |      |          |            |                 |          |                        |                 |                |                |                                 |                 |       |       |        |         |                |                |           |            |                     | 
| 2016-04-04T09:00:00 | 2016-04-04T16:00:00 | University of Washington Station - ORCA LIFT |                           |                                      | [null, null]                                                                                      |                                | orcatogo1@gmail.com         | [null, null]  | Metro ORCA To-Go        |                                                                        |                         |         |              |                      |          |         |         |        |           |           |           |             | true   |           |                |        |       |      |          | true  |      |            |       |         |      |          |            |                 |          |                        |                 |                |                |                                 |                 |       |       |        |         |                |                |           |            |                     | 
| 2015-03-17T22:01:00 | 2015-03-18T21:59:00 | Transit Driver Appreciation Day              |                           | King County                          | [http://metro.kingcounty.gov/transit-driver-day/, null]                                           | Jeff Switzer                   | jeff.switzer@kingcounty.gov | [null, null]  |                         |                                                                        | true                    |         |              |                      |          |         |         |        |           |           |           |             |        |           |                |        |       |      |          | true  |      |            |       |         |      |          |            |                 |          |                        |                 |                |                |                                 |                 |       |       |        |         |                |                |           |            | 2015-03-18T16:39:00 | 
| 2015-11-10T00:00:00 | 2015-11-10T23:59:00 | DES FBOD FMS Veterns Day Silent Auction      |                           | King Street Center, Room 7044 & 7045 | [null, null]                                                                                      |                                |                             | [null, null]  | Employee Giving Program | employee giving                                                        |                         |         |              |                      |          |         |         |        |           |           | true      |             | true   |           |                |        |       |      |          |       |      |            |       |         |      |          |            |                 |          |                        |                 |                |                |                                 |                 |       |       |        |         |                |                |           |            |                     | 
| 2015-10-22T09:30:00 | 2015-10-22T12:30:00 | Holiday                                      |                           |                                      | [null, null]                                                                                      | Robert Nedrow                  | robert.nedrow.kcm@gmail.com | [null, null]  | Metro ORCA To-Go        |                                                                        |                         |         |              |                      |          |         |         |        |           |           |           |             | true   |           |                |        |       |      |          | true  |      |            |       |         |      |          |            |                 |          |                        |                 |                |                |                                 |                 |       |       |        |         |                |                |           |            |                     | 
| 2016-04-02T09:00:00 | 2016-04-02T16:00:00 | Capital Hill Station (ORCA LIFT)             |                           |                                      | [null, null]                                                                                      |                                | orcatogo1@gmail.com         | [null, null]  | Metro ORCA To-Go        |                                                                        |                         |         |              |                      |          |         |         |        |           |           |           |             | true   |           |                |        |       |      |          | true  |      |            |       |         |      |          |            |                 |          |                        |                 |                |                |                                 |                 |       |       |        |         |                |                |           |            |                     | 
| 2017-07-04T00:00:00 | 2017-07-04T23:59:00 | July 4 holiday - most offices closed         |                           |                                      | [http://www.kingcounty.gov/about/contact-us/closures/july4.aspx, Fourth of July holiday closures] |                                |                             | [null, null]  |                         |                                                                        | true                    |         |              |                      |          | true    |         |        |           |           |           |             |        |           |                |        |       |      |          |       |      |            |       |         |      |          |            |                 |          |                        |                 |                |                |                                 |                 |       |       |        |         |                |                |           |            |                     | 
| 2014-08-05T16:00:00 | 2014-08-05T19:00:00 | National Night Out                           |                           | King County neighborhoods            | [http://www.kingcounty.gov/prepare, null]                                                         | Office of Emergency Management |                             | [null, null]  | DES/OEM                 | national, night, out, neighborhoods, events, safety, crime, prevention | true                    |         |              |                      |          |         |         |        |           |           |           |             | true   |           |                |        |       |      |          |       | true |            |       |         |      |          |            |                 |          |                        |                 |                |                |                                 |                 |       |       | true   | true    |                |                |           |            |                     | 
| 2016-08-27T11:00:00 | 2016-08-27T16:00:00 | ORCA Maintenance                             |                           |                                      | [null, null]                                                                                      | Robert Nedrow                  | robert.nedrow.kcm@gmail.com | [null, null]  | Metro ORCA To-Go        |                                                                        |                         |         |              |                      |          |         |         |        |           |           |           |             | true   |           |                |        |       |      |          | true  |      |            |       |         |      |          |            |                 |          |                        |                 |                |                |                                 |                 |       |       |        |         |                |                |           |            |                     | 
```