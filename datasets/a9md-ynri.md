# Civil Service List Certification

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/civil-service-list-certification) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/a9md-ynri) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/a9md-ynri/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/a9md-ynri/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | a9md-ynri |
| Name | Civil Service List Certification |
| Attribution | Department of Citywide Administrative Services (DCAS) |
| Category | City Government |
| Tags | civil, service, list, title, dcas |
| Created | 2016-11-16T19:24:56Z |
| Publication Date | 2017-04-20T13:30:57Z |

## Description

A List Certification includes the names of eligible candidates on an Active Civil Service List that has been established.  The Certification may contain part of a list, the whole list, or multiple lists at the request of an appointing agency, to fill vacancies and/or replace provisionals.  Eligible candidates on a Certification may be considered for probable appointment at the appointing Agency.  For more information visit DCAS? ?Work for the City? webpage at: http://www.nyc.gov/html/dcas/html/work/work.shtml

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type     | Render Type   |
| ======== | ============== | ======================= | ======================= | ============= | ============= |
| Yes      | series tag     | exam_no                 | Exam No                 | text          | text          |
| Yes      | series tag     | list_no                 | List No                 | text          | number        |
| Yes      | series tag     | first_name              | First Name              | text          | text          |
| No       |                | mi                      | MI                      | text          | text          |
| Yes      | series tag     | last_name               | Last Name               | text          | text          |
| Yes      | series tag     | list_agency_code        | List Agency Code        | text          | text          |
| Yes      | series tag     | list_agency_desc        | List Agency Desc        | text          | text          |
| Yes      | series tag     | list_title_desc         | List Title Desc         | text          | text          |
| Yes      | series tag     | cert_seq_no             | Cert Seq No             | text          | number        |
| Yes      | time           | request_date            | Request Date            | calendar_date | calendar_date |
| Yes      | numeric metric | salary                  | Salary                  | money         | money         |
| Yes      | series tag     | cert_issue_no           | Cert Issue No           | text          | number        |
| No       |                | cert_date               | Cert Date               | calendar_date | calendar_date |
| No       |                | reissue_date            | Reissue Date            | calendar_date | calendar_date |
| No       |                | cert_expiration_date    | Cert Expiration Date    | calendar_date | calendar_date |
| Yes      | numeric metric | no_certified            | No Certified            | number        | number        |
| Yes      | numeric metric | no_requested            | No Requested            | number        | number        |
| Yes      | series tag     | provisional_replacement | Provisional Replacement | text          | text          |
| Yes      | numeric metric | no_vacancies            | No Vacancies            | number        | number        |
| Yes      | series tag     | list_title_code         | List Title Code         | text          | text          |
| Yes      | series tag     | sel_cert_description    | Sel Cert Description    | text          | text          |
```

## Time Field

```ls
Value = request_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = mi,cert_date,reissue_date,cert_expiration_date
```

## Data Commands

```ls
series e:a9md-ynri d:2016-11-15T00:00:00.000Z t:first_name=ELIZABETH t:provisional_replacement=N t:cert_issue_no=62697 t:list_no=43.000 t:exam_no=04036 t:list_title_code=40501 t:list_agency_code=040 t:cert_seq_no=1.000 t:last_name=ELLIS t:list_title_desc="MANAGEMENT AUDITOR TRAINEE" t:list_agency_desc="DEPARTMENT OF EDUCATION" m:no_vacancies=1 m:no_requested=10 m:salary=42289 m:no_certified=18

series e:a9md-ynri d:2016-11-15T00:00:00.000Z t:first_name=YELENA t:provisional_replacement=N t:cert_issue_no=62697 t:list_no=48.000 t:exam_no=04036 t:list_title_code=40501 t:list_agency_code=040 t:cert_seq_no=2.000 t:last_name=KVETNAYA t:list_title_desc="MANAGEMENT AUDITOR TRAINEE" t:list_agency_desc="DEPARTMENT OF EDUCATION" m:no_vacancies=1 m:no_requested=10 m:salary=42289 m:no_certified=18

series e:a9md-ynri d:2016-11-15T00:00:00.000Z t:first_name=JING t:provisional_replacement=N t:cert_issue_no=62697 t:list_no=52.000 t:exam_no=04036 t:list_title_code=40501 t:list_agency_code=040 t:cert_seq_no=3.000 t:last_name=LU-HSIEH t:list_title_desc="MANAGEMENT AUDITOR TRAINEE" t:list_agency_desc="DEPARTMENT OF EDUCATION" m:no_vacancies=1 m:no_requested=10 m:salary=42289 m:no_certified=18
```

## Meta Commands

```ls
metric m:salary p:double l:Salary d:"The hiring salary for a title." t:dataTypeName=money

metric m:no_certified p:long l:"No Certified" d:"Represents the number (?No?) of eligible candidates sent to an appointing agency as part of the Certification." t:dataTypeName=number

metric m:no_requested p:long l:"No Requested" d:"Represents the number (?No?) of eligible candidates requested by an appointing Agency to fill vacancies." t:dataTypeName=number

metric m:no_vacancies p:long l:"No Vacancies" d:"Represent the number (?No?) of vacancies an agency is approved to fill." t:dataTypeName=number

