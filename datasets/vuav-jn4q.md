# 2015 Special February - Election Results by precinct (complete eCanvass dataset)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2015-special-february-election-results-by-precinct-complete-ecanvass-dataset) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/vuav-jn4q) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/vuav-jn4q/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/vuav-jn4q/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | vuav-jn4q |
| Name | 2015 Special February - Election Results by precinct (complete eCanvass dataset) |
| Attribution | King County Elections |
| Category | Election results |
| Tags | 2015, 2015 special, special, elections, results, precinct, ecanvass |
| Created | 2017-01-25T01:31:52Z |
| Publication Date | 2017-01-25T01:33:44Z |

## Description

February 2015 special election; final/official results by precinct.

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
Value = 2015
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = cc,cg
```

## Data Commands

```ls
series e:vuav-jn4q d:2015-01-01T00:00:00.000Z t:precinct=ALDARRA t:countertype=Approved t:countergroup=Total t:party=NP t:race="Snoqualmie Valley School District No. 410 Proposition No. 1" m:leg=5 m:sumofcount=127

series e:vuav-jn4q d:2015-01-01T00:00:00.000Z t:precinct=ALDARRA t:countertype="Registered Voters" t:countergroup=Total t:party=NP t:race="Snoqualmie Valley School District No. 410 Proposition No. 1" m:leg=5 m:sumofcount=714

series e:vuav-jn4q d:2015-01-01T00:00:00.000Z t:precinct=ALDARRA t:countertype=Rejected t:countergroup=Total t:party=NP t:race="Snoqualmie Valley School District No. 410 Proposition No. 1" m:leg=5 m:sumofcount=136
```

## Meta Commands

```ls
metric m:leg p:integer l:LEG t:dataTypeName=number

metric m:sumofcount p:integer l:SumOfCount t:dataTypeName=number

entity e:vuav-jn4q l:"2015 Special February - Election Results by precinct (complete eCanvass dataset)" t:attribution="King County Elections" t:url=https://data.kingcounty.gov/api/views/vuav-jn4q

property e:vuav-jn4q t:meta.view v:id=vuav-jn4q v:category="Election results" v:attributionLink=http://kingcounty.gov/elections/results v:averageRating=0 v:name="2015 Special February - Election Results by precinct (complete eCanvass dataset)" v:attribution="King County Elections"

property e:vuav-jn4q t:meta.view.license v:name="Public Domain"

property e:vuav-jn4q t:meta.view.owner v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:displayName="Kathy Gill"

property e:vuav-jn4q t:meta.view.tableauthor v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:roleName=publisher v:displayName="Kathy Gill"
```

## Top Records

```ls
| precinct | race                                                        | leg | cc | cg | countergroup | party | countertype       | sumofcount | 
| ======== | =========================================================== | === | == | == | ============ | ===== | ================= | ========== | 
| ALDARRA  | Snoqualmie Valley School District No. 410 Proposition No. 1 | 5   | 3  | 8  | Total        | NP    | Approved          | 127        | 
| ALDARRA  | Snoqualmie Valley School District No. 410 Proposition No. 1 | 5   | 3  | 8  | Total        | NP    | Registered Voters | 714        | 
| ALDARRA  | Snoqualmie Valley School District No. 410 Proposition No. 1 | 5   | 3  | 8  | Total        | NP    | Rejected          | 136        | 
| ALDARRA  | Snoqualmie Valley School District No. 410 Proposition No. 1 | 5   | 3  | 8  | Total        | NP    | Times Blank Voted | 0          | 
| ALDARRA  | Snoqualmie Valley School District No. 410 Proposition No. 1 | 5   | 3  | 8  | Total        | NP    | Times Counted     | 263        | 
| ALDARRA  | Snoqualmie Valley School District No. 410 Proposition No. 1 | 5   | 3  | 8  | Total        | NP    | Times Over Voted  | 0          | 
| ALPINE   | Snoqualmie Valley School District No. 410 Proposition No. 1 | 5   | 3  | 1  | Total        | NP    | Approved          | 98         | 
| ALPINE   | Snoqualmie Valley School District No. 410 Proposition No. 1 | 5   | 3  | 1  | Total        | NP    | Registered Voters | 565        | 
| ALPINE   | Snoqualmie Valley School District No. 410 Proposition No. 1 | 5   | 3  | 1  | Total        | NP    | Rejected          | 118        | 
| ALPINE   | Snoqualmie Valley School District No. 410 Proposition No. 1 | 5   | 3  | 1  | Total        | NP    | Times Blank Voted | 0          | 
```