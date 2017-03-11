# Performance Metrics - Chicago Park District - Park Security Checks

## Dataset

* [Dataset URL](https://data.cityofchicago.org/api/views/wrvx-zpw5/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/performance-metrics-chicago-park-district-park-security-checks-c7e46)
* [Metadata URL](https://data.cityofchicago.org/api/views/wrvx-zpw5)
* Id = wrvx-zpw5
* Name = Performance Metrics - Chicago Park District - Park Security Checks
* Attribution = Chicago Park District
* [Attribution Link](http://www.chicagoparkdistrict.com/)
* Category = Administration & Finance
* Tags = [performance metrics, parks]
* Created = 2011-11-25T19:33:56Z
* Publication Date = 2012-08-03T19:17:00Z
* Rows Updated = 2012-08-03T19:16:57Z

## Description

The Security Department ensures the safety and security of patrons, employees and facilities in Chicago?s Parks. The data that is displayed below represents the total number of security checks that staff made during the previous week.

## Columns

```ls
| Name        | Field Name  | Data Type | Render Type | Schema Type    | Included | 
| =========== | =========== | ========= | =========== | ============== | ======== | 
| updated_at  | :updated_at | meta_data | meta_data   | time           | No       | 
| Week        | week        | text      | text        | series tag     | Yes      | 
| Park Checks | park_checks | number    | number      | numeric metric | Yes      | 
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = 
Annotation Fields = 
```

## Data Commands

```ls
series e:wrvx-zpw5 d:2011-12-23T15:38:00.000Z t:week=07/16/2011 m:park_checks=2505

series e:wrvx-zpw5 d:2011-12-23T15:38:03.000Z t:week=07/23/2011 m:park_checks=2237

series e:wrvx-zpw5 d:2011-12-23T15:38:04.000Z t:week=07/30/2011 m:park_checks=2237
```

## Meta Commands

```ls
metric m:park_checks p:integer l:"Park Checks" t:dataTypeName=number

entity e:wrvx-zpw5 l:"Performance Metrics - Chicago Park District - Park Security Checks" t:attribution="Chicago Park District" t:url=https://data.cityofchicago.org/api/views/wrvx-zpw5

property e:wrvx-zpw5 t:meta.view d:2017-03-07T17:51:47.589Z v:id=wrvx-zpw5 v:category="Administration & Finance" v:attributionLink=http://www.chicagoparkdistrict.com/ v:averageRating=0 v:name="Performance Metrics - Chicago Park District - Park Security Checks" v:attribution="Chicago Park District"

property e:wrvx-zpw5 t:meta.view.owner d:2017-03-07T17:51:47.589Z v:id=7jj6-h75i v:screenName=Eve v:displayName=Eve

property e:wrvx-zpw5 t:meta.view.tableauthor d:2017-03-07T17:51:47.589Z v:id=7jj6-h75i v:screenName=Eve v:displayName=Eve
```