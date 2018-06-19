# 2011 State Expenditures

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2011-state-expenditures-62a06) |
| Metadata | [Link](https://data.mo.gov/api/views/nyk8-k9ti) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/nyk8-k9ti/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/nyk8-k9ti/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | nyk8-k9ti |
| Name | 2011 State Expenditures |
| Attribution | Office of Administration |
| Category | Government Administration |
| Created | 2012-02-15T22:11:47Z |
| Publication Date | 2012-02-15T22:34:56Z |

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
series e:nyk8-k9ti d:2011-01-01T00:00:00.000Z t:category_description="FUEL & UTILITIES" t:detail_description=ELECTRICITY t:agency_name=AGRICULTURE t:vendor_name="AMERENUE-ST LOUIS" m:payments_total=284.32

series e:nyk8-k9ti d:2011-01-01T00:00:00.000Z t:category_description="OTHER EQUIPMENT" t:detail_description="OTHER EQUIPMENT" t:agency_name=AGRICULTURE t:vendor_name=GRAINGER m:payments_total=609.82

series e:nyk8-k9ti d:2011-01-01T00:00:00.000Z t:category_description="PROFESSIONAL SERVICES" t:detail_description="VETERINARIAN SERVICES" t:agency_name=AGRICULTURE t:vendor_name="USA EQUESTRIAN" m:payments_total=2580
```

## Meta Commands

```ls
metric m:payments_total p:double l:"Payments Total" t:dataTypeName=money

entity e:nyk8-k9ti l:"2011 State Expenditures" t:attribution="Office of Administration" t:url=https://data.mo.gov/api/views/nyk8-k9ti

property e:nyk8-k9ti t:meta.view v:id=nyk8-k9ti v:category="Government Administration" v:averageRating=0 v:name="2011 State Expenditures" v:attribution="Office of Administration"

property e:nyk8-k9ti t:meta.view.owner v:id=wzcj-jrcg v:screenName=John v:displayName=John

property e:nyk8-k9ti t:meta.view.tableauthor v:id=8xqn-4t42 v:profileImageUrlMedium=/api/users/8xqn-4t42/profile_images/THUMB v:profileImageUrlLarge=/api/users/8xqn-4t42/profile_images/LARGE v:screenName="Rodney Distler" v:profileImageUrlSmall=/api/users/8xqn-4t42/profile_images/TINY v:roleName=publisher v:displayName="Rodney Distler"
```

## Top Records

```ls
| fiscal_year | agency_name          | category_description     | detail_description             | vendor_name         | payments_total | 
| =========== | ==================== | ======================== | ============================== | =================== | ============== | 
| 2011        | AGRICULTURE          | FUEL & UTILITIES         | ELECTRICITY                    | AMERENUE-ST LOUIS   | 284.32         | 
| 2011        | AGRICULTURE          | OTHER EQUIPMENT          | OTHER EQUIPMENT                | GRAINGER            | 609.82         | 
| 2011        | AGRICULTURE          | PROFESSIONAL SERVICES    | VETERINARIAN SERVICES          | USA EQUESTRIAN      | 2580.00        | 
| 2011        | AGRICULTURE          | SUPPLIES                 | POSTAGE                        | WANKUM, DARREN J    | 48.40          | 
| 2011        | CONSERVATION         | FUEL & UTILITIES         | ELECTRICITY                    | AMELON, GEORGE      | 1664.78        | 
| 2011        | CONSERVATION         | FUEL & UTILITIES         | WATER & SEWAGE                 | PIEDMONT WATER DEPT | 369.70         | 
| 2011        | CONSERVATION         | PROFESSIONAL DEVELOPMENT | OTHER PROFESSIONAL DEVELOPMENT | ESRI                | 2716.42        | 
| 2011        | CORRECTIONS          | SUPPLIES                 | CLOTHING SUPPLIES              | CHARM-TEX           | 9770.54        | 
| 2011        | CORRECTIONS          | SUPPLIES                 | MANUFACTURING SUPPLIES         | STEEL YARD, THE     | 2335.63        | 
| 2011        | ECONOMIC DEVELOPMENT | PROFESSIONAL DEVELOPMENT | TUITION EXPENSES               | WIEBE, LESLIE       | 100.00         | 
```