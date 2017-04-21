# Deficiencies

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/deficiencies-02c11) |
| Metadata | [Link](https://data.medicare.gov/api/views/r5ix-sfxw) |
| Data: JSON | [100 Rows](https://data.medicare.gov/api/views/r5ix-sfxw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicare.gov/api/views/r5ix-sfxw/rows.csv?max_rows=100) |
| Host | data.medicare.gov |
| Id | r5ix-sfxw |
| Name | Deficiencies |
| Category | Nursing Home Compare |
| Tags | nhc, nursing home, complaints, safety, inspection results |
| Created | 2013-07-11T15:38:00Z |
| Publication Date | 2017-03-22T02:00:51Z |

## Description

A list of all deficiencies currently listed on Nursing Home Compare, including the nursing home that received the deficiency, the associated inspection date, deficiency tag number, scope and severity, the current status of the deficiency and the correction date.  Data are presented as one deficiency per row.

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type     | Render Type   |
| ======== | ============== | ======================= | ======================= | ============= | ============= |
| Yes      | series tag     | federal_provider_number | Federal Provider Number | text          | text          |
| Yes      | series tag     | provider_name           | Provider Name           | text          | text          |
| No       |                | provider_address        | Provider Address        | text          | text          |
| Yes      | series tag     | provider_city           | Provider City           | text          | text          |
| Yes      | series tag     | provider_state          | Provider State          | text          | text          |
| Yes      | series tag     | provider_zip_code       | Provider Zip Code       | text          | text          |
| Yes      | time           | survey_date             | Survey Date             | calendar_date | calendar_date |
| Yes      | series tag     | survey_type             | Survey Type             | text          | text          |
| Yes      | series tag     | deficiency_prefix       | Deficiency Prefix       | text          | text          |
| Yes      | series tag     | deficiency_tag_number   | Deficiency Tag Number   | text          | text          |
| Yes      | series tag     | deficiency_description  | Deficiency Description  | text          | text          |
| Yes      | series tag     | scope_severity_code     | Scope Severity Code     | text          | text          |
| Yes      | series tag     | deficiency_corrected    | Deficiency Corrected    | text          | text          |
| No       |                | correction_date         | Correction Date         | calendar_date | calendar_date |
| Yes      | numeric metric | inspection_cycle        | Inspection Cycle        | number        | number        |
| Yes      | series tag     | standard_deficiency     | Standard Deficiency     | checkbox      | checkbox      |
| Yes      | series tag     | complaint_deficiency    | Complaint Deficiency    | checkbox      | checkbox      |
| No       |                | processing_date         | Processing Date         | calendar_date | calendar_date |
```

## Time Field

```ls
Value = survey_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = provider_address,correction_date,processing_date
```

## Data Commands

```ls
series e:r5ix-sfxw d:2015-03-26T00:00:00.000Z t:complaint_deficiency=false t:survey_type=Health t:deficiency_description="Make sure that a working call system is available in each resident's room or bathroom and bathing area." t:deficiency_corrected="Deficient, Provider has date of correction" t:provider_zip_code=40823 t:deficiency_prefix=F t:provider_city=CUMBERLAND t:deficiency_tag_number=0463 t:scope_severity_code=D t:federal_provider_number=185433 t:standard_deficiency=true t:provider_state=KY t:provider_name="TRI-CITIES NURSING AND REHABILITATION CENTER" m:inspection_cycle=2

series e:r5ix-sfxw d:2015-02-26T00:00:00.000Z t:complaint_deficiency=true t:survey_type=Health t:deficiency_description="Immediately tell the resident, the resident's doctor, and a family member of situations (injury/decline/room, etc.)  that affect the resident." t:deficiency_corrected="Deficient, Provider has date of correction" t:provider_zip_code=40065 t:deficiency_prefix=F t:provider_city=SHELBYVILLE t:deficiency_tag_number=0157 t:scope_severity_code=D t:federal_provider_number=185409 t:standard_deficiency=true t:provider_state=KY t:provider_name="CRESTVIEW CENTER" m:inspection_cycle=2

series e:r5ix-sfxw d:2015-02-26T00:00:00.000Z t:complaint_deficiency=true t:survey_type=Health t:deficiency_description="Ensure residents maintain acceptable nutritional status." t:deficiency_corrected="Deficient, Provider has date of correction" t:provider_zip_code=40065 t:deficiency_prefix=F t:provider_city=SHELBYVILLE t:deficiency_tag_number=0325 t:scope_severity_code=D t:federal_provider_number=185409 t:standard_deficiency=true t:provider_state=KY t:provider_name="CRESTVIEW CENTER" m:inspection_cycle=2
```

## Meta Commands

```ls
metric m:inspection_cycle p:integer l:"Inspection Cycle" t:dataTypeName=number

entity e:r5ix-sfxw l:Deficiencies t:url=https://data.medicare.gov/api/views/r5ix-sfxw

property e:r5ix-sfxw t:meta.view v:id=r5ix-sfxw v:category="Nursing Home Compare" v:averageRating=0 v:name=Deficiencies

property e:r5ix-sfxw t:meta.view.owner v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:displayName=cms

property e:r5ix-sfxw t:meta.view.tableauthor v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:roleName=administrator v:displayName=cms

property e:r5ix-sfxw t:meta.view.metadata.custom_fields.common_core v:Publisher="Centers for Medicare & Medicaid Services (CMS)" v:Contact_Email=Edward.Mortimore@cms.hhs.gov v:Contact_Name=CMS v:Bureau_Code=009:38 v:Program_Code=009:078
```

## Top Records

```ls
| federal_provider_number | provider_name                                | provider_address           | provider_city | provider_state | provider_zip_code | survey_date         | survey_type | deficiency_prefix | deficiency_tag_number | deficiency_description                                                                                                                        | scope_severity_code | deficiency_corrected                       | correction_date     | inspection_cycle | standard_deficiency | complaint_deficiency | processing_date     | 
| ======================= | ============================================ | ========================== | ============= | ============== | ================= | =================== | =========== | ================= | ===================== | ============================================================================================================================================= | =================== | ========================================== | =================== | ================ | =================== | ==================== | =================== | 
| 185433                  | TRI-CITIES NURSING AND REHABILITATION CENTER | 19101 US HIGHWAY 119 NORTH | CUMBERLAND    | KY             | 40823             | 2015-03-26T00:00:00 | Health      | F                 | 0463                  | Make sure that a working call system is available in each resident's room or bathroom and bathing area.                                       | D                   | Deficient, Provider has date of correction | 2015-05-04T00:00:00 | 2                | true                | false                | 2017-03-01T00:00:00 | 
| 185409                  | CRESTVIEW CENTER                             | 1871 MIDLAND TRAIL         | SHELBYVILLE   | KY             | 40065             | 2015-02-26T00:00:00 | Health      | F                 | 0157                  | Immediately tell the resident, the resident's doctor, and a family member of situations (injury/decline/room, etc.) that affect the resident. | D                   | Deficient, Provider has date of correction | 2015-04-07T00:00:00 | 2                | true                | true                 | 2017-03-01T00:00:00 | 
| 185409                  | CRESTVIEW CENTER                             | 1871 MIDLAND TRAIL         | SHELBYVILLE   | KY             | 40065             | 2015-02-26T00:00:00 | Health      | F                 | 0325                  | Ensure residents maintain acceptable nutritional status.                                                                                      | D                   | Deficient, Provider has date of correction | 2015-04-07T00:00:00 | 2                | true                | true                 | 2017-03-01T00:00:00 | 
| 185414                  | MOUNTAIN MANOR OF PAINTSVILLE                | 1025 EUCLID AVENUE         | PAINTSVILLE   | KY             | 41240             | 2014-11-25T00:00:00 | Health      | F                 | 0314                  | Give residents proper treatment to prevent new bed (pressure) sores or heal existing bed sores.                                               | D                   | Deficient, Provider has date of correction | 2014-12-12T00:00:00 | 3                | false               | true                 | 2017-03-01T00:00:00 | 
| 185434                  | THE HERITAGE                                 | 192 BACON CREEK ROAD       | CORBIN        | KY             | 40702             | 2016-11-23T00:00:00 | Health      | F                 | 0364                  | Prepare food that is nutritional, appetizing, tasty, attractive, well-cooked, and at the right temperature.                                   | D                   | Deficient, Provider has date of correction | 2016-12-16T00:00:00 | 1                | true                | false                | 2017-03-01T00:00:00 | 
| 185423                  | EDGEWOOD ESTATES                             | 195 BERRYMAN ROAD          | FRENCHBURG    | KY             | 40322             | 2016-07-21T00:00:00 | Health      | F                 | 0431                  | Maintain drug records and properly mark/label drugs and other similar products according to accepted professional standards.                  | E                   | Deficient, Provider has date of correction | 2016-07-30T00:00:00 | 1                | true                | false                | 2017-03-01T00:00:00 | 
| 185447                  | VILLASPRING OF ERLANGER                      | 630 VIOX DRIVE             | ERLANGER      | KY             | 41018             | 2016-05-12T00:00:00 | Health      | F                 | 0309                  | Provide necessary care and services to maintain or improve the highest well being of each resident .                                          | D                   | Deficient, Provider has date of correction | 2016-06-17T00:00:00 | 1                | true                | false                | 2017-03-01T00:00:00 | 
| 185444                  | CAMBRIDGE PLACE GROUP, LLC                   | 2020 CAMBRIDGE DRIVE       | LEXINGTON     | KY             | 40504             | 2015-02-20T00:00:00 | Health      | F                 | 0441                  | Have a program that investigates, controls and keeps infection from spreading.                                                                | E                   | Deficient, Provider has date of correction | 2015-03-31T00:00:00 | 2                | true                | false                | 2017-03-01T00:00:00 | 
| 185402                  | HENDERSON NURSING AND REHABILITATION CENTER  | 2500 NORTH ELM ST.         | HENDERSON     | KY             | 42420             | 2015-04-07T00:00:00 | Health      | F                 | 0490                  | Make sure that the facility is administered in an acceptable way that maintains the well-being of each resident .                             | D                   | Deficient, Provider has date of correction | 2015-05-11T00:00:00 | 2                | false               | true                 | 2017-03-01T00:00:00 | 
| 185402                  | HENDERSON NURSING AND REHABILITATION CENTER  | 2500 NORTH ELM ST.         | HENDERSON     | KY             | 42420             | 2016-05-06T00:00:00 | Health      | F                 | 0282                  | Provide care by qualified persons according to each resident's written plan of care.                                                          | K                   | Deficient, Provider has date of correction | 2016-06-13T00:00:00 | 1                | true                | true                 | 2017-03-01T00:00:00 | 
```