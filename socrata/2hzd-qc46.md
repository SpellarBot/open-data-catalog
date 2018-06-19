# Asbestos Training Course Provider List

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/asbestos-training-course-provider-list-31945) |
| Metadata | [Link](https://data.illinois.gov/api/views/2hzd-qc46) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/2hzd-qc46/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/2hzd-qc46/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 2hzd-qc46 |
| Name | Asbestos Training Course Provider List |
| Attribution | IDPH, Division of Environmental Health, General Engineering Section, Asbestos Program |
| Category | Public Health |
| Tags | training course, asbestos |
| Created | 2014-03-03T20:47:30Z |
| Publication Date | 2017-03-03T20:27:55Z |

## Description

Updated February 2017 This list contains all training courses approved by the Illinois Department of Public Health for Asbestos Workers and Professionals.

## Columns

```ls
| Included | Schema Type    | Field Name                               | Name                                     | Data Type     | Render Type   |
| ======== | ============== | ======================================== | ======================================== | ============= | ============= |
| Yes      | numeric metric | idno                                     | IDNo                                     | number        | number        |
| Yes      | series tag     | course_provider                          | COURSE PROVIDER                          | text          | text          |
| Yes      | series tag     | contact_person                           | CONTACT PERSON                           | text          | text          |
| No       |                | address                                  | ADDRESS                                  | text          | text          |
| Yes      | series tag     | city                                     | CITY                                     | text          | text          |
| Yes      | series tag     | state                                    | STATE                                    | text          | text          |
| Yes      | series tag     | zip_code                                 | ZIP CODE                                 | text          | text          |
| Yes      | series tag     | phone                                    | PHONE                                    | phone         | phone         |
| Yes      | series tag     | fax                                      | FAX                                      | phone         | phone         |
| Yes      | series tag     | web_site                                 | WEB SITE                                 | url           | url           |
| No       |                | worker_initial_approval                  | WORKER INITIAL APPROVAL                  | calendar_date | calendar_date |
| No       |                | worker_initial_expire                    | WORKER INITIAL EXPIRE                    | calendar_date | calendar_date |
| No       |                | contractor_supervisor_initial_approval   | CONTRACTOR SUPERVISOR INITIAL APPROVAL   | calendar_date | calendar_date |
| No       |                | contract0r_supervisor_initial_expire     | CONTRACT0R SUPERVISOR INITIAL EXPIRE     | calendar_date | calendar_date |
| No       |                | inspector_initial_approval               | INSPECTOR INITIAL APPROVAL               | calendar_date | calendar_date |
| No       |                | inspector_initial_expire                 | INSPECTOR INITIAL EXPIRE                 | calendar_date | calendar_date |
| No       |                | management_planner_initial_approval      | MANAGEMENT PLANNER INITIAL APPROVAL      | calendar_date | calendar_date |
| No       |                | management_planner_initial_expire        | MANAGEMENT PLANNER INITIAL EXPIRE        | calendar_date | calendar_date |
| No       |                | project_designer_initial_approval        | PROJECT DESIGNER INITIAL APPROVAL        | calendar_date | calendar_date |
| No       |                | project_designer_initial_expire          | PROJECT DESIGNER INITIAL EXPIRE          | calendar_date | calendar_date |
| No       |                | worker_refresher_approval                | WORKER REFRESHER APPROVAL                | calendar_date | calendar_date |
| Yes      | time           | worker_refresher_expire                  | WORKER REFRESHER EXPIRE                  | calendar_date | calendar_date |
| No       |                | contractor_supervisor_refresher_approval | CONTRACTOR SUPERVISOR REFRESHER APPROVAL | calendar_date | calendar_date |
| No       |                | contractor_supevisor_refresher_expire    | CONTRACTOR SUPEVISOR REFRESHER EXPIRE    | calendar_date | calendar_date |
| No       |                | inspector_refresher_approval             | INSPECTOR REFRESHER APPROVAL             | calendar_date | calendar_date |
| No       |                | inspector_refresher_expire               | INSPECTOR REFRESHER EXPIRE               | calendar_date | calendar_date |
| No       |                | management_planner_refresher_approval    | MANAGEMENT PLANNER REFRESHER APPROVAL    | calendar_date | calendar_date |
| No       |                | management_planner_refrehser_expire      | MANAGEMENT PLANNER REFREHSER EXPIRE      | calendar_date | calendar_date |
| No       |                | project_designer_refresher_approval      | PROJECT DESIGNER REFRESHER APPROVAL      | calendar_date | calendar_date |
| No       |                | project_designer_expire                  | PROJECT DESIGNER EXPIRE                  | calendar_date | calendar_date |
```

## Time Field

```ls
Value = worker_refresher_expire
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address,worker_initial_approval,contractor_supervisor_initial_approval,contract0r_supervisor_initial_expire,inspector_initial_approval,inspector_initial_expire,management_planner_initial_approval,management_planner_initial_expire,project_designer_initial_approval,project_designer_initial_expire,worker_refresher_approval,worker_initial_expire,contractor_supervisor_refresher_approval,contractor_supevisor_refresher_expire,inspector_refresher_approval,inspector_refresher_expire,management_planner_refresher_approval,management_planner_refrehser_expire,project_designer_refresher_approval,project_designer_expire
```

## Data Commands

```ls
series e:2hzd-qc46 d:2017-08-03T00:00:00.000Z t:phone_number="(270) 442-7008" t:zip_code=42001 t:course_provider="ASBESTOS WORKERS REGIONAL LOCAL 207" t:state=KY t:contact_person="NEIL PITTMAN" t:city=PADUCAH m:idno=124

series e:2hzd-qc46 d:2017-04-06T00:00:00.000Z t:phone_number="(317) 375-0983" t:zip_code=46239 t:course_provider="ESAI   (SPANISH)" t:state=IN t:contact_person="SHARYN REYES" t:city=INDIANAPOLIS m:idno=160

series e:2hzd-qc46 d:2016-04-27T00:00:00.000Z t:phone_number="(309) 762-0522" t:zip_code=61265 t:course_provider="GRAVES ENVIRONMENTAL, INC." t:state=IL t:contact_person="WILLIAM WECKERLY" t:city=MOLINE m:idno=120
```

## Meta Commands

```ls
metric m:idno p:integer l:IDNo t:dataTypeName=number

entity e:2hzd-qc46 l:"Asbestos Training Course Provider List" t:attribution="IDPH, Division of Environmental Health, General Engineering Section, Asbestos Program" t:url=https://data.illinois.gov/api/views/2hzd-qc46

property e:2hzd-qc46 t:meta.view v:id=2hzd-qc46 v:category="Public Health" v:attributionLink=http://dph.illinois.gov/topics-services/environmental-health-protection/asbestos v:averageRating=0 v:name="Asbestos Training Course Provider List" v:attribution="IDPH, Division of Environmental Health, General Engineering Section, Asbestos Program"

property e:2hzd-qc46 t:meta.view.license v:name="Public Domain"

property e:2hzd-qc46 t:meta.view.owner v:id=mkk8-dris v:screenName="Greg Matheny" v:displayName="Greg Matheny"

property e:2hzd-qc46 t:meta.view.tableauthor v:id=mkk8-dris v:screenName="Greg Matheny" v:roleName=publisher v:displayName="Greg Matheny"
```

## Top Records

```ls
| idno | course_provider                            | contact_person          | address                             | city         | state | zip_code | phone                  | fax                    | web_site                            | worker_initial_approval | worker_initial_expire | contractor_supervisor_initial_approval | contract0r_supervisor_initial_expire | inspector_initial_approval | inspector_initial_expire | management_planner_initial_approval | management_planner_initial_expire | project_designer_initial_approval | project_designer_initial_expire | worker_refresher_approval | worker_refresher_expire | contractor_supervisor_refresher_approval | contractor_supevisor_refresher_expire | inspector_refresher_approval | inspector_refresher_expire | management_planner_refresher_approval | management_planner_refrehser_expire | project_designer_refresher_approval | project_designer_expire | 
| ==== | ========================================== | ======================= | =================================== | ============ | ===== | ======== | ====================== | ====================== | =================================== | ======================= | ===================== | ====================================== | ==================================== | ========================== | ======================== | =================================== | ================================= | ================================= | =============================== | ========================= | ======================= | ======================================== | ===================================== | ============================ | ========================== | ===================================== | =================================== | =================================== | ======================= | 
| 124  | ASBESTOS WORKERS REGIONAL LOCAL 207        | NEIL PITTMAN            | CENTURY BLDG 100 FOUNTAIN SUITE 101 | PADUCAH      | KY    | 42001    | [(800) 270-0940, null] | [(270) 442-7008, null] | [null, null]                        | 2006-07-24T00:00:00     | 2017-08-03T00:00:00   | 2006-03-03T00:00:00                    | 2018-03-28T00:00:00                  |                            |                          |                                     |                                   |                                   |                                 | 2006-07-24T00:00:00       | 2017-08-03T00:00:00     | 2006-03-03T00:00:00                      | 2018-03-28T00:00:00                   |                              |                            |                                       |                                     |                                     |                         | 
| 160  | ESAI (SPANISH)                             | SHARYN REYES            | 1435 SADLIER CIRCLE W DRIVE         | INDIANAPOLIS | IN    | 46239    | [(317) 352-1270, null] | [(317) 375-0983, null] | [null, null]                        | 2006-04-13T00:00:00     | 2017-05-05T00:00:00   |                                        |                                      |                            |                          |                                     |                                   |                                   |                                 | 2006-03-27T00:00:00       | 2017-04-06T00:00:00     |                                          |                                       |                              |                            |                                       |                                     |                                     |                         | 
| 120  | GRAVES ENVIRONMENTAL, INC.                 | WILLIAM WECKERLY        | PO BOX 1415                         | MOLINE       | IL    | 61265    | [(309) 762-0407, null] | [(309) 762-0522, null] | [null, null]                        | 2001-04-27T00:00:00     | 2002-04-27T00:00:00   | 2005-11-14T00:00:00                    | 2017-04-27T00:00:00                  | 2003-11-21T00:00:00        | 2015-05-02T00:00:00      |                                     |                                   |                                   |                                 | 2006-09-06T00:00:00       | 2016-04-27T00:00:00     | 2006-05-19T00:00:00                      | 2017-04-27T00:00:00                   | 2006-01-20T00:00:00          | 2017-11-13T00:00:00        | 2006-01-20T00:00:00                   | 2017-11-13T00:00:00                 |                                     |                         | 
| 5    | IL LABORERS & CONTRACTORS TRAINING PROGRAM | RON LITHERLAND          | 1730 750N AVENUE                    | MT STERLING  | IL    | 62353    | [(217) 773-2741, null] | [(217) 773-2835, null] | [null, null]                        | 2006-07-24T00:00:00     | 2017-08-09T00:00:00   | 2006-07-24T00:00:00                    | 2017-09-24T00:00:00                  |                            |                          |                                     |                                   |                                   |                                 | 2006-07-24T00:00:00       | 2017-08-09T00:00:00     | 2006-09-20T00:00:00                      | 2017-10-31T00:00:00                   |                              |                            |                                       |                                     |                                     |                         | 
| 159  | INDIANA LABORERS TRAINING TRUST FUND       | Gary M McCabe           | P.O. BOX 758                        | BEDFORD      | IN    | 47421    | [(812) 279-9751, null] | [(812) 279-5545, null] | [null, null]                        | 2006-02-15T00:00:00     | 2017-03-20T00:00:00   | 2006-02-15T00:00:00                    | 2017-03-20T00:00:00                  |                            |                          |                                     |                                   |                                   |                                 | 2006-02-15T00:00:00       | 2017-03-20T00:00:00     | 2006-02-15T00:00:00                      | 2017-03-20T00:00:00                   |                              |                            |                                       |                                     |                                     |                         | 
| 149  | SPANISH WORKSHOP CENTER-SPANISH (SWC)      | GUSTAVO DE LA ESPRIELLA | 2819 SOUTH ARCHER AVENE             | CHICAGO      | IL    | 60608    | [(312) 421-4505, null] | [(312) 421-3046, null] | [http://www.swcinstitute.com, null] | 2006-01-10T00:00:00     | 2018-01-06T00:00:00   |                                        |                                      |                            |                          |                                     |                                   |                                   |                                 | 2005-11-15T00:00:00       | 2017-11-12T00:00:00     |                                          |                                       |                              |                            |                                       |                                     |                                     |                         | 
| 192  | RESOLUTION, INC.                           | Angelina Mullen         | 1101 A DARBYTOWN DRIVE              | NASHVILLE    | TN    | 37207    | [(615) 865-8813, null] | [(615) 868-4140, null] | [null, null]                        |                         |                       |                                        | 2017-05-13T00:00:00                  |                            |                          |                                     |                                   |                                   |                                 |                           | 2017-02-27T00:00:00     |                                          | 2017-02-27T00:00:00                   |                              | 2017-02-27T00:00:00        |                                       |                                     |                                     |                         | 
| 8    | ENVIRONMENTAL GROUP SERVICE LTD (EGSL)     | VAHOOMAN MIRKHAEF       | 557 W. POLK STREET, SUITE 201       | CHICAGO      | IL    | 60607    | [(312) 447-1200, null] | [(312) 447-0922, null] | [null, null]                        | 2006-04-05T00:00:00     | 2017-05-14T00:00:00   | 2006-04-05T00:00:00                    | 2017-05-14T00:00:00                  |                            |                          |                                     |                                   |                                   |                                 | 2006-04-05T00:00:00       | 2017-05-14T00:00:00     | 2006-04-05T00:00:00                      | 2017-05-14T00:00:00                   |                              |                            |                                       |                                     |                                     |                         | 
| 189  | ESTC (ENGLISH)                             | Michael Renfroe         | 907 DOCK STREET                     | ST. LOUIS    | MO    | 63147    | [(314) 739-1155, null] | [(317) 870-1007, null] | [null, null]                        |                         |                       |                                        | 2017-03-05T00:00:00                  |                            | 2017-03-05T00:00:00      |                                     | 2015-12-10T00:00:00               |                                   |                                 |                           | 2018-01-14T00:00:00     |                                          | 2017-03-05T00:00:00                   |                              | 2017-03-05T00:00:00        |                                       | 2015-12-10T00:00:00                 |                                     |                         | 
| 112  | CARNOW, CONIBEAR & ASSOCIATES              | DAVID KEDROWSKI         | 600 WEST VAN BUREN ST SUITE 500     | CHICAGO      | IL    | 60607    | [(312) 782-4486, null] | [(312) 782-5145, null] | [null, null]                        | 2005-11-22T00:00:00     | 2007-12-29T00:00:00   | 2005-11-22T00:00:00                    | 2014-05-06T00:00:00                  | 1998-11-30T00:00:00        | 1999-12-29T00:00:00      | 1998-11-30T00:00:00                 | 1999-12-29T00:00:00               |                                   |                                 | 2005-11-22T00:00:00       | 2013-12-29T00:00:00     | 2005-11-22T00:00:00                      | 2013-12-29T00:00:00                   | 2005-11-22T00:00:00          | 2013-12-29T00:00:00        | 1998-11-09T00:00:00                   | 1999-12-29T00:00:00                 |                                     |                         | 
```