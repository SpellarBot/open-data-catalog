# Micro-Market Recovery Program - Violations and Inspections

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/micro-market-recovery-program-violations-and-inspections-89dbf) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/ujwc-724r) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/ujwc-724r/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/ujwc-724r/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | ujwc-724r |
| Name | Micro-Market Recovery Program - Violations and Inspections |
| Attribution | City of Chicago |
| Category | Community & Economic Development |
| Tags | buildings, inspections |
| Created | 2013-06-21T17:38:59Z |
| Publication Date | 2014-01-28T17:57:22Z |

## Description

The City of Chicago launched the Micro-Market Recovery Program (MMRP), a coordinated effort among the City, not-for-profit intermediaries, and non-profit and for-profit capital sources to improve conditions, strengthen property values, and create environments supportive of private investment in targeted markets throughout the city. The goal of MMRP is to improve conditions, strengthen property values, and create environments supportive of private investment in targeted areas by strategically deploying public and private capital and other tools and resources in well-defined micro-markets.  This MMRP Violations and Inspections dataset contains Department of Buildings (DOB) Violations and associated Inspections that have occured at properties falling within an MMRP Zone.  Permits, Cases and Violations can be linked to the MMRP Geographies dataset using ADDRKEY or ADDRGRPKEY.  To link Violations and Inspections to their Permits and Cases use Violation PERMITORCASEKEY and link to Permits APKEY_PERMIT and Cases APKEY_CASE.  *Note: Inspections are included only when at least one violation was written.  Inspections without violations are not included in this dataset.

## Columns

```ls
| Included | Schema Type    | Field Name                         | Name                               | Data Type     | Render Type   |
| ======== | ============== | ================================== | ================================== | ============= | ============= |
| Yes      | series tag     | template_type                      | Template Type                      | text          | text          |
| Yes      | series tag     | permit_or_case_type                | Permit or Case Type                | text          | text          |
| Yes      | series tag     | permit_or_case_description         | Permit or Case Description         | text          | text          |
| Yes      | numeric metric | permit_or_case_primary_key         | Permit or Case Primary Key         | number        | number        |
| Yes      | series tag     | inspection_number                  | Inspection Number                  | text          | number        |
| Yes      | time           | inspection_completed_date_and_time | Inspection Completed Date and Time | calendar_date | calendar_date |
| Yes      | series tag     | inspected_by                       | Inspected By                       | text          | text          |
| Yes      | series tag     | inspection_type                    | Inspection Type                    | text          | text          |
| Yes      | series tag     | partial_inspection                 | Partial Inspection                 | text          | text          |
| Yes      | series tag     | trip_number                        | Trip Number                        | text          | number        |
| Yes      | series tag     | inspection_waived                  | Inspection Waived                  | text          | text          |
| No       |                | inspection_waived_date_and_time    | Inspection Waived Date and Time    | text          | text          |
| Yes      | series tag     | inspection_status                  | Inspection Status                  | text          | text          |
| Yes      | numeric metric | violation_primary_key              | Violation Primary Key              | number        | number        |
| No       |                | modified_date_time                 | Modified Date/Time                 | calendar_date | calendar_date |
| No       |                | violation_complied_date            | Violation Complied Date            | calendar_date | calendar_date |
| Yes      | series tag     | violation_comments                 | Violation Comments                 | text          | text          |
| Yes      | series tag     | violation_code                     | Violation Code                     | text          | text          |
| Yes      | series tag     | violation_location                 | Violation Location                 | text          | text          |
| No       |                | violation_date                     | Violation Date                     | calendar_date | calendar_date |
| Yes      | series tag     | violation_additional_comments      | Violation Additional Comments      | text          | text          |
| Yes      | series tag     | violation_additional_comments2     | Violation Additional Comments2     | text          | text          |
| Yes      | series tag     | violation_sequence_number          | Violation Sequence Number          | text          | number        |
| Yes      | series tag     | violation_status                   | Violation Status                   | text          | text          |
| Yes      | series tag     | violation_description              | Violation Description              | text          | text          |
| Yes      | series tag     | violation_code_book_text           | Violation Code Book Text           | text          | text          |
| Yes      | series tag     | mmrp_zone                          | MMRP Zone                          | text          | text          |
| Yes      | series tag     | street_number                      | Street Number                      | text          | number        |
| Yes      | series tag     | pre_direction                      | Pre-Direction                      | text          | text          |
| Yes      | series tag     | street_name                        | Street Name                        | text          | text          |
| Yes      | series tag     | suffix                             | Suffix                             | text          | text          |
| Yes      | numeric metric | post_direction                     | Post Direction                     | number        | number        |
| Yes      | series tag     | zip_code                           | Zip Code                           | text          | number        |
| Yes      | series tag     | community_area                     | Community Area                     | text          | number        |
| Yes      | series tag     | ward                               | Ward                               | text          | number        |
| Yes      | numeric metric | x_coord                            | X Coord                            | number        | number        |
| Yes      | numeric metric | y_coord                            | Y Coord                            | number        | number        |
| No       |                | latitude                           | Latitude                           | number        | number        |
| No       |                | longitude                          | Longitude                          | number        | number        |
| Yes      | series tag     | central_business_district          | Central Business District          | text          | text          |
| No       |                | address_key                        | Address Key                        | number        | number        |
| No       |                | address_grouping_key               | Address Grouping Key               | number        | number        |
```

