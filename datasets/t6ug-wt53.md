# Physician Compare 2014 Group Practice Public Reporting - Patient Experience

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/physician-compare-2014-group-practice-public-reporting-patient-experience) |
| Metadata | [Link](https://data.medicare.gov/api/views/t6ug-wt53) |
| Data: JSON | [100 Rows](https://data.medicare.gov/api/views/t6ug-wt53/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicare.gov/api/views/t6ug-wt53/rows.csv?max_rows=100) |
| Host | data.medicare.gov |
| Id | t6ug-wt53 |
| Name | Physician Compare 2014 Group Practice Public Reporting - Patient Experience |
| Category | Physician Compare |
| Tags | consumer assessment of healthcare providers and systems (cahps), physician quality reporting system, group practices. |
| Created | 2016-06-24T20:26:05Z |
| Publication Date | 2016-06-27T13:12:48Z |

## Description

Consumer Assessment of Healthcare Providers and Systems (CAHPS) for PQRS measures performance rates reported by group practices.

## Columns

```ls
| Included | Schema Type    | Field Name      | Name                                                      | Data Type | Render Type |
| ======== | ============== | =============== | ========================================================= | ========= | =========== |
| Yes      | series tag     | org_nm          | Organization legal name or 'doing business as' name       | text      | text        |
| Yes      | series tag     | org_pac_id      | Group Practice PAC ID                                     | text      | text        |
| No       |                | st              | State                                                     | text      | text        |
| Yes      | numeric metric | grp_cahps_1     | Getting timely care, appointments, and information.       | number    | number      |
| Yes      | numeric metric | fn_grp_cahps_1  | Footnote for measure CAHPS 1                              | number    | number      |
| Yes      | numeric metric | grp_cahps_2     | How well health care professionals communicate.           | number    | number      |
| Yes      | numeric metric | fn_grp_cahps_2  | Footnote for measure CAHPS 2                              | number    | number      |
| Yes      | numeric metric | grp_cahps_5     | Health promotion and education.                           | number    | number      |
| Yes      | numeric metric | fn_grp_cahps_5  | Footnote for measure CAHPS 5                              | number    | number      |
| Yes      | numeric metric | grp_cahps_3     | Patients' rating of doctors.                              | number    | number      |
| Yes      | numeric metric | fn_grp_cahps_3  | Footnote for measure CAHPS 3                              | number    | number      |
| Yes      | numeric metric | grp_cahps_8     | Courteous and helpful office staff.                       | number    | number      |
| Yes      | numeric metric | fn_grp_cahps_8  | Footnote for measure CAHPS 8                              | number    | number      |
| Yes      | numeric metric | grp_cahps_9     | Health care professionals working together for your care. | number    | number      |
| Yes      | numeric metric | fn_grp_cahps_9  | Footnote for measure CAHPS 9                              | number    | number      |
| Yes      | numeric metric | grp_cahps_10    | Between visit communication.                              | number    | number      |
| Yes      | numeric metric | fn_grp_cahps_10 | ootnote for measure CAHPS 10                              | number    | number      |
| Yes      | numeric metric | grp_cahps_12    | Attention to patient medication cost.                     | number    | number      |
| Yes      | numeric metric | fn_grp_cahps_12 | Footnote for measure CAHPS 12                             | number    | number      |
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
series e:t6ug-wt53 d:2014-01-01T00:00:00.000Z t:org_pac_id=0042105678 t:org_nm="HERITAGE VALLEY MEDICAL GROUP INC" m:grp_cahps_9=75 m:grp_cahps_8=79 m:grp_cahps_5=56 m:grp_cahps_1=61 m:grp_cahps_3=82 m:grp_cahps_12=29 m:grp_cahps_2=84 m:grp_cahps_10=53

series e:t6ug-wt53 d:2014-01-01T00:00:00.000Z t:org_pac_id=0042111981 t:org_nm="MAYO CLINIC HEALTH SYSTEM-OWATONNA" m:grp_cahps_9=75 m:grp_cahps_8=79 m:grp_cahps_5=52 m:grp_cahps_1=48 m:grp_cahps_3=78 m:grp_cahps_12=24 m:grp_cahps_2=81 m:grp_cahps_10=72

series e:t6ug-wt53 d:2014-01-01T00:00:00.000Z t:org_pac_id=0042128548 t:org_nm="UNIVERSITY OF TEXAS HEALTH SCIENCE CENTER AT SAN ANTONIO" m:grp_cahps_9=72 m:grp_cahps_8=80 m:grp_cahps_5=66 m:grp_cahps_1=53 m:grp_cahps_3=82 m:grp_cahps_12=25 m:grp_cahps_2=83 m:grp_cahps_10=63
```

## Meta Commands

```ls
metric m:grp_cahps_1 p:integer l:"Getting timely care, appointments, and information." d:"Getting care, appointments, and information when you need it is an important part of having access to health care that you deserve. To give this group practice a score, Medicare looked at the percentage of patients that said they always got timely care including: ? Getting an urgent care appointment as soon as needed. ? Getting answers to medical questions on the same day when calling during regular office hours. ? Seeing a health care professional within 15 minutes of the scheduled appointment time." t:dataTypeName=number

metric m:fn_grp_cahps_1 p:integer l:"Footnote for measure CAHPS 1" d:"4- Data are suppressed due to low reliability." t:dataTypeName=number

metric m:grp_cahps_2 p:integer l:"How well health care professionals communicate." d:"An important part of high quality health care is having a health care professional listen to you and talk to you about your health in a way that is easy for you to understand. To give this group practice a score, Medicare looked at the percentage of patients that said health care professionals always communicated well including: ? Explaining things in a way that was easy to understand. ? Listening carefully. ? Showing respect for what patients had to say. ? Spending enough time with patients." t:dataTypeName=number

metric m:fn_grp_cahps_2 p:integer l:"Footnote for measure CAHPS 2" d:"4- Data are suppressed due to low reliability." t:dataTypeName=number

metric m:grp_cahps_5 p:integer l:"Health promotion and education." d:"A part of high quality care is having your care team give you information about things you can do every day to stay healthy. This includes talking with you about how to prevent illness, keep a healthy diet, exercise, and set goals for your own health. To give this group practice a score, Medicare looked at the percentage of patients that said their care team always talked with them about what they can do to stay healthy." t:dataTypeName=number

metric m:fn_grp_cahps_5 p:integer l:"Footnote for measure CAHPS 5" d:"4- Data are suppressed due to low reliability." t:dataTypeName=number

metric m:grp_cahps_3 p:integer l:"Patients' rating of doctors." d:"To give this group practice a score, Medicare looked at the percentage of patients who gave their doctors a rating of 9 or 10 on a scale from 0 (lowest) to 10 (highest)." t:dataTypeName=number

metric m:fn_grp_cahps_3 p:integer l:"Footnote for measure CAHPS 3" d:"4- Data are suppressed due to low reliability." t:dataTypeName=number

metric m:grp_cahps_8 p:integer l:"Courteous and helpful office staff." d:"Office staff are the clerks and receptionists you talk with when you want to schedule appointments or have questions. To have a high quality patient experience, it is important that office staff help you when you need it. To give this group practice a score, Medicare looked at the percentage of patients that said office staff were always helpful, polite, and respectful." t:dataTypeName=number

metric m:fn_grp_cahps_8 p:integer l:"Footnote for measure CAHPS 8" d:"4- Data are suppressed due to low reliability." t:dataTypeName=number

metric m:grp_cahps_9 p:integer l:"Health care professionals working together for your care." d:"Care coordination involves important parts of your care like getting referrals and conducting visit follow ups. To give this group practice a score, Medicare looked at the percentage of patients that said their care was always coordinated by the practice including: ? Having medical records ready and available during visits. ? Following up after visits to give patients results of tests or x-rays. ? Managing tests, treatments, and appointments from different health care professionals." t:dataTypeName=number

metric m:fn_grp_cahps_9 p:integer l:"Footnote for measure CAHPS 9" d:"4- Data are suppressed due to low reliability." t:dataTypeName=number

metric m:grp_cahps_10 p:integer l:"Between visit communication." d:"Patients may not always remember the time of their next medical appointment. Getting reminders from the group practice is part of a high quality patient experience. To give this group practice a score, Medicare looked at the percentage of patients that said they always got reminders from the practice about scheduled appointments and about making appointments for tests or treatments." t:dataTypeName=number

metric m:fn_grp_cahps_10 p:integer l:"ootnote for measure CAHPS 10" d:"4- Data are suppressed due to low reliability." t:dataTypeName=number

metric m:grp_cahps_12 p:integer l:"Attention to patient medication cost." d:"When your health care professionals discuss medication costs with you, they can be sure that you will be able to afford to follow your care plan. To give this group practice a score, Medicare looked at the percentage of patients that said the care team always talked with them about the cost of their prescription medication." t:dataTypeName=number

metric m:fn_grp_cahps_12 p:integer l:"Footnote for measure CAHPS 12" d:"4- Data are suppressed due to low reliability." t:dataTypeName=number

entity e:t6ug-wt53 l:"Physician Compare 2014 Group Practice Public Reporting - Patient Experience" t:url=https://data.medicare.gov/api/views/t6ug-wt53

property e:t6ug-wt53 t:meta.view v:id=t6ug-wt53 v:category="Physician Compare" v:averageRating=0 v:name="Physician Compare 2014 Group Practice Public Reporting - Patient Experience"

property e:t6ug-wt53 t:meta.view.owner v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:displayName=cms

property e:t6ug-wt53 t:meta.view.tableauthor v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:roleName=administrator v:displayName=cms

property e:t6ug-wt53 t:meta.view.metadata.custom_fields.common_core v:Publisher="Centers for Medicare & Medicaid Services (CMS)" v:Contact_Email=PhysicianCompare@westat.com v:Contact_Name=CMS v:Bureau_Code=009:38 v:Program_Code=009:078
```

## Top Records

```ls
| org_nm                                                      | org_pac_id | st | grp_cahps_1 | fn_grp_cahps_1 | grp_cahps_2 | fn_grp_cahps_2 | grp_cahps_5 | fn_grp_cahps_5 | grp_cahps_3 | fn_grp_cahps_3 | grp_cahps_8 | fn_grp_cahps_8 | grp_cahps_9 | fn_grp_cahps_9 | grp_cahps_10 | fn_grp_cahps_10 | grp_cahps_12 | fn_grp_cahps_12 | 
| =========================================================== | ========== | == | =========== | ============== | =========== | ============== | =========== | ============== | =========== | ============== | =========== | ============== | =========== | ============== | ============ | =============== | ============ | =============== | 
| HERITAGE VALLEY MEDICAL GROUP INC                           | 0042105678 | PA | 61          |                | 84          |                | 56          |                | 82          |                | 79          |                | 75          |                | 53           |                 | 29           |                 | 
| MAYO CLINIC HEALTH SYSTEM-OWATONNA                          | 0042111981 | MN | 48          |                | 81          |                | 52          |                | 78          |                | 79          |                | 75          |                | 72           |                 | 24           |                 | 
| UNIVERSITY OF TEXAS HEALTH SCIENCE CENTER AT SAN ANTONIO    | 0042128548 | TX | 53          |                | 83          |                | 66          |                | 82          |                | 80          |                | 72          |                | 63           |                 | 25           |                 | 
| WHITE RIVER HEALTH SYSTEM INC                               | 0143134270 | AR | 67          |                | 88          |                | 52          |                | 81          |                | 86          |                | 73          |                |              | 4               |              | 4               | 
| UNITY HEALTHCARE LLC                                        | 0244123362 | IN | 67          |                | 86          |                | 58          |                | 78          |                | 85          |                | 77          |                | 51           |                 | 30           |                 | 
| NETWORK HEALTH SYSTEM, INC.                                 | 0244142420 | WI | 56          |                | 78          |                | 60          |                | 76          |                | 81          |                | 76          |                | 59           |                 | 24           |                 | 
| MEDICAL SPECIALISTS OF THE PALM BEACHES INC                 | 0244143758 | FL | 64          |                | 86          |                | 71          |                | 81          |                | 78          |                | 77          |                | 64           |                 | 30           |                 | 
| SANFORD CLINIC                                              | 0244143824 | SD | 62          |                | 79          |                | 59          |                | 76          |                | 85          |                | 80          |                | 64           |                 | 24           |                 | 
| SUTTER WEST BAY MEDICAL FOUNDATION                          | 0345145025 | CA | 62          |                | 82          |                | 56          |                | 79          |                | 83          |                | 73          |                | 57           |                 | 23           |                 | 
| MAYO CLINIC HEALTH SYSTEM - FRANCISCAN MEDICAL CENTER, INC. | 0345152443 | WI | 54          |                | 85          |                | 58          |                | 84          |                | 87          |                | 78          |                | 60           |                 | 23           |                 | 
```