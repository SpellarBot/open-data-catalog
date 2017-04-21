# Performance Metrics - Transportation - Pothole Repair

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/performance-metrics-transportation-pothole-repair-ff555) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/sbt5-2ec8) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/sbt5-2ec8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/sbt5-2ec8/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | sbt5-2ec8 |
| Name | Performance Metrics - Transportation - Pothole Repair |
| Attribution | City of Chicago |
| Category | Administration & Finance |
| Tags | service requests, pothole, performance metrics, streets, pavement |
| Created | 2011-09-26T15:26:12Z |
| Publication Date | 2014-07-10T16:35:08Z |

## Description

When moisture seeps into pavement, it expands when it freezes and contracts when it thaws.  This flexing of the pavement, combined with the melted water and the stress of vehicular traffic, causes pavement to deteriorate and potholes to form.  The Department of Transportation (CDOT) responds to potholes reported through 311?s Customer Service Requests (CSR) system by mapping open pothole requests each morning and routing crews in geographic clusters so as to fill as many potholes as possible per day.  This metric tracks the average number of days CDOT takes to complete pothole repairs per week.   Total number of requests fulfilled per week is also available by mousing over columns.  The target response time for pothole repairs is within 7 days.  For more information about pothole repairs, see CDOT?s pothole Frequently Asked Questions page: http://www.cityofchicago.org/content/dam/city/depts/cdot/PotholeFAQ_winter1011.pdf

## Columns

```ls
| Included | Schema Type    | Field Name                                       | Name                                             | Data Type | Render Type |
| ======== | ============== | ================================================ | ================================================ | ========= | =========== |
| Yes      | time           | week                                             | Week                                             | text      | text        |
| Yes      | numeric metric | average_days_to_complete_pothole_repair_requests | Average Days to Complete Pothole Repair Requests | number    | number      |
| Yes      | numeric metric | total_completed_requests                         | Total Completed Requests                         | number    | number      |
| Yes      | numeric metric | target_response_time_days_                       | Target Response Time (Days)                      | number    | number      |
```

## Time Field

```ls
Value = week
Format & Zone = ww,yyyy
```

## Data Commands

```ls
series e:sbt5-2ec8 d:2011-06-06T00:00:00.000Z m:total_completed_requests=805 m:target_response_time_days_=7 m:average_days_to_complete_pothole_repair_requests=11

series e:sbt5-2ec8 d:2011-06-13T00:00:00.000Z m:total_completed_requests=600 m:target_response_time_days_=7 m:average_days_to_complete_pothole_repair_requests=8.74

series e:sbt5-2ec8 d:2011-06-20T00:00:00.000Z m:total_completed_requests=620 m:target_response_time_days_=7 m:average_days_to_complete_pothole_repair_requests=4.81
```

## Meta Commands

```ls
metric m:average_days_to_complete_pothole_repair_requests p:float l:"Average Days to Complete Pothole Repair Requests" t:dataTypeName=number

metric m:total_completed_requests p:integer l:"Total Completed Requests" t:dataTypeName=number

metric m:target_response_time_days_ p:integer l:"Target Response Time (Days)" t:dataTypeName=number

entity e:sbt5-2ec8 l:"Performance Metrics - Transportation - Pothole Repair" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/sbt5-2ec8

property e:sbt5-2ec8 t:meta.view v:id=sbt5-2ec8 v:category="Administration & Finance" v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Performance Metrics - Transportation - Pothole Repair" v:attribution="City of Chicago"

property e:sbt5-2ec8 t:meta.view.owner v:id=zzya-y4bn v:screenName="Elizabeth Scott" v:displayName="Elizabeth Scott"

property e:sbt5-2ec8 t:meta.view.tableauthor v:id=zzya-y4bn v:screenName="Elizabeth Scott" v:displayName="Elizabeth Scott"
```

## Top Records

```ls
| week                | average_days_to_complete_pothole_repair_requests | total_completed_requests | target_response_time_days_ | 
| =================== | ================================================ | ======================== | ========================== | 
| June 6-12, 2011     | 11                                               | 805                      | 7                          | 
| June 13-19, 2011    | 8.74                                             | 600                      | 7                          | 
| June 20-26, 2011    | 4.81                                             | 620                      | 7                          | 
| June 27-July 3,2011 | 2.18                                             | 263                      | 7                          | 
| July 4 - 10, 2011   | 11.12                                            | 1166                     | 7                          | 
| July 11 - 17, 2011  | 3.93                                             | 188                      | 7                          | 
| July 18 - 24, 2011  | 4.62                                             | 95                       | 7                          | 
| July 25 - 31, 2011  | 3.49                                             | 251                      | 7                          | 
| August 1 - 7, 2011  | 3.84                                             | 189                      | 7                          | 
| August 8 - 14, 2011 | 3.84                                             | 143                      | 7                          | 
```