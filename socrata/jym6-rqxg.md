# OCIO IT Project Oversight Status Details

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ocio-it-project-oversight-status-details-c93ca) |
| Metadata | [Link](https://data.wa.gov/api/views/jym6-rqxg) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/jym6-rqxg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/jym6-rqxg/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | jym6-rqxg |
| Name | OCIO IT Project Oversight Status Details |
| Attribution | Office of the CIO |
| Category | Procurements and Contracts |
| Tags | it projects ocio |
| Created | 2014-07-15T20:40:15Z |
| Publication Date | 2015-04-07T03:52:53Z |

## Description

Project oversight status details. See OCIO IT Project Oversight Summary (https://data.wa.gov/resource/k495-fmg2) for main project information.

## Columns

```ls
| Included | Schema Type | Field Name      | Name            | Data Type     | Render Type   |
| ======== | =========== | =============== | =============== | ============= | ============= |
| Yes      | series tag  | project         | Project         | text          | text          |
| Yes      | series tag  | status          | Status          | text          | text          |
| Yes      | series tag  | scope_status    | Scope Status    | text          | text          |
| Yes      | series tag  | budget_status   | Budget Status   | text          | text          |
| Yes      | series tag  | schedule_status | Schedule Status | text          | text          |
| Yes      | series tag  | explanation     | Explanation     | text          | text          |
| Yes      | time        | entered_on      | Entered On      | calendar_date | calendar_date |
```

## Time Field

```ls
Value = entered_on
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:jym6-rqxg d:2013-07-25T00:00:00.000Z t:project="Enterprise Document Management System" t:scope_status=Green t:budget_status=Green t:status=Active t:explanation="This project is considered all ""green"" until most current status reports are updated." t:schedule_status=Green m:row_number.jym6-rqxg=1

series e:jym6-rqxg d:2013-11-20T00:00:00.000Z t:project="Enterprise Document Management System" t:scope_status=Green t:budget_status=Green t:status=Active t:explanation="The project is progressing according to plan. All indicators indicate a successful implementation to date." t:schedule_status=Green m:row_number.jym6-rqxg=2

series e:jym6-rqxg d:2014-03-17T00:00:00.000Z t:project="Enterprise Document Management System" t:scope_status=Green t:budget_status=Green t:status=Active t:explanation="All on track." t:schedule_status=Green m:row_number.jym6-rqxg=3
```

## Meta Commands

```ls
metric m:row_number.jym6-rqxg p:long l:"Row Number"

entity e:jym6-rqxg l:"OCIO IT Project Oversight Status Details" t:attribution="Office of the CIO" t:url=https://data.wa.gov/api/views/jym6-rqxg

property e:jym6-rqxg t:meta.view v:id=jym6-rqxg v:category="Procurements and Contracts" v:attributionLink=http://www.ocio.wa.gov/its-transparent-project-dashboard v:averageRating=0 v:name="OCIO IT Project Oversight Status Details" v:attribution="Office of the CIO"

property e:jym6-rqxg t:meta.view.license v:name="Public Domain"

property e:jym6-rqxg t:meta.view.owner v:id=2cik-4ce4 v:screenName="Jason McKee" v:displayName="Jason McKee"

property e:jym6-rqxg t:meta.view.tableauthor v:id=2cik-4ce4 v:screenName="Jason McKee" v:roleName=publisher v:displayName="Jason McKee"
```

## Top Records

```ls
| project                               | status | scope_status | budget_status | schedule_status | explanation                                                                                                                                                                                                                                                  | entered_on          | 
| ===================================== | ====== | ============ | ============= | =============== | ============================================================================================================================================================================================================================================================ | =================== | 
| Enterprise Document Management System | Active | Green        | Green         | Green           | This project is considered all "green" until most current status reports are updated.                                                                                                                                                                        | 2013-07-25T00:00:00 | 
| Enterprise Document Management System | Active | Green        | Green         | Green           | The project is progressing according to plan. All indicators indicate a successful implementation to date.                                                                                                                                                   | 2013-11-20T00:00:00 | 
| Enterprise Document Management System | Active | Green        | Green         | Green           | All on track.                                                                                                                                                                                                                                                | 2014-03-17T00:00:00 | 
| Gaming Vendor Replacement             | Active | Green        | Green         | Green           | Vendor acquisition phase has started. Expect contract signing by 12/30/2014.                                                                                                                                                                                 | 2014-04-17T00:00:00 | 
| Next Generation Tax System            | Active | Green        | Green         | Green           | NGTS post go-live critical bugs fixes are being worked in business priority order and testing of some of the employer facing portions of the system has started; a new schedule for this portion of the project is currently under review.                   | 2014-08-06T00:00:00 | 
| Next Generation Tax System            | Active | Green        | Green         | Green           | NGTS post go-live production environment operations stabilizing and streamlining efforts are showing progress and work on the employer facing portions of the system has resumed.                                                                            | 2014-06-02T00:00:00 | 
| Next Generation Tax System            | Active | Green        | Green         | Green           | Work continues on critical enhancements and bug fixes, primary focus is on billing related ones. Annual tax rates were sent out to employers in December 2014. A new schedule for the employer facing portion of the project was completed.                  | 2015-01-27T00:00:00 | 
| Next Generation Tax System            | Active | Green        | Green         | Green           | Stage 2/3 went live 3/12 and 3/13 2014 for users within ESD and on the state-government network respectively. Stage 4 goes live 8/25/2014 and includes an updated laptop audit application plus upgraded tax-filing applications and services for employers. | 2014-03-20T00:00:00 | 
| Next Generation Tax System            | Active | Green        | Green         | Green           | NGTS post go-live production environment operations stabilizing and streamlining efforts continue and work on the employer facing portions of the system is being looked at.                                                                                 | 2014-05-05T00:00:00 | 
| Next Generation Tax System            | Active | Green        | Green         | Green           | Work continues on critical enhancements and bug fixes. Treasury offset program was deployed successfully. A new schedule for the employer facing portion of the project is in review and when complete a revised investment plan will be submitted.          | 2014-11-18T00:00:00 | 
```