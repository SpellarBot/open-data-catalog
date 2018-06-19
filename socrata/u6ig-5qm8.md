# 2012 General - Election Results by precinct (complete eCanvass dataset)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2012-general-election-ecanvass-d5fac) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/u6ig-5qm8) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/u6ig-5qm8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/u6ig-5qm8/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | u6ig-5qm8 |
| Name | 2012 General - Election Results by precinct (complete eCanvass dataset) |
| Attribution | King County Elections |
| Category | Election results |
| Tags | 2012, 2012 general, general, elections, results, precinct, ecanvass |
| Created | 2012-12-01T00:53:32Z |
| Publication Date | 2012-12-04T22:15:22Z |

## Description

November 2012 general election; final/official results by precinct.

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
Value = 2012
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = cc,cg
```

## Data Commands

```ls
series e:u6ig-5qm8 d:2012-01-01T00:00:00.000Z t:precinct=ADAIR t:countertype="Bob Ferguson" t:countergroup=Total t:party=Dem t:race="Attorney General  partisan office" m:leg=45 m:sumofcount=367

series e:u6ig-5qm8 d:2012-01-01T00:00:00.000Z t:precinct=ADAIR t:countertype="Reagan Dunn" t:countergroup=Total t:party=Rep t:race="Attorney General  partisan office" m:leg=45 m:sumofcount=418

series e:u6ig-5qm8 d:2012-01-01T00:00:00.000Z t:precinct=ADAIR t:countertype="Registered Voters" t:countergroup=Total t:party=NP t:race="Attorney General  partisan office" m:leg=45 m:sumofcount=856
```

## Meta Commands

```ls
metric m:leg p:integer l:LEG t:dataTypeName=number

metric m:sumofcount p:integer l:SumOfCount t:dataTypeName=number

entity e:u6ig-5qm8 l:"2012 General - Election Results by precinct (complete eCanvass dataset)" t:attribution="King County Elections" t:url=https://data.kingcounty.gov/api/views/u6ig-5qm8

property e:u6ig-5qm8 t:meta.view v:id=u6ig-5qm8 v:category="Election results" v:attributionLink=http://kingcounty.gov/elections/results v:averageRating=0 v:name="2012 General - Election Results by precinct (complete eCanvass dataset)" v:attribution="King County Elections"

property e:u6ig-5qm8 t:meta.view.license v:name="Public Domain"

property e:u6ig-5qm8 t:meta.view.owner v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:displayName="Kathy Gill"

property e:u6ig-5qm8 t:meta.view.tableauthor v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:roleName=publisher v:displayName="Kathy Gill"
```

## Top Records

```ls
| precinct | race                             | leg | cc | cg | countergroup | party | countertype       | sumofcount | 
| ======== | ================================ | === | == | == | ============ | ===== | ================= | ========== | 
| ADAIR    | Attorney General partisan office | 45  | 3  | 1  | Total        | Dem   | Bob Ferguson      | 367        | 
| ADAIR    | Attorney General partisan office | 45  | 3  | 1  | Total        | Rep   | Reagan Dunn       | 418        | 
| ADAIR    | Attorney General partisan office | 45  | 3  | 1  | Total        | NP    | Registered Voters | 856        | 
| ADAIR    | Attorney General partisan office | 45  | 3  | 1  | Total        | NP    | Times Blank Voted | 24         | 
| ADAIR    | Attorney General partisan office | 45  | 3  | 1  | Total        | NP    | Times Counted     | 809        | 
| ADAIR    | Attorney General partisan office | 45  | 3  | 1  | Total        | NP    | Times Over Voted  | 0          | 
| ADAIR    | Attorney General partisan office | 45  | 3  | 1  | Total        | NP    | Write-in          | 0          | 
| ALDARRA  | Attorney General partisan office | 5   | 3  | 8  | Total        | Dem   | Bob Ferguson      | 283        | 
| ALDARRA  | Attorney General partisan office | 5   | 3  | 8  | Total        | Rep   | Reagan Dunn       | 296        | 
| ALDARRA  | Attorney General partisan office | 5   | 3  | 8  | Total        | NP    | Registered Voters | 733        | 
```