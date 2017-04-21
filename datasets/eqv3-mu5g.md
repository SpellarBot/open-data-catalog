# IT End-User Training

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/it-end-user-training-56a60) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/eqv3-mu5g) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/eqv3-mu5g/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/eqv3-mu5g/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | eqv3-mu5g |
| Name | IT End-User Training |
| Category | Employees |
| Tags | training, it |
| Created | 2012-01-04T22:41:46Z |
| Publication Date | 2013-05-13T20:10:56Z |

## Description

Course listed are intended for King County employees and may not be available to the general public.

## Columns

```ls
| Included | Schema Type | Field Name               | Name             | Data Type | Render Type |
| ======== | =========== | ======================== | ================ | ========= | =========== |
| No       | time        | :updated_at              | updated_at       | meta_data | meta_data   |
| Yes      | series tag  | title                    | Title            | text      | text        |
| Yes      | series tag  | description              | Description      | text      | text        |
| Yes      | series tag  | format                   | Format           | text      | text        |
| Yes      | series tag  | cost                     | Cost             | text      | text        |
| Yes      | series tag  | contact                  | Contact          | email     | email       |
| Yes      | series tag  | registration_information | More Information | url       | url         |
| Yes      | series tag  | keywords                 | Keywords         | text      | text        |
| Yes      | series tag  | new_employee             | New Employee     | text      | text        |
| Yes      | series tag  | vendor                   | Vendor           | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:eqv3-mu5g d:2012-01-04T14:41:59.000Z t:title="King County Acceptable Use of Assets" t:keywords="Acceptable Use of Assets, AUP" t:description="PowerPoint trainings covering the county's Acceptable Use of Assets policy" t:registration_information=http://kcweb.metrokc.gov/oirm/governance/training.aspx t:format=Online t:cost=Free t:new_employee=Yes m:row_number.eqv3-mu5g=1

series e:eqv3-mu5g d:2012-01-04T16:32:10.000Z t:title="CEMUG Distribution Lists" t:keywords="Access, Excel, Outlook, PowerPoint, Word" t:description="Email distribution lists to answer questions about the Access, Excel, Outlook, PowerPoint, and Word" t:format=Email t:contact=katie.moriarty@kingcounty.gov t:cost=Free t:new_employee=Yes m:row_number.eqv3-mu5g=2

series e:eqv3-mu5g d:2012-01-27T15:25:37.000Z t:title="Ramco Software Training" t:keywords="Access, Excel, Outlook, PowerPoint, Project, Publisher, SharePoint, Visio, Word" t:vendor=Yes t:description="Various levels of SharePoint, Outlook, Access, Excel, PowerPoint, Project, Publisher, Visio, and Word" t:registration_information=https://www.ramco-training.com/ t:format="Online, classroom, seminars" t:cost="$99 - $338" t:new_employee=Yes m:row_number.eqv3-mu5g=3
```

## Meta Commands

```ls
metric m:row_number.eqv3-mu5g p:long l:"Row Number"

entity e:eqv3-mu5g l:"IT End-User Training" t:url=https://data.kingcounty.gov/api/views/eqv3-mu5g

property e:eqv3-mu5g t:meta.view v:id=eqv3-mu5g v:category=Employees v:averageRating=0 v:name="IT End-User Training"

property e:eqv3-mu5g t:meta.view.license v:name="Public Domain"

property e:eqv3-mu5g t:meta.view.owner v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:displayName="King County Webteam"

property e:eqv3-mu5g t:meta.view.tableauthor v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:roleName=administrator v:displayName="King County Webteam"
```

## Top Records

