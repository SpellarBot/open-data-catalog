# Call Center Metrics for the Health Service System

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/call-center-metrics-for-the-health-service-system) |
| Metadata | [Link](https://data.sfgov.org/api/views/qz8r-q5ne) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/qz8r-q5ne/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/qz8r-q5ne/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | qz8r-q5ne |
| Name | Call Center Metrics for the Health Service System |
| Category | Health and Social Services |
| Tags | call center, metrics, performance |
| Created | 2016-09-13T23:49:06Z |
| Publication Date | 2017-04-11T17:07:33Z |

## Description

This dataset captures monthly data from HSS' phone system and includes metrics pertaining to Calls Answered, Average Speed of Answer, Abandonment Rate, In-person Assistance. This data supports the City's Performance Measures requirements.

## Columns

```ls
| Included | Schema Type    | Field Name                      | Name                            | Data Type     | Render Type   |
| ======== | ============== | =============================== | =============================== | ============= | ============= |
| No       | time           | :updated_at                     | updated_at                      | meta_data     | meta_data     |
| No       |                | month                           | Month                           | calendar_date | calendar_date |
| Yes      | numeric metric | inbound_calls                   | Inbound Calls                   | number        | number        |
| Yes      | numeric metric | average_speed_of_answer_in_secs | Average Speed of Answer in Secs | number        | number        |
| Yes      | numeric metric | abandoned_calls                 | Abandoned Calls                 | number        | number        |
| Yes      | numeric metric | call_abandonment_rate           | Call Abandonment Rate           | percent       | percent       |
| Yes      | numeric metric | in_person_visits                | In-person visits                | number        | number        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = month
```

## Data Commands

```ls
series e:qz8r-q5ne d:2017-04-11T17:05:59.000Z m:call_abandonment_rate=0.7 m:abandoned_calls=33 m:average_speed_of_answer_in_secs=11 m:inbound_calls=4521 m:in_person_visits=1345

series e:qz8r-q5ne d:2017-04-11T17:05:59.000Z m:call_abandonment_rate=1.9 m:abandoned_calls=53 m:average_speed_of_answer_in_secs=16 m:inbound_calls=4122 m:in_person_visits=1098

series e:qz8r-q5ne d:2017-04-11T17:05:59.000Z m:call_abandonment_rate=1.3 m:abandoned_calls=105 m:average_speed_of_answer_in_secs=34 m:inbound_calls=5438 m:in_person_visits=1338
```

## Meta Commands

```ls
metric m:inbound_calls p:integer l:"Inbound Calls" d:"Number of Automatic Call Distribution (ACD) calls received by the agent group" t:dataTypeName=number

metric m:average_speed_of_answer_in_secs p:integer l:"Average Speed of Answer in Secs" d:"Average Time to Answer. Average time callers waited to get an answer from an agent." t:dataTypeName=number

metric m:abandoned_calls p:integer l:"Abandoned Calls" d:"A call offered to an agent and the caller hangs up before receiving an answer" t:dataTypeName=number

metric m:call_abandonment_rate p:double l:"Call Abandonment Rate" d:"Percentage of callers who hang up before receiving an answer. It is the Number of Calls Abandoned by Number of Total Calls (Inbound Calls + Abandoned Calls), offered to an agent group." t:dataTypeName=percent

metric m:in_person_visits p:integer l:"In-person visits" d:"Member visit to HSS office for regular business and consultation, not Open Enrollment activities." t:dataTypeName=number

entity e:qz8r-q5ne l:"Call Center Metrics for the Health Service System" t:url=https://data.sfgov.org/api/views/qz8r-q5ne

property e:qz8r-q5ne t:meta.view v:id=qz8r-q5ne v:category="Health and Social Services" v:averageRating=0 v:name="Call Center Metrics for the Health Service System"

property e:qz8r-q5ne t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:qz8r-q5ne t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:displayName=OpenData

property e:qz8r-q5ne t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```

## Top Records

```ls
| :updated_at | month | inbound_calls | average_speed_of_answer_in_secs | abandoned_calls | call_abandonment_rate | in_person_visits | 
| =========== | ===== | ============= | =============================== | =============== | ===================== | ================ | 
| 1491930359  |       | 4521          | 11                              | 33              | 0.70                  | 1345             | 
| 1491930359  |       | 4122          | 16                              | 53              | 1.90                  | 1098             | 
| 1491930359  |       | 5438          | 34                              | 105             | 1.30                  | 1338             | 
| 1491930359  |       | 5705          | 77                              | 340             | 5.60                  | 1349             | 
| 1491930359  |       | 4052          | 28                              | 58              | 1.40                  | 1212             | 
| 1491930359  |       | 9943          | 31                              | 225             | 2.20                  | 1560             | 
| 1491930359  |       | 5012          | 27                              | 91              | 1.80                  | 1162             | 
| 1491930359  |       | 3607          | 16                              | 34              | 0.90                  | 1221             | 
| 1491930359  |       | 3153          | 25                              | 43              | 1.30                  | 1028             | 
| 1491930359  |       | 3552          | 31                              | 77              | 2.10                  | 1303             | 
```