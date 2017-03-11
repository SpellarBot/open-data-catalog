# NYCDCP Manhattan Bike Counts - On Street Weekday

## Dataset

* [Dataset URL](https://data.cityofnewyork.us/api/views/qfs9-xn8t/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/nycdcp-manhattan-bike-counts-on-street-weekday)
* [Metadata URL](https://data.cityofnewyork.us/api/views/qfs9-xn8t)
* Id = qfs9-xn8t
* Name = NYCDCP Manhattan Bike Counts - On Street Weekday
* Attribution = Department of City Planning (DCP)
* Category = Transportation
* Created = 2016-09-12T20:51:49Z
* Publication Date = 2016-09-12T21:23:22Z
* Rows Updated = 2016-09-12T20:52:01Z

## Description

The Transportation Division of the New York City Department of City Planning (NYCDCP) has performed annual bike counts in Manhattan since 1999. The counts have been conducted along designated bicycle routes at 10 on-street and 5 off-street locations during the fall season. These locations have remained generally consistent. The data collected includes cyclist/user volumes, helmet usage, use of bike lane, gender, etc. The bike counts data can offer insights into the overall trends in user demographics and travel patterns over time.

## Columns

```ls
| Name                  | Field Name            | Data Type | Render Type | Schema Type    | Included | 
| ===================== | ===================== | ========= | =========== | ============== | ======== | 
| LocationID            | locationid            | text      | number      | series tag     | Yes      | 
| LocationType          | locationtype          | text      | text        | series tag     | Yes      | 
| TypeOfTime            | typeoftime            | text      | text        | series tag     | Yes      | 
| Location              | location              | text      | text        | series tag     | Yes      | 
| Location_Lat          | location_lat          | number    | number      |                | No       | 
| Location_Long         | location_long         | number    | number      |                | No       | 
| Year                  | year                  | number    | number      | time           | Yes      | 
| TotalUsers            | totalusers            | number    | number      | numeric metric | Yes      | 
| NonCyc_OtherUser      | noncyc_otheruser      | number    | number      | numeric metric | Yes      | 
| CyclistVolume         | cyclistvolume         | number    | number      | numeric metric | Yes      | 
| CycBikeLane           | cycbikelane           | number    | number      | numeric metric | Yes      | 
| CycAdjacentLane       | cycadjacentlane       | number    | number      | numeric metric | Yes      | 
| CyclOtherLane         | cyclotherlane         | number    | number      | numeric metric | Yes      | 
| CycCounterFlowInLane  | cyccounterflowinlane  | number    | number      | numeric metric | Yes      | 
| CycSidewalk           | cycsidewalk           | number    | number      | numeric metric | Yes      | 
| CycCnterFlowOutOfLane | cyccnterflowoutoflane | number    | number      | numeric metric | Yes      | 
| FemaleCyc_Total       | femalecyc_total       | number    | number      | numeric metric | Yes      | 
| MaleCyc_Total         | malecyc_total         | number    | number      | numeric metric | Yes      | 
| Female_Cyc_Helmet     | female_cyc_helmet     | number    | number      | numeric metric | Yes      | 
| Male_Cyc_Helmet       | male_cyc_helmet       | number    | number      | numeric metric | Yes      | 
| Cycl_Helmet_all       | cycl_helmet_all       | number    | number      | numeric metric | Yes      | 
| Cyc_Under16           | cyc_under16           | number    | number      | numeric metric | Yes      | 
| Citibike_Male         | citibike_male         | number    | number      | numeric metric | Yes      | 
| Citibike_female       | citibike_female       | number    | number      | numeric metric | Yes      | 
| Citibike_All          | citibike_all          | number    | number      | numeric metric | Yes      | 
| Non_citibikeCyc       | non_citibikecyc       | number    | number      | numeric metric | Yes      | 
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = location_lat,location_long
Annotation Fields = 
```

## Data Commands

```ls
series e:qfs9-xn8t d:2005-01-01T00:00:00.000Z t:locationid=1 t:typeoftime=Weekday t:location="Second Avenue at E7 St." t:locationtype=On-Street m:citibike_all=0 m:non_citibikecyc=1027 m:cycadjacentlane=15 m:noncyc_otheruser=34 m:cycsidewalk=51 m:cyclistvolume=1027 m:malecyc_total=834 m:citibike_male=0 m:male_cyc_helmet=154 m:cyc_under16=36 m:cyccnterflowoutoflane=29 m:cyccounterflowinlane=99 m:cyclotherlane=247 m:cycbikelane=586 m:female_cyc_helmet=42 m:totalusers=1061 m:femalecyc_total=193 m:cycl_helmet_all=196 m:citibike_female=0

series e:qfs9-xn8t d:2006-01-01T00:00:00.000Z t:locationid=1 t:typeoftime=Weekday t:location="Second Avenue at E7 St." t:locationtype=On-Street m:citibike_all=0 m:non_citibikecyc=1101 m:cycadjacentlane=26 m:noncyc_otheruser=25 m:cycsidewalk=45 m:cyclistvolume=1101 m:malecyc_total=868 m:citibike_male=0 m:male_cyc_helmet=207 m:cyc_under16=27 m:cyccnterflowoutoflane=37 m:cyccounterflowinlane=94 m:cyclotherlane=207 m:cycbikelane=692 m:female_cyc_helmet=94 m:totalusers=1126 m:femalecyc_total=233 m:cycl_helmet_all=301 m:citibike_female=0

series e:qfs9-xn8t d:2007-01-01T00:00:00.000Z t:locationid=1 t:typeoftime=Weekday t:location="Second Avenue at E7 St." t:locationtype=On-Street m:citibike_all=0 m:non_citibikecyc=1109 m:cycadjacentlane=34 m:noncyc_otheruser=42 m:cycsidewalk=37 m:cyclistvolume=1109 m:malecyc_total=844 m:citibike_male=0 m:male_cyc_helmet=263 m:cyc_under16=37 m:cyccnterflowoutoflane=23 m:cyccounterflowinlane=84 m:cyclotherlane=205 m:cycbikelane=726 m:female_cyc_helmet=102 m:totalusers=1150 m:femalecyc_total=265 m:cycl_helmet_all=365 m:citibike_female=0
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

property e:qfs9-xn8t t:meta.view d:2017-03-08T01:53:00.421Z v:id=qfs9-xn8t v:category=Transportation v:averageRating=0 v:name="NYCDCP Manhattan Bike Counts - On Street Weekday" v:attribution="Department of City Planning (DCP)"

property e:qfs9-xn8t t:meta.view.owner d:2017-03-08T01:53:00.421Z v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"

property e:qfs9-xn8t t:meta.view.tableauthor d:2017-03-08T01:53:00.421Z v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"
```