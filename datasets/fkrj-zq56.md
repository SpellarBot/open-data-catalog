# Master 2014 SOS Juvenile Abundance Density Final 91614

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/master-2014-sos-juvenile-abundance-density-final-91614-67cfe) |
| Metadata | [Link](https://data.wa.gov/api/views/fkrj-zq56) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/fkrj-zq56/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/fkrj-zq56/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | fkrj-zq56 |
| Name | Master 2014 SOS Juvenile Abundance Density Final 91614 |
| Attribution | WDFW, Brodie Cox |
| Category | Natural Resources & Environment |
| Tags | smolt, sos, salmon, state-of-the-salmon, wdfw, fish, parr |
| Created | 2014-09-19T21:03:27Z |
| Publication Date | 2015-01-28T01:10:10Z |

## Description

WDFW Juvenile Salmon Density Data

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type | Render Type |
| ======== | ============== | ==================== | ==================== | ========= | =========== |
| Yes      | series tag     | region_name          | Region Name          | text      | text        |
| Yes      | series tag     | watershed            | Watershed            | text      | text        |
| Yes      | series tag     | trap_location        | Trap Location        | text      | text        |
| Yes      | time           | migration_year       | Migration Year       | number    | text        |
| Yes      | series tag     | population_type      | Population Type      | text      | text        |
| Yes      | series tag     | species              | Species              | text      | text        |
| Yes      | numeric metric | occupied_river_miles | Occupied River Miles | number    | number      |
| Yes      | numeric metric | abundance            | Abundance            | number    | number      |
| Yes      | numeric metric | density              | Density              | number    | number      |
| Yes      | series tag     | comment              | Comment              | text      | text        |
| Yes      | series tag     | contact              | Contact              | text      | text        |
```

## Time Field

```ls
Value = migration_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:fkrj-zq56 d:1978-01-01T00:00:00.000Z t:watershed="Big Beef Creek" t:region_name="Hood Canal" t:species=Steelhead t:trap_location="Big Beef Creek" t:contact="Clayton Kinsel" m:density=128 m:occupied_river_miles=6.9 m:abundance=881

series e:fkrj-zq56 d:1979-01-01T00:00:00.000Z t:watershed="Big Beef Creek" t:region_name="Hood Canal" t:species=Steelhead t:trap_location="Big Beef Creek" t:contact="Clayton Kinsel" m:density=126 m:occupied_river_miles=6.9 m:abundance=870

series e:fkrj-zq56 d:1980-01-01T00:00:00.000Z t:watershed="Big Beef Creek" t:region_name="Hood Canal" t:species=Steelhead t:trap_location="Big Beef Creek" t:contact="Clayton Kinsel" m:density=244 m:occupied_river_miles=6.9 m:abundance=1685
```

## Meta Commands

```ls
metric m:occupied_river_miles p:float l:"Occupied River Miles" t:dataTypeName=number

metric m:abundance p:integer l:Abundance t:dataTypeName=number

metric m:density p:integer l:Density t:dataTypeName=number

entity e:fkrj-zq56 l:"Master 2014 SOS Juvenile Abundance Density Final 91614" t:attribution="WDFW, Brodie Cox" t:url=https://data.wa.gov/api/views/fkrj-zq56

property e:fkrj-zq56 t:meta.view v:id=fkrj-zq56 v:category="Natural Resources & Environment" v:averageRating=0 v:name="Master 2014 SOS Juvenile Abundance Density Final 91614" v:attribution="WDFW, Brodie Cox"

property e:fkrj-zq56 t:meta.view.owner v:id=b2s6-8ii9 v:profileImageUrlMedium=/api/users/b2s6-8ii9/profile_images/THUMB v:profileImageUrlLarge=/api/users/b2s6-8ii9/profile_images/LARGE v:screenName="Brodie Cox" v:profileImageUrlSmall=/api/users/b2s6-8ii9/profile_images/TINY v:displayName="Brodie Cox"

property e:fkrj-zq56 t:meta.view.tableauthor v:id=b2s6-8ii9 v:profileImageUrlMedium=/api/users/b2s6-8ii9/profile_images/THUMB v:profileImageUrlLarge=/api/users/b2s6-8ii9/profile_images/LARGE v:screenName="Brodie Cox" v:profileImageUrlSmall=/api/users/b2s6-8ii9/profile_images/TINY v:roleName=publisher v:displayName="Brodie Cox"
```

## Top Records

```ls
| region_name | watershed      | trap_location  | migration_year | population_type | species   | occupied_river_miles | abundance | density | comment | contact        | 
| =========== | ============== | ============== | ============== | =============== | ========= | ==================== | ========= | ======= | ======= | ============== | 
| Hood Canal  | Big Beef Creek | Big Beef Creek | 1978           |                 | Steelhead | 6.9                  | 881       | 128     |         | Clayton Kinsel | 
| Hood Canal  | Big Beef Creek | Big Beef Creek | 1979           |                 | Steelhead | 6.9                  | 870       | 126     |         | Clayton Kinsel | 
| Hood Canal  | Big Beef Creek | Big Beef Creek | 1980           |                 | Steelhead | 6.9                  | 1685      | 244     |         | Clayton Kinsel | 
| Hood Canal  | Big Beef Creek | Big Beef Creek | 1981           |                 | Steelhead | 6.9                  | 1578      | 229     |         | Clayton Kinsel | 
| Hood Canal  | Big Beef Creek | Big Beef Creek | 1982           |                 | Steelhead | 6.9                  | 1269      | 184     |         | Clayton Kinsel | 
| Hood Canal  | Big Beef Creek | Big Beef Creek | 1983           |                 | Steelhead | 6.9                  | 1237      | 179     |         | Clayton Kinsel | 
| Hood Canal  | Big Beef Creek | Big Beef Creek | 1984           |                 | Steelhead | 6.9                  | 1770      | 257     |         | Clayton Kinsel | 
| Hood Canal  | Big Beef Creek | Big Beef Creek | 1985           |                 | Steelhead | 6.9                  | 1189      | 172     |         | Clayton Kinsel | 
| Hood Canal  | Big Beef Creek | Big Beef Creek | 1986           |                 | Steelhead | 6.9                  | 1210      | 175     |         | Clayton Kinsel | 
| Hood Canal  | Big Beef Creek | Big Beef Creek | 1987           |                 | Steelhead | 6.9                  | 1153      | 167     |         | Clayton Kinsel | 
```