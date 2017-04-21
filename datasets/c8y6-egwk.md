# Stormwater Management Concept Information

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/stormwater-management-concept-information) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/c8y6-egwk) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/c8y6-egwk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/c8y6-egwk/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | c8y6-egwk |
| Name | Stormwater Management Concept Information |
| Category | Licenses/Permits |
| Tags | permit, stormwater |
| Created | 2015-03-24T23:59:32Z |
| Publication Date | 2015-03-25T17:32:32Z |

## Description

A stormwater management concept is a statement or drawing, or both, describing the manner in which stormwater runoff from a proposed development will be controlled to minimize damage to neighboring properties and receiving streams and to also prevent the discharge of pollutants into surface waters. Update Frequency : Daily.

## Columns

```ls
| Included | Schema Type    | Field Name                     | Name                           | Data Type     | Render Type   |
| ======== | ============== | ============================== | ============================== | ============= | ============= |
| Yes      | series tag     | applicationtype                | Application Type               | text          | text          |
| Yes      | series tag     | application_number             | Application Number             | text          | text          |
| Yes      | time           | process_date                   | Process Date                   | calendar_date | calendar_date |
| No       |                | approveddate                   | Approved Date                  | calendar_date | calendar_date |
| Yes      | series tag     | project_name                   | Project Name                   | text          | text          |
| Yes      | series tag     | comments                       | Comments                       | text          | text          |
| Yes      | series tag     | wssc_map                       | WSSC Map                       | text          | text          |
| Yes      | series tag     | tax_map                        | Tax Map                        | text          | text          |
| Yes      | numeric metric | site_area                      | Site Area                      | number        | number        |
| Yes      | numeric metric | proposed_disturbed_area        | Proposed Disturbed Area        | number        | number        |
| Yes      | numeric metric | proposed_impervious_area       | Proposed Impervious Area       | number        | number        |
| Yes      | series tag     | current_zoning                 | Current Zoning                 | text          | text          |
| Yes      | series tag     | proposed_zoning                | Proposed Zoning                | text          | text          |
| Yes      | series tag     | current_land_use               | Current Land use               | text          | text          |
| Yes      | series tag     | proposed_land_use              | Proposed Land Use              | text          | text          |
| Yes      | series tag     | watershed                      | Watershed                      | text          | text          |
| Yes      | series tag     | state_water_use                | State Water Use                | text          | text          |
| Yes      | series tag     | tributary                      | Tributary                      | text          | text          |
| Yes      | series tag     | requested_waiver               | Requested Waiver               | text          | text          |
| Yes      | series tag     | resubmittal                    | Resubmittal                    | text          | text          |
| Yes      | series tag     | revision                       | Revision                       | text          | text          |
| Yes      | series tag     | onsite_quantitycontrol         | Onsite Quantity Control        | text          | text          |
| Yes      | numeric metric | quantitycontrol_ac             | Quantity Control               | number        | number        |
| Yes      | series tag     | onsite_qualitycontrol          | Onsite Quality Control         | text          | text          |
| Yes      | numeric metric | qualitycontrol_ac              | Quality Control                | number        | number        |
| Yes      | series tag     | quantity_waiver_proposed       | Quantity Waiver Proposed       | text          | text          |
| Yes      | numeric metric | quantity_waiver_acres_proposed | Quantity Waiver Acres Proposed | number        | number        |
| Yes      | series tag     | quality_waiver_proposed        | Quality Waiver Proposed        | text          | text          |
| Yes      | numeric metric | quality_waiver_acres_proposed  | Quality Waiver Acres Proposed  | number        | number        |
| Yes      | series tag     | stno                           | Street Number                  | text          | text          |
| Yes      | series tag     | predir                         | Pre-direction                  | text          | text          |
| Yes      | series tag     | stname                         | Street Name                    | text          | text          |
| Yes      | series tag     | suffix                         | Street Suffix                  | text          | text          |
| Yes      | series tag     | postdir                        | Post-direction                 | text          | text          |
| Yes      | series tag     | city                           | City                           | text          | text          |
| Yes      | series tag     | state                          | State                          | text          | text          |
| Yes      | series tag     | zip                            | ZIP code                       | text          | number        |
| Yes      | series tag     | location                       | Work Location                  | text          | text          |
```

