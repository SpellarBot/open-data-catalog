# Timely and Effective Care - Hospital

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/timely-and-effective-care-hospital-e4aad) |
| Metadata | [Link](https://data.medicare.gov/api/views/yv7e-xc69) |
| Data: JSON | [100 Rows](https://data.medicare.gov/api/views/yv7e-xc69/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicare.gov/api/views/yv7e-xc69/rows.csv?max_rows=100) |
| Host | data.medicare.gov |
| Id | yv7e-xc69 |
| Name | Timely and Effective Care - Hospital |
| Category | Hospital Compare |
| Tags | hospital compare, timely and effective care |
| Created | 2014-05-14T14:52:28Z |
| Publication Date | 2016-12-19T02:20:06Z |

## Description

Timely and Effective Care measures - provider data. This data set includes provider-level data for measures of heart attack care, heart failure care, pneumonia care, surgical care, emergency department care, preventive care, children?s asthma care, stroke care, blood clot prevention and treatment, and pregnancy and delivery care.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type     | Render Type   |
| ======== | ============== | ================== | ================== | ============= | ============= |
| Yes      | series tag     | provider_id        | Provider ID        | text          | text          |
| Yes      | series tag     | hospital_name      | Hospital Name      | text          | text          |
| No       |                | address            | Address            | text          | text          |
| Yes      | series tag     | city               | City               | text          | text          |
| Yes      | series tag     | state              | State              | text          | text          |
| Yes      | series tag     | zip_code           | ZIP Code           | text          | text          |
| Yes      | series tag     | county_name        | County Name        | text          | text          |
| Yes      | series tag     | phone_number       | Phone Number       | phone         | phone         |
| Yes      | series tag     | condition          | Condition          | text          | text          |
| Yes      | series tag     | measure_id         | Measure ID         | text          | text          |
| Yes      | series tag     | measure_name       | Measure Name       | text          | text          |
| Yes      | series tag     | score              | Score              | text          | text          |
| Yes      | numeric metric | sample             | Sample             | number        | text          |
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
Excluded Fields = address,footnote,measure_end_date
```

## Data Commands

```ls
series e:yv7e-xc69 d:2015-04-01T00:00:00.000Z t:hospital_name="SOUTHEAST ALABAMA MEDICAL CENTER" t:phone_number=3347938701 t:measure_id=ED_1b t:zip_code=36301 t:provider_id=010001 t:condition="Emergency Department" t:state=AL t:score=270 t:county_name=HOUSTON t:measure_name=ED1 t:city=DOTHAN m:sample=545

series e:yv7e-xc69 d:2015-04-01T00:00:00.000Z t:hospital_name="SOUTHEAST ALABAMA MEDICAL CENTER" t:phone_number=3347938701 t:measure_id=ED_2b t:zip_code=36301 t:provider_id=010001 t:condition="Emergency Department" t:state=AL t:score=74 t:county_name=HOUSTON t:measure_name=ED2 t:city=DOTHAN m:sample=545

series e:yv7e-xc69 d:2015-10-01T00:00:00.000Z t:hospital_name="SOUTHEAST ALABAMA MEDICAL CENTER" t:phone_number=3347938701 t:measure_id=IMM_2 t:zip_code=36301 t:provider_id=010001 t:condition="Preventive Care" t:state=AL t:score=95 t:county_name=HOUSTON t:measure_name="Immunization for influenza" t:city=DOTHAN m:sample=554
```

## Meta Commands

```ls
entity e:yv7e-xc69 l:"Timely and Effective Care - Hospital" t:url=https://data.medicare.gov/api/views/yv7e-xc69

property e:yv7e-xc69 t:meta.view v:id=yv7e-xc69 v:category="Hospital Compare" v:averageRating=0 v:name="Timely and Effective Care - Hospital"

property e:yv7e-xc69 t:meta.view.owner v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:displayName=cms

property e:yv7e-xc69 t:meta.view.tableauthor v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:roleName=administrator v:displayName=cms

property e:yv7e-xc69 t:meta.view.metadata.custom_fields.common_core v:Publisher="Centers for Medicare & Medicaid Services (CMS)" v:Contact_Email=HospitalCompare@hsag.com v:Contact_Name=CMS v:Bureau_Code=009:38 v:Program_Code=009:078
```

## Top Records

```ls
| provider_id | hospital_name                    | address                | city   | state | zip_code | county_name | phone_number       | condition                  | measure_id             | measure_name                                                  | score                                    | sample        | footnote                                                                                                       | measure_start_date  | measure_end_date    | 
| =========== | ================================ | ====================== | ====== | ===== | ======== | =========== | ================== | ========================== | ====================== | ============================================================= | ======================================== | ============= | ============================================================================================================== | =================== | =================== | 
| 010001      | SOUTHEAST ALABAMA MEDICAL CENTER | 1108 ROSS CLARK CIRCLE | DOTHAN | AL    | 36301    | HOUSTON     | [3347938701, null] | Emergency Department       | ED_1b                  | ED1                                                           | 270                                      | 545           | 2 - Data submitted were based on a sample of cases/patients.                                                   | 2015-04-01T00:00:00 | 2016-03-31T00:00:00 | 
| 010001      | SOUTHEAST ALABAMA MEDICAL CENTER | 1108 ROSS CLARK CIRCLE | DOTHAN | AL    | 36301    | HOUSTON     | [3347938701, null] | Emergency Department       | ED_2b                  | ED2                                                           | 74                                       | 545           | 2 - Data submitted were based on a sample of cases/patients.                                                   | 2015-04-01T00:00:00 | 2016-03-31T00:00:00 | 
| 010001      | SOUTHEAST ALABAMA MEDICAL CENTER | 1108 ROSS CLARK CIRCLE | DOTHAN | AL    | 36301    | HOUSTON     | [3347938701, null] | Emergency Department       | EDV                    | Emergency department volume                                   | High (40,000 - 59,999 patients annually) |               |                                                                                                                | 2015-01-01T00:00:00 | 2015-12-31T00:00:00 | 
| 010001      | SOUTHEAST ALABAMA MEDICAL CENTER | 1108 ROSS CLARK CIRCLE | DOTHAN | AL    | 36301    | HOUSTON     | [3347938701, null] | Preventive Care            | IMM_2                  | Immunization for influenza                                    | 95                                       | 554           | 2 - Data submitted were based on a sample of cases/patients.                                                   | 2015-10-01T00:00:00 | 2016-03-31T00:00:00 | 
| 010001      | SOUTHEAST ALABAMA MEDICAL CENTER | 1108 ROSS CLARK CIRCLE | DOTHAN | AL    | 36301    | HOUSTON     | [3347938701, null] | Preventive Care            | IMM_3_OP_27_FAC_ADHPCT | Healthcare workers given influenza vaccination                | 81                                       | 3791          |                                                                                                                | 2015-10-01T00:00:00 | 2016-03-31T00:00:00 | 
| 010001      | SOUTHEAST ALABAMA MEDICAL CENTER | 1108 ROSS CLARK CIRCLE | DOTHAN | AL    | 36301    | HOUSTON     | [3347938701, null] | Heart Attack or Chest Pain | OP_1                   | Median Time to Fibrinolysis                                   | Not Available                            | Not Available | 3 - Results are based on a shorter time period than required., 7 - No cases met the criteria for this measure. | 2015-04-01T00:00:00 | 2016-03-31T00:00:00 | 
| 010001      | SOUTHEAST ALABAMA MEDICAL CENTER | 1108 ROSS CLARK CIRCLE | DOTHAN | AL    | 36301    | HOUSTON     | [3347938701, null] | Emergency Department       | OP_18b                 | OP 18                                                         | 201                                      | 372           |                                                                                                                | 2015-04-01T00:00:00 | 2016-03-31T00:00:00 | 
| 010001      | SOUTHEAST ALABAMA MEDICAL CENTER | 1108 ROSS CLARK CIRCLE | DOTHAN | AL    | 36301    | HOUSTON     | [3347938701, null] | Heart Attack or Chest Pain | OP_2                   | Fibrinolytic Therapy Received Within 30 Minutes of ED Arrival | Not Available                            | Not Available | 3 - Results are based on a shorter time period than required., 7 - No cases met the criteria for this measure. | 2015-04-01T00:00:00 | 2016-03-31T00:00:00 | 
| 010001      | SOUTHEAST ALABAMA MEDICAL CENTER | 1108 ROSS CLARK CIRCLE | DOTHAN | AL    | 36301    | HOUSTON     | [3347938701, null] | Emergency Department       | OP_20                  | Door to diagnostic eval                                       | 66                                       | 374           |                                                                                                                | 2015-04-01T00:00:00 | 2016-03-31T00:00:00 | 
| 010001      | SOUTHEAST ALABAMA MEDICAL CENTER | 1108 ROSS CLARK CIRCLE | DOTHAN | AL    | 36301    | HOUSTON     | [3347938701, null] | Emergency Department       | OP_21                  | Median time to pain med                                       | 86                                       | 118           |                                                                                                                | 2015-04-01T00:00:00 | 2016-03-31T00:00:00 | 
```