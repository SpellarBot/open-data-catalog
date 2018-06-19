# IHDA - Illinois Housing Dev Auth - FY2010 Governor's Report - Closings.Multi-Family

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ihda-illinois-housing-dev-auth-fy2010-governors-report-closings-multi-family-d7ba6) |
| Metadata | [Link](https://data.illinois.gov/api/views/m2dq-yv7x) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/m2dq-yv7x/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/m2dq-yv7x/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | m2dq-yv7x |
| Name | IHDA - Illinois Housing Dev Auth - FY2010 Governor's Report - Closings.Multi-Family |
| Category | Housing |
| Tags | ihda, illinois housing development authority |
| Created | 2012-01-25T15:06:14Z |
| Publication Date | 2012-01-25T22:00:59Z |

## Description

FY2010 Governor's Report - Closings.Multi-Family

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| Yes      | time           | fiscal_year       | FISCAL YEAR       | number    | text        |
| Yes      | series tag     | project_name      | PROJECT NAME      | text      | text        |
| No       |                | project_address   | PROJECT ADDRESS   | text      | text        |
| Yes      | series tag     | project_city      | PROJECT CITY      | text      | text        |
| Yes      | series tag     | owner             | OWNER             | text      | text        |
| Yes      | series tag     | type_of_financing | TYPE OF FINANCING | text      | text        |
| No       |                | closing_date      | CLOSING DATE      | text      | text        |
| Yes      | numeric metric | amount            | AMOUNT            | money     | text        |
| Yes      | numeric metric | units             | UNITS             | number    | text        |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = project_address,closing_date
```

## Data Commands

```ls
series e:m2dq-yv7x d:2010-01-01T00:00:00.000Z t:project_name="Willow Heights Apartments" t:owner="Willow Heights Apartment Associates Limited Partnership" t:type_of_financing=Conduit t:project_city=Decatur m:amount=3000000 m:units=64
```

## Meta Commands

```ls
metric m:amount p:long l:AMOUNT t:dataTypeName=money

metric m:units p:integer l:UNITS t:dataTypeName=number

entity e:m2dq-yv7x l:"IHDA - Illinois Housing Dev Auth - FY2010 Governor's Report - Closings.Multi-Family" t:url=https://data.illinois.gov/api/views/m2dq-yv7x

property e:m2dq-yv7x t:meta.view v:id=m2dq-yv7x v:category=Housing v:averageRating=0 v:name="IHDA - Illinois Housing Dev Auth - FY2010 Governor's Report - Closings.Multi-Family"

property e:m2dq-yv7x t:meta.view.owner v:id=i46z-zq8e v:screenName="Larry Michalski" v:displayName="Larry Michalski"

property e:m2dq-yv7x t:meta.view.tableauthor v:id=i46z-zq8e v:screenName="Larry Michalski" v:roleName=publisher v:displayName="Larry Michalski"
```

## Top Records

```ls
| fiscal_year | project_name              | project_address     | project_city | owner                                                   | type_of_financing | closing_date | amount     | units | 
| =========== | ========================= | =================== | ============ | ======================================================= | ================= | ============ | ========== | ===== | 
| 2010        | Willow Heights Apartments | 1460 Wellington Way | Decatur      | Willow Heights Apartment Associates Limited Partnership | Conduit           | 2/16/2010    | $3,000,000 | 64    | 
```