## Time Field

```ls
Value = inspection_completed_date_and_time
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = inspection_waived_date_and_time,modified_date_time,violation_complied_date,violation_date,latitude,longitude,address_key,address_grouping_key
```

## Data Commands

```ls
series e:ujwc-724r d:2014-10-28T09:58:00.000Z t:zip_code=60637 t:partial_inspection=Y t:inspected_by=BL00836 t:street_name="COTTAGE GROVE" t:inspection_type=PL_PERMIT t:trip_number=1 t:template_type=BLDG t:suffix=AVE t:permit_or_case_description="PERMIT - NEW CONSTRUCTION" t:mmrp_zone="West Woodlawn" t:inspection_number=11279991 t:permit_or_case_type=BLDG_PERM t:ward=20 t:inspection_waived=N t:inspection_status=PASSED t:community_area=42 t:street_number=6100 t:pre_direction=S m:y_coord=1864705.8680384594 m:x_coord=1182574.4175713551 m:permit_or_case_primary_key=2540911

series e:ujwc-724r d:2014-10-28T12:03:57.000Z t:zip_code=60629 t:partial_inspection=N t:inspected_by=BL00812 t:violation_location="SEQ #: 004
OTHER   :    :" t:street_name=FAIRFIELD t:inspection_type=CN_COMPL t:trip_number=1 t:violation_description=OVERCROWDING t:template_type=CASE t:suffix=AVE t:permit_or_case_description="CONSERVATION COMPLAINT INVSTGN" t:mmrp_zone="Chicago Lawn" t:inspection_number=11353199 t:violation_comments="Attic five large beds without walls." t:permit_or_case_type=CN_COMPL t:ward=16 t:violation_code=CN114015 t:violation_sequence_number=4 t:inspection_waived=N t:inspection_status=FAILED t:community_area=66 t:street_number=5925 t:pre_direction=S t:violation_code_book_text="Provide 125 sq ft for each of first 2 occupants, 100 sq ft for each of next 2 occupants, and 75 sq ft for each additional occupant of family unit. (13-196-480)" m:y_coord=1865136.4641163237 m:x_coord=1159100.0989633715 m:permit_or_case_primary_key=2608338 m:violation_primary_key=4897845

series e:ujwc-724r d:2014-10-24T10:02:00.000Z t:zip_code=60643 t:partial_inspection=N t:inspected_by=BL01001 t:violation_location="SEQ #: 020" t:street_name=115TH t:inspection_type=STF t:trip_number=1 t:violation_description="LICENSED BONDED PLMBG CONTRCTR" t:template_type=CASE t:suffix=ST t:permit_or_case_description="STF COMPLAINT INVSTGN" t:mmrp_zone="West Pullman" t:inspection_number=11353081 t:violation_comments="1209 W 115TH / EMPLOY LICENSED AND BONDED PLUMBER TO PERFORM PLUMBING WORK" t:permit_or_case_type=STF_COMPL t:ward=34 t:violation_code=PL171027 t:violation_sequence_number=20 t:inspection_waived=N t:inspection_status=FAILED t:community_area=53 t:street_number=1201 t:pre_direction=W t:violation_code_book_text="Employ licensed and bonded plumber to perform plumbing work.  (18-29-106.1 thru 106.2)" m:y_coord=1828484.283634285 m:x_coord=1170374.6722074847 m:permit_or_case_primary_key=2608275 m:violation_primary_key=4897816
```

