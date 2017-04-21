# WDFW- Juvenile Population Abundance

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/wdfw-juvenile-population-abundance) |
| Metadata | [Link](https://data.wa.gov/api/views/cqra-s74n) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/cqra-s74n/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/cqra-s74n/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | cqra-s74n |
| Name | WDFW- Juvenile Population Abundance |
| Category | Natural Resources & Environment |
| Tags | wdfw, salmon, sos |
| Created | 2016-07-15T18:54:05Z |
| Publication Date | 2016-07-28T17:49:34Z |

## Description

WDFW juvenile wild salmonid abundance

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type     | Render Type   |
| ======== | ============== | ====================== | ====================== | ============= | ============= |
| Yes      | series tag     | salmon_recovery_region | Salmon Recovery Region | text          | text          |
| Yes      | series tag     | federal_status         | Federal Status         | text          | text          |
| Yes      | series tag     | stock_numbers          | Stock Numbers          | text          | text          |
| Yes      | series tag     | waterbody_name         | Waterbody Name         | text          | text          |
| Yes      | series tag     | species                | Species                | text          | text          |
| Yes      | series tag     | run_type               | Run Type               | text          | text          |
| No       |                | migration_year         | Migration Year         | number        | number        |
| Yes      | numeric metric | occupied_river_miles   | Occupied River Miles   | number        | number        |
| Yes      | numeric metric | abundance              | Abundance              | number        | number        |
| Yes      | numeric metric | density                | Density                | number        | number        |
| Yes      | series tag     | comments               | Comments               | text          | text          |
| Yes      | series tag     | local_biologist_name   | Local Biologist Name   | text          | text          |
| Yes      | time           | last_update            | Last Update            | calendar_date | calendar_date |
```

## Time Field

```ls
Value = last_update
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = migration_year
```

## Data Commands

```ls
series e:cqra-s74n d:2015-07-24T13:59:05.000Z t:waterbody_name="Cowlitz River" t:stock_numbers="6701; 6702" t:species=Steelhead t:run_type=Winter t:salmon_recovery_region="Lower Columbia River" t:local_biologist_name="John Serl" t:federal_status=Threatened m:density=38 m:occupied_river_miles=247.2 m:abundance=9300

series e:cqra-s74n d:2016-07-14T13:19:20.000Z t:waterbody_name="Seabeck Creek" t:stock_numbers=3207 t:species=Coho t:run_type=NA t:salmon_recovery_region="Puget Sound" t:local_biologist_name="Clayton Kinsel" t:federal_status="Not Warranted" m:abundance=1508

series e:cqra-s74n d:2015-06-25T16:06:34.000Z t:waterbody_name="Green River" t:stock_numbers=6175 t:species=Steelhead t:run_type=Winter t:salmon_recovery_region="Puget Sound" t:local_biologist_name="Peter Topping" t:federal_status=Threatened m:abundance=15339
```

## Meta Commands

```ls
metric m:occupied_river_miles p:float l:"Occupied River Miles" d:"The number of miles that are potentially utilized by the population." t:dataTypeName=number

metric m:abundance p:long l:Abundance d:"Juvenile abundance estimate" t:dataTypeName=number

metric m:density p:integer l:Density d:"The abundance divided by the occupied river miles." t:dataTypeName=number

entity e:cqra-s74n l:"WDFW- Juvenile Population Abundance" t:url=https://data.wa.gov/api/views/cqra-s74n

property e:cqra-s74n t:meta.view v:id=cqra-s74n v:category="Natural Resources & Environment" v:averageRating=0 v:name="WDFW- Juvenile Population Abundance"

property e:cqra-s74n t:meta.view.owner v:id=h2p6-jrpv v:profileImageUrlMedium=/api/users/h2p6-jrpv/profile_images/THUMB v:profileImageUrlLarge=/api/users/h2p6-jrpv/profile_images/LARGE v:screenName="WDFW Data" v:profileImageUrlSmall=/api/users/h2p6-jrpv/profile_images/TINY v:displayName="WDFW Data"

property e:cqra-s74n t:meta.view.tableauthor v:id=h2p6-jrpv v:profileImageUrlMedium=/api/users/h2p6-jrpv/profile_images/THUMB v:profileImageUrlLarge=/api/users/h2p6-jrpv/profile_images/LARGE v:screenName="WDFW Data" v:profileImageUrlSmall=/api/users/h2p6-jrpv/profile_images/TINY v:roleName=publisher v:displayName="WDFW Data"
```

## Top Records

```ls
| salmon_recovery_region | federal_status | stock_numbers | waterbody_name  | species   | run_type      | migration_year | occupied_river_miles | abundance | density | comments | local_biologist_name | last_update         | 
| ====================== | ============== | ============= | =============== | ========= | ============= | ============== | ==================== | ========= | ======= | ======== | ==================== | =================== | 
| Lower Columbia River   | Threatened     | 6701; 6702    | Cowlitz River   | Steelhead | Winter        | 2002           | 247.2                | 9300      | 38      |          | John Serl            | 2015-07-24T13:59:05 | 
| Puget Sound            | Not Warranted  | 3207          | Seabeck Creek   | Coho      | NA            | 2014           |                      | 1508      |         |          | Clayton Kinsel       | 2016-07-14T13:19:20 | 
| Puget Sound            | Threatened     | 6175          | Green River     | Steelhead | Winter        | 2013           |                      | 15339     |         |          | Peter Topping        | 2015-06-25T16:06:34 | 
| Lower Columbia River   | Not Warranted  | 6682          | Germany Creek   | Steelhead | Winter        | 2014           |                      | 5647      |         |          |                      | 2016-01-14T15:19:29 | 
| Puget Sound            | Threatened     | 1144          | Cedar River     | Chinook   | NA            | 2013           | 36.1                 | 893877    | 24761   |          | Kelly Kiyohara       | 2015-07-24T13:59:05 | 
| Puget Sound            | Not Warranted  | 3207          | Seabeck Creek   | Coho      | NA            | 2013           |                      | 1368      |         |          | Clayton Kinsel       | 2015-09-08T14:49:38 | 
| Upper Columbia River   | Threatened     | 6896          | Wenatchee River | Steelhead | Summer        | 2003           | 222.1                | 32710     | 147     |          | Mclain Johnson       | 2015-07-24T13:59:05 | 
| Lower Columbia River   | Not Warranted  | 6682          | Germany Creek   | Steelhead | Winter        | 2001           |                      | 7600      |         |          |                      | 2016-02-19T14:58:42 | 
| Upper Columbia River   | Endangered     | 1770          | Chiwawa River   | Chinook   | Spring        | 2004           |                      | 90948     |         |          | Mclain Johnson       | 2015-07-24T13:59:05 | 
| Lower Columbia River   | Threatened     | 6805          | Trout Creek     | Steelhead | Summer-Winter | 2000           |                      | 1321      |         |          | Patrick Cochran      | 2016-03-07T14:56:25 | 
```