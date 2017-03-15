# Demographic Projection Report - Enrollment Projections - New York City Public Schools prepared by the Grier Partnership Part C

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/demographic-projection-report-enrollment-projections-new-york-city-public-schools-prepared-29ec4) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/9gmp-f9x2) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/9gmp-f9x2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/9gmp-f9x2/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 9gmp-f9x2 |
| Name | Demographic Projection Report - Enrollment Projections - New York City Public Schools prepared by the Grier Partnership Part C |
| Attribution | School Construction Authority (SCA) |
| Category | Housing & Development |
| Tags | school, construction, authority, sca, demographic projection, part c, lifelong learning |
| Created | 2013-03-06T15:19:39Z |
| Publication Date | 2013-06-21T20:48:39Z |
| Rows Updated | 2013-06-21T20:48:35Z |

## Description

The SCA’s comprehensive capital planning process includes developing and analyzing quality data, creating and updating the Department of Education’s Five-Year Capital Plans, and monitoring projects through completion. The SCA prioritizes capital projects to best meet the capacity and building improvements needs throughout the City.  Additionally, the SCA assures that the Capital Plan aligns with New York State and City Department of Education mandates, academic initiatives, and budgetary resources.  This is one of the most current published reports.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | borough     | Borough    | text      | text        |
| Yes      | series tag     | grade       | Grade      | text      | text        |
| Yes      | numeric metric | 2008        | 2008       | number    | text        |
| Yes      | numeric metric | 2009        | 2009       | number    | text        |
| Yes      | numeric metric | 2010        | 2010       | number    | text        |
| Yes      | numeric metric | 2011        | 2011       | number    | text        |
| Yes      | numeric metric | 2012        | 2012       | number    | text        |
| Yes      | numeric metric | 2013        | 2013       | number    | text        |
| Yes      | numeric metric | 2014        | 2014       | number    | text        |
| Yes      | numeric metric | 2015        | 2015       | number    | text        |
| Yes      | numeric metric | 2016        | 2016       | number    | text        |
| Yes      | numeric metric | 2017        | 2017       | number    | text        |
| Yes      | numeric metric | 2018        | 2018       | number    | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:9gmp-f9x2 d:2013-03-06T07:19:47.000Z t:grade=9 t:borough=MANHATTAN m:2008=18366 m:2017=13725 m:2009=17150 m:2018=13764 m:2013=14380 m:2014=14440 m:2015=13884 m:2016=13327 m:2012=14879 m:2011=15537 m:2010=16092

series e:9gmp-f9x2 d:2013-03-06T07:19:47.000Z t:grade=10 t:borough=MANHATTAN m:2008=16631 m:2017=12038 m:2009=16113 m:2018=12451 m:2013=13255 m:2014=12860 m:2015=12962 m:2016=12475 m:2012=13782 m:2011=14246 m:2010=15107

series e:9gmp-f9x2 d:2013-03-06T07:19:47.000Z t:grade=11 t:borough=MANHATTAN m:2008=13281 m:2017=9555 m:2009=12256 m:2018=9255 m:2013=10330 m:2014=9990 m:2015=9755 m:2016=9876 m:2012=10632 m:2011=11213 m:2010=11899
```

## Meta Commands

```ls
metric m:2008 p:integer l:2008 t:dataTypeName=number

metric m:2009 p:integer l:2009 t:dataTypeName=number

metric m:2010 p:integer l:2010 t:dataTypeName=number

metric m:2011 p:integer l:2011 t:dataTypeName=number

metric m:2012 p:integer l:2012 t:dataTypeName=number

metric m:2013 p:integer l:2013 t:dataTypeName=number

metric m:2014 p:integer l:2014 t:dataTypeName=number

metric m:2015 p:integer l:2015 t:dataTypeName=number

metric m:2016 p:integer l:2016 t:dataTypeName=number

metric m:2017 p:integer l:2017 t:dataTypeName=number

metric m:2018 p:integer l:2018 t:dataTypeName=number

entity e:9gmp-f9x2 l:"Demographic Projection Report - Enrollment Projections - New York City Public Schools prepared by the Grier Partnership Part C" t:attribution="School Construction Authority (SCA)" t:url=https://data.cityofnewyork.us/api/views/9gmp-f9x2

property e:9gmp-f9x2 t:meta.view v:id=9gmp-f9x2 v:category="Housing & Development" v:averageRating=0 v:name="Demographic Projection Report - Enrollment Projections - New York City Public Schools prepared by the Grier Partnership Part C" v:attribution="School Construction Authority (SCA)"

property e:9gmp-f9x2 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"

property e:9gmp-f9x2 t:meta.view.tableauthor v:id=ci6y-i73t v:screenName="Harish Pathria" v:displayName="Harish Pathria"
```