# Healthcare Associated Infections - National

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/healthcare-associated-infections-national-901b7) |
| Metadata | [Link](https://data.medicare.gov/api/views/yd3s-jyhd) |
| Data: JSON | [100 Rows](https://data.medicare.gov/api/views/yd3s-jyhd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicare.gov/api/views/yd3s-jyhd/rows.csv?max_rows=100) |
| Host | data.medicare.gov |
| Id | yd3s-jyhd |
| Name | Healthcare Associated Infections - National |
| Category | Hospital Compare |
| Tags | hospital compare, complications |
| Created | 2014-05-14T13:46:57Z |
| Publication Date | 2016-12-19T02:03:20Z |

## Description

The?Healthcare-Associated Infections (HAI)?measures - national data.  These measures are developed by?Centers for Disease Control and Prevention (CDC)?and collected through the?National Healthcare Safety Network (NHSN). They provide information on infections that occur while the patient is in the hospital. These infections can be related to devices, such as central lines and urinary catheters, or spread from patient to patient after contact with an infected person or surface. Many healthcare associated infections can be prevented when the hospitals use?CDC-recommended infection control steps.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type     | Render Type   |
| ======== | ============== | ================== | ================== | ============= | ============= |
| Yes      | series tag     | measure_name       | Measure Name       | text          | text          |
| Yes      | series tag     | measure_id         | Measure ID         | text          | text          |
| Yes      | numeric metric | score              | Score              | number        | number        |
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
series e:yd3s-jyhd d:2015-01-01T00:00:00.000Z t:measure_id=HAI_1_SIR t:measure_name="Central line-associated bloodstream infections (CLABSI) in ICUs and select wards" m:score=1

series e:yd3s-jyhd d:2015-01-01T00:00:00.000Z t:measure_id=HAI_2_SIR t:measure_name="Catheter-associated urinary tract infections (CAUTI) in ICUs and select wards" m:score=1

series e:yd3s-jyhd d:2015-01-01T00:00:00.000Z t:measure_id=HAI_3_SIR t:measure_name="Surgical Site Infection from colon surgery (SSI: Colon)" m:score=1
```

## Meta Commands

```ls
metric m:score p:integer l:Score t:dataTypeName=number

entity e:yd3s-jyhd l:"Healthcare Associated Infections - National" t:url=https://data.medicare.gov/api/views/yd3s-jyhd

property e:yd3s-jyhd t:meta.view v:id=yd3s-jyhd v:category="Hospital Compare" v:averageRating=0 v:name="Healthcare Associated Infections - National"

property e:yd3s-jyhd t:meta.view.owner v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:displayName=cms

property e:yd3s-jyhd t:meta.view.tableauthor v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:roleName=administrator v:displayName=cms

property e:yd3s-jyhd t:meta.view.metadata.custom_fields.common_core v:Publisher="Centers for Medicare & Medicaid Services (CMS)" v:Contact_Email=HospitalCompare@hsag.com v:Contact_Name=CMS v:Bureau_Code=009:38 v:Program_Code=009:078
```

## Top Records

```ls
| measure_name                                                                                                   | measure_id | score | footnote | measure_start_date  | measure_end_date    | 
| ============================================================================================================== | ========== | ===== | ======== | =================== | =================== | 
| Central line-associated bloodstream infections (CLABSI) in ICUs and select wards                               | HAI_1_SIR  | 1     |          | 2015-01-01T00:00:00 | 2015-12-31T00:00:00 | 
| Catheter-associated urinary tract infections (CAUTI) in ICUs and select wards                                  | HAI_2_SIR  | 1     |          | 2015-01-01T00:00:00 | 2015-12-31T00:00:00 | 
| Surgical Site Infection from colon surgery (SSI: Colon)                                                        | HAI_3_SIR  | 1     |          | 2015-01-01T00:00:00 | 2015-12-31T00:00:00 | 
| Surgical Site Infection from abdominal hysterectomy (SSI: Hysterectomy)                                        | HAI_4_SIR  | 1     |          | 2015-01-01T00:00:00 | 2015-12-31T00:00:00 | 
| Methicillin-resistant Staphylococcus Aureus (MRSA) Blood Laboratory-identified Events (Bloodstream infections) | HAI_5_SIR  | 1     |          | 2015-01-01T00:00:00 | 2015-12-31T00:00:00 | 
| Clostridium difficile (C.diff.) Laboratory-identified Events (Intestinal infections)                           | HAI_6_SIR  | 1     |          | 2015-01-01T00:00:00 | 2015-12-31T00:00:00 | 
```