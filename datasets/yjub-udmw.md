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
| Publication Date | 2017-08-11T18:37:46Z |

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
| Yes      | series tag     | zip        | Postcode   | text          | number        |
| Yes      | numeric metric | borocd     | BoroCD     | number        | number        |
| Yes      | numeric metric | ct2010     | CT2010     | number        | number        |
| Yes      | numeric metric | bctcb2010  | BCTCB2010  | number        | number        |
| Yes      | numeric metric | bin        | BIN        | number        | number        |
| Yes      | numeric metric | bbl        | BBL        | number        | number        |
| Yes      | series tag     | doitt_id   | DOITT_ID   | text          | number        |
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
series e:yjub-udmw d:2017-01-18T00:00:00.000Z t:sourceid=LINK-008695 t:zip=10001 t:city="New York" t:boroname=Manhattan t:borough=MN t:type=Free t:location_t="Outdoor Kiosk" t:ntaname="Midtown-Midtown South" t:ssid="LinkNYC Free Wi-Fi" t:borocode=1 t:ntacode=MN17 t:doitt_id=1425 t:provider="LinkNYC - Citybridge" t:name=mn-05-123662 t:location="179 WEST 26 STREET" t:objectid=998 t:remarks="Tablet Internet -phone , Free 1 GB Wi-FI Service" m:bin=0 m:coundist=3 m:borocd=105 m:ct2010=95 m:bctcb2010=1009500 m:bbl=0

series e:yjub-udmw d:2017-06-21T00:00:00.000Z t:sourceid=LINK-014013 t:zip=10016 t:city="New York" t:boroname=Manhattan t:borough=MN t:type=Free t:location_t="Outdoor Kiosk" t:ntaname="Midtown-Midtown South" t:ssid="LinkNYC Free Wi-Fi" t:borocode=1 t:ntacode=MN17 t:doitt_id=1426 t:provider="LinkNYC - Citybridge" t:name=mn-05-123789 t:location="25 EAST 29 STREET" t:objectid=999 t:remarks="Tablet Internet -phone , Free 1 GB Wi-FI Service" m:bin=1016929 m:coundist=2 m:borocd=105 m:ct2010=74 m:bctcb2010=1007400 m:bbl=1008590024

series e:yjub-udmw d:2017-08-11T18:35:28.000Z t:sourceid=LINK-007083 t:zip=10036 t:city="New York" t:boroname=Manhattan t:borough=MN t:type=Free t:location_t="Outdoor Kiosk" t:ntaname="Midtown-Midtown South" t:ssid="LinkNYC Free Wi-Fi" t:borocode=1 t:ntacode=MN17 t:doitt_id=1427 t:provider="LinkNYC - Citybridge" t:name=mn-05-133354 t:location="1515 BROADWAY" t:objectid=1000 t:remarks="Tablet Internet -phone , Free 1 GB Wi-FI Service" m:bin=1024714 m:coundist=3 m:borocd=105 m:ct2010=119 m:bctcb2010=1011900 m:bbl=1010160036
```

## Meta Commands

```ls
metric m:coundist p:float l:CounDist d:"NYC City Council District number" t:dataTypeName=number

metric m:borocd p:float l:BoroCD d:"New York City Borough plus Community Board Numbers." t:dataTypeName=number

metric m:ct2010 p:float l:CT2010 d:"2010 U.S. Census data based on location." t:dataTypeName=number

metric m:bctcb2010 p:float l:BCTCB2010 d:"Combined value of Borough CD and Census 2010." t:dataTypeName=number

metric m:bin p:float l:BIN d:"Building Identification Number." t:dataTypeName=number

metric m:bbl p:double l:BBL d:"Borough Block Lot." t:dataTypeName=number

entity e:yjub-udmw l:"NYC Wi-Fi Hotspot Locations" t:attribution="Department of Information Technology & Telecommunications (DoITT)" t:url=https://data.cityofnewyork.us/api/views/yjub-udmw

