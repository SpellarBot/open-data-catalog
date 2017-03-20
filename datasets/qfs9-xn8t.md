# NYCDCP Manhattan Bike Counts - On Street Weekday

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nycdcp-manhattan-bike-counts-on-street-weekday) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/qfs9-xn8t) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/qfs9-xn8t/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/qfs9-xn8t/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | qfs9-xn8t |
| Name | NYCDCP Manhattan Bike Counts - On Street Weekday |
| Attribution | Department of City Planning (DCP) |
| Category | Transportation |
| Created | 2016-09-12T20:51:49Z |
| Publication Date | 2016-09-12T21:23:22Z |
| Rows Updated | 2016-09-12T20:52:01Z |

## Description

The Transportation Division of the New York City Department of City Planning (NYCDCP) has performed annual bike counts in Manhattan since 1999. The counts have been conducted along designated bicycle routes at 10 on-street and 5 off-street locations during the fall season. These locations have remained generally consistent. The data collected includes cyclist/user volumes, helmet usage, use of bike lane, gender, etc. The bike counts data can offer insights into the overall trends in user demographics and travel patterns over time.

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type | Render Type |
| ======== | ============== | ===================== | ===================== | ========= | =========== |
| Yes      | series tag     | locationid            | LocationID            | text      | number      |
| Yes      | series tag     | locationtype          | LocationType          | text      | text        |
| No       |                | typeoftime            | TypeOfTime            | text      | text        |
| Yes      | series tag     | location              | Location              | text      | text        |
| No       |                | location_lat          | Location_Lat          | number    | number      |
| No       |                | location_long         | Location_Long         | number    | number      |
| Yes      | time           | year                  | Year                  | number    | number      |
| Yes      | numeric metric | totalusers            | TotalUsers            | number    | number      |
| Yes      | numeric metric | noncyc_otheruser      | NonCyc_OtherUser      | number    | number      |
| Yes      | numeric metric | cyclistvolume         | CyclistVolume         | number    | number      |
| Yes      | numeric metric | cycbikelane           | CycBikeLane           | number    | number      |
| Yes      | numeric metric | cycadjacentlane       | CycAdjacentLane       | number    | number      |
| Yes      | numeric metric | cyclotherlane         | CyclOtherLane         | number    | number      |
| Yes      | numeric metric | cyccounterflowinlane  | CycCounterFlowInLane  | number    | number      |
| Yes      | numeric metric | cycsidewalk           | CycSidewalk           | number    | number      |
| Yes      | numeric metric | cyccnterflowoutoflane | CycCnterFlowOutOfLane | number    | number      |
| Yes      | numeric metric | femalecyc_total       | FemaleCyc_Total       | number    | number      |
| Yes      | numeric metric | malecyc_total         | MaleCyc_Total         | number    | number      |
| Yes      | numeric metric | female_cyc_helmet     | Female_Cyc_Helmet     | number    | number      |
| Yes      | numeric metric | male_cyc_helmet       | Male_Cyc_Helmet       | number    | number      |
| Yes      | numeric metric | cycl_helmet_all       | Cycl_Helmet_all       | number    | number      |
| Yes      | numeric metric | cyc_under16           | Cyc_Under16           | number    | number      |
| Yes      | numeric metric | citibike_male         | Citibike_Male         | number    | number      |
| Yes      | numeric metric | citibike_female       | Citibike_female       | number    | number      |
| Yes      | numeric metric | citibike_all          | Citibike_All          | number    | number      |
| Yes      | numeric metric | non_citibikecyc       | Non_citibikeCyc       | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = location_lat,location_long,typeoftime
```

## Data Commands

```ls
series e:qfs9-xn8t d:2005-01-01T00:00:00.000Z t:locationid=1 t:location="Second Avenue at E7 St." t:locationtype=On-Street m:citibike_all=0 m:non_citibikecyc=1027 m:cycadjacentlane=15 m:noncyc_otheruser=34 m:cycsidewalk=51 m:cyclistvolume=1027 m:malecyc_total=834 m:citibike_male=0 m:male_cyc_helmet=154 m:cyc_under16=36 m:cyccnterflowoutoflane=29 m:cyccounterflowinlane=99 m:cyclotherlane=247 m:cycbikelane=586 m:female_cyc_helmet=42 m:totalusers=1061 m:femalecyc_total=193 m:cycl_helmet_all=196 m:citibike_female=0

