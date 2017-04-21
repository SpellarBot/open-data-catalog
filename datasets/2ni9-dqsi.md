# 2016 Primary - Election Night Results Abstract by Precinct

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2016-primary-election-night-results-abstract-by-precinct) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/2ni9-dqsi) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/2ni9-dqsi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/2ni9-dqsi/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | 2ni9-dqsi |
| Name | 2016 Primary - Election Night Results Abstract by Precinct |
| Attribution | King County Elections |
| Category | Election results |
| Tags | 2016, 2016 primary, primary, elections, results |
| Created | 2017-01-24T23:45:51Z |
| Publication Date | 2017-01-24T23:58:56Z |

## Description

August 2016 election; election night results report by precinct.

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
series e:2ni9-dqsi d:2016-01-01T00:00:00.000Z t:precinct=ADAIR t:countertype="Bob Ferguson" t:countergroup=Total t:party=Dem t:race="Attorney General" m:leg=45 m:sumofcount=198

series e:2ni9-dqsi d:2016-01-01T00:00:00.000Z t:precinct=ADAIR t:countertype="Joshua B. Trumbull" t:countergroup=Total t:party=Lib t:race="Attorney General" m:leg=45 m:sumofcount=36

series e:2ni9-dqsi d:2016-01-01T00:00:00.000Z t:precinct=ADAIR t:countertype="Registered Voters" t:countergroup=Total t:party=NP t:race="Attorney General" m:leg=45 m:sumofcount=513
```

## Meta Commands

```ls
metric m:leg p:integer l:LEG t:dataTypeName=number

metric m:sumofcount p:integer l:SumOfCount t:dataTypeName=number

entity e:2ni9-dqsi l:"2016 Primary - Election Night Results Abstract by Precinct" t:attribution="King County Elections" t:url=https://data.kingcounty.gov/api/views/2ni9-dqsi

property e:2ni9-dqsi t:meta.view v:id=2ni9-dqsi v:category="Election results" v:attributionLink=http://kingcounty.gov/elections/results v:averageRating=0 v:name="2016 Primary - Election Night Results Abstract by Precinct" v:attribution="King County Elections"

property e:2ni9-dqsi t:meta.view.license v:name="Public Domain"

property e:2ni9-dqsi t:meta.view.owner v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:displayName="Kathy Gill"

property e:2ni9-dqsi t:meta.view.tableauthor v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:roleName=publisher v:displayName="Kathy Gill"
```

## Top Records

```ls
| precinct | race                         | leg | cc | cg | countergroup | party | countertype        | sumofcount | 
| ======== | ============================ | === | == | == | ============ | ===== | ================== | ========== | 
| ADAIR    | Attorney General             | 45  | 3  | 1  | Total        | Dem   | Bob Ferguson       | 198        | 
| ADAIR    | Attorney General             | 45  | 3  | 1  | Total        | Lib   | Joshua B. Trumbull | 36         | 
| ADAIR    | Attorney General             | 45  | 3  | 1  | Total        | NP    | Registered Voters  | 513        | 
| ADAIR    | Attorney General             | 45  | 3  | 1  | Total        | NP    | Times Blank Voted  | 27         | 
| ADAIR    | Attorney General             | 45  | 3  | 1  | Total        | NP    | Times Counted      | 261        | 
| ADAIR    | Attorney General             | 45  | 3  | 1  | Total        | NP    | Times Over Voted   | 0          | 
| ADAIR    | Attorney General             | 45  | 3  | 1  | Total        | NP    | Write-In           | 0          | 
| ADAIR    | Commissioner of Public Lands | 45  | 3  | 1  | Total        | Dem   | Dave Upthegrove    | 74         | 
| ADAIR    | Commissioner of Public Lands | 45  | 3  | 1  | Total        | Dem   | Hilary Franz       | 50         | 
| ADAIR    | Commissioner of Public Lands | 45  | 3  | 1  | Total        | Dem   | John Stillings     | 2          | 
```