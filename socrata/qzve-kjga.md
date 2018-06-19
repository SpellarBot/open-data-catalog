# Hourly Traffic on Metropolitan Transportation Authority (MTA) Bridges and Tunnels: Beginning 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/hourly-traffic-on-metropolitan-transportation-authority-mta-bridges-and-tunnels-beginning-) |
| Metadata | [Link](https://data.ny.gov/api/views/qzve-kjga) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/qzve-kjga/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/qzve-kjga/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | qzve-kjga |
| Name | Hourly Traffic on Metropolitan Transportation Authority (MTA) Bridges and Tunnels: Beginning 2010 |
| Attribution | MTA Bridges and Tunnels |
| Category | Transportation |
| Tags | bridges and tunnels, hourly traffic |
| Created | 2015-11-12T18:56:42Z |
| Publication Date | 2017-04-17T22:06:15Z |

## Description

This dataset provides data showing the number of vehicles (including cars, buses, trucks and motorcycles) that pass through each of the bridges and tunnels operated by the MTA each hour of the day. The data is updated weekly.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name                       | Data Type     | Render Type   |
| ======== | ============== | ================ | ========================== | ============= | ============= |
| Yes      | series tag     | plaza_id         | Plaza ID                   | text          | number        |
| Yes      | time           | date             | Date                       | calendar_date | calendar_date |
| Yes      | numeric metric | hour             | Hour                       | number        | number        |
| Yes      | series tag     | direction        | Direction                  | text          | text          |
| Yes      | numeric metric | vehicles_e_zpass | # Vehicles - ETC (E-ZPass) | number        | number        |
| Yes      | numeric metric | vehicles_cash    | # Vehicles - Cash          | number        | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:qzve-kjga d:2015-11-28T00:00:00.000Z t:direction=I t:plaza_id=1 m:vehicles_e_zpass=477 m:hour=0 m:vehicles_cash=205

series e:qzve-kjga d:2015-11-28T00:00:00.000Z t:direction=O t:plaza_id=1 m:vehicles_e_zpass=486 m:hour=0 m:vehicles_cash=252

series e:qzve-kjga d:2015-11-28T00:00:00.000Z t:direction=I t:plaza_id=1 m:vehicles_e_zpass=350 m:hour=1 m:vehicles_cash=171
```

## Meta Commands

```ls
metric m:hour p:integer l:Hour d:"The hour (0-23) associated with the line data (0 = between 12am and 1am." t:dataTypeName=number

metric m:vehicles_e_zpass p:integer l:"# Vehicles - ETC (E-ZPass)" d:"The number of vehicles that pass through each bridge or tunnel?s toll plaza using E-ZPass during each hour." t:dataTypeName=number

metric m:vehicles_cash p:integer l:"# Vehicles - Cash" d:"The number of vehicles that paid their tolls in cash during that hour. For HHB (plaza ID 4), this column is the traffic without valid tags for system to collect the payment at the time of passing the plaza. It will be tags payment by Mail with fine collected later." t:dataTypeName=number

entity e:qzve-kjga l:"Hourly Traffic on Metropolitan Transportation Authority (MTA) Bridges and Tunnels: Beginning 2010" t:attribution="MTA Bridges and Tunnels" t:url=https://data.ny.gov/api/views/qzve-kjga

property e:qzve-kjga t:meta.view v:id=qzve-kjga v:category=Transportation v:attributionLink=http://www.mta.info/developers/data/bandt/trafficdata.html v:averageRating=0 v:name="Hourly Traffic on Metropolitan Transportation Authority (MTA) Bridges and Tunnels: Beginning 2010" v:attribution="MTA Bridges and Tunnels"

property e:qzve-kjga t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:qzve-kjga t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| plaza_id | date                | hour | direction | vehicles_e_zpass | vehicles_cash | 
| ======== | =================== | ==== | ========= | ================ | ============= | 
| 1        | 2015-11-28T00:00:00 | 0    | I         | 477              | 205           | 
| 1        | 2015-11-28T00:00:00 | 0    | O         | 486              | 252           | 
| 1        | 2015-11-28T00:00:00 | 1    | I         | 350              | 171           | 
| 1        | 2015-11-28T00:00:00 | 1    | O         | 307              | 182           | 
| 1        | 2015-11-28T00:00:00 | 2    | I         | 280              | 133           | 
| 1        | 2015-11-28T00:00:00 | 2    | O         | 258              | 134           | 
| 1        | 2015-11-28T00:00:00 | 3    | I         | 305              | 164           | 
| 1        | 2015-11-28T00:00:00 | 3    | O         | 282              | 139           | 
| 1        | 2015-11-28T00:00:00 | 4    | I         | 440              | 276           | 
| 1        | 2015-11-28T00:00:00 | 4    | O         | 328              | 190           | 
```