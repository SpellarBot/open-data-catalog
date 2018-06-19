# 2015 General - Election Results by precinct (complete eCanvass dataset)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2015-general-election-results-by-precinct-complete-ecanvass-dataset) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/kncv-f6kh) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/kncv-f6kh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/kncv-f6kh/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | kncv-f6kh |
| Name | 2015 General - Election Results by precinct (complete eCanvass dataset) |
| Attribution | King County Elections |
| Category | Election results |
| Tags | 2015, 2015 general, general, elections, results, precinct, ecanvass |
| Created | 2017-01-25T00:54:14Z |
| Publication Date | 2017-01-25T01:10:02Z |

## Description

November 2015 general election; final/official results by precinct.

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
series e:kncv-f6kh d:2015-01-01T00:00:00.000Z t:precinct=ADAIR t:countertype=Maintained t:countergroup=Total t:party=NP t:race="Advisory Vote No. 10" m:leg=45 m:sumofcount=178

series e:kncv-f6kh d:2015-01-01T00:00:00.000Z t:precinct=ADAIR t:countertype="Registered Voters" t:countergroup=Total t:party=NP t:race="Advisory Vote No. 10" m:leg=45 m:sumofcount=503

series e:kncv-f6kh d:2015-01-01T00:00:00.000Z t:precinct=ADAIR t:countertype=Repealed t:countergroup=Total t:party=NP t:race="Advisory Vote No. 10" m:leg=45 m:sumofcount=133
```

## Meta Commands

```ls
metric m:leg p:integer l:LEG t:dataTypeName=number

metric m:sumofcount p:integer l:SumOfCount t:dataTypeName=number

entity e:kncv-f6kh l:"2015 General - Election Results by precinct (complete eCanvass dataset)" t:attribution="King County Elections" t:url=https://data.kingcounty.gov/api/views/kncv-f6kh

property e:kncv-f6kh t:meta.view v:id=kncv-f6kh v:category="Election results" v:attributionLink=http://kingcounty.gov/elections/results v:averageRating=0 v:name="2015 General - Election Results by precinct (complete eCanvass dataset)" v:attribution="King County Elections"

property e:kncv-f6kh t:meta.view.license v:name="Public Domain"

property e:kncv-f6kh t:meta.view.owner v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:displayName="Kathy Gill"

property e:kncv-f6kh t:meta.view.tableauthor v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:roleName=publisher v:displayName="Kathy Gill"
```

## Top Records

```ls
| precinct | race                 | leg | cc | cg | countergroup | party | countertype       | sumofcount | 
| ======== | ==================== | === | == | == | ============ | ===== | ================= | ========== | 
| ADAIR    | Advisory Vote No. 10 | 45  | 3  | 1  | Total        | NP    | Maintained        | 178        | 
| ADAIR    | Advisory Vote No. 10 | 45  | 3  | 1  | Total        | NP    | Registered Voters | 503        | 
| ADAIR    | Advisory Vote No. 10 | 45  | 3  | 1  | Total        | NP    | Repealed          | 133        | 
| ADAIR    | Advisory Vote No. 10 | 45  | 3  | 1  | Total        | NP    | Times Blank Voted | 16         | 
| ADAIR    | Advisory Vote No. 10 | 45  | 3  | 1  | Total        | NP    | Times Counted     | 327        | 
| ADAIR    | Advisory Vote No. 10 | 45  | 3  | 1  | Total        | NP    | Times Over Voted  | 0          | 
| ADAIR    | Advisory Vote No. 11 | 45  | 3  | 1  | Total        | NP    | Maintained        | 200        | 
| ADAIR    | Advisory Vote No. 11 | 45  | 3  | 1  | Total        | NP    | Registered Voters | 503        | 
| ADAIR    | Advisory Vote No. 11 | 45  | 3  | 1  | Total        | NP    | Repealed          | 116        | 
| ADAIR    | Advisory Vote No. 11 | 45  | 3  | 1  | Total        | NP    | Times Blank Voted | 11         | 
```