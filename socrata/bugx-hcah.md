# 2012 Primary - Election Results - PCO

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/master-cumulative-canvass-pco-august-2012-primary-79a65) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/bugx-hcah) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/bugx-hcah/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/bugx-hcah/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | bugx-hcah |
| Name | 2012 Primary - Election Results - PCO |
| Attribution | King County Elections |
| Category | Election results |
| Tags | 2012, 2012 primary, primary, elections, results, precinct, ecanvass, pco |
| Created | 2012-08-28T20:06:03Z |
| Publication Date | 2012-08-28T20:10:12Z |

## Description

August 2012 primary election; final daily results report for PCO contests.

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
series e:bugx-hcah d:2012-01-01T00:00:00.000Z t:precinct="ALG 30-0013" t:countertype="Registered Voters" t:countergroup=Total t:party=NP t:race="Precinct Committee Officer ALG 30-0013 PCO" m:leg=30 m:sumofcount=449

series e:bugx-hcah d:2012-01-01T00:00:00.000Z t:precinct="ALG 30-0013" t:countertype="Times Blank Voted" t:countergroup=Total t:party=NP t:race="Precinct Committee Officer ALG 30-0013 PCO" m:leg=30 m:sumofcount=53

series e:bugx-hcah d:2012-01-01T00:00:00.000Z t:precinct="ALG 30-0013" t:countertype="Times Counted" t:countergroup=Total t:party=NP t:race="Precinct Committee Officer ALG 30-0013 PCO" m:leg=30 m:sumofcount=104
```

## Meta Commands

```ls
metric m:leg p:integer l:LEG t:dataTypeName=number

metric m:sumofcount p:integer l:SumOfCount t:dataTypeName=number

entity e:bugx-hcah l:"2012 Primary - Election Results - PCO" t:attribution="King County Elections" t:url=https://data.kingcounty.gov/api/views/bugx-hcah

property e:bugx-hcah t:meta.view v:id=bugx-hcah v:category="Election results" v:attributionLink=http://kingcounty.gov/elections v:averageRating=0 v:name="2012 Primary - Election Results - PCO" v:attribution="King County Elections"

property e:bugx-hcah t:meta.view.license v:name="Public Domain"

property e:bugx-hcah t:meta.view.owner v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:displayName="Kathy Gill"

property e:bugx-hcah t:meta.view.tableauthor v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:roleName=publisher v:displayName="Kathy Gill"
```

## Top Records

```ls
| precinct    | race                                       | leg | cc | cg | countergroup | party | countertype            | sumofcount | 
| =========== | ========================================== | === | == | == | ============ | ===== | ====================== | ========== | 
| ALG 30-0013 | Precinct Committee Officer ALG 30-0013 PCO | 30  | 7  | 8  | Total        | NP    | Registered Voters      | 449        | 
| ALG 30-0013 | Precinct Committee Officer ALG 30-0013 PCO | 30  | 7  | 8  | Total        | NP    | Times Blank Voted      | 53         | 
| ALG 30-0013 | Precinct Committee Officer ALG 30-0013 PCO | 30  | 7  | 8  | Total        | NP    | Times Counted          | 104        | 
| ALG 30-0013 | Precinct Committee Officer ALG 30-0013 PCO | 30  | 7  | 8  | Total        | NP    | Times Over Voted       | 0          | 
| ALG 30-0013 | Precinct Committee Officer ALG 30-0013 PCO | 30  | 7  | 8  | Total        | RPC   | Autumn Davis - Rep     | 37         | 
| ALG 30-0013 | Precinct Committee Officer ALG 30-0013 PCO | 30  | 7  | 8  | Total        | RPC   | Deidre N. Lorenz - Rep | 14         | 
| ALPINE      | Precinct Committee Officer ALPINE PCO      | 5   | 3  | 1  | Total        | NP    | Registered Voters      | 554        | 
| ALPINE      | Precinct Committee Officer ALPINE PCO      | 5   | 3  | 1  | Total        | NP    | Times Blank Voted      | 112        | 
| ALPINE      | Precinct Committee Officer ALPINE PCO      | 5   | 3  | 1  | Total        | NP    | Times Counted          | 177        | 
| ALPINE      | Precinct Committee Officer ALPINE PCO      | 5   | 3  | 1  | Total        | NP    | Times Over Voted       | 0          | 
```