# Outpatient Imaging Efficiency - National

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/outpatient-imaging-efficiency-national-f0670) |
| Metadata | [Link](https://data.medicare.gov/api/views/di9i-zzrc) |
| Data: JSON | [100 Rows](https://data.medicare.gov/api/views/di9i-zzrc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicare.gov/api/views/di9i-zzrc/rows.csv?max_rows=100) |
| Host | data.medicare.gov |
| Id | di9i-zzrc |
| Name | Outpatient Imaging Efficiency - National |
| Category | Hospital Compare |
| Tags | hospital compare, medical imaging, quality, ratings, mri, ct, mammogram, ultrasound, national average, use of medical imaging |
| Created | 2014-05-14T14:13:03Z |
| Publication Date | 2016-12-19T02:11:51Z |

## Description

Use of medical imaging - national data. These measures give you information about hospitals' use of medical imaging tests for outpatients. Examples of medical imaging tests include CT Scans, MRIs, and mammograms.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type     | Render Type   |
| ======== | ============== | ================== | ================== | ============= | ============= |
| Yes      | series tag     | measure_id         | Measure ID         | text          | text          |
| Yes      | series tag     | measure_name       | Measure Name       | text          | text          |
| Yes      | numeric metric | score              | Score              | number        | text          |
| No       |                | footnote           | Footnote           | text          | text          |
| Yes      | time           | measure_start_date | Measure Start Date | calendar_date | calendar_date |
| No       |                | measure_end_date   | Measure End Date   | calendar_date | calendar_date |
```

## Time Field

```ls
Value = measure_start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = footnote,measure_end_date
```

## Data Commands

```ls
series e:di9i-zzrc d:2014-07-01T00:00:00.000Z t:measure_id=OP_10 t:measure_name="Abdomen CT Use of Contrast Material" m:score=8.4

series e:di9i-zzrc d:2014-07-01T00:00:00.000Z t:measure_id=OP_11 t:measure_name="Thorax CT Use of Contrast Material" m:score=2.1

series e:di9i-zzrc d:2014-07-01T00:00:00.000Z t:measure_id=OP_13 t:measure_name="Outpatients who got cardiac imaging stress tests before low-risk outpatient surgery" m:score=4.8
```

## Meta Commands

```ls
metric m:score p:float l:Score t:dataTypeName=number

entity e:di9i-zzrc l:"Outpatient Imaging Efficiency - National" t:url=https://data.medicare.gov/api/views/di9i-zzrc

property e:di9i-zzrc t:meta.view v:id=di9i-zzrc v:category="Hospital Compare" v:averageRating=0 v:name="Outpatient Imaging Efficiency - National"

property e:di9i-zzrc t:meta.view.owner v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:displayName=cms

property e:di9i-zzrc t:meta.view.tableauthor v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:roleName=administrator v:displayName=cms

property e:di9i-zzrc t:meta.view.metadata.custom_fields.common_core v:Publisher="Centers for Medicare & Medicaid Services (CMS)" v:Contact_Email=HospitalCompare@hsag.com v:Contact_Name=CMS v:Bureau_Code=009:38 v:Program_Code=009:078
```

## Top Records

```ls
| measure_id | measure_name                                                                        | score | footnote | measure_start_date  | measure_end_date    | 
| ========== | =================================================================================== | ===== | ======== | =================== | =================== | 
| OP_10      | Abdomen CT Use of Contrast Material                                                 | 8.4   |          | 2014-07-01T00:00:00 | 2015-06-30T00:00:00 | 
| OP_11      | Thorax CT Use of Contrast Material                                                  | 2.1   |          | 2014-07-01T00:00:00 | 2015-06-30T00:00:00 | 
| OP_13      | Outpatients who got cardiac imaging stress tests before low-risk outpatient surgery | 4.8   |          | 2014-07-01T00:00:00 | 2015-06-30T00:00:00 | 
| OP_14      | Outpatients with brain CT scans who got a sinus CT scan at the same time            | 2.9   |          | 2014-07-01T00:00:00 | 2015-06-30T00:00:00 | 
| OP_8       | MRI Lumbar Spine for Low Back Pain                                                  | 39.5  |          | 2014-07-01T00:00:00 | 2015-06-30T00:00:00 | 
| OP_9       | Mammography Follow-up Rates                                                         | 8.9   |          | 2014-07-01T00:00:00 | 2015-06-30T00:00:00 | 
```