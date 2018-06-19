# Parking Spaces at Off-street Parking Facilities

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/parking-spaces-at-off-street-parking-facilities) |
| Metadata | [Link](https://data.sfgov.org/api/views/yqii-ihqq) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/yqii-ihqq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/yqii-ihqq/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | yqii-ihqq |
| Name | Parking Spaces at Off-street Parking Facilities |
| Category | Transportation |
| Tags | parking supply, parking census |
| Created | 2016-02-27T01:33:12Z |
| Publication Date | 2016-04-15T18:09:03Z |

## Description

This dataset identifies the location and number of parking spaces at off-street parking facilities with publicly available parking in order to support good parking management policies. Data was created through the manual addition of points and attributes in a GIS system. Data originally sourced from the Registered Businesses in SF published by the SF Treasurer's office https://data.sfgov.org/Economy-and-Community/Registered-Business-Locations-San-Francisco/g8m3-pdis. Additional field work conducted in 2009-2013 to verify, correct, and augment the Treasurer's office registered businesses database. Full documentation found here: http://sfpark.org/resources/parking-census-map-april-2014/ The data is updated infrequently. SFMTA owned garage attributes are updated approximately twice a year. Note: Count of spaces found in the "RegCap" field ("regular capacity")

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                         | Data Type | Render Type |
| ======== | ============== | ============================ | ============================ | ========= | =========== |
| Yes      | series tag     | object_id                    | Object ID                    | text      | number      |
| Yes      | series tag     | oldhours                     | OLDHOURS                     | text      | text        |
| Yes      | numeric metric | off_id_1                     | OFF_ID_1                     | number    | number      |
| Yes      | numeric metric | assessor_1                   | ASSESSOR_1                   | number    | number      |
| Yes      | series tag     | name1_1                      | NAME1_1                      | text      | text        |
| Yes      | series tag     | name2_1                      | NAME2_1                      | text      | text        |
| Yes      | series tag     | agency                       | Agency                       | text      | text        |
| No       |                | address                      | Address                      | text      | text        |
| Yes      | series tag     | g_l_1                        | G_L_1                        | text      | text        |
| Yes      | series tag     | primary_type                 | Primary Type                 | text      | text        |
| Yes      | series tag     | secondary_type               | Secondary Type               | text      | text        |
| Yes      | series tag     | definiti_1                   | DEFINITI_1                   | text      | text        |
| Yes      | numeric metric | regular_capacity             | Regular Capacity             | number    | number      |
| Yes      | numeric metric | valet_capacity               | Valet Capacity               | number    | number      |
| Yes      | numeric metric | mc_cap_1                     | MC_CAP_1                     | number    | number      |
| Yes      | series tag     | oldhours_1                   | OLDHOURS_1                   | text      | text        |
| No       |                | monday_open_time             | Monday Open Time             | number    | number      |
| No       |                | monday_close_time            | Monday Close Time            | number    | number      |
| No       |                | tuesday_open_time            | Tuesday Open Time            | number    | number      |
| No       |                | tuesday_close_time           | Tuesday Close Time           | number    | number      |
| No       |                | wednesday_open_time          | Wednesday Open Time          | number    | number      |
| No       |                | wednesday_close_time         | Wednesday Close Time         | number    | number      |
| No       |                | thursday_open_time           | Thursday Open Time           | number    | number      |
| No       |                | thursday_close_time          | Thursday Close Time          | number    | number      |
| No       |                | friday_open_time             | Friday Open Time             | number    | number      |
| No       |                | friday_close_time            | Friday Close Time            | number    | number      |
| No       |                | saturday_open_time           | Saturday Open Time           | number    | number      |
| No       |                | saturday_close_time          | Saturday Close Time          | number    | number      |
| No       |                | sunday_open_time             | Sunday Open Time             | number    | number      |
| No       |                | sunday_close_time            | Sunday Close Time            | number    | number      |
| Yes      | numeric metric | regmonth_1                   | REGMONTH_1                   | number    | number      |
| Yes      | numeric metric | assignmt_1                   | ASSIGNMT_1                   | number    | number      |
| Yes      | numeric metric | dailyfla_1                   | DAILYFLA_1                   | number    | number      |
| Yes      | numeric metric | daily_start                  | Daily Start                  | number    | text        |
| Yes      | numeric metric | daily_end                    | Daily End                    | number    | text        |
| Yes      | numeric metric | eveflat_1                    | EVEFLAT_1                    | number    | number      |
| Yes      | numeric metric | evening_start                | Evening Start                | number    | text        |
| Yes      | numeric metric | evening_end                  | Evening End                  | number    | text        |
| Yes      | numeric metric | early_bird_rate_1            | Early Bird Rate 1            | number    | number      |
| No       |                | early_bird_rate_1_start_time | Early Bird Rate 1 Start Time | number    | number      |
| Yes      | numeric metric | early_bird_rate_1_endtime    | Early Bird Rate 1 EndTime    | number    | number      |
| Yes      | numeric metric | early_bird_rate_2            | Early Bird Rate 2            | number    | number      |
| No       |                | early_bird_rate_2_start_time | Early Bird Rate 2 Start Time | number    | number      |
| Yes      | numeric metric | early_bird_rate_2_endtime    | Early Bird Rate 2 EndTime    | number    | number      |
| Yes      | numeric metric | onehr_1                      | ONEHR_1                      | number    | number      |
| Yes      | numeric metric | twohr_1                      | TWOHR_1                      | number    | number      |
| Yes      | numeric metric | threehr_1                    | THREEHR_1                    | number    | number      |
| Yes      | numeric metric | fourhr_1                     | FOURHR_1                     | number    | number      |
| Yes      | numeric metric | twelvehr_1                   | TWELVEHR_1                   | number    | number      |
| Yes      | numeric metric | dailymax_1                   | DAILYMAX_1                   | number    | number      |
| Yes      | time           | verified_date                | Verified Date                | date      | date        |
| Yes      | series tag     | notes                        | Notes                        | text      | text        |
| Yes      | numeric metric | lotgone                      | LOTGONE                      | number    | number      |
| Yes      | series tag     | owner                        | Owner                        | text      | text        |
| No       |                | last_edited_date             | Last Edited Date             | date      | date        |
```

## Time Field

```ls
Value = verified_date
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address,monday_open_time,monday_close_time,tuesday_open_time,tuesday_close_time,wednesday_open_time,wednesday_close_time,thursday_open_time,thursday_close_time,friday_open_time,friday_close_time,saturday_open_time,saturday_close_time,sunday_open_time,sunday_close_time,early_bird_rate_1_start_time,early_bird_rate_2_start_time,last_edited_date
```

## Data Commands

```ls
series e:yqii-ihqq d:2011-07-12T00:00:00.000Z t:oldhours_1=8-530 t:oldhours=8-530 t:object_id=1 t:g_l_1=G t:owner=Private t:primary_type=PPA t:name2_1=AMPCO t:notes="Early bird rate is in by 7:30 am out by 5:30 pm." m:early_bird_rate_2=0 m:early_bird_rate_1=22 m:eveflat_1=0 m:assessor_1=141 m:onehr_1=12 m:regmonth_1=450 m:regular_capacity=30 m:threehr_1=32 m:off_id_1=46 m:early_bird_rate_2_endtime=0 m:twelvehr_1=32 m:twohr_1=24 m:fourhr_1=32 m:dailyfla_1=0 m:mc_cap_1=0 m:early_bird_rate_1_endtime=830 m:lotgone=0 m:valet_capacity=25 m:dailymax_1=32 m:assignmt_1=0

series e:yqii-ihqq d:2008-11-09T00:00:00.000Z t:oldhours_1=6-7 t:oldhours=6-7 t:object_id=2 t:g_l_1=G t:owner=Private t:primary_type=PPA t:name2_1=AMPCO m:early_bird_rate_2=0 m:early_bird_rate_1=19 m:eveflat_1=0 m:assessor_1=142 m:onehr_1=12 m:regmonth_1=375 m:regular_capacity=90 m:threehr_1=25 m:off_id_1=47 m:early_bird_rate_2_endtime=0 m:twelvehr_1=25 m:twohr_1=22 m:fourhr_1=25 m:dailyfla_1=0 m:mc_cap_1=0 m:early_bird_rate_1_endtime=0 m:lotgone=0 m:valet_capacity=0 m:dailymax_1=0 m:assignmt_1=0

series e:yqii-ihqq d:2009-01-13T00:00:00.000Z t:oldhours_1=8-6 t:oldhours=8-6 t:object_id=3 t:g_l_1=L t:owner=Private t:primary_type=PPA t:name2_1=AMPCO m:early_bird_rate_2=0 m:early_bird_rate_1=0 m:eveflat_1=0 m:assessor_1=158 m:onehr_1=5 m:regmonth_1=145 m:regular_capacity=120 m:threehr_1=15 m:off_id_1=48 m:early_bird_rate_2_endtime=0 m:twelvehr_1=15 m:twohr_1=10 m:fourhr_1=15 m:dailyfla_1=0 m:mc_cap_1=0 m:early_bird_rate_1_endtime=0 m:lotgone=0 m:valet_capacity=0 m:dailymax_1=0 m:assignmt_1=0
```

## Meta Commands

```ls
metric m:off_id_1 p:integer l:OFF_ID_1 t:dataTypeName=number

metric m:assessor_1 p:integer l:ASSESSOR_1 t:dataTypeName=number

metric m:regular_capacity p:integer l:"Regular Capacity" t:dataTypeName=number

metric m:valet_capacity p:integer l:"Valet Capacity" t:dataTypeName=number

metric m:mc_cap_1 p:integer l:MC_CAP_1 t:dataTypeName=number

metric m:regmonth_1 p:integer l:REGMONTH_1 t:dataTypeName=number

metric m:assignmt_1 p:integer l:ASSIGNMT_1 t:dataTypeName=number

metric m:dailyfla_1 p:integer l:DAILYFLA_1 t:dataTypeName=number

metric m:daily_start p:long l:"Daily Start" t:dataTypeName=number

metric m:daily_end p:long l:"Daily End" t:dataTypeName=number

metric m:eveflat_1 p:integer l:EVEFLAT_1 t:dataTypeName=number

metric m:evening_start p:long l:"Evening Start" t:dataTypeName=number

metric m:evening_end p:long l:"Evening End" t:dataTypeName=number

metric m:early_bird_rate_1 p:integer l:"Early Bird Rate 1" t:dataTypeName=number

metric m:early_bird_rate_1_endtime p:integer l:"Early Bird Rate 1 EndTime" t:dataTypeName=number

metric m:early_bird_rate_2 p:integer l:"Early Bird Rate 2" t:dataTypeName=number

metric m:early_bird_rate_2_endtime p:integer l:"Early Bird Rate 2 EndTime" t:dataTypeName=number

metric m:onehr_1 p:double l:ONEHR_1 t:dataTypeName=number

metric m:twohr_1 p:integer l:TWOHR_1 t:dataTypeName=number

metric m:threehr_1 p:double l:THREEHR_1 t:dataTypeName=number

metric m:fourhr_1 p:integer l:FOURHR_1 t:dataTypeName=number

metric m:twelvehr_1 p:integer l:TWELVEHR_1 t:dataTypeName=number

metric m:dailymax_1 p:integer l:DAILYMAX_1 t:dataTypeName=number

metric m:lotgone p:integer l:LOTGONE t:dataTypeName=number

entity e:yqii-ihqq l:"Parking Spaces at Off-street Parking Facilities" t:url=https://data.sfgov.org/api/views/yqii-ihqq

property e:yqii-ihqq t:meta.view v:id=yqii-ihqq v:category=Transportation v:averageRating=0 v:name="Parking Spaces at Off-street Parking Facilities"

property e:yqii-ihqq t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:yqii-ihqq t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:displayName=OpenData

property e:yqii-ihqq t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```

## Top Records

```ls
| object_id | oldhours | off_id_1 | assessor_1 | name1_1                | name2_1     | agency | address             | g_l_1 | primary_type | secondary_type | definiti_1 | regular_capacity | valet_capacity | mc_cap_1 | oldhours_1 | monday_open_time | monday_close_time | tuesday_open_time | tuesday_close_time | wednesday_open_time | wednesday_close_time | thursday_open_time | thursday_close_time | friday_open_time | friday_close_time | saturday_open_time | saturday_close_time | sunday_open_time | sunday_close_time | regmonth_1 | assignmt_1 | dailyfla_1 | daily_start | daily_end | eveflat_1 | evening_start | evening_end | early_bird_rate_1 | early_bird_rate_1_start_time | early_bird_rate_1_endtime | early_bird_rate_2 | early_bird_rate_2_start_time | early_bird_rate_2_endtime | onehr_1 | twohr_1 | threehr_1 | fourhr_1 | twelvehr_1 | dailymax_1 | verified_date | notes                                                                                                                                                        | lotgone | owner   | last_edited_date | 
| ========= | ======== | ======== | ========== | ====================== | =========== | ====== | =================== | ===== | ============ | ============== | ========== | ================ | ============== | ======== | ========== | ================ | ================= | ================= | ================== | =================== | ==================== | ================== | =================== | ================ | ================= | ================== | =================== | ================ | ================= | ========== | ========== | ========== | =========== | ========= | ========= | ============= | =========== | ================= | ============================ | ========================= | ================= | ============================ | ========================= | ======= | ======= | ========= | ======== | ========== | ========== | ============= | ============================================================================================================================================================ | ======= | ======= | ================ | 
| 1         | 8-530    | 46       | 141        |                        | AMPCO       |        | 201 CALIFORNIA ST   | G     | PPA          |                |            | 30               | 25             | 0        | 8-530      | 730              | 1730              | 730               | 1730               | 730                 | 1730                 | 730                | 1730                | 730              | 1730              | 0                  | 0                   | 0                | 0                 | 450        | 0          | 0          |             |           | 0         |               |             | 22                | 730                          | 830                       | 0                 | 0                            | 0                         | 12      | 24      | 32        | 32       | 32         | 32         | 1310428800    | Early bird rate is in by 7:30 am out by 5:30 pm.                                                                                                             | 0       | Private |                  | 
| 2         | 6-7      | 47       | 142        |                        | AMPCO       |        | 201 SPEAR ST        | G     | PPA          |                |            | 90               | 0              | 0        | 6-7        | 0                | 0                 | 0                 | 0                  | 0                   | 0                    | 0                  | 0                   | 0                | 0                 | 0                  | 0                   | 0                | 0                 | 375        | 0          | 0          |             |           | 0         |               |             | 19                | 0                            | 0                         | 0                 | 0                            | 0                         | 12      | 22      | 25        | 25       | 25         | 0          | 1226188800    |                                                                                                                                                              | 0       | Private |                  | 
| 3         | 8-6      | 48       | 158        |                        | AMPCO       |        | 2186 GEARY BLVD     | L     | PPA          |                |            | 120              | 0              | 0        | 8-6        | 0                | 0                 | 0                 | 0                  | 0                   | 0                    | 0                  | 0                   | 0                | 0                 | 0                  | 0                   | 0                | 0                 | 145        | 0          | 0          |             |           | 0         |               |             | 0                 | 0                            | 0                         | 0                 | 0                            | 0                         | 5       | 10      | 15        | 15       | 15         | 0          | 1231804800    |                                                                                                                                                              | 0       | Private |                  | 
| 4         | 530-730  | 49       | 163        | Mills Building         | AMPCO       |        | 220 BUSH ST         | G     | PPA          |                |            | 150              | 0              | 5        | 530-730    | 530              | 1930              | 530               | 1930               | 530                 | 1930                 | 530                | 1930                | 530              | 1930              | 0                  | 0                   | 0                | 0                 | 450        | 0          | 0          |             |           | 0         |               |             | 0                 | 0                            | 0                         | 0                 | 0                            | 0                         | 12      | 24      | 30        | 30       | 30         | 30         | 1310428800    | Motorcycle rage: $7.50/day Actual motorcycle capacity is "some" -- I entered "5" as an estimate. Tenant monthly rate: 400                                    | 0       | Private |                  | 
| 5         | 5-8      | 50       | 187        |                        | AMPCO       |        | 235 MONTGOMERY ST   | G     | PPA          |                |            | 312              | 0              | 0        | 5-8        | 500              | 2000              | 500               | 2000               | 500                 | 2000                 | 500                | 2000                | 500              | 2000              | 0                  | 0                   | 0                | 0                 | 460        | 0          | 0          |             |           | 0         |               |             | 23                | 500                          | 830                       | 0                 | 0                            | 0                         | 14      | 28      | 31        | 31       | 31         | 31         | 1310428800    | Early bird rate is in by 8:30 am out by 5:30 pm. Tenant monthly rate is 400. This RegCap actually includes valet parking.                                    | 0       | Private |                  | 
| 6         | 5-12     | 51       | 135        | Embarcadero 2          | AMPCO       |        | 250 Sacramento St   | G     | PPA          |                |            | 664              | 0              | 10       | 5-12       | 500              | 2400              | 500               | 2400               | 500                 | 2400                 | 500                | 2400                | 500              | 2400              | 700                | 2400                | 700              | 2400              | 435        | 0          | 0          |             |           | 24        | 1700          | 100         | 0                 | 0                            | 0                         | 0                 | 0                            | 0                         | 12      | 24      | 32        | 32       | 32         | 32         | 1310428800    | See notes for EC1/OffID 64. MC parking is $85/month.                                                                                                         | 0       | Private |                  | 
| 7         |          | 52       | 202        | Seawall 351            | Ace Parking | Port   | 250 The Embarcadero |       | PPA          |                |            | 77               | 31             | 0        |            | 800              | 2030              | 800               | 2030               | 800                 | 2030                 | 800                | 2030                | 800              | 2030              | 700                | 2030                | 800              | 2000              | 0          | 0          | 0          |             |           | 15        | 1600          | 2030        | 0                 | 0                            | 0                         | 0                 | 0                            | 0                         | 6.5     | 13      | 19.5      | 26       | 50         | 50         | 1310428800    | Pier 3. Unknown capacity. Close time varies depending on how busy the garage is. EveEnd depends on closing time. Early bird rate is in by 8 am, out by 6 pm. | 0       | Port    |                  | 
| 8         |          | 53       | 210        |                        | Douglas     |        | 255 CALIFORNIA ST   | G     | PPA          |                |            | 45               | 15             | 0        |            | 630              | 2000              | 630               | 2000               | 630                 | 2000                 | 630                | 2000                | 630              | 2000              | 0                  | 0                   | 0                | 0                 | 450        | 0          | 0          |             |           | 0         |               |             | 22                | 630                          | 830                       | 0                 | 0                            | 0                         | 12      | 24      | 33        | 33       | 33         | 33         | 1310428800    |                                                                                                                                                              | 0       | Private |                  | 
| 9         |          | 54       | 211        | Pier 39 Garage         | AMPCO       |        | 2550 POWELL ST      | G     | PPA          |                |            | 980              | 0              | 0        |            | 0                | 0                 | 0                 | 0                  | 0                   | 0                    | 0                  | 0                   | 0                | 0                 | 0                  | 0                   | 0                | 0                 | 0          | 0          | 0          |             |           | 0         |               |             | 0                 | 0                            | 0                         | 0                 | 0                            | 0                         | 0       | 0       | 0         | 0        | 0          | 0          | 1221955200    |                                                                                                                                                              | 0       | Private |                  | 
| 10        | 24       | 56       | 233        | Mason-O'Farrell Garage | AMPCO       |        | 325 MASON ST        | G     | PPA          |                |            | 640              | 0              | 0        | 24         | 0                | 0                 | 0                 | 0                  | 0                   | 0                    | 0                  | 0                   | 0                | 0                 | 0                  | 0                   | 0                | 0                 | 300        | 400        | 0          |             |           | 15        | 1730          | 2430        | 15                | 1000                         | 1900                      | 0                 | 0                            | 0                         | 8       | 16      | 24        | 32       | 32         | 32         | 1311638400    | Later evening: $20, in after 1730, out by 930 next day only 42 spaces open 3:30pm Wed 7/27                                                                   | 0       | Private |                  | 
```