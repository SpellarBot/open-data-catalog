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
| Rows Updated | 2017-02-02T21:21:24Z |

## Description

Location of wifi hotspots in the city with basic descriptive information.

## Columns

```ls
| Included | Schema Type    | Field Name | Name       | Data Type     | Render Type   |
| ======== | ============== | ========== | ========== | ============= | ============= |
| Yes      | series tag     | objectid   | OBJECTID   | text          | number        |
| Yes      | series tag     | boro       | Boro       | text          | text          |
| Yes      | series tag     | type       | Type       | text          | text          |
| Yes      | series tag     | provider   | Provider   | text          | text          |
| Yes      | series tag     | name       | Name       | text          | text          |
| Yes      | series tag     | location   | Location   | text          | text          |
| Yes      | numeric metric | lat        | Lat        | number        | number        |
| Yes      | numeric metric | long_      | Long_      | number        | number        |
| No       |                | x          | X          | number        | number        |
| No       |                | y          | Y          | number        | number        |
| Yes      | series tag     | location_t | Location_T | text          | text          |
| Yes      | series tag     | remarks    | Remarks    | text          | text          |
| Yes      | series tag     | city       | City       | text          | text          |
| Yes      | series tag     | ssid       | SSID       | text          | text          |
| Yes      | series tag     | sourceid   | SourceID   | text          | text          |
| Yes      | time           | activated  | Activated  | calendar_date | calendar_date |
```

## Time Field

```ls
Value = activated
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = y,x
```

## Data Commands

```ls
series e:yjub-udmw d:2017-03-11T20:45:00.653Z t:boro=QU t:location_t="Outdoor TWC Aerial" t:location="155th St between 29th Ave and 32nd Ave" t:name="Bowne Park" t:sourceid=0 t:ssid=GuestWiFi t:provider="Time Warner Cable" t:remarks="3 free 10 min sessions" t:objectid=848 t:type="Limited Free" t:city=Queens m:long_=-73.80905 m:lat=40.77123

series e:yjub-udmw d:2017-03-11T20:45:00.653Z t:boro=QU t:location_t="Outdoor TWC Aerial" t:location="32nd Ave between 155th and 156th St" t:name="Bowne Park" t:sourceid=0 t:ssid=GuestWiFi t:provider="Time Warner Cable" t:remarks="3 free 10 min sessions" t:objectid=849 t:type="Limited Free" t:city=Queens m:long_=-73.80875 m:lat=40.76975

series e:yjub-udmw d:2017-03-11T20:45:00.653Z t:boro=QU t:location_t="Outdoor TWC Aerial" t:location="32nd Ave between 155th and 156th St" t:name="Bowne Park" t:sourceid=0 t:ssid=GuestWiFi t:provider="Time Warner Cable" t:remarks="3 free 10 min sessions" t:objectid=850 t:type="Limited Free" t:city=Queens m:long_=-73.80751 m:lat=40.76965
```

## Meta Commands

```ls
metric m:lat l:Lat d:"Latitude: Points that fall North or South of the Equator, expressed in degrees." t:dataTypeName=number

metric m:long_ l:Long_ d:"Longitude: Points that fall East or West of the Prime Meridian, expressed in degrees." t:dataTypeName=number

entity e:yjub-udmw l:"NYC Wi-Fi Hotspot Locations" t:attribution="Department of Information Technology & Telecommunications (DoITT)" t:url=https://data.cityofnewyork.us/api/views/yjub-udmw

property e:yjub-udmw t:meta.view v:id=yjub-udmw v:category="City Government" v:averageRating=0 v:name="NYC Wi-Fi Hotspot Locations" v:attribution="Department of Information Technology & Telecommunications (DoITT)"

property e:yjub-udmw t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"

property e:yjub-udmw t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"
```