# 311 Call Metrics

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/311-call-metrics) |
| Metadata | [Link](https://data.sfgov.org/api/views/mwjb-biik) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/mwjb-biik/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/mwjb-biik/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | mwjb-biik |
| Name | 311 Call Metrics |
| Category | City Infrastructure |
| Created | 2014-06-25T18:49:52Z |
| Publication Date | 2017-03-01T19:10:37Z |

## Description

Monthly metrics from the SF311 Call Center including Calls Answered, Percentage of Calls Ansewered within 60 Seconds, Average Speed of Answer (seconds) and Transferred Calls Percentage.

## Columns

```ls
| Included | Schema Type    | Field Name                                                   | Name                              | Data Type     | Render Type   |
| ======== | ============== | ============================================================ | ================================= | ============= | ============= |
| Yes      | time           | month                                                        | Month                             | calendar_date | calendar_date |
| Yes      | numeric metric | calls_answered                                               | Calls Answered                    | number        | number        |
| Yes      | numeric metric | percentage_of_calls_answered_within_60_seconds_service_level | Svc Level (% answered w/i 60 sec) | percent       | percent       |
| Yes      | numeric metric | average_speed_of_answer                                      | Avg Speed Answer (sec)            | number        | number        |
| Yes      | numeric metric | transferred_calls_percentage                                 | Transferred Calls %               | percent       | percent       |
```

## Time Field

```ls
Value = month
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:mwjb-biik d:2015-12-01T00:00:00.000Z m:average_speed_of_answer=138 m:percentage_of_calls_answered_within_60_seconds_service_level=43.7 m:transferred_calls_percentage=8.3 m:calls_answered=71042

series e:mwjb-biik d:2015-11-01T00:00:00.000Z m:average_speed_of_answer=149 m:percentage_of_calls_answered_within_60_seconds_service_level=43.8 m:transferred_calls_percentage=8.6 m:calls_answered=70038

series e:mwjb-biik d:2015-10-01T00:00:00.000Z m:average_speed_of_answer=191 m:percentage_of_calls_answered_within_60_seconds_service_level=32.3 m:transferred_calls_percentage=9.1 m:calls_answered=73047
```

## Meta Commands

```ls
metric m:calls_answered p:integer l:"Calls Answered" t:dataTypeName=number

metric m:percentage_of_calls_answered_within_60_seconds_service_level p:float l:"Svc Level (% answered w/i 60 sec)" t:dataTypeName=percent

metric m:average_speed_of_answer p:integer l:"Avg Speed Answer (sec)" t:dataTypeName=number

metric m:transferred_calls_percentage p:float l:"Transferred Calls %" t:dataTypeName=percent

entity e:mwjb-biik l:"311 Call Metrics" t:url=https://data.sfgov.org/api/views/mwjb-biik

property e:mwjb-biik t:meta.view v:id=mwjb-biik v:category="City Infrastructure" v:averageRating=0 v:name="311 Call Metrics"

property e:mwjb-biik t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:mwjb-biik t:meta.view.owner v:id=isin-8y46 v:profileImageUrlMedium=/api/users/isin-8y46/profile_images/THUMB v:profileImageUrlLarge=/api/users/isin-8y46/profile_images/LARGE v:screenName=AndyM v:profileImageUrlSmall=/api/users/isin-8y46/profile_images/TINY v:displayName=AndyM

property e:mwjb-biik t:meta.view.tableauthor v:id=isin-8y46 v:profileImageUrlMedium=/api/users/isin-8y46/profile_images/THUMB v:profileImageUrlLarge=/api/users/isin-8y46/profile_images/LARGE v:screenName=AndyM v:profileImageUrlSmall=/api/users/isin-8y46/profile_images/TINY v:roleName=publisher v:displayName=AndyM
```

## Top Records

```ls
| month               | calls_answered | percentage_of_calls_answered_within_60_seconds_service_level | average_speed_of_answer | transferred_calls_percentage | 
| =================== | ============== | ============================================================ | ======================= | ============================ | 
| 2015-12-01T00:00:00 | 71042          | 43.7                                                         | 138                     | 8.3                          | 
| 2015-11-01T00:00:00 | 70038          | 43.8                                                         | 149                     | 8.6                          | 
| 2015-10-01T00:00:00 | 73047          | 32.3                                                         | 191                     | 9.1                          | 
| 2015-09-01T00:00:00 | 74445          | 41.1                                                         | 124                     | 8.9                          | 
| 2015-08-01T00:00:00 | 73027          | 32.6                                                         | 217                     | 9.6                          | 
| 2015-07-01T00:00:00 | 77644          | 33.9                                                         | 214                     | 7.8                          | 
| 2015-06-01T00:00:00 | 74064          | 29.1                                                         | 217                     | 8.7                          | 
| 2015-05-01T00:00:00 | 80836          | 32.6                                                         | 215                     | 8.4                          | 
| 2015-04-01T00:00:00 | 84685          | 38.4                                                         | 156                     | 8.7                          | 
| 2015-03-01T00:00:00 | 89074          | 37.3                                                         | 153                     | 9.0                          | 
```