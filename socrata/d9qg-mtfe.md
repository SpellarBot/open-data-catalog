# 2016 Primary - Election Results by precinct (complete eCanvass dataset)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2016-primary-election-results-by-precinct-complete-ecanvass-dataset) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/d9qg-mtfe) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/d9qg-mtfe/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/d9qg-mtfe/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | d9qg-mtfe |
| Name | 2016 Primary - Election Results by precinct (complete eCanvass dataset) |
| Attribution | King County Elections |
| Category | Election results |
| Tags | 2016, 2016 primary, primary, elections, results, precinct, ecanvass |
| Created | 2017-01-25T00:08:24Z |
| Publication Date | 2017-01-25T00:22:41Z |

## Description

August 2016 primary election; final/official results by precinct.

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
series e:d9qg-mtfe d:2016-01-01T00:00:00.000Z t:precinct=ADAIR t:countertype="Bob Ferguson" t:countergroup=Total t:party=Dem t:race="Attorney General" m:leg=45 m:sumofcount=260

series e:d9qg-mtfe d:2016-01-01T00:00:00.000Z t:precinct=ADAIR t:countertype="Joshua B. Trumbull" t:countergroup=Total t:party=Lib t:race="Attorney General" m:leg=45 m:sumofcount=48

series e:d9qg-mtfe d:2016-01-01T00:00:00.000Z t:precinct=ADAIR t:countertype="Registered Voters" t:countergroup=Total t:party=NP t:race="Attorney General" m:leg=45 m:sumofcount=513
```

## Meta Commands

```ls
metric m:leg p:integer l:LEG t:dataTypeName=number

metric m:sumofcount p:integer l:SumOfCount t:dataTypeName=number

entity e:d9qg-mtfe l:"2016 Primary - Election Results by precinct (complete eCanvass dataset)" t:attribution="King County Elections" t:url=https://data.kingcounty.gov/api/views/d9qg-mtfe

property e:d9qg-mtfe t:meta.view v:id=d9qg-mtfe v:category="Election results" v:attributionLink=http://kingcounty.gov/elections/results v:averageRating=0 v:name="2016 Primary - Election Results by precinct (complete eCanvass dataset)" v:attribution="King County Elections"

property e:d9qg-mtfe t:meta.view.license v:name="Public Domain"

property e:d9qg-mtfe t:meta.view.owner v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:displayName="Kathy Gill"

property e:d9qg-mtfe t:meta.view.tableauthor v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:roleName=publisher v:displayName="Kathy Gill"
```

## Top Records

```ls
| precinct | race                         | leg | cc | cg | countergroup | party | countertype        | sumofcount | 
| ======== | ============================ | === | == | == | ============ | ===== | ================== | ========== | 
| ADAIR    | Attorney General             | 45  | 3  | 1  | Total        | Dem   | Bob Ferguson       | 260        | 
| ADAIR    | Attorney General             | 45  | 3  | 1  | Total        | Lib   | Joshua B. Trumbull | 48         | 
| ADAIR    | Attorney General             | 45  | 3  | 1  | Total        | NP    | Registered Voters  | 513        | 
| ADAIR    | Attorney General             | 45  | 3  | 1  | Total        | NP    | Times Blank Voted  | 35         | 
| ADAIR    | Attorney General             | 45  | 3  | 1  | Total        | NP    | Times Counted      | 344        | 
| ADAIR    | Attorney General             | 45  | 3  | 1  | Total        | NP    | Times Over Voted   | 0          | 
| ADAIR    | Attorney General             | 45  | 3  | 1  | Total        | NP    | Write-In           | 1          | 
| ADAIR    | Commissioner of Public Lands | 45  | 3  | 1  | Total        | Dem   | Dave Upthegrove    | 84         | 
| ADAIR    | Commissioner of Public Lands | 45  | 3  | 1  | Total        | Dem   | Hilary Franz       | 68         | 
| ADAIR    | Commissioner of Public Lands | 45  | 3  | 1  | Total        | Dem   | John Stillings     | 5          | 
```