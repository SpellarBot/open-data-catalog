# EMS - Incidents by Month

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ems-incidents-by-month) |
| Metadata | [Link](https://data.austintexas.gov/api/views/gjtj-jt2d) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/gjtj-jt2d/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/gjtj-jt2d/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | gjtj-jt2d |
| Name | EMS - Incidents by Month |
| Attribution | Austin-Travis County EMS |
| Category | Public Safety |
| Tags | ems, incidents, atcems, demand, workload, response times, incident counts, incident priority, city, county, coa, operations |
| Created | 2014-10-16T13:33:05Z |
| Publication Date | 2016-10-11T14:11:54Z |

## Description

This table contains data describing requests for assistance received by ATCEMS.  Incident counts are broken out by location, and priority for City of Austin and Travis County incidents.

See document attached to metadata for more details.

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                                        | Data Type     | Render Type   |
| ======== | ============== | ========================= | =========================================== | ============= | ============= |
| Yes      | numeric metric | month_key                 | Month Key                                   | number        | number        |
| Yes      | time           | month_start_date          | Month-Year                                  | calendar_date | calendar_date |
| Yes      | numeric metric | count_incidents_all       | Total Incidents                             | number        | number        |
| Yes      | numeric metric | count_incidents_coa       | Austin Incidents                            | number        | number        |
| Yes      | numeric metric | count_incidents_tc        | Travis County Incidents                     | number        | number        |
| Yes      | numeric metric | count_incidents_other     | Other Area Incidents                        | number        | number        |
| Yes      | numeric metric | count_incidents_coa_or_tc | Combined Austin and Travis County Incidents | number        | number        |
| Yes      | numeric metric | count_incidents_coa_p1    | Austin P1 Incidents                         | number        | number        |
| Yes      | numeric metric | count_incidents_coa_p2    | Austin P2 Incidents                         | number        | number        |
| Yes      | numeric metric | count_incidents_coa_p3    | Austin P3 Incidents                         | number        | number        |
| Yes      | numeric metric | count_incidents_coa_p4    | Austin P4 Incidents                         | number        | number        |
| Yes      | numeric metric | count_incidents_coa_p5    | Austin P5 Incidents                         | number        | number        |
| Yes      | numeric metric | count_incidents_tc_p1     | Travis County P1 Incidents                  | number        | number        |
| Yes      | numeric metric | count_incidents_tc_p2     | Travis County P2 Incidents                  | number        | number        |
| Yes      | numeric metric | count_incidents_tc_p3     | Travis County P3 Incidents                  | number        | number        |
| Yes      | numeric metric | count_incidents_tc_p4     | Travis County P4 Incidents                  | number        | number        |
| Yes      | numeric metric | count_incidents_tc_p5     | Travis County P5 Incidents                  | number        | number        |
| Yes      | numeric metric | percent_on_time_all       | Overall On-Time Compliance                  | percent       | percent       |
| Yes      | numeric metric | percent_on_time_coa       | Austin On-Time Compliance                   | percent       | percent       |
| Yes      | numeric metric | percent_on_time_tc        | Travis County On-Time Compliance            | percent       | percent       |
| Yes      | numeric metric | percent_on_time_coa_p1    | Austin P1 On-Time Compliance                | percent       | percent       |
| Yes      | numeric metric | percent_on_time_coa_p2    | Austin P2 On-Time Compliance                | percent       | percent       |
| Yes      | numeric metric | percent_on_time_coa_p3    | Austin P3 On-Time Compliance                | percent       | percent       |
| Yes      | numeric metric | percent_on_time_coa_p4    | Austin P4 On-Time Compliance                | percent       | percent       |
| Yes      | numeric metric | percent_on_time_coa_p5    | Austin P5 On-Time Compliance                | percent       | percent       |
| Yes      | numeric metric | percent_on_time_tc_p1     | Travis County P1 On-Time Compliance         | percent       | percent       |
| Yes      | numeric metric | percent_on_time_tc_p2     | Travis County P2 On-Time Compliance         | percent       | percent       |
| Yes      | numeric metric | percent_on_time_tc_p3     | Travis County P3 On-Time Compliance         | percent       | percent       |
| Yes      | numeric metric | percent_on_time_tc_p4     | Travis County P4 On-Time Compliance         | percent       | percent       |
| Yes      | numeric metric | percent_on_time_tc_p5     | Travis County P5 On-Time Compliance         | percent       | percent       |
| Yes      | numeric metric | percent_on_time_target    | Target On-Time Compliance                   | percent       | percent       |
```

## Time Field

```ls
Value = month_start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:gjtj-jt2d d:2010-10-01T00:00:00.000Z m:percent_on_time_target=90 m:count_incidents_coa_or_tc=8892 m:count_incidents_other=18 m:count_incidents_coa=7571 m:percent_on_time_coa_p4=98.8235 m:percent_on_time_coa_p5=94.5727 m:percent_on_time_coa_p2=96.7793 m:percent_on_time_coa_p3=99.2608 m:percent_on_time_coa_p1=94.1544 m:count_incidents_tc_p1=81 m:count_incidents_tc_p4=498 m:count_incidents_tc_p5=163 m:count_incidents_tc_p2=380 m:count_incidents_tc_p3=199 m:count_incidents_all=8910 m:count_incidents_tc=1321 m:month_key=201010 m:percent_on_time_tc_p5=88.1118 m:percent_on_time_tc_p4=95.6666 m:percent_on_time_all=95.7696 m:percent_on_time_coa=97.3176 m:percent_on_time_tc=86.4209 m:count_incidents_coa_p1=533 m:percent_on_time_tc_p1=79.7297 m:count_incidents_coa_p3=1039 m:percent_on_time_tc_p3=89.7727 m:count_incidents_coa_p2=2103 m:percent_on_time_tc_p2=77.2189 m:count_incidents_coa_p5=958 m:count_incidents_coa_p4=2938

series e:gjtj-jt2d d:2010-11-01T00:00:00.000Z m:percent_on_time_target=90 m:count_incidents_coa_or_tc=7796 m:count_incidents_other=30 m:count_incidents_coa=6564 m:percent_on_time_coa_p4=98.4278 m:percent_on_time_coa_p5=95.4929 m:percent_on_time_coa_p2=96.7289 m:percent_on_time_coa_p3=98.9424 m:percent_on_time_coa_p1=92.9971 m:count_incidents_tc_p1=83 m:count_incidents_tc_p4=473 m:count_incidents_tc_p5=165 m:count_incidents_tc_p2=346 m:count_incidents_tc_p3=165 m:count_incidents_all=7826 m:count_incidents_tc=1232 m:month_key=201011 m:percent_on_time_tc_p5=92.9078 m:percent_on_time_tc_p4=96.7532 m:percent_on_time_all=96.0068 m:percent_on_time_coa=97.2278 m:percent_on_time_tc=89.4 m:count_incidents_coa_p1=401 m:percent_on_time_tc_p1=80.7692 m:count_incidents_coa_p3=931 m:percent_on_time_tc_p3=89.1025 m:count_incidents_coa_p2=1896 m:percent_on_time_tc_p2=82.9652 m:count_incidents_coa_p5=796 m:count_incidents_coa_p4=2540

series e:gjtj-jt2d d:2010-12-01T00:00:00.000Z m:percent_on_time_target=90 m:count_incidents_coa_or_tc=8148 m:count_incidents_other=34 m:count_incidents_coa=6858 m:percent_on_time_coa_p4=98.2436 m:percent_on_time_coa_p5=94.5029 m:percent_on_time_coa_p2=96.6337 m:percent_on_time_coa_p3=98.6698 m:percent_on_time_coa_p1=93.154 m:count_incidents_tc_p1=97 m:count_incidents_tc_p4=501 m:count_incidents_tc_p5=152 m:count_incidents_tc_p2=363 m:count_incidents_tc_p3=177 m:count_incidents_all=8182 m:count_incidents_tc=1290 m:month_key=201012 m:percent_on_time_tc_p5=92.5373 m:percent_on_time_tc_p4=96.0396 m:percent_on_time_all=95.4497 m:percent_on_time_coa=96.8772 m:percent_on_time_tc=87.5855 m:count_incidents_coa_p1=458 m:percent_on_time_tc_p1=75.2808 m:count_incidents_coa_p3=903 m:percent_on_time_tc_p3=86.3354 m:count_incidents_coa_p2=1892 m:percent_on_time_tc_p2=81.8452 m:count_incidents_coa_p5=950 m:count_incidents_coa_p4=2655
```

## Meta Commands

```ls
metric m:month_key p:integer l:"Month Key" d:"Year and month for record in <yyyymm> format." t:dataTypeName=number

metric m:count_incidents_all p:integer l:"Total Incidents" d:"Count of all incidents to which ATCEMS responded." t:dataTypeName=number

metric m:count_incidents_coa p:integer l:"Austin Incidents" d:"Count of all incidents to which ATCEMS responded in the City of Austin." t:dataTypeName=number

metric m:count_incidents_tc p:integer l:"Travis County Incidents" d:"Count of all incidents to which ATCEMS responded in Travis County." t:dataTypeName=number

metric m:count_incidents_other p:integer l:"Other Area Incidents" d:"Count of all incidents to which ATCEMS responded outside the department service area." t:dataTypeName=number

metric m:count_incidents_coa_or_tc p:integer l:"Combined Austin and Travis County Incidents" d:"Count of all incidents to which ATCEMS responded in the City of Austin and Travis County outside the City of Austin, combined." t:dataTypeName=number

metric m:count_incidents_coa_p1 p:integer l:"Austin P1 Incidents" d:"Count of Priority 1 incidents to which ATCEMS responded in the City of Austin." t:dataTypeName=number

metric m:count_incidents_coa_p2 p:integer l:"Austin P2 Incidents" d:"Count of Priority 2 incidents to which ATCEMS responded in the City of Austin" t:dataTypeName=number

metric m:count_incidents_coa_p3 p:integer l:"Austin P3 Incidents" d:"Count of Priority 3 incidents to which ATCEMS responded in the City of Austin." t:dataTypeName=number

metric m:count_incidents_coa_p4 p:integer l:"Austin P4 Incidents" d:"Count of Priority 4 incidents to which ATCEMS responded in the City of Austin" t:dataTypeName=number

metric m:count_incidents_coa_p5 p:integer l:"Austin P5 Incidents" d:"Count of Priority 5 incidents to which ATCEMS responded in the City of Austin." t:dataTypeName=number

metric m:count_incidents_tc_p1 p:integer l:"Travis County P1 Incidents" d:"Count of Priority 1 incidents to which ATCEMS responded in Travis County." t:dataTypeName=number

metric m:count_incidents_tc_p2 p:integer l:"Travis County P2 Incidents" d:"Count of Priority 2 incidents to which ATCEMS responded in Travis County." t:dataTypeName=number

metric m:count_incidents_tc_p3 p:integer l:"Travis County P3 Incidents" d:"Count of Priority 3 incidents to which ATCEMS responded in Travis County." t:dataTypeName=number

metric m:count_incidents_tc_p4 p:integer l:"Travis County P4 Incidents" d:"Count of Priority 4 incidents to which ATCEMS responded in Travis County." t:dataTypeName=number

metric m:count_incidents_tc_p5 p:integer l:"Travis County P5 Incidents" d:"Count of Priority 5 incidents to which ATCEMS responded in Travis County." t:dataTypeName=number

metric m:percent_on_time_all p:float l:"Overall On-Time Compliance" d:"Percent of incidents for which ATCEMS met or exceeded response time goals." t:dataTypeName=percent

metric m:percent_on_time_coa p:float l:"Austin On-Time Compliance" d:"Percent of incidents for which ATCEMS met or exceeded response time goals in the City of Austin." t:dataTypeName=percent

metric m:percent_on_time_tc p:float l:"Travis County On-Time Compliance" d:"Percent of incidents for which ATCEMS met or exceeded response time goals in Travis County." t:dataTypeName=percent

metric m:percent_on_time_coa_p1 p:float l:"Austin P1 On-Time Compliance" d:"Percent of incidents for which ATCEMS met or exceeded response time goals for Priority 1 incidents within the City of Austin." t:dataTypeName=percent

metric m:percent_on_time_coa_p2 p:float l:"Austin P2 On-Time Compliance" d:"Percent of incidents for which ATCEMS met or exceeded response time goals for Priority 2 incidents within the City of Austin." t:dataTypeName=percent

metric m:percent_on_time_coa_p3 p:float l:"Austin P3 On-Time Compliance" d:"Percent of incidents for which ATCEMS met or exceeded response time goals for Priority 3 incidents within the City of Austin." t:dataTypeName=percent

metric m:percent_on_time_coa_p4 p:float l:"Austin P4 On-Time Compliance" d:"Percent of incidents for which ATCEMS met or exceeded response time goals for Priority 4 incidents within the City of Austin." t:dataTypeName=percent

metric m:percent_on_time_coa_p5 p:float l:"Austin P5 On-Time Compliance" d:"Percent of incidents for which ATCEMS met or exceeded response time goals for Priority 5 incidents within the City of Austin." t:dataTypeName=percent

metric m:percent_on_time_tc_p1 p:float l:"Travis County P1 On-Time Compliance" d:"Percent of incidents for which ATCEMS met or exceeded response time goals for Priority 1 incidents within Travis County outside the City of Austin." t:dataTypeName=percent

metric m:percent_on_time_tc_p2 p:float l:"Travis County P2 On-Time Compliance" d:"Percent of incidents for which ATCEMS met or exceeded response time goals for Priority 2 incidents within Travis County outside the City of Austin." t:dataTypeName=percent

metric m:percent_on_time_tc_p3 p:float l:"Travis County P3 On-Time Compliance" d:"Percent of incidents for which ATCEMS met or exceeded response time goals for Priority 3 incidents within Travis County outside the City of Austin." t:dataTypeName=percent

metric m:percent_on_time_tc_p4 p:float l:"Travis County P4 On-Time Compliance" d:"Percent of incidents for which ATCEMS met or exceeded response time goals for Priority 4 incidents within Travis County outside the City of Austin." t:dataTypeName=percent

metric m:percent_on_time_tc_p5 p:float l:"Travis County P5 On-Time Compliance" d:"Percent of incidents for which ATCEMS met or exceeded response time goals for Priority 5 incidents within Travis County outside the City of Austin." t:dataTypeName=percent

metric m:percent_on_time_target p:integer l:"Target On-Time Compliance" d:"On-time performance target for the month" t:dataTypeName=percent

entity e:gjtj-jt2d l:"EMS - Incidents by Month" t:attribution="Austin-Travis County EMS" t:url=https://data.austintexas.gov/api/views/gjtj-jt2d

property e:gjtj-jt2d t:meta.view v:id=gjtj-jt2d v:category="Public Safety" v:attributionLink=http://www.austintexas.gov/department/ems v:averageRating=0 v:name="EMS - Incidents by Month" v:attribution="Austin-Travis County EMS"

property e:gjtj-jt2d t:meta.view.owner v:id=4zcf-8die v:profileImageUrlMedium=/api/users/4zcf-8die/profile_images/THUMB v:profileImageUrlLarge=/api/users/4zcf-8die/profile_images/LARGE v:screenName="Austin-Travis County EMS" v:profileImageUrlSmall=/api/users/4zcf-8die/profile_images/TINY v:displayName="Austin-Travis County EMS"

property e:gjtj-jt2d t:meta.view.tableauthor v:id=4zcf-8die v:profileImageUrlMedium=/api/users/4zcf-8die/profile_images/THUMB v:profileImageUrlLarge=/api/users/4zcf-8die/profile_images/LARGE v:screenName="Austin-Travis County EMS" v:profileImageUrlSmall=/api/users/4zcf-8die/profile_images/TINY v:roleName=publisher_stories v:displayName="Austin-Travis County EMS"
```

## Top Records

```ls
| month_key | month_start_date    | count_incidents_all | count_incidents_coa | count_incidents_tc | count_incidents_other | count_incidents_coa_or_tc | count_incidents_coa_p1 | count_incidents_coa_p2 | count_incidents_coa_p3 | count_incidents_coa_p4 | count_incidents_coa_p5 | count_incidents_tc_p1 | count_incidents_tc_p2 | count_incidents_tc_p3 | count_incidents_tc_p4 | count_incidents_tc_p5 | percent_on_time_all | percent_on_time_coa | percent_on_time_tc | percent_on_time_coa_p1 | percent_on_time_coa_p2 | percent_on_time_coa_p3 | percent_on_time_coa_p4 | percent_on_time_coa_p5 | percent_on_time_tc_p1 | percent_on_time_tc_p2 | percent_on_time_tc_p3 | percent_on_time_tc_p4 | percent_on_time_tc_p5 | percent_on_time_target | 
| ========= | =================== | =================== | =================== | ================== | ===================== | ========================= | ====================== | ====================== | ====================== | ====================== | ====================== | ===================== | ===================== | ===================== | ===================== | ===================== | =================== | =================== | ================== | ====================== | ====================== | ====================== | ====================== | ====================== | ===================== | ===================== | ===================== | ===================== | ===================== | ====================== | 
| 201010    | 2010-10-01T00:00:00 | 8910                | 7571                | 1321               | 18                    | 8892                      | 533                    | 2103                   | 1039                   | 2938                   | 958                    | 81                    | 380                   | 199                   | 498                   | 163                   | 95.769600           | 97.317600           | 86.420900          | 94.154400              | 96.779300              | 99.260800              | 98.823500              | 94.572700              | 79.729700             | 77.218900             | 89.772700             | 95.666600             | 88.111800             | 90                     | 
| 201011    | 2010-11-01T00:00:00 | 7826                | 6564                | 1232               | 30                    | 7796                      | 401                    | 1896                   | 931                    | 2540                   | 796                    | 83                    | 346                   | 165                   | 473                   | 165                   | 96.006800           | 97.227800           | 89.400000          | 92.997100              | 96.728900              | 98.942400              | 98.427800              | 95.492900              | 80.769200             | 82.965200             | 89.102500             | 96.753200             | 92.907800             | 90                     | 
| 201012    | 2010-12-01T00:00:00 | 8182                | 6858                | 1290               | 34                    | 8148                      | 458                    | 1892                   | 903                    | 2655                   | 950                    | 97                    | 363                   | 177                   | 501                   | 152                   | 95.449700           | 96.877200           | 87.585500          | 93.154000              | 96.633700              | 98.669800              | 98.243600              | 94.502900              | 75.280800             | 81.845200             | 86.335400             | 96.039600             | 92.537300             | 90                     | 
| 201101    | 2011-01-01T00:00:00 | 8287                | 7081                | 1185               | 21                    | 8266                      | 466                    | 2017                   | 1025                   | 2573                   | 1000                   | 77                    | 336                   | 184                   | 450                   | 138                   | 95.921800           | 97.134200           | 88.357500          | 95.402200              | 96.340100              | 97.987200              | 98.817200              | 95.248600              | 66.666600             | 86.816700             | 90.797500             | 94.425000             | 88.095200             | 90                     | 
| 201102    | 2011-02-01T00:00:00 | 8241                | 6969                | 1255               | 17                    | 8224                      | 426                    | 2058                   | 982                    | 2520                   | 983                    | 79                    | 382                   | 198                   | 429                   | 167                   | 94.516900           | 96.139300           | 84.994900          | 92.207700              | 96.184800              | 97.777700              | 97.969500              | 92.519200              | 64.383500             | 81.065000             | 85.310700             | 93.750000             | 88.590600             | 90                     | 
| 201103    | 2011-03-01T00:00:00 | 8764                | 7449                | 1302               | 13                    | 8751                      | 514                    | 2091                   | 1056                   | 2832                   | 956                    | 82                    | 358                   | 216                   | 489                   | 157                   | 95.457600           | 96.511600           | 89.248300          | 93.640300              | 96.920600              | 97.684200              | 98.073900              | 92.419100              | 78.666600             | 85.758500             | 89.898900             | 95.161200             | 88.965500             | 90                     | 
| 201104    | 2011-04-01T00:00:00 | 8848                | 7506                | 1319               | 23                    | 8825                      | 475                    | 2219                   | 1064                   | 2790                   | 958                    | 84                    | 389                   | 197                   | 498                   | 151                   | 95.787400           | 97.465200           | 86.074700          | 94.348800              | 97.230600              | 98.543100              | 98.919100              | 95.094700              | 71.232800             | 79.083000             | 90.960400             | 92.401200             | 90.140800             | 90                     | 
| 201105    | 2011-05-01T00:00:00 | 9166                | 7704                | 1432               | 30                    | 9136                      | 534                    | 2294                   | 1059                   | 2869                   | 948                    | 115                   | 407                   | 205                   | 527                   | 178                   | 95.838300           | 97.369200           | 87.174800          | 93.073500              | 97.169300              | 98.111200              | 98.524900              | 96.704500              | 71.428500             | 83.098500             | 89.673900             | 94.801200             | 87.417200             | 90                     | 
| 201106    | 2011-06-01T00:00:00 | 9102                | 7743                | 1339               | 20                    | 9082                      | 530                    | 2258                   | 1078                   | 2849                   | 1028                   | 82                    | 407                   | 200                   | 467                   | 183                   | 95.698200           | 97.089200           | 87.406700          | 92.672400              | 96.809000              | 97.946600              | 98.258100              | 96.573200              | 74.647800             | 83.149100             | 88.636300             | 94.822000             | 87.012900             | 90                     | 
| 201107    | 2011-07-01T00:00:00 | 9121                | 7762                | 1349               | 10                    | 9111                      | 561                    | 2295                   | 1084                   | 2801                   | 1021                   | 111                   | 406                   | 183                   | 485                   | 164                   | 95.330800           | 96.786700           | 86.728100          | 92.638000              | 96.404200              | 98.057200              | 98.650000              | 94.687500              | 71.578900             | 80.939200             | 87.272700             | 94.285700             | 93.918900             | 90                     | 
```