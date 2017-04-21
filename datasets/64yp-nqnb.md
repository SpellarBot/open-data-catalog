# Performance Metrics - Streets & Sanitation - Sanitation Code Complaints

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/performance-metrics-streets-sanitation-sanitation-code-complaints-b05f0) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/64yp-nqnb) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/64yp-nqnb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/64yp-nqnb/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | 64yp-nqnb |
| Name | Performance Metrics - Streets & Sanitation - Sanitation Code Complaints |
| Attribution | City of Chicago |
| Category | Administration & Finance |
| Tags | performance metrics, service delivery, garbage, sanitation, complaints |
| Created | 2011-09-22T02:28:54Z |
| Publication Date | 2012-07-26T20:51:58Z |

## Description

The Department of Streets and Sanitation (DSS) investigates and remedies reported violations of Chicago?s sanitation code. Residents may request service for violations such as overflowing dumpsters and garbage in the alley. This metric tracks the average number of days the DSS takes to complete sanitation code violation requests per week. Median days to complete requests as well as total number of requests fulfilled per week are available by mousing over columns. Currently the performance target for completing sanitation code violation requests is 3 days. For more information on sanitation code complaints, see https://data.cityofchicago.org/d/me59-5fac

## Columns

```ls
| Included | Schema Type    | Field Name                                                 | Name                                                       | Data Type | Render Type |
| ======== | ============== | ========================================================== | ========================================================== | ========= | =========== |
| Yes      | time           | week                                                       | Week                                                       | text      | text        |
| Yes      | numeric metric | average_days_to_complete_sanitation_code_requests          | Average Days to Complete Sanitation Code Requests          | number    | number      |
| Yes      | numeric metric | total_completed_requests                                   | Total Completed Requests                                   | number    | number      |
| Yes      | numeric metric | median_days_to_repond_to_sanitation_code_complaint_request | Median Days to Repond to Sanitation Code Complaint Request | number    | number      |
| Yes      | numeric metric | target_response_time_days_                                 | Target Response Time (Days)                                | number    | number      |
```

## Time Field

```ls
Value = week
Format & Zone = ww,yyyy
```

## Data Commands

```ls
series e:64yp-nqnb d:2011-04-03T00:00:00.000Z m:median_days_to_repond_to_sanitation_code_complaint_request=2 m:total_completed_requests=379 m:target_response_time_days_=3 m:average_days_to_complete_sanitation_code_requests=2.9

series e:64yp-nqnb d:2011-04-10T00:00:00.000Z m:median_days_to_repond_to_sanitation_code_complaint_request=2 m:total_completed_requests=360 m:target_response_time_days_=3 m:average_days_to_complete_sanitation_code_requests=2.9

series e:64yp-nqnb d:2011-04-17T00:00:00.000Z m:median_days_to_repond_to_sanitation_code_complaint_request=2 m:total_completed_requests=282 m:target_response_time_days_=3 m:average_days_to_complete_sanitation_code_requests=3
```

## Meta Commands

```ls
metric m:average_days_to_complete_sanitation_code_requests p:float l:"Average Days to Complete Sanitation Code Requests" t:dataTypeName=number

metric m:total_completed_requests p:integer l:"Total Completed Requests" t:dataTypeName=number

metric m:median_days_to_repond_to_sanitation_code_complaint_request p:integer l:"Median Days to Repond to Sanitation Code Complaint Request" t:dataTypeName=number

metric m:target_response_time_days_ p:integer l:"Target Response Time (Days)" t:dataTypeName=number

entity e:64yp-nqnb l:"Performance Metrics - Streets & Sanitation - Sanitation Code Complaints" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/64yp-nqnb

property e:64yp-nqnb t:meta.view v:id=64yp-nqnb v:category="Administration & Finance" v:attributionLink=http://www.cityofchicago.org/performance v:averageRating=0 v:name="Performance Metrics - Streets & Sanitation - Sanitation Code Complaints" v:attribution="City of Chicago"

property e:64yp-nqnb t:meta.view.owner v:id=vi9p-p863 v:screenName="Eric Phillips" v:displayName="Eric Phillips"

property e:64yp-nqnb t:meta.view.tableauthor v:id=vi9p-p863 v:screenName="Eric Phillips" v:displayName="Eric Phillips"
```

## Top Records

```ls
| week               | average_days_to_complete_sanitation_code_requests | total_completed_requests | median_days_to_repond_to_sanitation_code_complaint_request | target_response_time_days_ | 
| ================== | ================================================= | ======================== | ========================================================== | ========================== | 
| Apr 3-9, 2011      | 2.9                                               | 379                      | 2                                                          | 3                          | 
| Apr 10-16, 2011    | 2.9                                               | 360                      | 2                                                          | 3                          | 
| Apr 17-23, 2011    | 3                                                 | 282                      | 2                                                          | 3                          | 
| Apr 24-30, 2011    | 2.7                                               | 314                      | 1                                                          | 3                          | 
| May 1-7, 2011      | 3.1                                               | 329                      | 2                                                          | 3                          | 
| May 6-14, 2011     | 2.5                                               | 372                      | 1                                                          | 3                          | 
| May 15-21, 2011    | 2.8                                               | 380                      | 2                                                          | 3                          | 
| May 22-28,2011     | 3.1                                               | 470                      | 2                                                          | 3                          | 
| May 29-Jun 4, 2011 | 3.1                                               | 412                      | 1                                                          | 3                          | 
| June 5-11, 2011    | 4.5                                               | 477                      | 2                                                          | 3                          | 
```