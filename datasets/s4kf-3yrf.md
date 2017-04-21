# LinkNYC Locations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/linknyc-locations) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/s4kf-3yrf) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/s4kf-3yrf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/s4kf-3yrf/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | s4kf-3yrf |
| Name | LinkNYC Locations |
| Attribution | Department of Information Technology & Telecommunications (DoITT) |
| Category | Social Services |
| Tags | link nyc locations, wifi, wi-fi, hotspot, internet, kiosk |
| Created | 2016-04-12T15:47:38Z |
| Publication Date | 2017-04-20T14:37:20Z |

## Description

Wi-Fi Provider: LinkNYC - CityBridge, LLC (Free): LinkNYC 1 gigabyte (GB), Free Wi-Fi Internet Kiosks, Free Nation Wide Phone Locals

## Columns

```ls
| Included | Schema Type    | Field Name                        | Name                                | Data Type     | Render Type   |
| ======== | ============== | ================================= | =================================== | ============= | ============= |
| Yes      | series tag     | cb_link_id                        | CB Link ID                          | text          | text          |
| Yes      | series tag     | boro                              | Boro                                | text          | text          |
| Yes      | numeric metric | community_board                   | Community Board                     | number        | number        |
| Yes      | numeric metric | latitude                          | Latitude                            | number        | number        |
| Yes      | numeric metric | longitude                         | Longitude                           | number        | number        |
| Yes      | series tag     | link_installation_status          | Link Installation Status            | text          | text          |
| Yes      | numeric metric | smallest_ppt                      | Smallest PPT                        | number        | number        |
| Yes      | series tag     | street_address                    | Street Address                      | text          | text          |
| Yes      | series tag     | kiosk_bearing                     | Kiosk Bearing                       | text          | text          |
| Yes      | series tag     | boro_id                           | Boro ID                             | text          | text          |
| Yes      | series tag     | link_site_id                      | Link Site ID                        | text          | text          |
| Yes      | series tag     | link_smoke_tested_and_activated_a | Link Smoke Tested and Activated (A) | text          | text          |
| Yes      | time           | link_installation                 | Link Installation (A)               | calendar_date | calendar_date |
```

## Time Field

```ls
Value = link_installation
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:s4kf-3yrf d:2017-03-31T00:00:00.000Z t:link_smoke_tested_and_activated_a=4/14/17 t:boro=Brooklyn t:cb_link_id=LINK-000027 t:link_installation_status="A - Link Live" t:link_site_id=bk-01-125268 t:boro_id=NY-BK t:street_address="817 Manhattan Ave" t:kiosk_bearing=144SE m:longitude=-73.953439 m:latitude=40.728133 m:smallest_ppt=125268 m:community_board=301

series e:s4kf-3yrf d:2017-02-24T00:00:00.000Z t:link_smoke_tested_and_activated_a=4/3/17 t:boro=Brooklyn t:cb_link_id=LINK-000031 t:link_installation_status="A - Link Live" t:link_site_id=bk-06-125931 t:boro_id=NY-BK t:street_address="270 5Th Ave" t:kiosk_bearing="118 SE" m:longitude=-73.981943 m:latitude=40.674559 m:smallest_ppt=125931 m:community_board=306

series e:s4kf-3yrf d:2017-02-24T00:00:00.000Z t:link_smoke_tested_and_activated_a=4/3/17 t:boro=Brooklyn t:cb_link_id=LINK-000032 t:link_installation_status="A - Link Live" t:link_site_id=bk-06-125930 t:boro_id=NY-BK t:street_address="168 5Th Ave" t:kiosk_bearing="103 E" m:longitude=-73.979739 m:latitude=40.67762 m:smallest_ppt=125930 m:community_board=306
```

## Meta Commands

