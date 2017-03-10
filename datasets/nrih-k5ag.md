# SB 272 Enterprise Software

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ab272-enterprise-software) |
| Metadata | [Link](https://data.srcity.org/api/views/nrih-k5ag) |
| Data: JSON | [100 Rows](https://data.srcity.org/api/views/nrih-k5ag/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.srcity.org/api/views/nrih-k5ag/rows.csv?max_rows=100) |
| Host | data.srcity.org |
| Id | nrih-k5ag |
| Name | SB 272 Enterprise Software |
| Category | Government |
| Tags | sb 272 ab272 sb272 |
| Created | 2016-03-14T17:56:26Z |
| Publication Date | 2016-03-14T17:57:03Z |
| Rows Updated | 2016-03-22T12:00:17Z |

## Description

Approved on October 11, 2015, adds a section to the California Public Records Act requiring local agencies to create a catalog of Enterprise Systems by July 1, 2016 with annual updates. 

Enterprise System
 A software application or computer system that collects, stores, exchanges and analyzes information that the agency uses that is both of the following:  
?A multi-departmental system or a system that contains information collected about the public. 
?A system that serves as an original source of data within an agency. 
An Enterprise System does not include any of the following: 

? Information Technology security systems, including firewalls and other cybersecurity systems. 
? Physical access control systems, employee identification management systems, video monitoring and other physical control systems. 
? Infrastructure and mechanical control systems, including those that control or manage street lights, electrical, natural gas or water or sewer functions. 
? Systems related to 911 dispatch and operation or emergency services. 
? Systems that would be restricted from disclosure by Section 6254.19. 
? The specific records that the information technology system collects, stores, exchanges or analyzes. 
Requirements 
 1. Create a catalog of enterprise systems, containing: 

? Current system vendor 
? Current system product 
? System?s purpose 
? A description of categories or types of data 
? The department that is the prime custodian of the data 
? The frequency that system data is collected 
? The frequency that system data is updated

2. To make the catalog publicly available upon request 
 3. To post the catalog in a prominent location on the agency?s website 

Exception
 If the public interest served by not disclosing the information described clearly outweighs the public interest served by disclosure, the local agency may instead provide a system name, brief title or identifier of the system.

## Columns

```ls
| Included | Schema Type | Field Name                   | Name                         | Data Type | Render Type |
| ======== | =========== | ============================ | ============================ | ========= | =========== |
| No       | time        | :updated_at                  | updated_at                   | meta_data | meta_data   |
| Yes      | series tag  | vendor_name                  | Vendor Name                  | text      | text        |
| Yes      | series tag  | product                      | Product                      | text      | text        |
| Yes      | series tag  | system_purpose               | System Purpose               | text      | text        |
| Yes      | series tag  | custodian                    | Custodian                    | text      | text        |
| Yes      | series tag  | frequency_of_data_collection | Frequency of data collection | text      | text        |
| Yes      | series tag  | frequency_of_data_update     | Frequency of data update     | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
```

## Meta Commands

```ls
entity e:nrih-k5ag l:"SB 272 Enterprise Software" t:url=https://data.srcity.org/api/views/nrih-k5ag

property e:nrih-k5ag t:meta.view d:2017-03-10T16:12:42.850Z v:id=nrih-k5ag v:category=Government v:averageRating=0 v:name="SB 272 Enterprise Software"

property e:nrih-k5ag t:meta.view.owner d:2017-03-10T16:12:42.850Z v:id=s466-99pv v:profileImageUrlMedium=/api/users/s466-99pv/profile_images/THUMB v:profileImageUrlLarge=/api/users/s466-99pv/profile_images/LARGE v:screenName=Webmaster v:profileImageUrlSmall=/api/users/s466-99pv/profile_images/TINY v:roleName=administrator v:displayName=Webmaster

property e:nrih-k5ag t:meta.view.tableauthor d:2017-03-10T16:12:42.850Z v:id=s466-99pv v:profileImageUrlMedium=/api/users/s466-99pv/profile_images/THUMB v:profileImageUrlLarge=/api/users/s466-99pv/profile_images/LARGE v:screenName=Webmaster v:profileImageUrlSmall=/api/users/s466-99pv/profile_images/TINY v:roleName=administrator v:displayName=Webmaster
```