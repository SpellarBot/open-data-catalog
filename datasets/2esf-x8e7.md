# Salary: OUS: Western Oregon University: Fiscal Year 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/salary-ous-western-oregon-university-fiscal-year-2012-56f54) |
| Metadata | [Link](https://data.oregon.gov/api/views/2esf-x8e7) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/2esf-x8e7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/2esf-x8e7/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | 2esf-x8e7 |
| Name | Salary: OUS: Western Oregon University: Fiscal Year 2012 |
| Category | Revenue & Expense |
| Created | 2012-12-15T01:09:04Z |
| Publication Date | 2012-12-15T01:09:53Z |

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
series e:2esf-x8e7 d:2012-01-01T00:00:00.000Z t:service_type="Executive/Admin and Managerial" t:classification="Uncl Non-Teach 12mo .5+ FTE" t:agency_title="OUS - Western Oregon University" t:agency=58020 t:full_part_time=Full-Time m:annual_salary=185460

series e:2esf-x8e7 d:2012-01-01T00:00:00.000Z t:service_type="Executive/Admin and Managerial" t:classification="Uncl Non-Teach 12mo .5+ FTE" t:agency_title="OUS - Western Oregon University" t:agency=58020 t:full_part_time=Full-Time m:annual_salary=162744

series e:2esf-x8e7 d:2012-01-01T00:00:00.000Z t:service_type="Executive/Admin and Managerial" t:classification="Uncl Non-Teach 12mo .5+ FTE" t:agency_title="OUS - Western Oregon University" t:agency=58020 t:full_part_time=Full-Time m:annual_salary=118464
```

## Meta Commands

```ls
metric m:annual_salary p:integer l:"ANNUAL SALARY" t:dataTypeName=money

entity e:2esf-x8e7 l:"Salary: OUS: Western Oregon University: Fiscal Year 2012" t:url=https://data.oregon.gov/api/views/2esf-x8e7

property e:2esf-x8e7 t:meta.view v:id=2esf-x8e7 v:category="Revenue & Expense" v:averageRating=0 v:name="Salary: OUS: Western Oregon University: Fiscal Year 2012"

property e:2esf-x8e7 t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:2esf-x8e7 t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| agency | agency_title                    | classification                | service_type                   | full_part_time | annual_salary | 
| ====== | =============================== | ============================= | ============================== | ============== | ============= | 
| 58020  | OUS - Western Oregon University | Uncl Non-Teach 12mo .5+ FTE   | Executive/Admin and Managerial | Full-Time      | 185460        | 
| 58020  | OUS - Western Oregon University | Uncl Non-Teach 12mo .5+ FTE   | Executive/Admin and Managerial | Full-Time      | 162744        | 
| 58020  | OUS - Western Oregon University | Uncl Non-Teach 12mo .5+ FTE   | Executive/Admin and Managerial | Full-Time      | 118464        | 
| 58020  | OUS - Western Oregon University | Uncl Non-Teach 12mo .5+ FTE   | Executive/Admin and Managerial | Full-Time      | 118464        | 
| 58020  | OUS - Western Oregon University | Uncl Non-Teach 12mo .5+ FTE   | Executive/Admin and Managerial | Full-Time      | 113868        | 
| 58020  | OUS - Western Oregon University | Uncl Non-Teach 12mo .5+ FTE   | Executive/Admin and Managerial | Full-Time      | 113304        | 
| 58020  | OUS - Western Oregon University | Uncl Non-Teach 12mo .5+ FTE   | Other Professionals            | Full-Time      | 110007        | 
| 58020  | OUS - Western Oregon University | Uncl Non-Teach 12mo .5+ FTE   | Executive/Admin and Managerial | Full-Time      | 107208        | 
| 58020  | OUS - Western Oregon University | Fixed Term Fac/ Uncl 12mo .5+ | Faculty                        | Full-Time      | 106080        | 
| 58020  | OUS - Western Oregon University | Fixed Term Fac/ Uncl 12mo .5+ | Faculty                        | Full-Time      | 105576        | 
```