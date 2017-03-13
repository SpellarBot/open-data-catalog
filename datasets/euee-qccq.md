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
| Rows Updated | 2014-04-29T02:53:31Z |

## Description

As underground drainage systems age, occasionally failures in the pipes and joints can cause pavement cave-ins.  The Department of Transportation (CDOT) responds to pavement cave-ins reported through 311?s Customer Service Requests (CSR) system on a case-by-case basis.  This metric tracks the average number of days CDOT takes to complete pavement cave-in repairs per week.  The target response time for pavement cave-ins is within 3 days.

## Columns

```ls
| Included | Schema Type    | Field Name                                         | Name                                               | Data Type | Render Type |
| ======== | ============== | ================================================== | ================================================== | ========= | =========== |
| No       | time           | :updated_at                                        | updated_at                                         | meta_data | meta_data   |
| Yes      | series tag     | week                                               | Week                                               | text      | text        |
| Yes      | numeric metric | average_days_to_complete_pavement_cave_in_requests | Average Days to Complete Pavement Cave-in Requests | number    | number      |
| Yes      | numeric metric | total_completed_requests                           | Total Completed Requests                           | number    | number      |
| Yes      | numeric metric | target_response_time_days_                         | Target Response Time (Days)                        | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:euee-qccq d:2013-12-08T22:59:26.000Z t:week="March 28-April 3, 2011" m:total_completed_requests=45 m:target_response_time_days_=3 m:average_days_to_complete_pavement_cave_in_requests=1.05

series e:euee-qccq d:2013-12-08T22:59:26.000Z t:week="April 4 - 10, 2011" m:total_completed_requests=138 m:target_response_time_days_=3 m:average_days_to_complete_pavement_cave_in_requests=1.36

series e:euee-qccq d:2013-12-08T22:59:26.000Z t:week="April 11-17, 2011" m:total_completed_requests=139 m:target_response_time_days_=3 m:average_days_to_complete_pavement_cave_in_requests=1.61
```

## Meta Commands

```ls
metric m:average_days_to_complete_pavement_cave_in_requests l:"Average Days to Complete Pavement Cave-in Requests" t:dataTypeName=number

metric m:total_completed_requests p:integer l:"Total Completed Requests" t:dataTypeName=number

metric m:target_response_time_days_ p:integer l:"Target Response Time (Days)" t:dataTypeName=number

entity e:euee-qccq l:"Performance Metrics - Transportation - Pavement Cave-ins" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/euee-qccq

property e:euee-qccq t:meta.view v:id=euee-qccq v:category="Administration & Finance" v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Performance Metrics - Transportation - Pavement Cave-ins" v:attribution="City of Chicago"

property e:euee-qccq t:meta.view.owner v:id=zzya-y4bn v:screenName="Elizabeth Scott" v:displayName="Elizabeth Scott"

property e:euee-qccq t:meta.view.tableauthor v:id=zzya-y4bn v:screenName="Elizabeth Scott" v:displayName="Elizabeth Scott"
```