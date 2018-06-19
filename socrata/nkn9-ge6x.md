# NYCHA Application - Frequently Asked Questions

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nycha-application-frequently-asked-questions-e0952) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/nkn9-ge6x) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/nkn9-ge6x/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/nkn9-ge6x/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | nkn9-ge6x |
| Name | NYCHA Application - Frequently Asked Questions |
| Attribution | New York City Housing Authority (NYCHA) |
| Category | Housing & Development |
| Tags | nycha, nyc housing, public housing, application, subsidized housing |
| Created | 2013-03-28T19:31:07Z |
| Publication Date | 2013-06-21T20:48:54Z |

## Description

FAQ about applying for housing at NYCHA

## Columns

```ls
| Included | Schema Type | Field Name                  | Name                        | Data Type | Render Type |
| ======== | =========== | =========================== | =========================== | ========= | =========== |
| No       | time        | :updated_at                 | updated_at                  | meta_data | meta_data   |
| Yes      | series tag  | frequentyly_asked_questions | Frequentyly Asked Questions | text      | text        |
| Yes      | series tag  | answers                     | Answers                     | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:nkn9-ge6x d:2013-03-28T13:02:34.000Z t:frequentyly_asked_questions="How do I apply for public housing with NYCHA?" t:answers="Apply Online You may apply online at (http://apply.nycha.info) from any device with Internet access; or you may file online from any of our Walk-in centers. 

Get a Paper Application Call or visit NYCHA?s Customer Contact Center to get a paper application Submit a request to have an application mailed to you." m:row_number.nkn9-ge6x=1

series e:nkn9-ge6x d:2013-03-28T13:02:34.000Z t:frequentyly_asked_questions="Do I need to submit documents with the NYCHA public housing application?" t:answers="No, you do not need to submit documents with the NYCHA public housing application. The information you provide on your application will be verified if and when we are able to reach your application for an eligibility interview. Please do not send any documents with your application. (If you are applying for NYCHA public housing as a Victim of Domestic Violence, please see these guidelines regarding supporting documents.)" m:row_number.nkn9-ge6x=2

series e:nkn9-ge6x d:2013-03-28T13:02:34.000Z t:frequentyly_asked_questions="How will I know that my public housing application has been received by NYCHA?" t:answers="Applicants will receive a letter from NYCHA within 45 days acknowledging the date your application was received and the housing priority that you have been assigned based on the information provided in your application. If you do not receive such a letter from NYCHA, please contact the Customer Contact Center at (718)-707-7771 from 8 AM ? 5PM, Monday through Friday." m:row_number.nkn9-ge6x=3
```

## Meta Commands

```ls
metric m:row_number.nkn9-ge6x p:long l:"Row Number"

entity e:nkn9-ge6x l:"NYCHA Application - Frequently Asked Questions" t:attribution="New York City Housing Authority (NYCHA)" t:url=https://data.cityofnewyork.us/api/views/nkn9-ge6x

property e:nkn9-ge6x t:meta.view v:id=nkn9-ge6x v:category="Housing & Development" v:attributionLink=http://www.nyc.gov/html/nycha/html/assistance/generalfaq.shtml v:averageRating=0 v:name="NYCHA Application - Frequently Asked Questions" v:attribution="New York City Housing Authority (NYCHA)"

property e:nkn9-ge6x t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:nkn9-ge6x t:meta.view.tableauthor v:id=8b43-zkvh v:screenName="Ram S." v:displayName="Ram S."
```

## Top Records

```ls
| :updated_at | frequentyly_asked_questions                                                                   | answers                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | 
| =========== | ============================================================================================= | ============================================================================================================================================================================================================================================================================================================================================================================================================================================================================================ | 
| 1364475754  | How do I apply for public housing with NYCHA?                                                 | Apply Online You may apply online at (http://apply.nycha.info) from any device with Internet access; or you may file online from any of our Walk-in centers. Get a Paper Application Call or visit NYCHA?s Customer Contact Center to get a paper application Submit a request to have an application mailed to you.                                                                                                                                                                         | 
| 1364475754  | Do I need to submit documents with the NYCHA public housing application?                      | No, you do not need to submit documents with the NYCHA public housing application. The information you provide on your application will be verified if and when we are able to reach your application for an eligibility interview. Please do not send any documents with your application. (If you are applying for NYCHA public housing as a Victim of Domestic Violence, please see these guidelines regarding supporting documents.)                                                     | 
| 1364475754  | How will I know that my public housing application has been received by NYCHA?                | Applicants will receive a letter from NYCHA within 45 days acknowledging the date your application was received and the housing priority that you have been assigned based on the information provided in your application. If you do not receive such a letter from NYCHA, please contact the Customer Contact Center at (718)-707-7771 from 8 AM ? 5PM, Monday through Friday.                                                                                                             | 
| 1364475754  | How often should I file an application?                                                       | If you are still interested in applying for public housing you can re-apply every 12 months. If you have not been invited for an eligibility interview, you must file a new application every 12 months to remain on the waiting list. You will retain the filing date from your original application.                                                                                                                                                                                       | 
| 1364475754  | What is the difference between Public Housing and Section 8?                                  | Public housing apartments are owned and operated by NYCHA. More than 400,000 New Yorkers reside in one of the 178,895 apartments located around the five boroughs of New York City. The public housing waiting list has over 160,000 applications. The Section 8 Program enables eligible persons to rent privately owned apartments. Housing assistance payments are made to the private landlords. Please be aware that the Section 8 waiting list is presenting closed to new applicants. | 
| 1364475754  | Can I be on the waiting list for both Public Housing and Section 8?                           | Yes, you can apply for both programs, but once you rent an apartment with the assistance of one program, your housing priority in the program that you did not yet receive will be significantly reduced. This reduction in priority would likely mean that you will not be reached on the waiting list.                                                                                                                                                                                     | 
| 1364475754  | Do I have to be a resident of New York City to be eligible to apply for public housing?       | No, you do not have to be a resident of New York City to apply, but due to NYCHA?s long waiting list, available apartments will be offered to applicants who live or work in New York City first.                                                                                                                                                                                                                                                                                            | 
| 1364475754  | Do I have to be citizen of the United States to be eligible to apply for public housing?      | No, you do not have to be a citizen of the United States but at least one member of your household must be a United States citizen or a non-citizen with eligible immigration status (e.g Permanent Resident, Refugee/Asylum statuses).                                                                                                                                                                                                                                                      | 
| 1364475754  | How old must I be to apply for public housing?                                                | You must be at least 18 years or older, or an emancipated minor to be eligible to apply for public housing. An emancipated minor is a child who has been granted the status of adulthood by a court order or other formal arrangement. In the United States, there are three main ways for a teenager to become emancipated and they are: Court petition; Marriage and Military Service.                                                                                                     | 
| 1364475754  | Do I need to have children living in my household to be eligible to apply for public housing? | No, single adults are eligible to apply for public housing.                                                                                                                                                                                                                                                                                                                                                                                                                                  | 
```