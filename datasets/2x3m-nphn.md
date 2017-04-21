# Performance Dashboard - Degree Attainment - US Census ACS

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/performance-dashboard-degree-attainment-us-census-acs) |
| Metadata | [Link](https://data.maryland.gov/api/views/2x3m-nphn) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/2x3m-nphn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/2x3m-nphn/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | 2x3m-nphn |
| Name | Performance Dashboard - Degree Attainment - US Census ACS |
| Attribution | Governor's Office of Performance Improvement |
| Category | Education |
| Tags | degree attainment, statewide, national, census bureau, american community survey |
| Created | 2016-09-29T12:49:48Z |
| Publication Date | 2016-10-19T19:13:50Z |

## Description

This data set includes information from the U.S. Census Bureau's American Community Survey on national and statewide degree attainment.

## Columns

```ls
| Included | Schema Type    | Field Name                         | Name                                   | Data Type     | Render Type   |
| ======== | ============== | ================================== | ====================================== | ============= | ============= |
| Yes      | time           | date                               | Date                                   | calendar_date | calendar_date |
| No       |                | year                               | Year                                   | number        | text          |
| Yes      | numeric metric | degree_attainment_united_states_cy | Degree Attainment - United States - CY | percent       | percent       |
| Yes      | numeric metric | degree_attainment_maryland_cy      | Degree Attainment - Maryland - CY      | percent       | percent       |
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
series e:2x3m-nphn d:2006-12-31T00:00:00.000Z m:degree_attainment_maryland_cy=35.1 m:degree_attainment_united_states_cy=27

series e:2x3m-nphn d:2007-12-31T00:00:00.000Z m:degree_attainment_maryland_cy=35.2 m:degree_attainment_united_states_cy=27.5

series e:2x3m-nphn d:2008-12-31T00:00:00.000Z m:degree_attainment_maryland_cy=35.2 m:degree_attainment_united_states_cy=27.7
```

## Meta Commands

```ls
metric m:degree_attainment_united_states_cy p:float l:"Degree Attainment - United States - CY" d:"percentage of the United States population 25 years old and over who have earned at least a Bachelor's degree. Based on the US Census Bureau's American Community Survey 1-year average" t:dataTypeName=percent

metric m:degree_attainment_maryland_cy p:float l:"Degree Attainment - Maryland - CY" d:"percentage of Maryland residents 25 years old and over who have earned at least a Bachelor's degree. Based on the US Census Bureau's American Community Survey 1-year average" t:dataTypeName=percent

entity e:2x3m-nphn l:"Performance Dashboard - Degree Attainment - US Census ACS" t:attribution="Governor's Office of Performance Improvement" t:url=https://data.maryland.gov/api/views/2x3m-nphn

property e:2x3m-nphn t:meta.view v:id=2x3m-nphn v:category=Education v:attributionLink=http://gopi.maryland.gov/ v:averageRating=0 v:name="Performance Dashboard - Degree Attainment - US Census ACS" v:attribution="Governor's Office of Performance Improvement"

property e:2x3m-nphn t:meta.view.license v:name="Public Domain"

property e:2x3m-nphn t:meta.view.owner v:id=9ei4-2q5c v:screenName="Pat Pscherer" v:displayName="Pat Pscherer"

property e:2x3m-nphn t:meta.view.tableauthor v:id=9ei4-2q5c v:screenName="Pat Pscherer" v:roleName=administrator v:displayName="Pat Pscherer"
```

## Top Records

```ls
| date                | year | degree_attainment_united_states_cy | degree_attainment_maryland_cy | 
| =================== | ==== | ================================== | ============================= | 
| 2006-12-31T00:00:00 | 2006 | 27.0                               | 35.1                          | 
| 2007-12-31T00:00:00 | 2007 | 27.5                               | 35.2                          | 
| 2008-12-31T00:00:00 | 2008 | 27.7                               | 35.2                          | 
| 2009-12-31T00:00:00 | 2009 | 27.9                               | 35.7                          | 
| 2010-12-31T00:00:00 | 2010 | 28.2                               | 36.1                          | 
| 2011-12-31T00:00:00 | 2011 | 28.5                               | 36.9                          | 
| 2012-12-31T00:00:00 | 2012 | 29.1                               | 36.9                          | 
| 2013-12-31T00:00:00 | 2013 | 29.6                               | 37.4                          | 
| 2014-12-31T00:00:00 | 2014 | 30.1                               | 38.2                          | 
| 2015-12-31T00:00:00 | 2015 | 30.6                               | 38.8                          | 
```