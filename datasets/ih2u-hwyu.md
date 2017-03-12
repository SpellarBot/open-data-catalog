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
| Rows Updated | 2012-12-15T01:15:38Z |

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| No       | time           | :updated_at    | updated_at     | meta_data | meta_data   |
| Yes      | numeric metric | agency         | AGENCY #       | number    | text        |
| Yes      | series tag     | agency_title   | AGENCY TITLE   | text      | text        |
| Yes      | series tag     | classification | CLASSIFICATION | text      | text        |
| Yes      | series tag     | service_type   | SERVICE TYPE   | text      | text        |
| Yes      | series tag     | full_part_time | FULL/PART-TIME | text      | text        |
| Yes      | numeric metric | annual_salary  | ANNUAL SALARY  | money     | money       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:ih2u-hwyu d:2012-12-14T17:15:36.000Z t:service_type="Classified Staff" t:classification="Accountant 1" t:agency_title="OUS - Southern Oregon University" t:full_part_time=Full-Time m:annual_salary=36048 m:agency=58040

series e:ih2u-hwyu d:2012-12-14T17:15:36.000Z t:service_type="Classified Staff" t:classification="Administrative Program Assist" t:agency_title="OUS - Southern Oregon University" t:full_part_time=Full-Time m:annual_salary=37800 m:agency=58040

series e:ih2u-hwyu d:2012-12-14T17:15:36.000Z t:service_type="Classified Staff" t:classification="Medical Transcriptionist" t:agency_title="OUS - Southern Oregon University" t:full_part_time=Full-Time m:annual_salary=36048 m:agency=58040
```

## Meta Commands

```ls
metric m:agency p:integer l:"AGENCY #" t:dataTypeName=number

entity e:ih2u-hwyu l:"Salary: OUS: Southern Oregon University: Fiscal Year 2012" t:url=https://data.oregon.gov/api/views/ih2u-hwyu

property e:ih2u-hwyu t:meta.view v:id=ih2u-hwyu v:category="Revenue & Expense" v:averageRating=0 v:name="Salary: OUS: Southern Oregon University: Fiscal Year 2012"

property e:ih2u-hwyu t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:displayName="Paula N."

property e:ih2u-hwyu t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:displayName="Paula N."
```