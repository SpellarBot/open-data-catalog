# K-12 Public School Enrollment by Grade Level October Enrollment Report 2009-2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/k-12-public-school-enrollment-by-grade-level-october-enrollment-report-2009-2013) |
| Metadata | [Link](https://data.wa.gov/api/views/2uyp-yrqf) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/2uyp-yrqf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/2uyp-yrqf/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | 2uyp-yrqf |
| Name | K-12 Public School Enrollment by Grade Level October Enrollment Report 2009-2013 |
| Attribution | Office of Juvenile Justice |
| Category | Education |
| Created | 2015-11-29T03:53:24Z |
| Publication Date | 2015-11-29T03:54:56Z |

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type | Render Type |
| ======== | ============== | =========== | =========== | ========= | =========== |
| Yes      | series tag     | grade_level | Grade Level | text      | text        |
| Yes      | numeric metric | 2013        | 2013        | number    | number      |
| Yes      | numeric metric | 2012        | 2012        | number    | number      |
| Yes      | numeric metric | 2011        | 2011        | number    | number      |
| Yes      | numeric metric | 2010        | 2010        | number    | number      |
| Yes      | numeric metric | 2009        | 2009        | number    | number      |
```

## Time Field

```ls
Value = 2009
Format & Zone = yyyy
```

## Data Commands

```ls
series e:2uyp-yrqf d:2009-01-01T00:00:00.000Z t:grade_level=K m:2009=74645 m:2013=81530 m:2012=80258 m:2011=77919 m:2010=75998

series e:2uyp-yrqf d:2009-01-01T00:00:00.000Z t:grade_level=First m:2009=77336 m:2013=83345 m:2012=80497 m:2011=79022 m:2010=78080

series e:2uyp-yrqf d:2009-01-01T00:00:00.000Z t:grade_level=Second m:2009=75989 m:2013=80436 m:2012=78779 m:2011=78445 m:2010=77539
```

## Meta Commands

```ls
metric m:2013 p:integer l:2013 t:dataTypeName=number

metric m:2012 p:integer l:2012 t:dataTypeName=number

metric m:2011 p:integer l:2011 t:dataTypeName=number

metric m:2010 p:integer l:2010 t:dataTypeName=number

metric m:2009 p:integer l:2009 t:dataTypeName=number

entity e:2uyp-yrqf l:"K-12 Public School Enrollment by Grade Level October Enrollment Report 2009-2013" t:attribution="Office of Juvenile Justice" t:url=https://data.wa.gov/api/views/2uyp-yrqf

property e:2uyp-yrqf t:meta.view v:id=2uyp-yrqf v:category=Education v:attributionLink=https://dshs.wa.gov/ra/office-juvenile-justice/washington-state-juvenile-justice-annual-report v:averageRating=0 v:name="K-12 Public School Enrollment by Grade Level October Enrollment Report 2009-2013" v:attribution="Office of Juvenile Justice"

property e:2uyp-yrqf t:meta.view.license v:name="Public Domain"

property e:2uyp-yrqf t:meta.view.owner v:id=6p7r-jviv v:profileImageUrlMedium=/api/users/6p7r-jviv/profile_images/THUMB v:profileImageUrlLarge=/api/users/6p7r-jviv/profile_images/LARGE v:screenName="Alysa Kipersztok" v:profileImageUrlSmall=/api/users/6p7r-jviv/profile_images/TINY v:displayName="Alysa Kipersztok"

property e:2uyp-yrqf t:meta.view.tableauthor v:id=6p7r-jviv v:profileImageUrlMedium=/api/users/6p7r-jviv/profile_images/THUMB v:profileImageUrlLarge=/api/users/6p7r-jviv/profile_images/LARGE v:screenName="Alysa Kipersztok" v:profileImageUrlSmall=/api/users/6p7r-jviv/profile_images/TINY v:roleName=viewer v:displayName="Alysa Kipersztok"
```

## Top Records

```ls
| grade_level | 2013  | 2012  | 2011  | 2010  | 2009  | 
| =========== | ===== | ===== | ===== | ===== | ===== | 
| K           | 81530 | 80258 | 77919 | 75998 | 74645 | 
| First       | 83345 | 80497 | 79022 | 78080 | 77336 | 
| Second      | 80436 | 78779 | 78445 | 77539 | 75989 | 
| Third       | 79228 | 78595 | 78018 | 76503 | 77762 | 
| Fourth      | 78929 | 78154 | 77168 | 78445 | 78185 | 
| Fifth       | 78534 | 77242 | 79081 | 78315 | 78051 | 
| Sixth       | 77672 | 78881 | 79211 | 78296 | 77611 | 
| Seventh     | 79452 | 79385 | 79058 | 78512 | 77680 | 
| Eighth      | 79984 | 79306 | 78995 | 77628 | 77263 | 
| Ninth       | 83313 | 84088 | 84457 | 84113 | 85608 | 
```