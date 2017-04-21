# Performance Metrics - Transportation - Stop Sign Out

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/performance-metrics-transportation-stop-sign-out-60880) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/hybd-quwr) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/hybd-quwr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/hybd-quwr/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | hybd-quwr |
| Name | Performance Metrics - Transportation - Stop Sign Out |
| Attribution | City of Chicago |
| Category | Administration & Finance |
| Tags | performance metrics, signs, service delivery |
| Created | 2011-09-26T15:19:43Z |
| Publication Date | 2014-05-01T03:17:58Z |

## Description

Due to vehicular accidents, theft and normal wear and tear, City stop signs occasionally need to be replaced or repaired.  The Department of Transportation (CDOT) responds to damaged or missing stop signs reported through 311?s Customer Service Requests (CSR) system on a case-by-case basis.  Total number of requests fulfilled per week is also available by mousing over columns.  Due to the public safety importance of stop signs, the target time to respond to stop sign requests is within 1 day.  To report a missing or damaged stop sign, call 311 or see http://www.cityofchicago.org/city/en/depts/cdot/provdrs/signs_and_pavementmarkings/svcs/stop_sign.html

## Columns

```ls
| Included | Schema Type    | Field Name                                      | Name                                            | Data Type | Render Type |
| ======== | ============== | =============================================== | =============================================== | ========= | =========== |
| Yes      | time           | week                                            | week                                            | text      | text        |
| Yes      | numeric metric | average_days_to_complete_stop_sign_out_requests | Average Days to Complete Stop Sign Out Requests | number    | number      |
| Yes      | numeric metric | total_completed_requests                        | Total Completed Requests                        | number    | number      |
| Yes      | numeric metric | target_response_time_days_                      | Target Response Time (Days)                     | number    | number      |
```

## Time Field

```ls
Value = week
Format & Zone = ww,yyyy
```

## Data Commands

```ls
series e:hybd-quwr d:2011-03-28T00:00:00.000Z m:average_days_to_complete_stop_sign_out_requests=1 m:total_completed_requests=27 m:target_response_time_days_=1

series e:hybd-quwr d:2011-04-04T00:00:00.000Z m:average_days_to_complete_stop_sign_out_requests=1 m:total_completed_requests=87 m:target_response_time_days_=1

series e:hybd-quwr d:2011-04-11T00:00:00.000Z m:average_days_to_complete_stop_sign_out_requests=1 m:total_completed_requests=88 m:target_response_time_days_=1
```

## Meta Commands

```ls
metric m:average_days_to_complete_stop_sign_out_requests p:double l:"Average Days to Complete Stop Sign Out Requests" t:dataTypeName=number

metric m:total_completed_requests p:integer l:"Total Completed Requests" t:dataTypeName=number

metric m:target_response_time_days_ p:integer l:"Target Response Time (Days)" t:dataTypeName=number

entity e:hybd-quwr l:"Performance Metrics - Transportation - Stop Sign Out" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/hybd-quwr

property e:hybd-quwr t:meta.view v:id=hybd-quwr v:category="Administration & Finance" v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Performance Metrics - Transportation - Stop Sign Out" v:attribution="City of Chicago"

property e:hybd-quwr t:meta.view.owner v:id=zzya-y4bn v:screenName="Elizabeth Scott" v:displayName="Elizabeth Scott"

property e:hybd-quwr t:meta.view.tableauthor v:id=zzya-y4bn v:screenName="Elizabeth Scott" v:displayName="Elizabeth Scott"
```

## Top Records

```ls
| week                   | average_days_to_complete_stop_sign_out_requests | total_completed_requests | target_response_time_days_ | 
| ====================== | =============================================== | ======================== | ========================== | 
| March 28-April 3, 2011 | 1                                               | 27                       | 1                          | 
| April 4 - 10, 2011     | 1                                               | 87                       | 1                          | 
| April 11-17, 2011      | 1                                               | 88                       | 1                          | 
| April 18-24, 2011      | 1                                               | 81                       | 1                          | 
| April 25-May 1, 2011   | 1                                               | 100                      | 1                          | 
| May 2-8, 2011          | 1                                               | 82                       | 1                          | 
| May 9-15, 2011         | 1                                               | 79                       | 1                          | 
| May 16-22, 2011        | 1                                               | 93                       | 1                          | 
| May 23-29, 2011        | 1.04                                            | 76                       | 1                          | 
| May 30-June 5, 2011    | 1                                               | 70                       | 1                          | 
```