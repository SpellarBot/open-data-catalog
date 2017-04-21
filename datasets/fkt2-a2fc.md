# University Of Hawaii - Enrollment Demographics

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/university-of-hawaii-enrollment-demographics-f403f) |
| Metadata | [Link](https://data.hawaii.gov/api/views/fkt2-a2fc) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/fkt2-a2fc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/fkt2-a2fc/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | fkt2-a2fc |
| Name | University Of Hawaii - Enrollment Demographics |
| Category | Formal Education |
| Tags | enrollment, higher education, demographics, gender, college |
| Created | 2013-08-01T20:59:52Z |
| Publication Date | 2015-09-18T18:36:18Z |

## Description

Enrollment demographics for the University of Hawaii for Fall Enrollments from Fall 2010

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| No       | time           | :updated_at       | updated_at        | meta_data | meta_data   |
| Yes      | series tag     | semester          | SEMESTER          | text      | text        |
| Yes      | series tag     | campus            | CAMPUS            | text      | text        |
| Yes      | series tag     | academic_level    | ACADEMIC LEVEL    | text      | text        |
| Yes      | series tag     | education_level   | EDUCATION LEVEL   | text      | text        |
| Yes      | series tag     | gender            | GENDER            | text      | text        |
| Yes      | series tag     | residency_status  | RESIDENCY STATUS  | text      | text        |
| Yes      | series tag     | age_group         | AGE_GROUP         | text      | text        |
| Yes      | series tag     | hawaiian_ancestry | HAWAIIAN_ANCESTRY | text      | text        |
| Yes      | numeric metric | enrollment        | ENROLLMENT        | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:fkt2-a2fc d:2015-09-18T11:32:47.000Z t:education_level=Juniors t:age_group="22-24 yrs" t:gender=Women t:academic_level=Undergraduate t:residency_status=Resident t:campus="University of Hawai`i at Manoa" t:semester="Fall 2010" m:enrollment=6

series e:fkt2-a2fc d:2015-09-18T11:32:47.000Z t:education_level=Sophomores t:age_group="20-21 yrs" t:gender=Men t:academic_level=Undergraduate t:residency_status=Resident t:campus="Hawai`i Community College" t:semester="Fall 2010" m:enrollment=2

series e:fkt2-a2fc d:2015-09-18T11:32:47.000Z t:education_level=Freshmen t:age_group="18-19 yrs" t:gender=Men t:academic_level=Undergraduate t:residency_status=Resident t:campus="Honolulu Community College" t:semester="Fall 2010" m:enrollment=20
```

## Meta Commands

```ls
metric m:enrollment p:integer l:ENROLLMENT t:dataTypeName=number

entity e:fkt2-a2fc l:"University Of Hawaii - Enrollment Demographics" t:url=https://data.hawaii.gov/api/views/fkt2-a2fc

property e:fkt2-a2fc t:meta.view v:id=fkt2-a2fc v:category="Formal Education" v:averageRating=0 v:name="University Of Hawaii - Enrollment Demographics"

property e:fkt2-a2fc t:meta.view.owner v:id=axmy-vcri v:screenName="Jared Takazawa" v:displayName="Jared Takazawa"

property e:fkt2-a2fc t:meta.view.tableauthor v:id=axmy-vcri v:screenName="Jared Takazawa" v:roleName=editor v:displayName="Jared Takazawa"
```

## Top Records

```ls
| :updated_at | semester  | campus                         | academic_level                | education_level | gender | residency_status | age_group | hawaiian_ancestry | enrollment | 
| =========== | ========= | ============================== | ============================= | =============== | ====== | ================ | ========= | ================= | ========== | 
| 1442575967  | Fall 2010 | University of Hawai`i at Manoa | Undergraduate                 | Juniors         | Women  | Resident         | 22-24 yrs |                   | 6          | 
| 1442575967  | Fall 2010 | Hawai`i Community College      | Undergraduate                 | Sophomores      | Men    | Resident         | 20-21 yrs |                   | 2          | 
| 1442575967  | Fall 2010 | Honolulu Community College     | Undergraduate                 | Freshmen        | Men    | Resident         | 18-19 yrs |                   | 20         | 
| 1442575967  | Fall 2010 | Honolulu Community College     | Undergraduate                 | Freshmen        | Men    | Resident         | 18-19 yrs |                   | 38         | 
| 1442575967  | Fall 2010 | University of Hawai`i at Hilo  | Undergraduate                 | Sophomores      | Women  | Resident         | 18-19 yrs |                   | 3          | 
| 1442575967  | Fall 2010 | Kapi`olani Community College   | Undergraduate                 | Sophomores      | Men    | Resident         | 30-34 yrs |                   | 4          | 
| 1442575967  | Fall 2010 | Hawai`i Community College      | Undergraduate                 | Freshmen        | Men    | Resident         | 18-19 yrs | HAWAIIAN          | 72         | 
| 1442575967  | Fall 2010 | University of Hawai`i at Manoa | Undergraduate                 | Seniors         | Men    | Non-Resident     | 20-21 yrs |                   | 2          | 
| 1442575967  | Fall 2010 | Leeward Community College      | Home-Based at Other UH Campus |                 | Men    | Resident         | 18-19 yrs |                   | 9          | 
| 1442575967  | Fall 2010 | Leeward Community College      | Undergraduate                 | Freshmen        | Women  | Resident         | <18 yrs   |                   | 21         | 
```