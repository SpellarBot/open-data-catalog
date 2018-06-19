# 2013 Primary - Election Results by precinct (complete eCanvass dataset)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2013-primary-election-results-by-precinct-complete-ecanvass-dataset) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/e537-zsyr) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/e537-zsyr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/e537-zsyr/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | e537-zsyr |
| Name | 2013 Primary - Election Results by precinct (complete eCanvass dataset) |
| Attribution | King County Elections |
| Category | Election results |
| Tags | 2013, 2013 primary, primary, elections, results, precinct, ecanvass |
| Created | 2017-01-27T22:24:26Z |
| Publication Date | 2017-01-27T22:27:54Z |

## Description

August 2013 primary election; final/official results by precinct.

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
Value = 2013
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = cc,cg
```

## Data Commands

```ls
series e:e537-zsyr d:2013-01-01T00:00:00.000Z t:precinct=ADAIR t:countertype="Andrew Pilloud" t:countergroup=Total t:party=NP t:race="Port of Seattle Commissioner Position No. 3  short and full term nonpartisan office" m:leg=45 m:sumofcount=87

series e:e537-zsyr d:2013-01-01T00:00:00.000Z t:precinct=ADAIR t:countertype="Michael Wolfe" t:countergroup=Total t:party=NP t:race="Port of Seattle Commissioner Position No. 3  short and full term nonpartisan office" m:leg=45 m:sumofcount=52

series e:e537-zsyr d:2013-01-01T00:00:00.000Z t:precinct=ADAIR t:countertype="Registered Voters" t:countergroup=Total t:party=NP t:race="Port of Seattle Commissioner Position No. 3  short and full term nonpartisan office" m:leg=45 m:sumofcount=881
```

## Meta Commands

```ls
metric m:leg p:integer l:LEG t:dataTypeName=number

metric m:sumofcount p:integer l:SumOfCount t:dataTypeName=number

entity e:e537-zsyr l:"2013 Primary - Election Results by precinct (complete eCanvass dataset)" t:attribution="King County Elections" t:url=https://data.kingcounty.gov/api/views/e537-zsyr

property e:e537-zsyr t:meta.view v:id=e537-zsyr v:category="Election results" v:attributionLink=http://kingcounty.gov/elections/results v:averageRating=0 v:name="2013 Primary - Election Results by precinct (complete eCanvass dataset)" v:attribution="King County Elections"

property e:e537-zsyr t:meta.view.license v:name="Public Domain"

property e:e537-zsyr t:meta.view.owner v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:displayName="Kathy Gill"

property e:e537-zsyr t:meta.view.tableauthor v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:roleName=publisher v:displayName="Kathy Gill"
```

## Top Records

```ls
| precinct | race                                                                               | leg | cc | cg | countergroup | party | countertype       | sumofcount | 
| ======== | ================================================================================== | === | == | == | ============ | ===== | ================= | ========== | 
| ADAIR    | Port of Seattle Commissioner Position No. 3 short and full term nonpartisan office | 45  | 3  | 1  | Total        | NP    | Andrew Pilloud    | 87         | 
| ADAIR    | Port of Seattle Commissioner Position No. 3 short and full term nonpartisan office | 45  | 3  | 1  | Total        | NP    | Michael Wolfe     | 52         | 
| ADAIR    | Port of Seattle Commissioner Position No. 3 short and full term nonpartisan office | 45  | 3  | 1  | Total        | NP    | Registered Voters | 881        | 
| ADAIR    | Port of Seattle Commissioner Position No. 3 short and full term nonpartisan office | 45  | 3  | 1  | Total        | NP    | Stephanie Bowman  | 247        | 
| ADAIR    | Port of Seattle Commissioner Position No. 3 short and full term nonpartisan office | 45  | 3  | 1  | Total        | NP    | Times Blank Voted | 80         | 
| ADAIR    | Port of Seattle Commissioner Position No. 3 short and full term nonpartisan office | 45  | 3  | 1  | Total        | NP    | Times Counted     | 468        | 
| ADAIR    | Port of Seattle Commissioner Position No. 3 short and full term nonpartisan office | 45  | 3  | 1  | Total        | NP    | Times Over Voted  | 0          | 
| ADAIR    | Port of Seattle Commissioner Position No. 3 short and full term nonpartisan office | 45  | 3  | 1  | Total        | NP    | Write-in          | 2          | 
| ADAIR    | King County Executive nonpartisan office                                           | 45  | 3  | 1  | Total        | NP    | Alan E. Lobdell   | 50         | 
| ADAIR    | King County Executive nonpartisan office                                           | 45  | 3  | 1  | Total        | NP    | Dow Constantine   | 330        | 
```