# Healthcare Associated Infections - State

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/healthcare-associated-infections-state-d5fba) |
| Metadata | [Link](https://data.medicare.gov/api/views/k2ze-bqvw) |
| Data: JSON | [100 Rows](https://data.medicare.gov/api/views/k2ze-bqvw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicare.gov/api/views/k2ze-bqvw/rows.csv?max_rows=100) |
| Host | data.medicare.gov |
| Id | k2ze-bqvw |
| Name | Healthcare Associated Infections - State |
| Category | Hospital Compare |
| Tags | hospital compare, complications |
| Created | 2014-05-14T13:56:46Z |
| Publication Date | 2016-12-19T02:03:42Z |

## Description

The?Healthcare-Associated Infections (HAI)?measures - state data.  These measures are developed by?Centers for Disease Control and Prevention (CDC)?and collected through the?National Healthcare Safety Network (NHSN). They provide information on infections that occur while the patient is in the hospital. These infections can be related to devices, such as central lines and urinary catheters, or spread from patient to patient after contact with an infected person or surface. Many healthcare associated infections can be prevented when the hospitals use?CDC-recommended infection control steps.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type     | Render Type   |
| ======== | ============== | ================== | ================== | ============= | ============= |
| Yes      | series tag     | state              | State              | text          | text          |
| Yes      | series tag     | measure_name       | Measure Name       | text          | text          |
| Yes      | series tag     | measure_id         | Measure ID         | text          | text          |
| Yes      | numeric metric | score              | Score              | number        | text          |
| No       |                | footnote           | Footnote           | text          | text          |
| Yes      | time           | measure_start_date | Measure Start Date | calendar_date | calendar_date |
| No       |                | measure_end_date   | Measure End Date   | calendar_date | calendar_date |
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
series e:k2ze-bqvw d:2015-01-01T00:00:00.000Z t:measure_id=HAI_1_SIR t:state=AK t:measure_name="Central line-associated bloodstream infections (CLABSI) in ICUs and select wards" m:score=0.956

series e:k2ze-bqvw d:2015-01-01T00:00:00.000Z t:measure_id=HAI_1_SIR t:state=AL t:measure_name="Central line-associated bloodstream infections (CLABSI) in ICUs and select wards" m:score=1.53

series e:k2ze-bqvw d:2015-01-01T00:00:00.000Z t:measure_id=HAI_1_SIR t:state=AR t:measure_name="Central line-associated bloodstream infections (CLABSI) in ICUs and select wards" m:score=1.219
```

## Meta Commands

```ls
entity e:k2ze-bqvw l:"Healthcare Associated Infections - State" t:url=https://data.medicare.gov/api/views/k2ze-bqvw

property e:k2ze-bqvw t:meta.view v:id=k2ze-bqvw v:category="Hospital Compare" v:averageRating=0 v:name="Healthcare Associated Infections - State"

property e:k2ze-bqvw t:meta.view.owner v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:displayName=cms

property e:k2ze-bqvw t:meta.view.tableauthor v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:roleName=administrator v:displayName=cms

property e:k2ze-bqvw t:meta.view.metadata.custom_fields.common_core v:Publisher="Centers for Medicare & Medicaid Services (CMS)" v:Contact_Email=HospitalCompare@hsag.com v:Contact_Name=CMS v:Bureau_Code=009:38 v:Program_Code=009:078
```

## Top Records

```ls
| state | measure_name                                                                     | measure_id | score         | footnote                                                     | measure_start_date  | measure_end_date    | 
| ===== | ================================================================================ | ========== | ============= | ============================================================ | =================== | =================== | 
| AK    | Central line-associated bloodstream infections (CLABSI) in ICUs and select wards | HAI_1_SIR  | 0.956         |                                                              | 2015-01-01T00:00:00 | 2015-12-31T00:00:00 | 
| AL    | Central line-associated bloodstream infections (CLABSI) in ICUs and select wards | HAI_1_SIR  | 1.530         |                                                              | 2015-01-01T00:00:00 | 2015-12-31T00:00:00 | 
| AR    | Central line-associated bloodstream infections (CLABSI) in ICUs and select wards | HAI_1_SIR  | 1.219         |                                                              | 2015-01-01T00:00:00 | 2015-12-31T00:00:00 | 
| AS    | Central line-associated bloodstream infections (CLABSI) in ICUs and select wards | HAI_1_SIR  | Not Available | 13 - Results cannot be calculated for this reporting period. | 2015-01-01T00:00:00 | 2015-12-31T00:00:00 | 
| AZ    | Central line-associated bloodstream infections (CLABSI) in ICUs and select wards | HAI_1_SIR  | 0.917         |                                                              | 2015-01-01T00:00:00 | 2015-12-31T00:00:00 | 
| CA    | Central line-associated bloodstream infections (CLABSI) in ICUs and select wards | HAI_1_SIR  | 0.973         |                                                              | 2015-01-01T00:00:00 | 2015-12-31T00:00:00 | 
| CO    | Central line-associated bloodstream infections (CLABSI) in ICUs and select wards | HAI_1_SIR  | 0.935         |                                                              | 2015-01-01T00:00:00 | 2015-12-31T00:00:00 | 
| CT    | Central line-associated bloodstream infections (CLABSI) in ICUs and select wards | HAI_1_SIR  | 1.221         |                                                              | 2015-01-01T00:00:00 | 2015-12-31T00:00:00 | 
| DC    | Central line-associated bloodstream infections (CLABSI) in ICUs and select wards | HAI_1_SIR  | 1.273         |                                                              | 2015-01-01T00:00:00 | 2015-12-31T00:00:00 | 
| DE    | Central line-associated bloodstream infections (CLABSI) in ICUs and select wards | HAI_1_SIR  | 0.944         |                                                              | 2015-01-01T00:00:00 | 2015-12-31T00:00:00 | 
```