# Percent of students proficient on End of Course (EOC) tests (2008-2009 - Present)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/percent-of-students-proficient-on-end-of-course-eoc-tests-2008-2009-present) |
| Metadata | [Link](https://data.nola.gov/api/views/6yfr-q2et) |
| Data: JSON | [100 Rows](https://data.nola.gov/api/views/6yfr-q2et/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.nola.gov/api/views/6yfr-q2et/rows.csv?max_rows=100) |
| Host | data.nola.gov |
| Id | 6yfr-q2et |
| Name | Percent of students proficient on End of Course (EOC) tests (2008-2009 - Present) |
| Attribution | Louisiana Department of Education |
| Category | Health, Education, and Social Services |
| Tags | resultsnola |
| Created | 2016-01-28T21:24:27Z |
| Publication Date | 2016-01-28T22:26:51Z |

## Description

This data includes the percentage of students proficient on End of Course (EOC) tests for New Orleans and Louisiana since 2008-2009.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type     | Render Type   |
| ======== | ============== | ============== | ============== | ============= | ============= |
| Yes      | series tag     | rowid          | RowID          | text          | text          |
| Yes      | series tag     | year           | Year           | text          | text          |
| No       |                | year2          | Year2          | text          | text          |
| No       |                | year3          | Year3          | number        | number        |
| Yes      | time           | date           | Date           | calendar_date | calendar_date |
| Yes      | series tag     | location       | Location       | text          | text          |
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
Excluded Fields = year3,year2
```

## Data Commands

```ls
series e:6yfr-q2et d:2009-06-01T00:00:00.000Z t:location="New Orleans" t:year=2008-2009 t:rowid="Percent of students proficient on End of Course (EOC) tests)New Orleans2008-2009" t:indicatorname="Percent of students proficient on End of Course (EOC) tests)" m:indicatorvalue=33

series e:6yfr-q2et d:2010-06-01T00:00:00.000Z t:location="New Orleans" t:year=2009-2010 t:rowid="Percent of students proficient on End of Course (EOC) tests)New Orleans2009-2010" t:indicatorname="Percent of students proficient on End of Course (EOC) tests)" m:indicatorvalue=30

series e:6yfr-q2et d:2011-06-01T00:00:00.000Z t:location="New Orleans" t:year=2010-2011 t:rowid="Percent of students proficient on End of Course (EOC) tests)New Orleans2010-2011" t:indicatorname="Percent of students proficient on End of Course (EOC) tests)" m:indicatorvalue=39
```

## Meta Commands

```ls
metric m:indicatorvalue p:integer l:IndicatorValue t:dataTypeName=number

entity e:6yfr-q2et l:"Percent of students proficient on End of Course (EOC) tests (2008-2009 - Present)" t:attribution="Louisiana Department of Education" t:url=https://data.nola.gov/api/views/6yfr-q2et

property e:6yfr-q2et t:meta.view v:id=6yfr-q2et v:category="Health, Education, and Social Services" v:attributionLink=http://www.louisianabelieves.com v:averageRating=0 v:name="Percent of students proficient on End of Course (EOC) tests (2008-2009 - Present)" v:attribution="Louisiana Department of Education"

property e:6yfr-q2et t:meta.view.owner v:id=ii98-542e v:screenName=mschigoda v:displayName=mschigoda

property e:6yfr-q2et t:meta.view.tableauthor v:id=ii98-542e v:screenName=mschigoda v:roleName=publisher v:displayName=mschigoda

property e:6yfr-q2et t:meta.view.metadata.custom_fields.common_core v:Contact_Email=data@nola.gov v:Public_Access_Level=public
```

## Top Records

```ls
| rowid                                                                            | year      | year2   | year3 | date                | location    | indicatorname                                                | indicatorvalue | 
| ================================================================================ | ========= | ======= | ===== | =================== | =========== | ============================================================ | ============== | 
| Percent of students proficient on End of Course (EOC) tests)New Orleans2008-2009 | 2008-2009 | 2008-09 | 2009  | 2009-06-01T00:00:00 | New Orleans | Percent of students proficient on End of Course (EOC) tests) | 33             | 
| Percent of students proficient on End of Course (EOC) tests)New Orleans2009-2010 | 2009-2010 | 2009-10 | 2010  | 2010-06-01T00:00:00 | New Orleans | Percent of students proficient on End of Course (EOC) tests) | 30             | 
| Percent of students proficient on End of Course (EOC) tests)New Orleans2010-2011 | 2010-2011 | 2010-11 | 2011  | 2011-06-01T00:00:00 | New Orleans | Percent of students proficient on End of Course (EOC) tests) | 39             | 
| Percent of students proficient on End of Course (EOC) tests)New Orleans2011-2012 | 2011-2012 | 2011-12 | 2012  | 2012-06-01T00:00:00 | New Orleans | Percent of students proficient on End of Course (EOC) tests) | 45             | 
| Percent of students proficient on End of Course (EOC) tests)New Orleans2012-2013 | 2012-2013 | 2012-13 | 2013  | 2013-06-01T00:00:00 | New Orleans | Percent of students proficient on End of Course (EOC) tests) | 52             | 
| Percent of students proficient on End of Course (EOC) tests)New Orleans2013-2014 | 2013-2014 | 2013-14 | 2014  | 2014-06-01T00:00:00 | New Orleans | Percent of students proficient on End of Course (EOC) tests) | 59             | 
| Percent of students proficient on End of Course (EOC) tests)New Orleans2014-2015 | 2014-2015 | 2014-15 | 2015  | 2015-06-01T00:00:00 | New Orleans | Percent of students proficient on End of Course (EOC) tests) | 61             | 
| Percent of students proficient on End of Course (EOC) tests)Louisiana2008-2009   | 2008-2009 | 2008-09 | 2009  | 2009-06-01T00:00:00 | Louisiana   | Percent of students proficient on End of Course (EOC) tests) | 43             | 
| Percent of students proficient on End of Course (EOC) tests)Louisiana2009-2010   | 2009-2010 | 2009-10 | 2010  | 2010-06-01T00:00:00 | Louisiana   | Percent of students proficient on End of Course (EOC) tests) | 43             | 
| Percent of students proficient on End of Course (EOC) tests)Louisiana2010-2011   | 2010-2011 | 2010-11 | 2011  | 2011-06-01T00:00:00 | Louisiana   | Percent of students proficient on End of Course (EOC) tests) | 49             | 
```