# Salary Ranges by Job Classification

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/salary-ranges-by-job-classification-9be65) |
| Metadata | [Link](https://data.sfgov.org/api/views/7h4w-reyq) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/7h4w-reyq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/7h4w-reyq/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | 7h4w-reyq |
| Name | Salary Ranges by Job Classification |
| Attribution | Department of Human Resources |
| Category | City Management and Ethics |
| Created | 2011-11-13T00:00:41Z |
| Publication Date | 2011-11-13T00:05:37Z |

## Description

Shows the job titles associated with job classifications. Used with the Job Titles by Classification and Employees by Classification

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type     | Render Type   |
| ======== | ============== | ================== | ================== | ============= | ============= |
| Yes      | series tag     | setid              | SetID              | text          | text          |
| Yes      | series tag     | job_code           | Job Code           | text          | text          |
| Yes      | time           | eff_date           | Eff Date           | calendar_date | calendar_date |
| No       |                | sal_end_date       | Sal End Date       | calendar_date | calendar_date |
| Yes      | series tag     | salary_setid       | Salary SetID       | text          | text          |
| Yes      | series tag     | sal_plan           | Sal Plan           | text          | text          |
| Yes      | series tag     | grade              | Grade              | text          | text          |
| Yes      | numeric metric | step               | Step               | number        | number        |
| Yes      | numeric metric | biweekly_high_rate | Biweekly High Rate | money         | money         |
| Yes      | numeric metric | biweekly_low_rate  | Biweekly Low Rate  | money         | money         |
| Yes      | series tag     | union_code         | Union Code         | text          | number        |
| Yes      | numeric metric | extended_step      | Extended Step      | number        | number        |
| Yes      | series tag     | pay_type           | Pay Type           | text          | text          |
```

## Time Field

```ls
Value = eff_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = sal_end_date
```

## Data Commands

```ls
series e:7h4w-reyq d:2009-07-01T00:00:00.000Z t:job_code=0109 t:sal_plan=SFM t:pay_type=C t:grade=00000 t:setid=COMMN t:salary_setid=COMMN t:union_code=330 m:biweekly_low_rate=0 m:extended_step=0 m:biweekly_high_rate=0 m:step=1

series e:7h4w-reyq d:2009-07-01T00:00:00.000Z t:job_code=0110 t:sal_plan=SFM t:pay_type=D t:grade=00000 t:setid=COMMN t:salary_setid=COMMN t:union_code=323 m:biweekly_low_rate=15 m:extended_step=0 m:biweekly_high_rate=15 m:step=1

series e:7h4w-reyq d:2009-07-01T00:00:00.000Z t:job_code=0111 t:sal_plan=SFM t:pay_type=D t:grade=00000 t:setid=COMMN t:salary_setid=COMMN t:union_code=323 m:biweekly_low_rate=25 m:extended_step=0 m:biweekly_high_rate=25 m:step=1
```

## Meta Commands

```ls
metric m:step p:integer l:Step t:dataTypeName=number

metric m:biweekly_high_rate p:double l:"Biweekly High Rate" t:dataTypeName=money

metric m:biweekly_low_rate p:double l:"Biweekly Low Rate" t:dataTypeName=money

metric m:extended_step p:integer l:"Extended Step" t:dataTypeName=number

entity e:7h4w-reyq l:"Salary Ranges by Job Classification" t:attribution="Department of Human Resources" t:url=https://data.sfgov.org/api/views/7h4w-reyq

property e:7h4w-reyq t:meta.view v:id=7h4w-reyq v:category="City Management and Ethics" v:attributionLink=http://www.sfdhr.org v:averageRating=0 v:name="Salary Ranges by Job Classification" v:attribution="Department of Human Resources"

property e:7h4w-reyq t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:7h4w-reyq t:meta.view.owner v:id=ivaz-tugd v:screenName="Department of Human Resources" v:displayName="Department of Human Resources"

property e:7h4w-reyq t:meta.view.tableauthor v:id=ivaz-tugd v:screenName="Department of Human Resources" v:roleName=editor v:displayName="Department of Human Resources"
```

## Top Records

```ls
| setid | job_code | eff_date            | sal_end_date        | salary_setid | sal_plan | grade | step | biweekly_high_rate | biweekly_low_rate | union_code | extended_step | pay_type | 
| ===== | ======== | =================== | =================== | ============ | ======== | ===== | ==== | ================== | ================= | ========== | ============= | ======== | 
| COMMN | 0109     | 2009-07-01T00:00:00 | 2010-06-30T00:00:00 | COMMN        | SFM      | 00000 | 1    | 0.00               | 0.00              | 330        | 0             | C        | 
| COMMN | 0110     | 2009-07-01T00:00:00 | 2010-06-30T00:00:00 | COMMN        | SFM      | 00000 | 1    | 15.00              | 15.00             | 323        | 0             | D        | 
| COMMN | 0111     | 2009-07-01T00:00:00 | 2010-06-30T00:00:00 | COMMN        | SFM      | 00000 | 1    | 25.00              | 25.00             | 323        | 0             | D        | 
| COMMN | 0112     | 2009-07-01T00:00:00 | 2010-06-30T00:00:00 | COMMN        | SFM      | 00000 | 1    | 50.00              | 50.00             | 323        | 0             | D        | 
| COMMN | 0114     | 2009-07-01T00:00:00 | 2010-06-30T00:00:00 | COMMN        | SFM      | 00000 | 1    | 100.00             | 100.00            | 323        | 0             | M        | 
| COMMN | 0115     | 2009-07-01T00:00:00 | 2010-06-30T00:00:00 | COMMN        | SFM      | 00000 | 1    | 100.00             | 100.00            | 323        | 0             | D        | 
| COMMN | 0116     | 2009-07-01T00:00:00 | 2010-06-30T00:00:00 | COMMN        | SFM      | 00000 | 1    | 200.00             | 200.00            | 323        | 0             | D        | 
| COMMN | 0118     | 2009-07-01T00:00:00 | 2010-06-30T00:00:00 | COMMN        | SFM      | 00000 | 1    | 500.00             | 500.00            | 323        | 0             | M        | 
| COMMN | 0119     | 2009-07-01T00:00:00 | 2010-06-30T00:00:00 | COMMN        | SFM      | 00000 | 1    | 0.00               | 0.00              | 323        | 0             |          | 
| COMMN | 0140     | 2009-07-01T00:00:00 | 2009-12-25T00:00:00 | COMMN        | SFM      | 0140F | 1    | 10630.00           | 10630.00          | 352        | 0             | B        | 
```