# 2016 State Expenditures As Of COB June 30, 2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2016-state-expenditures-as-of-cob-june-30-2016) |
| Metadata | [Link](https://data.mo.gov/api/views/s6qx-cm2s) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/s6qx-cm2s/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/s6qx-cm2s/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | s6qx-cm2s |
| Name | 2016 State Expenditures As Of COB June 30, 2016 |
| Attribution | Office of Administration |
| Category | Government Administration |
| Created | 2016-07-01T14:16:14Z |
| Publication Date | 2016-07-01T14:44:16Z |

## Description

Financial data relating to the purchases of goods and services by the state as well as financial disbursements through various state programs. Current as of the close of business June 30, 2016

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
series e:s6qx-cm2s d:2016-01-01T00:00:00.000Z t:category_description="BUILDING LEASE PAYMENTS" t:detail_description="BUILDING/STORAGE/STRUCTURE LEASES, OPER" t:agency_name=AGRICULTURE t:vendor_name="AA ALL STOR" m:payments_total=6174

series e:s6qx-cm2s d:2016-01-01T00:00:00.000Z t:category_description="BUILDING LEASE PAYMENTS" t:detail_description="BUILDING/STORAGE/STRUCTURE LEASES, OPER" t:agency_name=AGRICULTURE t:vendor_name="COUNTY OF AUDRAIN-COMMISSIONER" m:payments_total=750

series e:s6qx-cm2s d:2016-01-01T00:00:00.000Z t:category_description="BUILDING LEASE PAYMENTS" t:detail_description="BUILDING/STORAGE/STRUCTURE LEASES, OPER" t:agency_name=AGRICULTURE t:vendor_name="COURTOIS, HAROLD" m:payments_total=624.36
```

## Meta Commands

```ls
metric m:payments_total p:double l:"Payments Total" t:dataTypeName=money

entity e:s6qx-cm2s l:"2016 State Expenditures As Of COB June 30, 2016" t:attribution="Office of Administration" t:url=https://data.mo.gov/api/views/s6qx-cm2s

property e:s6qx-cm2s t:meta.view d:2017-06-09T13:56:40.303Z v:id=s6qx-cm2s v:category="Government Administration" v:averageRating=0 v:name="2016 State Expenditures As Of COB June 30, 2016" v:attribution="Office of Administration"

property e:s6qx-cm2s t:meta.view.owner d:2017-06-09T13:56:40.303Z v:id=4cdh-4my4 v:screenName=Dwight v:displayName=Dwight

property e:s6qx-cm2s t:meta.view.tableauthor d:2017-06-09T13:56:40.303Z v:id=4cdh-4my4 v:screenName=Dwight v:roleName=editor v:displayName=Dwight
```

## Top Records

```ls
| fiscal_year | agency_name | category_description    | detail_description                      | vendor_name                    | payments_total | 
| =========== | =========== | ======================= | ======================================= | ============================== | ============== | 
| 2016        | AGRICULTURE | BUILDING LEASE PAYMENTS | BUILDING/STORAGE/STRUCTURE LEASES, OPER | AA ALL STOR                    | 6174           | 
| 2016        | AGRICULTURE | BUILDING LEASE PAYMENTS | BUILDING/STORAGE/STRUCTURE LEASES, OPER | COUNTY OF AUDRAIN-COMMISSIONER | 750            | 
| 2016        | AGRICULTURE | BUILDING LEASE PAYMENTS | BUILDING/STORAGE/STRUCTURE LEASES, OPER | COURTOIS, HAROLD               | 624.36         | 
| 2016        | AGRICULTURE | BUILDING LEASE PAYMENTS | BUILDING/STORAGE/STRUCTURE LEASES, OPER | FARMERS & TRADERS COMMISSION   | 770            | 
| 2016        | AGRICULTURE | BUILDING LEASE PAYMENTS | BUILDING/STORAGE/STRUCTURE LEASES, OPER | FOXFIRE WEST MINI STORAGE      | 1620           | 
| 2016        | AGRICULTURE | BUILDING LEASE PAYMENTS | BUILDING/STORAGE/STRUCTURE LEASES, OPER | HUNTER DEVELOPMENT CO INC      | 24849          | 
| 2016        | AGRICULTURE | BUILDING LEASE PAYMENTS | BUILDING/STORAGE/STRUCTURE LEASES, OPER | OZARK JAR LLC                  | 144076.07      | 
| 2016        | AGRICULTURE | BUILDING LEASE PAYMENTS | BUILDING/STORAGE/STRUCTURE LEASES, OPER | WHITAKER, STEVEN H             | 760            | 
| 2016        | AGRICULTURE | BUILDING LEASE PAYMENTS | LEASEHOLD IMPROVEMENTS, OPERATING       | OZARK JAR LLC                  | 11965.65       | 
| 2016        | AGRICULTURE | BUILDING LEASE PAYMENTS | MEETING ROOM/EXHIBIT SPACE RENTALS      | AKEY FARMS INC                 | 250            | 
```