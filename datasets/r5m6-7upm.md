# Illinois Lead Program Exam Dates

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/illinois-lead-program-exam-dates) |
| Metadata | [Link](https://data.illinois.gov/api/views/r5m6-7upm) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/r5m6-7upm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/r5m6-7upm/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | r5m6-7upm |
| Name | Illinois Lead Program Exam Dates |
| Category | Public Health |
| Tags | lead, exam, risk assessor |
| Created | 2014-01-21T20:28:47Z |
| Publication Date | 2017-01-05T17:57:42Z |

## Description

Lead Inspectors, Risk Assessors, and Supervisors
Third Party Examination Schedule for Illinois
Since classroom space is limited, examination applications must be submitted at least four weeks prior to the desired examination date. After meeting all the requirements and passing the (Third Party Examination), your license and examination certificate will be processed and mailed to you.
Updated January 2017

## Columns

```ls
| Included | Schema Type | Field Name              | Name                    | Data Type     | Render Type   |
| ======== | =========== | ======================= | ======================= | ============= | ============= |
| Yes      | series tag  | exam_location           | Exam Location           | text          | text          |
| Yes      | series tag  | exam_site_contact_phone | Exam Site Contact Phone | text          | text          |
| No       |             | exam_date               | Exam Date               | calendar_date | calendar_date |
| No       |             | exam_time               | Exam Time               | text          | text          |
| Yes      | series tag  | lead_program_contact    | Lead Program Contact    | text          | text          |
| Yes      | series tag  | class_space             | Class Space             | text          | text          |
| Yes      | series tag  | notes                   | Notes                   | text          | text          |
```

## Time Field

```ls
Value = exam_date-exam_time
Format & Zone = yyyy-MM-dd'T'HH:mm:ss-hh:mm a
```

## Series Fields

```ls
Excluded Fields = exam_time,exam_date
```

## Data Commands

```ls
series e:r5m6-7upm d:2017-02-02T09:00:00.000Z t:lead_program_contact=217-782-3517 t:exam_site_contact_phone=217-278-5900 t:exam_location="IDPH Champaign Regional Office" t:notes="Since classroom space is limited, examination applications must be submitted at least four weeks prior to the desired examination date. After meeting all the requirements and passing the (Third Party Examination), your license and examination certificate will be processed and mailed to you." m:row_number.r5m6-7upm=1

series e:r5m6-7upm d:2017-03-02T09:00:00.000Z t:lead_program_contact=217-782-3517 t:exam_site_contact_phone=217-278-5900 t:exam_location="IDPH Champaign Regional Office" t:notes="Since classroom space is limited, examination applications must be submitted at least four weeks prior to the desired examination date. After meeting all the requirements and passing the (Third Party Examination), your license and examination certificate will be processed and mailed to you." m:row_number.r5m6-7upm=2

series e:r5m6-7upm d:2017-04-06T09:00:00.000Z t:lead_program_contact=217-782-3517 t:exam_site_contact_phone=217-278-5900 t:exam_location="IDPH Champaign Regional Office" t:notes="Since classroom space is limited, examination applications must be submitted at least four weeks prior to the desired examination date. After meeting all the requirements and passing the (Third Party Examination), your license and examination certificate will be processed and mailed to you." m:row_number.r5m6-7upm=3
```

## Meta Commands

```ls
metric m:row_number.r5m6-7upm p:long l:"Row Number"

entity e:r5m6-7upm l:"Illinois Lead Program Exam Dates" t:url=https://data.illinois.gov/api/views/r5m6-7upm

property e:r5m6-7upm t:meta.view v:id=r5m6-7upm v:category="Public Health" v:averageRating=0 v:name="Illinois Lead Program Exam Dates"

property e:r5m6-7upm t:meta.view.license v:name="Public Domain"

property e:r5m6-7upm t:meta.view.owner v:id=6dyi-26tm v:screenName="ken mccann" v:displayName="ken mccann"

property e:r5m6-7upm t:meta.view.tableauthor v:id=6dyi-26tm v:screenName="ken mccann" v:roleName=publisher v:displayName="ken mccann"
```

## Top Records

```ls
| exam_location                  | exam_site_contact_phone | exam_date           | exam_time | lead_program_contact | class_space | notes                                                                                                                                                                                                                                                                                               | 
| ============================== | ======================= | =================== | ========= | ==================== | =========== | =================================================================================================================================================================================================================================================================================================== | 
| IDPH Champaign Regional Office | 217-278-5900            | 2017-02-02T00:00:00 | 9:00 AM   | 217-782-3517         |             | Since classroom space is limited, examination applications must be submitted at least four weeks prior to the desired examination date. After meeting all the requirements and passing the (Third Party Examination), your license and examination certificate will be processed and mailed to you. | 
| IDPH Champaign Regional Office | 217-278-5900            | 2017-03-02T00:00:00 | 9:00 AM   | 217-782-3517         |             | Since classroom space is limited, examination applications must be submitted at least four weeks prior to the desired examination date. After meeting all the requirements and passing the (Third Party Examination), your license and examination certificate will be processed and mailed to you. | 
| IDPH Champaign Regional Office | 217-278-5900            | 2017-04-06T00:00:00 | 9:00 AM   | 217-782-3517         |             | Since classroom space is limited, examination applications must be submitted at least four weeks prior to the desired examination date. After meeting all the requirements and passing the (Third Party Examination), your license and examination certificate will be processed and mailed to you. | 
| IDPH Champaign Regional Office | 217-278-5900            | 2017-05-04T00:00:00 | 9:00 AM   | 217-782-3517         |             | Since classroom space is limited, examination applications must be submitted at least four weeks prior to the desired examination date. After meeting all the requirements and passing the (Third Party Examination), your license and examination certificate will be processed and mailed to you. | 
| IDPH Champaign Regional Office | 217-278-5900            | 2017-06-01T00:00:00 | 9:00 AM   | 217-782-3517         |             | Since classroom space is limited, examination applications must be submitted at least four weeks prior to the desired examination date. After meeting all the requirements and passing the (Third Party Examination), your license and examination certificate will be processed and mailed to you. | 
| IDPH Champaign Regional Office | 217-278-5900            | 2017-07-06T00:00:00 | 9:00 AM   | 217-782-3517         |             | Since classroom space is limited, examination applications must be submitted at least four weeks prior to the desired examination date. After meeting all the requirements and passing the (Third Party Examination), your license and examination certificate will be processed and mailed to you. | 
| IDPH Champaign Regional Office | 217-278-5900            | 2017-08-03T00:00:00 | 9:00 AM   | 217-782-3517         |             | Since classroom space is limited, examination applications must be submitted at least four weeks prior to the desired examination date. After meeting all the requirements and passing the (Third Party Examination), your license and examination certificate will be processed and mailed to you. | 
| IDPH Champaign Regional Office | 217-278-5900            | 2017-09-07T00:00:00 | 9:00 AM   | 217-782-3517         |             | Since classroom space is limited, examination applications must be submitted at least four weeks prior to the desired examination date. After meeting all the requirements and passing the (Third Party Examination), your license and examination certificate will be processed and mailed to you. | 
| IDPH Champaign Regional Office | 217-278-5900            | 2017-10-05T00:00:00 | 9:00 AM   | 217-782-3517         |             | Since classroom space is limited, examination applications must be submitted at least four weeks prior to the desired examination date. After meeting all the requirements and passing the (Third Party Examination), your license and examination certificate will be processed and mailed to you. | 
| IDPH Champaign Regional Office | 217-278-5900            | 2017-11-02T00:00:00 | 9:00 AM   | 217-782-3517         |             | Since classroom space is limited, examination applications must be submitted at least four weeks prior to the desired examination date. After meeting all the requirements and passing the (Third Party Examination), your license and examination certificate will be processed and mailed to you. | 
```