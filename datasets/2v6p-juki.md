# Wastewater Treatment Plants

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/wastewater-treatment-plants-30303) |
| Metadata | [Link](https://data.ny.gov/api/views/2v6p-juki) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/2v6p-juki/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/2v6p-juki/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 2v6p-juki |
| Name | Wastewater Treatment Plants |
| Attribution | New York State Department of Environmental Conservation |
| Category | Energy & Environment |
| Tags | water, treatment, facility, waste, spdes |
| Created | 2014-10-31T20:25:52Z |
| Publication Date | 2016-05-31T19:45:16Z |

## Description

Data regarding wastewater treatment plants with permits issued under the New York State Pollutant Discharge Elimination System

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                          | Data Type | Render Type |
| ======== | ============== | ========================= | ============================= | ========= | =========== |
| No       | time           | :updated_at               | updated_at                    | meta_data | meta_data   |
| Yes      | series tag     | plant_type                | Plant Type                    | text      | text        |
| Yes      | series tag     | spdes_permit_number       | SPDES Permit Number           | text      | text        |
| Yes      | series tag     | facility_name             | Facility Name                 | text      | text        |
| Yes      | series tag     | ground_or_surface         | Ground or Surface             | text      | text        |
| Yes      | numeric metric | avg_design_hydraulic_flow | Average Design Hydraulic Flow | number    | number      |
| Yes      | series tag     | street                    | Street                        | text      | text        |
| Yes      | series tag     | city                      | City                          | text      | text        |
| Yes      | series tag     | state                     | State                         | text      | text        |
| Yes      | series tag     | country                   | Country                       | text      | text        |
| Yes      | series tag     | zip_code                  | Zip Code                      | text      | number      |
| No       |                | latitude                  | Latitude                      | number    | number      |
| No       |                | longitude                 | Longitude                     | number    | number      |
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
series e:2v6p-juki d:2016-05-26T12:14:40.000Z t:facility_name="RIVERHEAD SEWER DISTRICT WWTF" t:zip_code=11901 t:street="2 RIVER AVE |SCTM  600-131-3-31.1 AND 35.1" t:spdes_permit_number=NY0020061 t:state=NY t:ground_or_surface=Surface t:plant_type=Municipal t:city=RIVERHEAD t:country=USA m:avg_design_hydraulic_flow=1.3

series e:2v6p-juki d:2016-05-26T12:14:40.000Z t:facility_name="V-GREENPORT WASTEWATER TREAMENT PLANT" t:zip_code=11944 t:street="1885 MOORES LN" t:spdes_permit_number=NY0020079 t:state=NY t:ground_or_surface=Surface t:plant_type=Municipal t:city=GREENPORT t:country=USA m:avg_design_hydraulic_flow=0.655

series e:2v6p-juki d:2016-05-26T12:14:40.000Z t:facility_name="GOUVERNEUR (V) WWTF" t:zip_code=13642 t:street="ST RTE 58 - NATURAL DAM RD - S SIDE OF RD" t:spdes_permit_number=NY0020117 t:state=NY t:ground_or_surface=Surface t:plant_type=Municipal t:city=GOUVERNEUR t:country=USA m:avg_design_hydraulic_flow=3.67
```

## Meta Commands

```ls
metric m:avg_design_hydraulic_flow p:float l:"Average Design Hydraulic Flow" d:"Average volume the wastewater treatment facility is designed to treat, in millions of gallons per day (mgd)" t:dataTypeName=number

entity e:2v6p-juki l:"Wastewater Treatment Plants" t:attribution="New York State Department of Environmental Conservation" t:url=https://data.ny.gov/api/views/2v6p-juki

property e:2v6p-juki t:meta.view v:id=2v6p-juki v:category="Energy & Environment" v:attributionLink=http://www.dec.ny.gov/permits/6054.html v:averageRating=0 v:name="Wastewater Treatment Plants" v:attribution="New York State Department of Environmental Conservation"

property e:2v6p-juki t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:2v6p-juki t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:2v6p-juki t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| :updated_at | plant_type | spdes_permit_number | facility_name                         | ground_or_surface | avg_design_hydraulic_flow | street                                    | city         | state | country | zip_code | latitude | longitude | 
| =========== | ========== | =================== | ===================================== | ================= | ========================= | ========================================= | ============ | ===== | ======= | ======== | ======== | ========= | 
| 1464264880  | Municipal  | NY0020061           | RIVERHEAD SEWER DISTRICT WWTF         | Surface           | 1.3                       | 2 RIVER AVE |SCTM 600-131-3-31.1 AND 35.1 | RIVERHEAD    | NY    | USA     | 11901    | 40.92    | -72.64    | 
| 1464264880  | Municipal  | NY0020079           | V-GREENPORT WASTEWATER TREAMENT PLANT | Surface           | 0.655                     | 1885 MOORES LN                            | GREENPORT    | NY    | USA     | 11944    | 41.1     | -72.38    | 
| 1464264880  | Municipal  | NY0020117           | GOUVERNEUR (V) WWTF                   | Surface           | 3.67                      | ST RTE 58 - NATURAL DAM RD - S SIDE OF RD | GOUVERNEUR   | NY    | USA     | 13642    | 44.33    | -75.49    | 
| 1464264880  | Municipal  | NY0020125           | LOWVILLE MUNICIPAL POLL CTRL FAC      | Surface           | 1.8                       | 7514 E STATE ST                           | LOWVILLE     | NY    | USA     | 13367    | 43.78    | -75.48    | 
| 1464264880  | Municipal  | NY0020133           | SCOTTSVILLE - V STP                   | Surface           | 0.65                      | 4620 RIVER RD                             | SCOTTSVILLE  | NY    | USA     | 14546    | 43.02    | -77.75    | 
| 1464264880  | Municipal  | NY0020141           | ROTTERDAM SEWER DIST #2               | Surface           | 1.5                       | 26 W CAMPBELL AVE                         | SCHENECTADY  | NY    | USA     | 12306    | 42.8     | -73.99    | 
| 1464264880  | Municipal  | NY0020168           | OCEAN BEACH SEWAGE TREATMENT PLANT    | Surface           | 0.5                       | 94 BAY WALK                               | OCEAN BEACH  | NY    | USA     | 11770    | 40.65    | -73.15    | 
| 1464264880  | Municipal  | NY0020184           | HADLEY SEWAGE TREATMENT PLANT         | Ground            | 0.05                      | WOODWARD AVE EXT                          | HADLEY       | NY    | USA     | 12835    | 43.32    | -73.85    | 
| 1464264880  | Municipal  | NY0020222           | WESTPORT WWTP                         | Surface           | 0.18                      | 18 MARKS RD                               | WESTPORT     | NY    | USA     | 12993    | 44.19    | -73.43    | 
| 1464264880  | Municipal  | NY0020231           | SCHROON LAKE WWTP                     | Surface           | 0.35                      | 49 FOWLER AVE                             | SCHROON LAKE | NY    | USA     | 12870    | 43.84    | -73.76    | 
```