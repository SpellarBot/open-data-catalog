# College Aid Awards and Payments by Academic Year, Institution and Program

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/college-aid-awards-and-payments-by-academic-year-institution-and-program) |
| Metadata | [Link](https://data.iowa.gov/api/views/4qe2-ucmd) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/4qe2-ucmd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/4qe2-ucmd/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | 4qe2-ucmd |
| Name | College Aid Awards and Payments by Academic Year, Institution and Program |
| Attribution | Iowa College Student Aid Commission |
| Category | Education |
| Tags | college aid, grants, scholarships |
| Created | 2014-12-05T14:07:02Z |
| Publication Date | 2016-09-28T14:31:03Z |

## Description

State scholarships and grant programs provide funding to assist Iowa students in paying for postsecondary education in Iowa. Programmatic reports provide information about the total number of applicants, recipients, and the total dollars they received under each program administered by the Commission.

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| No       | time           | :updated_at   | updated_at    | meta_data | meta_data   |
| Yes      | series tag     | academic_year | ACADEMIC YEAR | text      | text        |
| Yes      | series tag     | sector_name   | SECTOR NAME   | text      | text        |
| Yes      | series tag     | school        | SCHOOL        | text      | text        |
| Yes      | series tag     | program       | PROGRAM       | text      | text        |
| Yes      | numeric metric | awarded       | AWARDED       | number    | number      |
| Yes      | numeric metric | awarddollars  | AWARDDOLLARS  | money     | money       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:4qe2-ucmd d:2014-12-05T06:07:06.000Z t:academic_year=2013-2014 t:school="Iowa State University" t:program="Barber and Cosmetology Arts & Sciences Tuition Grant" t:sector_name="Regent Universities" m:awarddollars=0 m:awarded=0

series e:4qe2-ucmd d:2014-12-05T06:07:06.000Z t:academic_year=2013-2014 t:school="Iowa State University" t:program="Governors State Fair Scholarship" t:sector_name="Regent Universities" m:awarddollars=0 m:awarded=0

series e:4qe2-ucmd d:2014-12-05T06:07:06.000Z t:academic_year=2013-2014 t:school="Iowa State University" t:program="Iowa Tuition Grant Program" t:sector_name="Regent Universities" m:awarddollars=0 m:awarded=0
```

## Meta Commands

```ls
metric m:awarded p:integer l:AWARDED d:"Number of awards made" t:dataTypeName=number

metric m:awarddollars p:integer l:AWARDDOLLARS d:"Amount of payments made" t:dataTypeName=money

entity e:4qe2-ucmd l:"College Aid Awards and Payments by Academic Year, Institution and Program" t:attribution="Iowa College Student Aid Commission" t:url=https://data.iowa.gov/api/views/4qe2-ucmd

property e:4qe2-ucmd t:meta.view v:id=4qe2-ucmd v:category=Education v:averageRating=0 v:name="College Aid Awards and Payments by Academic Year, Institution and Program" v:attribution="Iowa College Student Aid Commission"

property e:4qe2-ucmd t:meta.view.license v:name="Public Domain"

property e:4qe2-ucmd t:meta.view.owner v:id=cx54-n882 v:profileImageUrlMedium=/api/users/cx54-n882/profile_images/THUMB v:profileImageUrlLarge=/api/users/cx54-n882/profile_images/LARGE v:screenName="Iowa College Student Aid Commission" v:profileImageUrlSmall=/api/users/cx54-n882/profile_images/TINY v:displayName="Iowa College Student Aid Commission"

property e:4qe2-ucmd t:meta.view.tableauthor v:id=cx54-n882 v:profileImageUrlMedium=/api/users/cx54-n882/profile_images/THUMB v:profileImageUrlLarge=/api/users/cx54-n882/profile_images/LARGE v:screenName="Iowa College Student Aid Commission" v:profileImageUrlSmall=/api/users/cx54-n882/profile_images/TINY v:roleName=editor v:displayName="Iowa College Student Aid Commission"
```

## Top Records

```ls
| :updated_at | academic_year | sector_name         | school                | program                                              | awarded | awarddollars | 
| =========== | ============= | =================== | ===================== | ==================================================== | ======= | ============ | 
| 1417759626  | 2013-2014     | Regent Universities | Iowa State University | Barber and Cosmetology Arts & Sciences Tuition Grant | 0       | 0            | 
| 1417759626  | 2013-2014     | Regent Universities | Iowa State University | Governors State Fair Scholarship                     | 0       | 0            | 
| 1417759626  | 2013-2014     | Regent Universities | Iowa State University | Iowa Tuition Grant Program                           | 0       | 0            | 
| 1417759626  | 2013-2014     | Regent Universities | Iowa State University | Iowa Voc-Tech Tuition Grant Program                  | 0       | 0            | 
| 1417759626  | 2013-2014     | Regent Universities | Iowa State University | Kibbie Grant Program                                 | 0       | 0            | 
| 1417759626  | 2013-2014     | Regent Universities | Iowa State University | Educational Training Voucher Program                 | 5       | 20000        | 
| 1417759626  | 2013-2014     | Regent Universities | Iowa State University | All Iowa Opportunity Foster Grant Program            | 6       | 15267        | 
| 1417759626  | 2013-2014     | Regent Universities | Iowa State University | All Iowa Opportunity Scholarship                     | 76      | 496986       | 
| 1417759626  | 2013-2014     | Regent Universities | Iowa State University | Iowa Grant Program                                   | 145     | 126505       | 
| 1417759626  | 2013-2014     | Regent Universities | Iowa State University | Iowa National Guard Education Assistance Program     | 225     | 1220082      | 
```