# 2015 Primary - Election Night Results Abstract by Precinct

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2015-primary-election-night-results-abstract-by-precinct) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/s4xf-st5s) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/s4xf-st5s/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/s4xf-st5s/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | s4xf-st5s |
| Name | 2015 Primary - Election Night Results Abstract by Precinct |
| Attribution | King County Elections |
| Category | Election results |
| Tags | 2015, 2015 primary, primary, elections, results, precinct |
| Created | 2017-01-27T21:31:38Z |
| Publication Date | 2017-01-27T21:34:01Z |

## Description

August 2015 primary election; election night results report by precinct.

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
series e:s4xf-st5s d:2015-01-01T00:00:00.000Z t:precinct=ADAIR t:countertype="Christopher Roberts" t:countergroup=Total t:party=NP t:race="Director of Elections" m:leg=45 m:sumofcount=33

series e:s4xf-st5s d:2015-01-01T00:00:00.000Z t:precinct=ADAIR t:countertype="Julie Wise" t:countergroup=Total t:party=NP t:race="Director of Elections" m:leg=45 m:sumofcount=157

series e:s4xf-st5s d:2015-01-01T00:00:00.000Z t:precinct=ADAIR t:countertype="Registered Voters" t:countergroup=Total t:party=NP t:race="Director of Elections" m:leg=45 m:sumofcount=499
```

## Meta Commands

```ls
metric m:leg p:integer l:LEG t:dataTypeName=number

metric m:sumofcount p:integer l:SumOfCount t:dataTypeName=number

entity e:s4xf-st5s l:"2015 Primary - Election Night Results Abstract by Precinct" t:attribution="King County Elections" t:url=https://data.kingcounty.gov/api/views/s4xf-st5s

property e:s4xf-st5s t:meta.view v:id=s4xf-st5s v:category="Election results" v:attributionLink=http://kingcounty.gov/elections/results v:averageRating=0 v:name="2015 Primary - Election Night Results Abstract by Precinct" v:attribution="King County Elections"

property e:s4xf-st5s t:meta.view.license v:name="Public Domain"

property e:s4xf-st5s t:meta.view.owner v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:displayName="Kathy Gill"

property e:s4xf-st5s t:meta.view.tableauthor v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:roleName=publisher v:displayName="Kathy Gill"
```

## Top Records

```ls
| precinct | race                                        | leg | cc | cg | countergroup | party | countertype         | sumofcount | 
| ======== | =========================================== | === | == | == | ============ | ===== | =================== | ========== | 
| ADAIR    | Director of Elections                       | 45  | 3  | 1  | Total        | NP    | Christopher Roberts | 33         | 
| ADAIR    | Director of Elections                       | 45  | 3  | 1  | Total        | NP    | Julie Wise          | 157        | 
| ADAIR    | Director of Elections                       | 45  | 3  | 1  | Total        | NP    | Registered Voters   | 499        | 
| ADAIR    | Director of Elections                       | 45  | 3  | 1  | Total        | NP    | Times Blank Voted   | 5          | 
| ADAIR    | Director of Elections                       | 45  | 3  | 1  | Total        | NP    | Times Counted       | 221        | 
| ADAIR    | Director of Elections                       | 45  | 3  | 1  | Total        | NP    | Times Over Voted    | 0          | 
| ADAIR    | Director of Elections                       | 45  | 3  | 1  | Total        | NP    | Write-in            | 0          | 
| ADAIR    | Director of Elections                       | 45  | 3  | 1  | Total        | NP    | Zack Hudgins        | 26         | 
| ADAIR    | Port of Seattle Commissioner Position No. 2 | 45  | 3  | 1  | Total        | NP    | Courtney Gregoire   | 189        | 
| ADAIR    | Port of Seattle Commissioner Position No. 2 | 45  | 3  | 1  | Total        | NP    | Goodspaceguy        | 11         | 
```