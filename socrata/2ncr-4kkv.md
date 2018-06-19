# 2011 Primary - Election Results by precinct (complete eCanvass dataset)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cumulative-canvass-7e59a) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/2ncr-4kkv) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/2ncr-4kkv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/2ncr-4kkv/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | 2ncr-4kkv |
| Name | 2011 Primary - Election Results by precinct (complete eCanvass dataset) |
| Attribution | King County Elections |
| Category | Election results |
| Tags | 2011, 2011 primary, primary, elections, results, precinct, ecanvass |
| Created | 2011-09-01T23:05:36Z |
| Publication Date | 2011-09-01T23:05:36Z |

## Description

August 2011 primary election; final/official results by precinct.

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type | Render Type |
| ======== | ============== | ============ | ============ | ========= | =========== |
| Yes      | series tag     | precinct     | Precinct     | text      | text        |
| Yes      | series tag     | race         | Race         | text      | text        |
| Yes      | series tag     | leg          | LEG          | text      | text        |
| No       |                | cc           | CC           | text      | text        |
| No       |                | cg           | CG           | number    | text        |
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
series e:2ncr-4kkv d:2011-01-01T00:00:00.000Z t:precinct="AUB 47-0056" t:leg=47 t:countertype="Times Over Voted" t:countergroup=Total t:party=NP t:race="Court of Appeals, Division No. 1, District No. 1" m:sumofcount=0

series e:2ncr-4kkv d:2011-01-01T00:00:00.000Z t:precinct="B-D 05-2407" t:leg=5 t:countertype=Write-in t:countergroup=Total t:party=NP t:race="Public Hospital District No. 1 Commissioner District No. 1 nonpartisan office" m:sumofcount=0

series e:2ncr-4kkv d:2011-01-01T00:00:00.000Z t:precinct="BEL 48-0134" t:leg=48 t:countertype="Times Counted" t:countergroup=Total t:party=NP t:race="Court of Appeals, Division No. 1, District No. 1" m:sumofcount=96
```

## Meta Commands

```ls
metric m:sumofcount p:float l:SumOfCount t:dataTypeName=number

entity e:2ncr-4kkv l:"2011 Primary - Election Results by precinct (complete eCanvass dataset)" t:attribution="King County Elections" t:url=https://data.kingcounty.gov/api/views/2ncr-4kkv

property e:2ncr-4kkv t:meta.view v:id=2ncr-4kkv v:category="Election results" v:attributionLink=http://www.kingcounty.gov/elections v:averageRating=0 v:name="2011 Primary - Election Results by precinct (complete eCanvass dataset)" v:attribution="King County Elections"

property e:2ncr-4kkv t:meta.view.license v:name="Public Domain"

property e:2ncr-4kkv t:meta.view.owner v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:displayName="King County Webteam"

property e:2ncr-4kkv t:meta.view.tableauthor v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:roleName=administrator v:displayName="King County Webteam"
```

## Top Records

```ls
| precinct    | race                                                                          | leg | cc | cg | countergroup | party | countertype       | sumofcount | 
| =========== | ============================================================================= | === | == | == | ============ | ===== | ================= | ========== | 
| AUB 47-0056 | Court of Appeals, Division No. 1, District No. 1                              | 47  | 7  | 9  | Total        | NP    | Times Over Voted  | 0.00       | 
| B-D 05-2407 | Public Hospital District No. 1 Commissioner District No. 1 nonpartisan office | 5   | 9  | 8  | Total        | NP    | Write-in          | 0.00       | 
| BEL 48-0134 | Court of Appeals, Division No. 1, District No. 1                              | 48  | 6  | 8  | Total        | NP    | Times Counted     | 96.00      | 
| BUR 11-0009 | City of Burien Council Position No. 2 nonpartisan office                      | 11  | 8  | 7  | Total        | NP    | Registered Voters | 220.00     | 
| BUR 11-0033 | Court of Appeals, Division No. 1, District No. 1                              | 11  | 8  | 7  | Total        | NP    | Times Over Voted  | 0.00       | 
| BUR 11-0913 | Court of Appeals, Division No. 1, District No. 1                              | 11  | 8  | 7  | Total        | NP    | Times Over Voted  | 0.00       | 
| BUR 33-0476 | Court of Appeals, Division No. 1, District No. 1                              | 33  | 8  | 9  | Total        | NP    | Times Over Voted  | 0.00       | 
| BUR 34-0402 | Court of Appeals, Division No. 1, District No. 1                              | 34  | 8  | 9  | Total        | NP    | Write-in          | 1.00       | 
| BUR 34-0848 | Court of Appeals, Division No. 1, District No. 1                              | 34  | 8  | 9  | Total        | NP    | Times Over Voted  | 0.00       | 
| BUR 34-1192 | City of Burien Council Position No. 4 nonpartisan office                      | 34  | 8  | 9  | Total        | NP    | Write-in          | 3.00       | 
```