```ls
metric m:community_board p:long l:"Community Board" d:"Appointed advisory groups from a variety of districts throughout NYC's five boroughs. They deal with issues such as zoning, land usage, and any other matter related to the quality of life of their residents." t:dataTypeName=number

metric m:latitude p:long l:Latitude d:"Points that fall North or South of the Equator, expressed in degrees." t:dataTypeName=number

metric m:longitude p:long l:Longitude d:"Points that fall East or West of the Prime Meridian, expressed in degrees." t:dataTypeName=number

metric m:smallest_ppt p:long l:"Smallest PPT" d:"The Public Pay Telephone unique identification number." t:dataTypeName=number

entity e:s4kf-3yrf l:"LinkNYC Locations" t:attribution="Department of Information Technology & Telecommunications (DoITT)" t:url=https://data.cityofnewyork.us/api/views/s4kf-3yrf

property e:s4kf-3yrf t:meta.view v:id=s4kf-3yrf v:category="Social Services" v:averageRating=0 v:name="LinkNYC Locations" v:attribution="Department of Information Technology & Telecommunications (DoITT)"

property e:s4kf-3yrf t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:s4kf-3yrf t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| cb_link_id  | boro     | community_board | latitude           | longitude           | link_installation_status | smallest_ppt | street_address       | kiosk_bearing | boro_id | link_site_id | link_smoke_tested_and_activated_a | link_installation   | 
| =========== | ======== | =============== | ================== | =================== | ======================== | ============ | ==================== | ============= | ======= | ============ | ================================= | =================== | 
| LINK-000027 | Brooklyn | 301             | 40.728133          | -73.953439000000003 | A - Link Live            | 125268       | 817 Manhattan Ave    | 144SE         | NY-BK   | bk-01-125268 | 4/14/17                           | 2017-03-31T00:00:00 | 
| LINK-000031 | Brooklyn | 306             | 40.674559000000002 | -73.981943000000001 | A - Link Live            | 125931       | 270 5Th Ave          | 118 SE        | NY-BK   | bk-06-125931 | 4/3/17                            | 2017-02-24T00:00:00 | 
| LINK-000032 | Brooklyn | 306             | 40.677619999999997 | -73.979738999999995 | A - Link Live            | 125930       | 168 5Th Ave          | 103 E         | NY-BK   | bk-06-125930 | 4/3/17                            | 2017-02-24T00:00:00 | 
| LINK-000040 | Brooklyn | 306             | 40.668536000000003 | -73.986962000000005 | A - Link Live            | 125910       | 462 5Th Avenue       | 85 E          | NY-BK   | bk-06-125910 | 4/3/17                            | 2017-02-23T00:00:00 | 
| LINK-000042 | Brooklyn | 306             | 40.669732000000003 | -73.985960000000006 | A - Link Live            | 125921       | 426 5Th Avenue       | 103 E         | NY-BK   | bk-06-125921 | 4/3/17                            | 2017-02-23T00:00:00 | 
| LINK-000045 | Brooklyn | 302             | 40.688851          | -73.980613000000005 | A - Link Live            | 126565       | 395 Flatbush Avenue  | 320 NW        | NY-BK   | bk-02-126565 | 1/20/17                           | 2016-11-13T00:00:00 | 
| LINK-000064 | Bronx    | 207             | 40.863135          | -73.904563999999993 | A - Link Live            | 111540       | 2408 University Ave  | 317 NW        | NY-BX   | bx-07-111540 | 3/30/17                           | 2017-02-18T00:00:00 | 
| LINK-000067 | Bronx    | 205             | 40.860214999999997 | -73.893060000000006 | A - Link Live            | 116218       | 2461 Webster Ave     | 108 E         | NY-BX   | bx-05-116218 | 5/25/16                           | 2016-05-12T00:00:00 | 
| LINK-000070 | Bronx    | 207             | 40.862644000000003 | -73.903244000000001 | A - Link Live            | 119564       | 48 W Fordham Rd      | 4 N           | NY-BX   | bx-07-119564 | 9/15/16                           | 2016-08-13T00:00:00 | 
| LINK-000072 | Bronx    | 205             | 40.861348999999997 | -73.898022999999995 | A - Link Live            | 119575       | 2437 Grand Concourse | 100 E         | NY-BX   | bx-05-119575 | 7/19/16                           | 2016-07-01T00:00:00 | 
```