# LEAP Test Passage Rates (2007 - Present)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/leap-test-passage-rates-2007-present) |
| Metadata | [Link](https://data.nola.gov/api/views/agtp-9axa) |
| Data: JSON | [100 Rows](https://data.nola.gov/api/views/agtp-9axa/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.nola.gov/api/views/agtp-9axa/rows.csv?max_rows=100) |
| Host | data.nola.gov |
| Id | agtp-9axa |
| Name | LEAP Test Passage Rates (2007 - Present) |
| Attribution | Louisiana Department of Education |
| Category | Health, Education, and Social Services |
| Created | 2015-04-28T16:53:52Z |
| Publication Date | 2015-11-03T22:35:32Z |

## Description

This data includes the percentage of students passing LEAP and iLEAP tests in Orleans Parish, East Baton Rouge Parish, and Jefferson Parish annually from 2007 to present.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type     | Render Type   |
| ======== | ============== | ============== | ============== | ============= | ============= |
| Yes      | series tag     | rowid          | RowID          | text          | text          |
| Yes      | time           | date           | Date           | calendar_date | calendar_date |
| No       |                | year           | Year           | number        | number        |
| Yes      | series tag     | location       | Location       | text          | text          |
| Yes      | series tag     | indicator      | IndicatorName  | text          | text          |
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
series e:agtp-9axa d:2007-01-01T00:00:00.000Z t:indicator="Percent of students passing LEAP and ILEAP tests" t:location="East Baton Rouge Parish, LA" t:rowid="East Baton Rouge Parish, LAPercent of students passing LEAP and ILEAP tests2007" m:indicatorvalue=47

series e:agtp-9axa d:2007-01-01T00:00:00.000Z t:indicator="Percent of students passing LEAP and ILEAP tests" t:location="Jefferson Parish, LA" t:rowid="Jefferson Parish, LAPercent of students passing LEAP and ILEAP tests2007" m:indicatorvalue=51

series e:agtp-9axa d:2007-01-01T00:00:00.000Z t:indicator="Percent of students passing LEAP and ILEAP tests" t:location="Orleans Parish, LA" t:rowid="Orleans Parish, LAPercent of students passing LEAP and ILEAP tests2007" m:indicatorvalue=37
```

## Meta Commands

```ls
metric m:indicatorvalue p:integer l:IndicatorValue t:dataTypeName=number

entity e:agtp-9axa l:"LEAP Test Passage Rates (2007 - Present)" t:attribution="Louisiana Department of Education" t:url=https://data.nola.gov/api/views/agtp-9axa

property e:agtp-9axa t:meta.view v:id=agtp-9axa v:category="Health, Education, and Social Services" v:attributionLink=http://www.louisianabelieves.com/resources/library/test-results v:averageRating=0 v:name="LEAP Test Passage Rates (2007 - Present)" v:attribution="Louisiana Department of Education"

property e:agtp-9axa t:meta.view.owner v:id=ii98-542e v:screenName=mschigoda v:displayName=mschigoda

property e:agtp-9axa t:meta.view.tableauthor v:id=ii98-542e v:screenName=mschigoda v:roleName=publisher v:displayName=mschigoda

property e:agtp-9axa t:meta.view.metadata.custom_fields.common_core v:Contact_Email=data@nola.gov
```

## Top Records

```ls
| rowid                                                                           | date                | year | location                    | indicator                                        | indicatorvalue | 
| =============================================================================== | =================== | ==== | =========================== | ================================================ | ============== | 
| East Baton Rouge Parish, LAPercent of students passing LEAP and ILEAP tests2007 | 2007-01-01T00:00:00 | 2007 | East Baton Rouge Parish, LA | Percent of students passing LEAP and ILEAP tests | 47             | 
| Jefferson Parish, LAPercent of students passing LEAP and ILEAP tests2007        | 2007-01-01T00:00:00 | 2007 | Jefferson Parish, LA        | Percent of students passing LEAP and ILEAP tests | 51             | 
| Orleans Parish, LAPercent of students passing LEAP and ILEAP tests2007          | 2007-01-01T00:00:00 | 2007 | Orleans Parish, LA          | Percent of students passing LEAP and ILEAP tests | 37             | 
| East Baton Rouge Parish, LAPercent of students passing LEAP and ILEAP tests2008 | 2008-01-01T00:00:00 | 2008 | East Baton Rouge Parish, LA | Percent of students passing LEAP and ILEAP tests | 48             | 
| Jefferson Parish, LAPercent of students passing LEAP and ILEAP tests2008        | 2008-01-01T00:00:00 | 2008 | Jefferson Parish, LA        | Percent of students passing LEAP and ILEAP tests | 53             | 
| Orleans Parish, LAPercent of students passing LEAP and ILEAP tests2008          | 2008-01-01T00:00:00 | 2008 | Orleans Parish, LA          | Percent of students passing LEAP and ILEAP tests | 40             | 
| East Baton Rouge Parish, LAPercent of students passing LEAP and ILEAP tests2009 | 2009-01-01T00:00:00 | 2009 | East Baton Rouge Parish, LA | Percent of students passing LEAP and ILEAP tests | 54             | 
| Jefferson Parish, LAPercent of students passing LEAP and ILEAP tests2009        | 2009-01-01T00:00:00 | 2009 | Jefferson Parish, LA        | Percent of students passing LEAP and ILEAP tests | 57             | 
| Orleans Parish, LAPercent of students passing LEAP and ILEAP tests2009          | 2009-01-01T00:00:00 | 2009 | Orleans Parish, LA          | Percent of students passing LEAP and ILEAP tests | 48             | 
| East Baton Rouge Parish, LAPercent of students passing LEAP and ILEAP tests2010 | 2010-01-01T00:00:00 | 2010 | East Baton Rouge Parish, LA | Percent of students passing LEAP and ILEAP tests | 56             | 
```