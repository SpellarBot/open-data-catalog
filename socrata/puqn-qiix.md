# 2012 Primary - Election Results by precinct (complete eCanvass dataset)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/master-cumulative-canvass-august-2012-primary-dc59b) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/puqn-qiix) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/puqn-qiix/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/puqn-qiix/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | puqn-qiix |
| Name | 2012 Primary - Election Results by precinct (complete eCanvass dataset) |
| Attribution | King County Elections |
| Category | Election results |
| Tags | 2012, 2012 primary, primary, elections, results, precinct, ecanvass |
| Created | 2012-08-25T00:48:54Z |
| Publication Date | 2012-08-25T00:53:33Z |

## Description

August 2012 primary election; final/official results by precinct.

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type | Render Type |
| ======== | ============== | ============ | ============ | ========= | =========== |
| Yes      | series tag     | race         | Race         | text      | text        |
| Yes      | series tag     | precinct     | Precinct     | text      | text        |
| Yes      | numeric metric | leg          | LEG          | number    | number      |
| No       |                | cc           | CC           | number    | number      |
| No       |                | cg           | CG           | number    | number      |
| Yes      | series tag     | countergroup | CounterGroup | text      | text        |
| Yes      | series tag     | party        | Party        | text      | text        |
| Yes      | series tag     | countertype  | CounterType  | text      | text        |
| Yes      | numeric metric | count        | Count        | number    | number      |
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
series e:puqn-qiix d:2012-01-01T00:00:00.000Z t:precinct=ADAIR t:countertype="Bob Ferguson" t:countergroup=Total t:party=Dem t:race="Attorney General  partisan office" m:leg=45 m:count=224

series e:puqn-qiix d:2012-01-01T00:00:00.000Z t:precinct=ADAIR t:countertype="Reagan Dunn" t:countergroup=Total t:party=Rep t:race="Attorney General  partisan office" m:leg=45 m:count=308

series e:puqn-qiix d:2012-01-01T00:00:00.000Z t:precinct=ADAIR t:countertype="Registered Voters" t:countergroup=Total t:party=NP t:race="Attorney General  partisan office" m:leg=45 m:count=853
```

## Meta Commands

```ls
metric m:leg p:integer l:LEG t:dataTypeName=number

metric m:count p:integer l:Count t:dataTypeName=number

entity e:puqn-qiix l:"2012 Primary - Election Results by precinct (complete eCanvass dataset)" t:attribution="King County Elections" t:url=https://data.kingcounty.gov/api/views/puqn-qiix

property e:puqn-qiix t:meta.view v:id=puqn-qiix v:category="Election results" v:attributionLink=http://kingcounty.gov/elections v:averageRating=0 v:name="2012 Primary - Election Results by precinct (complete eCanvass dataset)" v:attribution="King County Elections"

property e:puqn-qiix t:meta.view.license v:name="Public Domain"

property e:puqn-qiix t:meta.view.owner v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:displayName="Kathy Gill"

property e:puqn-qiix t:meta.view.tableauthor v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:roleName=publisher v:displayName="Kathy Gill"
```

## Top Records

```ls
| race                             | precinct | leg | cc | cg | countergroup | party | countertype       | count | 
| ================================ | ======== | === | == | == | ============ | ===== | ================= | ===== | 
| Attorney General partisan office | ADAIR    | 45  | 3  | 1  | Total        | Dem   | Bob Ferguson      | 224   | 
| Attorney General partisan office | ADAIR    | 45  | 3  | 1  | Total        | Rep   | Reagan Dunn       | 308   | 
| Attorney General partisan office | ADAIR    | 45  | 3  | 1  | Total        | NP    | Registered Voters | 853   | 
| Attorney General partisan office | ADAIR    | 45  | 3  | 1  | Total        | Rep   | Stephen Pidgeon   | 44    | 
| Attorney General partisan office | ADAIR    | 45  | 3  | 1  | Total        | NP    | Times Blank Voted | 21    | 
| Attorney General partisan office | ADAIR    | 45  | 3  | 1  | Total        | NP    | Times Counted     | 597   | 
| Attorney General partisan office | ADAIR    | 45  | 3  | 1  | Total        | NP    | Times Over Voted  | 0     | 
| Attorney General partisan office | ADAIR    | 45  | 3  | 1  | Total        | NP    | Write-in          | 0     | 
| Attorney General partisan office | ALDARRA  | 5   | 3  | 8  | Total        | Dem   | Bob Ferguson      | 109   | 
| Attorney General partisan office | ALDARRA  | 5   | 3  | 8  | Total        | Rep   | Reagan Dunn       | 143   | 
```