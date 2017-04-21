# Value of care - National

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/value-of-care-national) |
| Metadata | [Link](https://data.medicare.gov/api/views/gbq5-7hzr) |
| Data: JSON | [100 Rows](https://data.medicare.gov/api/views/gbq5-7hzr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicare.gov/api/views/gbq5-7hzr/rows.csv?max_rows=100) |
| Host | data.medicare.gov |
| Id | gbq5-7hzr |
| Name | Value of care - National |
| Category | Hospital Compare |
| Tags | hospital compare, medicare payment |
| Created | 2015-09-03T19:00:43Z |
| Publication Date | 2016-12-19T02:16:16Z |

## Description

Value of care displays ? national data. This data set includes national-level data for the value of care displays associated with a 30-day episode of care for heart attack, heart failure, and pneumonia patients.

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type     | Render Type   |
| ======== | ============== | ========================== | ========================== | ============= | ============= |
| Yes      | series tag     | value_of_care_measure_name | Value of care measure name | text          | text          |
| Yes      | series tag     | value_of_care_measure_id   | Value of care measure ID   | text          | text          |
| Yes      | numeric metric | number_of_hospitals        | Number of hospitals        | number        | number        |
| Yes      | time           | measure_start_date         | Measure start date         | calendar_date | calendar_date |
| No       |                | measure_end_date           | Measure end date           | calendar_date | calendar_date |
```

## Time Field

```ls
Value = measure_start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = measure_end_date
```

## Data Commands

```ls
series e:gbq5-7hzr d:2012-07-01T00:00:00.000Z t:value_of_care_measure_name="Value of Care for heart attack patients - Worse mortality & lower payment" t:value_of_care_measure_id=TOT_MORT_30_AMI_WORSE_PAYM_30_AMI_LOWER m:number_of_hospitals=4

series e:gbq5-7hzr d:2012-07-01T00:00:00.000Z t:value_of_care_measure_name="Value of Care for heart attack patients - Worse mortality & average payment" t:value_of_care_measure_id=TOT_MORT_30_AMI_WORSE_PAYM_30_AMI_AVERAGE m:number_of_hospitals=17

series e:gbq5-7hzr d:2012-07-01T00:00:00.000Z t:value_of_care_measure_name="Value of Care for heart attack patients - Worse mortality & higher payment" t:value_of_care_measure_id=TOT_MORT_30_AMI_WORSE_PAYM_30_AMI_HIGHER m:number_of_hospitals=3
```

## Meta Commands

```ls
metric m:number_of_hospitals p:integer l:"Number of hospitals" t:dataTypeName=number

entity e:gbq5-7hzr l:"Value of care -  National" t:url=https://data.medicare.gov/api/views/gbq5-7hzr

property e:gbq5-7hzr t:meta.view v:id=gbq5-7hzr v:category="Hospital Compare" v:averageRating=0 v:name="Value of care -  National"

property e:gbq5-7hzr t:meta.view.owner v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:displayName=cms

property e:gbq5-7hzr t:meta.view.tableauthor v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:roleName=administrator v:displayName=cms

property e:gbq5-7hzr t:meta.view.metadata.custom_fields.common_core v:Publisher="Centers for Medicare & Medicaid Services (CMS)" v:Contact_Email=HospitalCompare@hsag.com v:Contact_Name=CMS v:Bureau_Code=009:38 v:Program_Code=009:078
```

## Top Records

```ls
| value_of_care_measure_name                                                    | value_of_care_measure_id                    | number_of_hospitals | measure_start_date  | measure_end_date    | 
| ============================================================================= | =========================================== | =================== | =================== | =================== | 
| Value of Care for heart attack patients - Worse mortality & lower payment     | TOT_MORT_30_AMI_WORSE_PAYM_30_AMI_LOWER     | 4                   | 2012-07-01T00:00:00 | 2015-06-30T00:00:00 | 
| Value of Care for heart attack patients - Worse mortality & average payment   | TOT_MORT_30_AMI_WORSE_PAYM_30_AMI_AVERAGE   | 17                  | 2012-07-01T00:00:00 | 2015-06-30T00:00:00 | 
| Value of Care for heart attack patients - Worse mortality & higher payment    | TOT_MORT_30_AMI_WORSE_PAYM_30_AMI_HIGHER    | 3                   | 2012-07-01T00:00:00 | 2015-06-30T00:00:00 | 
| Value of Care for heart attack patients - Average mortality & lower payment   | TOT_MORT_30_AMI_AVERAGE_PAYM_30_AMI_LOWER   | 166                 | 2012-07-01T00:00:00 | 2015-06-30T00:00:00 | 
| Value of Care for heart attack patients - Average mortality & average payment | TOT_MORT_30_AMI_AVERAGE_PAYM_30_AMI_AVERAGE | 1921                | 2012-07-01T00:00:00 | 2015-06-30T00:00:00 | 
| Value of Care for heart attack patients - Average mortality & higher payment  | TOT_MORT_30_AMI_AVERAGE_PAYM_30_AMI_HIGHER  | 240                 | 2012-07-01T00:00:00 | 2015-06-30T00:00:00 | 
| Value of Care for heart attack patients - Better mortality & lower payment    | TOT_MORT_30_AMI_BETTER_PAYM_30_AMI_LOWER    | 12                  | 2012-07-01T00:00:00 | 2015-06-30T00:00:00 | 
| Value of Care for heart attack patients - Better mortality & average payment  | TOT_MORT_30_AMI_BETTER_PAYM_30_AMI_AVERAGE  | 33                  | 2012-07-01T00:00:00 | 2015-06-30T00:00:00 | 
| Value of Care for heart attack patients - Better mortality & higher payment   | TOT_MORT_30_AMI_BETTER_PAYM_30_AMI_HIGHER   | 12                  | 2012-07-01T00:00:00 | 2015-06-30T00:00:00 | 
| Value of Care for pneumonia patients - Worse mortality & lower payment        | TOT_MORT_30_PN_WORSE_PAYM_30_PN_LOWER       | 35                  | 2012-07-01T00:00:00 | 2015-06-30T00:00:00 | 
```