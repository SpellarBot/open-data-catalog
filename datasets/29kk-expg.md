# Unemployment Rate (2005- Present)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/unemployment-rate-2005-present) |
| Metadata | [Link](https://data.nola.gov/api/views/29kk-expg) |
| Data: JSON | [100 Rows](https://data.nola.gov/api/views/29kk-expg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.nola.gov/api/views/29kk-expg/rows.csv?max_rows=100) |
| Host | data.nola.gov |
| Id | 29kk-expg |
| Name | Unemployment Rate (2005- Present) |
| Attribution | Bureau of Labor Statistics |
| Category | Economy and Workforce |
| Tags | resultsnola |
| Created | 2015-07-10T17:22:04Z |
| Publication Date | 2015-09-15T16:15:05Z |

## Description

This unemployment rate data comes from the Bureau of Labot Statistics Local Area Unemployment Statistics (LAUS), which are published on a monthly basis.  It is not seasonally adjusted. It includes data for the following counties: Orleans Parish, LA (New Orleans); Oklahoma County, OK (Oklahoma City); Hillsborough County, FL (Tampa); Wake County, NC (Raleigh); Fulton County, GA (Atlanta); Miami-Dade County, FL (Miami); Davidson County, TN (Nashville); Shelby County, TN (Memphis); Jefferson County, KY (Louisiville). This data covers the time period of 2005 to present.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type     | Render Type   |
| ======== | ============== | ============== | ============== | ============= | ============= |
| Yes      | series tag     | rowid          | RowID          | text          | text          |
| Yes      | time           | date           | Date           | calendar_date | calendar_date |
| No       |                | month          | Month          | text          | text          |
| No       |                | year           | Year           | number        | number        |
| Yes      | series tag     | location       | Location       | text          | text          |
| Yes      | series tag     | indicatorname  | IndicatorName  | text          | text          |
| Yes      | numeric metric | indicatorvalue | IndicatorValue | percent       | percent       |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = year,month
```

## Data Commands

```ls
series e:29kk-expg d:2005-01-01T00:00:00.000Z t:location=BenchmarkAverage t:rowid="Unemployment rate (annual average)BenchmarkAverage20050101" t:indicatorname="Unemployment rate (annual average)" m:indicatorvalue=5.0037037037037

series e:29kk-expg d:2006-01-01T00:00:00.000Z t:location=BenchmarkAverage t:rowid="Unemployment rate (annual average)BenchmarkAverage20060101" t:indicatorname="Unemployment rate (annual average)" m:indicatorvalue=4.33611111111111

series e:29kk-expg d:2007-01-01T00:00:00.000Z t:location=BenchmarkAverage t:rowid="Unemployment rate (annual average)BenchmarkAverage20070101" t:indicatorname="Unemployment rate (annual average)" m:indicatorvalue=4.23981481481481
```

## Meta Commands

```ls
metric m:indicatorvalue p:float l:IndicatorValue t:dataTypeName=percent

entity e:29kk-expg l:"Unemployment Rate (2005- Present)" t:attribution="Bureau of Labor Statistics" t:url=https://data.nola.gov/api/views/29kk-expg

property e:29kk-expg t:meta.view v:id=29kk-expg v:category="Economy and Workforce" v:attributionLink=http://www.bls.gov/home.htm v:averageRating=0 v:name="Unemployment Rate (2005- Present)" v:attribution="Bureau of Labor Statistics"

property e:29kk-expg t:meta.view.owner v:id=ii98-542e v:screenName=mschigoda v:displayName=mschigoda

property e:29kk-expg t:meta.view.tableauthor v:id=ii98-542e v:screenName=mschigoda v:roleName=publisher v:displayName=mschigoda

property e:29kk-expg t:meta.view.metadata.custom_fields.common_core v:Contact_Email=data@nola.gov
```

## Top Records

```ls
| rowid                                                      | date                | month | year | location         | indicatorname                      | indicatorvalue   | 
| ========================================================== | =================== | ===== | ==== | ================ | ================================== | ================ | 
| Unemployment rate (annual average)BenchmarkAverage20050101 | 2005-01-01T00:00:00 |       | 2005 | BenchmarkAverage | Unemployment rate (annual average) | 5.0037037037037  | 
| Unemployment rate (annual average)BenchmarkAverage20060101 | 2006-01-01T00:00:00 |       | 2006 | BenchmarkAverage | Unemployment rate (annual average) | 4.33611111111111 | 
| Unemployment rate (annual average)BenchmarkAverage20070101 | 2007-01-01T00:00:00 |       | 2007 | BenchmarkAverage | Unemployment rate (annual average) | 4.23981481481481 | 
| Unemployment rate (annual average)BenchmarkAverage20080101 | 2008-01-01T00:00:00 |       | 2008 | BenchmarkAverage | Unemployment rate (annual average) | 5.50833333333333 | 
| Unemployment rate (annual average)BenchmarkAverage20090101 | 2009-01-01T00:00:00 |       | 2009 | BenchmarkAverage | Unemployment rate (annual average) | 8.97222222222222 | 
| Unemployment rate (annual average)BenchmarkAverage20100101 | 2010-01-01T00:00:00 |       | 2010 | BenchmarkAverage | Unemployment rate (annual average) | 9.13981481481481 | 
| Unemployment rate (annual average)BenchmarkAverage20110101 | 2011-01-01T00:00:00 |       | 2011 | BenchmarkAverage | Unemployment rate (annual average) | 8.51111111111111 | 
| Unemployment rate (annual average)BenchmarkAverage20120101 | 2012-01-01T00:00:00 |       | 2012 | BenchmarkAverage | Unemployment rate (annual average) | 7.44444444444444 | 
| Unemployment rate (annual average)BenchmarkAverage20130101 | 2013-01-01T00:00:00 |       | 2013 | BenchmarkAverage | Unemployment rate (annual average) | 6.89074074074074 | 
| Unemployment rate (annual average)BenchmarkAverage20140101 | 2014-01-01T00:00:00 |       | 2014 | BenchmarkAverage | Unemployment rate (annual average) | 5.95185185185185 | 
```