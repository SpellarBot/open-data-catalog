# ESRD QIP - National Healthcare Safety Network (NHSN) Dialysis Reporting - Payment Year 2017

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/esrd-qip-national-healthcare-safety-network-nhsn-dialysis-reporting-payment-year-2016) |
| Metadata | [Link](https://data.medicare.gov/api/views/bmqj-88i5) |
| Data: JSON | [100 Rows](https://data.medicare.gov/api/views/bmqj-88i5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicare.gov/api/views/bmqj-88i5/rows.csv?max_rows=100) |
| Host | data.medicare.gov |
| Id | bmqj-88i5 |
| Name | ESRD QIP - National Healthcare Safety Network (NHSN) Dialysis Reporting - Payment Year 2017 |
| Category | Dialysis Facility Compare |
| Tags | dfc, dialysis, dialysis facilities, linking quality to payment - qip |
| Created | 2013-12-19T04:14:21Z |
| Publication Date | 2017-01-26T01:50:31Z |

## Description

Lists NHSN data used by ESRD QIP to assess dialysis facility performance.

## Columns

```ls
| Included | Schema Type    | Field Name                                       | Name                            | Data Type | Render Type |
| ======== | ============== | ================================================ | =============================== | ========= | =========== |
| Yes      | series tag     | facility_name                                    | Facility Name                   | text      | text        |
| Yes      | series tag     | cms_certification_number_ccn                     | CMS Certification Number (CCN)  | text      | text        |
| Yes      | numeric metric | alternate_ccn_1                                  | Alternate CCN 1                 | number    | text        |
| No       |                | address_1                                        | Address 1                       | text      | text        |
| No       |                | address_2                                        | Address 2                       | text      | text        |
| Yes      | series tag     | city                                             | City                            | text      | text        |
| Yes      | series tag     | state                                            | State                           | text      | text        |
| Yes      | series tag     | zip_code                                         | Zip Code                        | text      | text        |
| Yes      | numeric metric | network                                          | Network                         | number    | number      |
| Yes      | series tag     | measure_name                                     | Measure Name                    | text      | text        |
| Yes      | series tag     | achievement_measure_ratio                        | Achievement Measure Ratio       | text      | text        |
| Yes      | series tag     | national_avg_score_nhsn_dialysis_event_reporting | NHSN Measure Score              | text      | text        |
| Yes      | numeric metric | state_avg_nhsn_measure_score                     | State Avg NHSN Measure Score    | number    | text        |
| Yes      | numeric metric | national_avg_nhsn_measure_score                  | National Avg NHSN Measure Score | number    | text        |
```

## Time Field

```ls
Value = 2017
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = address_1,address_2
```

## Data Commands

```ls
series e:bmqj-88i5 d:2017-01-01T00:00:00.000Z t:cms_certification_number_ccn=012306 t:achievement_measure_ratio=2.035 t:facility_name="CHILDRENS HOSPITAL DIALYSIS" t:zip_code=35233 t:state=AL t:national_avg_score_nhsn_dialysis_event_reporting=0 t:measure_name=NHSN t:city=BIRMINGHAM m:state_avg_nhsn_measure_score=5 m:national_avg_nhsn_measure_score=5 m:alternate_ccn_1=13300 m:network=8

series e:bmqj-88i5 d:2017-01-01T00:00:00.000Z t:cms_certification_number_ccn=012500 t:achievement_measure_ratio=0.136 t:facility_name="FMC CAPITOL CITY" t:zip_code=36104 t:alternate_ccn_1=- t:state=AL t:national_avg_score_nhsn_dialysis_event_reporting=9 t:measure_name=NHSN t:city=MONTGOMERY m:state_avg_nhsn_measure_score=5 m:national_avg_nhsn_measure_score=5 m:network=8

series e:bmqj-88i5 d:2017-01-01T00:00:00.000Z t:cms_certification_number_ccn=012501 t:achievement_measure_ratio=1.506 t:facility_name="GADSDEN DIALYSIS" t:zip_code=35901 t:alternate_ccn_1=- t:state=AL t:national_avg_score_nhsn_dialysis_event_reporting=6 t:measure_name=NHSN t:city=GADSDEN m:state_avg_nhsn_measure_score=5 m:national_avg_nhsn_measure_score=5 m:network=8
```

## Meta Commands

```ls
metric m:network p:integer l:Network t:dataTypeName=number

metric m:state_avg_nhsn_measure_score p:integer l:"State Avg NHSN Measure Score" t:dataTypeName=number

metric m:national_avg_nhsn_measure_score p:integer l:"National Avg NHSN Measure Score" t:dataTypeName=number

entity e:bmqj-88i5 l:"ESRD QIP - National Healthcare Safety Network (NHSN) Dialysis  Reporting - Payment Year 2017" t:url=https://data.medicare.gov/api/views/bmqj-88i5

property e:bmqj-88i5 t:meta.view v:id=bmqj-88i5 v:category="Dialysis Facility Compare" v:averageRating=0 v:name="ESRD QIP - National Healthcare Safety Network (NHSN) Dialysis  Reporting - Payment Year 2017"

property e:bmqj-88i5 t:meta.view.owner v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:displayName=cms

property e:bmqj-88i5 t:meta.view.tableauthor v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:roleName=administrator v:displayName=cms

property e:bmqj-88i5 t:meta.view.metadata.custom_fields.common_core v:Publisher="Centers for Medicare & Medicaid Services (CMS)" v:Contact_Email=DialysisData@umich.edu v:Contact_Name=CMS v:Bureau_Code=009:38 v:Program_Code=009:078
```

## Top Records

```ls
| facility_name                  | cms_certification_number_ccn | alternate_ccn_1 | address_1                  | address_2 | city       | state | zip_code | network | measure_name | achievement_measure_ratio | national_avg_score_nhsn_dialysis_event_reporting | state_avg_nhsn_measure_score | national_avg_nhsn_measure_score | 
| ============================== | ============================ | =============== | ========================== | ========= | ========== | ===== | ======== | ======= | ============ | ========================= | ================================================ | ============================ | =============================== | 
| CHILDRENS HOSPITAL DIALYSIS    | 012306                       | 013300          | 1600 7TH AVENUE SOUTH      | -         | BIRMINGHAM | AL    | 35233    | 8       | NHSN         | 2.035                     | 0                                                | 5                            | 5                               | 
| FMC CAPITOL CITY               | 012500                       | -               | 255 S JACKSON STREET       | -         | MONTGOMERY | AL    | 36104    | 8       | NHSN         | 0.136                     | 9                                                | 5                            | 5                               | 
| GADSDEN DIALYSIS               | 012501                       | -               | 409 SOUTH FIRST STREET     | -         | GADSDEN    | AL    | 35901    | 8       | NHSN         | 1.506                     | 6                                                | 5                            | 5                               | 
| TUSCALOOSA UNIVERSITY DIALYSIS | 012502                       | -               | 220 15TH STREET            | -         | TUSCALOOSA | AL    | 35401    | 8       | NHSN         | 1.056                     | 4                                                | 5                            | 5                               | 
| PCD MONTGOMERY                 | 012505                       | -               | 1001 FOREST AVENUE         | -         | MONTGOMERY | AL    | 36106    | 8       | NHSN         | 1.817                     | 0                                                | 5                            | 5                               | 
| DOTHAN DIALYSIS                | 012506                       | -               | 216 GRACELAND DR.          | -         | DOTHAN     | AL    | 36305    | 8       | NHSN         | 0.374                     | 8                                                | 5                            | 5                               | 
| FMC MOBILE                     | 012507                       | -               | 2620 OLD SHELL RD          | -         | MOBILE     | AL    | 36607    | 8       | NHSN         | 0.825                     | 5                                                | 5                            | 5                               | 
| BIRMINGHAM EAST DIALYSIS       | 012508                       | -               | 1105 EAST PARK DRIVE       | -         | BIRMINGHAM | AL    | 35235    | 8       | NHSN         | 3.191                     | 0                                                | 5                            | 5                               | 
| FMC NORTH ALABAMA              | 012509                       | -               | 1311 N MEMORIAL PKWY #200  | -         | HUNTSVILLE | AL    | 35801    | 8       | NHSN         | 0.210                     | 8                                                | 5                            | 5                               | 
| FMC SELMA                      | 012512                       | -               | 905 MEDICAL CENTER PARKWAY | -         | SELMA      | AL    | 36701    | 8       | NHSN         | 0.250                     | 8                                                | 5                            | 5                               | 
```