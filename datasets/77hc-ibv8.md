# Healthcare Associated Infections - Hospital

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/healthcare-associated-infections-hospital-3ca5e) |
| Metadata | [Link](https://data.medicare.gov/api/views/77hc-ibv8) |
| Data: JSON | [100 Rows](https://data.medicare.gov/api/views/77hc-ibv8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicare.gov/api/views/77hc-ibv8/rows.csv?max_rows=100) |
| Host | data.medicare.gov |
| Id | 77hc-ibv8 |
| Name | Healthcare Associated Infections - Hospital |
| Category | Hospital Compare |
| Tags | hospital compare, complications |
| Created | 2014-05-13T20:53:13Z |
| Publication Date | 2016-12-19T02:07:27Z |

## Description

The?Healthcare-Associated Infection (HAI)?measures - provider data. These measures are developed by?Centers for Disease Control and Prevention (CDC)?and collected through the?National Healthcare Safety Network (NHSN). They provide information on infections that occur while the patient is in the hospital. These infections can be related to devices, such as central lines and urinary catheters, or spread from patient to patient after contact with an infected person or surface. Many healthcare associated infections can be prevented when the hospitals use?CDC-recommended infection control steps.

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type     | Render Type   |
| ======== | ============== | ==================== | ==================== | ============= | ============= |
| Yes      | series tag     | provider_id          | Provider ID          | text          | text          |
| Yes      | series tag     | hospital_name        | Hospital Name        | text          | text          |
| No       |                | address              | Address              | text          | text          |
| Yes      | series tag     | city                 | City                 | text          | text          |
| Yes      | series tag     | state                | State                | text          | text          |
| Yes      | series tag     | zip_code             | ZIP Code             | text          | text          |
| Yes      | series tag     | county_name          | County Name          | text          | text          |
| Yes      | series tag     | phone_number         | Phone Number         | phone         | phone         |
| Yes      | series tag     | measure_name         | Measure Name         | text          | text          |
| Yes      | series tag     | measure_id           | Measure ID           | text          | text          |
| Yes      | series tag     | compared_to_national | Compared to National | text          | text          |
| Yes      | numeric metric | score                | Score                | number        | text          |
| No       |                | footnote             | Footnote             | text          | text          |
| Yes      | time           | measure_start_date   | Measure Start Date   | calendar_date | calendar_date |
| No       |                | measure_end_date     | Measure End Date     | calendar_date | calendar_date |
```

## Time Field

```ls
Value = measure_start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address,footnote,measure_end_date
```

## Data Commands

```ls
series e:77hc-ibv8 d:2015-01-01T00:00:00.000Z t:hospital_name="SOUTHEAST ALABAMA MEDICAL CENTER" t:phone_number=3347938701 t:measure_id=HAI_1_CI_LOWER t:zip_code=36301 t:provider_id=010001 t:state=AL t:compared_to_national="Worse than the National Benchmark" t:county_name=HOUSTON t:measure_name="CLABSI: Lower Confidence Limit" t:city=DOTHAN m:score=1.667

series e:77hc-ibv8 d:2015-01-01T00:00:00.000Z t:hospital_name="SOUTHEAST ALABAMA MEDICAL CENTER" t:phone_number=3347938701 t:measure_id=HAI_1_CI_UPPER t:zip_code=36301 t:provider_id=010001 t:state=AL t:compared_to_national="Worse than the National Benchmark" t:county_name=HOUSTON t:measure_name="CLABSI: Upper Confidence Limit" t:city=DOTHAN m:score=4.476

series e:77hc-ibv8 d:2015-01-01T00:00:00.000Z t:hospital_name="SOUTHEAST ALABAMA MEDICAL CENTER" t:phone_number=3347938701 t:measure_id=HAI_1_DOPC_DAYS t:zip_code=36301 t:provider_id=010001 t:state=AL t:compared_to_national="Worse than the National Benchmark" t:county_name=HOUSTON t:measure_name="CLABSI: Number of Device Days" t:city=DOTHAN m:score=7117
```

## Meta Commands

```ls
entity e:77hc-ibv8 l:"Healthcare Associated Infections - Hospital" t:url=https://data.medicare.gov/api/views/77hc-ibv8

property e:77hc-ibv8 t:meta.view v:id=77hc-ibv8 v:category="Hospital Compare" v:averageRating=0 v:name="Healthcare Associated Infections - Hospital"

property e:77hc-ibv8 t:meta.view.owner v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:displayName=cms

property e:77hc-ibv8 t:meta.view.tableauthor v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:roleName=administrator v:displayName=cms

property e:77hc-ibv8 t:meta.view.metadata.custom_fields.common_core v:Publisher="Centers for Medicare & Medicaid Services (CMS)" v:Contact_Email=HospitalCompare@hsag.com v:Contact_Name=CMS v:Bureau_Code=009:38 v:Program_Code=009:078
```

## Top Records

```ls
| provider_id | hospital_name                    | address                | city   | state | zip_code | county_name | phone_number       | measure_name                                                                     | measure_id      | compared_to_national              | score  | footnote | measure_start_date  | measure_end_date    | 
| =========== | ================================ | ====================== | ====== | ===== | ======== | =========== | ================== | ================================================================================ | =============== | ================================= | ====== | ======== | =================== | =================== | 
| 010001      | SOUTHEAST ALABAMA MEDICAL CENTER | 1108 ROSS CLARK CIRCLE | DOTHAN | AL    | 36301    | HOUSTON     | [3347938701, null] | CLABSI: Lower Confidence Limit                                                   | HAI_1_CI_LOWER  | Worse than the National Benchmark | 1.667  |          | 2015-01-01T00:00:00 | 2015-12-31T00:00:00 | 
| 010001      | SOUTHEAST ALABAMA MEDICAL CENTER | 1108 ROSS CLARK CIRCLE | DOTHAN | AL    | 36301    | HOUSTON     | [3347938701, null] | CLABSI: Upper Confidence Limit                                                   | HAI_1_CI_UPPER  | Worse than the National Benchmark | 4.476  |          | 2015-01-01T00:00:00 | 2015-12-31T00:00:00 | 
| 010001      | SOUTHEAST ALABAMA MEDICAL CENTER | 1108 ROSS CLARK CIRCLE | DOTHAN | AL    | 36301    | HOUSTON     | [3347938701, null] | CLABSI: Number of Device Days                                                    | HAI_1_DOPC_DAYS | Worse than the National Benchmark | 7117   |          | 2015-01-01T00:00:00 | 2015-12-31T00:00:00 | 
| 010001      | SOUTHEAST ALABAMA MEDICAL CENTER | 1108 ROSS CLARK CIRCLE | DOTHAN | AL    | 36301    | HOUSTON     | [3347938701, null] | CLABSI: Predicted Cases                                                          | HAI_1_ELIGCASES | Worse than the National Benchmark | 5.681  |          | 2015-01-01T00:00:00 | 2015-12-31T00:00:00 | 
| 010001      | SOUTHEAST ALABAMA MEDICAL CENTER | 1108 ROSS CLARK CIRCLE | DOTHAN | AL    | 36301    | HOUSTON     | [3347938701, null] | CLABSI: Observed Cases                                                           | HAI_1_NUMERATOR | Worse than the National Benchmark | 16     |          | 2015-01-01T00:00:00 | 2015-12-31T00:00:00 | 
| 010001      | SOUTHEAST ALABAMA MEDICAL CENTER | 1108 ROSS CLARK CIRCLE | DOTHAN | AL    | 36301    | HOUSTON     | [3347938701, null] | Central line-associated bloodstream infections (CLABSI) in ICUs and select wards | HAI_1_SIR       | Worse than the National Benchmark | 2.816  |          | 2015-01-01T00:00:00 | 2015-12-31T00:00:00 | 
| 010001      | SOUTHEAST ALABAMA MEDICAL CENTER | 1108 ROSS CLARK CIRCLE | DOTHAN | AL    | 36301    | HOUSTON     | [3347938701, null] | CAUTI: Lower Confidence Limit                                                    | HAI_2_CI_LOWER  | Worse than the National Benchmark | 1.595  |          | 2015-01-01T00:00:00 | 2015-12-31T00:00:00 | 
| 010001      | SOUTHEAST ALABAMA MEDICAL CENTER | 1108 ROSS CLARK CIRCLE | DOTHAN | AL    | 36301    | HOUSTON     | [3347938701, null] | CAUTI: Upper Confidence Limit                                                    | HAI_2_CI_UPPER  | Worse than the National Benchmark | 3.313  |          | 2015-01-01T00:00:00 | 2015-12-31T00:00:00 | 
| 010001      | SOUTHEAST ALABAMA MEDICAL CENTER | 1108 ROSS CLARK CIRCLE | DOTHAN | AL    | 36301    | HOUSTON     | [3347938701, null] | CAUTI: Number of Urinary Catheter Days                                           | HAI_2_DOPC_DAYS | Worse than the National Benchmark | 14326  |          | 2015-01-01T00:00:00 | 2015-12-31T00:00:00 | 
| 010001      | SOUTHEAST ALABAMA MEDICAL CENTER | 1108 ROSS CLARK CIRCLE | DOTHAN | AL    | 36301    | HOUSTON     | [3347938701, null] | CAUTI: Predicted Cases                                                           | HAI_2_ELIGCASES | Worse than the National Benchmark | 12.407 |          | 2015-01-01T00:00:00 | 2015-12-31T00:00:00 | 
```