## Meta Commands

```ls
metric m:permit_or_case_primary_key p:integer l:"Permit or Case Primary Key" d:"Permit or Case Primary Key (use this key to link violations and inspections with Permit APKEY_PERMIT and Case APKEY_CASE datasets)" t:dataTypeName=number

metric m:violation_primary_key p:integer l:"Violation Primary Key" d:"Violation Primary Key" t:dataTypeName=number

metric m:post_direction p:long l:"Post Direction" d:"Address Post Direction" t:dataTypeName=number

metric m:x_coord p:double l:"X Coord" d:"X Coord - State Plane Eastern IL 1983" t:dataTypeName=number

metric m:y_coord p:double l:"Y Coord" d:"Y Coord - State Plane Eastern IL 1983" t:dataTypeName=number

entity e:ujwc-724r l:"Micro-Market Recovery Program - Violations and Inspections" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/ujwc-724r

property e:ujwc-724r t:meta.view v:id=ujwc-724r v:category="Community & Economic Development" v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Micro-Market Recovery Program - Violations and Inspections" v:attribution="City of Chicago"

property e:ujwc-724r t:meta.view.owner v:id=vewm-vupz v:screenName="Jonathan Levy" v:displayName="Jonathan Levy"

property e:ujwc-724r t:meta.view.tableauthor v:id=vewm-vupz v:screenName="Jonathan Levy" v:roleName=administrator v:displayName="Jonathan Levy"
```

## Top Records

