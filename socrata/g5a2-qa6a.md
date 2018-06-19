# Current Descriptive Data of Municipal Wastewater Treatment Plants

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/current-descriptive-data-of-municipal-wastewater-treatment-plants) |
| Metadata | [Link](https://data.ny.gov/api/views/g5a2-qa6a) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/g5a2-qa6a/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/g5a2-qa6a/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | g5a2-qa6a |
| Name | Current Descriptive Data of Municipal Wastewater Treatment Plants |
| Attribution | New York State Department of Environmental Conservation |
| Category | Energy & Environment |
| Tags | water, treatment, facility, waste, design, spdes |
| Created | 2016-09-30T19:05:50Z |
| Publication Date | 2016-12-28T15:54:36Z |

## Description

Data containing municipal wastewater treatment plant design other features, with data current through the most recent survey.

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type | Render Type |
| ======== | ============== | ====================== | ====================== | ========= | =========== |
| Yes      | series tag     | permittee_name         | Permittee Name         | text      | text        |
| Yes      | series tag     | facility_name          | Facility Name          | text      | text        |
| Yes      | series tag     | county                 | County                 | text      | text        |
| Yes      | series tag     | spdes_number           | SPDES Number           | text      | text        |
| Yes      | series tag     | chief_operator         | Chief Operator         | text      | text        |
| Yes      | series tag     | phone_number           | Phone Number           | text      | text        |
| Yes      | series tag     | receiving_waterbody    | Receiving Waterbody    | text      | text        |
| Yes      | series tag     | drainage_basin         | Drainage Basin         | text      | text        |
| Yes      | series tag     | stream_class           | Stream Class           | text      | text        |
| Yes      | time           | year_built             | Year Built             | number    | number      |
| No       |                | year_updated           | Year Updated           | number    | number      |
| Yes      | numeric metric | design_flow            | Design Flow            | number    | number      |
| Yes      | series tag     | plant_class            | Plant Class            | text      | text        |
| Yes      | numeric metric | population_served      | Population Served      | number    | number      |
| Yes      | numeric metric | number_employees       | Number Employees       | number    | number      |
| Yes      | series tag     | collection_system      | Collection System      | text      | text        |
| Yes      | series tag     | equalization           | Equalization           | text      | text        |
| Yes      | series tag     | screening              | Screening              | text      | text        |
| Yes      | series tag     | grit_removal           | Grit Removal           | text      | text        |
| Yes      | series tag     | pretreatment           | Pretreatment           | text      | text        |
| Yes      | series tag     | primary_settling       | Primary Settling       | text      | text        |
| Yes      | series tag     | intermediate_treatment | Intermediate Treatment | text      | text        |
| Yes      | series tag     | biological_treatment   | Biological Treatment   | text      | text        |
| Yes      | series tag     | filters                | Filters                | text      | text        |
| Yes      | series tag     | disinfection           | Disinfection           | text      | text        |
| Yes      | series tag     | metering               | Metering               | text      | text        |
| Yes      | series tag     | sludge_digestion       | Sludge Digestion       | text      | text        |
| Yes      | series tag     | sludge_thickening      | Sludge Thickening      | text      | text        |
| Yes      | series tag     | sludge_dewatering      | Sludge Dewatering      | text      | text        |
| Yes      | series tag     | sludge_conditioning    | Sludge Conditioning    | text      | text        |
| Yes      | series tag     | sludge_drying_beds     | Sludge Drying Beds     | text      | text        |
| Yes      | series tag     | sludge_storage         | Sludge Storage         | text      | text        |
| Yes      | series tag     | sludge_disposal        | Sludge Disposal        | text      | text        |
| Yes      | series tag     | lagoons                | Lagoons                | text      | text        |
| Yes      | series tag     | additional_treatment   | Additional Treatment   | text      | text        |
```

## Time Field

```ls
Value = year_built
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = year_updated
```

## Data Commands

```ls
series e:g5a2-qa6a d:1936-01-01T00:00:00.000Z t:spdes_number=NY0020524 t:grit_removal="GRIT CHAMBER MECHANICAL GRIT REMOVAL" t:phone_number="(607) 535-9962" t:sludge_thickening=GRAVITY t:sludge_digestion="AEROBIC SLUDGE DIGESTION DIFFUSED AERATI" t:collection_system=S t:plant_class=3A t:receiving_waterbody="SENECA LAKE" t:chief_operator="RICHARD J SCAPTURA" t:metering=ULTRASONIC t:sludge_disposal="LANDSPREADING / LANDFILL" t:permittee_name="WATKINS GLEN (V)" t:screening="BAR RACK/SCREEN (MECHANICALLY CLEANED)" t:primary_settling="SETTLING TANK" t:facility_name="WATKINS GLEN (V) SEWAGE DISPOSAL PLANT" t:county=SCHUYLER t:disinfection="HYPOCHLORITE-CONTACT TANK" t:sludge_dewatering="BELT FILTER PRESS" t:sludge_conditioning=POLYMER t:biological_treatment="COMPLETE MIX ACTIVATED SLUDGE / SECONDARY CLARIFIER" t:stream_class=B(T) t:drainage_basin=07 m:number_employees=3 m:design_flow=0.7 m:population_served=2490

series e:g5a2-qa6a d:1959-01-01T00:00:00.000Z t:spdes_number=NY0020532 t:grit_removal="GRIT CHAMBER (GRAVITY SEPARATION)" t:phone_number="(315) 673-4491" t:sludge_digestion="AEROBIC SLUDGE DIGESTION DIFFUSED AERATI" t:collection_system=S t:plant_class=2A t:sludge_drying_beds="COVERED DRYING BEDS / COVERED SAND / OPEN-ASPHALT" t:receiving_waterbody="NINE MILE CREEK" t:chief_operator="JOHN C HOPKINS" t:metering="PARSHALL FLUME / ULTRASONIC" t:sludge_disposal="LANDFILL / TO ANOTHER TREATMENT PLANT / SCAVENGER" t:permittee_name="MARCELLUS (V) WATER POLLUTION CONTRL PLT" t:screening="BAR RACK/SCREEN (1/2"" TO 2"" OPENINGS)" t:facility_name="MARCELLUS (V) W P C P" t:county=ONONDAGA t:disinfection="DECHLORINATION / CHLORINE GAS DISINFECTION" t:sludge_dewatering="BELT FILTER PRESS" t:sludge_conditioning="LIME TREATMENT / POLYMER" t:biological_treatment="CONTACT STABILIZATION" t:stream_class=C(T) t:drainage_basin=07 m:number_employees=2 m:design_flow=0.38 m:population_served=0

series e:g5a2-qa6a d:1960-01-01T00:00:00.000Z t:spdes_number=NY0020541 t:grit_removal="GRIT CHAMBER (GRAVITY SEPARATION)" t:phone_number="(716) 937-4497" t:sludge_digestion="ANAEROBIC SLUDGE DIGESTION TWO STAGE" t:collection_system=S t:plant_class=3 t:sludge_drying_beds="COVERED DRYING BEDS / OPEN DRYING BED" t:receiving_waterbody="ELLICOTT CREEK" t:chief_operator="ROBERT L HOLTZ" t:metering="PARSHALL FLUME / ULTRASONIC" t:sludge_disposal=LANDFILL t:permittee_name="ALDEN (V)" t:screening="BAR RACK/SCREEN (MECHANICALLY CLEANED) / COARSE SCREEN-HAND CLEANED" t:primary_settling="MECHANICALLY CLEANED CLARIFIER" t:facility_name="ALDEN (V) WASTEWATER TREATMENT PLANT" t:county=ERIE t:disinfection="CHLORINE GAS-CONTACT TANK / SEASONAL" t:sludge_dewatering="BELT FILTER PRESS" t:biological_treatment="ROTATING BIOLOGICAL CONTACTOR" t:stream_class=C t:additional_treatment="POST AERATION" t:drainage_basin=01 t:filters="RAPID SAND (HIGH RATE) FILTERS" m:number_employees=3 m:design_flow=0.65 m:population_served=3500
```

## Meta Commands

```ls
metric m:design_flow p:double l:"Design Flow" d:"Indicates the design flow of the treatment plant in units of million gallons per day (gpd), as indicated in the most recent SPDES permit." t:dataTypeName=number

metric m:population_served p:float l:"Population Served" d:"Refers to the estimation of people living within the service area and connected to the facility." t:dataTypeName=number

metric m:number_employees p:float l:"Number Employees" d:"Refers to the number of employees at the facility. The term ?+P/T? refers to the fact the facility also has some part time employees." t:dataTypeName=number

entity e:g5a2-qa6a l:"Current Descriptive Data of Municipal Wastewater Treatment Plants" t:attribution="New York State Department of Environmental Conservation" t:url=https://data.ny.gov/api/views/g5a2-qa6a

property e:g5a2-qa6a t:meta.view v:id=g5a2-qa6a v:category="Energy & Environment" v:attributionLink=http://www.dec.ny.gov/chemical/8721.html v:averageRating=0 v:name="Current Descriptive Data of Municipal Wastewater Treatment Plants" v:attribution="New York State Department of Environmental Conservation"

property e:g5a2-qa6a t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:g5a2-qa6a t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| permittee_name                           | facility_name                            | county   | spdes_number | chief_operator     | phone_number   | receiving_waterbody | drainage_basin | stream_class | year_built | year_updated | design_flow        | plant_class | population_served | number_employees | collection_system | equalization | screening                                                                            | grit_removal                                                             | pretreatment | primary_settling                  | intermediate_treatment | biological_treatment                                                         | filters                        | disinfection                               | metering                                        | sludge_digestion                         | sludge_thickening | sludge_dewatering | sludge_conditioning      | sludge_drying_beds                                | sludge_storage        | sludge_disposal                                   | lagoons         | additional_treatment                                                                  | 
| ======================================== | ======================================== | ======== | ============ | ================== | ============== | =================== | ============== | ============ | ========== | ============ | ================== | =========== | ================= | ================ | ================= | ============ | ==================================================================================== | ======================================================================== | ============ | ================================= | ====================== | ============================================================================ | ============================== | ========================================== | =============================================== | ======================================== | ================= | ================= | ======================== | ================================================= | ===================== | ================================================= | =============== | ===================================================================================== | 
| WATKINS GLEN (V)                         | WATKINS GLEN (V) SEWAGE DISPOSAL PLANT   | SCHUYLER | NY0020524    | RICHARD J SCAPTURA | (607) 535-9962 | SENECA LAKE         | 07             | B(T)         | 1936       | 1999         | 0.7                | 3A          | 2490.00           | 3.00             | S                 |              | BAR RACK/SCREEN (MECHANICALLY CLEANED)                                               | GRIT CHAMBER MECHANICAL GRIT REMOVAL                                     |              | SETTLING TANK                     |                        | COMPLETE MIX ACTIVATED SLUDGE / SECONDARY CLARIFIER                          |                                | HYPOCHLORITE-CONTACT TANK                  | ULTRASONIC                                      | AEROBIC SLUDGE DIGESTION DIFFUSED AERATI | GRAVITY           | BELT FILTER PRESS | POLYMER                  |                                                   |                       | LANDSPREADING / LANDFILL                          |                 |                                                                                       | 
| MARCELLUS (V) WATER POLLUTION CONTRL PLT | MARCELLUS (V) W P C P                    | ONONDAGA | NY0020532    | JOHN C HOPKINS     | (315) 673-4491 | NINE MILE CREEK     | 07             | C(T)         | 1959       | 2001         | 0.38               | 2A          | 0.00              | 2.00             | S                 |              | BAR RACK/SCREEN (1/2" TO 2" OPENINGS)                                                | GRIT CHAMBER (GRAVITY SEPARATION)                                        |              |                                   |                        | CONTACT STABILIZATION                                                        |                                | DECHLORINATION / CHLORINE GAS DISINFECTION | PARSHALL FLUME / ULTRASONIC                     | AEROBIC SLUDGE DIGESTION DIFFUSED AERATI |                   | BELT FILTER PRESS | LIME TREATMENT / POLYMER | COVERED DRYING BEDS / COVERED SAND / OPEN-ASPHALT |                       | LANDFILL / TO ANOTHER TREATMENT PLANT / SCAVENGER |                 |                                                                                       | 
| ALDEN (V)                                | ALDEN (V) WASTEWATER TREATMENT PLANT     | ERIE     | NY0020541    | ROBERT L HOLTZ     | (716) 937-4497 | ELLICOTT CREEK      | 01             | C            | 1960       | 1985         | 0.65               | 3           | 3500.00           | 3.00             | S                 |              | BAR RACK/SCREEN (MECHANICALLY CLEANED) / COARSE SCREEN-HAND CLEANED                  | GRIT CHAMBER (GRAVITY SEPARATION)                                        |              | MECHANICALLY CLEANED CLARIFIER    |                        | ROTATING BIOLOGICAL CONTACTOR                                                | RAPID SAND (HIGH RATE) FILTERS | CHLORINE GAS-CONTACT TANK / SEASONAL       | PARSHALL FLUME / ULTRASONIC                     | ANAEROBIC SLUDGE DIGESTION TWO STAGE     |                   | BELT FILTER PRESS |                          | COVERED DRYING BEDS / OPEN DRYING BED             |                       | LANDFILL                                          |                 | POST AERATION                                                                         | 
| WEEDSPORT (V)                            | WEEDSPORT (V) SEWAGE TREATMENT PLANT     | CAYUGA   | NY0020559    | JOHN D O'CONNELL   | (315) 834-6411 | COLD SPRINGS BROOK  | 07             | C            | 1966       |              | 0.3                | 2A          | 2000.00           | 2.00             | S                 |              | BAR RACK/SCREEN (1/2" TO 2" OPENINGS) / COMMINUTOR/BAR MINUTOR                       | GRIT CHAMBER (GRAVITY SEPARATION)                                        |              |                                   |                        | CONTACT STABILIZATION                                                        |                                | HYPOCHLORITE DISINFECTION                  | WEIR                                            | AEROBIC SLUDGE DIGESTION DIFFUSED AERATI |                   |                   |                          | OPEN DRYING BED                                   |                       | LANDFILL / SCAVENGER                              |                 |                                                                                       | 
| LONG BEACH (C)                           | LONG BEACH (C) WPCP                      | NASSAU   | NY0020567    | WILLIAM R NOTHOLT  | (516) 431-5691 | REYNOLDS CHANNEL    | 17             | SB           | 1951       | 2003         | 7.5                | 3           | 35000.00          | 13.00            | S                 |              | BAR RACK/SCREEN (1/2" TO 2" OPENINGS) / BAR RACK/SCREEN (MECHANICALLY CLEANED)       | GRIT CHAMBER (GRAVITY SEPARATION) / GRIT CHAMBER MECHANICAL GRIT REMOVAL |              | MECHANICALLY CLEANED CLARIFIER    |                        | HIGH RATE TRICKLING FILTER                                                   |                                | HYPOCHLORITE DISINFECTION                  | OTHER FLUME TYPES / VENTURI TUBE                | ANAEROBIC SLUDGE DIGESTION(NOT SPECIFIE) |                   |                   |                          |                                                   | COVERED STORAGE TANKS | LANDFILL                                          |                 |                                                                                       | 
| WELLSVILLE (V)                           | WELLSVILLE (V) WASTEWATER TRTMT PL       | ALLEGANY | NY0020621    | MICHAEL D SMITH    | (716) 593-4361 | GENESEE RIVER       | 04             | C(T)         | 1937       | 1997         | 2.2000000000000002 | 3           | 5200.00           | 2.50             | S                 |              | COMMINUTOR/BAR MINUTOR / FINE SCREEN (LESS THAN 1/8" OPENINGS)                       | AERATED GRIT CHAMBER                                                     |              | PLAIN CLARIFER WITH HOPPER BOTTOM |                        | SECONDARY CLARIFIER / TWO-STAGE TRICKLING FILTER                             |                                |                                            | ULTRASONIC                                      | ANAEROBIC SLUDGE DIGESTION TWO STAGE     |                   | BELT FILTER PRESS |                          | COVERED DRYING BEDS                               |                       | LANDFILL                                          |                 | PHOSPHORUS REMOVAL (CHEMICAL)                                                         | 
| SPENCERPORT (V)                          | SPENCERPORT (V) WASTEWATER TREATMNT PLNT | MONROE   | NY0020656    | MARK E ELLIOTT     | (585) 352-4773 | NORTHRUP CREEK      | 03             | C            | 1931       | 1986         | 1                  | 3A          | 4000.00           | 3.00             | S                 |              | BAR RACK/SCREEN (HAND CLEANED) / COMMINUTOR                                          | AERATED GRIT CHAMBER / GRIT CHAMBER MECHANICAL GRIT REMOVAL              |              |                                   |                        | MIXING - COARSE BUBBLE / CONVENTIONAL ACTIVATED SLUDGE / SECONDARY CLARIFIER |                                | ULTRA VIOLET                               | DOPPLER FLOWMETER / PARSHALL FLUME / ULTRASONIC |                                          | GRAVITY           |                   |                          |                                                   | OPEN STORAGE TANKS    | TO ANOTHER TREATMENT PLANT                        | AERATED LAGOONS | PHOSPHORUS REMOVAL (CHEMICAL)                                                         | 
| PHOENIX (V)                              | PHOENIX (V) SEWAGE TREATMENT PLANT       | OSWEGO   | NY0020664    | ROBERT DAVIS       | (315) 695-7202 | OSWEGO RIVER        | 07             | B            | 1964       | 1979         | 0.6                | 2A          | 2800.00           | 2.00             | S                 |              | BAR RACK/SCREEN (1/2" TO 2" OPENINGS) / COMMINUTOR/BAR MINUTOR                       | AERATED GRIT CHAMBER                                                     |              |                                   |                        | CONTACT STABILIZATION                                                        |                                | HYPOCHLORITE-SEASONAL                      | FLOWMETER - UNSPECIFIED                         | AEROBIC SLUDGE DIGESTION MECHANICAL AERA |                   |                   |                          | OPEN-ASPHALT / REED BEDS                          |                       | LANDFILL                                          |                 |                                                                                       | 
| HAMILTON (V)                             | HAMILTON (V) WATER POLLUTION CONTROL PLT | MADISON  | NY0020672    | JOHN LAWRENCE      | (315) 824-1760 | PAYNE BROOK         | 06             | C            | 1968       | 1987         | 0.85               | 3A          | 0.00              | 2.00             | S                 |              | BAR RACK/SCREEN (HAND CLEANED) / BAR RACK/SCREEN (MECHANICALLY CLEANED) / COMMINUTOR | GRIT CHAMBER (GRAVITY SEPARATION) / GRIT CLASSIFIER / CYCLONE DEGRITTER  |              |                                   |                        | EXTENDED AERATION / SECONDARY CLARIFIER                                      | RAPID SAND (HIGH RATE) FILTERS | DECHLORINATION / HYPOCHLORITE-SEASONAL     | PARSHALL FLUME                                  | AEROBIC (USING AERATION TANKS)           | GRAVITY           | BELT FILTER PRESS | POLYMER                  | COVERED ASPHALT                                   | HOLDING TANK-AERATED  | LANDFILL                                          |                 | NITROGEN REMOVAL (NOT SPECIFIED) / ONE STAGE BIOLOGICAL NITRIFICATION / POST AERATION | 
| BLASDELL (V)                             | BLASDELL (V) SEWAGE TREATMENT PLANT      | ERIE     | NY0020681    | JAMES KELLER       | (716) 823-8188 | LAKE ERIE           | 01             | A(S)         | 1950       | 1984         | 0.83               | 2           | 7000.00           | 4.50             | S                 |              | BAR RACK/SCREEN (1/2" TO 2" OPENINGS) / COMMINUTOR/BAR MINUTOR                       | GRIT CHAMBER (GRAVITY SEPARATION)                                        |              | MECHANICALLY CLEANED CLARIFIER    |                        | TWO-STAGE TRICKLING FILTER                                                   |                                | HYPOCHLORITE DISINFECTION                  | ULTRASONIC                                      | ANAEROBIC SLUDGE DIGESTION(NOT SPECIFIE) |                   |                   |                          | OPEN DRYING BED                                   |                       | LANDFILL                                          |                 |                                                                                       | 
```