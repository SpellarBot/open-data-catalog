# ESRD QIP - Dialysis Adequacy - Payment Year 2017

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/esrd-qip-dialysis-adequacy-payment-year-2015) |
| Metadata | [Link](https://data.medicare.gov/api/views/85f7-fdqf) |
| Data: JSON | [100 Rows](https://data.medicare.gov/api/views/85f7-fdqf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicare.gov/api/views/85f7-fdqf/rows.csv?max_rows=100) |
| Host | data.medicare.gov |
| Id | 85f7-fdqf |
| Name | ESRD QIP - Dialysis Adequacy - Payment Year 2017 |
| Category | Dialysis Facility Compare |
| Tags | dfc, dialysis, dialysis facilities, linking quality to payment - qip |
| Created | 2012-10-23T16:02:23Z |
| Publication Date | 2017-01-26T01:49:58Z |

## Description

ESRD QIP data by facility: % of hemodialysis patient-months with spKt/V >= 1.2; % of peritoneal patient-months with Kt/V >= 1.7 Kt/V (dialytic + residual) during the four-month study period; % of pediatric in-center hemodialysis patient-months with spKt/V >= 1.2

## Columns

```ls
| Included | Schema Type    | Field Name                                                 | Name                                                       | Data Type | Render Type |
| ======== | ============== | ========================================================== | ========================================================== | ========= | =========== |
| Yes      | series tag     | facility_name                                              | Facility Name                                              | text      | text        |
| Yes      | series tag     | cms_certification_number                                   | CMS Certification Number                                   | text      | text        |
| Yes      | numeric metric | alternate_ccn                                              | Alternate CCN 1                                            | number    | text        |
| No       |                | address1                                                   | Address 1                                                  | text      | text        |
| No       |                | address2                                                   | Address 2                                                  | text      | text        |
| Yes      | series tag     | city                                                       | City                                                       | text      | text        |
| Yes      | series tag     | state                                                      | State                                                      | text      | text        |
| Yes      | series tag     | zip_code                                                   | Zip Code                                                   | text      | text        |
| Yes      | numeric metric | network                                                    | Network                                                    | number    | number      |
| Yes      | series tag     | kt_v_adult_hemodialysis_achievement_measure_rate           | Kt/V Adult Hemodialysis Achievement Measure Rate           | text      | text        |
| Yes      | series tag     | kt_v_adult_hemodialysis_measure_score                      | Kt/V Adult Hemodialysis Measure Score                      | text      | text        |
| Yes      | numeric metric | state_avg_kt_v_adult_hemodialysis_measure_score            | State Avg Kt/V Adult Hemodialysis Measure Score            | number    | text        |
| Yes      | numeric metric | national_avg_kt_v_adult_hemodialysis_measure_score         | National Avg Kt/V Adult Hemodialysis Measure Score         | number    | text        |
| Yes      | series tag     | kt_v_adult_peritoneal_dialysis_achievement_measure_rate    | Kt/V Adult Peritoneal Dialysis Achievement Measure Rate    | text      | text        |
| Yes      | series tag     | kt_v_adult_peritoneal_dialysis_measure_score               | Kt/V Adult Peritoneal Dialysis Measure Score               | text      | text        |
| Yes      | numeric metric | state_avg_kt_v_adult_peritoneal_dialysis_measure_score     | State Avg Kt/V Adult Peritoneal Dialysis Measure Score     | number    | text        |
| Yes      | numeric metric | national_avg_kt_v_adult_peritoneal_dialysis_measure_score  | National Avg Kt/V Adult Peritoneal Dialysis Measure Score  | number    | text        |
| Yes      | series tag     | kt_v_pediatric_hemodialysis_achievement_measure_rate       | Kt/V Pediatric Hemodialysis Achievement Measure Rate       | text      | text        |
| Yes      | series tag     | kt_v_pediatric_hemodialysis_measure_score                  | Kt/V Pediatric Hemodialysis Measure Score                  | text      | text        |
| Yes      | numeric metric | state_avg_kt_v_pediatric_hemodialysis_measure_score        | State Avg Kt/V Pediatric Hemodialysis Measure Score        | number    | text        |
| Yes      | numeric metric | national_avg_kt_v_pediatric_hemodialysis_measure_score     | National Avg Kt/V Pediatric Hemodialysis Measure Score     | number    | text        |
| Yes      | series tag     | kt_v_dialysis_adequacy_combined_measure_score              | Kt/V Dialysis Adequacy Combined Measure Score              | text      | text        |
| Yes      | numeric metric | national_avg_kt_v_dialysis_adequacy_combined_measure_score | National Avg Kt/V Dialysis Adequacy Combined Measure Score | number    | text        |
```

## Time Field

```ls
Value = 2017
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = address1,address2
```

## Data Commands

```ls
series e:85f7-fdqf d:2017-01-01T00:00:00.000Z t:kt_v_adult_peritoneal_dialysis_achievement_measure_rate="No Rate" t:facility_name="CHILDRENS HOSPITAL DIALYSIS" t:cms_certification_number=012306 t:zip_code=35233 t:kt_v_adult_peritoneal_dialysis_measure_score="No Score" t:kt_v_pediatric_hemodialysis_measure_score="No Score" t:state=AL t:kt_v_pediatric_hemodialysis_achievement_measure_rate="No Rate" t:kt_v_adult_hemodialysis_achievement_measure_rate="No Rate" t:kt_v_adult_hemodialysis_measure_score="No Score" t:kt_v_dialysis_adequacy_combined_measure_score="No Score" t:city=BIRMINGHAM m:alternate_ccn=13300 m:national_avg_kt_v_adult_hemodialysis_measure_score=7 m:national_avg_kt_v_pediatric_hemodialysis_measure_score=8 m:state_avg_kt_v_adult_peritoneal_dialysis_measure_score=7 m:state_avg_kt_v_adult_hemodialysis_measure_score=7 m:national_avg_kt_v_adult_peritoneal_dialysis_measure_score=8 m:national_avg_kt_v_dialysis_adequacy_combined_measure_score=7 m:network=8

series e:85f7-fdqf d:2017-01-01T00:00:00.000Z t:alternate_ccn=- t:kt_v_adult_peritoneal_dialysis_achievement_measure_rate="No Rate" t:facility_name="FMC CAPITOL CITY" t:cms_certification_number=012500 t:zip_code=36104 t:kt_v_adult_peritoneal_dialysis_measure_score="No Score" t:kt_v_pediatric_hemodialysis_measure_score="No Score" t:state=AL t:kt_v_pediatric_hemodialysis_achievement_measure_rate="No Rate" t:kt_v_adult_hemodialysis_achievement_measure_rate=98% t:kt_v_adult_hemodialysis_measure_score=8 t:kt_v_dialysis_adequacy_combined_measure_score=8 t:city=MONTGOMERY m:national_avg_kt_v_adult_hemodialysis_measure_score=7 m:national_avg_kt_v_pediatric_hemodialysis_measure_score=8 m:state_avg_kt_v_adult_peritoneal_dialysis_measure_score=7 m:state_avg_kt_v_adult_hemodialysis_measure_score=7 m:national_avg_kt_v_adult_peritoneal_dialysis_measure_score=8 m:national_avg_kt_v_dialysis_adequacy_combined_measure_score=7 m:network=8

series e:85f7-fdqf d:2017-01-01T00:00:00.000Z t:alternate_ccn=- t:kt_v_adult_peritoneal_dialysis_achievement_measure_rate="No Rate" t:facility_name="GADSDEN DIALYSIS" t:cms_certification_number=012501 t:zip_code=35901 t:kt_v_adult_peritoneal_dialysis_measure_score="No Score" t:kt_v_pediatric_hemodialysis_measure_score="No Score" t:state=AL t:kt_v_pediatric_hemodialysis_achievement_measure_rate="No Rate" t:kt_v_adult_hemodialysis_achievement_measure_rate=96% t:kt_v_adult_hemodialysis_measure_score=6 t:kt_v_dialysis_adequacy_combined_measure_score=6 t:city=GADSDEN m:national_avg_kt_v_adult_hemodialysis_measure_score=7 m:national_avg_kt_v_pediatric_hemodialysis_measure_score=8 m:state_avg_kt_v_adult_peritoneal_dialysis_measure_score=7 m:state_avg_kt_v_adult_hemodialysis_measure_score=7 m:national_avg_kt_v_adult_peritoneal_dialysis_measure_score=8 m:national_avg_kt_v_dialysis_adequacy_combined_measure_score=7 m:network=8
```

## Meta Commands

```ls
metric m:network p:integer l:Network t:dataTypeName=number

metric m:state_avg_kt_v_adult_hemodialysis_measure_score p:integer l:"State Avg Kt/V Adult Hemodialysis Measure Score" t:dataTypeName=number

metric m:national_avg_kt_v_adult_hemodialysis_measure_score p:integer l:"National Avg Kt/V Adult Hemodialysis Measure Score" t:dataTypeName=number

metric m:state_avg_kt_v_adult_peritoneal_dialysis_measure_score p:integer l:"State Avg Kt/V Adult Peritoneal Dialysis Measure Score" t:dataTypeName=number

metric m:national_avg_kt_v_adult_peritoneal_dialysis_measure_score p:integer l:"National Avg Kt/V Adult Peritoneal Dialysis Measure Score" t:dataTypeName=number

metric m:state_avg_kt_v_pediatric_hemodialysis_measure_score p:integer l:"State Avg Kt/V Pediatric Hemodialysis Measure Score" t:dataTypeName=number

metric m:national_avg_kt_v_pediatric_hemodialysis_measure_score p:integer l:"National Avg Kt/V Pediatric Hemodialysis Measure Score" t:dataTypeName=number

metric m:national_avg_kt_v_dialysis_adequacy_combined_measure_score p:integer l:"National Avg Kt/V Dialysis Adequacy Combined Measure Score" t:dataTypeName=number

entity e:85f7-fdqf l:"ESRD QIP - Dialysis Adequacy - Payment Year 2017" t:url=https://data.medicare.gov/api/views/85f7-fdqf

property e:85f7-fdqf t:meta.view v:id=85f7-fdqf v:category="Dialysis Facility Compare" v:averageRating=0 v:name="ESRD QIP - Dialysis Adequacy - Payment Year 2017"

property e:85f7-fdqf t:meta.view.owner v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:displayName=cms

property e:85f7-fdqf t:meta.view.tableauthor v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:roleName=administrator v:displayName=cms

property e:85f7-fdqf t:meta.view.metadata.custom_fields.common_core v:Publisher="Centers for Medicare & Medicaid Services (CMS)" v:Contact_Email=DialysisData@umich.edu v:Contact_Name=CMS v:Bureau_Code=009:38 v:Program_Code=009:078
```

## Top Records

```ls
| facility_name                  | cms_certification_number | alternate_ccn | address1                   | address2 | city       | state | zip_code | network | kt_v_adult_hemodialysis_achievement_measure_rate | kt_v_adult_hemodialysis_measure_score | state_avg_kt_v_adult_hemodialysis_measure_score | national_avg_kt_v_adult_hemodialysis_measure_score | kt_v_adult_peritoneal_dialysis_achievement_measure_rate | kt_v_adult_peritoneal_dialysis_measure_score | state_avg_kt_v_adult_peritoneal_dialysis_measure_score | national_avg_kt_v_adult_peritoneal_dialysis_measure_score | kt_v_pediatric_hemodialysis_achievement_measure_rate | kt_v_pediatric_hemodialysis_measure_score | state_avg_kt_v_pediatric_hemodialysis_measure_score | national_avg_kt_v_pediatric_hemodialysis_measure_score | kt_v_dialysis_adequacy_combined_measure_score | national_avg_kt_v_dialysis_adequacy_combined_measure_score | 
| ============================== | ======================== | ============= | ========================== | ======== | ========== | ===== | ======== | ======= | ================================================ | ===================================== | =============================================== | ================================================== | ======================================================= | ============================================ | ====================================================== | ========================================================= | ==================================================== | ========================================= | =================================================== | ====================================================== | ============================================= | ========================================================== | 
| CHILDRENS HOSPITAL DIALYSIS    | 012306                   | 013300        | 1600 7TH AVENUE SOUTH      | -        | BIRMINGHAM | AL    | 35233    | 8       | No Rate                                          | No Score                              | 7                                               | 7                                                  | No Rate                                                 | No Score                                     | 7                                                      | 8                                                         | No Rate                                              | No Score                                  |                                                     | 8                                                      | No Score                                      | 7                                                          | 
| FMC CAPITOL CITY               | 012500                   | -             | 255 S JACKSON STREET       | -        | MONTGOMERY | AL    | 36104    | 8       | 98%                                              | 8                                     | 7                                               | 7                                                  | No Rate                                                 | No Score                                     | 7                                                      | 8                                                         | No Rate                                              | No Score                                  |                                                     | 8                                                      | 8                                             | 7                                                          | 
| GADSDEN DIALYSIS               | 012501                   | -             | 409 SOUTH FIRST STREET     | -        | GADSDEN    | AL    | 35901    | 8       | 96%                                              | 6                                     | 7                                               | 7                                                  | No Rate                                                 | No Score                                     | 7                                                      | 8                                                         | No Rate                                              | No Score                                  |                                                     | 8                                                      | 6                                             | 7                                                          | 
| TUSCALOOSA UNIVERSITY DIALYSIS | 012502                   | -             | 220 15TH STREET            | -        | TUSCALOOSA | AL    | 35401    | 8       | 97%                                              | 7                                     | 7                                               | 7                                                  | No Rate                                                 | No Score                                     | 7                                                      | 8                                                         | No Rate                                              | No Score                                  |                                                     | 8                                                      | 7                                             | 7                                                          | 
| PCD MONTGOMERY                 | 012505                   | -             | 1001 FOREST AVENUE         | -        | MONTGOMERY | AL    | 36106    | 8       | 99%                                              | 9                                     | 7                                               | 7                                                  | 97%                                                     | 10                                           | 7                                                      | 8                                                         | No Rate                                              | No Score                                  |                                                     | 8                                                      | 9                                             | 7                                                          | 
| DOTHAN DIALYSIS                | 012506                   | -             | 216 GRACELAND DR.          | -        | DOTHAN     | AL    | 36305    | 8       | 98%                                              | 8                                     | 7                                               | 7                                                  | 96%                                                     | 10                                           | 7                                                      | 8                                                         | No Rate                                              | No Score                                  |                                                     | 8                                                      | 9                                             | 7                                                          | 
| FMC MOBILE                     | 012507                   | -             | 2620 OLD SHELL RD          | -        | MOBILE     | AL    | 36607    | 8       | 95%                                              | 5                                     | 7                                               | 7                                                  | No Rate                                                 | No Score                                     | 7                                                      | 8                                                         | No Rate                                              | No Score                                  |                                                     | 8                                                      | 5                                             | 7                                                          | 
| BIRMINGHAM EAST DIALYSIS       | 012508                   | -             | 1105 EAST PARK DRIVE       | -        | BIRMINGHAM | AL    | 35235    | 8       | 97%                                              | 7                                     | 7                                               | 7                                                  | No Rate                                                 | No Score                                     | 7                                                      | 8                                                         | No Rate                                              | No Score                                  |                                                     | 8                                                      | 7                                             | 7                                                          | 
| FMC NORTH ALABAMA              | 012509                   | -             | 1311 N MEMORIAL PKWY #200  | -        | HUNTSVILLE | AL    | 35801    | 8       | 92%                                              | 2                                     | 7                                               | 7                                                  | No Rate                                                 | No Score                                     | 7                                                      | 8                                                         | No Rate                                              | No Score                                  |                                                     | 8                                                      | 2                                             | 7                                                          | 
| FMC SELMA                      | 012512                   | -             | 905 MEDICAL CENTER PARKWAY | -        | SELMA      | AL    | 36701    | 8       | 96%                                              | 6                                     | 7                                               | 7                                                  | No Rate                                                 | No Score                                     | 7                                                      | 8                                                         | No Rate                                              | No Score                                  |                                                     | 8                                                      | 6                                             | 7                                                          | 
```