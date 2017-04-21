# Aircraft Parking Activity Records at SFO

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/aircraft-parking-activity-records-at-sfo) |
| Metadata | [Link](https://data.sfgov.org/api/views/5rkh-waic) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/5rkh-waic/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/5rkh-waic/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | 5rkh-waic |
| Name | Aircraft Parking Activity Records at SFO |
| Category | Transportation |
| Created | 2016-01-19T23:52:48Z |
| Publication Date | 2016-04-12T17:35:28Z |

## Description

Aircraft parking records including airlines, aircraft types, parking spot, and dates

## Columns

```ls
| Included | Schema Type | Field Name        | Name              | Data Type     | Render Type   |
| ======== | =========== | ================= | ================= | ============= | ============= |
| Yes      | series tag  | source_id         | Source ID         | text          | text          |
| Yes      | series tag  | source_type       | Source Type       | text          | text          |
| Yes      | time        | start_date        | Start Date        | calendar_date | calendar_date |
| No       |             | end_date          | End Date          | calendar_date | calendar_date |
| Yes      | series tag  | reserving_company | Reserving Company | text          | text          |
| Yes      | series tag  | operator_company  | Operator Company  | text          | text          |
| Yes      | series tag  | model             | Model             | text          | text          |
| Yes      | series tag  | tail_number       | Tail Number       | text          | text          |
| Yes      | series tag  | spot              | Spot              | text          | text          |
```

## Time Field

```ls
Value = start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = end_date
```

## Data Commands

```ls
series e:5rkh-waic d:2015-12-31T00:00:00.000Z t:operator_company="Air New Zealand" t:model=B777-300 t:tail_number=ZK-OKO t:source_id=90505 t:source_type=callin t:reserving_company="Air New Zealand" t:spot=09-04 m:row_number.5rkh-waic=1

series e:5rkh-waic d:2015-12-30T00:00:00.000Z t:operator_company="American Airlines" t:model=A321-200 t:tail_number=N184US t:source_id=90431 t:source_type=callin t:reserving_company="American Airlines" t:spot=03-02 m:row_number.5rkh-waic=2

series e:5rkh-waic d:2015-12-30T00:00:00.000Z t:operator_company="American Airlines" t:model=A321-200 t:tail_number=N978UY t:source_id=90433 t:source_type=callin t:reserving_company="American Airlines" t:spot=03-03 m:row_number.5rkh-waic=3
```

## Meta Commands

```ls
metric m:row_number.5rkh-waic p:long l:"Row Number"

entity e:5rkh-waic l:"Aircraft Parking Activity Records at SFO" t:url=https://data.sfgov.org/api/views/5rkh-waic

property e:5rkh-waic t:meta.view v:id=5rkh-waic v:category=Transportation v:averageRating=0 v:name="Aircraft Parking Activity Records at SFO"

property e:5rkh-waic t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:5rkh-waic t:meta.view.owner v:id=5cu4-55ms v:screenName="APS Data" v:displayName="APS Data"

property e:5rkh-waic t:meta.view.tableauthor v:id=5cu4-55ms v:screenName="APS Data" v:roleName=editor v:displayName="APS Data"
```

## Top Records

```ls
| source_id | source_type | start_date          | end_date            | reserving_company   | operator_company    | model      | tail_number | spot   | 
| ========= | =========== | =================== | =================== | =================== | =================== | ========== | =========== | ====== | 
| 90505     | callin      | 2015-12-31T00:00:00 | 2015-12-31T00:00:00 | Air New Zealand     | Air New Zealand     | B777-300   | ZK-OKO      | 09-04  | 
| 90431     | callin      | 2015-12-30T00:00:00 | 2015-12-31T00:00:00 | American Airlines   | American Airlines   | A321-200   | N184US      | 03-02  | 
| 90433     | callin      | 2015-12-30T00:00:00 | 2015-12-31T00:00:00 | American Airlines   | American Airlines   | A321-200   | N978UY      | 03-03  | 
| 90459     | callin      | 2015-12-31T00:00:00 | 2015-12-31T00:00:00 | Asiana Airlines     | Asiana Airlines     | B747-400   |             | 09-09  | 
| 90491     | callin      | 2015-12-31T00:00:00 | 2015-12-31T00:00:00 | COPA Airlines, Inc. | COPA Airlines, Inc. | B737-800   | HP-1846     | 41-18  | 
| 90467     | callin      | 2015-12-31T00:00:00 | 2015-12-31T00:00:00 | China Airlines      | China Airlines      | B747-400   | B18717      | 50-07  | 
| 90451     | callin      | 2015-12-30T00:00:00 | 2015-12-31T00:00:00 | DHL Express (USA)   | DHL Express (USA)   | METROLINER | N21RZ       | 50-02A | 
| 90449     | callin      | 2015-12-31T00:00:00 | 2015-12-31T00:00:00 | DHL Express (USA)   | DHL Express (USA)   | B767-200   | N655GT      | 50-06  | 
| 90447     | callin      | 2015-12-31T00:00:00 | 2015-12-31T00:00:00 | DHL Express (USA)   | DHL Express (USA)   | B767-200   | N659GT      | 50-01  | 
| 90445     | callin      | 2015-12-30T00:00:00 | 2015-12-31T00:00:00 | Delta Air Lines     | Compass Airlines    | EMB-170    | N607CZ      | B-025  | 
```