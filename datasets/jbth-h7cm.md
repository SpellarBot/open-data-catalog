# FOIA Request Log - Aviation

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/foia-request-log-aviation-7d7a9) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/jbth-h7cm) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/jbth-h7cm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/jbth-h7cm/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | jbth-h7cm |
| Name | FOIA Request Log - Aviation |
| Attribution | City of Chicago |
| Category | FOIA |
| Created | 2011-09-22T17:24:00Z |
| Publication Date | 2016-08-22T15:54:07Z |

## Description

FOIA requests received by Aviation as of May 1, 2010

## Columns

```ls
| Included | Schema Type | Field Name             | Name                   | Data Type     | Render Type   |
| ======== | =========== | ====================== | ====================== | ============= | ============= |
| Yes      | series tag  | requestor_name         | REQUESTOR NAME         | text          | text          |
| Yes      | series tag  | organization           | ORGANIZATION           | text          | text          |
| Yes      | series tag  | description_of_request | DESCRIPTION OF REQUEST | text          | text          |
| Yes      | time        | date_received          | DATE RECEIVED          | calendar_date | calendar_date |
| No       |             | due_date               | DUE DATE               | calendar_date | calendar_date |
```

## Time Field

```ls
Value = date_received
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = due_date
```

## Data Commands

```ls
series e:jbth-h7cm d:2016-07-27T00:00:00.000Z t:description_of_request="Unpaid/Unclaimed checks for more than $100 issued prior to 12-31-15" t:organization="Marketsphere Consulting" t:requestor_name="Michael Lazar" m:row_number.jbth-h7cm=1

series e:jbth-h7cm d:2016-07-27T00:00:00.000Z t:description_of_request="Accident on 7/21/16 at Baggage Claim #5/6 at ORD" t:organization="Bekkerman Law Offices, LLC" t:requestor_name="Meghan McDonald" m:row_number.jbth-h7cm=2

series e:jbth-h7cm d:2016-07-25T00:00:00.000Z t:description_of_request="Incident on 7/24/16 at Gate M23 at ORD" t:organization="Qatar Airways - ORD" t:requestor_name="Djamel Eddine Benkortbi" m:row_number.jbth-h7cm=3
```

## Meta Commands

```ls
metric m:row_number.jbth-h7cm p:long l:"Row Number"

entity e:jbth-h7cm l:"FOIA Request Log - Aviation" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/jbth-h7cm

property e:jbth-h7cm t:meta.view v:id=jbth-h7cm v:category=FOIA v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="FOIA Request Log - Aviation" v:attribution="City of Chicago"

property e:jbth-h7cm t:meta.view.owner v:id=3yz3-24vm v:screenName=mariawanamaker v:displayName=mariawanamaker

property e:jbth-h7cm t:meta.view.tableauthor v:id=3yz3-24vm v:screenName=mariawanamaker v:displayName=mariawanamaker
```

## Top Records

```ls
| requestor_name          | organization                                  | description_of_request                                              | date_received       | due_date            | 
| ======================= | ============================================= | =================================================================== | =================== | =================== | 
| Michael Lazar           | Marketsphere Consulting                       | Unpaid/Unclaimed checks for more than $100 issued prior to 12-31-15 | 2016-07-27T00:00:00 | 2016-08-03T00:00:00 | 
| Meghan McDonald         | Bekkerman Law Offices, LLC                    | Accident on 7/21/16 at Baggage Claim #5/6 at ORD                    | 2016-07-27T00:00:00 | 2016-08-03T00:00:00 | 
| Djamel Eddine Benkortbi | Qatar Airways - ORD                           | Incident on 7/24/16 at Gate M23 at ORD                              | 2016-07-25T00:00:00 | 2016-08-01T00:00:00 | 
| Antoinette Villa        | Skyline Management Group O'Hare               | Accident on 7/23/16 at T5 Parking Lot at ORD                        | 2016-07-25T00:00:00 | 2016-08-01T00:00:00 | 
| Anthony Mastrantonio    | Illinois House of Representatives, Jim Durkin | Contracts for Gates at ORD                                          | 2016-07-22T00:00:00 | 2016-07-29T00:00:00 | 
| Spiro Kezios            | Kezios Group, Inc.                            | Maximum Building Height Harlem and Higgins Avenues                  | 2016-07-22T00:00:00 | 2016-07-29T00:00:00 | 
| Allie Nixon             | Country Financial                             | Accident on 6/19/16 between T2 and T3 near loading/departure door 3 | 2016-07-20T00:00:00 | 2016-07-27T00:00:00 | 
| Alberto Ramirez         | Midwest REM Enterprises, Inc.                 | Pay Estimate #4 for Daytona Beach Sanitary Lift Station Project     | 2016-07-19T00:00:00 | 2016-07-26T00:00:00 | 
| Alberto Ramirez         | Midwest REM Enterprises, Inc.                 | Pay Estimate #14 for Taxiway LL Construction Project                | 2016-07-19T00:00:00 | 2016-07-26T00:00:00 | 
| Asif Qureshi            |                                               | Questions re Airlines and Criminal/Banned activities at ORD         | 2016-07-12T00:00:00 | 2016-07-19T00:00:00 | 
```