# Human Resources - Exempt Positions

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/human-resources-exempt-positions) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/6ybd-qcyy) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/6ybd-qcyy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/6ybd-qcyy/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | 6ybd-qcyy |
| Name | Human Resources - Exempt Positions |
| Attribution | Cook County Human Resources |
| Category | Finance & Administration |
| Created | 2016-05-05T19:49:42Z |
| Publication Date | 2017-04-14T21:00:21Z |

## Description

An exempt position is one that involves policy making to an extent or is confidential in such a way that political affiliation is an appropriate consideration for the effective performance of the job. Please refer to the exempt list and associated job descriptions for more information.

## Columns

```ls
| Included | Schema Type    | Field Name                     | Name                           | Data Type | Render Type |
| ======== | ============== | ============================== | ============================== | ========= | =========== |
| No       | time           | :updated_at                    | updated_at                     | meta_data | meta_data   |
| Yes      | series tag     | department                     | Department                     | text      | text        |
| Yes      | series tag     | job_title_description          | Job Title & Description        | url       | url         |
| Yes      | numeric metric | grade                          | Grade                          | number    | number      |
| Yes      | series tag     | position_identification_number | Position Identification Number | text      | text        |
| Yes      | series tag     | incumbent                      | Incumbent                      | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:6ybd-qcyy d:2017-04-14T20:59:49.000Z t:job_title_description=http://opendocs.cookcountyil.gov/human-resources/exempt-positions/0017509-1031-Special_Assistant.pdf t:position_identification_number=0017509 t:department="Office of the Chief Administrative Officer" t:incumbent="Kindle, Aldophus G." m:grade=24

series e:6ybd-qcyy d:2017-04-14T20:59:49.000Z t:job_title_description=http://opendocs.cookcountyil.gov/human-resources/exempt-positions/6791-Aide_to_the_Commissioner_I.pdf t:position_identification_number=0201801 t:department="Eleventh District" m:grade=24

series e:6ybd-qcyy d:2017-04-14T20:59:49.000Z t:job_title_description=http://opendocs.cookcountyil.gov/human-resources/exempt-positions/669501-4714-Executive_Director.pdf t:position_identification_number=0669501 t:department="Department of Homeland Security and Emergency Management" m:grade=24
```

## Meta Commands

```ls
metric m:grade p:integer l:Grade t:dataTypeName=number

entity e:6ybd-qcyy l:"Human Resources - Exempt Positions" t:attribution="Cook County Human Resources" t:url=https://datacatalog.cookcountyil.gov/api/views/6ybd-qcyy

property e:6ybd-qcyy t:meta.view v:id=6ybd-qcyy v:category="Finance & Administration" v:averageRating=0 v:name="Human Resources - Exempt Positions" v:attribution="Cook County Human Resources"

property e:6ybd-qcyy t:meta.view.license v:name="Public Domain"

property e:6ybd-qcyy t:meta.view.owner v:id=u38g-hbsa v:screenName="Cook County Open Data" v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"

property e:6ybd-qcyy t:meta.view.tableauthor v:id=u38g-hbsa v:screenName="Cook County Open Data" v:roleName=administrator v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"
```

## Top Records

```ls
| :updated_at | department                                               | job_title_description                                                                                                                                        | grade | position_identification_number | incumbent             | 
| =========== | ======================================================== | ============================================================================================================================================================ | ===== | ============================== | ===================== | 
| 1492203589  | Office of the Chief Administrative Officer               | [http://opendocs.cookcountyil.gov/human-resources/exempt-positions/0017509-1031-Special_Assistant.pdf, Special Assistant]                                    | 24    | 0017509                        | Kindle, Aldophus G.   | 
| 1492203589  | Eleventh District                                        | [http://opendocs.cookcountyil.gov/human-resources/exempt-positions/6791-Aide_to_the_Commissioner_I.pdf, Aide to the Commissioner I]                          | 24    | 0201801                        |                       | 
| 1492203589  | Department of Homeland Security and Emergency Management | [http://opendocs.cookcountyil.gov/human-resources/exempt-positions/669501-4714-Executive_Director.pdf, Executive Director]                                   | 24    | 0669501                        |                       | 
| 1492203589  | Department of Homeland Security and Emergency Management | [http://opendocs.cookcountyil.gov/human-resources/exempt-positions/669502-4811-Deputy_Director_of_Operations.pdf, Deputy Director of Operations]             | 24    | 0669502                        | Tilton, Thomas W.     | 
| 1492203589  | Department of Homeland Security and Emergency Management | [http://opendocs.cookcountyil.gov/human-resources/exempt-positions/669503-4812-Training_and_Exercise_Manager_1.pdf, Training and Exercise Manager]           | 23    | 0669503                        | Burke Jr., Edward M.  | 
| 1492203589  | Department of Homeland Security and Emergency Management | [http://opendocs.cookcountyil.gov/human-resources/exempt-positions/669504-4813-Planning_Preparedness_Manager_1.pdf, Planning and Preparedness Manager]       | 24    | 0669504                        |                       | 
| 1492203589  | Human Rights and Ethics                                  | [http://opendocs.cookcountyil.gov/human-resources/exempt-positions/900201-5205-Deputy_Director.pdf, Deputy Director]                                         | 24    | 0900201                        | Crawford, Amy E.      | 
| 1492203589  | Office of Chief Financial Officer                        | [http://opendocs.cookcountyil.gov/human-resources/exempt-positions/0903307-5426-Financial_Research_Analyst.pdf, Financial Research Analyst IV]               | 22    | 0903307                        |                       | 
| 1492203589  | Department of Homeland Security and Emergency Management | [http://opendocs.cookcountyil.gov/human-resources/exempt-positions/956518-4812-Training_and_Exercise_Manager_2.pdf, Training and Exercise Manager]           | 23    | 0956518                        | Rodrigues, Jeffrey J. | 
| 1492203589  | Department of Homeland Security and Emergency Management | [http://opendocs.cookcountyil.gov/human-resources/exempt-positions/956520-5531_Special_Assistant_for_Legal_Affairs.pdf, Special Assistant for Legal Affairs] | 24    | 0956520                        |                       | 
```