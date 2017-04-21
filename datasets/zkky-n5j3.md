# Water Resevoir Levels

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/water-resevoir-levels-76ae8) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/zkky-n5j3) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/zkky-n5j3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/zkky-n5j3/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | zkky-n5j3 |
| Name | Water Resevoir Levels |
| Attribution | Department of Environmental Protection (DEP) |
| Category | Environment |
| Tags | department of environmental protection, dep, environment, water, reservoir, health, ecosystem, eco-system, agua, water system, water supply, nyc, tap, tap water, conservation, healthy living |
| Created | 2011-08-30T21:44:25Z |
| Publication Date | 2013-06-21T19:42:55Z |

## Description

New York City water supply system reservoir levels

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type | Render Type |
| ======== | ============== | ====================== | ====================== | ========= | =========== |
| Yes      | time           | neversink_date         | Neversink Date         | date      | date        |
| Yes      | numeric metric | neversink_elevation    | Neversink Elevation    | number    | number      |
| Yes      | numeric metric | neversink_storage      | Neversink Storage      | number    | number      |
| No       |                | rondout_date           | Rondout Date           | date      | date        |
| Yes      | numeric metric | rondout_elevation      | Rondout Elevation      | number    | number      |
| Yes      | numeric metric | rondout_storage        | Rondout Storage        | number    | number      |
| No       |                | schoharie_date         | Schoharie Date         | date      | date        |
| Yes      | numeric metric | schoharie_elevation    | Schoharie Elevation    | number    | number      |
| Yes      | numeric metric | schoharie_storage      | Schoharie Storage      | number    | number      |
| No       |                | cannonsville_date      | Cannonsville Date      | date      | date        |
| Yes      | numeric metric | cannonsville_elevation | Cannonsville Elevation | number    | number      |
| Yes      | numeric metric | cannonsville_storage   | Cannonsville Storage   | number    | number      |
| No       |                | pepacton_date          | Pepacton Date          | date      | date        |
| Yes      | numeric metric | pepacton_elevation     | Pepacton Elevation     | number    | number      |
| Yes      | numeric metric | pepacton_storage       | Pepacton Storage       | number    | number      |
| No       |                | ashokan_east_date      | Ashokan East Date      | date      | date        |
| Yes      | numeric metric | ashokan_east_elevation | Ashokan East Elevation | number    | number      |
| Yes      | numeric metric | ashokan_east_storage   | Ashokan East Storage   | number    | number      |
| No       |                | ashokan_west_date      | Ashokan West Date      | date      | date        |
| Yes      | numeric metric | ashokan_west_elevation | Ashokan West Elevation | number    | number      |
| Yes      | numeric metric | ashokan_west_storage   | Ashokan West Storage   | number    | number      |
```

## Time Field

```ls
Value = neversink_date
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = rondout_date,schoharie_date,cannonsville_date,pepacton_date,ashokan_east_date,ashokan_west_date
```

## Data Commands

```ls
series e:zkky-n5j3 d:2005-03-01T16:00:00.000Z m:pepacton_storage=138986 m:schoharie_storage=19618 m:ashokan_west_elevation=587.24 m:schoharie_elevation=1130.09 m:rondout_elevation=835.1 m:ashokan_east_elevation=586.61 m:cannonsville_elevation=1150.33 m:ashokan_east_storage=79856 m:cannonsville_storage=97257 m:pepacton_elevation=1277.42 m:rondout_storage=46757 m:neversink_storage=35570 m:ashokan_west_storage=44432 m:neversink_elevation=1440.21

series e:zkky-n5j3 d:2005-03-02T16:00:00.000Z m:pepacton_storage=138696 m:schoharie_storage=19610 m:ashokan_west_elevation=586.93 m:schoharie_elevation=1130.07 m:rondout_elevation=834.98 m:ashokan_east_elevation=586.61 m:cannonsville_elevation=1150.29 m:ashokan_east_storage=79856 m:cannonsville_storage=97193 m:pepacton_elevation=1277.26 m:rondout_storage=46678 m:neversink_storage=35575 m:ashokan_west_storage=44123 m:neversink_elevation=1440.22

series e:zkky-n5j3 d:2005-03-03T16:00:00.000Z m:pepacton_storage=138406 m:schoharie_storage=19602 m:ashokan_west_elevation=586.61 m:schoharie_elevation=1130.05 m:rondout_elevation=834.84 m:ashokan_east_elevation=586.6 m:cannonsville_elevation=1150.22 m:ashokan_east_storage=79839 m:cannonsville_storage=97080 m:pepacton_elevation=1277.1 m:rondout_storage=46585 m:neversink_storage=35570 m:ashokan_west_storage=43804 m:neversink_elevation=1440.21
```

## Meta Commands

```ls
metric m:neversink_elevation p:float l:"Neversink Elevation" t:dataTypeName=number

metric m:neversink_storage p:integer l:"Neversink Storage" t:dataTypeName=number

metric m:rondout_elevation p:float l:"Rondout Elevation" t:dataTypeName=number

metric m:rondout_storage p:integer l:"Rondout Storage" t:dataTypeName=number

metric m:schoharie_elevation p:float l:"Schoharie Elevation" t:dataTypeName=number

metric m:schoharie_storage p:integer l:"Schoharie Storage" t:dataTypeName=number

