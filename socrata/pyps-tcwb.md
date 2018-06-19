# 2015 Primary - Election Results by precinct (complete eCanvass dataset)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2015-primary-election-results-by-precinct-complete-ecanvass-dataset) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/pyps-tcwb) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/pyps-tcwb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/pyps-tcwb/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | pyps-tcwb |
| Name | 2015 Primary - Election Results by precinct (complete eCanvass dataset) |
| Attribution | King County Election |
| Category | Election results |
| Tags | 2015, 2015 primary, primary, elections, results, precinct, ecanvass |
| Created | 2017-01-25T01:11:05Z |
| Publication Date | 2017-01-25T01:12:47Z |

## Description

August 2015 primary election; final/official results by precinct.

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
series e:pyps-tcwb d:2015-01-01T00:00:00.000Z t:precinct=ADAIR t:countertype="Christopher Roberts" t:countergroup=Total t:party=NP t:race="Director of Elections" m:leg=45 m:sumofcount=38

series e:pyps-tcwb d:2015-01-01T00:00:00.000Z t:precinct=ADAIR t:countertype="Julie Wise" t:countergroup=Total t:party=NP t:race="Director of Elections" m:leg=45 m:sumofcount=171

series e:pyps-tcwb d:2015-01-01T00:00:00.000Z t:precinct=ADAIR t:countertype="Registered Voters" t:countergroup=Total t:party=NP t:race="Director of Elections" m:leg=45 m:sumofcount=499
```

## Meta Commands

```ls
metric m:leg p:integer l:LEG t:dataTypeName=number

metric m:sumofcount p:integer l:SumOfCount t:dataTypeName=number

entity e:pyps-tcwb l:"2015 Primary - Election Results by precinct (complete eCanvass dataset)" t:attribution="King County Election" t:url=https://data.kingcounty.gov/api/views/pyps-tcwb

property e:pyps-tcwb t:meta.view v:id=pyps-tcwb v:category="Election results" v:attributionLink=http://kingcounty.gov/elections/results v:averageRating=0 v:name="2015 Primary - Election Results by precinct (complete eCanvass dataset)" v:attribution="King County Election"

property e:pyps-tcwb t:meta.view.license v:name="Public Domain"

property e:pyps-tcwb t:meta.view.owner v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:displayName="Kathy Gill"

property e:pyps-tcwb t:meta.view.tableauthor v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:roleName=publisher v:displayName="Kathy Gill"
```

## Top Records

```ls
| precinct | race                                        | leg | cc | cg | countergroup | party | countertype         | sumofcount | 
| ======== | =========================================== | === | == | == | ============ | ===== | =================== | ========== | 
| ADAIR    | Director of Elections                       | 45  | 3  | 1  | Total        | NP    | Christopher Roberts | 38         | 
| ADAIR    | Director of Elections                       | 45  | 3  | 1  | Total        | NP    | Julie Wise          | 171        | 
| ADAIR    | Director of Elections                       | 45  | 3  | 1  | Total        | NP    | Registered Voters   | 499        | 
| ADAIR    | Director of Elections                       | 45  | 3  | 1  | Total        | NP    | Times Blank Voted   | 5          | 
| ADAIR    | Director of Elections                       | 45  | 3  | 1  | Total        | NP    | Times Counted       | 242        | 
| ADAIR    | Director of Elections                       | 45  | 3  | 1  | Total        | NP    | Times Over Voted    | 0          | 
| ADAIR    | Director of Elections                       | 45  | 3  | 1  | Total        | NP    | Write-in            | 0          | 
| ADAIR    | Director of Elections                       | 45  | 3  | 1  | Total        | NP    | Zack Hudgins        | 28         | 
| ADAIR    | Port of Seattle Commissioner Position No. 2 | 45  | 3  | 1  | Total        | NP    | Courtney Gregoire   | 206        | 
| ADAIR    | Port of Seattle Commissioner Position No. 2 | 45  | 3  | 1  | Total        | NP    | Goodspaceguy        | 13         | 
```