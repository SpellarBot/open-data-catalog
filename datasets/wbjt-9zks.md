# Physician Compare 2014 Individual EP Public Reporting - Clinical Quality Of Care

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/physician-compare-2014-individual-ep-public-reporting-clinical-quality-of-care) |
| Metadata | [Link](https://data.medicare.gov/api/views/wbjt-9zks) |
| Data: JSON | [100 Rows](https://data.medicare.gov/api/views/wbjt-9zks/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicare.gov/api/views/wbjt-9zks/rows.csv?max_rows=100) |
| Host | data.medicare.gov |
| Id | wbjt-9zks |
| Name | Physician Compare 2014 Individual EP Public Reporting - Clinical Quality Of Care |
| Category | Physician Compare |
| Tags | physician compare, physician quality reporting system |
| Created | 2016-06-24T20:27:05Z |
| Publication Date | 2016-06-27T12:57:11Z |

## Description

Individual EP Physician Quality Reporting System (PQRS) measures performance rates reported via claims.

## Columns

```ls
| Included | Schema Type    | Field Name | Name                                                                         | Data Type | Render Type |
| ======== | ============== | ========== | ============================================================================ | ========= | =========== |
| Yes      | numeric metric | npi        | NPI                                                                          | number    | number      |
| Yes      | series tag     | ind_pac_id | PAC ID                                                                       | text      | text        |
| Yes      | series tag     | lst_nm     | Last Name                                                                    | text      | text        |
| Yes      | series tag     | fst_nm     | First Name                                                                   | text      | text        |
| Yes      | numeric metric | ep_134     | Screening for depression and developing a follow-up plan.                    | number    | number      |
| Yes      | numeric metric | ep_226     | Screening for tobacco use and providing help quitting when needed.           | number    | number      |
| Yes      | numeric metric | ep_128     | Screening for an unhealthy body weight and developing a follow-up plan.      | number    | number      |
| Yes      | numeric metric | ep_317     | Screening for high blood pressure and developing a follow-up plan.           | number    | number      |
| Yes      | numeric metric | ep_46      | Comparing new and old medications.                                           | number    | number      |
| Yes      | numeric metric | ep_204     | Using aspirin or prescription medicines to reduce heart attacks and strokes. | number    | number      |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:wbjt-9zks d:2014-01-01T00:00:00.000Z t:lst_nm=FERUCCI t:ind_pac_id=0042100612 t:fst_nm=PAUL m:npi=1578594750 m:ep_226=86

series e:wbjt-9zks d:2014-01-01T00:00:00.000Z t:lst_nm=CHIARO t:ind_pac_id=0042100760 t:fst_nm=JOHN m:npi=1508863630 m:ep_226=100 m:ep_128=96

series e:wbjt-9zks d:2014-01-01T00:00:00.000Z t:lst_nm=TANTRA t:ind_pac_id=0042101214 t:fst_nm=ZUBIN m:npi=1417040411 m:ep_128=12
```

## Meta Commands

```ls
metric m:npi p:integer l:NPI d:"Unique professional ID assigned by NPPES" t:dataTypeName=number

metric m:ep_134 p:integer l:"Screening for depression and developing a follow-up plan." d:"Depression is a leading cause of disability and suffering. Managing depression can lead to better coping and outcomes for patients.To give this health care professional a score, Medicare looked at the percentage of this health care professional?s patients who were screened for depression and if they have depression, got a plan outlining next steps." t:dataTypeName=number

metric m:ep_226 p:integer l:"Screening for tobacco use and providing help quitting when needed." d:"Quitting tobacco lowers a patient?s chance of getting heart and lung diseases. To give this health care professional a score, Medicare looked at the percentage of this health care professional?s patients that were asked at least once in the last two years if they use tobacco. If patients use tobacco, this health care professional spoke with them about ways to help them quit using tobacco." t:dataTypeName=number

metric m:ep_128 p:integer l:"Screening for an unhealthy body weight and developing a follow-up plan." d:"When patients have a higher or lower than normal weight for their body type and height, they are at risk for certain health conditions such as heart disease, diabetes, or malnourishment. To give this health care professional a score, Medicare looked at the percentage of this health care professional?s patients who were screened at least once in the last six months. If the patient?s weight was higher or lower than normal for his or her body type and height, they received a plan of recommended next steps." t:dataTypeName=number

metric m:ep_317 p:integer l:"Screening for high blood pressure and developing a follow-up plan." d:"High blood pressure can cause heart disease and stroke. To give this health care professional a score, Medicare looked at the percentage of this health care professional?s patients who had their blood pressure checked. If the patient had high blood pressure, they received a plan of recommended next steps." t:dataTypeName=number

metric m:ep_46 p:integer l:"Comparing new and old medications." d:"Comparing medications is important because it can help avoid medical errors. To give this health care professional a score, Medicare looked at the percentage of this health care professional?s patients that had their medications compared within 30 days after coming home from an inpatient facility." t:dataTypeName=number

metric m:ep_204 p:integer l:"Using aspirin or prescription medicines to reduce heart attacks and strokes." d:"Cardiovascular disease, which is a disease of the arteries and veins, can lead to a heart attack or stroke. Aspirin has been shown to be a safe, easy, and low cost way of reducing heart attacks and stroke. To give this health care professional a score, Medicare looked at the percentage of this health care professional?s patients who have cardiovascular disease and are taking aspirin or prescription medicines to reduce their risk of heart attack or stroke." t:dataTypeName=number

entity e:wbjt-9zks l:"Physician Compare 2014 Individual EP Public Reporting - Clinical Quality Of Care" t:url=https://data.medicare.gov/api/views/wbjt-9zks

property e:wbjt-9zks t:meta.view v:id=wbjt-9zks v:category="Physician Compare" v:averageRating=0 v:name="Physician Compare 2014 Individual EP Public Reporting - Clinical Quality Of Care"

property e:wbjt-9zks t:meta.view.owner v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:displayName=cms

property e:wbjt-9zks t:meta.view.tableauthor v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:roleName=administrator v:displayName=cms

property e:wbjt-9zks t:meta.view.metadata.custom_fields.common_core v:Publisher="Centers for Medicare & Medicaid Services (CMS)" v:Contact_Email=PhysicianCompare@westat.com v:Contact_Name=CMS v:Bureau_Code=009:38 v:Program_Code=009:078
```

## Top Records

```ls
| npi        | ind_pac_id | lst_nm     | fst_nm  | ep_134 | ep_226 | ep_128 | ep_317 | ep_46 | ep_204 | 
| ========== | ========== | ========== | ======= | ====== | ====== | ====== | ====== | ===== | ====== | 
| 1578594750 | 0042100612 | FERUCCI    | PAUL    |        | 86     |        |        |       |        | 
| 1508863630 | 0042100760 | CHIARO     | JOHN    |        | 100    | 96     |        |       |        | 
| 1417040411 | 0042101214 | TANTRA     | ZUBIN   |        |        | 12     |        |       |        | 
| 1265464077 | 0042102154 | SIMENTAL   | ALFRED  |        | 94     | 45     |        |       |        | 
| 1992762215 | 0042102246 | SEIFF      | MICHAEL |        | 100    | 100    |        |       |        | 
| 1255333167 | 0042102543 | GIZE       | GARY    |        | 100    |        |        |       |        | 
| 1447285739 | 0042103442 | ALONSO     | OSCAR   |        | 100    | 100    |        |       |        | 
| 1285715409 | 0042104507 | SAKHAROVA  | ALLA    |        |        | 100    | 100    |       |        | 
| 1689755910 | 0042104796 | HENDRIKSON | ROBERT  |        | 94     | 24     |        |       |        | 
| 1710962543 | 0042105421 | RAJAN      | SUJATHA |        | 100    | 96     |        |       |        | 
```