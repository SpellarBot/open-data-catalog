# 2015 Short Duration Automated Bike Counts

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2015-short-duration-automated-bike-counts) |
| Metadata | [Link](https://data.seattle.gov/api/views/jqzt-uqux) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/jqzt-uqux/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/jqzt-uqux/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | jqzt-uqux |
| Name | 2015 Short Duration Automated Bike Counts |
| Attribution | Seattle Department of Transportation |
| Category | Transportation |
| Tags | seattle, bike, counts, sdot, bicycle |
| Created | 2016-04-25T22:15:03Z |
| Publication Date | 2016-04-25T22:22:02Z |

## Description

SDOT used Eco-Counter automated pneumatic tube counters to count cyclist volumes across the city. Most counts are for six days, but some may be longer or shorter. This is the raw data from counts conducted during 2015.

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
| Yes      | series tag     | notes            | NOTES            | text          | text          |
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
series e:jqzt-uqux d:2015-07-03T00:00:00.000Z t:location="12th Ave NE n/o NE 50th st NB" m:day_4=134 m:day_3=60 m:day_6=133 m:day_5=159 m:compkey=1569 m:day_1=86 m:day_2=68

series e:jqzt-uqux d:2015-07-03T00:00:00.000Z t:location="12th Ave NE s/o NE 50th st SB" m:day_4=263 m:day_3=175 m:day_6=333 m:day_5=323 m:compkey=1569 m:day_1=212 m:day_2=190

series e:jqzt-uqux d:2015-05-02T00:00:00.000Z t:location="12th Ave S s/o S Weller St NB" m:compkey=626835 m:day_1=70 m:day_2=85 m:day_4=76 m:day_14=57 m:day_15=20 m:day_3=175 m:day_20=131 m:day_12=35 m:day_6=82 m:day_13=38 m:day_5=59 m:day_8=74 m:day_10=37 m:day_7=47 m:day_11=37 m:day_9=56 m:day_18=84 m:day_19=45 m:day_16=22 m:day_17=59
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

entity e:jqzt-uqux l:"2015 Short Duration Automated Bike Counts" t:attribution="Seattle Department of Transportation" t:url=https://data.seattle.gov/api/views/jqzt-uqux

property e:jqzt-uqux t:meta.view v:id=jqzt-uqux v:category=Transportation v:averageRating=0 v:name="2015 Short Duration Automated Bike Counts" v:attribution="Seattle Department of Transportation"

property e:jqzt-uqux t:meta.view.license v:name="Public Domain"

property e:jqzt-uqux t:meta.view.owner v:id=pf4e-vhvy v:screenName="Conor, Jeffrey" v:displayName="Conor, Jeffrey"

property e:jqzt-uqux t:meta.view.tableauthor v:id=pf4e-vhvy v:screenName="Conor, Jeffrey" v:roleName=publisher v:displayName="Conor, Jeffrey"
```

## Top Records

```ls
| compkey | location                                 | full_count_start    | full_count_end      | notes                         | day_1 | day_2 | day_3 | day_4 | day_5 | day_6 | day_7 | day_8 | day_9 | day_10 | day_11 | day_12 | day_13 | day_14 | day_15 | day_16 | day_17 | day_18 | day_19 | day_20 | day_21 | 
| ======= | ======================================== | =================== | =================== | ============================= | ===== | ===== | ===== | ===== | ===== | ===== | ===== | ===== | ===== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | 
| 1569    | 12th Ave NE n/o NE 50th st NB            | 2015-07-03T00:00:00 | 2015-07-08T00:00:00 |                               | 86    | 68    | 60    | 134   | 159   | 133   |       |       |       |        |        |        |        |        |        |        |        |        |        |        |        | 
| 1569    | 12th Ave NE s/o NE 50th st SB            | 2015-07-03T00:00:00 | 2015-07-08T00:00:00 |                               | 212   | 190   | 175   | 263   | 323   | 333   |       |       |       |        |        |        |        |        |        |        |        |        |        |        |        | 
| 626835  | 12th Ave S s/o S Weller St NB            | 2015-05-02T00:00:00 | 2015-05-21T00:00:00 |                               | 70    | 85    | 175   | 76    | 59    | 82    | 47    | 74    | 56    | 37     | 37     | 35     | 38     | 57     | 20     | 22     | 59     | 84     | 45     | 131    |        | 
| 626835  | 12th Ave S s/o S Weller St SB            | 2015-05-02T00:00:00 | 2015-05-21T00:00:00 |                               | 219   | 187   | 383   | 724   | 385   | 435   | 411   | 235   | 153   | 372    | 367    | 304    | 374    | 517    | 186    | 139    | 417    | 436    | 428    | 413    |        | 
| 2437    | 17th Ave NW n/o NW 53rd St               | 2015-08-08T00:00:00 | 2015-08-13T00:00:00 | Hose unplugged 8/11           | 177   | 116   | 283   |       |       |       |       |       |       |        |        |        |        |        |        |        |        |        |        |        |        | 
| 2509    | 17th Ave SW n/o Henderson                | 2015-12-05T00:00:00 | 2015-12-10T00:00:00 |                               | 2     | 2     | 7     | 7     | 7     | 9     |       |       |       |        |        |        |        |        |        |        |        |        |        |        |        | 
| 2604    | 18th ave S n/o S Bayview St              | 2015-09-05T00:00:00 | 2015-09-10T00:00:00 |                               | 17    | 15    | 19    | 32    | 34    | 38    |       |       |       |        |        |        |        |        |        |        |        |        |        |        |        | 
| 1003    | 1st Ave btwn Madison St and Marion St SB | 2015-08-18T00:00:00 | 2015-08-26T00:00:00 | Hose unplugged first two days |       |       | 208   | 260   | 151   | 123   | 213   | 274   | 268   |        |        |        |        |        |        |        |        |        |        |        |        | 
| 3230    | 22nd Ave n/o E Columbia                  | 2015-08-01T00:00:00 | 2015-08-06T00:00:00 |                               | 49    | 34    | 47    | 46    | 49    | 42    |       |       |       |        |        |        |        |        |        |        |        |        |        |        |        | 
| 4037    | 27th Ave NE n/o NE 130th St              | 2015-07-03T00:00:00 | 2015-07-08T00:00:00 |                               | 79    | 43    | 45    | 89    | 55    | 98    |       |       |       |        |        |        |        |        |        |        |        |        |        |        |        | 
```