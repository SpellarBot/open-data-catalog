# HFD Response Under 4 minutes 1/1/2012 - Current

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/hfd-response-under-4-minutes-1-1-2012-current) |
| Metadata | [Link](https://data.hartford.gov/api/views/2qj6-tvch) |
| Data: JSON | [100 Rows](https://data.hartford.gov/api/views/2qj6-tvch/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hartford.gov/api/views/2qj6-tvch/rows.csv?max_rows=100) |
| Host | data.hartford.gov |
| Id | 2qj6-tvch |
| Name | HFD Response Under 4 minutes 1/1/2012 - Current |
| Attribution | City of Hartford |
| Category | Public Safety |
| Tags | fire, public safety, hartford, ct |
| Created | 2015-09-03T18:41:58Z |
| Publication Date | 2015-09-09T17:40:01Z |

## Description

This data is being used for our HartStat application to track Fire Department response times 4 minutes and under. Updated nightly

## Columns

```ls
| Included | Schema Type    | Field Name                    | Name                          | Data Type     | Render Type   |
| ======== | ============== | ============================= | ============================= | ============= | ============= |
| Yes      | time           | alarm_date                    | Alarm Date                    | calendar_date | calendar_date |
| Yes      | numeric metric | total_calls                   | Total Calls                   | number        | number        |
| Yes      | numeric metric | fire_count                    | Fire_Count                    | number        | number        |
| Yes      | numeric metric | ems_count                     | EMS_Count                     | number        | number        |
| Yes      | numeric metric | other_count                   | Other_Count                   | number        | number        |
| Yes      | numeric metric | fireresponseunder4min         | FireResponseUnder4min         | number        | number        |
| Yes      | numeric metric | emsresponseunder4min          | EMSResponseUnder4min          | number        | number        |
| Yes      | numeric metric | otherresponseunder4min        | OtherResponseUnder4min        | number        | number        |
| Yes      | numeric metric | allcallsunder4min             | AllCallsUnder4min             | number        | number        |
| Yes      | numeric metric | fireresponseunder4minpercent  | FireResponseUnder4minPercent  | percent       | percent       |
| Yes      | numeric metric | emsresponseunder4minpercent   | EMSResponseUnder4minPercent   | percent       | percent       |
| Yes      | numeric metric | otherresponseunder4minpercent | OtherResponseUnder4minPercent | percent       | percent       |
| Yes      | numeric metric | allcallsunder4minpercent      | AllCallsUnder4minPercent      | percent       | percent       |
```

## Time Field

```ls
Value = alarm_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:2qj6-tvch d:2014-08-11T00:00:00.000Z m:emsresponseunder4min=25 m:ems_count=40 m:emsresponseunder4minpercent=62 m:allcallsunder4minpercent=72 m:total_calls=65 m:fire_count=4 m:fireresponseunder4min=4 m:allcallsunder4min=47 m:otherresponseunder4min=18 m:fireresponseunder4minpercent=100 m:other_count=21 m:otherresponseunder4minpercent=86

series e:2qj6-tvch d:2013-03-23T00:00:00.000Z m:emsresponseunder4min=41 m:ems_count=55 m:emsresponseunder4minpercent=75 m:allcallsunder4minpercent=68 m:total_calls=69 m:fire_count=1 m:fireresponseunder4min=0 m:allcallsunder4min=47 m:otherresponseunder4min=6 m:fireresponseunder4minpercent=0 m:other_count=13 m:otherresponseunder4minpercent=46

series e:2qj6-tvch d:2014-12-13T00:00:00.000Z m:emsresponseunder4min=23 m:ems_count=38 m:emsresponseunder4minpercent=61 m:allcallsunder4minpercent=57 m:total_calls=51 m:fire_count=0 m:fireresponseunder4min=0 m:allcallsunder4min=29 m:otherresponseunder4min=6 m:fireresponseunder4minpercent=0 m:other_count=13 m:otherresponseunder4minpercent=46
```

## Meta Commands

```ls
metric m:total_calls p:integer l:"Total Calls" t:dataTypeName=number

metric m:fire_count p:integer l:Fire_Count t:dataTypeName=number

metric m:ems_count p:integer l:EMS_Count t:dataTypeName=number

metric m:other_count p:integer l:Other_Count t:dataTypeName=number

metric m:fireresponseunder4min p:integer l:FireResponseUnder4min t:dataTypeName=number

metric m:emsresponseunder4min p:integer l:EMSResponseUnder4min t:dataTypeName=number

metric m:otherresponseunder4min p:integer l:OtherResponseUnder4min t:dataTypeName=number

metric m:allcallsunder4min p:integer l:AllCallsUnder4min t:dataTypeName=number

metric m:fireresponseunder4minpercent p:integer l:FireResponseUnder4minPercent t:dataTypeName=percent

metric m:emsresponseunder4minpercent p:integer l:EMSResponseUnder4minPercent t:dataTypeName=percent

metric m:otherresponseunder4minpercent p:integer l:OtherResponseUnder4minPercent t:dataTypeName=percent

metric m:allcallsunder4minpercent p:integer l:AllCallsUnder4minPercent t:dataTypeName=percent

entity e:2qj6-tvch l:"HFD Response Under 4 minutes 1/1/2012 - Current" t:attribution="City of Hartford" t:url=https://data.hartford.gov/api/views/2qj6-tvch

property e:2qj6-tvch t:meta.view v:id=2qj6-tvch v:category="Public Safety" v:attributionLink=http://www.hartford.gov v:averageRating=0 v:name="HFD Response Under 4 minutes 1/1/2012 - Current" v:attribution="City of Hartford"

property e:2qj6-tvch t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:2qj6-tvch t:meta.view.owner v:id=cdqe-xcn5 v:screenName=Brett v:displayName=Brett

property e:2qj6-tvch t:meta.view.tableauthor v:id=cdqe-xcn5 v:screenName=Brett v:roleName=administrator v:displayName=Brett
```

## Top Records

```ls
| alarm_date          | total_calls | fire_count | ems_count | other_count | fireresponseunder4min | emsresponseunder4min | otherresponseunder4min | allcallsunder4min | fireresponseunder4minpercent | emsresponseunder4minpercent | otherresponseunder4minpercent | allcallsunder4minpercent | 
| =================== | =========== | ========== | ========= | =========== | ===================== | ==================== | ====================== | ================= | ============================ | =========================== | ============================= | ======================== | 
| 2014-08-11T00:00:00 | 65          | 4          | 40        | 21          | 4                     | 25                   | 18                     | 47                | 100                          | 62                          | 86                            | 72                       | 
| 2013-03-23T00:00:00 | 69          | 1          | 55        | 13          | 0                     | 41                   | 6                      | 47                | 0                            | 75                          | 46                            | 68                       | 
| 2014-12-13T00:00:00 | 51          | 0          | 38        | 13          | 0                     | 23                   | 6                      | 29                | 0                            | 61                          | 46                            | 57                       | 
| 2014-04-19T00:00:00 | 55          | 3          | 39        | 13          | 0                     | 31                   | 5                      | 36                | 0                            | 79                          | 38                            | 65                       | 
| 2012-09-23T00:00:00 | 46          | 2          | 33        | 11          | 1                     | 26                   | 10                     | 37                | 50                           | 79                          | 91                            | 80                       | 
| 2012-01-20T00:00:00 | 73          | 2          | 49        | 22          | 1                     | 24                   | 11                     | 36                | 50                           | 49                          | 50                            | 49                       | 
| 2015-07-13T00:00:00 | 79          | 2          | 50        | 27          | 1                     | 33                   | 18                     | 52                | 50                           | 66                          | 67                            | 66                       | 
| 2014-09-28T00:00:00 | 62          | 3          | 43        | 16          | 3                     | 25                   | 10                     | 38                | 100                          | 58                          | 62                            | 61                       | 
| 2013-02-27T00:00:00 | 42          | 1          | 35        | 6           | 1                     | 20                   | 4                      | 25                | 100                          | 57                          | 67                            | 60                       | 
| 2012-08-07T00:00:00 | 54          | 1          | 48        | 5           | 0                     | 33                   | 2                      | 35                | 0                            | 69                          | 40                            | 65                       | 
```