property e:yjub-udmw t:meta.view d:2017-09-25T07:31:20.557Z v:averageRating=0 v:name="NYC Wi-Fi Hotspot Locations" v:attribution="Department of Information Technology & Telecommunications (DoITT)" v:id=yjub-udmw v:category="City Government"

property e:yjub-udmw t:meta.view.owner d:2017-09-25T07:31:20.557Z v:displayName="NYC OpenData" v:lastNotificationSeenAt=1496414226 v:id=5fuc-pqz2 v:screenName="NYC OpenData"

property e:yjub-udmw t:meta.view.tableauthor d:2017-09-25T07:31:20.557Z v:displayName="NYC OpenData" v:lastNotificationSeenAt=1496414226 v:roleName=administrator v:id=5fuc-pqz2 v:screenName="NYC OpenData"
```

## Top Records

```ls
| objectid | borough | type | provider             | name         | location           | latitude       | longitude       | x                  | y                  | location_t    | remarks                                          | city     | ssid               | sourceid    | activated           | borocode | boroname  | ntacode | ntaname               | coundist      | zip   | borocd          | ct2010          | bctcb2010           | bin                 | bbl                    | doitt_id | 
| ======== | ======= | ==== | ==================== | ============ | ================== | ============== | =============== | ================== | ================== | ============= | ================================================ | ======== | ================== | =========== | =================== | ======== | ========= | ======= | ===================== | ============= | ===== | =============== | =============== | =================== | =================== | ====================== | ======== | 
| 998      | MN      | Free | LinkNYC - Citybridge | mn-05-123662 | 179 WEST 26 STREET | 40.74596800000 | -73.99403900000 | 985901.69530700000 | 211053.13064400000 | Outdoor Kiosk | Tablet Internet -phone , Free 1 GB Wi-FI Service | New York | LinkNYC Free Wi-Fi | LINK-008695 | 2017-01-18T00:00:00 | 1        | Manhattan | MN17    | Midtown-Midtown South | 3.00000000000 | 10001 | 105.00000000000 | 95.00000000000  | 1009500.00000000000 | 0.00000000000       | 0.00000000000          | 1425     | 
| 999      | MN      | Free | LinkNYC - Citybridge | mn-05-123789 | 25 EAST 29 STREET  | 40.74461400000 | -73.98506900000 | 988387.30947300000 | 210559.94668400000 | Outdoor Kiosk | Tablet Internet -phone , Free 1 GB Wi-FI Service | New York | LinkNYC Free Wi-Fi | LINK-014013 | 2017-06-21T00:00:00 | 1        | Manhattan | MN17    | Midtown-Midtown South | 2.00000000000 | 10016 | 105.00000000000 | 74.00000000000  | 1007400.00000000000 | 1016929.00000000000 | 1008590024.00000000000 | 1426     | 
| 1000     | MN      | Free | LinkNYC - Citybridge | mn-05-133354 | 1515 BROADWAY      | 40.75766600000 | -73.98587800000 | 988162.25644900000 | 215315.02126300000 | Outdoor Kiosk | Tablet Internet -phone , Free 1 GB Wi-FI Service | New York | LinkNYC Free Wi-Fi | LINK-007083 |                     | 1        | Manhattan | MN17    | Midtown-Midtown South | 3.00000000000 | 10036 | 105.00000000000 | 119.00000000000 | 1011900.00000000000 | 1024714.00000000000 | 1010160036.00000000000 | 1427     | 
| 1001     | MN      | Free | LinkNYC - Citybridge | mn-05-133359 | 201 WEST 48 STREET | 40.75997100000 | -73.98434200000 | 988587.75761700000 | 216155.03344800000 | Outdoor Kiosk | Tablet Internet -phone , Free 1 GB Wi-FI Service | New York | LinkNYC Free Wi-Fi | LINK-003309 | 2016-11-10T00:00:00 | 1        | Manhattan | MN17    | Midtown-Midtown South | 4.00000000000 | 10036 | 105.00000000000 | 125.00000000000 | 1012500.00000000000 | 1076195.00000000000 | 1010200046.00000000000 | 1428     | 
| 1002     | MN      | Free | LinkNYC - Citybridge | mn-05-133361 | 1600 Broadway      | 40.76041300000 | -73.98454100000 | 988532.65536000000 | 216316.03688100000 | Outdoor Kiosk | Tablet Internet -phone , Free 1 GB Wi-FI Service | New York | LinkNYC Free Wi-Fi | LINK-000162 | 2016-07-18T00:00:00 | 1        | Manhattan | MN17    | Midtown-Midtown South | 4.00000000000 | 10019 | 105.00000000000 | 125.00000000000 | 1012500.00000000000 | 1087187.00000000000 | 1010207502.00000000000 | 1429     | 
| 1003     | MN      | Free | LinkNYC - Citybridge | mn-05-133505 | 1668 Broadway      | 40.76259300000 | -73.98307700000 | 988938.04546000000 | 217110.48854000000 | Outdoor Kiosk | Tablet Internet -phone , Free 1 GB Wi-FI Service | New York | LinkNYC Free Wi-Fi | LINK-000173 | 2016-10-28T00:00:00 | 1        | Manhattan | MN17    | Midtown-Midtown South | 4.00000000000 | 10019 | 105.00000000000 | 131.00000000000 | 1013100.00000000000 | 1024818.00000000000 | 1010230029.00000000000 | 1430     | 
| 1004     | MN      | Free | LinkNYC - Citybridge | mn-05-133508 | 1626 Broadway      | 40.76088300000 | -73.98427700000 | 988605.59699200000 | 216487.22433500000 | Outdoor Kiosk | Tablet Internet -phone , Free 1 GB Wi-FI Service | New York | LinkNYC Free Wi-Fi | LINK-000168 | 2016-07-18T00:00:00 | 1        | Manhattan | MN17    | Midtown-Midtown South | 4.00000000000 | 10019 | 105.00000000000 | 125.00000000000 | 1012500.00000000000 | 1024795.00000000000 | 1010210026.00000000000 | 1431     | 
| 1005     | MN      | Free | LinkNYC - Citybridge | mn-05-133511 | 1606 Broadway      | 40.76063200000 | -73.98428300000 | 988604.08922900000 | 216395.92389200000 | Outdoor Kiosk | Tablet Internet -phone , Free 1 GB Wi-FI Service | New York | LinkNYC Free Wi-Fi | LINK-000165 | 2016-07-19T00:00:00 | 1        | Manhattan | MN17    | Midtown-Midtown South | 4.00000000000 | 10019 | 105.00000000000 | 125.00000000000 | 1012500.00000000000 | 1024779.00000000000 | 1010200038.00000000000 | 1432     | 
| 1006     | MN      | Free | LinkNYC - Citybridge | mn-05-133538 | 300 Madison Ave    | 40.75233500000 | -73.97973800000 | 989863.78714400000 | 213373.34647400000 | Outdoor Kiosk | Tablet Internet -phone , Free 1 GB Wi-FI Service | New York | LinkNYC Free Wi-Fi | LINK-000726 | 2017-05-04T00:00:00 | 1        | Manhattan | MN20    | Murray Hill-Kips Bay  | 4.00000000000 | 10017 | 105.00000000000 | 82.00000000000  | 1008200.00000000000 | 1085972.00000000000 | 1012760058.00000000000 | 1433     | 
| 1007     | MN      | Free | LinkNYC - Citybridge | mn-05-133550 | 370 Lexington Ave  | 40.75083300000 | -73.97681700000 | 990673.37478200000 | 212826.12701300000 | Outdoor Kiosk | Tablet Internet -phone , Free 1 GB Wi-FI Service | New York | LinkNYC Free Wi-Fi | LINK-000666 | 2017-05-19T00:00:00 | 1        | Manhattan | MN20    | Murray Hill-Kips Bay  | 4.00000000000 | 10017 | 105.00000000000 | 80.00000000000  | 1008000.00000000000 | 1036150.00000000000 | 1012950058.00000000000 | 1434     | 
```