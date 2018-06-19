# Hospice Agencies

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/hospice-agencies) |
| Metadata | [Link](https://data.medicare.gov/api/views/s8t3-rfbq) |
| Data: JSON | [100 Rows](https://data.medicare.gov/api/views/s8t3-rfbq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicare.gov/api/views/s8t3-rfbq/rows.csv?max_rows=100) |
| Host | data.medicare.gov |
| Id | s8t3-rfbq |
| Name | Hospice Agencies |
| Category | Hospice Data Directory |
| Tags | hospice care, care, hospice, list |
| Created | 2016-06-13T23:29:44Z |
| Publication Date | 2017-02-22T08:04:20Z |

## Description

A list of all Hospice Agencies that have been certified by Medicare.  The list includes addresses, phone numbers, and date of original CMS certification, as well as additional demographic data for each agency.

## Columns

```ls
| Included | Schema Type | Field Name                                  | Name                                        | Data Type | Render Type |
| ======== | =========== | =========================================== | =========================================== | ========= | =========== |
| No       | time        | :updated_at                                 | updated_at                                  | meta_data | meta_data   |
| Yes      | series tag  | state_abbreviation                          | State Abbreviation                          | text      | text        |
| Yes      | series tag  | ccn                                         | CCN                                         | text      | text        |
| Yes      | series tag  | facility_name                               | Facility Name                               | text      | text        |
| Yes      | series tag  | address_street                              | Address: Street                             | text      | text        |
| No       |             | address_city                                | Address: City                               | text      | text        |
| No       |             | address_zip_code                            | Address: Zip Code                           | text      | text        |
| Yes      | series tag  | telephone_number                            | Telephone Number                            | phone     | phone       |
| Yes      | series tag  | ownership_type_description                  | Ownership Type Description                  | text      | text        |
| Yes      | series tag  | profit_status                               | Profit Status                               | text      | text        |
| Yes      | series tag  | category_specific_facility_type_description | Category-specific Facility Type Description | text      | text        |
| Yes      | series tag  | original_participation_date                 | Original Participation Date                 | html      | html        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address_city,address_zip_code
```

## Data Commands

```ls
series e:s8t3-rfbq d:2017-02-07T19:39:06.000Z t:phone_number=3343955000 t:facility_name="BAPTIST HOSPICE" t:profit_status=OTHER t:ccn=011500 t:category_specific_facility_type_description="Freestanding Hospice" t:ownership_type_description=OTHER t:original_participation_date=19840323 t:state_abbreviation=AL t:address_street="301 INTERSTATE PARK" m:row_number.s8t3-rfbq=1

series e:s8t3-rfbq d:2017-02-07T19:39:06.000Z t:phone_number=2059398799 t:facility_name="SOUTHERNCARE NEW BEACON N. BIRMINGHAM" t:profit_status="FOR PROFIT" t:ccn=011501 t:category_specific_facility_type_description="Freestanding Hospice" t:ownership_type_description="PROPRIETARY - CORPORATION" t:original_participation_date=19840524 t:state_abbreviation=AL t:address_street="4735 NORREL DRIVE, SUITE 129" m:row_number.s8t3-rfbq=2

series e:s8t3-rfbq d:2017-02-07T19:39:06.000Z t:phone_number=2514621428 t:facility_name="COMFORT CARE COASTAL HOSPICE - BALDWIN" t:profit_status=OTHER t:ccn=011502 t:category_specific_facility_type_description="Freestanding Hospice" t:ownership_type_description=OTHER t:original_participation_date=19840703 t:state_abbreviation=AL t:address_street="374 GREENO ROAD" m:row_number.s8t3-rfbq=3
```

## Meta Commands

```ls
metric m:row_number.s8t3-rfbq p:long l:"Row Number"

entity e:s8t3-rfbq l:"Hospice Agencies" t:url=https://data.medicare.gov/api/views/s8t3-rfbq

property e:s8t3-rfbq t:meta.view v:id=s8t3-rfbq v:category="Hospice Data Directory" v:averageRating=0 v:name="Hospice Agencies"

property e:s8t3-rfbq t:meta.view.owner v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:displayName=cms

property e:s8t3-rfbq t:meta.view.tableauthor v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:roleName=administrator v:displayName=cms

property e:s8t3-rfbq t:meta.view.metadata.custom_fields.common_core v:Publisher="Centers for Medicare & Medicaid Services (CMS)" v:Contact_Name=CMS v:Bureau_Code=009:38 v:Program_Code=009:078
```

## Top Records

```ls
| :updated_at | state_abbreviation | ccn    | facility_name                          | address_street                         | address_city | address_zip_code | telephone_number   | ownership_type_description     | profit_status | category_specific_facility_type_description | original_participation_date | 
| =========== | ================== | ====== | ====================================== | ====================================== | ============ | ================ | ================== | ============================== | ============= | =========================================== | =========================== | 
| 1486496346  | AL                 | 011500 | BAPTIST HOSPICE                        | 301 INTERSTATE PARK                    | MONTGOMERY   | 36109            | [3343955000, null] | OTHER                          | OTHER         | Freestanding Hospice                        | 19840323                    | 
| 1486496346  | AL                 | 011501 | SOUTHERNCARE NEW BEACON N. BIRMINGHAM  | 4735 NORREL DRIVE, SUITE 129           | TRUSSVILLE   | 35173            | [2059398799, null] | PROPRIETARY - CORPORATION      | FOR PROFIT    | Freestanding Hospice                        | 19840524                    | 
| 1486496346  | AL                 | 011502 | COMFORT CARE COASTAL HOSPICE - BALDWIN | 374 GREENO ROAD                        | FAIR HOPE    | 36532            | [2514621428, null] | OTHER                          | OTHER         | Freestanding Hospice                        | 19840703                    | 
| 1486496346  | AL                 | 011503 | SAAD HEALTHCARE                        | 1515 UNIVERSITY BOULEVARD, SOUTH       | MOBILE       | 36609            | [2513439600, null] | PROPRIETARY - CORPORATION      | FOR PROFIT    | Freestanding Hospice                        | 19860108                    | 
| 1486496346  | AL                 | 011504 | GADSDEN REGIONAL HOSPICE               | 301 SOUTH 4TH STREET                   | GADSDEN      | 35901            | [2055382273, null] | PROPRIETARY - CORPORATION      | FOR PROFIT    | Hospital                                    | 19860117                    | 
| 1486496346  | AL                 | 011505 | HOSPICE FAMILY CARE                    | 3304 WESTMILL DRIVE SOUTHWEST          | HUNTSVILLE   | 35805            | [2566501212, null] | VOLUNTARY NON-PROFIT - PRIVATE | NON-PROFIT    | Freestanding Hospice                        | 19861030                    | 
| 1486496346  | AL                 | 011506 | SOUTHERNCARE NEW BEACON - JASPER       | 300 NORTH AIRPORT ROAD, UNITS 3 AND 4  | JASPER       | 35504            | [2053879339, null] | PROPRIETARY - CORPORATION      | FOR PROFIT    | Freestanding Hospice                        | 19861119                    | 
| 1486496346  | AL                 | 011508 | SOUTHERNCARE NEW BEACON OF ANNISTON    | 1419 LEIGHTON AVENUE, UNIT A           | ANNISTON     | 36207            | [2052365334, null] | PROPRIETARY - CORPORATION      | FOR PROFIT    | Freestanding Hospice                        | 19871222                    | 
| 1486496346  | AL                 | 011510 | HOSPICE OF CULLMAN COUNTY              | 1912 ALABAMA HWY 157, POB 1, 2ND FLOOR | CULLMAN      | 35058            | [2057395185, null] | OTHER                          | OTHER         | Freestanding Hospice                        | 19880218                    | 
| 1486496346  | AL                 | 011511 | HOSPICE OF THE VALLEY, INC             | 216 JOHNSON STREET, SE P O BOX 2745    | DECATUR      | 35601            | [2053505585, null] | VOLUNTARY NON-PROFIT - PRIVATE | NON-PROFIT    | Freestanding Hospice                        | 19880303                    | 
```