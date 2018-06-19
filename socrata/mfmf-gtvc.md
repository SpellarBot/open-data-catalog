# NYCDCP Manhattan Bike Counts - Off Street

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nycdcp-manhattan-bike-counts-off-street) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/mfmf-gtvc) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/mfmf-gtvc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/mfmf-gtvc/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | mfmf-gtvc |
| Name | NYCDCP Manhattan Bike Counts - Off Street |
| Attribution | Department of City Planning (DCP) |
| Category | Transportation |
| Created | 2016-09-12T20:51:52Z |
| Publication Date | 2016-09-12T21:27:31Z |

## Description

The Transportation Division of the New York City Department of City Planning (NYCDCP) has performed annual bike counts in Manhattan since 1999. The counts have been conducted along designated bicycle routes at 10 on-street and 5 off-street locations during the fall season. These locations have remained generally consistent. The data collected includes cyclist/user volumes, helmet usage, use of bike lane, gender, etc. The bike counts data can offer insights into the overall trends in user demographics and travel patterns over time.

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type | Render Type |
| ======== | ============== | ===================== | ===================== | ========= | =========== |
| Yes      | series tag     | locationid            | LocationID            | text      | number      |
| Yes      | series tag     | locationtype          | LocationType          | text      | text        |
| Yes      | series tag     | typeoftime            | TypeOfTime            | text      | text        |
| Yes      | series tag     | location              | Location              | text      | text        |
| No       |                | location_lat          | Location_Lat          | number    | number      |
| No       |                | location_long         | Location_Long         | number    | number      |
| Yes      | time           | year                  | Year                  | number    | number      |
| Yes      | numeric metric | alluservolume         | AllUserVolume         | number    | number      |
| Yes      | numeric metric | cyclists_all          | Cyclists_all          | number    | number      |
| Yes      | numeric metric | cyc_greenway_only     | Cyc_Greenway_only     | number    | number      |
| Yes      | numeric metric | cyc_helmet_greenwy    | Cyc_Helmet_Greenwy    | number    | number      |
| Yes      | numeric metric | citibike_all          | Citibike_All          | number    | number      |
| Yes      | numeric metric | non_citibikecyc       | Non_citibikeCyc       | number    | number      |
| Yes      | numeric metric | rllrbld_scootr        | RllrBld_Scootr        | number    | number      |
| Yes      | numeric metric | jogger                | Jogger                | number    | number      |
| Yes      | numeric metric | walker                | Walker                | number    | number      |
| Yes      | numeric metric | cycmalehel_greenwy    | CycMaleHel_greenwy    | number    | number      |
| Yes      | numeric metric | cycmale_greenwy       | CycMale_greenwy       | number    | number      |
| Yes      | numeric metric | cycfemalehell_greenwy | CycFemaleHell_greenwy | number    | number      |
| Yes      | numeric metric | cycfemale_greenwy     | CycFemale_greenwy     | number    | number      |
| Yes      | numeric metric | cyclists_male         | Cyclists_Male         | number    | number      |
| Yes      | numeric metric | cyclists_female       | Cyclists_Female       | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = location_lat,location_long
```

## Data Commands

```ls
series e:mfmf-gtvc d:2005-01-01T00:00:00.000Z t:locationid=11 t:typeoftime=Weekday t:location="East River at E Houston St." t:locationtype=Off-Street m:citibike_all=0 m:non_citibikecyc=426 m:cyc_greenway_only=426 m:cyc_helmet_greenwy=133 m:alluservolume=1315 m:rllrbld_scootr=17 m:walker=374 m:cyclists_all=426 m:jogger=498

series e:mfmf-gtvc d:2006-01-01T00:00:00.000Z t:locationid=11 t:typeoftime=Weekday t:location="East River at E Houston St." t:locationtype=Off-Street m:citibike_all=0 m:non_citibikecyc=315 m:cyc_greenway_only=315 m:cyc_helmet_greenwy=117 m:alluservolume=1170 m:rllrbld_scootr=11 m:walker=342 m:cyclists_all=315 m:jogger=502

series e:mfmf-gtvc d:2007-01-01T00:00:00.000Z t:locationid=11 t:typeoftime=Weekday t:location="East River at E Houston St." t:locationtype=Off-Street m:citibike_all=0 m:non_citibikecyc=451 m:cyc_greenway_only=451 m:cyc_helmet_greenwy=185 m:alluservolume=1422 m:rllrbld_scootr=12 m:walker=334 m:cyclists_all=451 m:jogger=629
```

## Meta Commands

```ls
metric m:alluservolume p:integer l:AllUserVolume t:dataTypeName=number

metric m:cyclists_all p:integer l:Cyclists_all t:dataTypeName=number

metric m:cyc_greenway_only p:integer l:Cyc_Greenway_only t:dataTypeName=number

metric m:cyc_helmet_greenwy p:integer l:Cyc_Helmet_Greenwy t:dataTypeName=number

metric m:citibike_all p:integer l:Citibike_All t:dataTypeName=number

