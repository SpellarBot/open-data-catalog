# Performance Metrics - Transportation

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/performance-metrics-transportation-04563) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/eaff-5ff2) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/eaff-5ff2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/eaff-5ff2/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | eaff-5ff2 |
| Name | Performance Metrics - Transportation |
| Attribution | City of Chicago |
| Category | Administration & Finance |
| Tags | service requests, pothole, performance metrics, streets, pavement |
| Created | 2014-01-22T21:16:12Z |
| Publication Date | 2015-07-16T04:14:35Z |

## Description

This dataset contains performance metrics tracked by the Chicago Department of Transportation (CDOT). Thirty-five different performance metrics are tracked in this dataset, which reports the performance target, actual performance, and number of requests completed for a given metric. These metrics are based on data calculated from the city's 311 system. Individual breakout of each performance metric are also available under the "More Views" button.

## Columns

```ls
| Included | Schema Type    | Field Name                        | Name                              | Data Type     | Render Type   |
| ======== | ============== | ================================= | ================================= | ============= | ============= |
| Yes      | series tag     | activity                          | Activity                          | text          | text          |
| Yes      | time           | period_start                      | Period Start                      | calendar_date | calendar_date |
| Yes      | series tag     | period_length                     | Period Length                     | text          | text          |
| Yes      | numeric metric | target_response_days              | Target Response Days              | number        | number        |
| Yes      | numeric metric | average_days_to_complete_activity | Average Days to Complete Activity | number        | number        |
| Yes      | numeric metric | total_completed_requests          | Total Completed Requests          | number        | number        |
| Yes      | series tag     | period                            | Period                            | text          | text          |
```

## Time Field

```ls
Value = period_start
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:eaff-5ff2 d:2011-06-06T00:00:00.000Z t:period="06/06/2011 - 06/12/2011" t:period_length=Week t:activity="Alley Light Out" m:average_days_to_complete_activity=1.3 m:target_response_days=30 m:total_completed_requests=28

series e:eaff-5ff2 d:2011-06-06T00:00:00.000Z t:period="06/06/2011 - 06/12/2011" t:period_length=Week t:activity="Alley Pot Hole" m:average_days_to_complete_activity=1.65 m:target_response_days=10 m:total_completed_requests=3

series e:eaff-5ff2 d:2011-06-06T00:00:00.000Z t:period="06/06/2011 - 06/12/2011" t:period_length=Week t:activity="Bridges and Viaducts (All Types)" m:average_days_to_complete_activity=1.08 m:target_response_days=7 m:total_completed_requests=7
```

## Meta Commands

```ls
metric m:target_response_days p:integer l:"Target Response Days" d:"The target number of days to perform this activity, from request to completion." t:dataTypeName=number

metric m:average_days_to_complete_activity p:float l:"Average Days to Complete Activity" d:"Average days between creation of request for service and completion of that service, for activities completed in this period." t:dataTypeName=number

metric m:total_completed_requests p:integer l:"Total Completed Requests" t:dataTypeName=number

entity e:eaff-5ff2 l:"Performance Metrics - Transportation" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/eaff-5ff2

property e:eaff-5ff2 t:meta.view v:id=eaff-5ff2 v:category="Administration & Finance" v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Performance Metrics - Transportation" v:attribution="City of Chicago"

property e:eaff-5ff2 t:meta.view.owner v:id=vewm-vupz v:screenName="Jonathan Levy" v:displayName="Jonathan Levy"

property e:eaff-5ff2 t:meta.view.tableauthor v:id=vewm-vupz v:screenName="Jonathan Levy" v:roleName=administrator v:displayName="Jonathan Levy"
```

## Top Records

```ls
| activity                                           | period_start        | period_length | target_response_days | average_days_to_complete_activity | total_completed_requests | period                  | 
| ================================================== | =================== | ============= | ==================== | ================================= | ======================== | ======================= | 
| Alley Light Out                                    | 2011-06-06T00:00:00 | Week          | 30                   | 1.30                              | 28                       | 06/06/2011 - 06/12/2011 | 
| Alley Pot Hole                                     | 2011-06-06T00:00:00 | Week          | 10                   | 1.65                              | 3                        | 06/06/2011 - 06/12/2011 | 
| Bridges and Viaducts (All Types)                   | 2011-06-06T00:00:00 | Week          | 7                    | 1.08                              | 7                        | 06/06/2011 - 06/12/2011 | 
| CDOT Construction Complaints                       | 2011-06-06T00:00:00 | Week          | 14                   | 1.00                              | 31                       | 06/06/2011 - 06/12/2011 | 
| CDOT Electrical Operations Construction Complaints | 2011-06-06T00:00:00 | Week          | 25                   | 1.50                              | 28                       | 06/06/2011 - 06/12/2011 | 
| Cable Cut                                          | 2011-06-06T00:00:00 | Week          | 5                    | 1.13                              | 9                        | 06/06/2011 - 06/12/2011 | 
| City Electrical Vault                              | 2011-06-06T00:00:00 | Week          | 40                   | 1.00                              | 1                        | 06/06/2011 - 06/12/2011 | 
| Gym Shoe/Object On Electrical Wire                 | 2011-06-06T00:00:00 | Week          | 7                    | 1.00                              | 5                        | 06/06/2011 - 06/12/2011 | 
| Inspect Public Way Survey                          | 2011-06-06T00:00:00 | Week          | 10                   | 1.25                              | 52                       | 06/06/2011 - 06/12/2011 | 
| Landscape Median Maintenance                       | 2011-06-06T00:00:00 | Week          | 30                   | 1.16                              | 6                        | 06/06/2011 - 06/12/2011 | 
```