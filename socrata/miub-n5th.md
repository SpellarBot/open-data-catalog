# New York State Forest Ranger Wildland Fire Reporting Database: Beginning 2008

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/new-york-state-forest-ranger-wildland-fire-reporting-database-beginning-2008) |
| Metadata | [Link](https://data.ny.gov/api/views/miub-n5th) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/miub-n5th/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/miub-n5th/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | miub-n5th |
| Name | New York State Forest Ranger Wildland Fire Reporting Database: Beginning 2008 |
| Attribution | NYS Department of Environmental Conservation Division of Forest Protection |
| Category | Energy & Environment |
| Tags | forest fire, brush fire, wildland fire, prescribed fire, grass fire, forest ranger |
| Created | 2015-08-10T19:11:48Z |
| Publication Date | 2017-01-03T22:14:19Z |

## Description

This dataset includes details for each wildland fire recorded after 2007 under the jurisdiction of the DEC NYS Forest Rangers. Earlier wildfires (1975-2007) under the jurisdiction of NYS DEC Forest Rangers can be found in the historical wildfire dataset. That dataset was formatted for use with FireFamily Plus. Each wildfire controlled or prescribed fire conducted by NYS DEC Forest Rangers is documented as a single incident in this database.

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                        | Data Type     | Render Type   |
| ======== | ============== | =========================== | =========================== | ============= | ============= |
| Yes      | series tag     | fire_number                 | Fire Number                 | text          | text          |
| Yes      | series tag     | incident_name               | Incident Name               | text          | text          |
| Yes      | time           | fire_start_date             | Fire Start Date             | calendar_date | calendar_date |
| No       |                | initial_report_date         | Initial Report Date         | calendar_date | calendar_date |
| No       |                | fire_out_date               | Fire Out Date               | calendar_date | calendar_date |
| Yes      | series tag     | region                      | Region                      | text          | number        |
| Yes      | series tag     | zone                        | Zone                        | text          | text          |
| Yes      | series tag     | county                      | County                      | text          | text          |
| Yes      | series tag     | municipality                | Municipality                | text          | text          |
| Yes      | series tag     | cause                       | Cause                       | text          | text          |
| Yes      | series tag     | nffl_fuel_model             | NFFL Fuel Model             | text          | text          |
| Yes      | series tag     | complex_type                | Complex Type                | text          | number        |
| Yes      | numeric metric | acreage                     | Acreage                     | number        | number        |
| No       |                | latitude                    | Latitude                    | number        | number        |
| No       |                | longitude                   | Longitude                   | number        | number        |
| Yes      | series tag     | ownership                   | Ownership                   | text          | text          |
| Yes      | series tag     | state_land_unit_name        | State Land Unit Name        | text          | text          |
| Yes      | numeric metric | total                       | Total                       | number        | number        |
| Yes      | numeric metric | fatalities                  | Fatalities                  | number        | number        |
| Yes      | numeric metric | injuries                    | Injuries                    | number        | number        |
| Yes      | numeric metric | homes_losts                 | Homes Lost                  | number        | number        |
| Yes      | numeric metric | homes_threatened            | Homes Threatened            | number        | number        |
| Yes      | numeric metric | other_structures_lost       | Other Structures Lost       | number        | number        |
| Yes      | numeric metric | other_structures_threatened | Other Structures Threatened | number        | number        |
| Yes      | series tag     | reporting_ranger            | Reporting Ranger            | text          | text          |
| Yes      | series tag     | fire_report_method          | Fire Report Method          | text          | text          |
| Yes      | series tag     | railroad_name               | Railroad Name               | text          | text          |
```

## Time Field

```ls
Value = fire_start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = initial_report_date,fire_out_date,latitude,longitude
```

## Data Commands

```ls
series e:miub-n5th d:2008-01-21T00:00:00.000Z t:fire_number=NYS-2008-0001 t:region=1 t:incident_name="OBPP Powerline Surge" t:cause=Equipment t:ownership="State Forest/RF Area" t:complex_type=5 t:county=SUFFOLK t:state_land_unit_name="Oak Brush Plains Preserve" t:municipality=BABYLON t:reporting_ranger=Byrnes,Timothy t:nffl_fuel_model="8 - Timber - Light Hardwood Litter" t:zone=1A t:fire_report_method="Fire Department" m:total=0 m:homes_threatened=0 m:homes_losts=0 m:injuries=0 m:other_structures_lost=0 m:fatalities=0 m:acreage=0.2 m:other_structures_threatened=0

series e:miub-n5th d:2008-03-18T00:00:00.000Z t:fire_number=NYS-2008-0002 t:region=1 t:incident_name="Otis Pike @ Dog Pond Line Rd" t:cause="Prescribed Fire" t:ownership="Wildlife Management Area" t:complex_type=5 t:county=SUFFOLK t:state_land_unit_name="Peconic River HWNRMA" t:municipality=RIVERHEAD t:reporting_ranger=Byrnes,Timothy t:nffl_fuel_model="1 - Grass - Light" t:zone=1A t:fire_report_method=Supervisor m:total=0 m:homes_threatened=0 m:homes_losts=0 m:injuries=0 m:other_structures_lost=0 m:fatalities=0 m:acreage=10.9 m:other_structures_threatened=0

series e:miub-n5th d:2008-03-18T00:00:00.000Z t:fire_number=NYS-2008-0003 t:region=1 t:incident_name="Otis Pike @ Linus Dog Pond" t:cause="Prescribed Fire" t:ownership="Wildlife Management Area" t:complex_type=5 t:county=SUFFOLK t:state_land_unit_name="Peconic River HWNRMA" t:municipality=RIVERHEAD t:reporting_ranger=Byrnes,Timothy t:nffl_fuel_model="1 - Grass - Light" t:zone=1A t:fire_report_method=Supervisor m:total=0 m:homes_threatened=0 m:homes_losts=0 m:injuries=0 m:other_structures_lost=0 m:fatalities=0 m:acreage=2.3 m:other_structures_threatened=0
```

## Meta Commands

```ls
metric m:acreage p:float l:Acreage d:"Total size of the fire in acres. Smallest fire is 0.1 acre and all fires are limited to one tenth acre reporting." t:dataTypeName=number

metric m:total p:float l:Total d:"Total amount of non-personnel expenses associated with the control and extinguishment of this fire." t:dataTypeName=number

metric m:fatalities p:integer l:Fatalities d:"Number of people who were killed or died on the fire incident" t:dataTypeName=number

metric m:injuries p:integer l:Injuries d:"Number of people injured on the fire incident." t:dataTypeName=number

metric m:homes_losts p:integer l:"Homes Lost" d:"Number of residential units that became uninhabitable by the fire" t:dataTypeName=number

metric m:homes_threatened p:integer l:"Homes Threatened" d:"Number of residential units damaged or in threat of damage if fire suppression was not effective." t:dataTypeName=number

metric m:other_structures_lost p:integer l:"Other Structures Lost" d:"Number of non-residential buildings severely damaged or destroyed by the fire." t:dataTypeName=number

metric m:other_structures_threatened p:integer l:"Other Structures Threatened" d:"Number of non-residential buildings damaged or in threat of damage if fire suppression was not effective." t:dataTypeName=number

entity e:miub-n5th l:"New York State Forest Ranger Wildland Fire Reporting Database: Beginning 2008" t:attribution="NYS Department of Environmental Conservation Division of Forest Protection" t:url=https://data.ny.gov/api/views/miub-n5th

property e:miub-n5th t:meta.view v:id=miub-n5th v:category="Energy & Environment" v:attributionLink=http://www.dec.ny.gov/lands/4975.html v:averageRating=0 v:name="New York State Forest Ranger Wildland Fire Reporting Database: Beginning 2008" v:attribution="NYS Department of Environmental Conservation Division of Forest Protection"

property e:miub-n5th t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:miub-n5th t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:miub-n5th t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| fire_number   | incident_name                | fire_start_date     | initial_report_date | fire_out_date       | region | zone | county    | municipality | cause           | nffl_fuel_model                     | complex_type | acreage | latitude | longitude | ownership                | state_land_unit_name       | total | fatalities | injuries | homes_losts | homes_threatened | other_structures_lost | other_structures_threatened | reporting_ranger | fire_report_method | railroad_name | 
| ============= | ============================ | =================== | =================== | =================== | ====== | ==== | ========= | ============ | =============== | =================================== | ============ | ======= | ======== | ========= | ======================== | ========================== | ===== | ========== | ======== | =========== | ================ | ===================== | =========================== | ================ | ================== | ============= | 
| NYS-2008-0001 | OBPP Powerline Surge         | 2008-01-21T00:00:00 | 2008-01-21T00:00:00 | 2008-01-21T00:00:00 | 1      | 1A   | SUFFOLK   | BABYLON      | Equipment       | 8 - Timber - Light Hardwood Litter  | 5            | 0.2     | 40.78510 | -73.29247 | State Forest/RF Area     | Oak Brush Plains Preserve  | 0.00  | 0          | 0        | 0           | 0                | 0                     | 0                           | Byrnes,Timothy   | Fire Department    |               | 
| NYS-2008-0002 | Otis Pike @ Dog Pond Line Rd | 2008-03-18T00:00:00 | 2008-03-18T00:00:00 | 2008-03-18T00:00:00 | 1      | 1A   | SUFFOLK   | RIVERHEAD    | Prescribed Fire | 1 - Grass - Light                   | 5            | 10.9    | 40.90200 | -72.80200 | Wildlife Management Area | Peconic River HWNRMA       | 0.00  | 0          | 0        | 0           | 0                | 0                     | 0                           | Byrnes,Timothy   | Supervisor         |               | 
| NYS-2008-0003 | Otis Pike @ Linus Dog Pond   | 2008-03-18T00:00:00 | 2008-03-18T00:00:00 | 2008-03-18T00:00:00 | 1      | 1A   | SUFFOLK   | RIVERHEAD    | Prescribed Fire | 1 - Grass - Light                   | 5            | 2.3     | 40.88800 | -72.81800 | Wildlife Management Area | Peconic River HWNRMA       | 0.00  | 0          | 0        | 0           | 0                | 0                     | 0                           | Byrnes,Timothy   | Supervisor         |               | 
| NYS-2008-0004 | Quadt Fire                   | 2008-03-22T00:00:00 | 2008-03-22T00:00:00 | 2008-03-22T00:00:00 | 4      | 4B   | SCHOHARIE | SCHOHARIE    | Miscellaneous   | 1 - Grass - Light                   | 5            | 0.2     | 42.65000 | -74.32000 | Private Property         |                            | 0.00  | 0          | 0        | 0           | 0                | 0                     | 0                           | Henry,William    | 911 Dispatch       |               | 
| NYS-2008-0005 | Prestons Pond                | 2008-03-22T00:00:00 | 2008-03-22T00:00:00 | 2008-03-22T00:00:00 | 1      | 1A   | SUFFOLK   | RIVERHEAD    | Prescribed Fire | 1 - Grass - Light                   | 5            | 5.8     | 40.90210 | -72.82048 | Wildlife Management Area | Peconic River HWNRMA       | 0.00  | 0          | 0        | 0           | 0                | 0                     | 0                           | Byrnes,Timothy   | Supervisor         |               | 
| NYS-2008-0006 | Wellhead Pond                | 2008-03-22T00:00:00 | 2008-03-22T00:00:00 | 2008-03-22T00:00:00 | 1      | 1A   | SUFFOLK   | RIVERHEAD    | Prescribed Fire | 1 - Grass - Light                   | 5            | 5.8     | 40.90167 | -72.82158 | Wildlife Management Area | Peconic River HWNRMA       | 0.00  | 0          | 0        | 0           | 0                | 0                     | 0                           | Byrnes,Timothy   | Supervisor         |               | 
| NYS-2008-0007 | Brown Fire                   | 2008-03-24T00:00:00 | 2008-03-24T00:00:00 | 2008-03-24T00:00:00 | 4      | 4B   | SCHOHARIE | SCHOHARIE    | Debris Burning  | 1 - Grass - Light                   | 5            | 1.0     | 42.69700 | -74.25700 | Private Property         |                            | 0.00  | 0          | 0        | 0           | 0                | 0                     | 0                           | Henry,William    | 911 Dispatch       |               | 
| NYS-2008-0008 | EASTPORT GRASS FIRE          | 2008-03-25T00:00:00 | 2008-03-25T00:00:00 | 2008-03-25T00:00:00 | 1      | 1A   | SUFFOLK   | BROOKHAVEN   | Prescribed Fire | 3 - Grass - Heavy                   | 5            | 14.0    | 40.86325 | -72.72410 | Wildlife Management Area | Eastport Conservation Area | 0.00  | 0          | 0        | 0           | 0                | 0                     | 0                           | Byrnes,Timothy   | Ranger Patrol      |               | 
| NYS-2008-0009 | Center Hill Road Fire        | 2008-03-25T00:00:00 | 2008-03-25T00:00:00 | 2008-03-25T00:00:00 | 4      | 4A   | COLUMBIA  | COPAKE       | Debris Burning  | 9 - Timber - Medium Hardwood Litter | 4            | 7.0     | 42.14286 | -73.55760 | Private Property         |                            | 0.00  | 0          | 0        | 0           | 1                | 0                     | 0                           | DiCintio,Chris A | 911 Dispatch       |               | 
| NYS-2008-0012 | Wellhead & Big Field Take 2  | 2008-04-03T00:00:00 | 2008-04-03T00:00:00 | 2008-04-03T00:00:00 | 1      | 1A   | SUFFOLK   | BROOKHAVEN   | Prescribed Fire | 3 - Grass - Heavy                   | 5            | 20.4    | 40.90304 | -72.82380 | Wildlife Management Area | Peconic River HWNRMA       | 0.00  | 0          | 0        | 0           | 0                | 0                     | 0                           | Gallagher,Bryan  | Ranger Patrol      |               | 
```