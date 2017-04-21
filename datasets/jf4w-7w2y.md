# City Streetlights Retrofitted With LED Technology By Year (2012 - Present)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/city-streetlights-retrofitted-with-led-technology-by-year-2012-present) |
| Metadata | [Link](https://data.nola.gov/api/views/jf4w-7w2y) |
| Data: JSON | [100 Rows](https://data.nola.gov/api/views/jf4w-7w2y/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.nola.gov/api/views/jf4w-7w2y/rows.csv?max_rows=100) |
| Host | data.nola.gov |
| Id | jf4w-7w2y |
| Name | City Streetlights Retrofitted With LED Technology By Year (2012 - Present) |
| Attribution | City of New Orleans |
| Category | Transportation and Infrastructure |
| Tags | resultsnola |
| Created | 2016-02-26T18:52:21Z |
| Publication Date | 2016-02-26T20:20:07Z |

## Description

This data includes city streetlights that have been retrofitted with LED technology each year

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type | Render Type |
| ======== | ============== | ======================== | ======================== | ========= | =========== |
| Yes      | time           | year                     | Year                     | number    | number      |
| Yes      | series tag     | indicatorname            | IndicatorName            | text      | text        |
| Yes      | numeric metric | indicatorvalue           | IndicatorValue           | number    | number      |
| Yes      | numeric metric | cumulativeindicatorvalue | CumulativeIndicatorValue | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:jf4w-7w2y d:2012-01-01T00:00:00.000Z t:indicatorname="City streeetlights retrofitted with LED technology" m:cumulativeindicatorvalue=1499 m:indicatorvalue=1499

series e:jf4w-7w2y d:2013-01-01T00:00:00.000Z t:indicatorname="City streeetlights retrofitted with LED technology" m:cumulativeindicatorvalue=13249 m:indicatorvalue=11750

series e:jf4w-7w2y d:2014-01-01T00:00:00.000Z t:indicatorname="City streeetlights retrofitted with LED technology" m:cumulativeindicatorvalue=36907 m:indicatorvalue=23658
```

## Meta Commands

```ls
metric m:indicatorvalue p:integer l:IndicatorValue t:dataTypeName=number

metric m:cumulativeindicatorvalue p:integer l:CumulativeIndicatorValue t:dataTypeName=number

entity e:jf4w-7w2y l:"City Streetlights Retrofitted With LED Technology By Year (2012 - Present)" t:attribution="City of New Orleans" t:url=https://data.nola.gov/api/views/jf4w-7w2y

property e:jf4w-7w2y t:meta.view v:id=jf4w-7w2y v:category="Transportation and Infrastructure" v:attributionLink=http://www.nola.gov/dpw/ v:averageRating=0 v:name="City Streetlights Retrofitted With LED Technology By Year (2012 - Present)" v:attribution="City of New Orleans"

property e:jf4w-7w2y t:meta.view.owner v:id=ii98-542e v:screenName=mschigoda v:displayName=mschigoda

property e:jf4w-7w2y t:meta.view.tableauthor v:id=ii98-542e v:screenName=mschigoda v:roleName=publisher v:displayName=mschigoda

property e:jf4w-7w2y t:meta.view.metadata.custom_fields.common_core v:Contact_Email=data@nola.gov
```

## Top Records

```ls
| year | indicatorname                                      | indicatorvalue | cumulativeindicatorvalue | 
| ==== | ================================================== | ============== | ======================== | 
| 2012 | City streeetlights retrofitted with LED technology | 1499           | 1499                     | 
| 2013 | City streeetlights retrofitted with LED technology | 11750          | 13249                    | 
| 2014 | City streeetlights retrofitted with LED technology | 23658          | 36907                    | 
| 2015 | City streeetlights retrofitted with LED technology | 4001           | 40908                    | 
```