# Performance Metrics - Streets & Sanitation - Graffiti Removal

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/performance-metrics-streets-sanitation-graffiti-removal-b4d14) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/qcfn-tiw7) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/qcfn-tiw7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/qcfn-tiw7/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | qcfn-tiw7 |
| Name | Performance Metrics - Streets & Sanitation - Graffiti Removal |
| Attribution | City of Chicago |
| Category | Administration & Finance |
| Tags | performance metrics, service delivery, graffiti |
| Created | 2011-09-22T14:18:26Z |
| Publication Date | 2012-07-16T14:58:35Z |

## Description

The Department of Streets & Sanitation's (DSS) Graffiti Blasters crews offer a vandalism removal service to private property owners. This metric tracks the average number of days DSS takes to complete graffiti removal requests per week. Median days to complete requests as well as total number of requests fulfilled per week are available by mousing over columns. Currently the performance target for completing a graffiti removal request is 10 days. For more information on graffiti removal requests, see https://data.cityofchicago.org/d/hec5-y4x5

## Columns

```ls
| Included | Schema Type    | Field Name                                       | Name                                             | Data Type | Render Type |
| ======== | ============== | ================================================ | ================================================ | ========= | =========== |
| Yes      | time           | week                                             | Week                                             | text      | text        |
| Yes      | numeric metric | average_days_to_complete_graffiti_removal        | Average Days to Complete Graffiti Removal        | number    | number      |
| Yes      | numeric metric | total_completed_requests                         | Total Completed Requests                         | number    | number      |
| Yes      | numeric metric | median_days_to_complete_graffiti_removal_request | Median Days to Complete Graffiti Removal Request | number    | number      |
| Yes      | numeric metric | target_response_time_days_                       | Target Response Time (Days)                      | number    | number      |
```

## Time Field

```ls
Value = week
Format & Zone = ww,yyyy
```

## Data Commands

```ls
series e:qcfn-tiw7 d:2011-04-03T00:00:00.000Z m:average_days_to_complete_graffiti_removal=6.62 m:median_days_to_complete_graffiti_removal_request=2 m:total_completed_requests=2966 m:target_response_time_days_=10

series e:qcfn-tiw7 d:2011-04-10T00:00:00.000Z m:average_days_to_complete_graffiti_removal=4.95 m:median_days_to_complete_graffiti_removal_request=2 m:total_completed_requests=2722 m:target_response_time_days_=10

series e:qcfn-tiw7 d:2011-04-17T00:00:00.000Z m:average_days_to_complete_graffiti_removal=6.67 m:median_days_to_complete_graffiti_removal_request=2 m:total_completed_requests=2602 m:target_response_time_days_=10
```

## Meta Commands

```ls
metric m:average_days_to_complete_graffiti_removal p:float l:"Average Days to Complete Graffiti Removal" t:dataTypeName=number

metric m:total_completed_requests p:integer l:"Total Completed Requests" t:dataTypeName=number

metric m:median_days_to_complete_graffiti_removal_request p:integer l:"Median Days to Complete Graffiti Removal Request" t:dataTypeName=number

metric m:target_response_time_days_ p:integer l:"Target Response Time (Days)" t:dataTypeName=number

entity e:qcfn-tiw7 l:"Performance Metrics - Streets & Sanitation - Graffiti Removal" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/qcfn-tiw7

property e:qcfn-tiw7 t:meta.view v:id=qcfn-tiw7 v:category="Administration & Finance" v:attributionLink=http://www.cityofchicago.org/performance v:averageRating=0 v:name="Performance Metrics - Streets & Sanitation - Graffiti Removal" v:attribution="City of Chicago"

property e:qcfn-tiw7 t:meta.view.owner v:id=vi9p-p863 v:screenName="Eric Phillips" v:displayName="Eric Phillips"

property e:qcfn-tiw7 t:meta.view.tableauthor v:id=vi9p-p863 v:screenName="Eric Phillips" v:displayName="Eric Phillips"
```

## Top Records

```ls
| week                  | average_days_to_complete_graffiti_removal | total_completed_requests | median_days_to_complete_graffiti_removal_request | target_response_time_days_ | 
| ===================== | ========================================= | ======================== | ================================================ | ========================== | 
| April 3 - 9, 2011     | 6.62                                      | 2966                     | 2                                                | 10                         | 
| April 10 - 16, 2011   | 4.95                                      | 2722                     | 2                                                | 10                         | 
| April 17 - 23, 2011   | 6.67                                      | 2602                     | 2                                                | 10                         | 
| April 24 - 30, 2011   | 3.9                                       | 3201                     | 1                                                | 10                         | 
| May 1 - 7, 2011       | 3.76                                      | 2791                     | 2                                                | 10                         | 
| May 8 - 14, 2011      | 4.1                                       | 2860                     | 1                                                | 10                         | 
| May 15 - 21, 2011     | 3.28                                      | 2751                     | 1                                                | 10                         | 
| May 22 - 28, 2011     | 3.15                                      | 2839                     | 1                                                | 10                         | 
| May 29 - June 4, 2011 | 3.82                                      | 2087                     | 1                                                | 10                         | 
| June 5 - 11, 2011     | 3.69                                      | 2869                     | 1                                                | 10                         | 
```