# 2014 Special April - Election Results by precinct (complete eCanvass dataset)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2014-special-april-election-results-by-precinct-complete-ecanvass-dataset) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/q52v-pcg7) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/q52v-pcg7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/q52v-pcg7/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | q52v-pcg7 |
| Name | 2014 Special April - Election Results by precinct (complete eCanvass dataset) |
| Attribution | King County Elections |
| Category | Election results |
| Tags | 2014, 2014 special, special, elections, results, precinct, ecanvass |
| Created | 2017-01-25T01:49:49Z |
| Publication Date | 2017-01-25T01:57:42Z |

## Description

April 2014 special election; final/official results by precinct.

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
series e:q52v-pcg7 d:2014-01-01T00:00:00.000Z t:precinct=ADAIR t:countertype=No t:countergroup=Total t:party=NP t:race="King County Transportation District Proposition No. 1 Sales and Use Tax and Vehicle Fee for Transportation Improvements" m:leg=45 m:sumofcount=426

series e:q52v-pcg7 d:2014-01-01T00:00:00.000Z t:precinct=ADAIR t:countertype="Registered Voters" t:countergroup=Total t:party=NP t:race="King County Transportation District Proposition No. 1 Sales and Use Tax and Vehicle Fee for Transportation Improvements" m:leg=45 m:sumofcount=900

series e:q52v-pcg7 d:2014-01-01T00:00:00.000Z t:precinct=ADAIR t:countertype="Times Blank Voted" t:countergroup=Total t:party=NP t:race="King County Transportation District Proposition No. 1 Sales and Use Tax and Vehicle Fee for Transportation Improvements" m:leg=45 m:sumofcount=0
```

## Meta Commands

```ls
metric m:leg p:integer l:LEG t:dataTypeName=number

metric m:sumofcount p:integer l:SumOfCount t:dataTypeName=number

entity e:q52v-pcg7 l:"2014 Special April - Election Results by precinct (complete eCanvass dataset)" t:attribution="King County Elections" t:url=https://data.kingcounty.gov/api/views/q52v-pcg7

property e:q52v-pcg7 t:meta.view v:id=q52v-pcg7 v:category="Election results" v:attributionLink=http://kingcounty.gov/elections/results v:averageRating=0 v:name="2014 Special April - Election Results by precinct (complete eCanvass dataset)" v:attribution="King County Elections"

property e:q52v-pcg7 t:meta.view.license v:name="Public Domain"

property e:q52v-pcg7 t:meta.view.owner v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:displayName="Kathy Gill"

property e:q52v-pcg7 t:meta.view.tableauthor v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:roleName=publisher v:displayName="Kathy Gill"
```

## Top Records

```ls
| precinct | race                                                                                                                    | leg | cc | cg | countergroup | party | countertype       | sumofcount | 
| ======== | ======================================================================================================================= | === | == | == | ============ | ===== | ================= | ========== | 
| ADAIR    | King County Transportation District Proposition No. 1 Sales and Use Tax and Vehicle Fee for Transportation Improvements | 45  | 3  | 1  | Total        | NP    | No                | 426        | 
| ADAIR    | King County Transportation District Proposition No. 1 Sales and Use Tax and Vehicle Fee for Transportation Improvements | 45  | 3  | 1  | Total        | NP    | Registered Voters | 900        | 
| ADAIR    | King County Transportation District Proposition No. 1 Sales and Use Tax and Vehicle Fee for Transportation Improvements | 45  | 3  | 1  | Total        | NP    | Times Blank Voted | 0          | 
| ADAIR    | King County Transportation District Proposition No. 1 Sales and Use Tax and Vehicle Fee for Transportation Improvements | 45  | 3  | 1  | Total        | NP    | Times Counted     | 612        | 
| ADAIR    | King County Transportation District Proposition No. 1 Sales and Use Tax and Vehicle Fee for Transportation Improvements | 45  | 3  | 1  | Total        | NP    | Times Over Voted  | 0          | 
| ADAIR    | King County Transportation District Proposition No. 1 Sales and Use Tax and Vehicle Fee for Transportation Improvements | 45  | 3  | 1  | Total        | NP    | Yes               | 186        | 
| ADAIR    | Lake Washington School District No. 414 Proposition No. 1 General Obligation Bonds - $404,000,000                       | 45  | 3  | 1  | Total        | NP    | Approved          | 122        | 
| ADAIR    | Lake Washington School District No. 414 Proposition No. 1 General Obligation Bonds - $404,000,000                       | 45  | 3  | 1  | Total        | NP    | Registered Voters | 516        | 
| ADAIR    | Lake Washington School District No. 414 Proposition No. 1 General Obligation Bonds - $404,000,000                       | 45  | 3  | 1  | Total        | NP    | Rejected          | 237        | 
| ADAIR    | Lake Washington School District No. 414 Proposition No. 1 General Obligation Bonds - $404,000,000                       | 45  | 3  | 1  | Total        | NP    | Times Blank Voted | 0          | 
```