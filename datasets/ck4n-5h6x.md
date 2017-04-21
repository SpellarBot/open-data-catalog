# Complaint Log

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/lpc-complaint-log-9d8e8) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/ck4n-5h6x) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/ck4n-5h6x/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/ck4n-5h6x/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | ck4n-5h6x |
| Name | Complaint Log |
| Attribution | Landmarks Preservation Commission (LPC) |
| Category | City Government |
| Tags | lpc, complaint log |
| Created | 2014-10-26T01:47:21Z |
| Publication Date | 2015-03-17T17:47:12Z |

## Description

Contains information related to violation complaints received by LPC

## Columns

```ls
| Included | Schema Type    | Field Name       | Name              | Data Type | Render Type |
| ======== | ============== | ================ | ================= | ========= | =========== |
| Yes      | numeric metric | log              | Log #             | number    | number      |
| Yes      | series tag     | complaint        | Complaint #       | text      | text        |
| Yes      | time           | date             | Date              | text      | text        |
| No       |                | address          | Address #         | text      | text        |
| Yes      | series tag     | street_name      | Street Name       | text      | text        |
| Yes      | series tag     | borough          | Borough           | text      | text        |
| Yes      | series tag     | district         | District          | text      | text        |
| Yes      | series tag     | work_reported    | Work Reported     | text      | text        |
| Yes      | numeric metric | closed           | Closed            | number    | text        |
| Yes      | numeric metric | issued_violation | Issued Violation? | number    | text        |
```

## Time Field

```ls
Value = date
Format & Zone = MM/dd/yy
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:ck4n-5h6x d:1999-10-03T00:00:00.000Z t:street_name="Bond Street" t:borough=Bn t:district=BOE t:complaint=00-07-02-001 m:issued_violation=0 m:closed=1 m:log=1601

series e:ck4n-5h6x d:1999-10-03T00:00:00.000Z t:work_reported="3rd floor windows" t:street_name="Dean Street" t:borough=Bn t:district=BOE t:complaint=00-07-02-002 m:issued_violation=0 m:closed=1 m:log=1602

series e:ck4n-5h6x d:1999-06-29T00:00:00.000Z t:work_reported="Interior Alts." t:street_name="East 76th Street" t:borough=Mn t:district=UES t:complaint=00-07-02-003 m:issued_violation=0 m:closed=1 m:log=1603
```

## Meta Commands

```ls
metric m:log p:integer l:"Log #" t:dataTypeName=number

metric m:closed p:integer l:Closed t:dataTypeName=number

metric m:issued_violation p:integer l:"Issued Violation?" t:dataTypeName=number

entity e:ck4n-5h6x l:"Complaint Log" t:attribution="Landmarks Preservation Commission (LPC)" t:url=https://data.cityofnewyork.us/api/views/ck4n-5h6x

property e:ck4n-5h6x t:meta.view v:id=ck4n-5h6x v:category="City Government" v:averageRating=0 v:name="Complaint Log" v:attribution="Landmarks Preservation Commission (LPC)"

property e:ck4n-5h6x t:meta.view.license v:name="Public Domain"

property e:ck4n-5h6x t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:ck4n-5h6x t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| log  | complaint    | date    | address | street_name      | borough | district | work_reported                                 | closed | issued_violation | 
| ==== | ============ | ======= | ======= | ================ | ======= | ======== | ============================================= | ====== | ================ | 
| 1601 | 00-07-02-001 | 10/3/99 | 141     | Bond Street      | Bn      | BOE      |                                               | 1      | 0                | 
| 1602 | 00-07-02-002 | 10/3/99 | 201     | Dean Street      | Bn      | BOE      | 3rd floor windows                             | 1      | 0                | 
| 1603 | 00-07-02-003 | 6/29/99 | 110-120 | East 76th Street | Mn      | UES      | Interior Alts.                                | 1      | 0                | 
| 1604 | 00-07-02-004 | 7/1/99  |         | Lorimer Street   | Bn      | GP       | Bell Atlantic Cable Box                       | 1      | 0                | 
| 1605 | 00-07-02-005 | 7/1/99  | 258     | West 12th Street | Mn      | GVE      | Brownstone repair                             | 1      | 0                | 
| 1606 | 00-07-02-006 | 7/1/99  | 117     | East 78th Street | Mn      | UES      | Clovers removed from entry                    | 1      | 0                | 
| 1607 | 00-07-02-007 | 7/2/99  | 170     | Fifth Avenue     | Mn      | LM       | Work                                          | 1      | 0                | 
| 1608 | 00-07-02-008 | 7/2/99  | 123     | Prince Street    | Mn      | SOHO     | Rooftop addt. Visible from 141 Wooster Street | 1      | 0                | 
| 1609 | 00-07-06-009 | 7/6/99  | 116     | East 91st Street | Mn      | CARE     | Interior Alts.                                | 1      | 1                | 
| 1610 | 00-07-06-010 | 7/6/99  | 1313    | Madison Avenue   | Mn      | CARE     | Ramp                                          | 1      | 0                | 
```