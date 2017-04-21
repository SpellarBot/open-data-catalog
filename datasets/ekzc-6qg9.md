# Heat Rate

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/heat-rate) |
| Metadata | [Link](https://data.austintexas.gov/api/views/ekzc-6qg9) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/ekzc-6qg9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/ekzc-6qg9/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | ekzc-6qg9 |
| Name | Heat Rate |
| Attribution | Austin Energy |
| Category | Utility |
| Tags | "heat rate", btu |
| Created | 2015-08-17T14:50:44Z |
| Publication Date | 2016-07-07T20:09:30Z |

## Description

The heat rate is the number of British Thermal Units (BTU) needed to produce a kilowatt-hour (kWh) of electricity. In other words, the average heat rate is a measurement of how efficiently a generating unit converts fuel into electricity. The lower the heat rate, the higher the efficiency. 
 
The system average heat rate will vary somewhat year-to-year due to a number of factors including outages and market conditions. The approximately one percent increase for FY 2012 was primarily due to lower demand and lower natural gas prices which resulted in lower dispatch of Fayette Power Project (FPP). The reduced levels of production mean that units operated at lower, less efficient levels.

## Columns

```ls
| Included | Schema Type    | Field Name                                  | Name                                          | Data Type | Render Type |
| ======== | ============== | =========================================== | ============================================= | ========= | =========== |
| Yes      | time           | fiscal_year                                 | Fiscal Year                                   | number    | number      |
| Yes      | numeric metric | system_annual_average_heat_rate_btu_net_kwh | System annual average heat rate (BTU/net kWh) | number    | number      |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ekzc-6qg9 d:2013-01-01T00:00:00.000Z m:system_annual_average_heat_rate_btu_net_kwh=9972

series e:ekzc-6qg9 d:2012-01-01T00:00:00.000Z m:system_annual_average_heat_rate_btu_net_kwh=10050

series e:ekzc-6qg9 d:2011-01-01T00:00:00.000Z m:system_annual_average_heat_rate_btu_net_kwh=9943
```

## Meta Commands

```ls
metric m:system_annual_average_heat_rate_btu_net_kwh p:integer l:"System annual average heat rate (BTU/net kWh)" t:dataTypeName=number

entity e:ekzc-6qg9 l:"Heat Rate" t:attribution="Austin Energy" t:url=https://data.austintexas.gov/api/views/ekzc-6qg9

property e:ekzc-6qg9 t:meta.view v:id=ekzc-6qg9 v:category=Utility v:averageRating=0 v:name="Heat Rate" v:attribution="Austin Energy"

property e:ekzc-6qg9 t:meta.view.license v:name="Public Domain"

property e:ekzc-6qg9 t:meta.view.owner v:id=fxfz-wsmq v:profileImageUrlMedium=/api/users/fxfz-wsmq/profile_images/THUMB v:profileImageUrlLarge=/api/users/fxfz-wsmq/profile_images/LARGE v:screenName="Shannon Wisner" v:profileImageUrlSmall=/api/users/fxfz-wsmq/profile_images/TINY v:displayName="Shannon Wisner"

property e:ekzc-6qg9 t:meta.view.tableauthor v:id=fxfz-wsmq v:profileImageUrlMedium=/api/users/fxfz-wsmq/profile_images/THUMB v:profileImageUrlLarge=/api/users/fxfz-wsmq/profile_images/LARGE v:screenName="Shannon Wisner" v:profileImageUrlSmall=/api/users/fxfz-wsmq/profile_images/TINY v:roleName=publisher v:displayName="Shannon Wisner"
```

## Top Records

```ls
| fiscal_year | system_annual_average_heat_rate_btu_net_kwh | 
| =========== | =========================================== | 
| 2013        | 9972                                        | 
| 2012        | 10050                                       | 
| 2011        | 9943                                        | 
| 2010        | 9884                                        | 
| 2009        | 9810                                        | 
| 2008        | 9803                                        | 
| 2007        | 9837                                        | 
| 2006        | 10040                                       | 
| 2014        | 10005                                       | 
```