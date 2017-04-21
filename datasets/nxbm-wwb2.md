# 2013 Special June - Election Results by precinct (complete eCanvass dataset)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2013-special-june-election-results-by-precinct-complete-ecanvass-dataset) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/nxbm-wwb2) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/nxbm-wwb2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/nxbm-wwb2/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | nxbm-wwb2 |
| Name | 2013 Special June - Election Results by precinct (complete eCanvass dataset) |
| Attribution | King County Elections |
| Category | Election results |
| Tags | 2013, 2013 special, special, elections, results, precinct, ecanvass |
| Created | 2017-01-27T22:21:22Z |
| Publication Date | 2017-01-27T22:23:24Z |

## Description

June 2013 special election; final/official results by precinct.

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type | Render Type |
| ======== | ============== | ============ | ============ | ========= | =========== |
| Yes      | series tag     | precinct     | Precinct     | text      | text        |
| Yes      | series tag     | race         | Race         | text      | text        |
| Yes      | numeric metric | leg          | LEG          | number    | number      |
| Yes      | series tag     | party        | Party        | text      | text        |
| Yes      | series tag     | countergroup | CounterGroup | text      | text        |
| Yes      | series tag     | countertype  | CounterType  | text      | text        |
| Yes      | numeric metric | sumofcount   | SumOfCount   | number    | number      |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:nxbm-wwb2 d:2013-01-01T00:00:00.000Z t:precinct="PAC 30-0885" t:countertype="Recall Yes" t:countergroup=Total t:party=NP t:race="Ballot Synopsis of Recall Charges Against Mayor Cy Sun, City of Pacific
City of Pacific Mayor Cy Sun Response to the Recall Charges" m:leg=30 m:sumofcount=221

series e:nxbm-wwb2 d:2013-01-01T00:00:00.000Z t:precinct="PAC 30-0885" t:countertype="Recall No" t:countergroup=Total t:party=NP t:race="Ballot Synopsis of Recall Charges Against Mayor Cy Sun, City of Pacific
City of Pacific Mayor Cy Sun Response to the Recall Charges" m:leg=30 m:sumofcount=160

series e:nxbm-wwb2 d:2013-01-01T00:00:00.000Z t:precinct="PAC 30-0885" t:countertype="Times Blank Voted" t:countergroup=Total t:party=NP t:race="Ballot Synopsis of Recall Charges Against Mayor Cy Sun, City of Pacific
City of Pacific Mayor Cy Sun Response to the Recall Charges" m:leg=30 m:sumofcount=1
```

## Meta Commands

```ls
metric m:leg p:integer l:LEG t:dataTypeName=number

metric m:sumofcount p:integer l:SumOfCount t:dataTypeName=number

entity e:nxbm-wwb2 l:"2013 Special June - Election Results by precinct (complete eCanvass dataset)" t:attribution="King County Elections" t:url=https://data.kingcounty.gov/api/views/nxbm-wwb2

property e:nxbm-wwb2 t:meta.view v:id=nxbm-wwb2 v:category="Election results" v:attributionLink=http://kingcounty.gov/elections/results v:averageRating=0 v:name="2013 Special June - Election Results by precinct (complete eCanvass dataset)" v:attribution="King County Elections"

property e:nxbm-wwb2 t:meta.view.license v:name="Public Domain"

property e:nxbm-wwb2 t:meta.view.owner v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:displayName="Kathy Gill"

property e:nxbm-wwb2 t:meta.view.tableauthor v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:roleName=publisher v:displayName="Kathy Gill"
```

## Top Records

```ls
| precinct    | race                                                                                                                                | leg | party | countergroup | countertype       | sumofcount | 
| =========== | =================================================================================================================================== | === | ===== | ============ | ================= | ========== | 
| PAC 30-0885 | Ballot Synopsis of Recall Charges Against Mayor Cy Sun, City of Pacific City of Pacific Mayor Cy Sun Response to the Recall Charges | 30  | NP    | Total        | Recall Yes        | 221        | 
| PAC 30-0885 | Ballot Synopsis of Recall Charges Against Mayor Cy Sun, City of Pacific City of Pacific Mayor Cy Sun Response to the Recall Charges | 30  | NP    | Total        | Recall No         | 160        | 
| PAC 30-0885 | Ballot Synopsis of Recall Charges Against Mayor Cy Sun, City of Pacific City of Pacific Mayor Cy Sun Response to the Recall Charges | 30  | NP    | Total        | Times Blank Voted | 1          | 
| PAC 30-0885 | Ballot Synopsis of Recall Charges Against Mayor Cy Sun, City of Pacific City of Pacific Mayor Cy Sun Response to the Recall Charges | 30  | NP    | Total        | Times Over Voted  | 0          | 
| PAC 30-0885 | Ballot Synopsis of Recall Charges Against Mayor Cy Sun, City of Pacific City of Pacific Mayor Cy Sun Response to the Recall Charges | 30  | NP    | Total        | Times Counted     | 382        | 
| PAC 30-0885 | Ballot Synopsis of Recall Charges Against Mayor Cy Sun, City of Pacific City of Pacific Mayor Cy Sun Response to the Recall Charges | 30  | NP    | Total        | Registered Voters | 807        | 
| PAC 30-0886 | Ballot Synopsis of Recall Charges Against Mayor Cy Sun, City of Pacific City of Pacific Mayor Cy Sun Response to the Recall Charges | 30  | NP    | Total        | Recall Yes        | 272        | 
| PAC 30-0886 | Ballot Synopsis of Recall Charges Against Mayor Cy Sun, City of Pacific City of Pacific Mayor Cy Sun Response to the Recall Charges | 30  | NP    | Total        | Recall No         | 85         | 
| PAC 30-0886 | Ballot Synopsis of Recall Charges Against Mayor Cy Sun, City of Pacific City of Pacific Mayor Cy Sun Response to the Recall Charges | 30  | NP    | Total        | Times Blank Voted | 0          | 
| PAC 30-0886 | Ballot Synopsis of Recall Charges Against Mayor Cy Sun, City of Pacific City of Pacific Mayor Cy Sun Response to the Recall Charges | 30  | NP    | Total        | Times Over Voted  | 0          | 
```