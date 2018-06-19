# Degrees and Other Formal Awards Granted by the State University of New York (SUNY) by Institution and Award Level: Beginning Academic Year 2010-11

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/degrees-and-other-formal-awards-granted-by-the-state-university-of-new-york-suny-by-ins-20) |
| Metadata | [Link](https://data.ny.gov/api/views/xnq9-9igi) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/xnq9-9igi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/xnq9-9igi/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | xnq9-9igi |
| Name | Degrees and Other Formal Awards Granted by the State University of New York (SUNY) by Institution and Award Level: Beginning Academic Year 2010-11 |
| Attribution | SUNY System Administration, Office of Institutional Research |
| Category | Education |
| Tags | suny institutions, degrees and awards, higher education |
| Created | 2013-03-06T15:10:16Z |
| Publication Date | 2016-09-09T21:07:34Z |

## Description

This dataset records the number and type of degrees awarded by the State University of New York by award type and institution.

## Columns

```ls
| Included | Schema Type    | Field Name                             | Name                                   | Data Type | Render Type |
| ======== | ============== | ====================================== | ====================================== | ========= | =========== |
| Yes      | series tag     | academic_year                          | Academic Year                          | text      | text        |
| Yes      | series tag     | campus_type                            | Campus Type                            | text      | text        |
| Yes      | series tag     | campus                                 | Campus                                 | text      | text        |
| Yes      | numeric metric | undergraduate_certificates             | Undergraduate Certificates             | number    | number      |
| Yes      | numeric metric | associate_s_degrees                    | Associate's Degrees                    | number    | number      |
| Yes      | numeric metric | bachelor_s_degrees                     | Bachelor's Degrees                     | number    | number      |
| Yes      | numeric metric | master_s_degrees                       | Master's Degrees                       | number    | number      |
| Yes      | numeric metric | doctoral_research_scholarship_degrees  | Doctoral Research/Scholarship Degrees  | number    | number      |
| Yes      | numeric metric | doctoral_professional_practice_degrees | Doctoral/Professional Practice Degrees | number    | number      |
| Yes      | numeric metric | graduate_certificates                  | Graduate Certificates                  | number    | number      |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:xnq9-9igi d:2010-01-01T00:00:00.000Z t:academic_year=2010-2011 t:campus_type=1 t:campus="Doctoral Degree Granting Institutions" m:bachelor_s_degrees=0 m:graduate_certificates=0 m:master_s_degrees=3113 m:doctoral_professional_practice_degrees=154 m:doctoral_research_scholarship_degrees=1268 m:associate_s_degrees=0

series e:xnq9-9igi d:2010-01-01T00:00:00.000Z t:academic_year=2010-2011 t:campus_type=1 t:campus="Doctoral Degree Granting Institutions" m:bachelor_s_degrees=0 m:graduate_certificates=0 m:master_s_degrees=135 m:doctoral_professional_practice_degrees=7 m:doctoral_research_scholarship_degrees=26 m:associate_s_degrees=0

series e:xnq9-9igi d:2010-01-01T00:00:00.000Z t:academic_year=2010-2011 t:campus_type=1 t:campus="Doctoral Degree Granting Institutions" m:bachelor_s_degrees=0 m:graduate_certificates=0 m:master_s_degrees=2990 m:doctoral_professional_practice_degrees=140 m:doctoral_research_scholarship_degrees=893 m:associate_s_degrees=0
```

## Meta Commands

```ls
metric m:undergraduate_certificates p:long l:"Undergraduate Certificates" t:dataTypeName=number

metric m:associate_s_degrees p:integer l:"Associate's Degrees" t:dataTypeName=number

metric m:bachelor_s_degrees p:integer l:"Bachelor's Degrees" t:dataTypeName=number

metric m:master_s_degrees p:integer l:"Master's Degrees" t:dataTypeName=number

metric m:doctoral_research_scholarship_degrees p:integer l:"Doctoral Research/Scholarship Degrees" t:dataTypeName=number

metric m:doctoral_professional_practice_degrees p:integer l:"Doctoral/Professional Practice Degrees" t:dataTypeName=number

metric m:graduate_certificates p:integer l:"Graduate Certificates" t:dataTypeName=number

entity e:xnq9-9igi l:"Degrees and Other Formal Awards Granted by the State University of New York (SUNY) by Institution and Award Level: Beginning Academic Year 2010-11" t:attribution="SUNY System Administration, Office of Institutional Research" t:url=https://data.ny.gov/api/views/xnq9-9igi

property e:xnq9-9igi t:meta.view v:id=xnq9-9igi v:category=Education v:attributionLink=http://www.suny.edu/ v:averageRating=0 v:name="Degrees and Other Formal Awards Granted by the State University of New York (SUNY) by Institution and Award Level: Beginning Academic Year 2010-11" v:attribution="SUNY System Administration, Office of Institutional Research"

property e:xnq9-9igi t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:xnq9-9igi t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:xnq9-9igi t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| academic_year | campus_type | campus                                | undergraduate_certificates | associate_s_degrees | bachelor_s_degrees | master_s_degrees | doctoral_research_scholarship_degrees | doctoral_professional_practice_degrees | graduate_certificates | 
| ============= | =========== | ===================================== | ========================== | =================== | ================== | ================ | ===================================== | ====================================== | ===================== | 
| 2010-2011     | 1           | Doctoral Degree Granting Institutions |                            | 0                   | 0                  | 3113             | 1268                                  | 154                                    | 0                     | 
| 2010-2011     | 1           | Doctoral Degree Granting Institutions |                            | 0                   | 0                  | 135              | 26                                    | 7                                      | 0                     | 
| 2010-2011     | 1           | Doctoral Degree Granting Institutions |                            | 0                   | 0                  | 2990             | 893                                   | 140                                    | 0                     | 
| 2010-2011     | 1           | Doctoral Degree Granting Institutions |                            | 14                  | 0                  | 4370             | 2122                                  | 357                                    | 591                   | 
| 2010-2011     | 1           | Doctoral Degree Granting Institutions |                            | 0                   | 0                  | 1487             | 349                                   | 173                                    | 87                    | 
| 2010-2011     | 1           | Doctoral Degree Granting Institutions |                            | 0                   | 0                  | 187              | 165                                   | 31                                     | 192                   | 
| 2010-2011     | 1           | Doctoral Degree Granting Institutions |                            | 0                   | 45                 | 349              | 91                                    | 20                                     | 0                     | 
| 2010-2011     | 1           | Doctoral Degree Granting Institutions |                            | 0                   | 0                  | 0                | 8                                     | 0                                      | 65                    | 
| 2010-2011     | 1           | Doctoral Degree Granting Institutions |                            | 0                   | 0                  | 3697             | 1839                                  | 301                                    | 259                   | 
| 2010-2011     | 1           | Doctoral Degree Granting Institutions |                            | 0                   | 0                  | 122              | 72                                    | 74                                     | 156                   | 
```