```ls
| template_type | permit_or_case_type | permit_or_case_description     | permit_or_case_primary_key | inspection_number | inspection_completed_date_and_time | inspected_by | inspection_type | partial_inspection | trip_number | inspection_waived | inspection_waived_date_and_time | inspection_status | violation_primary_key | modified_date_time  | violation_complied_date | violation_comments                                                                                                                             | violation_code | violation_location   | violation_date      | violation_additional_comments | violation_additional_comments2 | violation_sequence_number | violation_status | violation_description          | violation_code_book_text                                                                                                                                                                                                                                               | mmrp_zone     | street_number | pre_direction | street_name   | suffix | post_direction | zip_code | community_area | ward | x_coord            | y_coord            | latitude          | longitude          | central_business_district | address_key | address_grouping_key | 
| ============= | =================== | ============================== | ========================== | ================= | ================================== | ============ | =============== | ================== | =========== | ================= | =============================== | ================= | ===================== | =================== | ======================= | ============================================================================================================================================== | ============== | ==================== | =================== | ============================= | ============================== | ========================= | ================ | ============================== | ====================================================================================================================================================================================================================================================================== | ============= | ============= | ============= | ============= | ====== | ============== | ======== | ============== | ==== | ================== | ================== | ================= | ================== | ========================= | =========== | ==================== | 
| BLDG          | BLDG_PERM           | PERMIT - NEW CONSTRUCTION      | 2540911                    | 11279991          | 2014-10-28T09:58:00                | BL00836      | PL_PERMIT       | Y                  | 1           | N                 |                                 | PASSED            |                       |                     |                         |                                                                                                                                                |                |                      |                     |                               |                                |                           |                  |                                |                                                                                                                                                                                                                                                                        | West Woodlawn | 6100          | S             | COTTAGE GROVE | AVE    |                | 60637    | 42             | 20   | 1182574.4175713551 | 1864705.8680384594 | 41.78396436530654 | -87.60615379069809 |                           | 1237404     | 360348               | 
| CASE          | CN_COMPL            | CONSERVATION COMPLAINT INVSTGN | 2608338                    | 11353199          | 2014-10-28T12:03:57                | BL00812      | CN_COMPL        | N                  | 1           | N                 |                                 | FAILED            | 4897845               |                     |                         | Attic five large beds without walls.                                                                                                           | CN114015       | SEQ #: 004 OTHER : : | 2014-10-28T11:42:57 |                               |                                | 4                         |                  | OVERCROWDING                   | Provide 125 sq ft for each of first 2 occupants, 100 sq ft for each of next 2 occupants, and 75 sq ft for each additional occupant of family unit. (13-196-480)                                                                                                        | Chicago Lawn  | 5925          | S             | FAIRFIELD     | AVE    |                | 60629    | 66             | 16   | 1159100.0989633715 | 1865136.4641163237 | 41.78565852394959 | -87.69220779482723 |                           | 432138      | 367129               | 
| CASE          | STF_COMPL           | STF COMPLAINT INVSTGN          | 2608275                    | 11353081          | 2014-10-24T10:02:00                | BL01001      | STF             | N                  | 1           | N                 |                                 | FAILED            | 4897816               | 2014-10-29T11:12:50 |                         | 1209 W 115TH / EMPLOY LICENSED AND BONDED PLUMBER TO PERFORM PLUMBING WORK                                                                     | PL171027       | SEQ #: 020           | 2014-10-24T00:00:00 |                               |                                | 20                        |                  | LICENSED BONDED PLMBG CONTRCTR | Employ licensed and bonded plumber to perform plumbing work. (18-29-106.1 thru 106.2)                                                                                                                                                                                  | West Pullman  | 1201          | W             | 115TH         | ST     |                | 60643    | 53             | 34   | 1170374.6722074847 | 1828484.283634285  | 41.68484165414073 | -87.6519338234656  |                           | 603260      | 532944               | 
| CASE          | STF_COMPL           | STF COMPLAINT INVSTGN          | 2608275                    | 11353081          | 2014-10-24T10:02:00                | BL01001      | STF             | N                  | 1           | N                 |                                 | FAILED            | 4898073               |                     |                         | 3 FEET CLEARANCE NOT MET AT 1201 W 115TH ST AND 11509 S ELIZABETH                                                                              | EL0009         | SEQ #: 038           | 2014-10-24T00:00:00 |                               |                                | 38                        |                  | WORKING SPACE                  | Provide at least 3 ft of clear space around electrical service and distribution equipment. (18-27-110.26)                                                                                                                                                              | West Pullman  | 1201          | W             | 115TH         | ST     |                | 60643    | 53             | 34   | 1170374.6722074847 | 1828484.283634285  | 41.68484165414073 | -87.6519338234656  |                           | 603260      | 532944               | 
| CASE          | TB_COMPL            | TROUBLED BUILDINGS COMPLAINT   | 2608249                    | 11352914          | 2014-10-28T08:38:01                | BL00900      | CHECKLIST       | N                  | 1           | N                 |                                 | CLOSED            | 4897689               |                     |                         |                                                                                                                                                | CN193029       | SEQ #: 004           | 2014-10-28T08:38:00 |                               |                                | 4                         |                  | WATCHMAN                       | Maintain watchman from 4:00 PM to 8:00 AM for vacant and dangerous residential premises. (13-12-140)                                                                                                                                                                   | Humboldt Park | 3324          | W             | OHIO          | ST     |                | 60624    | 23             | 27   | 1153952.744506234  | 1903838.864649914  | 41.89196645204714 | -87.71005086436033 |                           | 77820       | 40079                | 
| CASE          | STF_COMPL           | STF COMPLAINT INVSTGN          | 2608275                    | 11353081          | 2014-10-24T10:02:00                | BL01001      | STF             | N                  | 1           | N                 |                                 | FAILED            | 4897899               |                     |                         | 1209 W 115TH ST / PROVIDE PROPER MATERIAL FOE WATER SUPPLY PIPE, FLEXABLE WATER LINES TO FIXTURES, REMOVE FLEXABLE CORRUGATED LINES AT HEATER. | PL237020       | SEQ #: 025           | 2014-10-24T00:00:00 |                               |                                | 25                        |                  | PROPER MATRL WATER SUPPLY PIPE | Provide proper material for water supply pipe. (18-29-605)                                                                                                                                                                                                             | West Pullman  | 1201          | W             | 115TH         | ST     |                | 60643    | 53             | 34   | 1170374.6722074847 | 1828484.283634285  | 41.68484165414073 | -87.6519338234656  |                           | 603260      | 532944               | 
| CASE          | STF_COMPL           | STF COMPLAINT INVSTGN          | 2608275                    | 11353081          | 2014-10-24T10:02:00                | BL01001      | STF             | N                  | 1           | N                 |                                 | FAILED            | 4898095               |                     |                         | AT 11509 S ELIZABETH                                                                                                                           | EL0083         | SEQ #: 047           | 2014-10-24T00:00:00 |                               |                                | 47                        |                  | REPAIR BATTERY LIGHT           | Repair emergency battery light unit. (18-27-700.66)                                                                                                                                                                                                                    | West Pullman  | 1201          | W             | 115TH         | ST     |                | 60643    | 53             | 34   | 1170374.6722074847 | 1828484.283634285  | 41.68484165414073 | -87.6519338234656  |                           | 603260      | 532944               | 
| CASE          | STF_COMPL           | STF COMPLAINT INVSTGN          | 2608275                    | 11353081          | 2014-10-24T10:02:00                | BL01001      | STF             | N                  | 1           | N                 |                                 | FAILED            | 4897754               |                     |                         | 11509 S ELIZABETH / SPACE BUILT-OUT WITH MULTIPLE OFFICE SUITES, NO PERMITS ON FILE                                                            | NC2011         | SEQ #: 008           | 2014-10-24T00:00:00 |                               |                                | 8                         |                  | PLANS & PERMITS REQ - CONTRCTR | Performed or allowed work to be performed without submitting plans prepared, signed and sealed by a licensed architect or registered structural engineer for approval and without obtaining a permit to perform the work. (13-32-010, 13-32-040, 13-40-020, 13-12-050) | West Pullman  | 1201          | W             | 115TH         | ST     |                | 60643    | 53             | 34   | 1170374.6722074847 | 1828484.283634285  | 41.68484165414073 | -87.6519338234656  |                           | 603260      | 532944               | 
| CASE          | STF_COMPL           | STF COMPLAINT INVSTGN          | 2608275                    | 11353081          | 2014-10-24T10:02:00                | BL01001      | STF             | N                  | 1           | N                 |                                 | FAILED            | 4898091               |                     |                         | THROUGH CEILING AREAS AND DISTRIBUTION AREAS AT 1215 W 115TH ST                                                                                | EL0030         | SEQ #: 044           | 2014-10-24T00:00:00 |                               |                                | 44                        |                  | ARMORED CABLE                  | Remove defective armored cable. (18-27-110.2, 18-27-110.3, 18-27-333.2, 18-27-333.3)                                                                                                                                                                                   | West Pullman  | 1201          | W             | 115TH         | ST     |                | 60643    | 53             | 34   | 1170374.6722074847 | 1828484.283634285  | 41.68484165414073 | -87.6519338234656  |                           | 603260      | 532944               | 
| CASE          | STF_COMPL           | STF COMPLAINT INVSTGN          | 2608275                    | 11353081          | 2014-10-24T10:02:00                | BL01001      | STF             | N                  | 1           | N                 |                                 | FAILED            | 4897977               |                     |                         | 1215 W 115TH ST / EXPOSE PLUMBING SYSTEM FOR INSPECTION AND APPROVAL, EXPOSE WATER HEATER IN CEILING                                           | PL231010       | SEQ #: 028           | 2014-10-24T00:00:00 |                               |                                | 28                        |                  | EXPOSE FOR INSPECT APPROVAL    | Expose plumbing system for inspection and approval. (18-29-312.1 thru 312.8)                                                                                                                                                                                           | West Pullman  | 1201          | W             | 115TH         | ST     |                | 60643    | 53             | 34   | 1170374.6722074847 | 1828484.283634285  | 41.68484165414073 | -87.6519338234656  |                           | 603260      | 532944               | 
```