# OCA Code Enforcement

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/oca-code-enforcement) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/qdey-wt67) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/qdey-wt67/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/qdey-wt67/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | qdey-wt67 |
| Name | OCA Code Enforcement |
| Attribution | Montgomery County, MD |
| Category | Law/Judicial |
| Tags | law, code enforcement, judicial, cases, litigation |
| Created | 2016-05-17T20:42:47Z |
| Publication Date | 2017-01-04T13:22:17Z |

## Description

The Office of the County Attorney (OCA) processes Code Violation Citations issued by County agencies. The citations can be viewed by issued department, issued date and location.

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type     | Render Type   |
| ======== | ============== | ===================== | ===================== | ============= | ============= |
| Yes      | series tag     | citation_no           | Citation No           | text          | text          |
| Yes      | series tag     | department            | Department            | text          | text          |
| Yes      | series tag     | status                | Status                | text          | text          |
| Yes      | time           | openeddate            | Open Date             | calendar_date | calendar_date |
| No       |                | citation_date         | Citation Date         | calendar_date | calendar_date |
| No       |                | statusdate            | Status Date           | calendar_date | calendar_date |
| Yes      | numeric metric | qcitationamount       | Citation Amount       | money         | money         |
| Yes      | series tag     | qcedispositionc       | Disposition Code      | text          | text          |
| No       |                | qcedispositiond       | Disposition Date      | calendar_date | calendar_date |
| Yes      | series tag     | qviolationcode        | Violation Code        | text          | text          |
| Yes      | series tag     | violation_description | Violation Description | text          | text          |
```

## Time Field

```ls
Value = openeddate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = citation_date,statusdate,qcedispositiond
```

## Data Commands

```ls
series e:qdey-wt67 d:2014-10-04T00:00:00.000Z t:citation_no=2Z39905315 t:status=Open t:qcedispositionc=Guilty t:department="Animal Control and Humane Treatment" t:qviolationcode=5-402-a t:violation_description="Vaccinate the animal and provide proof of vaccination to the MC Animal Services Division" m:qcitationamount=500

series e:qdey-wt67 d:2015-06-19T00:00:00.000Z t:citation_no=1Z36214795 t:status=Open t:qcedispositionc="Abatement Order entered" t:department="Department of Housing and Community Affairs" t:qviolationcode=26-9(b)(5) t:violation_description="Failure to maintain grounds: free of erosion or gullying; grass or weeds over 12 inches high; and/or shrubbery, trees, vines, hedges, and other vegetation, including dead trees and branches." m:qcitationamount=500

series e:qdey-wt67 d:2015-12-10T00:00:00.000Z t:citation_no=0Z36215851 t:status=Open t:qcedispositionc="Abatement Order entered" t:department="Department of Housing and Community Affairs" t:qviolationcode=26-9(a)(2) t:violation_description="Failure to maintain door, window, and/or hatchway in sound working condition." m:qcitationamount=500
```

## Meta Commands

```ls
metric m:qcitationamount p:integer l:"Citation Amount" t:dataTypeName=money

entity e:qdey-wt67 l:"OCA Code Enforcement" t:attribution="Montgomery County, MD" t:url=https://data.montgomerycountymd.gov/api/views/qdey-wt67

property e:qdey-wt67 t:meta.view v:id=qdey-wt67 v:category=Law/Judicial v:averageRating=0 v:name="OCA Code Enforcement" v:attribution="Montgomery County, MD"

property e:qdey-wt67 t:meta.view.license v:name="Public Domain"

property e:qdey-wt67 t:meta.view.owner v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"

