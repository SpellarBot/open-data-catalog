# 2015 Special April - Election Results by precinct (complete eCanvass dataset)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2015-special-april-election-results-by-precinct-complete-ecanvass-dataset) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/qg8b-ssmp) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/qg8b-ssmp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/qg8b-ssmp/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | qg8b-ssmp |
| Name | 2015 Special April - Election Results by precinct (complete eCanvass dataset) |
| Attribution | King County Elections |
| Category | Election results |
| Tags | 2015, 2015 primary, primary, elections, results, precinct, ecanvass |
| Created | 2017-01-25T01:23:36Z |
| Publication Date | 2017-01-25T01:30:24Z |

## Description

April 2015 special election; final/official results by precinct.

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
series e:qg8b-ssmp d:2015-01-01T00:00:00.000Z t:precinct=ADAIR t:countertype=Approved t:countergroup=Total t:party=NP t:race="King County Proposition No. 1" m:leg=45 m:sumofcount=308

series e:qg8b-ssmp d:2015-01-01T00:00:00.000Z t:precinct=ADAIR t:countertype="Registered Voters" t:countergroup=Total t:party=NP t:race="King County Proposition No. 1" m:leg=45 m:sumofcount=912

series e:qg8b-ssmp d:2015-01-01T00:00:00.000Z t:precinct=ADAIR t:countertype=Rejected t:countergroup=Total t:party=NP t:race="King County Proposition No. 1" m:leg=45 m:sumofcount=162
```

## Meta Commands

```ls
metric m:leg p:integer l:LEG t:dataTypeName=number

metric m:sumofcount p:integer l:SumOfCount t:dataTypeName=number

entity e:qg8b-ssmp l:"2015 Special April - Election Results by precinct (complete eCanvass dataset)" t:attribution="King County Elections" t:url=https://data.kingcounty.gov/api/views/qg8b-ssmp

property e:qg8b-ssmp t:meta.view v:id=qg8b-ssmp v:category="Election results" v:attributionLink=http://kingcounty.gov/elections/results v:averageRating=0 v:name="2015 Special April - Election Results by precinct (complete eCanvass dataset)" v:attribution="King County Elections"

property e:qg8b-ssmp t:meta.view.license v:name="Public Domain"

property e:qg8b-ssmp t:meta.view.owner v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:displayName="Kathy Gill"

property e:qg8b-ssmp t:meta.view.tableauthor v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:roleName=publisher v:displayName="Kathy Gill"
```

## Top Records

```ls
| precinct | race                          | leg | cc | cg | countergroup | party | countertype       | sumofcount | 
| ======== | ============================= | === | == | == | ============ | ===== | ================= | ========== | 
| ADAIR    | King County Proposition No. 1 | 45  | 3  | 1  | Total        | NP    | Approved          | 308        | 
| ADAIR    | King County Proposition No. 1 | 45  | 3  | 1  | Total        | NP    | Registered Voters | 912        | 
| ADAIR    | King County Proposition No. 1 | 45  | 3  | 1  | Total        | NP    | Rejected          | 162        | 
| ADAIR    | King County Proposition No. 1 | 45  | 3  | 1  | Total        | NP    | Times Blank Voted | 3          | 
| ADAIR    | King County Proposition No. 1 | 45  | 3  | 1  | Total        | NP    | Times Counted     | 473        | 
| ADAIR    | King County Proposition No. 1 | 45  | 3  | 1  | Total        | NP    | Times Over Voted  | 0          | 
| ALDARRA  | King County Proposition No. 1 | 5   | 3  | 8  | Total        | NP    | Approved          | 109        | 
| ALDARRA  | King County Proposition No. 1 | 5   | 3  | 8  | Total        | NP    | Registered Voters | 704        | 
| ALDARRA  | King County Proposition No. 1 | 5   | 3  | 8  | Total        | NP    | Rejected          | 109        | 
| ALDARRA  | King County Proposition No. 1 | 5   | 3  | 8  | Total        | NP    | Times Blank Voted | 0          | 
```