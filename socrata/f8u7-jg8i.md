# High Wage Jobs (2009 - Present)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/high-wage-jobs-2007-present) |
| Metadata | [Link](https://data.nola.gov/api/views/f8u7-jg8i) |
| Data: JSON | [100 Rows](https://data.nola.gov/api/views/f8u7-jg8i/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.nola.gov/api/views/f8u7-jg8i/rows.csv?max_rows=100) |
| Host | data.nola.gov |
| Id | f8u7-jg8i |
| Name | High Wage Jobs (2009 - Present) |
| Attribution | Bureau of Labor Statistics |
| Category | Economy and Workforce |
| Tags | resultsnola |
| Created | 2015-10-07T22:12:54Z |
| Publication Date | 2015-10-07T22:15:13Z |

## Description

This dataset is created by the City's Office of Performance and Accountability using data on jobs and wages from the Bureau of Labor Statistics.  This dataset includes data for New Orleans MSA and several benchmark MSAs including: Atlanta, Baton Rouge, Louisville, Memphis, Miami, Nashville/Davidson, Oklahoma City, Raleigh, and Tampa. The data is compiled annually beginning in 2009.

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
| Yes      | series tag     | indicatortable | IndicatorTable | text          | text          |
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
series e:f8u7-jg8i d:2009-01-01T00:00:00.000Z t:location="Atlanta-Sandy Springs-Marietta, GA" t:indicatortable="Occupational Employment Statistics" t:rowid="Atlanta-Sandy Springs-Marietta, GA_Occupational Employment Statistics_2009" t:indicatorname="Total number of jobs" m:indicatorvalue=2231100

series e:f8u7-jg8i d:2009-01-01T00:00:00.000Z t:location="Atlanta-Sandy Springs-Marietta, GA" t:indicatortable="Occupational Employment Statistics" t:rowid="Atlanta-Sandy Springs-Marietta, GA_Occupational Employment Statistics_2009" t:indicatorname="Number of high and very high wage jobs" m:indicatorvalue=571160

series e:f8u7-jg8i d:2009-01-01T00:00:00.000Z t:location="Atlanta-Sandy Springs-Marietta, GA" t:indicatortable="Occupational Employment Statistics" t:rowid="Atlanta-Sandy Springs-Marietta, GA_Occupational Employment Statistics_2009" t:indicatorname="Percent of total jobs that are high or very high wage jobs" m:indicatorvalue=25.5999282864954
```

## Meta Commands

```ls
metric m:indicatorvalue p:double l:IndicatorValue t:dataTypeName=number

entity e:f8u7-jg8i l:"High Wage Jobs (2009 - Present)" t:attribution="Bureau of Labor Statistics" t:url=https://data.nola.gov/api/views/f8u7-jg8i

property e:f8u7-jg8i t:meta.view v:id=f8u7-jg8i v:category="Economy and Workforce" v:attributionLink=http://www.bls.gov/home.htm v:averageRating=0 v:name="High Wage Jobs (2009 - Present)" v:attribution="Bureau of Labor Statistics"

property e:f8u7-jg8i t:meta.view.owner v:id=ii98-542e v:screenName=mschigoda v:displayName=mschigoda

property e:f8u7-jg8i t:meta.view.tableauthor v:id=ii98-542e v:screenName=mschigoda v:roleName=publisher v:displayName=mschigoda

property e:f8u7-jg8i t:meta.view.metadata.custom_fields.common_core v:Contact_Email=data@nola.gov
```

## Top Records

```ls
| rowid                                                                      | date                | year | location                           | indicatorname                                              | indicatorvalue   | indicatortable                     | 
| ========================================================================== | =================== | ==== | ================================== | ========================================================== | ================ | ================================== | 
| Atlanta-Sandy Springs-Marietta, GA_Occupational Employment Statistics_2009 | 2009-01-01T00:00:00 | 2009 | Atlanta-Sandy Springs-Marietta, GA | Total number of jobs                                       | 2231100          | Occupational Employment Statistics | 
| Atlanta-Sandy Springs-Marietta, GA_Occupational Employment Statistics_2009 | 2009-01-01T00:00:00 | 2009 | Atlanta-Sandy Springs-Marietta, GA | Number of high and very high wage jobs                     | 571160           | Occupational Employment Statistics | 
| Atlanta-Sandy Springs-Marietta, GA_Occupational Employment Statistics_2009 | 2009-01-01T00:00:00 | 2009 | Atlanta-Sandy Springs-Marietta, GA | Percent of total jobs that are high or very high wage jobs | 25.5999282864954 | Occupational Employment Statistics | 
| Atlanta-Sandy Springs-Marietta, GA_Occupational Employment Statistics_2010 | 2010-01-01T00:00:00 | 2010 | Atlanta-Sandy Springs-Marietta, GA | Total number of jobs                                       | 2145200          | Occupational Employment Statistics | 
| Atlanta-Sandy Springs-Marietta, GA_Occupational Employment Statistics_2010 | 2010-01-01T00:00:00 | 2010 | Atlanta-Sandy Springs-Marietta, GA | Number of high and very high wage jobs                     | 544770           | Occupational Employment Statistics | 
| Atlanta-Sandy Springs-Marietta, GA_Occupational Employment Statistics_2010 | 2010-01-01T00:00:00 | 2010 | Atlanta-Sandy Springs-Marietta, GA | Percent of total jobs that are high or very high wage jobs | 25.3948349804214 | Occupational Employment Statistics | 
| Atlanta-Sandy Springs-Marietta, GA_Occupational Employment Statistics_2011 | 2011-01-01T00:00:00 | 2011 | Atlanta-Sandy Springs-Marietta, GA | Total number of jobs                                       | 2177690          | Occupational Employment Statistics | 
| Atlanta-Sandy Springs-Marietta, GA_Occupational Employment Statistics_2011 | 2011-01-01T00:00:00 | 2011 | Atlanta-Sandy Springs-Marietta, GA | Number of high and very high wage jobs                     | 542700           | Occupational Employment Statistics | 
| Atlanta-Sandy Springs-Marietta, GA_Occupational Employment Statistics_2011 | 2011-01-01T00:00:00 | 2011 | Atlanta-Sandy Springs-Marietta, GA | Percent of total jobs that are high or very high wage jobs | 24.9209024241283 | Occupational Employment Statistics | 
| Atlanta-Sandy Springs-Marietta, GA_Occupational Employment Statistics_2012 | 2012-01-01T00:00:00 | 2012 | Atlanta-Sandy Springs-Marietta, GA | Total number of jobs                                       | 2221610          | Occupational Employment Statistics | 
```