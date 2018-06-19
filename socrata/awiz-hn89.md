# FAS Facilities

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fas-facilities-19977) |
| Metadata | [Link](https://data.seattle.gov/api/views/awiz-hn89) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/awiz-hn89/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/awiz-hn89/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | awiz-hn89 |
| Name | FAS Facilities |
| Attribution | FAS |
| Category | Land Base |
| Tags | fas, facilities |
| Created | 2014-08-14T20:52:16Z |
| Publication Date | 2014-08-14T21:50:37Z |

## Description

FAS Facilities

## Columns

```ls
| Included | Schema Type    | Field Name                    | Name                            | Data Type | Render Type |
| ======== | ============== | ============================= | =============================== | ========= | =========== |
| Yes      | series tag     | name                          | Facility Name                   | text      | text        |
| No       |                | physical_address              | Street Address                  | text      | text        |
| Yes      | series tag     | description                   | Description                     | text      | text        |
| Yes      | series tag     | description_1                 | Description 1                   | text      | text        |
| Yes      | series tag     | pma_number                    | PMA Number                      | text      | number      |
| Yes      | series tag     | number                        | Number                          | text      | text        |
| Yes      | series tag     | primary_use_type              | Primary Use Type                | text      | text        |
| Yes      | time           | year_built                    | Year Built                      | number    | number      |
| Yes      | numeric metric | gross_bldg_sq_ft              | Gross Bldg Sq. Ft.              | number    | number      |
| Yes      | series tag     | emergency_preparadness_zone   | Emergency Preparadness Zone     | text      | text        |
| Yes      | numeric metric | number_of_floors              | Number of Floors                | number    | number      |
| Yes      | series tag     | owner                         | Owner                           | text      | text        |
| Yes      | numeric metric | critical_facilities_index_cfi | Critical Facilities Index (CFI) | number    | number      |
| Yes      | series tag     | property_manager              | Property Manager                | text      | text        |
| Yes      | series tag     | secondary_use_type            | Secondary Use Type              | text      | text        |
| Yes      | series tag     | other_property_name_s         | Other Property Name(s)          | text      | text        |
| Yes      | series tag     | pma_other_names               | PMA Other Names                 | text      | text        |
| Yes      | series tag     | temporary_facility            | Temporary Facility              | text      | text        |
```

## Time Field

```ls
Value = year_built
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = physical_address
```

## Data Commands

```ls
series e:awiz-hn89 d:2014-01-01T00:00:00.000Z t:property_manager="Jason Phillips" t:emergency_preparadness_zone="3 - W" t:temporary_facility=No t:name="Civic Square Block" t:owner="City FFD" t:pma_number=87 t:primary_use_type="Vacant Lot" t:number=A50002 t:description_1="Future public/private partnership with construction of an office building and plaza space." m:number_of_floors=0 m:critical_facilities_index_cfi=1 m:gross_bldg_sq_ft=0

series e:awiz-hn89 d:1993-01-01T00:00:00.000Z t:property_manager="Jason Phillips" t:emergency_preparadness_zone="3 - W" t:temporary_facility=No t:name="Sea-Park Garage" t:owner="City FFD" t:pma_number=4271 t:primary_use_type="Parking Lot/Garage" t:secondary_use_type="Office, Shop" t:number=A50005 m:number_of_floors=8 m:critical_facilities_index_cfi=2.4 m:gross_bldg_sq_ft=5558

series e:awiz-hn89 d:1923-01-01T00:00:00.000Z t:property_manager="Scott Thomson" t:temporary_facility=No t:name="Dexter Horton Building" t:owner="Non City" t:pma_number=88 t:primary_use_type=Warehouse t:number=A50006 t:description_1="DoIT leased closet" m:number_of_floors=1 m:critical_facilities_index_cfi=0 m:gross_bldg_sq_ft=48
```

## Meta Commands

```ls
metric m:gross_bldg_sq_ft p:integer l:"Gross Bldg Sq. Ft." t:dataTypeName=number

metric m:number_of_floors p:integer l:"Number of Floors" t:dataTypeName=number

metric m:critical_facilities_index_cfi p:float l:"Critical Facilities Index (CFI)" t:dataTypeName=number

entity e:awiz-hn89 l:"FAS Facilities" t:attribution=FAS t:url=https://data.seattle.gov/api/views/awiz-hn89

property e:awiz-hn89 t:meta.view v:id=awiz-hn89 v:category="Land Base" v:averageRating=0 v:name="FAS Facilities" v:attribution=FAS

property e:awiz-hn89 t:meta.view.license v:name="Public Domain"

property e:awiz-hn89 t:meta.view.owner v:id=fqtv-q6su v:profileImageUrlMedium=/api/users/fqtv-q6su/profile_images/THUMB v:profileImageUrlLarge=/api/users/fqtv-q6su/profile_images/LARGE v:screenName="FAS - Real Estate Services" v:profileImageUrlSmall=/api/users/fqtv-q6su/profile_images/TINY v:displayName="FAS - Real Estate Services"

property e:awiz-hn89 t:meta.view.tableauthor v:id=fqtv-q6su v:profileImageUrlMedium=/api/users/fqtv-q6su/profile_images/THUMB v:profileImageUrlLarge=/api/users/fqtv-q6su/profile_images/LARGE v:screenName="FAS - Real Estate Services" v:profileImageUrlSmall=/api/users/fqtv-q6su/profile_images/TINY v:roleName=publisher v:displayName="FAS - Real Estate Services"
```

## Top Records

```ls
| name                                        | physical_address                        | description                                    | description_1                                                                              | pma_number | number | primary_use_type   | year_built | gross_bldg_sq_ft | emergency_preparadness_zone | number_of_floors | owner    | critical_facilities_index_cfi | property_manager | secondary_use_type                     | other_property_name_s                | pma_other_names | temporary_facility | 
| =========================================== | ======================================= | ============================================== | ========================================================================================== | ========== | ====== | ================== | ========== | ================ | =========================== | ================ | ======== | ============================= | ================ | ====================================== | ==================================== | =============== | ================== | 
| Name                                        | Physical Address                        | Description                                    | Description 1                                                                              |            | Number | Primary Use Type   |            |                  | Emergency Preparadness Zone |                  | Owner    |                               | Property Manager | Secondary Use Type                     | Other Property Name(s)               | PMA Other Names | Temporary Facility | 
| Civic Square Block                          | 610 3RD AV, SEATTLE, WA, 98104          |                                                | Future public/private partnership with construction of an office building and plaza space. | 87         | A50002 | Vacant Lot         |            | 0                | 3 - W                       | 0                | City FFD | 1                             | Jason Phillips   |                                        |                                      |                 | No                 | 
| Sea-Park Garage                             | 609 6TH AV, SEATTLE, WA, 98104          |                                                |                                                                                            | 4271       | A50005 | Parking Lot/Garage | 1993       | 5558             | 3 - W                       | 8                | City FFD | 2.4                           | Jason Phillips   | Office, Shop                           |                                      |                 | No                 | 
| Dexter Horton Building                      | 710 2ND AV, SEATTLE, WA, 98104          |                                                | DoIT leased closet                                                                         | 88         | A50006 | Warehouse          | 1923       | 48               |                             | 1                | Non City | 0                             | Scott Thomson    |                                        |                                      |                 | No                 | 
| SFD Commissary                              | 3601 2ND AVE S, SEATTLE, WA, 98134      |                                                |                                                                                            | 4066       | A50011 | Warehouse          | 1980       | 27611            | 3 - W                       | 1                | Non City | 2.5499999999999998            | Tanya Reeves     | Office                                 |                                      |                 | No                 | 
| Pacific Building                            | 720 THIRD AV, SEATTLE, WA, 98104        | leased space for CERS; lease expires 8/31/2021 | CERS                                                                                       | 4125       | A50013 | Office             |            | 8225             | 3 - W                       | 1                | Non City | 2.4                           | Tanya Reeves     |                                        |                                      |                 | No                 | 
| Charles Street - Fleets Vehicle Maintenance | 805 S CHARLES ST, SEATTLE, WA, 98134    |                                                |                                                                                            | 90         | A50015 | Shop               | 1975       | 68359            | 3 - W                       | 2                | City FFD | 3.4                           | Nonila Masmela   | Office, Parking Lot/Garage, Yard Space |                                      |                 | No                 | 
| Charles Street - Tire Shop                  | 814 8TH AVE S, SEATTLE, WA, 98134       |                                                |                                                                                            | 90         | A50016 | Shop               | 1967       | 6504             | 3 - W                       | 2                | City FFD | 3.4                           | Nonila Masmela   | Warehouse                              |                                      |                 | No                 | 
| University Child Development Home           | 3500 INTERLAKE AV N, SEATTLE, WA, 98103 |                                                | Was Temporary Fire Station 9, and the Print Shop                                           | 91         | A50017 | Storage            | 1960       | 6364             | 1 - NW                      | 1                | City FFD | 1.6                           | Scott Thomson    | Storage                                | Print Shop, Temporary Fire Station 9 |                 | No                 | 
| Charles Street - Fire Garage                | 815 S DEARBORN, SEATTLE, WA, 98134      | Fire station garage parking                    |                                                                                            | 95         | A50018 | Parking Lot/Garage | 1975       | 18553            |                             | 2                | City FFD | 0                             | Nonila Masmela   |                                        |                                      |                 | No                 | 
```