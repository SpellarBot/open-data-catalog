# On- Site Energy Resources

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/on-site-energy-resources) |
| Metadata | [Link](https://data.austintexas.gov/api/views/ktsk-a3bg) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/ktsk-a3bg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/ktsk-a3bg/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | ktsk-a3bg |
| Name | On- Site Energy Resources |
| Attribution | Austin Energy |
| Category | Utility |
| Tags | energy resources, cooling plants, energy |
| Created | 2016-09-12T12:57:38Z |
| Publication Date | 2016-11-15T16:34:10Z |

## Description

On-Site Energy Resources (OSER) is the business unit that operates Austin Energy's district cooling plants. On-Site Energy Resources provides chilled water to 69 large customers cooling more than 19 million square feet of commercial, retail and residential space. OSER has capacity for shifting up to 110 megawatt hours (MWh) of summer peak demand. View the projects, year installed, fuel type, and more. Visit austinenergy.com/go/onsiteenergysystems to learn more.

## Columns

```ls
| Included | Schema Type    | Field Name                       | Name                             | Data Type     | Render Type   |
| ======== | ============== | ================================ | ================================ | ============= | ============= |
| Yes      | series tag     | project                          | Project                          | text          | text          |
| Yes      | time           | installed_2                      | Installed                        | calendar_date | calendar_date |
| Yes      | series tag     | fuel_type                        | Fuel Type                        | text          | text          |
| Yes      | numeric metric | tons_of_chilled_water            | Tons of Chilled Water            | number        | number        |
| Yes      | numeric metric | ton_hours_of_thermal_storage     | Ton Hours of Thermal Storage     | number        | number        |
| Yes      | numeric metric | lbs_per_hour_of_heating_capacity | Lbs Per Hour of Heating Capacity | number        | number        |
| Yes      | numeric metric | generation_capacity_mw           | Generation Capacity (MW)         | number        | number        |
```

## Time Field

```ls
Value = installed_2
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:ktsk-a3bg d:2001-01-01T00:00:00.000Z t:project="Downtown, Paul Robbins Plant" t:fuel_type=Electric m:ton_hours_of_thermal_storage=26200 m:tons_of_chilled_water=6000

series e:ktsk-a3bg d:2001-01-01T00:00:00.000Z t:project=Domain t:fuel_type=Electric m:tons_of_chilled_water=10000

series e:ktsk-a3bg d:2006-01-01T00:00:00.000Z t:project="Mueller Energy Center" t:fuel_type=Electric m:lbs_per_hour_of_heating_capacity=70000 m:ton_hours_of_thermal_storage=8000 m:tons_of_chilled_water=7200
```

## Meta Commands

```ls
metric m:tons_of_chilled_water p:integer l:"Tons of Chilled Water" t:dataTypeName=number

metric m:ton_hours_of_thermal_storage p:integer l:"Ton Hours of Thermal Storage" t:dataTypeName=number

metric m:lbs_per_hour_of_heating_capacity p:integer l:"Lbs Per Hour of Heating Capacity" t:dataTypeName=number

metric m:generation_capacity_mw p:float l:"Generation Capacity (MW)" t:dataTypeName=number

entity e:ktsk-a3bg l:"On- Site Energy Resources" t:attribution="Austin Energy" t:url=https://data.austintexas.gov/api/views/ktsk-a3bg

property e:ktsk-a3bg t:meta.view v:id=ktsk-a3bg v:category=Utility v:averageRating=0 v:name="On- Site Energy Resources" v:attribution="Austin Energy"

property e:ktsk-a3bg t:meta.view.license v:name="Public Domain"

property e:ktsk-a3bg t:meta.view.owner v:id=c433-zrb5 v:profileImageUrlMedium=/api/users/c433-zrb5/profile_images/THUMB v:profileImageUrlLarge=/api/users/c433-zrb5/profile_images/LARGE v:screenName="Sarah Lambert" v:profileImageUrlSmall=/api/users/c433-zrb5/profile_images/TINY v:displayName="Sarah Lambert"

property e:ktsk-a3bg t:meta.view.tableauthor v:id=c433-zrb5 v:profileImageUrlMedium=/api/users/c433-zrb5/profile_images/THUMB v:profileImageUrlLarge=/api/users/c433-zrb5/profile_images/LARGE v:screenName="Sarah Lambert" v:profileImageUrlSmall=/api/users/c433-zrb5/profile_images/TINY v:roleName=publisher v:displayName="Sarah Lambert"
```

## Top Records

```ls
| project                      | installed_2         | fuel_type   | tons_of_chilled_water | ton_hours_of_thermal_storage | lbs_per_hour_of_heating_capacity | generation_capacity_mw | 
| ============================ | =================== | =========== | ===================== | ============================ | ================================ | ====================== | 
| Downtown, Paul Robbins Plant | 2001-01-01T00:00:00 | Electric    | 6000                  | 26200                        |                                  |                        | 
| Domain                       | 2001-01-01T00:00:00 | Electric    | 10000                 |                              |                                  |                        | 
| Mueller Energy Center        | 2006-01-01T00:00:00 | Electric    | 7200                  | 8000                         | 70000                            |                        | 
| Mueller Energy Center        | 2006-01-01T00:00:00 | Natural Gas |                       |                              |                                  | 4.6                    | 
| Downtown, DCP-2              | 2007-01-01T00:00:00 | Electric    | 10000                 | 52400                        |                                  |                        | 
```