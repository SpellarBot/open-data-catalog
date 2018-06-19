# Community Board Appointments

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/community-board-appointments-699cb) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/3gkd-ddzn) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/3gkd-ddzn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/3gkd-ddzn/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 3gkd-ddzn |
| Name | Community Board Appointments |
| Attribution | Manhattan Borough President (MBP) |
| Category | City Government |
| Tags | community board appointments, mbp, manhattan borough president (mbp) |
| Created | 2014-03-06T17:40:48Z |
| Publication Date | 2017-09-14T20:43:38Z |

## Description

This list contains information on community board appointments.

## Columns

```ls
| Included | Schema Type    | Field Name                    | Name                          | Data Type | Render Type |
| ======== | ============== | ============================= | ============================= | ========= | =========== |
| No       | time           | :updated_at                   | updated_at                    | meta_data | meta_data   |
| Yes      | series tag     | community_board_number        | Community Board Number        | text      | number      |
| Yes      | series tag     | chair                         | Chair                         | text      | text        |
| Yes      | series tag     | district_manager              | District Manager              | text      | text        |
| Yes      | series tag     | board_meeting_cabinet_meeting | Board Meeting/Cabinet Meeting | text      | text        |
| Yes      | series tag     | location_2                    | Location 2                    | text      | text        |
| No       |                | latitude                      | Latitude                      | number    | number      |
| No       |                | longitude                     | Longitude                     | number    | number      |
| Yes      | numeric metric | community_board               | Community Board               | number    | number      |
| Yes      | numeric metric | community_council             | Community Council             | number    | number      |
| Yes      | numeric metric | census_tract                  | Census Tract                  | number    | number      |
| Yes      | numeric metric | bin                           | BIN                           | number    | number      |
| Yes      | numeric metric | bbl                           | BBL                           | number    | number      |
| Yes      | series tag     | nta                           | NTA                           | text      | text        |
| Yes      | series tag     | postcode                      | Postcode                      | text      | number      |
| Yes      | series tag     | borough                       | Borough                       | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = latitude,longitude
```

## Data Commands

```ls
series e:3gkd-ddzn d:2017-09-14T20:43:14.000Z t:chair="Georgette Morgan-Thomas" t:board_meeting_cabinet_meeting="Third Thursday, 6:30 PM" t:postcode=10027 t:district_manager="Eutha R. Prince" t:community_board_number=9 t:nta=Manhattanville t:borough=MANHATTAN m:bin=1059714 m:community_board=9 m:bbl=1019820067 m:community_council=7 m:census_tract=219

series e:3gkd-ddzn d:2017-09-14T20:43:14.000Z t:chair="Mark N. Diller" t:board_meeting_cabinet_meeting="First Tuesday, 6:30PM" t:postcode=10024 t:district_manager="Penny Ryan" t:community_board_number=7 t:nta="Upper West Side" t:borough=MANHATTAN m:bin=1076251 m:community_board=7 m:bbl=1012347501 m:community_council=6 m:census_tract=175

series e:3gkd-ddzn d:2017-09-14T20:43:14.000Z t:chair="Henrietta Lyle" t:board_meeting_cabinet_meeting="First Wednesday, 6PM" t:postcode=10027 t:district_manager="Christopher T. Wooley" t:community_board_number=10 t:nta="Central Harlem South" t:borough=MANHATTAN t:location_2="4th floor" m:bin=1058659 m:community_board=10 m:bbl=1019310021 m:community_council=9 m:census_tract=222
```

## Meta Commands

