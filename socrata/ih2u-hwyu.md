# Salary: OUS: Southern Oregon University: Fiscal Year 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/salary-ous-southern-oregon-university-fiscal-year-2012-37428) |
| Metadata | [Link](https://data.oregon.gov/api/views/ih2u-hwyu) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/ih2u-hwyu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/ih2u-hwyu/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | ih2u-hwyu |
| Name | Salary: OUS: Southern Oregon University: Fiscal Year 2012 |
| Category | Revenue & Expense |
| Created | 2012-12-15T01:15:34Z |
| Publication Date | 2012-12-15T01:16:21Z |

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| Yes      | series tag     | agency         | AGENCY #       | text      | text        |
| Yes      | series tag     | agency_title   | AGENCY TITLE   | text      | text        |
| Yes      | series tag     | classification | CLASSIFICATION | text      | text        |
| Yes      | series tag     | service_type   | SERVICE TYPE   | text      | text        |
| Yes      | series tag     | full_part_time | FULL/PART-TIME | text      | text        |
| Yes      | numeric metric | annual_salary  | ANNUAL SALARY  | money     | money       |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ih2u-hwyu d:2012-01-01T00:00:00.000Z t:service_type="Classified Staff" t:full_part_time=Full-Time t:agency=58040 t:agency_title="OUS - Southern Oregon University" t:classification="Accountant 1" m:annual_salary=36048

series e:ih2u-hwyu d:2012-01-01T00:00:00.000Z t:service_type="Classified Staff" t:full_part_time=Full-Time t:agency=58040 t:agency_title="OUS - Southern Oregon University" t:classification="Administrative Program Assist" m:annual_salary=37800

series e:ih2u-hwyu d:2012-01-01T00:00:00.000Z t:service_type="Classified Staff" t:full_part_time=Full-Time t:agency=58040 t:agency_title="OUS - Southern Oregon University" t:classification="Medical Transcriptionist" m:annual_salary=36048
```

## Meta Commands

```ls
metric m:annual_salary p:integer l:"ANNUAL SALARY" t:dataTypeName=money

entity e:ih2u-hwyu l:"Salary: OUS: Southern Oregon University: Fiscal Year 2012" t:url=https://data.oregon.gov/api/views/ih2u-hwyu

property e:ih2u-hwyu t:meta.view d:2017-09-25T07:31:56.947Z v:averageRating=0 v:name="Salary: OUS: Southern Oregon University: Fiscal Year 2012" v:id=ih2u-hwyu v:category="Revenue & Expense"

property e:ih2u-hwyu t:meta.view.owner d:2017-09-25T07:31:56.947Z v:displayName="Paula N." v:lastNotificationSeenAt=1500509429 v:id=d6zz-js5q v:screenName="Paula N."

property e:ih2u-hwyu t:meta.view.tableauthor d:2017-09-25T07:31:56.947Z v:displayName="Paula N." v:lastNotificationSeenAt=1500509429 v:roleName=administrator v:id=d6zz-js5q v:screenName="Paula N."
```

## Top Records

```ls
| agency | agency_title                     | classification                | service_type     | full_part_time | annual_salary | 
| ====== | ================================ | ============================= | ================ | ============== | ============= | 
| 58040  | OUS - Southern Oregon University | Accountant 1                  | Classified Staff | Full-Time      | 36048         | 
| 58040  | OUS - Southern Oregon University | Administrative Program Assist | Classified Staff | Full-Time      | 37800         | 
| 58040  | OUS - Southern Oregon University | Medical Transcriptionist      | Classified Staff | Full-Time      | 36048         | 
| 58040  | OUS - Southern Oregon University | Library Technician 3          | Classified Staff | Full-Time      | 41472         | 
| 58040  | OUS - Southern Oregon University | Program Representative 2      | Classified Staff | Full-Time      | 50064         | 
| 58040  | OUS - Southern Oregon University | Painter                       | Classified Staff | Full-Time      | 41472         | 
| 58040  | OUS - Southern Oregon University | Office Specialist 2           | Classified Staff | Full-Time      | 27924         | 
| 58040  | OUS - Southern Oregon University | Food Service Coordinator      | Classified Staff | Full-Time      | 31608         | 
| 58040  | OUS - Southern Oregon University | Office Specialist 2           | Classified Staff | Full-Time      | 39588         | 
| 58040  | OUS - Southern Oregon University | Property Specialist 2         | Classified Staff | Full-Time      | 25104         | 
```