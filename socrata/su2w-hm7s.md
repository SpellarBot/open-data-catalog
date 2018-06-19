# Choose Maryland: Compare States - Utilities

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/choose-maryland-compare-states-utilities) |
| Metadata | [Link](https://data.maryland.gov/api/views/su2w-hm7s) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/su2w-hm7s/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/su2w-hm7s/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | su2w-hm7s |
| Name | Choose Maryland: Compare States - Utilities |
| Attribution | Maryland Department of Commerce |
| Category | Energy and Environment |
| Tags | maryland, state, compare, utilities, electric, natural gas |
| Created | 2013-08-19T17:33:22Z |
| Publication Date | 2017-03-07T16:59:54Z |

## Description

Average industrial and commercial unit prices for natural gas and electric energy.

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                                                                      | Data Type | Render Type |
| ======== | ============== | ====================== | ========================================================================= | ========= | =========== |
| No       | time           | :updated_at            | updated_at                                                                | meta_data | meta_data   |
| Yes      | series tag     | state                  | State                                                                     | text      | text        |
| Yes      | numeric metric | electric_commercial    | Average Retail Price Per kWh, Commercial (Cents)                          | number    | number      |
| Yes      | numeric metric | electric_industrial    | Average Retail Price Per kWh, Industrial (Cents)                          | number    | number      |
| Yes      | numeric metric | natural_gas_commercial | Natural Gas, Average Cost per Thousand Cubic Feet, Commercial ($ Dollars) | money     | money       |
| Yes      | numeric metric | natural_gas_industrial | Natural Gas, Average Cost per Thousand Cubic Feet, Industrial ($ Dollars) | money     | money       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:su2w-hm7s d:2017-03-07T16:59:30.000Z t:state=Alabama m:electric_commercial=11.12 m:natural_gas_industrial=4.08 m:electric_industrial=6.08 m:natural_gas_commercial=11.26

series e:su2w-hm7s d:2017-03-07T16:59:30.000Z t:state=Alaska m:electric_commercial=18.19 m:natural_gas_industrial=6.86 m:electric_industrial=15.56 m:natural_gas_commercial=8.01

series e:su2w-hm7s d:2017-03-07T16:59:30.000Z t:state=Arizona m:electric_commercial=10.49 m:natural_gas_industrial=6.78 m:electric_industrial=6.07 m:natural_gas_commercial=10.53
```

## Meta Commands

```ls
metric m:electric_commercial p:float l:"Average Retail Price Per kWh, Commercial (Cents)" t:dataTypeName=number

metric m:electric_industrial p:float l:"Average Retail Price Per kWh, Industrial (Cents)" t:dataTypeName=number

metric m:natural_gas_commercial p:double l:"Natural Gas, Average Cost per Thousand Cubic Feet, Commercial ($ Dollars)" t:dataTypeName=money

metric m:natural_gas_industrial p:double l:"Natural Gas, Average Cost per Thousand Cubic Feet, Industrial ($ Dollars)" t:dataTypeName=money

entity e:su2w-hm7s l:"Choose Maryland:  Compare States - Utilities" t:attribution="Maryland Department of Commerce" t:url=https://data.maryland.gov/api/views/su2w-hm7s

property e:su2w-hm7s t:meta.view v:id=su2w-hm7s v:category="Energy and Environment" v:attributionLink=http://commerce.maryland.gov v:averageRating=0 v:name="Choose Maryland:  Compare States - Utilities" v:attribution="Maryland Department of Commerce"

property e:su2w-hm7s t:meta.view.owner v:id=m2gt-bxeg v:screenName="Mike Grandel" v:displayName="Mike Grandel"

property e:su2w-hm7s t:meta.view.tableauthor v:id=m2gt-bxeg v:screenName="Mike Grandel" v:roleName=editor v:displayName="Mike Grandel"
```

## Top Records

```ls
| :updated_at | state       | electric_commercial | electric_industrial | natural_gas_commercial | natural_gas_industrial | 
| =========== | =========== | =================== | =================== | ====================== | ====================== | 
| 1488905970  | Alabama     | 11.12               | 6.08                | 11.26                  | 4.08                   | 
| 1488905970  | Alaska      | 18.19               | 15.56               | 8.01                   | 6.86                   | 
| 1488905970  | Arizona     | 10.49               | 6.07                | 10.53                  | 6.78                   | 
| 1488905970  | Arkansas    | 8.13                | 5.93                | 8.43                   | 6.91                   | 
| 1488905970  | California  | 15.15               | 12.07               | 8.04                   | 6.41                   | 
| 1488905970  | Colorado    | 9.66                | 7.13                | 7.47                   | 5.74                   | 
| 1488905970  | Connecticut | 15.72               | 13.02               | 8.60                   | 6.35                   | 
| 1488905970  | Delaware    | 10.12               | 7.98                | 10.70                  | 10.11                  | 
| 1488905970  | Florida     | 9.11                | 7.81                | 10.92                  | 6.43                   | 
| 1488905970  | Georgia     | 9.63                | 5.64                | 8.58                   | 4.42                   | 
```