# 2011 Special February - Election Results by precinct (complete eCanvass dataset)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/election-results-february-8-2011-cumulative-fb42f) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/dx5r-rh67) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/dx5r-rh67/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/dx5r-rh67/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | dx5r-rh67 |
| Name | 2011 Special February - Election Results by precinct (complete eCanvass dataset) |
| Attribution | King County Elections |
| Category | Election results |
| Tags | 2011, 2011 special, special, elections, results, precinct, ecanvass |
| Created | 2011-05-10T21:33:18Z |
| Publication Date | 2011-05-10T21:33:18Z |

## Description

February 2011 special election; final/official results by precinct.

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
series e:dx5r-rh67 d:2011-01-01T00:00:00.000Z t:precinct=ADAIR t:countertype=NO t:countergroup=Total t:party=NP t:race="Lake Washington School District No. 414 Proposition No. 1 Capital Projects Levy" m:leg=45

series e:dx5r-rh67 d:2011-01-01T00:00:00.000Z t:precinct=ADAIR t:countertype="Registered Voters" t:countergroup=Total t:party=NP t:race="Lake Washington School District No. 414 Proposition No. 1 Capital Projects Levy" m:leg=45

series e:dx5r-rh67 d:2011-01-01T00:00:00.000Z t:precinct=ADAIR t:countertype="Times Blank Voted" t:countergroup=Total t:party=NP t:race="Lake Washington School District No. 414 Proposition No. 1 Capital Projects Levy" m:leg=45
```

## Meta Commands

```ls
metric m:leg p:integer l:LEG t:dataTypeName=number

entity e:dx5r-rh67 l:"2011 Special February - Election Results by precinct (complete eCanvass dataset)" t:attribution="King County Elections" t:url=https://data.kingcounty.gov/api/views/dx5r-rh67

property e:dx5r-rh67 t:meta.view v:id=dx5r-rh67 v:category="Election results" v:attributionLink=http://www.kingcounty.gov/elections.aspx v:averageRating=0 v:name="2011 Special February - Election Results by precinct (complete eCanvass dataset)" v:attribution="King County Elections"

property e:dx5r-rh67 t:meta.view.license v:name="Public Domain"

property e:dx5r-rh67 t:meta.view.owner v:id=z7jt-m6hz v:screenName="Elections Open Data" v:displayName="Elections Open Data"

property e:dx5r-rh67 t:meta.view.tableauthor v:id=z7jt-m6hz v:screenName="Elections Open Data" v:roleName=publisher v:displayName="Elections Open Data"
```

## Top Records

```ls
| precinct | race                                                                                               | leg | cc | cg | countergroup | party | countertype       | 
| ======== | ================================================================================================== | === | == | == | ============ | ===== | ================= | 
| Precinct | Race                                                                                               |     |    |    | CounterGroup | Party | CounterType       | 
| ADAIR    | Lake Washington School District No. 414 Proposition No. 1 Capital Projects Levy                    | 45  | 3  | 8  | Total        | NP    | NO                | 
| ADAIR    | Lake Washington School District No. 414 Proposition No. 1 Capital Projects Levy                    | 45  | 3  | 8  | Total        | NP    | Registered Voters | 
| ADAIR    | Lake Washington School District No. 414 Proposition No. 1 Capital Projects Levy                    | 45  | 3  | 8  | Total        | NP    | Times Blank Voted | 
| ADAIR    | Lake Washington School District No. 414 Proposition No. 1 Capital Projects Levy                    | 45  | 3  | 8  | Total        | NP    | Times Counted     | 
| ADAIR    | Lake Washington School District No. 414 Proposition No. 1 Capital Projects Levy                    | 45  | 3  | 8  | Total        | NP    | Times Over Voted  | 
| ADAIR    | Lake Washington School District No. 414 Proposition No. 1 Capital Projects Levy                    | 45  | 3  | 8  | Total        | NP    | YES               | 
| ALDARRA  | Snoqualmie Valley School District No. 410 Proposition No. 1 General Obligation Bonds - $56,200,000 | 5   | 3  | 8  | Total        | NP    | APPROVED          | 
| ALDARRA  | Snoqualmie Valley School District No. 410 Proposition No. 1 General Obligation Bonds - $56,200,000 | 5   | 3  | 8  | Total        | NP    | Registered Voters | 
| ALDARRA  | Snoqualmie Valley School District No. 410 Proposition No. 1 General Obligation Bonds - $56,200,000 | 5   | 3  | 8  | Total        | NP    | REJECTED          | 
```