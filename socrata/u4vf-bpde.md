# IDOL 2012 Registered Day and Temporary Labor Agencies

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idol-2012-registered-day-and-temporary-labor-agencies-d20a9) |
| Metadata | [Link](https://data.illinois.gov/api/views/u4vf-bpde) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/u4vf-bpde/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/u4vf-bpde/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | u4vf-bpde |
| Name | IDOL 2012 Registered Day and Temporary Labor Agencies |
| Attribution | Illinois Department of Labor |
| Category | Labor |
| Tags | labor, dtlsa, 820 ilcs 175, jobs, work |
| Created | 2014-09-26T18:33:14Z |
| Publication Date | 2014-09-26T18:40:29Z |

## Description

This is the list of current and approved Day and Temporary Labor Agencies, under the Illinois Day and Temporary Labor Services Act, 820 ILCS 175. Last Updated: December 19, 2012

## Columns

```ls
| Included | Schema Type | Field Name | Name    | Data Type | Render Type |
| ======== | =========== | ========== | ======= | ========= | =========== |
| Yes      | series tag  | company    | Company | text      | text        |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:u4vf-bpde d:2012-01-01T00:00:00.000Z t:company="PEOPLELINK STAFFING SOLUTIONS, LLC" m:row_number.u4vf-bpde=1

series e:u4vf-bpde d:2012-01-01T00:00:00.000Z t:company="RANDSTAD US, L.P." m:row_number.u4vf-bpde=2

series e:u4vf-bpde d:2012-01-01T00:00:00.000Z t:company="CROWN SERVICES, INC." m:row_number.u4vf-bpde=3
```

## Meta Commands

```ls
metric m:row_number.u4vf-bpde p:long l:"Row Number"

entity e:u4vf-bpde l:"IDOL 2012 Registered Day and Temporary Labor Agencies" t:attribution="Illinois Department of Labor" t:url=https://data.illinois.gov/api/views/u4vf-bpde

property e:u4vf-bpde t:meta.view v:id=u4vf-bpde v:category=Labor v:attributionLink=http://labor.illinois.gov v:averageRating=0 v:name="IDOL 2012 Registered Day and Temporary Labor Agencies" v:attribution="Illinois Department of Labor"

property e:u4vf-bpde t:meta.view.license v:name="Public Domain"

property e:u4vf-bpde t:meta.view.owner v:id=qz2n-kjc9 v:screenName="IL Department of Labor" v:displayName="IL Department of Labor"

property e:u4vf-bpde t:meta.view.tableauthor v:id=qz2n-kjc9 v:screenName="IL Department of Labor" v:roleName=publisher v:displayName="IL Department of Labor"
```

## Top Records

```ls
| company                             | 
| =================================== | 
| PEOPLELINK STAFFING SOLUTIONS, LLC  | 
| RANDSTAD US, L.P.                   | 
| CROWN SERVICES, INC.                | 
| STAFFMARK INVESTMENT, LLC           | 
| QPS EMPLOYMENT GROUP, INC.          | 
| LUMEA STAFFING OF IL, INC.          | 
| T.S. STAFFING SERVICES              | 
| STAFF ON SITE, INC.                 | 
| USCADEN CORPORATION/MANPOWER        | 
| PARALLEL EMPLOYMENT GRP OF ILLINOIS | 
```