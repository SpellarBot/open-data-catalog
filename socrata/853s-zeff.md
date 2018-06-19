# City of Austin Employee Detail Information

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/city-of-austin-employee-detail-information) |
| Metadata | [Link](https://data.austintexas.gov/api/views/853s-zeff) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/853s-zeff/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/853s-zeff/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | 853s-zeff |
| Name | City of Austin Employee Detail Information |
| Attribution | City of Austin - Human Resources Department |
| Category | Business |
| Tags | employee detail, jobs, title, hourly rate, annual salary |
| Created | 2015-08-25T21:42:31Z |
| Publication Date | 2015-08-28T15:58:32Z |

## Description

City of Austin Employee Detail Information for FY2015 PN19

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type     | Render Type   |
| ======== | ============== | ======================== | ======================== | ============= | ============= |
| No       | time           | :updated_at              | updated_at               | meta_data     | meta_data     |
| Yes      | series tag     | emp_id                   | Emp ID                   | text          | number        |
| Yes      | series tag     | last                     | Last                     | text          | text          |
| Yes      | series tag     | first                    | First                    | text          | text          |
| No       |                | mi                       | MI                       | text          | text          |
| Yes      | series tag     | department               | Department               | text          | text          |
| Yes      | series tag     | department_name          | Department Name          | text          | text          |
| Yes      | series tag     | division_no              | Division No              | text          | text          |
| Yes      | series tag     | division_title           | Division Title           | text          | text          |
| No       |                | effective_date           | Effective Date           | calendar_date | calendar_date |
| Yes      | numeric metric | length_of_service_w_city | Length of Service w City | number        | number        |
| Yes      | numeric metric | length_of_service_in_job | Length of Service in Job | number        | number        |
| Yes      | series tag     | staffing_level           | Staffing Level           | text          | text          |
| Yes      | series tag     | staffing_level_desc      | Staffing Level Desc      | text          | text          |
| Yes      | series tag     | posn                     | Posn                     | text          | text          |
| Yes      | series tag     | title                    | Title                    | text          | text          |
| Yes      | series tag     | job_status               | Job Status               | text          | text          |
| Yes      | series tag     | employee_status          | Employee Status          | text          | text          |
| Yes      | series tag     | ecls_code                | ECLS Code                | text          | text          |
| Yes      | series tag     | ecls_desc                | ECLS Desc                | text          | text          |
| Yes      | numeric metric | job_fte                  | Job FTE                  | number        | number        |
| Yes      | numeric metric | job_hrs_pay              | Job Hrs/Pay              | number        | number        |
| Yes      | numeric metric | hourly_rate              | Hourly Rate              | money         | money         |
| Yes      | numeric metric | annual_salary            | Annual Salary            | money         | money         |
| Yes      | series tag     | eeo_code                 | EEO Code                 | text          | text          |
| Yes      | series tag     | eeo_desc                 | EEO Desc                 | text          | text          |
| Yes      | numeric metric | age                      | Age                      | number        | number        |
| Yes      | series tag     | ethnicity                | Ethnicity                | text          | text          |
| Yes      | series tag     | ethnicity_code           | Ethnicity Code           | text          | text          |
| Yes      | series tag     | gender                   | Gender                   | text          | text          |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = mi,effective_date
```

## Data Commands

```ls
series e:853s-zeff d:2015-08-25T14:42:39.000Z t:last=Turner t:department=91G t:emp_id=10000003 t:ecls_desc=Standard/Exempt t:job_status=A t:division_title="Womens,Infant,Children (WIC)" t:eeo_desc=Professionals t:employee_status=A t:title="Supv, WIC" t:division_no=91G427 t:staffing_level=02 t:staffing_level_desc=Supervisor t:eeo_code=20 t:ecls_code=02 t:gender=F t:posn=105664 t:ethnicity_code=1 t:department_name="Health & Human Services" t:ethnicity=White t:first=Diane m:annual_salary=62608 m:length_of_service_w_city=15 m:age=50 m:hourly_rate=30.1 m:job_fte=1 m:job_hrs_pay=80 m:length_of_service_in_job=16

series e:853s-zeff d:2015-08-25T14:42:39.000Z t:last=Michael t:department=87G t:emp_id=10000008 t:ecls_desc=Police/Exempt t:job_status=A t:division_title="Police Law Enforcement" t:eeo_desc=Professionals t:employee_status=A t:title="Police Commander" t:division_no=87G010 t:staffing_level=03 t:staffing_level_desc=Manager t:eeo_code=20 t:ecls_code=19 t:gender=M t:posn=102924 t:ethnicity_code=1 t:department_name=Police t:ethnicity=White t:first=Andrew m:annual_salary=146101.28 m:length_of_service_w_city=18 m:age=46 m:hourly_rate=70.24 m:job_fte=1 m:job_hrs_pay=80 m:length_of_service_in_job=2

series e:853s-zeff d:2015-08-25T14:42:39.000Z t:last=Greco t:department=85G t:emp_id=10000015 t:ecls_desc=Standard/Exempt t:job_status=A t:division_title="Lib Information Systems" t:eeo_desc=Professionals t:employee_status=A t:title="IT Supervisor Sr" t:division_no=85G100 t:staffing_level=02 t:staffing_level_desc=Supervisor t:eeo_code=20 t:ecls_code=02 t:gender=M t:posn=108449 t:ethnicity_code=1 t:department_name=Library t:ethnicity=White t:first=James m:annual_salary=96345.6 m:length_of_service_w_city=22 m:age=50 m:hourly_rate=46.32 m:job_fte=1 m:job_hrs_pay=80 m:length_of_service_in_job=17
```

## Meta Commands

```ls
metric m:length_of_service_w_city p:integer l:"Length of Service w City" t:dataTypeName=number

metric m:length_of_service_in_job p:integer l:"Length of Service in Job" t:dataTypeName=number

metric m:job_fte p:double l:"Job FTE" t:dataTypeName=number

metric m:job_hrs_pay p:integer l:"Job Hrs/Pay" t:dataTypeName=number

metric m:hourly_rate p:double l:"Hourly Rate" t:dataTypeName=money

metric m:annual_salary p:double l:"Annual Salary" t:dataTypeName=money

metric m:age p:integer l:Age t:dataTypeName=number

entity e:853s-zeff l:"City of Austin Employee Detail Information" t:attribution="City of Austin - Human Resources Department" t:url=https://data.austintexas.gov/api/views/853s-zeff

property e:853s-zeff t:meta.view v:id=853s-zeff v:category=Business v:attributionLink=https://opendata.bloomfire.com/posts/1013422 v:averageRating=0 v:name="City of Austin Employee Detail Information" v:attribution="City of Austin - Human Resources Department"

property e:853s-zeff t:meta.view.license v:name="Public Domain"

property e:853s-zeff t:meta.view.owner v:id=q57t-cafe v:screenName="Perry Perez" v:displayName="Perry Perez"

property e:853s-zeff t:meta.view.tableauthor v:id=q57t-cafe v:screenName="Perry Perez" v:roleName=editor v:displayName="Perry Perez"
```

## Top Records

```ls
| :updated_at | emp_id   | last            | first   | mi        | department | department_name            | division_no | division_title               | effective_date | length_of_service_w_city | length_of_service_in_job | staffing_level | staffing_level_desc | posn   | title                     | job_status | employee_status | ecls_code | ecls_desc           | job_fte | job_hrs_pay | hourly_rate | annual_salary | eeo_code | eeo_desc      | age | ethnicity | ethnicity_code | gender | 
| =========== | ======== | =============== | ======= | ========= | ========== | ========================== | =========== | ============================ | ============== | ======================== | ======================== | ============== | =================== | ====== | ========================= | ========== | =============== | ========= | =================== | ======= | =========== | =========== | ============= | ======== | ============= | === | ========= | ============== | ====== | 
| 1440513759  | 10000003 | Turner          | Diane   | Dallas    | 91G        | Health & Human Services    | 91G427      | Womens,Infant,Children (WIC) |                | 15                       | 16                       | 02             | Supervisor          | 105664 | Supv, WIC                 | A          | A               | 02        | Standard/Exempt     | 1       | 80          | 30.1        | 62608         | 20       | Professionals | 50  | White     | 1              | F      | 
| 1440513759  | 10000008 | Michael         | Andrew  | Joseph    | 87G        | Police                     | 87G010      | Police Law Enforcement       |                | 18                       | 2                        | 03             | Manager             | 102924 | Police Commander          | A          | A               | 19        | Police/Exempt       | 1       | 80          | 70.24       | 146101.28     | 20       | Professionals | 46  | White     | 1              | M      | 
| 1440513759  | 10000015 | Greco           | James   | B         | 85G        | Library                    | 85G100      | Lib Information Systems      |                | 22                       | 17                       | 02             | Supervisor          | 108449 | IT Supervisor Sr          | A          | A               | 02        | Standard/Exempt     | 1       | 80          | 46.32       | 96345.6       | 20       | Professionals | 50  | White     | 1              | M      | 
| 1440513759  | 10000022 | Wiswell-DeCampo | Sherryl | Ann       | 91G        | Health & Human Services    | 91G100      | HHSD Office of the Director  |                | 26                       | 11                       | 01             | Worker              | 104243 | Administrative Specialist | A          | A               | 01        | Standard/Non-Exempt | 1       | 80          | 21.96       | 45676.8       | 60       | Admin/Supp    | 57  | Hispanic  | 3              | F      | 
| 1440513759  | 10000026 | White           | Gregory | W         | 87G        | Police                     | 87G010      | Police Law Enforcement       |                | 17                       | 3                        | 02             | Supervisor          | 103035 | Police Sergeant           | A          | A               | 03        | Police/Non-Exempt   | 1       | 80          | 52.82       | 109867.68     | 40       | Protect/Svc   | 40  | White     | 1              | M      | 
| 1440513759  | 10000039 | Candoli         | Joanna  | Marie     | 87G        | Police                     | 87G010      | Police Law Enforcement       |                | 21                       | 11                       | 01             | Worker              | 106522 | Police Corporal/Detective | A          | A               | 03        | Police/Non-Exempt   | 1       | 80          | 48.46       | 100800.96     | 40       | Protect/Svc   | 45  | White     | 1              | F      | 
| 1440513759  | 10000066 | Mason           | James   | Alexander | 87G        | Police                     | 87G010      | Police Law Enforcement       |                | 16                       | 2                        | 03             | Manager             | 102943 | Police Lieutenant         | A          | A               | 19        | Police/Exempt       | 1       | 80          | 60.74       | 126349.6      | 40       | Protect/Svc   | 50  | White     | 1              | M      | 
| 1440513759  | 10000084 | Lynch           | Amy     | E         | 87G        | Police                     | 87G010      | Police Law Enforcement       |                | 15                       | 1                        | 01             | Worker              | 103062 | Police Corporal/Detective | A          | A               | 03        | Police/Non-Exempt   | 1       | 80          | 45.29       | 94203.2       | 40       | Protect/Svc   | 41  | White     | 1              | F      | 
| 1440513759  | 10000127 | Wosky           | Glen    | Edward    | 93G        | Emergency Medical Services | 93G040      | Operations                   |                | 18                       | 7                        | 02             | Supervisor          | 105459 | EMS Commander             | A          | A               | 23        | EMS42/Non-Exempt    | 1       | 84          | 43.03       | 93977.52      | 20       | Professionals | 55  | White     | 1              | M      | 
| 1440513759  | 10000132 | Ringuette       | Mark    | Louis     | 87G        | Police                     | 87G010      | Police Law Enforcement       |                | 13                       | 6                        | 01             | Worker              | 110627 | Police Officer            | A          | A               | 03        | Police/Non-Exempt   | 1       | 80          | 36.29       | 75487.36      | 40       | Protect/Svc   | 39  | White     | 1              | M      | 
```