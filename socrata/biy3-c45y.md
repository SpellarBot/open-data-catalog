# Dominant Languages by School and English Learner (EL) Status, 2014-15

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dominant-languages-by-school-and-english-learner-el-status-2014-15) |
| Metadata | [Link](https://data.ct.gov/api/views/biy3-c45y) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/biy3-c45y/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/biy3-c45y/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | biy3-c45y |
| Name | Dominant Languages by School and English Learner (EL) Status, 2014-15 |
| Attribution | State Department of Education |
| Category | Education |
| Tags | language, english learner, el |
| Created | 2015-07-21T13:29:13Z |
| Publication Date | 2015-07-21T13:31:28Z |

## Description

Under Connecticut General Statute 10-17f and NCLB, Local Education Agencies must ascertain the dominant language of all new K-12 students, which is typically done through a home language survey. This dataset contains the dominant languages reported by LEAs for students and English Learners during the 2014-15 school year by school.

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type | Render Type |
| ======== | ============== | ============ | ============ | ========= | =========== |
| Yes      | series tag     | districtname | DistrictName | text      | text        |
| Yes      | series tag     | schoolname   | SchoolName   | text      | text        |
| Yes      | series tag     | language     | Language     | text      | text        |
| Yes      | numeric metric | students     | Students     | number    | number      |
| Yes      | numeric metric | els          | ELs          | number    | number      |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:biy3-c45y d:2014-01-01T00:00:00.000Z t:schoolname="Andover Elementary School" t:districtname="Andover School District" t:language=English m:students=261

series e:biy3-c45y d:2014-01-01T00:00:00.000Z t:schoolname="Andover Elementary School" t:districtname="Andover School District" t:language=Polish m:students=7

series e:biy3-c45y d:2014-01-01T00:00:00.000Z t:schoolname="PACE (Positive and Create Education)" t:districtname="Ansonia School District" t:language=English m:students=38
```

## Meta Commands

```ls
metric m:students p:integer l:Students t:dataTypeName=number

metric m:els p:integer l:ELs t:dataTypeName=number

entity e:biy3-c45y l:"Dominant Languages by School and English Learner (EL) Status, 2014-15" t:attribution="State Department of Education" t:url=https://data.ct.gov/api/views/biy3-c45y

property e:biy3-c45y t:meta.view v:id=biy3-c45y v:category=Education v:averageRating=0 v:name="Dominant Languages by School and English Learner (EL) Status, 2014-15" v:attribution="State Department of Education"

property e:biy3-c45y t:meta.view.owner v:id=nyku-jy9c v:screenName="Stephanie O'Day" v:displayName="Stephanie O'Day"

property e:biy3-c45y t:meta.view.tableauthor v:id=nyku-jy9c v:screenName="Stephanie O'Day" v:roleName=editor v:displayName="Stephanie O'Day"
```

## Top Records

```ls
| districtname            | schoolname                           | language  | students | els | 
| ======================= | ==================================== | ========= | ======== | === | 
| Andover School District | Andover Elementary School            | English   | 261      |     | 
| Andover School District | Andover Elementary School            | Spanish   |          |     | 
| Andover School District | Andover Elementary School            | Italian   |          |     | 
| Andover School District | Andover Elementary School            | Polish    | 7        |     | 
| Andover School District | Andover Elementary School            | Ukrainian |          |     | 
| Andover School District | Andover Elementary School            | Bangla    |          |     | 
| Ansonia School District | PACE (Positive and Create Education) | English   | 38       |     | 
| Ansonia School District | PACE (Positive and Create Education) | Spanish   |          |     | 
| Ansonia School District | Mead School                          | English   | 541      |     | 
| Ansonia School District | Mead School                          | Spanish   | 31       | 16  | 
```