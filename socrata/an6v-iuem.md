# NYCHA Resident Jobs Programs and Training

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nycha-resident-jobs-programs-and-training-a2892) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/an6v-iuem) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/an6v-iuem/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/an6v-iuem/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | an6v-iuem |
| Name | NYCHA Resident Jobs Programs and Training |
| Attribution | New York City Housing Authority (NYCHA) |
| Category | Social Services |
| Tags | nycha, nyc housing, job preparation, job training, job readiness |
| Created | 2013-03-28T19:31:09Z |
| Publication Date | 2013-03-28T21:01:56Z |

## Description

Job preparation or training programs

## Columns

```ls
| Included | Schema Type | Field Name          | Name                | Data Type | Render Type |
| ======== | =========== | =================== | =================== | ========= | =========== |
| No       | time        | :updated_at         | updated_at          | meta_data | meta_data   |
| Yes      | series tag  | program_name        | Program Name        | text      | text        |
| Yes      | series tag  | program_description | Program Description | text      | text        |
| Yes      | series tag  | program_details     | Program Details     | text      | text        |
| Yes      | series tag  | eligibility         | Eligibility         | text      | text        |
| Yes      | series tag  | locations           | Locations           | text      | text        |
| Yes      | series tag  | contact             | Contact             | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:an6v-iuem d:2013-03-28T13:03:37.000Z t:program_details="Employment-Related Services
? Client Enrollment, Assessment, Orientation.
? Job readiness, job search assistance and training.
? Job development, placement and retention/advancement support.
? Referrals for social supports.

Financial Incentives that ?Make Work Pay?
? Increasing awareness and take up of EID.
? Ensuring residents take advantages of work supports such as ?.
? Child support services such as ?
? Financial counseling services.

Community Support for Work
? The strengthening of social ties among residents and community stakeholders to support
residents? job preparation and work efforts." t:program_description="Jobs-Plus is an employment program that was created to work with all working-age residents in designated public housing developments or a cluster of developments.  The goal of the Jobs-Plus program is to raise the levels of employment and earnings among New York City public housing communities.  Services are limited only to residents who live in a Jobs-Plus designated development." t:locations="Jobs-Plus at BronxWorks
Serving residents of Betances, Moore Houses and East 152nd Street-Courtlandt Houses the South Bronx.

Operated by BronxWorks.
Funded by the NYC Center for Economic Opportunity." t:program_name="Jobs-Plus at BronxWorks" t:contact="(718) 289-8100" m:row_number.an6v-iuem=1

series e:an6v-iuem d:2013-03-28T13:03:37.000Z t:program_details="Employment-Related Services
? Client Enrollment, Assessment, Orientation.
? Job readiness, job search assistance and training.
? Job development, placement and retention/advancement support.
? Referrals for social supports.

Financial Incentives that ?Make Work Pay?
? Increasing awareness and take up of EID.
? Ensuring residents take advantages of work supports such as ?.
? Child support services such as ?
? Financial counseling services.

Community Support for Work
? The strengthening of social ties among residents and community stakeholders to support
residents? job preparation and work efforts." t:program_description="Jobs-Plus is an employment program that was created to work with all working-age residents in designated public housing developments or a cluster of developments.  The goal of the Jobs-Plus program is to raise the levels of employment and earnings among New York City public housing communities.  Services are limited only to residents who live in a Jobs-Plus designated development." t:locations="Jefferson Houses Jobs-Plus
Serving residents of Jefferson Houses in East Harlem.

Operated by Hostos Community College.
Funded by the Department of Human Resources Administration." t:program_name="Jobs-Plus at Jefferson Houses" t:contact="(718) 289-8100" m:row_number.an6v-iuem=2

series e:an6v-iuem d:2013-03-28T13:03:37.000Z t:program_description="The NYCHA Resident Training Academy (NRTA) provides employment-linked training opportunities and job placement assistance to NYCHA residents in the construction, pest control, maintenance, and janitorial fields. The NRTA works with successful graduates of the Academy to provide job placement assistance by focusing on jobs with career paths. Past NRTA graduates have obtained jobs at NYCHA in positions such as Caretakers and Pest Control Technicians, and with NYCHA contractors and affordable housing developers in the various construction trades." t:program_name="NYCHA RESIDENT TRAINING ACADEMY (NRTA) - Janitorial" t:eligibility="Minimum Requirements for Caretaker (Janitorial) Training
? NYCHA resident on the lease
? 18 years of age or older
? Ability to score a 6.0 reading and math level on the Test of Adult Basic Education (T.A.B.E.)
? Ability to pass a drug test
? Ability to perform eight (8) hours of physical work each day" t:contact="(718) 289-8100" m:row_number.an6v-iuem=3
```

## Meta Commands

```ls
metric m:row_number.an6v-iuem p:long l:"Row Number"

entity e:an6v-iuem l:"NYCHA Resident Jobs Programs and Training" t:attribution="New York City Housing Authority (NYCHA)" t:url=https://data.cityofnewyork.us/api/views/an6v-iuem

property e:an6v-iuem t:meta.view v:id=an6v-iuem v:category="Social Services" v:averageRating=0 v:name="NYCHA Resident Jobs Programs and Training" v:attribution="New York City Housing Authority (NYCHA)"

property e:an6v-iuem t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:an6v-iuem t:meta.view.tableauthor v:id=8b43-zkvh v:screenName="Ram S." v:displayName="Ram S."
```

## Top Records

