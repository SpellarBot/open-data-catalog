# School Enrollment: 2013-14

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/school-enrollment-2013-14) |
| Metadata | [Link](https://data.ct.gov/api/views/fzp6-x2p2) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/fzp6-x2p2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/fzp6-x2p2/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | fzp6-x2p2 |
| Name | School Enrollment: 2013-14 |
| Attribution | State Department of Education |
| Category | Education |
| Tags | education, enrollment, school, district |
| Created | 2014-06-19T20:39:54Z |
| Publication Date | 2014-06-19T20:41:04Z |

## Description

This dataset contains school-level enrollment counts for 2013-14. Data are disaggregated by race and gender. 

Note: Cells are suppressed (marked with an asterisk) where the cell count is less than or equal to five.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| Yes      | series tag     | institution_code  | Institution Code  | text      | number      |
| Yes      | series tag     | district_code     | District Code     | text      | number      |
| Yes      | series tag     | school_code       | School Code       | text      | number      |
| Yes      | series tag     | district_name     | District Name     | text      | text        |
| Yes      | series tag     | school_name       | School Name       | text      | text        |
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
series e:fzp6-x2p2 d:2013-01-01T00:00:00.000Z t:institution_code=11 t:district_code=1 t:district_name="Andover School District" t:school_name="Andover Elementary School" t:school_code=1 m:total=298 m:female=141 m:male=157 m:white=274 m:pacific_islander=0 m:two_or_more_races=6 m:american_indian=0 m:hispanic=11

series e:fzp6-x2p2 d:2013-01-01T00:00:00.000Z t:institution_code=11 t:district_code=2 t:district_name="Ansonia School District" t:school_name="Mead School" t:school_code=3 m:total=566 m:female=288 m:male=278 m:white=248 m:pacific_islander=10 m:two_or_more_races=7 m:american_indian=6 m:hispanic=185 m:black=108

series e:fzp6-x2p2 d:2013-01-01T00:00:00.000Z t:institution_code=11 t:district_code=2 t:district_name="Ansonia School District" t:school_name="Prendergast School" t:school_code=8 m:total=661 m:female=308 m:male=353 m:white=313 m:pacific_islander=7 m:two_or_more_races=13 m:asian_american=10 m:hispanic=213 m:black=101
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

entity e:fzp6-x2p2 l:"School Enrollment: 2013-14" t:attribution="State Department of Education" t:url=https://data.ct.gov/api/views/fzp6-x2p2

property e:fzp6-x2p2 t:meta.view v:id=fzp6-x2p2 v:category=Education v:averageRating=0 v:name="School Enrollment: 2013-14" v:attribution="State Department of Education"

property e:fzp6-x2p2 t:meta.view.owner v:id=nyku-jy9c v:screenName="Stephanie O'Day" v:displayName="Stephanie O'Day"

property e:fzp6-x2p2 t:meta.view.tableauthor v:id=nyku-jy9c v:screenName="Stephanie O'Day" v:roleName=editor v:displayName="Stephanie O'Day"
```

## Top Records

```ls
| institution_code | district_code | school_code | district_name           | school_name               | total | male | female | american_indian | asian_american | black | white | hispanic | pacific_islander | two_or_more_races | 
| ================ | ============= | =========== | ======================= | ========================= | ===== | ==== | ====== | =============== | ============== | ===== | ===== | ======== | ================ | ================= | 
| 11               | 1             | 1           | Andover School District | Andover Elementary School | 298   | 157  | 141    | 0               |                |       | 274   | 11       | 0                | 6                 | 
| 11               | 2             | 3           | Ansonia School District | Mead School               | 566   | 278  | 288    | 6               |                | 108   | 248   | 185      | 10               | 7                 | 
| 11               | 2             | 8           | Ansonia School District | Prendergast School        | 661   | 353  | 308    |                 | 10             | 101   | 313   | 213      | 7                | 13                | 
| 11               | 2             | 51          | Ansonia School District | Ansonia Middle School     | 487   | 262  | 225    |                 | 7              | 107   | 214   | 145      | 8                |                   | 
| 11               | 2             | 61          | Ansonia School District | Ansonia High School       | 602   | 333  | 269    |                 | 9              | 129   | 305   | 148      | 6                |                   | 
| 11               | 3             | 1           | Ashford School District | Ashford School            | 422   | 217  | 205    | 0               | 9              | 10    | 363   | 27       | 0                | 13                | 
| 11               | 4             | 3           | Avon School District    | Roaring Brook School      | 573   | 301  | 272    |                 | 54             | 27    | 420   | 41       |                  | 29                | 
| 11               | 4             | 4           | Avon School District    | Pine Grove School         | 592   | 279  | 313    |                 | 88             | 27    | 426   | 37       |                  | 10                | 
| 11               | 4             | 5           | Avon School District    | Thompson Brook School     | 563   | 303  | 260    |                 | 75             | 21    | 426   | 26       | 0                | 14                | 
| 11               | 4             | 51          | Avon School District    | Avon Middle School        | 584   | 283  | 301    | 0               | 58             | 17    | 454   | 32       | 0                | 23                | 
```