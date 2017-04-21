# Maui County Fuel Tax Allocation (by Island)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/maui-county-fuel-tax-allocation-by-island) |
| Metadata | [Link](https://data.hawaii.gov/api/views/vqnr-9t47) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/vqnr-9t47/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/vqnr-9t47/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | vqnr-9t47 |
| Name | Maui County Fuel Tax Allocation (by Island) |
| Created | 2015-01-29T21:31:36Z |
| Publication Date | 2015-09-21T22:03:43Z |

## Description

The Maui County Fuel Tax Allocation by island, which is 99% of what is collected, as is reported on tax form M-20A.

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type     | Render Type   |
| ======== | ============== | ======================= | ======================= | ============= | ============= |
| Yes      | series tag     | fuel_tax_by_maui_county | FUEL TAX BY MAUI COUNTY | text          | text          |
| Yes      | numeric metric | amount                  | AMOUNT                  | money         | money         |
| Yes      | time           | date                    | DATE                    | calendar_date | calendar_date |
| Yes      | series tag     | month                   | MONTH                   | text          | text          |
| No       |                | year                    | YEAR                    | number        | text          |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = year
```

## Data Commands

```ls
series e:vqnr-9t47 d:1999-01-31T00:00:00.000Z t:fuel_tax_by_maui_county=Lanai t:month=01 m:amount=0

series e:vqnr-9t47 d:1999-01-31T00:00:00.000Z t:fuel_tax_by_maui_county=Molokai t:month=01 m:amount=0

series e:vqnr-9t47 d:1999-01-31T00:00:00.000Z t:fuel_tax_by_maui_county=Maui t:month=01 m:amount=571537.7
```

## Meta Commands

```ls
metric m:amount p:double l:AMOUNT t:dataTypeName=money

entity e:vqnr-9t47 l:"Maui County Fuel Tax Allocation (by Island)" t:url=https://data.hawaii.gov/api/views/vqnr-9t47

property e:vqnr-9t47 t:meta.view v:id=vqnr-9t47 v:averageRating=0 v:name="Maui County Fuel Tax Allocation (by Island)"

property e:vqnr-9t47 t:meta.view.owner v:id=vx5q-wjs8 v:screenName=ninomid v:displayName=ninomid

property e:vqnr-9t47 t:meta.view.tableauthor v:id=vx5q-wjs8 v:screenName=ninomid v:roleName=publisher v:displayName=ninomid
```

## Top Records

```ls
| fuel_tax_by_maui_county | amount    | date                | month | year | 
| ======================= | ========= | =================== | ===== | ==== | 
| Lanai                   | 0         | 1999-01-31T00:00:00 | 01    | 1999 | 
| Molokai                 | 0         | 1999-01-31T00:00:00 | 01    | 1999 | 
| Maui                    | 571537.70 | 1999-01-31T00:00:00 | 01    | 1999 | 
| Lanai                   | 3.3       | 1999-02-28T00:00:00 | 02    | 1999 | 
| Molokai                 | 41.16     | 1999-02-28T00:00:00 | 02    | 1999 | 
| Maui                    | 649006.37 | 1999-02-28T00:00:00 | 02    | 1999 | 
| Lanai                   | 7.93      | 1999-03-31T00:00:00 | 03    | 1999 | 
| Molokai                 | 75.11     | 1999-03-31T00:00:00 | 03    | 1999 | 
| Maui                    | 688873.33 | 1999-03-31T00:00:00 | 03    | 1999 | 
| Lanai                   | 4.46      | 1999-04-30T00:00:00 | 04    | 1999 | 
```