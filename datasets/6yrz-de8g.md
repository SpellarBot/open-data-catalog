# System Fuel Cost Average

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/system-fuel-cost-average) |
| Metadata | [Link](https://data.austintexas.gov/api/views/6yrz-de8g) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/6yrz-de8g/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/6yrz-de8g/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | 6yrz-de8g |
| Name | System Fuel Cost Average |
| Attribution | Austin Energy |
| Category | Utility |
| Tags | system fuel cost average, energy, austin energy |
| Created | 2016-08-02T16:13:33Z |
| Publication Date | 2016-09-30T19:13:42Z |

## Description

The system fuel cost average is the cost of fuel purchased divided by the number of kilowatts generated. Scan data for annual system fuel cost averages starting in 2006.

## Columns

```ls
| Included | Schema Type    | Field Name                                | Name                                        | Data Type     | Render Type   |
| ======== | ============== | ========================================= | =========================================== | ============= | ============= |
| Yes      | time           | fiscal_year_2                             | Fiscal Year                                 | calendar_date | calendar_date |
| Yes      | numeric metric | system_annual_average_fuel_cost_cents_kwh | System annual average fuel cost (cents/kWh) | number        | number        |
```

## Time Field

```ls
Value = fiscal_year_2
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:6yrz-de8g d:2006-09-01T00:00:00.000Z m:system_annual_average_fuel_cost_cents_kwh=3.178

series e:6yrz-de8g d:2007-09-01T00:00:00.000Z m:system_annual_average_fuel_cost_cents_kwh=2.905

series e:6yrz-de8g d:2008-09-01T00:00:00.000Z m:system_annual_average_fuel_cost_cents_kwh=3.655
```

## Meta Commands

```ls
metric m:system_annual_average_fuel_cost_cents_kwh p:float l:"System annual average fuel cost (cents/kWh)" t:dataTypeName=number

entity e:6yrz-de8g l:"System Fuel Cost Average" t:attribution="Austin Energy" t:url=https://data.austintexas.gov/api/views/6yrz-de8g

property e:6yrz-de8g t:meta.view v:id=6yrz-de8g v:category=Utility v:averageRating=0 v:name="System Fuel Cost Average" v:attribution="Austin Energy"

property e:6yrz-de8g t:meta.view.license v:name="Public Domain"

property e:6yrz-de8g t:meta.view.owner v:id=c433-zrb5 v:profileImageUrlMedium=/api/users/c433-zrb5/profile_images/THUMB v:profileImageUrlLarge=/api/users/c433-zrb5/profile_images/LARGE v:screenName="Sarah Lambert" v:profileImageUrlSmall=/api/users/c433-zrb5/profile_images/TINY v:displayName="Sarah Lambert"

property e:6yrz-de8g t:meta.view.tableauthor v:id=c433-zrb5 v:profileImageUrlMedium=/api/users/c433-zrb5/profile_images/THUMB v:profileImageUrlLarge=/api/users/c433-zrb5/profile_images/LARGE v:screenName="Sarah Lambert" v:profileImageUrlSmall=/api/users/c433-zrb5/profile_images/TINY v:roleName=publisher v:displayName="Sarah Lambert"
```

## Top Records

```ls
| fiscal_year_2       | system_annual_average_fuel_cost_cents_kwh | 
| =================== | ========================================= | 
| 2006-09-01T00:00:00 | 3.178                                     | 
| 2007-09-01T00:00:00 | 2.905                                     | 
| 2008-09-01T00:00:00 | 3.655                                     | 
| 2009-09-01T00:00:00 | 3.371                                     | 
| 2010-09-01T00:00:00 | 3.446                                     | 
| 2011-09-01T00:00:00 | 3.523                                     | 
| 2012-09-01T00:00:00 | 3.225                                     | 
| 2013-09-01T00:00:00 | 3.495                                     | 
| 2014-09-01T00:00:00 | 3.815                                     | 
| 2015-09-01T00:00:00 | 3.314                                     | 
```