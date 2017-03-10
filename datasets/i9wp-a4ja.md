# NYC Transit Subway Entrance And Exit Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nyc-transit-subway-entrance-and-exit-data) |
| Metadata | [Link](https://data.ny.gov/api/views/i9wp-a4ja) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/i9wp-a4ja/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/i9wp-a4ja/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | i9wp-a4ja |
| Name | NYC Transit Subway Entrance And Exit Data |
| Attribution | MTA Headquarters, New York City Transit |
| Category | Transportation |
| Tags | subway, stations, routes, line |
| Created | 2013-05-09T18:07:46Z |
| Publication Date | 2015-09-18T15:18:42Z |
| Rows Updated | 2015-09-18T15:16:45Z |

## Description

This data file provides a variety of information on subway station entrances and exits which includes but is not limited to: Division, Line, Station Name, Longitude and Latitude coordinates of entrances/exits.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| No       | time           | :updated_at        | updated_at         | meta_data | meta_data   |
| Yes      | series tag     | division           | Division           | text      | text        |
| Yes      | series tag     | line               | Line               | text      | text        |
| Yes      | series tag     | station_name       | Station Name       | text      | text        |
| Yes      | numeric metric | station_latitude   | Station Latitude   | number    | number      |
| Yes      | numeric metric | station_longitude  | Station Longitude  | number    | number      |
| Yes      | series tag     | route1             | Route1             | text      | text        |
| Yes      | series tag     | route2             | Route2             | text      | text        |
| Yes      | series tag     | route3             | Route3             | text      | text        |
| Yes      | numeric metric | route4             | Route4             | number    | text        |
| Yes      | numeric metric | route5             | Route5             | number    | text        |
| Yes      | numeric metric | route6             | Route6             | number    | text        |
| Yes      | series tag     | route7             | Route7             | text      | text        |
| Yes      | numeric metric | route8             | Route8             | number    | text        |
| Yes      | numeric metric | route9             | Route9             | number    | text        |
| Yes      | numeric metric | route10            | Route10            | number    | text        |
| Yes      | numeric metric | route11            | Route11            | number    | text        |
| Yes      | series tag     | entrance_type      | Entrance Type      | text      | text        |
| Yes      | series tag     | entry              | Entry              | text      | text        |
| Yes      | series tag     | exit_only          | Exit Only          | text      | text        |
| Yes      | series tag     | vending            | Vending            | text      | text        |
| Yes      | series tag     | staffing           | Staffing           | text      | text        |
| Yes      | series tag     | staff_hours        | Staff Hours        | text      | text        |
| Yes      | series tag     | ada                | ADA                | text      | text        |
| Yes      | series tag     | ada_notes          | ADA Notes          | text      | text        |
| Yes      | series tag     | free_crossover     | Free Crossover     | text      | text        |
| Yes      | series tag     | north_south_street | North South Street | text      | text        |
| Yes      | series tag     | east_west_street   | East West Street   | text      | text        |
| Yes      | series tag     | corner             | Corner             | text      | text        |
| Yes      | numeric metric | entrance_latitude  | Entrance Latitude  | number    | number      |
| Yes      | numeric metric | entrance_longitude | Entrance Longitude | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:i9wp-a4ja d:2015-09-18T08:16:30.000Z t:ada=FALSE t:station_name="25th St" t:route1=R t:division=BMT t:corner=SE t:entrance_type=Stair t:vending=YES t:entry=YES t:free_crossover=FALSE t:north_south_street="4th Ave" t:east_west_street="25th St" t:line="4 Avenue" t:staffing=FULL m:station_longitude=-73.99809 m:entrance_latitude=40.66032 m:station_latitude=40.6604 m:entrance_longitude=-73.99795

series e:i9wp-a4ja d:2015-09-18T08:16:30.000Z t:ada=FALSE t:station_name="25th St" t:route1=R t:division=BMT t:corner=SW t:entrance_type=Stair t:vending=YES t:entry=YES t:free_crossover=FALSE t:north_south_street="4th Ave" t:east_west_street="25th St" t:line="4 Avenue" t:staffing=NONE m:station_longitude=-73.99809 m:entrance_latitude=40.66049 m:station_latitude=40.6604 m:entrance_longitude=-73.99822

series e:i9wp-a4ja d:2015-09-18T08:16:30.000Z t:ada=FALSE t:station_name="36th St" t:route2=R t:route1=N t:division=BMT t:corner=NW t:entrance_type=Stair t:vending=YES t:entry=YES t:free_crossover=TRUE t:north_south_street="4th Ave" t:east_west_street="36th St" t:line="4 Avenue" t:staffing=FULL m:station_longitude=-74.00355 m:entrance_latitude=40.65449 m:station_latitude=40.65514 m:entrance_longitude=-74.0045
```

## Meta Commands

```ls
metric m:station_latitude l:"Station Latitude" t:dataTypeName=number

metric m:station_longitude l:"Station Longitude" t:dataTypeName=number

metric m:route8 p:integer l:Route8 t:dataTypeName=number

metric m:route9 p:integer l:Route9 t:dataTypeName=number

metric m:route10 p:integer l:Route10 t:dataTypeName=number

metric m:route11 p:integer l:Route11 t:dataTypeName=number

metric m:entrance_latitude l:"Entrance Latitude" t:dataTypeName=number

metric m:entrance_longitude l:"Entrance Longitude" t:dataTypeName=number

entity e:i9wp-a4ja l:"NYC Transit Subway Entrance And Exit Data" t:attribution="MTA Headquarters, New York City Transit" t:url=https://data.ny.gov/api/views/i9wp-a4ja

property e:i9wp-a4ja t:meta.view d:2017-03-10T14:21:50.425Z v:id=i9wp-a4ja v:category=Transportation v:attributionLink=http://www.mta.info/developers/download.html v:averageRating=0 v:name="NYC Transit Subway Entrance And Exit Data" v:attribution="MTA Headquarters, New York City Transit"

property e:i9wp-a4ja t:meta.view.owner d:2017-03-10T14:21:50.425Z v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:i9wp-a4ja t:meta.view.tableauthor d:2017-03-10T14:21:50.425Z v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:i9wp-a4ja t:meta.view.metadata.custom_fields.common_core d:2017-03-10T14:21:50.425Z v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```