# Salaries: OUS: Oregon State University: FY 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/salaries-ous-oregon-state-university-fy-2014-33235) |
| Metadata | [Link](https://data.oregon.gov/api/views/6vza-6wij) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/6vza-6wij/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/6vza-6wij/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | 6vza-6wij |
| Name | Salaries: OUS: Oregon State University: FY 2014 |
| Category | Revenue & Expense |
| Tags | ous salaries, oregon univeristy system salaries, oregon state university salaries, osu salaries 2014, 2014 |
| Created | 2014-12-27T01:29:02Z |
| Publication Date | 2014-12-29T03:06:55Z |

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
series e:6vza-6wij d:2014-01-01T00:00:00.000Z t:service_type="Executive/Admin and managerial" t:classification="Administrator 3-Tier 1 H-COA" t:agency_title="OUS - Oregon State University" t:agency=58030 t:full_part_time=Full-Time m:annual_salary=1060008

series e:6vza-6wij d:2014-01-01T00:00:00.000Z t:service_type="Executive/Admin and managerial" t:classification="Administrator 3-PAC12 Md H-COA" t:agency_title="OUS - Oregon State University" t:agency=58030 t:full_part_time=Full-Time m:annual_salary=800004

series e:6vza-6wij d:2014-01-01T00:00:00.000Z t:service_type="Executive/Admin and managerial" t:classification="Executive 3-Athletics" t:agency_title="OUS - Oregon State University" t:agency=58030 t:full_part_time=Full-Time m:annual_salary=545508
```

## Meta Commands

```ls
metric m:annual_salary p:integer l:"ANNUAL SALARY" t:dataTypeName=money

entity e:6vza-6wij l:"Salaries: OUS: Oregon State University: FY 2014" t:url=https://data.oregon.gov/api/views/6vza-6wij

property e:6vza-6wij t:meta.view v:id=6vza-6wij v:category="Revenue & Expense" v:averageRating=0 v:name="Salaries: OUS: Oregon State University: FY 2014"

property e:6vza-6wij t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:6vza-6wij t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| agency | agency_title                  | classification                 | service_type                   | full_part_time | annual_salary | 
| ====== | ============================= | ============================== | ============================== | ============== | ============= | 
| 58030  | OUS - Oregon State University | Administrator 3-Tier 1 H-COA   | Executive/Admin and managerial | Full-Time      | 1060008       | 
| 58030  | OUS - Oregon State University | Administrator 3-PAC12 Md H-COA | Executive/Admin and managerial | Full-Time      | 800004        | 
| 58030  | OUS - Oregon State University | Executive 3-Athletics          | Executive/Admin and managerial | Full-Time      | 545508        | 
| 58030  | OUS - Oregon State University | Coordinator-Tier 1 Asst COA    | Other professionals            | Full-Time      | 490008        | 
| 58030  | OUS - Oregon State University | Executive 1-President          | Executive/Admin and managerial | Full-Time      | 485088        | 
| 58030  | OUS - Oregon State University | Administrator 3-Rev Oly H-COA  | Executive/Admin and managerial | Full-Time      | 323640        | 
| 58030  | OUS - Oregon State University | Coordinator-Tier 1 Asst COA    | Other professionals            | Full-Time      | 320004        | 
| 58030  | OUS - Oregon State University | Coordinator-Tier 1 Asst COA    | Other professionals            | Full-Time      | 315000        | 
| 58030  | OUS - Oregon State University | Executive 1-Provost/Exec VP    | Executive/Admin and managerial | Full-Time      | 309000        | 
| 58030  | OUS - Oregon State University | Administrator 3-PAC12 Md H-COA | Executive/Admin and managerial | Full-Time      | 275004        | 
```