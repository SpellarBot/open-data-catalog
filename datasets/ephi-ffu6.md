# Combined Sewer Overflows (CSOs): Beginning 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/combined-sewer-overflows-csos-beginning-2013) |
| Metadata | [Link](https://data.ny.gov/api/views/ephi-ffu6) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/ephi-ffu6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/ephi-ffu6/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | ephi-ffu6 |
| Name | Combined Sewer Overflows (CSOs): Beginning 2013 |
| Attribution | New York State Department of Environmental Conservation |
| Category | Energy & Environment |
| Tags | csos, sewage, sewage pollution, water quality, wet weather |
| Created | 2015-02-27T18:58:21Z |
| Publication Date | 2016-06-08T14:43:06Z |

## Description

The dataset represents the locations of combined sewer overflow (CSOs) outfall locations in NYS. It also includes overflow detection capabilities of CSO communities and overflow frequency data within a specified timeframe.

## Columns

```ls
| Included | Schema Type    | Field Name                               | Name                                     | Data Type | Render Type |
| ======== | ============== | ======================================== | ======================================== | ========= | =========== |
| Yes      | series tag     | spdes_permit_number                      | SPDES Permit Number                      | text      | text        |
| Yes      | series tag     | outfall_number                           | Outfall Number                           | text      | text        |
| Yes      | series tag     | cso_identification_number                | CSO Identification Number                | text      | text        |
| Yes      | series tag     | facility_name                            | Facility Name                            | text      | text        |
| Yes      | series tag     | facility_owner_name                      | Facility Owner Name                      | text      | text        |
| Yes      | series tag     | receiving_waterbody_name                 | Receiving Waterbody Name                 | text      | text        |
| Yes      | numeric metric | number_of_permitted_outfalls             | Number of Permitted Outfalls             | number    | number      |
| Yes      | series tag     | discharge_activation_type                | Discharge Activation Type                | text      | text        |
| Yes      | series tag     | number_of_overflow_events                | Number of Overflow Events                | text      | text        |
| Yes      | series tag     | timeframe_of_overflow_events_information | Timeframe of Overflow Events Information | text      | text        |
| Yes      | numeric metric | data_as_of                               | Data as of                               | number    | number      |
| Yes      | series tag     | link_to_real_time_information            | Link to Real-time Information            | url       | url         |
| Yes      | numeric metric | dec_region                               | DEC Region                               | number    | number      |
| Yes      | series tag     | county                                   | County                                   | text      | text        |
| No       |                | latitude                                 | Latitude                                 | number    | number      |
| No       |                | longtitude                               | Longtitude                               | number    | number      |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = latitude,longtitude
```

## Data Commands

```ls
series e:ephi-ffu6 d:2013-01-01T00:00:00.000Z t:cso_identification_number=NY0026107-001 t:facility_name="NYCDEP - Port Richmond WPCF" t:number_of_overflow_events="Visit facility website" t:county=Richmond t:outfall_number=1 t:timeframe_of_overflow_events_information="Real-time waterbody advisory, visit website" t:facility_owner_name="NYC DEP" t:spdes_permit_number=NY0026107 t:receiving_waterbody_name="Kill Van Kull" t:discharge_activation_type=Model t:link_to_real_time_information=http://www.nyc.gov/html/dep/html/harborwater/nyc_waterbody_advisory_program.shtml m:data_as_of=2015 m:number_of_permitted_outfalls=36 m:dec_region=2

series e:ephi-ffu6 d:2013-01-01T00:00:00.000Z t:cso_identification_number=NY0026107-002 t:facility_name="NYCDEP - Port Richmond WPCF" t:number_of_overflow_events="Visit facility website" t:county=Richmond t:outfall_number=2 t:timeframe_of_overflow_events_information="Real-time waterbody advisory, visit website" t:facility_owner_name="NYC DEP" t:spdes_permit_number=NY0026107 t:receiving_waterbody_name="Kill Van Kull" t:discharge_activation_type=Model t:link_to_real_time_information=http://www.nyc.gov/html/dep/html/harborwater/nyc_waterbody_advisory_program.shtml m:data_as_of=2015 m:number_of_permitted_outfalls=36 m:dec_region=2

series e:ephi-ffu6 d:2013-01-01T00:00:00.000Z t:cso_identification_number=NY0026107-003 t:facility_name="NYCDEP - Port Richmond WPCF" t:number_of_overflow_events="Visit facility website" t:county=Richmond t:outfall_number=3 t:timeframe_of_overflow_events_information="Real-time waterbody advisory, visit website" t:facility_owner_name="NYC DEP" t:spdes_permit_number=NY0026107 t:receiving_waterbody_name="Kill Van Kull" t:discharge_activation_type=Model t:link_to_real_time_information=http://www.nyc.gov/html/dep/html/harborwater/nyc_waterbody_advisory_program.shtml m:data_as_of=2015 m:number_of_permitted_outfalls=36 m:dec_region=2
```

## Meta Commands

```ls
metric m:number_of_permitted_outfalls p:integer l:"Number of Permitted Outfalls" d:"Number of CSO outfall locations listed in the facility?s SPDES permit" t:dataTypeName=number

metric m:data_as_of p:integer l:"Data as of" d:"Calendar year for which data is applicable." t:dataTypeName=number

metric m:dec_region p:integer l:"DEC Region" d:"NYSDEC Region where the site is located: Region 1: (Long Island) Nassau and Suffolk counties; Region 2: (New York City) Brooklyn, Bronx, Manhattan, Queens and Staten Island; Region 3: (Lower Hudson Valley) Dutchess, Orange, Putnam, Rockland, Sullivan, Ulster and Westchester counties; Region 4: (Capital Region/Northern Catskills) Albany, Columbia, Delaware, Greene, Montgomery, Otsego, Rensselaer, Schenectady and Schoharie counties; Region 5: (Eastern Adirondacks/Lake Champlain) Clinton, Essex, Franklin, Fulton, Hamilton, Saratoga, Warren and Washington counties; Region 6: (Western Adirondacks/Eastern Lake Ontario) Herkimer, Jefferson, Lewis, Oneida and St. Lawrence counties; Region 7: (Central New York) Broome, Cayuga, Chenango, Cortland, Madison, Onondaga, Oswego, Tioga and Tompkins counties; Region 8: (Western Finger Lakes) Chemung, Genesee, Livingston, Monroe, Ontario, Orleans, Schuyler, Seneca, Steuben, Wayne and Yates counties; Region 9: (Western New York) Allegany, Chautauqua, Cattaraugus, Erie, Niagara and Wyoming counties" t:dataTypeName=number

entity e:ephi-ffu6 l:"Combined Sewer Overflows (CSOs): Beginning 2013" t:attribution="New York State Department of Environmental Conservation" t:url=https://data.ny.gov/api/views/ephi-ffu6

property e:ephi-ffu6 t:meta.view v:id=ephi-ffu6 v:category="Energy & Environment" v:attributionLink=http://www.dec.ny.gov/chemical/88736.html v:averageRating=0 v:name="Combined Sewer Overflows (CSOs): Beginning 2013" v:attribution="New York State Department of Environmental Conservation"

property e:ephi-ffu6 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:ephi-ffu6 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:ephi-ffu6 t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| spdes_permit_number | outfall_number | cso_identification_number | facility_name               | facility_owner_name | receiving_waterbody_name | number_of_permitted_outfalls | discharge_activation_type | number_of_overflow_events | timeframe_of_overflow_events_information    | data_as_of | link_to_real_time_information                                                             | dec_region | county   | latitude  | longtitude | 
| =================== | ============== | ========================= | =========================== | =================== | ======================== | ============================ | ========================= | ========================= | =========================================== | ========== | ========================================================================================= | ========== | ======== | ========= | ========== | 
| NY0026107           | 1              | NY0026107-001             | NYCDEP - Port Richmond WPCF | NYC DEP             | Kill Van Kull            | 36                           | Model                     | Visit facility website    | Real-time waterbody advisory, visit website | 2015       | [http://www.nyc.gov/html/dep/html/harborwater/nyc_waterbody_advisory_program.shtml, null] | 2          | Richmond | 40.641355 | -74.124855 | 
| NY0026107           | 2              | NY0026107-002             | NYCDEP - Port Richmond WPCF | NYC DEP             | Kill Van Kull            | 36                           | Model                     | Visit facility website    | Real-time waterbody advisory, visit website | 2015       | [http://www.nyc.gov/html/dep/html/harborwater/nyc_waterbody_advisory_program.shtml, null] | 2          | Richmond | 40.640039 | -74.12347  | 
| NY0026107           | 3              | NY0026107-003             | NYCDEP - Port Richmond WPCF | NYC DEP             | Kill Van Kull            | 36                           | Model                     | Visit facility website    | Real-time waterbody advisory, visit website | 2015       | [http://www.nyc.gov/html/dep/html/harborwater/nyc_waterbody_advisory_program.shtml, null] | 2          | Richmond | 40.641517 | -74.118397 | 
| NY0026107           | 4              | NY0026107-004             | NYCDEP - Port Richmond WPCF | NYC DEP             | Kill Van Kull            | 36                           | Model                     | Visit facility website    | Real-time waterbody advisory, visit website | 2015       | [http://www.nyc.gov/html/dep/html/harborwater/nyc_waterbody_advisory_program.shtml, null] | 2          | Richmond | 40.645553 | -74.108859 | 
| NY0026107           | 5              | NY0026107-005             | NYCDEP - Port Richmond WPCF | NYC DEP             | Kill Van Kull            | 36                           | Model                     | Visit facility website    | Real-time waterbody advisory, visit website | 2015       | [http://www.nyc.gov/html/dep/html/harborwater/nyc_waterbody_advisory_program.shtml, null] | 2          | Richmond | 40.645504 | -74.106785 | 
| NY0026107           | 6              | NY0026107-006             | NYCDEP - Port Richmond WPCF | NYC DEP             | Kill Van Kull            | 36                           | Model                     | Visit facility website    | Real-time waterbody advisory, visit website | 2015       | [http://www.nyc.gov/html/dep/html/harborwater/nyc_waterbody_advisory_program.shtml, null] | 2          | Richmond | 40.64536  | -74.098394 | 
| NY0026107           | 7              | NY0026107-007             | NYCDEP - Port Richmond WPCF | NYC DEP             | Kill Van Kull            | 36                           | Model                     | Visit facility website    | Real-time waterbody advisory, visit website | 2015       | [http://www.nyc.gov/html/dep/html/harborwater/nyc_waterbody_advisory_program.shtml, null] | 2          | Richmond | 40.645491 | -74.102072 | 
| NY0026107           | 8              | NY0026107-008             | NYCDEP - Port Richmond WPCF | NYC DEP             | Kill Van Kull            | 36                           | Model                     | Visit facility website    | Real-time waterbody advisory, visit website | 2015       | [http://www.nyc.gov/html/dep/html/harborwater/nyc_waterbody_advisory_program.shtml, null] | 2          | Richmond | 40.646004 | -74.093068 | 
| NY0026107           | 9              | NY0026107-009             | NYCDEP - Port Richmond WPCF | NYC DEP             | Kill Van Kull            | 36                           | Model                     | Visit facility website    | Real-time waterbody advisory, visit website | 2015       | [http://www.nyc.gov/html/dep/html/harborwater/nyc_waterbody_advisory_program.shtml, null] | 2          | Richmond | 40.647321 | -74.089374 | 
| NY0026107           | 10             | NY0026107-010             | NYCDEP - Port Richmond WPCF | NYC DEP             | Upper New York Bay       | 36                           | Model                     | Visit facility website    | Real-time waterbody advisory, visit website | 2015       | [http://www.nyc.gov/html/dep/html/harborwater/nyc_waterbody_advisory_program.shtml, null] | 2          | Richmond | 40.648648 | -74.084232 | 
```