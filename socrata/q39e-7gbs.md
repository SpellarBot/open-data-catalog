# Energy and Water Data Disclosure for Local Law 84 (2011)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/energy-and-water-data-disclosure-for-local-law-84-2011-f4180) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/q39e-7gbs) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/q39e-7gbs/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/q39e-7gbs/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | q39e-7gbs |
| Name | Energy and Water Data Disclosure for Local Law 84 (2011) |
| Attribution | Mayor's Office of Long-Term Planning and Sustainability (OLTPS) |
| Category | Environment |
| Tags | mayor's office of long term planning and sustainability (oltps), energy, water, benchmarking |
| Created | 2013-12-11T17:57:17Z |
| Publication Date | 2013-12-12T16:52:53Z |

## Description

In September 2012, New York City released the 2011 energy and water use data for all properties required to annually benchmark under Local Law 84.

## Columns

```ls
| Included | Schema Type    | Field Name                       | Name                             | Data Type | Render Type |
| ======== | ============== | ================================ | ================================ | ========= | =========== |
| Yes      | numeric metric | bbl                              | BBL                              | number    | number      |
| Yes      | series tag     | street_number                    | Street Number                    | text      | number      |
| Yes      | series tag     | street_name                      | Street Name                      | text      | text        |
| Yes      | series tag     | borough                          | Borough                          | text      | text        |
| Yes      | series tag     | zip                              | Zip                              | text      | number      |
| Yes      | series tag     | benchmarking_submission          | Benchmarking Submission          | text      | text        |
| Yes      | series tag     | entry_number                     | Entry Number                     | text      | number      |
| Yes      | numeric metric | site_eui                         | Site EUI                         | number    | number      |
| Yes      | numeric metric | weather_normalized_source_eui    | Weather Normalized Source EUI    | number    | number      |
| Yes      | numeric metric | water_per_square_foot            | Water per Square Foot            | number    | number      |
| Yes      | numeric metric | energy_star_score                | ENERGY STAR Score                | number    | text        |
| Yes      | numeric metric | ghg                              | GHG                              | number    | number      |
| Yes      | numeric metric | reported_building_square_footage | Reported Building Square Footage | number    | number      |
| Yes      | series tag     | reported_facility_type           | Reported Facility Type           | text      | text        |
| Yes      | numeric metric | number_of_buildings              | Number of Buildings              | number    | number      |
| Yes      | numeric metric | reported_bins                    | Reported BINs                    | number    | number      |
```

## Time Field

```ls
Value = 2011
Format & Zone = yyyy
```

## Data Commands

```ls
series e:q39e-7gbs d:2011-01-01T00:00:00.000Z t:zip=10004 t:street_name="BROAD STREET" t:street_number=115 t:borough=MANHATTAN t:benchmarking_submission="No DOF Record as of 08/01/12" m:bbl=1000050010

series e:q39e-7gbs d:2011-01-01T00:00:00.000Z t:zip=10004 t:entry_number=1518 t:reported_facility_type=Office t:street_name="WHITEHALL STREET" t:street_number=34 t:borough=MANHATTAN t:benchmarking_submission=Yes m:bbl=1000090001 m:weather_normalized_source_eui=437.40000000000003 m:energy_star_score=27 m:reported_building_square_footage=852840 m:ghg=12077.53 m:number_of_buildings=1 m:reported_bins=1000018 m:site_eui=157.9

series e:q39e-7gbs d:2011-01-01T00:00:00.000Z t:zip=10004 t:entry_number=312 t:reported_facility_type=Office t:street_name="STATE STREET" t:street_number=17 t:borough=MANHATTAN t:benchmarking_submission=Yes m:bbl=1000090014 m:weather_normalized_source_eui=278.7 m:energy_star_score=61 m:reported_building_square_footage=574105 m:ghg=4817.62 m:number_of_buildings=1 m:reported_bins=1000020 m:site_eui=91.5
```

## Meta Commands

