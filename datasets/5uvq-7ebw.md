# Eastbound Tunnel and Bridge Traffic Monthly Volume, Port Authority of NY NJ: Beginning 2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/eastbound-tunnel-and-bridge-traffic-monthly-volume-port-authority-of-ny-nj-beginning-2011) |
| Metadata | [Link](https://data.ny.gov/api/views/5uvq-7ebw) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/5uvq-7ebw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/5uvq-7ebw/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 5uvq-7ebw |
| Name | Eastbound Tunnel and Bridge Traffic Monthly Volume, Port Authority of NY NJ: Beginning 2011 |
| Attribution | The Port Authority of NY & NJ |
| Category | Transportation |
| Tags | traffic, vehicles, port authority, bridges, tunnels |
| Created | 2013-05-09T17:57:32Z |
| Publication Date | 2016-10-11T19:51:12Z |

## Description

The Port Authority collects eastbound vehicle traffic volumes from its toll plazas at the six Port Authority vehicular crossings (i.e., George Washington Bridge, Holland Tunnel, Lincoln Tunnel, Goethals Bridge, Outerbridge Crossing and Bayonne Bridge).  This dataset contains monthly eastbound traffic volumes for each crossing and for all Port Authority crossings combined, based on vehicles passing through Authority?s toll plazas, for each month starting in January 2011 through December 2012.  The dataset contains traffic volumes for three types of vehicles (autos, buses, trucks) for each month.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| Yes      | series tag     | bridge_tunnel    | Bridge/Tunnel    | text      | text        |
| No       |                | year             | Year             | number    | number      |
| No       |                | month            | Month            | text      | text        |
| Yes      | series tag     | vehicles_type    | Vehicles Type    | text      | text        |
| Yes      | numeric metric | eastbound_volume | Eastbound Volume | number    | number      |
```

## Time Field

```ls
Value = year-month
Format & Zone = yyyy-MMM
```

## Series Fields

```ls
Excluded Fields = year,month
```

## Data Commands

```ls
series e:5uvq-7ebw d:2011-01-01T00:00:00.000Z t:vehicles_type=Automobile t:bridge_tunnel="George Washington Bridge" m:eastbound_volume=3370936

series e:5uvq-7ebw d:2011-01-01T00:00:00.000Z t:vehicles_type=Bus t:bridge_tunnel="George Washington Bridge" m:eastbound_volume=36807

series e:5uvq-7ebw d:2011-01-01T00:00:00.000Z t:vehicles_type=Truck t:bridge_tunnel="George Washington Bridge" m:eastbound_volume=287941
```

## Meta Commands

```ls
metric m:eastbound_volume p:integer l:"Eastbound Volume" t:dataTypeName=number

entity e:5uvq-7ebw l:"Eastbound Tunnel and Bridge Traffic Monthly Volume, Port Authority of NY NJ:  Beginning 2011" t:attribution="The Port Authority of NY & NJ" t:url=https://data.ny.gov/api/views/5uvq-7ebw

property e:5uvq-7ebw t:meta.view v:id=5uvq-7ebw v:category=Transportation v:averageRating=0 v:name="Eastbound Tunnel and Bridge Traffic Monthly Volume, Port Authority of NY NJ:  Beginning 2011" v:attribution="The Port Authority of NY & NJ"

property e:5uvq-7ebw t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:5uvq-7ebw t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| bridge_tunnel            | year | month | vehicles_type  | eastbound_volume | 
| ======================== | ==== | ===== | ============== | ================ | 
| George Washington Bridge | 2011 | Jan   | Automobile     | 3370936          | 
| George Washington Bridge | 2011 | Jan   | Bus            | 36807            | 
| George Washington Bridge | 2011 | Jan   | Truck          | 287941           | 
| George Washington Bridge | 2011 | Jan   | Total vehicles | 3695684          | 
| Holland Tunnel           | 2011 | Jan   | Automobile     | 1192262          | 
| Holland Tunnel           | 2011 | Jan   | Bus            | 18936            | 
| Holland Tunnel           | 2011 | Jan   | Truck          | 25252            | 
| Holland Tunnel           | 2011 | Jan   | Total vehicles | 1236450          | 
| Lincoln Tunnel           | 2011 | Jan   | Automobile     | 1244648          | 
| Lincoln Tunnel           | 2011 | Jan   | Bus            | 165583           | 
```