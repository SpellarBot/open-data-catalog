# District Enrollment: 2013-14

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/district-enrollment-2013-14) |
| Metadata | [Link](https://data.ct.gov/api/views/bb6g-79yj) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/bb6g-79yj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/bb6g-79yj/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | bb6g-79yj |
| Name | District Enrollment: 2013-14 |
| Attribution | State Department of Education |
| Category | Education |
| Tags | education, enrollment, district, school |
| Created | 2014-06-19T20:42:09Z |
| Publication Date | 2015-01-28T14:08:47Z |

## Description

This dataset contains district-level enrollment counts for 2013-14. Data are disaggregated by race and gender. 

Note: Cells are suppressed (marked with an asterisk) where the cell count is less than or equal to five.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| Yes      | series tag     | institution_code  | Institution Code  | text      | number      |
| Yes      | series tag     | district_code     | District Code     | text      | number      |
| Yes      | series tag     | district_name     | District Name     | text      | text        |
| Yes      | numeric metric | total             | Total             | number    | number      |
| Yes      | numeric metric | male              | Male              | number    | number      |
| Yes      | numeric metric | female            | Female            | number    | number      |
| Yes      | numeric metric | american_indian   | American Indian   | number    | number      |
| Yes      | numeric metric | asian_american    | Asian American    | number    | number      |
| Yes      | numeric metric | black             | Black             | number    | number      |
| Yes      | numeric metric | white             | White             | number    | number      |
| Yes      | numeric metric | hispanic          | Hispanic          | number    | number      |
| Yes      | numeric metric | pacific_islander  | Pacific Islander  | number    | number      |
| Yes      | numeric metric | two_or_more_races | Two or More races | number    | number      |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:bb6g-79yj d:2013-01-01T00:00:00.000Z t:district_code=1 t:institution_code=11 t:district_name="Andover School District" m:total=298 m:female=141 m:male=157 m:white=274 m:pacific_islander=0 m:two_or_more_races=6 m:american_indian=0 m:hispanic=11

series e:bb6g-79yj d:2013-01-01T00:00:00.000Z t:district_code=2 t:institution_code=11 t:district_name="Ansonia School District" m:total=2316 m:female=1090 m:male=1226 m:white=1080 m:pacific_islander=31 m:two_or_more_races=27 m:asian_american=28 m:american_indian=14 m:hispanic=691 m:black=445

series e:bb6g-79yj d:2013-01-01T00:00:00.000Z t:district_code=3 t:institution_code=11 t:district_name="Ashford School District" m:total=422 m:female=205 m:male=217 m:white=363 m:pacific_islander=0 m:two_or_more_races=13 m:asian_american=9 m:american_indian=0 m:hispanic=27 m:black=10
```

## Meta Commands

```ls
metric m:total p:integer l:Total t:dataTypeName=number

metric m:male p:integer l:Male t:dataTypeName=number

metric m:female p:integer l:Female t:dataTypeName=number

metric m:american_indian p:integer l:"American Indian" t:dataTypeName=number

metric m:asian_american p:integer l:"Asian American" t:dataTypeName=number

metric m:black p:integer l:Black t:dataTypeName=number

metric m:white p:integer l:White t:dataTypeName=number

metric m:hispanic p:integer l:Hispanic t:dataTypeName=number

metric m:pacific_islander p:integer l:"Pacific Islander" t:dataTypeName=number

metric m:two_or_more_races p:integer l:"Two or More races" t:dataTypeName=number

entity e:bb6g-79yj l:"District Enrollment: 2013-14" t:attribution="State Department of Education" t:url=https://data.ct.gov/api/views/bb6g-79yj

property e:bb6g-79yj t:meta.view v:id=bb6g-79yj v:category=Education v:averageRating=0 v:name="District Enrollment: 2013-14" v:attribution="State Department of Education"

property e:bb6g-79yj t:meta.view.owner v:id=nyku-jy9c v:screenName="Stephanie O'Day" v:displayName="Stephanie O'Day"

property e:bb6g-79yj t:meta.view.tableauthor v:id=nyku-jy9c v:screenName="Stephanie O'Day" v:roleName=editor v:displayName="Stephanie O'Day"
```

## Top Records

```ls
| institution_code | district_code | district_name               | total | male | female | american_indian | asian_american | black | white | hispanic | pacific_islander | two_or_more_races | 
| ================ | ============= | =========================== | ===== | ==== | ====== | =============== | ============== | ===== | ===== | ======== | ================ | ================= | 
| 11               | 1             | Andover School District     | 298   | 157  | 141    | 0               |                |       | 274   | 11       | 0                | 6                 | 
| 11               | 2             | Ansonia School District     | 2316  | 1226 | 1090   | 14              | 28             | 445   | 1080  | 691      | 31               | 27                | 
| 11               | 3             | Ashford School District     | 422   | 217  | 205    | 0               | 9              | 10    | 363   | 27       | 0                | 13                | 
| 11               | 4             | Avon School District        | 3369  | 1671 | 1698   | 6               | 369            | 129   | 2561  | 195      |                  | 106               | 
| 11               | 5             | Barkhamsted School District | 306   | 171  | 135    | 0               |                |       | 296   |          | 0                |                   | 
| 11               | 7             | Berlin School District      | 2949  | 1582 | 1367   |                 | 78             | 67    | 2459  | 252      |                  | 89                | 
| 11               | 8             | Bethany School District     | 436   | 237  | 199    |                 | 43             | 11    | 369   | 10       | 0                |                   | 
| 11               | 9             | Bethel School District      | 2989  | 1557 | 1432   | 0               | 193            | 58    | 2252  | 412      |                  | 72                | 
| 11               | 11            | Bloomfield School District  | 2087  | 1058 | 1029   |                 | 27             | 1504  | 224   | 234      |                  | 94                | 
| 11               | 12            | Bolton School District      | 862   | 432  | 430    | 0               | 23             | 48    | 741   | 36       | 0                | 14                | 
```