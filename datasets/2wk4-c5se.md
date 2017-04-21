# Performance Metrics - Housing & Economic Development - Landmark Permitting Review

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/performance-metrics-housing-economic-development-landmark-permitting-review-a6116) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/2wk4-c5se) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/2wk4-c5se/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/2wk4-c5se/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | 2wk4-c5se |
| Name | Performance Metrics - Housing & Economic Development - Landmark Permitting Review |
| Attribution | City of Chicago |
| Category | Administration & Finance |
| Tags | performance metrics, permits, landmarks |
| Created | 2011-07-19T21:35:38Z |
| Publication Date | 2014-10-03T05:29:07Z |

## Description

With a goal of reviewing landmark permits in one-day, the department strives to meet this goal no less than 95% of the time.
The Historic Preservation Division staffs the Commission on Chicago Landmarks and reviews all permit applications for work involving designated and proposed Chicago landmarks and landmark districts.

## Columns

```ls
| Included | Schema Type    | Field Name                                  | Name                                        | Data Type | Render Type |
| ======== | ============== | =========================================== | =========================================== | ========= | =========== |
| Yes      | series tag     | month                                       | Month                                       | text      | text        |
| Yes      | time           | year                                        | Year                                        | number    | text        |
| Yes      | numeric metric | permit_applications_reviewed                | Permit applications reviewed                | number    | number      |
| Yes      | numeric metric | permit_applications_reviewed_within_one_day | Permit applications reviewed within one day | percent   | percent     |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:2wk4-c5se d:2014-01-01T00:00:00.000Z t:month=8/2014 m:permit_applications_reviewed=267 m:permit_applications_reviewed_within_one_day=92

series e:2wk4-c5se d:2014-01-01T00:00:00.000Z t:month=7/2014 m:permit_applications_reviewed=286 m:permit_applications_reviewed_within_one_day=93

series e:2wk4-c5se d:2014-01-01T00:00:00.000Z t:month=6/2014 m:permit_applications_reviewed=245 m:permit_applications_reviewed_within_one_day=93
```

## Meta Commands

```ls
metric m:permit_applications_reviewed p:integer l:"Permit applications reviewed" t:dataTypeName=number

metric m:permit_applications_reviewed_within_one_day p:integer l:"Permit applications reviewed within one day" t:dataTypeName=percent

entity e:2wk4-c5se l:"Performance Metrics - Housing & Economic Development - Landmark Permitting Review" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/2wk4-c5se

property e:2wk4-c5se t:meta.view v:id=2wk4-c5se v:category="Administration & Finance" v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Performance Metrics - Housing & Economic Development - Landmark Permitting Review" v:attribution="City of Chicago"

property e:2wk4-c5se t:meta.view.owner v:id=7jj6-h75i v:screenName=Eve v:displayName=Eve

property e:2wk4-c5se t:meta.view.tableauthor v:id=7jj6-h75i v:screenName=Eve v:displayName=Eve
```

## Top Records

```ls
| month   | year | permit_applications_reviewed | permit_applications_reviewed_within_one_day | 
| ======= | ==== | ============================ | =========================================== | 
| 8/2014  | 2014 | 267                          | 92                                          | 
| 7/2014  | 2014 | 286                          | 93                                          | 
| 6/2014  | 2014 | 245                          | 93                                          | 
| 5/2014  | 2014 | 233                          | 89                                          | 
| 4/2014  | 2014 | 225                          | 91                                          | 
| 3/2014  | 2014 | 173                          | 89                                          | 
| 2/2014  | 2012 | 206                          | 97                                          | 
| 2/2014  | 2014 | 166                          | 95                                          | 
| 1/2014  | 2014 | 161                          | 91                                          | 
| 12/2013 | 2013 | 181                          | 94                                          | 
```