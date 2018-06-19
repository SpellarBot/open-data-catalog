# Budget Table: J4 (Motor Vehicles)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/budget-table-j4-motor-vehicles-dfefd) |
| Metadata | [Link](https://data.hawaii.gov/api/views/htsw-v9h2) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/htsw-v9h2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/htsw-v9h2/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | htsw-v9h2 |
| Name | Budget Table: J4 (Motor Vehicles) |
| Created | 2014-01-29T06:05:03Z |
| Publication Date | 2014-01-29T06:09:45Z |

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| No       | time           | :updated_at        | updated_at         | meta_data | meta_data   |
| Yes      | series tag     | source_file_header | Source File Header | text      | text        |
| Yes      | series tag     | dept_code          | Dept Code          | text      | text        |
| Yes      | series tag     | program_id         | Program ID         | text      | text        |
| Yes      | series tag     | line_no            | Line No.           | text      | number      |
| Yes      | series tag     | item_description   | Item Description   | text      | text        |
| Yes      | series tag     | mof                | MOF                | text      | text        |
| Yes      | series tag     | object_code        | Object Code        | text      | number      |
| Yes      | series tag     | isl                | ISL                | text      | text        |
| Yes      | series tag     | r_a                | R/A                | text      | text        |
| Yes      | numeric metric | year               | Year               | number    | number      |
| Yes      | series tag     | model              | Model              | text      | text        |
| Yes      | numeric metric | miles_run          | Miles Run          | number    | number      |
| Yes      | numeric metric | actual_fy_2012     | Actual FY 2012     | money     | money       |
| Yes      | numeric metric | est_fy_2013        | Est FY 2013        | money     | money       |
| Yes      | numeric metric | fy_2014            | FY 2014            | money     | money       |
| Yes      | numeric metric | fy_2015            | FY 2015            | money     | money       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:htsw-v9h2 d:2014-01-28T22:05:06.000Z t:mof=B t:line_no=1 t:dept_code=AGR t:item_description=VEHICLE t:program_id=AGR101GA t:source_file_header="Act 134, SLH 2013 - AGR Motor Vehicles" t:object_code=7798 m:fy_2014=0 m:fy_2015=0 m:miles_run=0 m:year=0 m:est_fy_2013=0 m:actual_fy_2012=0

series e:htsw-v9h2 d:2014-01-28T22:05:06.000Z t:mof=A t:line_no=1 t:dept_code=AGR t:item_description=VEHICLES t:program_id=AGR122EB t:r_a=A t:source_file_header="Act 134, SLH 2013 - AGR Motor Vehicles" t:object_code=7798 m:fy_2014=0 m:fy_2015=0 m:miles_run=0 m:year=0 m:est_fy_2013=0 m:actual_fy_2012=0

series e:htsw-v9h2 d:2014-01-28T22:05:06.000Z t:mof=A t:line_no=2 t:dept_code=AGR t:item_description=VEHICLE t:program_id=AGR122EB t:source_file_header="Act 134, SLH 2013 - AGR Motor Vehicles" t:object_code=7798 m:fy_2014=0 m:fy_2015=0 m:miles_run=0 m:year=0 m:est_fy_2013=0 m:actual_fy_2012=0
```

## Meta Commands

```ls
metric m:year p:integer l:Year t:dataTypeName=number

metric m:miles_run p:integer l:"Miles Run" t:dataTypeName=number

metric m:actual_fy_2012 p:double l:"Actual FY 2012" t:dataTypeName=money

metric m:est_fy_2013 p:double l:"Est FY 2013" t:dataTypeName=money

metric m:fy_2014 p:double l:"FY 2014" t:dataTypeName=money

metric m:fy_2015 p:double l:"FY 2015" t:dataTypeName=money

entity e:htsw-v9h2 l:"Budget Table: J4 (Motor Vehicles)" t:url=https://data.hawaii.gov/api/views/htsw-v9h2

property e:htsw-v9h2 t:meta.view v:id=htsw-v9h2 v:averageRating=0 v:name="Budget Table: J4 (Motor Vehicles)"

property e:htsw-v9h2 t:meta.view.owner v:id=wktp-67q4 v:screenName=karen v:displayName=karen

property e:htsw-v9h2 t:meta.view.tableauthor v:id=wktp-67q4 v:screenName=karen v:roleName=administrator v:displayName=karen
```

## Top Records

```ls
| :updated_at | source_file_header                     | dept_code | program_id | line_no | item_description           | mof | object_code | isl | r_a | year | model | miles_run | actual_fy_2012 | est_fy_2013 | fy_2014 | fy_2015 | 
| =========== | ====================================== | ========= | ========== | ======= | ========================== | === | =========== | === | === | ==== | ===== | ========= | ============== | =========== | ======= | ======= | 
| 1390946706  | Act 134, SLH 2013 - AGR Motor Vehicles | AGR       | AGR101GA   | 1       | VEHICLE                    | B   | 7798        |     |     | 0    |       | 0         | 0.00           | 0.00        | 0.00    | 0.00    | 
| 1390946706  | Act 134, SLH 2013 - AGR Motor Vehicles | AGR       | AGR122EB   | 1       | VEHICLES                   | A   | 7798        |     | A   | 0    |       | 0         | 0.00           | 0.00        | 0.00    | 0.00    | 
| 1390946706  | Act 134, SLH 2013 - AGR Motor Vehicles | AGR       | AGR122EB   | 2       | VEHICLE                    | A   | 7798        |     |     | 0    |       | 0         | 0.00           | 0.00        | 0.00    | 0.00    | 
| 1390946706  | Act 134, SLH 2013 - AGR Motor Vehicles | AGR       | AGR122EB   | 3       | VEHICLE                    | A   | 7798        |     | A   | 0    |       | 0         | 0.00           | 0.00        | 0.00    | 0.00    | 
| 1390946706  | Act 134, SLH 2013 - AGR Motor Vehicles | AGR       | AGR122EB   | 4       | SPORT UTILITY VEHICLE, 4WD | A   | 7798        |     | A   | 0    |       | 0         | 0.00           | 0.00        | 0.00    | 0.00    | 
| 1390946706  | Act 134, SLH 2013 - AGR Motor Vehicles | AGR       | AGR122EB   | 5       | SPORT UTILITY VEHICLE, 4WD | A   | 7798        |     | A   | 0    |       | 0         | 0.00           | 0.00        | 0.00    | 0.00    | 
| 1390946706  | Act 134, SLH 2013 - AGR Motor Vehicles | AGR       | AGR122EB   | 6       | SPORT UTILITY VEHICLE, 4WD | A   | 7798        |     | A   | 0    |       | 0         | 0.00           | 0.00        | 0.00    | 0.00    | 
| 1390946706  | Act 134, SLH 2013 - AGR Motor Vehicles | AGR       | AGR122EB   | 7       | VAN                        | A   | 7798        |     | A   | 0    |       | 0         | 0.00           | 0.00        | 0.00    | 0.00    | 
| 1390946706  | Act 134, SLH 2013 - AGR Motor Vehicles | AGR       | AGR122EB   | 8       | VAN                        | A   | 7798        |     | A   | 0    |       | 0         | 0.00           | 0.00        | 0.00    | 0.00    | 
| 1390946706  | Act 134, SLH 2013 - AGR Motor Vehicles | AGR       | AGR122EC   | 1       | VEHICLE                    | A   | 7798        |     |     | 0    |       | 0         | 0.00           | 0.00        | 0.00    | 0.00    | 
```