# Expenditures: ESD: Grant: Fiscal Year 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/expenditures-esd-grant-fiscal-year-2014-53dfa) |
| Metadata | [Link](https://data.oregon.gov/api/views/w55c-wi7p) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/w55c-wi7p/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/w55c-wi7p/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | w55c-wi7p |
| Name | Expenditures: ESD: Grant: Fiscal Year 2014 |
| Category | Revenue & Expense |
| Tags | expenditures, esd, grant, fiscal year 2014 |
| Created | 2014-12-16T19:32:09Z |
| Publication Date | 2014-12-29T06:09:51Z |

## Description

Expenditures for Grant ESD for Fiscal Year 2014

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| Yes      | numeric metric | esd            | ESD #          | number    | number      |
| Yes      | series tag     | esd_name       | ESD Name       | text      | text        |
| Yes      | numeric metric | fund           | Fund           | number    | number      |
| Yes      | series tag     | fund_name      | Fund Name      | text      | text        |
| Yes      | numeric metric | obj            | Obj            | number    | number      |
| Yes      | series tag     | obj_title      | Obj Title      | text      | text        |
| Yes      | series tag     | vendor_name    | Vendor Name    | text      | text        |
| No       |                | vendor_address | Vendor Address | text      | text        |
| Yes      | series tag     | vendor_city    | Vendor City    | text      | text        |
| Yes      | series tag     | vendor_state   | Vendor State   | text      | text        |
| Yes      | series tag     | vendor_zip     | Vendor Zip     | text      | number      |
| Yes      | numeric metric | totalcost      | TotalCost      | money     | money       |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = vendor_address
```

## Data Commands

```ls
series e:w55c-wi7p d:2014-01-01T00:00:00.000Z t:vendor_city=Alachua t:fund_name="CTE Revitalization" t:vendor_state=FL t:esd_name="Grant ESD" t:vendor_zip=32615 t:obj_title="Instruction Services" t:vendor_name="NCCER - Accreditation Department" m:totalcost=150 m:esd=2007 m:obj=311 m:fund=263

series e:w55c-wi7p d:2014-01-01T00:00:00.000Z t:vendor_city=Alsip t:fund_name="CTE Revitalization" t:vendor_state=IL t:esd_name="Grant ESD" t:vendor_zip=60803 t:obj_title="Depreciable Equipment" t:vendor_name="Paxton/Patterson LLC" m:totalcost=75990 m:esd=2007 m:obj=550 m:fund=263

series e:w55c-wi7p d:2014-01-01T00:00:00.000Z t:vendor_city=Alsip t:fund_name="CTE Revitalization" t:vendor_state=IL t:esd_name="Grant ESD" t:vendor_zip=60803 t:obj_title="Depreciable Equipment" t:vendor_name="Paxton/Patterson LLC" m:totalcost=43750 m:esd=2007 m:obj=550 m:fund=263
```

## Meta Commands

```ls
metric m:esd p:integer l:"ESD #" t:dataTypeName=number

metric m:fund p:integer l:Fund t:dataTypeName=number

metric m:obj p:integer l:Obj t:dataTypeName=number

metric m:totalcost p:double l:TotalCost t:dataTypeName=money

entity e:w55c-wi7p l:"Expenditures: ESD: Grant: Fiscal Year 2014" t:url=https://data.oregon.gov/api/views/w55c-wi7p

property e:w55c-wi7p t:meta.view v:id=w55c-wi7p v:category="Revenue & Expense" v:averageRating=0 v:name="Expenditures: ESD: Grant: Fiscal Year 2014"

property e:w55c-wi7p t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:w55c-wi7p t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| esd  | esd_name  | fund | fund_name                            | obj | obj_title               | vendor_name                      | vendor_address       | vendor_city | vendor_state | vendor_zip | totalcost | 
| ==== | ========= | ==== | ==================================== | === | ======================= | ================================ | ==================== | =========== | ============ | ========== | ========= | 
| 2007 | Grant ESD | 263  | CTE Revitalization                   | 311 | Instruction Services    | NCCER - Accreditation Department | 13614 Progress Blvd  | Alachua     | FL           | 32615      | 150.00    | 
| 2007 | Grant ESD | 263  | CTE Revitalization                   | 550 | Depreciable Equipment   | Paxton/Patterson LLC             | 4141 W. 126th Street | Alsip       | IL           | 60803      | 75990.00  | 
| 2007 | Grant ESD | 263  | CTE Revitalization                   | 550 | Depreciable Equipment   | Paxton/Patterson LLC             | 4141 W. 126th Street | Alsip       | IL           | 60803      | 43750.00  | 
| 2007 | Grant ESD | 241  | County Funds - Technology/Curriculum | 460 | Non-Consumable Supplies | Pearson Education                | P. O. Box 409496     | Atlanta     | GA           |            | 4866.99   | 
| 2007 | Grant ESD | 266  | Perkins Basic                        | 311 | Instruction Services    | Baker High School                | 2500 E. Street       | Baker City  | OR           | 97814      | 184.00    | 
| 2007 | Grant ESD | 265  | Perkins Reserve                      | 311 | Instruction Services    | Baker High School                | 2500 E. Street       | Baker City  | OR           | 97814      | 276.00    | 
| 2007 | Grant ESD | 263  | CTE Revitalization                   | 311 | Instruction Services    | Baker High School                | 2500 E. Street       | Baker City  | OR           | 97814      | 552.00    | 
| 2007 | Grant ESD | 263  | CTE Revitalization                   | 311 | Instruction Services    | Baker High School                | 2500 E. Street       | Baker City  | OR           | 97814      | 276.00    | 
| 2007 | Grant ESD | 267  | Literacy-in-CTE                      | 311 | Instruction Services    | Baker High School                | 2500 E. Street       | Baker City  | OR           | 97814      | 184.00    | 
| 2007 | Grant ESD | 263  | CTE Revitalization                   | 460 | Non-Consumable Supplies | Baker High School                | 2500 E. Street       | Baker City  | OR           | 97814      | 70.89     | 
```