series e:qfs9-xn8t d:2006-01-01T00:00:00.000Z t:locationid=1 t:location="Second Avenue at E7 St." t:locationtype=On-Street m:citibike_all=0 m:non_citibikecyc=1101 m:cycadjacentlane=26 m:noncyc_otheruser=25 m:cycsidewalk=45 m:cyclistvolume=1101 m:malecyc_total=868 m:citibike_male=0 m:male_cyc_helmet=207 m:cyc_under16=27 m:cyccnterflowoutoflane=37 m:cyccounterflowinlane=94 m:cyclotherlane=207 m:cycbikelane=692 m:female_cyc_helmet=94 m:totalusers=1126 m:femalecyc_total=233 m:cycl_helmet_all=301 m:citibike_female=0

series e:qfs9-xn8t d:2007-01-01T00:00:00.000Z t:locationid=1 t:location="Second Avenue at E7 St." t:locationtype=On-Street m:citibike_all=0 m:non_citibikecyc=1109 m:cycadjacentlane=34 m:noncyc_otheruser=42 m:cycsidewalk=37 m:cyclistvolume=1109 m:malecyc_total=844 m:citibike_male=0 m:male_cyc_helmet=263 m:cyc_under16=37 m:cyccnterflowoutoflane=23 m:cyccounterflowinlane=84 m:cyclotherlane=205 m:cycbikelane=726 m:female_cyc_helmet=102 m:totalusers=1150 m:femalecyc_total=265 m:cycl_helmet_all=365 m:citibike_female=0
```

## Meta Commands

```ls
metric m:totalusers p:integer l:TotalUsers t:dataTypeName=number

metric m:noncyc_otheruser p:integer l:NonCyc_OtherUser t:dataTypeName=number

metric m:cyclistvolume p:integer l:CyclistVolume t:dataTypeName=number

metric m:cycbikelane p:integer l:CycBikeLane t:dataTypeName=number

metric m:cycadjacentlane p:integer l:CycAdjacentLane t:dataTypeName=number

metric m:cyclotherlane p:integer l:CyclOtherLane t:dataTypeName=number

metric m:cyccounterflowinlane p:integer l:CycCounterFlowInLane t:dataTypeName=number

metric m:cycsidewalk p:integer l:CycSidewalk t:dataTypeName=number

metric m:cyccnterflowoutoflane p:integer l:CycCnterFlowOutOfLane t:dataTypeName=number

metric m:femalecyc_total p:integer l:FemaleCyc_Total t:dataTypeName=number

metric m:malecyc_total p:integer l:MaleCyc_Total t:dataTypeName=number

metric m:female_cyc_helmet p:integer l:Female_Cyc_Helmet t:dataTypeName=number

metric m:male_cyc_helmet p:integer l:Male_Cyc_Helmet t:dataTypeName=number

metric m:cycl_helmet_all p:integer l:Cycl_Helmet_all t:dataTypeName=number

metric m:cyc_under16 p:integer l:Cyc_Under16 t:dataTypeName=number

metric m:citibike_male p:integer l:Citibike_Male t:dataTypeName=number

metric m:citibike_female p:integer l:Citibike_female t:dataTypeName=number

metric m:citibike_all p:integer l:Citibike_All t:dataTypeName=number

metric m:non_citibikecyc p:integer l:Non_citibikeCyc t:dataTypeName=number

entity e:qfs9-xn8t l:"NYCDCP Manhattan Bike Counts - On Street Weekday" t:attribution="Department of City Planning (DCP)" t:url=https://data.cityofnewyork.us/api/views/qfs9-xn8t

property e:qfs9-xn8t t:meta.view v:id=qfs9-xn8t v:category=Transportation v:averageRating=0 v:name="NYCDCP Manhattan Bike Counts - On Street Weekday" v:attribution="Department of City Planning (DCP)"

property e:qfs9-xn8t t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"

property e:qfs9-xn8t t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"
```