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
| No       |                | station_latitude   | Station Latitude   | number    | number      |
| No       |                | station_longitude  | Station Longitude  | number    | number      |
| Yes      | series tag     | route1             | Route1             | text      | text        |
| Yes      | series tag     | route2             | Route2             | text      | text        |
| Yes      | series tag     | route3             | Route3             | text      | text        |
| Yes      | series tag     | route4             | Route4             | text      | text        |
| Yes      | series tag     | route5             | Route5             | text      | text        |
| Yes      | series tag     | route6             | Route6             | text      | text        |
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
| No       |                | entrance_latitude  | Entrance Latitude  | number    | number      |
| No       |                | entrance_longitude | Entrance Longitude | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = station_latitude,station_longitude,entrance_latitude,entrance_longitude
```

## Data Commands

```ls
series e:i9wp-a4ja d:2015-09-18T08:16:30.000Z t:station_name="Atlantic Av-Barclays Ctr" t:corner=NE t:line="4 Avenue" t:east_west_street="Pacific St" t:ada=TRUE t:route4=N t:route3=D t:route2=Q t:route1=B t:division=BMT t:entrance_type=Elevator t:route7=3 t:route6=2 t:vending=YES t:route5=R t:entry=YES t:free_crossover=TRUE t:north_south_street="4th Ave" t:staffing=FULL m:route8=4 m:route9=5

series e:i9wp-a4ja d:2015-09-18T08:16:30.000Z t:station_name="Pacific St" t:corner=NW t:line="4 Avenue" t:east_west_street="Pacific St" t:ada=TRUE t:route4=N t:route3=D t:route2=Q t:route1=B t:division=BMT t:entrance_type=Stair t:route7=3 t:route6=2 t:vending=YES t:route5=R t:entry=YES t:free_crossover=TRUE t:north_south_street="4th Ave" t:staffing=FULL m:route8=4 m:route9=5

series e:i9wp-a4ja d:2015-09-18T08:16:30.000Z t:station_name="Pacific St" t:corner=NE t:line="4 Avenue" t:east_west_street="Pacific St" t:ada=TRUE t:route4=N t:route3=D t:route2=Q t:route1=B t:division=BMT t:entrance_type=Stair t:route7=3 t:route6=2 t:vending=YES t:route5=R t:entry=YES t:free_crossover=TRUE t:north_south_street="4th Ave" t:staffing=FULL m:route8=4 m:route9=5
```

## Meta Commands

```ls
metric m:route8 p:integer l:Route8 t:dataTypeName=number

metric m:route9 p:integer l:Route9 t:dataTypeName=number

metric m:route10 p:integer l:Route10 t:dataTypeName=number

metric m:route11 p:integer l:Route11 t:dataTypeName=number

entity e:i9wp-a4ja l:"NYC Transit Subway Entrance And Exit Data" t:attribution="MTA Headquarters, New York City Transit" t:url=https://data.ny.gov/api/views/i9wp-a4ja

property e:i9wp-a4ja t:meta.view v:id=i9wp-a4ja v:category=Transportation v:attributionLink=http://www.mta.info/developers/download.html v:averageRating=0 v:name="NYC Transit Subway Entrance And Exit Data" v:attribution="MTA Headquarters, New York City Transit"

property e:i9wp-a4ja t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:i9wp-a4ja t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:i9wp-a4ja t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| :updated_at | division | line     | station_name | station_latitude | station_longitude | route1 | route2 | route3 | route4 | route5 | route6 | route7 | route8 | route9 | route10 | route11 | entrance_type | entry | exit_only | vending | staffing | staff_hours | ada   | ada_notes | free_crossover | north_south_street | east_west_street | corner | entrance_latitude | entrance_longitude | 
| =========== | ======== | ======== | ============ | ================ | ================= | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ======= | ======= | ============= | ===== | ========= | ======= | ======== | =========== | ===== | ========= | ============== | ================== | ================ | ====== | ================= | ================== | 
| 1442564190  | BMT      | 4 Avenue | 25th St      | 40.660397        | -73.998091        | R      |        |        |        |        |        |        |        |        |         |         | Stair         | YES   |           | YES     | FULL     |             | FALSE |           | FALSE          | 4th Ave            | 25th St          | SE     | 40.660323         | -73.997952         | 
| 1442564190  | BMT      | 4 Avenue | 25th St      | 40.660397        | -73.998091        | R      |        |        |        |        |        |        |        |        |         |         | Stair         | YES   |           | YES     | NONE     |             | FALSE |           | FALSE          | 4th Ave            | 25th St          | SW     | 40.660489         | -73.998220         | 
| 1442564190  | BMT      | 4 Avenue | 36th St      | 40.655144        | -74.003549        | N      | R      |        |        |        |        |        |        |        |         |         | Stair         | YES   |           | YES     | FULL     |             | FALSE |           | TRUE           | 4th Ave            | 36th St          | NW     | 40.654490         | -74.004499         | 
| 1442564190  | BMT      | 4 Avenue | 36th St      | 40.655144        | -74.003549        | N      | R      |        |        |        |        |        |        |        |         |         | Stair         | YES   |           | YES     | FULL     |             | FALSE |           | TRUE           | 4th Ave            | 36th St          | NE     | 40.654365         | -74.004113         | 
| 1442564190  | BMT      | 4 Avenue | 36th St      | 40.655144        | -74.003549        | N      | R      |        |        |        |        |        |        |        |         |         | Stair         | YES   |           | YES     | FULL     |             | FALSE |           | TRUE           | 4th Ave            | 36th St          | NW     | 40.654676         | -74.004306         | 
| 1442564190  | BMT      | 4 Avenue | 45th St      | 40.648939        | -74.010006        | R      |        |        |        |        |        |        |        |        |         |         | Stair         | YES   |           | YES     | FULL     |             | FALSE |           | TRUE           | 4th Ave            | 45th St          | NE     | 40.649389         | -74.009333         | 
| 1442564190  | BMT      | 4 Avenue | 45th St      | 40.648939        | -74.010006        | R      |        |        |        |        |        |        |        |        |         |         | Stair         | YES   |           | YES     | FULL     |             | FALSE |           | TRUE           | 4th Ave            | 45th St          | NW     | 40.649424         | -74.009728         | 
| 1442564190  | BMT      | 4 Avenue | 45th St      | 40.648939        | -74.010006        | R      |        |        |        |        |        |        |        |        |         |         | Stair         | YES   |           | YES     | FULL     |             | FALSE |           | TRUE           | 4th Ave            | 45th St          | NE     | 40.649265         | -74.009457         | 
| 1442564190  | BMT      | 4 Avenue | 45th St      | 40.648939        | -74.010006        | R      |        |        |        |        |        |        |        |        |         |         | Stair         | YES   |           | YES     | FULL     |             | FALSE |           | TRUE           | 4th Ave            | 45th St          | NW     | 40.649546         | -74.009602         | 
| 1442564190  | BMT      | 4 Avenue | 53rd St      | 40.645069        | -74.014034        | R      |        |        |        |        |        |        |        |        |         |         | Stair         | YES   |           | YES     | FULL     |             | FALSE |           | TRUE           | 4th Ave            | 53rd St          | SW     | 40.644653         | -74.014690         | 
```