# City Streetlights Retrofitted With LED Technology By Month (2012 - Present)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/city-streetlights-retrofitted-with-led-technology-by-month-2012-present) |
| Metadata | [Link](https://data.nola.gov/api/views/gvn7-pxhz) |
| Data: JSON | [100 Rows](https://data.nola.gov/api/views/gvn7-pxhz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.nola.gov/api/views/gvn7-pxhz/rows.csv?max_rows=100) |
| Host | data.nola.gov |
| Id | gvn7-pxhz |
| Name | City Streetlights Retrofitted With LED Technology By Month (2012 - Present) |
| Attribution | City of New Orleans |
| Category | Transportation and Infrastructure |
| Tags | resultsnola |
| Created | 2016-02-12T17:06:04Z |
| Publication Date | 2016-02-25T22:27:32Z |

## Description

This data includes city streetlights that have been retrofitted with LED technology aggregated by month.

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type     | Render Type   |
| ======== | ============== | ======================== | ======================== | ============= | ============= |
| Yes      | series tag     | rowid                    | RowID                    | text          | text          |
| No       |                | year                     | Year                     | number        | number        |
| No       |                | month                    | Month                    | text          | text          |
| Yes      | time           | date                     | Date                     | calendar_date | calendar_date |
| Yes      | series tag     | indicatorname            | IndicatorName            | text          | text          |
| Yes      | numeric metric | indicatorvalue           | IndicatorValue           | number        | number        |
| No       |                | date_label               | Date label               | text          | text          |
| Yes      | numeric metric | cumulativeindicatorvalue | CumulativeIndicatorValue | number        | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = date_label,year,month
```

## Data Commands

```ls
series e:gvn7-pxhz d:2012-01-01T00:00:00.000Z t:rowid="City streeetlights retrofitted with LED technology2012Jan" t:indicatorname="City streeetlights retrofitted with LED technology" m:cumulativeindicatorvalue=0 m:indicatorvalue=0

series e:gvn7-pxhz d:2012-02-01T00:00:00.000Z t:rowid="City streeetlights retrofitted with LED technology2012Feb" t:indicatorname="City streeetlights retrofitted with LED technology" m:cumulativeindicatorvalue=0 m:indicatorvalue=0

series e:gvn7-pxhz d:2012-03-01T00:00:00.000Z t:rowid="City streeetlights retrofitted with LED technology2012Mar" t:indicatorname="City streeetlights retrofitted with LED technology" m:cumulativeindicatorvalue=0 m:indicatorvalue=0
```

## Meta Commands

```ls
metric m:indicatorvalue p:integer l:IndicatorValue t:dataTypeName=number

metric m:cumulativeindicatorvalue p:integer l:CumulativeIndicatorValue t:dataTypeName=number

entity e:gvn7-pxhz l:"City Streetlights Retrofitted With LED Technology By Month (2012 - Present)" t:attribution="City of New Orleans" t:url=https://data.nola.gov/api/views/gvn7-pxhz

property e:gvn7-pxhz t:meta.view v:id=gvn7-pxhz v:category="Transportation and Infrastructure" v:attributionLink=http://www.nola.gov/dpw/ v:averageRating=0 v:name="City Streetlights Retrofitted With LED Technology By Month (2012 - Present)" v:attribution="City of New Orleans"

property e:gvn7-pxhz t:meta.view.owner v:id=ii98-542e v:screenName=mschigoda v:displayName=mschigoda

property e:gvn7-pxhz t:meta.view.tableauthor v:id=ii98-542e v:screenName=mschigoda v:roleName=publisher v:displayName=mschigoda

property e:gvn7-pxhz t:meta.view.metadata.custom_fields.common_core v:Contact_Email=data@nola.gov
```

## Top Records

```ls
| rowid                                                     | year | month | date                | indicatorname                                      | indicatorvalue | date_label | cumulativeindicatorvalue | 
| ========================================================= | ==== | ===== | =================== | ================================================== | ============== | ========== | ======================== | 
| City streeetlights retrofitted with LED technology2012Jan | 2012 | Jan   | 2012-01-01T00:00:00 | City streeetlights retrofitted with LED technology | 0              | Jan 2012   | 0                        | 
| City streeetlights retrofitted with LED technology2012Feb | 2012 | Feb   | 2012-02-01T00:00:00 | City streeetlights retrofitted with LED technology | 0              | Feb 2012   | 0                        | 
| City streeetlights retrofitted with LED technology2012Mar | 2012 | Mar   | 2012-03-01T00:00:00 | City streeetlights retrofitted with LED technology | 0              | Mar 2012   | 0                        | 
| City streeetlights retrofitted with LED technology2012Apr | 2012 | Apr   | 2012-04-01T00:00:00 | City streeetlights retrofitted with LED technology | 5              | Apr 2012   | 5                        | 
| City streeetlights retrofitted with LED technology2012May | 2012 | May   | 2012-05-01T00:00:00 | City streeetlights retrofitted with LED technology | 0              | May 2012   | 5                        | 
| City streeetlights retrofitted with LED technology2012Jun | 2012 | Jun   | 2012-06-01T00:00:00 | City streeetlights retrofitted with LED technology | 0              | Jun 2012   | 5                        | 
| City streeetlights retrofitted with LED technology2012Jul | 2012 | Jul   | 2012-07-01T00:00:00 | City streeetlights retrofitted with LED technology | 0              | Jul 2012   | 5                        | 
| City streeetlights retrofitted with LED technology2012Aug | 2012 | Aug   | 2012-08-01T00:00:00 | City streeetlights retrofitted with LED technology | 0              | Aug 2012   | 5                        | 
| City streeetlights retrofitted with LED technology2012Sep | 2012 | Sep   | 2012-09-01T00:00:00 | City streeetlights retrofitted with LED technology | 0              | Sep 2012   | 5                        | 
| City streeetlights retrofitted with LED technology2012Oct | 2012 | Oct   | 2012-10-01T00:00:00 | City streeetlights retrofitted with LED technology | 19             | Oct 2012   | 24                       | 
```