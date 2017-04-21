# 2008 Primary - Election Results by precinct (complete eCanvass dataset)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/election-results-august-2008-primary-cumulative-58bb0) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/9ycg-yemn) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/9ycg-yemn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/9ycg-yemn/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | 9ycg-yemn |
| Name | 2008 Primary - Election Results by precinct (complete eCanvass dataset) |
| Attribution | King County Elections |
| Category | Election results |
| Tags | 2008, 2008 primary, primary, elections, results, precinct, ecanvass |
| Created | 2011-05-09T20:52:25Z |
| Publication Date | 2011-05-09T20:52:25Z |

## Description

August 2008 primary election; final/official results by precinct.

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type | Render Type |
| ======== | ============== | ============ | ============ | ========= | =========== |
| Yes      | series tag     | race         | Race         | text      | text        |
| Yes      | series tag     | precinct     | Precinct     | text      | text        |
| Yes      | numeric metric | leg          | LEG          | number    | number      |
| No       |                | cc           | CC           | number    | number      |
| Yes      | series tag     | countergroup | CounterGroup | text      | text        |
| Yes      | series tag     | countertype  | CounterType  | text      | text        |
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
series e:9ycg-yemn d:2008-01-01T00:00:00.000Z t:precinct=ALDARRA t:countertype="John Ladenburg" t:countergroup=Absentee t:race="Attorney General" m:leg=5 m:count=105

series e:9ycg-yemn d:2008-01-01T00:00:00.000Z t:precinct=ALDARRA t:countertype="John Ladenburg" t:countergroup=Polling t:race="Attorney General" m:leg=5 m:count=23

series e:9ycg-yemn d:2008-01-01T00:00:00.000Z t:precinct=ALDARRA t:countertype="John Ladenburg" t:countergroup=Polling t:race="Attorney General" m:leg=5 m:count=0
```

## Meta Commands

```ls
metric m:leg p:integer l:LEG d:"Legislative District" t:dataTypeName=number

metric m:count p:integer l:Count t:dataTypeName=number

entity e:9ycg-yemn l:"2008 Primary - Election Results by precinct (complete eCanvass dataset)" t:attribution="King County Elections" t:url=https://data.kingcounty.gov/api/views/9ycg-yemn

property e:9ycg-yemn t:meta.view v:id=9ycg-yemn v:category="Election results" v:attributionLink=http://www.kingcounty.gov/elections/.aspx v:averageRating=0 v:name="2008 Primary - Election Results by precinct (complete eCanvass dataset)" v:attribution="King County Elections"

property e:9ycg-yemn t:meta.view.license v:name="Public Domain"

property e:9ycg-yemn t:meta.view.owner v:id=z7jt-m6hz v:screenName="Elections Open Data" v:displayName="Elections Open Data"

property e:9ycg-yemn t:meta.view.tableauthor v:id=z7jt-m6hz v:screenName="Elections Open Data" v:roleName=publisher v:displayName="Elections Open Data"
```

## Top Records

```ls
| race             | precinct | leg | cc | countergroup | countertype       | count | 
| ================ | ======== | === | == | ============ | ================= | ===== | 
| Race             | Precinct |     |    | CounterGroup | CounterType       |       | 
| Attorney General | ALDARRA  | 5   | 3  | Absentee     | John Ladenburg    | 105   | 
| Attorney General | ALDARRA  | 5   | 3  | Polling      | John Ladenburg    | 23    | 
| Attorney General | ALDARRA  | 5   | 3  | Polling      | John Ladenburg    | 0     | 
| Attorney General | ALDARRA  | 5   | 3  | Total        | John Ladenburg    | 128   | 
| Attorney General | ALDARRA  | 5   | 3  | Polling      | Registered Voters | 0     | 
| Attorney General | ALDARRA  | 5   | 3  | Absentee     | Registered Voters | 0     | 
| Attorney General | ALDARRA  | 5   | 3  | Polling      | Registered Voters | 0     | 
| Attorney General | ALDARRA  | 5   | 3  | Total        | Registered Voters | 1089  | 
| Attorney General | ALDARRA  | 5   | 3  | Polling      | Rob McKenna       | 28    | 
```