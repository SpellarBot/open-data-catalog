# 2012 Special April - Election Results by precinct (complete eCanvass dataset)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/final-ecanvass-april-2012-special-election-results-king-co-elections-01413) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/kt8p-gznb) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/kt8p-gznb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/kt8p-gznb/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | kt8p-gznb |
| Name | 2012 Special April - Election Results by precinct (complete eCanvass dataset) |
| Attribution | King County Elections |
| Category | Election results |
| Tags | 2012, 2012 special, special, elections, results, precinct, ecanvass |
| Created | 2012-05-01T21:37:32Z |
| Publication Date | 2012-05-01T21:42:28Z |

## Description

April 2012 special election; final/official results by precinct.

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
series e:kt8p-gznb d:2012-01-01T00:00:00.000Z t:precinct="ANGEL CITY" t:countertype=APPROVED t:countergroup=Total t:party=NP t:race="Renton School District No. 403 Proposition No. 1" m:leg=37 m:sumofcount=94

series e:kt8p-gznb d:2012-01-01T00:00:00.000Z t:precinct="ANGEL CITY" t:countertype="Registered Voters" t:countergroup=Total t:party=NP t:race="Renton School District No. 403 Proposition No. 1" m:leg=37 m:sumofcount=672

series e:kt8p-gznb d:2012-01-01T00:00:00.000Z t:precinct="ANGEL CITY" t:countertype=REJECTED t:countergroup=Total t:party=NP t:race="Renton School District No. 403 Proposition No. 1" m:leg=37 m:sumofcount=84
```

## Meta Commands

```ls
metric m:leg p:integer l:LEG t:dataTypeName=number

metric m:sumofcount p:integer l:SumOfCount t:dataTypeName=number

entity e:kt8p-gznb l:"2012 Special April - Election Results by precinct (complete eCanvass dataset)" t:attribution="King County Elections" t:url=https://data.kingcounty.gov/api/views/kt8p-gznb

property e:kt8p-gznb t:meta.view v:id=kt8p-gznb v:category="Election results" v:attributionLink=http://kingcounty.gov/elections/results v:averageRating=0 v:name="2012 Special April - Election Results by precinct (complete eCanvass dataset)" v:attribution="King County Elections"

property e:kt8p-gznb t:meta.view.license v:name="Public Domain"

property e:kt8p-gznb t:meta.view.owner v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:displayName="Kathy Gill"

property e:kt8p-gznb t:meta.view.tableauthor v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"
```

## Top Records

```ls
| precinct   | race                                             | leg | cc | cg | countergroup | party | countertype       | sumofcount | 
| ========== | ================================================ | === | == | == | ============ | ===== | ================= | ========== | 
| ANGEL CITY | Renton School District No. 403 Proposition No. 1 | 37  | 2  | 7  | Total        | NP    | APPROVED          | 94         | 
| ANGEL CITY | Renton School District No. 403 Proposition No. 1 | 37  | 2  | 7  | Total        | NP    | Registered Voters | 672        | 
| ANGEL CITY | Renton School District No. 403 Proposition No. 1 | 37  | 2  | 7  | Total        | NP    | REJECTED          | 84         | 
| ANGEL CITY | Renton School District No. 403 Proposition No. 1 | 37  | 2  | 7  | Total        | NP    | Times Blank Voted | 0          | 
| ANGEL CITY | Renton School District No. 403 Proposition No. 1 | 37  | 2  | 7  | Total        | NP    | Times Counted     | 178        | 
| ANGEL CITY | Renton School District No. 403 Proposition No. 1 | 37  | 2  | 7  | Total        | NP    | Times Over Voted  | 0          | 
| ANGELO     | South King Fire & Rescue Proposition No. 1       | 30  | 7  | 9  | Total        | NP    | NO                | 64         | 
| ANGELO     | South King Fire & Rescue Proposition No. 1       | 30  | 7  | 9  | Total        | NP    | Registered Voters | 423        | 
| ANGELO     | South King Fire & Rescue Proposition No. 1       | 30  | 7  | 9  | Total        | NP    | Times Blank Voted | 0          | 
| ANGELO     | South King Fire & Rescue Proposition No. 1       | 30  | 7  | 9  | Total        | NP    | Times Counted     | 142        | 
```