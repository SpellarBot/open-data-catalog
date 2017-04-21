# Port of Los Angeles - ADP Project

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/port-of-los-angeles-adp-project) |
| Metadata | [Link](https://data.lacity.org/api/views/s5jy-jcce) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/s5jy-jcce/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/s5jy-jcce/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | s5jy-jcce |
| Name | Port of Los Angeles - ADP Project |
| Attribution | Port of Los Angeles |
| Category | A Livable and Sustainable City |
| Tags | permit |
| Created | 2014-04-15T23:37:22Z |
| Publication Date | 2015-12-07T20:15:12Z |

## Description

Port of Los Angeles - Application for Discretionary Permit (ADP) Project

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type     | Render Type   |
| ======== | ============== | ======================== | ======================== | ============= | ============= |
| Yes      | series tag     | incrementalid            | IncrementalID            | text          | number        |
| Yes      | series tag     | adpnumber                | ADPNumber                | text          | text          |
| Yes      | series tag     | adpstatus                | ADPStatus                | text          | text          |
| Yes      | series tag     | applicant                | Applicant                | text          | text          |
| Yes      | series tag     | entitlement              | Entitlement              | text          | text          |
| Yes      | series tag     | projectdescription       | ProjectDescription       | text          | text          |
| Yes      | series tag     | projectlocation          | ProjectLocation          | text          | text          |
| Yes      | series tag     | projecttype              | ProjectType              | text          | text          |
| Yes      | time           | adpreceiveddate          | ADPReceivedDate          | calendar_date | calendar_date |
| No       |                | adpsenttodivisiondate    | ADPSentToDivisionDate    | calendar_date | calendar_date |
| No       |                | emdreceiveddate          | EMDReceivedDate          | calendar_date | calendar_date |
| No       |                | engpermitreceiveddate    | ENGPermitReceivedDate    | calendar_date | calendar_date |
| Yes      | series tag     | engpermitreceiveddatena  | ENGPermitReceivedDateNA  | text          | text          |
| No       |                | adpcompletiondate        | ADPCompletionDate        | calendar_date | calendar_date |
| Yes      | series tag     | typeofcdp                | TypeofCDP                | text          | text          |
| Yes      | series tag     | typeofexemption          | TypeofExemption          | text          | text          |
| Yes      | series tag     | cdpnumber                | CDPNumber                | text          | text          |
| No       |                | cdpsentdatetoapplicant   | CDPSentDateToApplicant   | calendar_date | calendar_date |
| Yes      | series tag     | cdpsentdatetoapplicantna | CDPSentDateToApplicantNA | text          | text          |
| No       |                | cdpreceiveddate          | CDPReceivedDate          | calendar_date | calendar_date |
| Yes      | series tag     | cdpreceiveddatena        | CDPReceivedDateNA        | text          | text          |
| No       |                | publichearingdate        | PublicHearingDate        | calendar_date | calendar_date |
| Yes      | series tag     | publichearingdatena      | PublicHearingDateNA      | text          | text          |
| No       |                | bhcapprovaldate          | BHCApprovalDate          | calendar_date | calendar_date |
| Yes      | series tag     | bhcapprovaldatena        | BHCApprovalDateNA        | text          | text          |
| Yes      | numeric metric | appealablecdp            | AppealableCDP            | number        | number        |
| No       |                | endofappealperioddate    | EndOfAppealPeriodDate    | calendar_date | calendar_date |
| Yes      | series tag     | endofappealperioddatena  | EndofAppealPeriodDateNA  | text          | text          |
| No       |                | costalcommapprovaldate   | CostalCommApprovalDate   | text          | text          |
| Yes      | series tag     | costalcommapprovaldatena | CostalCommApprovalDateNA | text          | text          |
| No       |                | cdpsentdatetodivsions    | CDPSentDateToDivsions    | calendar_date | calendar_date |
| Yes      | series tag     | cdpsentdatetodivsionsna  | CDPSentDateToDivsionsNA  | text          | text          |
| Yes      | numeric metric | riskanalysis             | RiskAnalysis             | number        | number        |
| Yes      | series tag     | senttolafd               | SentToLAFD               | text          | text          |
| Yes      | series tag     | lafd10dayreview          | LAFD10DayReview          | text          | text          |
| No       |                | reporttoapplicant        | ReportToApplicant        | calendar_date | calendar_date |
| Yes      | series tag     | reporttoapplicantna      | ReportToApplicantNA      | text          | text          |
| Yes      | series tag     | notes                    | Notes                    | text          | text          |
| Yes      | series tag     | cancellationflag         | CancellationFlag         | text          | text          |
| Yes      | series tag     | cdpfoldername            | CDPFolderName            | text          | text          |
```

## Time Field

```ls
Value = adpreceiveddate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = adpsenttodivisiondate,emdreceiveddate,engpermitreceiveddate,adpcompletiondate,cdpsentdatetoapplicant,cdpreceiveddate,publichearingdate,bhcapprovaldate,endofappealperioddate,costalcommapprovaldate,cdpsentdatetodivsions,reporttoapplicant
```

## Data Commands

```ls
series e:s5jy-jcce d:2008-01-03T00:00:00.000Z t:projectdescription="Abandonment of existing natural gas main.  Isolated cut (4x4)" t:projectlocation="Pier ""A"" Place" t:reporttoapplicantna=FALSE t:engpermitreceiveddatena=FALSE t:endofappealperioddatena=FALSE t:projecttype=Development t:incrementalid=188 t:costalcommapprovaldatena=FALSE t:typeofcdp=Exempt t:cdpsentdatetoapplicantna=FALSE t:cancellationflag=FALSE t:bhcapprovaldatena=FALSE t:adpstatus=Completed t:adpnumber=080103-001 t:cdpreceiveddatena=FALSE t:applicant="Southern California Gas Co." t:publichearingdatena=FALSE t:cdpnumber=N/A t:entitlement="Order 4506" t:typeofexemption=30610(f) t:cdpsentdatetodivsionsna=FALSE m:riskanalysis=0 m:appealablecdp=3

series e:s5jy-jcce d:2008-01-09T00:00:00.000Z t:projectdescription="POLA - CEQA determination to Permit 718 of Crowley Marine Services, Inc. for five year term November 24, 2006 - November 23, 2011 at Berth 86" t:reporttoapplicantna=FALSE t:engpermitreceiveddatena=FALSE t:endofappealperioddatena=TRUE t:projecttype=Administrative t:incrementalid=264 t:costalcommapprovaldatena=TRUE t:typeofcdp=N/A t:cdpsentdatetoapplicantna=TRUE t:cancellationflag=FALSE t:bhcapprovaldatena=TRUE t:adpstatus=Completed t:adpnumber=080109-002 t:cdpreceiveddatena=TRUE t:applicant=POLA t:publichearingdatena=TRUE t:cdpnumber=N/A t:entitlement="Permit 718" t:typeofexemption=N/A t:cdpsentdatetodivsionsna=TRUE m:riskanalysis=3 m:appealablecdp=3

series e:s5jy-jcce d:2008-01-10T00:00:00.000Z t:projectdescription="Holiday Harbor-Fleitz Bros. LLC - requesting to set-up chairs on the turn-around outside office building at Berth 34 for Bill Gribble Memorial" t:reporttoapplicantna=FALSE t:engpermitreceiveddatena=FALSE t:endofappealperioddatena=TRUE t:projecttype=Administrative t:incrementalid=415 t:costalcommapprovaldatena=TRUE t:typeofcdp=N/A t:cdpsentdatetoapplicantna=TRUE t:cancellationflag=FALSE t:bhcapprovaldatena=TRUE t:adpstatus=Completed t:adpnumber=080110-003 t:cdpreceiveddatena=TRUE t:applicant="Holiday Harbor-Fleitz Bros. LLC" t:publichearingdatena=TRUE t:cdpnumber=N/A t:typeofexemption=N/A t:cdpsentdatetodivsionsna=TRUE m:riskanalysis=3 m:appealablecdp=3
```

## Meta Commands

```ls
metric m:appealablecdp p:integer l:AppealableCDP t:dataTypeName=number

metric m:riskanalysis p:integer l:RiskAnalysis t:dataTypeName=number

entity e:s5jy-jcce l:"Port of Los Angeles - ADP Project" t:attribution="Port of Los Angeles" t:url=https://data.lacity.org/api/views/s5jy-jcce

property e:s5jy-jcce t:meta.view v:id=s5jy-jcce v:category="A Livable and Sustainable City" v:averageRating=0 v:name="Port of Los Angeles - ADP Project" v:attribution="Port of Los Angeles"

property e:s5jy-jcce t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:s5jy-jcce t:meta.view.owner v:id=2ib6-ssvz v:profileImageUrlMedium=/api/users/2ib6-ssvz/profile_images/THUMB v:profileImageUrlLarge=/api/users/2ib6-ssvz/profile_images/LARGE v:screenName="Port of Los Angeles" v:profileImageUrlSmall=/api/users/2ib6-ssvz/profile_images/TINY v:displayName="Port of Los Angeles"

property e:s5jy-jcce t:meta.view.tableauthor v:id=2ib6-ssvz v:profileImageUrlMedium=/api/users/2ib6-ssvz/profile_images/THUMB v:profileImageUrlLarge=/api/users/2ib6-ssvz/profile_images/LARGE v:screenName="Port of Los Angeles" v:profileImageUrlSmall=/api/users/2ib6-ssvz/profile_images/TINY v:roleName=publisher v:displayName="Port of Los Angeles"
```

## Top Records

```ls
| incrementalid | adpnumber  | adpstatus | applicant                       | entitlement | projectdescription                                                                                                                             | projectlocation                                                                            | projecttype    | adpreceiveddate     | adpsenttodivisiondate | emdreceiveddate     | engpermitreceiveddate | engpermitreceiveddatena | adpcompletiondate   | typeofcdp | typeofexemption | cdpnumber | cdpsentdatetoapplicant | cdpsentdatetoapplicantna | cdpreceiveddate | cdpreceiveddatena | publichearingdate | publichearingdatena | bhcapprovaldate | bhcapprovaldatena | appealablecdp | endofappealperioddate | endofappealperioddatena | costalcommapprovaldate | costalcommapprovaldatena | cdpsentdatetodivsions | cdpsentdatetodivsionsna | riskanalysis | senttolafd | lafd10dayreview | reporttoapplicant   | reporttoapplicantna | notes                                                   | cancellationflag | cdpfoldername | 
| ============= | ========== | ========= | =============================== | =========== | ============================================================================================================================================== | ========================================================================================== | ============== | =================== | ===================== | =================== | ===================== | ======================= | =================== | ========= | =============== | ========= | ====================== | ======================== | =============== | ================= | ================= | =================== | =============== | ================= | ============= | ===================== | ======================= | ====================== | ======================== | ===================== | ======================= | ============ | ========== | =============== | =================== | =================== | ======================================================= | ================ | ============= | 
| 188           | 080103-001 | Completed | Southern California Gas Co.     | Order 4506  | Abandonment of existing natural gas main. Isolated cut (4x4)                                                                                   | Pier "A" Place                                                                             | Development    | 2008-01-03T00:00:00 | 2008-01-03T00:00:00   | 2008-01-25T00:00:00 | 2008-02-07T00:00:00   | FALSE                   | 2008-02-07T00:00:00 | Exempt    | 30610(f)        | N/A       |                        | FALSE                    |                 | FALSE             |                   | FALSE               |                 | FALSE             | 3             |                       | FALSE                   |                        | FALSE                    |                       | FALSE                   | 0            |            |                 | 2008-01-29T00:00:00 | FALSE               |                                                         | FALSE            |               | 
| 264           | 080109-002 | Completed | POLA                            | Permit 718  | POLA - CEQA determination to Permit 718 of Crowley Marine Services, Inc. for five year term November 24, 2006 - November 23, 2011 at Berth 86  |                                                                                            | Administrative | 2008-01-09T00:00:00 | 2008-01-09T00:00:00   | 2008-01-16T00:00:00 |                       | FALSE                   | 2008-01-16T00:00:00 | N/A       | N/A             | N/A       |                        | TRUE                     |                 | TRUE              |                   | TRUE                |                 | TRUE              | 3             |                       | TRUE                    |                        | TRUE                     |                       | TRUE                    | 3            |            |                 |                     | FALSE               |                                                         | FALSE            |               | 
| 415           | 080110-003 | Completed | Holiday Harbor-Fleitz Bros. LLC |             | Holiday Harbor-Fleitz Bros. LLC - requesting to set-up chairs on the turn-around outside office building at Berth 34 for Bill Gribble Memorial |                                                                                            | Administrative | 2008-01-10T00:00:00 | 2008-01-10T00:00:00   | 2008-02-27T00:00:00 |                       | FALSE                   | 2008-02-27T00:00:00 | N/A       | N/A             | N/A       |                        | TRUE                     |                 | TRUE              |                   | TRUE                |                 | TRUE              | 3             |                       | TRUE                    |                        | TRUE                     |                       | TRUE                    | 3            |            |                 |                     | FALSE               |                                                         | FALSE            |               | 
| 416           | 080114-004 | Completed | Exxon Mobil                     |             | ExxonMobil - install permanent flow test on fire water system                                                                                  | 799 South Seaside Ave. Terminal Island                                                     |                | 2008-01-14T00:00:00 | 2008-01-14T00:00:00   | 2008-02-22T00:00:00 |                       | FALSE                   | 2008-02-22T00:00:00 | Exempt    | 30610(f)        |           |                        | FALSE                    |                 | FALSE             |                   | FALSE               |                 | FALSE             | 0             |                       | FALSE                   |                        | FALSE                    |                       | FALSE                   | 0            |            |                 |                     | FALSE               |                                                         | FALSE            |               | 
| 417           | 080115-005 | Completed | Container Intermodal Transport  |             | lease subject site for container and truck parking,                                                                                            | see Exhibit A for project location                                                         | Development    | 2008-01-14T00:00:00 | 2008-01-14T00:00:00   | 2008-02-27T00:00:00 |                       | FALSE                   | 2012-01-18T00:00:00 | N/A       | N/A             | N/A       |                        | TRUE                     |                 | TRUE              |                   | TRUE                |                 | TRUE              | 3             |                       | TRUE                    |                        | TRUE                     |                       | TRUE                    | 3            |            |                 | 2013-03-05T00:00:00 | FALSE               |                                                         | FALSE            |               | 
| 418           | 080115-006 | Completed | LBCT                            | RP 07-11    | proposed retaining wall on property line and drainage per plans                                                                                | 1040 N. Goodrich Ave, Wilmington CA 90744                                                  | Development    | 2008-01-15T00:00:00 | 2008-01-15T00:00:00   | 2008-04-01T00:00:00 |                       | FALSE                   | 2012-04-19T00:00:00 | N/A       | Outside CZ      |           |                        | FALSE                    |                 | FALSE             |                   | FALSE               |                 | FALSE             | 0             |                       | FALSE                   |                        | FALSE                    |                       | FALSE                   | 0            |            |                 | 2008-03-27T00:00:00 | FALSE               | 4/2012:Tenant is no longer occupying the Port property. | FALSE            |               | 
| 427           | 080115-007 | Completed | Pacific Harbor Line             | TEUP 1048   | proposes to operate a temporary liquefied natural gas (LNG) fueling station                                                                    | at end of West Basin Container Terminal                                                    | Development    | 2008-01-15T00:00:00 | 2008-01-15T00:00:00   | 2008-01-28T00:00:00 | 2008-03-03T00:00:00   | FALSE                   | 2008-03-03T00:00:00 | Exempt    | 30610(b)        |           |                        | FALSE                    |                 | FALSE             |                   | FALSE               |                 | FALSE             | 0             |                       | FALSE                   |                        | FALSE                    |                       | FALSE                   | 0            |            |                 | 2008-01-28T00:00:00 | FALSE               |                                                         | FALSE            |               | 
| 419           | 080116-008 | Completed | Arco Terminal Services Corp.    | Permit 705  | installation of test leads to enhance cathodic protection system                                                                               | Middle Road south of Sepulveda Blvd.                                                       | Development    | 2008-01-16T00:00:00 | 2008-01-16T00:00:00   | 2008-03-13T00:00:00 | 2008-04-02T00:00:00   | FALSE                   | 2008-04-02T00:00:00 | Exempt    | 30610(d)        |           |                        | FALSE                    |                 | FALSE             |                   | FALSE               |                 | FALSE             | 0             |                       | FALSE                   |                        | FALSE                    |                       | FALSE                   | 0            |            |                 | 2008-02-22T00:00:00 | FALSE               |                                                         | FALSE            |               | 
| 420           | 080116-009 | Completed | Arco Terminal Services Corp     | Permit 705  | close interval potential survey                                                                                                                | 2401 E PCH, Wilmington; east of Dominguez Channel, north of 3rd Street and west of TI Fwy. | Development    | 2008-01-16T00:00:00 | 2008-01-16T00:00:00   | 2008-02-22T00:00:00 | 2008-04-01T00:00:00   | FALSE                   | 2008-04-01T00:00:00 | Exempt    | 30610(d)        |           |                        | FALSE                    |                 | FALSE             |                   | FALSE               |                 | FALSE             | 0             |                       | FALSE                   |                        | FALSE                    |                       | FALSE                   | 0            |            |                 | 2008-03-11T00:00:00 | FALSE               |                                                         | FALSE            |               | 
| 421           | 080117-010 | Completed | Pacific Energy Partners         | TEUP 1042   | perform potholing, geotechnical bores, and CPTs for pipelines                                                                                  | Pier 400                                                                                   | Development    | 2008-01-17T00:00:00 | 2008-01-22T00:00:00   | 2008-02-27T00:00:00 | 2008-03-04T00:00:00   | FALSE                   | 2008-03-04T00:00:00 | Exempt    | 30610(d)        |           |                        | FALSE                    |                 | FALSE             |                   | FALSE               |                 | FALSE             | 0             |                       | FALSE                   |                        | FALSE                    |                       | FALSE                   | 0            |            |                 | 2008-02-22T00:00:00 | FALSE               |                                                         | FALSE            |               | 
```