# DMV Boating Registrations 2008 To 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dmv-boating-registrations-2008-to-2014) |
| Metadata | [Link](https://data.ct.gov/api/views/mrb6-7ee5) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/mrb6-7ee5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/mrb6-7ee5/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | mrb6-7ee5 |
| Name | DMV Boating Registrations 2008 To 2014 |
| Attribution | Departmet of Motor Vehicles |
| Category | Transportation |
| Created | 2014-09-23T13:19:51Z |
| Publication Date | 2014-09-23T13:22:22Z |

## Description

No. of Boats Registered per Year by Type of Transactions and Type of Boats

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type | Render Type |
| ======== | ============== | ==================== | ==================== | ========= | =========== |
| Yes      | time           | fiscal_year          | Fiscal Year          | number    | number      |
| Yes      | series tag     | type_of_transactions | Type of Transactions | text      | text        |
| Yes      | numeric metric | no_of_boats          | No .of Boats         | number    | number      |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:mrb6-7ee5 d:2008-01-01T00:00:00.000Z t:type_of_transactions="BOAT CHANGE OF TYPE" m:no_of_boats=59

series e:mrb6-7ee5 d:2009-01-01T00:00:00.000Z t:type_of_transactions="BOAT CHANGE OF TYPE" m:no_of_boats=50

series e:mrb6-7ee5 d:2010-01-01T00:00:00.000Z t:type_of_transactions="BOAT CHANGE OF TYPE" m:no_of_boats=21
```

## Meta Commands

```ls
metric m:no_of_boats p:integer l:"No .of Boats" t:dataTypeName=number

entity e:mrb6-7ee5 l:"DMV Boating Registrations 2008 To 2014" t:attribution="Departmet of Motor Vehicles" t:url=https://data.ct.gov/api/views/mrb6-7ee5

property e:mrb6-7ee5 t:meta.view v:id=mrb6-7ee5 v:category=Transportation v:averageRating=0 v:name="DMV Boating Registrations 2008 To 2014" v:attribution="Departmet of Motor Vehicles"

property e:mrb6-7ee5 t:meta.view.owner v:id=fd5k-6njr v:screenName=APatel v:displayName=APatel

property e:mrb6-7ee5 t:meta.view.tableauthor v:id=fd5k-6njr v:screenName=APatel v:roleName=editor v:displayName=APatel
```

## Top Records

```ls
| fiscal_year | type_of_transactions        | no_of_boats | 
| =========== | =========================== | =========== | 
| 2008        | BOAT CHANGE OF TYPE         | 59          | 
| 2009        | BOAT CHANGE OF TYPE         | 50          | 
| 2010        | BOAT CHANGE OF TYPE         | 21          | 
| 2011        | BOAT CHANGE OF TYPE         | 41          | 
| 2012        | BOAT CHANGE OF TYPE         | 16          | 
| 2013        | BOAT CHANGE OF TYPE         | 27          | 
| 2014        | BOAT CHANGE OF TYPE         | 54          | 
| 2008        | BOAT RECORD XFER NO PROBATE | 6           | 
| 2009        | BOAT RECORD XFER NO PROBATE | 12          | 
| 2010        | BOAT RECORD XFER NO PROBATE | 15          | 
```