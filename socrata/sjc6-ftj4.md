# Broadband Availability By Municipality

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/broadband-availability-by-municipality) |
| Metadata | [Link](https://data.ny.gov/api/views/sjc6-ftj4) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/sjc6-ftj4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/sjc6-ftj4/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | sjc6-ftj4 |
| Name | Broadband Availability By Municipality |
| Attribution | Office of Information Technology Services |
| Category | Economic Development |
| Tags | broadband, internet, dsl, fiber, cable, wireless, satellite, speed, ntia, fcc |
| Created | 2013-02-14T03:38:50Z |
| Publication Date | 2014-12-29T17:44:51Z |

## Description

New York State has just completed a broadband mapping program as part of the national broadband mapping program funded by the National Telecommunications and Information Administration in the US Department of Commerce. Information about the availability of high-speed Internet services, commonly called Broadband, was collected from broadband provider companies regarding the technology type and speed of services offered. The data was updated every six months for five years, and is shown on the NYS Broadband Map at www.broadbandmap.ny.gov as well as the National Broadband Map at www.broadbandmap.gov. The data on the map depicts broadband availability at the Census Block level. This table summarizes the information for each municipality (town, city, village, Indian Reservation) in New York State.

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| No       | time           | :updated_at             | updated_at              | meta_data | meta_data   |
| Yes      | series tag     | gnis_id                 | GNIS ID                 | text      | number      |
| Yes      | series tag     | municipality_name       | Municipality Name       | text      | text        |
| Yes      | series tag     | municipality_type       | Municipality Type       | text      | text        |
| Yes      | numeric metric | 2010_muni_population    | 2010 Muni Population    | number    | number      |
| Yes      | numeric metric | 2010_muni_housing_units | 2010 Muni Housing Units | number    | number      |
| Yes      | numeric metric | muni_area_sq_mi         | Muni Area (sq mi)       | number    | number      |
| Yes      | series tag     | county                  | County                  | text      | text        |
| Yes      | series tag     | redc_region             | REDC Region             | text      | text        |
| Yes      | numeric metric | cable_providers         | # Cable Providers       | number    | number      |
| Yes      | numeric metric | hse_units_cable_1       | # Hse Units Cable       | number    | number      |
| Yes      | numeric metric | hse_units_cable_2       | % Hse Units Cable       | percent   | percent     |
| Yes      | numeric metric | of_dsl_providers        | # of DSL Providers      | number    | number      |
| Yes      | numeric metric | hse_units_dsl_1         | # Hse Units DSL         | number    | number      |
| Yes      | numeric metric | hse_units_dsl_2         | % Hse Units DSL         | percent   | percent     |
| Yes      | numeric metric | fiber_providers         | # Fiber Providers       | number    | number      |
| Yes      | numeric metric | hse_units_fiber_1       | # Hse Units Fiber       | number    | number      |
| Yes      | numeric metric | hse_units_fiber_2       | % Hse Units Fiber       | percent   | percent     |
| Yes      | numeric metric | wireline_providers      | # Wireline Providers    | number    | number      |
| Yes      | numeric metric | hse_units_wireline_1    | # Hse Units Wireline    | number    | number      |
| Yes      | numeric metric | hse_units_wireline_2    | % Hse Units Wireline    | percent   | percent     |
| Yes      | numeric metric | wireless_providers      | # Wireless Providers    | number    | number      |
| Yes      | numeric metric | hse_units_wireless_1    | # Hse Units Wireless    | number    | number      |
| Yes      | numeric metric | hse_units_wireless_2    | % Hse Units Wireless    | percent   | percent     |
| Yes      | numeric metric | satellite_providers     | # Satellite Providers   | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:sjc6-ftj4 d:2014-12-29T08:55:03.000Z t:municipality_name=Adams t:county=Jefferson t:municipality_type=Village t:redc_region="North Country Region" t:gnis_id=942159 m:of_dsl_providers=1 m:hse_units_wireless_2=96 m:hse_units_wireless_1=760 m:cable_providers=1 m:hse_units_fiber_1=0 m:hse_units_fiber_2=0 m:2010_muni_population=1775 m:hse_units_cable_2=96 m:hse_units_cable_1=760 m:wireline_providers=3 m:wireless_providers=3 m:muni_area_sq_mi=1.5 m:hse_units_dsl_1=760 m:2010_muni_housing_units=793 m:hse_units_dsl_2=96 m:fiber_providers=1 m:hse_units_wireline_1=760 m:hse_units_wireline_2=96 m:satellite_providers=4

series e:sjc6-ftj4 d:2014-12-29T08:55:03.000Z t:municipality_name=Adams t:county=Jefferson t:municipality_type=Town t:redc_region="North Country Region" t:gnis_id=978655 m:of_dsl_providers=1 m:hse_units_wireless_2=94 m:hse_units_wireless_1=2000 m:cable_providers=1 m:hse_units_fiber_1=0 m:hse_units_fiber_2=0 m:2010_muni_population=5143 m:hse_units_cable_2=85 m:hse_units_cable_1=1800 m:wireline_providers=3 m:wireless_providers=4 m:muni_area_sq_mi=42.4 m:hse_units_dsl_1=2000 m:2010_muni_housing_units=2126 m:hse_units_dsl_2=94 m:fiber_providers=1 m:hse_units_wireline_1=2000 m:hse_units_wireline_2=94 m:satellite_providers=4

series e:sjc6-ftj4 d:2014-12-29T08:55:03.000Z t:municipality_name=Addison t:county=Steuben t:municipality_type=Village t:redc_region="Southern Tier Region" t:gnis_id=942177 m:of_dsl_providers=1 m:hse_units_wireless_2=96 m:hse_units_wireless_1=740 m:cable_providers=1 m:hse_units_fiber_1=0 m:hse_units_fiber_2=0 m:2010_muni_population=1763 m:hse_units_cable_2=96 m:hse_units_cable_1=740 m:wireline_providers=3 m:wireless_providers=2 m:muni_area_sq_mi=1.9 m:hse_units_dsl_1=740 m:2010_muni_housing_units=770 m:hse_units_dsl_2=96 m:fiber_providers=1 m:hse_units_wireline_1=740 m:hse_units_wireline_2=96 m:satellite_providers=4
```

## Meta Commands

```ls
metric m:2010_muni_population p:integer l:"2010 Muni Population" d:"Total Population in the Municipality according to the 2010 US Census" t:dataTypeName=number

metric m:2010_muni_housing_units p:integer l:"2010 Muni Housing Units" d:"Total Housing Units (occupied & unoccupied households) in the Municipality according to the 2010 US Census" t:dataTypeName=number

metric m:muni_area_sq_mi p:float l:"Muni Area (sq mi)" d:"Area of the Municipality in square miles" t:dataTypeName=number

metric m:cable_providers p:integer l:"# Cable Providers" d:"# of Cable broadband providers by Municipality" t:dataTypeName=number

metric m:hse_units_cable_1 p:integer l:"# Hse Units Cable" d:"# of 2010 Census Housing Units with access to cable broadband (?768 kbps download, ?200 kbps upload) in the Municipality. This is a rounded estimate with a ?3% bias factor applied." t:dataTypeName=number

metric m:hse_units_cable_2 p:integer l:"% Hse Units Cable" d:"% of 2010 Census Housing Units with access to cable broadband (?768 kbps download, ?200 kbps upload) in the Municipality. This is a rounded estimate with a ?3% bias factor applied." t:dataTypeName=percent

metric m:of_dsl_providers p:integer l:"# of DSL Providers" d:"# of DSL broadband providers by Municipality" t:dataTypeName=number

metric m:hse_units_dsl_1 p:integer l:"# Hse Units DSL" d:"# of 2010 Census Housing Units with access to DSL broadband (?768 kbps download, ?200 kbps upload) in the Municipality. This is a rounded estimate with a ?3% bias factor applied." t:dataTypeName=number

metric m:hse_units_dsl_2 p:integer l:"% Hse Units DSL" d:"% of 2010 Census Housing Units with access to DSL broadband (?768 kbps download, ?200 kbps upload) in the Municipality. This is a rounded estimate with a ?3% bias factor applied." t:dataTypeName=percent

metric m:fiber_providers p:integer l:"# Fiber Providers" d:"# of Fiber broadband providers by Municipality (includes Business-Only providers)" t:dataTypeName=number

metric m:hse_units_fiber_1 p:integer l:"# Hse Units Fiber" d:"# of 2010 Census Housing Units with access to fiber broadband (?768 kbps download, ?200 kbps upload) in the Municipality. This is a rounded estimate with a ?3% bias factor applied." t:dataTypeName=number

metric m:hse_units_fiber_2 p:integer l:"% Hse Units Fiber" d:"% of 2010 Census Housing Units with access to fiber broadband (?768 kbps download, ?200 kbps upload) in the Municipality. This is a rounded estimate with a ?3% bias factor applied." t:dataTypeName=percent

metric m:wireline_providers p:integer l:"# Wireline Providers" d:"# of wireline (DSL, Cable, or Fiber) broadband providers by Municipality" t:dataTypeName=number

metric m:hse_units_wireline_1 p:integer l:"# Hse Units Wireline" d:"# of 2010 Census Housing Units with access to wireline (DSL, cable, or fiber) broadband (?768 kbps download, ?200 kbps upload) in the Municipality. This is a rounded estimate with a ?3% bias factor applied." t:dataTypeName=number

metric m:hse_units_wireline_2 p:integer l:"% Hse Units Wireline" d:"% of 2010 Census Housing Units with access to wireline (DSL, cable, or fiber) broadband (?768 kbps download, ?200 kbps upload) in the Municipality. This is a rounded estimate with a ?3% bias factor applied." t:dataTypeName=percent

metric m:wireless_providers p:integer l:"# Wireless Providers" d:"# of Wireless (Fixed or Mobile) broadband providers by Municipality" t:dataTypeName=number

metric m:hse_units_wireless_1 p:integer l:"# Hse Units Wireless" d:"# of 2010 Census Housing Units with access to wireless (fixed or mobile) broadband (?768 kbps download, ?200 kbps upload) in the Municipality. This is a rounded estimate with a ?3% bias factor applied." t:dataTypeName=number

metric m:hse_units_wireless_2 p:integer l:"% Hse Units Wireless" d:"% of 2010 Census Housing Units with access to wireless (fixed or mobile) broadband (?768 kbps download, ?200 kbps upload) in the Municipality. This is a rounded estimate with a ?3% bias factor applied." t:dataTypeName=percent

metric m:satellite_providers p:integer l:"# Satellite Providers" d:"# of satellite broadband providers" t:dataTypeName=number

entity e:sjc6-ftj4 l:"Broadband Availability By Municipality" t:attribution="Office of Information Technology Services" t:url=https://data.ny.gov/api/views/sjc6-ftj4

property e:sjc6-ftj4 t:meta.view v:id=sjc6-ftj4 v:category="Economic Development" v:attributionLink=http://www.broadbandmap.ny.gov v:averageRating=0 v:name="Broadband Availability By Municipality" v:attribution="Office of Information Technology Services"

property e:sjc6-ftj4 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:sjc6-ftj4 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:sjc6-ftj4 t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| :updated_at | gnis_id | municipality_name | municipality_type | 2010_muni_population | 2010_muni_housing_units | muni_area_sq_mi | county    | redc_region          | cable_providers | hse_units_cable_1 | hse_units_cable_2 | of_dsl_providers | hse_units_dsl_1 | hse_units_dsl_2 | fiber_providers | hse_units_fiber_1 | hse_units_fiber_2 | wireline_providers | hse_units_wireline_1 | hse_units_wireline_2 | wireless_providers | hse_units_wireless_1 | hse_units_wireless_2 | satellite_providers | 
| =========== | ======= | ================= | ================= | ==================== | ======================= | =============== | ========= | ==================== | =============== | ================= | ================= | ================ | =============== | =============== | =============== | ================= | ================= | ================== | ==================== | ==================== | ================== | ==================== | ==================== | =================== | 
| 1419843303  | 942159  | Adams             | Village           | 1775                 | 793                     | 1.5             | Jefferson | North Country Region | 1               | 760               | 96                | 1                | 760             | 96              | 1               | 0                 | 0                 | 3                  | 760                  | 96                   | 3                  | 760                  | 96                   | 4                   | 
| 1419843303  | 978655  | Adams             | Town              | 5143                 | 2126                    | 42.4            | Jefferson | North Country Region | 1               | 1800              | 85                | 1                | 2000            | 94              | 1               | 0                 | 0                 | 3                  | 2000                 | 94                   | 4                  | 2000                 | 94                   | 4                   | 
| 1419843303  | 942177  | Addison           | Village           | 1763                 | 770                     | 1.9             | Steuben   | Southern Tier Region | 1               | 740               | 96                | 1                | 740             | 96              | 1               | 0                 | 0                 | 3                  | 740                  | 96                   | 2                  | 740                  | 96                   | 4                   | 
| 1419843303  | 978656  | Addison           | Town              | 2595                 | 1159                    | 25.7            | Steuben   | Southern Tier Region | 1               | 950               | 82                | 1                | 1000            | 86              | 1               | 0                 | 0                 | 3                  | 1000                 | 86                   | 3                  | 1100                 | 95                   | 4                   | 
| 1419843303  | 942198  | Afton             | Village           | 822                  | 430                     | 1.7             | Chenango  | Southern Tier Region | 1               | 410               | 95                | 1                | 410             | 95              | 0               | 0                 | 0                 | 2                  | 410                  | 95                   | 4                  | 410                  | 95                   | 4                   | 
| 1419843303  | 978657  | Afton             | Town              | 2851                 | 1457                    | 46.7            | Chenango  | Southern Tier Region | 2               | 1100              | 75                | 2                | 1400            | 96              | 0               | 0                 | 0                 | 4                  | 1400                 | 96                   | 6                  | 1400                 | 96                   | 4                   | 
| 1419843303  | 979664  | Airmont           | Village           | 8628                 | 2791                    | 4.5             | Rockland  | Mid-Hudson Region    | 1               | 2700              | 97                | 2                | 2700            | 97              | 5               | 2600              | 93                | 7                  | 2700                 | 97                   | 4                  | 2700                 | 97                   | 4                   | 
| 1419843303  | 942224  | Akron             | Village           | 2868                 | 1382                    | 1.9             | Erie      | Western NY Region    | 1               | 1300              | 94                | 1                | 1300            | 94              | 1               | 0                 | 0                 | 3                  | 1300                 | 94                   | 5                  | 1300                 | 94                   | 4                   | 
| 1419843303  | 978658  | Alabama           | Town              | 1869                 | 765                     | 52.0            | Genesee   | Finger Lakes Region  | 1               | 670               | 88                | 2                | 600             | 78              | 0               | 0                 | 0                 | 3                  | 720                  | 94                   | 6                  | 740                  | 97                   | 4                   | 
| 1419843303  | 974099  | Albany            | County            | 304204               | 137739                  | 532.9           | Albany    | Capital Region       | 2               | 131000            | 95                | 3                | 115000          | 83              | 9               | 47300             | 34                | 11                 | 131000               | 95                   | 8                  | 133000               | 97                   | 4                   | 
```