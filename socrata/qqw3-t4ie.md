# Readmissions and Deaths - National

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/readmissions-and-deaths-national) |
| Metadata | [Link](https://data.medicare.gov/api/views/qqw3-t4ie) |
| Data: JSON | [100 Rows](https://data.medicare.gov/api/views/qqw3-t4ie/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicare.gov/api/views/qqw3-t4ie/rows.csv?max_rows=100) |
| Host | data.medicare.gov |
| Id | qqw3-t4ie |
| Name | Readmissions and Deaths - National |
| Category | Hospital Compare |
| Tags | hospital compare, readmissions and death |
| Created | 2015-05-31T03:37:11Z |
| Publication Date | 2016-12-19T02:14:55Z |

## Description

Readmissions and Deaths measures - national data. This data set includes national-level data for 30-day death and readmission measures.

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                        | Data Type     | Render Type   |
| ======== | ============== | =========================== | =========================== | ============= | ============= |
| Yes      | series tag     | measure_name                | Measure Name                | text          | text          |
| Yes      | series tag     | measure_id                  | Measure ID                  | text          | text          |
| Yes      | numeric metric | national_rate               | National Rate               | number        | number        |
| Yes      | numeric metric | number_of_hospitals_worse   | Number of Hospitals Worse   | number        | number        |
| Yes      | numeric metric | number_of_hospitals_same    | Number of Hospitals Same    | number        | number        |
| Yes      | numeric metric | number_of_hospitals_better  | Number of Hospitals Better  | number        | number        |
| Yes      | numeric metric | number_of_hospitals_too_few | Number of Hospitals Too Few | number        | number        |
| No       |                | footnote                    | Footnote                    | text          | text          |
| Yes      | time           | measure_start_date          | Measure Start Date          | calendar_date | calendar_date |
| No       |                | measure_end_date            | Measure End Date            | calendar_date | calendar_date |
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
series e:qqw3-t4ie d:2012-07-01T00:00:00.000Z t:measure_id=MORT_30_AMI t:measure_name="Acute Myocardial Infarction (AMI) 30-Day Mortality Rate" m:number_of_hospitals_same=2375 m:number_of_hospitals_better=57 m:national_rate=14.1 m:number_of_hospitals_too_few=1909 m:number_of_hospitals_worse=24

series e:qqw3-t4ie d:2012-07-01T00:00:00.000Z t:measure_id=MORT_30_HF t:measure_name="Heart failure (HF) 30-Day Mortality Rate" m:number_of_hospitals_same=3510 m:number_of_hospitals_better=168 m:national_rate=12.1 m:number_of_hospitals_too_few=873 m:number_of_hospitals_worse=89

series e:qqw3-t4ie d:2012-07-01T00:00:00.000Z t:measure_id=MORT_30_PN t:measure_name="Pneumonia (PN) 30-Day Mortality Rate" m:number_of_hospitals_same=3783 m:number_of_hospitals_better=252 m:national_rate=16.3 m:number_of_hospitals_too_few=387 m:number_of_hospitals_worse=267
```

## Meta Commands

```ls
metric m:national_rate p:float l:"National Rate" t:dataTypeName=number

metric m:number_of_hospitals_worse p:integer l:"Number of Hospitals Worse" t:dataTypeName=number

metric m:number_of_hospitals_same p:integer l:"Number of Hospitals Same" t:dataTypeName=number

metric m:number_of_hospitals_better p:integer l:"Number of Hospitals Better" t:dataTypeName=number

metric m:number_of_hospitals_too_few p:integer l:"Number of Hospitals Too Few" t:dataTypeName=number

entity e:qqw3-t4ie l:"Readmissions and Deaths - National" t:url=https://data.medicare.gov/api/views/qqw3-t4ie

property e:qqw3-t4ie t:meta.view v:id=qqw3-t4ie v:category="Hospital Compare" v:averageRating=0 v:name="Readmissions and Deaths - National"

property e:qqw3-t4ie t:meta.view.owner v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:displayName=cms

property e:qqw3-t4ie t:meta.view.tableauthor v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:roleName=administrator v:displayName=cms

property e:qqw3-t4ie t:meta.view.metadata.custom_fields.common_core v:Publisher="Centers for Medicare & Medicaid Services (CMS)" v:Contact_Email=HospitalCompare@hsag.com v:Contact_Name=CMS v:Bureau_Code=009:38 v:Program_Code=009:078
```

## Top Records

```ls
| measure_name                                                                  | measure_id         | national_rate | number_of_hospitals_worse | number_of_hospitals_same | number_of_hospitals_better | number_of_hospitals_too_few | footnote | measure_start_date  | measure_end_date    | 
| ============================================================================= | ================== | ============= | ========================= | ======================== | ========================== | =========================== | ======== | =================== | =================== | 
| Acute Myocardial Infarction (AMI) 30-Day Mortality Rate                       | MORT_30_AMI        | 14.1          | 24                        | 2375                     | 57                         | 1909                        |          | 2012-07-01T00:00:00 | 2015-06-30T00:00:00 | 
| Heart failure (HF) 30-Day Mortality Rate                                      | MORT_30_HF         | 12.1          | 89                        | 3510                     | 168                        | 873                         |          | 2012-07-01T00:00:00 | 2015-06-30T00:00:00 | 
| Pneumonia (PN) 30-Day Mortality Rate                                          | MORT_30_PN         | 16.3          | 267                       | 3783                     | 252                        | 387                         |          | 2012-07-01T00:00:00 | 2015-06-30T00:00:00 | 
| Acute Myocardial Infarction (AMI) 30-Day Readmission Rate                     | READM_30_AMI       | 16.8          | 26                        | 2181                     | 12                         | 2008                        |          | 2012-07-01T00:00:00 | 2015-06-30T00:00:00 | 
| Heart failure (HF) 30-Day Readmission Rate                                    | READM_30_HF        | 21.9          | 129                       | 3590                     | 89                         | 831                         |          | 2012-07-01T00:00:00 | 2015-06-30T00:00:00 | 
| Pneumonia (PN) 30-Day Readmission Rate                                        | READM_30_PN        | 17.1          | 186                       | 4044                     | 79                         | 383                         |          | 2012-07-01T00:00:00 | 2015-06-30T00:00:00 | 
| Rate of readmission after hip/knee replacement                                | READM_30_HIP_KNEE  | 4.6           | 31                        | 2740                     | 48                         | 654                         |          | 2012-07-01T00:00:00 | 2015-06-30T00:00:00 | 
| Rate of readmission after discharge from hospital (hospital-wide)             | READM_30_HOSP_WIDE | 15.6          | 283                       | 4074                     | 214                        | 175                         |          | 2014-07-01T00:00:00 | 2015-06-30T00:00:00 | 
| Rate of readmission for chronic obstructive pulmonary disease (COPD) patients | READM_30_COPD      | 20.0          | 82                        | 3698                     | 30                         | 835                         |          | 2012-07-01T00:00:00 | 2015-06-30T00:00:00 | 
| Rate of readmission for stroke patients                                       | READM_30_STK       | 12.5          | 50                        | 2634                     | 7                          | 1722                        |          | 2012-07-01T00:00:00 | 2015-06-30T00:00:00 | 
```