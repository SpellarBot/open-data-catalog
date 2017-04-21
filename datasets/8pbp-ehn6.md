# 20130423 ERP STAFF AND INTERESTED PARTIES

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/20130423-erp-staff-and-interested-parties-80750) |
| Metadata | [Link](https://data.hawaii.gov/api/views/8pbp-ehn6) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/8pbp-ehn6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/8pbp-ehn6/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | 8pbp-ehn6 |
| Name | 20130423 ERP STAFF AND INTERESTED PARTIES |
| Category | Other |
| Created | 2013-04-24T19:06:09Z |
| Publication Date | 2013-04-26T21:04:11Z |

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                  | Data Type | Render Type |
| ======== | ============== | ====================== | ===================== | ========= | =========== |
| No       | time           | :updated_at            | updated_at            | meta_data | meta_data   |
| Yes      | numeric metric | method_of_recfruitment | METHOD OF RECRUITMENT | number    | number      |
| Yes      | series tag     | method_of_recruitment  | Method of Recruitment | text      | text        |
| Yes      | numeric metric | dept                   | DEPT                  | number    | number      |
| Yes      | series tag     | department             | Department            | text      | text        |
| Yes      | series tag     | employee               | EMPLOYEE              | text      | text        |
| Yes      | series tag     | status                 | status                | text      | number      |
| Yes      | series tag     | work_status            | Work Status           | text      | text        |
| Yes      | numeric metric | fte_for_erp            | % FTE for ERP         | number    | number      |
| Yes      | series tag     | fte_for_erp_2          | FTE for ERP           | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:8pbp-ehn6 d:2013-04-25T19:23:39.000Z t:work_status=STARTED t:status=2 t:department=DOT t:method_of_recruitment="PAOLA INQUIRED" t:employee="ARTHUR MINAGAWA" m:dept=6 m:method_of_recfruitment=1 m:fte_for_erp=1

series e:8pbp-ehn6 d:2013-04-25T19:23:53.000Z t:work_status=STARTED t:status=2 t:department=DOH t:method_of_recruitment="EMPLOYEE VOLUNTEERED" t:employee="CHAD SAKAGAWA" m:dept=7 m:method_of_recfruitment=3 m:fte_for_erp=0.15

series e:8pbp-ehn6 d:2013-04-25T19:23:53.000Z t:work_status=PROJECTED t:status=3 t:department=DOE t:method_of_recruitment="SUPERVISOR OFFERED" t:employee="ERIC NOUCHI" m:dept=5 m:method_of_recfruitment=2 m:fte_for_erp=1
```

## Meta Commands

```ls
metric m:method_of_recfruitment p:integer l:"METHOD OF RECRUITMENT" t:dataTypeName=number

metric m:dept p:integer l:DEPT t:dataTypeName=number

metric m:fte_for_erp p:double l:"% FTE for ERP" t:dataTypeName=number

entity e:8pbp-ehn6 l:"20130423 ERP STAFF AND INTERESTED PARTIES" t:url=https://data.hawaii.gov/api/views/8pbp-ehn6

property e:8pbp-ehn6 t:meta.view v:id=8pbp-ehn6 v:category=Other v:averageRating=0 v:name="20130423 ERP STAFF AND INTERESTED PARTIES"

property e:8pbp-ehn6 t:meta.view.owner v:id=w54k-atk9 v:screenName=Chad v:displayName=Chad

property e:8pbp-ehn6 t:meta.view.tableauthor v:id=w54k-atk9 v:screenName=Chad v:roleName=editor v:displayName=Chad
```

## Top Records

```ls
| :updated_at | method_of_recfruitment | method_of_recruitment | dept | department | employee        | status | work_status | fte_for_erp | fte_for_erp_2 | 
| =========== | ====================== | ===================== | ==== | ========== | =============== | ====== | =========== | =========== | ============= | 
| 1366917819  | 1                      | PAOLA INQUIRED        | 6    | DOT        | ARTHUR MINAGAWA | 2      | STARTED     | 1           |               | 
| 1366917833  | 3                      | EMPLOYEE VOLUNTEERED  | 7    | DOH        | CHAD SAKAGAWA   | 2      | STARTED     | 0.15        |               | 
| 1366917833  | 2                      | SUPERVISOR OFFERED    | 5    | DOE        | ERIC NOUCHI     | 3      | PROJECTED   | 1           |               | 
| 1366917847  | 3                      | EMPLOYEE VOLUNTEERED  | 9    | ICSD       | PING BLAS       | 1      | PENDING     | 0.15        |               | 
| 1366917848  | 3                      | EMPLOYEE VOLUNTEERED  | 9    | ICSD       | ROGER THOREN    | 2      | STARTED     | 0.25        |               | 
| 1366918098  | 1                      | PAOLA INQUIRED        | 10   | PUC        | DAVID TAKASHIMA | 2      | STARTED     | 0.15        |               | 
| 1366918156  | 1                      | PAOLA INQUIRED        | 4    | DLIR       | RENEE NAGAHISA  | 1      | PENDING     | 0           |               | 
| 1366918166  | 1                      | PAOLA INQUIRED        | 8    | HSPLS      | LYNN NAKAMURA   | 2      | STARTED     | 1           |               | 
| 1366918173  | 1                      | PAOLA INQUIRED        | 1    | AG         | CLAY SATO       | 1      | PENDING     | 0           |               | 
| 1366918199  | 1                      | PAOLA INQUIRED        | 9    | ICSD       | CHAD TAIRA      | 2      | STARTED     | 0.15        |               | 
```