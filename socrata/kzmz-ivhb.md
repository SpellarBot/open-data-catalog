# DSNY's Refuse and Recycling Disposal Networks

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dsnys-refuse-and-recycling-disposal-networks-d0e72) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/kzmz-ivhb) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/kzmz-ivhb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/kzmz-ivhb/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | kzmz-ivhb |
| Name | DSNY's Refuse and Recycling Disposal Networks |
| Attribution | Department of Sanitation (DSNY) |
| Category | City Government |
| Tags | sanitation, services, community, district, refuse, paper, metal, glass, plastic, recycle, recycling, clean web |
| Created | 2011-10-10T22:48:24Z |
| Publication Date | 2017-09-18T20:29:21Z |

## Description

For each Community District, the name and address of the location where Refuse, Paper, and Metal/Glass/Plastic collected in that district are disposed of under normal operating circumstances.
Update Schedule: As required

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                      | Data Type | Render Type |
| ======== | ============== | ========================= | ========================= | ========= | =========== |
| No       | time           | :updated_at               | updated_at                | meta_data | meta_data   |
| Yes      | series tag     | district                  | District                  | text      | text        |
| Yes      | series tag     | material                  | Material                  | text      | text        |
| Yes      | series tag     | primary_disposal_facility | Primary Disposal Facility | text      | text        |
| Yes      | series tag     | location                  | Location                  | text      | text        |
| Yes      | series tag     | borough                   | Borough                   | text      | text        |
| Yes      | series tag     | postcode                  | Postcode                  | text      | number      |
| No       |                | latitude                  | Latitude                  | number    | number      |
| No       |                | longitude                 | Longitude                 | number    | number      |
| Yes      | numeric metric | community_board           | Community Board           | number    | number      |
| Yes      | numeric metric | community_council         | Council District          | number    | number      |
| Yes      | numeric metric | census_tract              | Census Tract              | number    | number      |
| Yes      | numeric metric | bin                       | BIN                       | number    | number      |
| Yes      | numeric metric | bbl                       | BBL                       | number    | number      |
| Yes      | series tag     | nta                       | NTA                       | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = latitude,longitude
```

## Data Commands

```ls
series e:kzmz-ivhb d:2017-09-18T20:28:40.000Z t:material=Refuse t:district=BK01 t:postcode=11237 t:location="215 Varick Ave Brooklyn, NY" t:nta="East Williamsburg" t:borough=BROOKLYN t:primary_disposal_facility="WM - Varick" m:bin=3332350 m:community_board=1 m:bbl=3029500001 m:community_council=34 m:census_tract=449

series e:kzmz-ivhb d:2017-09-18T20:28:40.000Z t:material="Met, Glass, Plastic" t:district=BK01 t:postcode=11222 t:location="30-27 Greenpoint Avenue LIC, NY" t:nta=Greenpoint t:borough=BROOKLYN t:primary_disposal_facility="Sims - LIC" m:bin=3336968 m:community_board=1 m:bbl=3025560001 m:community_council=33 m:census_tract=565

series e:kzmz-ivhb d:2017-09-18T20:28:40.000Z t:material=Paper t:district=BK01 t:postcode=11222 t:location="30-27 Greenpoint Avenue LIC, NY" t:nta=Greenpoint t:borough=BROOKLYN t:primary_disposal_facility="Sims LIC" m:bin=3336968 m:community_board=1 m:bbl=3025560001 m:community_council=33 m:census_tract=565
```

## Meta Commands

```ls
metric m:community_board p:integer l:"Community Board" t:dataTypeName=number

metric m:community_council p:integer l:"Council District" t:dataTypeName=number

metric m:census_tract p:integer l:"Census Tract" t:dataTypeName=number

metric m:bin p:integer l:BIN t:dataTypeName=number

metric m:bbl p:long l:BBL t:dataTypeName=number

entity e:kzmz-ivhb l:"DSNY's Refuse and Recycling Disposal Networks" t:attribution="Department of Sanitation (DSNY)" t:url=https://data.cityofnewyork.us/api/views/kzmz-ivhb