```ls
metric m:community_board p:integer l:"Community Board" t:dataTypeName=number

metric m:community_council p:integer l:"Community Council" t:dataTypeName=number

metric m:census_tract p:integer l:"Census Tract" t:dataTypeName=number

metric m:bin p:integer l:BIN t:dataTypeName=number

metric m:bbl p:integer l:BBL t:dataTypeName=number

entity e:3gkd-ddzn l:"Community Board Appointments" t:attribution="Manhattan Borough President (MBP)" t:url=https://data.cityofnewyork.us/api/views/3gkd-ddzn

property e:3gkd-ddzn t:meta.view d:2017-09-25T07:31:13.214Z v:averageRating=0 v:name="Community Board Appointments" v:attribution="Manhattan Borough President (MBP)" v:id=3gkd-ddzn v:category="City Government"

property e:3gkd-ddzn t:meta.view.owner d:2017-09-25T07:31:13.214Z v:displayName="NYC OpenData" v:lastNotificationSeenAt=1496414226 v:id=5fuc-pqz2 v:screenName="NYC OpenData"

property e:3gkd-ddzn t:meta.view.tableauthor d:2017-09-25T07:31:13.214Z v:displayName="NYC OpenData" v:lastNotificationSeenAt=1496414226 v:roleName=administrator v:id=5fuc-pqz2 v:screenName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | community_board_number | chair                   | district_manager      | board_meeting_cabinet_meeting | location_2   | latitude  | longitude  | community_board | community_council | census_tract | bin     | bbl        | nta                                    | postcode | borough   | 
| =========== | ====================== | ======================= | ===================== | ============================= | ============ | ========= | ========== | =============== | ================= | ============ | ======= | ========== | ====================================== | ======== | ========= | 
| 1505421794  | 9                      | Georgette Morgan-Thomas | Eutha R. Prince       | Third Thursday, 6:30 PM       |              | 40.815433 | -73.957204 | 9               | 7                 | 219          | 1059714 | 1019820067 | Manhattanville                         | 10027    | MANHATTAN | 
| 1505421794  | 7                      | Mark N. Diller          | Penny Ryan            | First Tuesday, 6:30PM         |              | 40.789078 | -73.976245 | 7               | 6                 | 175          | 1076251 | 1012347501 | Upper West Side                        | 10024    | MANHATTAN | 
| 1505421794  | 10                     | Henrietta Lyle          | Christopher T. Wooley | First Wednesday, 6PM          | 4th floor    | 40.809259 | -73.948979 | 10              | 9                 | 222          | 1058659 | 1019310021 | Central Harlem South                   | 10027    | MANHATTAN | 
| 1505421794  | 12                     | George Fernandez        | Ebenezer Smith        | Fourth Tuesday, 7PM           | Ground Floor | 40.842259 | -73.942481 | 12              | 10                | 255          | 1063402 | 1021390051 | Washington Heights South               | 10032    | MANHATTAN | 
| 1505421794  | 6                      | Sandro Sherrod          | Dan Miner             | Second Wednesday, 7PM         | Suite 308    | 40.752925 | -73.966834 | 6               | 4                 | 8603         | 1040072 | 1013607501 | Turtle Bay-East Midtown                | 10017    | MANHATTAN | 
| 1505421794  | 11                     | Matthew Washington      | George Sarkissian     | Third Tuesday, 6:30PM         | Ground Floor | 40.800223 | -73.942564 | 11              | 9                 | 184          | 1051688 | 1016230035 | East Harlem North                      | 10035    | MANHATTAN | 
| 1505421794  | 2                      | David Gruber            | Bob Gormley           | Second to last Thursday, 6PM  | 1A           | 40.727881 | -73.998557 | 2               | 1                 | 5501         | 1077835 | 1005330001 | West Village                           | 10012    | MANHATTAN | 
| 1505421794  | 1                      | Catherine McVey-Hughes  | Noah Pfefferbilt      | Fourth Tuesday, 6PM           | Room 715     | 40.713767 | -74.005429 | 1               | 1                 | 31           | 1079216 | 1001530018 | SoHo-TriBeCa-Civic Center-Little Italy | 10007    | MANHATTAN | 
| 1505421794  | 8                      | Nicholas Viest          | Latha Thompson        | Third Wednesday, 6:30PM       | Suite 620    | 40.763117 | -73.969641 | 8               | 4                 | 11402        | 1041900 | 1013940001 | Upper East Side-Carnegie Hill          | 10022    | MANHATTAN | 
| 1505421794  | 4                      | Corey Johnson           | Robert J. Benfatto    | First Wednesday. 6:30PM       | Suite 2618   | 40.757661 | -73.990832 | 4               | 3                 | 115          | 1024926 | 1010320048 | Clinton                                | 10036    | MANHATTAN | 
```