# 2014 Primary - PCO Election Results by precinct (complete eCanvass dataset)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2014-primary-election-results-by-precinct-complete-ecanvass-dataset) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/xd4b-q4c2) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/xd4b-q4c2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/xd4b-q4c2/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | xd4b-q4c2 |
| Name | 2014 Primary - PCO Election Results by precinct (complete eCanvass dataset) |
| Attribution | King County Elections |
| Category | Election results |
| Tags | 2014, 2014 primary, primary, elections, results, precinct, ecanvass, pco |
| Created | 2017-01-25T23:19:56Z |
| Publication Date | 2017-01-25T23:21:12Z |

## Description

August 2014 primary election; final/official PCO results by precinct.

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
series e:xd4b-q4c2 d:2014-01-01T00:00:00.000Z t:precinct="BOT 01-0256" t:countertype="Erik Heino" t:countergroup=Total t:party=DPC t:race="PCO BOT 01-0256" m:leg=1 m:sumofcount=17

series e:xd4b-q4c2 d:2014-01-01T00:00:00.000Z t:precinct="BOT 01-0256" t:countertype="Julia C. Lacey" t:countergroup=Total t:party=DPC t:race="PCO BOT 01-0256" m:leg=1 m:sumofcount=58

series e:xd4b-q4c2 d:2014-01-01T00:00:00.000Z t:precinct="BOT 01-0256" t:countertype="Registered Voters" t:countergroup=Total t:party=NP t:race="PCO BOT 01-0256" m:leg=1 m:sumofcount=659
```

## Meta Commands

```ls
metric m:leg p:integer l:LEG t:dataTypeName=number

metric m:sumofcount p:integer l:SumOfCount t:dataTypeName=number

entity e:xd4b-q4c2 l:"2014 Primary - PCO Election Results by precinct (complete eCanvass dataset)" t:attribution="King County Elections" t:url=https://data.kingcounty.gov/api/views/xd4b-q4c2

property e:xd4b-q4c2 t:meta.view v:id=xd4b-q4c2 v:category="Election results" v:attributionLink=http://kingcounty.gov/elections/results v:averageRating=0 v:name="2014 Primary - PCO Election Results by precinct (complete eCanvass dataset)" v:attribution="King County Elections"

property e:xd4b-q4c2 t:meta.view.license v:name="Public Domain"

property e:xd4b-q4c2 t:meta.view.owner v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:displayName="Kathy Gill"

property e:xd4b-q4c2 t:meta.view.tableauthor v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:roleName=publisher v:displayName="Kathy Gill"
```

## Top Records

```ls
| precinct    | race            | leg | cc | cg | countergroup | party | countertype       | sumofcount | 
| =========== | =============== | === | == | == | ============ | ===== | ================= | ========== | 
| BOT 01-0256 | PCO BOT 01-0256 | 1   | 1  | 1  | Total        | DPC   | Erik Heino        | 17         | 
| BOT 01-0256 | PCO BOT 01-0256 | 1   | 1  | 1  | Total        | DPC   | Julia C. Lacey    | 58         | 
| BOT 01-0256 | PCO BOT 01-0256 | 1   | 1  | 1  | Total        | NP    | Registered Voters | 659        | 
| BOT 01-0256 | PCO BOT 01-0256 | 1   | 1  | 1  | Total        | NP    | Times Blank Voted | 72         | 
| BOT 01-0256 | PCO BOT 01-0256 | 1   | 1  | 1  | Total        | NP    | Times Counted     | 196        | 
| BOT 01-0256 | PCO BOT 01-0256 | 1   | 1  | 1  | Total        | NP    | Times Over Voted  | 0          | 
| BOT 01-0256 | PCO BOT 01-0256 | 1   | 1  | 1  | Total        | RPC   | James Allsup      | 18         | 
| BOT 01-0256 | PCO BOT 01-0256 | 1   | 1  | 1  | Total        | RPC   | Jim Schumacher    | 31         | 
| BOT 01-0261 | PCO BOT 01-0261 | 1   | 1  | 1  | Total        | NP    | Registered Voters | 621        | 
| BOT 01-0261 | PCO BOT 01-0261 | 1   | 1  | 1  | Total        | NP    | Times Blank Voted | 136        | 
```