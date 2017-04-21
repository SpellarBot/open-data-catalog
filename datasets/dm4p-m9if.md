# Agricultural Use Refunds (Gasoline)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/agricultural-use-refunds-gasoline) |
| Metadata | [Link](https://data.hawaii.gov/api/views/dm4p-m9if) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/dm4p-m9if/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/dm4p-m9if/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | dm4p-m9if |
| Name | Agricultural Use Refunds (Gasoline) |
| Created | 2015-01-29T21:23:10Z |
| Publication Date | 2015-09-21T22:06:31Z |

## Description

Gasoline used for off-road consumption in agricultural production is subject to a tax of only 1 cent per gallon.  The user is eligible for a refund for any taxes paid on such gasoline in excess of 1 cent per gallon.

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type     | Render Type   |
| ======== | ============== | =============== | =============== | ============= | ============= |
| Yes      | series tag     | county          | COUNTY          | text          | text          |
| Yes      | numeric metric | gallons         | GALLONS         | number        | number        |
| Yes      | numeric metric | state_tax       | STATE TAX       | money         | money         |
| Yes      | numeric metric | county_fuel_tax | COUNTY FUEL TAX | money         | money         |
| Yes      | numeric metric | total_tax       | TOTAL TAX       | money         | money         |
| Yes      | time           | date            | DATE            | calendar_date | calendar_date |
| Yes      | series tag     | month           | MONTH           | text          | text          |
| No       |                | year            | YEAR            | number        | text          |
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
series e:dm4p-m9if d:1999-01-31T00:00:00.000Z t:county="City & County of Honolulu" t:month=01 m:gallons=0 m:county_fuel_tax=0 m:state_tax=0 m:total_tax=0

series e:dm4p-m9if d:1999-01-31T00:00:00.000Z t:county="County of Maui" t:month=01 m:gallons=59393.29 m:county_fuel_tax=7721.13 m:state_tax=8908.99 m:total_tax=16630.12

series e:dm4p-m9if d:1999-01-31T00:00:00.000Z t:county="County of Hawaii" t:month=01 m:gallons=0 m:county_fuel_tax=0 m:state_tax=0 m:total_tax=0
```

## Meta Commands

```ls
metric m:gallons p:float l:GALLONS t:dataTypeName=number

metric m:state_tax p:double l:"STATE TAX" t:dataTypeName=money

metric m:county_fuel_tax p:double l:"COUNTY FUEL TAX" t:dataTypeName=money

metric m:total_tax p:double l:"TOTAL TAX" t:dataTypeName=money

entity e:dm4p-m9if l:"Agricultural Use Refunds (Gasoline)" t:url=https://data.hawaii.gov/api/views/dm4p-m9if

property e:dm4p-m9if t:meta.view v:id=dm4p-m9if v:averageRating=0 v:name="Agricultural Use Refunds (Gasoline)"

property e:dm4p-m9if t:meta.view.owner v:id=vx5q-wjs8 v:screenName=ninomid v:displayName=ninomid

property e:dm4p-m9if t:meta.view.tableauthor v:id=vx5q-wjs8 v:screenName=ninomid v:roleName=publisher v:displayName=ninomid
```

## Top Records

```ls
| county                    | gallons  | state_tax | county_fuel_tax | total_tax | date                | month | year | 
| ========================= | ======== | ========= | =============== | ========= | =================== | ===== | ==== | 
| City & County of Honolulu | 0        | 0         | 0               | 0         | 1999-01-31T00:00:00 | 01    | 1999 | 
| County of Maui            | 59393.29 | 8908.99   | 7721.13         | 16630.12  | 1999-01-31T00:00:00 | 01    | 1999 | 
| County of Hawaii          | 0        | 0         | 0               | 0         | 1999-01-31T00:00:00 | 01    | 1999 | 
| County of Kauai           | 16050.00 | 2407.50   | 1605.00         | 4012.50   | 1999-01-31T00:00:00 | 01    | 1999 | 
| City & County of Honolulu | 1159.00  | 173.85    | 191.24          | 365.09    | 1999-02-28T00:00:00 | 02    | 1999 | 
| County of Maui            | 0        | 0         | 0               | 0         | 1999-02-28T00:00:00 | 02    | 1999 | 
| County of Hawaii          | 0        | 0         | 0               | 0         | 1999-02-28T00:00:00 | 02    | 1999 | 
| County of Kauai           | 331      | 49.65     | 33.1            | 82.75     | 1999-02-28T00:00:00 | 02    | 1999 | 
| City & County of Honolulu | 9922.79  | 1488.42   | 1637.26         | 3125.68   | 1999-03-31T00:00:00 | 03    | 1999 | 
| County of Maui            | 44959.89 | 6743.99   | 5844.78         | 12588.77  | 1999-03-31T00:00:00 | 03    | 1999 | 
```