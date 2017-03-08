# Performance Metrics - Transportation - Pavement Cave-ins

## Dataset

* [Dataset URL](https://data.cityofchicago.org/api/views/euee-qccq/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/performance-metrics-transportation-pavement-cave-ins-a4f5b)
* [Metadata URL](https://data.cityofchicago.org/api/views/euee-qccq)
* Id = euee-qccq
* Name = Performance Metrics - Transportation - Pavement Cave-ins
* Attribution = City of Chicago
* [Attribution Link](http://www.cityofchicago.org)
* Category = Administration & Finance
* Tags = [performance metrics, service delivery]
* Created = 2011-09-22T22:10:01Z
* Publication Date = 2014-04-29T03:01:47Z
* Rows Updated = 2014-04-29T02:53:31Z

## Description

As underground drainage systems age, occasionally failures in the pipes and joints can cause pavement cave-ins.  The Department of Transportation (CDOT) responds to pavement cave-ins reported through 311?s Customer Service Requests (CSR) system on a case-by-case basis.  This metric tracks the average number of days CDOT takes to complete pavement cave-in repairs per week.  The target response time for pavement cave-ins is within 3 days.

## Columns

```ls
| Name                                               | Field Name                                         | Data Type | Render Type | Schema Type    | Included | 
| ================================================== | ================================================== | ========= | =========== | ============== | ======== | 
| updated_at                                         | :updated_at                                        | meta_data | meta_data   | time           | No       | 
| Week                                               | week                                               | text      | text        | series tag     | Yes      | 
| Average Days to Complete Pavement Cave-in Requests | average_days_to_complete_pavement_cave_in_requests | number    | number      | numeric metric | Yes      | 
| Total Completed Requests                           | total_completed_requests                           | number    | number      | numeric metric | Yes      | 
| Target Response Time (Days)                        | target_response_time_days_                         | number    | number      | numeric metric | Yes      | 
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = 
Annotation Fields = 
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

property e:euee-qccq t:meta.view d:2017-03-07T22:49:17.910Z v:id=euee-qccq v:category="Administration & Finance" v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Performance Metrics - Transportation - Pavement Cave-ins" v:attribution="City of Chicago"

property e:euee-qccq t:meta.view.owner d:2017-03-07T22:49:17.910Z v:id=zzya-y4bn v:screenName="Elizabeth Scott" v:displayName="Elizabeth Scott"

property e:euee-qccq t:meta.view.tableauthor d:2017-03-07T22:49:17.910Z v:id=zzya-y4bn v:screenName="Elizabeth Scott" v:displayName="Elizabeth Scott"
```