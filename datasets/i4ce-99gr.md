# Budget Table - J1 (Salary and FTE)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/budget-table-j1-salary-and-fte-f28d8) |
| Metadata | [Link](https://data.hawaii.gov/api/views/i4ce-99gr) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/i4ce-99gr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/i4ce-99gr/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | i4ce-99gr |
| Name | Budget Table - J1 (Salary and FTE) |
| Created | 2014-01-28T20:54:32Z |
| Publication Date | 2014-01-28T21:07:40Z |
| Rows Updated | 2014-01-28T20:59:53Z |

## Columns

```ls
| Included | Schema Type    | Field Name         | Name                | Data Type     | Render Type   |
| ======== | ============== | ================== | =================== | ============= | ============= |
| Yes      | series tag     | source_file_header | Source File Header  | text          | text          |
| Yes      | series tag     | dept_code          | Dept Code           | text          | text          |
| Yes      | series tag     | prog_id_org        | Prog ID/Org         | text          | text          |
| Yes      | series tag     | position_number    | Position Number     | text          | text          |
| Yes      | series tag     | perm_temp_j1a      | Perm/Temp/J1A       | text          | text          |
| Yes      | series tag     | mof                | MOF                 | text          | text          |
| Yes      | series tag     | position_title     | Position Title      | text          | text          |
| Yes      | numeric metric | fy_12_fte          | FY 12 FTE           | number        | number        |
| Yes      | numeric metric | fy_12_salary       | FY 12 Salary        | money         | money         |
| Yes      | numeric metric | fy_13_fte          | FY 13 FTE           | number        | number        |
| Yes      | numeric metric | fy_13_salary       | FY 13 Salary        | money         | money         |
| Yes      | numeric metric | fy_14_fte          | FY 14 FTE           | number        | number        |
| Yes      | numeric metric | fy_14_salary       | FY 14 Salary        | money         | money         |
| Yes      | numeric metric | fy_15_fte          | FY 15 FTE           | number        | number        |
| Yes      | numeric metric | fy_15_salary       | FY 15 Salary        | money         | money         |
| Yes      | series tag     | incumbent_name     | Incumbent Name      | text          | text          |
| Yes      | series tag     | bu_code            | BU Code             | text          | number        |
| Yes      | series tag     | sr_level           | SR Level            | text          | text          |
| Yes      | series tag     | soh_org_code       | SOH Org Code        | text          | number        |
| Yes      | time           | next_step_mvt_date | Next Step Mvt Date  | calendar_date | calendar_date |
| Yes      | series tag     | job_code           | Job Code            | text          | number        |
| Yes      | series tag     | apprn_account_uac  | Apprn Account (UAC) | text          | text          |
```

## Time Field

```ls
Value = next_step_mvt_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:i4ce-99gr d:2017-03-15T07:15:18.279Z t:mof=A t:perm_temp_j1a=J1A t:dept_code=UOH t:position_title=CASUAL-PAYROLL t:source_file_header="Act 134, SLH 2013 - UOH Personal Services" t:prog_id_org=UOH800HE t:position_number=60 m:fy_14_salary=0 m:fy_12_salary=12926 m:fy_15_salary=0 m:fy_13_salary=0

series e:i4ce-99gr d:2017-03-15T07:15:18.279Z t:mof=B t:perm_temp_j1a=J1A t:dept_code=UOH t:position_title=CASUAL-PAYROLL t:source_file_header="Act 134, SLH 2013 - UOH Personal Services" t:prog_id_org=UOH800HE t:position_number=61 m:fy_14_salary=0 m:fy_12_salary=21265 m:fy_15_salary=0 m:fy_13_salary=0

series e:i4ce-99gr d:2017-03-15T07:15:18.279Z t:mof=A t:perm_temp_j1a=J1A t:dept_code=HMS t:position_title="RIF SAVINGS" t:source_file_header="Act 134, SLH 2013 -  HMS Personal Services" t:prog_id_org=HMS301SA t:position_number=975 m:fy_14_salary=0 m:fy_12_salary=2759573 m:fy_15_salary=0 m:fy_13_salary=0
```

## Meta Commands

```ls
metric m:fy_12_fte p:float l:"FY 12 FTE" t:dataTypeName=number

metric m:fy_12_salary p:double l:"FY 12 Salary" t:dataTypeName=money

metric m:fy_13_fte p:float l:"FY 13 FTE" t:dataTypeName=number

metric m:fy_13_salary p:double l:"FY 13 Salary" t:dataTypeName=money

metric m:fy_14_fte p:float l:"FY 14 FTE" t:dataTypeName=number

metric m:fy_14_salary p:double l:"FY 14 Salary" t:dataTypeName=money

metric m:fy_15_fte p:float l:"FY 15 FTE" t:dataTypeName=number

metric m:fy_15_salary p:double l:"FY 15 Salary" t:dataTypeName=money

entity e:i4ce-99gr l:"Budget Table - J1 (Salary and FTE)" t:url=https://data.hawaii.gov/api/views/i4ce-99gr

property e:i4ce-99gr t:meta.view v:id=i4ce-99gr v:averageRating=0 v:name="Budget Table - J1 (Salary and FTE)"

property e:i4ce-99gr t:meta.view.owner v:id=trij-xrnq v:profileImageUrlMedium=/api/users/trij-xrnq/profile_images/THUMB v:profileImageUrlLarge=/api/users/trij-xrnq/profile_images/LARGE v:screenName="Meredith Slota" v:profileImageUrlSmall=/api/users/trij-xrnq/profile_images/TINY v:displayName="Meredith Slota"

property e:i4ce-99gr t:meta.view.tableauthor v:id=trij-xrnq v:profileImageUrlMedium=/api/users/trij-xrnq/profile_images/THUMB v:profileImageUrlLarge=/api/users/trij-xrnq/profile_images/LARGE v:screenName="Meredith Slota" v:profileImageUrlSmall=/api/users/trij-xrnq/profile_images/TINY v:displayName="Meredith Slota"
```