```ls
| :updated_at | program_name                                          | program_description                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | program_details                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | eligibility                                                                                                                                                                                                                                                                                                                        | locations                                                                                                                                                                                               | contact        | 
| =========== | ===================================================== | ===================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================== | ========================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================== | ================================================================================================================================================================================================================================================================================================================================== | ======================================================================================================================================================================================================= | ============== | 
| 1364475817  | Jobs-Plus at BronxWorks                               | Jobs-Plus is an employment program that was created to work with all working-age residents in designated public housing developments or a cluster of developments. The goal of the Jobs-Plus program is to raise the levels of employment and earnings among New York City public housing communities. Services are limited only to residents who live in a Jobs-Plus designated development.                                                                                                                                                                         | Employment-Related Services ? Client Enrollment, Assessment, Orientation. ? Job readiness, job search assistance and training. ? Job development, placement and retention/advancement support. ? Referrals for social supports. Financial Incentives that ?Make Work Pay? ? Increasing awareness and take up of EID. ? Ensuring residents take advantages of work supports such as ?. ? Child support services such as ? ? Financial counseling services. Community Support for Work ? The strengthening of social ties among residents and community stakeholders to support residents? job preparation and work efforts. |                                                                                                                                                                                                                                                                                                                                    | Jobs-Plus at BronxWorks Serving residents of Betances, Moore Houses and East 152nd Street-Courtlandt Houses the South Bronx. Operated by BronxWorks. Funded by the NYC Center for Economic Opportunity. | (718) 289-8100 | 
| 1364475817  | Jobs-Plus at Jefferson Houses                         | Jobs-Plus is an employment program that was created to work with all working-age residents in designated public housing developments or a cluster of developments. The goal of the Jobs-Plus program is to raise the levels of employment and earnings among New York City public housing communities. Services are limited only to residents who live in a Jobs-Plus designated development.                                                                                                                                                                         | Employment-Related Services ? Client Enrollment, Assessment, Orientation. ? Job readiness, job search assistance and training. ? Job development, placement and retention/advancement support. ? Referrals for social supports. Financial Incentives that ?Make Work Pay? ? Increasing awareness and take up of EID. ? Ensuring residents take advantages of work supports such as ?. ? Child support services such as ? ? Financial counseling services. Community Support for Work ? The strengthening of social ties among residents and community stakeholders to support residents? job preparation and work efforts. |                                                                                                                                                                                                                                                                                                                                    | Jefferson Houses Jobs-Plus Serving residents of Jefferson Houses in East Harlem. Operated by Hostos Community College. Funded by the Department of Human Resources Administration.                      | (718) 289-8100 | 
| 1364475817  | NYCHA RESIDENT TRAINING ACADEMY (NRTA) - Janitorial   | The NYCHA Resident Training Academy (NRTA) provides employment-linked training opportunities and job placement assistance to NYCHA residents in the construction, pest control, maintenance, and janitorial fields. The NRTA works with successful graduates of the Academy to provide job placement assistance by focusing on jobs with career paths. Past NRTA graduates have obtained jobs at NYCHA in positions such as Caretakers and Pest Control Technicians, and with NYCHA contractors and affordable housing developers in the various construction trades. |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | Minimum Requirements for Caretaker (Janitorial) Training ? NYCHA resident on the lease ? 18 years of age or older ? Ability to score a 6.0 reading and math level on the Test of Adult Basic Education (T.A.B.E.) ? Ability to pass a drug test ? Ability to perform eight (8) hours of physical work each day                     |                                                                                                                                                                                                         | (718) 289-8100 | 
| 1364475817  | NYCHA RESIDENT TRAINING ACADEMY (NRTA) - Construction | The NYCHA Resident Training Academy (NRTA) provides employment-linked training opportunities and job placement assistance to NYCHA residents in the construction, pest control, maintenance, and janitorial fields. The NRTA works with successful graduates of the Academy to provide job placement assistance by focusing on jobs with career paths. Past NRTA graduates have obtained jobs at NYCHA in positions such as Caretakers and Pest Control Technicians, and with NYCHA contractors and affordable housing developers in the various construction trades. |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | Minimum Requirements for Construction Training ? NYCHA resident on the lease ? 18 years of age or older ? High school diploma or GED ? Ability to score a 7.0 reading and math level on the T.A.B.E. ? Ability to pass a drug test ? Ability to lift 50 lbs or more ? Ability to perform eight (8) hours of physical work each day |                                                                                                                                                                                                         | (718) 289-8100 | 
| 1364475817  | REES Information Sessions                             | NYCHA?s Office of Resident Economic Empowerment & Sustainability (REES) develops and implements programs, policies and collaborations to measurably support residents? increased economic opportunities with a focus on employment and advancement, financial literacy and asset building, adult education and training, and business development.                                                                                                                                                                                                                    | General REES Information Sessions are held twice a week on Tuesdays and Thursdays at 8:30 a.m. You will be greeted by REES staff and asked to attend a short presentation where you will receive an overview of all of REES? available services, which include referrals for employment, training, GED and ESOL classes available through a NYCHA Community Center, financial counseling, and appointments to attend the Test of Adult Basic Education (T.A.B.E.), which is the first step in the application process for the NYCHA Resident Training Academy (NRTA).                                                      | To receive services, you must be an authorized NYCHA resident. Documents Needed for Your Appointment: Valid photo ID (examples include: a DMV issued ID)                                                                                                                                                                           | 787 Atlantic Ave., 2nd Fl., Brooklyn, NY 11238                                                                                                                                                          | (718) 289-8100 | 
```