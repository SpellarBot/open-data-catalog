# Salaries: OUS: University of Oregon: FY 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/salaries-ous-university-of-oregon-fy-2014-513c5) |
| Metadata | [Link](https://data.oregon.gov/api/views/uvwt-8xnj) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/uvwt-8xnj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/uvwt-8xnj/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | uvwt-8xnj |
| Name | Salaries: OUS: University of Oregon: FY 2014 |
| Category | Revenue & Expense |
| Tags | ous salaries, oregon university system salaries, university of oregon salaries, uo salaries 2014, 2014 |
| Created | 2014-12-27T02:01:12Z |
| Publication Date | 2014-12-29T03:08:57Z |

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
series e:uvwt-8xnj d:2014-01-01T00:00:00.000Z t:service_type=Faculty t:classification="Fixed Term Faculty" t:agency_title="OUS - University of Oregon" t:agency=58050 t:full_part_time=Part-Time m:annual_salary=12387

series e:uvwt-8xnj d:2014-01-01T00:00:00.000Z t:service_type=Faculty t:classification="Fixed Term Faculty" t:agency_title="OUS - University of Oregon" t:agency=58050 t:full_part_time=Full-Time m:annual_salary=37800

series e:uvwt-8xnj d:2014-01-01T00:00:00.000Z t:service_type="Classified Staff" t:classification="Campus Sec/Public Sfty Officer" t:agency_title="OUS - University of Oregon" t:agency=58050 t:full_part_time=Full-Time m:annual_salary=42708
```

## Meta Commands

```ls
metric m:annual_salary p:integer l:"ANNUAL SALARY" t:dataTypeName=money

entity e:uvwt-8xnj l:"Salaries: OUS: University of Oregon: FY 2014" t:url=https://data.oregon.gov/api/views/uvwt-8xnj

property e:uvwt-8xnj t:meta.view v:id=uvwt-8xnj v:category="Revenue & Expense" v:averageRating=0 v:name="Salaries: OUS: University of Oregon: FY 2014"

property e:uvwt-8xnj t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:uvwt-8xnj t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| agency | agency_title               | classification                 | service_type        | full_part_time | annual_salary | 
| ====== | ========================== | ============================== | =================== | ============== | ============= | 
| 58050  | OUS - University of Oregon | Fixed Term Faculty             | Faculty             | Part-Time      | 12387         | 
| 58050  | OUS - University of Oregon | Fixed Term Faculty             | Faculty             | Full-Time      | 37800         | 
| 58050  | OUS - University of Oregon | Campus Sec/Public Sfty Officer | Classified Staff    | Full-Time      | 42708         | 
| 58050  | OUS - University of Oregon | Office Specialist 2            | Classified Staff    | Full-Time      | 28745         | 
| 58050  | OUS - University of Oregon | Broadcast/Tele Engineer 1      | Classified Staff    | Full-Time      | 17733         | 
| 58050  | OUS - University of Oregon | Laboratory Assistant           | Classified Staff    | Full-Time      | 19473         | 
| 58050  | OUS - University of Oregon | 4:6400 Dir, Educ. Outreach     | Other professionals | Full-Time      | 65820         | 
| 58050  | OUS - University of Oregon | B:3520 Ablow Asst Professor    | Faculty             | Full-Time      | 79318         | 
| 58050  | OUS - University of Oregon | S:0000 CostAcctFinAnlystRptMgr | Other professionals | Full-Time      | 72776         | 
| 58050  | OUS - University of Oregon | Fixed Term Teach/Rsrch 12 mo   | Faculty             | Full-Time      | 51000         | 
```