entity e:a9md-ynri l:"Civil Service List Certification" t:attribution="Department of Citywide Administrative Services (DCAS)" t:url=https://data.cityofnewyork.us/api/views/a9md-ynri

property e:a9md-ynri t:meta.view v:id=a9md-ynri v:category="City Government" v:averageRating=0 v:name="Civil Service List Certification" v:attribution="Department of Citywide Administrative Services (DCAS)"

property e:a9md-ynri t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:a9md-ynri t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| exam_no | list_no | first_name    | mi | last_name | list_agency_code | list_agency_desc        | list_title_desc            | cert_seq_no | request_date        | salary   | cert_issue_no | cert_date           | reissue_date | cert_expiration_date | no_certified | no_requested | provisional_replacement | no_vacancies | list_title_code | sel_cert_description | 
| ======= | ======= | ============= | == | ========= | ================ | ======================= | ========================== | =========== | =================== | ======== | ============= | =================== | ============ | ==================== | ============ | ============ | ======================= | ============ | =============== | ==================== | 
| 04036   | 43.000  | ELIZABETH     | J  | ELLIS     | 040              | DEPARTMENT OF EDUCATION | MANAGEMENT AUDITOR TRAINEE | 1.000       | 2016-11-15T00:00:00 | 42289.00 | 62697         | 2016-11-17T00:00:00 |              | 2016-12-19T00:00:00  | 18           | 10           | N                       | 1            | 40501           |                      | 
| 04036   | 48.000  | YELENA        |    | KVETNAYA  | 040              | DEPARTMENT OF EDUCATION | MANAGEMENT AUDITOR TRAINEE | 2.000       | 2016-11-15T00:00:00 | 42289.00 | 62697         | 2016-11-17T00:00:00 |              | 2016-12-19T00:00:00  | 18           | 10           | N                       | 1            | 40501           |                      | 
| 04036   | 52.000  | JING          |    | LU-HSIEH  | 040              | DEPARTMENT OF EDUCATION | MANAGEMENT AUDITOR TRAINEE | 3.000       | 2016-11-15T00:00:00 | 42289.00 | 62697         | 2016-11-17T00:00:00 |              | 2016-12-19T00:00:00  | 18           | 10           | N                       | 1            | 40501           |                      | 
| 04036   | 53.000  | YING          |    | CHEN      | 040              | DEPARTMENT OF EDUCATION | MANAGEMENT AUDITOR TRAINEE | 4.000       | 2016-11-15T00:00:00 | 42289.00 | 62697         | 2016-11-17T00:00:00 |              | 2016-12-19T00:00:00  | 18           | 10           | N                       | 1            | 40501           |                      | 
| 04036   | 58.000  | SARAH         |    | REISMAN   | 040              | DEPARTMENT OF EDUCATION | MANAGEMENT AUDITOR TRAINEE | 5.000       | 2016-11-15T00:00:00 | 42289.00 | 62697         | 2016-11-17T00:00:00 |              | 2016-12-19T00:00:00  | 18           | 10           | N                       | 1            | 40501           |                      | 
| 04036   | 89.000  | KARIM         |    | NUGENT    | 040              | DEPARTMENT OF EDUCATION | MANAGEMENT AUDITOR TRAINEE | 6.000       | 2016-11-15T00:00:00 | 42289.00 | 62697         | 2016-11-17T00:00:00 |              | 2016-12-19T00:00:00  | 18           | 10           | N                       | 1            | 40501           |                      | 
| 04036   | 94.000  | THYWILL       | M  | AVI       | 040              | DEPARTMENT OF EDUCATION | MANAGEMENT AUDITOR TRAINEE | 7.000       | 2016-11-15T00:00:00 | 42289.00 | 62697         | 2016-11-17T00:00:00 |              | 2016-12-19T00:00:00  | 18           | 10           | N                       | 1            | 40501           |                      | 
| 04036   | 110.000 | DEVANAND      |    | PERSAUD   | 040              | DEPARTMENT OF EDUCATION | MANAGEMENT AUDITOR TRAINEE | 8.000       | 2016-11-15T00:00:00 | 42289.00 | 62697         | 2016-11-17T00:00:00 |              | 2016-12-19T00:00:00  | 18           | 10           | N                       | 1            | 40501           |                      | 
| 04036   | 112.500 | CATHY PIK SIM |    | YAU       | 040              | DEPARTMENT OF EDUCATION | MANAGEMENT AUDITOR TRAINEE | 9.000       | 2016-11-15T00:00:00 | 42289.00 | 62697         | 2016-11-17T00:00:00 |              | 2016-12-19T00:00:00  | 18           | 10           | N                       | 1            | 40501           |                      | 
| 04036   | 162.500 | MATTHEW       | O  | AIGBE     | 040              | DEPARTMENT OF EDUCATION | MANAGEMENT AUDITOR TRAINEE | 10.000      | 2016-11-15T00:00:00 | 42289.00 | 62697         | 2016-11-17T00:00:00 |              | 2016-12-19T00:00:00  | 18           | 10           | N                       | 1            | 40501           |                      | 
```