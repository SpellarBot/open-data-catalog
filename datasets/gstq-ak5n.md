# Annual Population Estimates (2012 - Present)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/annual-population-estimates-2012-present) |
| Metadata | [Link](https://data.nola.gov/api/views/gstq-ak5n) |
| Data: JSON | [100 Rows](https://data.nola.gov/api/views/gstq-ak5n/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.nola.gov/api/views/gstq-ak5n/rows.csv?max_rows=100) |
| Host | data.nola.gov |
| Id | gstq-ak5n |
| Name | Annual Population Estimates (2012 - Present) |
| Attribution | U.S. Census Bureau |
| Category | Economy and Workforce |
| Tags | resultsnola |
| Created | 2015-06-29T20:33:33Z |
| Publication Date | 2015-07-01T15:36:27Z |

## Description

This dataset includes population estimates from the U.S. Census Bureau which are published an annual basis. The data which is published in May represents the estimate for July of the previous year. While the Census publishes revised estimates for previous years each time a new estimate comes out, this data set only represents the unrevised estimate for each year. This data is used in ResultsNOLA to calculate population adjusted outcome and performance indicators.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type     | Render Type   |
| ======== | ============== | ============== | ============== | ============= | ============= |
| Yes      | series tag     | rowid          | RowID          | text          | text          |
| Yes      | time           | date           | Date           | calendar_date | calendar_date |
| No       |                | month          | Month          | text          | text          |
| No       |                | year           | Year           | number        | number        |
| No       |                | releasedate    | ReleaseDate    | calendar_date | calendar_date |
| Yes      | series tag     | releasemonth   | ReleaseMonth   | text          | text          |
| No       |                | releaseyear    | ReleaseYear    | number        | number        |
| Yes      | series tag     | indicatorname  | IndicatorName  | text          | text          |
| Yes      | numeric metric | indicatorvalue | IndicatorValue | number        | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = releasedate,releaseyear,year,month
```

## Data Commands

```ls
series e:gstq-ak5n d:2014-07-01T00:00:00.000Z t:releasemonth=May t:rowid="Annual Population Estimate (unrevised)20140701" t:indicatorname="Annual Population Estimate (unrevised)" m:indicatorvalue=384320

series e:gstq-ak5n d:2011-07-01T00:00:00.000Z t:releasemonth=May t:rowid="Annual Population Estimate (unrevised)20110701" t:indicatorname="Annual Population Estimate (unrevised)" m:indicatorvalue=360740

series e:gstq-ak5n d:2012-07-01T00:00:00.000Z t:releasemonth=May t:rowid="Annual Population Estimate (unrevised)20120701" t:indicatorname="Annual Population Estimate (unrevised)" m:indicatorvalue=369250
```

## Meta Commands

```ls
metric m:indicatorvalue p:integer l:IndicatorValue t:dataTypeName=number

entity e:gstq-ak5n l:"Annual Population Estimates (2012 - Present)" t:attribution="U.S. Census Bureau" t:url=https://data.nola.gov/api/views/gstq-ak5n

property e:gstq-ak5n t:meta.view v:id=gstq-ak5n v:category="Economy and Workforce" v:attributionLink=http://www.census.gov/ v:averageRating=0 v:name="Annual Population Estimates (2012 - Present)" v:attribution="U.S. Census Bureau"

property e:gstq-ak5n t:meta.view.license v:name="Public Domain"

property e:gstq-ak5n t:meta.view.owner v:id=ii98-542e v:screenName=mschigoda v:displayName=mschigoda

property e:gstq-ak5n t:meta.view.tableauthor v:id=ii98-542e v:screenName=mschigoda v:roleName=publisher v:displayName=mschigoda

property e:gstq-ak5n t:meta.view.metadata.custom_fields.common_core v:Contact_Email=data@nola.gov
```

## Top Records

```ls
| rowid                                          | date                | month | year | releasedate         | releasemonth | releaseyear | indicatorname                          | indicatorvalue | 
| ============================================== | =================== | ===== | ==== | =================== | ============ | =========== | ====================================== | ============== | 
| Annual Population Estimate (unrevised)20140701 | 2014-07-01T00:00:00 | July  | 2014 | 2015-05-01T00:00:00 | May          | 2015        | Annual Population Estimate (unrevised) | 384320         | 
| Annual Population Estimate (unrevised)20110701 | 2011-07-01T00:00:00 | July  | 2011 | 2012-05-01T00:00:00 | May          | 2012        | Annual Population Estimate (unrevised) | 360740         | 
| Annual Population Estimate (unrevised)20120701 | 2012-07-01T00:00:00 | July  | 2012 | 2013-05-01T00:00:00 | May          | 2013        | Annual Population Estimate (unrevised) | 369250         | 
| Annual Population Estimate (unrevised)20130701 | 2013-07-01T00:00:00 | July  | 2013 | 2014-05-01T00:00:00 | May          | 2014        | Annual Population Estimate (unrevised) | 378715         | 
```