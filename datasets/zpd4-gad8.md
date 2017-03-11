# NYS Math Test Results By Grade 2006-2011 - Boro - By English Proficiency Status

## Dataset

* [Dataset URL](https://data.cityofnewyork.us/api/views/zpd4-gad8/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/nys-math-test-results-by-grade-2006-2011-boro-by-english-proficiency-status-fdef8)
* [Metadata URL](https://data.cityofnewyork.us/api/views/zpd4-gad8)
* Id = zpd4-gad8
* Name = NYS Math Test Results By Grade 2006-2011 - Boro - By English Proficiency Status
* Attribution = Department of Education (DOE)
* Category = Education
* Tags = [lifelong learning]
* Created = 2011-10-05T22:14:31Z
* Publication Date = 2011-10-11T16:57:18Z
* Rows Updated = 2011-10-05T22:14:41Z

## Description

New York City Results on the New York State Mathematics Tests, Grades 3 - 8
Notes:
As of 2006, the New York State Education Department expanded the ELA and mathematics testing programs to Grades 3-8. Previously, state tests were administered in Grades 4 and 8 and citywide tests were administered in Grades 3, 5, 6, and 7.
In 2006, NYSED treated District 75 students as a distinct geographic district. For 2007-2011, District 75 students are represented in their home districts and boroughs. Spreadsheets for District and Borough do not include District 75 students in 2006.
Starting in 2010, NYSED changed the scale score required to meet each of the proficiency levels, increasing the number of questions students needed to answer correctly to meet proficiency.

## Columns

```ls
| Name             | Field Name       | Data Type | Render Type | Schema Type    | Included | 
| ================ | ================ | ========= | =========== | ============== | ======== | 
| Borough          | borough          | text      | text        | series tag     | Yes      | 
| Grade            | grade            | text      | text        | series tag     | Yes      | 
| Year             | year             | number    | text        | time           | Yes      | 
| Category         | category         | text      | text        | series tag     | Yes      | 
| Number Tested    | number_tested    | number    | number      | numeric metric | Yes      | 
| Mean Scale Score | mean_scale_score | number    | number      | numeric metric | Yes      | 
| Level 1 #        | level_1_1        | number    | number      | numeric metric | Yes      | 
| Level 1 %        | level_1_2        | percent   | percent     | numeric metric | Yes      | 
| Level 2 #        | level_2_1        | number    | number      | numeric metric | Yes      | 
| Level 2 %        | level_2_2        | percent   | percent     | numeric metric | Yes      | 
| Level 3 #        | level_3_1        | number    | number      | numeric metric | Yes      | 
| Level 3 %        | level_3_2        | percent   | percent     | numeric metric | Yes      | 
| Level 4 #        | level_4_1        | number    | number      | numeric metric | Yes      | 
| Level 4 %        | level_4_2        | percent   | percent     | numeric metric | Yes      | 
| Level 3+4 #      | level_3_4_1      | number    | number      | numeric metric | Yes      | 
| Level 3+4 %      | level_3_4_2      | percent   | percent     | numeric metric | Yes      | 
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
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
series e:zpd4-gad8 d:2006-01-01T00:00:00.000Z t:category=ELL t:grade=3 t:borough=BRONX m:level_4_1=202 m:level_3_4_2=49 m:mean_scale_score=645 m:level_2_2=27.6 m:level_4_2=5.4 m:level_2_1=1037 m:level_1_2=23.3 m:level_1_1=876 m:number_tested=3754 m:level_3_2=43.7 m:level_3_4_1=1841 m:level_3_1=1639

series e:zpd4-gad8 d:2006-01-01T00:00:00.000Z t:category=EP t:grade=3 t:borough=BRONX m:level_4_1=2306 m:level_3_4_2=73.2 m:mean_scale_score=669 m:level_2_2=17.5 m:level_4_2=18.2 m:level_2_1=2220 m:level_1_2=9.3 m:level_1_1=1186 m:number_tested=12691 m:level_3_2=55 m:level_3_4_1=9285 m:level_3_1=6979

series e:zpd4-gad8 d:2007-01-01T00:00:00.000Z t:category=ELL t:grade=3 t:borough=BRONX m:level_4_1=376 m:level_3_4_2=62.5 m:mean_scale_score=659 m:level_2_2=24.4 m:level_4_2=10.1 m:level_2_1=908 m:level_1_2=13.1 m:level_1_1=489 m:number_tested=3726 m:level_3_2=52.4 m:level_3_4_1=2329 m:level_3_1=1953
```

## Meta Commands

```ls
metric m:number_tested p:integer l:"Number Tested" t:dataTypeName=number

metric m:mean_scale_score p:integer l:"Mean Scale Score" t:dataTypeName=number

metric m:level_1_1 p:integer l:"Level 1 #" t:dataTypeName=number

metric m:level_2_1 p:integer l:"Level 2 #" t:dataTypeName=number

metric m:level_3_1 p:integer l:"Level 3 #" t:dataTypeName=number

metric m:level_4_1 p:integer l:"Level 4 #" t:dataTypeName=number

metric m:level_3_4_1 p:integer l:"Level 3+4 #" t:dataTypeName=number

entity e:zpd4-gad8 l:"NYS Math Test Results By Grade 2006-2011 - Boro - By English Proficiency Status" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/zpd4-gad8

property e:zpd4-gad8 t:meta.view d:2017-03-07T18:35:36.557Z v:id=zpd4-gad8 v:category=Education v:averageRating=0 v:name="NYS Math Test Results By Grade 2006-2011 - Boro - By English Proficiency Status" v:attribution="Department of Education (DOE)"

property e:zpd4-gad8 t:meta.view.owner d:2017-03-07T18:35:36.557Z v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"

property e:zpd4-gad8 t:meta.view.tableauthor d:2017-03-07T18:35:36.557Z v:id=rnig-m3uj v:profileImageUrlMedium=/api/users/rnig-m3uj/profile_images/THUMB v:profileImageUrlLarge=/api/users/rnig-m3uj/profile_images/LARGE v:screenName="Jorge J." v:profileImageUrlSmall=/api/users/rnig-m3uj/profile_images/TINY v:displayName="Jorge J."
```