# Performance Metrics - Chicago Park District - Park Security Checks

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/performance-metrics-chicago-park-district-park-security-checks-c7e46) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/wrvx-zpw5) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/wrvx-zpw5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/wrvx-zpw5/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | wrvx-zpw5 |
| Name | Performance Metrics - Chicago Park District - Park Security Checks |
| Attribution | Chicago Park District |
| Category | Administration & Finance |
| Tags | performance metrics, parks |
| Created | 2011-11-25T19:33:56Z |
| Publication Date | 2012-08-03T19:17:00Z |

## Description

The Security Department ensures the safety and security of patrons, employees and facilities in Chicago’s Parks. The data that is displayed below represents the total number of security checks that staff made during the previous week.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type | Render Type |
| ======== | ============== | =========== | =========== | ========= | =========== |
| No       | time           | :updated_at | updated_at  | meta_data | meta_data   |
| No       |                | week        | Week        | text      | text        |
| Yes      | numeric metric | park_checks | Park Checks | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = week
```

## Data Commands

```ls
series e:wrvx-zpw5 d:2011-12-23T15:38:00.000Z m:park_checks=2505

series e:wrvx-zpw5 d:2011-12-23T15:38:03.000Z m:park_checks=2237

series e:wrvx-zpw5 d:2011-12-23T15:38:04.000Z m:park_checks=2237
```

## Meta Commands

```ls
metric m:park_checks p:integer l:"Park Checks" t:dataTypeName=number

entity e:wrvx-zpw5 l:"Performance Metrics - Chicago Park District - Park Security Checks" t:attribution="Chicago Park District" t:url=https://data.cityofchicago.org/api/views/wrvx-zpw5

property e:wrvx-zpw5 t:meta.view v:id=wrvx-zpw5 v:category="Administration & Finance" v:attributionLink=http://www.chicagoparkdistrict.com/ v:averageRating=0 v:name="Performance Metrics - Chicago Park District - Park Security Checks" v:attribution="Chicago Park District"

property e:wrvx-zpw5 t:meta.view.owner v:id=7jj6-h75i v:screenName=Eve v:displayName=Eve

property e:wrvx-zpw5 t:meta.view.tableauthor v:id=7jj6-h75i v:screenName=Eve v:displayName=Eve
```