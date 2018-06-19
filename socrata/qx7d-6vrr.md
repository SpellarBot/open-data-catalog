# Sales Tax Revenues To The City's General Fund (2003 - Present)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/sales-tax-revenues-to-the-citys-general-fund-2003-present) |
| Metadata | [Link](https://data.nola.gov/api/views/qx7d-6vrr) |
| Data: JSON | [100 Rows](https://data.nola.gov/api/views/qx7d-6vrr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.nola.gov/api/views/qx7d-6vrr/rows.csv?max_rows=100) |
| Host | data.nola.gov |
| Id | qx7d-6vrr |
| Name | Sales Tax Revenues To The City's General Fund (2003 - Present) |
| Attribution | City of New Orleans |
| Category | City Finance and Budget |
| Tags | resultsnola |
| Created | 2016-02-11T20:26:40Z |
| Publication Date | 2016-02-16T22:55:08Z |

## Description

Sales taxes received by the City include: General Sales Use Tax, Motor Vehicle Tax, and Hotel/Motel Tax. This data includes all three types for the City of New Orleans on an annual basis. This data comes from the City's Comprehensive Annual Financial Report (CAFR).

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
series e:qx7d-6vrr d:2014-01-01T00:00:00.000Z t:rowid="Sales tax revenues to the City's General Fund2014" t:indicatorname="Sales tax revenues to the City's General Fund" m:indicatorvalue=193183000

series e:qx7d-6vrr d:2013-01-01T00:00:00.000Z t:rowid="Sales tax revenues to the City's General Fund2013" t:indicatorname="Sales tax revenues to the City's General Fund" m:indicatorvalue=176465000

series e:qx7d-6vrr d:2012-01-01T00:00:00.000Z t:rowid="Sales tax revenues to the City's General Fund2012" t:indicatorname="Sales tax revenues to the City's General Fund" m:indicatorvalue=163128000
```

## Meta Commands

```ls
metric m:indicatorvalue p:integer l:IndicatorValue t:dataTypeName=number

entity e:qx7d-6vrr l:"Sales Tax Revenues To The City's General Fund (2003 - Present)" t:attribution="City of New Orleans" t:url=https://data.nola.gov/api/views/qx7d-6vrr

property e:qx7d-6vrr t:meta.view v:id=qx7d-6vrr v:category="City Finance and Budget" v:attributionLink=http://www.nola.gov/accounting/ v:averageRating=0 v:name="Sales Tax Revenues To The City's General Fund (2003 - Present)" v:attribution="City of New Orleans"

property e:qx7d-6vrr t:meta.view.owner v:id=ii98-542e v:screenName=mschigoda v:displayName=mschigoda

property e:qx7d-6vrr t:meta.view.tableauthor v:id=ii98-542e v:screenName=mschigoda v:roleName=publisher v:displayName=mschigoda

property e:qx7d-6vrr t:meta.view.metadata.custom_fields.common_core v:Contact_Email=data@nola.gov
```

## Top Records

```ls
| rowid                                             | year | date                | indicatorname                                 | indicatorvalue | 
| ================================================= | ==== | =================== | ============================================= | ============== | 
| Sales tax revenues to the City's General Fund2014 | 2014 | 2014-01-01T00:00:00 | Sales tax revenues to the City's General Fund | 193183000      | 
| Sales tax revenues to the City's General Fund2013 | 2013 | 2013-01-01T00:00:00 | Sales tax revenues to the City's General Fund | 176465000      | 
| Sales tax revenues to the City's General Fund2012 | 2012 | 2012-01-01T00:00:00 | Sales tax revenues to the City's General Fund | 163128000      | 
| Sales tax revenues to the City's General Fund2011 | 2011 | 2011-01-01T00:00:00 | Sales tax revenues to the City's General Fund | 153955000      | 
| Sales tax revenues to the City's General Fund2010 | 2010 | 2010-01-01T00:00:00 | Sales tax revenues to the City's General Fund | 147453000      | 
| Sales tax revenues to the City's General Fund2009 | 2009 | 2009-01-01T00:00:00 | Sales tax revenues to the City's General Fund | 133868000      | 
| Sales tax revenues to the City's General Fund2008 | 2008 | 2008-01-01T00:00:00 | Sales tax revenues to the City's General Fund | 137581000      | 
| Sales tax revenues to the City's General Fund2007 | 2007 | 2007-01-01T00:00:00 | Sales tax revenues to the City's General Fund | 134114000      | 
| Sales tax revenues to the City's General Fund2006 | 2006 | 2006-01-01T00:00:00 | Sales tax revenues to the City's General Fund | 124229000      | 
| Sales tax revenues to the City's General Fund2005 | 2005 | 2005-01-01T00:00:00 | Sales tax revenues to the City's General Fund | 116339000      | 
```