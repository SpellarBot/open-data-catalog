# New York City Health and Hospitals Corporation (HHC) Patient Satisfaction - 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/new-york-city-health-and-hospitals-corporation-hhc-patient-satisfaction-2009-820cc) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/hi3x-y76v) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/hi3x-y76v/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/hi3x-y76v/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | hi3x-y76v |
| Name | New York City Health and Hospitals Corporation (HHC) Patient Satisfaction - 2009 |
| Attribution | Health and Hospitals Corporation (HHC) |
| Category | Health |
| Tags | health, patient, satisfaction, consumer, healthcare, healthcare provider, survey, hospital, medicare, medicaid, gcahps, healthy living |
| Created | 2011-09-30T17:30:12Z |
| Publication Date | 2011-10-11T19:49:46Z |

## Description

Patient satisfaction at HHC hospitals is measured by a standardized survey known as the Hospital Consumer Assessment of Healthcare Providers & Systems (HCAHPS). The survey has been validated by the federal Centers for Medicare and Medicaid Services (CMS) as a standard assessment tool for all hospitals throughout the nation. This data shows patient satisfaction scores in HHC hospitals.
Update Frequency: Annually

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                      | Data Type | Render Type |
| ======== | ============== | ========================= | ========================= | ========= | =========== |
| Yes      | series tag     | hospital_name             | Hospital Name             | text      | text        |
| Yes      | series tag     | hcahps_question           | HCAHPS Question           | text      | text        |
| Yes      | series tag     | hcahps_answer_description | HCAHPS Answer Description | text      | text        |
| Yes      | numeric metric | hcahps_answer_percent     | HCAHPS Answer Percent     | number    | number      |
```

## Time Field

```ls
Value = 2009
Format & Zone = yyyy
```

## Data Commands

```ls
series e:hi3x-y76v d:2009-01-01T00:00:00.000Z t:hospital_name="BELLEVUE HOSPITAL CENTER" t:hcahps_question="How often were the patients rooms and bathrooms kept clean?" t:hcahps_answer_description="Room was ""always"" clean" m:hcahps_answer_percent=56

series e:hi3x-y76v d:2009-01-01T00:00:00.000Z t:hospital_name="CONEY ISLAND HOSPITAL" t:hcahps_question="How often were the patients rooms and bathrooms kept clean?" t:hcahps_answer_description="Room was ""always"" clean" m:hcahps_answer_percent=64

series e:hi3x-y76v d:2009-01-01T00:00:00.000Z t:hospital_name="ELMHURST HOSPITAL CENTER" t:hcahps_question="How often were the patients rooms and bathrooms kept clean?" t:hcahps_answer_description="Room was ""always"" clean" m:hcahps_answer_percent=57
```

## Meta Commands

```ls
metric m:hcahps_answer_percent p:integer l:"HCAHPS Answer Percent" t:dataTypeName=number

entity e:hi3x-y76v l:"New York City Health and Hospitals Corporation (HHC) Patient Satisfaction - 2009" t:attribution="Health and Hospitals Corporation (HHC)" t:url=https://data.cityofnewyork.us/api/views/hi3x-y76v

property e:hi3x-y76v t:meta.view v:id=hi3x-y76v v:category=Health v:averageRating=0 v:name="New York City Health and Hospitals Corporation (HHC) Patient Satisfaction - 2009" v:attribution="Health and Hospitals Corporation (HHC)"

property e:hi3x-y76v t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:hi3x-y76v t:meta.view.tableauthor v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```

## Top Records

```ls
| hospital_name                          | hcahps_question                                             | hcahps_answer_description | hcahps_answer_percent | 
| ====================================== | =========================================================== | ========================= | ===================== | 
| BELLEVUE HOSPITAL CENTER               | How often were the patients rooms and bathrooms kept clean? | Room was "always" clean   | 56                    | 
| CONEY ISLAND HOSPITAL                  | How often were the patients rooms and bathrooms kept clean? | Room was "always" clean   | 64                    | 
| ELMHURST HOSPITAL CENTER               | How often were the patients rooms and bathrooms kept clean? | Room was "always" clean   | 57                    | 
| HARLEM HOSPITAL CENTER                 | How often were the patients rooms and bathrooms kept clean? | Room was "always" clean   | 61                    | 
| JACOBI MEDICAL CENTER                  | How often were the patients rooms and bathrooms kept clean? | Room was "always" clean   | 63                    | 
| KINGS COUNTY HOSPITAL CENTER           | How often were the patients rooms and bathrooms kept clean? | Room was "always" clean   | 73                    | 
| LINCOLN MEDICAL & MENTAL HEALTH CENTER | How often were the patients rooms and bathrooms kept clean? | Room was "always" clean   | 65                    | 
| METROPOLITAN HOSPITAL CENTER           | How often were the patients rooms and bathrooms kept clean? | Room was "always" clean   | 63                    | 
| NORTH CENTRAL BRONX HOSPITAL           | How often were the patients rooms and bathrooms kept clean? | Room was "always" clean   | 62                    | 
| QUEENS HOSPITAL CENTER                 | How often were the patients rooms and bathrooms kept clean? | Room was "always" clean   | 68                    | 
```