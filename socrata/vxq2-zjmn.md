# Solar Program Current Incentive Levels and Available Capacity

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/solar-program-current-incentive-levels-and-available-capacity) |
| Metadata | [Link](https://data.austintexas.gov/api/views/vxq2-zjmn) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/vxq2-zjmn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/vxq2-zjmn/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | vxq2-zjmn |
| Name | Solar Program Current Incentive Levels and Available Capacity |
| Attribution | Austin Energy |
| Category | Utility |
| Tags | solar, rebate |
| Created | 2015-08-21T19:07:43Z |
| Publication Date | 2017-03-20T18:14:51Z |

## Description

This data can be used to track the capacity and incentive levels available for Austin Energy's Solar Rebate Program.

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                              | Data Type     | Render Type   |
| ======== | ============== | ======================== | ================================= | ============= | ============= |
| Yes      | series tag     | program                  | Program and Incentive Level       | text          | text          |
| Yes      | numeric metric | capacity_requested_kw_ac | Capacity Requested kW-ac          | number        | number        |
| Yes      | numeric metric | capacity_reserved_kw_ac  | Capacity Reserved/Installed kW-ac | number        | number        |
| Yes      | numeric metric | capacity_available_kw_ac | Capacity Available kW-ac          | number        | number        |
| Yes      | time           | date_last_updated        | Date last updated                 | calendar_date | calendar_date |
```

## Time Field

```ls
Value = date_last_updated
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:vxq2-zjmn d:2015-08-24T00:00:00.000Z t:program="Residential - $1.00/Watt - Closed" m:capacity_reserved_kw_ac=1000 m:capacity_available_kw_ac=0 m:capacity_requested_kw_ac=0

series e:vxq2-zjmn d:2015-11-09T00:00:00.000Z t:program="Residential - $0.90/Watt - Closed" m:capacity_reserved_kw_ac=1500 m:capacity_available_kw_ac=0 m:capacity_requested_kw_ac=0

series e:vxq2-zjmn d:2015-12-07T00:00:00.000Z t:program="Small Commercial - $0.08/kWh Closed" m:capacity_reserved_kw_ac=500 m:capacity_available_kw_ac=0 m:capacity_requested_kw_ac=0
```

## Meta Commands

```ls
metric m:capacity_requested_kw_ac p:integer l:"Capacity Requested kW-ac" t:dataTypeName=number

metric m:capacity_reserved_kw_ac p:integer l:"Capacity Reserved/Installed kW-ac" t:dataTypeName=number

metric m:capacity_available_kw_ac p:integer l:"Capacity Available kW-ac" t:dataTypeName=number

entity e:vxq2-zjmn l:"Solar Program Current Incentive Levels and Available Capacity" t:attribution="Austin Energy" t:url=https://data.austintexas.gov/api/views/vxq2-zjmn

property e:vxq2-zjmn t:meta.view v:id=vxq2-zjmn v:category=Utility v:averageRating=0 v:name="Solar Program Current Incentive Levels and Available Capacity" v:attribution="Austin Energy"

property e:vxq2-zjmn t:meta.view.license v:name="Public Domain"

property e:vxq2-zjmn t:meta.view.owner v:id=fxfz-wsmq v:profileImageUrlMedium=/api/users/fxfz-wsmq/profile_images/THUMB v:profileImageUrlLarge=/api/users/fxfz-wsmq/profile_images/LARGE v:screenName="Shannon Wisner" v:profileImageUrlSmall=/api/users/fxfz-wsmq/profile_images/TINY v:displayName="Shannon Wisner"

property e:vxq2-zjmn t:meta.view.tableauthor v:id=fxfz-wsmq v:profileImageUrlMedium=/api/users/fxfz-wsmq/profile_images/THUMB v:profileImageUrlLarge=/api/users/fxfz-wsmq/profile_images/LARGE v:screenName="Shannon Wisner" v:profileImageUrlSmall=/api/users/fxfz-wsmq/profile_images/TINY v:roleName=publisher v:displayName="Shannon Wisner"
```

## Top Records

```ls
| program                             | capacity_requested_kw_ac | capacity_reserved_kw_ac | capacity_available_kw_ac | date_last_updated   | 
| =================================== | ======================== | ======================= | ======================== | =================== | 
| Residential - $1.00/Watt - Closed   | 0                        | 1000                    | 0                        | 2015-08-24T00:00:00 | 
| Residential - $0.90/Watt - Closed   | 0                        | 1500                    | 0                        | 2015-11-09T00:00:00 | 
| Small Commercial - $0.08/kWh Closed | 0                        | 500                     | 0                        | 2015-12-07T00:00:00 | 
| Residential - $0.80/Watt - Closed   | 0                        | 4000                    | 0                        | 2016-09-14T00:00:00 | 
| Medium Commercial - $0.05/kWh       | 0                        | 259                     | 1241                     | 2017-01-06T00:00:00 | 
| Small Commercial - $0.05/kWh        | 0                        | 0                       | 2000                     | 2017-01-06T00:00:00 | 
| Medium Commercial - $0.04/kWh       | 0                        | 0                       | 1500                     | 2017-01-06T00:00:00 | 
| Residential - $0.50/Watt            | 0                        | 0                       | 2500                     | 2017-01-06T00:00:00 | 
| Medium Commercial - $0.03/kWh       | 0                        | 0                       | 1500                     | 2017-01-06T00:00:00 | 
| Residential - $0.70/Watt Closed     | 808                      | 1692                    | 0                        | 2017-02-13T00:00:00 | 
```