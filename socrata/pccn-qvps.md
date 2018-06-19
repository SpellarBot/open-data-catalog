# 2009 Special March - Election Results by precinct (complete eCanvass dataset)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/election-results-march-10-2009-special-17662) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/pccn-qvps) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/pccn-qvps/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/pccn-qvps/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | pccn-qvps |
| Name | 2009 Special March - Election Results by precinct (complete eCanvass dataset) |
| Attribution | King County Elections |
| Category | Election results |
| Tags | 2009, 2009 special, special, elections, results, precinct, ecanvass |
| Created | 2011-02-11T17:41:01Z |
| Publication Date | 2011-04-17T00:03:09Z |

## Description

March 2009 special election; final/official results by precinct.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type | Render Type |
| ======== | ============== | =========== | =========== | ========= | =========== |
| Yes      | series tag     | race        | Race        | text      | text        |
| Yes      | series tag     | precinct    | Precinct    | text      | text        |
| Yes      | numeric metric | leg         | Leg         | number    | number      |
| No       |                | cc          | CC          | number    | number      |
| Yes      | numeric metric | cong        | Cong        | number    | number      |
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
Excluded Fields = cc
```

## Data Commands

```ls
series e:pccn-qvps d:2009-01-01T00:00:00.000Z t:precinct=ALDARRA t:countertype="Times Blank Voted" t:race="SNOQUALMIE VALLEY SCHOOL DISTRICT # 410 Proposition No. 1" m:leg=5 m:count=0 m:cong=8

series e:pccn-qvps d:2009-01-01T00:00:00.000Z t:precinct=ALDARRA t:countertype=REJECTED t:race="SNOQUALMIE VALLEY SCHOOL DISTRICT # 410 Proposition No. 1" m:leg=5 m:count=217 m:cong=8

series e:pccn-qvps d:2009-01-01T00:00:00.000Z t:precinct=ALDARRA t:countertype="Times Over Voted" t:race="SNOQUALMIE VALLEY SCHOOL DISTRICT # 410 Proposition No. 1" m:leg=5 m:count=0 m:cong=8
```

## Meta Commands

```ls
metric m:leg p:integer l:Leg d:"Legislative district" t:dataTypeName=number

metric m:cong p:integer l:Cong d:"Congressional district" t:dataTypeName=number

metric m:count p:integer l:Count t:dataTypeName=number

entity e:pccn-qvps l:"2009 Special March - Election Results by precinct (complete eCanvass dataset)" t:attribution="King County Elections" t:url=https://data.kingcounty.gov/api/views/pccn-qvps

property e:pccn-qvps t:meta.view v:id=pccn-qvps v:category="Election results" v:attributionLink=http://www.kingcounty.gov/elections.aspx v:averageRating=0 v:name="2009 Special March - Election Results by precinct (complete eCanvass dataset)" v:attribution="King County Elections"

property e:pccn-qvps t:meta.view.license v:name="Public Domain"

property e:pccn-qvps t:meta.view.owner v:id=zw63-9v9t v:screenName=jeffhsu v:displayName=jeffhsu

property e:pccn-qvps t:meta.view.tableauthor v:id=zw63-9v9t v:screenName=jeffhsu v:roleName=publisher v:displayName=jeffhsu
```

## Top Records

```ls
| race                                                      | precinct    | leg | cc | cong | countertype       | count | 
| ========================================================= | =========== | === | == | ==== | ================= | ===== | 
| SNOQUALMIE VALLEY SCHOOL DISTRICT # 410 Proposition No. 1 | ALDARRA     | 5   | 3  | 8    | Times Blank Voted | 0     | 
| SNOQUALMIE VALLEY SCHOOL DISTRICT # 410 Proposition No. 1 | ALDARRA     | 5   | 3  | 8    | REJECTED          | 217   | 
| SNOQUALMIE VALLEY SCHOOL DISTRICT # 410 Proposition No. 1 | ALDARRA     | 5   | 3  | 8    | Times Over Voted  | 0     | 
| SNOQUALMIE VALLEY SCHOOL DISTRICT # 410 Proposition No. 1 | ALDARRA     | 5   | 3  | 8    | Times Counted     | 526   | 
| SNOQUALMIE VALLEY SCHOOL DISTRICT # 410 Proposition No. 1 | ALDARRA     | 5   | 3  | 8    | Registered Voters | 1169  | 
| SNOQUALMIE VALLEY SCHOOL DISTRICT # 410 Proposition No. 1 | ALDARRA     | 5   | 3  | 8    | APPROVED          | 309   | 
| AUBURN SCHOOL DISTRICT NO. 408 Proposition No. 1          | ALG 30-0013 | 30  | 7  | 9    | Registered Voters | 401   | 
| AUBURN SCHOOL DISTRICT NO. 408 Proposition No. 1          | ALG 30-0013 | 30  | 7  | 9    | Times Blank Voted | 0     | 
| AUBURN SCHOOL DISTRICT NO. 408 Proposition No. 1          | ALG 30-0013 | 30  | 7  | 9    | Times Over Voted  | 0     | 
| AUBURN SCHOOL DISTRICT NO. 408 Proposition No. 1          | ALG 30-0013 | 30  | 7  | 9    | APPROVED          | 45    | 
```