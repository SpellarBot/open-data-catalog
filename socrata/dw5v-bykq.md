# K-12 Public School Enrollment by Race/Ethnicity October 2009-2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/k-12-public-school-enrollment-by-race-ethnicity-october-2009-2013) |
| Metadata | [Link](https://data.wa.gov/api/views/dw5v-bykq) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/dw5v-bykq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/dw5v-bykq/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | dw5v-bykq |
| Name | K-12 Public School Enrollment by Race/Ethnicity October 2009-2013 |
| Attribution | Office of Juvenile Justice |
| Tags | juvenile justice, annual report, wa-pcjj report, office of juvenile justice, dshs, race, ethnicity, public school, youth |
| Created | 2015-11-29T03:57:48Z |
| Publication Date | 2015-11-29T04:00:07Z |

## Columns

```ls
| Included | Schema Type    | Field Name       | Name               | Data Type | Render Type |
| ======== | ============== | ================ | ================== | ========= | =========== |
| Yes      | series tag     | race_ethnicity   | Race/Ethnicity     | text      | text        |
| Yes      | numeric metric | 2013_students    | *2013 Students     | number    | number      |
| Yes      | numeric metric | of_2013_students | % of 2013 Students | percent   | percent     |
| Yes      | numeric metric | 2012_students    | *2012 Students     | number    | number      |
| Yes      | numeric metric | of_2012_students | % of 2012 Students | percent   | percent     |
| Yes      | numeric metric | 2011_students    | *2011 Students     | number    | number      |
| Yes      | numeric metric | of_2011          | % of 2011          | percent   | percent     |
| Yes      | numeric metric | 2010_students    | *2010 Students     | number    | number      |
| Yes      | numeric metric | of_2010_students | % of 2010 Students | percent   | percent     |
| Yes      | numeric metric | 2009_students    | 2009 Students      | number    | number      |
| Yes      | numeric metric | of_2009          | % of 2009          | percent   | percent     |
```

## Time Field

```ls
Value = 2009
Format & Zone = yyyy
```

## Data Commands

```ls
series e:dw5v-bykq d:2009-01-01T00:00:00.000Z t:race_ethnicity="Black/African American (Not Hispanic)" m:of_2013_students=4.5 m:of_2009=5.6 m:of_2010_students=4.7 m:2010_students=48413 m:of_2011=4.6 m:2013_students=46963 m:of_2012_students=4.6 m:2011_students=47191 m:2012_students=47856 m:2009_students=57718

series e:dw5v-bykq d:2009-01-01T00:00:00.000Z t:race_ethnicity="Asian (Not Hispanic)" m:of_2013_students=7.2 m:of_2009=7.9 m:of_2010_students=7.2 m:2010_students=73797 m:of_2011=7.2 m:2013_students=75187 m:of_2012_students=7.2 m:2011_students=74138 m:2012_students=74612 m:2009_students=81465

series e:dw5v-bykq d:2009-01-01T00:00:00.000Z t:race_ethnicity="American Indian/Alaskan Native (Not Hispanic)" m:of_2013_students=1.5 m:of_2009=2.5 m:of_2010_students=1.7 m:2010_students=17557 m:of_2011=1.6 m:2013_students=15775 m:of_2012_students=1.5 m:2011_students=16530 m:2012_students=16041 m:2009_students=25772
```

## Meta Commands

```ls
metric m:2013_students p:integer l:"*2013 Students" t:dataTypeName=number

metric m:of_2013_students p:float l:"% of 2013 Students" t:dataTypeName=percent

metric m:2012_students p:integer l:"*2012 Students" t:dataTypeName=number

metric m:of_2012_students p:float l:"% of 2012 Students" t:dataTypeName=percent

metric m:2011_students p:integer l:"*2011 Students" t:dataTypeName=number

metric m:of_2011 p:float l:"% of 2011" t:dataTypeName=percent

metric m:2010_students p:integer l:"*2010 Students" t:dataTypeName=number

metric m:of_2010_students p:float l:"% of 2010 Students" t:dataTypeName=percent

metric m:2009_students p:integer l:"2009 Students" t:dataTypeName=number

metric m:of_2009 p:float l:"% of 2009" t:dataTypeName=percent

entity e:dw5v-bykq l:"K-12 Public School Enrollment by Race/Ethnicity October 2009-2013" t:attribution="Office of Juvenile Justice" t:url=https://data.wa.gov/api/views/dw5v-bykq

property e:dw5v-bykq t:meta.view v:id=dw5v-bykq v:attributionLink=https://dshs.wa.gov/ra/office-juvenile-justice/washington-state-juvenile-justice-annual-report v:averageRating=0 v:name="K-12 Public School Enrollment by Race/Ethnicity October 2009-2013" v:attribution="Office of Juvenile Justice"

property e:dw5v-bykq t:meta.view.license v:name="Public Domain"

property e:dw5v-bykq t:meta.view.owner v:id=6p7r-jviv v:profileImageUrlMedium=/api/users/6p7r-jviv/profile_images/THUMB v:profileImageUrlLarge=/api/users/6p7r-jviv/profile_images/LARGE v:screenName="Alysa Kipersztok" v:profileImageUrlSmall=/api/users/6p7r-jviv/profile_images/TINY v:displayName="Alysa Kipersztok"

property e:dw5v-bykq t:meta.view.tableauthor v:id=6p7r-jviv v:profileImageUrlMedium=/api/users/6p7r-jviv/profile_images/THUMB v:profileImageUrlLarge=/api/users/6p7r-jviv/profile_images/LARGE v:screenName="Alysa Kipersztok" v:profileImageUrlSmall=/api/users/6p7r-jviv/profile_images/TINY v:roleName=viewer v:displayName="Alysa Kipersztok"
```

## Top Records

```ls
| race_ethnicity                                        | 2013_students | of_2013_students | 2012_students | of_2012_students | 2011_students | of_2011 | 2010_students | of_2010_students | 2009_students | of_2009 | 
| ===================================================== | ============= | ================ | ============= | ================ | ============= | ======= | ============= | ================ | ============= | ======= | 
| Black/African American (Not Hispanic)                 | 46963         | 4.5              | 47856         | 4.6              | 47191         | 4.6     | 48413         | 4.7              | 57718         | 5.6     | 
| Asian (Not Hispanic)                                  | 75187         | 7.2              | 74612         | 7.2              | 74138         | 7.2     | 73797         | 7.2              | 81465         | 7.9     | 
| American Indian/Alaskan Native (Not Hispanic)         | 15775         | 1.5              | 16041         | 1.5              | 16530         | 1.6     | 17557         | 1.7              | 25772         | 2.5     | 
| Hispanic/Latino of any race                           | 220500        | 21.0             | 210222        | 20.2             | 201789        | 19.5    | 193158        | 18.8             | 162844        | 15.9    | 
| White (Not Hispanic)                                  | 609029        | 58.1             | 615790        | 59.3             | 623497        | 60.2    | 631193        | 61.3             | 655263        | 63.9    | 
| Multiracial (2 or more races, Not Hispanic)           | 70226         | 6.7              | 65014         | 6.3              | 61563         | 5.9     | 55665         | 5.4              | 28570         | 2.8     | 
| Native Hawaiian/Other Pacific Islander (Not Hispanic) | 10107         | 1.0              | 9567          | 0.9              | 9232          | 0.9     | 9011          | 0.9              | 8912          | 0.9     | 
| * Not Provided/ Other/NA                              | 66            | 0.0              | 113           | 0.0              | 992           | 0.1     | 293           | 0.0              | 4177          | 0.4     | 
```