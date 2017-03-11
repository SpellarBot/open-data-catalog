# Salary: OUS: Southern Oregon University: Fiscal Year 2012

## Dataset

* [Dataset URL](https://data.oregon.gov/api/views/ih2u-hwyu/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/salary-ous-southern-oregon-university-fiscal-year-2012-37428)
* [Metadata URL](https://data.oregon.gov/api/views/ih2u-hwyu)
* Id = ih2u-hwyu
* Name = Salary: OUS: Southern Oregon University: Fiscal Year 2012
* Category = Revenue & Expense
* Created = 2012-12-15T01:15:34Z
* Publication Date = 2012-12-15T01:16:21Z
* Rows Updated = 2012-12-15T01:15:38Z

## Description



## Columns

```ls
| Name           | Field Name     | Data Type | Render Type | Schema Type    | Included | 
| ============== | ============== | ========= | =========== | ============== | ======== | 
| updated_at     | :updated_at    | meta_data | meta_data   | time           | No       | 
| AGENCY #       | agency         | number    | text        | numeric metric | Yes      | 
| AGENCY TITLE   | agency_title   | text      | text        | series tag     | Yes      | 
| CLASSIFICATION | classification | text      | text        | series tag     | Yes      | 
| SERVICE TYPE   | service_type   | text      | text        | series tag     | Yes      | 
| FULL/PART-TIME | full_part_time | text      | text        | series tag     | Yes      | 
| ANNUAL SALARY  | annual_salary  | money     | money       | numeric metric | Yes      | 
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = 
Annotation Fields = 
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

property e:ih2u-hwyu t:meta.view d:2017-03-07T18:08:16.058Z v:id=ih2u-hwyu v:category="Revenue & Expense" v:averageRating=0 v:name="Salary: OUS: Southern Oregon University: Fiscal Year 2012"

property e:ih2u-hwyu t:meta.view.owner d:2017-03-07T18:08:16.058Z v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:displayName="Paula N."

property e:ih2u-hwyu t:meta.view.tableauthor d:2017-03-07T18:08:16.058Z v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:displayName="Paula N."
```