# Generation by Fuel Type

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/generation-by-fuel-type) |
| Metadata | [Link](https://data.austintexas.gov/api/views/ss6t-rumq) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/ss6t-rumq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/ss6t-rumq/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | ss6t-rumq |
| Name | Generation by Fuel Type |
| Attribution | Austin Energy |
| Category | Utility |
| Tags | power, generation, fuel type, coal, natural gas and oil, nuclear, renewable, energy |
| Created | 2016-07-12T20:35:01Z |
| Publication Date | 2016-10-13T20:27:07Z |

## Description

Austin Energy fuel types include coal, natural gas and oil, nuclear, and renewable. We also purchase some power from other power generators. Browse the percent of power generated annually by each type of fuel.

*Austin Energy participates in the competitive Texas market ? the Electric Reliability Council of Texas ? and sells all power generated into the market. Purchased Power is no longer considered a source of generation, so it is not included in the ?Generation by Fuel Type" data since 2014.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name              | Data Type     | Render Type   |
| ======== | ============== | ================ | ================= | ============= | ============= |
| Yes      | time           | fiscal_year_2    | Fiscal Year       | calendar_date | calendar_date |
| Yes      | numeric metric | coal             | Coal              | percent       | percent       |
| Yes      | numeric metric | natural_gas_oil  | Natural Gas & Oil | percent       | percent       |
| Yes      | numeric metric | nuclear          | Nuclear           | percent       | percent       |
| Yes      | numeric metric | renewable_energy | Renewable Energy  | percent       | percent       |
| Yes      | numeric metric | purchased_power  | Purchased Power   | percent       | percent       |
```

## Time Field

```ls
Value = fiscal_year_2
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:ss6t-rumq d:2006-10-01T00:00:00.000Z m:nuclear=27.3 m:renewable_energy=5.7 m:purchased_power=9.4 m:coal=29.7 m:natural_gas_oil=27.9

series e:ss6t-rumq d:2007-10-01T00:00:00.000Z m:nuclear=25.8 m:renewable_energy=5.1 m:purchased_power=9.6 m:coal=32.2 m:natural_gas_oil=27.3

series e:ss6t-rumq d:2008-10-01T00:00:00.000Z m:nuclear=27.1 m:renewable_energy=6.1 m:purchased_power=7.9 m:coal=33.2 m:natural_gas_oil=25.7
```

## Meta Commands

```ls
metric m:coal p:float l:Coal t:dataTypeName=percent

metric m:natural_gas_oil p:float l:"Natural Gas & Oil" t:dataTypeName=percent

metric m:nuclear p:double l:Nuclear t:dataTypeName=percent

metric m:renewable_energy p:double l:"Renewable Energy" t:dataTypeName=percent

metric m:purchased_power p:float l:"Purchased Power" t:dataTypeName=percent

entity e:ss6t-rumq l:"Generation by Fuel Type" t:attribution="Austin Energy" t:url=https://data.austintexas.gov/api/views/ss6t-rumq

property e:ss6t-rumq t:meta.view v:id=ss6t-rumq v:category=Utility v:averageRating=0 v:name="Generation by Fuel Type" v:attribution="Austin Energy"

property e:ss6t-rumq t:meta.view.license v:name="Public Domain"

property e:ss6t-rumq t:meta.view.owner v:id=c433-zrb5 v:profileImageUrlMedium=/api/users/c433-zrb5/profile_images/THUMB v:profileImageUrlLarge=/api/users/c433-zrb5/profile_images/LARGE v:screenName="Sarah Lambert" v:profileImageUrlSmall=/api/users/c433-zrb5/profile_images/TINY v:displayName="Sarah Lambert"

property e:ss6t-rumq t:meta.view.tableauthor v:id=c433-zrb5 v:profileImageUrlMedium=/api/users/c433-zrb5/profile_images/THUMB v:profileImageUrlLarge=/api/users/c433-zrb5/profile_images/LARGE v:screenName="Sarah Lambert" v:profileImageUrlSmall=/api/users/c433-zrb5/profile_images/TINY v:roleName=publisher v:displayName="Sarah Lambert"
```

## Top Records

```ls
| fiscal_year_2       | coal | natural_gas_oil | nuclear | renewable_energy | purchased_power | 
| =================== | ==== | =============== | ======= | ================ | =============== | 
| 2006-10-01T00:00:00 | 29.7 | 27.9            | 27.3    | 5.7              | 9.4             | 
| 2007-10-01T00:00:00 | 32.2 | 27.3            | 25.8    | 5.1              | 9.6             | 
| 2008-10-01T00:00:00 | 33.2 | 25.7            | 27.1    | 6.1              | 7.9             | 
| 2009-10-01T00:00:00 | 28.3 | 26.5            | 26.4    | 9.5              | 9.3             | 
| 2010-10-01T00:00:00 | 32.5 | 22.3            | 25.2    | 9.7              | 10.3            | 
| 2011-10-01T00:00:00 | 28.9 | 25.8            | 21.3    | 9.5              | 14.5            | 
| 2012-10-01T00:00:00 | 27.0 | 20.3            | 21.9    | 15.0             | 15.8            | 
| 2013-10-01T00:00:00 | 25.9 | 15.7            | 22.8    | 20.7             | 14.9            | 
| 2014-10-01T00:00:00 | 32.1 | 15.3            | 26.9    | 25.5             |                 | 
| 2015-10-01T00:00:00 | 27   | 18              | 29      | 26               |                 | 
```