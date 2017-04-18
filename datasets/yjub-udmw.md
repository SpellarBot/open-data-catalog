# NYC Wi-Fi Hotspot Locations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nyc-wi-fi-hotspot-locations) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/yjub-udmw) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/yjub-udmw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/yjub-udmw/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | yjub-udmw |
| Name | NYC Wi-Fi Hotspot Locations |
| Attribution | Department of Information Technology & Telecommunications (DoITT) |
| Category | City Government |
| Created | 2015-07-14T18:14:19Z |
| Publication Date | 2017-04-10T18:38:04Z |

## Description

Location of wifi hotspots in the city with basic descriptive information.

## Columns

```ls
| Included | Schema Type    | Field Name | Name       | Data Type     | Render Type   |
| ======== | ============== | ========== | ========== | ============= | ============= |
| Yes      | series tag     | objectid   | OBJECTID   | text          | number        |
| Yes      | series tag     | borough    | Borough    | text          | text          |
| Yes      | series tag     | type       | Type       | text          | text          |
| Yes      | series tag     | provider   | Provider   | text          | text          |
| Yes      | series tag     | name       | Name       | text          | text          |
| Yes      | series tag     | location   | Location   | text          | text          |
| No       |                | latitude   | Latitude   | number        | number        |
| No       |                | longitude  | Longitude  | number        | number        |
| No       |                | x          | X          | number        | number        |
| No       |                | y          | Y          | number        | number        |
| Yes      | series tag     | location_t | Location_T | text          | text          |
| Yes      | series tag     | remarks    | Remarks    | text          | text          |
| Yes      | series tag     | city       | City       | text          | text          |
| Yes      | series tag     | ssid       | SSID       | text          | text          |
| Yes      | series tag     | sourceid   | SourceID   | text          | text          |
| Yes      | time           | activated  | Activated  | calendar_date | calendar_date |
| Yes      | series tag     | borocode   | BoroCode   | text          | number        |
| Yes      | series tag     | boroname   | BoroName   | text          | text          |
| Yes      | series tag     | ntacode    | NTACode    | text          | text          |
| Yes      | series tag     | ntaname    | NTAName    | text          | text          |
| Yes      | numeric metric | coundist   | CounDist   | number        | number        |
| Yes      | series tag     | zip        | ZIP        | text          | number        |
| Yes      | numeric metric | borocd     | BoroCD     | number        | number        |
| Yes      | numeric metric | ct2010     | CT2010     | number        | number        |
| Yes      | numeric metric | bctcb2010  | BCTCB2010  | number        | number        |
| Yes      | numeric metric | bin        | BIN        | number        | number        |
| Yes      | numeric metric | bbl        | BBL        | number        | number        |
```

## Time Field

```ls
Value = activated
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = latitude,longitude,x,y
```

## Data Commands

```ls
series e:yjub-udmw d:2017-04-10T17:39:46.000Z t:borocode=3 t:zip=11205 t:location="138 Cumberland Walk" t:borough=BK t:provider=NYCHA t:type=Free t:city=Brooklyn t:boroname=Brooklyn t:location_t=Outdoor t:ntaname="Fort Greene" t:name=0 t:ntacode=BK68 t:ssid=DowntownBrooklynWiFi_Fon t:objectid=1673 m:coundist=35 m:ct2010=18501 m:borocd=302 m:bctcb2010=30185013001 m:bin=0

series e:yjub-udmw d:2017-04-10T17:39:45.000Z t:borocode=1 t:zip=10007 t:location="Fulton St (A,C,J,Z,2,3,4,5)" t:provider="Transit Wireless" t:remarks="SN 412" t:borough=MN t:type=Free t:city="New York" t:boroname=Manhattan t:location_t="Subway Station" t:ntaname="Battery Park City-Lower Manhattan" t:name="Fulton St (J,M,Z,2,3,4,5)/Bway-Nassau St (A,C) (4-5)" t:ntacode=MN25 t:ssid=TransitWirelessWiFi t:objectid=2364 m:coundist=1 m:ct2010=1502 m:borocd=101 m:bctcb2010=10015021000 m:bin=0

series e:yjub-udmw d:2017-04-10T17:39:45.000Z t:borocode=1 t:zip=10016 t:location="28th Street - Park Avenue South" t:provider="Transit Wireless" t:remarks="SN 404" t:borough=MN t:type=Free t:city="New York" t:boroname=Manhattan t:location_t="Subway Station" t:ntaname="Hudson Yards-Chelsea-Flatiron-Union Square" t:name="28th Street - (6)" t:ntacode=MN13 t:ssid=TransitWirelessWiFi t:objectid=2258 m:coundist=2 m:ct2010=5600 m:borocd=105 m:bctcb2010=10056001000 m:bin=0
```

