# District Enrollment: 2012-13

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/district-enrollment-2012-13) |
| Metadata | [Link](https://data.ct.gov/api/views/bygz-gaef) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/bygz-gaef/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/bygz-gaef/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | bygz-gaef |
| Name | District Enrollment: 2012-13 |
| Attribution | State Department of Education |
| Category | Education |
| Tags | education, enrollment, school, district |
| Created | 2014-06-19T20:37:39Z |
| Publication Date | 2014-06-19T20:38:45Z |

## Description

This dataset contains district-level enrollment counts for 2012-13. Data are disaggregated by race and gender. 

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
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:bygz-gaef d:2012-01-01T00:00:00.000Z t:district_code=1 t:institution_code=11 t:district_name="Andover School District" m:total=314 m:female=141 m:male=173 m:white=290 m:pacific_islander=0 m:two_or_more_races=9 m:american_indian=0 m:hispanic=9

series e:bygz-gaef d:2012-01-01T00:00:00.000Z t:district_code=2 t:institution_code=11 t:district_name="Ansonia School District" m:total=2409 m:female=1161 m:male=1248 m:white=1153 m:pacific_islander=32 m:two_or_more_races=12 m:asian_american=23 m:american_indian=15 m:hispanic=667 m:black=507

series e:bygz-gaef d:2012-01-01T00:00:00.000Z t:district_code=3 t:institution_code=11 t:district_name="Ashford School District" m:total=439 m:female=211 m:male=228 m:white=381 m:pacific_islander=0 m:two_or_more_races=13 m:asian_american=11 m:american_indian=0 m:hispanic=24 m:black=10
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

entity e:bygz-gaef l:"District Enrollment: 2012-13" t:attribution="State Department of Education" t:url=https://data.ct.gov/api/views/bygz-gaef

property e:bygz-gaef t:meta.view v:id=bygz-gaef v:category=Education v:averageRating=0 v:name="District Enrollment: 2012-13" v:attribution="State Department of Education"

property e:bygz-gaef t:meta.view.owner v:id=nyku-jy9c v:screenName="Stephanie O'Day" v:displayName="Stephanie O'Day"

property e:bygz-gaef t:meta.view.tableauthor v:id=nyku-jy9c v:screenName="Stephanie O'Day" v:roleName=editor v:displayName="Stephanie O'Day"
```

## Top Records

```ls
| institution_code | district_code | district_name               | total | male | female | american_indian | asian_american | black | white | hispanic | pacific_islander | two_or_more_races | 
| ================ | ============= | =========================== | ===== | ==== | ====== | =============== | ============== | ===== | ===== | ======== | ================ | ================= | 
| 11               | 1             | Andover School District     | 314   | 173  | 141    | 0               |                |       | 290   | 9        | 0                | 9                 | 
| 11               | 2             | Ansonia School District     | 2409  | 1248 | 1161   | 15              | 23             | 507   | 1153  | 667      | 32               | 12                | 
| 11               | 3             | Ashford School District     | 439   | 228  | 211    | 0               | 11             | 10    | 381   | 24       | 0                | 13                | 
| 11               | 4             | Avon School District        | 3403  | 1703 | 1700   | 6               | 337            | 123   | 2672  | 170      | 9                | 86                | 
| 11               | 5             | Barkhamsted School District | 349   | 198  | 151    | 0               |                |       | 334   | 6        | 0                |                   | 
| 11               | 7             | Berlin School District      | 2972  | 1584 | 1388   |                 | 102            | 53    | 2487  | 240      |                  | 88                | 
| 11               | 8             | Bethany School District     | 473   | 250  | 223    | 8               | 34             | 9     | 413   | 7        | 0                |                   | 
| 11               | 9             | Bethel School District      | 2975  | 1543 | 1432   |                 | 195            | 71    | 2264  | 383      |                  | 59                | 
| 11               | 11            | Bloomfield School District  | 2108  | 1076 | 1032   |                 | 28             | 1534  | 246   | 205      |                  | 90                | 
| 11               | 12            | Bolton School District      | 892   | 448  | 444    | 0               | 12             | 35    | 783   | 33       | 0                | 29                | 
```