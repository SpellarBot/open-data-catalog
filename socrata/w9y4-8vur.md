# 2001 State Expenditures

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2001-state-expenditures-1a2ba) |
| Metadata | [Link](https://data.mo.gov/api/views/w9y4-8vur) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/w9y4-8vur/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/w9y4-8vur/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | w9y4-8vur |
| Name | 2001 State Expenditures |
| Attribution | Office of Administration |
| Category | Government Administration |
| Created | 2012-05-15T16:17:40Z |
| Publication Date | 2012-05-15T16:20:29Z |

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
series e:w9y4-8vur d:2001-01-01T00:00:00.000Z t:category_description="BUILDING LEASE PAYMENTS" t:detail_description="BLDG/STORAGE/STRUCTURE LEASES, CAPITAL" t:agency_name=AGRICULTURE t:vendor_name="NORTH SHORE RESORT" m:payments_total=125

series e:w9y4-8vur d:2001-01-01T00:00:00.000Z t:category_description="BUILDING LEASE PAYMENTS" t:detail_description="BLDG/STORAGE/STRUCTURE LEASES, CAPITAL" t:agency_name=AGRICULTURE t:vendor_name="WHAT'S UP DOCK" m:payments_total=81

series e:w9y4-8vur d:2001-01-01T00:00:00.000Z t:category_description="BUILDING LEASE PAYMENTS" t:detail_description="BUILDING/STORAGE/STRUCTURE LEASES, OPER" t:agency_name=AGRICULTURE t:vendor_name="BREWER, DURWARD H AND DONNA G" m:payments_total=1353.42
```

## Meta Commands

```ls
metric m:payments_total p:double l:"Payments Total" t:dataTypeName=money

entity e:w9y4-8vur l:"2001 State Expenditures" t:attribution="Office of Administration" t:url=https://data.mo.gov/api/views/w9y4-8vur

property e:w9y4-8vur t:meta.view v:id=w9y4-8vur v:category="Government Administration" v:averageRating=0 v:name="2001 State Expenditures" v:attribution="Office of Administration"

property e:w9y4-8vur t:meta.view.owner v:id=wzcj-jrcg v:screenName=John v:displayName=John

property e:w9y4-8vur t:meta.view.tableauthor v:id=wzcj-jrcg v:screenName=John v:roleName=editor v:displayName=John
```

## Top Records

```ls
| fiscal_year | agency_name | category_description    | detail_description                      | vendor_name                   | payments_total | 
| =========== | =========== | ======================= | ======================================= | ============================= | ============== | 
| 2001        | AGRICULTURE | BUILDING LEASE PAYMENTS | BLDG/STORAGE/STRUCTURE LEASES, CAPITAL  | NORTH SHORE RESORT            | 125            | 
| 2001        | AGRICULTURE | BUILDING LEASE PAYMENTS | BLDG/STORAGE/STRUCTURE LEASES, CAPITAL  | WHAT'S UP DOCK                | 81             | 
| 2001        | AGRICULTURE | BUILDING LEASE PAYMENTS | BUILDING/STORAGE/STRUCTURE LEASES, OPER | BREWER, DURWARD H AND DONNA G | 1353.42        | 
| 2001        | AGRICULTURE | BUILDING LEASE PAYMENTS | BUILDING/STORAGE/STRUCTURE LEASES, OPER | BREWER, DURWOOD H AND DONNA G | 270.68         | 
| 2001        | AGRICULTURE | BUILDING LEASE PAYMENTS | BUILDING/STORAGE/STRUCTURE LEASES, OPER | CITY TREASURER-KANSAS CITY    | 2080.64        | 
| 2001        | AGRICULTURE | BUILDING LEASE PAYMENTS | BUILDING/STORAGE/STRUCTURE LEASES, OPER | COUNTY OF AUDRAIN COMMISSION  | 1125           | 
| 2001        | AGRICULTURE | BUILDING LEASE PAYMENTS | BUILDING/STORAGE/STRUCTURE LEASES, OPER | FARMERS & TRADERS COMMISSION  | 910            | 
| 2001        | AGRICULTURE | BUILDING LEASE PAYMENTS | BUILDING/STORAGE/STRUCTURE LEASES, OPER | HOOVER LEASING INC            | 1364.4         | 
| 2001        | AGRICULTURE | BUILDING LEASE PAYMENTS | BUILDING/STORAGE/STRUCTURE LEASES, OPER | HUNTER DEVELOPMENT CO INC     | 21630          | 
| 2001        | AGRICULTURE | BUILDING LEASE PAYMENTS | BUILDING/STORAGE/STRUCTURE LEASES, OPER | KOVAC, CHARLES F REVOCABLE    | 12300          | 
```