## Meta Commands

```ls
metric m:coundist p:integer l:CounDist d:"NYC City Council District number" t:dataTypeName=number

metric m:borocd p:integer l:BoroCD d:"New York City Borough plus Community Board Numbers." t:dataTypeName=number

metric m:ct2010 p:integer l:CT2010 d:"2010 U.S. Census data based on location." t:dataTypeName=number

metric m:bctcb2010 p:long l:BCTCB2010 d:"Combined value of Borough CD and Census 2010." t:dataTypeName=number

metric m:bin p:integer l:BIN d:"Building Identification Number." t:dataTypeName=number

metric m:bbl p:long l:BBL d:"Borough Block Lot." t:dataTypeName=number

entity e:yjub-udmw l:"NYC Wi-Fi Hotspot Locations" t:attribution="Department of Information Technology & Telecommunications (DoITT)" t:url=https://data.cityofnewyork.us/api/views/yjub-udmw

property e:yjub-udmw t:meta.view v:id=yjub-udmw v:category="City Government" v:averageRating=0 v:name="NYC Wi-Fi Hotspot Locations" v:attribution="Department of Information Technology & Telecommunications (DoITT)"

property e:yjub-udmw t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:yjub-udmw t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| objectid | borough | type | provider             | name                                                 | location                        | latitude       | longitude       | x                  | y                  | location_t     | remarks                                          | city     | ssid                     | sourceid    | activated           | borocode | boroname  | ntacode | ntaname                                    | coundist | zip   | borocd | ct2010 | bctcb2010   | bin | bbl | 
| ======== | ======= | ==== | ==================== | ==================================================== | =============================== | ============== | =============== | ================== | ================== | ============== | ================================================ | ======== | ======================== | =========== | =================== | ======== | ========= | ======= | ========================================== | ======== | ===== | ====== | ====== | =========== | === | === | 
| 1673     | BK      | Free | NYCHA                | 0                                                    | 138 Cumberland Walk             | 40.69438200000 | -73.97461400000 | 991289.58870800000 | 192259.55524200000 | Outdoor        |                                                  | Brooklyn | DowntownBrooklynWiFi_Fon |             |                     | 3        | Brooklyn  | BK68    | Fort Greene                                | 35       | 11205 | 302    | 18501  | 30185013001 | 0   |     | 
| 2364     | MN      | Free | Transit Wireless     | Fulton St (J,M,Z,2,3,4,5)/Bway-Nassau St (A,C) (4-5) | Fulton St (A,C,J,Z,2,3,4,5)     | 40.71036800000 | -74.00950900000 | 981613.74666100000 | 198082.85529800000 | Subway Station | SN 412                                           | New York | TransitWirelessWiFi      |             |                     | 1        | Manhattan | MN25    | Battery Park City-Lower Manhattan          | 1        | 10007 | 101    | 1502   | 10015021000 | 0   |     | 
| 2258     | MN      | Free | Transit Wireless     | 28th Street - (6)                                    | 28th Street - Park Avenue South | 40.74307000000 | -73.98426400000 | 988610.47221600000 | 209997.45729300000 | Subway Station | SN 404                                           | New York | TransitWirelessWiFi      |             |                     | 1        | Manhattan | MN13    | Hudson Yards-Chelsea-Flatiron-Union Square | 2        | 10016 | 105    | 5600   | 10056001000 | 0   |     | 
| 3391     | MN      | Free | LinkNYC - Citybridge | mn-05-121626                                         | 63 Madison Ave                  | 40.74338100000 | -73.98596300000 | 988139.65829000000 | 210110.68449300000 | Outdoor Kiosk  | Tablet Internet -phone , Free 1 GB Wi-FI Service | New York | LinkNYC Free Wi-Fi       | LINK-011982 | 2016-12-09T00:00:00 | 1        | Manhattan | MN13    | Hudson Yards-Chelsea-Flatiron-Union Square | 2        | 10016 | 105    | 5600   | 10056001000 | 0   |     | 
| 3448     | MN      | Free | LinkNYC - Citybridge | mn-05-139806                                         | 1170 Broadway                   | 40.74512600000 | -73.98866100000 | 987391.95912400000 | 210746.33539300000 | Outdoor Kiosk  | Tablet Internet -phone , Free 1 GB Wi-FI Service | New York | LinkNYC Free Wi-Fi       | LINK-000120 | 2016-11-02T00:00:00 | 1        | Manhattan | MN13    | Hudson Yards-Chelsea-Flatiron-Union Square | 2        | 10001 | 105    | 5800   | 10058001000 | 0   |     | 
| 968      | MN      | Free | Chelsea              |                                                      | 17th near 9th                   | 40.74247745350 | -74.00296211240 | 983429.18634100000 | 209781.19597300000 | Outdoor        |                                                  | New York | CICFreeWiFi              |             |                     | 1        | Manhattan | MN13    | Hudson Yards-Chelsea-Flatiron-Union Square | 3        | 10011 | 104    | 8300   | 10083001000 | 0   |     | 
| 3347     | MN      | Free | LinkNYC - Citybridge | mn-04-108537                                         | 159 8 Avenue                    | 40.74229700000 | -74.00094000000 | 983989.52138700000 | 209715.43852400000 | Outdoor Kiosk  | Tablet Internet -phone , Free 1 GB Wi-FI Service | New York | LinkNYC Free Wi-Fi       | LINK-000453 | 2016-04-07T00:00:00 | 1        | Manhattan | MN13    | Hudson Yards-Chelsea-Flatiron-Union Square | 3        | 10011 | 104    | 8300   | 10083001000 | 0   |     | 
| 959      | MN      | Free | Chelsea              |                                                      | 19th between 9th and 10th r     | 40.74457030860 | -74.00458853680 | 982978.53730800000 | 210543.70921200000 | Outdoor        |                                                  | New York | CICFreeWiFi              |             |                     | 1        | Manhattan | MN13    | Hudson Yards-Chelsea-Flatiron-Union Square | 3        | 10011 | 104    | 8900   | 10089003001 | 0   |     | 
| 3411     | MN      | Free | LinkNYC - Citybridge | mn-05-122453                                         | 341 7 AVENUE                    | 40.74790400000 | -73.99274500000 | 986260.22691500000 | 211758.32967100000 | Outdoor Kiosk  | Tablet Internet -phone , Free 1 GB Wi-FI Service | New York | LinkNYC Free Wi-Fi       | LINK-013873 | 2016-12-16T00:00:00 | 1        | Manhattan | MN17    | Midtown-Midtown South                      | 3        | 10001 | 105    | 9500   | 10095001000 | 0   |     | 
| 3395     | MN      | Free | LinkNYC - Citybridge | mn-05-121798                                         | 133 E 55 St                     | 40.75980900000 | -73.97036800000 | 992459.01421500000 | 216097.01231200000 | Outdoor Kiosk  | Tablet Internet -phone , Free 1 GB Wi-FI Service | New York | LinkNYC Free Wi-Fi       | LINK-000626 | 2017-03-23T00:00:00 | 1        | Manhattan | MN19    | Turtle Bay-East Midtown                    | 4        | 10022 | 105    | 10000  | 10100001000 | 0   |     | 
```