# Oil, Gas, & Other Regulated Wells: Beginning 1860

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/oil-gas-other-regulated-wells-beginning-1860) |
| Metadata | [Link](https://data.ny.gov/api/views/szye-wmt3) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/szye-wmt3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/szye-wmt3/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | szye-wmt3 |
| Name | Oil, Gas, & Other Regulated Wells: Beginning 1860 |
| Attribution | New York State Department of Environmental Conservation, Division of Mineral Resources |
| Category | Energy & Environment |
| Tags | oil, gas, wells, geology, mineral resources, geothermal, stratigraphic, storage, solution salt |
| Created | 2014-09-11T21:55:25Z |
| Publication Date | 2017-04-20T10:24:11Z |

## Description

Information on oil, gas, storage, solution salt, stratigraphic, and geothermal wells in New York State

## Columns

```ls
| Included | Schema Type    | Field Name                     | Name                           | Data Type     | Render Type   |
| ======== | ============== | ============================== | ============================== | ============= | ============= |
| Yes      | series tag     | api_well_number                | API Well Number                | text          | number        |
| Yes      | series tag     | county_code                    | County Code                    | text          | number        |
| Yes      | series tag     | api_hole_number                | API Hole Number                | text          | number        |
| Yes      | numeric metric | sidetrack                      | Sidetrack                      | number        | number        |
| Yes      | numeric metric | completion                     | Completion                     | number        | number        |
| Yes      | series tag     | well_name                      | Well Name                      | text          | text          |
| Yes      | series tag     | company_name                   | Company Name                   | text          | text          |
| Yes      | series tag     | operator_number                | Operator Number                | text          | number        |
| Yes      | series tag     | well_type                      | Well Type                      | text          | text          |
| Yes      | series tag     | map_symbol                     | Map Symbol                     | text          | text          |
| Yes      | series tag     | well_status                    | Well Status                    | text          | text          |
| No       |                | status_date                    | Status Date                    | calendar_date | calendar_date |
| No       |                | permit_application_date        | Permit Application Date        | calendar_date | calendar_date |
| No       |                | permit_issued_date             | Permit Issued Date             | calendar_date | calendar_date |
| No       |                | date_spudded                   | Date Spudded                   | calendar_date | calendar_date |
| No       |                | date_of_total_depth            | Date of Total Depth            | calendar_date | calendar_date |
| No       |                | date_well_completed            | Date Well Completed            | calendar_date | calendar_date |
| No       |                | date_well_plugged              | Date Well Plugged              | calendar_date | calendar_date |
| No       |                | date_well_confidentiality_ends | Date Well Confidentiality Ends | calendar_date | calendar_date |
| Yes      | series tag     | confidentiality_code           | Confidentiality Code           | text          | text          |
| Yes      | series tag     | town                           | Town                           | text          | text          |
| Yes      | series tag     | quad                           | Quad                           | text          | text          |
| Yes      | series tag     | quad_section                   | Quad Section                   | text          | text          |
| Yes      | series tag     | producing_field                | Producing Field                | text          | text          |
| Yes      | series tag     | producing_formation            | Producing Formation            | text          | text          |
| Yes      | series tag     | financial_security             | Financial Security             | text          | text          |
| Yes      | series tag     | slant                          | Slant                          | text          | text          |
| Yes      | series tag     | county                         | County                         | text          | text          |
| Yes      | series tag     | region                         | Region                         | text          | number        |
| Yes      | series tag     | state_lease                    | State Lease                    | text          | text          |
| Yes      | numeric metric | proposed_depth_ft              | Proposed Depth, ft             | number        | number        |
| No       |                | surface_longitude              | Surface Longitude              | number        | number        |
| No       |                | surface_latitude               | Surface Latitude               | number        | number        |
| No       |                | bottom_hole_longitude          | Bottom Hole Longitude          | number        | number        |
| No       |                | bottom_hole_latitude           | Bottom Hole Latitude           | number        | number        |
| Yes      | numeric metric | true_vertical_depth_ft         | True Vertical Depth, ft        | number        | number        |
| Yes      | numeric metric | measured_depth_ft              | Measured Depth, ft             | number        | number        |
| Yes      | numeric metric | kickoff_ft                     | Kickoff, ft                    | number        | number        |
| Yes      | numeric metric | drilled_depth_ft               | Drilled Depth, ft              | number        | number        |
| Yes      | numeric metric | elevation_ft                   | Elevation, ft                  | number        | number        |
| Yes      | series tag     | original_well_type             | Original Well Type             | text          | text          |
| Yes      | numeric metric | permit_fee                     | Permit Fee                     | number        | number        |
| Yes      | series tag     | objective_formation            | Objective Formation            | text          | text          |
| Yes      | numeric metric | depth_fee                      | Depth Fee                      | number        | number        |
| Yes      | series tag     | spacing                        | Spacing                        | text          | text          |
| Yes      | numeric metric | spacing_acres                  | Spacing Acres                  | number        | number        |
| Yes      | series tag     | integration                    | Integration                    | text          | text          |
| No       |                | hearing_date                   | Hearing Date                   | calendar_date | calendar_date |
| Yes      | time           | date_last_modified             | Date Last Modified             | calendar_date | calendar_date |
| Yes      | series tag     | dec_database_link              | DEC Database Link              | url           | url           |
```

## Time Field

```ls
Value = date_last_modified
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = permit_application_date,permit_issued_date,date_spudded,date_of_total_depth,status_date,date_well_plugged,date_well_confidentiality_ends,surface_longitude,surface_latitude,bottom_hole_longitude,bottom_hole_latitude,hearing_date,date_well_completed
```

## Data Commands

```ls
series e:szye-wmt3 d:2015-10-08T00:00:00.000Z t:financial_security=False t:map_symbol=O t:state_lease=NA t:quad_section=I t:slant=Vertical t:original_well_type=NL t:api_well_number=31000171670000 t:well_status=VP t:well_name="L. Harrington #1-A" t:quad=Westfield t:confidentiality_code=Released t:company_name="Envirogas, Inc." t:county=Chautauqua t:operator_number=412 t:well_type=NL t:api_hole_number=17167 t:town=Chautauqua t:dec_database_link="http://www.dec.ny.gov/cfmx/extapps/GasOil/search/wells/index.cfm?api=31000171670000" t:county_code=0 m:sidetrack=0 m:kickoff_ft=0 m:true_vertical_depth_ft=0 m:depth_fee=-100 m:completion=0 m:permit_fee=0 m:drilled_depth_ft=0 m:measured_depth_ft=0

series e:szye-wmt3 d:2012-11-27T00:00:00.000Z t:financial_security=False t:map_symbol=O t:state_lease=NA t:slant=Vertical t:api_well_number=31000321820000 t:original_well_type=NL t:well_status=VP t:confidentiality_code=Released t:county=Statewide t:operator_number=9998 t:well_type=NL t:api_hole_number=32182 t:dec_database_link="http://www.dec.ny.gov/cfmx/extapps/GasOil/search/wells/index.cfm?api=31000321820000" t:county_code=0 m:sidetrack=0 m:kickoff_ft=0 m:true_vertical_depth_ft=0 m:depth_fee=-100 m:completion=0 m:permit_fee=0 m:drilled_depth_ft=0 m:measured_depth_ft=0

series e:szye-wmt3 d:2015-10-08T00:00:00.000Z t:financial_security=False t:map_symbol=O t:state_lease=NA t:slant=Vertical t:api_well_number=31000664470000 t:original_well_type=NL t:well_status=VP t:well_name="Enos Miller 1" t:quad=Arcade t:confidentiality_code=No t:company_name="Fault Line Oil Corporation" t:county=Wyoming t:operator_number=1070 t:well_type=NL t:api_hole_number=66447 t:town=Arcade t:dec_database_link="http://www.dec.ny.gov/cfmx/extapps/GasOil/search/wells/index.cfm?api=31000664470000" t:county_code=0 m:sidetrack=0 m:kickoff_ft=0 m:true_vertical_depth_ft=0 m:depth_fee=-100 m:completion=0 m:permit_fee=0 m:drilled_depth_ft=0 m:measured_depth_ft=0
```

## Meta Commands

```ls
metric m:sidetrack p:integer l:Sidetrack d:"Two-digit code identifying any secondary wellbore, called a sidetrack, which is drilled out of and away from the original wellbore; this code also appears as the eleventh and twelfth digits of the API number. (Note: The data does not display any preceding zeroes.)" t:dataTypeName=number

metric m:completion p:integer l:Completion d:"Two-digit code identifying the number of operations, known as completions, which have occurred in a given wellbore to allow oil/gas to enter the wellbore; this code also appears as the thirteenth and fourteenth digits of the API number. (Note: The data does not display any preceding zeroes.)" t:dataTypeName=number

metric m:proposed_depth_ft p:integer l:"Proposed Depth, ft" d:"Depth (feet) specified on permit application" t:dataTypeName=number

metric m:true_vertical_depth_ft p:integer l:"True Vertical Depth, ft" d:"Total vertical distance (feet) between the bottom hole, or lowest/deepest location of the wellbore and the surface" t:dataTypeName=number

metric m:measured_depth_ft p:integer l:"Measured Depth, ft" d:"Total measured length (feet) of the wellbore" t:dataTypeName=number

metric m:kickoff_ft p:integer l:"Kickoff, ft" d:"Depth (feet) in a vertical wellbore at which a deviated or slanted wellbore is started to allow for directional drilling" t:dataTypeName=number

metric m:drilled_depth_ft p:integer l:"Drilled Depth, ft" d:"Total measured length (feet) of the wellbore in a vertical well or the measured length (feet) of the wellbore from the kickoff point to the bottom hole, or total depth, of the wellbore" t:dataTypeName=number

metric m:elevation_ft p:integer l:"Elevation, ft" d:"Elevation (feet) above sea level at the surface location of the well" t:dataTypeName=number

metric m:permit_fee p:integer l:"Permit Fee" d:"Total dollar amount charged for a well permit, including a fee based on depth (ft.) of the wellbore and a mandatory $100 fee to be credited to the oil and gas account. Permit fees can be calculated at: http://www.dec.ny.gov/energy/1779.html" t:dataTypeName=number

metric m:depth_fee p:integer l:"Depth Fee" d:"Dollar amount charged as part of the permit fee, based on depth (ft.) of the wellbore" t:dataTypeName=number

metric m:spacing_acres p:float l:"Spacing Acres" d:"Acres comprising the spacing unit" t:dataTypeName=number

entity e:szye-wmt3 l:"Oil, Gas, & Other Regulated Wells: Beginning 1860" t:attribution="New York State Department of Environmental Conservation, Division of Mineral Resources" t:url=https://data.ny.gov/api/views/szye-wmt3

property e:szye-wmt3 t:meta.view v:id=szye-wmt3 v:category="Energy & Environment" v:attributionLink=http://www.dec.ny.gov/energy/205.html v:averageRating=0 v:name="Oil, Gas, & Other Regulated Wells: Beginning 1860" v:attribution="New York State Department of Environmental Conservation, Division of Mineral Resources"

property e:szye-wmt3 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:szye-wmt3 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| api_well_number | county_code | api_hole_number | sidetrack | completion | well_name          | company_name                | operator_number | well_type | map_symbol | well_status | status_date         | permit_application_date | permit_issued_date  | date_spudded        | date_of_total_depth | date_well_completed | date_well_plugged   | date_well_confidentiality_ends | confidentiality_code | town         | quad          | quad_section | producing_field | producing_formation | financial_security | slant    | county     | region | state_lease | proposed_depth_ft | surface_longitude   | surface_latitude   | bottom_hole_longitude | bottom_hole_latitude | true_vertical_depth_ft | measured_depth_ft | kickoff_ft | drilled_depth_ft | elevation_ft | original_well_type | permit_fee | objective_formation | depth_fee | spacing                                                    | spacing_acres | integration | hearing_date | date_last_modified  | dec_database_link                                                                           | 
| =============== | =========== | =============== | ========= | ========== | ================== | =========================== | =============== | ========= | ========== | =========== | =================== | ======================= | =================== | =================== | =================== | =================== | =================== | ============================== | ==================== | ============ | ============= | ============ | =============== | =================== | ================== | ======== | ========== | ====== | =========== | ================= | =================== | ================== | ===================== | ==================== | ====================== | ================= | ========== | ================ | ============ | ================== | ========== | =================== | ========= | ========================================================== | ============= | =========== | ============ | =================== | =========================================================================================== | 
| 31000171670000  | 0           | 17167           | 0         | 0          | L. Harrington #1-A | Envirogas, Inc.             | 412             | NL        | O          | VP          |                     |                         |                     |                     |                     |                     |                     |                                | Released             | Chautauqua   | Westfield     | I            |                 |                     | False              | Vertical | Chautauqua |        | NA          |                   |                     |                    |                       |                      | 0                      | 0                 | 0          | 0                |              | NL                 | 0          |                     | -100      |                                                            |               |             |              | 2015-10-08T00:00:00 | [http://www.dec.ny.gov/cfmx/extapps/GasOil/search/wells/index.cfm?api=31000171670000, null] | 
| 31000321820000  | 0           | 32182           | 0         | 0          |                    |                             | 9998            | NL        | O          | VP          |                     |                         |                     |                     |                     |                     |                     |                                | Released             |              |               |              |                 |                     | False              | Vertical | Statewide  |        | NA          |                   |                     |                    |                       |                      | 0                      | 0                 | 0          | 0                |              | NL                 | 0          |                     | -100      |                                                            |               |             |              | 2012-11-27T00:00:00 | [http://www.dec.ny.gov/cfmx/extapps/GasOil/search/wells/index.cfm?api=31000321820000, null] | 
| 31000664470000  | 0           | 66447           | 0         | 0          | Enos Miller 1      | Fault Line Oil Corporation  | 1070            | NL        | O          | VP          |                     |                         |                     |                     |                     |                     |                     |                                | No                   | Arcade       | Arcade        |              |                 |                     | False              | Vertical | Wyoming    |        | NA          |                   |                     |                    |                       |                      | 0                      | 0                 | 0          | 0                |              | NL                 | 0          |                     | -100      |                                                            |               |             |              | 2015-10-08T00:00:00 | [http://www.dec.ny.gov/cfmx/extapps/GasOil/search/wells/index.cfm?api=31000664470000, null] | 
| 31001010720000  | 1           | 1072            | 0         | 0          | Finch 1            | Carona Typewriter           | 9372            | NL        | O          | UN          |                     |                         |                     |                     |                     |                     |                     |                                |                      | Knox         | Durham        | C            |                 |                     | False              | Vertical | Albany     | 4      | NA          |                   | -74.126810000000006 | 42.490290000000002 | -74.126810000000006   | 42.490290000000002   | 2200                   | 2200              | 0          | 2200             | 1155         | NL                 | 0          |                     | -100      |                                                            |               |             |              | 2016-09-20T00:00:00 | [http://www.dec.ny.gov/cfmx/extapps/GasOil/search/wells/index.cfm?api=31001010720000, null] | 
| 31001010730000  | 1           | 1073            | 0         | 0          | Hilton James 1     | Belmont Quadrangle Drilling | 9034            | NL        | O          | IN          |                     |                         |                     |                     |                     |                     |                     |                                | No                   | New Scotland | Voorheesville | I            |                 |                     | False              | Vertical | Albany     | 4      | NA          | 0                 | -73.907679999999999 | 42.644799999999996 | -73.907679999999999   | 42.644799999999996   | 0                      | 0                 | 0          | 0                | 0            | NL                 | 0          |                     | -100      | Exempt from Title 5; variance needed from 6 NYCRR 533.1(a) |               |             |              | 2014-12-02T00:00:00 | [http://www.dec.ny.gov/cfmx/extapps/GasOil/search/wells/index.cfm?api=31001010730000, null] | 
| 31001210070000  | 1           | 21007           | 0         | 0          | 1                  | Turf Western Ave., Inc.     | 1903            | TH        | OP         | PA          | 2016-04-06T00:00:00 | 1998-04-24T00:00:00     | 1998-07-16T00:00:00 | 1994-09-07T00:00:00 | 1994-09-13T00:00:00 | 1994-10-27T00:00:00 | 2016-04-06T00:00:00 |                                | Released             | Guilderland  | Albany        |              |                 | NA - Geoexchange    | True               | Vertical | Albany     | 4      | NA          | 1500              | -73.835880000000003 | 42.679310000000001 | -73.835880000000003   | 42.679310000000001   | 1500                   | 1500              | 0          | 1500             | 203          | TH                 | 475        |                     | 375       |                                                            |               |             |              | 2016-05-17T00:00:00 | [http://www.dec.ny.gov/cfmx/extapps/GasOil/search/wells/index.cfm?api=31001210070000, null] | 
| 31001210080000  | 1           | 21008           | 0         | 0          | 2                  | Turf Western Ave., Inc.     | 1903            | TH        | OP         | PA          | 2016-04-06T00:00:00 | 1998-04-04T00:00:00     | 1998-07-16T00:00:00 | 1994-09-14T00:00:00 | 1994-09-21T00:00:00 | 1994-11-01T00:00:00 | 2016-04-06T00:00:00 |                                | Released             | Guilderland  | Albany        |              |                 |                     | True               | Vertical | Albany     | 4      | NA          | 1500              | -73.835989999999995 | 42.679200000000002 | -73.835989999999995   | 42.679200000000002   | 1500                   | 1500              | 0          | 1500             | 204          | TH                 | 475        |                     | 375       |                                                            |               |             |              | 2016-05-17T00:00:00 | [http://www.dec.ny.gov/cfmx/extapps/GasOil/search/wells/index.cfm?api=31001210080000, null] | 
| 31001210090000  | 1           | 21009           | 0         | 0          | 3                  | Turf Western Ave., Inc.     | 1903            | TH        | OP         | PA          | 2016-05-06T00:00:00 | 1998-04-24T00:00:00     | 1998-07-16T00:00:00 | 1994-09-21T00:00:00 | 1994-09-28T00:00:00 | 1994-11-04T00:00:00 | 2016-05-06T00:00:00 |                                | Released             | Guilderland  | Albany        |              |                 |                     | True               | Vertical | Albany     | 4      | NA          | 1500              | -73.836250000000007 | 42.679250000000003 | -73.836250000000007   | 42.679250000000003   | 1420                   | 1420              | 0          | 1420             | 204          | TH                 | 475        |                     | 375       |                                                            |               |             |              | 2016-05-17T00:00:00 | [http://www.dec.ny.gov/cfmx/extapps/GasOil/search/wells/index.cfm?api=31001210090000, null] | 
| 31001210100000  | 1           | 21010           | 0         | 0          | 4                  | Turf Western Ave., Inc.     | 1903            | TH        | OP         | PA          | 2016-04-07T00:00:00 | 1998-04-24T00:00:00     | 1998-07-16T00:00:00 | 1994-09-29T00:00:00 | 1994-10-04T00:00:00 | 1994-11-09T00:00:00 | 2016-04-07T00:00:00 |                                | Released             | Guilderland  | Albany        |              |                 |                     | True               | Vertical | Albany     | 4      | NA          | 1500              | -73.836380000000005 | 42.679310000000001 | -73.836380000000005   | 42.679310000000001   | 1500                   | 1500              | 0          | 1500             | 204          | TH                 | 475        |                     | 375       |                                                            |               |             |              | 2016-05-17T00:00:00 | [http://www.dec.ny.gov/cfmx/extapps/GasOil/search/wells/index.cfm?api=31001210100000, null] | 
| 31001210110000  | 1           | 21011           | 0         | 0          | 5                  | Turf Western Ave., Inc.     | 1903            | TH        | OP         | PA          | 2016-04-08T00:00:00 | 1998-04-24T00:00:00     | 1998-07-16T00:00:00 | 1994-10-04T00:00:00 | 1994-10-11T00:00:00 | 1994-11-14T00:00:00 | 2016-04-08T00:00:00 |                                | Released             | Guilderland  | Albany        |              |                 |                     | True               | Vertical | Albany     | 4      | NA          | 1500              | -73.836510000000004 | 42.679380000000002 | -73.836510000000004   | 42.679380000000002   | 1500                   | 1500              | 0          | 1500             | 204          | TH                 | 475        |                     | 375       |                                                            |               |             |              | 2016-05-17T00:00:00 | [http://www.dec.ny.gov/cfmx/extapps/GasOil/search/wells/index.cfm?api=31001210110000, null] | 
```