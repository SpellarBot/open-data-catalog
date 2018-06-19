# 2008 General - Absentee Election Results

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/election-results-november-4-2008-general-absentee-84843) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/r4pa-sjau) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/r4pa-sjau/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/r4pa-sjau/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | r4pa-sjau |
| Name | 2008 General - Absentee Election Results |
| Attribution | King County Elections |
| Category | Election results |
| Tags | 2008, 2008 general, general, elections, results |
| Created | 2011-02-23T17:07:10Z |
| Publication Date | 2011-04-17T00:03:09Z |

## Description

November 2008 general election; final/official absentee results.

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type | Render Type |
| ======== | ============== | ============ | ============ | ========= | =========== |
| Yes      | series tag     | race         | Race         | text      | text        |
| Yes      | series tag     | precinct     | Precinct     | text      | text        |
| No       |                | cc           | CC           | number    | number      |
| Yes      | numeric metric | leg          | LEG          | number    | number      |
| Yes      | numeric metric | cong         | CONG         | number    | number      |
| Yes      | series tag     | party        | Party        | text      | text        |
| Yes      | series tag     | countertype  | CounterType  | text      | text        |
| Yes      | series tag     | countergroup | CounterGroup | text      | text        |
| Yes      | numeric metric | count        | Count        | number    | number      |
```

## Time Field

```ls
Value = 2008
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = cc
```

## Data Commands

```ls
series e:r4pa-sjau d:2008-01-01T00:00:00.000Z t:precinct=CHALLENGER t:countertype=Write-in t:countergroup=Absentee t:party=NP t:race="State Treasurer" m:leg=5 m:count=0 m:cong=8

series e:r4pa-sjau d:2008-01-01T00:00:00.000Z t:precinct=CHALLENGER t:countertype="Times Counted" t:countergroup=Absentee t:party=NP t:race="State Auditor" m:leg=5 m:count=191 m:cong=8

series e:r4pa-sjau d:2008-01-01T00:00:00.000Z t:precinct=CHALLENGER t:countertype="Times Blank Voted" t:countergroup=Absentee t:party=NP t:race="State Auditor" m:leg=5 m:count=29 m:cong=8
```

## Meta Commands

```ls
metric m:leg p:integer l:LEG t:dataTypeName=number

metric m:cong p:integer l:CONG t:dataTypeName=number

metric m:count p:integer l:Count t:dataTypeName=number

entity e:r4pa-sjau l:"2008 General - Absentee Election Results" t:attribution="King County Elections" t:url=https://data.kingcounty.gov/api/views/r4pa-sjau

property e:r4pa-sjau t:meta.view v:id=r4pa-sjau v:category="Election results" v:attributionLink=http://www.kingcounty.gov/elections v:averageRating=0 v:name="2008 General - Absentee Election Results" v:attribution="King County Elections"

property e:r4pa-sjau t:meta.view.license v:name="Public Domain"

property e:r4pa-sjau t:meta.view.owner v:id=zw63-9v9t v:screenName=jeffhsu v:displayName=jeffhsu

property e:r4pa-sjau t:meta.view.tableauthor v:id=zw63-9v9t v:screenName=jeffhsu v:roleName=publisher v:displayName=jeffhsu
```

## Top Records

```ls
| race             | precinct   | cc | leg | cong | party | countertype          | countergroup | count | 
| ================ | ========== | == | === | ==== | ===== | ==================== | ============ | ===== | 
| State Treasurer  | CHALLENGER | 3  | 5   | 8    | NP    | Write-in             | Absentee     | 0     | 
| State Auditor    | CHALLENGER | 3  | 5   | 8    | NP    | Times Counted        | Absentee     | 191   | 
| State Auditor    | CHALLENGER | 3  | 5   | 8    | NP    | Times Blank Voted    | Absentee     | 29    | 
| State Auditor    | CHALLENGER | 3  | 5   | 8    | NP    | Times Over Voted     | Absentee     | 0     | 
| State Auditor    | CHALLENGER | 3  | 5   | 8    | Dem   | Brian Sonntag        | Absentee     | 105   | 
| State Auditor    | CHALLENGER | 3  | 5   | 8    | Rep   | J. Richard (Dick) Mc | Absentee     | 57    | 
| State Auditor    | CHALLENGER | 3  | 5   | 8    | NP    | Write-in             | Absentee     | 0     | 
| Attorney General | CHALLENGER | 3  | 5   | 8    | NP    | Times Counted        | Absentee     | 191   | 
| Attorney General | CHALLENGER | 3  | 5   | 8    | NP    | Times Blank Voted    | Absentee     | 19    | 
| Attorney General | CHALLENGER | 3  | 5   | 8    | NP    | Times Over Voted     | Absentee     | 0     | 
```