metric m:cannonsville_elevation p:float l:"Cannonsville Elevation" t:dataTypeName=number

metric m:cannonsville_storage p:integer l:"Cannonsville Storage" t:dataTypeName=number

metric m:pepacton_elevation p:float l:"Pepacton Elevation" t:dataTypeName=number

metric m:pepacton_storage p:integer l:"Pepacton Storage" t:dataTypeName=number

metric m:ashokan_east_elevation p:float l:"Ashokan East Elevation" t:dataTypeName=number

metric m:ashokan_east_storage p:integer l:"Ashokan East Storage" t:dataTypeName=number

metric m:ashokan_west_elevation p:float l:"Ashokan West Elevation" t:dataTypeName=number

metric m:ashokan_west_storage p:integer l:"Ashokan West Storage" t:dataTypeName=number

entity e:zkky-n5j3 l:"Water Resevoir Levels" t:attribution="Department of Environmental Protection (DEP)" t:url=https://data.cityofnewyork.us/api/views/zkky-n5j3

property e:zkky-n5j3 t:meta.view v:id=zkky-n5j3 v:category=Environment v:averageRating=0 v:name="Water Resevoir Levels" v:attribution="Department of Environmental Protection (DEP)"

property e:zkky-n5j3 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:zkky-n5j3 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| neversink_date | neversink_elevation | neversink_storage | rondout_date | rondout_elevation | rondout_storage | schoharie_date | schoharie_elevation | schoharie_storage | cannonsville_date | cannonsville_elevation | cannonsville_storage | pepacton_date | pepacton_elevation | pepacton_storage | ashokan_east_date | ashokan_east_elevation | ashokan_east_storage | ashokan_west_date | ashokan_west_elevation | ashokan_west_storage | 
| ============== | =================== | ================= | ============ | ================= | =============== | ============== | =================== | ================= | ================= | ====================== | ==================== | ============= | ================== | ================ | ================= | ====================== | ==================== | ================= | ====================== | ==================== | 
| 1109692800     | 1440.21             | 35570             | 1109692800   | 835.1             | 46757           | 1109692800     | 1130.09             | 19618             | 1109779200        | 1150.33                | 97257                | 1109692800    | 1277.42            | 138986           | 1109692800        | 586.61                 | 79856                | 1109692800        | 587.24                 | 44432                | 
| 1109779200     | 1440.22             | 35575             | 1109779200   | 834.98            | 46678           | 1109779200     | 1130.07             | 19610             | 1109865600        | 1150.29                | 97193                | 1109779200    | 1277.26            | 138696           | 1109779200        | 586.61                 | 79856                | 1109779200        | 586.93                 | 44123                | 
| 1109865600     | 1440.21             | 35570             | 1109865600   | 834.84            | 46585           | 1109865600     | 1130.05             | 19602             | 1109952000        | 1150.22                | 97080                | 1109865600    | 1277.1             | 138406           | 1109865600        | 586.6                  | 79839                | 1109865600        | 586.61                 | 43804                | 
| 1109952000     | 1440.21             | 35570             | 1109952000   | 834.85            | 46592           | 1109952000     | 1130.04             | 19599             | 1110038400        | 1150.14                | 96951                | 1109952000    | 1276.9             | 138045           | 1109952000        | 586.61                 | 79856                | 1109952000        | 586.31                 | 43505                | 
| 1110038400     | 1440.21             | 35570             | 1110038400   | 834.88            | 46612           | 1110038400     | 1130.04             | 19599             | 1110124800        | 1149.97                | 96680                | 1110038400    | 1276.72            | 137721           | 1110038400        | 586.61                 | 79856                | 1110038400        | 586                    | 43197                | 
| 1110124800     | 1440.21             | 35570             | 1110124800   | 834.97            | 46671           | 1110124800     | 1130.05             | 19602             | 1110211200        | 1150.14                | 96951                | 1110124800    | 1276.56            | 137434           | 1110124800        | 586.6                  | 79839                | 1110124800        | 585.84                 | 43037                | 
| 1110211200     | 1440.21             | 35570             | 1110211200   | 835.07            | 46737           | 1110211200     | 1130.19             | 19657             | 1110297600        | 1150.26                | 97144                | 1110211200    | 1276.38            | 137110           | 1110211200        | 586.65                 | 79923                | 1110211200        | 585.82                 | 43017                | 
| 1110297600     | 1440.24             | 35585             | 1110297600   | 835.18            | 46810           | 1110297600     | 1130.16             | 19645             | 1110384000        | 1150.21                | 97064                | 1110297600    | 1276.31            | 136984           | 1110297600        | 586.65                 | 79923                | 1110297600        | 585.82                 | 43017                | 
| 1110384000     | 1440.22             | 35575             | 1110384000   | 835.23            | 46843           | 1110384000     | 1130.11             | 19626             | 1110470400        | 1150.24                | 97112                | 1110384000    | 1276.21            | 136804           | 1110384000        | 586.65                 | 79923                | 1110384000        | 585.75                 | 42948                | 
| 1110470400     | 1440.22             | 35575             | 1110470400   | 835.3             | 46889           | 1110470400     | 1130.1              | 19622             | 1110556800        | 1150.21                | 97064                | 1110470400    | 1276.06            | 136535           | 1110470400        | 586.65                 | 79923                | 1110470400        | 585.53                 | 42729                | 
```