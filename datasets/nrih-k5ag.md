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

## Description

Approved on October 11, 2015, adds a section to the California Public Records Act requiring local agencies to create a catalog of Enterprise Systems by July 1, 2016 with annual updates. 

Enterprise System
 A software application or computer system that collects, stores, exchanges and analyzes information that the agency uses that is both of the following:  
•A multi-departmental system or a system that contains information collected about the public. 
•A system that serves as an original source of data within an agency. 
An Enterprise System does not include any of the following: 

• Information Technology security systems, including firewalls and other cybersecurity systems. 
• Physical access control systems, employee identification management systems, video monitoring and other physical control systems. 
• Infrastructure and mechanical control systems, including those that control or manage street lights, electrical, natural gas or water or sewer functions. 
• Systems related to 911 dispatch and operation or emergency services. 
• Systems that would be restricted from disclosure by Section 6254.19. 
• The specific records that the information technology system collects, stores, exchanges or analyzes. 
Requirements 
 1. Create a catalog of enterprise systems, containing: 

• Current system vendor 
• Current system product 
• System’s purpose 
• A description of categories or types of data 
• The department that is the prime custodian of the data 
• The frequency that system data is collected 
• The frequency that system data is updated

2. To make the catalog publicly available upon request 
 3. To post the catalog in a prominent location on the agency’s website 

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
series e:nrih-k5ag d:2016-03-14T10:56:29.000Z t:product="Office 365" t:custodian="Information Technology" t:system_purpose="Office suite of products (mail, spreadsheets, etc)" t:vendor_name=Microsoft t:frequency_of_data_update=Daily t:frequency_of_data_collection=Daily m:row_number.nrih-k5ag=1

series e:nrih-k5ag d:2016-03-14T10:56:29.000Z t:product=IFAS t:custodian=Finance t:system_purpose="Financial and HR system" t:vendor_name="Sungard Public Sector" t:frequency_of_data_update=Daily t:frequency_of_data_collection=Daily m:row_number.nrih-k5ag=2

series e:nrih-k5ag d:2016-03-14T10:56:29.000Z t:product="Accela Automation (Permits Plus prior to 13/14)" t:custodian="Information Technology" t:system_purpose="Permit management" t:vendor_name="Accela Automation" t:frequency_of_data_update=Daily t:frequency_of_data_collection=Daily m:row_number.nrih-k5ag=3
```

## Meta Commands

```ls
metric m:row_number.nrih-k5ag p:long l:"Row Number"

entity e:nrih-k5ag l:"SB 272 Enterprise Software" t:url=https://data.srcity.org/api/views/nrih-k5ag

property e:nrih-k5ag t:meta.view d:2017-09-25T07:28:20.596Z v:averageRating=0 v:name="SB 272 Enterprise Software" v:id=nrih-k5ag v:category=Government

property e:nrih-k5ag t:meta.view.owner d:2017-09-25T07:28:20.596Z v:displayName=Webmaster v:profileImageUrlLarge=/api/users/s466-99pv/profile_images/LARGE v:profileImageUrlSmall=/api/users/s466-99pv/profile_images/TINY v:id=s466-99pv v:screenName=Webmaster v:profileImageUrlMedium=/api/users/s466-99pv/profile_images/THUMB

property e:nrih-k5ag t:meta.view.tableauthor d:2017-09-25T07:28:20.596Z v:displayName=Webmaster v:profileImageUrlLarge=/api/users/s466-99pv/profile_images/LARGE v:roleName=administrator v:profileImageUrlSmall=/api/users/s466-99pv/profile_images/TINY v:id=s466-99pv v:screenName=Webmaster v:profileImageUrlMedium=/api/users/s466-99pv/profile_images/THUMB
```

## Top Records

```ls
| :updated_at | vendor_name                | product                                         | system_purpose                                     | custodian              | frequency_of_data_collection | frequency_of_data_update | 
| =========== | ========================== | =============================================== | ================================================== | ====================== | ============================ | ======================== | 
| 1457952989  | Microsoft                  | Office 365                                      | Office suite of products (mail, spreadsheets, etc) | Information Technology | Daily                        | Daily                    | 
| 1457952989  | Sungard Public Sector      | IFAS                                            | Financial and HR system                            | Finance                | Daily                        | Daily                    | 
| 1457952989  | Accela Automation          | Accela Automation (Permits Plus prior to 13/14) | Permit management                                  | Information Technology | Daily                        | Daily                    | 
| 1457952989  | CIS-N Harris Computer Corp | CIS-N Harris Computer Corp                      | Utility Billing                                    | Finance                | Daily                        | Daily                    | 
| 1457952989  | Granicus                   | Legislative Suite                               | Legislative Records                                | City Clerk             | Daily                        | Daily                    | 
| 1457952989  | ESRI                       | GIS                                             | Assorted city parcel and facility information      | Information Technology | Daily                        | Daily                    | 
| 1457952989  | eCivis                     | Grant Mgt                                       | Grant Management                                   | City Manager Office    | As Needed                    | As Needed                | 
| 1457952989  | CCG Systems                | Fleet Mgt                                       | Fleet Management                                   | Public Works           | Daily                        | Daily                    | 
| 1457952989  | LaserFiche                 | LaserFiche                                      | Electronic Documents Management System             | Information Technology | Daily                        | Daily                    | 
| 1457952989  | GovDelivery                | Web email alert services                        | Web email alert services                           | Information Technology | Daily                        | Daily                    | 
```