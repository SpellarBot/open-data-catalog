# 2009 General - Election Results by precinct (complete eCanvass dataset)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/election-results-november-3-2009-general-334a1) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/c34s-iuef) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/c34s-iuef/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/c34s-iuef/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | c34s-iuef |
| Name | 2009 General - Election Results by precinct (complete eCanvass dataset) |
| Attribution | King County Elections |
| Category | Election results |
| Tags | 2009, 2009 general, general, elections, results, precinct, ecanvass |
| Created | 2011-02-09T17:22:39Z |
| Publication Date | 2011-04-17T00:03:09Z |

## Description

November 2009 general election; final/official results by precinct.

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
Value = 2009
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = cc,cg
```

## Data Commands

```ls
series e:c34s-iuef d:2009-01-01T00:00:00.000Z t:precinct=ADAIR t:countertype="Bob Blanchard" t:race="Assessor unexpired 2-year term" m:leg=45 m:count=73

series e:c34s-iuef d:2009-01-01T00:00:00.000Z t:precinct=ADAIR t:countertype="Bob Rosenberger" t:race="Assessor unexpired 2-year term" m:leg=45 m:count=89

series e:c34s-iuef d:2009-01-01T00:00:00.000Z t:precinct=ADAIR t:countertype="Gene Lux" t:race="Assessor unexpired 2-year term" m:leg=45 m:count=7
```

## Meta Commands

```ls
metric m:leg p:integer l:LEG d:"Legislative District" t:dataTypeName=number

metric m:count p:integer l:Count t:dataTypeName=number

entity e:c34s-iuef l:"2009 General - Election Results by precinct (complete eCanvass dataset)" t:attribution="King County Elections" t:url=https://data.kingcounty.gov/api/views/c34s-iuef

property e:c34s-iuef t:meta.view v:id=c34s-iuef v:category="Election results" v:attributionLink=http://www.kingcounty.gov/elections.aspx v:averageRating=0 v:name="2009 General - Election Results by precinct (complete eCanvass dataset)" v:attribution="King County Elections"

property e:c34s-iuef t:meta.view.license v:name="Public Domain"

property e:c34s-iuef t:meta.view.owner v:id=zw63-9v9t v:screenName=jeffhsu v:displayName=jeffhsu

property e:c34s-iuef t:meta.view.tableauthor v:id=zw63-9v9t v:screenName=jeffhsu v:roleName=publisher v:displayName=jeffhsu
```

## Top Records

```ls
| race                           | precinct | leg | cc | cg | countertype       | count | 
| ============================== | ======== | === | == | == | ================= | ===== | 
| Assessor unexpired 2-year term | ADAIR    | 45  | 3  | 8  | Bob Blanchard     | 73    | 
| Assessor unexpired 2-year term | ADAIR    | 45  | 3  | 8  | Bob Rosenberger   | 89    | 
| Assessor unexpired 2-year term | ADAIR    | 45  | 3  | 8  | Gene Lux          | 7     | 
| Assessor unexpired 2-year term | ADAIR    | 45  | 3  | 8  | Graham Albertini  | 162   | 
| Assessor unexpired 2-year term | ADAIR    | 45  | 3  | 8  | Lloyd Hara        | 167   | 
| Assessor unexpired 2-year term | ADAIR    | 45  | 3  | 8  | Registered Voters | 746   | 
| Assessor unexpired 2-year term | ADAIR    | 45  | 3  | 8  | Times Blank Voted | 99    | 
| Assessor unexpired 2-year term | ADAIR    | 45  | 3  | 8  | Times Counted     | 600   | 
| Assessor unexpired 2-year term | ADAIR    | 45  | 3  | 8  | Times Over Voted  | 0     | 
| Assessor unexpired 2-year term | ADAIR    | 45  | 3  | 8  | Write-in          | 3     | 
```