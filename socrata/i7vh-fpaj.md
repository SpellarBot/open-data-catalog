# Green Building Energy Code Compliance

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/green-building-energy-code-compliance) |
| Metadata | [Link](https://data.austintexas.gov/api/views/i7vh-fpaj) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/i7vh-fpaj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/i7vh-fpaj/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | i7vh-fpaj |
| Name | Green Building Energy Code Compliance |
| Attribution | Austin Energy |
| Category | Utility |
| Tags | austin energy, green building, code, compliance, conservation |
| Created | 2016-12-15T22:18:12Z |
| Publication Date | 2017-01-30T15:45:21Z |

## Description

Austin Energy Green Building is responsible for development of the City of Austin Energy Code. The 2007 Austin Climate Protection Plan established the 2000 International Energy Conservation Code (IECC) with Austin Amendments as a baseline to compare energy savings for each successive energy code adoption.  Calculated deemed energy savings are modeled using representative buildings for each of the construction types ? single family, multifamily, and commercial and applied to permitted new construction buildings. While the Austin Energy Code has a positive impact on remodeling and renovation of existing buildings, these savings are not included.  Energy code compliance contributes to the goals of the Austin Climate Protection Plan to reach 900 MW of peak demand savings by 2025, benefits Austin Energy customers with lower utility bills and reduces greenhouse gas emissions.

## Columns

```ls
| Included | Schema Type    | Field Name                                    | Name                                  | Data Type     | Render Type   |
| ======== | ============== | ============================================= | ===================================== | ============= | ============= |
| Yes      | time           | fiscal_year                                   | Fiscal Year                           | calendar_date | calendar_date |
| Yes      | numeric metric | number_of_residential_building_permits        | # of Residential Building Permits     | number        | number        |
| Yes      | numeric metric | residential_energy_code_savings_kw            | Residential Energy Code Savings (kW)  | number        | number        |
| Yes      | numeric metric | residential_energy_code_savings_mwh           | Residential Energy Code Savings (MWh) | number        | number        |
| Yes      | numeric metric | number_of_multifamily_unit_permits            | # of Multifamily Unit Permits         | number        | number        |
| Yes      | numeric metric | multifamily_energy_code_savings_kw            | Multifamily Energy Code Savings (kW)  | number        | number        |
| Yes      | numeric metric | multifamily_energy_code_savings_mwh           | Multifamily Energy Code Savings (MWh) | number        | number        |
| Yes      | numeric metric | square_footage_of_commercial_building_permits | Commercial Building Permits (sq. ft.) | number        | number        |
| Yes      | numeric metric | commercial_energy_code_savings_kw             | Commercial Energy Code Savings (kW)   | number        | number        |
| Yes      | numeric metric | commercial_energy_code_savings_mwh            | Commercial Energy Code Savings (MWh)  | number        | number        |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:i7vh-fpaj d:2016-01-01T00:00:00.000Z m:residential_energy_code_savings_mwh=15336 m:multifamily_energy_code_savings_mwh=5658 m:square_footage_of_commercial_building_permits=5114000 m:residential_energy_code_savings_kw=12119 m:number_of_residential_building_permits=4056 m:commercial_energy_code_savings_kw=9072 m:multifamily_energy_code_savings_kw=6802 m:number_of_multifamily_unit_permits=7722 m:commercial_energy_code_savings_mwh=23471

series e:i7vh-fpaj d:2015-01-01T00:00:00.000Z m:residential_energy_code_savings_mwh=11960 m:multifamily_energy_code_savings_mwh=4684 m:square_footage_of_commercial_building_permits=7393000 m:residential_energy_code_savings_kw=8566 m:number_of_residential_building_permits=2890 m:commercial_energy_code_savings_kw=10394 m:multifamily_energy_code_savings_kw=6818 m:number_of_multifamily_unit_permits=7498 m:commercial_energy_code_savings_mwh=31410

series e:i7vh-fpaj d:2014-01-01T00:00:00.000Z m:residential_energy_code_savings_mwh=11397 m:multifamily_energy_code_savings_mwh=10504 m:square_footage_of_commercial_building_permits=4699182 m:residential_energy_code_savings_kw=8163 m:number_of_residential_building_permits=2754 m:commercial_energy_code_savings_kw=4593 m:multifamily_energy_code_savings_kw=6901 m:number_of_multifamily_unit_permits=7803 m:commercial_energy_code_savings_mwh=15404
```

## Meta Commands

```ls
metric m:number_of_residential_building_permits p:integer l:"# of Residential Building Permits" t:dataTypeName=number

metric m:residential_energy_code_savings_kw p:integer l:"Residential Energy Code Savings (kW)" t:dataTypeName=number

metric m:residential_energy_code_savings_mwh p:integer l:"Residential Energy Code Savings (MWh)" t:dataTypeName=number

metric m:number_of_multifamily_unit_permits p:integer l:"# of Multifamily Unit Permits" t:dataTypeName=number

metric m:multifamily_energy_code_savings_kw p:integer l:"Multifamily Energy Code Savings (kW)" t:dataTypeName=number

metric m:multifamily_energy_code_savings_mwh p:integer l:"Multifamily Energy Code Savings (MWh)" t:dataTypeName=number

metric m:square_footage_of_commercial_building_permits p:integer l:"Commercial Building Permits (sq. ft.)" t:dataTypeName=number

metric m:commercial_energy_code_savings_kw p:integer l:"Commercial Energy Code Savings (kW)" t:dataTypeName=number

metric m:commercial_energy_code_savings_mwh p:integer l:"Commercial Energy Code Savings (MWh)" t:dataTypeName=number

entity e:i7vh-fpaj l:"Green Building Energy Code Compliance" t:attribution="Austin Energy" t:url=https://data.austintexas.gov/api/views/i7vh-fpaj

property e:i7vh-fpaj t:meta.view v:id=i7vh-fpaj v:category=Utility v:averageRating=0 v:name="Green Building Energy Code Compliance" v:attribution="Austin Energy"

property e:i7vh-fpaj t:meta.view.license v:name="Public Domain"

property e:i7vh-fpaj t:meta.view.owner v:id=c433-zrb5 v:profileImageUrlMedium=/api/users/c433-zrb5/profile_images/THUMB v:profileImageUrlLarge=/api/users/c433-zrb5/profile_images/LARGE v:screenName="Sarah Lambert" v:profileImageUrlSmall=/api/users/c433-zrb5/profile_images/TINY v:displayName="Sarah Lambert"

property e:i7vh-fpaj t:meta.view.tableauthor v:id=c433-zrb5 v:profileImageUrlMedium=/api/users/c433-zrb5/profile_images/THUMB v:profileImageUrlLarge=/api/users/c433-zrb5/profile_images/LARGE v:screenName="Sarah Lambert" v:profileImageUrlSmall=/api/users/c433-zrb5/profile_images/TINY v:roleName=publisher v:displayName="Sarah Lambert"
```

## Top Records

```ls
| fiscal_year         | number_of_residential_building_permits | residential_energy_code_savings_kw | residential_energy_code_savings_mwh | number_of_multifamily_unit_permits | multifamily_energy_code_savings_kw | multifamily_energy_code_savings_mwh | square_footage_of_commercial_building_permits | commercial_energy_code_savings_kw | commercial_energy_code_savings_mwh | 
| =================== | ====================================== | ================================== | =================================== | ================================== | ================================== | =================================== | ============================================= | ================================= | ================================== | 
| 2016-01-01T00:00:00 | 4056                                   | 12119                              | 15336                               | 7722                               | 6802                               | 5658                                | 5114000                                       | 9072                              | 23471                              | 
| 2015-01-01T00:00:00 | 2890                                   | 8566                               | 11960                               | 7498                               | 6818                               | 4684                                | 7393000                                       | 10394                             | 31410                              | 
| 2014-01-01T00:00:00 | 2754                                   | 8163                               | 11397                               | 7803                               | 6901                               | 10504                               | 4699182                                       | 4593                              | 15404                              | 
| 2013-01-01T00:00:00 | 2783                                   | 4542                               | 10878                               | 8580                               | 5766                               | 12219                               | 2835734                                       | 3132                              | 8735                               | 
| 2012-01-01T00:00:00 | 2394                                   | 3907                               | 9357                                | 5631                               | 3784                               | 8020                                | 1457912                                       | 2430                              | 5814                               | 
| 2011-01-01T00:00:00 | 1857                                   | 3005                               | 7258                                | 1800                               | 1200                               | 2564                                | 928153                                        | 3285                              | 8006                               | 
| 2010-01-01T00:00:00 | 1909                                   | 3158                               | 5137                                | 266                                | 132                                | 281                                 | 852118                                        | 1424                              | 4138                               | 
| 2009-01-01T00:00:00 | 1738                                   | 2875                               | 4677                                | 2260                               | 1022                               | 2176                                | 1844015                                       | 3102                              | 9011                               | 
| 2008-01-01T00:00:00 | 2941                                   | 4865                               | 7914                                | 4805                               | 2173                               | 4627                                | 3629050                                       | 5212                              | 14590                              | 
| 2007-01-01T00:00:00 | 5270                                   | 6898                               | 5639                                | 6056                               | 2739                               | 5832                                | 2166891                                       | 3181                              | 8923                               | 
```