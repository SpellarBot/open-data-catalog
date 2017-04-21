# 2002 State Expenditures

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2002-state-expenditures-4a16a) |
| Metadata | [Link](https://data.mo.gov/api/views/rr2u-sazk) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/rr2u-sazk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/rr2u-sazk/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | rr2u-sazk |
| Name | 2002 State Expenditures |
| Attribution | Office of Administration |
| Category | Government Administration |
| Created | 2012-05-15T16:13:27Z |
| Publication Date | 2012-05-15T16:16:19Z |

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
series e:rr2u-sazk d:2002-01-01T00:00:00.000Z t:category_description="BUILDING LEASE PAYMENTS" t:detail_description="BLDG/STORAGE/STRUCTURE LEASES, CAPITAL" t:agency_name=AGRICULTURE t:vendor_name="NORTH SHORE RESORT" m:payments_total=150

series e:rr2u-sazk d:2002-01-01T00:00:00.000Z t:category_description="BUILDING LEASE PAYMENTS" t:detail_description="BLDG/STORAGE/STRUCTURE LEASES, CAPITAL" t:agency_name=AGRICULTURE t:vendor_name="THOMAS HILL ENTERPRISE CENTER" m:payments_total=1534.13

series e:rr2u-sazk d:2002-01-01T00:00:00.000Z t:category_description="BUILDING LEASE PAYMENTS" t:detail_description="BLDG/STORAGE/STRUCTURE LEASES, CAPITAL" t:agency_name=AGRICULTURE t:vendor_name="WHAT'S UP DOCK" m:payments_total=51.5
```

## Meta Commands

```ls
metric m:payments_total p:double l:"Payments Total" t:dataTypeName=money

entity e:rr2u-sazk l:"2002 State Expenditures" t:attribution="Office of Administration" t:url=https://data.mo.gov/api/views/rr2u-sazk

property e:rr2u-sazk t:meta.view v:id=rr2u-sazk v:category="Government Administration" v:averageRating=0 v:name="2002 State Expenditures" v:attribution="Office of Administration"

property e:rr2u-sazk t:meta.view.owner v:id=wzcj-jrcg v:screenName=John v:displayName=John

property e:rr2u-sazk t:meta.view.tableauthor v:id=wzcj-jrcg v:screenName=John v:roleName=editor v:displayName=John
```

## Top Records

```ls
| fiscal_year | agency_name | category_description    | detail_description                      | vendor_name                   | payments_total | 
| =========== | =========== | ======================= | ======================================= | ============================= | ============== | 
| 2002        | AGRICULTURE | BUILDING LEASE PAYMENTS | BLDG/STORAGE/STRUCTURE LEASES, CAPITAL  | NORTH SHORE RESORT            | 150            | 
| 2002        | AGRICULTURE | BUILDING LEASE PAYMENTS | BLDG/STORAGE/STRUCTURE LEASES, CAPITAL  | THOMAS HILL ENTERPRISE CENTER | 1534.13        | 
| 2002        | AGRICULTURE | BUILDING LEASE PAYMENTS | BLDG/STORAGE/STRUCTURE LEASES, CAPITAL  | WHAT'S UP DOCK                | 51.5           | 
| 2002        | AGRICULTURE | BUILDING LEASE PAYMENTS | BUILDING/STORAGE/STRUCTURE LEASES, OPER | BREWER, DURWARD H AND DONNA G | 1624.08        | 
| 2002        | AGRICULTURE | BUILDING LEASE PAYMENTS | BUILDING/STORAGE/STRUCTURE LEASES, OPER | COUNTY OF AUDRAIN COMMISSION  | 900            | 
| 2002        | AGRICULTURE | BUILDING LEASE PAYMENTS | BUILDING/STORAGE/STRUCTURE LEASES, OPER | FARMERS & TRADERS COMMISSION  | 840            | 
| 2002        | AGRICULTURE | BUILDING LEASE PAYMENTS | BUILDING/STORAGE/STRUCTURE LEASES, OPER | HOOVER LEASING INC            | 1364.48        | 
| 2002        | AGRICULTURE | BUILDING LEASE PAYMENTS | BUILDING/STORAGE/STRUCTURE LEASES, OPER | HUNTER DEVELOPMENT CO INC     | 20538          | 
| 2002        | AGRICULTURE | BUILDING LEASE PAYMENTS | BUILDING/STORAGE/STRUCTURE LEASES, OPER | KOVAC, CHARLES F REVOCABLE    | 15000          | 
| 2002        | AGRICULTURE | BUILDING LEASE PAYMENTS | BUILDING/STORAGE/STRUCTURE LEASES, OPER | LESLIE PROPERTIES LLC         | 21600          | 
```