## Time Field

```ls
Value = process_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = approveddate
```

## Data Commands

```ls
series e:c8y6-egwk d:2004-01-27T00:00:00.000Z t:project_name="PATTON PROPERTY" t:location="NORWOOD ROAD & NORBECK ROAD EXTENDED, PARCEL 915" t:current_land_use=RESID t:current_zoning=RE-2C t:tax_map=JS342 t:requested_waiver=N t:watershed=NWB t:revision=N t:applicationtype="STORMWATER CONCEPT" t:quality_waiver_proposed=N t:proposed_land_use=RESID t:onsite_quantitycontrol=Y t:quantity_waiver_proposed=N t:proposed_zoning=RE-2C t:state_water_use="RECREATION TROUT" t:resubmittal=N t:onsite_qualitycontrol=Y t:comments="PARCEL P915" t:wssc_map=221NW1 t:application_number=211130 m:site_area=15.1 m:quantity_waiver_acres_proposed=0 m:quantitycontrol_ac=6.2 m:proposed_disturbed_area=6.2 m:quality_waiver_acres_proposed=0 m:proposed_impervious_area=1.2 m:qualitycontrol_ac=6.2

series e:c8y6-egwk d:2012-06-12T00:00:00.000Z t:location="MUNCASTER MILL ROAD BETWEEN MAGRUDER HIGH SCHOOL AND THE ICC" t:current_land_use=ROADWAY t:tax_map=GS563 t:requested_waiver=N t:watershed=URC t:revision=N t:applicationtype="STORMWATER CONCEPT" t:proposed_land_use=ROADWAY t:quality_waiver_proposed=N t:onsite_quantitycontrol=Y t:quantity_waiver_proposed=N t:state_water_use="RECREATION TROUT" t:resubmittal=N t:onsite_qualitycontrol=Y t:wssc_map=222NWO5 t:application_number=243512 m:site_area=1.9 m:quantity_waiver_acres_proposed=0 m:quantitycontrol_ac=1.9 m:proposed_disturbed_area=1.9 m:quality_waiver_acres_proposed=0 m:proposed_impervious_area=0.8 m:qualitycontrol_ac=1.9

series e:c8y6-egwk d:2002-09-23T00:00:00.000Z t:project_name="VALOIS PROPRETY" t:location="PARCEL 76, CRYSTAL SPRING DRIVE" t:current_zoning=RE-2 t:tax_map=JT341 t:requested_waiver=N t:watershed=NWB t:revision=N t:applicationtype="STORMWATER CONCEPT" t:quality_waiver_proposed=N t:onsite_quantitycontrol=Y t:quantity_waiver_proposed=N t:proposed_zoning=RE-2 t:state_water_use="RECREATION TROUT" t:resubmittal=N t:onsite_qualitycontrol=Y t:comments="Lot 29/D, Parcel P76" t:wssc_map=223NW01 t:application_number=206657 m:site_area=2 m:quantity_waiver_acres_proposed=0 m:quantitycontrol_ac=2.1 m:proposed_disturbed_area=1 m:quality_waiver_acres_proposed=0 m:proposed_impervious_area=0.1 m:qualitycontrol_ac=2.1
```

## Meta Commands

```ls
metric m:site_area p:float l:"Site Area" d:"The number of acres that the Stormwater Management Concept includes." t:dataTypeName=number

metric m:proposed_disturbed_area p:float l:"Proposed Disturbed Area" d:"The number of acres disturbed in the plan." t:dataTypeName=number

metric m:proposed_impervious_area p:float l:"Proposed Impervious Area" d:"The number of proposed impervious acres in the plan." t:dataTypeName=number

metric m:quantitycontrol_ac p:float l:"Quantity Control" d:"Quantity Control" t:dataTypeName=number

metric m:qualitycontrol_ac p:float l:"Quality Control" d:"Quality Control" t:dataTypeName=number

metric m:quantity_waiver_acres_proposed p:double l:"Quantity Waiver Acres Proposed" d:"Quantity Waiver Acres Proposed" t:dataTypeName=number

metric m:quality_waiver_acres_proposed p:double l:"Quality Waiver Acres Proposed" d:"Quality Waiver Acres Proposed" t:dataTypeName=number

entity e:c8y6-egwk l:"Stormwater Management Concept Information" t:url=https://data.montgomerycountymd.gov/api/views/c8y6-egwk

property e:c8y6-egwk t:meta.view v:id=c8y6-egwk v:category=Licenses/Permits v:averageRating=0 v:name="Stormwater Management Concept Information"

property e:c8y6-egwk t:meta.view.owner v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"

property e:c8y6-egwk t:meta.view.tableauthor v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:roleName=administrator v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"
```

