# 2016 Special February - Election Results by precinct (complete eCanvass dataset)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2016-special-february-election-results-by-precinct-complete-ecanvass-dataset) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/fku3-m3bn) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/fku3-m3bn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/fku3-m3bn/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | fku3-m3bn |
| Name | 2016 Special February - Election Results by precinct (complete eCanvass dataset) |
| Attribution | King County Election |
| Category | Election results |
| Tags | 2016, 2016 special, special, elections, results, precinct, ecanvass |
| Created | 2017-01-25T00:42:32Z |
| Publication Date | 2017-01-25T00:49:39Z |

## Description

February 2016 special election; final/official results by precinct.

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
series e:fku3-m3bn d:2016-01-01T00:00:00.000Z t:precinct="ALG 30-0013" t:countertype=No t:countergroup=Total t:party=NP t:race="Auburn School District No. 408 Proposition No. 1" m:leg=30 m:sumofcount=33

series e:fku3-m3bn d:2016-01-01T00:00:00.000Z t:precinct="ALG 30-0013" t:countertype="Registered Voters" t:countergroup=Total t:party=NP t:race="Auburn School District No. 408 Proposition No. 1" m:leg=30 m:sumofcount=460

series e:fku3-m3bn d:2016-01-01T00:00:00.000Z t:precinct="ALG 30-0013" t:countertype="Times Blank Voted" t:countergroup=Total t:party=NP t:race="Auburn School District No. 408 Proposition No. 1" m:leg=30 m:sumofcount=0
```

## Meta Commands

```ls
metric m:leg p:integer l:LEG t:dataTypeName=number

metric m:sumofcount p:integer l:SumOfCount t:dataTypeName=number

entity e:fku3-m3bn l:"2016 Special February - Election Results by precinct (complete eCanvass dataset)" t:attribution="King County Election" t:url=https://data.kingcounty.gov/api/views/fku3-m3bn

property e:fku3-m3bn t:meta.view v:id=fku3-m3bn v:category="Election results" v:attributionLink=http://kingcounty.gov/elections/results v:averageRating=0 v:name="2016 Special February - Election Results by precinct (complete eCanvass dataset)" v:attribution="King County Election"

property e:fku3-m3bn t:meta.view.license v:name="Public Domain"

property e:fku3-m3bn t:meta.view.owner v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:displayName="Kathy Gill"

property e:fku3-m3bn t:meta.view.tableauthor v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:roleName=publisher v:displayName="Kathy Gill"
```

## Top Records

```ls
| precinct    | race                                             | leg | cc | cg | countergroup | party | countertype       | sumofcount | 
| =========== | ================================================ | === | == | == | ============ | ===== | ================= | ========== | 
| ALG 30-0013 | Auburn School District No. 408 Proposition No. 1 | 30  | 7  | 8  | Total        | NP    | No                | 33         | 
| ALG 30-0013 | Auburn School District No. 408 Proposition No. 1 | 30  | 7  | 8  | Total        | NP    | Registered Voters | 460        | 
| ALG 30-0013 | Auburn School District No. 408 Proposition No. 1 | 30  | 7  | 8  | Total        | NP    | Times Blank Voted | 0          | 
| ALG 30-0013 | Auburn School District No. 408 Proposition No. 1 | 30  | 7  | 8  | Total        | NP    | Times Counted     | 84         | 
| ALG 30-0013 | Auburn School District No. 408 Proposition No. 1 | 30  | 7  | 8  | Total        | NP    | Times Over Voted  | 0          | 
| ALG 30-0013 | Auburn School District No. 408 Proposition No. 1 | 30  | 7  | 8  | Total        | NP    | Yes               | 51         | 
| ALG 30-0014 | Auburn School District No. 408 Proposition No. 1 | 30  | 7  | 8  | Total        | NP    | No                | 47         | 
| ALG 30-0014 | Auburn School District No. 408 Proposition No. 1 | 30  | 7  | 8  | Total        | NP    | Registered Voters | 491        | 
| ALG 30-0014 | Auburn School District No. 408 Proposition No. 1 | 30  | 7  | 8  | Total        | NP    | Times Blank Voted | 0          | 
| ALG 30-0014 | Auburn School District No. 408 Proposition No. 1 | 30  | 7  | 8  | Total        | NP    | Times Counted     | 98         | 
```