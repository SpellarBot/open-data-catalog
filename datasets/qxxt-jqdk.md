# Income Quintiles (2005 - Present)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/income-quintiles-2005-present-bedc1) |
| Metadata | [Link](https://data.nola.gov/api/views/qxxt-jqdk) |
| Data: JSON | [100 Rows](https://data.nola.gov/api/views/qxxt-jqdk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.nola.gov/api/views/qxxt-jqdk/rows.csv?max_rows=100) |
| Host | data.nola.gov |
| Id | qxxt-jqdk |
| Name | Income Quintiles (2005 - Present) |
| Attribution | U.S. Census Bureau |
| Category | Economy and Workforce |
| Tags | resultsnola |
| Created | 2015-10-13T21:26:51Z |
| Publication Date | 2015-10-13T21:53:14Z |

## Description

This dataset is created by the City's Office of Performance and Accountability using data on household income from the U.S. Census Bureau's Public Use Microdata Samples. It includes data for the following cities: Tampa, Florida; Memphis, Tennessee; Louisville, Kentucky; Nashville, Tennessee; Raleigh, North Carolina; Atlanta, Georgia; Baton Rouge, Louisiana; New Orleans, Louisiana. This data is compiled annually beginning in 2005.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type     | Render Type   |
| ======== | ============== | ============== | ============== | ============= | ============= |
| Yes      | series tag     | rowid          | RowID          | text          | text          |
| Yes      | time           | date           | Date           | calendar_date | calendar_date |
| No       |                | year           | Year           | number        | number        |
| Yes      | series tag     | location       | Location       | text          | text          |
| Yes      | series tag     | indicatorname  | IndicatorName  | text          | text          |
| Yes      | numeric metric | indicatorvalue | IndicatorValue | number        | number        |
| Yes      | numeric metric | indicatororder | IndicatorOrder | number        | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = year
```

## Data Commands

```ls
series e:qxxt-jqdk d:2005-01-01T00:00:00.000Z t:location="Atlanta, GA" t:rowid="Atlanta, GA_1_2005" t:indicatorname="Percent of Households in Low Income Quintile (<$22,150)" m:indicatorvalue=27 m:indicatororder=1

series e:qxxt-jqdk d:2005-01-01T00:00:00.000Z t:location="Atlanta, GA" t:rowid="Atlanta, GA_2_2005" t:indicatorname="Percent of Households in Mid-Low Income Quintile ($22,150-$41,500)" m:indicatorvalue=18 m:indicatororder=2

series e:qxxt-jqdk d:2005-01-01T00:00:00.000Z t:location="Atlanta, GA" t:rowid="Atlanta, GA_3_2005" t:indicatorname="Percent of households in Middle Income Quintile ($41,500-$66,000)" m:indicatorvalue=16 m:indicatororder=3
```

## Meta Commands

```ls
metric m:indicatorvalue p:integer l:IndicatorValue t:dataTypeName=number

metric m:indicatororder p:integer l:IndicatorOrder t:dataTypeName=number

entity e:qxxt-jqdk l:"Income Quintiles (2005 - Present)" t:attribution="U.S. Census Bureau" t:url=https://data.nola.gov/api/views/qxxt-jqdk

property e:qxxt-jqdk t:meta.view v:id=qxxt-jqdk v:category="Economy and Workforce" v:attributionLink=http://www.census.gov/ v:averageRating=0 v:name="Income Quintiles (2005 - Present)" v:attribution="U.S. Census Bureau"

property e:qxxt-jqdk t:meta.view.owner v:id=ii98-542e v:screenName=mschigoda v:displayName=mschigoda

property e:qxxt-jqdk t:meta.view.tableauthor v:id=ii98-542e v:screenName=mschigoda v:roleName=publisher v:displayName=mschigoda

property e:qxxt-jqdk t:meta.view.metadata.custom_fields.common_core v:Contact_Email=data@nola.gov
```

## Top Records

```ls
| rowid                  | date                | year | location        | indicatorname                                                        | indicatorvalue | indicatororder | 
| ====================== | =================== | ==== | =============== | ==================================================================== | ============== | ============== | 
| Atlanta, GA_1_2005     | 2005-01-01T00:00:00 | 2005 | Atlanta, GA     | Percent of Households in Low Income Quintile (<$22,150)              | 27             | 1              | 
| Atlanta, GA_2_2005     | 2005-01-01T00:00:00 | 2005 | Atlanta, GA     | Percent of Households in Mid-Low Income Quintile ($22,150-$41,500)   | 18             | 2              | 
| Atlanta, GA_3_2005     | 2005-01-01T00:00:00 | 2005 | Atlanta, GA     | Percent of households in Middle Income Quintile ($41,500-$66,000)    | 16             | 3              | 
| Atlanta, GA_4_2005     | 2005-01-01T00:00:00 | 2005 | Atlanta, GA     | Percent of households in Mid-High Income Quintile ($66,000-$106,329) | 16             | 4              | 
| Atlanta, GA_5_2005     | 2005-01-01T00:00:00 | 2005 | Atlanta, GA     | Percent of households in High Income Quintile (>$106,330)            | 23             | 5              | 
| Baton Rouge, LA_1_2005 | 2005-01-01T00:00:00 | 2005 | Baton Rouge, LA | Percent of Households in Low Income Quintile (<$22,150)              | 33             | 1              | 
| Baton Rouge, LA_2_2005 | 2005-01-01T00:00:00 | 2005 | Baton Rouge, LA | Percent of Households in Mid-Low Income Quintile ($22,150-$41,500)   | 23             | 2              | 
| Baton Rouge, LA_3_2005 | 2005-01-01T00:00:00 | 2005 | Baton Rouge, LA | Percent of households in Middle Income Quintile ($41,500-$66,000)    | 16             | 3              | 
| Baton Rouge, LA_4_2005 | 2005-01-01T00:00:00 | 2005 | Baton Rouge, LA | Percent of households in Mid-High Income Quintile ($66,000-$106,329) | 15             | 4              | 
| Baton Rouge, LA_5_2005 | 2005-01-01T00:00:00 | 2005 | Baton Rouge, LA | Percent of households in High Income Quintile (>$106,330)            | 14             | 5              | 
```