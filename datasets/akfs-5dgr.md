# Hospital ACS Measures

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/hospital-acs-measures-473ed) |
| Metadata | [Link](https://data.medicare.gov/api/views/akfs-5dgr) |
| Data: JSON | [100 Rows](https://data.medicare.gov/api/views/akfs-5dgr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicare.gov/api/views/akfs-5dgr/rows.csv?max_rows=100) |
| Host | data.medicare.gov |
| Id | akfs-5dgr |
| Name | Hospital ACS Measures |
| Category | Hospital Compare |
| Tags | hospital compare, readmissions and death |
| Created | 2012-07-26T15:00:31Z |
| Publication Date | 2016-12-19T02:03:26Z |

## Description

These "Outcome of Care Surgical Measures" show whether hospitals differ in what happens to patients after they have one of three types of surgeries.

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                        | Data Type | Render Type |
| ======== | ============== | =========================== | =========================== | ========= | =========== |
| No       | time           | :updated_at                 | updated_at                  | meta_data | meta_data   |
| Yes      | series tag     | ccn                         | CCN                         | text      | text        |
| Yes      | series tag     | hospital_name               | Hospital Name               | text      | text        |
| Yes      | series tag     | acs_1                       | Surg65                      | text      | text        |
| Yes      | numeric metric | acs_1_f                     | Surg65_FN                   | number    | number      |
| Yes      | series tag     | surg65_fn_description       | Surg65_FN_Description       | text      | text        |
| Yes      | series tag     | acs_2                       | Colon                       | text      | text        |
| Yes      | numeric metric | acs_2_f                     | Colon_FN                    | number    | number      |
| Yes      | series tag     | colon_fn_description        | Colon_FN_Description        | text      | text        |
| Yes      | series tag     | acs_3                       | LowExtBypass                | text      | text        |
| Yes      | numeric metric | acs_3_f                     | LowExtBypass_FN             | number    | number      |
| Yes      | series tag     | lowextbypass_fn_description | LowExtBypass_FN_Description | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:akfs-5dgr d:2016-11-16T15:18:48.000Z t:lowextbypass_fn_description="This measure does not apply to this hospital for this reporting period." t:hospital_name="University of Miami Hospital and Clinics/Sylvester" t:ccn=100079 t:colon_fn_description="This measure does not apply to this hospital for this reporting period." t:acs_1=Average t:acs_2="Not Available" t:acs_3="Not Available" m:acs_3_f=12 m:acs_2_f=12

series e:akfs-5dgr d:2016-11-16T15:18:48.000Z t:lowextbypass_fn_description="This measure does not apply to this hospital for this reporting period." t:hospital_name="St. Bernards Medical Center" t:surg65_fn_description="This measure does not apply to this hospital for this reporting period." t:ccn=040020 t:colon_fn_description="This measure does not apply to this hospital for this reporting period." t:acs_1="Not Available" t:acs_2="Not Available" t:acs_3="Not Available" m:acs_3_f=12 m:acs_1_f=12 m:acs_2_f=12

series e:akfs-5dgr d:2016-11-16T15:18:48.000Z t:lowextbypass_fn_description="This measure does not apply to this hospital for this reporting period." t:hospital_name="California Pacific Medical Ctr - Pacific Campus Hosp" t:surg65_fn_description="This measure does not apply to this hospital for this reporting period." t:ccn=050047 t:colon_fn_description="This measure does not apply to this hospital for this reporting period." t:acs_1="Not Available" t:acs_2="Not Available" t:acs_3="Not Available" m:acs_3_f=12 m:acs_1_f=12 m:acs_2_f=12
```

## Meta Commands

```ls
metric m:acs_1_f p:integer l:Surg65_FN t:dataTypeName=number

metric m:acs_2_f p:integer l:Colon_FN t:dataTypeName=number

metric m:acs_3_f p:integer l:LowExtBypass_FN t:dataTypeName=number

entity e:akfs-5dgr l:"Hospital ACS Measures" t:url=https://data.medicare.gov/api/views/akfs-5dgr

property e:akfs-5dgr t:meta.view v:id=akfs-5dgr v:category="Hospital Compare" v:averageRating=0 v:name="Hospital ACS Measures"

property e:akfs-5dgr t:meta.view.owner v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:displayName=cms

property e:akfs-5dgr t:meta.view.tableauthor v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:roleName=administrator v:displayName=cms

property e:akfs-5dgr t:meta.view.metadata.custom_fields.common_core v:Publisher="Centers for Medicare & Medicaid Services (CMS)" v:Contact_Email=HospitalCompare@hsag.com v:Contact_Name=CMS v:Bureau_Code=009:38 v:Program_Code=009:078
```

## Top Records

```ls
| :updated_at | ccn    | hospital_name                                                    | acs_1         | acs_1_f | surg65_fn_description                                                   | acs_2         | acs_2_f | colon_fn_description                                                    | acs_3         | acs_3_f | lowextbypass_fn_description                                             | 
| =========== | ====== | ================================================================ | ============= | ======= | ======================================================================= | ============= | ======= | ======================================================================= | ============= | ======= | ======================================================================= | 
| 1479309528  | 100079 | University of Miami Hospital and Clinics/Sylvester               | Average       |         |                                                                         | Not Available | 12      | This measure does not apply to this hospital for this reporting period. | Not Available | 12      | This measure does not apply to this hospital for this reporting period. | 
| 1479309528  | 010033 | University of Alabama Hospital                                   | Average       |         |                                                                         | Average       |         |                                                                         | Average       |         |                                                                         | 
| 1479309528  | 030038 | Scottsdale Healthcare Osborn Medical Center & Greenbaum Surgical | Average       |         |                                                                         | Average       |         |                                                                         | Average       |         |                                                                         | 
| 1479309528  | 040020 | St. Bernards Medical Center                                      | Not Available | 12      | This measure does not apply to this hospital for this reporting period. | Not Available | 12      | This measure does not apply to this hospital for this reporting period. | Not Available | 12      | This measure does not apply to this hospital for this reporting period. | 
| 1479309528  | 050007 | Peninsula Medical Center                                         | Average       |         |                                                                         | Average       |         |                                                                         | Average       |         |                                                                         | 
| 1479309528  | 050047 | California Pacific Medical Ctr - Pacific Campus Hosp             | Not Available | 12      | This measure does not apply to this hospital for this reporting period. | Not Available | 12      | This measure does not apply to this hospital for this reporting period. | Not Available | 12      | This measure does not apply to this hospital for this reporting period. | 
| 1479309528  | 050072 | Kaiser Foundation Hospital - Walnut Creek                        | Average       |         |                                                                         | Average       |         |                                                                         | Average       |         |                                                                         | 
| 1479309528  | 050159 | Ventura County Medical Center                                    | Not Available | 12      | This measure does not apply to this hospital for this reporting period. | Not Available | 12      | This measure does not apply to this hospital for this reporting period. | Not Available | 12      | This measure does not apply to this hospital for this reporting period. | 
| 1479309528  | 050180 | John Muir Medical Center - Walnut Creek Campus                   | Average       |         |                                                                         | Average       |         |                                                                         | Not Available | 1       | The number of cases/patients is too few to report.                      | 
| 1479309528  | 050292 | Riverside County Regional Medical Center                         | Not Available | 12      | This measure does not apply to this hospital for this reporting period. | Not Available | 12      | This measure does not apply to this hospital for this reporting period. | Not Available | 12      | This measure does not apply to this hospital for this reporting period. | 
```