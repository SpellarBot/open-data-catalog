# Calculated Library Indicators For Results NOLA

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/calculated-library-indicators-for-results-nola-be62d) |
| Metadata | [Link](https://data.nola.gov/api/views/s995-ndgk) |
| Data: JSON | [100 Rows](https://data.nola.gov/api/views/s995-ndgk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.nola.gov/api/views/s995-ndgk/rows.csv?max_rows=100) |
| Host | data.nola.gov |
| Id | s995-ndgk |
| Name | Calculated Library Indicators For Results NOLA |
| Attribution | New Orleans Public Library |
| Category | Recreation and Culture |
| Tags | resultsnola |
| Created | 2016-01-19T21:00:11Z |
| Publication Date | 2016-01-28T22:40:02Z |

## Description

This dataset includes data for ResultsNOLA indicators that were calculated based on the following source datasets: “Library Cardholders (2012 - present)” and “Annual population estimates (2012 – present)."

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type     | Render Type   |
| ======== | ============== | ============== | ============== | ============= | ============= |
| Yes      | series tag     | rowid          | RowID          | text          | text          |
| Yes      | time           | date           | Date           | calendar_date | calendar_date |
| No       |                | month          | Month          | text          | text          |
| No       |                | year           | Year           | number        | number        |
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
Excluded Fields = year,month
```

## Data Commands

```ls
series e:s995-ndgk d:2012-01-01T00:00:00.000Z t:rowid="Percent of the pop. that are library cardholders (year-to-date)201201" t:indicatorname="Percent of the pop. that are library cardholders (year-to-date)" m:indicatorvalue=14.71

series e:s995-ndgk d:2012-01-01T00:00:00.000Z t:rowid="Percent of the pop. that are library cardholders (current month)201201" t:indicatorname="Percent of the pop. that are library cardholders (current month)" m:indicatorvalue=14.71

series e:s995-ndgk d:2012-02-01T00:00:00.000Z t:rowid="Percent of the pop. that are library cardholders (year-to-date)201202" t:indicatorname="Percent of the pop. that are library cardholders (year-to-date)" m:indicatorvalue=14.818
```

## Meta Commands

```ls
metric m:indicatorvalue p:float l:IndicatorValue t:dataTypeName=number

entity e:s995-ndgk l:"Calculated Library Indicators For Results NOLA" t:attribution="New Orleans Public Library" t:url=https://data.nola.gov/api/views/s995-ndgk

property e:s995-ndgk t:meta.view v:id=s995-ndgk v:category="Recreation and Culture" v:attributionLink=http://www.neworleanspubliclibrary.org v:averageRating=0 v:name="Calculated Library Indicators For Results NOLA" v:attribution="New Orleans Public Library"

property e:s995-ndgk t:meta.view.owner v:id=ii98-542e v:screenName=mschigoda v:displayName=mschigoda

property e:s995-ndgk t:meta.view.tableauthor v:id=ii98-542e v:screenName=mschigoda v:roleName=publisher v:displayName=mschigoda

property e:s995-ndgk t:meta.view.metadata.custom_fields.common_core v:Contact_Email=data@nola.gov
```

## Top Records

```ls
| rowid                                                                  | date                | month    | year | indicatorname                                                    | indicatorvalue | 
| ====================================================================== | =================== | ======== | ==== | ================================================================ | ============== | 
| Percent of the pop. that are library cardholders (year-to-date)201201  | 2012-01-01T00:00:00 | January  | 2012 | Percent of the pop. that are library cardholders (year-to-date)  | 14.71          | 
| Percent of the pop. that are library cardholders (current month)201201 | 2012-01-01T00:00:00 | January  | 2012 | Percent of the pop. that are library cardholders (current month) | 14.71          | 
| Percent of the pop. that are library cardholders (year-to-date)201202  | 2012-02-01T00:00:00 | February | 2012 | Percent of the pop. that are library cardholders (year-to-date)  | 14.818         | 
| Percent of the pop. that are library cardholders (current month)201202 | 2012-02-01T00:00:00 | February | 2012 | Percent of the pop. that are library cardholders (current month) | 14.926         | 
| Percent of the pop. that are library cardholders (year-to-date)201203  | 2012-03-01T00:00:00 | March    | 2012 | Percent of the pop. that are library cardholders (year-to-date)  | 14.9005        | 
| Percent of the pop. that are library cardholders (current month)201203 | 2012-03-01T00:00:00 | March    | 2012 | Percent of the pop. that are library cardholders (current month) | 15.0654        | 
| Percent of the pop. that are library cardholders (year-to-date)201204  | 2012-04-01T00:00:00 | April    | 2012 | Percent of the pop. that are library cardholders (year-to-date)  | 14.9893        | 
| Percent of the pop. that are library cardholders (current month)201204 | 2012-04-01T00:00:00 | April    | 2012 | Percent of the pop. that are library cardholders (current month) | 15.2559        | 
| Percent of the pop. that are library cardholders (year-to-date)201205  | 2012-05-01T00:00:00 | May      | 2012 | Percent of the pop. that are library cardholders (year-to-date)  | 15.2071        | 
| Percent of the pop. that are library cardholders (current month)201205 | 2012-05-01T00:00:00 | May      | 2012 | Percent of the pop. that are library cardholders (current month) | 16.0781        | 
```