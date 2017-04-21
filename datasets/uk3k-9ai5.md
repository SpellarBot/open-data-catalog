# Full Time Employees By Job Classification

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/full-time-employees-by-job-classification-a0538) |
| Metadata | [Link](https://data.sfgov.org/api/views/uk3k-9ai5) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/uk3k-9ai5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/uk3k-9ai5/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | uk3k-9ai5 |
| Name | Full Time Employees By Job Classification |
| Attribution | San Francisco Department of Human Resources |
| Category | City Management and Ethics |
| Created | 2011-11-13T00:08:22Z |
| Publication Date | 2011-11-13T00:12:24Z |

## Description

Shows Full Time Employees by Classification. Used with the Salary Ranges by Classification and Job Titles by Classification

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| No       | time           | :updated_at        | updated_at         | meta_data | meta_data   |
| No       |                | fy                 | FY                 | number    | number      |
| Yes      | series tag     | dept_level         | Dept Level         | text      | text        |
| Yes      | series tag     | job_code           | Job Code           | text      | text        |
| Yes      | series tag     | job_title          | Job Title          | text      | text        |
| Yes      | numeric metric | sum_fte            | Sum FTE            | number    | number      |
| Yes      | numeric metric | biweekly_low_rate  | Biweekly Low Rate  | money     | money       |
| Yes      | numeric metric | biweekly_high_rate | Biweekly High Rate | money     | money       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = fy
```

## Data Commands

```ls
series e:uk3k-9ai5 d:2011-11-12T16:08:24.000Z t:job_code=0922 t:dept_level=AAM t:job_title="Manager I" m:biweekly_low_rate=3282 m:sum_fte=2 m:biweekly_high_rate=4188

series e:uk3k-9ai5 d:2011-11-12T16:08:24.000Z t:job_code=0963 t:dept_level=AAM t:job_title="Dept Head III" m:biweekly_low_rate=5368 m:sum_fte=1 m:biweekly_high_rate=6851

series e:uk3k-9ai5 d:2011-11-12T16:08:24.000Z t:job_code=1450 t:dept_level=AAM t:job_title="Executive Secretary 1" m:biweekly_low_rate=2074 m:sum_fte=1 m:biweekly_high_rate=2521
```

## Meta Commands

```ls
metric m:sum_fte p:float l:"Sum FTE" t:dataTypeName=number

metric m:biweekly_low_rate p:double l:"Biweekly Low Rate" t:dataTypeName=money

metric m:biweekly_high_rate p:double l:"Biweekly High Rate" t:dataTypeName=money

entity e:uk3k-9ai5 l:"Full Time Employees By Job Classification" t:attribution="San Francisco Department of Human Resources" t:url=https://data.sfgov.org/api/views/uk3k-9ai5

property e:uk3k-9ai5 t:meta.view v:id=uk3k-9ai5 v:category="City Management and Ethics" v:attributionLink=http://www.sfdhr.org v:averageRating=0 v:name="Full Time Employees By Job Classification" v:attribution="San Francisco Department of Human Resources"

property e:uk3k-9ai5 t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:uk3k-9ai5 t:meta.view.owner v:id=ivaz-tugd v:screenName="Department of Human Resources" v:displayName="Department of Human Resources"

property e:uk3k-9ai5 t:meta.view.tableauthor v:id=ivaz-tugd v:screenName="Department of Human Resources" v:roleName=editor v:displayName="Department of Human Resources"
```

## Top Records

```ls
| :updated_at | fy   | dept_level | job_code | job_title                   | sum_fte | biweekly_low_rate | biweekly_high_rate | 
| =========== | ==== | ========== | ======== | =========================== | ======= | ================= | ================== | 
| 1321114104  | 2010 | AAM        | 0922     | Manager I                   | 2.00    | 3282.00           | 4188.00            | 
| 1321114104  | 2010 | AAM        | 0963     | Dept Head III               | 1.00    | 5368.00           | 6851.00            | 
| 1321114104  | 2010 | AAM        | 1450     | Executive Secretary 1       | 1.00    | 2074.00           | 2521.00            | 
| 1321114104  | 2010 | AAM        | 3302     | Admission Attendant         | 4.00    | 1349.00           | 1634.00            | 
| 1321114104  | 2010 | AAM        | 3518     | Assoc Musm Cnsrvt, AAM      | 1.00    | 2377.00           | 2890.00            | 
| 1321114104  | 2010 | AAM        | 3524     | Principal Museum Preparator | 1.00    | 2104.00           | 2557.00            | 
| 1321114104  | 2010 | AAM        | 3525     | Chief Preparator            | 1.00    | 2314.00           | 2813.00            | 
| 1321114104  | 2010 | AAM        | 3546     | Curator 4                   | 2.00    | 2918.00           | 3547.00            | 
| 1321114104  | 2010 | AAM        | 3558     | Senior Museum Registrar     | 1.00    | 2319.00           | 2819.00            | 
| 1321114104  | 2010 | AAM        | 3633     | Librarian 2 - Asian Arts    | 1.00    | 2621.00           | 3187.00            | 
```