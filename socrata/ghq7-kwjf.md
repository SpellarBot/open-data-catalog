# Liquid Fuel Tax Base and Tax Collections

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/liquid-fuel-tax-base-and-tax-collections) |
| Metadata | [Link](https://data.hawaii.gov/api/views/ghq7-kwjf) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/ghq7-kwjf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/ghq7-kwjf/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | ghq7-kwjf |
| Name | Liquid Fuel Tax Base and Tax Collections |
| Created | 2015-01-29T23:00:33Z |
| Publication Date | 2015-09-21T22:00:29Z |

## Description

This series shows quantities and tax amounts for fuel subject to fuel taxes or to the environmental response tax. The quantities and taxes are broken down by county and by type of fuel.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type     | Render Type   |
| ======== | ============== | ================= | ================= | ============= | ============= |
| Yes      | series tag     | source_of_revenue | SOURCE OF REVENUE | text          | text          |
| Yes      | numeric metric | gallons           | GALLONS           | number        | number        |
| Yes      | numeric metric | state_tax         | STATE TAX         | money         | money         |
| Yes      | numeric metric | cty_fuel_tax      | CTY FUEL TAX      | money         | money         |
| Yes      | numeric metric | total_tax         | TOTAL TAX         | money         | money         |
| Yes      | series tag     | county            | COUNTY            | text          | text          |
| Yes      | time           | date              | DATE              | calendar_date | calendar_date |
| Yes      | series tag     | month             | MONTH             | text          | text          |
| No       |                | year              | YEAR              | number        | text          |
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
series e:ghq7-kwjf d:1999-01-31T00:00:00.000Z t:county=HONOLULU t:month=01 t:source_of_revenue=Gasoline m:cty_fuel_tax=3673730 m:gallons=22265030.31 m:state_tax=3562404.85 m:total_tax=7236134.85

series e:ghq7-kwjf d:1999-01-31T00:00:00.000Z t:county=HONOLULU t:month=01 t:source_of_revenue="DO (non-hwy)" m:gallons=7256705 m:state_tax=72567.05 m:total_tax=72567.05

series e:ghq7-kwjf d:1999-01-31T00:00:00.000Z t:county=HONOLULU t:month=01 t:source_of_revenue="DO (hwy use)" m:cty_fuel_tax=219831.87 m:gallons=1332314.34 m:state_tax=213170.29 m:total_tax=433002.16
```

## Meta Commands

```ls
metric m:gallons p:double l:GALLONS t:dataTypeName=number

metric m:state_tax p:double l:"STATE TAX" t:dataTypeName=money

metric m:cty_fuel_tax p:double l:"CTY FUEL TAX" t:dataTypeName=money

metric m:total_tax p:double l:"TOTAL TAX" t:dataTypeName=money

entity e:ghq7-kwjf l:"Liquid Fuel Tax Base and Tax Collections" t:url=https://data.hawaii.gov/api/views/ghq7-kwjf

property e:ghq7-kwjf t:meta.view v:id=ghq7-kwjf v:averageRating=0 v:name="Liquid Fuel Tax Base and Tax Collections"

property e:ghq7-kwjf t:meta.view.owner v:id=vx5q-wjs8 v:screenName=ninomid v:displayName=ninomid

property e:ghq7-kwjf t:meta.view.tableauthor v:id=vx5q-wjs8 v:screenName=ninomid v:roleName=publisher v:displayName=ninomid
```

## Top Records

```ls
| source_of_revenue | gallons     | state_tax  | cty_fuel_tax | total_tax  | county   | date                | month | year | 
| ================= | =========== | ========== | ============ | ========== | ======== | =================== | ===== | ==== | 
| Gasoline          | 22265030.31 | 3562404.85 | 3673730.00   | 7236134.85 | HONOLULU | 1999-01-31T00:00:00 | 01    | 1999 | 
| DO (non-hwy)      | 7256705.00  | 72567.05   |              | 72567.05   | HONOLULU | 1999-01-31T00:00:00 | 01    | 1999 | 
| DO (hwy use)      | 1332314.34  | 213170.29  | 219831.87    | 433002.16  | HONOLULU | 1999-01-31T00:00:00 | 01    | 1999 | 
| LPG (off hwy)     | 41412.00    | 414.12     |              | 414.12     | HONOLULU | 1999-01-31T00:00:00 | 01    | 1999 | 
| LPG (hwy use)     | 3872.82     | 426.01     | 426.01       | 852.02     | HONOLULU | 1999-01-31T00:00:00 | 01    | 1999 | 
| SB (gas)          | 520.71      | 83.31      | 85.92        | 169.23     | HONOLULU | 1999-01-31T00:00:00 | 01    | 1999 | 
| SB (diesel oil)   | 780         | 7.8        |              | 7.8        | HONOLULU | 1999-01-31T00:00:00 | 01    | 1999 | 
| Aviation fuel     | 27591846.00 | 275918.46  |              | 275918.46  | HONOLULU | 1999-01-31T00:00:00 | 01    | 1999 | 
| Environmental Tax | 2216725.80  | 110836.29  |              | 110836.29  | HONOLULU | 1999-01-31T00:00:00 | 01    | 1999 | 
| Gasoline          | 4277090.82  | 675425.54  | 548300.68    | 1223726.22 | MAUI     | 1999-01-31T00:00:00 | 01    | 1999 | 
```