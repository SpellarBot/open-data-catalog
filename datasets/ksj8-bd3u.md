# Montgomery County Council Legislation - Bills

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/montgomery-county-council-legislation-bills) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/ksj8-bd3u) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/ksj8-bd3u/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/ksj8-bd3u/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | ksj8-bd3u |
| Name | Montgomery County Council Legislation - Bills |
| Category | Government |
| Tags | council, bills |
| Created | 2015-05-05T22:18:50Z |
| Publication Date | 2017-02-15T13:36:47Z |

## Description

The Council enacts local public laws for the ?peace, good government, health, and welfare of the county?. The bills dataset contains all legislation considered by the County Council to amend specific sections of the Montgomery County Code. Update Frequency : Daily

## Columns

```ls
| Included | Schema Type | Field Name                       | Name              | Data Type     | Render Type   |
| ======== | =========== | ================================ | ================= | ============= | ============= |
| Yes      | series tag  | bill_no                          | Bill No           | text          | text          |
| Yes      | series tag  | title                            | Title             | text          | text          |
| Yes      | series tag  | status                           | Status            | text          | text          |
| Yes      | series tag  | enacted_bill                     | Enacted Bill      | url           | url           |
| Yes      | series tag  | sponsors                         | Sponsor(s)        | text          | text          |
| Yes      | series tag  | co_sponsors                      | Co-Sponsor(s)     | text          | text          |
| Yes      | time        | introduction_date                | Introduction Date | calendar_date | calendar_date |
| No       |             | public_hearing_date              | PH Date           | calendar_date | calendar_date |
| No       |             | expiration_date_of_pending_bills | Expiration Date   | calendar_date | calendar_date |
| Yes      | series tag  | council_action                   | Council Action    | text          | text          |
| Yes      | series tag  | yeas                             | Yeas              | text          | text          |
| Yes      | series tag  | nays                             | Nays              | text          | text          |
| Yes      | series tag  | abstain                          | Abstain           | text          | text          |
| No       |             | action_date                      | Action Date       | calendar_date | calendar_date |
| Yes      | series tag  | absent                           | Absent            | text          | text          |
| Yes      | series tag  | executive_action                 | Executive Action  | text          | text          |
| No       |             | effective_date                   | Effective Date    | calendar_date | calendar_date |
| No       |             | sunset_date                      | Sunset Date       | calendar_date | calendar_date |
| Yes      | series tag  | mc_code_chapter                  | MC Code Chapter   | text          | text          |
| Yes      | series tag  | mc_code_section                  | MC Code Section   | text          | text          |
| Yes      | series tag  | committee                        | Committee         | text          | text          |
| Yes      | series tag  | lmc_chapter_no                   | LMC Chapter No    | text          | text          |
```

## Time Field

```ls
Value = introduction_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = public_hearing_date,expiration_date_of_pending_bills,action_date,effective_date,sunset_date
```

## Data Commands

```ls
series e:ksj8-bd3u d:2014-10-28T00:00:00.000Z t:title="Taxicabs - Centralized Electronic Dispatch System" t:committee="T&E 6/22/15  Worksession" t:mc_code_chapter=53 t:status=Expired t:sponsors=Riemer t:bill_no=55-14 t:mc_code_section=53-111 m:row_number.ksj8-bd3u=1

series e:ksj8-bd3u d:2014-10-28T00:00:00.000Z t:title="Taxicabs - Transportation Network Service - Requirements" t:committee="T&E 6/22/15  Worksession" t:mc_code_chapter=53 t:status=Expired t:sponsors="Berliner,  Floreen,  Riemer, Navarro" t:bill_no=54-14 t:mc_code_section="By amending Sections 53-101and 53-106. By adding Sections 53-801, 53-802, 53-803, 53-804, 53-805, and 53-806" m:row_number.ksj8-bd3u=2

series e:ksj8-bd3u d:2013-10-29T00:00:00.000Z t:title="Personnel - Regulations - Persons with Disabilities - Veterans - Hiring Preference Points" t:mc_code_chapter=33 t:status=Expired t:sponsors="Council President at the Request of the County Executive" t:bill_no=29-13E t:mc_code_section=33-7 m:row_number.ksj8-bd3u=3
```