metric m:non_citibikecyc p:integer l:Non_citibikeCyc t:dataTypeName=number

metric m:rllrbld_scootr p:integer l:RllrBld_Scootr t:dataTypeName=number

metric m:jogger p:integer l:Jogger t:dataTypeName=number

metric m:walker p:integer l:Walker t:dataTypeName=number

metric m:cycmalehel_greenwy p:integer l:CycMaleHel_greenwy t:dataTypeName=number

metric m:cycmale_greenwy p:integer l:CycMale_greenwy t:dataTypeName=number

metric m:cycfemalehell_greenwy p:integer l:CycFemaleHell_greenwy t:dataTypeName=number

metric m:cycfemale_greenwy p:integer l:CycFemale_greenwy t:dataTypeName=number

metric m:cyclists_male p:integer l:Cyclists_Male t:dataTypeName=number

metric m:cyclists_female p:integer l:Cyclists_Female t:dataTypeName=number

entity e:mfmf-gtvc l:"NYCDCP Manhattan Bike Counts - Off Street" t:attribution="Department of City Planning (DCP)" t:url=https://data.cityofnewyork.us/api/views/mfmf-gtvc

property e:mfmf-gtvc t:meta.view v:id=mfmf-gtvc v:category=Transportation v:averageRating=0 v:name="NYCDCP Manhattan Bike Counts - Off Street" v:attribution="Department of City Planning (DCP)"

property e:mfmf-gtvc t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:mfmf-gtvc t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| locationid | locationtype | typeoftime | location                    | location_lat       | location_long       | year | alluservolume | cyclists_all | cyc_greenway_only | cyc_helmet_greenwy | citibike_all | non_citibikecyc | rllrbld_scootr | jogger | walker | cycmalehel_greenwy | cycmale_greenwy | cycfemalehell_greenwy | cycfemale_greenwy | cyclists_male | cyclists_female | 
| ========== | ============ | ========== | =========================== | ================== | =================== | ==== | ============= | ============ | ================= | ================== | ============ | =============== | ============== | ====== | ====== | ================== | =============== | ===================== | ================= | ============= | =============== | 
| 11         | Off-Street   | Weekday    | East River at E Houston St. | 40.718708999999997 | -73.974100000000007 | 2005 | 1315          | 426          | 426               | 133                | 0            | 426             | 17             | 498    | 374    |                    |                 |                       |                   |               |                 | 
| 11         | Off-Street   | Weekday    | East River at E Houston St. | 40.718708999999997 | -73.974100000000007 | 2006 | 1170          | 315          | 315               | 117                | 0            | 315             | 11             | 502    | 342    |                    |                 |                       |                   |               |                 | 
| 11         | Off-Street   | Weekday    | East River at E Houston St. | 40.718708999999997 | -73.974100000000007 | 2007 | 1422          | 451          | 451               | 185                | 0            | 451             | 12             | 629    | 334    |                    |                 |                       |                   |               |                 | 
| 11         | Off-Street   | Weekday    | East River at E Houston St. | 40.718708999999997 | -73.974100000000007 | 2008 | 1672          | 460          | 460               | 246                | 0            | 460             | 10             | 728    | 474    |                    |                 |                       |                   |               |                 | 
| 11         | Off-Street   | Weekday    | East River at E Houston St. | 40.718708999999997 | -73.974100000000007 | 2009 | 1399          | 715          | 715               | 460                | 0            | 715             | 36             | 412    | 236    |                    |                 |                       |                   |               |                 | 
| 11         | Off-Street   | Weekday    | East River at E Houston St. | 40.718708999999997 | -73.974100000000007 | 2010 | 1153          | 357          | 357               | 204                | 0            | 357             | 10             | 414    | 372    |                    |                 |                       |                   |               |                 | 
| 11         | Off-Street   | Weekday    | East River at E Houston St. | 40.718708999999997 | -73.974100000000007 | 2011 | 2244          | 444          | 215               | 103                | 0            | 444             | 19             | 1065   | 716    |                    |                 |                       |                   |               |                 | 
| 11         | Off-Street   | Weekday    | East River at E Houston St. | 40.718708999999997 | -73.974100000000007 | 2012 | 2704          | 631          | 210               | 85                 | 0            | 631             | 25             | 1356   | 692    | 59                 | 154             | 26                    | 56                | 453           | 178             | 
| 11         | Off-Street   | Weekday    | East River at E Houston St. | 40.718708999999997 | -73.974100000000007 | 2013 | 3148          | 1052         | 557               | 240                | 298          | 754             | 35             | 1395   | 666    | 154                | 400             | 86                    | 157               | 777           | 275             | 
| 11         | Off-Street   | Weekday    | East River at E Houston St. | 40.718708999999997 | -73.974100000000007 | 2014 | 3321          | 920          | 495               | 216                | 266          | 654             | 25             | 1600   | 776    | 156                | 371             | 60                    | 124               | 675           | 245             | 
```