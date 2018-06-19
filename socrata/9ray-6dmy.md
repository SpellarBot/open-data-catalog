# Eastbound Tunnel and Bridge Traffic Annual Volume, Port Authority of NY NJ: Beginning 2002

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/eastbound-tunnel-and-bridge-traffic-annual-volume-port-authority-of-ny-nj-beginning-2002) |
| Metadata | [Link](https://data.ny.gov/api/views/9ray-6dmy) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/9ray-6dmy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/9ray-6dmy/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 9ray-6dmy |
| Name | Eastbound Tunnel and Bridge Traffic Annual Volume, Port Authority of NY NJ: Beginning 2002 |
| Attribution | The Port Authority of NY & NJ |
| Category | Transportation |
| Tags | traffic, vehicles, port authority, bridges, tunnels |
| Created | 2013-05-09T16:01:29Z |
| Publication Date | 2016-10-11T19:48:31Z |

## Description

The Port Authority collects eastbound vehicle traffic volumes from its toll plazas at the six Port Authority vehicular crossings (i.e., George Washington Bridge, Holland Tunnel, Lincoln Tunnel, Goethals Bridge, Outerbridge Crossing and Bayonne Bridge).  This dataset contains annual eastbound traffic volumes for each crossing and for all Port Authority crossings combined, based on vehicles passing through Authority?s toll plazas, for each year from 2002 through 2012.  The dataset contains traffic volumes for three types of vehicles (autos, buses, trucks) for each year.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| Yes      | series tag     | bridge_tunnel    | Bridge/Tunnel    | text      | text        |
| Yes      | time           | year             | Year             | number    | number      |
| Yes      | series tag     | vehicle_type     | Vehicle Type     | text      | text        |
| Yes      | numeric metric | eastbound_volume | Eastbound Volume | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:9ray-6dmy d:2002-01-01T00:00:00.000Z t:bridge_tunnel="George Washington Bridge" t:vehicle_type=Automobile m:eastbound_volume=49921000

series e:9ray-6dmy d:2002-01-01T00:00:00.000Z t:bridge_tunnel="George Washington Bridge" t:vehicle_type=Bus m:eastbound_volume=597000

series e:9ray-6dmy d:2002-01-01T00:00:00.000Z t:bridge_tunnel="George Washington Bridge" t:vehicle_type=Truck m:eastbound_volume=4156000
```

## Meta Commands

```ls
metric m:eastbound_volume p:integer l:"Eastbound Volume" t:dataTypeName=number

entity e:9ray-6dmy l:"Eastbound Tunnel and Bridge Traffic Annual Volume, Port Authority of NY NJ:  Beginning 2002" t:attribution="The Port Authority of NY & NJ" t:url=https://data.ny.gov/api/views/9ray-6dmy

property e:9ray-6dmy t:meta.view v:id=9ray-6dmy v:category=Transportation v:averageRating=0 v:name="Eastbound Tunnel and Bridge Traffic Annual Volume, Port Authority of NY NJ:  Beginning 2002" v:attribution="The Port Authority of NY & NJ"

property e:9ray-6dmy t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:9ray-6dmy t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| bridge_tunnel            | year | vehicle_type   | eastbound_volume | 
| ======================== | ==== | ============== | ================ | 
| George Washington Bridge | 2002 | Automobile     | 49921000         | 
| George Washington Bridge | 2002 | Bus            | 597000           | 
| George Washington Bridge | 2002 | Truck          | 4156000          | 
| George Washington Bridge | 2002 | Total vehicles | 54674000         | 
| Holland Tunnel           | 2002 | Automobile     | 15227000         | 
| Holland Tunnel           | 2002 | Bus            | 214000           | 
| Holland Tunnel           | 2002 | Truck          | 324000           | 
| Holland Tunnel           | 2002 | Total vehicles | 15765000         | 
| Lincoln Tunnel           | 2002 | Automobile     | 17750000         | 
| Lincoln Tunnel           | 2002 | Bus            | 2042000          | 
```