```ls
metric m:bbl p:long l:BBL t:dataTypeName=number

metric m:site_eui p:float l:"Site EUI" t:dataTypeName=number

metric m:weather_normalized_source_eui p:double l:"Weather Normalized Source EUI" t:dataTypeName=number

metric m:water_per_square_foot p:float l:"Water per Square Foot" t:dataTypeName=number

metric m:ghg p:decimal l:GHG t:dataTypeName=number

metric m:reported_building_square_footage p:integer l:"Reported Building Square Footage" t:dataTypeName=number

metric m:number_of_buildings p:integer l:"Number of Buildings" t:dataTypeName=number

metric m:reported_bins p:long l:"Reported BINs" t:dataTypeName=number

entity e:q39e-7gbs l:"Energy and Water Data Disclosure for Local Law 84 (2011)" t:attribution="Mayor's Office of Long-Term Planning and Sustainability (OLTPS)" t:url=https://data.cityofnewyork.us/api/views/q39e-7gbs

property e:q39e-7gbs t:meta.view v:id=q39e-7gbs v:category=Environment v:averageRating=0 v:name="Energy and Water Data Disclosure for Local Law 84 (2011)" v:attribution="Mayor's Office of Long-Term Planning and Sustainability (OLTPS)"

property e:q39e-7gbs t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:q39e-7gbs t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| bbl        | street_number | street_name      | borough   | zip   | benchmarking_submission      | entry_number | site_eui           | weather_normalized_source_eui | water_per_square_foot | energy_star_score | ghg                | reported_building_square_footage | reported_facility_type | number_of_buildings | reported_bins | 
| ========== | ============= | ================ | ========= | ===== | ============================ | ============ | ================== | ============================= | ===================== | ================= | ================== | ================================ | ====================== | =================== | ============= | 
| 1000050010 | 115           | BROAD STREET     | MANHATTAN | 10004 | No DOF Record as of 08/01/12 |              |                    |                               |                       |                   |                    |                                  |                        |                     |               | 
| 1000090001 | 34            | WHITEHALL STREET | MANHATTAN | 10004 | Yes                          | 1518         | 157.9              | 437.40000000000003            |                       | 27                | 12077.53           | 852840                           | Office                 | 1                   | 1000018       | 
| 1000090014 | 17            | STATE STREET     | MANHATTAN | 10004 | Yes                          | 312          | 91.5               | 278.7                         |                       | 61                | 4817.62            | 574105                           | Office                 | 1                   | 1000020       | 
| 1000090029 | 24            | WHITEHALL STREET | MANHATTAN | 10004 | Yes                          | 52           | 137.19999999999999 | 306.60000000000002            | 6.66                  | 41                | 10190.379999999999 | 859807                           | Office                 | 1                   | 1000021       | 
| 1000100014 | 33            | WHITEHALL STREET | MANHATTAN | 10004 | No DOF Record as of 08/01/12 |              |                    |                               |                       |                   |                    |                                  |                        |                     |               | 
| 1000100016 | 90            | BROAD STREET     | MANHATTAN | 10004 | Yes                          | 602          | 53.5               | 153.80000000000001            |                       | 76                | 1846.5             | 380788                           | Office                 | 1                   |               | 
| 1000100023 | 1             | WHITEHALL STREET | MANHATTAN | 10004 | Yes                          | 48           | 113.10000000000001 | 252.1                         | 12.96                 | 58                | 3218.11            | 329991                           | Office                 | 1                   | 1000027       | 
| 1000110021 | 80            | BROAD STREET     | MANHATTAN | 10004 | Yes                          | 2531         | 77.2               | 194.6                         |                       | 69                | 2719.82            | 400000                           | Office                 | 1                   | 1000038       | 
| 1000130001 | 1             | BROADWAY         | MANHATTAN | 10004 | Yes                          | 1925         |                    |                               |                       | N/A               |                    | 182899                           | Office                 | 1                   |               | 
| 1000130005 | 11            | BROADWAY         | MANHATTAN | 10004 | Yes                          | 275          | 100.9              | 237.20000000000002            |                       | 72                | 3717.62            | 423348                           | Office                 | 1                   |               | 
```