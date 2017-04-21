# Inpatient Rehabilitation Facility - Provider Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/inpatient-rehabilitation-facility-provider-data) |
| Metadata | [Link](https://data.medicare.gov/api/views/v9e4-nwhh) |
| Data: JSON | [100 Rows](https://data.medicare.gov/api/views/v9e4-nwhh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicare.gov/api/views/v9e4-nwhh/rows.csv?max_rows=100) |
| Host | data.medicare.gov |
| Id | v9e4-nwhh |
| Name | Inpatient Rehabilitation Facility - Provider Data |
| Category | Inpatient Rehabilitation Facility Compare |
| Tags | inpatient rehabilitation facilities, inpatient rehabilitation facility, rehabilitation |
| Created | 2016-03-29T13:51:36Z |
| Publication Date | 2017-03-21T01:12:52Z |

## Description

A list of inpatient rehabilitation facilities with data on the quality of patient care measures shown on Inpatient Rehabilitation Facility Compare.

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                           | Data Type     | Render Type   |
| ======== | ============== | ============================ | ============================== | ============= | ============= |
| Yes      | series tag     | cms_certification_number_ccn | CMS Certification Number (CCN) | text          | text          |
| Yes      | series tag     | facility_name                | Facility Name                  | text          | text          |
| No       |                | address_line_1               | Address Line 1                 | text          | text          |
| No       |                | address_line_2               | Address Line 2                 | text          | text          |
| Yes      | series tag     | city                         | City                           | text          | text          |
| Yes      | series tag     | state                        | State                          | text          | text          |
| Yes      | series tag     | zip_code                     | Zip Code                       | text          | text          |
| Yes      | series tag     | county_name                  | County Name                    | text          | text          |
| Yes      | series tag     | phonenumber                  | PhoneNumber                    | phone         | phone         |
| Yes      | numeric metric | cms_region                   | CMS Region                     | number        | number        |
| Yes      | series tag     | measure_code                 | Measure Code                   | text          | text          |
| Yes      | series tag     | score                        | Score                          | text          | text          |
| No       |                | footnote                     | Footnote                       | text          | text          |
| Yes      | time           | start_date                   | Start Date                     | calendar_date | calendar_date |
| No       |                | end_date                     | End Date                       | calendar_date | calendar_date |
```

## Time Field

```ls
Value = start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address_line_1,address_line_2,footnote,end_date
```

## Data Commands

```ls
series e:v9e4-nwhh d:2015-04-01T00:00:00.000Z t:cms_certification_number_ccn=013025 t:phone_number="(205) 868-2000" t:facility_name="HEALTHSOUTH LAKESHORE REHABILITATION HOSPITAL" t:zip_code=35209 t:state=AL t:score=0.5 t:measure_code=I_001_01_ADJ_RATE t:county_name=Jefferson t:city=BIRMINGHAM m:cms_region=4

series e:v9e4-nwhh d:2015-04-01T00:00:00.000Z t:cms_certification_number_ccn=013025 t:phone_number="(205) 868-2000" t:facility_name="HEALTHSOUTH LAKESHORE REHABILITATION HOSPITAL" t:zip_code=35209 t:state=AL t:score=2255 t:measure_code=I_001_01_DENOMINATOR t:county_name=Jefferson t:city=BIRMINGHAM m:cms_region=4

series e:v9e4-nwhh d:2015-04-01T00:00:00.000Z t:cms_certification_number_ccn=013025 t:phone_number="(205) 868-2000" t:facility_name="HEALTHSOUTH LAKESHORE REHABILITATION HOSPITAL" t:zip_code=35209 t:state=AL t:score="Not Available" t:measure_code=I_006_01_CI_LOWER t:county_name=Jefferson t:city=BIRMINGHAM m:cms_region=4
```

## Meta Commands

```ls
metric m:cms_region p:integer l:"CMS Region" t:dataTypeName=number

entity e:v9e4-nwhh l:"Inpatient Rehabilitation Facility - Provider Data" t:url=https://data.medicare.gov/api/views/v9e4-nwhh

property e:v9e4-nwhh t:meta.view v:id=v9e4-nwhh v:category="Inpatient Rehabilitation Facility Compare" v:averageRating=0 v:name="Inpatient Rehabilitation Facility - Provider Data"

property e:v9e4-nwhh t:meta.view.owner v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:displayName=cms

property e:v9e4-nwhh t:meta.view.tableauthor v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:roleName=administrator v:displayName=cms

property e:v9e4-nwhh t:meta.view.metadata.custom_fields.common_core v:Publisher="Centers for Medicare & Medicaid Services (CMS)" v:Contact_Email=IRFQualityQuestions@cms.hhs.gov v:Contact_Name=CMS v:Bureau_Code=009:38 v:Program_Code=009:078
```

## Top Records

```ls
| cms_certification_number_ccn | facility_name                                 | address_line_1      | address_line_2 | city       | state | zip_code | county_name | phonenumber            | cms_region | measure_code         | score                                    | footnote | start_date          | end_date            | 
| ============================ | ============================================= | =================== | ============== | ========== | ===== | ======== | =========== | ====================== | ========== | ==================== | ======================================== | ======== | =================== | =================== | 
| 013025                       | HEALTHSOUTH LAKESHORE REHABILITATION HOSPITAL | 3800 RIDGEWAY DRIVE |                | BIRMINGHAM | AL    | 35209    | Jefferson   | [(205) 868-2000, null] | 4          | I_001_01_ADJ_RATE    | 0.5                                      |          | 2015-04-01T00:00:00 | 2016-03-31T00:00:00 | 
| 013025                       | HEALTHSOUTH LAKESHORE REHABILITATION HOSPITAL | 3800 RIDGEWAY DRIVE |                | BIRMINGHAM | AL    | 35209    | Jefferson   | [(205) 868-2000, null] | 4          | I_001_01_DENOMINATOR | 2255                                     |          | 2015-04-01T00:00:00 | 2016-03-31T00:00:00 | 
| 013025                       | HEALTHSOUTH LAKESHORE REHABILITATION HOSPITAL | 3800 RIDGEWAY DRIVE |                | BIRMINGHAM | AL    | 35209    | Jefferson   | [(205) 868-2000, null] | 4          | I_006_01_CI_LOWER    | Not Available                            | 6        | 2015-04-01T00:00:00 | 2016-03-31T00:00:00 | 
| 013025                       | HEALTHSOUTH LAKESHORE REHABILITATION HOSPITAL | 3800 RIDGEWAY DRIVE |                | BIRMINGHAM | AL    | 35209    | Jefferson   | [(205) 868-2000, null] | 4          | I_006_01_CI_UPPER    | 1.160                                    |          | 2015-04-01T00:00:00 | 2016-03-31T00:00:00 | 
| 013025                       | HEALTHSOUTH LAKESHORE REHABILITATION HOSPITAL | 3800 RIDGEWAY DRIVE |                | BIRMINGHAM | AL    | 35209    | Jefferson   | [(205) 868-2000, null] | 4          | I_006_01_COMP_PERF   | No Different than the National Benchmark |          | 2015-04-01T00:00:00 | 2016-03-31T00:00:00 | 
| 013025                       | HEALTHSOUTH LAKESHORE REHABILITATION HOSPITAL | 3800 RIDGEWAY DRIVE |                | BIRMINGHAM | AL    | 35209    | Jefferson   | [(205) 868-2000, null] | 4          | I_006_01_DOPC_DAYS   | 1504                                     |          | 2015-04-01T00:00:00 | 2016-03-31T00:00:00 | 
| 013025                       | HEALTHSOUTH LAKESHORE REHABILITATION HOSPITAL | 3800 RIDGEWAY DRIVE |                | BIRMINGHAM | AL    | 35209    | Jefferson   | [(205) 868-2000, null] | 4          | I_006_01_ELIGCASES   | 2.582                                    |          | 2015-04-01T00:00:00 | 2016-03-31T00:00:00 | 
| 013025                       | HEALTHSOUTH LAKESHORE REHABILITATION HOSPITAL | 3800 RIDGEWAY DRIVE |                | BIRMINGHAM | AL    | 35209    | Jefferson   | [(205) 868-2000, null] | 4          | I_006_01_NUMERATOR   | 0                                        |          | 2015-04-01T00:00:00 | 2016-03-31T00:00:00 | 
| 013025                       | HEALTHSOUTH LAKESHORE REHABILITATION HOSPITAL | 3800 RIDGEWAY DRIVE |                | BIRMINGHAM | AL    | 35209    | Jefferson   | [(205) 868-2000, null] | 4          | I_006_01_SIR         | 0.000                                    |          | 2015-04-01T00:00:00 | 2016-03-31T00:00:00 | 
| 013025                       | HEALTHSOUTH LAKESHORE REHABILITATION HOSPITAL | 3800 RIDGEWAY DRIVE |                | BIRMINGHAM | AL    | 35209    | Jefferson   | [(205) 868-2000, null] | 4          | I_007_01_COMP_PERF   | Worse than the National Rate             |          | 2013-01-01T00:00:00 | 2014-12-31T00:00:00 | 
```