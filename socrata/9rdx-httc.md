# Mayor?s Office of Housing and Community Development Affordable Rental Portfolio

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/mayors-office-of-housing-and-community-development-affordable-rental-portfolio) |
| Metadata | [Link](https://data.sfgov.org/api/views/9rdx-httc) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/9rdx-httc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/9rdx-httc/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | 9rdx-httc |
| Name | Mayor?s Office of Housing and Community Development Affordable Rental Portfolio |
| Attribution | Mayor's Office of Housing and Community Development |
| Category | Housing and Buildings |
| Created | 2016-02-04T23:32:01Z |
| Publication Date | 2016-06-15T19:17:10Z |

## Description

Affordable rental housing developed in partnership with non-profit and private developers and financed through the Mayor?s Office of Housing and Community Development (MOHCD) and the Office of Community Investment and Infrastructure (OCII) through City Funding Agreements, Ground Leases, Disposition & Participation Agreements and Conduit Mortgage Revenue Bond Financing, as of December 31, 2015.

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                        | Data Type | Render Type |
| ======== | ============== | =========================== | =========================== | ========= | =========== |
| No       | time           | :updated_at                 | updated_at                  | meta_data | meta_data   |
| Yes      | series tag     | project_id                  | Project ID                  | text      | number      |
| Yes      | series tag     | project_status              | Project Status              | text      | text        |
| Yes      | series tag     | project_name                | Project Name                | text      | text        |
| No       |                | project_address             | Project Address             | text      | text        |
| Yes      | series tag     | project_sponsor             | Project Sponsor             | text      | text        |
| Yes      | numeric metric | total_units                 | Total Units                 | number    | number      |
| Yes      | numeric metric | total_beds                  | Total Beds                  | number    | number      |
| Yes      | numeric metric | affordable_units            | Affordable Units            | number    | number      |
| Yes      | numeric metric | affordable_beds             | Affordable Beds             | number    | number      |
| Yes      | numeric metric | single_room_occupancy_units | Single Room Occupancy Units | number    | number      |
| Yes      | numeric metric | studio_units                | Studio Units                | number    | number      |
| Yes      | numeric metric | 1_bedroom_units             | 1 Bedroom Units             | number    | number      |
| Yes      | numeric metric | 2_bedroom_units             | 2 Bedroom Units             | number    | number      |
| Yes      | numeric metric | 3_bedroom_units             | 3 Bedroom Units             | number    | number      |
| Yes      | numeric metric | 4_bedroom_units             | 4 Bedroom Units             | number    | number      |
| Yes      | numeric metric | 5_bedroom_or_larger_units   | 5 Bedroom or Larger Units   | number    | number      |
| Yes      | numeric metric | units_at_20_ami             | Units at 20% AMI            | number    | number      |
| Yes      | numeric metric | units_at_30_ami             | Units at 30% AMI            | number    | number      |
| Yes      | numeric metric | units_at_50_ami             | Units at 50% AMI            | number    | number      |
| Yes      | numeric metric | units_at_60_ami             | Units at 60% AMI            | number    | number      |
| Yes      | numeric metric | units_at_80_ami             | Units at 80% AMI            | number    | number      |
| Yes      | numeric metric | units_at_120_ami            | Units at 120% AMI           | number    | number      |
| Yes      | numeric metric | units_greater_than_120_ami  | Units Greater Than 120% AMI | number    | number      |
| Yes      | numeric metric | losp_units                  | LOSP Units                  | number    | number      |
| Yes      | series tag     | losp_funding_agency         | LOSP Funder                 | text      | text        |
| Yes      | series tag     | neighborhood                | Neighborhood                | text      | text        |
| Yes      | series tag     | supervisor_district         | Supervisor District         | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = project_address
```

## Data Commands

```ls
series e:9rdx-httc d:2016-06-15T12:12:28.000Z t:project_sponsor="Mei Fong And Associates" t:project_status=Operational t:project_name="Asian Women's Shelter" t:project_id=1 m:units_at_120_ami=0 m:units_at_30_ami=0 m:1_bedroom_units=0 m:units_greater_than_120_ami=0 m:single_room_occupancy_units=0 m:4_bedroom_units=0 m:total_units=5 m:losp_units=0 m:units_at_20_ami=0 m:3_bedroom_units=0 m:units_at_80_ami=0 m:total_beds=16 m:affordable_units=0 m:2_bedroom_units=0 m:affordable_beds=16 m:5_bedroom_or_larger_units=0 m:studio_units=0 m:units_at_60_ami=16 m:units_at_50_ami=0

series e:9rdx-httc d:2016-06-15T12:12:28.000Z t:project_sponsor="St. Vincent De Paul Society" t:project_status=Operational t:project_name="Brennan House" t:project_id=2 m:units_at_120_ami=0 m:units_at_30_ami=0 m:1_bedroom_units=0 m:units_greater_than_120_ami=0 m:single_room_occupancy_units=15 m:4_bedroom_units=0 m:total_units=15 m:losp_units=0 m:units_at_20_ami=0 m:3_bedroom_units=0 m:units_at_80_ami=0 m:total_beds=0 m:affordable_units=15 m:2_bedroom_units=0 m:affordable_beds=0 m:5_bedroom_or_larger_units=0 m:studio_units=0 m:units_at_60_ami=12 m:units_at_50_ami=3

series e:9rdx-httc d:2016-06-15T12:12:28.000Z t:project_sponsor="Mercy Housing California" t:project_status=Operational t:project_name="Mercy Family Plaza" t:project_id=3 t:neighborhood="Lone Mountain/USF" t:supervisor_district=5 m:units_at_120_ami=0 m:units_at_30_ami=0 m:1_bedroom_units=6 m:units_greater_than_120_ami=0 m:single_room_occupancy_units=0 m:4_bedroom_units=0 m:total_units=36 m:losp_units=0 m:units_at_20_ami=0 m:3_bedroom_units=5 m:units_at_80_ami=22 m:total_beds=0 m:affordable_units=22 m:2_bedroom_units=8 m:affordable_beds=0 m:5_bedroom_or_larger_units=0 m:studio_units=3 m:units_at_60_ami=0 m:units_at_50_ami=0
```

## Meta Commands

```ls
metric m:total_units p:integer l:"Total Units" t:dataTypeName=number

metric m:total_beds p:integer l:"Total Beds" t:dataTypeName=number

metric m:affordable_units p:integer l:"Affordable Units" t:dataTypeName=number

metric m:affordable_beds p:integer l:"Affordable Beds" t:dataTypeName=number

metric m:single_room_occupancy_units p:integer l:"Single Room Occupancy Units" t:dataTypeName=number

metric m:studio_units p:integer l:"Studio Units" t:dataTypeName=number

metric m:1_bedroom_units p:integer l:"1 Bedroom Units" t:dataTypeName=number

metric m:2_bedroom_units p:integer l:"2 Bedroom Units" t:dataTypeName=number

metric m:3_bedroom_units p:integer l:"3 Bedroom Units" t:dataTypeName=number

metric m:4_bedroom_units p:integer l:"4 Bedroom Units" t:dataTypeName=number

metric m:5_bedroom_or_larger_units p:integer l:"5 Bedroom or Larger Units" t:dataTypeName=number

metric m:units_at_20_ami p:integer l:"Units at 20% AMI" t:dataTypeName=number

metric m:units_at_30_ami p:integer l:"Units at 30% AMI" t:dataTypeName=number

metric m:units_at_50_ami p:integer l:"Units at 50% AMI" t:dataTypeName=number

metric m:units_at_60_ami p:integer l:"Units at 60% AMI" t:dataTypeName=number

metric m:units_at_80_ami p:integer l:"Units at 80% AMI" t:dataTypeName=number

metric m:units_at_120_ami p:integer l:"Units at 120% AMI" t:dataTypeName=number

metric m:units_greater_than_120_ami p:integer l:"Units Greater Than 120% AMI" t:dataTypeName=number

metric m:losp_units p:integer l:"LOSP Units" t:dataTypeName=number

entity e:9rdx-httc l:"Mayor?s Office of Housing and Community Development Affordable Rental Portfolio" t:attribution="Mayor's Office of Housing and Community Development" t:url=https://data.sfgov.org/api/views/9rdx-httc

property e:9rdx-httc t:meta.view v:id=9rdx-httc v:category="Housing and Buildings" v:attributionLink=http://sf-moh.org/ v:averageRating=0 v:name="Mayor?s Office of Housing and Community Development Affordable Rental Portfolio" v:attribution="Mayor's Office of Housing and Community Development"

property e:9rdx-httc t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:9rdx-httc t:meta.view.owner v:id=9wvp-x5mw v:screenName="Charlie MacNulty" v:displayName="Charlie MacNulty"

property e:9rdx-httc t:meta.view.tableauthor v:id=9wvp-x5mw v:screenName="Charlie MacNulty" v:roleName=editor v:displayName="Charlie MacNulty"
```

## Top Records

```ls
| :updated_at | project_id | project_status | project_name             | project_address                              | project_sponsor                         | total_units | total_beds | affordable_units | affordable_beds | single_room_occupancy_units | studio_units | 1_bedroom_units | 2_bedroom_units | 3_bedroom_units | 4_bedroom_units | 5_bedroom_or_larger_units | units_at_20_ami | units_at_30_ami | units_at_50_ami | units_at_60_ami | units_at_80_ami | units_at_120_ami | units_greater_than_120_ami | losp_units | losp_funding_agency | neighborhood       | supervisor_district | 
| =========== | ========== | ============== | ======================== | ============================================ | ======================================= | =========== | ========== | ================ | =============== | =========================== | ============ | =============== | =============== | =============== | =============== | ========================= | =============== | =============== | =============== | =============== | =============== | ================ | ========================== | ========== | =================== | ================== | =================== | 
| 1465992748  | 1          | Operational    | Asian Women's Shelter    | 0 Confidential, San Francisco, CA 00000      | Mei Fong And Associates                 | 5           | 16         | 0                | 16              | 0                           | 0            | 0               | 0               | 0               | 0               | 0                         | 0               | 0               | 0               | 16              | 0               | 0                | 0                          | 0          |                     |                    |                     | 
| 1465992748  | 2          | Operational    | Brennan House            | 0 Confidential, San Francisco, CA 00000      | St. Vincent De Paul Society             | 15          | 0          | 15               | 0               | 15                          | 0            | 0               | 0               | 0               | 0               | 0                         | 0               | 0               | 3               | 12              | 0               | 0                | 0                          | 0          |                     |                    |                     | 
| 1465992748  | 3          | Operational    | Mercy Family Plaza       | 1509 Hayes St, San Francisco, CA 94117       | Mercy Housing California                | 36          | 0          | 22               | 0               | 0                           | 3            | 6               | 8               | 5               | 0               | 0                         | 0               | 0               | 0               | 0               | 22              | 0                | 0                          | 0          |                     | Lone Mountain/USF  | 5                   | 
| 1465992748  | 5          | Operational    | Market Heights           | 1000 Tompkins Ave, San Francisco, CA 94110   | Bernal Heights Neighborhood Center      | 46          | 0          | 45               | 0               | 0                           | 0            | 6               | 16              | 22              | 1               | 0                         | 0               | 0               | 22              | 23              | 0               | 0                | 0                          | 0          |                     | Bernal Heights     | 9                   | 
| 1465992748  | 6          | Operational    | San Cristina             | 1000 Market St, San Francisco, CA 94102      | Community Housing Partnership           | 58          | 0          | 58               | 0               | 58                          | 0            | 0               | 0               | 0               | 0               | 0                         | 0               | 0               | 0               | 0               | 58              | 0                | 0                          | 0          |                     | Tenderloin         | 6                   | 
| 1465992748  | 9          | Operational    | Juan Pifarre Plaza       | 1010 South Van Ness, San Francisco, CA 94110 | Mission Housing Development Corporation | 30          | 0          | 29               | 0               | 0                           | 0            | 3               | 8               | 14              | 4               | 0                         | 0               | 0               | 14              | 15              | 0               | 0                | 0                          | 0          |                     | Mission            | 9                   | 
| 1465992748  | 10         | Operational    | Hotel Parkview           | 102 South Park, San Francisco, CA 94107      | Mission Housing Development Corporation | 40          | 0          | 40               | 0               | 36                          | 4            | 0               | 0               | 0               | 0               | 0                         | 0               | 32              | 8               | 0               | 0               | 0                | 0                          | 0          |                     | Financial District | 6                   | 
| 1465992748  | 11         | Operational    | Veterans Academy         | 1030 Girard Rd, San Francisco, CA 94129      | Swords To Plowshares                    | 108         | 0          | 100              | 0               | 100                         | 0            | 0               | 0               | 0               | 0               | 0                         | 0               | 100             | 0               | 0               | 0               | 0                | 0                          | 0          |                     | Presidio           | 2                   | 
| 1465992748  | 12         | Operational    | Mary Elizabeth Inn       | 1040 Bush St, San Francisco, CA 94109        | Mary Elizabeth Inn                      | 92          | 0          | 88               | 0               | 88                          | 0            | 0               | 0               | 0               | 0               | 0                         | 0               | 30              | 58              | 0               | 0               | 0                | 0                          | 0          |                     | Nob Hill           | 3                   | 
| 1465992748  | 13         | Operational    | Abel Gonzales Apartments | 1045 Capp St, San Francisco, CA 94110        | Mission Housing Development Corporation | 30          | 0          | 30               | 0               | 0                           | 9            | 21              | 0               | 0               | 0               | 0                         | 0               | 0               | 30              | 0               | 0               | 0                | 0                          | 0          |                     | Mission            | 9                   | 
```