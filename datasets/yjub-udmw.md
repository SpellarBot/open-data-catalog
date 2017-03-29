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
| Publication Date | 2017-02-02T21:21:46Z |

## Description

Location of wifi hotspots in the city with basic descriptive information.

## Columns

```ls
| Included | Schema Type | Field Name | Name       | Data Type     | Render Type   |
| ======== | =========== | ========== | ========== | ============= | ============= |
| Yes      | series tag  | objectid   | OBJECTID   | text          | number        |
| Yes      | series tag  | boro       | Boro       | text          | text          |
| Yes      | series tag  | type       | Type       | text          | text          |
| Yes      | series tag  | provider   | Provider   | text          | text          |
| Yes      | series tag  | name       | Name       | text          | text          |
| Yes      | series tag  | location   | Location   | text          | text          |
| No       |             | lat        | Lat        | number        | number        |
| No       |             | long_      | Long_      | number        | number        |
| No       |             | x          | X          | number        | number        |
| No       |             | y          | Y          | number        | number        |
| Yes      | series tag  | location_t | Location_T | text          | text          |
| Yes      | series tag  | remarks    | Remarks    | text          | text          |
| Yes      | series tag  | city       | City       | text          | text          |
| Yes      | series tag  | ssid       | SSID       | text          | text          |
| Yes      | series tag  | sourceid   | SourceID   | text          | text          |
| Yes      | time        | activated  | Activated  | calendar_date | calendar_date |
```

## Time Field

```ls
Value = activated
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = lat,long_,x,y
```

## Data Commands

```ls
series e:yjub-udmw d:2017-02-02T21:21:11.000Z t:boro=QU t:location_t="Outdoor TWC Aerial" t:location="155th St between 29th Ave and 32nd Ave" t:name="Bowne Park" t:sourceid=0 t:ssid=GuestWiFi t:provider="Time Warner Cable" t:remarks="3 free 10 min sessions" t:objectid=848 t:type="Limited Free" t:city=Queens m:row_number.yjub-udmw=1

series e:yjub-udmw d:2017-02-02T21:21:11.000Z t:boro=QU t:location_t="Outdoor TWC Aerial" t:location="32nd Ave between 155th and 156th St" t:name="Bowne Park" t:sourceid=0 t:ssid=GuestWiFi t:provider="Time Warner Cable" t:remarks="3 free 10 min sessions" t:objectid=849 t:type="Limited Free" t:city=Queens m:row_number.yjub-udmw=2

series e:yjub-udmw d:2017-02-02T21:21:11.000Z t:boro=QU t:location_t="Outdoor TWC Aerial" t:location="32nd Ave between 155th and 156th St" t:name="Bowne Park" t:sourceid=0 t:ssid=GuestWiFi t:provider="Time Warner Cable" t:remarks="3 free 10 min sessions" t:objectid=850 t:type="Limited Free" t:city=Queens m:row_number.yjub-udmw=3
```

## Meta Commands

```ls
metric m:row_number.yjub-udmw p:long l:"Row Number"

entity e:yjub-udmw l:"NYC Wi-Fi Hotspot Locations" t:attribution="Department of Information Technology & Telecommunications (DoITT)" t:url=https://data.cityofnewyork.us/api/views/yjub-udmw

property e:yjub-udmw t:meta.view v:id=yjub-udmw v:category="City Government" v:averageRating=0 v:name="NYC Wi-Fi Hotspot Locations" v:attribution="Department of Information Technology & Telecommunications (DoITT)"

property e:yjub-udmw t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:displayName="NYC OpenData"

property e:yjub-udmw t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"
```

## Top Records

```ls
| objectid | boro | type         | provider          | name                       | location                                                                          | lat            | long_           | x                   | y                  | location_t         | remarks                | city     | ssid      | sourceid | activated | 
| ======== | ==== | ============ | ================= | ========================== | ================================================================================= | ============== | =============== | =================== | ================== | ================== | ====================== | ======== | ========= | ======== | ========= | 
| 848      | QU   | Limited Free | Time Warner Cable | Bowne Park                 | 155th St between 29th Ave and 32nd Ave                                            | 40.77122900000 | -73.80905000000 | 1037140.16258000000 | 220313.95377900000 | Outdoor TWC Aerial | 3 free 10 min sessions | Queens   | GuestWiFi | 0        |           | 
| 849      | QU   | Limited Free | Time Warner Cable | Bowne Park                 | 32nd Ave between 155th and 156th St                                               | 40.76975100000 | -73.80874800000 | 1037224.98754000000 | 219775.65301800000 | Outdoor TWC Aerial | 3 free 10 min sessions | Queens   | GuestWiFi | 0        |           | 
| 850      | QU   | Limited Free | Time Warner Cable | Bowne Park                 | 32nd Ave between 155th and 156th St                                               | 40.76965200000 | -73.80750800000 | 1037568.53443000000 | 219740.33648800000 | Outdoor TWC Aerial | 3 free 10 min sessions | Queens   | GuestWiFi | 0        |           | 
| 851      | QU   | Limited Free | Time Warner Cable | Bowne Park                 | 32nd Ave between 155th and 156th St                                               | 40.76953600000 | -73.80596800000 | 1037995.19335000000 | 219699.01504800000 | Outdoor TWC Aerial | 3 free 10 min sessions | Queens   | GuestWiFi | 0        |           | 
| 852      | QU   | Limited Free | Time Warner Cable | Bowne Park                 | 159th St between 29th Ave and 32nd Ave                                            | 40.77053200000 | -73.80550700000 | 1038122.08056000000 | 220062.17311400000 | Outdoor TWC Aerial | 3 free 10 min sessions | Queens   | GuestWiFi | 0        |           | 
| 853      | MN   | Limited Free | Time Warner Cable | Bryant Park                | Back of library - Corner of 6th Ave by Jose Bonifacio de Andrada e Silva Monument | 40.75444700000 | -73.98422200000 | 988621.36394900000  | 214142.46612200000 | Outdoor            | 3 free 10 min sessions | New York | GuestWiFi | 0        |           | 
| 854      | BK   | Free         | AT&T              | Brooklyn Heights Promenade | Near Montague St and Brooklyn Queens Expressway                                   | 40.69430000000 | -73.99880000000 | 984582.76539900000  | 192228.66250900000 | Outdoor            |                        | Brooklyn | attwifi   |          |           | 
| 855      | MN   | Limited Free | Time Warner Cable | Bryant Park                | Back of library - 2nd St between 5th Ave and 6th Ave                              | 40.75431700000 | -73.98309400000 | 988933.89022700000  | 214095.16142600000 | Outdoor            | 3 free 10 min sessions | New York | GuestWiFi | 0        |           | 
| 856      | MN   | Limited Free | Time Warner Cable | Bryant Park                | Back of library - 40th St between 5th Ave and 6th Ave                             | 40.75316400000 | -73.98396400000 | 988692.92942200000  | 213675.04054700000 | Outdoor            | 3 free 10 min sessions | New York | GuestWiFi | 0        |           | 
| 857      | MN   | Limited Free | Time Warner Cable | Bryant Park                | Back of library - Corner of 6th Ave by 40th St                                    | 40.75368900000 | -73.98476900000 | 988469.86326800000  | 213866.27540100000 | Outdoor            | 3 free 10 min sessions | New York | GuestWiFi | 0        |           | 
```