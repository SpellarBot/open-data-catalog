# 2011 Special April - Election Results by precinct (complete eCanvass dataset)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/election-results-april-26-2011-special-33d5d) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/xhwu-st2x) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/xhwu-st2x/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/xhwu-st2x/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | xhwu-st2x |
| Name | 2011 Special April - Election Results by precinct (complete eCanvass dataset) |
| Attribution | King County |
| Category | Election results |
| Tags | 2011, 2011 special, special, elections, results, precinct, ecanvass |
| Created | 2011-05-11T21:17:14Z |
| Publication Date | 2011-05-11T21:17:14Z |

## Description

April 2011 special election; final/official results by precinct.

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type | Render Type |
| ======== | ============== | ============ | ============ | ========= | =========== |
| Yes      | series tag     | precinct     | Precinct     | text      | text        |
| Yes      | series tag     | race         | Race         | text      | text        |
| Yes      | series tag     | leg          | LEG          | text      | text        |
| No       |                | cc           | CC           | text      | text        |
| No       |                | cg           | CG           | text      | text        |
| Yes      | series tag     | countergroup | CounterGroup | text      | text        |
| Yes      | series tag     | party        | Party        | text      | text        |
| Yes      | series tag     | countertype  | CounterType  | text      | text        |
| Yes      | numeric metric | sumofcount   | SumOfCount   | number    | number      |
```

## Time Field

```ls
Value = 2011
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = cc,cg
```

## Data Commands

```ls
series e:xhwu-st2x d:2011-01-01T00:00:00.000Z t:precinct=ALDARRA t:leg=5 t:countertype=APPROVED t:countergroup=Total t:party=NP t:race="Snoqualmie Valley School District No. 410 Proposition No. 1" m:sumofcount=156

series e:xhwu-st2x d:2011-01-01T00:00:00.000Z t:precinct=ALDARRA t:leg=5 t:countertype="Registered Voters" t:countergroup=Total t:party=NP t:race="Snoqualmie Valley School District No. 410 Proposition No. 1" m:sumofcount=591

series e:xhwu-st2x d:2011-01-01T00:00:00.000Z t:precinct=ALDARRA t:leg=5 t:countertype=REJECTED t:countergroup=Total t:party=NP t:race="Snoqualmie Valley School District No. 410 Proposition No. 1" m:sumofcount=159
```

## Meta Commands

```ls
metric m:sumofcount p:float l:SumOfCount t:dataTypeName=number

entity e:xhwu-st2x l:"2011 Special April - Election Results by precinct (complete eCanvass dataset)" t:attribution="King County" t:url=https://data.kingcounty.gov/api/views/xhwu-st2x

property e:xhwu-st2x t:meta.view v:id=xhwu-st2x v:category="Election results" v:attributionLink=http://www.kingcounty.gov/elections/ v:averageRating=0 v:name="2011 Special April - Election Results by precinct (complete eCanvass dataset)" v:attribution="King County"

property e:xhwu-st2x t:meta.view.license v:name="Public Domain"

property e:xhwu-st2x t:meta.view.owner v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:displayName="King County Webteam"

property e:xhwu-st2x t:meta.view.tableauthor v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:roleName=administrator v:displayName="King County Webteam"
```

## Top Records

```ls
| precinct | race                                                        | leg | cc | cg | countergroup | party | countertype       | sumofcount | 
| ======== | =========================================================== | === | == | == | ============ | ===== | ================= | ========== | 
| Precinct | Race                                                        | LEG | CC | CG | CounterGroup | Party | CounterType       |            | 
| ALDARRA  | Snoqualmie Valley School District No. 410 Proposition No. 1 | 5   | 3  | 8  | Total        | NP    | APPROVED          | 156.00     | 
| ALDARRA  | Snoqualmie Valley School District No. 410 Proposition No. 1 | 5   | 3  | 8  | Total        | NP    | Registered Voters | 591.00     | 
| ALDARRA  | Snoqualmie Valley School District No. 410 Proposition No. 1 | 5   | 3  | 8  | Total        | NP    | REJECTED          | 159.00     | 
| ALDARRA  | Snoqualmie Valley School District No. 410 Proposition No. 1 | 5   | 3  | 8  | Total        | NP    | Times Blank Voted | 0.00       | 
| ALDARRA  | Snoqualmie Valley School District No. 410 Proposition No. 1 | 5   | 3  | 8  | Total        | NP    | Times Counted     | 315.00     | 
| ALDARRA  | Snoqualmie Valley School District No. 410 Proposition No. 1 | 5   | 3  | 8  | Total        | NP    | Times Over Voted  | 0.00       | 
| ALPINE   | Snoqualmie Valley School District No. 410 Proposition No. 1 | 5   | 3  | 8  | Total        | NP    | APPROVED          | 130.00     | 
| ALPINE   | Snoqualmie Valley School District No. 410 Proposition No. 1 | 5   | 3  | 8  | Total        | NP    | Registered Voters | 547.00     | 
| ALPINE   | Snoqualmie Valley School District No. 410 Proposition No. 1 | 5   | 3  | 8  | Total        | NP    | REJECTED          | 167.00     | 
```