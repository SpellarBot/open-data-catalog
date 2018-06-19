# 2013 Police Video Equipment And Technology ( PVET) JAG Local Pass-through Grant Program

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2013-police-video-equipment-and-technology-pvet-jag-local-pass-through-grant-program) |
| Metadata | [Link](https://data.ct.gov/api/views/5m9p-astg) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/5m9p-astg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/5m9p-astg/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | 5m9p-astg |
| Name | 2013 Police Video Equipment And Technology ( PVET) JAG Local Pass-through Grant Program |
| Category | Government |
| Tags | pvet, police, opm |
| Created | 2014-06-26T14:30:54Z |
| Publication Date | 2014-06-26T14:44:18Z |

## Description

Approximately $2.6 million of federal funds was distributed to nine police departments/municipalities with the primary purpose to assist towns in complying with Public Act 11-174 AAC Electronic Recording of Interrogations.  Data fields include: (1) Town Name; (2) Total Award; (3) Total Expenditures; and (4) Summary description of goods and services procured.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| Yes      | series tag     | name             | Name             | text      | text        |
| Yes      | series tag     | pvet_grant_id    | PVET_Grant_ID    | text      | text        |
| Yes      | numeric metric | award_amount     | Award Amount     | number    | number      |
| Yes      | numeric metric | fed_expenditures | Fed Expenditures | number    | number      |
| Yes      | series tag     | project_summary  | Project Summary  | text      | text        |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:5m9p-astg d:2013-01-01T00:00:00.000Z t:name="Avon, Town of" t:project_summary="1 LR-101 LED Light/Switch; 2 LIR 2 Channel Video Audio Recording Equipment; Cat 5e cable and wall plates; Router for CISS Project; UPS Power-Saving - Mini for Interrogation Equipment" t:pvet_grant_id=09JAGPVET_004 m:award_amount=22475.85 m:fed_expenditures=22167.54

series e:5m9p-astg d:2013-01-01T00:00:00.000Z t:name="Bethel, Town of" t:project_summary="Computer Switch for CJIS System; IRecord video & audio Recording System" t:pvet_grant_id=09JAGPVET_009 m:award_amount=23532 m:fed_expenditures=22980.2

series e:5m9p-astg d:2013-01-01T00:00:00.000Z t:name="Brookfield, Town of" t:project_summary="CISCO 3925 Router, additional hardware and Software Licenses; IRecord Professional Port License, Cables, 2 Covert Cameras, Covert Microphone, 2 Channel date/time overlay, 4 Channel Quad Video PinP Video Processor; LifePak 1000 AED; Paging Software - 2 seats and year 1 support;" t:pvet_grant_id=09JAGPVET_018 m:award_amount=22398 m:fed_expenditures=21160.8
```

## Meta Commands

```ls
metric m:award_amount p:float l:"Award Amount" t:dataTypeName=number

metric m:fed_expenditures p:float l:"Fed Expenditures" t:dataTypeName=number

entity e:5m9p-astg l:"2013 Police Video Equipment And Technology ( PVET) JAG Local Pass-through Grant Program" t:url=https://data.ct.gov/api/views/5m9p-astg

property e:5m9p-astg t:meta.view v:id=5m9p-astg v:category=Government v:averageRating=0 v:name="2013 Police Video Equipment And Technology ( PVET) JAG Local Pass-through Grant Program"

property e:5m9p-astg t:meta.view.owner v:id=6ypf-grnx v:screenName="Jamie Gamble" v:displayName="Jamie Gamble"

property e:5m9p-astg t:meta.view.tableauthor v:id=6ypf-grnx v:screenName="Jamie Gamble" v:roleName=editor v:displayName="Jamie Gamble"
```

## Top Records

```ls
| name                | pvet_grant_id | award_amount       | fed_expenditures   | project_summary                                                                                                                                                                                                                                                                                                                                                                  | 
| =================== | ============= | ================== | ================== | ================================================================================================================================================================================================================================================================================================================================================================================ | 
| Avon, Town of       | 09JAGPVET_004 | 22475.85           | 22167.54           | 1 LR-101 LED Light/Switch; 2 LIR 2 Channel Video Audio Recording Equipment; Cat 5e cable and wall plates; Router for CISS Project; UPS Power-Saving - Mini for Interrogation Equipment                                                                                                                                                                                           | 
| Bethel, Town of     | 09JAGPVET_009 | 23532              | 22980.2            | Computer Switch for CJIS System; IRecord video & audio Recording System                                                                                                                                                                                                                                                                                                          | 
| Brookfield, Town of | 09JAGPVET_018 | 22398              | 21160.799999999999 | CISCO 3925 Router, additional hardware and Software Licenses; IRecord Professional Port License, Cables, 2 Covert Cameras, Covert Microphone, 2 Channel date/time overlay, 4 Channel Quad Video PinP Video Processor; LifePak 1000 AED; Paging Software - 2 seats and year 1 support;                                                                                            | 
| Canton, Town of     | 09JAGPVET_023 | 24174.65           | 24174.65           | Computer, cameras and microphone; Criminal Booking Livescan Workstation; Prisoner Transport System (Setina) Install (NECS)                                                                                                                                                                                                                                                       | 
| Cheshire, Town of   | 09JAGPVET_025 | 28480.2            | 27470.01           | 14 portable radios; 4 handheld portable radios/ microphones, batteries and cases; Computer switch                                                                                                                                                                                                                                                                                | 
| Coventry, Town of   | 09JAGPVET_032 | 25432.85           | 25427.67           | 15 Glock handguns, 15 lights, 15 holsters; Cogent LIVESCAN unit and printer; Computer equipment and peripherals to upgrade video recording system in order to comply with PA 11-274; Digital media for storing evidence; Printer, Monitor, toner cartridges for Video recording system; Upgrade to Video recording system includes camera, microphones, audio controls and labor | 
| Darien, Town of     | 09JAGPVET_035 | 19259.650000000001 | 19259.650000000001 | 2 new MDT computer and 3 new MDT CPU components                                                                                                                                                                                                                                                                                                                                  | 
| Easton, Town of     | 09JAGPVET_046 | 13433.95           | 13431              | Audio and Video Equipment including hidden camera, auto on features, Linear 1 room receiver, wire and install rooms and installation                                                                                                                                                                                                                                             | 
| Fairfield, Town of  | 09JAGPVET_051 | 47080.55           | 44154.9            | ID portable reader; Interrogation surveillance system; License Plate Reader; MDT Computer; Photo array software bundle; Sierra Wireless modem for MDT; Software for Citizen Incident Reporting                                                                                                                                                                                   | 
| Farmington, Town of | 09JAGPVET_052 | 26164.95           | 26164.95           | 2 new LIR 2 channel video recording equipment for interrogation rooms; 1 LR-101 USB LED switch and light; CS1000P criminal booking LiveScan workstation, Cogent scanner, software, printer, monitor, cabinet, installation, training, 2 year maintenance                                                                                                                         | 
```