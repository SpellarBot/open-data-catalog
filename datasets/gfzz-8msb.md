# ESRD QIP - In-Center Hemodialysis Consumer Assessment of Healthcare Providers and Services Systems (ICH CAHPS) Survey Reporting - Payment Year 2017

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/esrd-qip-in-center-hemodialysis-consumer-assessment-of-healthcare-providers-and-services-2) |
| Metadata | [Link](https://data.medicare.gov/api/views/gfzz-8msb) |
| Data: JSON | [100 Rows](https://data.medicare.gov/api/views/gfzz-8msb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicare.gov/api/views/gfzz-8msb/rows.csv?max_rows=100) |
| Host | data.medicare.gov |
| Id | gfzz-8msb |
| Name | ESRD QIP - In-Center Hemodialysis Consumer Assessment of Healthcare Providers and Services Systems (ICH CAHPS) Survey Reporting - Payment Year 2017 |
| Category | Dialysis Facility Compare |
| Tags | dfc, dialysis, dialysis facilities, linking quality to payment - qip |
| Created | 2013-12-19T04:18:02Z |
| Publication Date | 2017-01-26T01:50:26Z |
| Rows Updated | 2017-01-05T20:50:37Z |

## Description

Lists ICH CAHPS survey data used by ESRD QIP to assess dialysis facility performance.

## Columns

```ls
| Included | Schema Type    | Field Name                                  | Name                                              | Data Type | Render Type |
| ======== | ============== | =========================================== | ================================================= | ========= | =========== |
| Yes      | series tag     | facility_name                               | Facility Name                                     | text      | text        |
| Yes      | series tag     | cms_certification_number_ccn                | CMS Certification Number (CCN)                    | text      | text        |
| Yes      | numeric metric | alternate_ccn_1                             | Alternate CCN 1                                   | number    | text        |
| Yes      | series tag     | address_1                                   | Address 1                                         | text      | text        |
| Yes      | series tag     | address_2                                   | Address 2                                         | text      | text        |
| Yes      | series tag     | city                                        | City                                              | text      | text        |
| Yes      | series tag     | state                                       | State                                             | text      | text        |
| Yes      | series tag     | zip_code                                    | Zip Code                                          | text      | text        |
| Yes      | numeric metric | network                                     | Network                                           | number    | number      |
| Yes      | series tag     | measure_name                                | Measure Name                                      | text      | text        |
| Yes      | series tag     | ich_cahps_administration_score              | ICH CAHPS Administration Score                    | text      | text        |
| Yes      | numeric metric | state_avg_ich_cahps_administration_score    | State Avg ICH CAHPS Administration Score          | number    | text        |
| Yes      | numeric metric | national_avg_score_ich_cahps_administration | National Avg Score ICH CAHPS Administration Score | number    | text        |
```

## Time Field

```ls
Value = 
Format & Zone = yyyy
```

## Data Commands

```ls
series e:gfzz-8msb d:2017-01-01T00:00:00.000Z t:cms_certification_number_ccn=012306 t:facility_name="CHILDRENS HOSPITAL DIALYSIS" t:zip_code=35233 t:ich_cahps_administration_score="No Score" t:state=AL t:address_1="1600 7TH AVENUE SOUTH" t:address_2=- t:measure_name="ICH CAHPS" t:city=BIRMINGHAM m:alternate_ccn_1=13300 m:state_avg_ich_cahps_administration_score=10 m:network=8 m:national_avg_score_ich_cahps_administration=10

series e:gfzz-8msb d:2017-01-01T00:00:00.000Z t:cms_certification_number_ccn=012500 t:facility_name="FMC CAPITOL CITY" t:zip_code=36104 t:ich_cahps_administration_score=10 t:alternate_ccn_1=- t:state=AL t:address_1="255 S JACKSON STREET" t:address_2=- t:measure_name="ICH CAHPS" t:city=MONTGOMERY m:state_avg_ich_cahps_administration_score=10 m:network=8 m:national_avg_score_ich_cahps_administration=10

series e:gfzz-8msb d:2017-01-01T00:00:00.000Z t:cms_certification_number_ccn=012501 t:facility_name="GADSDEN DIALYSIS" t:zip_code=35901 t:ich_cahps_administration_score="No Score" t:alternate_ccn_1=- t:state=AL t:address_1="409 SOUTH FIRST STREET" t:address_2=- t:measure_name="ICH CAHPS" t:city=GADSDEN m:state_avg_ich_cahps_administration_score=10 m:network=8 m:national_avg_score_ich_cahps_administration=10
```

## Meta Commands

```ls
metric m:network p:integer l:Network t:dataTypeName=number

metric m:state_avg_ich_cahps_administration_score p:integer l:"State Avg ICH CAHPS Administration Score" t:dataTypeName=number

metric m:national_avg_score_ich_cahps_administration p:integer l:"National Avg Score ICH CAHPS Administration Score" t:dataTypeName=number

entity e:gfzz-8msb l:"ESRD QIP - In-Center Hemodialysis Consumer Assessment of Healthcare Providers and Services Systems (ICH CAHPS) Survey Reporting - Payment Year 2017" t:url=https://data.medicare.gov/api/views/gfzz-8msb

property e:gfzz-8msb t:meta.view v:id=gfzz-8msb v:category="Dialysis Facility Compare" v:averageRating=0 v:name="ESRD QIP - In-Center Hemodialysis Consumer Assessment of Healthcare Providers and Services Systems (ICH CAHPS) Survey Reporting - Payment Year 2017"

property e:gfzz-8msb t:meta.view.owner v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:roleName=administrator v:displayName=cms

property e:gfzz-8msb t:meta.view.tableauthor v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:roleName=administrator v:displayName=cms

property e:gfzz-8msb t:meta.view.metadata.custom_fields.common_core v:Publisher="Centers for Medicare & Medicaid Services (CMS)" v:Contact_Email=DialysisData@umich.edu v:Contact_Name=CMS v:Bureau_Code=009:38 v:Program_Code=009:078
```