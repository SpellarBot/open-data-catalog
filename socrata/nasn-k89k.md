# Inpatient Rehabilitation Facility - Nation Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/inpatient-rehabilitation-facility-nation-data) |
| Metadata | [Link](https://data.medicare.gov/api/views/nasn-k89k) |
| Data: JSON | [100 Rows](https://data.medicare.gov/api/views/nasn-k89k/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicare.gov/api/views/nasn-k89k/rows.csv?max_rows=100) |
| Host | data.medicare.gov |
| Id | nasn-k89k |
| Name | Inpatient Rehabilitation Facility - Nation Data |
| Category | Inpatient Rehabilitation Facility Compare |
| Tags | inpatient rehabilitation facilities, inpatient rehabilitation facility, rehabilitation |
| Created | 2016-03-28T17:53:27Z |
| Publication Date | 2017-03-21T01:12:47Z |

## Description

National data on the quality of patient care measures shown on Inpatient Rehabilitation Facility Compare.

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                           | Data Type     | Render Type   |
| ======== | ============== | ============================ | ============================== | ============= | ============= |
| Yes      | series tag     | cms_certification_number_ccn | CMS Certification Number (CCN) | text          | text          |
| Yes      | series tag     | measure_code                 | Measure Code                   | text          | text          |
| Yes      | numeric metric | score                        | Score                          | number        | text          |
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
Excluded Fields = footnote,end_date
```

## Data Commands

```ls
series e:nasn-k89k d:2015-04-01T00:00:00.000Z t:cms_certification_number_ccn=Nation t:measure_code=I_001_01_ADJ_RATE m:score=0.7

series e:nasn-k89k d:2015-04-01T00:00:00.000Z t:cms_certification_number_ccn=Nation t:measure_code=I_006_01_SIR m:score=0.933

series e:nasn-k89k d:2013-01-01T00:00:00.000Z t:cms_certification_number_ccn=Nation t:measure_code=I_007_01_N_BETTER_NAT m:score=426
```

## Meta Commands

```ls
metric m:score p:integer l:Score t:dataTypeName=number

entity e:nasn-k89k l:"Inpatient Rehabilitation Facility - Nation Data" t:url=https://data.medicare.gov/api/views/nasn-k89k

property e:nasn-k89k t:meta.view v:id=nasn-k89k v:category="Inpatient Rehabilitation Facility Compare" v:averageRating=0 v:name="Inpatient Rehabilitation Facility - Nation Data"

property e:nasn-k89k t:meta.view.owner v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:displayName=cms

property e:nasn-k89k t:meta.view.tableauthor v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:roleName=administrator v:displayName=cms

property e:nasn-k89k t:meta.view.metadata.custom_fields.common_core v:Publisher="Centers for Medicare & Medicaid Services (CMS)" v:Contact_Email=IRFQualityQuestions@cms.hhs.gov v:Contact_Name=CMS v:Bureau_Code=009:38 v:Program_Code=009:078
```

## Top Records

```ls
| cms_certification_number_ccn | measure_code           | score | footnote | start_date          | end_date            | 
| ============================ | ====================== | ===== | ======== | =================== | =================== | 
| Nation                       | I_001_01_ADJ_RATE      | 0.7   |          | 2015-04-01T00:00:00 | 2016-03-31T00:00:00 | 
| Nation                       | I_006_01_SIR           | 0.933 |          | 2015-04-01T00:00:00 | 2016-03-31T00:00:00 | 
| Nation                       | I_007_01_N_BETTER_NAT  | 426   |          | 2013-01-01T00:00:00 | 2014-12-31T00:00:00 | 
| Nation                       | I_007_01_N_NO_DIFF_NAT | 277   |          | 2013-01-01T00:00:00 | 2014-12-31T00:00:00 | 
| Nation                       | I_007_01_N_TOO_SMALL   | 11    |          | 2013-01-01T00:00:00 | 2014-12-31T00:00:00 | 
| Nation                       | I_007_01_N_WORSE_NAT   | 407   |          | 2013-01-01T00:00:00 | 2014-12-31T00:00:00 | 
| Nation                       | I_007_01_RSRR          | 13.06 |          | 2013-01-01T00:00:00 | 2014-12-31T00:00:00 | 
```