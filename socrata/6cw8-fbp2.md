# Human Resources--2010 Job Posting Information and Applicants

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/human-resources-2010-job-posting-information-and-applicants-f9751) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/6cw8-fbp2) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/6cw8-fbp2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/6cw8-fbp2/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | 6cw8-fbp2 |
| Name | Human Resources--2010 Job Posting Information and Applicants |
| Attribution | Cook County Department of Human Resources |
| Category | Finance & Administration |
| Created | 2011-09-12T18:18:37Z |
| Publication Date | 2014-10-27T16:44:15Z |

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type | Render Type |
| ======== | ============== | ==================== | ==================== | ========= | =========== |
| Yes      | series tag     | month_number         | Month Number         | text      | number      |
| No       |                | month                | Month                | text      | text        |
| Yes      | time           | closing_date         | Closing Date         | date      | date        |
| Yes      | series tag     | posting_number       | Posting Number       | text      | text        |
| Yes      | series tag     | job_code             | Job Code             | text      | text        |
| Yes      | series tag     | job_title            | Job Title            | text      | text        |
| Yes      | numeric metric | number_of_applicants | Number of Applicants | number    | number      |
```

## Time Field

```ls
Value = closing_date
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = month
```

## Data Commands

```ls
series e:6cw8-fbp2 d:2010-02-16T08:00:00.000Z t:posting_number=101686 t:job_code=144 t:job_title="Accountant IV-INTERNAL" t:month_number=2 m:number_of_applicants=1

series e:6cw8-fbp2 d:2010-02-16T08:00:00.000Z t:posting_number=101687 t:job_code=144 t:job_title="Accountant IV- EXTERNAL" t:month_number=2 m:number_of_applicants=19

series e:6cw8-fbp2 d:2010-02-16T08:00:00.000Z t:posting_number=101688 t:job_code=835 t:job_title="Law Librarian I - INTERNAL" t:month_number=2 m:number_of_applicants=1
```

## Meta Commands

```ls
metric m:number_of_applicants p:integer l:"Number of Applicants" d:"Amount of applications received for this posting number." t:dataTypeName=number

entity e:6cw8-fbp2 l:"Human Resources--2010 Job Posting Information and Applicants" t:attribution="Cook County Department of Human Resources" t:url=https://datacatalog.cookcountyil.gov/api/views/6cw8-fbp2

property e:6cw8-fbp2 t:meta.view v:id=6cw8-fbp2 v:category="Finance & Administration" v:averageRating=0 v:name="Human Resources--2010 Job Posting Information and Applicants" v:attribution="Cook County Department of Human Resources"

property e:6cw8-fbp2 t:meta.view.license v:name="Public Domain"

property e:6cw8-fbp2 t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:6cw8-fbp2 t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| month_number | month    | closing_date | posting_number | job_code | job_title                             | number_of_applicants | 
| ============ | ======== | ============ | ============== | ======== | ===================================== | ==================== | 
| 2            | February | 1266307200   | 101686         | 144      | Accountant IV-INTERNAL                | 1                    | 
| 2            | February | 1266307200   | 101687         | 144      | Accountant IV- EXTERNAL               | 19                   | 
| 2            | February | 1266307200   | 101688         | 835      | Law Librarian I - INTERNAL            | 1                    | 
| 2            | February | 1266307200   | 101689         | 835      | LAW LIBRARIAN I - EXTERNAL            | 12                   | 
| 2            | February | 1266307200   | 101690         | 907      | CLERK V-INTERNAL                      | 7                    | 
| 2            | February | 1266307200   | 101691         | 907      | CLERK V -EXTERNAL                     | 112                  | 
| 2            | February | 1266307200   | 101692         | 50       | ADMINISTRATIVE ASSISTANT IV-INTERNAL  | 0                    | 
| 2            | February | 1266307200   | 101693         | 50       | ADMINISTRATIVE ASSISTANT IV -EXTERNAL | 21                   | 
| 2            | February | 1266307200   | 101694         | 906      | CLERK IV-INTERNAL                     | 2                    | 
| 2            | February | 1266307200   | 101695         | 906      | CLERK IV-EXTERNAL                     | 116                  | 
```