## Top Records

```ls
| applicationtype    | application_number | process_date        | approveddate        | project_name                   | comments                                               | wssc_map | tax_map | site_area | proposed_disturbed_area | proposed_impervious_area | current_zoning | proposed_zoning | current_land_use | proposed_land_use | watershed | state_water_use  | tributary | requested_waiver | resubmittal | revision | onsite_quantitycontrol | quantitycontrol_ac | onsite_qualitycontrol | qualitycontrol_ac | quantity_waiver_proposed | quantity_waiver_acres_proposed | quality_waiver_proposed | quality_waiver_acres_proposed | stno | predir | stname | suffix | postdir | city | state | zip | location                                                                                              | 
| ================== | ================== | =================== | =================== | ============================== | ====================================================== | ======== | ======= | ========= | ======================= | ======================== | ============== | =============== | ================ | ================= | ========= | ================ | ========= | ================ | =========== | ======== | ====================== | ================== | ===================== | ================= | ======================== | ============================== | ======================= | ============================= | ==== | ====== | ====== | ====== | ======= | ==== | ===== | === | ===================================================================================================== | 
| STORMWATER CONCEPT | 211130             | 2004-01-27T00:00:00 | 2004-04-16T00:00:00 | PATTON PROPERTY                | PARCEL P915                                            | 221NW1   | JS342   | 15.1      | 6.2                     | 1.2                      | RE-2C          | RE-2C           | RESID            | RESID             | NWB       | RECREATION TROUT |           | N                | N           | N        | Y                      | 6.2                | Y                     | 6.2               | N                        | 0                              | N                       | 0                             |      |        |        |        |         |      |       |     | NORWOOD ROAD & NORBECK ROAD EXTENDED, PARCEL 915                                                      | 
| STORMWATER CONCEPT | 243512             | 2012-06-12T00:00:00 | 2012-09-24T00:00:00 |                                |                                                        | 222NWO5  | GS563   | 1.9       | 1.9                     | 0.8                      |                |                 | ROADWAY          | ROADWAY           | URC       | RECREATION TROUT |           | N                | N           | N        | Y                      | 1.9                | Y                     | 1.9               | N                        | 0                              | N                       | 0                             |      |        |        |        |         |      |       |     | MUNCASTER MILL ROAD BETWEEN MAGRUDER HIGH SCHOOL AND THE ICC                                          | 
| STORMWATER CONCEPT | 206657             | 2002-09-23T00:00:00 | 2002-10-25T00:00:00 | VALOIS PROPRETY                | Lot 29/D, Parcel P76                                   | 223NW01  | JT341   | 2         | 1                       | 0.1                      | RE-2           | RE-2            |                  |                   | NWB       | RECREATION TROUT |           | N                | N           | N        | Y                      | 2.1                | Y                     | 2.1               | N                        | 0                              | N                       | 0                             |      |        |        |        |         |      |       |     | PARCEL 76, CRYSTAL SPRING DRIVE                                                                       | 
| STORMWATER CONCEPT | 228742             | 2006-10-06T00:00:00 | 2007-03-05T00:00:00 | BONIFANT PLAZA                 | Lots 10, pts of lot 12 & 12A/1                         | 210NE1NW | JN33    | 0.4       | 0.4                     | 0.3                      | CBD-1          | CBD-1           | RETAIL           | RESIDENT          | SCR       | GENERAL USE      |           | N                | N           | N        | Y                      | 0.4                | Y                     | 0.3               | N                        | 0                              | Y                       | 0.1                           |      |        |        |        |         |      |       |     | BONIFANT ST, BETEEN GEORGIA AVE & FENTON STREET                                                       | 
| STORMWATER CONCEPT | 259995             | 2013-12-18T00:00:00 | 2015-03-04T00:00:00 | COUNTRY CLUB HILLS             |                                                        | 208NW06  | GN61    | 0.2       | 0.2                     | 0                        | R-60           | R-60            | RESIDENT         | RESIDENT          | LFB       | GENERAL USE      |           | N                | N           | N        | Y                      | 0.2                | Y                     | 0.2               | N                        | 0                              | N                       | 0                             |      |        |        |        |         |      |       |     | 5712 RIVER ROAD, BETHESDA, MD 20816 (PART OF LOTS 8 & 9)                                              | 
| STORMWATER CONCEPT | 235445             | 2009-03-27T00:00:00 |                     | 3RD DISTRICT POLICE STATION    | 3RD DISTRICT POLICE STATION - PARCELS P790, P731, P725 | 219NE01  | JQ62    | 12.8      | 5.9                     | 2.1                      | R-90           | LSC             | FORESTED         | POLICE            | PBR       | NATURAL TROUT    |           | N                | N           | Y        | Y                      | 3.6                | Y                     | 3.6               | N                        | 0                              | N                       | 0                             |      |        |        |        |         |      |       |     | MILESTONE DRIVE, WHITE OAK, MD 20904                                                                  | 
| STORMWATER CONCEPT | 204843             | 2002-02-11T00:00:00 | 2002-02-15T00:00:00 | SNOWDENS MANOR/BROOKE PROPERTY | Parcels 543 & 655; Revision approved 11/18/03          | 223NE2   | KT341   | 30.1      | 5.5                     | 1                        | RC             | RC              | RESID            | RESID             | LPR       | GENERAL USE      |           | N                | N           | N        | Y                      | 5.5                | Y                     | 5.5               | N                        | 0                              | N                       | 0                             |      |        |        |        |         |      |       |     | END OF EXISTING OAK HILL RD, APPROXIMATELY 6000'+ NORTH OF SPENCERVILLE RD                            | 
| STORMWATER CONCEPT | 211123             | 2004-01-23T00:00:00 | 2004-04-26T00:00:00 | TWINBROOK COMMONS              | refer to appendix "F" for lots/Block 8, Parcel "A"     | 216NW06  | GQ563   | 16.2      | 16.2                    | 13                       | R-90           | TS-R            | PARKING          | RES/COMM          | LRC       | GENERAL USE      |           | N                | N           | N        | Y                      | 16.2               | Y                     | 16.2              | N                        | 0                              | N                       | 0                             |      |        |        |        |         |      |       |     | BETWEEN EXISTING RR TRACKS & ARDENNES RD, NORTH OF TWINBROOK PKY ON EXISTING WMATA TWINBROOK STATION. | 
| STORMWATER CONCEPT | 212825             | 2004-05-28T00:00:00 | 2004-07-26T00:00:00 | MONTG VILLAGE/CANDLE RIDGE     | part of parcel F                                       | 277NW9   | FU63    | 0.2       | 0.2                     | 0.1                      |                |                 |                  |                   | GSC       | GENERAL USE      |           | N                | N           | N        | Y                      | 0.2                | Y                     | 0.2               | N                        | 0                              | N                       | 0                             |      |        |        |        |         |      |       |     | EAST VILLAGE AVE, MONTGOMERY VILAGE, PART OF PARCEL F                                                 | 
| STORMWATER CONCEPT | 203425             | 2001-03-19T00:00:00 | 2001-08-27T00:00:00 | KENGAR SWM WETLAND             | Kengar SWM Wetlandx                                    | 214NW04  | HQ41    | 7.5       | 1.5                     | 0                        | R-60           | R-60            | PARK             | PARK              | LRC       | GENERAL USE      |           | N                | N           | N        | N                      | 0                  | Y                     | 60                | N                        | 0                              | N                       | 0                             |      |        |        |        |         |      |       |     | 4100 BLOCK OFWEXFORD (NEAR BEACH DR)                                                                  | 
```