# Affordable Housing Pipeline

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/affordable-housing-pipeline) |
| Metadata | [Link](https://data.sfgov.org/api/views/aaxw-2cb8) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/aaxw-2cb8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/aaxw-2cb8/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | aaxw-2cb8 |
| Name | Affordable Housing Pipeline |
| Attribution | Mayor's Office of Housing and Community Development |
| Category | Housing and Buildings |
| Tags | mohcd, ocii, affordable housing, pipeline |
| Created | 2016-07-21T21:14:15Z |
| Publication Date | 2017-04-03T22:33:20Z |

## Description

Snapshot of the Mayor?s Office of Housing and Community Development (MOHCD) and the Office of Community Investment and Infrastructure (OCII) affordable housing pipeline projects. The projects listed are in the process of development--or are anticipated to be developed--in partnership with non-profit or for-profit developers and financed through city funding agreements, ground leases, disposition and participation agreements and conduit bond financing. The Affordable Housing Pipeline also includes housing units produced by private developers through the Inclusionary Affordable Housing Program. Data reflects all projects as of FY2016-17.

## Columns

```ls
| Included | Schema Type    | Field Name                               | Name                                     | Data Type     | Render Type   |
| ======== | ============== | ======================================== | ======================================== | ============= | ============= |
| Yes      | series tag     | project_id                               | Project ID                               | text          | text          |
| Yes      | series tag     | project_status                           | Project Status                           | text          | text          |
| Yes      | series tag     | project_name                             | Project Name                             | text          | text          |
| Yes      | series tag     | street_number                            | Street Number                            | text          | text          |
| Yes      | series tag     | street_name                              | Street Name                              | text          | text          |
| Yes      | series tag     | street_type                              | Street Type                              | text          | text          |
| Yes      | series tag     | zip_code                                 | Zip Code                                 | text          | text          |
| No       |                | planning_address                         | Planning Address                         | text          | text          |
| Yes      | series tag     | apn_s                                    | APN(s)                                   | text          | text          |
| Yes      | series tag     | supervisor_district                      | Supervisor District                      | text          | text          |
| Yes      | series tag     | planning_neighborhood                    | Planning Neighborhood                    | text          | text          |
| Yes      | series tag     | city_analysis_neighborhood               | City Analysis Neighborhood               | text          | text          |
| Yes      | series tag     | lead_agency                              | Lead Agency                              | text          | text          |
| Yes      | series tag     | program_area                             | Program Area                             | text          | text          |
| Yes      | series tag     | project_area                             | Project Area                             | text          | text          |
| Yes      | series tag     | project_type                             | Project Type                             | text          | text          |
| Yes      | series tag     | housing_tenure                           | Housing Tenure                           | text          | text          |
| No       |                | issuance_of_notice_to_proceed            | Issuance of Notice to Proceed            | calendar_date | calendar_date |
| No       |                | issuance_of_building_permit              | Issuance of Building Permit              | date          | date          |
| No       |                | issuance_of_first_construction_document  | Issuance of First Construction Document  | calendar_date | calendar_date |
| Yes      | time           | estimated_actual_construction_start_date | Estimated/Actual Construction Start Date | calendar_date | calendar_date |
| No       |                | estimated_construction_completion        | Estimated Construction Completion        | calendar_date | calendar_date |
| Yes      | series tag     | project_lead_sponsor                     | Project Lead Sponsor                     | text          | text          |
| Yes      | series tag     | project_co_sponsor                       | Project Co-Sponsor                       | text          | text          |
| Yes      | series tag     | project_owner                            | Project Owner                            | text          | text          |
| Yes      | series tag     | dbi_permit_number                        | DBI Permit Number                        | text          | text          |
| Yes      | series tag     | planning_case_number                     | Planning Case Number                     | text          | text          |
| Yes      | series tag     | property_informaiton_map_link            | Property Informaiton Map Link            | url           | url           |
| Yes      | series tag     | planning_entitlements                    | Planning Entitlements                    | text          | text          |
| No       |                | entitlement_approval                     | Entitlement Approval                     | calendar_date | calendar_date |
| Yes      | series tag     | section_415_declaration                  | Section 415 Declaration                  | text          | text          |
| Yes      | series tag     | recording_number                         | Recording Number                         | text          | text          |
| No       |                | recording_date                           | Recording Date                           | calendar_date | calendar_date |
| Yes      | numeric metric | project_units                            | Project Units                            | number        | number        |
| Yes      | numeric metric | affordable_units                         | Affordable Units                         | number        | number        |
| Yes      | numeric metric | market_rate_units                        | Market Rate Units                        | number        | number        |
| Yes      | numeric metric | affordable                               | % Affordable                             | percent       | percent       |
| Yes      | numeric metric | sro_units                                | SRO Units                                | number        | number        |
| Yes      | numeric metric | studio_units                             | Studio Units                             | number        | number        |
| Yes      | numeric metric | 1bd_units                                | 1bd Units                                | number        | number        |
| Yes      | numeric metric | 2bd_units                                | 2bd Units                                | number        | number        |
| Yes      | numeric metric | 3bd_units                                | 3bd Units                                | number        | number        |
| Yes      | numeric metric | 4bd_units                                | 4bd Units                                | number        | number        |
| Yes      | numeric metric | 5_bd_units                               | 5+ bd Units                              | number        | number        |
| Yes      | numeric metric | mobility_units                           | Mobility Units                           | number        | number        |
| Yes      | numeric metric | manager_units                            | Manager Units                            | number        | number        |
| Yes      | series tag     | manager_unit_s_type                      | Manager Unit(s) Type                     | text          | text          |
| Yes      | numeric metric | family_units                             | Family Units                             | number        | number        |
| Yes      | numeric metric | senior_units                             | Senior Units                             | number        | number        |
| Yes      | numeric metric | tay_units                                | TAY Units                                | number        | number        |
| Yes      | numeric metric | homeless_units                           | Homeless Units                           | number        | number        |
| Yes      | numeric metric | disabled_units                           | Disabled Units                           | number        | number        |
| Yes      | numeric metric | 20_ami                                   | 20% AMI                                  | number        | number        |
| Yes      | numeric metric | 30_ami                                   | 30% AMI                                  | number        | number        |
| Yes      | numeric metric | 50_ami                                   | 50% AMI                                  | number        | number        |
| Yes      | numeric metric | 55_ami                                   | 55% AMI                                  | number        | number        |
| Yes      | numeric metric | 60_ami                                   | 60% AMI                                  | number        | number        |
| Yes      | numeric metric | 80_ami                                   | 80% AMI                                  | number        | number        |
| Yes      | numeric metric | 90_ami                                   | 90% AMI                                  | number        | number        |
| Yes      | numeric metric | 100_ami                                  | 100% AMI                                 | number        | number        |
| Yes      | numeric metric | 120_ami                                  | 120% AMI                                 | number        | number        |
| Yes      | numeric metric | 150_ami                                  | 150% AMI                                 | number        | number        |
| No       |                | latitude                                 | Latitude                                 | number        | number        |
| No       |                | longitude                                | Longitude                                | number        | number        |
```

## Time Field

```ls
Value = estimated_actual_construction_start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = planning_address,issuance_of_building_permit,issuance_of_first_construction_document,issuance_of_notice_to_proceed,estimated_construction_completion,entitlement_approval,recording_date,latitude,longitude
```

## Data Commands

```ls
series e:aaxw-2cb8 d:2016-09-01T00:00:00.000Z t:housing_tenure=Rental t:planning_case_number=2014.0103 t:project_name="1036 Mission" t:project_status="(5) First Construction Document Issued" t:city_analysis_neighborhood="South of Market" t:zip_code=94103 t:lead_agency=MOHCD t:program_area=Multifamily t:manager_unit_s_type=1bd t:street_name=Mission t:project_lead_sponsor="Tenderloin Neighborhood Development Corporation" t:project_type="New Construction" t:planning_neighborhood="South of Market" t:planning_entitlements=2014.0103C,2014.0103V,2014.0103X t:supervisor_district=6 t:apn_s=3703162 t:project_id=2006-001 t:project_owner="1036 Mission Associates, LP" t:street_number=1036 t:dbi_permit_number=201406269523 t:property_informaiton_map_link="http://propertymap.sfplanning.org/?search=2014.0103" t:street_type=St m:homeless_units=40 m:30_ami=20 m:senior_units=0 m:80_ami=0 m:project_units=83 m:100_ami=0 m:mobility_units=0 m:50_ami=42 m:studio_units=0 m:sro_units=0 m:5_bd_units=0 m:tay_units=0 m:60_ami=0 m:family_units=42 m:55_ami=0 m:3bd_units=7 m:affordable=99 m:2bd_units=38 m:90_ami=0 m:market_rate_units=1 m:manager_units=1 m:affordable_units=82 m:4bd_units=0 m:120_ami=0 m:150_ami=0 m:1bd_units=37 m:disabled_units=0 m:20_ami=20

series e:aaxw-2cb8 d:2017-04-03T22:32:15.000Z t:housing_tenure=Rental t:planning_case_number=2014.0563 t:project_status="(2) Predevelopment Feasibility" t:project_name="Midtown Park Apartments" t:city_analysis_neighborhood="Western Addition" t:zip_code=94115 t:lead_agency=MOHCD t:program_area=Multifamily t:street_name=Scott t:project_lead_sponsor="Mercy Housing California" t:project_type=Rehabilitation t:planning_neighborhood="Western Addition" t:planning_entitlements=2014.0563R t:supervisor_district=5 t:apn_s=1099031 t:project_id=2006-002 t:project_owner="Entity to be formed" t:street_number=1415 t:property_informaiton_map_link="http://propertymap.sfplanning.org/?search=2014.0563" t:street_type=St m:homeless_units=0 m:30_ami=0 m:senior_units=0 m:80_ami=0 m:project_units=0 m:100_ami=0 m:mobility_units=0 m:50_ami=0 m:studio_units=0 m:sro_units=0 m:5_bd_units=0 m:tay_units=0 m:60_ami=0 m:family_units=0 m:55_ami=0 m:3bd_units=0 m:2bd_units=0 m:90_ami=0 m:manager_units=0 m:market_rate_units=0 m:affordable_units=0 m:4bd_units=0 m:120_ami=0 m:150_ami=0 m:1bd_units=0 m:disabled_units=0 m:20_ami=0

series e:aaxw-2cb8 d:2014-04-23T00:00:00.000Z t:housing_tenure=Unknown t:planning_case_number=2004.0552 t:project_name="340 Fremont" t:project_status="(6) Complete" t:city_analysis_neighborhood="Financial District/South Beach" t:zip_code=94105 t:lead_agency=MOHCD t:program_area=Inclusionary t:street_name=Fremont t:project_lead_sponsor="Jackson Pacific Ventures/Archstone Smith" t:project_type="New Construction" t:planning_neighborhood="South of Market" t:planning_entitlements=2004.0552E,2004.0552K,2004.0552V,2004.0552X t:supervisor_district=6 t:apn_s=3748006 t:project_id=2006-003 t:street_number=340-350 t:section_415_declaration="Fee Payment" t:dbi_permit_number=201208036505 t:property_informaiton_map_link="http://propertymap.sfplanning.org/?search=2004.0552" t:street_type=St m:homeless_units=0 m:30_ami=0 m:senior_units=0 m:80_ami=0 m:project_units=348 m:100_ami=0 m:mobility_units=0 m:50_ami=0 m:studio_units=0 m:sro_units=0 m:5_bd_units=0 m:tay_units=0 m:60_ami=0 m:family_units=0 m:55_ami=0 m:3bd_units=0 m:affordable=0 m:2bd_units=0 m:90_ami=0 m:market_rate_units=348 m:manager_units=0 m:affordable_units=0 m:4bd_units=0 m:120_ami=0 m:150_ami=0 m:1bd_units=0 m:disabled_units=0 m:20_ami=0
```

## Meta Commands

```ls
metric m:project_units p:integer l:"Project Units" t:dataTypeName=number

metric m:affordable_units p:integer l:"Affordable Units" t:dataTypeName=number

metric m:market_rate_units p:integer l:"Market Rate Units" t:dataTypeName=number

metric m:affordable p:integer l:"% Affordable" t:dataTypeName=percent

metric m:sro_units p:integer l:"SRO Units" t:dataTypeName=number

metric m:studio_units p:integer l:"Studio Units" t:dataTypeName=number

metric m:1bd_units p:integer l:"1bd Units" t:dataTypeName=number

metric m:2bd_units p:integer l:"2bd Units" t:dataTypeName=number

metric m:3bd_units p:integer l:"3bd Units" t:dataTypeName=number

metric m:4bd_units p:integer l:"4bd Units" t:dataTypeName=number

metric m:5_bd_units p:integer l:"5+ bd Units" t:dataTypeName=number

metric m:mobility_units p:integer l:"Mobility Units" t:dataTypeName=number

metric m:manager_units p:integer l:"Manager Units" t:dataTypeName=number

metric m:family_units p:integer l:"Family Units" t:dataTypeName=number

metric m:senior_units p:integer l:"Senior Units" t:dataTypeName=number

metric m:tay_units p:integer l:"TAY Units" t:dataTypeName=number

metric m:homeless_units p:integer l:"Homeless Units" t:dataTypeName=number

metric m:disabled_units p:integer l:"Disabled Units" t:dataTypeName=number

metric m:20_ami p:integer l:"20% AMI" t:dataTypeName=number

metric m:30_ami p:integer l:"30% AMI" t:dataTypeName=number

metric m:50_ami p:integer l:"50% AMI" t:dataTypeName=number

metric m:55_ami p:integer l:"55% AMI" t:dataTypeName=number

metric m:60_ami p:integer l:"60% AMI" t:dataTypeName=number

metric m:80_ami p:integer l:"80% AMI" t:dataTypeName=number

metric m:90_ami p:integer l:"90% AMI" t:dataTypeName=number

metric m:100_ami p:integer l:"100% AMI" t:dataTypeName=number

metric m:120_ami p:integer l:"120% AMI" t:dataTypeName=number

metric m:150_ami p:integer l:"150% AMI" t:dataTypeName=number

entity e:aaxw-2cb8 l:"Affordable Housing Pipeline" t:attribution="Mayor's Office of Housing and Community Development" t:url=https://data.sfgov.org/api/views/aaxw-2cb8

property e:aaxw-2cb8 t:meta.view v:id=aaxw-2cb8 v:category="Housing and Buildings" v:attributionLink=http://sfmohcd.org/ v:averageRating=0 v:name="Affordable Housing Pipeline" v:attribution="Mayor's Office of Housing and Community Development"

property e:aaxw-2cb8 t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:aaxw-2cb8 t:meta.view.owner v:id=9wvp-x5mw v:screenName="Charlie MacNulty" v:displayName="Charlie MacNulty"

property e:aaxw-2cb8 t:meta.view.tableauthor v:id=9wvp-x5mw v:screenName="Charlie MacNulty" v:roleName=editor v:displayName="Charlie MacNulty"
```

## Top Records

```ls
| project_id | project_status                         | project_name                                    | street_number | street_name | street_type | zip_code | planning_address                                     | apn_s   | supervisor_district | planning_neighborhood | city_analysis_neighborhood     | lead_agency | program_area | project_area | project_type     | housing_tenure | issuance_of_notice_to_proceed | issuance_of_building_permit | issuance_of_first_construction_document | estimated_actual_construction_start_date | estimated_construction_completion | project_lead_sponsor                            | project_co_sponsor | project_owner                   | dbi_permit_number          | planning_case_number | property_informaiton_map_link                                    | planning_entitlements                                                                              | entitlement_approval | section_415_declaration | recording_number    | recording_date      | project_units | affordable_units | market_rate_units | affordable | sro_units | studio_units | 1bd_units | 2bd_units | 3bd_units | 4bd_units | 5_bd_units | mobility_units | manager_units | manager_unit_s_type | family_units | senior_units | tay_units | homeless_units | disabled_units | 20_ami | 30_ami | 50_ami | 55_ami | 60_ami | 80_ami | 90_ami | 100_ami | 120_ami | 150_ami | latitude           | longitude           | 
| ========== | ====================================== | =============================================== | ============= | =========== | =========== | ======== | ==================================================== | ======= | =================== | ===================== | ============================== | =========== | ============ | ============ | ================ | ============== | ============================= | =========================== | ======================================= | ======================================== | ================================= | =============================================== | ================== | =============================== | ========================== | ==================== | ================================================================ | ================================================================================================== | ==================== | ======================= | =================== | =================== | ============= | ================ | ================= | ========== | ========= | ============ | ========= | ========= | ========= | ========= | ========== | ============== | ============= | =================== | ============ | ============ | ========= | ============== | ============== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ======= | ======= | ======= | ================== | =================== | 
| 2006-001   | (5) First Construction Document Issued | 1036 Mission                                    | 1036          | Mission     | St          | 94103    | 1036 MISSION ST 94103                                | 3703162 | 6                   | South of Market       | South of Market                | MOHCD       | Multifamily  |              | New Construction | Rental         | 2016-09-01T00:00:00           | 1441929600                  |                                         | 2016-09-01T00:00:00                      | 2018-09-01T00:00:00               | Tenderloin Neighborhood Development Corporation |                    | 1036 Mission Associates, LP     | 201406269523               | 2014.0103            | [http://propertymap.sfplanning.org/?search=2014.0103, null]      | 2014.0103C,2014.0103V,2014.0103X                                                                   | 2014-04-24T00:00:00  |                         |                     |                     | 83            | 82               | 1                 | 99         | 0         | 0            | 37        | 38        | 7         | 0         | 0          | 0              | 1             | 1bd                 | 42           | 0            | 0         | 40             | 0              | 20     | 20     | 42     | 0      | 0      | 0      | 0      | 0       | 0       | 0       | 37.780539016580903 | -122.40984379460799 | 
| 2006-002   | (2) Predevelopment Feasibility         | Midtown Park Apartments                         | 1415          | Scott       | St          | 94115    | 2040 OFARRELL ST, SAN FRANCISCO, CA                  | 1099031 | 5                   | Western Addition      | Western Addition               | MOHCD       | Multifamily  |              | Rehabilitation   | Rental         |                               |                             |                                         |                                          |                                   | Mercy Housing California                        |                    | Entity to be formed             |                            | 2014.0563            | [http://propertymap.sfplanning.org/?search=2014.0563, null]      | 2014.0563R                                                                                         |                      |                         |                     |                     | 0             | 0                | 0                 |            | 0         | 0            | 0         | 0         | 0         | 0         | 0          | 0              | 0             |                     | 0            | 0            | 0         | 0              | 0              | 0      | 0      | 0      | 0      | 0      | 0      | 0      | 0       | 0       | 0       | 37.783005259108499 | -122.43849957786099 | 
| 2006-003   | (6) Complete                           | 340 Fremont                                     | 340-350       | Fremont     | St          | 94105    | 340 FREMONT ST, SAN FRANCISCO, CA 94105              | 3748006 | 6                   | South of Market       | Financial District/South Beach | MOHCD       | Inclusionary |              | New Construction | Unknown        |                               |                             | 2014-04-23T00:00:00                     | 2014-04-23T00:00:00                      | 2017-03-13T00:00:00               | Jackson Pacific Ventures/Archstone Smith        |                    |                                 | 201208036505               | 2004.0552            | [http://propertymap.sfplanning.org/?search=2004.0552, null]      | 2004.0552E,2004.0552K,2004.0552V,2004.0552X                                                        | 2006-06-08T00:00:00  | Fee Payment             |                     |                     | 348           | 0                | 348               | 0          | 0         | 0            | 0         | 0         | 0         | 0         | 0          | 0              | 0             |                     | 0            | 0            | 0         | 0              | 0              | 0      | 0      | 0      | 0      | 0      | 0      | 0      | 0       | 0       | 0       | 37.787066809146303 | -122.392976800458   | 
| 2006-004   | (6) Complete                           | 399 Fremont                                     | 355-399       | Fremont     | St          | 94105    | 355 SITUS TO BE ASSIGNED ST, SAN FRANCISCO, CA 94105 | 3747320 | 6                   | South of Market       | Financial District/South Beach | MOHCD       | Inclusionary |              | New Construction | Unknown        |                               | 1371168000                  | 2014-02-10T00:00:00                     | 2014-02-10T00:00:00                      | 2017-02-10T00:00:00               | OMD/UDR, LLC                                    |                    |                                 | 200605161774               | 2006.0358            | [http://propertymap.sfplanning.org/?search=2006.0358, null]      | 07-091,2006.0358E,2006.0358K,2006.0358Q,2006.0358V,2006.0358X                                      | 2006-06-15T00:00:00  | Fee Payment             |                     |                     | 452           | 0                | 452               | 0          | 0         | 0            | 0         | 0         | 0         | 0         | 0          | 0              | 0             |                     | 0            | 0            | 0         | 0              | 0              | 0      | 0      | 0      | 0      | 0      | 0      | 0      | 0       | 0       | 0       | 37.7873224327112   | -122.392223707721   | 
| 2006-005   | (4) Site Work Permit Issued            | Trinity Plaza Apartments, Phase IV              | 1167          | Market      | St          | 94103    | 1167 MARKET ST, SAN FRANCISCO, CA 94103              | 3702053 | 6                   | South of Market       | South of Market                | MOHCD       | Inclusionary |              | New Construction | Rental         |                               | 1383177600                  |                                         | 2011-08-02T00:00:00                      | 2018-08-01T00:00:00               | Trinity Properties                              |                    |                                 | 200704098308, 201012166843 | 2002.1179            | [http://propertymap.sfplanning.org/?search=2002.1179, null]      | 2002.1179C,2002.1179E,2002.1179K,2002.1179M,2002.1179Q,2002.1179T,2002.1179W,2002.1179X,2002.1179Z | 2006-08-03T00:00:00  | On-site BMR Project     |                     |                     | 493           | 74               | 419               | 15         | 0         | 0            | 0         | 0         | 0         | 0         | 0          | 0              | 0             |                     | 74           | 0            | 0         | 0              | 0              | 0      | 0      | 0      | 0      | 0      | 0      | 0      | 0       | 0       | 0       | 37.778456857897297 | -122.413427037733   | 
| 2006-006   | (5) First Construction Document Issued | Trinity Plaza Apartments, Phase III             | 33            | 8th         | St          | 94103    | 1167 MARKET ST, SAN FRANCISCO, CA 94103              | 3702053 | 6                   | South of Market       | South of Market                | MOHCD       | Inclusionary |              | New Construction | Rental         |                               | 1383177600                  | 2014-04-07T00:00:00                     | 2014-04-07T00:00:00                      | 2017-02-22T00:00:00               | Trinity Properties                              |                    |                                 | 200704098308, 201012166843 | 2002.1179            | [http://propertymap.sfplanning.org/?search=2002.1179, null]      | 2002.1179C,2002.1179E,2002.1179K,2002.1179M,2002.1179Q,2002.1179T,2002.1179W,2002.1179X,2002.1179Z | 2006-08-03T00:00:00  | On-site BMR Project     | 2016-K338024        | 2016-10-04T00:00:00 | 540           | 82               | 458               | 15         | 0         | 0            | 0         | 0         | 0         | 0         | 0          | 0              | 0             |                     | 82           | 0            | 0         | 0              | 0              | 0      | 0      | 0      | 82     | 0      | 0      | 0      | 0       | 0       | 0       | 37.778456857897297 | -122.413427037733   | 
| 2007-003   | (3) Design with Entitlements Approved  | Eddy & Taylor                                   | 238           | Taylor      | St          | 94102    | 210 TAYLOR ST 94102                                  | 0331010 | 6                   | Downtown/Civic Center | Tenderloin                     | MOHCD       | Multifamily  |              | New Construction | Rental         | 2017-04-01T00:00:00           |                             |                                         | 2017-04-01T00:00:00                      | 2018-10-01T00:00:00               | Tenderloin Neighborhood Development Corporation |                    | Eddy & Taylor Associates, LP    | 201602179822               | 2015-001077PRJ       | [http://propertymap.sfplanning.org/?search=2015-001077PRJ, null] | 2015-001077CUA                                                                                     |                      |                         |                     |                     | 113           | 112              | 1                 | 99         | 0         | 16           | 14        | 67        | 15        | 0         | 0          | 0              | 1             | 2bd                 | 82           | 0            | 0         | 30             | 0              | 0      | 0      | 112    | 0      | 0      | 0      | 0      | 0       | 0       | 0       | 37.784486516240499 | -122.410661522927   | 
| 2007-005   | (5) First Construction Document Issued | Willie B Kennedy Senior Housing (Rosa Parks II) | 1239          | Turk        | St          | 94115    | 1251 TURK ST, SAN FRANCISCO, CA 94115                | 0757027 | 5                   | Western Addition      | Western Addition               | MOHCD       | Multifamily  |              | New Construction | Rental         | 2014-09-15T00:00:00           |                             |                                         | 2014-09-15T00:00:00                      | 2016-07-31T00:00:00               | Tenderloin Neighborhood Development Corporation |                    | Rosa Parks II, LP               |                            | 2014.0888            | [http://propertymap.sfplanning.org/?search=2014.0888, null]      | 2014.0888C                                                                                         | 2014-07-17T00:00:00  |                         |                     |                     | 98            | 97               | 1                 | 99         | 0         | 32           | 65        | 0         | 0         | 0         | 0          | 0              | 1             | 2bd                 | 0            | 77           | 0         | 20             | 0              | 0      | 0      | 97     | 0      | 0      | 0      | 0      | 0       | 0       | 0       | 37.780628507173603 | -122.429579272056   | 
| 2008-001   | (5) First Construction Document Issued | Bill Sorro Community (Hugo/200 6th)             | 1009          | Howard      | St          | 94103    | 200 06TH ST, SAN FRANCISCO, CA 94103                 | 3731001 | 6                   | South of Market       | South of Market                | MOHCD       | Multifamily  |              | New Construction | Rental         | 2014-12-16T00:00:00           | 1391040000                  |                                         | 2014-12-16T00:00:00                      | 2016-12-01T00:00:00               | Mercy Housing California                        |                    | Mercy Housing California 51, LP | 201211295086, 201211295087 | 2011.0119            | [http://propertymap.sfplanning.org/?search=2011.0119, null]      | 2011.0119C,2011.0119E,2011.0119E_3,2011.0119K,2011.0119R,2011.0119V                                | 2013-08-01T00:00:00  |                         | DOC-2014-J993319-00 | 2014-12-16T00:00:00 | 67            | 66               | 1                 | 99         | 0         | 8            | 24        | 24        | 10        | 0         | 0          | 0              | 1             | 2bd                 | 52           | 0            | 0         | 0              | 14             | 0      | 0      | 66     | 0      | 0      | 0      | 0      | 0       | 0       | 0       | 37.779379389921502 | -122.407101573117   | 
| 2008-004   | (5) First Construction Document Issued | 5050 Mission                                    | 5050          | Mission     | St          | 94112    | 5050 MISSION ST, SAN FRANCISCO, CA 94112             | 6969001 | 11                  | Outer Mission         | Outer Mission                  | MOHCD       | Inclusionary |              | New Construction | Ownership      | 2016-06-24T00:00:00           | 1454630400                  | 2016-06-24T00:00:00                     | 2016-06-24T00:00:00                      | 2017-12-16T00:00:00               | John Sanger                                     |                    |                                 |                            | 2006.1213            | [http://propertymap.sfplanning.org/?search=2006.1213, null]      | 2006.1213C,2006.1213E,2006.1213E_3,2006.1213E_5,2006.1213K                                         | 2008-08-14T00:00:00  | On-site BMR Project     | 2015-K132351        | 2015-09-15T00:00:00 | 61            | 9                | 52                | 15         | 0         | 0            | 0         | 0         | 0         | 0         | 0          | 0              | 0             |                     | 9            | 0            | 0         | 0              | 0              | 0      | 0      | 0      | 0      | 0      | 0      | 9      | 0       | 0       | 0       | 37.717796590887303 | -122.44066630175    | 
```