# Data Updates

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/data-updates-0009d) |
| Metadata | [Link](https://data.medicare.gov/api/views/bzsr-4my4) |
| Data: JSON | [100 Rows](https://data.medicare.gov/api/views/bzsr-4my4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicare.gov/api/views/bzsr-4my4/rows.csv?max_rows=100) |
| Host | data.medicare.gov |
| Id | bzsr-4my4 |
| Name | Data Updates |
| Category | Hospital Compare |
| Tags | hospital compare, general information |
| Created | 2013-08-27T20:25:32Z |
| Publication Date | 2017-01-11T14:27:22Z |

## Description

Lists the data updates for a scheduled quarterly refresh and as well those that are updated in between refreshes.

## Columns

```ls
| Included | Schema Type | Field Name                             | Name                                   | Data Type | Render Type |
| ======== | =========== | ====================================== | ====================================== | ========= | =========== |
| No       | time        | :updated_at                            | updated_at                             | meta_data | meta_data   |
| Yes      | series tag  | data_medicare_gov_location_affected    | Data.Medicare.gov location affected    | url       | url         |
| Yes      | series tag  | downloadable_access_file_affected      | Downloadable Access file affected      | text      | text        |
| Yes      | series tag  | downloadable_csv_revised_file_affected | Downloadable CSV revised file affected | text      | text        |
| Yes      | series tag  | data_last_updated                      | Data Last Updated                      | text      | text        |
| Yes      | series tag  | data_last_updated_details              | Data Last Updated Details              | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:bzsr-4my4 d:2017-01-10T21:25:03.000Z t:downloadable_csv_revised_file_affected="Ambulatory Surgical Measures-Facility.csv" t:data_medicare_gov_location_affected=https://data.medicare.gov/Hospital-Compare/Ambulatory-Surgical-Measures-Facility/4jcv-atw7 t:data_last_updated=19-Dec-16 t:downloadable_access_file_affected="Ambulatory Surgical Measures-Facility" t:data_last_updated_details="Data refreshed - New measure: ASC-11" m:row_number.bzsr-4my4=1

series e:bzsr-4my4 d:2017-01-10T21:25:03.000Z t:downloadable_csv_revised_file_affected="Ambulatory Surgical Measures-National.csv" t:data_medicare_gov_location_affected=https://data.medicare.gov/Hospital-Compare/Ambulatory-Surgical-Measures-National/wue8-3vwe t:data_last_updated=19-Dec-16 t:downloadable_access_file_affected="Ambulatory Surgical Measures-National" t:data_last_updated_details="Data refreshed - New measure: ASC-11" m:row_number.bzsr-4my4=2

series e:bzsr-4my4 d:2017-01-10T21:25:03.000Z t:downloadable_csv_revised_file_affected="Ambulatory Surgical Measures-State.csv" t:data_medicare_gov_location_affected=https://data.medicare.gov/Hospital-Compare/Ambulatory-Surgical-Measures-State/axe7-s95e t:data_last_updated=19-Dec-16 t:downloadable_access_file_affected="Ambulatory Surgical Measures-State" t:data_last_updated_details="Data refreshed - New measure: ASC-11" m:row_number.bzsr-4my4=3
```

## Meta Commands

```ls
metric m:row_number.bzsr-4my4 p:long l:"Row Number"

entity e:bzsr-4my4 l:"Data Updates" t:url=https://data.medicare.gov/api/views/bzsr-4my4

property e:bzsr-4my4 t:meta.view v:id=bzsr-4my4 v:category="Hospital Compare" v:averageRating=0 v:name="Data Updates"

property e:bzsr-4my4 t:meta.view.owner v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:displayName=cms

property e:bzsr-4my4 t:meta.view.tableauthor v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:roleName=administrator v:displayName=cms

property e:bzsr-4my4 t:meta.view.metadata.custom_fields.common_core v:Publisher="Centers for Medicare & Medicaid Services (CMS)" v:Contact_Email=HospitalCompare@hsag.com v:Contact_Name=CMS v:Bureau_Code=009:38 v:Program_Code=009:078
```

## Top Records

```ls
| :updated_at | data_medicare_gov_location_affected                                                                             | downloadable_access_file_affected                             | downloadable_csv_revised_file_affected                           | data_last_updated | data_last_updated_details            | 
| =========== | =============================================================================================================== | ============================================================= | ================================================================ | ================= | ==================================== | 
| 1484083503  | [https://data.medicare.gov/Hospital-Compare/Ambulatory-Surgical-Measures-Facility/4jcv-atw7, null]              | Ambulatory Surgical Measures-Facility                         | Ambulatory Surgical Measures-Facility.csv                        | 19-Dec-16         | Data refreshed - New measure: ASC-11 | 
| 1484083503  | [https://data.medicare.gov/Hospital-Compare/Ambulatory-Surgical-Measures-National/wue8-3vwe, null]              | Ambulatory Surgical Measures-National                         | Ambulatory Surgical Measures-National.csv                        | 19-Dec-16         | Data refreshed - New measure: ASC-11 | 
| 1484083503  | [https://data.medicare.gov/Hospital-Compare/Ambulatory-Surgical-Measures-State/axe7-s95e, null]                 | Ambulatory Surgical Measures-State                            | Ambulatory Surgical Measures-State.csv                           | 19-Dec-16         | Data refreshed - New measure: ASC-11 | 
| 1484083503  | [https://data.medicare.gov/Hospital-Compare/Complications-Hospital/632h-zaca, null]                             | HQI_HOSP_Comp                                                 | Complications - Hospital.csv                                     | 19-Dec-16         | Hospital open/closed list applied    | 
| 1484083503  | [https://data.medicare.gov/Hospital-Compare/Complications-National/cvcs-xecj, null]                             | HQI_NATIONAL_Comp                                             | Complications - National.csv                                     | 19-Dec-16         | Hospital open/closed list applied    | 
| 1484083503  | [https://data.medicare.gov/Hospital-Compare/Complications-State/4gkm-5ypv, null]                                | HQI_STATE_Comp                                                | Complications - State.csv                                        | 19-Dec-16         | Hospital open/closed list applied    | 
| 1484083503  | [https://data.medicare.gov/Hospital-Compare/Footnote-Crosswalk/y9us-9xdf, null]                                 | HQI_FTNT                                                      | Footnote Crosswalk.csv                                           | 19-Dec-16         | Data refreshed                       | 
| 1484083503  | [https://data.medicare.gov/Hospital-Compare/Table-1-Net-Change-in-Base-Operating-DRG-Payment-A/5gv4-jwyv, null] | FY2015_Distribution_of_ Net_Change_in_Base_Op_DRG_Payment_Amt | FY2015_Distribution_of_Net_Change_in_Base_Op_DRG_Payment_Amt.csv | 19-Dec-16         | Data refreshed                       | 
| 1484083503  | [https://data.medicare.gov/Hospital-Compare/Table-2-FY2015-Distribution-of-Net-Change-in-Base-/xrgf-x36b, null] | FY2015_Net_Change_in_Base_Op_DRG_Payment_Amt                  | FY2015_Net_Change_in_Base_Op_DRG_Payment_Amt.csv                 | 19-Dec-16         | Data refreshed                       | 
| 1484083503  | [https://data.medicare.gov/Hospital-Compare/Table-3-FY2015-Percent-Change-in-Base-Operating-DR/u625-zae7, null] | FY2015_Percent_Change_in_Base_Operating_DRG_Payment_ Amount   | FY2015_Percent_Change_in_Medicare_Payments.csv                   | 19-Dec-16         | Data refreshed                       | 
```