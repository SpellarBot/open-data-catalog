# 2012 State Expenditures as of COB June 30, 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2012-state-expenditures-as-of-cob-june-30-2012-20487) |
| Metadata | [Link](https://data.mo.gov/api/views/wv59-xa9p) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/wv59-xa9p/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/wv59-xa9p/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | wv59-xa9p |
| Name | 2012 State Expenditures as of COB June 30, 2012 |
| Category | Government |
| Tags | government expenditures |
| Created | 2012-07-02T16:29:42Z |
| Publication Date | 2012-07-02T16:34:19Z |

## Description

Financial data relating to the purchases of goods and services by the state as well as financial disbursements through various state programs for fiscal year 2012 as of June30, 2012.

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type | Render Type |
| ======== | ============== | ==================== | ==================== | ========= | =========== |
| Yes      | time           | fiscal_year          | Fiscal Year          | number    | number      |
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
series e:wv59-xa9p d:2012-01-01T00:00:00.000Z t:category_description="BUILDING LEASE PAYMENTS" t:detail_description="BUILDING/STORAGE/STRUCTURE LEASES, OPER" t:agency_name=AGRICULTURE t:vendor_name="AA ALL STOR" m:payments_total=6345

series e:wv59-xa9p d:2012-01-01T00:00:00.000Z t:category_description="BUILDING LEASE PAYMENTS" t:detail_description="BUILDING/STORAGE/STRUCTURE LEASES, OPER" t:agency_name=AGRICULTURE t:vendor_name="COUNTY OF AUDRAIN-COMMISSIONER" m:payments_total=900

series e:wv59-xa9p d:2012-01-01T00:00:00.000Z t:category_description="BUILDING LEASE PAYMENTS" t:detail_description="BUILDING/STORAGE/STRUCTURE LEASES, OPER" t:agency_name=AGRICULTURE t:vendor_name="FARMERS & TRADERS COMMISSION" m:payments_total=770
```

## Meta Commands

```ls
metric m:payments_total p:double l:"Payments Total" t:dataTypeName=money

entity e:wv59-xa9p l:"2012 State Expenditures as of COB June 30, 2012" t:url=https://data.mo.gov/api/views/wv59-xa9p

property e:wv59-xa9p t:meta.view v:id=wv59-xa9p v:category=Government v:averageRating=0 v:name="2012 State Expenditures as of COB June 30, 2012"

property e:wv59-xa9p t:meta.view.owner v:id=29n3-s86h v:screenName="Carolyn Aggeler" v:displayName="Carolyn Aggeler"

property e:wv59-xa9p t:meta.view.tableauthor v:id=29n3-s86h v:screenName="Carolyn Aggeler" v:roleName=editor v:displayName="Carolyn Aggeler"
```

## Top Records

```ls
| fiscal_year | agency_name | category_description    | detail_description                      | vendor_name                    | payments_total | 
| =========== | =========== | ======================= | ======================================= | ============================== | ============== | 
| 2012        | AGRICULTURE | BUILDING LEASE PAYMENTS | BUILDING/STORAGE/STRUCTURE LEASES, OPER | AA ALL STOR                    | 6345           | 
| 2012        | AGRICULTURE | BUILDING LEASE PAYMENTS | BUILDING/STORAGE/STRUCTURE LEASES, OPER | COUNTY OF AUDRAIN-COMMISSIONER | 900            | 
| 2012        | AGRICULTURE | BUILDING LEASE PAYMENTS | BUILDING/STORAGE/STRUCTURE LEASES, OPER | FARMERS & TRADERS COMMISSION   | 770            | 
| 2012        | AGRICULTURE | BUILDING LEASE PAYMENTS | BUILDING/STORAGE/STRUCTURE LEASES, OPER | HUNTER DEVELOPMENT CO INC      | 24849          | 
| 2012        | AGRICULTURE | BUILDING LEASE PAYMENTS | BUILDING/STORAGE/STRUCTURE LEASES, OPER | OZARK JAR LLC                  | 151659         | 
| 2012        | AGRICULTURE | BUILDING LEASE PAYMENTS | BUILDING/STORAGE/STRUCTURE LEASES, OPER | WILDWOOD REAL ESTATE CO INC    | 2983.41        | 
| 2012        | AGRICULTURE | BUILDING LEASE PAYMENTS | LEASEHOLD IMPROVEMENTS, OPERATING       | OZARK JAR LLC                  | 1625.8         | 
| 2012        | AGRICULTURE | BUILDING LEASE PAYMENTS | MEETING ROOM/EXHIBIT SPACE RENTALS      | BAYMONT INN & SUITES           | 244            | 
| 2012        | AGRICULTURE | BUILDING LEASE PAYMENTS | MEETING ROOM/EXHIBIT SPACE RENTALS      | COLE COUNTY EXTENSION CENTER   | 1300           | 
| 2012        | AGRICULTURE | BUILDING LEASE PAYMENTS | MEETING ROOM/EXHIBIT SPACE RENTALS      | CURATORS OF THE UNIVERSITY OF  | 200            | 
```