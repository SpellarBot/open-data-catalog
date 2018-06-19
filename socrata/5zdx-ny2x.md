# Long- Term Care Hospital - Nation Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/long-term-care-hospital-nation-data) |
| Metadata | [Link](https://data.medicare.gov/api/views/5zdx-ny2x) |
| Data: JSON | [100 Rows](https://data.medicare.gov/api/views/5zdx-ny2x/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicare.gov/api/views/5zdx-ny2x/rows.csv?max_rows=100) |
| Host | data.medicare.gov |
| Id | 5zdx-ny2x |
| Name | Long- Term Care Hospital - Nation Data |
| Category | Long-Term Care Hospital Compare |
| Tags | long term care hospital, hospital |
| Created | 2016-03-29T14:15:54Z |
| Publication Date | 2017-03-21T01:11:38Z |

## Description

National data on the quality of patient care measures shown on Long-Term Care Hospital Compare.

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
series e:5zdx-ny2x d:2015-04-01T00:00:00.000Z t:cms_certification_number_ccn=Nation t:measure_code=L_001_01_ADJ_RATE m:score=1.7

series e:5zdx-ny2x d:2015-04-01T00:00:00.000Z t:cms_certification_number_ccn=Nation t:measure_code=L_006_01_SIR m:score=0.887

series e:5zdx-ny2x d:2015-04-01T00:00:00.000Z t:cms_certification_number_ccn=Nation t:measure_code=L_007_01_SIR m:score=0.905
```

## Meta Commands

```ls
metric m:score p:integer l:Score t:dataTypeName=number

entity e:5zdx-ny2x l:"Long- Term Care Hospital - Nation Data" t:url=https://data.medicare.gov/api/views/5zdx-ny2x

property e:5zdx-ny2x t:meta.view v:id=5zdx-ny2x v:category="Long-Term Care Hospital Compare" v:averageRating=0 v:name="Long- Term Care Hospital - Nation Data"

property e:5zdx-ny2x t:meta.view.owner v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:displayName=cms

property e:5zdx-ny2x t:meta.view.tableauthor v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:roleName=administrator v:displayName=cms

property e:5zdx-ny2x t:meta.view.metadata.custom_fields.common_core v:Publisher="Centers for Medicare & Medicaid Services (CMS)" v:Contact_Email=LTCHQualityQuestions@cms.hhs.gov v:Contact_Name=CMS v:Bureau_Code=009:38 v:Program_Code=009:078
```

## Top Records

```ls
| cms_certification_number_ccn | measure_code           | score | footnote | start_date          | end_date            | 
| ============================ | ====================== | ===== | ======== | =================== | =================== | 
| Nation                       | L_001_01_ADJ_RATE      | 1.7   |          | 2015-04-01T00:00:00 | 2016-03-31T00:00:00 | 
| Nation                       | L_006_01_SIR           | 0.887 |          | 2015-04-01T00:00:00 | 2016-03-31T00:00:00 | 
| Nation                       | L_007_01_SIR           | 0.905 |          | 2015-04-01T00:00:00 | 2016-03-31T00:00:00 | 
| Nation                       | L_008_01_N_BETTER_NAT  | 177   |          | 2013-01-01T00:00:00 | 2014-12-31T00:00:00 | 
| Nation                       | L_008_01_N_NO_DIFF_NAT | 66    |          | 2013-01-01T00:00:00 | 2014-12-31T00:00:00 | 
| Nation                       | L_008_01_N_TOO_SMALL   | 9     |          | 2013-01-01T00:00:00 | 2014-12-31T00:00:00 | 
| Nation                       | L_008_01_N_WORSE_NAT   | 167   |          | 2013-01-01T00:00:00 | 2014-12-31T00:00:00 | 
| Nation                       | L_008_01_RSRR          | 24.61 |          | 2013-01-01T00:00:00 | 2014-12-31T00:00:00 | 
```