# 2010 Special February - Election Results by precinct (complete eCanvass dataset)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/election-results-february-9-2010-special-95c0e) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/d4y4-sjx2) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/d4y4-sjx2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/d4y4-sjx2/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | d4y4-sjx2 |
| Name | 2010 Special February - Election Results by precinct (complete eCanvass dataset) |
| Attribution | King County Elections |
| Category | Election results |
| Tags | 2010, 2010 special, special, elections, results, precinct, ecanvass |
| Created | 2011-02-09T18:41:18Z |
| Publication Date | 2011-04-17T00:03:09Z |

## Description

February 2010 special election; final/official results by precinct.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type | Render Type |
| ======== | ============== | =========== | =========== | ========= | =========== |
| Yes      | series tag     | race        | Race        | text      | text        |
| Yes      | series tag     | precinct    | Precinct    | text      | text        |
| Yes      | numeric metric | leg         | LEG         | number    | number      |
| No       |                | cc          | CC          | number    | number      |
| No       |                | cg          | CG          | number    | number      |
| Yes      | series tag     | countertype | CounterType | text      | text        |
| Yes      | numeric metric | count       | Count       | number    | number      |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = cc,cg
```

## Data Commands

```ls
series e:d4y4-sjx2 d:2010-01-01T00:00:00.000Z t:precinct=ALLEN t:countertype=NO t:race="BELLEVUE SCHOOL DISTRICT NO. 405 PROPOSITION NO. 1" m:leg=41 m:count=36

series e:d4y4-sjx2 d:2010-01-01T00:00:00.000Z t:precinct=ALLEN t:countertype="Registered Voters" t:race="BELLEVUE SCHOOL DISTRICT NO. 405 PROPOSITION NO. 1" m:leg=41 m:count=351

series e:d4y4-sjx2 d:2010-01-01T00:00:00.000Z t:precinct=ALLEN t:countertype="Times Blank Voted" t:race="BELLEVUE SCHOOL DISTRICT NO. 405 PROPOSITION NO. 1" m:leg=41 m:count=0
```

## Meta Commands

```ls
metric m:leg p:integer l:LEG d:"Legislative district" t:dataTypeName=number

metric m:count p:integer l:Count t:dataTypeName=number

entity e:d4y4-sjx2 l:"2010 Special February - Election Results by precinct (complete eCanvass dataset)" t:attribution="King County Elections" t:url=https://data.kingcounty.gov/api/views/d4y4-sjx2

property e:d4y4-sjx2 t:meta.view v:id=d4y4-sjx2 v:category="Election results" v:attributionLink=http://www.kingcounty.gov/elections.aspx v:averageRating=0 v:name="2010 Special February - Election Results by precinct (complete eCanvass dataset)" v:attribution="King County Elections"

property e:d4y4-sjx2 t:meta.view.license v:name="Public Domain"

property e:d4y4-sjx2 t:meta.view.owner v:id=zw63-9v9t v:screenName=jeffhsu v:displayName=jeffhsu

property e:d4y4-sjx2 t:meta.view.tableauthor v:id=zw63-9v9t v:screenName=jeffhsu v:roleName=publisher v:displayName=jeffhsu
```

## Top Records

```ls
| race                                               | precinct    | leg | cc | cg | countertype       | count | 
| ================================================== | =========== | === | == | == | ================= | ===== | 
| BELLEVUE SCHOOL DISTRICT NO. 405 PROPOSITION NO. 1 | ALLEN       | 41  | 6  | 8  | NO                | 36    | 
| BELLEVUE SCHOOL DISTRICT NO. 405 PROPOSITION NO. 1 | ALLEN       | 41  | 6  | 8  | Registered Voters | 351   | 
| BELLEVUE SCHOOL DISTRICT NO. 405 PROPOSITION NO. 1 | ALLEN       | 41  | 6  | 8  | Times Blank Voted | 0     | 
| BELLEVUE SCHOOL DISTRICT NO. 405 PROPOSITION NO. 1 | ALLEN       | 41  | 6  | 8  | Times Counted     | 120   | 
| BELLEVUE SCHOOL DISTRICT NO. 405 PROPOSITION NO. 1 | ALLEN       | 41  | 6  | 8  | Times Over Voted  | 0     | 
| BELLEVUE SCHOOL DISTRICT NO. 405 PROPOSITION NO. 1 | ALLEN       | 41  | 6  | 8  | YES               | 84    | 
| BELLEVUE SCHOOL DISTRICT NO. 405 PROPOSITION NO. 1 | BEA 41-0099 | 41  | 6  | 8  | NO                | 45    | 
| BELLEVUE SCHOOL DISTRICT NO. 405 PROPOSITION NO. 1 | BEA 41-0099 | 41  | 6  | 8  | Registered Voters | 214   | 
| BELLEVUE SCHOOL DISTRICT NO. 405 PROPOSITION NO. 1 | BEA 41-0099 | 41  | 6  | 8  | Times Blank Voted | 0     | 
| BELLEVUE SCHOOL DISTRICT NO. 405 PROPOSITION NO. 1 | BEA 41-0099 | 41  | 6  | 8  | Times Counted     | 121   | 
```