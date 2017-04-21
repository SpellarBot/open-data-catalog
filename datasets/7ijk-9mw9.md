# School Enrollment: 2012-13

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/school-enrollment-2012-13) |
| Metadata | [Link](https://data.ct.gov/api/views/7ijk-9mw9) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/7ijk-9mw9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/7ijk-9mw9/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | 7ijk-9mw9 |
| Name | School Enrollment: 2012-13 |
| Attribution | State Department of Education |
| Category | Education |
| Tags | education, enrollment, school, district |
| Created | 2014-06-19T20:34:58Z |
| Publication Date | 2014-06-19T20:36:03Z |

## Description

This dataset contains school-level enrollment counts for 2012-13. Data are disaggregated by race and gender. 

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
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:7ijk-9mw9 d:2012-01-01T00:00:00.000Z t:institution_code=11 t:district_code=1 t:district_name="Andover School District" t:school_name="Andover Elementary School" t:school_code=1 m:total=314 m:female=141 m:male=173 m:white=290 m:pacific_islander=0 m:two_or_more_races=9 m:american_indian=0 m:hispanic=9

series e:7ijk-9mw9 d:2012-01-01T00:00:00.000Z t:institution_code=11 t:district_code=2 t:district_name="Ansonia School District" t:school_name="Mead School" t:school_code=3 m:total=619 m:female=312 m:male=307 m:white=272 m:pacific_islander=13 m:hispanic=204 m:black=119

series e:7ijk-9mw9 d:2012-01-01T00:00:00.000Z t:institution_code=11 t:district_code=2 t:district_name="Ansonia School District" t:school_name="Prendergast School" t:school_code=8 m:total=699 m:female=322 m:male=377 m:white=340 m:pacific_islander=9 m:two_or_more_races=7 m:asian_american=8 m:hispanic=193 m:black=137
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

entity e:7ijk-9mw9 l:"School Enrollment: 2012-13" t:attribution="State Department of Education" t:url=https://data.ct.gov/api/views/7ijk-9mw9

property e:7ijk-9mw9 t:meta.view v:id=7ijk-9mw9 v:category=Education v:averageRating=0 v:name="School Enrollment: 2012-13" v:attribution="State Department of Education"

property e:7ijk-9mw9 t:meta.view.owner v:id=nyku-jy9c v:screenName="Stephanie O'Day" v:displayName="Stephanie O'Day"

property e:7ijk-9mw9 t:meta.view.tableauthor v:id=nyku-jy9c v:screenName="Stephanie O'Day" v:roleName=editor v:displayName="Stephanie O'Day"
```

## Top Records

```ls
| institution_code | district_code | school_code | district_name           | school_name               | total | male | female | american_indian | asian_american | black | white | hispanic | pacific_islander | two_or_more_races | 
| ================ | ============= | =========== | ======================= | ========================= | ===== | ==== | ====== | =============== | ============== | ===== | ===== | ======== | ================ | ================= | 
| 11               | 1             | 1           | Andover School District | Andover Elementary School | 314   | 173  | 141    | 0               |                |       | 290   | 9        | 0                | 9                 | 
| 11               | 2             | 3           | Ansonia School District | Mead School               | 619   | 307  | 312    |                 |                | 119   | 272   | 204      | 13               |                   | 
| 11               | 2             | 8           | Ansonia School District | Prendergast School        | 699   | 377  | 322    |                 | 8              | 137   | 340   | 193      | 9                | 7                 | 
| 11               | 2             | 51          | Ansonia School District | Ansonia Middle School     | 460   | 242  | 218    |                 |                | 105   | 208   | 133      | 6                |                   | 
| 11               | 2             | 61          | Ansonia School District | Ansonia High School       | 631   | 322  | 309    |                 | 9              | 146   | 333   | 137      |                  |                   | 
| 11               | 3             | 1           | Ashford School District | Ashford School            | 439   | 228  | 211    | 0               | 11             | 10    | 381   | 24       | 0                | 13                | 
| 11               | 4             | 3           | Avon School District    | Roaring Brook School      | 569   | 289  | 280    |                 | 53             | 23    | 443   | 30       |                  | 18                | 
| 11               | 4             | 4           | Avon School District    | Pine Grove School         | 592   | 306  | 286    |                 | 71             | 29    | 446   | 28       |                  | 14                | 
| 11               | 4             | 5           | Avon School District    | Thompson Brook School     | 548   | 258  | 290    |                 | 55             | 18    | 432   | 27       |                  | 14                | 
| 11               | 4             | 51          | Avon School District    | Avon Middle School        | 611   | 316  | 295    | 0               | 62             | 19    | 481   | 32       |                  | 15                | 
```