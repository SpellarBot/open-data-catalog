# 2014 Primary Election Results by precinct (eCanvass dataset does not contain PCO data)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2014-primary-election-results-by-precinct-ecanvass-dataset-does-not-contain-pco-data) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/fps8-w6vc) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/fps8-w6vc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/fps8-w6vc/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | fps8-w6vc |
| Name | 2014 Primary Election Results by precinct (eCanvass dataset does not contain PCO data) |
| Attribution | King County Elections |
| Category | Election results |
| Tags | 2014, 2014 primary, primary, elections, results, precinct, ecanvass |
| Created | 2017-01-25T21:23:55Z |
| Publication Date | 2017-01-25T23:19:07Z |

## Description

August 2014 primary election; final/official results by precinct Does not contain PCO races.

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
Value = 2014
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = cc,cg
```

## Data Commands

```ls
series e:fps8-w6vc d:2014-01-01T00:00:00.000Z t:precinct=ADAIR t:countertype="Roger Goodman" t:countergroup=Total t:party=Dem t:race="Legislative District No. 45 Representative Position No. 1" m:leg=45 m:sumofcount=270

series e:fps8-w6vc d:2014-01-01T00:00:00.000Z t:precinct=ADAIR t:countertype="Registered Voters" t:countergroup=Total t:party=NP t:race="Legislative District No. 45 Representative Position No. 1" m:leg=45 m:sumofcount=919

series e:fps8-w6vc d:2014-01-01T00:00:00.000Z t:precinct=ADAIR t:countertype="Times Blank Voted" t:countergroup=Total t:party=NP t:race="Legislative District No. 45 Representative Position No. 1" m:leg=45 m:sumofcount=11
```

## Meta Commands

```ls
metric m:leg p:integer l:LEG t:dataTypeName=number

metric m:sumofcount p:integer l:SumOfCount t:dataTypeName=number

entity e:fps8-w6vc l:"2014 Primary Election Results by precinct (eCanvass dataset does not contain PCO data)" t:attribution="King County Elections" t:url=https://data.kingcounty.gov/api/views/fps8-w6vc

property e:fps8-w6vc t:meta.view v:id=fps8-w6vc v:category="Election results" v:attributionLink=http://kingcounty.gov/elections/results v:averageRating=0 v:name="2014 Primary Election Results by precinct (eCanvass dataset does not contain PCO data)" v:attribution="King County Elections"

property e:fps8-w6vc t:meta.view.license v:name="Public Domain"

property e:fps8-w6vc t:meta.view.owner v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:displayName="Kathy Gill"

property e:fps8-w6vc t:meta.view.tableauthor v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:roleName=publisher v:displayName="Kathy Gill"
```

## Top Records

```ls
| precinct | race                                                      | leg | cc | cg | countergroup | party | countertype       | sumofcount | 
| ======== | ========================================================= | === | == | == | ============ | ===== | ================= | ========== | 
| ADAIR    | Legislative District No. 45 Representative Position No. 1 | 45  | 3  | 1  | Total        | Dem   | Roger Goodman     | 270        | 
| ADAIR    | Legislative District No. 45 Representative Position No. 1 | 45  | 3  | 1  | Total        | NP    | Registered Voters | 919        | 
| ADAIR    | Legislative District No. 45 Representative Position No. 1 | 45  | 3  | 1  | Total        | NP    | Times Blank Voted | 11         | 
| ADAIR    | Legislative District No. 45 Representative Position No. 1 | 45  | 3  | 1  | Total        | NP    | Times Counted     | 587        | 
| ADAIR    | Legislative District No. 45 Representative Position No. 1 | 45  | 3  | 1  | Total        | NP    | Times Over Voted  | 0          | 
| ADAIR    | Legislative District No. 45 Representative Position No. 1 | 45  | 3  | 1  | Total        | NP    | Write-in          | 0          | 
| ADAIR    | Legislative District No. 45 Representative Position No. 1 | 45  | 3  | 1  | Total        | Rep   | Joel Hussey       | 306        | 
| ADAIR    | Legislative District No. 45 Representative Position No. 2 | 45  | 3  | 1  | Total        | Dem   | Larry Springer    | 285        | 
| ADAIR    | Legislative District No. 45 Representative Position No. 2 | 45  | 3  | 1  | Total        | NP    | Registered Voters | 919        | 
| ADAIR    | Legislative District No. 45 Representative Position No. 2 | 45  | 3  | 1  | Total        | NP    | Times Blank Voted | 11         | 
```