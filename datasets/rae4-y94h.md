# End Of Year General Fund Fund Balance Before Assignment (2003 - Present)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/end-of-year-general-fund-fund-balance-before-assignment-2003-present) |
| Metadata | [Link](https://data.nola.gov/api/views/rae4-y94h) |
| Data: JSON | [100 Rows](https://data.nola.gov/api/views/rae4-y94h/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.nola.gov/api/views/rae4-y94h/rows.csv?max_rows=100) |
| Host | data.nola.gov |
| Id | rae4-y94h |
| Name | End Of Year General Fund Fund Balance Before Assignment (2003 - Present) |
| Attribution | City of New Orleans |
| Category | City Finance and Budget |
| Tags | resultsnola |
| Created | 2016-02-11T21:13:56Z |
| Publication Date | 2016-02-11T21:20:09Z |

## Description

The end of year General Fund fund balance before assignment is the amount of resources left at the end of the year in the general fund (beginning balance plus total revenues minus total expenditures minus adjustments). The end of year fund balance can be either: assigned, unassigned, restricted, committed, or non-spendable. This data is presented at the city-level on an annual basis.  This data comes from the City?s Comprehensive Annual Financial Report (CAFR), and includes activities related to the Library and non-major funds.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type     | Render Type   |
| ======== | ============== | ============== | ============== | ============= | ============= |
| Yes      | series tag     | rowid          | RowID          | text          | text          |
| No       |                | year           | Year           | number        | number        |
| Yes      | time           | date           | Date           | calendar_date | calendar_date |
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
series e:rae4-y94h d:2014-01-01T00:00:00.000Z t:rowid="End of year General Fund fund balance before assignment2014" t:indicatorname="End of year General Fund fund balance before assignment" m:indicatorvalue=42984000

series e:rae4-y94h d:2013-01-01T00:00:00.000Z t:rowid="End of year General Fund fund balance before assignment2013" t:indicatorname="End of year General Fund fund balance before assignment" m:indicatorvalue=16956000

series e:rae4-y94h d:2012-01-01T00:00:00.000Z t:rowid="End of year General Fund fund balance before assignment2012" t:indicatorname="End of year General Fund fund balance before assignment" m:indicatorvalue=-9336000
```

## Meta Commands

```ls
metric m:indicatorvalue p:integer l:IndicatorValue t:dataTypeName=number

entity e:rae4-y94h l:"End Of Year General Fund Fund Balance Before Assignment (2003 - Present)" t:attribution="City of New Orleans" t:url=https://data.nola.gov/api/views/rae4-y94h

property e:rae4-y94h t:meta.view v:id=rae4-y94h v:category="City Finance and Budget" v:attributionLink=http://www.nola.gov/accounting/ v:averageRating=0 v:name="End Of Year General Fund Fund Balance Before Assignment (2003 - Present)" v:attribution="City of New Orleans"

property e:rae4-y94h t:meta.view.owner v:id=ii98-542e v:screenName=mschigoda v:displayName=mschigoda

property e:rae4-y94h t:meta.view.tableauthor v:id=ii98-542e v:screenName=mschigoda v:roleName=publisher v:displayName=mschigoda

property e:rae4-y94h t:meta.view.metadata.custom_fields.common_core v:Contact_Email=data@nola.gov
```

## Top Records

```ls
| rowid                                                       | year | date                | indicatorname                                           | indicatorvalue | 
| =========================================================== | ==== | =================== | ======================================================= | ============== | 
| End of year General Fund fund balance before assignment2014 | 2014 | 2014-01-01T00:00:00 | End of year General Fund fund balance before assignment | 42984000       | 
| End of year General Fund fund balance before assignment2013 | 2013 | 2013-01-01T00:00:00 | End of year General Fund fund balance before assignment | 16956000       | 
| End of year General Fund fund balance before assignment2012 | 2012 | 2012-01-01T00:00:00 | End of year General Fund fund balance before assignment | -9336000       | 
| End of year General Fund fund balance before assignment2011 | 2011 | 2011-01-01T00:00:00 | End of year General Fund fund balance before assignment | -3717000       | 
| End of year General Fund fund balance before assignment2010 | 2010 | 2010-01-01T00:00:00 | End of year General Fund fund balance before assignment | -11061000      | 
| End of year General Fund fund balance before assignment2009 | 2009 | 2009-01-01T00:00:00 | End of year General Fund fund balance before assignment | 7936000        | 
| End of year General Fund fund balance before assignment2008 | 2008 | 2008-01-01T00:00:00 | End of year General Fund fund balance before assignment | 61015000       | 
| End of year General Fund fund balance before assignment2007 | 2007 | 2007-01-01T00:00:00 | End of year General Fund fund balance before assignment | 95194000       | 
| End of year General Fund fund balance before assignment2006 | 2006 | 2006-01-01T00:00:00 | End of year General Fund fund balance before assignment | 99828000       | 
| End of year General Fund fund balance before assignment2005 | 2005 | 2005-01-01T00:00:00 | End of year General Fund fund balance before assignment | 46307000       | 
```