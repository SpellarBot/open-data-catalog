# 2009 Special February - Election Results by precinct (complete eCanvass dataset)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/election-results-february-3-2009-special-ceea9) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/pg4p-fsqw) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/pg4p-fsqw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/pg4p-fsqw/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | pg4p-fsqw |
| Name | 2009 Special February - Election Results by precinct (complete eCanvass dataset) |
| Attribution | King County Elections |
| Category | Election results |
| Tags | 2009, 2009 special, special, elections, results, precinct, ecanvass |
| Created | 2011-02-11T18:09:44Z |
| Publication Date | 2011-04-17T00:03:09Z |

## Description

February 2009 special election; final/official results by precinct.

## Columns

```ls
| Included | Schema Type    | Field Name | Name      | Data Type | Render Type |
| ======== | ============== | ========== | ========= | ========= | =========== |
| Yes      | series tag     | race       | Race      | text      | text        |
| Yes      | series tag     | precinct   | Precinct  | text      | text        |
| Yes      | numeric metric | leg        | LEG       | number    | number      |
| No       |                | cc         | CC        | number    | number      |
| Yes      | numeric metric | cong       | CONG      | number    | number      |
| Yes      | series tag     | candidate  | Candidate | text      | text        |
| Yes      | numeric metric | count      | Count     | number    | number      |
```

## Time Field

```ls
Value = 2009
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = cc
```

## Data Commands

```ls
series e:pg4p-fsqw d:2009-01-01T00:00:00.000Z t:precinct="ALG 30-0013" t:candidate="Pam Roach" t:race="Director of Elections" m:leg=30 m:count=9 m:cong=9

series e:pg4p-fsqw d:2009-01-01T00:00:00.000Z t:precinct="ALG 30-0013" t:candidate="Registered Voters" t:race="Director of Elections" m:leg=30 m:count=397 m:cong=9

series e:pg4p-fsqw d:2009-01-01T00:00:00.000Z t:precinct="ALG 30-0013" t:candidate="Sherril Huff" t:race="Director of Elections" m:leg=30 m:count=10 m:cong=9
```

## Meta Commands

```ls
metric m:leg p:integer l:LEG d:"Legislative district" t:dataTypeName=number

metric m:cong p:integer l:CONG d:"Congressional district" t:dataTypeName=number

metric m:count p:integer l:Count t:dataTypeName=number

entity e:pg4p-fsqw l:"2009 Special February - Election Results by precinct (complete eCanvass dataset)" t:attribution="King County Elections" t:url=https://data.kingcounty.gov/api/views/pg4p-fsqw

property e:pg4p-fsqw t:meta.view v:id=pg4p-fsqw v:category="Election results" v:attributionLink=http://www.kingcounty.gov/elections.aspx v:averageRating=0 v:name="2009 Special February - Election Results by precinct (complete eCanvass dataset)" v:attribution="King County Elections"

property e:pg4p-fsqw t:meta.view.license v:name="Public Domain"

property e:pg4p-fsqw t:meta.view.owner v:id=zw63-9v9t v:screenName=jeffhsu v:displayName=jeffhsu

property e:pg4p-fsqw t:meta.view.tableauthor v:id=zw63-9v9t v:screenName=jeffhsu v:roleName=publisher v:displayName=jeffhsu
```

## Top Records

```ls
| race                  | precinct    | leg | cc | cong | candidate            | count | 
| ===================== | =========== | === | == | ==== | ==================== | ===== | 
| Director of Elections | ALG 30-0013 | 30  | 7  | 9    | Pam Roach            | 9     | 
| Director of Elections | ALG 30-0013 | 30  | 7  | 9    | Registered Voters    | 397   | 
| Director of Elections | ALG 30-0013 | 30  | 7  | 9    | Sherril Huff         | 10    | 
| Director of Elections | ALG 30-0013 | 30  | 7  | 9    | Times Blank Voted    | 0     | 
| Director of Elections | ALG 30-0013 | 30  | 7  | 9    | Times Counted        | 56    | 
| Director of Elections | ALG 30-0013 | 30  | 7  | 9    | Times Over Voted     | 0     | 
| Director of Elections | ALG 30-0013 | 30  | 7  | 9    | Write-in             | 0     | 
| Director of Elections | ALG 30-0014 | 30  | 7  | 9    | Bill Anderson        | 14    | 
| Director of Elections | ALG 30-0014 | 30  | 7  | 9    | Christopher Clifford | 6     | 
| Director of Elections | ALG 30-0014 | 30  | 7  | 9    | David Irons          | 14    | 
```