# 2016 General - Election Night Results Abstract by Precinct

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2016-general-election-night-results-abstract-by-precinct) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/gt6w-efj2) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/gt6w-efj2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/gt6w-efj2/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | gt6w-efj2 |
| Name | 2016 General - Election Night Results Abstract by Precinct |
| Attribution | King County Elections |
| Category | Election results |
| Tags | 2016, 2016 general, general, elections, results |
| Created | 2017-01-24T23:21:32Z |
| Publication Date | 2017-01-24T23:34:23Z |

## Description

November 2016 general election; election night results report by precinct.

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
series e:gt6w-efj2 d:2016-01-01T00:00:00.000Z t:precinct=ADAIR t:countertype=Maintained t:countergroup=Total t:party=NP t:race="Advisory Vote 14" m:leg=45 m:sumofcount=135

series e:gt6w-efj2 d:2016-01-01T00:00:00.000Z t:precinct=ADAIR t:countertype="Registered Voters" t:countergroup=Total t:party=NP t:race="Advisory Vote 14" m:leg=45 m:sumofcount=519

series e:gt6w-efj2 d:2016-01-01T00:00:00.000Z t:precinct=ADAIR t:countertype=Repealed t:countergroup=Total t:party=NP t:race="Advisory Vote 14" m:leg=45 m:sumofcount=193
```

## Meta Commands

```ls
metric m:leg p:integer l:LEG t:dataTypeName=number

metric m:sumofcount p:integer l:SumOfCount t:dataTypeName=number

entity e:gt6w-efj2 l:"2016 General - Election Night Results Abstract by Precinct" t:attribution="King County Elections" t:url=https://data.kingcounty.gov/api/views/gt6w-efj2

property e:gt6w-efj2 t:meta.view v:id=gt6w-efj2 v:category="Election results" v:attributionLink=http://kingcounty.gov/elections/results v:averageRating=0 v:name="2016 General - Election Night Results Abstract by Precinct" v:attribution="King County Elections"

property e:gt6w-efj2 t:meta.view.license v:name="Public Domain"

property e:gt6w-efj2 t:meta.view.owner v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:displayName="Kathy Gill"

property e:gt6w-efj2 t:meta.view.tableauthor v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:roleName=publisher v:displayName="Kathy Gill"
```

## Top Records

```ls
| precinct | race             | leg | cc | cg | countergroup | party | countertype       | sumofcount | 
| ======== | ================ | === | == | == | ============ | ===== | ================= | ========== | 
| ADAIR    | Advisory Vote 14 | 45  | 3  | 1  | Total        | NP    | Maintained        | 135        | 
| ADAIR    | Advisory Vote 14 | 45  | 3  | 1  | Total        | NP    | Registered Voters | 519        | 
| ADAIR    | Advisory Vote 14 | 45  | 3  | 1  | Total        | NP    | Repealed          | 193        | 
| ADAIR    | Advisory Vote 14 | 45  | 3  | 1  | Total        | NP    | Times Blank Voted | 38         | 
| ADAIR    | Advisory Vote 14 | 45  | 3  | 1  | Total        | NP    | Times Counted     | 366        | 
| ADAIR    | Advisory Vote 14 | 45  | 3  | 1  | Total        | NP    | Times Over Voted  | 0          | 
| ADAIR    | Advisory Vote 15 | 45  | 3  | 1  | Total        | NP    | Maintained        | 158        | 
| ADAIR    | Advisory Vote 15 | 45  | 3  | 1  | Total        | NP    | Registered Voters | 519        | 
| ADAIR    | Advisory Vote 15 | 45  | 3  | 1  | Total        | NP    | Repealed          | 176        | 
| ADAIR    | Advisory Vote 15 | 45  | 3  | 1  | Total        | NP    | Times Blank Voted | 32         | 
```