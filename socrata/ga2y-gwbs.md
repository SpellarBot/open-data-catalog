# Performance Metrics - Streets & Sanitation - Rodent Baiting

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/performance-metrics-streets-sanitation-rodent-baiting-7e648) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/ga2y-gwbs) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/ga2y-gwbs/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/ga2y-gwbs/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | ga2y-gwbs |
| Name | Performance Metrics - Streets & Sanitation - Rodent Baiting |
| Attribution | City of Chicago |
| Category | Administration & Finance |
| Tags | performance metrics, service delivery, rodents, rats |
| Created | 2011-09-22T01:48:19Z |
| Publication Date | 2012-07-13T21:21:29Z |

## Description

In addition to performing regular scheduled preventative rodent control, the Department of Streets & Sanitation (DSS) responds to site-specific customer rat complaints logged through 311?s Customer Service Requests (CSR) system. This metric tracks the average number of days the DSS takes to complete rodent baiting requests per week. Median days to complete requests as well as total number of requests fulfilled per week are available by mousing over columns. The target response time for rodent baiting requests is within 7 days. For more information on open rat complaints, see https://data.cityofchicago.org/Government/311-Service-Requests-Rodent-Baiting-2011-/97t6-zrhs

## Columns

```ls
| Included | Schema Type    | Field Name                                                     | Name                                                             | Data Type | Render Type |
| ======== | ============== | ============================================================== | ================================================================ | ========= | =========== |
| Yes      | time           | week                                                           | Week                                                             | text      | text        |
| Yes      | numeric metric | average_days_to_complete_rodent_baiting_rat_complaint_requests | Average Days to Complete Rodent Baiting / Rat Complaint Requests | number    | number      |
| Yes      | numeric metric | median_days_to_repond_to_rodent_baiting_request                | Median Days to Repond to Rodent Baiting Request                  | number    | number      |
| Yes      | numeric metric | target_response_time_days_                                     | Target Response Time (Days)                                      | number    | number      |
```

## Time Field

```ls
Value = week
Format & Zone = ww,yyyy
```

## Data Commands

```ls
series e:ga2y-gwbs d:2011-06-06T00:00:00.000Z m:median_days_to_repond_to_rodent_baiting_request=8 m:average_days_to_complete_rodent_baiting_rat_complaint_requests=8 m:target_response_time_days_=7

series e:ga2y-gwbs d:2011-06-13T00:00:00.000Z m:median_days_to_repond_to_rodent_baiting_request=10 m:average_days_to_complete_rodent_baiting_rat_complaint_requests=9.9 m:target_response_time_days_=7

series e:ga2y-gwbs d:2011-06-20T00:00:00.000Z m:median_days_to_repond_to_rodent_baiting_request=12 m:average_days_to_complete_rodent_baiting_rat_complaint_requests=14.3 m:target_response_time_days_=7
```

## Meta Commands

```ls
metric m:average_days_to_complete_rodent_baiting_rat_complaint_requests p:float l:"Average Days to Complete Rodent Baiting / Rat Complaint Requests" t:dataTypeName=number

metric m:median_days_to_repond_to_rodent_baiting_request p:integer l:"Median Days to Repond to Rodent Baiting Request" t:dataTypeName=number

metric m:target_response_time_days_ p:integer l:"Target Response Time (Days)" t:dataTypeName=number

entity e:ga2y-gwbs l:"Performance Metrics - Streets & Sanitation - Rodent Baiting" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/ga2y-gwbs

property e:ga2y-gwbs t:meta.view v:id=ga2y-gwbs v:category="Administration & Finance" v:attributionLink=http://www.cityofchicago.org/performance v:averageRating=0 v:name="Performance Metrics - Streets & Sanitation - Rodent Baiting" v:attribution="City of Chicago"

property e:ga2y-gwbs t:meta.view.owner v:id=vi9p-p863 v:screenName="Eric Phillips" v:displayName="Eric Phillips"

property e:ga2y-gwbs t:meta.view.tableauthor v:id=vi9p-p863 v:screenName="Eric Phillips" v:displayName="Eric Phillips"
```

## Top Records

```ls
| week                 | average_days_to_complete_rodent_baiting_rat_complaint_requests | median_days_to_repond_to_rodent_baiting_request | target_response_time_days_ | 
| ==================== | ============================================================== | =============================================== | ========================== | 
| June 6-12, 2011      | 8                                                              | 8                                               | 7                          | 
| June 13-19, 2011     | 9.9                                                            | 10                                              | 7                          | 
| June 20-26, 2011     | 14.3                                                           | 12                                              | 7                          | 
| June 27-July 3,2011  | 12.7                                                           | 13                                              | 7                          | 
| July 4 - 10, 2011    | 15.2                                                           | 16                                              | 7                          | 
| July 11 - 17, 2011   | 15.8                                                           | 16                                              | 7                          | 
| July 25 - 31, 2011   | 17.6                                                           | 18                                              | 7                          | 
| August 1 - 7, 2011   | 20.7                                                           | 21                                              | 7                          | 
| August 8 - 14, 2011  | 24.3                                                           | 26                                              | 7                          | 
| August 15 - 21, 2011 | 26.2                                                           | 27                                              | 7                          | 
```