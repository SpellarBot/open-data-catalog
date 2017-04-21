# 2010 State Expenditures

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2010-state-expenditures-c6a4e) |
| Metadata | [Link](https://data.mo.gov/api/views/3fvs-m4di) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/3fvs-m4di/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/3fvs-m4di/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | 3fvs-m4di |
| Name | 2010 State Expenditures |
| Attribution | Office of Administration |
| Category | Government Administration |
| Created | 2012-02-23T17:11:25Z |
| Publication Date | 2012-02-23T19:12:47Z |

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
series e:3fvs-m4di d:2010-01-01T00:00:00.000Z t:category_description="BUILDING LEASE PAYMENTS" t:detail_description="BUILDING/STORAGE/STRUCTURE LEASES, OPER" t:agency_name=AGRICULTURE t:vendor_name="AA ALL STOR" m:payments_total=7200

series e:3fvs-m4di d:2010-01-01T00:00:00.000Z t:category_description="BUILDING LEASE PAYMENTS" t:detail_description="BUILDING/STORAGE/STRUCTURE LEASES, OPER" t:agency_name=AGRICULTURE t:vendor_name="BRM 2002 LLC" m:payments_total=116194.8

series e:3fvs-m4di d:2010-01-01T00:00:00.000Z t:category_description="BUILDING LEASE PAYMENTS" t:detail_description="BUILDING/STORAGE/STRUCTURE LEASES, OPER" t:agency_name=AGRICULTURE t:vendor_name="COUNTY OF AUDRAIN-COMMISSIONER" m:payments_total=900
```

## Meta Commands

```ls
metric m:payments_total p:double l:"Payments Total" t:dataTypeName=money

entity e:3fvs-m4di l:"2010 State Expenditures" t:attribution="Office of Administration" t:url=https://data.mo.gov/api/views/3fvs-m4di

property e:3fvs-m4di t:meta.view v:id=3fvs-m4di v:category="Government Administration" v:averageRating=0 v:name="2010 State Expenditures" v:attribution="Office of Administration"

property e:3fvs-m4di t:meta.view.owner v:id=wzcj-jrcg v:screenName=John v:displayName=John

property e:3fvs-m4di t:meta.view.tableauthor v:id=wzcj-jrcg v:screenName=John v:roleName=editor v:displayName=John
```

## Top Records

```ls
| fiscal_year | agency_name | category_description    | detail_description                      | vendor_name                    | payments_total | 
| =========== | =========== | ======================= | ======================================= | ============================== | ============== | 
| 2010        | AGRICULTURE | BUILDING LEASE PAYMENTS | BUILDING/STORAGE/STRUCTURE LEASES, OPER | AA ALL STOR                    | 7200.00        | 
| 2010        | AGRICULTURE | BUILDING LEASE PAYMENTS | BUILDING/STORAGE/STRUCTURE LEASES, OPER | BRM 2002 LLC                   | 116194.80      | 
| 2010        | AGRICULTURE | BUILDING LEASE PAYMENTS | BUILDING/STORAGE/STRUCTURE LEASES, OPER | COUNTY OF AUDRAIN-COMMISSIONER | 900.00         | 
| 2010        | AGRICULTURE | BUILDING LEASE PAYMENTS | BUILDING/STORAGE/STRUCTURE LEASES, OPER | FARMERS & TRADERS COMMISSION   | 840.00         | 
| 2010        | AGRICULTURE | BUILDING LEASE PAYMENTS | BUILDING/STORAGE/STRUCTURE LEASES, OPER | HUNTER DEVELOPMENT CO INC      | 24849.00       | 
| 2010        | AGRICULTURE | BUILDING LEASE PAYMENTS | BUILDING/STORAGE/STRUCTURE LEASES, OPER | NEW CAPITAL CITY WAREHOUSE CO  | 2965.42        | 
| 2010        | AGRICULTURE | BUILDING LEASE PAYMENTS | BUILDING/STORAGE/STRUCTURE LEASES, OPER | OZARK JAR LLC                  | 151659.00      | 
| 2010        | AGRICULTURE | BUILDING LEASE PAYMENTS | BUILDING/STORAGE/STRUCTURE LEASES, OPER | TILLMAN PROPERTIES             | 577.32         | 
| 2010        | AGRICULTURE | BUILDING LEASE PAYMENTS | LEASEHOLD IMPROVEMENTS, OPERATING       | BRM 2002 LLC                   | 7150.00        | 
| 2010        | AGRICULTURE | BUILDING LEASE PAYMENTS | MEETING ROOM/EXHIBIT SPACE RENTALS      | ADAMS POINTE CONFERENCE CENTER | 2520.00        | 
```