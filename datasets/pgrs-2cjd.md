# NYS Math Test Results By Grade 2006-2011 - District - By Race- Ethnicity

## Dataset

* [Dataset URL](https://data.cityofnewyork.us/api/views/pgrs-2cjd/rows.json?accessType=DOWNLOAD)
* [Catalog URL](https://catalog.data.gov/dataset/nys-math-test-results-by-grade-2006-2011-district-by-race-ethnicity-0058b)
* Id = pgrs-2cjd
* Name = NYS Math Test Results By Grade 2006-2011 - District - By Race- Ethnicity
* Attribution = Department of Education (DOE)
* Category = Education
* Tags = [lifelong learning]
* Created = 2011-10-05T22:55:29Z
* Publication Date = 2011-10-11T18:11:37Z
* Rows Updated = 2011-10-05T22:55:51Z

## Description

New York City Results on the New York State Mathematics Tests, Grades 3 - 8
Notes:
As of 2006, the New York State Education Department expanded the ELA and mathematics testing programs to Grades 3-8. Previously, state tests were administered in Grades 4 and 8 and citywide tests were administered in Grades 3, 5, 6, and 7.
In 2006, NYSED treated District 75 students as a distinct geographic district. For 2007-2011, District 75 students are represented in their home districts and boroughs. Spreadsheets for District and Borough do not include District 75 students in 2006.
Starting in 2010, NYSED changed the scale score required to meet each of the proficiency levels, increasing the number of questions students needed to answer correctly to meet proficiency.

Rows are suppressed (noted with ?s?) if the number of tested students was 5 or fewer.

## Columns

```ls
| Name             | Field Name       | Data Type | Render Type | Schema Type    | Included | 
| ================ | ================ | ========= | =========== | ============== | ======== | 
| District         | district         | number    | text        | numeric metric | Yes      | 
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
series e:pgrs-2cjd d:2006-01-01T00:00:00.000Z t:category=Asian t:grade=3 m:level_4_1=79 m:mean_scale_score=704 m:level_4_2=51 m:level_1_2=2.6 m:level_1_1=4 m:level_3_2=43.9 m:level_3_4_1=147 m:level_3_1=68 m:level_3_4_2=94.8 m:level_2_2=2.6 m:level_2_1=4 m:district=1 m:number_tested=155

series e:pgrs-2cjd d:2006-01-01T00:00:00.000Z t:category=Black t:grade=3 m:level_4_1=13 m:mean_scale_score=659 m:level_4_2=7 m:level_1_2=11.4 m:level_1_1=21 m:level_3_2=56.2 m:level_3_4_1=117 m:level_3_1=104 m:level_3_4_2=63.2 m:level_2_2=25.4 m:level_2_1=47 m:district=1 m:number_tested=185

series e:pgrs-2cjd d:2006-01-01T00:00:00.000Z t:category=Hispanic t:grade=3 m:level_4_1=73 m:mean_scale_score=664 m:level_4_2=14.8 m:level_1_2=9.3 m:level_1_1=46 m:level_3_2=53.4 m:level_3_4_1=337 m:level_3_1=264 m:level_3_4_2=68.2 m:level_2_2=22.5 m:level_2_1=111 m:district=1 m:number_tested=494
```

## Meta Commands

```ls
metric m:district p:integer l:District t:dataTypeName=number

metric m:number_tested p:integer l:"Number Tested" t:dataTypeName=number

metric m:mean_scale_score p:integer l:"Mean Scale Score" t:dataTypeName=number

metric m:level_1_1 p:integer l:"Level 1 #" t:dataTypeName=number

metric m:level_2_1 p:integer l:"Level 2 #" t:dataTypeName=number

metric m:level_3_1 p:integer l:"Level 3 #" t:dataTypeName=number

metric m:level_4_1 p:integer l:"Level 4 #" t:dataTypeName=number

metric m:level_3_4_1 p:integer l:"Level 3+4 #" t:dataTypeName=number

entity e:pgrs-2cjd l:"NYS Math Test Results By Grade 2006-2011 - District - By Race- Ethnicity" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/pgrs-2cjd

property e:pgrs-2cjd t:meta.view d:2017-03-03T14:36:56.015Z v:id=pgrs-2cjd v:category=Education v:averageRating=0 v:name="NYS Math Test Results By Grade 2006-2011 - District - By Race- Ethnicity" v:attribution="Department of Education (DOE)"

property e:pgrs-2cjd t:meta.view.owner d:2017-03-03T14:36:56.015Z v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"

property e:pgrs-2cjd t:meta.view.tableauthor d:2017-03-03T14:36:56.015Z v:id=rnig-m3uj v:profileImageUrlMedium=/api/users/rnig-m3uj/profile_images/THUMB v:profileImageUrlLarge=/api/users/rnig-m3uj/profile_images/LARGE v:screenName="Jorge J." v:profileImageUrlSmall=/api/users/rnig-m3uj/profile_images/TINY v:displayName="Jorge J."
```