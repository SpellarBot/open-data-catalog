# Performance Metrics - Transportation - Pavement Cave-ins

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/performance-metrics-transportation-pavement-cave-ins-a4f5b) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/euee-qccq) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/euee-qccq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/euee-qccq/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | euee-qccq |
| Name | Performance Metrics - Transportation - Pavement Cave-ins |
| Attribution | City of Chicago |
| Category | Administration & Finance |
| Tags | performance metrics, service delivery |
| Created | 2011-09-22T22:10:01Z |
| Publication Date | 2014-04-29T03:01:47Z |

## Description

As underground drainage systems age, occasionally failures in the pipes and joints can cause pavement cave-ins.  The Department of Transportation (CDOT) responds to pavement cave-ins reported through 311’s Customer Service Requests (CSR) system on a case-by-case basis.  This metric tracks the average number of days CDOT takes to complete pavement cave-in repairs per week.  The target response time for pavement cave-ins is within 3 days.

## Columns

```ls
| Included | Schema Type    | Field Name                                         | Name                                               | Data Type | Render Type |
| ======== | ============== | ================================================== | ================================================== | ========= | =========== |
| Yes      | time           | week                                               | Week                                               | text      | text        |
| Yes      | numeric metric | average_days_to_complete_pavement_cave_in_requests | Average Days to Complete Pavement Cave-in Requests | number    | number      |
| Yes      | numeric metric | total_completed_requests                           | Total Completed Requests                           | number    | number      |
| Yes      | numeric metric | target_response_time_days_                         | Target Response Time (Days)                        | number    | number      |
```

## Time Field

```ls
Value = week
Format & Zone = ww,yyyy
```

## Data Commands

```ls
series e:euee-qccq d:2011-03-28T00:00:00.000Z m:total_completed_requests=45 m:target_response_time_days_=3 m:average_days_to_complete_pavement_cave_in_requests=1.05

series e:euee-qccq d:2011-04-04T00:00:00.000Z m:total_completed_requests=138 m:target_response_time_days_=3 m:average_days_to_complete_pavement_cave_in_requests=1.36

series e:euee-qccq d:2011-04-11T00:00:00.000Z m:total_completed_requests=139 m:target_response_time_days_=3 m:average_days_to_complete_pavement_cave_in_requests=1.61
```

## Meta Commands

```ls
metric m:average_days_to_complete_pavement_cave_in_requests p:float l:"Average Days to Complete Pavement Cave-in Requests" t:dataTypeName=number

metric m:total_completed_requests p:integer l:"Total Completed Requests" t:dataTypeName=number

metric m:target_response_time_days_ p:integer l:"Target Response Time (Days)" t:dataTypeName=number

entity e:euee-qccq l:"Performance Metrics - Transportation - Pavement Cave-ins" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/euee-qccq

property e:euee-qccq t:meta.view d:2017-09-25T07:23:05.645Z v:averageRating=0 v:name="Performance Metrics - Transportation - Pavement Cave-ins" v:attribution="City of Chicago" v:attributionLink=http://www.cityofchicago.org v:id=euee-qccq v:category="Administration & Finance"

property e:euee-qccq t:meta.view.owner d:2017-09-25T07:23:05.645Z v:displayName="Elizabeth Scott" v:id=zzya-y4bn v:screenName="Elizabeth Scott"

property e:euee-qccq t:meta.view.tableauthor d:2017-09-25T07:23:05.645Z v:displayName="Elizabeth Scott" v:id=zzya-y4bn v:screenName="Elizabeth Scott"
```

## Top Records

```ls
| week                   | average_days_to_complete_pavement_cave_in_requests | total_completed_requests | target_response_time_days_ | 
| ====================== | ================================================== | ======================== | ========================== | 
| March 28-April 3, 2011 | 1.05                                               | 45                       | 3                          | 
| April 4 - 10, 2011     | 1.36                                               | 138                      | 3                          | 
| April 11-17, 2011      | 1.61                                               | 139                      | 3                          | 
| April 18-24, 2011      | 1.43                                               | 148                      | 3                          | 
| April 25-May 1, 2011   | 1.68                                               | 179                      | 3                          | 
| May 2-8, 2011          | 1.31                                               | 163                      | 3                          | 
| May 9-15, 2011         | 1.39                                               | 175                      | 3                          | 
| May 16-22, 2011        | 1.31                                               | 174                      | 3                          | 
| May 23-29, 2011        | 2.81                                               | 126                      | 3                          | 
| May 30-June 5, 2011    | 1.47                                               | 179                      | 3                          | 
```