# Physician Compare 2014 Group Practice Public Reporting - Clinical Quality Of Care

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/physician-compare-2014-group-practice-public-reporting-clinical-quality-of-care) |
| Metadata | [Link](https://data.medicare.gov/api/views/yfyj-vj3w) |
| Data: JSON | [100 Rows](https://data.medicare.gov/api/views/yfyj-vj3w/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicare.gov/api/views/yfyj-vj3w/rows.csv?max_rows=100) |
| Host | data.medicare.gov |
| Id | yfyj-vj3w |
| Name | Physician Compare 2014 Group Practice Public Reporting - Clinical Quality Of Care |
| Category | Physician Compare |
| Tags | physician compare, physician quality reporting system |
| Created | 2016-06-24T20:22:12Z |
| Publication Date | 2016-06-27T13:42:45Z |

## Description

Physician Quality Reporting System (PQRS) measures performance rates reported by group practices via the Web Interface.

## Columns

```ls
| Included | Schema Type    | Field Name   | Name                                                                                                                                  | Data Type | Render Type |
| ======== | ============== | ============ | ===================================================================================================================================== | ========= | =========== |
| Yes      | series tag     | org_nm       | Organization legal name or 'doing business as' name                                                                                   | text      | text        |
| Yes      | series tag     | org_pac_id   | Group Practice PAC ID                                                                                                                 | text      | text        |
| No       |                | st           | State                                                                                                                                 | text      | text        |
| Yes      | series tag     | pqrs         | Participating in PQRS                                                                                                                 | text      | text        |
| Yes      | numeric metric | grp_110      | Getting a flu shot during flu season.                                                                                                 | number    | number      |
| Yes      | numeric metric | fn_grp_110   | Footnote for measure 110                                                                                                              | number    | number      |
| Yes      | numeric metric | grp_111      | Making sure older adults have gotten a pneumonia vaccine.                                                                             | number    | number      |
| Yes      | numeric metric | fn_grp_111   | Footnote for measure 111                                                                                                              | number    | number      |
| Yes      | numeric metric | grp_134      | Screening for depression and developing a follow-up plan.                                                                             | number    | number      |
| Yes      | numeric metric | fn_grp_134   | Footnote for measure 134                                                                                                              | number    | number      |
| Yes      | numeric metric | grp_226      | Screening for tobacco use and providing help quitting when needed.                                                                    | number    | number      |
| Yes      | numeric metric | fn_grp_226   | Footnote for measure 226                                                                                                              | number    | number      |
| Yes      | numeric metric | grp_128      | Screening for an unhealthy body weight and developing a follow-up plan.                                                               | number    | number      |
| Yes      | numeric metric | fn_grp_128   | Footnote for measure 128                                                                                                              | number    | number      |
| Yes      | numeric metric | grp_317      | Screening for high blood pressure and developing a follow-up plan.                                                                    | number    | number      |
| Yes      | numeric metric | fn_grp_317   | Footnote for measure 317                                                                                                              | number    | number      |
| Yes      | numeric metric | grp_112      | Screening for breast cancer.                                                                                                          | number    | number      |
| Yes      | numeric metric | fn_grp_112   | Footnote for measure 112                                                                                                              | number    | number      |
| Yes      | numeric metric | grp_113      | Screening for colorectal (colon or rectum) cancer.                                                                                    | number    | number      |
| Yes      | numeric metric | fn_grp_113   | Footnote for measure 113                                                                                                              | number    | number      |
| Yes      | numeric metric | grp_46       | Comparing new and old medications.                                                                                                    | number    | number      |
| Yes      | numeric metric | fn_grp_46    | Footnote for measure 46                                                                                                               | number    | number      |
| Yes      | numeric metric | grp_dm_13    | Controlling blood pressure in patients with diabetes.                                                                                 | number    | number      |
| Yes      | numeric metric | fn_grp_dm_13 | Footnote for measure DM 13                                                                                                            | number    | number      |
| Yes      | numeric metric | grp_dm_16    | Using aspirin or prescription medicines to reduce heart attacks and strokes in patients with diabetes.                                | number    | number      |
| Yes      | numeric metric | fn_grp_dm_16 | Footnote for measure DM 16                                                                                                            | number    | number      |
| Yes      | numeric metric | grp_204      | Using aspirin or prescription medicines to reduce heart attacks and strokes.                                                          | number    | number      |
| Yes      | numeric metric | fn_grp_204   | Footnote for measure 204                                                                                                              | number    | number      |
| Yes      | numeric metric | grp_8        | Patients with heart failure and a weakened pumping chamber of the heart who got a beta blocker.                                       | number    | number      |
| Yes      | numeric metric | fn_grp_8     | Footnote for measure 8                                                                                                                | number    | number      |
| Yes      | numeric metric | grp_118      | Prescribing medicine to improve the pumping action of the heart in patients who have both heart disease and certain other conditions. | number    | number      |
| Yes      | numeric metric | fn_grp_118   | Footnote for measure 118                                                                                                              | number    | number      |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = st
```

## Data Commands

```ls
series e:yfyj-vj3w d:2014-01-01T00:00:00.000Z t:org_pac_id=0042105678 t:org_nm="HERITAGE VALLEY MEDICAL GROUP INC" t:pqrs=Y m:grp_dm_16=82 m:grp_317=26 m:grp_dm_13=65 m:grp_118=78 m:grp_46=84 m:grp_134=1 m:grp_128=40 m:grp_204=78 m:grp_113=27 m:grp_112=50 m:grp_111=59 m:grp_226=61 m:grp_110=59 m:fn_grp_8=1

series e:yfyj-vj3w d:2014-01-01T00:00:00.000Z t:org_pac_id=0042111981 t:org_nm="MAYO CLINIC HEALTH SYSTEM-OWATONNA" t:pqrs=Y m:grp_dm_16=100 m:grp_317=58 m:grp_8=87 m:grp_dm_13=90 m:grp_118=88 m:grp_46=90 m:grp_134=10 m:grp_128=46 m:grp_204=96 m:grp_113=80 m:grp_112=79 m:grp_111=92 m:grp_226=97 m:grp_110=83

series e:yfyj-vj3w d:2014-01-01T00:00:00.000Z t:org_pac_id=0042128548 t:org_nm="UNIVERSITY OF TEXAS HEALTH SCIENCE CENTER AT SAN ANTONIO" t:pqrs=Y m:grp_dm_16=85 m:grp_317=49 m:grp_8=98 m:grp_dm_13=66 m:grp_118=83 m:grp_46=54 m:grp_134=55 m:grp_128=73 m:grp_204=86 m:grp_113=59 m:grp_112=65 m:grp_111=75 m:grp_226=96 m:grp_110=46
```

## Meta Commands

```ls
metric m:grp_110 p:integer l:"Getting a flu shot during flu season." d:"Getting a flu shot during flu season can help prevent the flu and the problems the flu causes.To give this group practice a score, Medicare looked at the percentage of this group practice?s patients who could get the flu shot and either got one from this group practice or from someone else during flu season." t:dataTypeName=number

metric m:fn_grp_110 p:integer l:"Footnote for measure 110" d:"1- Data are suppressed due to small sample size. 2- No cases met the criteria for this measure. 3- Data were not satisfactorily reported." t:dataTypeName=number

metric m:grp_111 p:integer l:"Making sure older adults have gotten a pneumonia vaccine." d:"Pneumonia is a common cause of illness and death in older adults and people with certain health conditions. A pneumonia vaccine helps prevent pneumonia and complications from pneumonia.To give this group practice a score, Medicare looked at the percentage of this group practice?s patients who have ever gotten a pneumonia vaccine." t:dataTypeName=number

metric m:fn_grp_111 p:integer l:"Footnote for measure 111" d:"1- Data are suppressed due to small sample size. 2- No cases met the criteria for this measure. 3- Data were not satisfactorily reported." t:dataTypeName=number

metric m:grp_134 p:integer l:"Screening for depression and developing a follow-up plan." d:"Depression is a leading cause of disability and suffering. Managing depression can lead to better coping and outcomes for patients.To give this group practice a score, Medicare looked at the percentage of this group practice?s patients who were screened for depression and, if they have depression, got a plan outlining next steps." t:dataTypeName=number

metric m:fn_grp_134 p:integer l:"Footnote for measure 134" d:"1- Data are suppressed due to small sample size. 2- No cases met the criteria for this measure. 3- Data were not satisfactorily reported." t:dataTypeName=number

metric m:grp_226 p:integer l:"Screening for tobacco use and providing help quitting when needed." d:"Quitting tobacco lowers a patient?s chance of getting heart and lung diseases. To give this group practice a score, Medicare looked at the percentage of this group practice?s patients that were asked at least once in the last two years if they use tobacco. If patients use tobacco, the group practice worked with them on ways to help them quit using tobacco." t:dataTypeName=number

metric m:fn_grp_226 p:integer l:"Footnote for measure 226" d:"1- Data are suppressed due to small sample size. 2- No cases met the criteria for this measure. 3- Data were not satisfactorily reported." t:dataTypeName=number

metric m:grp_128 p:integer l:"Screening for an unhealthy body weight and developing a follow-up plan." d:"When patients have a higher or lower than normal weight for their body type and height, they are at risk for certain health conditions such as heart disease, diabetes, or malnourishment. To give this group practice a score, Medicare looked at the percentage of this group practice?s patients who were screened at least once in the last six months. If the patient?s weight was higher or lower than normal for his/her body type and height, he/she received a plan of recommended next steps." t:dataTypeName=number

metric m:fn_grp_128 p:integer l:"Footnote for measure 128" d:"1- Data are suppressed due to small sample size. 2- No cases met the criteria for this measure. 3- Data were not satisfactorily reported." t:dataTypeName=number

metric m:grp_317 p:integer l:"Screening for high blood pressure and developing a follow-up plan." d:"High blood pressure can cause heart disease and stroke. To give this group practice a score, Medicare looked at the percentage of this group practice?s patients who had their blood pressure checked. If the patient had high blood pressure, they received a plan of recommended next steps." t:dataTypeName=number

metric m:fn_grp_317 p:integer l:"Footnote for measure 317" d:"1- Data are suppressed due to small sample size. 2- No cases met the criteria for this measure. 3- Data were not satisfactorily reported." t:dataTypeName=number

metric m:grp_112 p:integer l:"Screening for breast cancer." d:"Breast cancer is a leading cause of death in women. Mammograms can help find breast cancer early, when treatment works best. All women 50 years old and older should get a mammogram at least every two years. To give this group practice a score, Medicare looked at the percentage of this group practice?s female patients that got a mammogram within the past 27 months." t:dataTypeName=number

metric m:fn_grp_112 p:integer l:"Footnote for measure 112" d:"1- Data are suppressed due to small sample size. 2- No cases met the criteria for this measure. 3- Data were not satisfactorily reported." t:dataTypeName=number

metric m:grp_113 p:integer l:"Screening for colorectal (colon or rectum) cancer." d:"Colorectal cancer is a leading cause of cancer death in the United States. All patients 50 years old and older should be checked for colorectal cancer. The patient?s health care professional will recommend the most appropriate test(s) based on the patient?s age, risk factors, and current conditions. To give this group practice a score, Medicare looked at the percentage of this group practice?s patients that got tested for colorectal cancer." t:dataTypeName=number

metric m:fn_grp_113 p:integer l:"Footnote for measure 113" d:"1- Data are suppressed due to small sample size. 2- No cases met the criteria for this measure. 3- Data were not satisfactorily reported." t:dataTypeName=number

metric m:grp_46 p:integer l:"Comparing new and old medications." d:"Comparing medications is important because it can help avoid medical errors. To give this group practice a score, Medicare looked at the percentage of this group practice?s patients that had their medications compared within 30 days after coming home from an inpatient facility." t:dataTypeName=number

metric m:fn_grp_46 p:integer l:"Footnote for measure 46" d:"1- Data are suppressed due to small sample size. 2- No cases met the criteria for this measure. 3- Data were not satisfactorily reported." t:dataTypeName=number

metric m:grp_dm_13 p:integer l:"Controlling blood pressure in patients with diabetes." d:"Most people with diabetes have other conditions such as high blood pressure. High blood pressure can cause heart disease and stroke. It is important to control high blood pressure to avoid additional health problems. To give this group practice a score, Medicare looked at the percentage of this group practice?s patients with diabetes whose most recent blood pressure was at a healthy level (less than 140 over 90)." t:dataTypeName=number

metric m:fn_grp_dm_13 p:integer l:"Footnote for measure DM 13" d:"1- Data are suppressed due to small sample size. 2- No cases met the criteria for this measure. 3- Data were not satisfactorily reported." t:dataTypeName=number

metric m:grp_dm_16 p:integer l:"Using aspirin or prescription medicines to reduce heart attacks and strokes in patients with diabetes." d:"Most people with diabetes have other conditions, such as heart disease. Heart disease can lead to a heart attack or stroke. Aspirin has been shown to be a safe, easy, and low cost way of reducing heart attacks and stroke. To give this group practice a score, Medicare looked at the percentage of this group practice?s patients who have both diabetes and heart disease and are taking aspirin or prescription drugs daily to reduce their risk of heart attack or stroke unless they have a medical reason for not taking these medicines." t:dataTypeName=number

metric m:fn_grp_dm_16 p:integer l:"Footnote for measure DM 16" d:"1- Data are suppressed due to small sample size. 2- No cases met the criteria for this measure. 3- Data were not satisfactorily reported." t:dataTypeName=number

metric m:grp_204 p:integer l:"Using aspirin or prescription medicines to reduce heart attacks and strokes." d:"Cardiovascular disease, which is a disease of the arteries and veins, can lead to a heart attack or stroke. Aspirin has been shown to be a safe, easy, and low cost way of reducing heart attacks and stroke. To give this group practice a score, Medicare looked at the percentage of this group practice?s patients who have cardiovascular disease and are taking aspirin or prescription medicines to reduce their risk of heart attack or stroke." t:dataTypeName=number

metric m:fn_grp_204 p:integer l:"Footnote for measure 204" d:"1- Data are suppressed due to small sample size. 2- No cases met the criteria for this measure. 3- Data were not satisfactorily reported." t:dataTypeName=number

metric m:grp_8 p:integer l:"Patients with heart failure and a weakened pumping chamber of the heart who got a beta blocker." d:"The left ventricle is the main pumping chamber of the heart. When patients have a weakened left ventricle, or LVSD, treatment recommendations say health care professionals should prescribe a type of medication called a ?beta-blocker.? Beta-blockers slow the heart rate and help blood vessels open up, which lets the heart pump blood more easily. To give this group practice a score, Medicare looked at the percentage of this group practice?s patients with heart failure and a weakened left ventricle who got a beta-blocker." t:dataTypeName=number

metric m:fn_grp_8 p:integer l:"Footnote for measure 8" d:"1- Data are suppressed due to small sample size. 2- No cases met the criteria for this measure. 3- Data were not satisfactorily reported." t:dataTypeName=number

metric m:grp_118 p:integer l:"Prescribing medicine to improve the pumping action of the heart in patients who have both heart disease and certain other conditions." d:"If patients with heart disease also have diabetes or if the main pumping chamber of their heart (the left ventricle) is not pumping well, treatment recommendations say that doctors should prescribe an ACE inhibitor or ARB drug. (""ACE"" means ""Angiotensin-Converting Enzyme"" and ""ARB"" means ""Angiotensin Receptor Blocker."") These types of medication help lower blood pressure and make it easier for the heart to pump blood.To give this group practice a score, Medicare looked at this group practice's patients with heart disease who also have diabetes or a weakened left ventricle. The score is based on the percentage of these patients who were prescribed medicine to improve the pumping action of the heart." t:dataTypeName=number

metric m:fn_grp_118 p:integer l:"Footnote for measure 118" d:"1- Data are suppressed due to small sample size. 2- No cases met the criteria for this measure. 3- Data were not satisfactorily reported." t:dataTypeName=number

entity e:yfyj-vj3w l:"Physician Compare 2014 Group Practice Public Reporting - Clinical Quality Of Care" t:url=https://data.medicare.gov/api/views/yfyj-vj3w

property e:yfyj-vj3w t:meta.view v:id=yfyj-vj3w v:category="Physician Compare" v:averageRating=0 v:name="Physician Compare 2014 Group Practice Public Reporting - Clinical Quality Of Care"

property e:yfyj-vj3w t:meta.view.owner v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:displayName=cms

property e:yfyj-vj3w t:meta.view.tableauthor v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:roleName=administrator v:displayName=cms

property e:yfyj-vj3w t:meta.view.metadata.custom_fields.common_core v:Publisher="Centers for Medicare & Medicaid Services (CMS)" v:Contact_Email=PhysicianCompare@westat.com v:Contact_Name=CMS v:Bureau_Code=009:38 v:Program_Code=009:078
```

## Top Records

```ls
| org_nm                                              | org_pac_id | st | pqrs | grp_110 | fn_grp_110 | grp_111 | fn_grp_111 | grp_134 | fn_grp_134 | grp_226 | fn_grp_226 | grp_128 | fn_grp_128 | grp_317 | fn_grp_317 | grp_112 | fn_grp_112 | grp_113 | fn_grp_113 | grp_46 | fn_grp_46 | grp_dm_13 | fn_grp_dm_13 | grp_dm_16 | fn_grp_dm_16 | grp_204 | fn_grp_204 | grp_8 | fn_grp_8 | grp_118 | fn_grp_118 | 
| =================================================== | ========== | == | ==== | ======= | ========== | ======= | ========== | ======= | ========== | ======= | ========== | ======= | ========== | ======= | ========== | ======= | ========== | ======= | ========== | ====== | ========= | ========= | ============ | ========= | ============ | ======= | ========== | ===== | ======== | ======= | ========== | 
| DERMATOLOGY and SURGERY ASSOCIATES, LLP             | 0042101818 | NY | Y    |         |            |         |            |         |            |         |            |         |            |         |            |         |            |         |            |        |           |           |              |           |              |         |            |       |          |         |            | 
| COUNTY OF CLAY                                      | 0042101982 | IL | Y    |         |            |         |            |         |            |         |            |         |            |         |            |         |            |         |            |        |           |           |              |           |              |         |            |       |          |         |            | 
| NORTHWEST FAMILY PHYSICIANS PA                      | 0042102956 | MN | Y    |         |            |         |            |         |            |         |            |         |            |         |            |         |            |         |            |        |           |           |              |           |              |         |            |       |          |         |            | 
| HERITAGE VALLEY MEDICAL GROUP INC                   | 0042105678 | PA | Y    | 59      |            | 59      |            | 1       |            | 61      |            | 40      |            | 26      |            | 50      |            | 27      |            | 84     |           | 65        |              | 82        |              | 78      |            |       | 1        | 78      |            | 
| ST MARYS REGIONAL MEDICAL CENTER                    | 0042107120 | ME | Y    |         |            |         |            |         |            |         |            |         |            |         |            |         |            |         |            |        |           |           |              |           |              |         |            |       |          |         |            | 
| EDWARD HOSPITAL                                     | 0042108110 | IL | Y    |         |            |         |            |         |            |         |            |         |            |         |            |         |            |         |            |        |           |           |              |           |              |         |            |       |          |         |            | 
| UNIVERSITY OF MARYLAND ORTHOPAEDIC ASSOCIATES, P.A. | 0042108722 | MD | Y    |         |            |         |            |         |            |         |            |         |            |         |            |         |            |         |            |        |           |           |              |           |              |         |            |       |          |         |            | 
| HR PHYSICIAN SERVICES                               | 0042109902 | PA | Y    |         |            |         |            |         |            |         |            |         |            |         |            |         |            |         |            |        |           |           |              |           |              |         |            |       |          |         |            | 
| MAYO CLINIC HEALTH SYSTEM-OWATONNA                  | 0042111981 | MN | Y    | 83      |            | 92      |            | 10      |            | 97      |            | 46      |            | 58      |            | 79      |            | 80      |            | 90     |           | 90        |              | 100       |              | 96      |            | 87    |          | 88      |            | 
| FLORIDA INSTITUTE FOR CARDIOVASCULAR CARE PA        | 0042112278 | FL | Y    |         |            |         |            |         |            |         |            |         |            |         |            |         |            |         |            |        |           |           |              |           |              |         |            |       |          |         |            | 
```