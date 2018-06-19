# 2016 Presidential Primary - Election Results by precinct (complete eCanvass dataset)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2016-presidential-primary-election-results-by-precinct-complete-ecanvass-dataset) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/eutd-6iwc) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/eutd-6iwc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/eutd-6iwc/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | eutd-6iwc |
| Name | 2016 Presidential Primary - Election Results by precinct (complete eCanvass dataset) |
| Attribution | King County Elections |
| Category | Election results |
| Tags | 2016, 2016 primary, primary, elections, results, precinct, ecanvass |
| Created | 2017-01-25T00:29:55Z |
| Publication Date | 2017-01-25T00:31:21Z |

## Description

May 2016 presidential primary election; final/official results by precinct.

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
series e:eutd-6iwc d:2016-01-01T00:00:00.000Z t:precinct=ADAIR t:countertype="Bernie Sanders" t:countergroup=Total t:party=NP t:race="Democratic Party" m:leg=45 m:sumofcount=24

series e:eutd-6iwc d:2016-01-01T00:00:00.000Z t:precinct=ADAIR t:countertype="Hillary Clinton" t:countergroup=Total t:party=NP t:race="Democratic Party" m:leg=45 m:sumofcount=117

series e:eutd-6iwc d:2016-01-01T00:00:00.000Z t:precinct=ADAIR t:countertype="Registered Voters" t:countergroup=Total t:party=NP t:race="Democratic Party" m:leg=45 m:sumofcount=503
```

## Meta Commands

```ls
metric m:leg p:integer l:LEG t:dataTypeName=number

metric m:sumofcount p:integer l:SumOfCount t:dataTypeName=number

entity e:eutd-6iwc l:"2016 Presidential Primary - Election Results by precinct (complete eCanvass dataset)" t:attribution="King County Elections" t:url=https://data.kingcounty.gov/api/views/eutd-6iwc

property e:eutd-6iwc t:meta.view v:id=eutd-6iwc v:category="Election results" v:attributionLink=http://kingcounty.gov/elections/results v:averageRating=0 v:name="2016 Presidential Primary - Election Results by precinct (complete eCanvass dataset)" v:attribution="King County Elections"

property e:eutd-6iwc t:meta.view.license v:name="Public Domain"

property e:eutd-6iwc t:meta.view.owner v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:displayName="Kathy Gill"

property e:eutd-6iwc t:meta.view.tableauthor v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:roleName=publisher v:displayName="Kathy Gill"
```

## Top Records

```ls
| precinct | race             | leg | cc | cg | countergroup | party | countertype       | sumofcount | 
| ======== | ================ | === | == | == | ============ | ===== | ================= | ========== | 
| ADAIR    | Democratic Party | 45  | 3  | 1  | Total        | NP    | Bernie Sanders    | 24         | 
| ADAIR    | Democratic Party | 45  | 3  | 1  | Total        | NP    | Hillary Clinton   | 117        | 
| ADAIR    | Democratic Party | 45  | 3  | 1  | Total        | NP    | Registered Voters | 503        | 
| ADAIR    | Democratic Party | 45  | 3  | 1  | Total        | NP    | Times Blank Voted | 141        | 
| ADAIR    | Democratic Party | 45  | 3  | 1  | Total        | NP    | Times Counted     | 282        | 
| ADAIR    | Democratic Party | 45  | 3  | 1  | Total        | NP    | Times Over Voted  | 0          | 
| ADAIR    | Democratic Party | 45  | 3  | 1  | Total        | NP    | Write-In          | 0          | 
| ADAIR    | Republican Party | 45  | 3  | 1  | Total        | NP    | Ben Carson        | 1          | 
| ADAIR    | Republican Party | 45  | 3  | 1  | Total        | NP    | Donald J. Trump   | 101        | 
| ADAIR    | Republican Party | 45  | 3  | 1  | Total        | NP    | John R. Kasich    | 28         | 
```