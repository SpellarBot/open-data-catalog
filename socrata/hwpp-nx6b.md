# Performance Metrics - Streets & Sanitation - Tree Debris

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/performance-metrics-streets-sanitation-tree-debris-fea94) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/hwpp-nx6b) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/hwpp-nx6b/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/hwpp-nx6b/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | hwpp-nx6b |
| Name | Performance Metrics - Streets & Sanitation - Tree Debris |
| Attribution | City of Chicago |
| Category | Administration & Finance |
| Tags | performance metrics, service delivery, trees |
| Created | 2011-09-22T22:08:41Z |
| Publication Date | 2012-07-26T20:50:37Z |

## Description

After extreme weather events, the Bureau of Forestry Tree Emergency is deployed to remove plant debris blocking or cluttering the public way. This metric tracks the average number of days the Department of Streets and Sanitation (DSS) takes to complete tree debris removal requests per week. Median days to complete requests as well as total number of requests fulfilled per week are also available by mousing over columns. The Department of Streets & Sanitation responds to emergency tree debris removal requests logged by 311?s Customer Service Requests (CSR) system. The target response time for Tree Debris Removal is 1 day. For more information on open tree debris removal requests, see https://data.cityofchicago.org/d/mab8-y9h3

## Columns

```ls
| Included | Schema Type    | Field Name                                           | Name                                                 | Data Type | Render Type |
| ======== | ============== | ==================================================== | ==================================================== | ========= | =========== |
| Yes      | time           | week                                                 | Week                                                 | text      | text        |
| Yes      | numeric metric | average_days_to_complete_tree_debris_requests        | Average Days to Complete Tree Debris Requests        | number    | number      |
| Yes      | numeric metric | total_completed_requests                             | Total Completed Requests                             | number    | number      |
| Yes      | numeric metric | median_days_to_repond_to_tree_debris_removal_request | Median Days to Repond to Tree Debris Removal Request | number    | number      |
| Yes      | numeric metric | target_response_time_days_                           | Target Response Time (Days)                          | number    | number      |
```

## Time Field

```ls
Value = week
Format & Zone = ww,yyyy
```

## Data Commands

```ls
series e:hwpp-nx6b d:2011-06-06T00:00:00.000Z m:average_days_to_complete_tree_debris_requests=10.6 m:median_days_to_repond_to_tree_debris_removal_request=7 m:total_completed_requests=154 m:target_response_time_days_=5

series e:hwpp-nx6b d:2011-06-13T00:00:00.000Z m:average_days_to_complete_tree_debris_requests=10.5 m:median_days_to_repond_to_tree_debris_removal_request=7 m:total_completed_requests=864 m:target_response_time_days_=5

series e:hwpp-nx6b d:2011-06-20T00:00:00.000Z m:average_days_to_complete_tree_debris_requests=9 m:median_days_to_repond_to_tree_debris_removal_request=3 m:total_completed_requests=283 m:target_response_time_days_=5
```

## Meta Commands

```ls
metric m:average_days_to_complete_tree_debris_requests p:float l:"Average Days to Complete Tree Debris Requests" t:dataTypeName=number

metric m:total_completed_requests p:integer l:"Total Completed Requests" t:dataTypeName=number

metric m:median_days_to_repond_to_tree_debris_removal_request p:integer l:"Median Days to Repond to Tree Debris Removal Request" t:dataTypeName=number

metric m:target_response_time_days_ p:integer l:"Target Response Time (Days)" t:dataTypeName=number

entity e:hwpp-nx6b l:"Performance Metrics - Streets & Sanitation - Tree Debris" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/hwpp-nx6b

property e:hwpp-nx6b t:meta.view v:id=hwpp-nx6b v:category="Administration & Finance" v:attributionLink=http://www.cityofchicago.org/performance v:averageRating=0 v:name="Performance Metrics - Streets & Sanitation - Tree Debris" v:attribution="City of Chicago"

property e:hwpp-nx6b t:meta.view.owner v:id=vi9p-p863 v:screenName="Eric Phillips" v:displayName="Eric Phillips"

property e:hwpp-nx6b t:meta.view.tableauthor v:id=vi9p-p863 v:screenName="Eric Phillips" v:displayName="Eric Phillips"
```

## Top Records

```ls
| week                | average_days_to_complete_tree_debris_requests | total_completed_requests | median_days_to_repond_to_tree_debris_removal_request | target_response_time_days_ | 
| =================== | ============================================= | ======================== | ==================================================== | ========================== | 
| June 6-12, 2011     | 10.6                                          | 154                      | 7                                                    | 5                          | 
| June 13-19, 2011    | 10.5                                          | 864                      | 7                                                    | 5                          | 
| June 20-26, 2011    | 9                                             | 283                      | 3                                                    | 5                          | 
| June 27-July 3,2011 | 6.3                                           | 1616                     | 5                                                    | 5                          | 
| July 4 - 10, 2011   | 4.5                                           | 819                      | 4                                                    | 5                          | 
| July 11 - 17, 2011  | 4.2                                           | 1411                     | 4                                                    | 5                          | 
| July 18 - 24, 2011  | 4.9                                           | 1358                     | 5                                                    | 5                          | 
| July 25 - 31, 2011  | 4.4                                           | 527                      | 3                                                    | 5                          | 
| August 1 - 7, 2011  | 6                                             | 640                      | 5                                                    | 5                          | 
| August 8 - 14, 2011 | 9.5                                           | 911                      | 9                                                    | 5                          | 
```