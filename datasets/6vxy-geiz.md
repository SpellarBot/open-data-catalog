# 2012 Special February - Election Results by precinct (complete eCanvass dataset)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cumulative-canvass-2012-february-14-special-election-e639a) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/6vxy-geiz) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/6vxy-geiz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/6vxy-geiz/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | 6vxy-geiz |
| Name | 2012 Special February - Election Results by precinct (complete eCanvass dataset) |
| Attribution | King County Elections |
| Category | Election results |
| Tags | 2012, 2012 special, special, elections, results, precinct, ecanvass |
| Created | 2012-03-02T20:26:23Z |
| Publication Date | 2012-03-02T20:30:24Z |

## Description

February 2012 special election; final/official results by precinct.

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type | Render Type |
| ======== | ============== | ============ | ============ | ========= | =========== |
| Yes      | series tag     | precinct     | Precinct     | text      | text        |
| Yes      | series tag     | race         | Race         | text      | text        |
| Yes      | numeric metric | leg          | LEG          | number    | number      |
| No       |                | cc           | CC           | number    | number      |
| No       |                | cg           | CG           | number    | number      |
| Yes      | series tag     | countergroup | CounterGroup | text      | text        |
| Yes      | series tag     | party        | Party        | text      | text        |
| Yes      | series tag     | countertype  | CounterType  | text      | text        |
| Yes      | numeric metric | sumofcount   | SumOfCount   | number    | number      |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = cc,cg
```

## Data Commands

```ls
series e:6vxy-geiz d:2012-01-01T00:00:00.000Z t:precinct=ALDARRA t:countertype=APPROVED t:countergroup=Total t:party=NP t:race="King County Fire Protection District No. 10 Proposition No. 1" m:leg=5 m:sumofcount=36

series e:6vxy-geiz d:2012-01-01T00:00:00.000Z t:precinct=ALDARRA t:countertype="Registered Voters" t:countergroup=Total t:party=NP t:race="King County Fire Protection District No. 10 Proposition No. 1" m:leg=5 m:sumofcount=125

series e:6vxy-geiz d:2012-01-01T00:00:00.000Z t:precinct=ALDARRA t:countertype=REJECTED t:countergroup=Total t:party=NP t:race="King County Fire Protection District No. 10 Proposition No. 1" m:leg=5 m:sumofcount=32
```

## Meta Commands

```ls
metric m:leg p:integer l:LEG t:dataTypeName=number

metric m:sumofcount p:float l:SumOfCount t:dataTypeName=number

entity e:6vxy-geiz l:"2012 Special February - Election Results by precinct (complete eCanvass dataset)" t:attribution="King County Elections" t:url=https://data.kingcounty.gov/api/views/6vxy-geiz

property e:6vxy-geiz t:meta.view v:id=6vxy-geiz v:category="Election results" v:attributionLink=http://your.kingcounty.gov/elections/2012feb-special/results.aspx v:averageRating=0 v:name="2012 Special February - Election Results by precinct (complete eCanvass dataset)" v:attribution="King County Elections"

property e:6vxy-geiz t:meta.view.license v:name="Public Domain"

property e:6vxy-geiz t:meta.view.owner v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:displayName="Kathy Gill"

property e:6vxy-geiz t:meta.view.tableauthor v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:roleName=publisher v:displayName="Kathy Gill"
```

## Top Records

```ls
| precinct    | race                                                          | leg | cc | cg | countergroup | party | countertype       | sumofcount | 
| =========== | ============================================================= | === | == | == | ============ | ===== | ================= | ========== | 
| ALDARRA     | King County Fire Protection District No. 10 Proposition No. 1 | 5   | 3  | 8  | Total        | NP    | APPROVED          | 36.00      | 
| ALDARRA     | King County Fire Protection District No. 10 Proposition No. 1 | 5   | 3  | 8  | Total        | NP    | Registered Voters | 125.00     | 
| ALDARRA     | King County Fire Protection District No. 10 Proposition No. 1 | 5   | 3  | 8  | Total        | NP    | REJECTED          | 32.00      | 
| ALDARRA     | King County Fire Protection District No. 10 Proposition No. 1 | 5   | 3  | 8  | Total        | NP    | Times Blank Voted | 0.00       | 
| ALDARRA     | King County Fire Protection District No. 10 Proposition No. 1 | 5   | 3  | 8  | Total        | NP    | Times Counted     | 68.00      | 
| ALDARRA     | King County Fire Protection District No. 10 Proposition No. 1 | 5   | 3  | 8  | Total        | NP    | Times Over Voted  | 0.00       | 
| ALG 30-0013 | Auburn School District No. 408 Proposition No. 1              | 30  | 7  | 9  | Total        | NP    | NO                | 52.00      | 
| ALG 30-0013 | Auburn School District No. 408 Proposition No. 1              | 30  | 7  | 9  | Total        | NP    | Registered Voters | 428.00     | 
| ALG 30-0013 | Auburn School District No. 408 Proposition No. 1              | 30  | 7  | 9  | Total        | NP    | Times Blank Voted | 1.00       | 
| ALG 30-0013 | Auburn School District No. 408 Proposition No. 1              | 30  | 7  | 9  | Total        | NP    | Times Counted     | 105.00     | 
```