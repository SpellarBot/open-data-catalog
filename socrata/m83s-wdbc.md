# 2014 Short Duration Automated Bike Counts

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2014-short-duration-automated-bike-counts) |
| Metadata | [Link](https://data.seattle.gov/api/views/m83s-wdbc) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/m83s-wdbc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/m83s-wdbc/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | m83s-wdbc |
| Name | 2014 Short Duration Automated Bike Counts |
| Attribution | Seattle Department of Transportation |
| Category | Transportation |
| Tags | seattle, bike, counts, sdot, bicycle |
| Created | 2016-04-25T21:52:01Z |
| Publication Date | 2016-04-25T22:09:23Z |

## Description

SDOT used Eco-Counter automated pneumatic tube counters to count cyclist volumes across the city. Most counts are for six days, but some may be longer or shorter. This is the raw data from counts conducted during 2014.

Counts are for both directions (when a street is not one way) unless specified in the Location Field.
SB = Southbound
NB = Northbound
EB = Eastbound
WB = Westbound

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type     | Render Type   |
| ======== | ============== | ================ | ================ | ============= | ============= |
| Yes      | numeric metric | compkey          | CompKey          | number        | number        |
| Yes      | series tag     | location         | LOCATION         | text          | text          |
| Yes      | time           | full_count_start | Full Count Start | calendar_date | calendar_date |
| No       |                | full_count_end   | Full Count End   | calendar_date | calendar_date |
| Yes      | series tag     | notes            | Notes            | text          | text          |
| Yes      | numeric metric | day_1            | Day 1            | number        | number        |
| Yes      | numeric metric | day_2            | Day 2            | number        | number        |
| Yes      | numeric metric | day_3            | Day 3            | number        | number        |
| Yes      | numeric metric | day_4            | Day 4            | number        | number        |
| Yes      | numeric metric | day_5            | Day 5            | number        | number        |
| Yes      | numeric metric | day_6            | Day 6            | number        | number        |
| Yes      | numeric metric | day_7            | Day 7            | number        | number        |
| Yes      | numeric metric | day_8            | Day 8            | number        | number        |
| Yes      | numeric metric | day_9            | Day 9            | number        | number        |
| Yes      | numeric metric | day_10           | Day 10           | number        | number        |
| Yes      | numeric metric | day_11           | Day 11           | number        | number        |
| Yes      | numeric metric | day_12           | Day 12           | number        | number        |
| Yes      | numeric metric | day_13           | Day 13           | number        | number        |
| Yes      | numeric metric | day_14           | Day 14           | number        | number        |
| Yes      | numeric metric | day_15           | Day 15           | number        | number        |
| Yes      | numeric metric | day_16           | Day 16           | number        | number        |
| Yes      | numeric metric | day_17           | Day 17           | number        | number        |
| Yes      | numeric metric | day_18           | Day 18           | number        | number        |
| Yes      | numeric metric | day_19           | Day 19           | number        | number        |
| Yes      | numeric metric | day_20           | Day 20           | number        | number        |
| Yes      | numeric metric | day_21           | Day 21           | number        | number        |
| Yes      | numeric metric | day_22           | Day 22           | number        | number        |
| Yes      | numeric metric | day_23           | Day 23           | number        | number        |
| Yes      | numeric metric | day_24           | Day 24           | number        | number        |
| Yes      | numeric metric | day_25           | Day 25           | number        | number        |
| Yes      | numeric metric | day_26           | Day 26           | number        | number        |
| Yes      | numeric metric | day_27           | Day 27           | number        | number        |
| Yes      | numeric metric | day_28           | Day 28           | number        | number        |
| Yes      | numeric metric | day_29           | Day 29           | number        | number        |
| Yes      | numeric metric | day_30           | Day 30           | number        | number        |
```

## Time Field

```ls
Value = full_count_start
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = full_count_end
```

## Data Commands

```ls
series e:m83s-wdbc d:2014-10-25T00:00:00.000Z t:location="12th Ave NE n/o NE 50th St" t:notes="Hose up after Nov 14" m:compkey=1570 m:day_1=64 m:day_2=59 m:day_4=120 m:day_14=108 m:day_15=79 m:day_3=114 m:day_20=136 m:day_12=111 m:day_6=124 m:day_13=123 m:day_5=117 m:day_8=94 m:day_10=101 m:day_7=112 m:day_11=108 m:day_9=67 m:day_18=105 m:day_19=116 m:day_16=43 m:day_17=123

series e:m83s-wdbc d:2014-12-16T00:00:00.000Z t:location="12th Ave S s/o S Weller St NB" m:compkey=626835 m:day_1=113 m:day_2=101 m:day_4=72 m:day_14=84 m:day_3=80 m:day_15=74 m:day_12=35 m:day_6=42 m:day_13=30 m:day_5=43 m:day_8=50 m:day_10=27 m:day_7=91 m:day_11=43 m:day_9=43

series e:m83s-wdbc d:2014-07-02T00:00:00.000Z t:location="17th Ave NW n/o nw 53rd" m:day_4=100 m:day_3=115 m:day_6=242 m:day_5=140 m:day_8=295 m:day_7=307 m:compkey=2437 m:day_1=281 m:day_2=199
```

## Meta Commands

```ls
metric m:compkey p:integer l:CompKey t:dataTypeName=number

metric m:day_1 p:integer l:"Day 1" t:dataTypeName=number

metric m:day_2 p:integer l:"Day 2" t:dataTypeName=number

metric m:day_3 p:integer l:"Day 3" t:dataTypeName=number

metric m:day_4 p:integer l:"Day 4" t:dataTypeName=number

metric m:day_5 p:integer l:"Day 5" t:dataTypeName=number

metric m:day_6 p:integer l:"Day 6" t:dataTypeName=number

metric m:day_7 p:integer l:"Day 7" t:dataTypeName=number

metric m:day_8 p:integer l:"Day 8" t:dataTypeName=number

metric m:day_9 p:integer l:"Day 9" t:dataTypeName=number

metric m:day_10 p:integer l:"Day 10" t:dataTypeName=number

metric m:day_11 p:integer l:"Day 11" t:dataTypeName=number

metric m:day_12 p:integer l:"Day 12" t:dataTypeName=number

metric m:day_13 p:integer l:"Day 13" t:dataTypeName=number

metric m:day_14 p:integer l:"Day 14" t:dataTypeName=number

metric m:day_15 p:integer l:"Day 15" t:dataTypeName=number

metric m:day_16 p:integer l:"Day 16" t:dataTypeName=number

metric m:day_17 p:integer l:"Day 17" t:dataTypeName=number

metric m:day_18 p:integer l:"Day 18" t:dataTypeName=number

metric m:day_19 p:integer l:"Day 19" t:dataTypeName=number

metric m:day_20 p:integer l:"Day 20" t:dataTypeName=number

metric m:day_21 p:integer l:"Day 21" t:dataTypeName=number

metric m:day_22 p:integer l:"Day 22" t:dataTypeName=number

metric m:day_23 p:integer l:"Day 23" t:dataTypeName=number

metric m:day_24 p:integer l:"Day 24" t:dataTypeName=number

metric m:day_25 p:integer l:"Day 25" t:dataTypeName=number

metric m:day_26 p:integer l:"Day 26" t:dataTypeName=number

metric m:day_27 p:integer l:"Day 27" t:dataTypeName=number

metric m:day_28 p:integer l:"Day 28" t:dataTypeName=number

metric m:day_29 p:integer l:"Day 29" t:dataTypeName=number

metric m:day_30 p:integer l:"Day 30" t:dataTypeName=number

entity e:m83s-wdbc l:"2014 Short Duration Automated Bike Counts" t:attribution="Seattle Department of Transportation" t:url=https://data.seattle.gov/api/views/m83s-wdbc

property e:m83s-wdbc t:meta.view v:id=m83s-wdbc v:category=Transportation v:averageRating=0 v:name="2014 Short Duration Automated Bike Counts" v:attribution="Seattle Department of Transportation"

property e:m83s-wdbc t:meta.view.license v:name="Public Domain"

property e:m83s-wdbc t:meta.view.owner v:id=pf4e-vhvy v:screenName="Conor, Jeffrey" v:displayName="Conor, Jeffrey"

property e:m83s-wdbc t:meta.view.tableauthor v:id=pf4e-vhvy v:screenName="Conor, Jeffrey" v:roleName=publisher v:displayName="Conor, Jeffrey"
```

## Top Records

```ls
| compkey | location                      | full_count_start    | full_count_end      | notes                             | day_1 | day_2 | day_3 | day_4 | day_5 | day_6 | day_7 | day_8 | day_9 | day_10 | day_11 | day_12 | day_13 | day_14 | day_15 | day_16 | day_17 | day_18 | day_19 | day_20 | day_21 | day_22 | day_23 | day_24 | day_25 | day_26 | day_27 | day_28 | day_29 | day_30 | 
| ======= | ============================= | =================== | =================== | ================================= | ===== | ===== | ===== | ===== | ===== | ===== | ===== | ===== | ===== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | 
| 1570    | 12th Ave NE n/o NE 50th St    | 2014-10-25T00:00:00 | 2014-11-20T00:00:00 | Hose up after Nov 14              | 64    | 59    | 114   | 120   | 117   | 124   | 112   | 94    | 67    | 101    | 108    | 111    | 123    | 108    | 79     | 43     | 123    | 105    | 116    | 136    |        |        |        |        |        |        |        |        |        |        | 
| 626835  | 12th Ave S s/o S Weller St NB | 2014-12-16T00:00:00 | 2014-12-30T00:00:00 |                                   | 113   | 101   | 80    | 72    | 43    | 42    | 91    | 50    | 43    | 27     | 43     | 35     | 30     | 84     | 74     |        |        |        |        |        |        |        |        |        |        |        |        |        |        |        | 
| 2437    | 17th Ave NW n/o nw 53rd       | 2014-07-02T00:00:00 | 2014-07-09T00:00:00 |                                   | 281   | 199   | 115   | 100   | 140   | 242   | 307   | 295   |       |        |        |        |        |        |        |        |        |        |        |        |        |        |        |        |        |        |        |        |        |        | 
| 2443    | 17th Ave NW n/o nw 58th       | 2014-07-02T00:00:00 | 2014-07-09T00:00:00 |                                   | 232   | 186   | 100   | 93    | 135   | 197   | 233   | 228   |       |        |        |        |        |        |        |        |        |        |        |        |        |        |        |        |        |        |        |        |        |        | 
| 2509    | 17th Ave SW n/o SW Henderson  | 2014-10-25T00:00:00 | 2014-11-13T00:00:00 |                                   | 1     | 2     | 4     | 1     | 3     | 5     | 5     | 3     | 4     | 3      | 2      | 6      | 2      | 6      | 7      | 0      | 2      | 5      | 6      | 2      |        |        |        |        |        |        |        |        |        |        | 
| 2604    | 18th Ave S n/o S Bayview St   | 2014-08-08T00:00:00 | 2014-08-13T00:00:00 |                                   | 53    | 34    | 40    | 57    | 72    | 47    |       |       |       |        |        |        |        |        |        |        |        |        |        |        |        |        |        |        |        |        |        |        |        |        | 
| 3855    | 26th Ave E n/o Boyer Ave E    | 2014-10-11T00:00:00 | 2014-11-13T00:00:00 |                                   | 141   | 198   | 297   | 266   | 206   | 348   | 190   | 133   | 306   | 240    | 251    | 162    | 180    | 228    | 80     | 108    | 237    | 167    | 249    | 178    | 124    | 190    | 109    | 195    | 238    | 204    | 211    | 281    | 238    | 70     | 
| 4037    | 27th Ave NE n/o n130th St     | 2014-07-19T00:00:00 | 2014-07-24T00:00:00 |                                   | 35    | 15    | 70    | 67    | 38    | 52    |       |       |       |        |        |        |        |        |        |        |        |        |        |        |        |        |        |        |        |        |        |        |        |        | 
| 2768    | 2nd Ave and Cedar             | 2014-07-19T00:00:00 | 2014-07-24T00:00:00 |                                   | 48    | 39    | 126   | 120   | 63    | 85    |       |       |       |        |        |        |        |        |        |        |        |        |        |        |        |        |        |        |        |        |        |        |        |        | 
| 2752    | 2nd Ave bike lane             | 2014-07-29T00:00:00 | 2014-08-03T00:00:00 | Replaced by a PBL in Sept of 2014 | 413   | 446   | 379   | 386   | 120   | 113   |       |       |       |        |        |        |        |        |        |        |        |        |        |        |        |        |        |        |        |        |        |        |        |        | 
```