```ls
| :updated_at | title                                | description                                                                                                                                                                    | format                      | cost       | contact                       | registration_information                                                                                                                                                     | keywords                                                                                                                                                                       | new_employee | vendor | 
| =========== | ==================================== | ============================================================================================================================================================================== | =========================== | ========== | ============================= | ============================================================================================================================================================================ | ============================================================================================================================================================================== | ============ | ====== | 
| 1325688119  | King County Acceptable Use of Assets | PowerPoint trainings covering the county's Acceptable Use of Assets policy                                                                                                     | Online                      | Free       |                               | [http://kcweb.metrokc.gov/oirm/governance/training.aspx, null]                                                                                                               | Acceptable Use of Assets, AUP                                                                                                                                                  | Yes          |        | 
| 1325694730  | CEMUG Distribution Lists             | Email distribution lists to answer questions about the Access, Excel, Outlook, PowerPoint, and Word                                                                            | Email                       | Free       | katie.moriarty@kingcounty.gov | [null, null]                                                                                                                                                                 | Access, Excel, Outlook, PowerPoint, Word                                                                                                                                       | Yes          |        | 
| 1327677937  | Ramco Software Training              | Various levels of SharePoint, Outlook, Access, Excel, PowerPoint, Project, Publisher, Visio, and Word                                                                          | Online, classroom, seminars | $99 - $338 |                               | [https://www.ramco-training.com/, null]                                                                                                                                      | Access, Excel, Outlook, PowerPoint, Project, Publisher, SharePoint, Visio, Word                                                                                                | Yes          | Yes    | 
| 1327677941  | SmartPath LLC                        | Various levels of Excel, InfoPath, PowerPoint, Project, Word, and Visio                                                                                                        | Online, classroom           | $12 - $375 |                               | [http://www.smartpathllc.com/, null]                                                                                                                                         | Excel, InfoPath, PowerPoint, Project, Word, Visio                                                                                                                              | Yes          | Yes    | 
| 1327679182  | Microsoft eLearning - Applications   | Various levels of Access, Excel, InfoPath, OneNote, Outlook, PowerPoint, Project, Visio, Windows, and Word                                                                     | Online                      | Free       |                               | [http://kcweb.metrokc.gov/oirm/services/kcit/MSOffice.aspx, null]                                                                                                            | Access, Excel, InfoPath, OneNote, Outlook, PowerPoint, Project, Visio, Windows, Word                                                                                           | Yes          |        | 
| 1327679192  | Microsoft eLearning - Software       | Analytics, BizTalk Server, Content Management Server, Exchange Server, Forms Server, Groove, SharePoint Server, SQL Server, Windows 2000, Windows XP, Windows Vista, Windows 7 | Online                      | Free       |                               | [http://kcweb.metrokc.gov/oirm/services/kcit/MSOffice.aspx, null]                                                                                                            | Analytics, BizTalk Server, Content Management Server, Exchange Server, Forms Server, Groove, SharePoint Server, SQL Server, Windows 2000, Windows XP, Windows Vista, Windows 7 | Yes          |        | 
| 1327921012  | Radio Communications Training        | refresher on using your 800 MHz radio                                                                                                                                          | Online                      | Free       |                               | [http://kcweb.metrokc.gov/oirm/services/kcit/Refresher_Training.ppt, http://kcweb.metrokc.gov/oirm/services/kcit/Refresher_Training.ppt]                                     | radio, 800 MHz                                                                                                                                                                 | No           |        | 
| 1327921087  | Radio Communications Training        | Subscriber Training                                                                                                                                                            | Online                      | Free       |                               | [http://kcweb.metrokc.gov/oirm/services/kcit/radio/RCS_Subscriber_Training352X240.mpg, http://kcweb.metrokc.gov/oirm/services/kcit/radio/RCS_Subscriber_Training352X240.mpg] | radio, subscriber                                                                                                                                                              | No           |        | 
| 1328689803  | King County SiteCore - Advanced      | Advanced User Training for SiteCore (Web Content Management System)                                                                                                            | Classroom                   | Free       | tom.braman@kingcounty.gov     | [http://training.kingcounty.gov/, null]                                                                                                                                      | SiteCore, WCMS, Web Content Management System                                                                                                                                  | No           |        | 
| 1328689810  | King County SiteCore - Basics        | Basic User Training for SiteCore (Web Content Management System)                                                                                                               | Classroom                   | Free       | tom.braman@kingcounty.gov     | [http://training.kingcounty.gov/, null]                                                                                                                                      | SiteCore, WCMS, Web Content Management System                                                                                                                                  | No           |        | 
```