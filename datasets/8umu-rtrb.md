# Budget Table: J3 (Equipment)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/budget-table-j3-equipment-5731b) |
| Metadata | [Link](https://data.hawaii.gov/api/views/8umu-rtrb) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/8umu-rtrb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/8umu-rtrb/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | 8umu-rtrb |
| Name | Budget Table: J3 (Equipment) |
| Created | 2014-01-29T05:07:17Z |
| Publication Date | 2014-01-29T05:09:47Z |

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| No       | time           | :updated_at        | updated_at         | meta_data | meta_data   |
| Yes      | series tag     | source_file_header | Source File Header | text      | text        |
| Yes      | series tag     | dept_code          | Dept Code          | text      | text        |
| Yes      | series tag     | prog_id_org        | Prog ID/Org        | text      | text        |
| Yes      | series tag     | line_no            | Line No.           | text      | number      |
| Yes      | series tag     | item_description   | Item Description   | text      | text        |
| Yes      | series tag     | mof                | MOF                | text      | text        |
| Yes      | series tag     | object_code        | Object Code        | text      | number      |
| Yes      | series tag     | isl                | ISL                | text      | text        |
| Yes      | series tag     | r_a                | R/A                | text      | text        |
| Yes      | numeric metric | unit_cost          | Unit Cost          | money     | money       |
| Yes      | numeric metric | no_of_units        | No. of Units       | number    | number      |
| Yes      | numeric metric | fy_2012            | FY 2012            | money     | money       |
| Yes      | numeric metric | fy_2013            | FY 2013            | money     | money       |
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
series e:8umu-rtrb d:2014-01-28T21:07:21.000Z t:mof=B t:line_no=1 t:dept_code=AGR t:item_description="MISCELLANEOUS EQUIPMENT" t:source_file_header="Act 134, SLH 2013 AGR - Equipment" t:object_code=7700 t:prog_id_org=AGR101GA m:fy_2014=0 m:no_of_units=0 m:fy_2013=0 m:fy_2015=0 m:unit_cost=0 m:fy_2012=0

series e:8umu-rtrb d:2014-01-28T21:07:21.000Z t:mof=B t:line_no=2 t:dept_code=AGR t:item_description="VARIOUS EDP EQUIPMENT" t:source_file_header="Act 134, SLH 2013 AGR - Equipment" t:object_code=7760 t:prog_id_org=AGR101GA m:fy_2014=0 m:no_of_units=0 m:fy_2013=0 m:fy_2015=0 m:unit_cost=0 m:fy_2012=0

series e:8umu-rtrb d:2014-01-28T21:07:21.000Z t:mof=A t:line_no=1 t:dept_code=AGR t:item_description="VARIOUS EDP EQUIPMENT" t:source_file_header="Act 134, SLH 2013 AGR - Equipment" t:object_code=7760 t:prog_id_org=AGR122EA m:fy_2014=0 m:no_of_units=0 m:fy_2013=0 m:fy_2015=0 m:unit_cost=0 m:fy_2012=0
```

## Meta Commands

```ls
metric m:unit_cost p:double l:"Unit Cost" t:dataTypeName=money

metric m:no_of_units p:integer l:"No. of Units" t:dataTypeName=number

metric m:fy_2012 p:double l:"FY 2012" t:dataTypeName=money

metric m:fy_2013 p:double l:"FY 2013" t:dataTypeName=money

metric m:fy_2014 p:double l:"FY 2014" t:dataTypeName=money

metric m:fy_2015 p:double l:"FY 2015" t:dataTypeName=money

entity e:8umu-rtrb l:"Budget Table: J3 (Equipment)" t:url=https://data.hawaii.gov/api/views/8umu-rtrb

property e:8umu-rtrb t:meta.view v:id=8umu-rtrb v:averageRating=0 v:name="Budget Table: J3 (Equipment)"

property e:8umu-rtrb t:meta.view.owner v:id=wktp-67q4 v:screenName=karen v:displayName=karen

property e:8umu-rtrb t:meta.view.tableauthor v:id=wktp-67q4 v:screenName=karen v:roleName=administrator v:displayName=karen
```

## Top Records

```ls
| :updated_at | source_file_header                | dept_code | prog_id_org | line_no | item_description        | mof | object_code | isl | r_a | unit_cost | no_of_units | fy_2012 | fy_2013 | fy_2014 | fy_2015 | 
| =========== | ================================= | ========= | =========== | ======= | ======================= | === | =========== | === | === | ========= | =========== | ======= | ======= | ======= | ======= | 
| 1390943241  | Act 134, SLH 2013 AGR - Equipment | AGR       | AGR101GA    | 1       | MISCELLANEOUS EQUIPMENT | B   | 7700        |     |     | 0.00      | 0           | 0.00    | 0.00    | 0.00    | 0.00    | 
| 1390943241  | Act 134, SLH 2013 AGR - Equipment | AGR       | AGR101GA    | 2       | VARIOUS EDP EQUIPMENT   | B   | 7760        |     |     | 0.00      | 0           | 0.00    | 0.00    | 0.00    | 0.00    | 
| 1390943241  | Act 134, SLH 2013 AGR - Equipment | AGR       | AGR122EA    | 1       | VARIOUS EDP EQUIPMENT   | A   | 7760        |     |     | 0.00      | 0           | 0.00    | 0.00    | 0.00    | 0.00    | 
| 1390943241  | Act 134, SLH 2013 AGR - Equipment | AGR       | AGR122EA    | 2       | VARIOUS EQUIPMENT       | U   | 7700        |     |     | 0.00      | 0           | 0.00    | 0.00    | 0.00    | 0.00    | 
| 1390943241  | Act 134, SLH 2013 AGR - Equipment | AGR       | AGR122EB    | 1       | MISCELLANEOUS EQUIPMENT | W   | 7754        |     |     | 0.00      | 0           | 0.00    | 0.00    | 0.00    | 0.00    | 
| 1390943241  | Act 134, SLH 2013 AGR - Equipment | AGR       | AGR122EB    | 2       | MISCELLANEOUS EQUIPMENT | A   | 7754        |     |     | 0.00      | 0           | 0.00    | 0.00    | 0.00    | 0.00    | 
| 1390943241  | Act 134, SLH 2013 AGR - Equipment | AGR       | AGR122EB    | 3       | MISCELLANEOUS EQUIPMENT | U   | 7754        |     |     | 0.00      | 0           | 0.00    | 0.00    | 0.00    | 0.00    | 
| 1390943241  | Act 134, SLH 2013 AGR - Equipment | AGR       | AGR122EB    | 4       | GOLF CARTS              | A   | 7793        |     |     | 0.00      | 0           | 0.00    | 0.00    | 0.00    | 0.00    | 
| 1390943241  | Act 134, SLH 2013 AGR - Equipment | AGR       | AGR122EB    | 5       | COMPUTERS               | A   | 7763        |     |     | 0.00      | 0           | 0.00    | 0.00    | 0.00    | 0.00    | 
| 1390943241  | Act 134, SLH 2013 AGR - Equipment | AGR       | AGR122EB    | 6       | MICROSCOPES             | A   | 7732        |     |     | 0.00      | 0           | 0.00    | 0.00    | 0.00    | 0.00    | 
```