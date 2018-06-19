# Salary: OUS: Portland State University: Fiscal Year 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/salary-ous-portland-state-university-fiscal-year-2012-7ab2b) |
| Metadata | [Link](https://data.oregon.gov/api/views/c2ic-f5ec) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/c2ic-f5ec/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/c2ic-f5ec/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | c2ic-f5ec |
| Name | Salary: OUS: Portland State University: Fiscal Year 2012 |
| Category | Revenue & Expense |
| Created | 2012-12-15T01:10:50Z |
| Publication Date | 2012-12-15T01:11:34Z |

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
series e:c2ic-f5ec d:2012-01-01T00:00:00.000Z t:service_type="Executive/Admin and managerial" t:classification="POF UU President" t:agency_title="OUS - Portland State University" t:agency=58090 t:full_part_time=Full-Time m:annual_salary=354694

series e:c2ic-f5ec d:2012-01-01T00:00:00.000Z t:service_type="Executive/Admin and managerial" t:classification="RSP UX Vice President" t:agency_title="OUS - Portland State University" t:agency=58090 t:full_part_time=Full-Time m:annual_salary=265440

series e:c2ic-f5ec d:2012-01-01T00:00:00.000Z t:service_type="Executive/Admin and managerial" t:classification="FAD UU Vice President FADM" t:agency_title="OUS - Portland State University" t:agency=58090 t:full_part_time=Full-Time m:annual_salary=255444
```

## Meta Commands

```ls
metric m:annual_salary p:integer l:"ANNUAL SALARY" t:dataTypeName=money

entity e:c2ic-f5ec l:"Salary: OUS: Portland State University: Fiscal Year 2012" t:url=https://data.oregon.gov/api/views/c2ic-f5ec

property e:c2ic-f5ec t:meta.view v:id=c2ic-f5ec v:category="Revenue & Expense" v:averageRating=0 v:name="Salary: OUS: Portland State University: Fiscal Year 2012"

property e:c2ic-f5ec t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:c2ic-f5ec t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| agency | agency_title                    | classification                 | service_type                   | full_part_time | annual_salary | 
| ====== | =============================== | ============================== | ============================== | ============== | ============= | 
| 58090  | OUS - Portland State University | POF UU President               | Executive/Admin and managerial | Full-Time      | 354694        | 
| 58090  | OUS - Portland State University | RSP UX Vice President          | Executive/Admin and managerial | Full-Time      | 265440        | 
| 58090  | OUS - Portland State University | FAD UU Vice President FADM     | Executive/Admin and managerial | Full-Time      | 255444        | 
| 58090  | OUS - Portland State University | REL UU VP For Univ Relations   | Executive/Admin and managerial | Full-Time      | 235440        | 
| 58090  | OUS - Portland State University | EAS UX Dean, Engr & Appld Sci  | Executive/Admin and managerial | Full-Time      | 225636        | 
| 58090  | OUS - Portland State University | SBA UX Dean, Sch Of Bus Admin  | Executive/Admin and managerial | Full-Time      | 210504        | 
| 58090  | OUS - Portland State University | ECE UP Professor               | Faculty                        | Full-Time      | 200520        | 
| 58090  | OUS - Portland State University | SSW UX Dean,Sch Of Social Wor  | Executive/Admin and managerial | Full-Time      | 200004        | 
| 58090  | OUS - Portland State University | OAA UX ViceProvostFiscalStr&Pl | Executive/Admin and managerial | Full-Time      | 197172        | 
| 58090  | OUS - Portland State University | LAS UX Dean,Liberal Arts & Sc  | Executive/Admin and managerial | Full-Time      | 190440        | 
```