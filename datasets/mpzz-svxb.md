# Election Results - February 8, 2011 - Cumulative

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/election-results-february-8-2011-cumulative-ef681) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/mpzz-svxb) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/mpzz-svxb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/mpzz-svxb/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | mpzz-svxb |
| Name | Election Results - February 8, 2011 - Cumulative |
| Attribution | King County Elections |
| Category | Election operations |
| Tags | elections, results |
| Created | 2011-05-10T21:38:30Z |
| Publication Date | 2011-05-10T21:38:30Z |

## Description

Detailed results for the February 2011 Special Election

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type | Render Type |
| ======== | ============== | =========== | =========== | ========= | =========== |
| Yes      | series tag     | race        | Race        | text      | text        |
| Yes      | series tag     | precinct    | Precinct    | text      | text        |
| Yes      | numeric metric | leg         | LEG         | number    | number      |
| No       |                | cc          | CC          | number    | number      |
| No       |                | cg          | CG          | number    | number      |
| Yes      | series tag     | party       | Party       | text      | text        |
| Yes      | series tag     | countertype | CounterType | text      | text        |
| Yes      | numeric metric | sumofcount  | SumOfCount  | number    | number      |
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
series e:mpzz-svxb d:2011-01-01T00:00:00.000Z t:precinct=ADAIR t:countertype=NO t:party=NP t:race="Lake Washington School District No. 414 Proposition No. 1 Capital Projects Levy" m:leg=45 m:sumofcount=137

series e:mpzz-svxb d:2011-01-01T00:00:00.000Z t:precinct=ADAIR t:countertype="Registered Voters" t:party=NP t:race="Lake Washington School District No. 414 Proposition No. 1 Capital Projects Levy" m:leg=45 m:sumofcount=434

series e:mpzz-svxb d:2011-01-01T00:00:00.000Z t:precinct=ADAIR t:countertype="Times Blank Voted" t:party=NP t:race="Lake Washington School District No. 414 Proposition No. 1 Capital Projects Levy" m:leg=45 m:sumofcount=0
```

## Meta Commands

```ls
metric m:leg p:integer l:LEG d:"Legislative District" t:dataTypeName=number

metric m:sumofcount p:float l:SumOfCount t:dataTypeName=number

entity e:mpzz-svxb l:"Election Results - February 8, 2011 - Cumulative" t:attribution="King County Elections" t:url=https://data.kingcounty.gov/api/views/mpzz-svxb

property e:mpzz-svxb t:meta.view v:id=mpzz-svxb v:category="Election operations" v:attributionLink=http://kingcounty.gov/elections.aspx v:averageRating=0 v:name="Election Results - February 8, 2011 - Cumulative" v:attribution="King County Elections"

property e:mpzz-svxb t:meta.view.license v:name="Public Domain"

property e:mpzz-svxb t:meta.view.owner v:id=z7jt-m6hz v:screenName="Elections Open Data" v:displayName="Elections Open Data"

property e:mpzz-svxb t:meta.view.tableauthor v:id=z7jt-m6hz v:screenName="Elections Open Data" v:roleName=publisher v:displayName="Elections Open Data"
```

## Top Records

```ls
| race                                                                                               | precinct | leg | cc | cg | party | countertype       | sumofcount | 
| ================================================================================================== | ======== | === | == | == | ===== | ================= | ========== | 
| Race                                                                                               | Precinct |     |    |    | Party | CounterType       |            | 
| Lake Washington School District No. 414 Proposition No. 1 Capital Projects Levy                    | ADAIR    | 45  | 3  | 8  | NP    | NO                | 137.00     | 
| Lake Washington School District No. 414 Proposition No. 1 Capital Projects Levy                    | ADAIR    | 45  | 3  | 8  | NP    | Registered Voters | 434.00     | 
| Lake Washington School District No. 414 Proposition No. 1 Capital Projects Levy                    | ADAIR    | 45  | 3  | 8  | NP    | Times Blank Voted | 0.00       | 
| Lake Washington School District No. 414 Proposition No. 1 Capital Projects Levy                    | ADAIR    | 45  | 3  | 8  | NP    | Times Counted     | 268.00     | 
| Lake Washington School District No. 414 Proposition No. 1 Capital Projects Levy                    | ADAIR    | 45  | 3  | 8  | NP    | Times Over Voted  | 0.00       | 
| Lake Washington School District No. 414 Proposition No. 1 Capital Projects Levy                    | ADAIR    | 45  | 3  | 8  | NP    | YES               | 131.00     | 
| Snoqualmie Valley School District No. 410 Proposition No. 1 General Obligation Bonds - $56,200,000 | ALDARRA  | 5   | 3  | 8  | NP    | APPROVED          | 132.00     | 
| Snoqualmie Valley School District No. 410 Proposition No. 1 General Obligation Bonds - $56,200,000 | ALDARRA  | 5   | 3  | 8  | NP    | Registered Voters | 589.00     | 
| Snoqualmie Valley School District No. 410 Proposition No. 1 General Obligation Bonds - $56,200,000 | ALDARRA  | 5   | 3  | 8  | NP    | REJECTED          | 135.00     | 
```