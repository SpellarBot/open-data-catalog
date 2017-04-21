# 2013 Special February - Election Results by precinct (complete eCanvass dataset)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/february-2013-ecanvass-d0348) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/96im-qsys) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/96im-qsys/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/96im-qsys/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | 96im-qsys |
| Name | 2013 Special February - Election Results by precinct (complete eCanvass dataset) |
| Attribution | King County Elections |
| Category | Election results |
| Tags | 2013, 2013 special, special, elections, results, precinct, ecanvass |
| Created | 2013-02-28T21:34:25Z |
| Publication Date | 2013-02-28T21:35:27Z |

## Description

February 2013 special election; final/official results by precinct.

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
Value = 2013
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = cc,cg
```

## Data Commands

```ls
series e:96im-qsys d:2013-01-01T00:00:00.000Z t:precinct=GLENDALE t:countertype=No t:countergroup=Total t:party=NP t:race="Seattle School District No. 1 Proposition No. 1 Operations Levy" m:leg=33 m:sumofcount=1

series e:96im-qsys d:2013-01-01T00:00:00.000Z t:precinct=GLENDALE t:countertype="Registered Voters" t:countergroup=Total t:party=NP t:race="Seattle School District No. 1 Proposition No. 1 Operations Levy" m:leg=33 m:sumofcount=0

series e:96im-qsys d:2013-01-01T00:00:00.000Z t:precinct=GLENDALE t:countertype="Times Blank Voted" t:countergroup=Total t:party=NP t:race="Seattle School District No. 1 Proposition No. 1 Operations Levy" m:leg=33 m:sumofcount=1
```

## Meta Commands

```ls
metric m:leg p:integer l:LEG t:dataTypeName=number

metric m:sumofcount p:integer l:SumOfCount t:dataTypeName=number

entity e:96im-qsys l:"2013 Special February - Election Results by precinct (complete eCanvass dataset)" t:attribution="King County Elections" t:url=https://data.kingcounty.gov/api/views/96im-qsys

property e:96im-qsys t:meta.view v:id=96im-qsys v:category="Election results" v:attributionLink=http://kingcounty.gov/elections/results v:averageRating=0 v:name="2013 Special February - Election Results by precinct (complete eCanvass dataset)" v:attribution="King County Elections"

property e:96im-qsys t:meta.view.license v:name="Public Domain"

property e:96im-qsys t:meta.view.owner v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:displayName="Kathy Gill"

property e:96im-qsys t:meta.view.tableauthor v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:roleName=publisher v:displayName="Kathy Gill"
```

## Top Records

```ls
| precinct | race                                                            | leg | cc | cg | countergroup | party | countertype       | sumofcount | 
| ======== | =============================================================== | === | == | == | ============ | ===== | ================= | ========== | 
| GLENDALE | Seattle School District No. 1 Proposition No. 1 Operations Levy | 33  | 8  | 9  | Total        | NP    | No                | 1          | 
| GLENDALE | Seattle School District No. 1 Proposition No. 1 Operations Levy | 33  | 8  | 9  | Total        | NP    | Registered Voters | 0          | 
| GLENDALE | Seattle School District No. 1 Proposition No. 1 Operations Levy | 33  | 8  | 9  | Total        | NP    | Times Blank Voted | 1          | 
| GLENDALE | Seattle School District No. 1 Proposition No. 1 Operations Levy | 33  | 8  | 9  | Total        | NP    | Times Counted     | 5          | 
| GLENDALE | Seattle School District No. 1 Proposition No. 1 Operations Levy | 33  | 8  | 9  | Total        | NP    | Times Over Voted  | 0          | 
| GLENDALE | Seattle School District No. 1 Proposition No. 1 Operations Levy | 33  | 8  | 9  | Total        | NP    | Yes               | 3          | 
| GLENDALE | Seattle School District No. 1 Proposition No. 2 Capital Levy    | 33  | 8  | 9  | Total        | NP    | No                | 0          | 
| GLENDALE | Seattle School District No. 1 Proposition No. 2 Capital Levy    | 33  | 8  | 9  | Total        | NP    | Registered Voters | 0          | 
| GLENDALE | Seattle School District No. 1 Proposition No. 2 Capital Levy    | 33  | 8  | 9  | Total        | NP    | Times Blank Voted | 1          | 
| GLENDALE | Seattle School District No. 1 Proposition No. 2 Capital Levy    | 33  | 8  | 9  | Total        | NP    | Times Counted     | 5          | 
```