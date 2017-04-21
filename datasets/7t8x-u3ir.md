# Inpatient Rehabilitation Facility - General Information

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/inpatient-rehabilitation-facility-general-information) |
| Metadata | [Link](https://data.medicare.gov/api/views/7t8x-u3ir) |
| Data: JSON | [100 Rows](https://data.medicare.gov/api/views/7t8x-u3ir/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicare.gov/api/views/7t8x-u3ir/rows.csv?max_rows=100) |
| Host | data.medicare.gov |
| Id | 7t8x-u3ir |
| Name | Inpatient Rehabilitation Facility - General Information |
| Category | Inpatient Rehabilitation Facility Compare |
| Tags | inpatient rehabilitation facilities, inpatient rehabilitation facility, rehabilitation |
| Created | 2016-03-28T17:51:16Z |
| Publication Date | 2017-03-21T01:12:45Z |

## Description

This dataset shows characteristics of the inpatient rehabilitation facilities that are shown on Inpatient Rehabilitation Facility Compare.

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                           | Data Type     | Render Type   |
| ======== | ============== | ============================ | ============================== | ============= | ============= |
| Yes      | series tag     | cms_certification_number_ccn | CMS Certification Number (CCN) | text          | text          |
| Yes      | series tag     | facility_name                | Facility Name                  | text          | text          |
| No       |                | address_line_1               | Address Line 1                 | text          | text          |
| No       |                | address_line_2               | Address Line 2                 | text          | text          |
| Yes      | series tag     | city                         | City                           | text          | text          |
| Yes      | series tag     | state                        | State                          | text          | text          |
| Yes      | series tag     | zip_code                     | Zip Code                       | text          | text          |
| Yes      | series tag     | county_name                  | County Name                    | text          | text          |
| Yes      | series tag     | phonenumber                  | PhoneNumber                    | phone         | phone         |
| Yes      | numeric metric | cms_region                   | CMS Region                     | number        | number        |
| Yes      | series tag     | ownership_type               | Ownership Type                 | text          | text          |
| Yes      | time           | certification_date           | Certification Date             | calendar_date | calendar_date |
```

## Time Field

```ls
Value = certification_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address_line_1,address_line_2
```

## Data Commands

```ls
series e:7t8x-u3ir d:1988-07-01T00:00:00.000Z t:cms_certification_number_ccn=39T147 t:ownership_type=Non-profit t:phone_number="(724) 258-1405" t:zip_code=15063 t:facility_name="MONONGAHELA VALLEY HOSPITAL" t:state=PA t:county_name=Washington t:city=MONONGAHELA m:cms_region=3

series e:7t8x-u3ir d:1992-06-01T00:00:00.000Z t:cms_certification_number_ccn=19T204 t:ownership_type=Non-profit t:phone_number="(985) 649-7070" t:zip_code=70461 t:facility_name="OCHSNER MEDICAL CENTER - NORTH SHORE" t:state=LA t:county_name="St. Tammany" t:city=SLIDELL m:cms_region=6

series e:7t8x-u3ir d:1999-10-01T00:00:00.000Z t:cms_certification_number_ccn=11T007 t:ownership_type=Government t:phone_number="(229) 434-2264" t:zip_code=31701 t:facility_name="PHOEBE PUTNEY MEMORIAL HOSPITAL" t:state=GA t:county_name=Dougherty t:city=ALBANY m:cms_region=4
```

## Meta Commands

```ls
metric m:cms_region p:integer l:"CMS Region" t:dataTypeName=number

entity e:7t8x-u3ir l:"Inpatient Rehabilitation Facility - General Information" t:url=https://data.medicare.gov/api/views/7t8x-u3ir

property e:7t8x-u3ir t:meta.view v:id=7t8x-u3ir v:category="Inpatient Rehabilitation Facility Compare" v:averageRating=0 v:name="Inpatient Rehabilitation Facility - General Information"

property e:7t8x-u3ir t:meta.view.owner v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:displayName=cms

property e:7t8x-u3ir t:meta.view.tableauthor v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:roleName=administrator v:displayName=cms

property e:7t8x-u3ir t:meta.view.metadata.custom_fields.common_core v:Publisher="Centers for Medicare & Medicaid Services (CMS)" v:Contact_Email=IRFQualityQuestions@cms.hhs.gov v:Contact_Name=CMS v:Bureau_Code=009:38 v:Program_Code=009:078
```

## Top Records

```ls
| cms_certification_number_ccn | facility_name                        | address_line_1           | address_line_2  | city        | state | zip_code | county_name | phonenumber            | cms_region | ownership_type | certification_date  | 
| ============================ | ==================================== | ======================== | =============== | =========== | ===== | ======== | =========== | ====================== | ========== | ============== | =================== | 
| 39T147                       | MONONGAHELA VALLEY HOSPITAL          | COUNTRY CLUB ROAD        |                 | MONONGAHELA | PA    | 15063    | Washington  | [(724) 258-1405, null] | 3          | Non-profit     | 1988-07-01T00:00:00 | 
| 19T204                       | OCHSNER MEDICAL CENTER - NORTH SHORE | 100 MEDICAL CENTER DRIVE |                 | SLIDELL     | LA    | 70461    | St. Tammany | [(985) 649-7070, null] | 6          | Non-profit     | 1992-06-01T00:00:00 | 
| 11T007                       | PHOEBE PUTNEY MEMORIAL HOSPITAL      | 2000 PALMYRA RD          |                 | ALBANY      | GA    | 31701    | Dougherty   | [(229) 434-2264, null] | 4          | Government     | 1999-10-01T00:00:00 | 
| 36T074                       | FLOWER REHABILITATION CENTER         | 5150 HARROUN ROAD        |                 | SYLVANIA    | OH    | 43560    | Lucas       | [(419) 824-1095, null] | 5          | Non-profit     | 1986-10-11T00:00:00 | 
| 33T279                       | BUFFALO MERCY REHABILITATION UNIT    | 565 ABBOTT ROAD          |                 | BUFFALO     | NY    | 14220    | Erie        | [(716) 862-2118, null] | 2          | Non-profit     | 1986-01-01T00:00:00 | 
| 11T054                       | FLOYD MEDICAL CENTER                 | P. O. BOX 233            |                 | ROME        | GA    | 30162    | Floyd       | [(706) 509-6627, null] | 4          | Government     | 2007-02-05T00:00:00 | 
| 11T143                       | WELLSTAR COBB HOSPITAL               | 3950 AUSTELL ROAD        | 3950 AUSTELL RD | AUSTELL     | GA    | 30106    | Cobb        | [(770) 732-5033, null] | 4          | Non-profit     | 1997-07-01T00:00:00 | 
| 26T062                       | ST LUKES NORTHLAND HOSPITAL          | 601 SOUTH 169 HIGHWAY    |                 | SMITHVILLE  | MO    | 64089    | Clay        | [(816) 532-3700, null] | 7          | Non-profit     | 2003-01-01T00:00:00 | 
| 11T043                       | THE REHAB CENTER AT ST. JOSEPH'S     | 11705 MERCY BLVD.        |                 | SAVANNAH    | GA    | 31419    | Chatham     | [(912) 819-4100, null] | 4          | Non-profit     | 1998-07-01T00:00:00 | 
| 03T085                       | NORTHWEST MEDICAL CENTER/CHS         | 6200 N LA CHOLLA BLVD    |                 | TUCSON      | AZ    | 85741    | Pima        | [(520) 469-8366, null] | 9          | For profit     | 2013-10-01T00:00:00 | 
```