## Meta Commands

```ls
metric m:row_number.ksj8-bd3u p:long l:"Row Number"

entity e:ksj8-bd3u l:"Montgomery County Council Legislation - Bills" t:url=https://data.montgomerycountymd.gov/api/views/ksj8-bd3u

property e:ksj8-bd3u t:meta.view v:id=ksj8-bd3u v:category=Government v:averageRating=0 v:name="Montgomery County Council Legislation - Bills"

property e:ksj8-bd3u t:meta.view.owner v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"

property e:ksj8-bd3u t:meta.view.tableauthor v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:roleName=administrator v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"
```

## Top Records

```ls
| bill_no | title                                                                                     | status  | enacted_bill                                                                                                              | sponsors                                                 | co_sponsors             | introduction_date   | public_hearing_date | expiration_date_of_pending_bills | council_action                  | yeas                                                                      | nays    | abstain | action_date         | absent | executive_action    | effective_date      | sunset_date         | mc_code_chapter        | mc_code_section                                                                                              | committee                                         | lmc_chapter_no | 
| ======= | ========================================================================================= | ======= | ========================================================================================================================= | ======================================================== | ======================= | =================== | =================== | ================================ | =============================== | ========================================================================= | ======= | ======= | =================== | ====== | =================== | =================== | =================== | ====================== | ============================================================================================================ | ================================================= | ============== | 
| 55-14   | Taxicabs - Centralized Electronic Dispatch System                                         | Expired | [null, null]                                                                                                              | Riemer                                                   |                         | 2014-10-28T00:00:00 | 2014-12-02T00:00:00 | 2016-04-28T00:00:00              |                                 |                                                                           |         |         |                     |        |                     |                     |                     | 53                     | 53-111                                                                                                       | T&E 6/22/15 Worksession                           |                | 
| 54-14   | Taxicabs - Transportation Network Service - Requirements                                  | Expired | [null, null]                                                                                                              | Berliner, Floreen, Riemer, Navarro                       |                         | 2014-10-28T00:00:00 | 2014-12-02T00:00:00 | 2016-04-28T00:00:00              |                                 |                                                                           |         |         |                     |        |                     |                     |                     | 53                     | By amending Sections 53-101and 53-106. By adding Sections 53-801, 53-802, 53-803, 53-804, 53-805, and 53-806 | T&E 6/22/15 Worksession                           |                | 
| 29-13E  | Personnel - Regulations - Persons with Disabilities - Veterans - Hiring Preference Points | Expired | [null, null]                                                                                                              | Council President at the Request of the County Executive |                         | 2013-10-29T00:00:00 | 2014-02-11T00:00:00 | 2015-04-29T00:00:00              |                                 |                                                                           |         |         |                     |        |                     |                     |                     | 33                     | 33-7                                                                                                         |                                                   |                | 
| 44-16   | Retirement - Fossil Fuel Investments - Restrictions                                       | Pending | [null, null]                                                                                                              | Berliner, Navarro                                        | Elrich                  | 2016-10-25T00:00:00 | 2016-12-06T00:00:00 | 2018-04-25T00:00:00              |                                 |                                                                           |         |         |                     |        |                     |                     |                     | Adding 33; Amending 33 | 33-60C; 33-61A and 33-165                                                                                    | GO/T&E 2/2/17 Worksession; to be continued        |                | 
| 46-15   | Human Rights and Civil Liberties - Building Maintenance Worker - Minimum Work Week        | Pending | [null, null]                                                                                                              | Riemer                                                   | Navarro, Elrich, Hucker | 2015-11-17T00:00:00 |                     | 2017-05-17T00:00:00              |                                 |                                                                           |         |         |                     |        |                     |                     |                     | Amending 27; Adding 27 | 27-7 and 27-8; Article XIV                                                                                   |                                                   |                | 
| 62-14   | Taxation - Development Impact Taxes - Exemptions - Ancillary Facilities                   | Enacted | [null, null]                                                                                                              | Rice, Leventhal, Floreen, Katz, Riemer, Navarro          |                         | 2014-11-25T00:00:00 | 2015-01-13T00:00:00 |                                  | Enacted (9y)                    | Berliner, Elrich, Floreen, Hucker, Katz, Leventhal, Navarro, Rice, Riemer |         |         | 2015-02-03T00:00:00 |        | Approved 2/11/2015  | 2014-10-30T00:00:00 |                     | 52                     | 52-49 and 52-89                                                                                              | GO 1/29/15 Recommends enactment with amendments   | 4 LMC 2015     | 
| 48-16   | Taxation - Credit to Offset Certain Income Tax Revenues - Amendments                      | Enacted | [https://www.montgomerycountymd.gov/council/resources/files/lims/bill/2016/Signed/pdf/421_1058_Signed_02222017.pdf, null] | Navarro, Katz and Riemer                                 | Rice                    | 2016-12-06T00:00:00 | 2017-01-17T00:00:00 |                                  | Enacted (9y)                    | Berliner, Elrich, Floreen, Hucker, Katz, Leventhal, Navarro, Rice, Riemer |         |         | 2017-02-07T00:00:00 |        | Approved 2/16/2017  | 2017-05-18T00:00:00 |                     | Amending 52            | 52-86                                                                                                        | 1/30/17 GO Recommended enactment                  | 2 LMC 2017     | 
| 46-16E  | Streets and Roads - Snow Removal - Violations                                             | Enacted | [null, null]                                                                                                              | Riemer                                                   | Berliner                | 2016-11-15T00:00:00 | 2016-11-29T00:00:00 |                                  | Enacted (8y; NF n)              | Berliner, Elrich, Hucker, Katz, Leventhal, Navarro, Rice, Riemer          | Floreen |         | 2016-12-13T00:00:00 |        | Approved 12/19/2016 | 2016-12-19T00:00:00 |                     | Amending 49            | Article I; Section 49-17                                                                                     | T&E 12/1/16 Recommended enactment with amendments | 40 LMC 2016    | 
| 45-16E  | Contracts and Procurement - Minority-Owned Businesses - Sunset Date - Amendments          | Enacted | [null, null]                                                                                                              | Government Operations and Fiscal Policy Committee        |                         | 2016-11-01T00:00:00 | 2016-11-08T00:00:00 |                                  | Enacted (8y; TH ta) (8y; TH ta) | Berliner, Elrich, Floreen, Katz, Leventhal, Navarro, Rice, Riemer         |         |         | 2016-11-15T00:00:00 | Hucker | Approved 11/28/2016 | 2016-11-28T00:00:00 | 2019-12-31T00:00:00 | Amending 11B           | 11B-64                                                                                                       |                                                   | 38 LMC 2016    | 
| 43-16E  | Retirement - Membership Groups - Group J - Established                                    | Enacted | [https://www.montgomerycountymd.gov/council/resources/files/lims/bill/2016/Signed/pdf/695_1049_Signed_03072017.pdf, null] | Council President at the Request of the County Executive |                         | 2016-10-18T00:00:00 | 2016-11-15T00:00:00 |                                  | Enacted (9y)                    | Berliner, Elrich, Floreen, Hucker, Katz, Leventhal, Navarro, Rice, Riemer |         |         | 2016-12-13T00:00:00 |        | Approved 12/21/2016 | 2016-12-21T00:00:00 |                     | Amending 33            | 33-37, 33-38, 33-39, 33-42 and 33-43                                                                         | GO 12/12/16 Recommended enactment with amendments | 42 LMC 2016    | 
```