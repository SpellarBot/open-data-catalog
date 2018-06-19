# Budget Table: K2 (Other Current Expenses: Leasing)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/budget-table-k2-other-current-expenses-leasing-cb06a) |
| Metadata | [Link](https://data.hawaii.gov/api/views/ac7w-gtwf) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/ac7w-gtwf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/ac7w-gtwf/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | ac7w-gtwf |
| Name | Budget Table: K2 (Other Current Expenses: Leasing) |
| Created | 2014-01-29T06:42:21Z |
| Publication Date | 2014-01-29T06:45:55Z |

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
| Yes      | series tag     | non_recur          | Non-recur          | text      | text        |
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
series e:ac7w-gtwf d:2014-01-28T22:42:24.000Z t:mof=A t:line_no=1 t:dept_code=AGS t:item_description="RENTAL OF LAND & BUILDING" t:source_file_header="Act 134, SLH 2013  - AGS Other Current Expenses (Leasing)" t:object_code=5500 t:prog_id_org=AGS223IB m:fy_2014=4739600 m:fy_2013=4739600 m:fy_2015=4739600 m:fy_2012=4739600

series e:ac7w-gtwf d:2014-01-28T22:42:24.000Z t:mof=U t:line_no=1 t:dept_code=AGS t:item_description="RENTAL OF LAND AND BUILDING" t:source_file_header="Act 134, SLH 2013  - AGS Other Current Expenses (Leasing)" t:object_code=5500 t:prog_id_org=AGS223IB m:fy_2014=2100300 m:fy_2013=2100300 m:fy_2015=2100300 m:fy_2012=2100300

series e:ac7w-gtwf d:2014-01-28T22:42:24.000Z t:mof=A t:line_no=1 t:dept_code=AGS t:item_description="OTHER RENTAL OF EQUIPMENT" t:source_file_header="Act 134, SLH 2013  - AGS Other Current Expenses (Leasing)" t:object_code=5629 t:prog_id_org=AGS231FA m:fy_2014=494880 m:fy_2013=1087152 m:fy_2015=494880 m:fy_2012=307716
```

## Meta Commands

```ls
metric m:fy_2012 p:integer l:"FY 2012" t:dataTypeName=money

metric m:fy_2013 p:integer l:"FY 2013" t:dataTypeName=money

metric m:fy_2014 p:integer l:"FY 2014" t:dataTypeName=money

metric m:fy_2015 p:integer l:"FY 2015" t:dataTypeName=money

entity e:ac7w-gtwf l:"Budget Table: K2 (Other Current Expenses: Leasing)" t:url=https://data.hawaii.gov/api/views/ac7w-gtwf

property e:ac7w-gtwf t:meta.view v:id=ac7w-gtwf v:averageRating=0 v:name="Budget Table: K2 (Other Current Expenses: Leasing)"

property e:ac7w-gtwf t:meta.view.owner v:id=wktp-67q4 v:screenName=karen v:displayName=karen

property e:ac7w-gtwf t:meta.view.tableauthor v:id=wktp-67q4 v:screenName=karen v:roleName=administrator v:displayName=karen
```

## Top Records

```ls
| :updated_at | source_file_header                                              | dept_code | prog_id_org | line_no | item_description                    | mof | object_code | isl | non_recur | fy_2012  | fy_2013  | fy_2014  | fy_2015  | 
| =========== | =============================================================== | ========= | =========== | ======= | =================================== | === | =========== | === | ========= | ======== | ======== | ======== | ======== | 
| 1390948944  | Act 134, SLH 2013 - AGS Other Current Expenses (Leasing)        | AGS       | AGS223IB    | 1       | RENTAL OF LAND & BUILDING           | A   | 5500        |     |           | 4739600  | 4739600  | 4739600  | 4739600  | 
| 1390948944  | Act 134, SLH 2013 - AGS Other Current Expenses (Leasing)        | AGS       | AGS223IB    | 1       | RENTAL OF LAND AND BUILDING         | U   | 5500        |     |           | 2100300  | 2100300  | 2100300  | 2100300  | 
| 1390948944  | Act 134, SLH 2013 - AGS Other Current Expenses (Leasing)        | AGS       | AGS231FA    | 1       | OTHER RENTAL OF EQUIPMENT           | A   | 5629        |     |           | 307716   | 1087152  | 494880   | 494880   | 
| 1390948944  | Act 134, SLH 2013 - HHL Leasing (BK2) - Other Current Expenses  | HHL       | HHL602BB    | 27      | OTHER RENTALS                       | A   | 5700        |     |           | 0        | 0        | 1720000  | 1720000  | 
| 1390948944  | Act 134, SLH 2013 - HHL Leasing (BK2) - Other Current Expenses  | HHL       | HHL602BB    | 92      | CERTIFICATE OF PARTICIPATION (COPS) | B   | 5700        |     |           | 1720000  | 1720000  | 0        | 0        | 
| 1390948944  | Act 134, SLH 2013 - HHL Leasing (BK2) - Other Current Expenses  | HHL       | HHL625BB    | 43      | CERTIFICATE OF PARTICIPATION (COPS) | B   | 5700        |     |           | 0        | 0        | 0        | 0        | 
| 1390948944  | Act 134, SLH 2013 - HHSC Leasing (BK2) - Other Current Expenses | HTH-HHSC  | HTH210LA    | 2       | OTHER CURRENT SERVICES - LEASES     | B   | 7200        |     |           | 320000   | 234000   | 96000    | 32000    | 
| 1390948944  | Act 134, SLH 2013 - HHSC Leasing (BK2) - Other Current Expenses | HTH-HHSC  | HTH212LS    | 1       | OTHER CURRENT SERVICES - LEASES     | B   | 7200        |     |           | 12301000 | 12260000 | 14285000 | 11488000 | 
| 1390948944  | Act 134, SLH 2013 - PSD Leasing (BK2) - Other Current Expenses  | PSD       | PSD402ED    | 1       | NORESCO LEASE PAYMENT               | A   | 5790        |     |           | 0        | 0        | 1075563  | 1109869  | 
| 1390948944  | Act 134, SLH 2013 - PSD Leasing (BK2) - Other Current Expenses  | PSD       | PSD407EC    | 1       | NORESCO LEASE PAYMENT               | A   | 5790        |     |           | 0        | 0        | 639009   | 661609   | 
```