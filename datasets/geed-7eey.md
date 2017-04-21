# Port of Los Angeles - Film Permit Tracking 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/port-of-los-angeles-film-permit-tracking-2014-442b7) |
| Metadata | [Link](https://data.lacity.org/api/views/geed-7eey) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/geed-7eey/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/geed-7eey/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | geed-7eey |
| Name | Port of Los Angeles - Film Permit Tracking 2014 |
| Attribution | Port of Los Angeles |
| Category | A Prosperous City |
| Created | 2014-03-24T16:27:02Z |
| Publication Date | 2014-03-24T16:27:43Z |

## Description

Port of Los Angeles - Film Permit Tracking 2014

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                  | Data Type | Render Type |
| ======== | ============== | =================== | ===================== | ========= | =========== |
| Yes      | series tag     | harbor_tracking_no  | HARBOR TRACKING NO.   | text      | text        |
| Yes      | series tag     | film_la             | FILM LA #.            | text      | text        |
| Yes      | series tag     | filming_dates       | FILMING DATES         | text      | text        |
| Yes      | numeric metric | harbor_fees         | HARBOR FEES           | money     | money       |
| Yes      | series tag     | location_s          | LOCATION(S)           | text      | text        |
| Yes      | series tag     | production_co_title | PRODUCTION CO./ TITLE | text      | text        |
| Yes      | series tag     | comments            | COMMENTS              | text      | text        |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:geed-7eey d:2014-01-01T00:00:00.000Z t:film_la=F00073400 t:location_s="Ports O' Call Village" t:harbor_tracking_no=14-001 t:production_co_title="AM Stock Cameo Film Library" t:filming_dates=1/9/14 t:comments="Exterior establishing shots; camera with tripod; cast/crew of 12." m:harbor_fees=300

series e:geed-7eey d:2014-01-01T00:00:00.000Z t:film_la=F00073358 t:location_s="Knoll Hill; POC overflow lot" t:harbor_tracking_no=14-002 t:production_co_title="Chelsea Pictures/Project Q." t:filming_dates=1/9/14 t:comments="Exterior dialogue; BMX bike rider; child walks on piece of wood keeping balanced; rolling back section of chain link fence and restoring. Cast of 5/crew 45; parking at POC overflow." m:harbor_fees=600

series e:geed-7eey d:2014-01-01T00:00:00.000Z t:film_la=S00073495 t:location_s="Gateway Plaza Fanfare Fountain" t:harbor_tracking_no=14-003 t:production_co_title="Innerspin Marketing, LLC" t:filming_dates=1/10/14 t:comments="Still photos; cast/crew of 8." m:harbor_fees=50
```

## Meta Commands

```ls
metric m:harbor_fees p:double l:"HARBOR FEES" t:dataTypeName=money

entity e:geed-7eey l:"Port of Los Angeles - Film Permit Tracking 2014" t:attribution="Port of Los Angeles" t:url=https://data.lacity.org/api/views/geed-7eey

property e:geed-7eey t:meta.view v:id=geed-7eey v:category="A Prosperous City" v:averageRating=0 v:name="Port of Los Angeles - Film Permit Tracking 2014" v:attribution="Port of Los Angeles"

property e:geed-7eey t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:geed-7eey t:meta.view.owner v:id=2ib6-ssvz v:profileImageUrlMedium=/api/users/2ib6-ssvz/profile_images/THUMB v:profileImageUrlLarge=/api/users/2ib6-ssvz/profile_images/LARGE v:screenName="Port of Los Angeles" v:profileImageUrlSmall=/api/users/2ib6-ssvz/profile_images/TINY v:displayName="Port of Los Angeles"

property e:geed-7eey t:meta.view.tableauthor v:id=2ib6-ssvz v:profileImageUrlMedium=/api/users/2ib6-ssvz/profile_images/THUMB v:profileImageUrlLarge=/api/users/2ib6-ssvz/profile_images/LARGE v:screenName="Port of Los Angeles" v:profileImageUrlSmall=/api/users/2ib6-ssvz/profile_images/TINY v:roleName=publisher v:displayName="Port of Los Angeles"
```

## Top Records

```ls
| harbor_tracking_no | film_la     | filming_dates     | harbor_fees | location_s                                                                                                              | production_co_title                           | comments                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | 
| ================== | =========== | ================= | =========== | ======================================================================================================================= | ============================================= | ==================================================================================================================================================================================================================================================================================================================================================================================================================================================================================== | 
| 14-001             | F00073400   | 1/9/14            | 300.00      | Ports O' Call Village                                                                                                   | AM Stock Cameo Film Library                   | Exterior establishing shots; camera with tripod; cast/crew of 12.                                                                                                                                                                                                                                                                                                                                                                                                                    | 
| 14-002             | F00073358   | 1/9/14            | 600.00      | Knoll Hill; POC overflow lot                                                                                            | Chelsea Pictures/Project Q.                   | Exterior dialogue; BMX bike rider; child walks on piece of wood keeping balanced; rolling back section of chain link fence and restoring. Cast of 5/crew 45; parking at POC overflow.                                                                                                                                                                                                                                                                                                | 
| 14-003             | S00073495   | 1/10/14           | 50.00       | Gateway Plaza Fanfare Fountain                                                                                          | Innerspin Marketing, LLC                      | Still photos; cast/crew of 8.                                                                                                                                                                                                                                                                                                                                                                                                                                                        | 
| 14-004             | F00073447   | 1/10/14           | 2988.00     | Berth 60, U.S. Water Taxi; west side Signal Street                                                                      | MJZ/GE                                        | Exterior dialogue; filming on 50' fish boat up to 300' feet away; lighting on floating barge and support boats; basecamp on Signal Street; requested lights at southern Signal street and Berth 49/Miner St palm tree/street lights to be turn off 1/10, service request submitted to PEMs Port Police Marine Unit assigned 3pm to 3am (12hrs) $2,688                                                                                                                                | 
| 14-005             | F00073432   | 1/13/14           |             | Berth 95, Parking Concepts Inc.                                                                                         | Brown Hills Productions, LLC                  | Not filming on Port property; basecamp only.                                                                                                                                                                                                                                                                                                                                                                                                                                         | 
| 14-006             | F00073539   | 1/13/14           | 300.00      | Berth 73; outside breakwater; Al Larson Boat Shop; Port vacant lot on Canner Street                                     | Chelsea Pictures/Project Q.                   | Boarding equipment/crew at Berth 73 onto F/V Santa Maria - filming at sea. Al Larson: Exterior dialogue; diver jumps in water off of dock; basecamp at Cannery lot                                                                                                                                                                                                                                                                                                                   | 
| 14-007             | F00073459   | 1/13/14 1/14/14   | 1456.00     | Berth 60, U.S. Water Taxi; west side Signal Street                                                                      | Turner North Center Productions/The Last Ship | 1/13: F/V Day Island departing from dock, filming at sea; 1/14: filming F/V Day Island at dock; basecamp/crew parking o west side Signal street, fees collected under rider A. One Port Police officer assigned 0600-1900(13hrs) $1,456                                                                                                                                                                                                                                              | 
| 14-008             | F00073459-A | 1/15/14 - 1/16/14 | 5008.00     | Berth 49, Lane Victory; Outer Harbor; Berth 46 parking lot; west side Signal Street; Cal Yacht Marina, 24 Whaler's Walk | Turner North Center Productions/The Last Ship | Smoke effects; brandish weapons; vessels in water adjacent to Lane Victory; 4 camera boats; trucks/lighting at Berth 46 parking lot;special effects on barge; request to turn off lights in area 1/14-1/15 service request submitted to PEMs; Tom Welch at Westrec accomodated request to turn off parking lot lights; film company paid Westrec for extra security; Cal Yacht Marina-picnic scene on grass. Port Police Marine unit assigned 1/15 (noon) to 1/16 5am (17hrs) $3,808 | 
| 14-009             | F00073242-A | 1/14/14           | 3162.00     | Ports O' Call Village                                                                                                   | ABC Studios/Revenge                           | Prep 1/10; 1/13; Film 1/14; strike 1/15;set dress windows; banners; pop-up tents, "art walk" scene; closure of southern end Nagoya way with detour; Filming POC restaurant; and public area adjacent; requested sprinklers to be turned off 1/10 - 1/15 service request submitted; large cast/crew/extras total 225. Two Port Police officers assigned 1/14 7am to 11pm (16hrs) $3,584 NOTE: actual hours were 13.5 for ONE officer $1,512; requested refund for $2,072              | 
| 14-010             | F00072495-C | 1/14/14 - 1/16/14 |             | Crafted at the Port of LA, 112 E. 22nd Street; USS Iowa, 250 S. Harbor Blvd;                                            | Muffin Magic Productions LLC/The Brink        | Crafted 1/14-1/16: interior/exterior dialogue; cast/crew of 86; basecamp/parking on location; Iowa 1/16: Interior/exterior dialogue; basecamp in PCI lot                                                                                                                                                                                                                                                                                                                             | 
```