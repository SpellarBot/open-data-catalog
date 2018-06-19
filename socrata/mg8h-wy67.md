# Restraint and Seclusion: 2012-13

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/restraint-and-seclusion-2012-13) |
| Metadata | [Link](https://data.ct.gov/api/views/mg8h-wy67) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/mg8h-wy67/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/mg8h-wy67/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | mg8h-wy67 |
| Name | Restraint and Seclusion: 2012-13 |
| Attribution | State Department of Education |
| Category | Education |
| Tags | restraint, seclusion, ctkids |
| Created | 2014-09-03T15:08:28Z |
| Publication Date | 2014-09-03T15:21:35Z |

## Description

This dataset contains data on the use of physical restraint and seclusion in Connecticut for the 2012-13 school year. The total number of restraint and seclusion incidents as well as an unduplicated count of students restrained and/or secluded is provided for each district/organization. Data for districts/organizations reporting incidents for fewer than 6 students have been suppressed. For districts/organizations reporting incidents for 6 or more students, disaggregation by the available subgroups is provided. *Please note that if a student had an incident in more than one district/organization, he/she is only counted once in the statewide student count and statewide subgroup counts. The full text of the Annual Report on the Use of Physical Restraint and Seclusion in Connecticut can be found at: http://www.sde.ct.gov/sde/lib/sde/pdf/deps/special/restraint_and_seclusion_annual_report_2012_13.pdf

## Columns

```ls
| Included | Schema Type    | Field Name                                | Name                                      | Data Type | Render Type |
| ======== | ============== | ========================================= | ========================================= | ========= | =========== |
| Yes      | series tag     | district_number_if_applicable             | District Number (if applicable)           | text      | text        |
| Yes      | series tag     | district_organization_name                | District/Organization Name                | text      | text        |
| Yes      | numeric metric | count_of_restraint_seclusion_incidents    | Count of Restraint/Seclusion Incidents    | number    | number      |
| Yes      | numeric metric | count_of_students_restrained_or_secluded  | Count of Students Restrained or Secluded  | number    | number      |
| Yes      | numeric metric | prekindergarten                           | Prekindergarten                           | number    | number      |
| Yes      | numeric metric | kindergarten                              | Kindergarten                              | number    | number      |
| Yes      | numeric metric | grade_1                                   | Grade 1                                   | number    | number      |
| Yes      | numeric metric | grade_2                                   | Grade 2                                   | number    | number      |
| Yes      | numeric metric | grade_3                                   | Grade 3                                   | number    | number      |
| Yes      | numeric metric | grade_4                                   | Grade 4                                   | number    | number      |
| Yes      | numeric metric | grade_5                                   | Grade 5                                   | number    | number      |
| Yes      | numeric metric | grade_6                                   | Grade 6                                   | number    | number      |
| Yes      | numeric metric | grade_7                                   | Grade 7                                   | number    | number      |
| Yes      | numeric metric | grade_8                                   | Grade 8                                   | number    | number      |
| Yes      | numeric metric | grade_9                                   | Grade 9                                   | number    | number      |
| Yes      | numeric metric | grade_10                                  | Grade 10                                  | number    | number      |
| Yes      | numeric metric | grade_11                                  | Grade 11                                  | number    | number      |
| Yes      | numeric metric | grade_12                                  | Grade 12                                  | number    | number      |
| Yes      | numeric metric | female                                    | Female                                    | number    | number      |
| Yes      | numeric metric | male                                      | Male                                      | number    | number      |
| Yes      | numeric metric | american_indian_or_alaska_native          | American Indian or Alaska Native          | number    | number      |
| Yes      | numeric metric | asian                                     | Asian                                     | number    | number      |
| Yes      | numeric metric | black_or_african_american                 | Black or African American                 | number    | number      |
| Yes      | numeric metric | hispanic_latino_of_any_race               | Hispanic Latino of any Race               | number    | number      |
| Yes      | numeric metric | native_hawaiian_or_other_pacific_islander | Native Hawaiian or Other Pacific Islander | number    | number      |
| Yes      | numeric metric | two_or_more_races                         | Two or More Races                         | number    | number      |
| Yes      | numeric metric | white                                     | White                                     | number    | number      |
| Yes      | numeric metric | consent_for_evaluation                    | Consent For Evaluation                    | number    | number      |
| Yes      | numeric metric | iep                                       | IEP                                       | number    | number      |
| Yes      | numeric metric | total_student_count                       | Total Student Count                       | number    | number      |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:mg8h-wy67 d:2012-01-01T00:00:00.000Z t:district_organization_name="The Bridge Academy District" t:district_number_if_applicable=269 m:black_or_african_american=0 m:total_student_count=0 m:count_of_restraint_seclusion_incidents=0 m:male=0 m:white=0 m:grade_3=0 m:grade_2=0 m:hispanic_latino_of_any_race=0 m:grade_1=0 m:american_indian_or_alaska_native=0 m:two_or_more_races=0 m:iep=0 m:grade_7=0 m:grade_6=0 m:grade_5=0 m:count_of_students_restrained_or_secluded=0 m:asian=0 m:grade_4=0 m:grade_8=0 m:grade_12=0 m:grade_9=0 m:grade_11=0 m:native_hawaiian_or_other_pacific_islander=0 m:female=0 m:kindergarten=0 m:grade_10=0 m:consent_for_evaluation=0 m:prekindergarten=0

series e:mg8h-wy67 d:2012-01-01T00:00:00.000Z t:district_organization_name=Franklin t:district_number_if_applicable=53 m:black_or_african_american=0 m:total_student_count=0 m:count_of_restraint_seclusion_incidents=0 m:male=0 m:white=0 m:grade_3=0 m:grade_2=0 m:hispanic_latino_of_any_race=0 m:grade_1=0 m:american_indian_or_alaska_native=0 m:two_or_more_races=0 m:iep=0 m:grade_7=0 m:grade_6=0 m:grade_5=0 m:count_of_students_restrained_or_secluded=0 m:asian=0 m:grade_4=0 m:grade_8=0 m:grade_12=0 m:grade_9=0 m:grade_11=0 m:native_hawaiian_or_other_pacific_islander=0 m:female=0 m:kindergarten=0 m:grade_10=0 m:consent_for_evaluation=0 m:prekindergarten=0

series e:mg8h-wy67 d:2012-01-01T00:00:00.000Z t:district_organization_name=Andover t:district_number_if_applicable=1 m:black_or_african_american=0 m:total_student_count=0 m:count_of_restraint_seclusion_incidents=0 m:male=0 m:white=0 m:grade_3=0 m:grade_2=0 m:hispanic_latino_of_any_race=0 m:grade_1=0 m:american_indian_or_alaska_native=0 m:two_or_more_races=0 m:iep=0 m:grade_7=0 m:grade_6=0 m:grade_5=0 m:count_of_students_restrained_or_secluded=0 m:asian=0 m:grade_4=0 m:grade_8=0 m:grade_12=0 m:grade_9=0 m:grade_11=0 m:native_hawaiian_or_other_pacific_islander=0 m:female=0 m:kindergarten=0 m:grade_10=0 m:consent_for_evaluation=0 m:prekindergarten=0
```

## Meta Commands

```ls
metric m:count_of_restraint_seclusion_incidents p:integer l:"Count of Restraint/Seclusion Incidents" t:dataTypeName=number

metric m:count_of_students_restrained_or_secluded p:integer l:"Count of Students Restrained or Secluded" t:dataTypeName=number

metric m:prekindergarten p:integer l:Prekindergarten t:dataTypeName=number

metric m:kindergarten p:integer l:Kindergarten t:dataTypeName=number

metric m:grade_1 p:integer l:"Grade 1" t:dataTypeName=number

metric m:grade_2 p:integer l:"Grade 2" t:dataTypeName=number

metric m:grade_3 p:integer l:"Grade 3" t:dataTypeName=number

metric m:grade_4 p:integer l:"Grade 4" t:dataTypeName=number

metric m:grade_5 p:integer l:"Grade 5" t:dataTypeName=number

metric m:grade_6 p:integer l:"Grade 6" t:dataTypeName=number

metric m:grade_7 p:integer l:"Grade 7" t:dataTypeName=number

metric m:grade_8 p:integer l:"Grade 8" t:dataTypeName=number

metric m:grade_9 p:integer l:"Grade 9" t:dataTypeName=number

metric m:grade_10 p:integer l:"Grade 10" t:dataTypeName=number

metric m:grade_11 p:integer l:"Grade 11" t:dataTypeName=number

metric m:grade_12 p:integer l:"Grade 12" t:dataTypeName=number

metric m:female p:integer l:Female t:dataTypeName=number

metric m:male p:integer l:Male t:dataTypeName=number

metric m:american_indian_or_alaska_native p:integer l:"American Indian or Alaska Native" t:dataTypeName=number

metric m:asian p:integer l:Asian t:dataTypeName=number

metric m:black_or_african_american p:integer l:"Black or African American" t:dataTypeName=number

metric m:hispanic_latino_of_any_race p:integer l:"Hispanic Latino of any Race" t:dataTypeName=number

metric m:native_hawaiian_or_other_pacific_islander p:integer l:"Native Hawaiian or Other Pacific Islander" t:dataTypeName=number

metric m:two_or_more_races p:integer l:"Two or More Races" t:dataTypeName=number

metric m:white p:integer l:White t:dataTypeName=number

metric m:consent_for_evaluation p:integer l:"Consent For Evaluation" t:dataTypeName=number

metric m:iep p:integer l:IEP t:dataTypeName=number

metric m:total_student_count p:integer l:"Total Student Count" t:dataTypeName=number

entity e:mg8h-wy67 l:"Restraint and Seclusion: 2012-13" t:attribution="State Department of Education" t:url=https://data.ct.gov/api/views/mg8h-wy67

property e:mg8h-wy67 t:meta.view v:id=mg8h-wy67 v:category=Education v:averageRating=0 v:name="Restraint and Seclusion: 2012-13" v:attribution="State Department of Education"

property e:mg8h-wy67 t:meta.view.owner v:id=nyku-jy9c v:screenName="Stephanie O'Day" v:displayName="Stephanie O'Day"

property e:mg8h-wy67 t:meta.view.tableauthor v:id=nyku-jy9c v:screenName="Stephanie O'Day" v:roleName=editor v:displayName="Stephanie O'Day"
```

## Top Records

```ls
| district_number_if_applicable | district_organization_name  | count_of_restraint_seclusion_incidents | count_of_students_restrained_or_secluded | prekindergarten | kindergarten | grade_1 | grade_2 | grade_3 | grade_4 | grade_5 | grade_6 | grade_7 | grade_8 | grade_9 | grade_10 | grade_11 | grade_12 | female | male | american_indian_or_alaska_native | asian | black_or_african_american | hispanic_latino_of_any_race | native_hawaiian_or_other_pacific_islander | two_or_more_races | white | consent_for_evaluation | iep | total_student_count | 
| ============================= | =========================== | ====================================== | ======================================== | =============== | ============ | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======== | ======== | ======== | ====== | ==== | ================================ | ===== | ========================= | =========================== | ========================================= | ================= | ===== | ====================== | === | =================== | 
| 269                           | The Bridge Academy District | 0                                      | 0                                        | 0               | 0            | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0        | 0        | 0        | 0      | 0    | 0                                | 0     | 0                         | 0                           | 0                                         | 0                 | 0     | 0                      | 0   | 0                   | 
| 53                            | Franklin                    | 0                                      | 0                                        | 0               | 0            | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0        | 0        | 0        | 0      | 0    | 0                                | 0     | 0                         | 0                           | 0                                         | 0                 | 0     | 0                      | 0   | 0                   | 
| 1                             | Andover                     | 0                                      | 0                                        | 0               | 0            | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0        | 0        | 0        | 0      | 0    | 0                                | 0     | 0                         | 0                           | 0                                         | 0                 | 0     | 0                      | 0   | 0                   | 
| 2                             | Ansonia                     | 0                                      | 0                                        | 0               | 0            | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0        | 0        | 0        | 0      | 0    | 0                                | 0     | 0                         | 0                           | 0                                         | 0                 | 0     | 0                      | 0   | 0                   | 
| 3                             | Ashford                     |                                        |                                          |                 |              |         |         |         |         |         |         |         |         |         |          |          |          |        |      |                                  |       |                           |                             |                                           |                   |       |                        |     |                     | 
| 4                             | Avon                        |                                        |                                          |                 |              |         |         |         |         |         |         |         |         |         |          |          |          |        |      |                                  |       |                           |                             |                                           |                   |       |                        |     |                     | 
| 5                             | Barkhamsted                 | 0                                      | 0                                        | 0               | 0            | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0        | 0        | 0        | 0      | 0    | 0                                | 0     | 0                         | 0                           | 0                                         | 0                 | 0     | 0                      | 0   | 0                   | 
| 7                             | Berlin                      |                                        |                                          |                 |              |         |         |         |         |         |         |         |         |         |          |          |          |        |      |                                  |       |                           |                             |                                           |                   |       |                        |     |                     | 
| 8                             | Bethany                     |                                        |                                          |                 |              |         |         |         |         |         |         |         |         |         |          |          |          |        |      |                                  |       |                           |                             |                                           |                   |       |                        |     |                     | 
| 9                             | Bethel                      |                                        |                                          |                 |              |         |         |         |         |         |         |         |         |         |          |          |          |        |      |                                  |       |                           |                             |                                           |                   |       |                        |     |                     | 
```