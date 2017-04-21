# OPA Complaint Tracker - Task Language

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/opa-complaint-tracker-task-language) |
| Metadata | [Link](https://data.seattle.gov/api/views/qew5-gawh) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/qew5-gawh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/qew5-gawh/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | qew5-gawh |
| Name | OPA Complaint Tracker - Task Language |
| Attribution | OPA |
| Category | Public Safety |
| Created | 2015-03-25T21:25:57Z |
| Publication Date | 2015-06-16T21:57:49Z |

## Description

OPA COMPLAINT TRACKER Task language; data used to report a user friendly message to

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type | Render Type |
| ======== | =========== | ================ | ================ | ========= | =========== |
| No       | time        | :updated_at      | updated_at       | meta_data | meta_data   |
| Yes      | series tag  | data_field       | DATA FIELD       | text      | text        |
| Yes      | series tag  | complaint_status | COMPLAINT STATUS | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:qew5-gawh d:2015-06-16T14:54:23.000Z t:data_field="OPA 5 Day Notice" t:complaint_status="OPA is reviewing the complaint. The employee and his/her supervisors have been informed of the complaint." m:row_number.qew5-gawh=1

series e:qew5-gawh d:2015-06-16T14:54:23.000Z t:data_field="OPA 30 Day Notice" t:complaint_status="The OPA Director has classified the complaint as a full misconduct investigation. An OPA Investigator is conducting the investigation." m:row_number.qew5-gawh=2

series e:qew5-gawh d:2015-06-16T14:54:23.000Z t:data_field="OPA Intake" t:complaint_status="The complaint has been received. An OPA Investigator has gathered evidence and relevant background information. The evidence is being reviewed by the OPA Lieutenant." m:row_number.qew5-gawh=3
```

## Meta Commands

```ls
metric m:row_number.qew5-gawh p:long l:"Row Number"

entity e:qew5-gawh l:"OPA Complaint Tracker - Task Language" t:attribution=OPA t:url=https://data.seattle.gov/api/views/qew5-gawh

property e:qew5-gawh t:meta.view v:id=qew5-gawh v:category="Public Safety" v:averageRating=0 v:name="OPA Complaint Tracker - Task Language" v:attribution=OPA

property e:qew5-gawh t:meta.view.license v:name="Public Domain"

property e:qew5-gawh t:meta.view.owner v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:displayName="Seattle IT"

property e:qew5-gawh t:meta.view.tableauthor v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:roleName=administrator v:displayName="Seattle IT"
```

## Top Records

```ls
| :updated_at | data_field             | complaint_status                                                                                                                                                                                                                                                                                                                                        | 
| =========== | ====================== | ======================================================================================================================================================================================================================================================================================================================================================= | 
| 1434466463  | OPA 5 Day Notice       | OPA is reviewing the complaint. The employee and his/her supervisors have been informed of the complaint.                                                                                                                                                                                                                                               | 
| 1434466463  | OPA 30 Day Notice      | The OPA Director has classified the complaint as a full misconduct investigation. An OPA Investigator is conducting the investigation.                                                                                                                                                                                                                  | 
| 1434466463  | OPA Intake             | The complaint has been received. An OPA Investigator has gathered evidence and relevant background information. The evidence is being reviewed by the OPA Lieutenant.                                                                                                                                                                                   | 
| 1434466463  | OPA Intake Review      | Background information has been gathered and reviewed by the OPA Lieutenant. The OPA Director is reviewing the information.                                                                                                                                                                                                                             | 
| 1434466463  | OPA Director CL Review | Background information has been gathered and reviewed by the OPA Director. The information is being reviewed by the OPA independent Auditor.                                                                                                                                                                                                            | 
| 1434466463  | OPA Auditor CL Review  | Complete The contact has been reviewed and documented by OPA. No further action is needed. Thank you for contacting us.                                                                                                                                                                                                                                 | 
| 1434466463  | OPA Close CL           | Complete The contact has been reviewed and documented by OPA. No further action is needed. Thank you for contacting us.                                                                                                                                                                                                                                 | 
| 1434466463  | OPA Create SAN         | The OPA Lieutenant has recommended that the complaint be processed as a Supervisor Action. This means that the employee's supervisor would address the complaint and resolve the issues with the employee. The OPA Director is reviewing the complaint.                                                                                                 | 
| 1434466463  | OPA Classification     | The complaint is being reviewed to determine whether it should be handled by the employee's supervisor (Supervisor Action) or if a full misconduct investigation is required.                                                                                                                                                                           | 
| 1434466463  | OPA Process SA         | The OPA Director has determined that the complaint will be processed as a Supervisor Action. This means that the employee's supervisor will address the complaint and resolve the issues with the employee as directed by OPA. After the employee's supervisor completes the actions, the supervisor will send a report to OPA for review and approval. | 
```