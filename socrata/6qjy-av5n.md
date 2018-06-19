# 2000 State Expenditures

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2000-state-expenditures-34a25) |
| Metadata | [Link](https://data.mo.gov/api/views/6qjy-av5n) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/6qjy-av5n/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/6qjy-av5n/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | 6qjy-av5n |
| Name | 2000 State Expenditures |
| Attribution | Office of Administration |
| Category | Government Administration |
| Created | 2012-05-15T16:21:41Z |
| Publication Date | 2012-05-15T16:24:24Z |

## Description

Financial data relating to the purchases of goods and services by the state as well as financial disbursements through various state programs

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type | Render Type |
| ======== | ============== | ==================== | ==================== | ========= | =========== |
| Yes      | time           | fiscal_year          | Fiscal Year          | number    | text        |
| Yes      | series tag     | agency_name          | Agency Name          | text      | text        |
| Yes      | series tag     | category_description | Category Description | text      | text        |
| Yes      | series tag     | detail_description   | Detail Description   | text      | text        |
| Yes      | series tag     | vendor_name          | Vendor Name          | text      | text        |
| Yes      | numeric metric | payments_total       | Payments Total       | money     | money       |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:6qjy-av5n d:2000-01-01T00:00:00.000Z t:category_description="BUILDING LEASE PAYMENTS" t:detail_description="BLDG/STORAGE/STRUCTURE LEASES, CAPITAL" t:agency_name=AGRICULTURE t:vendor_name="COLE COUNTY EXTENSION CENTER" m:payments_total=70

series e:6qjy-av5n d:2000-01-01T00:00:00.000Z t:category_description="BUILDING LEASE PAYMENTS" t:detail_description="BLDG/STORAGE/STRUCTURE LEASES, CAPITAL" t:agency_name=AGRICULTURE t:vendor_name="LESLIE PROPERTIES  LLC" m:payments_total=3993.99

series e:6qjy-av5n d:2000-01-01T00:00:00.000Z t:category_description="BUILDING LEASE PAYMENTS" t:detail_description="BLDG/STORAGE/STRUCTURE LEASES, CAPITAL" t:agency_name=AGRICULTURE t:vendor_name="NORTH SHORE RESORT" m:payments_total=125
```

## Meta Commands

```ls
metric m:payments_total p:double l:"Payments Total" t:dataTypeName=money

entity e:6qjy-av5n l:"2000 State Expenditures" t:attribution="Office of Administration" t:url=https://data.mo.gov/api/views/6qjy-av5n

property e:6qjy-av5n t:meta.view v:id=6qjy-av5n v:category="Government Administration" v:averageRating=0 v:name="2000 State Expenditures" v:attribution="Office of Administration"

property e:6qjy-av5n t:meta.view.owner v:id=wzcj-jrcg v:screenName=John v:displayName=John

property e:6qjy-av5n t:meta.view.tableauthor v:id=wzcj-jrcg v:screenName=John v:roleName=editor v:displayName=John
```

## Top Records

```ls
| fiscal_year | agency_name | category_description    | detail_description                      | vendor_name                  | payments_total | 
| =========== | =========== | ======================= | ======================================= | ============================ | ============== | 
| 2000        | AGRICULTURE | BUILDING LEASE PAYMENTS | BLDG/STORAGE/STRUCTURE LEASES, CAPITAL  | COLE COUNTY EXTENSION CENTER | 70             | 
| 2000        | AGRICULTURE | BUILDING LEASE PAYMENTS | BLDG/STORAGE/STRUCTURE LEASES, CAPITAL  | LESLIE PROPERTIES LLC        | 3993.99        | 
| 2000        | AGRICULTURE | BUILDING LEASE PAYMENTS | BLDG/STORAGE/STRUCTURE LEASES, CAPITAL  | NORTH SHORE RESORT           | 125            | 
| 2000        | AGRICULTURE | BUILDING LEASE PAYMENTS | BLDG/STORAGE/STRUCTURE LEASES, CAPITAL  | WHAT'S UP DOCK               | 214.18         | 
| 2000        | AGRICULTURE | BUILDING LEASE PAYMENTS | BUILDING/STORAGE/STRUCTURE LEASES, OPER | COUNTY OF AUDRAIN COMMISSION | 675            | 
| 2000        | AGRICULTURE | BUILDING LEASE PAYMENTS | BUILDING/STORAGE/STRUCTURE LEASES, OPER | FARMERS & TRADERS COMMISSION | 770            | 
| 2000        | AGRICULTURE | BUILDING LEASE PAYMENTS | BUILDING/STORAGE/STRUCTURE LEASES, OPER | HUNTER DEVELOPMENT CO INC    | 19992          | 
| 2000        | AGRICULTURE | BUILDING LEASE PAYMENTS | BUILDING/STORAGE/STRUCTURE LEASES, OPER | KOVAC, CHARLES F REVOCABLE   | 12300          | 
| 2000        | AGRICULTURE | BUILDING LEASE PAYMENTS | BUILDING/STORAGE/STRUCTURE LEASES, OPER | LANGE-STEMANN COMPANY        | 19236          | 
| 2000        | AGRICULTURE | BUILDING LEASE PAYMENTS | BUILDING/STORAGE/STRUCTURE LEASES, OPER | LESLIE PROPERTIES LLC        | 14325.32       | 
```