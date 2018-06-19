# 2011 General - Election Results by precinct (complete eCanvass dataset)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cumulative-canvass-november-2011-general-election-31723) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/hgu2-qaye) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/hgu2-qaye/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/hgu2-qaye/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | hgu2-qaye |
| Name | 2011 General - Election Results by precinct (complete eCanvass dataset) |
| Attribution | King County Elections |
| Category | Election results |
| Tags | 2011, 2011 general, general, elections, results, precinct, ecanvass |
| Created | 2011-12-03T00:10:05Z |
| Publication Date | 2011-12-03T00:23:14Z |

## Description

November 2011 general election; final/official results by precinct.

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
Value = 2011
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = cc,cg
```

## Data Commands

```ls
series e:hgu2-qaye d:2011-01-01T00:00:00.000Z t:precinct=ADAIR t:countertype="Lloyd Hara" t:countergroup=Total t:party=NP t:race="Assessor  nonpartisan office" m:leg=45 m:sumofcount=429

series e:hgu2-qaye d:2011-01-01T00:00:00.000Z t:precinct=ADAIR t:countertype="Registered Voters" t:countergroup=Total t:party=NP t:race="Assessor  nonpartisan office" m:leg=45 m:sumofcount=823

series e:hgu2-qaye d:2011-01-01T00:00:00.000Z t:precinct=ADAIR t:countertype="Times Blank Voted" t:countergroup=Total t:party=NP t:race="Assessor  nonpartisan office" m:leg=45 m:sumofcount=245
```

## Meta Commands

```ls
metric m:leg p:integer l:LEG t:dataTypeName=number

metric m:sumofcount p:float l:SumOfCount t:dataTypeName=number

entity e:hgu2-qaye l:"2011 General - Election Results by precinct (complete eCanvass dataset)" t:attribution="King County Elections" t:url=https://data.kingcounty.gov/api/views/hgu2-qaye

property e:hgu2-qaye t:meta.view v:id=hgu2-qaye v:category="Election results" v:attributionLink=http://www.kingcounty.gov/elections v:averageRating=0 v:name="2011 General - Election Results by precinct (complete eCanvass dataset)" v:attribution="King County Elections"

property e:hgu2-qaye t:meta.view.license v:name="Public Domain"

property e:hgu2-qaye t:meta.view.owner v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:displayName="King County Webteam"

property e:hgu2-qaye t:meta.view.tableauthor v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:roleName=administrator v:displayName="King County Webteam"
```

## Top Records

```ls
| precinct | race                                                                                     | leg | cc | cg | countergroup | party | countertype       | sumofcount | 
| ======== | ======================================================================================== | === | == | == | ============ | ===== | ================= | ========== | 
| ADAIR    | Assessor nonpartisan office                                                              | 45  | 3  | 8  | Total        | NP    | Lloyd Hara        | 429.00     | 
| ADAIR    | Assessor nonpartisan office                                                              | 45  | 3  | 8  | Total        | NP    | Registered Voters | 823.00     | 
| ADAIR    | Assessor nonpartisan office                                                              | 45  | 3  | 8  | Total        | NP    | Times Blank Voted | 245.00     | 
| ADAIR    | Assessor nonpartisan office                                                              | 45  | 3  | 8  | Total        | NP    | Times Counted     | 674.00     | 
| ADAIR    | Assessor nonpartisan office                                                              | 45  | 3  | 8  | Total        | NP    | Times Over Voted  | 0.00       | 
| ADAIR    | Assessor nonpartisan office                                                              | 45  | 3  | 8  | Total        | NP    | Write-in          | 0.00       | 
| ADAIR    | Court of Appeals, Division No. 1, District No. 1 Judge Position No. 2 nonpartisan office | 45  | 3  | 8  | Total        | NP    | Michael Spearman  | 384.00     | 
| ADAIR    | Court of Appeals, Division No. 1, District No. 1 Judge Position No. 2 nonpartisan office | 45  | 3  | 8  | Total        | NP    | Registered Voters | 823.00     | 
| ADAIR    | Court of Appeals, Division No. 1, District No. 1 Judge Position No. 2 nonpartisan office | 45  | 3  | 8  | Total        | NP    | Times Blank Voted | 286.00     | 
| ADAIR    | Court of Appeals, Division No. 1, District No. 1 Judge Position No. 2 nonpartisan office | 45  | 3  | 8  | Total        | NP    | Times Counted     | 674.00     | 
```