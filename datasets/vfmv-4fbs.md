# Performance Metrics - Transportation - Traffic Lights Out

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/performance-metrics-transportation-traffic-lights-out-6b4a7) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/vfmv-4fbs) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/vfmv-4fbs/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/vfmv-4fbs/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | vfmv-4fbs |
| Name | Performance Metrics - Transportation - Traffic Lights Out |
| Attribution | City of Chicago |
| Category | Administration & Finance |
| Tags | performance metrics, service delivery, traffic light, outage |
| Created | 2011-09-26T15:17:20Z |
| Publication Date | 2014-05-01T03:13:04Z |

## Description

The Chicago Department of Transportation (CDOT) receives reports from 311?s Customer Service Requests (CSR) system of traffic light outages.  This metric tracks the average number of days CDOT takes to complete traffic light repair requests.  Total number of requests fulfilled per week is also available by mousing over columns Due to the public safety importance of traffic signals, the target time to respond to traffic light outages is within 1 day.

## Columns

```ls
| Included | Schema Type    | Field Name                                          | Name                                                | Data Type | Render Type |
| ======== | ============== | =================================================== | =================================================== | ========= | =========== |
| Yes      | time           | week                                                | week                                                | text      | text        |
| Yes      | numeric metric | average_days_to_complete_traffic_light_out_requests | Average Days to Complete Traffic Light Out Requests | number    | number      |
| Yes      | numeric metric | total_completed_requests                            | Total Completed Requests                            | number    | number      |
| Yes      | numeric metric | target_response_time_days_                          | Target Response Time (Days)                         | number    | number      |
```

## Time Field

```ls
Value = week
Format & Zone = ww,yyyy
```

## Data Commands

```ls
series e:vfmv-4fbs d:2011-03-28T00:00:00.000Z m:total_completed_requests=84 m:target_response_time_days_=1 m:average_days_to_complete_traffic_light_out_requests=1.11

series e:vfmv-4fbs d:2011-04-04T00:00:00.000Z m:total_completed_requests=266 m:target_response_time_days_=1 m:average_days_to_complete_traffic_light_out_requests=1.13

series e:vfmv-4fbs d:2011-04-11T00:00:00.000Z m:total_completed_requests=274 m:target_response_time_days_=1 m:average_days_to_complete_traffic_light_out_requests=1.13
```

## Meta Commands

```ls
metric m:average_days_to_complete_traffic_light_out_requests p:float l:"Average Days to Complete Traffic Light Out Requests" t:dataTypeName=number

metric m:total_completed_requests p:integer l:"Total Completed Requests" t:dataTypeName=number

metric m:target_response_time_days_ p:integer l:"Target Response Time (Days)" t:dataTypeName=number

entity e:vfmv-4fbs l:"Performance Metrics - Transportation - Traffic Lights Out" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/vfmv-4fbs

property e:vfmv-4fbs t:meta.view v:id=vfmv-4fbs v:category="Administration & Finance" v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Performance Metrics - Transportation - Traffic Lights Out" v:attribution="City of Chicago"

property e:vfmv-4fbs t:meta.view.owner v:id=zzya-y4bn v:screenName="Elizabeth Scott" v:displayName="Elizabeth Scott"

property e:vfmv-4fbs t:meta.view.tableauthor v:id=zzya-y4bn v:screenName="Elizabeth Scott" v:displayName="Elizabeth Scott"
```

## Top Records

```ls
| week                   | average_days_to_complete_traffic_light_out_requests | total_completed_requests | target_response_time_days_ | 
| ====================== | =================================================== | ======================== | ========================== | 
| March 28-April 3, 2011 | 1.11                                                | 84                       | 1                          | 
| April 4 - 10, 2011     | 1.13                                                | 266                      | 1                          | 
| April 11-17, 2011      | 1.13                                                | 274                      | 1                          | 
| April 18-24, 2011      | 1.04                                                | 263                      | 1                          | 
| April 25-May 1, 2011   | 1.18                                                | 233                      | 1                          | 
| May 2-8, 2011          | 1.03                                                | 209                      | 1                          | 
| May 9-15, 2011         | 1.05                                                | 247                      | 1                          | 
| May 16-22, 2011        | 1.07                                                | 187                      | 1                          | 
| May 23-29, 2011        | 1.08                                                | 271                      | 1                          | 
| May 30-June 5, 2011    | 1.02                                                | 214                      | 1                          | 
```