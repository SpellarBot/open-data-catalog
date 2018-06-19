# Library Cardholders (2012 - Present)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/library-cardholders-2012-present) |
| Metadata | [Link](https://data.nola.gov/api/views/vsuc-xd5b) |
| Data: JSON | [100 Rows](https://data.nola.gov/api/views/vsuc-xd5b/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.nola.gov/api/views/vsuc-xd5b/rows.csv?max_rows=100) |
| Host | data.nola.gov |
| Id | vsuc-xd5b |
| Name | Library Cardholders (2012 - Present) |
| Attribution | New Orleans Public Library |
| Category | Recreation and Culture |
| Tags | resultsnola |
| Created | 2015-06-26T21:15:40Z |
| Publication Date | 2016-01-28T22:30:18Z |

## Description

This data set includes data on library cardholders who registered in the past month, library cardholders who used their card during the last month, and library cardholders that used their card in the last three years. It includes monthly data beginning with January 2012.

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
series e:vsuc-xd5b d:2012-01-01T00:00:00.000Z t:rowid="Number of cardholders who registered in the past month201201" t:indicatorname="Number of cardholders who registered in the past month" m:indicatorvalue=1510

series e:vsuc-xd5b d:2012-01-01T00:00:00.000Z t:rowid="Number of cardholders who used their card during the last month201201" t:indicatorname="Number of cardholders who used their card during the last month" m:indicatorvalue=6445

series e:vsuc-xd5b d:2012-01-01T00:00:00.000Z t:rowid="Number of cardholders who used their card in the last three years201201" t:indicatorname="Number of cardholders who used their card in the last three years" m:indicatorvalue=53065
```

## Meta Commands

```ls
metric m:indicatorvalue p:integer l:IndicatorValue t:dataTypeName=number

entity e:vsuc-xd5b l:"Library Cardholders (2012 - Present)" t:attribution="New Orleans Public Library" t:url=https://data.nola.gov/api/views/vsuc-xd5b

property e:vsuc-xd5b t:meta.view v:id=vsuc-xd5b v:category="Recreation and Culture" v:attributionLink=http://www.neworleanspubliclibrary.org v:averageRating=0 v:name="Library Cardholders (2012 - Present)" v:attribution="New Orleans Public Library"

property e:vsuc-xd5b t:meta.view.license v:name="Public Domain"

property e:vsuc-xd5b t:meta.view.owner v:id=ii98-542e v:screenName=mschigoda v:displayName=mschigoda

property e:vsuc-xd5b t:meta.view.tableauthor v:id=ii98-542e v:screenName=mschigoda v:roleName=publisher v:displayName=mschigoda

property e:vsuc-xd5b t:meta.view.metadata.custom_fields.common_core v:Contact_Email=data@nola.gov
```

## Top Records

```ls
| rowid                                                                   | date                | month    | year | indicatorname                                                     | indicatorvalue | 
| ======================================================================= | =================== | ======== | ==== | ================================================================= | ============== | 
| Number of cardholders who registered in the past month201201            | 2012-01-01T00:00:00 | January  | 2012 | Number of cardholders who registered in the past month            | 1510           | 
| Number of cardholders who used their card during the last month201201   | 2012-01-01T00:00:00 | January  | 2012 | Number of cardholders who used their card during the last month   | 6445           | 
| Number of cardholders who used their card in the last three years201201 | 2012-01-01T00:00:00 | January  | 2012 | Number of cardholders who used their card in the last three years | 53065          | 
| Number of cardholders who registered in the past month201202            | 2012-02-01T00:00:00 | February | 2012 | Number of cardholders who registered in the past month            | 1174           | 
| Number of cardholders who used their card in the last three years201202 | 2012-02-01T00:00:00 | February | 2012 | Number of cardholders who used their card in the last three years | 53844          | 
| Number of cardholders who used their card during the last month201202   | 2012-02-01T00:00:00 | February | 2012 | Number of cardholders who used their card during the last month   | 5634           | 
| Number of cardholders who used their card in the last three years201203 | 2012-03-01T00:00:00 | March    | 2012 | Number of cardholders who used their card in the last three years | 54347          | 
| Number of cardholders who used their card during the last month201203   | 2012-03-01T00:00:00 | March    | 2012 | Number of cardholders who used their card during the last month   | 6792           | 
| Number of cardholders who registered in the past month201203            | 2012-03-01T00:00:00 | March    | 2012 | Number of cardholders who registered in the past month            | 1851           | 
| Number of cardholders who used their card in the last three years201204 | 2012-04-01T00:00:00 | April    | 2012 | Number of cardholders who used their card in the last three years | 55034          | 
```