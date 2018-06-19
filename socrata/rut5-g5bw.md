# High School 4-Year Cohort Graduation Rates (2010-11 - Present)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/high-school-graduation-rates-2008-present) |
| Metadata | [Link](https://data.nola.gov/api/views/rut5-g5bw) |
| Data: JSON | [100 Rows](https://data.nola.gov/api/views/rut5-g5bw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.nola.gov/api/views/rut5-g5bw/rows.csv?max_rows=100) |
| Host | data.nola.gov |
| Id | rut5-g5bw |
| Name | High School 4-Year Cohort Graduation Rates (2010-11 - Present) |
| Attribution | Louisiana Department of Education and National Center for Education Statistics |
| Category | Health, Education, and Social Services |
| Tags | resultsnola |
| Created | 2015-04-28T16:47:16Z |
| Publication Date | 2016-01-28T22:28:28Z |

## Description

This data set includes the high school 4-year cohort graduation rates as of spring of year four for Orleans Parish (RSD and OPSB schools combined), Louisiana, and the United States.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type     | Render Type   |
| ======== | ============== | ============== | ============== | ============= | ============= |
| Yes      | series tag     | rowid          | RowID          | text          | text          |
| Yes      | series tag     | year           | Year           | text          | text          |
| No       |                | year2          | Year2          | number        | number        |
| Yes      | time           | date           | Date           | calendar_date | calendar_date |
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
Excluded Fields = year2
```

## Data Commands

```ls
series e:rut5-g5bw d:2011-06-01T00:00:00.000Z t:indicator="4-year cohort graduation rates" t:location=Louisiana t:year=2010-2011 t:rowid="4-year cohort graduation ratesLouisiana2011" m:indicatorvalue=71.4

series e:rut5-g5bw d:2012-06-01T00:00:00.000Z t:indicator="4-year cohort graduation rates" t:location=Louisiana t:year=2011-2012 t:rowid="4-year cohort graduation ratesLouisiana2012" m:indicatorvalue=72.3

series e:rut5-g5bw d:2013-06-01T00:00:00.000Z t:indicator="4-year cohort graduation rates" t:location=Louisiana t:year=2012-2013 t:rowid="4-year cohort graduation ratesLouisiana2013" m:indicatorvalue=73.5
```

## Meta Commands

```ls
metric m:indicatorvalue p:double l:IndicatorValue t:dataTypeName=number

entity e:rut5-g5bw l:"High School 4-Year Cohort Graduation Rates (2010-11 - Present)" t:attribution="Louisiana Department of Education and National Center for Education Statistics" t:url=https://data.nola.gov/api/views/rut5-g5bw

property e:rut5-g5bw t:meta.view v:id=rut5-g5bw v:category="Health, Education, and Social Services" v:attributionLink=http://www.louisianabelieves.com/ v:averageRating=0 v:name="High School 4-Year Cohort Graduation Rates (2010-11 - Present)" v:attribution="Louisiana Department of Education and National Center for Education Statistics"

property e:rut5-g5bw t:meta.view.owner v:id=ii98-542e v:screenName=mschigoda v:displayName=mschigoda

property e:rut5-g5bw t:meta.view.tableauthor v:id=ii98-542e v:screenName=mschigoda v:roleName=publisher v:displayName=mschigoda

property e:rut5-g5bw t:meta.view.metadata.custom_fields.common_core v:Contact_Email=data@nola.gov v:Public_Access_Level=public
```

## Top Records

```ls
| rowid                                              | year      | year2 | date                | location         | indicator                      | indicatorvalue     | 
| ================================================== | ========= | ===== | =================== | ================ | ============================== | ================== | 
| 4-year cohort graduation ratesLouisiana2011        | 2010-2011 | 2011  | 2011-06-01T00:00:00 | Louisiana        | 4-year cohort graduation rates | 71.400000000000006 | 
| 4-year cohort graduation ratesLouisiana2012        | 2011-2012 | 2012  | 2012-06-01T00:00:00 | Louisiana        | 4-year cohort graduation rates | 72.3               | 
| 4-year cohort graduation ratesLouisiana2013        | 2012-2013 | 2013  | 2013-06-01T00:00:00 | Louisiana        | 4-year cohort graduation rates | 73.5               | 
| 4-year cohort graduation ratesLouisiana2014        | 2013-2014 | 2014  | 2014-06-01T00:00:00 | Louisiana        | 4-year cohort graduation rates | 74.599999999999994 | 
| 4-year cohort graduation ratesUnited States2011    | 2010-2011 | 2011  | 2011-06-01T00:00:00 | United States    | 4-year cohort graduation rates | 79                 | 
| 4-year cohort graduation ratesUnited States2012    | 2011-2012 | 2012  | 2012-06-01T00:00:00 | United States    | 4-year cohort graduation rates | 80                 | 
| 4-year cohort graduation ratesUnited States2013    | 2012-2013 | 2013  | 2013-06-01T00:00:00 | United States    | 4-year cohort graduation rates | 81                 | 
| 4-year cohort graduation ratesJefferson Parish2011 | 2010-2011 | 2011  | 2011-06-01T00:00:00 | Jefferson Parish | 4-year cohort graduation rates | 67.3               | 
| 4-year cohort graduation ratesJefferson Parish2012 | 2011-2012 | 2012  | 2012-06-01T00:00:00 | Jefferson Parish | 4-year cohort graduation rates | 70.900000000000006 | 
| 4-year cohort graduation ratesJefferson Parish2013 | 2012-2013 | 2013  | 2013-06-01T00:00:00 | Jefferson Parish | 4-year cohort graduation rates | 69.400000000000006 | 
```