# OCIO IT Project Oversight Assessment Details

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ocio-it-project-oversight-assessment-details-139fa) |
| Metadata | [Link](https://data.wa.gov/api/views/9dnz-48uh) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/9dnz-48uh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/9dnz-48uh/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | 9dnz-48uh |
| Name | OCIO IT Project Oversight Assessment Details |
| Attribution | Office of the CIO |
| Category | Procurements and Contracts |
| Tags | it projects ocio |
| Created | 2014-07-30T19:23:44Z |
| Publication Date | 2015-04-07T19:20:22Z |

## Description

Project oversight OCIO Assessment details. See OCIO IT Project Oversight Summary (https://data.wa.gov/resource/k495-fmg2) for main project information.

## Columns

```ls
| Included | Schema Type | Field Name | Name       | Data Type     | Render Type   |
| ======== | =========== | ========== | ========== | ============= | ============= |
| Yes      | series tag  | project    | Project    | text          | text          |
| Yes      | series tag  | status     | Status     | text          | text          |
| Yes      | series tag  | assessment | Assessment | text          | text          |
| Yes      | time        | entered_on | Entered On | calendar_date | calendar_date |
```

## Time Field

```ls
Value = entered_on
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:9dnz-48uh d:2014-07-23T00:00:00.000Z t:project="Enterprise Document Management System" t:assessment="Project on-hold until new calendar year." m:row_number.9dnz-48uh=1

series e:9dnz-48uh d:2013-11-20T00:00:00.000Z t:project="Enterprise Document Management System" t:status=Green t:assessment="Latest indicators suggest good progress towards goals." m:row_number.9dnz-48uh=2

series e:9dnz-48uh d:2013-07-25T00:00:00.000Z t:project="Enterprise Document Management System" t:status=Green t:assessment="This project is considered ""green"" until latest status and QA reports are received." m:row_number.9dnz-48uh=3
```

## Meta Commands

```ls
metric m:row_number.9dnz-48uh p:long l:"Row Number"

entity e:9dnz-48uh l:"OCIO IT Project Oversight Assessment Details" t:attribution="Office of the CIO" t:url=https://data.wa.gov/api/views/9dnz-48uh

property e:9dnz-48uh t:meta.view v:id=9dnz-48uh v:category="Procurements and Contracts" v:attributionLink=http://www.ocio.wa.gov/its-transparent-project-dashboard v:averageRating=0 v:name="OCIO IT Project Oversight Assessment Details" v:attribution="Office of the CIO"

property e:9dnz-48uh t:meta.view.license v:name="Public Domain"

property e:9dnz-48uh t:meta.view.owner v:id=2cik-4ce4 v:screenName="Jason McKee" v:displayName="Jason McKee"

property e:9dnz-48uh t:meta.view.tableauthor v:id=2cik-4ce4 v:screenName="Jason McKee" v:roleName=publisher v:displayName="Jason McKee"
```

## Top Records

```ls
| project                               | status | assessment                                                                                                                                                                                                             | entered_on          | 
| ===================================== | ====== | ====================================================================================================================================================================================================================== | =================== | 
| Enterprise Document Management System |        | Project on-hold until new calendar year.                                                                                                                                                                               | 2014-07-23T00:00:00 | 
| Enterprise Document Management System | Green  | Latest indicators suggest good progress towards goals.                                                                                                                                                                 | 2013-11-20T00:00:00 | 
| Enterprise Document Management System | Green  | This project is considered "green" until latest status and QA reports are received.                                                                                                                                    | 2013-07-25T00:00:00 | 
| Enterprise Document Management System | Green  | This project is a model project and all is well at this time.                                                                                                                                                          | 2014-03-17T00:00:00 | 
| Enterprise Document Management System | Green  | The OCIO was not able to attend this months Steering Committee meeting but after reviewing the documentation the project is progressing well and going well for this stage of the process.                             | 2014-04-21T00:00:00 | 
| Gaming Vendor Replacement             | Yellow | Steering Committee meetings are tentatively planned to begin at the end of March. Depending on how far off the new baseline schedule is from the original, we may need to amend the investment plan.                   | 2015-03-13T00:00:00 | 
| Gaming Vendor Replacement             | Green  | Lottery's submission of policy waiver and investment requests was oddly sequenced, but appropriate project documentation is now complete and posted.                                                                   | 2014-05-09T00:00:00 | 
| Next Generation Tax System            | Yellow | Schedule change. See latest amendment.                                                                                                                                                                                 | 2013-12-09T00:00:00 | 
| Next Generation Tax System            | Green  | There are no high risk categories noted in the March QA report. NGTS continues to stabilize in the wake of March 12 "go live" as work progresses toward the Stage 4 tax-filing applications "go live" August 25, 2014. | 2014-04-17T00:00:00 | 
| Next Generation Tax System            | Red    | This project is red pending receipt from ESD of an approval request for an amended investment plan that sets a new project completion date,                                                                            | 2014-08-27T00:00:00 | 
```