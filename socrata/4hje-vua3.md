# Structural Measures - Hospital

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/structural-measures-hospital-48b18) |
| Metadata | [Link](https://data.medicare.gov/api/views/4hje-vua3) |
| Data: JSON | [100 Rows](https://data.medicare.gov/api/views/4hje-vua3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicare.gov/api/views/4hje-vua3/rows.csv?max_rows=100) |
| Host | data.medicare.gov |
| Id | 4hje-vua3 |
| Name | Structural Measures - Hospital |
| Category | Hospital Compare |
| Tags | hospital compare, structural measures, quality, ratings, cardiac, heart, surgery, general information |
| Created | 2014-05-14T14:51:13Z |
| Publication Date | 2016-12-19T02:15:17Z |

## Description

A list of hospitals and the availability of structural measures at that hospital. A structural measure reflects the environment in which hospitals care for patients. For example, whether or not a hospital participates in a Cardiac Surgery Registry.

## Columns

```ls
| Included | Schema Type | Field Name         | Name               | Data Type     | Render Type   |
| ======== | =========== | ================== | ================== | ============= | ============= |
| Yes      | series tag  | provider_id        | Provider ID        | text          | text          |
| Yes      | series tag  | hospital_name      | Hospital Name      | text          | text          |
| No       |             | address            | Address            | text          | text          |
| Yes      | series tag  | city               | City               | text          | text          |
| Yes      | series tag  | state              | State              | text          | text          |
| Yes      | series tag  | zip_code           | ZIP Code           | text          | text          |
| Yes      | series tag  | county_name        | County Name        | text          | text          |
| Yes      | series tag  | phone_number       | Phone Number       | phone         | phone         |
| Yes      | series tag  | measure_name       | Measure Name       | text          | text          |
| Yes      | series tag  | measure_id         | Measure ID         | text          | text          |
| Yes      | series tag  | measure_response   | Measure Response   | text          | text          |
| No       |             | footnote           | Footnote           | text          | text          |
| Yes      | time        | measure_start_date | Measure Start Date | calendar_date | calendar_date |
| No       |             | measure_end_date   | Measure End Date   | calendar_date | calendar_date |
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
series e:4hje-vua3 d:2015-01-01T00:00:00.000Z t:hospital_name="SOUTHEAST ALABAMA MEDICAL CENTER" t:phone_number=3347938701 t:measure_id=OP_12 t:zip_code=36301 t:provider_id=010001 t:state=AL t:county_name=HOUSTON t:measure_response=Yes t:measure_name="Able to receive lab results electronically" t:city=DOTHAN m:row_number.4hje-vua3=1

series e:4hje-vua3 d:2015-01-01T00:00:00.000Z t:hospital_name="SOUTHEAST ALABAMA MEDICAL CENTER" t:phone_number=3347938701 t:measure_id=OP_17 t:zip_code=36301 t:provider_id=010001 t:state=AL t:county_name=HOUSTON t:measure_response=No t:measure_name="Able to track patients? lab results, tests, and referrals electronically between visits" t:city=DOTHAN m:row_number.4hje-vua3=2

series e:4hje-vua3 d:2015-01-01T00:00:00.000Z t:hospital_name="SOUTHEAST ALABAMA MEDICAL CENTER" t:phone_number=3347938701 t:measure_id=OP_25 t:zip_code=36301 t:provider_id=010001 t:state=AL t:county_name=HOUSTON t:measure_response=Yes t:measure_name="Safe surgery checklist use (outpatient)" t:city=DOTHAN m:row_number.4hje-vua3=3
```

## Meta Commands

```ls
metric m:row_number.4hje-vua3 p:long l:"Row Number"

entity e:4hje-vua3 l:"Structural Measures - Hospital" t:url=https://data.medicare.gov/api/views/4hje-vua3

property e:4hje-vua3 t:meta.view v:id=4hje-vua3 v:category="Hospital Compare" v:averageRating=0 v:name="Structural Measures - Hospital"

property e:4hje-vua3 t:meta.view.owner v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:displayName=cms

property e:4hje-vua3 t:meta.view.tableauthor v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:roleName=administrator v:displayName=cms

property e:4hje-vua3 t:meta.view.metadata.custom_fields.common_core v:Publisher="Centers for Medicare & Medicaid Services (CMS)" v:Contact_Email=HospitalCompare@hsag.com v:Contact_Name=CMS v:Bureau_Code=009:38 v:Program_Code=009:078
```

## Top Records

```ls
| provider_id | hospital_name                    | address                    | city   | state | zip_code | county_name | phone_number       | measure_name                                                                            | measure_id       | measure_response | footnote | measure_start_date  | measure_end_date    | 
| =========== | ================================ | ========================== | ====== | ===== | ======== | =========== | ================== | ======================================================================================= | ================ | ================ | ======== | =================== | =================== | 
| 010001      | SOUTHEAST ALABAMA MEDICAL CENTER | 1108 ROSS CLARK CIRCLE     | DOTHAN | AL    | 36301    | HOUSTON     | [3347938701, null] | Able to receive lab results electronically                                              | OP_12            | Yes              |          | 2015-01-01T00:00:00 | 2015-12-31T00:00:00 | 
| 010001      | SOUTHEAST ALABAMA MEDICAL CENTER | 1108 ROSS CLARK CIRCLE     | DOTHAN | AL    | 36301    | HOUSTON     | [3347938701, null] | Able to track patients? lab results, tests, and referrals electronically between visits | OP_17            | No               |          | 2015-01-01T00:00:00 | 2015-12-31T00:00:00 | 
| 010001      | SOUTHEAST ALABAMA MEDICAL CENTER | 1108 ROSS CLARK CIRCLE     | DOTHAN | AL    | 36301    | HOUSTON     | [3347938701, null] | Safe surgery checklist use (outpatient)                                                 | OP_25            | Yes              |          | 2015-01-01T00:00:00 | 2015-12-31T00:00:00 | 
| 010001      | SOUTHEAST ALABAMA MEDICAL CENTER | 1108 ROSS CLARK CIRCLE     | DOTHAN | AL    | 36301    | HOUSTON     | [3347938701, null] | General Surgery Registry                                                                | SM_PART_GEN_SURG | N                |          | 2015-01-01T00:00:00 | 2015-12-31T00:00:00 | 
| 010001      | SOUTHEAST ALABAMA MEDICAL CENTER | 1108 ROSS CLARK CIRCLE     | DOTHAN | AL    | 36301    | HOUSTON     | [3347938701, null] | Nursing care registry                                                                   | SM_PART_NURSE    | Y                |          | 2015-01-01T00:00:00 | 2015-12-31T00:00:00 | 
| 010001      | SOUTHEAST ALABAMA MEDICAL CENTER | 1108 ROSS CLARK CIRCLE     | DOTHAN | AL    | 36301    | HOUSTON     | [3347938701, null] | Safe surgery checklist use (inpatient)                                                  | SM_SS_CHECK      | Y                |          | 2015-01-01T00:00:00 | 2015-12-31T00:00:00 | 
| 010005      | MARSHALL MEDICAL CENTER SOUTH    | 2505 U S HIGHWAY 431 NORTH | BOAZ   | AL    | 35957    | MARSHALL    | [2565938310, null] | Able to receive lab results electronically                                              | OP_12            | Yes              |          | 2015-01-01T00:00:00 | 2015-12-31T00:00:00 | 
| 010005      | MARSHALL MEDICAL CENTER SOUTH    | 2505 U S HIGHWAY 431 NORTH | BOAZ   | AL    | 35957    | MARSHALL    | [2565938310, null] | Able to track patients? lab results, tests, and referrals electronically between visits | OP_17            | Yes              |          | 2015-01-01T00:00:00 | 2015-12-31T00:00:00 | 
| 010005      | MARSHALL MEDICAL CENTER SOUTH    | 2505 U S HIGHWAY 431 NORTH | BOAZ   | AL    | 35957    | MARSHALL    | [2565938310, null] | Safe surgery checklist use (outpatient)                                                 | OP_25            | Yes              |          | 2015-01-01T00:00:00 | 2015-12-31T00:00:00 | 
| 010005      | MARSHALL MEDICAL CENTER SOUTH    | 2505 U S HIGHWAY 431 NORTH | BOAZ   | AL    | 35957    | MARSHALL    | [2565938310, null] | General Surgery Registry                                                                | SM_PART_GEN_SURG | N                |          | 2015-01-01T00:00:00 | 2015-12-31T00:00:00 | 
```