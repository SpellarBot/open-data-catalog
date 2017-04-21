# Measure Dates

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/measure-dates-3bd67) |
| Metadata | [Link](https://data.medicare.gov/api/views/4j6d-yzce) |
| Data: JSON | [100 Rows](https://data.medicare.gov/api/views/4j6d-yzce/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicare.gov/api/views/4j6d-yzce/rows.csv?max_rows=100) |
| Host | data.medicare.gov |
| Id | 4j6d-yzce |
| Name | Measure Dates |
| Category | Hospital Compare |
| Tags | hospital compare, general information |
| Created | 2014-05-14T14:02:39Z |
| Publication Date | 2016-12-19T02:10:35Z |

## Description

Data Collection Periods for all measures on Hospital Compare.

## Columns

```ls
| Included | Schema Type | Field Name            | Name                  | Data Type     | Render Type   |
| ======== | =========== | ===================== | ===================== | ============= | ============= |
| Yes      | series tag  | measure_name          | Measure Name          | text          | text          |
| Yes      | series tag  | measure_id            | Measure ID            | text          | text          |
| No       |             | measure_start_quarter | Measure Start Quarter | text          | text          |
| Yes      | time        | measure_start_date    | Measure Start Date    | calendar_date | calendar_date |
| No       |             | measure_end_quarter   | Measure End Quarter   | text          | text          |
| No       |             | measure_end_date      | Measure End Date      | calendar_date | calendar_date |
```

## Time Field

```ls
Value = measure_start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = measure_end_quarter,measure_end_date,measure_start_quarter
```

## Data Commands

```ls
series e:4j6d-yzce d:2015-01-01T00:00:00.000Z t:measure_id=ACS_REGISTRY t:measure_name="ACS Participation data" m:row_number.4j6d-yzce=1

series e:4j6d-yzce d:2013-01-01T00:00:00.000Z t:measure_id=AMI_7a_HVBP_Baseline t:measure_name="Fibrinolytic Therapy Received Within 30 Minutes of Hospital Arrival" m:row_number.4j6d-yzce=2

series e:4j6d-yzce d:2015-01-01T00:00:00.000Z t:measure_id=AMI_7a_HVBP_Performance t:measure_name="Fibrinolytic Therapy Received Within 30 Minutes of Hospital Arrival" m:row_number.4j6d-yzce=3
```

## Meta Commands

```ls
metric m:row_number.4j6d-yzce p:long l:"Row Number"

entity e:4j6d-yzce l:"Measure Dates" t:url=https://data.medicare.gov/api/views/4j6d-yzce

property e:4j6d-yzce t:meta.view v:id=4j6d-yzce v:category="Hospital Compare" v:averageRating=0 v:name="Measure Dates"

property e:4j6d-yzce t:meta.view.owner v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:displayName=cms

property e:4j6d-yzce t:meta.view.tableauthor v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:roleName=administrator v:displayName=cms

property e:4j6d-yzce t:meta.view.metadata.custom_fields.common_core v:Publisher="Centers for Medicare & Medicaid Services (CMS)" v:Contact_Email=HospitalCompare@hsag.com v:Contact_Name=CMS v:Bureau_Code=009:38 v:Program_Code=009:078
```

## Top Records

```ls
| measure_name                                                                                                   | measure_id                                  | measure_start_quarter | measure_start_date  | measure_end_quarter | measure_end_date    | 
| ============================================================================================================== | =========================================== | ===================== | =================== | =================== | =================== | 
| ACS Participation data                                                                                         | ACS_REGISTRY                                | 1Q2015                | 2015-01-01T00:00:00 | 4Q2015              | 2015-12-31T00:00:00 | 
| Fibrinolytic Therapy Received Within 30 Minutes of Hospital Arrival                                            | AMI_7a_HVBP_Baseline                        | 1Q2013                | 2013-01-01T00:00:00 | 4Q2013              | 2013-12-31T00:00:00 | 
| Fibrinolytic Therapy Received Within 30 Minutes of Hospital Arrival                                            | AMI_7a_HVBP_Performance                     | 1Q2015                | 2015-01-01T00:00:00 | 4Q2015              | 2015-12-31T00:00:00 | 
| Combined SSI                                                                                                   | Combined_SSI_Measure_Score                  | 1Q2013                | 2013-01-01T00:00:00 | 4Q2013              | 2013-12-31T00:00:00 | 
| Combined SSI                                                                                                   | Combined_SSI_Measure_Score_HVBP_Performance | 1Q2015                | 2015-01-01T00:00:00 | 4Q2015              | 2015-12-31T00:00:00 | 
| Complication Rate Following Elective Primary Total Hip Arthroplasty (THA) and/or Total Knee Arthroplasty (TKA) | COMP_HIP_KNEE                               | 2Q2012                | 2012-04-01T00:00:00 | 1Q2015              | 2015-03-31T00:00:00 | 
| Communication with Nurses                                                                                      | Composite 1 Q1 to Q3                        | 2Q2015                | 2015-04-01T00:00:00 | 1Q2016              | 2016-03-31T00:00:00 | 
| Communication with Doctors                                                                                     | Composite 2 Q5 to Q7                        | 2Q2015                | 2015-04-01T00:00:00 | 1Q2016              | 2016-03-31T00:00:00 | 
| Responsiveness of Hospital Staff                                                                               | Composite 3 Q4 & Q11                        | 2Q2015                | 2015-04-01T00:00:00 | 1Q2016              | 2016-03-31T00:00:00 | 
| Pain Management                                                                                                | Composite 4 Q13 & Q14                       | 2Q2015                | 2015-04-01T00:00:00 | 1Q2016              | 2016-03-31T00:00:00 | 
```