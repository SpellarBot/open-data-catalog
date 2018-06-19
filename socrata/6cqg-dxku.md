# Meter Operating Schedules

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/meter-operating-schedules-151f7) |
| Metadata | [Link](https://data.sfgov.org/api/views/6cqg-dxku) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/6cqg-dxku/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/6cqg-dxku/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | 6cqg-dxku |
| Name | Meter Operating Schedules |
| Attribution | SFpark (info@sfpark.org) |
| Category | Transportation |
| Tags | meters, parking |
| Created | 2014-03-10T21:14:46Z |
| Publication Date | 2014-03-13T23:20:07Z |

## Description

Operating schedules and time limits for all meters owned by SFMTA and the Port of SF as of March 10, 2014. Tow periods and Alternate schedules trump all base Operating Schedules. Please direct any data inquiries to info@sfpark.org

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| No       | time           | :updated_at         | updated_at          | meta_data | meta_data   |
| Yes      | series tag     | street_and_block    | Street and Block    | text      | text        |
| Yes      | series tag     | block_side          | Block Side          | text      | text        |
| Yes      | series tag     | post_id             | Post ID             | text      | text        |
| Yes      | series tag     | cap_color           | Cap Color           | text      | text        |
| Yes      | series tag     | schedule_type       | Schedule Type       | text      | text        |
| Yes      | series tag     | applied_color_rule  | Applied Color Rule  | text      | text        |
| Yes      | numeric metric | priority            | Priority            | number    | number      |
| Yes      | series tag     | days_applied        | Days Applied        | text      | text        |
| No       |                | from_time           | From Time           | text      | text        |
| No       |                | to_time             | To Time             | text      | text        |
| Yes      | series tag     | active_meter_status | Active Meter Status | text      | text        |
| No       |                | time_limit          | Time Limit          | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = from_time,to_time,time_limit
```

## Data Commands

```ls
series e:6cqg-dxku d:2014-03-10T14:14:57.000Z t:street_and_block="01ST ST 0" t:applied_color_rule="Yellow - Commercial loading zone" t:block_side=Even t:cap_color=Yellow t:schedule_type="Operating Schedule" t:days_applied=Mo,Tu,We,Th,Fr t:active_meter_status="M - Active meter installed" t:post_id=201-00040 m:priority=1

series e:6cqg-dxku d:2014-03-10T14:14:57.000Z t:street_and_block="01ST ST 0" t:applied_color_rule="Yellow - Commercial loading zone" t:block_side=Even t:cap_color=Yellow t:schedule_type="Operating Schedule" t:days_applied=Sa t:active_meter_status="M - Active meter installed" t:post_id=201-00040 m:priority=2

series e:6cqg-dxku d:2014-03-10T14:14:57.000Z t:street_and_block="01ST ST 0" t:applied_color_rule="Yellow - Commercial loading zone" t:block_side=Even t:cap_color=Yellow t:schedule_type="Operating Schedule" t:days_applied=Su t:active_meter_status="M - Active meter installed" t:post_id=201-00040 m:priority=3
```

## Meta Commands

```ls
metric m:priority p:integer l:Priority t:dataTypeName=number

entity e:6cqg-dxku l:"Meter Operating Schedules" t:attribution="SFpark (info@sfpark.org)" t:url=https://data.sfgov.org/api/views/6cqg-dxku

property e:6cqg-dxku t:meta.view v:id=6cqg-dxku v:category=Transportation v:averageRating=0 v:name="Meter Operating Schedules" v:attribution="SFpark (info@sfpark.org)"

property e:6cqg-dxku t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:6cqg-dxku t:meta.view.owner v:id=mx96-mbir v:screenName="Drew Taylor" v:displayName="Drew Taylor"

property e:6cqg-dxku t:meta.view.tableauthor v:id=mx96-mbir v:screenName="Drew Taylor" v:roleName=editor v:displayName="Drew Taylor"
```

## Top Records

```ls
| :updated_at | street_and_block | block_side | post_id   | cap_color | schedule_type      | applied_color_rule               | priority | days_applied   | from_time | to_time | active_meter_status        | time_limit  | 
| =========== | ================ | ========== | ========= | ========= | ================== | ================================ | ======== | ============== | ========= | ======= | ========================== | =========== | 
| 1394460897  | 01ST ST 0        | Even       | 201-00040 | Yellow    | Operating Schedule | Yellow - Commercial loading zone | 1        | Mo,Tu,We,Th,Fr | 7:00 AM   | 6:00 PM | M - Active meter installed | 60 minutes  | 
| 1394460897  | 01ST ST 0        | Even       | 201-00040 | Yellow    | Operating Schedule | Yellow - Commercial loading zone | 2        | Sa             | 7:00 AM   | 6:00 PM | M - Active meter installed | 60 minutes  | 
| 1394460897  | 01ST ST 0        | Even       | 201-00040 | Yellow    | Operating Schedule | Yellow - Commercial loading zone | 3        | Su             | 12:00 PM  | 6:00 PM | M - Active meter installed | 240 minutes | 
| 1394460897  | 01ST ST 0        | Even       | 201-00040 | Yellow    | Tow                | -                                | 1        | Mo,Tu,We,Th,Fr | 7:00 AM   | 9:00 AM | M - Active meter installed | 0 minutes   | 
| 1394460897  | 01ST ST 0        | Even       | 201-00040 | Yellow    | Tow                | -                                | 2        | Mo,Tu,We,Th,Fr | 3:00 PM   | 7:00 PM | M - Active meter installed | 0 minutes   | 
| 1394460897  | 01ST ST 0        | Even       | 201-00040 | Yellow    | Alternate          | Grey - General metered parking   | 1        | Sa             | 7:00 AM   | 6:00 PM | M - Active meter installed | 60 minutes  | 
| 1394460897  | 01ST ST 0        | Even       | 201-00040 | Yellow    | Alternate          | Grey - General metered parking   | 2        | Su             | 12:00 PM  | 6:00 PM | M - Active meter installed | 240 minutes | 
| 1394460897  | 01ST ST 0        | Even       | 201-00060 | Yellow    | Operating Schedule | Yellow - Commercial loading zone | 1        | Mo,Tu,We,Th,Fr | 7:00 AM   | 6:00 PM | M - Active meter installed | 60 minutes  | 
| 1394460897  | 01ST ST 0        | Even       | 201-00060 | Yellow    | Operating Schedule | Yellow - Commercial loading zone | 2        | Sa             | 7:00 AM   | 6:00 PM | M - Active meter installed | 60 minutes  | 
| 1394460897  | 01ST ST 0        | Even       | 201-00060 | Yellow    | Operating Schedule | Yellow - Commercial loading zone | 3        | Su             | 12:00 PM  | 6:00 PM | M - Active meter installed | 240 minutes | 
```