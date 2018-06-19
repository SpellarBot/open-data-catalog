# Salaries: OUS: Portland State University: FY 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/salaries-ous-portland-state-university-fy-2014-b89b5) |
| Metadata | [Link](https://data.oregon.gov/api/views/kgdq-26yj) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/kgdq-26yj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/kgdq-26yj/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | kgdq-26yj |
| Name | Salaries: OUS: Portland State University: FY 2014 |
| Category | Revenue & Expense |
| Tags | ous salaries, oregon university system salaries, portland state university salaries, psu salaries 2014, 2014 |
| Created | 2014-12-27T01:52:03Z |
| Publication Date | 2014-12-29T03:07:51Z |

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| Yes      | series tag     | agency         | AGENCY #       | text      | number      |
| Yes      | series tag     | agency_title   | AGENCY TITLE   | text      | text        |
| Yes      | series tag     | classification | CLASSIFICATION | text      | text        |
| Yes      | series tag     | service_type   | SERVICE TYPE   | text      | text        |
| Yes      | series tag     | full_part_time | FULL/PART-TIME | text      | text        |
| Yes      | numeric metric | annual_salary  | ANNUAL SALARY  | money     | money       |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:kgdq-26yj d:2014-01-01T00:00:00.000Z t:service_type=Faculty t:classification="RRI UT Salary Pool < .50" t:agency_title="OUS - Portland State University" t:agency=58090 t:full_part_time=Part-Time m:annual_salary=16000

series e:kgdq-26yj d:2014-01-01T00:00:00.000Z t:service_type="Executive/Admin and managerial" t:classification="PHE UX DirCtrPublicHealth Stud" t:agency_title="OUS - Portland State University" t:agency=58090 t:full_part_time=Full-Time m:annual_salary=113342

series e:kgdq-26yj d:2014-01-01T00:00:00.000Z t:service_type=Faculty t:classification="USP UT Salary Pool < .50" t:agency_title="OUS - Portland State University" t:agency=58090 t:full_part_time=Part-Time m:annual_salary=2499
```

## Meta Commands

```ls
metric m:annual_salary p:double l:"ANNUAL SALARY" t:dataTypeName=money

entity e:kgdq-26yj l:"Salaries: OUS: Portland State University: FY 2014" t:url=https://data.oregon.gov/api/views/kgdq-26yj

property e:kgdq-26yj t:meta.view v:id=kgdq-26yj v:category="Revenue & Expense" v:averageRating=0 v:name="Salaries: OUS: Portland State University: FY 2014"

property e:kgdq-26yj t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:kgdq-26yj t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| agency | agency_title                    | classification                 | service_type                   | full_part_time | annual_salary | 
| ====== | =============================== | ============================== | ============================== | ============== | ============= | 
| 58090  | OUS - Portland State University | RRI UT Salary Pool < .50       | Faculty                        | Part-Time      | 16000.00      | 
| 58090  | OUS - Portland State University | PHE UX DirCtrPublicHealth Stud | Executive/Admin and managerial | Full-Time      | 113342.00     | 
| 58090  | OUS - Portland State University | USP UT Salary Pool < .50       | Faculty                        | Part-Time      | 2499.00       | 
| 58090  | OUS - Portland State University | SBA UT Salary Pool < .50       | Faculty                        | Part-Time      | 3332.00       | 
| 58090  | OUS - Portland State University | Office Specialist 2            | Classified Staff               | Full-Time      | 38916.00      | 
| 58090  | OUS - Portland State University | EDU UP Asst Prof SPED          | Faculty                        | Full-Time      | 57771.00      | 
| 58090  | OUS - Portland State University | MUS UP Asc Prof Appl Clar      | Faculty                        | Full-Time      | 65637.00      | 
| 58090  | OUS - Portland State University | SSW UT Salary Pool < .50       | Faculty                        | Part-Time      | 14771.00      | 
| 58090  | OUS - Portland State University | SSW UT Salary Pool < .50       | Faculty                        | Part-Time      | 9639.00       | 
| 58090  | OUS - Portland State University | EDU UP PracticumInternship Co  | Other professionals            | Full-Time      | 47160.00      | 
```