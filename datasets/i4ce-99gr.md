# Budget Table - J1 (Salary and FTE)

## Dataset

* [Dataset URL](https://data.hawaii.gov/api/views/i4ce-99gr/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/budget-table-j1-salary-and-fte-f28d8)
* [Metadata URL](https://data.hawaii.gov/api/views/i4ce-99gr)
* Id = i4ce-99gr
* Name = Budget Table - J1 (Salary and FTE)
* Created = 2014-01-28T20:54:32Z
* Publication Date = 2014-01-28T21:07:40Z
* Rows Updated = 2014-01-28T20:59:53Z

## Description



## Columns

```ls
| Name                | Field Name         | Data Type     | Render Type   | Schema Type    | Included | 
| =================== | ================== | ============= | ============= | ============== | ======== | 
| Source File Header  | source_file_header | text          | text          | series tag     | Yes      | 
| Dept Code           | dept_code          | text          | text          | series tag     | Yes      | 
| Prog ID/Org         | prog_id_org        | text          | text          | series tag     | Yes      | 
| Position Number     | position_number    | text          | text          | series tag     | Yes      | 
| Perm/Temp/J1A       | perm_temp_j1a      | text          | text          | series tag     | Yes      | 
| MOF                 | mof                | number        | text          | numeric metric | Yes      | 
| Position Title      | position_title     | text          | text          | series tag     | Yes      | 
| FY 12 FTE           | fy_12_fte          | number        | number        | numeric metric | Yes      | 
| FY 12 Salary        | fy_12_salary       | money         | money         | numeric metric | Yes      | 
| FY 13 FTE           | fy_13_fte          | number        | number        | numeric metric | Yes      | 
| FY 13 Salary        | fy_13_salary       | money         | money         | numeric metric | Yes      | 
| FY 14 FTE           | fy_14_fte          | number        | number        | numeric metric | Yes      | 
| FY 14 Salary        | fy_14_salary       | money         | money         | numeric metric | Yes      | 
| FY 15 FTE           | fy_15_fte          | number        | number        | numeric metric | Yes      | 
| FY 15 Salary        | fy_15_salary       | money         | money         | numeric metric | Yes      | 
| Incumbent Name      | incumbent_name     | text          | text          | series tag     | Yes      | 
| BU Code             | bu_code            | text          | number        | series tag     | Yes      | 
| SR Level            | sr_level           | text          | text          | series tag     | Yes      | 
| SOH Org Code        | soh_org_code       | text          | number        | series tag     | Yes      | 
| Next Step Mvt Date  | next_step_mvt_date | calendar_date | calendar_date | time           | Yes      | 
| Job Code            | job_code           | text          | number        | series tag     | Yes      | 
| Apprn Account (UAC) | apprn_account_uac  | text          | text          | series tag     | Yes      | 
```

## Time Field

```ls
Value = next_step_mvt_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
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
series e:i4ce-99gr d:2017-03-07T18:11:20.260Z t:mof=A t:perm_temp_j1a=J1A t:dept_code=UOH t:position_title=CASUAL-PAYROLL t:source_file_header="Act 134, SLH 2013 - UOH Personal Services" t:prog_id_org=UOH800HE t:position_number=60 m:fy_14_salary=0 m:fy_12_salary=12926 m:fy_15_salary=0 m:fy_13_salary=0

series e:i4ce-99gr d:2017-03-07T18:11:20.260Z t:mof=B t:perm_temp_j1a=J1A t:dept_code=UOH t:position_title=CASUAL-PAYROLL t:source_file_header="Act 134, SLH 2013 - UOH Personal Services" t:prog_id_org=UOH800HE t:position_number=61 m:fy_14_salary=0 m:fy_12_salary=21265 m:fy_15_salary=0 m:fy_13_salary=0

series e:i4ce-99gr d:2017-03-07T18:11:20.260Z t:mof=A t:perm_temp_j1a=J1A t:dept_code=HMS t:position_title="RIF SAVINGS" t:source_file_header="Act 134, SLH 2013 -  HMS Personal Services" t:prog_id_org=HMS301SA t:position_number=975 m:fy_14_salary=0 m:fy_12_salary=2759573 m:fy_15_salary=0 m:fy_13_salary=0
```

## Meta Commands

```ls
metric m:fy_12_fte l:"FY 12 FTE" t:dataTypeName=number

metric m:fy_13_fte l:"FY 13 FTE" t:dataTypeName=number

metric m:fy_14_fte l:"FY 14 FTE" t:dataTypeName=number

metric m:fy_15_fte l:"FY 15 FTE" t:dataTypeName=number

entity e:i4ce-99gr l:"Budget Table - J1 (Salary and FTE)" t:url=https://data.hawaii.gov/api/views/i4ce-99gr

property e:i4ce-99gr t:meta.view d:2017-03-07T18:11:20.260Z v:id=i4ce-99gr v:averageRating=0 v:name="Budget Table - J1 (Salary and FTE)"

property e:i4ce-99gr t:meta.view.owner d:2017-03-07T18:11:20.260Z v:id=trij-xrnq v:profileImageUrlMedium=/api/users/trij-xrnq/profile_images/THUMB v:profileImageUrlLarge=/api/users/trij-xrnq/profile_images/LARGE v:screenName="Meredith Slota" v:profileImageUrlSmall=/api/users/trij-xrnq/profile_images/TINY v:displayName="Meredith Slota"

property e:i4ce-99gr t:meta.view.tableauthor d:2017-03-07T18:11:20.260Z v:id=trij-xrnq v:profileImageUrlMedium=/api/users/trij-xrnq/profile_images/THUMB v:profileImageUrlLarge=/api/users/trij-xrnq/profile_images/LARGE v:screenName="Meredith Slota" v:profileImageUrlSmall=/api/users/trij-xrnq/profile_images/TINY v:displayName="Meredith Slota"
```