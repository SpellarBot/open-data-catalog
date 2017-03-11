# Demographic Projection Report - Enrollment Projections - New York City Public Schools prepared by the Grier Partnership Part C

## Dataset

* [Dataset URL](https://data.cityofnewyork.us/api/views/9gmp-f9x2/rows.json?accessType=DOWNLOAD)
* [Catalog URL](https://catalog.data.gov/dataset/demographic-projection-report-enrollment-projections-new-york-city-public-schools-prepared-29ec4)
* Id = 9gmp-f9x2
* Name = Demographic Projection Report - Enrollment Projections - New York City Public Schools prepared by the Grier Partnership Part C
* Attribution = School Construction Authority (SCA)
* Category = Housing & Development
* Tags = [school, construction, authority, sca, demographic projection, part c, lifelong learning]
* Created = 2013-03-06T15:19:39Z
* Publication Date = 2013-06-21T20:48:39Z
* Rows Updated = 2013-06-21T20:48:35Z

## Description

The SCA?s comprehensive capital planning process includes developing and analyzing quality data, creating and updating the Department of Education?s Five-Year Capital Plans, and monitoring projects through completion. The SCA prioritizes capital projects to best meet the capacity and building improvements needs throughout the City.  Additionally, the SCA assures that the Capital Plan aligns with New York State and City Department of Education mandates, academic initiatives, and budgetary resources.  This is one of the most current published reports.

## Columns

```ls
| Name       | Field Name  | Data Type | Render Type | Schema Type    | Included | 
| ========== | =========== | ========= | =========== | ============== | ======== | 
| updated_at | :updated_at | meta_data | meta_data   | time           | Yes      | 
| Borough    | borough     | text      | text        | series tag     | Yes      | 
| Grade      | grade       | text      | text        | series tag     | Yes      | 
| 2008       | _2008       | number    | text        | numeric metric | Yes      | 
| 2009       | _2009       | number    | text        | numeric metric | Yes      | 
| 2010       | _2010       | number    | text        | numeric metric | Yes      | 
| 2011       | _2011       | number    | text        | numeric metric | Yes      | 
| 2012       | _2012       | number    | text        | numeric metric | Yes      | 
| 2013       | _2013       | number    | text        | numeric metric | Yes      | 
| 2014       | _2014       | number    | text        | numeric metric | Yes      | 
| 2015       | _2015       | number    | text        | numeric metric | Yes      | 
| 2016       | _2016       | number    | text        | numeric metric | Yes      | 
| 2017       | _2017       | number    | text        | numeric metric | Yes      | 
| 2018       | _2018       | number    | text        | numeric metric | Yes      | 
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = 
Annotation Fields = 
```

## Data Commands

```ls
series e:9gmp-f9x2 d:2013-03-06T07:19:47.000Z t:grade=9 t:borough=MANHATTAN m:_2012=14879 m:_2013=14380 m:_2010=16092 m:_2011=15537 m:_2018=13764 m:_2015=13884 m:_2014=14440 m:_2009=17150 m:_2008=18366 m:_2017=13725 m:_2016=13327

series e:9gmp-f9x2 d:2013-03-06T07:19:47.000Z t:grade=10 t:borough=MANHATTAN m:_2012=13782 m:_2013=13255 m:_2010=15107 m:_2011=14246 m:_2018=12451 m:_2015=12962 m:_2014=12860 m:_2009=16113 m:_2008=16631 m:_2017=12038 m:_2016=12475

series e:9gmp-f9x2 d:2013-03-06T07:19:47.000Z t:grade=11 t:borough=MANHATTAN m:_2012=10632 m:_2013=10330 m:_2010=11899 m:_2011=11213 m:_2018=9255 m:_2015=9755 m:_2014=9990 m:_2009=12256 m:_2008=13281 m:_2017=9555 m:_2016=9876
```

## Meta Commands

```ls
metric m:_2008 p:integer l:2008 t:dataTypeName=number

metric m:_2009 p:integer l:2009 t:dataTypeName=number

metric m:_2010 p:integer l:2010 t:dataTypeName=number

metric m:_2011 p:integer l:2011 t:dataTypeName=number

metric m:_2012 p:integer l:2012 t:dataTypeName=number

metric m:_2013 p:integer l:2013 t:dataTypeName=number

metric m:_2014 p:integer l:2014 t:dataTypeName=number

metric m:_2015 p:integer l:2015 t:dataTypeName=number

metric m:_2016 p:integer l:2016 t:dataTypeName=number

metric m:_2017 p:integer l:2017 t:dataTypeName=number

metric m:_2018 p:integer l:2018 t:dataTypeName=number

entity e:9gmp-f9x2 l:"Demographic Projection Report - Enrollment Projections - New York City Public Schools prepared by the Grier Partnership Part C" t:attribution="School Construction Authority (SCA)" t:url=https://data.cityofnewyork.us/api/views/9gmp-f9x2

property e:9gmp-f9x2 t:meta.view d:2017-03-03T14:26:12.263Z v:id=9gmp-f9x2 v:category="Housing & Development" v:averageRating=0 v:name="Demographic Projection Report - Enrollment Projections - New York City Public Schools prepared by the Grier Partnership Part C" v:attribution="School Construction Authority (SCA)"

property e:9gmp-f9x2 t:meta.view.owner d:2017-03-03T14:26:12.263Z v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"

property e:9gmp-f9x2 t:meta.view.tableauthor d:2017-03-03T14:26:12.263Z v:id=ci6y-i73t v:screenName="Harish Pathria" v:displayName="Harish Pathria"
```