property e:kzmz-ivhb t:meta.view d:2017-09-25T07:26:56.462Z v:averageRating=0 v:name="DSNY's Refuse and Recycling Disposal Networks" v:attribution="Department of Sanitation (DSNY)" v:id=kzmz-ivhb v:category="City Government"

property e:kzmz-ivhb t:meta.view.owner d:2017-09-25T07:26:56.462Z v:displayName="NYC OpenData" v:lastNotificationSeenAt=1496414226 v:id=5fuc-pqz2 v:screenName="NYC OpenData"

property e:kzmz-ivhb t:meta.view.tableauthor d:2017-09-25T07:26:56.462Z v:displayName="NYC OpenData" v:lastNotificationSeenAt=1496414226 v:roleName=administrator v:id=5fuc-pqz2 v:screenName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | district | material            | primary_disposal_facility | location                        | borough  | postcode | latitude  | longitude  | community_board | community_council | census_tract | bin     | bbl        | nta                                      | 
| =========== | ======== | =================== | ========================= | =============================== | ======== | ======== | ========= | ========== | =============== | ================= | ============ | ======= | ========== | ======================================== | 
| 1505766520  | BK01     | Refuse              | WM - Varick               | 215 Varick Ave Brooklyn, NY     | BROOKLYN | 11237    | 40.7145   | -73.929744 | 1               | 34                | 449          | 3332350 | 3029500001 | East Williamsburg                        | 
| 1505766520  | BK01     | Met, Glass, Plastic | Sims - LIC                | 30-27 Greenpoint Avenue LIC, NY | BROOKLYN | 11222    | 40.737347 | -73.943138 | 1               | 33                | 565          | 3336968 | 3025560001 | Greenpoint                               | 
| 1505766520  | BK01     | Paper               | Sims LIC                  | 30-27 Greenpoint Avenue LIC, NY | BROOKLYN | 11222    | 40.737347 | -73.943138 | 1               | 33                | 565          | 3336968 | 3025560001 | Greenpoint                               | 
| 1505766520  | BK02     | Paper               | Visy                      | 4435 Victory Blvd SI, NY        |          |          | 40.587147 | -74.199155 |                 |                   |              |         |            |                                          | 
| 1505766520  | BK02     | Met, Glass, Plastic | Sims Bklyn                | 472 2nd Ave Brooklyn, NY        | BROOKLYN | 11232    | 40.661202 | -74.005105 | 7               | 38                | 18           | 3378171 | 3006620001 | Sunset Park West                         | 
| 1505766520  | BK02     | Refuse              | IESI - Court              | 577 Court St Brooklyn, NY       | BROOKLYN | 11231    | 40.672944 | -74.000227 | 6               | 38                | 53           | 3008194 | 3004840001 | Carroll Gardens-Columbia Street-Red Hook | 
| 1505766520  | BK03     | Refuse              | WM - Varick               | 215 Varick Ave Brooklyn, NY     | BROOKLYN | 11237    | 40.7145   | -73.929744 | 1               | 34                | 449          | 3332350 | 3029500001 | East Williamsburg                        | 
| 1505766520  | BK03     | Met, Glass, Plastic | Sims - LIC                | 30-27 Greenpoint Avenue LIC, NY | BROOKLYN | 11222    | 40.737347 | -73.943138 | 1               | 33                | 565          | 3336968 | 3025560001 | Greenpoint                               | 
| 1505766520  | BK03     | Paper               | Sims LIC                  | 30-27 Greenpoint Avenue LIC, NY | BROOKLYN | 11222    | 40.737347 | -73.943138 | 1               | 33                | 565          | 3336968 | 3025560001 | Greenpoint                               | 
| 1505766520  | BK04     | Refuse              | WM - Varick               | 215 Varick Ave Brooklyn, NY     | BROOKLYN | 11237    | 40.7145   | -73.929744 | 1               | 34                | 449          | 3332350 | 3029500001 | East Williamsburg                        | 
```