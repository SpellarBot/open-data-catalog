# 2015 State Expenditures As Of COB June 30, 2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2015-state-expenditures-as-of-cob-june-30-2015) |
| Metadata | [Link](https://data.mo.gov/api/views/9kfi-jsmi) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/9kfi-jsmi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/9kfi-jsmi/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | 9kfi-jsmi |
| Name | 2015 State Expenditures As Of COB June 30, 2015 |
| Category | Government Administration |
| Created | 2015-07-02T15:12:03Z |
| Publication Date | 2015-07-02T15:15:52Z |

## Description

Financial data relating to the purchases of goods and services by the state as well as financial disbursements through various state programs. Current as of the close of business June 30, 2015

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type | Render Type |
| ======== | ============== | ==================== | ==================== | ========= | =========== |
| Yes      | time           | fiscal_year          | Fiscal Year          | number    | text        |
| Yes      | series tag     | agency_name          | Agency Name          | text      | text        |
| Yes      | series tag     | category_description | Category Description | text      | text        |
| Yes      | series tag     | detail_description   | Detail Description   | text      | text        |
| Yes      | series tag     | vendor_name          | Vendor Name          | text      | text        |
| Yes      | numeric metric | payments_total       | Payments Total       | number    | number      |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:9kfi-jsmi d:2015-01-01T00:00:00.000Z t:category_description="BUILDING LEASE PAYMENTS" t:detail_description="BUILDING/STORAGE/STRUCTURE LEASES, OPER" t:agency_name=AGRICULTURE t:vendor_name="AA ALL STOR" m:payments_total=6174

series e:9kfi-jsmi d:2015-01-01T00:00:00.000Z t:category_description="BUILDING LEASE PAYMENTS" t:detail_description="BUILDING/STORAGE/STRUCTURE LEASES, OPER" t:agency_name=AGRICULTURE t:vendor_name="COUNTY OF AUDRAIN-COMMISSIONER" m:payments_total=900

series e:9kfi-jsmi d:2015-01-01T00:00:00.000Z t:category_description="BUILDING LEASE PAYMENTS" t:detail_description="BUILDING/STORAGE/STRUCTURE LEASES, OPER" t:agency_name=AGRICULTURE t:vendor_name="COURTOIS, HAROLD" m:payments_total=52.03
```

## Meta Commands

```ls
metric m:payments_total p:decimal l:"Payments Total" t:dataTypeName=number

entity e:9kfi-jsmi l:"2015 State Expenditures As Of COB June 30, 2015" t:url=https://data.mo.gov/api/views/9kfi-jsmi

property e:9kfi-jsmi t:meta.view v:id=9kfi-jsmi v:category="Government Administration" v:averageRating=0 v:name="2015 State Expenditures As Of COB June 30, 2015"

property e:9kfi-jsmi t:meta.view.license v:name="Public Domain"

property e:9kfi-jsmi t:meta.view.owner v:id=4cdh-4my4 v:screenName=Dwight v:displayName=Dwight

property e:9kfi-jsmi t:meta.view.tableauthor v:id=4cdh-4my4 v:screenName=Dwight v:roleName=editor v:displayName=Dwight
```

## Top Records

```ls
| fiscal_year | agency_name | category_description    | detail_description                      | vendor_name                    | payments_total | 
| =========== | =========== | ======================= | ======================================= | ============================== | ============== | 
| 2015        | AGRICULTURE | BUILDING LEASE PAYMENTS | BUILDING/STORAGE/STRUCTURE LEASES, OPER | AA ALL STOR                    | 6174.00        | 
| 2015        | AGRICULTURE | BUILDING LEASE PAYMENTS | BUILDING/STORAGE/STRUCTURE LEASES, OPER | COUNTY OF AUDRAIN-COMMISSIONER | 900            | 
| 2015        | AGRICULTURE | BUILDING LEASE PAYMENTS | BUILDING/STORAGE/STRUCTURE LEASES, OPER | COURTOIS, HAROLD               | 52.03          | 
| 2015        | AGRICULTURE | BUILDING LEASE PAYMENTS | BUILDING/STORAGE/STRUCTURE LEASES, OPER | FARMERS & TRADERS COMMISSION   | 770            | 
| 2015        | AGRICULTURE | BUILDING LEASE PAYMENTS | BUILDING/STORAGE/STRUCTURE LEASES, OPER | FOXFIRE WEST MINI STORAGE      | 835.00         | 
| 2015        | AGRICULTURE | BUILDING LEASE PAYMENTS | BUILDING/STORAGE/STRUCTURE LEASES, OPER | HUNTER DEVELOPMENT CO INC      | 24849.00       | 
| 2015        | AGRICULTURE | BUILDING LEASE PAYMENTS | BUILDING/STORAGE/STRUCTURE LEASES, OPER | OZARK JAR LLC                  | 144076.08      | 
| 2015        | AGRICULTURE | BUILDING LEASE PAYMENTS | BUILDING/STORAGE/STRUCTURE LEASES, OPER | WHITAKER, STEVEN H             | 720.00         | 
| 2015        | AGRICULTURE | BUILDING LEASE PAYMENTS | LEASEHOLD IMPROVEMENTS, OPERATING       | OZARK JAR LLC                  | 5850.00        | 
| 2015        | AGRICULTURE | BUILDING LEASE PAYMENTS | MEETING ROOM/EXHIBIT SPACE RENTALS      | BUCHANAN COUNTY EXTENSION      | 350.00         | 
```