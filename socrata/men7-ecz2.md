# Expenditures: ESD: North Central: Fiscal Year 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/expenditures-esd-north-central-fiscal-year-2013-b84ab) |
| Metadata | [Link](https://data.oregon.gov/api/views/men7-ecz2) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/men7-ecz2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/men7-ecz2/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | men7-ecz2 |
| Name | Expenditures: ESD: North Central: Fiscal Year 2013 |
| Category | Revenue & Expense |
| Tags | expenditures, esd, north central, fiscal year 2013 |
| Created | 2013-10-31T20:17:11Z |
| Publication Date | 2013-10-31T20:22:37Z |

## Description

Expenditures for North Central ESD for Fiscal Year 2013

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
| Yes      | series tag     | remit_zip  | Remit Zip  | text      | text        |
| Yes      | numeric metric | totalcost  | TotalCost  | money     | money       |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:men7-ecz2 d:2013-01-01T00:00:00.000Z t:remitstate=OR t:remit_zip=97823 t:remit_city=Condon t:remitname="Condon School District No. 25J" m:totalcost=2170.1 m:compt=1131 m:obj=241 m:fund=100

series e:men7-ecz2 d:2013-01-01T00:00:00.000Z t:remitstate=OR t:remit_zip=97823 t:remit_city=Condon t:remitname="Condon School District No. 25J" m:totalcost=1627.57 m:compt=1131 m:obj=241 m:fund=100

series e:men7-ecz2 d:2013-01-01T00:00:00.000Z t:remitstate=OR t:remit_zip=97823 t:remit_city=Condon t:remitname="Condon School District No. 25J" m:totalcost=2712.62 m:compt=1131 m:obj=241 m:fund=100
```

## Meta Commands

```ls
metric m:fund p:integer l:Fund t:dataTypeName=number

metric m:compt p:integer l:Compt t:dataTypeName=number

metric m:obj p:integer l:Obj t:dataTypeName=number

metric m:totalcost p:double l:TotalCost t:dataTypeName=money

entity e:men7-ecz2 l:"Expenditures: ESD: North Central: Fiscal Year 2013" t:url=https://data.oregon.gov/api/views/men7-ecz2

property e:men7-ecz2 t:meta.view v:id=men7-ecz2 v:category="Revenue & Expense" v:averageRating=0 v:name="Expenditures: ESD: North Central: Fiscal Year 2013"

property e:men7-ecz2 t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:men7-ecz2 t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| fund | compt | obj | remitname                      | remit_city | remitstate | remit_zip  | totalcost | 
| ==== | ===== | === | ============================== | ========== | ========== | ========== | ========= | 
| 100  | 1131  | 241 | Condon School District No. 25J | Condon     | OR         | 97823      | 2170.10   | 
| 100  | 1131  | 241 | Condon School District No. 25J | Condon     | OR         | 97823      | 1627.57   | 
| 100  | 1131  | 241 | Condon School District No. 25J | Condon     | OR         | 97823      | 2712.62   | 
| 100  | 1131  | 311 | OdysseyWare                    | Chandler   | AZ         | 85226      | 1000.00   | 
| 100  | 1131  | 311 | OdysseyWare                    | Chandler   | AZ         | 85226      | 500.00    | 
| 100  | 1131  | 311 | OdysseyWare                    | Chandler   | AZ         | 85226      | 500.00    | 
| 100  | 1131  | 311 | Wireless Generation            | Brooklyn   | NY         | 11201-1071 | 5507.30   | 
| 100  | 1131  | 311 | Northwest Health Partners      | Spokane    | WA         | 99210-0469 | 75.00     | 
| 100  | 1131  | 341 | Country Flowers                | Condon     | OR         | 97823      | 98.05     | 
| 100  | 1131  | 341 | Filbin Uto, Diane              | Dufur      | OR         | 97021      | 74.58     | 
```