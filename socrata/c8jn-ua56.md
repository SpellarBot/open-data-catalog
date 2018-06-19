# DBS Performance Plan Check Development Services Counter- Quarterly

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dbs-performance-plan-check-development-services-counter-quarterly-d63ab) |
| Metadata | [Link](https://data.lacity.org/api/views/c8jn-ua56) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/c8jn-ua56/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/c8jn-ua56/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | c8jn-ua56 |
| Name | DBS Performance Plan Check Development Services Counter- Quarterly |
| Tags | wait time, counters, dbs, development services, plan check, quarterly, completion |
| Created | 2014-05-30T21:30:54Z |
| Publication Date | 2015-12-07T20:24:45Z |

## Description

This data describes the Plan Check cases completed by DBS within 15 days the percentage of customers at DBS development services counters served within 30 minutes (wait time).

## Columns

```ls
| Included | Schema Type    | Field Name                                    | Name                                              | Data Type     | Render Type   |
| ======== | ============== | ============================================= | ================================================= | ============= | ============= |
| No       |                | date_name                                     | Date Name                                         | text          | text          |
| Yes      | time           | date_value                                    | Date Value                                        | calendar_date | calendar_date |
| Yes      | numeric metric | completed_within_15_days_plan_check           | % completed within 15 days (Plan Check)           | percent       | percent       |
| Yes      | numeric metric | served_in_30_minutes_or_less_services_counter | % Served in 30 minutes or less (Services Counter) | percent       | percent       |
```

## Time Field

```ls
Value = date_value
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = date_name
```

## Data Commands

```ls
series e:c8jn-ua56 d:2010-09-30T00:00:00.000Z m:served_in_30_minutes_or_less_services_counter=95 m:completed_within_15_days_plan_check=89

series e:c8jn-ua56 d:2010-12-31T00:00:00.000Z m:served_in_30_minutes_or_less_services_counter=96 m:completed_within_15_days_plan_check=86

series e:c8jn-ua56 d:2010-03-31T00:00:00.000Z m:served_in_30_minutes_or_less_services_counter=97 m:completed_within_15_days_plan_check=89
```

## Meta Commands

```ls
metric m:completed_within_15_days_plan_check p:integer l:"% completed within 15 days (Plan Check)" t:dataTypeName=percent

metric m:served_in_30_minutes_or_less_services_counter p:integer l:"% Served in 30 minutes or less (Services Counter)" t:dataTypeName=percent

entity e:c8jn-ua56 l:"DBS Performance Plan Check Development Services Counter- Quarterly" t:url=https://data.lacity.org/api/views/c8jn-ua56

property e:c8jn-ua56 t:meta.view v:id=c8jn-ua56 v:averageRating=0 v:name="DBS Performance Plan Check Development Services Counter- Quarterly"

property e:c8jn-ua56 t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:c8jn-ua56 t:meta.view.owner v:id=u8tq-3dir v:screenName=Saira v:displayName=Saira

property e:c8jn-ua56 t:meta.view.tableauthor v:id=u8tq-3dir v:screenName=Saira v:roleName=publisher v:displayName=Saira
```

## Top Records

```ls
| date_name  | date_value          | completed_within_15_days_plan_check | served_in_30_minutes_or_less_services_counter | 
| ========== | =================== | =================================== | ============================================= | 
| Q1 FY 2010 | 2010-09-30T00:00:00 | 89                                  | 95                                            | 
| Q2 FY 2010 | 2010-12-31T00:00:00 | 86                                  | 96                                            | 
| Q3 FY 2010 | 2010-03-31T00:00:00 | 89                                  | 97                                            | 
| Q4 FY 2010 | 2010-06-30T00:00:00 | 86                                  | 96                                            | 
| Q1 FY 2011 | 2011-09-30T00:00:00 | 87                                  | 93                                            | 
| Q2 FY 2011 | 2011-12-31T00:00:00 | 82                                  | 88                                            | 
| Q3 FY 2011 | 2011-03-31T00:00:00 | 89                                  | 87                                            | 
| Q4 FY 2011 | 2011-06-30T00:00:00 | 87                                  | 87                                            | 
| Q1 FY 2012 | 2012-09-30T00:00:00 | 90                                  | 87                                            | 
| Q2 FY 2012 | 2012-12-31T00:00:00 | 87                                  | 87                                            | 
```