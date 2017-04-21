# Library Monthly Stats

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/library-monthly-stats-6b1aa) |
| Metadata | [Link](https://data.lacity.org/api/views/m4ev-cuzz) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/m4ev-cuzz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/m4ev-cuzz/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | m4ev-cuzz |
| Name | Library Monthly Stats |
| Category | A Well Run City |
| Tags | library, statistics |
| Created | 2014-05-28T20:26:16Z |
| Publication Date | 2017-03-14T16:01:50Z |

## Description

Monthly statistics from the Library on Web visits, computer usage, e-media, etc.

## Columns

```ls
| Included | Schema Type    | Field Name                                | Name                                          | Data Type     | Render Type   |
| ======== | ============== | ========================================= | ============================================= | ============= | ============= |
| Yes      | time           | date                                      | Date                                          | calendar_date | calendar_date |
| Yes      | series tag     | month                                     | Month                                         | text          | text          |
| Yes      | numeric metric | total_library_visitors                    | Total Library Visitors                        | number        | number        |
| Yes      | numeric metric | total_library_programs                    | Total Library Programs                        | number        | number        |
| Yes      | numeric metric | total_program_attendees                   | Total Program Attendees                       | number        | number        |
| Yes      | numeric metric | total_volunteer_hours                     | Total Volunteer Hours                         | number        | number        |
| Yes      | numeric metric | total_web_visits                          | Total Web Visits                              | number        | number        |
| Yes      | numeric metric | total_emedia_circulation                  | Total eMedia Circulation                      | number        | number        |
| Yes      | numeric metric | total_wifi_sessions                       | Total WiFi Sessions                           | number        | number        |
| Yes      | numeric metric | total_reservation_pc_sessions             | Total Reservation PC Sessions                 | number        | number        |
| Yes      | numeric metric | total_cardholders                         | Total Cardholders                             | number        | number        |
| Yes      | numeric metric | total_computer_usage_wireless_pc_sessions | Total Computer Usage (Wireless + PC Sessions) | number        | number        |
| Yes      | numeric metric | new_cardholders                           | New Cardholders                               | number        | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:m4ev-cuzz d:2014-06-30T00:00:00.000Z t:month=Jun-14 m:total_web_visits=1852979 m:total_reservation_pc_sessions=193129 m:total_cardholders=1141782 m:total_wifi_sessions=118378 m:total_library_programs=2214 m:total_library_visitors=1261943 m:total_volunteer_hours=17264 m:total_program_attendees=47273 m:total_emedia_circulation=211622

series e:m4ev-cuzz d:2014-05-31T00:00:00.000Z t:month=May-14 m:total_web_visits=1805172 m:total_reservation_pc_sessions=198479 m:total_cardholders=1128767 m:total_wifi_sessions=127051 m:total_library_programs=1788 m:total_library_visitors=1203901 m:total_volunteer_hours=12614 m:total_program_attendees=25104 m:total_emedia_circulation=240236

series e:m4ev-cuzz d:2014-04-30T00:00:00.000Z t:month=Apr-14 m:total_web_visits=1892885 m:total_reservation_pc_sessions=208705 m:total_cardholders=1113767 m:total_wifi_sessions=124598 m:total_library_programs=1856 m:total_library_visitors=1458097 m:total_volunteer_hours=14925 m:total_program_attendees=31844 m:total_emedia_circulation=195307
```

## Meta Commands

```ls
metric m:total_library_visitors p:integer l:"Total Library Visitors" t:dataTypeName=number

metric m:total_library_programs p:integer l:"Total Library Programs" t:dataTypeName=number

metric m:total_program_attendees p:integer l:"Total Program Attendees" t:dataTypeName=number

metric m:total_volunteer_hours p:long l:"Total Volunteer Hours" t:dataTypeName=number

metric m:total_web_visits p:long l:"Total Web Visits" t:dataTypeName=number

metric m:total_emedia_circulation p:integer l:"Total eMedia Circulation" t:dataTypeName=number

metric m:total_wifi_sessions p:integer l:"Total WiFi Sessions" t:dataTypeName=number

metric m:total_reservation_pc_sessions p:long l:"Total Reservation PC Sessions" t:dataTypeName=number

metric m:total_cardholders p:integer l:"Total Cardholders" t:dataTypeName=number

metric m:total_computer_usage_wireless_pc_sessions p:integer l:"Total Computer Usage (Wireless + PC Sessions)" d:"Includes computers used at the libraries as well as wireless sessions logged." t:dataTypeName=number

metric m:new_cardholders p:integer l:"New Cardholders" d:"Number of people that signed up for a library card this month." t:dataTypeName=number

entity e:m4ev-cuzz l:"Library Monthly Stats" t:url=https://data.lacity.org/api/views/m4ev-cuzz

property e:m4ev-cuzz t:meta.view v:id=m4ev-cuzz v:category="A Well Run City" v:averageRating=0 v:name="Library Monthly Stats"

property e:m4ev-cuzz t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:m4ev-cuzz t:meta.view.owner v:id=ysts-hp3n v:profileImageUrlMedium=/api/users/ysts-hp3n/profile_images/THUMB v:profileImageUrlLarge=/api/users/ysts-hp3n/profile_images/LARGE v:screenName="Library OpenData" v:profileImageUrlSmall=/api/users/ysts-hp3n/profile_images/TINY v:displayName="Library OpenData"

property e:m4ev-cuzz t:meta.view.tableauthor v:id=ysts-hp3n v:profileImageUrlMedium=/api/users/ysts-hp3n/profile_images/THUMB v:profileImageUrlLarge=/api/users/ysts-hp3n/profile_images/LARGE v:screenName="Library OpenData" v:profileImageUrlSmall=/api/users/ysts-hp3n/profile_images/TINY v:roleName=publisher v:displayName="Library OpenData"
```

## Top Records

```ls
| date                | month  | total_library_visitors | total_library_programs | total_program_attendees | total_volunteer_hours | total_web_visits | total_emedia_circulation | total_wifi_sessions | total_reservation_pc_sessions | total_cardholders | total_computer_usage_wireless_pc_sessions | new_cardholders | 
| =================== | ====== | ====================== | ====================== | ======================= | ===================== | ================ | ======================== | =================== | ============================= | ================= | ========================================= | =============== | 
| 2014-06-30T00:00:00 | Jun-14 | 1261943                | 2214                   | 47273                   | 17264                 | 1852979          | 211622                   | 118378              | 193129                        | 1141782           |                                           |                 | 
| 2014-05-31T00:00:00 | May-14 | 1203901                | 1788                   | 25104                   | 12614                 | 1805172          | 240236                   | 127051              | 198479                        | 1128767           |                                           |                 | 
| 2014-04-30T00:00:00 | Apr-14 | 1458097                | 1856                   | 31844                   | 14925                 | 1892885          | 195307                   | 124598              | 208705                        | 1113767           |                                           |                 | 
| 2013-10-31T00:00:00 | Oct-13 | 1272628                | 1805                   | 44336                   | 14633                 | 1826659          | 180297                   | 132142              | 198666                        |                   |                                           |                 | 
| 2013-09-30T00:00:00 | Sep-13 | 1282431                | 1556                   | 27211                   | 13282                 | 1840740          | 171245                   | 130248              | 211232                        |                   |                                           |                 | 
| 2014-02-28T00:00:00 | Feb-14 | 1382040                | 1777                   | 30149                   | 14010                 | 1719801          | 191618                   | 115649              | 187467                        | 1112200           |                                           |                 | 
| 2013-08-31T00:00:00 | Aug-13 | 1223571                | 1534                   | 29875                   | 14415                 | 1991667          | 180508                   | 133975              | 237780                        |                   |                                           |                 | 
| 2013-07-31T00:00:00 | Jul-13 | 1279061                | 2138                   | 51955                   | 18876                 | 2026211          | 171332                   | 102743              | 233626                        |                   |                                           |                 | 
| 2014-01-31T00:00:00 | Jan-14 | 1092965                | 1567                   | 23581                   | 12634                 | 1884707          | 203037                   | 124704              | 204878                        | 1111441           |                                           |                 | 
| 2013-11-30T00:00:00 | Nov-13 | 1055041                | 1535                   | 28068                   | 12905                 | 1684896          | 159134                   | 115380              | 189724                        |                   |                                           |                 | 
```