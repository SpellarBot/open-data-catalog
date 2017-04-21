# Hospital Readmissions Reduction Program

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/hospital-readmission-reduction) |
| Metadata | [Link](https://data.medicare.gov/api/views/9n3s-kdb3) |
| Data: JSON | [100 Rows](https://data.medicare.gov/api/views/9n3s-kdb3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicare.gov/api/views/9n3s-kdb3/rows.csv?max_rows=100) |
| Host | data.medicare.gov |
| Id | 9n3s-kdb3 |
| Name | Hospital Readmissions Reduction Program |
| Category | Hospital Compare |
| Tags | hospital compare, linking quality to payment |
| Created | 2012-07-26T14:55:58Z |
| Publication Date | 2016-12-19T02:08:14Z |

## Description

In October 2012, CMS began reducing Medicare payments for Inpatient Prospective Payment System hospitals with excess readmissions. Excess readmissions are measured by a ratio, by dividing a hospital?s number of ?predicted? 30-day readmissions for heart attack, heart failure, and pneumonia by the number that would be ?expected,? based on an average hospital with similar patients. A ratio greater than 1 indicates excess readmissions.

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                       | Data Type | Render Type |
| ======== | ============== | ====================== | ========================== | ========= | =========== |
| No       | time           | :updated_at            | updated_at                 | meta_data | meta_data   |
| Yes      | series tag     | hospital_name          | Hospital Name              | text      | text        |
| Yes      | series tag     | provider_id            | Provider Number            | text      | text        |
| Yes      | series tag     | state                  | State                      | text      | text        |
| Yes      | series tag     | measure_id             | Measure Name               | text      | text        |
| Yes      | numeric metric | number_of_discharges   | Number of Discharges       | number    | text        |
| No       |                | footnote               | Footnote                   | number    | number      |
| Yes      | numeric metric | readm_ratio            | Excess Readmission Ratio   | number    | text        |
| Yes      | numeric metric | predicted              | Predicted Readmission Rate | number    | text        |
| Yes      | numeric metric | expected               | Expected Readmission Rate  | number    | text        |
| Yes      | series tag     | number_of_readmissions | Number of Readmissions     | text      | text        |
| No       |                | start_date             | Start Date                 | text      | text        |
| No       |                | end_date               | End Date                   | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = footnote,start_date,end_date
```

## Data Commands

```ls
series e:9n3s-kdb3 d:2016-11-21T00:13:44.000Z t:hospital_name="SOUTHEAST ALABAMA MEDICAL CENTER" t:measure_id=READM-30-AMI-HRRP t:provider_id=010001 t:number_of_readmissions=119 t:state=AL m:expected=15.6121 m:predicted=15.358 m:number_of_discharges=781 m:readm_ratio=0.9837

series e:9n3s-kdb3 d:2016-11-21T00:13:44.000Z t:hospital_name="SOUTHEAST ALABAMA MEDICAL CENTER" t:measure_id=READM-30-CABG-HRRP t:provider_id=010001 t:number_of_readmissions=40 t:state=AL m:expected=13.0809 m:predicted=13.8887 m:number_of_discharges=273 m:readm_ratio=1.0618

series e:9n3s-kdb3 d:2016-11-21T00:13:44.000Z t:hospital_name="SOUTHEAST ALABAMA MEDICAL CENTER" t:measure_id=READM-30-COPD-HRRP t:provider_id=010001 t:number_of_readmissions=143 t:state=AL m:expected=18.8932 m:predicted=19.7525 m:number_of_discharges=709 m:readm_ratio=1.0455
```

## Meta Commands

```ls
entity e:9n3s-kdb3 l:"Hospital Readmissions Reduction Program" t:url=https://data.medicare.gov/api/views/9n3s-kdb3

property e:9n3s-kdb3 t:meta.view v:id=9n3s-kdb3 v:category="Hospital Compare" v:averageRating=0 v:name="Hospital Readmissions Reduction Program"

property e:9n3s-kdb3 t:meta.view.owner v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:displayName=cms

property e:9n3s-kdb3 t:meta.view.tableauthor v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:roleName=administrator v:displayName=cms

property e:9n3s-kdb3 t:meta.view.metadata.custom_fields.common_core v:Publisher="Centers for Medicare & Medicaid Services (CMS)" v:Contact_Email=HospitalCompare@hsag.com v:Contact_Name=CMS v:Bureau_Code=009:38 v:Program_Code=009:078
```

## Top Records

```ls
| :updated_at | hospital_name                    | provider_id | state | measure_id             | number_of_discharges | footnote | readm_ratio   | predicted     | expected      | number_of_readmissions | start_date | end_date  | 
| =========== | ================================ | =========== | ===== | ====================== | ==================== | ======== | ============= | ============= | ============= | ====================== | ========== | ========= | 
| 1479687224  | SOUTHEAST ALABAMA MEDICAL CENTER | 010001      | AL    | READM-30-AMI-HRRP      | 781                  |          | 0.9837        | 15.3580       | 15.6121       | 119                    | 01-JUL-12  | 30-JUN-15 | 
| 1479687224  | SOUTHEAST ALABAMA MEDICAL CENTER | 010001      | AL    | READM-30-CABG-HRRP     | 273                  |          | 1.0618        | 13.8887       | 13.0809       | 40                     | 01-JUL-12  | 30-JUN-15 | 
| 1479687224  | SOUTHEAST ALABAMA MEDICAL CENTER | 010001      | AL    | READM-30-COPD-HRRP     | 709                  |          | 1.0455        | 19.7525       | 18.8932       | 143                    | 01-JUL-12  | 30-JUN-15 | 
| 1479687224  | SOUTHEAST ALABAMA MEDICAL CENTER | 010001      | AL    | READM-30-HF-HRRP       | 983                  |          | 0.9509        | 20.2502       | 21.2964       | 196                    | 01-JUL-12  | 30-JUN-15 | 
| 1479687224  | SOUTHEAST ALABAMA MEDICAL CENTER | 010001      | AL    | READM-30-HIP-KNEE-HRRP | 335                  |          | 1.1198        | 5.6025        | 5.0034        | 21                     | 01-JUL-12  | 30-JUN-15 | 
| 1479687224  | SOUTHEAST ALABAMA MEDICAL CENTER | 010001      | AL    | READM-30-PN-HRRP       | 664                  |          | 1.0892        | 17.2654       | 15.8507       | 119                    | 01-JUL-12  | 30-JUN-15 | 
| 1479687224  | MARSHALL MEDICAL CENTER SOUTH    | 010005      | AL    | READM-30-AMI-HRRP      | Not Available        |          | 0.9905        | 16.3958       | 16.5529       | Too Few to Report      | 01-JUL-12  | 30-JUN-15 | 
| 1479687224  | MARSHALL MEDICAL CENTER SOUTH    | 010005      | AL    | READM-30-CABG-HRRP     | Not Available        | 5        | Not Available | Not Available | Not Available | Not Available          | 01-JUL-12  | 30-JUN-15 | 
| 1479687224  | MARSHALL MEDICAL CENTER SOUTH    | 010005      | AL    | READM-30-COPD-HRRP     | 667                  |          | 0.9014        | 17.0536       | 18.9196       | 107                    | 01-JUL-12  | 30-JUN-15 | 
| 1479687224  | MARSHALL MEDICAL CENTER SOUTH    | 010005      | AL    | READM-30-HF-HRRP       | 389                  |          | 1.0001        | 21.5918       | 21.5891       | 84                     | 01-JUL-12  | 30-JUN-15 | 
```