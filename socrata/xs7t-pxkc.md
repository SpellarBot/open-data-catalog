# 311 Daily Service Requests

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/311-daily-service-requests) |
| Metadata | [Link](https://data.somervillema.gov/api/views/xs7t-pxkc) |
| Data: JSON | [100 Rows](https://data.somervillema.gov/api/views/xs7t-pxkc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.somervillema.gov/api/views/xs7t-pxkc/rows.csv?max_rows=100) |
| Host | data.somervillema.gov |
| Id | xs7t-pxkc |
| Name | 311 Daily Service Requests |
| Attribution | City of Somerville 311 Call Center |
| Category | 311 Call Center |
| Tags | 311, service requests, work orders, dpw, isd |
| Created | 2015-12-09T15:39:30Z |
| Publication Date | 2015-12-09T15:43:48Z |

## Description

This dataset includes all calls for service in which a work order is created. This dataset is a subset of all 311 Calls.

## Columns

```ls
| Included | Schema Type    | Field Name                    | Name                          | Data Type     | Render Type   |
| ======== | ============== | ============================= | ============================= | ============= | ============= |
| Yes      | series tag     | ticket_id                     | ticket_id                     | text          | number        |
| Yes      | series tag     | issue_type                    | issue_type                    | text          | text          |
| Yes      | time           | ticket_created_date_time      | ticket_created_date_time      | calendar_date | calendar_date |
| Yes      | numeric metric | submitter                     | submitter                     | number        | number        |
| Yes      | series tag     | issue_description             | issue_description             | text          | text          |
| Yes      | series tag     | ticket_status                 | ticket_status                 | text          | text          |
| No       |                | ticket_last_updated_date_time | ticket_last_updated_date_time | calendar_date | calendar_date |
| Yes      | series tag     | secondary_issue_type          | secondary_issue_type          | text          | text          |
| Yes      | series tag     | neighborhood_district         | neighborhood_district         | text          | text          |
| No       |                | ticket_closed_date_time       | ticket_closed_date_time       | calendar_date | calendar_date |
| Yes      | series tag     | street_address                | street_address                | text          | text          |
```

## Time Field

```ls
Value = ticket_created_date_time
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = ticket_last_updated_date_time,ticket_closed_date_time
```

## Data Commands

```ls
series e:xs7t-pxkc d:2015-07-21T09:13:00.000Z t:ticket_id=405377 t:secondary_issue_type="Service Requests" t:ticket_status=Closed t:issue_type=Sewer t:neighborhood_district="Ward 5" t:street_address="83 Alpine St" t:issue_description=DPW-Sewer m:submitter=14859

series e:xs7t-pxkc d:2015-07-23T13:19:00.000Z t:ticket_id=406217 t:secondary_issue_type="Service Requests" t:ticket_status=Closed t:issue_type="Furniture and equipment moving" t:neighborhood_district="Ward 2" t:street_address="220 Washington St" t:issue_description="DPW-Buildings & Grounds" m:submitter=67928

series e:xs7t-pxkc d:2015-07-31T16:08:00.000Z t:ticket_id=408433 t:secondary_issue_type="Service Requests" t:ticket_status=Closed t:issue_type="Park/grounds issue" t:street_address="0 Holland St" t:issue_description="DPW-Buildings & Grounds" m:submitter=10048
```

## Meta Commands

```ls
metric m:submitter p:integer l:submitter t:dataTypeName=number

entity e:xs7t-pxkc l:"311 Daily Service Requests" t:attribution="City of Somerville 311 Call Center" t:url=https://data.somervillema.gov/api/views/xs7t-pxkc

property e:xs7t-pxkc t:meta.view v:id=xs7t-pxkc v:category="311 Call Center" v:averageRating=0 v:name="311 Daily Service Requests" v:attribution="City of Somerville 311 Call Center"

property e:xs7t-pxkc t:meta.view.owner v:id=x7b9-bdhv v:screenName=SStewart v:displayName=SStewart

property e:xs7t-pxkc t:meta.view.tableauthor v:id=x7b9-bdhv v:screenName=SStewart v:roleName=administrator v:displayName=SStewart
```

## Top Records

```ls
| ticket_id | issue_type                            | ticket_created_date_time | submitter | issue_description       | ticket_status | ticket_last_updated_date_time | secondary_issue_type | neighborhood_district | ticket_closed_date_time | street_address    | 
| ========= | ===================================== | ======================== | ========= | ======================= | ============= | ============================= | ==================== | ===================== | ======================= | ================= | 
| 405377    | Sewer                                 | 2015-07-21T09:13:00      | 14859     | DPW-Sewer               | Closed        | 2017-04-18T10:06:00           | Service Requests     | Ward 5                | 2017-04-18T10:06:00     | 83 Alpine St      | 
| 406217    | Furniture and equipment moving        | 2015-07-23T13:19:00      | 67928     | DPW-Buildings & Grounds | Closed        | 2017-03-24T12:34:00           | Service Requests     | Ward 2                | 2017-03-24T12:34:00     | 220 Washington St | 
| 408433    | Park/grounds issue                    | 2015-07-31T16:08:00      | 10048     | DPW-Buildings & Grounds | Closed        | 2017-04-03T13:02:00           | Service Requests     |                       | 2017-04-03T13:02:00     | 0 Holland St      | 
| 409503    | Arborist and tree maintenance         | 2015-08-05T08:39:00      | 44902     | DPW-Highway             | Closed        | 2017-04-12T08:14:00           | Service Requests     | Ward 5                | 2017-04-12T08:14:00     | 23 Alpine St      | 
| 413266    | Sinkhole                              | 2015-08-18T15:46:00      | 34755     | DPW-Sewer               | Closed        | 2017-03-24T09:52:00           | Service Requests     | Ward 6                | 2017-03-24T09:52:00     | 31 Russell St     | 
| 422409    | Traffic light/crossing signal issue   | 2015-09-15T19:25:00      | 78604     | DPW-Lights & Lines      | Closed        | 2017-03-27T08:38:00           | Service Requests     | Ward 3                | 2017-03-27T08:38:00     | 11 Westwood Rd    | 
| 431509    | Health miscellaneous                  | 2015-10-20T08:15:00      | 0         | ISD-Health              | Open          | 2015-10-20T08:15:00           | Service Requests     | Ward 5                |                         | 116 Porter St     | 
| 433839    | School building maintenance & repairs | 2015-10-28T11:50:00      | 37604     | DPW-Buildings & Grounds | Closed        | 2017-03-24T12:51:00           | Service Requests     | Ward 3                | 2017-03-24T12:51:00     | 81 Highland Ave   | 
| 439257    | School building maintenance & repairs | 2015-11-18T08:59:00      | 37604     | DPW-Buildings & Grounds | Closed        | 2017-03-24T12:52:00           | Service Requests     | Ward 3                | 2017-03-24T12:52:00     | 81 Highland Ave   | 
| 450189    | City building maintenance & repairs   | 2016-01-08T09:23:00      | 67928     | DPW-Buildings & Grounds | Closed        | 2017-03-24T12:29:00           | Service Requests     | Ward 2                | 2017-03-24T12:29:00     | 220 Washington St | 
```