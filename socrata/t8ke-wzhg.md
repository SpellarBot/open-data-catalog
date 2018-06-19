# 2016 Special April - Election Night Results Abstract by Precinct

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2016-special-april-election-night-results-abstract-by-precinct) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/t8ke-wzhg) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/t8ke-wzhg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/t8ke-wzhg/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | t8ke-wzhg |
| Name | 2016 Special April - Election Night Results Abstract by Precinct |
| Attribution | King County Elections |
| Category | Election results |
| Tags | 2016, 2016 special, special, elections, results |
| Created | 2017-01-25T00:33:59Z |
| Publication Date | 2017-01-25T00:35:41Z |

## Description

April 2016 special election; election night results report by precinct.

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
series e:t8ke-wzhg d:2016-01-01T00:00:00.000Z t:precinct=ADAIR t:countertype=No t:countergroup=Total t:party=NP t:race="King County Fire Protection District No. 45 Proposition No. 1" m:leg=45 m:sumofcount=15

series e:t8ke-wzhg d:2016-01-01T00:00:00.000Z t:precinct=ADAIR t:countertype="Registered Voters" t:countergroup=Total t:party=NP t:race="King County Fire Protection District No. 45 Proposition No. 1" m:leg=45 m:sumofcount=170

series e:t8ke-wzhg d:2016-01-01T00:00:00.000Z t:precinct=ADAIR t:countertype="Times Blank Voted" t:countergroup=Total t:party=NP t:race="King County Fire Protection District No. 45 Proposition No. 1" m:leg=45 m:sumofcount=0
```

## Meta Commands

```ls
metric m:leg p:integer l:LEG t:dataTypeName=number

metric m:sumofcount p:integer l:SumOfCount t:dataTypeName=number

entity e:t8ke-wzhg l:"2016 Special April - Election Night Results Abstract by Precinct" t:attribution="King County Elections" t:url=https://data.kingcounty.gov/api/views/t8ke-wzhg

property e:t8ke-wzhg t:meta.view v:id=t8ke-wzhg v:category="Election results" v:attributionLink=http://kingcounty.gov/elections/results v:averageRating=0 v:name="2016 Special April - Election Night Results Abstract by Precinct" v:attribution="King County Elections"

property e:t8ke-wzhg t:meta.view.license v:name="Public Domain"

property e:t8ke-wzhg t:meta.view.owner v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:displayName="Kathy Gill"

property e:t8ke-wzhg t:meta.view.tableauthor v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:roleName=publisher v:displayName="Kathy Gill"
```

## Top Records

```ls
| precinct | race                                                          | leg | cc | cg | countergroup | party | countertype       | sumofcount | 
| ======== | ============================================================= | === | == | == | ============ | ===== | ================= | ========== | 
| ADAIR    | King County Fire Protection District No. 45 Proposition No. 1 | 45  | 3  | 1  | Total        | NP    | No                | 15         | 
| ADAIR    | King County Fire Protection District No. 45 Proposition No. 1 | 45  | 3  | 1  | Total        | NP    | Registered Voters | 170        | 
| ADAIR    | King County Fire Protection District No. 45 Proposition No. 1 | 45  | 3  | 1  | Total        | NP    | Times Blank Voted | 0          | 
| ADAIR    | King County Fire Protection District No. 45 Proposition No. 1 | 45  | 3  | 1  | Total        | NP    | Times Counted     | 85         | 
| ADAIR    | King County Fire Protection District No. 45 Proposition No. 1 | 45  | 3  | 1  | Total        | NP    | Times Over Voted  | 0          | 
| ADAIR    | King County Fire Protection District No. 45 Proposition No. 1 | 45  | 3  | 1  | Total        | NP    | Yes               | 70         | 
| ADAIR    | Lake Washington School District No. 414 Proposition No. 1     | 45  | 3  | 1  | Total        | NP    | Approved          | 101        | 
| ADAIR    | Lake Washington School District No. 414 Proposition No. 1     | 45  | 3  | 1  | Total        | NP    | Registered Voters | 329        | 
| ADAIR    | Lake Washington School District No. 414 Proposition No. 1     | 45  | 3  | 1  | Total        | NP    | Rejected          | 92         | 
| ADAIR    | Lake Washington School District No. 414 Proposition No. 1     | 45  | 3  | 1  | Total        | NP    | Times Blank Voted | 1          | 
```