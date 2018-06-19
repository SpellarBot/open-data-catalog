# Education Directory

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/education-directory) |
| Metadata | [Link](https://data.ct.gov/api/views/9k2y-kqxn) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/9k2y-kqxn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/9k2y-kqxn/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | 9k2y-kqxn |
| Name | Education Directory |
| Attribution | State Department of Education |
| Category | Education |
| Tags | education, school, district, directory |
| Created | 2014-05-29T18:06:02Z |
| Publication Date | 2016-10-28T17:40:08Z |

## Description

This dataset contains the official listing of all public educational organizations in Connecticut as of October 28, 2016.  Data elements include district name, school name, organization type, organization code, address, open date, interdistrict magnet status and grades offered.

Included data are collected by the CT State Department of Education (CSDE) through the Directory Manager (DM) portal in accordance with Connecticut General Statute (C.G.S.) 10-4. This critical information is used by other data collection systems and for state and federal reporting. 

For more information regarding DM, please visit http://www.csde.state.ct.us/public/directorymanager/default.asp

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type | Render Type |
| ======== | ============== | ==================== | ==================== | ========= | =========== |
| No       | time           | :updated_at          | updated_at           | meta_data | meta_data   |
| Yes      | series tag     | district_name        | District Name        | text      | text        |
| Yes      | series tag     | name                 | School Name          | text      | text        |
| Yes      | series tag     | organization_type    | Organization Type    | text      | text        |
| Yes      | series tag     | organization_code    | Organization Code    | text      | text        |
| Yes      | series tag     | zipcode              | Zipcode              | text      | text        |
| Yes      | series tag     | phone                | Phone                | text      | text        |
| Yes      | numeric metric | prekindergarten      | PreKindergarten      | number    | text        |
| Yes      | numeric metric | kindergarten         | Kindergarten         | number    | text        |
| Yes      | numeric metric | grade_1              | Grade 1              | number    | text        |
| Yes      | numeric metric | grade_2              | Grade 2              | number    | text        |
| Yes      | numeric metric | grade_3              | Grade 3              | number    | text        |
| Yes      | numeric metric | grade_4              | Grade 4              | number    | text        |
| Yes      | numeric metric | grade_5              | Grade 5              | number    | text        |
| Yes      | numeric metric | grade_6              | Grade 6              | number    | text        |
| Yes      | numeric metric | grade_7              | Grade 7              | number    | text        |
| Yes      | numeric metric | grade_8              | Grade 8              | number    | text        |
| Yes      | numeric metric | grade_9              | Grade 9              | number    | text        |
| Yes      | numeric metric | grade_10             | Grade 10             | number    | text        |
| Yes      | numeric metric | grade_11             | Grade 11             | number    | text        |
| Yes      | numeric metric | grade_12             | Grade 12             | number    | text        |
| No       |                | student_open_date    | Student Open Date    | text      | text        |
| Yes      | series tag     | interdistrict_magnet | Interdistrict Magnet | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = student_open_date
```

## Data Commands

```ls
series e:9k2y-kqxn d:2016-10-28T17:36:41.000Z t:phone=203-794-8601 t:district_name="Bethel School District" t:organization_code=0090011 t:name="Bethel School District" t:zipcode=06801 t:organization_type="Public School Districts" t:interdistrict_magnet=0 m:grade_3=1 m:grade_2=1 m:grade_1=1 m:grade_7=1 m:grade_6=1 m:grade_5=1 m:grade_4=1 m:grade_8=1 m:grade_12=1 m:grade_9=1 m:grade_11=1 m:kindergarten=1 m:grade_10=1 m:prekindergarten=1

series e:9k2y-kqxn d:2016-10-28T17:36:41.000Z t:phone=860-546-6950 t:district_name="Canterbury School District" t:organization_code=0220011 t:name="Canterbury School District" t:zipcode=06331 t:organization_type="Public School Districts" t:interdistrict_magnet=0 m:grade_3=1 m:grade_2=1 m:grade_1=1 m:grade_7=1 m:grade_6=1 m:grade_5=1 m:grade_4=1 m:grade_8=1 m:grade_12=0 m:grade_9=0 m:grade_11=0 m:kindergarten=1 m:grade_10=0 m:prekindergarten=1

series e:9k2y-kqxn d:2016-10-28T17:36:41.000Z t:phone=860-455-9306 t:district_name="Chaplin School District" t:organization_code=0240011 t:name="Chaplin School District" t:zipcode=06235 t:organization_type="Public School Districts" t:interdistrict_magnet=0 m:grade_3=1 m:grade_2=1 m:grade_1=1 m:grade_7=0 m:grade_6=1 m:grade_5=1 m:grade_4=1 m:grade_8=0 m:grade_12=0 m:grade_9=0 m:grade_11=0 m:kindergarten=1 m:grade_10=0 m:prekindergarten=1
```

## Meta Commands

```ls
metric m:prekindergarten p:integer l:PreKindergarten t:dataTypeName=number

metric m:kindergarten p:integer l:Kindergarten t:dataTypeName=number

metric m:grade_1 p:integer l:"Grade 1" t:dataTypeName=number

metric m:grade_2 p:integer l:"Grade 2" t:dataTypeName=number

metric m:grade_3 p:integer l:"Grade 3" t:dataTypeName=number

metric m:grade_4 p:integer l:"Grade 4" t:dataTypeName=number

metric m:grade_5 p:integer l:"Grade 5" t:dataTypeName=number

metric m:grade_6 p:integer l:"Grade 6" t:dataTypeName=number

metric m:grade_7 p:integer l:"Grade 7" t:dataTypeName=number

metric m:grade_8 p:integer l:"Grade 8" t:dataTypeName=number

metric m:grade_9 p:integer l:"Grade 9" t:dataTypeName=number

metric m:grade_10 p:integer l:"Grade 10" t:dataTypeName=number

metric m:grade_11 p:integer l:"Grade 11" t:dataTypeName=number

metric m:grade_12 p:integer l:"Grade 12" t:dataTypeName=number

entity e:9k2y-kqxn l:"Education Directory" t:attribution="State Department of Education" t:url=https://data.ct.gov/api/views/9k2y-kqxn

property e:9k2y-kqxn t:meta.view v:id=9k2y-kqxn v:category=Education v:averageRating=0 v:name="Education Directory" v:attribution="State Department of Education"

property e:9k2y-kqxn t:meta.view.owner v:id=nyku-jy9c v:screenName="Stephanie O'Day" v:displayName="Stephanie O'Day"

property e:9k2y-kqxn t:meta.view.tableauthor v:id=nyku-jy9c v:screenName="Stephanie O'Day" v:roleName=editor v:displayName="Stephanie O'Day"
```

## Top Records

```ls
| :updated_at | district_name               | name                          | organization_type       | organization_code | zipcode    | phone        | prekindergarten | kindergarten | grade_1 | grade_2 | grade_3 | grade_4 | grade_5 | grade_6 | grade_7 | grade_8 | grade_9 | grade_10 | grade_11 | grade_12 | student_open_date     | interdistrict_magnet | 
| =========== | =========================== | ============================= | ======================= | ================= | ========== | ============ | =============== | ============ | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======== | ======== | ======== | ===================== | ==================== | 
| 1477676201  | Bethel School District      | Bethel School District        | Public School Districts | 0090011           | 06801      | 203-794-8601 | 1               | 1            | 1       | 1       | 1       | 1       | 1       | 1       | 1       | 1       | 1       | 1        | 1        | 1        | 01Jul1996 0:00:00.000 | 0                    | 
| 1477676201  | Canterbury School District  | Canterbury School District    | Public School Districts | 0220011           | 06331      | 860-546-6950 | 1               | 1            | 1       | 1       | 1       | 1       | 1       | 1       | 1       | 1       | 0       | 0        | 0        | 0        | 01Jul1996 0:00:00.000 | 0                    | 
| 1477676201  | Chaplin School District     | Chaplin School District       | Public School Districts | 0240011           | 06235      | 860-455-9306 | 1               | 1            | 1       | 1       | 1       | 1       | 1       | 1       | 0       | 0       | 0       | 0        | 0        | 0        | 01Jul1996 0:00:00.000 | 0                    | 
| 1477676201  | Colebrook School District   | Colebrook School District     | Public School Districts | 0290011           | 06021      | 860-379-2179 | 0               | 1            | 1       | 1       | 1       | 1       | 1       | 1       | 0       | 0       | 0       | 0        | 0        | 0        | 01Jul1996 0:00:00.000 | 0                    | 
| 1477676201  | Colebrook School District   | Colebrook Consolidated School | Public Schools          | 0290111           | 06021      | 860-379-2179 | 0               | 1            | 1       | 1       | 1       | 1       | 1       | 1       | 0       | 0       | 0       | 0        | 0        | 0        | 01Jul1984 0:00:00.000 | 0                    | 
| 1477676201  | Columbia School District    | Horace W. Porter School       | Public Schools          | 0300111           | 06237-0166 | 860-228-9493 | 1               | 1            | 1       | 1       | 1       | 1       | 1       | 1       | 1       | 1       | 0       | 0        | 0        | 0        | 01Jul1984 0:00:00.000 | 0                    | 
| 1477676201  | Eastford School District    | Eastford Elementary School    | Public Schools          | 0390111           | 06242-0158 | 860-974-1130 | 1               | 1            | 1       | 1       | 1       | 1       | 1       | 1       | 1       | 1       | 0       | 0        | 0        | 0        | 01Jul1984 0:00:00.000 | 0                    | 
| 1477676201  | East Haddam School District | East Haddam School District   | Public School Districts | 0410011           | 06469      | 860-873-5090 | 1               | 1            | 1       | 1       | 1       | 1       | 1       | 1       | 1       | 1       | 1       | 1        | 1        | 1        | 01Jul1996 0:00:00.000 | 0                    | 
| 1477676201  | East Haddam School District | Nathan Hale-Ray High School   | Public Schools          | 0416111           | 06469-0404 | 860-873-5065 | 0               | 0            | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 1       | 1        | 1        | 1        | 01Aug1994 0:00:00.000 | 0                    | 
| 1477676201  | Farmington School District  | Farmington School District    | Public School Districts | 0520011           | 06032      | 860-673-8270 | 1               | 1            | 1       | 1       | 1       | 1       | 1       | 1       | 1       | 1       | 1       | 1        | 1        | 1        | 01Jul1996 0:00:00.000 | 0                    | 
```