property e:qdey-wt67 t:meta.view.tableauthor v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:roleName=administrator v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"
```

## Top Records

```ls
| citation_no | department                                  | status | openeddate          | citation_date       | statusdate          | qcitationamount | qcedispositionc         | qcedispositiond     | qviolationcode | violation_description                                                                                                                                                                          | 
| =========== | =========================================== | ====== | =================== | =================== | =================== | =============== | ======================= | =================== | ============== | ============================================================================================================================================================================================== | 
| 2Z39905315  | Animal Control and Humane Treatment         | Open   | 2014-10-04T00:00:00 | 2014-09-10T00:00:00 | 2014-10-04T00:00:00 | 500             | Guilty                  | 2014-12-09T00:00:00 | 5-402-a        | Vaccinate the animal and provide proof of vaccination to the MC Animal Services Division                                                                                                       | 
| 1Z36214795  | Department of Housing and Community Affairs | Open   | 2015-06-19T00:00:00 | 2015-06-17T00:00:00 | 2015-11-04T00:00:00 | 500             | Abatement Order entered | 2015-10-20T00:00:00 | 26-9(b)(5)     | Failure to maintain grounds: free of erosion or gullying; grass or weeds over 12 inches high; and/or shrubbery, trees, vines, hedges, and other vegetation, including dead trees and branches. | 
| 0Z36215851  | Department of Housing and Community Affairs | Open   | 2015-12-10T00:00:00 | 2015-12-04T00:00:00 | 2015-12-10T00:00:00 | 500             | Abatement Order entered | 2016-05-10T00:00:00 | 26-9(a)(2)     | Failure to maintain door, window, and/or hatchway in sound working condition.                                                                                                                  | 
| 5Z39895945  | Animal Control and Humane Treatment         | Open   | 2015-06-09T00:00:00 | 2015-05-12T00:00:00 | 2015-06-09T00:00:00 | 500             | Guilty                  | 2015-08-11T00:00:00 | 5-203-C        | Prevent the animal from having unwanted contact with a person or another domesticated animal at all times.                                                                                     | 
| 1Z36212793  | Department of Housing and Community Affairs | Open   | 2014-04-25T00:00:00 | 2014-04-16T00:00:00 | 2014-04-25T00:00:00 | 500             | Abatement Order entered | 2014-07-22T00:00:00 | 29-16(a)       | Operating a rental facility without first obtaining a rental facility license.                                                                                                                 | 
| 3Z39905610  | Animal Control and Humane Treatment         | Open   | 2016-06-02T00:00:00 | 2016-05-25T00:00:00 | 2016-06-02T00:00:00 | 100             | Abatement Order entered | 2016-08-09T00:00:00 | 5-203-A-1      | Prevent the animal other than an altered cat to be at large                                                                                                                                    | 
| 5Z36215338  | Department of Housing and Community Affairs | Open   | 2015-10-23T00:00:00 | 2015-10-13T00:00:00 | 2015-10-23T00:00:00 | 500             | Abatement Order entered | 2016-03-29T00:00:00 | 26-9(a)(9)     | Failure to exterminate insects, rodents, or other vermin.                                                                                                                                      | 
| 0Z39905306  | Animal Control and Humane Treatment         | Open   | 2014-07-03T00:00:00 | 2014-06-22T00:00:00 | 2014-07-03T00:00:00 | 100             | Default Judgment        | 2014-12-09T00:00:00 | 5-203-A-1      | Prevent the animal other than an altered cat to be at large                                                                                                                                    | 
| 1Z36216482  | Department of Housing and Community Affairs | Open   | 2016-05-20T00:00:00 | 2016-05-10T00:00:00 | 2016-05-20T00:00:00 | 500             | Abatement Order entered | 2016-07-26T00:00:00 | 26-9(a)(1)     | Failure to maintain item/structure in good repair.                                                                                                                                             | 
| 4Z35069507  | Washington Metro. and Transit Auth. Police  | Open   | 2014-08-17T00:00:00 | 2014-07-31T00:00:00 | 2014-08-17T00:00:00 | 50              | Default Judgment        | 2014-12-09T00:00:00 | 54-A-2-9       | Cease entering or leaving a fare-paid area of a rail transport station without paying the fare or presenting a valid transfer                                                                  | 
```