# 2009 State Expenditures

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2009-state-expenditures-9c649) |
| Metadata | [Link](https://data.mo.gov/api/views/fasu-dfdu) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/fasu-dfdu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/fasu-dfdu/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | fasu-dfdu |
| Name | 2009 State Expenditures |
| Attribution | Office of Administration |
| Category | Government Administration |
| Created | 2012-05-15T15:02:51Z |
| Publication Date | 2012-05-15T15:08:39Z |

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
series e:fasu-dfdu d:2009-01-01T00:00:00.000Z t:category_description="BUILDING LEASE PAYMENTS" t:detail_description="BUILDING/STORAGE/STRUCTURE LEASES, OPER" t:agency_name=AGRICULTURE t:vendor_name="AA ALL STOR" m:payments_total=7200

series e:fasu-dfdu d:2009-01-01T00:00:00.000Z t:category_description="BUILDING LEASE PAYMENTS" t:detail_description="BUILDING/STORAGE/STRUCTURE LEASES, OPER" t:agency_name=AGRICULTURE t:vendor_name="BRM 2002 LLC" m:payments_total=116194.8

series e:fasu-dfdu d:2009-01-01T00:00:00.000Z t:category_description="BUILDING LEASE PAYMENTS" t:detail_description="BUILDING/STORAGE/STRUCTURE LEASES, OPER" t:agency_name=AGRICULTURE t:vendor_name="COUNTY OF AUDRAIN-COMMISSIONER" m:payments_total=900
```

## Meta Commands

```ls
metric m:payments_total p:double l:"Payments Total" t:dataTypeName=money

entity e:fasu-dfdu l:"2009 State Expenditures" t:attribution="Office of Administration" t:url=https://data.mo.gov/api/views/fasu-dfdu

property e:fasu-dfdu t:meta.view v:id=fasu-dfdu v:category="Government Administration" v:averageRating=0 v:name="2009 State Expenditures" v:attribution="Office of Administration"

property e:fasu-dfdu t:meta.view.owner v:id=wzcj-jrcg v:screenName=John v:displayName=John

property e:fasu-dfdu t:meta.view.tableauthor v:id=wzcj-jrcg v:screenName=John v:roleName=editor v:displayName=John
```

## Top Records

```ls
| fiscal_year | agency_name | category_description    | detail_description                      | vendor_name                    | payments_total | 
| =========== | =========== | ======================= | ======================================= | ============================== | ============== | 
| 2009        | AGRICULTURE | BUILDING LEASE PAYMENTS | BUILDING/STORAGE/STRUCTURE LEASES, OPER | AA ALL STOR                    | 7200           | 
| 2009        | AGRICULTURE | BUILDING LEASE PAYMENTS | BUILDING/STORAGE/STRUCTURE LEASES, OPER | BRM 2002 LLC                   | 116194.8       | 
| 2009        | AGRICULTURE | BUILDING LEASE PAYMENTS | BUILDING/STORAGE/STRUCTURE LEASES, OPER | COUNTY OF AUDRAIN-COMMISSIONER | 900            | 
| 2009        | AGRICULTURE | BUILDING LEASE PAYMENTS | BUILDING/STORAGE/STRUCTURE LEASES, OPER | FARMERS & TRADERS COMMISSION   | 840            | 
| 2009        | AGRICULTURE | BUILDING LEASE PAYMENTS | BUILDING/STORAGE/STRUCTURE LEASES, OPER | HUNTER DEVELOPMENT CO INC      | 22966.5        | 
| 2009        | AGRICULTURE | BUILDING LEASE PAYMENTS | BUILDING/STORAGE/STRUCTURE LEASES, OPER | OZARK JAR LLC                  | 151659         | 
| 2009        | AGRICULTURE | BUILDING LEASE PAYMENTS | BUILDING/STORAGE/STRUCTURE LEASES, OPER | TILLMAN PROPERTIES             | 577.32         | 
| 2009        | AGRICULTURE | BUILDING LEASE PAYMENTS | MEETING ROOM/EXHIBIT SPACE RENTALS      | ADAMS POINTE CONFERENCE CENTER | 2838.25        | 
| 2009        | AGRICULTURE | BUILDING LEASE PAYMENTS | MEETING ROOM/EXHIBIT SPACE RENTALS      | CAPITAL ELECTRIC               | 95             | 
| 2009        | AGRICULTURE | BUILDING LEASE PAYMENTS | MEETING ROOM/EXHIBIT SPACE RENTALS      | CLARION HOTEL                  | 991.25         | 
```