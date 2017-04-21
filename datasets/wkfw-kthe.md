# Outpatient Imaging Efficiency - Hospital

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/outpatient-imaging-efficiency-hospital-e4de1) |
| Metadata | [Link](https://data.medicare.gov/api/views/wkfw-kthe) |
| Data: JSON | [100 Rows](https://data.medicare.gov/api/views/wkfw-kthe/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicare.gov/api/views/wkfw-kthe/rows.csv?max_rows=100) |
| Host | data.medicare.gov |
| Id | wkfw-kthe |
| Name | Outpatient Imaging Efficiency - Hospital |
| Category | Hospital Compare |
| Tags | hospital compare, medical imaging, quality, ratings, mri, ct, mammogram, ultrasound, use of medical imaging |
| Created | 2014-05-14T14:14:57Z |
| Publication Date | 2016-12-19T02:12:05Z |

## Description

Use of medical imaging - provider data. These measures give you information about hospitals' use of medical imaging tests for outpatients. Examples of medical imaging tests include CT Scans, MRIs, and mammograms.

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
| Yes      | series tag     | measure_id         | Measure ID         | text          | text          |
| Yes      | series tag     | measure_name       | Measure Name       | text          | text          |
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
Excluded Fields = address,footnote,measure_end_date
```

## Data Commands

```ls
series e:wkfw-kthe d:2014-07-01T00:00:00.000Z t:hospital_name="SOUTHEAST ALABAMA MEDICAL CENTER" t:phone_number=3347938701 t:measure_id=OP_10 t:zip_code=36301 t:provider_id=010001 t:state=AL t:county_name=HOUSTON t:measure_name="Abdomen CT Use of Contrast Material" t:city=DOTHAN m:score=6.4

series e:wkfw-kthe d:2014-07-01T00:00:00.000Z t:hospital_name="SOUTHEAST ALABAMA MEDICAL CENTER" t:phone_number=3347938701 t:measure_id=OP_11 t:zip_code=36301 t:provider_id=010001 t:state=AL t:county_name=HOUSTON t:measure_name="Thorax CT Use of Contrast Material" t:city=DOTHAN m:score=0.9

series e:wkfw-kthe d:2014-07-01T00:00:00.000Z t:hospital_name="SOUTHEAST ALABAMA MEDICAL CENTER" t:phone_number=3347938701 t:measure_id=OP_13 t:zip_code=36301 t:provider_id=010001 t:state=AL t:county_name=HOUSTON t:measure_name="Outpatients who got cardiac imaging stress tests before low-risk outpatient surgery" t:city=DOTHAN m:score=7.1
```

## Meta Commands

```ls
entity e:wkfw-kthe l:"Outpatient Imaging Efficiency - Hospital" t:url=https://data.medicare.gov/api/views/wkfw-kthe

property e:wkfw-kthe t:meta.view v:id=wkfw-kthe v:category="Hospital Compare" v:averageRating=0 v:name="Outpatient Imaging Efficiency - Hospital"

property e:wkfw-kthe t:meta.view.owner v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:displayName=cms

property e:wkfw-kthe t:meta.view.tableauthor v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:roleName=administrator v:displayName=cms

property e:wkfw-kthe t:meta.view.metadata.custom_fields.common_core v:Publisher="Centers for Medicare & Medicaid Services (CMS)" v:Contact_Email=HospitalCompare@hsag.com v:Contact_Name=CMS v:Bureau_Code=009:38 v:Program_Code=009:078
```

## Top Records

```ls
| provider_id | hospital_name                    | address                    | city   | state | zip_code | county_name | phone_number       | measure_id | measure_name                                                                        | score | footnote | measure_start_date  | measure_end_date    | 
| =========== | ================================ | ========================== | ====== | ===== | ======== | =========== | ================== | ========== | =================================================================================== | ===== | ======== | =================== | =================== | 
| 010001      | SOUTHEAST ALABAMA MEDICAL CENTER | 1108 ROSS CLARK CIRCLE     | DOTHAN | AL    | 36301    | HOUSTON     | [3347938701, null] | OP_10      | Abdomen CT Use of Contrast Material                                                 | 6.4   |          | 2014-07-01T00:00:00 | 2015-06-30T00:00:00 | 
| 010001      | SOUTHEAST ALABAMA MEDICAL CENTER | 1108 ROSS CLARK CIRCLE     | DOTHAN | AL    | 36301    | HOUSTON     | [3347938701, null] | OP_11      | Thorax CT Use of Contrast Material                                                  | 0.9   |          | 2014-07-01T00:00:00 | 2015-06-30T00:00:00 | 
| 010001      | SOUTHEAST ALABAMA MEDICAL CENTER | 1108 ROSS CLARK CIRCLE     | DOTHAN | AL    | 36301    | HOUSTON     | [3347938701, null] | OP_13      | Outpatients who got cardiac imaging stress tests before low-risk outpatient surgery | 7.1   |          | 2014-07-01T00:00:00 | 2015-06-30T00:00:00 | 
| 010001      | SOUTHEAST ALABAMA MEDICAL CENTER | 1108 ROSS CLARK CIRCLE     | DOTHAN | AL    | 36301    | HOUSTON     | [3347938701, null] | OP_14      | Outpatients with brain CT scans who got a sinus CT scan at the same time            | 2.4   |          | 2014-07-01T00:00:00 | 2015-06-30T00:00:00 | 
| 010001      | SOUTHEAST ALABAMA MEDICAL CENTER | 1108 ROSS CLARK CIRCLE     | DOTHAN | AL    | 36301    | HOUSTON     | [3347938701, null] | OP_8       | MRI Lumbar Spine for Low Back Pain                                                  | 38.1  |          | 2014-07-01T00:00:00 | 2015-06-30T00:00:00 | 
| 010001      | SOUTHEAST ALABAMA MEDICAL CENTER | 1108 ROSS CLARK CIRCLE     | DOTHAN | AL    | 36301    | HOUSTON     | [3347938701, null] | OP_9       | Mammography Follow-up Rates                                                         | 6.9   |          | 2014-07-01T00:00:00 | 2015-06-30T00:00:00 | 
| 010005      | MARSHALL MEDICAL CENTER SOUTH    | 2505 U S HIGHWAY 431 NORTH | BOAZ   | AL    | 35957    | MARSHALL    | [2565938310, null] | OP_10      | Abdomen CT Use of Contrast Material                                                 | 13.3  |          | 2014-07-01T00:00:00 | 2015-06-30T00:00:00 | 
| 010005      | MARSHALL MEDICAL CENTER SOUTH    | 2505 U S HIGHWAY 431 NORTH | BOAZ   | AL    | 35957    | MARSHALL    | [2565938310, null] | OP_11      | Thorax CT Use of Contrast Material                                                  | 10.2  |          | 2014-07-01T00:00:00 | 2015-06-30T00:00:00 | 
| 010005      | MARSHALL MEDICAL CENTER SOUTH    | 2505 U S HIGHWAY 431 NORTH | BOAZ   | AL    | 35957    | MARSHALL    | [2565938310, null] | OP_13      | Outpatients who got cardiac imaging stress tests before low-risk outpatient surgery | 5.3   |          | 2014-07-01T00:00:00 | 2015-06-30T00:00:00 | 
| 010005      | MARSHALL MEDICAL CENTER SOUTH    | 2505 U S HIGHWAY 431 NORTH | BOAZ   | AL    | 35957    | MARSHALL    | [2565938310, null] | OP_14      | Outpatients with brain CT scans who got a sinus CT scan at the same time            | 4.0   |          | 2014-07-01T00:00:00 | 2015-06-30T00:00:00 | 
```