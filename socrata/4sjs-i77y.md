# Salaries: OUS: Southern Oregon University: FY 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/salaries-ous-southern-oregon-university-fy-2014-6003c) |
| Metadata | [Link](https://data.oregon.gov/api/views/4sjs-i77y) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/4sjs-i77y/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/4sjs-i77y/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | 4sjs-i77y |
| Name | Salaries: OUS: Southern Oregon University: FY 2014 |
| Category | Revenue & Expense |
| Tags | ous salaries, oregon univeristy system salaries, southern oregon university salaries, sou salaries 2014, 2014 |
| Created | 2014-12-27T02:13:00Z |
| Publication Date | 2014-12-29T03:09:33Z |

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
series e:4sjs-i77y d:2014-01-01T00:00:00.000Z t:service_type="Classified Staff" t:classification="Administrative Program Assist" t:agency_title="OUS - Southern Oregon University" t:agency=58040 t:full_part_time=Full-Time m:annual_salary=29976

series e:4sjs-i77y d:2014-01-01T00:00:00.000Z t:service_type="Classified Staff" t:classification="Info Technology Consultant" t:agency_title="OUS - Southern Oregon University" t:agency=58040 t:full_part_time=Full-Time m:annual_salary=36552

series e:4sjs-i77y d:2014-01-01T00:00:00.000Z t:service_type="Classified Staff" t:classification="Accountant 1" t:agency_title="OUS - Southern Oregon University" t:agency=58040 t:full_part_time=Full-Time m:annual_salary=40764
```

## Meta Commands

```ls
metric m:annual_salary p:integer l:"ANNUAL SALARY" t:dataTypeName=money

entity e:4sjs-i77y l:"Salaries: OUS: Southern Oregon University: FY 2014" t:url=https://data.oregon.gov/api/views/4sjs-i77y

property e:4sjs-i77y t:meta.view v:id=4sjs-i77y v:category="Revenue & Expense" v:averageRating=0 v:name="Salaries: OUS: Southern Oregon University: FY 2014"

property e:4sjs-i77y t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:4sjs-i77y t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| agency | agency_title                     | classification                | service_type     | full_part_time | annual_salary | 
| ====== | ================================ | ============================= | ================ | ============== | ============= | 
| 58040  | OUS - Southern Oregon University | Administrative Program Assist | Classified Staff | Full-Time      | 29976         | 
| 58040  | OUS - Southern Oregon University | Info Technology Consultant    | Classified Staff | Full-Time      | 36552         | 
| 58040  | OUS - Southern Oregon University | Accountant 1                  | Classified Staff | Full-Time      | 40764         | 
| 58040  | OUS - Southern Oregon University | Library Technician 3          | Classified Staff | Full-Time      | 46980         | 
| 58040  | OUS - Southern Oregon University | Painter                       | Classified Staff | Full-Time      | 44724         | 
| 58040  | OUS - Southern Oregon University | Custodian                     | Classified Staff | Full-Time      | 24168         | 
| 58040  | OUS - Southern Oregon University | Info Technology Consultant    | Classified Staff | Full-Time      | 34896         | 
| 58040  | OUS - Southern Oregon University | Office Specialist 2           | Classified Staff | Full-Time      | 28752         | 
| 58040  | OUS - Southern Oregon University | Custodian                     | Classified Staff | Full-Time      | 24168         | 
| 58040  | OUS - Southern Oregon University | Equipment Systems Specialist  | Classified Staff | Full-Time      | 51276         | 
```