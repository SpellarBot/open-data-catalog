# 2016 Special February - Election Night Results Abstract by Precinct

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2016-special-february-election-night-results-abstract-by-precinct) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/u23d-y8xs) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/u23d-y8xs/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/u23d-y8xs/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | u23d-y8xs |
| Name | 2016 Special February - Election Night Results Abstract by Precinct |
| Attribution | King County Election |
| Category | Election results |
| Tags | 2016, 2016 special, special, elections, results |
| Created | 2017-01-25T00:40:36Z |
| Publication Date | 2017-01-25T00:41:42Z |

## Description

February 2016 special election; election night results report by precinct.

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
Value = 2016
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = cc,cg
```

## Data Commands

```ls
series e:u23d-y8xs d:2016-01-01T00:00:00.000Z t:precinct="ALG 30-0013" t:countertype=No t:countergroup=Total t:party=NP t:race="Auburn School District No. 408 Proposition No. 1" m:leg=30 m:sumofcount=31

series e:u23d-y8xs d:2016-01-01T00:00:00.000Z t:precinct="ALG 30-0013" t:countertype="Registered Voters" t:countergroup=Total t:party=NP t:race="Auburn School District No. 408 Proposition No. 1" m:leg=30 m:sumofcount=460

series e:u23d-y8xs d:2016-01-01T00:00:00.000Z t:precinct="ALG 30-0013" t:countertype="Times Blank Voted" t:countergroup=Total t:party=NP t:race="Auburn School District No. 408 Proposition No. 1" m:leg=30 m:sumofcount=0
```

## Meta Commands

```ls
metric m:leg p:integer l:LEG t:dataTypeName=number

metric m:sumofcount p:integer l:SumOfCount t:dataTypeName=number

entity e:u23d-y8xs l:"2016 Special February - Election Night Results Abstract by Precinct" t:attribution="King County Election" t:url=https://data.kingcounty.gov/api/views/u23d-y8xs

property e:u23d-y8xs t:meta.view v:id=u23d-y8xs v:category="Election results" v:attributionLink=http://kingcounty.gov/elections/results v:averageRating=0 v:name="2016 Special February - Election Night Results Abstract by Precinct" v:attribution="King County Election"

property e:u23d-y8xs t:meta.view.license v:name="Public Domain"

property e:u23d-y8xs t:meta.view.owner v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:displayName="Kathy Gill"

property e:u23d-y8xs t:meta.view.tableauthor v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:roleName=publisher v:displayName="Kathy Gill"
```

## Top Records

```ls
| precinct    | race                                             | leg | cc | cg | countergroup | party | countertype       | sumofcount | 
| =========== | ================================================ | === | == | == | ============ | ===== | ================= | ========== | 
| ALG 30-0013 | Auburn School District No. 408 Proposition No. 1 | 30  | 7  | 8  | Total        | NP    | No                | 31         | 
| ALG 30-0013 | Auburn School District No. 408 Proposition No. 1 | 30  | 7  | 8  | Total        | NP    | Registered Voters | 460        | 
| ALG 30-0013 | Auburn School District No. 408 Proposition No. 1 | 30  | 7  | 8  | Total        | NP    | Times Blank Voted | 0          | 
| ALG 30-0013 | Auburn School District No. 408 Proposition No. 1 | 30  | 7  | 8  | Total        | NP    | Times Counted     | 68         | 
| ALG 30-0013 | Auburn School District No. 408 Proposition No. 1 | 30  | 7  | 8  | Total        | NP    | Times Over Voted  | 0          | 
| ALG 30-0013 | Auburn School District No. 408 Proposition No. 1 | 30  | 7  | 8  | Total        | NP    | Yes               | 37         | 
| ALG 30-0014 | Auburn School District No. 408 Proposition No. 1 | 30  | 7  | 8  | Total        | NP    | No                | 46         | 
| ALG 30-0014 | Auburn School District No. 408 Proposition No. 1 | 30  | 7  | 8  | Total        | NP    | Registered Voters | 491        | 
| ALG 30-0014 | Auburn School District No. 408 Proposition No. 1 | 30  | 7  | 8  | Total        | NP    | Times Blank Voted | 0          | 
| ALG 30-0014 | Auburn School District No. 408 Proposition No. 1 | 30  | 7  | 8  | Total        | NP    | Times Counted     | 86         | 
```