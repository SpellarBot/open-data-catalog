# 2016 General - Election Results by precinct (complete eCanvass dataset)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2016-general-election-results-by-precinct-complete-ecanvass-dataset) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/b27z-cdmk) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/b27z-cdmk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/b27z-cdmk/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | b27z-cdmk |
| Name | 2016 General - Election Results by precinct (complete eCanvass dataset) |
| Attribution | King County Elections |
| Category | Election results |
| Tags | 2016, 2016 general, general, elections, results, precinct, ecanvass |
| Created | 2017-01-24T23:36:55Z |
| Publication Date | 2017-01-24T23:41:18Z |

## Description

November 2016 general election; final/official results by precinct.

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
series e:b27z-cdmk d:2016-01-01T00:00:00.000Z t:precinct=ADAIR t:countertype=Maintained t:countergroup=Total t:party=NP t:race="Advisory Vote 14" m:leg=45 m:sumofcount=183

series e:b27z-cdmk d:2016-01-01T00:00:00.000Z t:precinct=ADAIR t:countertype="Registered Voters" t:countergroup=Total t:party=NP t:race="Advisory Vote 14" m:leg=45 m:sumofcount=519

series e:b27z-cdmk d:2016-01-01T00:00:00.000Z t:precinct=ADAIR t:countertype=Repealed t:countergroup=Total t:party=NP t:race="Advisory Vote 14" m:leg=45 m:sumofcount=251
```

## Meta Commands

```ls
metric m:leg p:integer l:LEG t:dataTypeName=number

metric m:sumofcount p:integer l:SumOfCount t:dataTypeName=number

entity e:b27z-cdmk l:"2016 General - Election Results by precinct (complete eCanvass dataset)" t:attribution="King County Elections" t:url=https://data.kingcounty.gov/api/views/b27z-cdmk

property e:b27z-cdmk t:meta.view v:id=b27z-cdmk v:category="Election results" v:attributionLink=http://kingcounty.gov/elections/results v:averageRating=0 v:name="2016 General - Election Results by precinct (complete eCanvass dataset)" v:attribution="King County Elections"

property e:b27z-cdmk t:meta.view.license v:name="Public Domain"

property e:b27z-cdmk t:meta.view.owner v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:displayName="Kathy Gill"

property e:b27z-cdmk t:meta.view.tableauthor v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:roleName=publisher v:displayName="Kathy Gill"
```

## Top Records

```ls
| precinct | race             | leg | cc | cg | countergroup | party | countertype       | sumofcount | 
| ======== | ================ | === | == | == | ============ | ===== | ================= | ========== | 
| ADAIR    | Advisory Vote 14 | 45  | 3  | 1  | Total        | NP    | Maintained        | 183        | 
| ADAIR    | Advisory Vote 14 | 45  | 3  | 1  | Total        | NP    | Registered Voters | 519        | 
| ADAIR    | Advisory Vote 14 | 45  | 3  | 1  | Total        | NP    | Repealed          | 251        | 
| ADAIR    | Advisory Vote 14 | 45  | 3  | 1  | Total        | NP    | Times Blank Voted | 51         | 
| ADAIR    | Advisory Vote 14 | 45  | 3  | 1  | Total        | NP    | Times Counted     | 485        | 
| ADAIR    | Advisory Vote 14 | 45  | 3  | 1  | Total        | NP    | Times Over Voted  | 0          | 
| ADAIR    | Advisory Vote 15 | 45  | 3  | 1  | Total        | NP    | Maintained        | 220        | 
| ADAIR    | Advisory Vote 15 | 45  | 3  | 1  | Total        | NP    | Registered Voters | 519        | 
| ADAIR    | Advisory Vote 15 | 45  | 3  | 1  | Total        | NP    | Repealed          | 222        | 
| ADAIR    | Advisory Vote 15 | 45  | 3  | 1  | Total        | NP    | Times Blank Voted | 43         | 
```