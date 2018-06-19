# Disclosure Report Developers of Major City Projects Filings

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/disclosure-report-developers-of-major-city-projects-filings-f7205) |
| Metadata | [Link](https://data.sfgov.org/api/views/mqks-ty4r) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/mqks-ty4r/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/mqks-ty4r/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | mqks-ty4r |
| Name | Disclosure Report Developers of Major City Projects Filings |
| Attribution | San Francisco Ethics Commission |
| Category | City Management and Ethics |
| Tags | major developers city projects non-profits affiliate |
| Created | 2014-07-14T18:33:09Z |
| Publication Date | 2016-12-13T22:10:05Z |

## Description

Effective July 26, 2014, City law impose reporting requirements on developers of certain City real estate projects with an estimated construction cost of more than $1,000,000.  Developers must file five forms with the Ethics Commission over the course of about a year disclosing donations to nonprofit organizations that have contacted City officials about their project.  The first form is due within 30 days of certification of an Environmental Impact Report (???EIR??) by a local agency or, if the project relies on a program EIR, within 30 days of the adoption of a final environmental determination under the California Environmental Quality Act.  Disclosure is not required for a residential development project with four or fewer dwelling units. A disclosure report must be completed and filed by the developer of any ???major project.?? A major project is a real estate development project located in the City and County of San Francisco with estimated construction costs exceeding $1,000,000 where either:The Planning Commission or any other local lead agency certifies an Environmental Impact Review (???EIR??) for the project under the California Environmental Quality Act (???CEQA??); or  The project relies on a program EIR and the Planning Department, Planning Commission, or any other local lead agency adopts any final environmental determination under CEQA.  (See below to determine when a final environmental determination is adopted.)A major project does not include a residential development project with four or fewer dwelling units.For purposes of this filing requirement, a ???developer?? includes the individual or entity that is the project sponsor responsible for filing a completed Environmental Evaluation Application (???EEA??) with the Planning Department (or other lead agency) under CEQA.  However, if an individual who signs and submits the EEA will not be responsible for obtaining the entitlements or developing the major project, the developer is instead the individual or entity that is responsible for obtaining such entitlements.A developer must use the SFEC 3500 form to file a total of five reports with the Ethics Commission with respect to each major project.  The first (or initial) report must be filed within 30 days of the date the Planning Commission or any other local lead agency certifies the EIR for that project or, for a major project relying on a program EIR, within 30 days of the date that the Planning Department, Planning Commission, or any other local lead agency adopts a final environmental determination under CEQA.1The developer must also use this form to file four subsequent quarterly reports, beginning with the quarter in which in the initial report is filed.  The due dates for the quarterly reports are:April 15 for the period starting January 1 and ending March 31;July 15 for the period starting April 1 and ending June 30;October 15 for the period starting July 1 and ending September 30; andJanuary 15 for the period starting October 1 and ending December 31.

## Columns

```ls
| Included | Schema Type | Field Name                      | Name                            | Data Type     | Render Type   |
| ======== | =========== | =============================== | =============================== | ============= | ============= |
| Yes      | series tag  | name_of_developer               | Name of Developer               | text          | text          |
| Yes      | series tag  | report                          | Report                          | document      | document      |
| Yes      | series tag  | report_number                   | Report Number                   | text          | number        |
| Yes      | time        | period_start_date               | Period Start Date               | calendar_date | calendar_date |
| No       |             | period_end_date                 | Period End Date                 | calendar_date | calendar_date |
| Yes      | series tag  | amendment_filing                | Amendment Filing                | checkbox      | checkbox      |
| No       |             | filed_date                      | Filed Date                      | calendar_date | calendar_date |
| No       |             | amendment_to_report_filed       | Amendment to Report Filed       | calendar_date | calendar_date |
| Yes      | series tag  | planning_department_case_number | Planning Department Case Number | text          | text          |
| Yes      | series tag  | activity                        | Activity                        | checkbox      | checkbox      |
```

## Time Field

```ls
Value = period_start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = period_end_date,filed_date,amendment_to_report_filed
```

## Data Commands

```ls
series e:mqks-ty4r d:2012-05-09T00:00:00.000Z t:report.content_type=application/pdf t:name_of_developer="Trumark Urban" t:report_number=1 t:report.filename=20140902_20141202_3500_TrumarkUrban_20121218X_First_Redacted.pdf t:planning_department_case_number="2012.1218 X" t:report.file_id=-W9TbwH_wt9tKT9SLBpJq1_boDqrl6nnGEECxCzlkVc t:report.size=261533 t:activity=true m:row_number.mqks-ty4r=1

series e:mqks-ty4r d:2012-12-20T00:00:00.000Z t:report.content_type=application/pdf t:name_of_developer="TMG Partners" t:report_number=1 t:report.filename="20141212_2014XXXX_3500_TMG Partners_2012.1187 BCX_First_Redacted.pdf" t:planning_department_case_number="2012.1187 BCX" t:report.file_id=bdqFPCg71I3DmSdQVT0QuHBAL6Be232V0q9HbTegDDE t:report.size=5322945 m:row_number.mqks-ty4r=2

series e:mqks-ty4r d:2012-05-08T00:00:00.000Z t:report.content_type=application/pdf t:name_of_developer="Urban Green Devco LLC" t:report_number=1 t:report.filename="20150106_20150120_3500_Urban Green Devco LLC_3500_2012.0203E_First_Redacted.pdf" t:planning_department_case_number="2012.0203 E" t:report.file_id=8a1GvKz_zn_1ES6p84gSS0CR5HR3pB8UQncEj_tOWf0 t:report.size=2009328 t:activity=true m:row_number.mqks-ty4r=3
```

## Meta Commands

```ls
metric m:row_number.mqks-ty4r p:long l:"Row Number"

entity e:mqks-ty4r l:"Disclosure Report Developers of Major City Projects Filings" t:attribution="San Francisco Ethics Commission" t:url=https://data.sfgov.org/api/views/mqks-ty4r

property e:mqks-ty4r t:meta.view v:id=mqks-ty4r v:category="City Management and Ethics" v:attributionLink=http://www.sfethics.org v:averageRating=0 v:name="Disclosure Report Developers of Major City Projects Filings" v:attribution="San Francisco Ethics Commission"

property e:mqks-ty4r t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:mqks-ty4r t:meta.view.owner v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:displayName="Steven Massey"

property e:mqks-ty4r t:meta.view.tableauthor v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:roleName=publisher v:displayName="Steven Massey"
```

## Top Records

```ls
| name_of_developer                   | report                                                                                                                                                           | report_number | period_start_date   | period_end_date     | amendment_filing | filed_date          | amendment_to_report_filed | planning_department_case_number | activity | 
| =================================== | ================================================================================================================================================================ | ============= | =================== | =================== | ================ | =================== | ========================= | =============================== | ======== | 
| Trumark Urban                       | [application/pdf, -W9TbwH_wt9tKT9SLBpJq1_boDqrl6nnGEECxCzlkVc, 20140902_20141202_3500_TrumarkUrban_20121218X_First_Redacted.pdf, 261533]                         | 1             | 2012-05-09T00:00:00 | 2014-09-02T00:00:00 |                  | 2014-12-02T00:00:00 |                           | 2012.1218 X                     | true     | 
| TMG Partners                        | [application/pdf, bdqFPCg71I3DmSdQVT0QuHBAL6Be232V0q9HbTegDDE, 20141212_2014XXXX_3500_TMG Partners_2012.1187 BCX_First_Redacted.pdf, 5322945]                    | 1             | 2012-12-20T00:00:00 | 2015-07-07T00:00:00 |                  | 2015-09-03T16:49:52 | 2015-09-03T16:49:52       | 2012.1187 BCX                   |          | 
| Urban Green Devco LLC               | [application/pdf, 8a1GvKz_zn_1ES6p84gSS0CR5HR3pB8UQncEj_tOWf0, 20150106_20150120_3500_Urban Green Devco LLC_3500_2012.0203E_First_Redacted.pdf, 2009328]         | 1             | 2012-05-08T00:00:00 | 2015-01-06T00:00:00 |                  | 2015-09-03T22:10:21 | 2015-09-03T22:10:21       | 2012.0203 E                     | true     | 
| Hines Interests Limited Partnership | [application/pdf, -E989HTWGCIouwMzkVRJHWm7fg0FsdPOs87fgfQUYj8, 20130715_20151023_3500_Hines Interests Limited Partnership_2013.0159E_First_Redacted.pdf, 586247] | 1             | 2012-07-15T00:00:00 | 2015-09-19T00:00:00 |                  | 2015-10-23T00:00:00 | 2015-12-04T22:36:16       | 2013.0159E                      | true     | 
| 5M Project, LLC                     | [application/pdf, SUtdB7egSdF82WYRWJZL4Hjs764dRVNubb2AdiUlGfE, 20151019_20151019_3500_5M Project, LLC_Redacted.pdf, 1188810]                                     | 1             | 2011-02-02T00:00:00 | 2015-10-19T00:00:00 |                  | 2015-10-19T00:00:00 | 2015-12-04T22:57:27       | 2011.0409                       | true     | 
| GSW Arena LLC                       | [application/pdf, roNtjHU2VVvlXMwYYyWkLZSOG5MfMKSY4JRv9Qtv_jE, 20131119_20151203_3500_GSW Arena LLC_2014.1441E_First_Redacted.pdf, 222503]                       | 1             | 2013-11-19T00:00:00 | 2015-12-03T00:00:00 |                  | 2015-12-03T00:00:00 | 2015-12-14T18:52:25       | 2014.1441E                      |          | 
| TMG Partners                        | [application/pdf, JXo-pGq8BHery-i4jXmA2G6vNnIIDZz1Ts3lWDTc0SQ, 20150930_20151112_3500_TMG Partners_2012.1187 BCX_Fourth_Redacted.pdf, 265009]                    | 4             | 2015-07-01T00:00:00 | 2015-09-30T00:00:00 |                  | 2015-11-12T00:00:00 | 2015-12-14T18:54:40       | 2012.1187 BCX                   |          | 
| 5M Project, LLC                     | [application/pdf, eee31568-a380-4ac6-b601-745df9f973ef, 20160331_20160415_3500_5M Project, LLC_Redacted.pdf, 910058]                                             | 3             | 2016-01-01T00:00:00 | 2016-03-31T00:00:00 |                  | 2016-04-15T00:00:00 | 2016-04-19T19:00:16       | 2011.0409                       | true     | 
| 5M Project, LLC                     | [application/pdf, ad6567d1-6e3f-4c31-828e-d00eeaf3a3be, 20150202_20151207_3500_5M Project, LLC (Amendment)_Redacted.pdf, 1193588]                                | 1             | 2014-09-17T00:00:00 | 2015-09-17T00:00:00 | true             | 2015-12-07T00:00:00 | 2015-10-19T00:00:00       | 2011.0409                       | true     | 
| GSW Arena LLC                       | [application/pdf, 0377f166-2552-4383-bd3d-5288c9cdeb11, 20160331_20160415_3500_GSW_Arena_LLC_Redacted.pdf, 272779]                                               | 3             | 2016-01-01T00:00:00 | 2016-03-31T00:00:00 |                  | 2016-04-15T00:00:00 | 2016-04-19T19:09:57       | 2014.144 1E                     | true     | 
```