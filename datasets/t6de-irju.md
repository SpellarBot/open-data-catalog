# 2015 General - Election Night Results Abstract by Precinct

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2015-general-election-night-results-abstract-by-precinct) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/t6de-irju) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/t6de-irju/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/t6de-irju/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | t6de-irju |
| Name | 2015 General - Election Night Results Abstract by Precinct |
| Attribution | King County Elections |
| Category | Election results |
| Tags | 2015, 2015 general, general, elections, results, precinct |
| Created | 2017-01-25T20:26:50Z |
| Publication Date | 2017-01-25T21:21:28Z |

## Description

November 2015 election; final/official results by precinct.

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
series e:t6de-irju d:2015-01-01T00:00:00.000Z t:precinct="ALDER SPRINGS" t:countertype="Registered Voters" t:countergroup=Total t:party=NP t:race="Woodinville Fire & Rescue Commissioner Position No. 5" m:leg=45 m:sumofcount=447

series e:t6de-irju d:2015-01-01T00:00:00.000Z t:precinct="ALDER SPRINGS" t:countertype="Roger Collins" t:countergroup=Total t:party=NP t:race="Woodinville Fire & Rescue Commissioner Position No. 5" m:leg=45 m:sumofcount=43

series e:t6de-irju d:2015-01-01T00:00:00.000Z t:precinct="ALDER SPRINGS" t:countertype="Times Blank Voted" t:countergroup=Total t:party=NP t:race="Woodinville Fire & Rescue Commissioner Position No. 5" m:leg=45 m:sumofcount=28
```

## Meta Commands

```ls
metric m:leg p:integer l:LEG t:dataTypeName=number

metric m:sumofcount p:integer l:SumOfCount t:dataTypeName=number

entity e:t6de-irju l:"2015 General - Election Night Results Abstract by Precinct" t:attribution="King County Elections" t:url=https://data.kingcounty.gov/api/views/t6de-irju

property e:t6de-irju t:meta.view v:id=t6de-irju v:category="Election results" v:attributionLink=http://kingcounty.gov/elections/results v:averageRating=0 v:name="2015 General - Election Night Results Abstract by Precinct" v:attribution="King County Elections"

property e:t6de-irju t:meta.view.license v:name="Public Domain"

property e:t6de-irju t:meta.view.owner v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:displayName="Kathy Gill"

property e:t6de-irju t:meta.view.tableauthor v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:roleName=publisher v:displayName="Kathy Gill"
```

## Top Records

```ls
| precinct      | race                                                   | leg | cc | cg | countergroup | party | countertype       | sumofcount | 
| ============= | ====================================================== | === | == | == | ============ | ===== | ================= | ========== | 
| ALDER SPRINGS | Woodinville Fire & Rescue Commissioner Position No. 5  | 45  | 3  | 1  | Total        | NP    | Registered Voters | 447        | 
| ALDER SPRINGS | Woodinville Fire & Rescue Commissioner Position No. 5  | 45  | 3  | 1  | Total        | NP    | Roger Collins     | 43         | 
| ALDER SPRINGS | Woodinville Fire & Rescue Commissioner Position No. 5  | 45  | 3  | 1  | Total        | NP    | Times Blank Voted | 28         | 
| ALDER SPRINGS | Woodinville Fire & Rescue Commissioner Position No. 5  | 45  | 3  | 1  | Total        | NP    | Times Counted     | 75         | 
| ALDER SPRINGS | Woodinville Fire & Rescue Commissioner Position No. 5  | 45  | 3  | 1  | Total        | NP    | Times Over Voted  | 0          | 
| ALDER SPRINGS | Woodinville Fire & Rescue Commissioner Position No. 5  | 45  | 3  | 1  | Total        | NP    | Write-in          | 4          | 
| ALDER SPRINGS | Woodinville Water District Commissioner Position No. 3 | 45  | 3  | 1  | Total        | NP    | Pam Maloney       | 3          | 
| ALDER SPRINGS | Woodinville Water District Commissioner Position No. 3 | 45  | 3  | 1  | Total        | NP    | Registered Voters | 47         | 
| ALDER SPRINGS | Woodinville Water District Commissioner Position No. 3 | 45  | 3  | 1  | Total        | NP    | Times Blank Voted | 0          | 
| ALDER SPRINGS | Woodinville Water District Commissioner Position No. 3 | 45  | 3  | 1  | Total        | NP    | Times Counted     | 3          | 
```