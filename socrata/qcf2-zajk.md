# Oil and Gas Annual Production: 1985 - 2000

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/oil-and-gas-annual-production-1985-2000) |
| Metadata | [Link](https://data.ny.gov/api/views/qcf2-zajk) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/qcf2-zajk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/qcf2-zajk/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | qcf2-zajk |
| Name | Oil and Gas Annual Production: 1985 - 2000 |
| Attribution | New York State Department of Environmental Conservation Division of Mineral Resources |
| Category | Energy & Environment |
| Tags | oil, gas, wells, geology, mineral resources, production |
| Created | 2014-09-04T19:23:27Z |
| Publication Date | 2014-11-25T21:23:02Z |

## Description

This dataset contains annual production information of oil and gas wells in New York State from 1985 to 2000.

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type | Render Type |
| ======== | ============== | ===================== | ===================== | ========= | =========== |
| Yes      | series tag     | api_well_number       | API Well Number       | text      | number      |
| Yes      | numeric metric | county                | County                | number    | number      |
| Yes      | series tag     | company_name          | Company Name          | text      | text        |
| Yes      | series tag     | api_hole_number       | API Hole Number       | text      | number      |
| Yes      | numeric metric | sidetrack             | Sidetrack             | number    | number      |
| Yes      | numeric metric | completion            | Completion            | number    | number      |
| Yes      | series tag     | well_type             | Well Type             | text      | text        |
| Yes      | series tag     | production_field_name | Production Field Name | text      | text        |
| Yes      | series tag     | well_status           | Well Status           | text      | text        |
| Yes      | series tag     | well_name             | Well Name             | text      | text        |
| Yes      | series tag     | town                  | Town                  | text      | text        |
| Yes      | series tag     | producing_formation   | Producing Formation   | text      | text        |
| Yes      | numeric metric | months_in_production  | Months in Production  | number    | number      |
| Yes      | numeric metric | gas_mcf               | Gas Produced, MCF     | number    | number      |
| Yes      | numeric metric | water_bbl             | Water Produced, bbl   | number    | number      |
| Yes      | time           | reporting_year        | Reporting Year        | number    | number      |
```

## Time Field

```ls
Value = reporting_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:qcf2-zajk d:1987-01-01T00:00:00.000Z t:producing_formation="Bass Island" t:well_name="Piazza #2" t:company_name="REI-NY, Inc." t:well_type=OD t:api_hole_number=17719 t:town=Gerry t:api_well_number=31013177190000 t:production_field_name=Gerry-Charlotte t:well_status=IN m:months_in_production=12 m:sidetrack=0 m:county=13 m:completion=0 m:gas_mcf=10762 m:water_bbl=3523

series e:qcf2-zajk d:1995-01-01T00:00:00.000Z t:producing_formation=Medina t:well_name="J Bloomquist Unit 1" t:company_name="Dannic Energy Corp." t:well_type=GD t:api_hole_number=18415 t:town=Carroll t:api_well_number=31013184150000 t:production_field_name=Lakeshore t:well_status=AC m:months_in_production=12 m:sidetrack=0 m:county=13 m:completion=0 m:gas_mcf=880 m:water_bbl=0

series e:qcf2-zajk d:1991-01-01T00:00:00.000Z t:producing_formation="Bass Island" t:well_name="Willoughby #175" t:company_name="Lenape Resources, Inc." t:well_type=OW t:api_hole_number=18155 t:town=Ellery t:api_well_number=31013181550000 t:production_field_name=Ellery t:well_status=IN m:months_in_production=0 m:sidetrack=0 m:county=13 m:completion=0 m:gas_mcf=0 m:water_bbl=0
```

## Meta Commands

```ls
metric m:county p:integer l:County d:"County name" t:dataTypeName=number

metric m:sidetrack p:integer l:Sidetrack d:"2-digit sidetrack code" t:dataTypeName=number

metric m:completion p:integer l:Completion d:"2-digit completion code" t:dataTypeName=number

metric m:months_in_production p:integer l:"Months in Production" d:"Months in production" t:dataTypeName=number

metric m:gas_mcf p:integer l:"Gas Produced, MCF" d:"Amount of gas produced (MCF)" t:dataTypeName=number

metric m:water_bbl p:integer l:"Water Produced, bbl" d:"Amount of water produced (bbl)" t:dataTypeName=number

entity e:qcf2-zajk l:"Oil and Gas Annual Production: 1985 - 2000" t:attribution="New York State Department of Environmental Conservation Division of Mineral Resources" t:url=https://data.ny.gov/api/views/qcf2-zajk

property e:qcf2-zajk t:meta.view v:id=qcf2-zajk v:category="Energy & Environment" v:averageRating=0 v:name="Oil and Gas Annual Production: 1985 - 2000" v:attribution="New York State Department of Environmental Conservation Division of Mineral Resources"

property e:qcf2-zajk t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:qcf2-zajk t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:qcf2-zajk t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| api_well_number | county | company_name                             | api_hole_number | sidetrack | completion | well_type | production_field_name | well_status | well_name           | town      | producing_formation | months_in_production | gas_mcf | water_bbl | reporting_year | 
| =============== | ====== | ======================================== | =============== | ========= | ========== | ========= | ===================== | =========== | =================== | ========= | =================== | ==================== | ======= | ========= | ============== | 
| 31013177190000  | 13     | REI-NY, Inc.                             | 17719           | 0         | 0          | OD        | Gerry-Charlotte       | IN          | Piazza #2           | Gerry     | Bass Island         | 12                   | 10762   | 3523      | 1987           | 
| 31013184150000  | 13     | Dannic Energy Corp.                      | 18415           | 0         | 0          | GD        | Lakeshore             | AC          | J Bloomquist Unit 1 | Carroll   | Medina              | 12                   | 880     | 0         | 1995           | 
| 31013181550000  | 13     | Lenape Resources, Inc.                   | 18155           | 0         | 0          | OW        | Ellery                | IN          | Willoughby #175     | Ellery    | Bass Island         | 0                    | 0       | 0         | 1991           | 
| 31009187610000  | 9      | Seneca Resources Corp.                   | 18761           | 0         | 0          | GD        | Lakeshore             | AC          | Milks #6308         | Dayton    | Medina              | 12                   | 5459    | 3         | 1987           | 
| 31029186430000  | 29     | Sierra Energy, Inc.                      | 18643           | 0         | 0          | GD        | Orchard Park-Hamburg  | AC          | Fierle #1           | Hamburg   | Medina              | 12                   | 3406    | 12        | 1990           | 
| 31121170790000  | 121    | Lenape Resources, Inc.                   | 17079           | 0         | 0          | GD        | Leicester             | AC          | Butler, D #111      | Perry     | Medina              | 12                   | 6959    | 0         | 1987           | 
| 31051194320000  | 51     | Livingston Landowners Gas & Energy, Inc. | 19432           | 0         | 0          | GD        | Avon                  | IN          | Kotak 1             | Avon      | Medina              | 0                    | 0       | 0         | 1993           | 
| 31009172120000  | 9      | Great Lakes Energy Partners              | 17212           | 0         | 0          | GD        | Lakeshore             | AC          | Allen #1            | Conewango | Medina              | 12                   | 776     | 0         | 1999           | 
| 31003603480000  | 3      | Alma Gas, Inc.                           | 60348           | 0         | 0          | GD        | Sharon                | AC          | O'Donnell #2101     | Alma      | Upper Devonian      | 12                   | 156     | 0         | 1992           | 
| 31029164510000  | 29     | Eden Vfw Post #8265                      | 16451           | 0         | 0          | GD        | Brant-Eden            | AC          | Vfw 1               | Eden      | Medina              | 4                    | 251     | 2         | 1987           | 
```