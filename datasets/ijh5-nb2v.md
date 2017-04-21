# Measures of Rehospitalization, Emergency Room Visit, and Community Discharge

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/measures-of-rehospitalization-emergency-room-visit-and-community-discharge) |
| Metadata | [Link](https://data.medicare.gov/api/views/ijh5-nb2v) |
| Data: JSON | [100 Rows](https://data.medicare.gov/api/views/ijh5-nb2v/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicare.gov/api/views/ijh5-nb2v/rows.csv?max_rows=100) |
| Host | data.medicare.gov |
| Id | ijh5-nb2v |
| Name | Measures of Rehospitalization, Emergency Room Visit, and Community Discharge |
| Category | Nursing Home Compare |
| Tags | nhc, nursing home, quality, measures, ratings, quality measures |
| Created | 2016-04-13T18:12:47Z |
| Publication Date | 2017-03-22T01:54:28Z |

## Description

Measures of the Rate of Rehospitalization, Emergency Room Visit, and Community Discharge for Medicare Beneficiaries. These rates are based on Medicare claims data.

## Columns

```ls
| Included | Schema Type    | Field Name                               | Name                                     | Data Type | Render Type |
| ======== | ============== | ======================================== | ======================================== | ========= | =========== |
| No       | time           | :updated_at                              | updated_at                               | meta_data | meta_data   |
| Yes      | series tag     | federal_provider_number                  | Federal Provider Number                  | text      | text        |
| Yes      | series tag     | provider_name                            | Provider Name                            | text      | text        |
| No       |                | provider_address                         | Provider Address                         | text      | text        |
| Yes      | series tag     | provider_city                            | Provider City                            | text      | text        |
| Yes      | series tag     | provider_state                           | Provider State                           | text      | text        |
| Yes      | series tag     | provider_zip_code                        | Provider Zip Code                        | text      | text        |
| Yes      | series tag     | measure_code                             | Measure Code                             | text      | text        |
| Yes      | series tag     | measure_description                      | Measure Description                      | text      | text        |
| Yes      | series tag     | resident_type                            | Resident type                            | text      | text        |
| Yes      | numeric metric | adjusted_score                           | Adjusted Score                           | number    | number      |
| Yes      | numeric metric | observed_score                           | Observed Score                           | number    | number      |
| Yes      | numeric metric | expected_score                           | Expected Score                           | number    | number      |
| No       |                | footnote_for_score                       | Footnote for Score                       | text      | text        |
| Yes      | series tag     | used_in_quality_measure_five_star_rating | Used in Quality Measure Five Star Rating | checkbox  | checkbox    |
| Yes      | series tag     | measure_period                           | Measure Period                           | text      | text        |
| No       |                | processing_date                          | Processing Date                          | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = provider_address,footnote_for_score,processing_date
```

## Data Commands

```ls
series e:ijh5-nb2v d:2017-03-13T19:16:08.000Z t:resident_type="Short Stay" t:measure_period=2015Q1-2015Q4 t:used_in_quality_measure_five_star_rating=true t:federal_provider_number=015019 t:measure_code=521 t:measure_description="Percentage of short-stay residents who were rehospitalized after a nursing home admission" t:provider_zip_code=36025 t:provider_state=AL t:provider_name="MERRY WOOD LODGE CARE AND REHABILITATION CENTER" t:provider_city=ELMORE m:observed_score=25.714287 m:adjusted_score=21.517844 m:expected_score=27.229142

series e:ijh5-nb2v d:2017-03-13T19:16:08.000Z t:resident_type="Short Stay" t:measure_period=2015Q1-2015Q4 t:used_in_quality_measure_five_star_rating=true t:federal_provider_number=015019 t:measure_code=522 t:measure_description="Percentage of short-stay residents who had an outpatient emergency department visit" t:provider_zip_code=36025 t:provider_state=AL t:provider_name="MERRY WOOD LODGE CARE AND REHABILITATION CENTER" t:provider_city=ELMORE m:observed_score=14.285715 m:adjusted_score=12.65201 m:expected_score=12.972988

series e:ijh5-nb2v d:2017-03-13T19:16:08.000Z t:resident_type="Short Stay" t:measure_period=2015Q1-2015Q4 t:used_in_quality_measure_five_star_rating=true t:federal_provider_number=015187 t:measure_code=521 t:measure_description="Percentage of short-stay residents who were rehospitalized after a nursing home admission" t:provider_zip_code=35474 t:provider_state=AL t:provider_name="MOUNDVILLE HEALTH AND REHABILITATION, LLC" t:provider_city=MOUNDVILLE m:observed_score=25.806451 m:adjusted_score=25.643593 m:expected_score=22.930188
```

## Meta Commands

```ls
metric m:adjusted_score p:float l:"Adjusted Score" t:dataTypeName=number

metric m:observed_score p:float l:"Observed Score" t:dataTypeName=number

metric m:expected_score p:double l:"Expected Score" t:dataTypeName=number

entity e:ijh5-nb2v l:"Measures of Rehospitalization, Emergency Room Visit, and Community Discharge" t:url=https://data.medicare.gov/api/views/ijh5-nb2v

property e:ijh5-nb2v t:meta.view v:id=ijh5-nb2v v:category="Nursing Home Compare" v:averageRating=0 v:name="Measures of Rehospitalization, Emergency Room Visit, and Community Discharge"

property e:ijh5-nb2v t:meta.view.owner v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:displayName=cms

property e:ijh5-nb2v t:meta.view.tableauthor v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:roleName=administrator v:displayName=cms

property e:ijh5-nb2v t:meta.view.metadata.custom_fields.common_core v:Publisher="Centers for Medicare & Medicaid Services (CMS)" v:Contact_Email=Edward.Mortimore@cms.hhs.gov v:Contact_Name=CMS v:Bureau_Code=009:38 v:Program_Code=009:078
```

## Top Records

```ls
| :updated_at | federal_provider_number | provider_name                                   | provider_address          | provider_city | provider_state | provider_zip_code | measure_code | measure_description                                                                       | resident_type | adjusted_score | observed_score | expected_score | footnote_for_score                                                                                 | used_in_quality_measure_five_star_rating | measure_period | processing_date | 
| =========== | ======================= | =============================================== | ========================= | ============= | ============== | ================= | ============ | ========================================================================================= | ============= | ============== | ============== | ============== | ================================================================================================== | ======================================== | ============== | =============== | 
| 1489432568  | 015019                  | MERRY WOOD LODGE CARE AND REHABILITATION CENTER | P O BOX 130               | ELMORE        | AL             | 36025             | 521          | Percentage of short-stay residents who were rehospitalized after a nursing home admission | Short Stay    | 21.517844      | 25.714287      | 27.229142      |                                                                                                    | true                                     | 2015Q1-2015Q4  | 2017-03-01      | 
| 1489432568  | 015019                  | MERRY WOOD LODGE CARE AND REHABILITATION CENTER | P O BOX 130               | ELMORE        | AL             | 36025             | 522          | Percentage of short-stay residents who had an outpatient emergency department visit       | Short Stay    | 12.652010      | 14.285715      | 12.972988      |                                                                                                    | true                                     | 2015Q1-2015Q4  | 2017-03-01      | 
| 1489432568  | 015019                  | MERRY WOOD LODGE CARE AND REHABILITATION CENTER | P O BOX 130               | ELMORE        | AL             | 36025             | 523          | Percentage of short-stay residents who were successfully discharged to the community      | Short Stay    |                |                |                | The number of residents is too small to report. Call the facility to discuss this quality measure. | true                                     | 2015Q1-2015Q4  | 2017-03-01      | 
| 1489432568  | 015187                  | MOUNDVILLE HEALTH AND REHABILITATION, LLC       | THIRD AVENUE P O BOX 607  | MOUNDVILLE    | AL             | 35474             | 521          | Percentage of short-stay residents who were rehospitalized after a nursing home admission | Short Stay    | 25.643593      | 25.806451      | 22.930188      |                                                                                                    | true                                     | 2015Q1-2015Q4  | 2017-03-01      | 
| 1489432568  | 015187                  | MOUNDVILLE HEALTH AND REHABILITATION, LLC       | THIRD AVENUE P O BOX 607  | MOUNDVILLE    | AL             | 35474             | 522          | Percentage of short-stay residents who had an outpatient emergency department visit       | Short Stay    | 7.357227       | 8.064516       | 12.593943      |                                                                                                    | true                                     | 2015Q1-2015Q4  | 2017-03-01      | 
| 1489432568  | 015187                  | MOUNDVILLE HEALTH AND REHABILITATION, LLC       | THIRD AVENUE P O BOX 607  | MOUNDVILLE    | AL             | 35474             | 523          | Percentage of short-stay residents who were successfully discharged to the community      | Short Stay    | 58.243871      | 60.606062      | 60.440779      |                                                                                                    | true                                     | 2015Q1-2015Q4  | 2017-03-01      | 
| 1489432568  | 015188                  | JACKSON HEALTH CARE FACILITY                    | 2616 NORTH COLLEGE AVENUE | JACKSON       | AL             | 36545             | 521          | Percentage of short-stay residents who were rehospitalized after a nursing home admission | Short Stay    | 29.244363      | 23.529412      | 18.332730      |                                                                                                    | true                                     | 2015Q1-2015Q4  | 2017-03-01      | 
| 1489432568  | 015188                  | JACKSON HEALTH CARE FACILITY                    | 2616 NORTH COLLEGE AVENUE | JACKSON       | AL             | 36545             | 522          | Percentage of short-stay residents who had an outpatient emergency department visit       | Short Stay    | 7.198368       | 7.352941       | 11.736122      |                                                                                                    | true                                     | 2015Q1-2015Q4  | 2017-03-01      | 
| 1489432568  | 015188                  | JACKSON HEALTH CARE FACILITY                    | 2616 NORTH COLLEGE AVENUE | JACKSON       | AL             | 36545             | 523          | Percentage of short-stay residents who were successfully discharged to the community      | Short Stay    | 56.665808      | 54.545456      | 55.911571      |                                                                                                    | true                                     | 2015Q1-2015Q4  | 2017-03-01      | 
| 1489432568  | 015374                  | CAMDEN NURSING FACILITY INC.                    | 210 PONDEROSA DRIVE       | CAMDEN        | AL             | 36726             | 521          | Percentage of short-stay residents who were rehospitalized after a nursing home admission | Short Stay    | 23.360027      | 24.074075      | 23.481968      |                                                                                                    | true                                     | 2015Q1-2015Q4  | 2017-03-01      | 
```