# Structure Fires By Year (2002 - Present)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/structure-fires-by-year-2014-present) |
| Metadata | [Link](https://data.nola.gov/api/views/dngg-bnrg) |
| Data: JSON | [100 Rows](https://data.nola.gov/api/views/dngg-bnrg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.nola.gov/api/views/dngg-bnrg/rows.csv?max_rows=100) |
| Host | data.nola.gov |
| Id | dngg-bnrg |
| Name | Structure Fires By Year (2002 - Present) |
| Attribution | City of New Orleans |
| Category | Public Safety and Preparedness |
| Tags | resultsnola |
| Created | 2016-02-19T19:29:53Z |
| Publication Date | 2016-02-22T17:16:35Z |

## Description

This data on structure fires is reported on an annual basis from 2002 to present by the New Orleans Fire Department.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type     | Render Type   |
| ======== | ============== | ============== | ============== | ============= | ============= |
| Yes      | series tag     | rowid          | rowID          | text          | text          |
| No       |                | year           | year           | number        | number        |
| Yes      | time           | date           | date           | calendar_date | calendar_date |
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
Excluded Fields = year
```

## Data Commands

```ls
series e:dngg-bnrg d:2002-01-01T00:00:00.000Z t:rowid="Structure fires2002" t:indicatorname="Structure fires" m:indicatorvalue=746

series e:dngg-bnrg d:2003-01-01T00:00:00.000Z t:rowid="Structure fires2003" t:indicatorname="Structure fires" m:indicatorvalue=707

series e:dngg-bnrg d:2004-01-01T00:00:00.000Z t:rowid="Structure fires2004" t:indicatorname="Structure fires" m:indicatorvalue=682
```

## Meta Commands

```ls
metric m:indicatorvalue p:integer l:IndicatorValue t:dataTypeName=number

entity e:dngg-bnrg l:"Structure Fires By Year (2002 - Present)" t:attribution="City of New Orleans" t:url=https://data.nola.gov/api/views/dngg-bnrg

property e:dngg-bnrg t:meta.view v:id=dngg-bnrg v:category="Public Safety and Preparedness" v:attributionLink=http://www.nola.gov/nofd/ v:averageRating=0 v:name="Structure Fires By Year (2002 - Present)" v:attribution="City of New Orleans"

property e:dngg-bnrg t:meta.view.owner v:id=ii98-542e v:screenName=mschigoda v:displayName=mschigoda

property e:dngg-bnrg t:meta.view.tableauthor v:id=ii98-542e v:screenName=mschigoda v:roleName=publisher v:displayName=mschigoda

property e:dngg-bnrg t:meta.view.metadata.custom_fields.common_core v:Contact_Email=data@nola.gov
```

## Top Records

```ls
| rowid               | year | date                | indicatorname   | indicatorvalue | 
| =================== | ==== | =================== | =============== | ============== | 
| Structure fires2002 | 2002 | 2002-01-01T00:00:00 | Structure fires | 746            | 
| Structure fires2003 | 2003 | 2003-01-01T00:00:00 | Structure fires | 707            | 
| Structure fires2004 | 2004 | 2004-01-01T00:00:00 | Structure fires | 682            | 
| Structure fires2005 | 2005 | 2005-01-01T00:00:00 | Structure fires | 587            | 
| Structure fires2006 | 2006 | 2006-01-01T00:00:00 | Structure fires | 554            | 
| Structure fires2007 | 2007 | 2007-01-01T00:00:00 | Structure fires | 548            | 
| Structure fires2008 | 2008 | 2008-01-01T00:00:00 | Structure fires | 526            | 
| Structure fires2009 | 2009 | 2009-01-01T00:00:00 | Structure fires | 460            | 
| Structure fires2010 | 2010 | 2010-01-01T00:00:00 | Structure fires | 403            | 
| Structure fires2011 | 2011 | 2011-01-01T00:00:00 | Structure fires | 370            | 
```