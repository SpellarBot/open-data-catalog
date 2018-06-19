# SFO Things To Do

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/sfo-things-to-do) |
| Metadata | [Link](https://data.sfgov.org/api/views/y7d5-5crz) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/y7d5-5crz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/y7d5-5crz/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | y7d5-5crz |
| Name | SFO Things To Do |
| Category | Transportation |
| Tags | sfo, airport |
| Created | 2015-12-01T17:26:10Z |
| Publication Date | 2016-01-22T23:53:21Z |

## Description

General activity information including activity name, activity description, phone number, location at SFO, and hours of operation. These data are also available via an API at http://www.flysfo.com/api

## Columns

```ls
| Included | Schema Type    | Field Name       | Name                   | Data Type | Render Type |
| ======== | ============== | ================ | ====================== | ========= | =========== |
| No       | time           | :updated_at      | updated_at             | meta_data | meta_data   |
| Yes      | numeric metric | nid              | nid                    | number    | number      |
| Yes      | series tag     | service_name     | Passenger Service Name | text      | text        |
| Yes      | series tag     | body             | Description            | text      | text        |
| Yes      | series tag     | location_summary | Location Summary       | text      | text        |
| Yes      | numeric metric | phone            | Phone                  | number    | text        |
| Yes      | series tag     | hours            | Hours                  | text      | text        |
| Yes      | series tag     | data_tags        | Tags                   | text      | text        |
| Yes      | series tag     | terminal         | Terminal               | text      | text        |
| Yes      | series tag     | security         | Security               | text      | text        |
| Yes      | series tag     | image            | Image                  | url       | url         |
| Yes      | series tag     | map              | Map                    | url       | url         |
| Yes      | series tag     | url              | URL                    | url       | url         |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:y7d5-5crz d:2015-12-01T09:26:13.000Z t:body="A space for guests to exchange ideas about technology, start-ups, the shared economy, travel, politics and ways to change the world. The room has free wi-fi, tables, chairs, power outlets, a white board and a magnetic chalk board. Learn more about the <a href=""/converge"">#Converge@flySFO Lounge</a>." t:terminal="International Terminal" t:hours="Daily, 24 hours" t:map=http://www.flysfo.com/sites/default/files/converge_0.gif t:image=http://www.flysfo.com/sites/default/files/converge_850x677.jpg t:location_summary="Boarding Area G near Gate G93" t:security=Post-Security t:service_name=#Converge@flySFO t:url=http://www.flysfo.com/content/convergeflysfo m:nid=19896

series e:y7d5-5crz d:2015-12-01T09:26:13.000Z t:body="Exhibitions, research services, and educational programs in an architectural adaptation of the Airport's 1930s passenger lobby." t:terminal="International Terminal" t:hours="Sunday through Friday from 10:30 a.m. to 4:30 p.m." t:map=http://www.flysfo.com/sites/default/files/aviation-museum-and-library_0.gif t:image=http://www.flysfo.com/sites/default/files/ALM_850x677.jpg t:location_summary="Main Hall" t:security=Pre-Security t:service_name="Aviation Museum & Library" t:url=http://www.flysfo.com/content/aviation-museum-library m:phone=650.821 m:nid=3042

series e:y7d5-5crz d:2015-12-01T09:26:13.000Z t:body="A center for quiet self-reflection and meditation." t:terminal="International Terminal" t:hours="Daily, 7:00 a.m. to 11:00 p.m." t:map=http://www.flysfo.com/sites/default/files/berman-reflection-room_0.gif t:image=http://www.flysfo.com/sites/default/files/ReflectionRoom_850x677.jpg t:location_summary="Main Hall" t:security=Pre-Security t:service_name="Berman Reflection Room" t:url=http://www.flysfo.com/content/berman-reflection-room m:nid=3040
```

## Meta Commands

```ls
metric m:nid p:integer l:nid d:"Node ID used for listing on SFO website" t:dataTypeName=number

metric m:phone p:double l:Phone d:"Phone number for things to do" t:dataTypeName=number

entity e:y7d5-5crz l:"SFO Things To Do" t:url=https://data.sfgov.org/api/views/y7d5-5crz

property e:y7d5-5crz t:meta.view v:id=y7d5-5crz v:category=Transportation v:averageRating=0 v:name="SFO Things To Do"

property e:y7d5-5crz t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:y7d5-5crz t:meta.view.owner v:id=h9yb-8z9n v:screenName="Thant Hein" v:displayName="Thant Hein"

property e:y7d5-5crz t:meta.view.tableauthor v:id=h9yb-8z9n v:screenName="Thant Hein" v:roleName=editor v:displayName="Thant Hein"
```

## Top Records

```ls
| :updated_at | nid   | service_name                   | body                                                                                                                                                                                                                                                                                 | location_summary                        | phone        | hours                                                         | data_tags | terminal               | security      | image                                                                          | map                                                                                    | url                                                                  | 
| =========== | ===== | ============================== | ==================================================================================================================================================================================================================================================================================== | ======================================= | ============ | ============================================================= | ========= | ====================== | ============= | ============================================================================== | ====================================================================================== | ==================================================================== | 
| 1448961973  | 19896 | #Converge@flySFO               | A space for guests to exchange ideas about technology, start-ups, the shared economy, travel, politics and ways to change the world. The room has free wi-fi, tables, chairs, power outlets, a white board and a magnetic chalk board. Learn more about the #Converge@flySFO Lounge. | Boarding Area G near Gate G93           |              | Daily, 24 hours                                               |           | International Terminal | Post-Security | [http://www.flysfo.com/sites/default/files/converge_850x677.jpg, null]         | [http://www.flysfo.com/sites/default/files/converge_0.gif, null]                       | [http://www.flysfo.com/content/convergeflysfo, null]                 | 
| 1448961973  | 3042  | Aviation Museum & Library      | Exhibitions, research services, and educational programs in an architectural adaptation of the Airport's 1930s passenger lobby.                                                                                                                                                      | Main Hall                               | 650.821.9900 | Sunday through Friday from 10:30 a.m. to 4:30 p.m.            |           | International Terminal | Pre-Security  | [http://www.flysfo.com/sites/default/files/ALM_850x677.jpg, null]              | [http://www.flysfo.com/sites/default/files/aviation-museum-and-library_0.gif, null]    | [http://www.flysfo.com/content/aviation-museum-library, null]        | 
| 1448961973  | 3040  | Berman Reflection Room         | A center for quiet self-reflection and meditation.                                                                                                                                                                                                                                   | Main Hall                               |              | Daily, 7:00 a.m. to 11:00 p.m.                                |           | International Terminal | Pre-Security  | [http://www.flysfo.com/sites/default/files/ReflectionRoom_850x677.jpg, null]   | [http://www.flysfo.com/sites/default/files/berman-reflection-room_0.gif, null]         | [http://www.flysfo.com/content/berman-reflection-room, null]         | 
| 1448961973  | 3041  | Christian Science Reading Room | A quiet place to read, meditate or relax in a peaceful environment.                                                                                                                                                                                                                  | near entrance to Gates 40-48            | 650.877.0105 | Daily, 8:00 a.m. to 10:00 p.m.                                |           | Terminal 1             | Pre-Security  | [http://www.flysfo.com/sites/default/files/ChristianScience_850x677.jpg, null] | [http://www.flysfo.com/sites/default/files/christian-science-reading-room_0.gif, null] | [http://www.flysfo.com/content/christian-science-reading-room, null] | 
| 1448961973  | 5245  | Flight Deck                    | Interactive touchscreen kiosks with information about SFO and San Francisco. Learn more about Flight Deck.                                                                                                                                                                           | Boarding Area E near Gate 60            |              | Daily, 24 hours                                               |           | Terminal 3             | Post-Security | [http://www.flysfo.com/sites/default/files/flightdeck.jpg, null]               | [http://www.flysfo.com/sites/default/files/flight-deck_0.gif, null]                    | [http://www.flysfo.com/content/flight-deck, null]                    | 
| 1448961973  | 5284  | Kids' Spot                     | The SFO Kids? Spot is an interactive children?s exploration area featuring Spirogyrate by artist Eric Staller                                                                                                                                                                        | Boarding Area E near Gate 62            |              | Daily, 24 hours                                               |           | Terminal 3             | Post-Security | [http://www.flysfo.com/sites/default/files/KidsSpotT3_850x677.jpg, null]       | [http://www.flysfo.com/sites/default/files/kids-spot_3.gif, null]                      | [http://www.flysfo.com/content/kids-spot-1, null]                    | 
| 1448961973  | 5089  | Kids' Spot                     | An interactive play area where children can "let off steam" prior to their flights.                                                                                                                                                                                                  | Boarding Area D, near Gates 54A and 58B |              | Daily, 24 hours                                               |           | Terminal 2             | Post-Security | [http://www.flysfo.com/sites/default/files/T2KidsSpot_850x677.jpg, null]       | [http://www.flysfo.com/sites/default/files/kids-spot_2.gif, null]                      | [http://www.flysfo.com/content/kids-spot, null]                      | 
| 1448961973  | 5088  | Kids' Spot                     | The SFO Kids? Spot is an interactive children?s exploration area featuring weather related exhibits from the Exploratorium of San Francisco, as well as a crawling apparatus                                                                                                         | Boarding Area F, near Gate 87A          |              | Daily, 24 hours                                               |           | Terminal 3             | Post-Security | [http://www.flysfo.com/sites/default/files/KidsSpotT3F_850x677.jpg, null]      | [http://www.flysfo.com/sites/default/files/kids-spot_4.gif, null]                      | [http://www.flysfo.com/content/kids-spot-0, null]                    | 
| 1448961973  | 3895  | Self-Guided Tours              | Fun for children of all ages. View the Terminal 2 itinerary online and on iPad kiosks at the Information Booths.                                                                                                                                                                     |                                         |              | Daily, 24 hours; prizes available from 8:00 a.m. to 8:00 p.m. |           | Terminal 2             | Pre-Security  | [http://www.flysfo.com/sites/default/files/T2Tour_0.jpg, null]                 | [null, null]                                                                           | [http://www.flysfo.com/content/self-guided-tours-0, null]            | 
| 1448961973  | 3052  | Self-Guided Tours              | Fun for children of all ages. View the Terminal 3 itinerary online and on iPad kiosks at the Information Booths.                                                                                                                                                                     |                                         |              | Daily, 24 hours; prizes available from 8:00 a.m. to 8:00 p.m. |           | Terminal 3             | Pre-Security  | [http://www.flysfo.com/sites/default/files/T3Tour.jpg, null]                   | [null, null]                                                                           | [http://www.flysfo.com/content/self-guided-tours-2, null]            | 
```