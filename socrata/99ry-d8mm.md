# Expenditures: ESD: North Central: Fiscal Year 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/expenditures-esd-north-central-fiscal-year-2014-11edd) |
| Metadata | [Link](https://data.oregon.gov/api/views/99ry-d8mm) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/99ry-d8mm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/99ry-d8mm/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | 99ry-d8mm |
| Name | Expenditures: ESD: North Central: Fiscal Year 2014 |
| Category | Revenue & Expense |
| Tags | expenditures, esd, north central, fiscal year 2014 |
| Created | 2014-12-11T23:19:42Z |
| Publication Date | 2014-12-29T05:51:58Z |

## Description

Expenditures for North Central ESD for Fiscal Year 2014

## Columns

```ls
| Included | Schema Type    | Field Name | Name       | Data Type | Render Type |
| ======== | ============== | ========== | ========== | ========= | =========== |
| Yes      | numeric metric | fund       | Fund       | number    | number      |
| Yes      | numeric metric | compt      | Compt      | number    | number      |
| Yes      | numeric metric | obj        | Obj        | number    | number      |
| Yes      | series tag     | remitname  | RemitName  | text      | text        |
| Yes      | series tag     | remit_city | Remit City | text      | text        |
| Yes      | series tag     | remitstate | RemitState | text      | text        |
| Yes      | series tag     | remit_zip  | Remit Zip  | text      | number      |
| Yes      | numeric metric | totalcost  | TotalCost  | money     | money       |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:99ry-d8mm d:2014-01-01T00:00:00.000Z t:remitstate=OR t:remit_zip=97823 t:remit_city=Condon t:remitname="Condon School District No. 25J" m:totalcost=2171.49 m:compt=1131 m:obj=241 m:fund=100

series e:99ry-d8mm d:2014-01-01T00:00:00.000Z t:remitstate=OR t:remit_zip=97823 t:remit_city=Condon t:remitname="Condon School District No. 25J" m:totalcost=1628.62 m:compt=1131 m:obj=241 m:fund=100

series e:99ry-d8mm d:2014-01-01T00:00:00.000Z t:remitstate=OR t:remit_zip=97823 t:remit_city=Condon t:remitname="Condon School District No. 25J" m:totalcost=2714.36 m:compt=1131 m:obj=241 m:fund=100
```

## Meta Commands

```ls
metric m:fund p:integer l:Fund t:dataTypeName=number

metric m:compt p:integer l:Compt t:dataTypeName=number

metric m:obj p:integer l:Obj t:dataTypeName=number

metric m:totalcost p:double l:TotalCost t:dataTypeName=money

entity e:99ry-d8mm l:"Expenditures: ESD: North Central: Fiscal Year 2014" t:url=https://data.oregon.gov/api/views/99ry-d8mm

property e:99ry-d8mm t:meta.view v:id=99ry-d8mm v:category="Revenue & Expense" v:averageRating=0 v:name="Expenditures: ESD: North Central: Fiscal Year 2014"

property e:99ry-d8mm t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:99ry-d8mm t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| fund | compt | obj | remitname                      | remit_city | remitstate | remit_zip | totalcost | 
| ==== | ===== | === | ============================== | ========== | ========== | ========= | ========= | 
| 100  | 1131  | 241 | Condon School District No. 25J | Condon     | OR         | 97823     | 2171.49   | 
| 100  | 1131  | 241 | Condon School District No. 25J | Condon     | OR         | 97823     | 1628.62   | 
| 100  | 1131  | 241 | Condon School District No. 25J | Condon     | OR         | 97823     | 2714.36   | 
| 100  | 1131  | 311 | OdysseyWare                    | Chandler   | AZ         | 85226     | 1000.00   | 
| 100  | 1131  | 311 | OdysseyWare                    | Chandler   | AZ         | 85226     | 500.00    | 
| 100  | 1131  | 311 | Amplify                        | Brooklyn   | NY         | 11201     | 5507.30   | 
| 100  | 1131  | 341 | Bank of Eastern Oregon         | Condon     | OR         | 97823     | 181.40    | 
| 100  | 1131  | 341 | Michael P. Carroll             | Mitchell   | OR         | 97750     | 1679.24   | 
| 100  | 1131  | 342 | Rita Rattray                   | Condon     | OR         | 97823     | 1018.04   | 
| 100  | 1131  | 343 | Ore. Assoc. Student Councils   | Salem      | OR         | 97301     | 900.00    | 
```