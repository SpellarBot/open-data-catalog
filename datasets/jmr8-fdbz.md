# DOP Adult Early Discharges by Calendar Year

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dop-adult-early-discharges-by-calendar-year-5c37d) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/jmr8-fdbz) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/jmr8-fdbz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/jmr8-fdbz/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | jmr8-fdbz |
| Name | DOP Adult Early Discharges by Calendar Year |
| Attribution | Department of Probation (DOP) |
| Category | City Government |
| Tags | dop, probation, adult, early discharges, calendar year |
| Created | 2014-06-17T16:45:13Z |
| Publication Date | 2017-03-08T19:46:06Z |

## Description

Adult supervision cases that have had an early discharge request filed with a local court during the reporting period. Categorized by: new early discharge (ED) requests submitted; ED requests approved; ED requests disapproved. Based on carryover of pending early discharge requests from month-to-month, the number of approvals plus disapprovals may not equal the number of requests per year.

## Columns

```ls
| Included | Schema Type    | Field Name                     | Name                           | Data Type | Render Type |
| ======== | ============== | ============================== | ============================== | ========= | =========== |
| Yes      | series tag     | borough                        | Borough                        | text      | text        |
| Yes      | time           | calendar_year                  | Calendar Year                  | number    | number      |
| Yes      | series tag     | early_discharge_request_status | Early Discharge Request Status | text      | text        |
| Yes      | numeric metric | early_discharge_count          | Early Discharge Count          | number    | number      |
```

## Time Field

```ls
Value = calendar_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:jmr8-fdbz d:2006-01-01T00:00:00.000Z t:borough=Bronx t:early_discharge_request_status="New Requests" m:early_discharge_count=78

series e:jmr8-fdbz d:2007-01-01T00:00:00.000Z t:borough=Bronx t:early_discharge_request_status="New Requests" m:early_discharge_count=67

series e:jmr8-fdbz d:2008-01-01T00:00:00.000Z t:borough=Bronx t:early_discharge_request_status="New Requests" m:early_discharge_count=90
```

## Meta Commands

```ls
metric m:early_discharge_count p:integer l:"Early Discharge Count" d:"The number of early discharge filings or decisions by type during the reporting period." t:dataTypeName=number

entity e:jmr8-fdbz l:"DOP Adult Early Discharges by Calendar Year" t:attribution="Department of Probation (DOP)" t:url=https://data.cityofnewyork.us/api/views/jmr8-fdbz

property e:jmr8-fdbz t:meta.view v:id=jmr8-fdbz v:category="City Government" v:averageRating=0 v:name="DOP Adult Early Discharges by Calendar Year" v:attribution="Department of Probation (DOP)"

property e:jmr8-fdbz t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:jmr8-fdbz t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| borough | calendar_year | early_discharge_request_status | early_discharge_count | 
| ======= | ============= | ============================== | ===================== | 
| Bronx   | 2006          | New Requests                   | 78                    | 
| Bronx   | 2007          | New Requests                   | 67                    | 
| Bronx   | 2008          | New Requests                   | 90                    | 
| Bronx   | 2009          | New Requests                   | 135                   | 
| Bronx   | 2010          | New Requests                   | 407                   | 
| Bronx   | 2011          | New Requests                   | 339                   | 
| Bronx   | 2012          | New Requests                   | 248                   | 
| Bronx   | 2013          | New Requests                   | 285                   | 
| Bronx   | 2006          | Requests Approved              | 89                    | 
| Bronx   | 2007          | Requests Approved              | 61                    | 
```