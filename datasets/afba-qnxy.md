# Kindergarten Students with Pre-kindergarten Experience by District: 2009-2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/kindergarten-students-with-pre-kindergarten-experience-by-district-2009-2012) |
| Metadata | [Link](https://data.ct.gov/api/views/afba-qnxy) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/afba-qnxy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/afba-qnxy/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | afba-qnxy |
| Name | Kindergarten Students with Pre-kindergarten Experience by District: 2009-2012 |
| Attribution | State Department of Education |
| Category | Education |
| Tags | education, pre-kindergarten, prek, district, ctkids |
| Created | 2014-07-24T21:12:19Z |
| Publication Date | 2014-07-24T21:14:57Z |

## Description

This dataset contains the percentage of Kindergarten students with Pre-kindergarten experience by district for school years 2009-10 through 2012-13.

## Columns

```ls
| Included | Schema Type    | Field Name                                                                     | Name                                                                           | Data Type | Render Type |
| ======== | ============== | ============================================================================== | ============================================================================== | ========= | =========== |
| Yes      | series tag     | district_number                                                                | District number                                                                | text      | number      |
| Yes      | series tag     | district_name                                                                  | District name                                                                  | text      | text        |
| Yes      | numeric metric | percentage_of_kindergarten_students_with_pre_kindergarten_experience_2009_10   | Percentage of Kindergarten Students with Pre-kindergarten Experience 2009-10   | percent   | percent     |
| Yes      | numeric metric | percentage_of_kindergarten_students_with_pre_kindergarten_experience_2010_11   | Percentage of Kindergarten Students with Pre-kindergarten Experience 2010-11   | percent   | percent     |
| Yes      | numeric metric | percentage_of_kindergarten_students_with_pre_kindergarten_experience_2011_12   | Percentage of Kindergarten Students with Pre-kindergarten Experience 2011-12   | percent   | percent     |
| Yes      | numeric metric | percentage_of_kindergartener_students_with_pre_kindergarten_experience_2012_13 | Percentage of Kindergartener Students with Pre-Kindergarten Experience 2012-13 | percent   | percent     |
```

## Time Field

```ls
Value = 2009
Format & Zone = yyyy
```

## Data Commands

```ls
series e:afba-qnxy d:2009-01-01T00:00:00.000Z t:district_name="Andover School District" t:district_number=1 m:percentage_of_kindergarten_students_with_pre_kindergarten_experience_2010_11=92.86 m:percentage_of_kindergartener_students_with_pre_kindergarten_experience_2012_13=89.3 m:percentage_of_kindergarten_students_with_pre_kindergarten_experience_2011_12=68.6 m:percentage_of_kindergarten_students_with_pre_kindergarten_experience_2009_10=93.3

series e:afba-qnxy d:2009-01-01T00:00:00.000Z t:district_name="Ansonia School District" t:district_number=2 m:percentage_of_kindergarten_students_with_pre_kindergarten_experience_2010_11=80.39 m:percentage_of_kindergartener_students_with_pre_kindergarten_experience_2012_13=70.5 m:percentage_of_kindergarten_students_with_pre_kindergarten_experience_2011_12=70.7 m:percentage_of_kindergarten_students_with_pre_kindergarten_experience_2009_10=92.5

series e:afba-qnxy d:2009-01-01T00:00:00.000Z t:district_name="Ashford School District" t:district_number=3 m:percentage_of_kindergarten_students_with_pre_kindergarten_experience_2010_11=95.83 m:percentage_of_kindergartener_students_with_pre_kindergarten_experience_2012_13=80.6 m:percentage_of_kindergarten_students_with_pre_kindergarten_experience_2011_12=87.5 m:percentage_of_kindergarten_students_with_pre_kindergarten_experience_2009_10=90.3
```

## Meta Commands

```ls
metric m:percentage_of_kindergarten_students_with_pre_kindergarten_experience_2009_10 p:float l:"Percentage of Kindergarten Students with Pre-kindergarten Experience 2009-10" t:dataTypeName=percent

metric m:percentage_of_kindergarten_students_with_pre_kindergarten_experience_2010_11 p:float l:"Percentage of Kindergarten Students with Pre-kindergarten Experience 2010-11" t:dataTypeName=percent

metric m:percentage_of_kindergarten_students_with_pre_kindergarten_experience_2011_12 p:float l:"Percentage of Kindergarten Students with Pre-kindergarten Experience 2011-12" t:dataTypeName=percent

metric m:percentage_of_kindergartener_students_with_pre_kindergarten_experience_2012_13 p:float l:"Percentage of Kindergartener Students with Pre-Kindergarten Experience 2012-13" t:dataTypeName=percent

entity e:afba-qnxy l:"Kindergarten Students with Pre-kindergarten Experience by District: 2009-2012" t:attribution="State Department of Education" t:url=https://data.ct.gov/api/views/afba-qnxy

property e:afba-qnxy t:meta.view v:id=afba-qnxy v:category=Education v:averageRating=0 v:name="Kindergarten Students with Pre-kindergarten Experience by District: 2009-2012" v:attribution="State Department of Education"

property e:afba-qnxy t:meta.view.owner v:id=nyku-jy9c v:screenName="Stephanie O'Day" v:displayName="Stephanie O'Day"

property e:afba-qnxy t:meta.view.tableauthor v:id=nyku-jy9c v:screenName="Stephanie O'Day" v:roleName=editor v:displayName="Stephanie O'Day"
```

## Top Records

```ls
| district_number | district_name               | percentage_of_kindergarten_students_with_pre_kindergarten_experience_2009_10 | percentage_of_kindergarten_students_with_pre_kindergarten_experience_2010_11 | percentage_of_kindergarten_students_with_pre_kindergarten_experience_2011_12 | percentage_of_kindergartener_students_with_pre_kindergarten_experience_2012_13 | 
| =============== | =========================== | ============================================================================ | ============================================================================ | ============================================================================ | ============================================================================== | 
| 1               | Andover School District     | 93.3                                                                         | 92.86                                                                        | 68.6                                                                         | 89.3                                                                           | 
| 2               | Ansonia School District     | 92.5                                                                         | 80.39                                                                        | 70.7                                                                         | 70.5                                                                           | 
| 3               | Ashford School District     | 90.3                                                                         | 95.83                                                                        | 87.5                                                                         | 80.6                                                                           | 
| 4               | Avon School District        | 84.5                                                                         | 82.72                                                                        | 88.6                                                                         | 84.0                                                                           | 
| 5               | Barkhamsted School District | 71.4                                                                         | 77.55                                                                        | 23.8                                                                         | 75.0                                                                           | 
| 7               | Berlin School District      | 95.0                                                                         | 93.78                                                                        | 86.3                                                                         | 86.9                                                                           | 
| 8               | Bethany School District     | 96.5                                                                         | 88.68                                                                        | 91.5                                                                         | 90.0                                                                           | 
| 9               | Bethel School District      | 82.4                                                                         | 76.69                                                                        | 86.5                                                                         | 91.8                                                                           | 
| 11              | Bloomfield School District  | 88.7                                                                         | 93.91                                                                        | 91.9                                                                         | 90.5                                                                           | 
| 12              | Bolton School District      | 92.5                                                                         | 91.53                                                                        | 100.0                                                                        | 87.2                                                                           | 
```