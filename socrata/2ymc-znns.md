# Aircraft Parking Location Inventory at SFO

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/aircraft-parking-location-inventory-at-sfo) |
| Metadata | [Link](https://data.sfgov.org/api/views/2ymc-znns) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/2ymc-znns/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/2ymc-znns/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | 2ymc-znns |
| Name | Aircraft Parking Location Inventory at SFO |
| Category | Transportation |
| Created | 2016-01-19T23:49:27Z |
| Publication Date | 2016-04-12T17:37:55Z |

## Description

Aircraft parking spot inventory

## Columns

```ls
| Included | Schema Type | Field Name        | Name              | Data Type     | Render Type   |
| ======== | =========== | ================= | ================= | ============= | ============= |
| Yes      | series tag  | spot_id           | Spot ID           | text          | number        |
| Yes      | series tag  | spot_name         | Spot Name         | text          | text          |
| Yes      | time        | start_date        | Start Date        | calendar_date | calendar_date |
| No       |             | end_date          | End Date          | calendar_date | calendar_date |
| Yes      | series tag  | type              | Type              | text          | text          |
| Yes      | series tag  | configuration     | Configuration     | text          | text          |
| Yes      | series tag  | category          | Category          | text          | text          |
| Yes      | series tag  | status            | Status            | text          | text          |
| No       |             | creation_date     | Creation Date     | calendar_date | calendar_date |
| No       |             | modification_date | Modification Date | calendar_date | calendar_date |
```

## Time Field

```ls
Value = start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = end_date,creation_date,modification_date
```

## Data Commands

```ls
series e:2ymc-znns d:1980-01-01T00:00:00.000Z t:spot_name=03-01 t:category=L t:spot_id=376 t:status=Active t:configuration=Multi-Large t:type=Hardstand m:row_number.2ymc-znns=1

series e:2ymc-znns d:1980-01-01T00:00:00.000Z t:spot_name=03-01A t:category=C t:spot_id=535 t:status=Active t:configuration=Dependent t:type=Hardstand m:row_number.2ymc-znns=2

series e:2ymc-znns d:1980-01-01T00:00:00.000Z t:spot_name=03-01B t:category=C t:spot_id=536 t:status=Active t:configuration=Dependent t:type=Hardstand m:row_number.2ymc-znns=3
```

## Meta Commands

```ls
metric m:row_number.2ymc-znns p:long l:"Row Number"

entity e:2ymc-znns l:"Aircraft Parking Location Inventory at SFO" t:url=https://data.sfgov.org/api/views/2ymc-znns

property e:2ymc-znns t:meta.view v:id=2ymc-znns v:category=Transportation v:averageRating=0 v:name="Aircraft Parking Location Inventory at SFO"

property e:2ymc-znns t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:2ymc-znns t:meta.view.owner v:id=5cu4-55ms v:screenName="APS Data" v:displayName="APS Data"

property e:2ymc-znns t:meta.view.tableauthor v:id=5cu4-55ms v:screenName="APS Data" v:roleName=editor v:displayName="APS Data"
```

## Top Records

```ls
| spot_id | spot_name | start_date          | end_date | type      | configuration | category | status | creation_date       | modification_date   | 
| ======= | ========= | =================== | ======== | ========= | ============= | ======== | ====== | =================== | =================== | 
| 376     | 03-01     | 1980-01-01T00:00:00 |          | Hardstand | Multi-Large   | L        | Active | 2009-01-20T00:00:00 | 2009-02-26T00:00:00 | 
| 535     | 03-01A    | 1980-01-01T00:00:00 |          | Hardstand | Dependent     | C        | Active | 2009-02-27T00:00:00 | 2009-06-10T00:00:00 | 
| 536     | 03-01B    | 1980-01-01T00:00:00 |          | Hardstand | Dependent     | C        | Active | 2009-02-27T00:00:00 | 2009-06-10T00:00:00 | 
| 377     | 03-02     | 1980-01-01T00:00:00 |          | Hardstand | Independent   | E        | Active | 2009-01-20T00:00:00 |                     | 
| 378     | 03-03     | 1980-01-01T00:00:00 |          | Hardstand | Independent   | D        | Active | 2009-01-20T00:00:00 | 2012-06-14T00:00:00 | 
| 379     | 03-04     | 1980-01-01T00:00:00 |          | Hardstand | Multi-Large   | L        | Active | 2009-01-20T00:00:00 | 2009-02-26T00:00:00 | 
| 380     | 03-04A    | 1980-01-01T00:00:00 |          | Hardstand | Dependent     | C        | Active | 2009-01-20T00:00:00 | 2009-02-26T00:00:00 | 
| 381     | 03-04B    | 1980-01-01T00:00:00 |          | Hardstand | Dependent     | C        | Active | 2009-01-20T00:00:00 | 2012-06-14T00:00:00 | 
| 390     | 09-01     | 1980-01-01T00:00:00 |          | Hardstand | Independent   | B        | Active | 2009-01-20T00:00:00 | 2015-12-31T00:00:00 | 
| 391     | 09-02     | 1980-01-01T00:00:00 |          | Hardstand | Independent   | B        | Active | 2009-01-20T00:00:00 | 2015-12-31T00:00:00 | 
```