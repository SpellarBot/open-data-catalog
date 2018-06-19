# 2004 State Expenditures

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2004-state-expenditures-9b41c) |
| Metadata | [Link](https://data.mo.gov/api/views/dasw-mr6w) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/dasw-mr6w/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/dasw-mr6w/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | dasw-mr6w |
| Name | 2004 State Expenditures |
| Attribution | Office of Administration |
| Category | Government Administration |
| Created | 2012-05-15T16:01:40Z |
| Publication Date | 2012-05-15T16:04:27Z |

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
series e:dasw-mr6w d:2004-01-01T00:00:00.000Z t:category_description="BUILDING LEASE PAYMENTS" t:detail_description="BUILDING/STORAGE/STRUCTURE LEASES, OPER" t:agency_name=AGRICULTURE t:vendor_name="AA ALL STOR" m:payments_total=4200

series e:dasw-mr6w d:2004-01-01T00:00:00.000Z t:category_description="BUILDING LEASE PAYMENTS" t:detail_description="BUILDING/STORAGE/STRUCTURE LEASES, OPER" t:agency_name=AGRICULTURE t:vendor_name="BREWER, DURWARD H AND DONNA G" m:payments_total=406.02

series e:dasw-mr6w d:2004-01-01T00:00:00.000Z t:category_description="BUILDING LEASE PAYMENTS" t:detail_description="BUILDING/STORAGE/STRUCTURE LEASES, OPER" t:agency_name=AGRICULTURE t:vendor_name="BRM 2002 LLC" m:payments_total=114840
```

## Meta Commands

```ls
metric m:payments_total p:double l:"Payments Total" t:dataTypeName=money

entity e:dasw-mr6w l:"2004 State Expenditures" t:attribution="Office of Administration" t:url=https://data.mo.gov/api/views/dasw-mr6w

property e:dasw-mr6w t:meta.view v:id=dasw-mr6w v:category="Government Administration" v:averageRating=0 v:name="2004 State Expenditures" v:attribution="Office of Administration"

property e:dasw-mr6w t:meta.view.owner v:id=wzcj-jrcg v:screenName=John v:displayName=John

property e:dasw-mr6w t:meta.view.tableauthor v:id=wzcj-jrcg v:screenName=John v:roleName=editor v:displayName=John
```

## Top Records

```ls
| fiscal_year | agency_name | category_description    | detail_description                      | vendor_name                   | payments_total | 
| =========== | =========== | ======================= | ======================================= | ============================= | ============== | 
| 2004        | AGRICULTURE | BUILDING LEASE PAYMENTS | BUILDING/STORAGE/STRUCTURE LEASES, OPER | AA ALL STOR                   | 4200           | 
| 2004        | AGRICULTURE | BUILDING LEASE PAYMENTS | BUILDING/STORAGE/STRUCTURE LEASES, OPER | BREWER, DURWARD H AND DONNA G | 406.02         | 
| 2004        | AGRICULTURE | BUILDING LEASE PAYMENTS | BUILDING/STORAGE/STRUCTURE LEASES, OPER | BRM 2002 LLC                  | 114840         | 
| 2004        | AGRICULTURE | BUILDING LEASE PAYMENTS | BUILDING/STORAGE/STRUCTURE LEASES, OPER | COUNTY OF AUDRAIN COMMISSION  | 900            | 
| 2004        | AGRICULTURE | BUILDING LEASE PAYMENTS | BUILDING/STORAGE/STRUCTURE LEASES, OPER | FARMERS & TRADERS COMMISSION  | 840            | 
| 2004        | AGRICULTURE | BUILDING LEASE PAYMENTS | BUILDING/STORAGE/STRUCTURE LEASES, OPER | HOLMAN, JAMES M               | 404.46         | 
| 2004        | AGRICULTURE | BUILDING LEASE PAYMENTS | BUILDING/STORAGE/STRUCTURE LEASES, OPER | HOOVER LEASING INC            | 1364.52        | 
| 2004        | AGRICULTURE | BUILDING LEASE PAYMENTS | BUILDING/STORAGE/STRUCTURE LEASES, OPER | HUNTER DEVELOPMENT CO INC     | 21084          | 
| 2004        | AGRICULTURE | BUILDING LEASE PAYMENTS | BUILDING/STORAGE/STRUCTURE LEASES, OPER | LESLIE PROPERTIES LLC         | 21600          | 
| 2004        | AGRICULTURE | BUILDING LEASE PAYMENTS | BUILDING/STORAGE/STRUCTURE LEASES, OPER | NORTH SHORE RESORT            | 150            | 
```