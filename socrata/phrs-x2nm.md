# Performance Metrics - Transportation - Street Lights All Out

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/performance-metrics-transportation-street-lights-all-out-87625) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/phrs-x2nm) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/phrs-x2nm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/phrs-x2nm/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | phrs-x2nm |
| Name | Performance Metrics - Transportation - Street Lights All Out |
| Attribution | City of Chicago |
| Category | Administration & Finance |
| Tags | performance metrics, service delivery, street lights |
| Created | 2011-09-26T15:23:01Z |
| Publication Date | 2014-05-01T03:16:40Z |

## Description

The Chicago Department of Transportation (CDOT) oversees approximately 250,000 street lights that illuminate arterial and residential streets in Chicago. CDOT performs repairs and bulb replacements in response to residents? reports of street light outages. Whenever CDOT receives a report from 311?s Customer Service Requests (CSR) system of an ?All Out? (an outage of 3 or more lights) the electrician assigned to make the repair looks at all the lights in that circuit (each circuit has 8-16 lights) to make sure that they are all working properly.  This metric tracks the average number of days CDOT takes to complete street lights ?All Out? requests.   Total number of requests fulfilled per week is also available by mousing over columns.  The target response time for street light ?All Out? repairs is within 4 days.  To report a street light outage, call 311 or see http://www.cityofchicago.org/city/en/depts/cdot/provdrs/traffic_signals_andstreetlights/svcs/request_street_lights.html

## Columns

```ls
| Included | Schema Type    | Field Name                                              | Name                                                    | Data Type | Render Type |
| ======== | ============== | ======================================================= | ======================================================= | ========= | =========== |
| Yes      | time           | week                                                    | Week                                                    | text      | text        |
| Yes      | series tag     | average_days_to_complete_street_lights_all_out_requests | Average Days to Complete Street Lights All Out Requests | text      | number      |
| Yes      | numeric metric | total_completed_requests                                | Total Completed Requests                                | number    | number      |
| Yes      | numeric metric | target_response_time_days_                              | Target Response Time (Days)                             | number    | number      |
```

## Time Field

```ls
Value = week
Format & Zone = ww,yyyy
```

## Data Commands

```ls
series e:phrs-x2nm d:2011-03-28T00:00:00.000Z t:average_days_to_complete_street_lights_all_out_requests=4.75 m:total_completed_requests=117 m:target_response_time_days_=4

series e:phrs-x2nm d:2011-04-04T00:00:00.000Z t:average_days_to_complete_street_lights_all_out_requests=3.55 m:total_completed_requests=358 m:target_response_time_days_=4

series e:phrs-x2nm d:2011-04-11T00:00:00.000Z t:average_days_to_complete_street_lights_all_out_requests=5.53 m:total_completed_requests=368 m:target_response_time_days_=4
```

## Meta Commands

```ls
metric m:total_completed_requests p:integer l:"Total Completed Requests" t:dataTypeName=number

metric m:target_response_time_days_ p:integer l:"Target Response Time (Days)" t:dataTypeName=number

entity e:phrs-x2nm l:"Performance Metrics - Transportation - Street Lights All Out" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/phrs-x2nm

property e:phrs-x2nm t:meta.view v:id=phrs-x2nm v:category="Administration & Finance" v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Performance Metrics - Transportation - Street Lights All Out" v:attribution="City of Chicago"

property e:phrs-x2nm t:meta.view.owner v:id=zzya-y4bn v:screenName="Elizabeth Scott" v:displayName="Elizabeth Scott"

property e:phrs-x2nm t:meta.view.tableauthor v:id=zzya-y4bn v:screenName="Elizabeth Scott" v:displayName="Elizabeth Scott"
```

## Top Records

```ls
| week                   | average_days_to_complete_street_lights_all_out_requests | total_completed_requests | target_response_time_days_ | 
| ====================== | ======================================================= | ======================== | ========================== | 
| March 28-April 3, 2011 | 4.75                                                    | 117                      | 4                          | 
| April 4 - 10, 2011     | 3.55                                                    | 358                      | 4                          | 
| April 11-17, 2011      | 5.53                                                    | 368                      | 4                          | 
| April 18-24, 2011      | 5.1                                                     | 391                      | 4                          | 
| April 25-May 1, 2011   | 4.06                                                    | 392                      | 4                          | 
| May 2-8, 2011          | 3.61                                                    | 295                      | 4                          | 
| May 9-15, 2011         | 4.44                                                    | 356                      | 4                          | 
| May 16-22, 2011        | 4.43                                                    | 395                      | 4                          | 
| May 23-29, 2011        | 5.47                                                    | 502                      | 4                          | 
| May 30-June 5, 2011    | 4.37                                                    | 563                      | 4                          | 
```