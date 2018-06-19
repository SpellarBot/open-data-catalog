# Aircraft Tail Numbers and Models at SFO

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/aircraft-tail-numbers-and-models-at-sfo) |
| Metadata | [Link](https://data.sfgov.org/api/views/u7dr-xm3v) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/u7dr-xm3v/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/u7dr-xm3v/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | u7dr-xm3v |
| Name | Aircraft Tail Numbers and Models at SFO |
| Category | Transportation |
| Created | 2016-01-19T23:43:41Z |
| Publication Date | 2016-04-12T17:18:52Z |

## Description

Aircraft details including IDs, models, types, subtypes, and airlines

## Columns

```ls
| Included | Schema Type | Field Name        | Name              | Data Type     | Render Type   |
| ======== | =========== | ================= | ================= | ============= | ============= |
| Yes      | series tag  | aircraft_id       | Aircraft ID       | text          | number        |
| Yes      | series tag  | tail_number       | Tail Number       | text          | text          |
| Yes      | series tag  | aircraft_model    | Aircraft Model    | text          | text          |
| Yes      | series tag  | airline           | Airline           | text          | text          |
| Yes      | series tag  | status            | Status            | text          | text          |
| Yes      | time        | creation_date     | Creation Date     | calendar_date | calendar_date |
| No       |             | modification_date | Modification Date | calendar_date | calendar_date |
```

## Time Field

```ls
Value = creation_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = modification_date
```

## Data Commands

```ls
series e:u7dr-xm3v d:2015-10-22T00:00:00.000Z t:tail_number=151UW t:status=Active t:aircraft_model=A321-200 t:aircraft_id=9824 t:airline="American Airlines" m:row_number.u7dr-xm3v=1

series e:u7dr-xm3v d:2010-02-12T00:00:00.000Z t:tail_number=18702 t:status=Active t:aircraft_model=B747-400 t:aircraft_id=2035 t:airline="China Cargo Airlines" m:row_number.u7dr-xm3v=2

series e:u7dr-xm3v d:2012-09-07T00:00:00.000Z t:tail_number=215US t:status=Active t:aircraft_model=DC9-30 t:aircraft_id=5772 t:airline="Signature Flight Support" m:row_number.u7dr-xm3v=3
```

## Meta Commands

```ls
metric m:row_number.u7dr-xm3v p:long l:"Row Number"

entity e:u7dr-xm3v l:"Aircraft Tail Numbers and Models at SFO" t:url=https://data.sfgov.org/api/views/u7dr-xm3v

property e:u7dr-xm3v t:meta.view v:id=u7dr-xm3v v:category=Transportation v:averageRating=0 v:name="Aircraft Tail Numbers and Models at SFO"

property e:u7dr-xm3v t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:u7dr-xm3v t:meta.view.owner v:id=5cu4-55ms v:screenName="APS Data" v:displayName="APS Data"

property e:u7dr-xm3v t:meta.view.tableauthor v:id=5cu4-55ms v:screenName="APS Data" v:roleName=editor v:displayName="APS Data"
```

## Top Records

```ls
| aircraft_id | tail_number | aircraft_model | airline                          | status | creation_date       | modification_date   | 
| =========== | =========== | ============== | ================================ | ====== | =================== | =================== | 
| 9824        | 151UW       | A321-200       | American Airlines                | Active | 2015-10-22T00:00:00 |                     | 
| 2035        | 18702       | B747-400       | China Cargo Airlines             | Active | 2010-02-12T00:00:00 |                     | 
| 5772        | 215US       | DC9-30         | Signature Flight Support         | Active | 2012-09-07T00:00:00 |                     | 
| 9479        | 268         | A319           | Air Canada                       | Active | 2015-05-21T00:00:00 |                     | 
| 6908        | 2985UA      | B747-400       | United Airlines                  | Active | 2013-06-27T00:00:00 |                     | 
| 6909        | 2994UA      | B777-200       | United Airlines                  | Active | 2013-06-27T00:00:00 |                     | 
| 7779        | 316US       | A320-200       | Delta Air Lines                  | Active | 2013-10-24T00:00:00 |                     | 
| 799         | 318SW       | B737-300       | Southwest Airlines               | Active | 2009-03-07T00:00:00 |                     | 
| 216         | 3203EV      | B747-400       | Evergreen International Airlines | Active | 2009-01-23T00:00:00 |                     | 
| 1045        | 327NW       | A320-200       | Delta Air Lines                  | Active | 2009-05-11T00:00:00 | 2010-06-14T00:00:00 | 
```