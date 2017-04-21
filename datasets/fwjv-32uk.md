# Meter Rate Schedules

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/meter-rate-schedules-58041) |
| Metadata | [Link](https://data.sfgov.org/api/views/fwjv-32uk) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/fwjv-32uk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/fwjv-32uk/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | fwjv-32uk |
| Name | Meter Rate Schedules |
| Attribution | SFpark (info@sfpark.org) |
| Category | Transportation |
| Tags | meter, parking |
| Created | 2014-03-07T01:53:36Z |
| Publication Date | 2014-03-13T23:22:17Z |

## Description

Meter rate schedules for all meters owned by SFMTA and the Port of SF as of March 7, 2014. Base rates describe the standard rate for parking at the meter. Overrides to the Base Rate apply on the given days at the given times. Rates are subject to operating schedules, available here: https://data.sfgov.org/Transportation/Meter-Operating-Schedules/6cqg-dxku. When the time limit of a meter is 0 minutes, such as during Tow or Alternate Schedule - Passenger Loading, parking is not available and therefore meter rates do not apply. Please direct any data inquiries to info@sfpark.org

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| No       | time           | :updated_at       | updated_at        | meta_data | meta_data   |
| Yes      | series tag     | post_id           | Post ID           | text      | text        |
| Yes      | numeric metric | schedule_priority | Schedule Priority | number    | number      |
| Yes      | series tag     | days_applied      | Days Applied      | text      | text        |
| No       |                | from_time         | From Time         | text      | text        |
| No       |                | to_time           | To Time           | text      | text        |
| Yes      | series tag     | rate_type         | Rate Type         | text      | text        |
| Yes      | numeric metric | rate              | Rate              | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = from_time,to_time
```

## Data Commands

```ls
series e:fwjv-32uk d:2014-03-06T17:53:40.000Z t:rate_type="Base Rate" t:post_id=102-02990 m:schedule_priority=1 m:rate=2

series e:fwjv-32uk d:2014-03-06T17:53:40.000Z t:rate_type="Base Rate" t:post_id=102-03890 m:schedule_priority=1 m:rate=2

series e:fwjv-32uk d:2014-03-06T17:53:40.000Z t:rate_type="Base Rate" t:post_id=102-03900 m:schedule_priority=1 m:rate=2
```

## Meta Commands

```ls
metric m:schedule_priority p:integer l:"Schedule Priority" t:dataTypeName=number

metric m:rate p:double l:Rate t:dataTypeName=number

entity e:fwjv-32uk l:"Meter Rate Schedules" t:attribution="SFpark (info@sfpark.org)" t:url=https://data.sfgov.org/api/views/fwjv-32uk

property e:fwjv-32uk t:meta.view v:id=fwjv-32uk v:category=Transportation v:averageRating=0 v:name="Meter Rate Schedules" v:attribution="SFpark (info@sfpark.org)"

property e:fwjv-32uk t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:fwjv-32uk t:meta.view.owner v:id=mx96-mbir v:screenName="Drew Taylor" v:displayName="Drew Taylor"

property e:fwjv-32uk t:meta.view.tableauthor v:id=mx96-mbir v:screenName="Drew Taylor" v:roleName=editor v:displayName="Drew Taylor"
```

## Top Records

```ls
| :updated_at | post_id   | schedule_priority | days_applied | from_time | to_time | rate_type | rate | 
| =========== | ========= | ================= | ============ | ========= | ======= | ========= | ==== | 
| 1394128420  | 102-02990 | 1                 |              |           |         | Base Rate | 2    | 
| 1394128420  | 102-03890 | 1                 |              |           |         | Base Rate | 2    | 
| 1394128420  | 102-03900 | 1                 |              |           |         | Base Rate | 2    | 
| 1394128420  | 102-03910 | 1                 |              |           |         | Base Rate | 2    | 
| 1394128420  | 102-03920 | 1                 |              |           |         | Base Rate | 2    | 
| 1394128420  | 102-03930 | 1                 |              |           |         | Base Rate | 2    | 
| 1394128420  | 102-03940 | 1                 |              |           |         | Base Rate | 2    | 
| 1394128420  | 102-03950 | 1                 |              |           |         | Base Rate | 2    | 
| 1394128420  | 102-03960 | 1                 |              |           |         | Base Rate | 2    | 
| 1394128420  | 102-03970 | 1                 |              |           |         | Base Rate | 2    | 
```