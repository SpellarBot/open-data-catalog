# City-Parish Employees

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/city-parish-employees) |
| Metadata | [Link](https://data.brla.gov/api/views/gyhq-w3h3) |
| Data: JSON | [100 Rows](https://data.brla.gov/api/views/gyhq-w3h3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.brla.gov/api/views/gyhq-w3h3/rows.csv?max_rows=100) |
| Host | data.brla.gov |
| Id | gyhq-w3h3 |
| Name | City-Parish Employees |
| Attribution | Human Resources |
| Category | Government |
| Tags | employees, salary, job title |
| Created | 2014-12-07T00:58:20Z |
| Publication Date | 2015-07-14T14:51:33Z |

## Description

City-Parish employees, both active and inactive, that exist in the City-Parish Payroll System.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name                 | Data Type     | Render Type   |
| ======== | ============== | ================ | ==================== | ============= | ============= |
| Yes      | series tag     | employee_num     | EMPLOYEE NUM         | html          | html          |
| Yes      | series tag     | last_name        | LAST NAME            | text          | text          |
| Yes      | series tag     | first_name       | FIRST NAME           | text          | text          |
| Yes      | series tag     | middle_initial   | MIDDLE INITIAL       | text          | text          |
| Yes      | series tag     | department_num   | DEPARTMENT NUM       | text          | html          |
| Yes      | series tag     | department_name  | DEPARTMENT NAME      | text          | text          |
| Yes      | series tag     | division_num     | DIVISION NUM         | html          | html          |
| Yes      | series tag     | division_name    | DIVISION NAME        | text          | text          |
| Yes      | series tag     | job_code         | JOB CODE             | text          | html          |
| Yes      | series tag     | job_code_descr   | JOB TITLE            | text          | text          |
| Yes      | series tag     | pay_range        | PAY RANGE            | html          | html          |
| Yes      | numeric metric | pay_step         | PAY STEP             | number        | number        |
| Yes      | series tag     | sex              | SEX                  | text          | text          |
| Yes      | series tag     | race             | RACE                 | text          | text          |
| Yes      | time           | hire_date        | CURRENT HIRE DATE    | calendar_date | calendar_date |
| No       |                | term_date        | EMPLOYMENT END DATE  | calendar_date | calendar_date |
| Yes      | numeric metric | years_service    | YEARS SERVICE        | number        | number        |
| Yes      | numeric metric | scheduled_hours  | SCHEDULED HOURS      | number        | number        |
| No       |                | long_percent     | LONGEVITY PERCENTAGE | number        | number        |
| Yes      | numeric metric | hourly_rate      | HOURLY RATE          | number        | number        |
| Yes      | numeric metric | xtr_tot_hr_rate  | TOTAL HOURLY RATE    | number        | number        |
| Yes      | numeric metric | xtr_ot_hr_rate   | OVERTIME HOURLY RATE | number        | number        |
| Yes      | numeric metric | pm_annual_salary | ANNUAL SALARY        | money         | money         |
| Yes      | series tag     | pm_status        | EMPLOYMENT STATUS    | text          | number        |
```

## Time Field

```ls
Value = hire_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = term_date,long_percent
```

## Data Commands

```ls
series e:gyhq-w3h3 d:2017-04-10T00:00:00.000Z t:sex=F t:middle_initial=K t:job_code_descr="PROGRAM PARTICIPANT" t:division_name="WIA YOUTH PROGRAM" t:race=B t:pm_status=0 t:department_num=60 t:first_name=TIANNA t:pay_range=9999 t:job_code=801005 t:employee_num=469394 t:last_name=JOSHUA t:division_num=6055026 t:department_name="HUMAN DEVELOPMENT AND SERVICES" m:hourly_rate=10 m:years_service=0 m:xtr_ot_hr_rate=15 m:xtr_tot_hr_rate=10 m:scheduled_hours=0 m:pm_annual_salary=0 m:pay_step=1

series e:gyhq-w3h3 d:2017-02-20T00:00:00.000Z t:sex=M t:middle_initial=C t:job_code_descr=LABORER t:division_name="MAINTENANCE-LANDSCAPE MAINT" t:race=B t:pm_status=5 t:department_num=77 t:first_name=JAMES t:pay_range=1040 t:job_code=160105 t:employee_num=307300 t:last_name=VEALS t:division_num=7702002 t:department_name="DEPT OF MAINTENANCE" m:hourly_rate=9.3034 m:years_service=0 m:xtr_ot_hr_rate=13.9551 m:xtr_tot_hr_rate=9.3034 m:scheduled_hours=80 m:pm_annual_salary=19351.02 m:pay_step=5

series e:gyhq-w3h3 d:2016-09-22T00:00:00.000Z t:sex=F t:middle_initial=M t:job_code_descr="SUBSTITUTE TEACHER AIDE" t:division_name=HEADSTART t:race=B t:pm_status=5 t:department_num=60 t:first_name=ERNESTINE t:pay_range=1050 t:job_code=105360 t:employee_num=102261 t:last_name=GEORGE t:division_num=6021066 t:department_name="HUMAN DEVELOPMENT AND SERVICES" m:hourly_rate=9.4794 m:years_service=0 m:xtr_ot_hr_rate=14.2191 m:xtr_tot_hr_rate=9.4794 m:scheduled_hours=0 m:pm_annual_salary=19717.1 m:pay_step=4
```

## Meta Commands

```ls
metric m:pay_step p:integer l:"PAY STEP" t:dataTypeName=number

metric m:years_service p:integer l:"YEARS SERVICE" d:"Years of service with City-Parish based on current hire date" t:dataTypeName=number

metric m:scheduled_hours p:float l:"SCHEDULED HOURS" d:"Scheduled hours per pay period" t:dataTypeName=number

metric m:hourly_rate p:float l:"HOURLY RATE" t:dataTypeName=number

metric m:xtr_tot_hr_rate p:float l:"TOTAL HOURLY RATE" d:"Base hourly rate plus any additional earnings" t:dataTypeName=number

metric m:xtr_ot_hr_rate p:float l:"OVERTIME HOURLY RATE" d:"Total hourly rate times 1.5" t:dataTypeName=number

metric m:pm_annual_salary p:double l:"ANNUAL SALARY" d:"Annual salary based on paygrade and step, does not include any additional earnings" t:dataTypeName=money

entity e:gyhq-w3h3 l:"City-Parish Employees" t:attribution="Human Resources" t:url=https://data.brla.gov/api/views/gyhq-w3h3

property e:gyhq-w3h3 t:meta.view v:id=gyhq-w3h3 v:category=Government v:attributionLink=http://brgov.com/dept/hr v:averageRating=0 v:name="City-Parish Employees" v:attribution="Human Resources"

property e:gyhq-w3h3 t:meta.view.license v:name="Public Domain"

property e:gyhq-w3h3 t:meta.view.owner v:id=mjn2-v86v v:profileImageUrlMedium=/api/users/mjn2-v86v/profile_images/THUMB v:profileImageUrlLarge=/api/users/mjn2-v86v/profile_images/LARGE v:screenName="Open Data BR" v:profileImageUrlSmall=/api/users/mjn2-v86v/profile_images/TINY v:displayName="Open Data BR"

property e:gyhq-w3h3 t:meta.view.tableauthor v:id=mjn2-v86v v:profileImageUrlMedium=/api/users/mjn2-v86v/profile_images/THUMB v:profileImageUrlLarge=/api/users/mjn2-v86v/profile_images/LARGE v:screenName="Open Data BR" v:profileImageUrlSmall=/api/users/mjn2-v86v/profile_images/TINY v:roleName=viewer v:displayName="Open Data BR"
```

## Top Records

```ls
| employee_num | last_name    | first_name | middle_initial | department_num | department_name                             | division_num | division_name                           | job_code | job_code_descr           | pay_range | pay_step | sex | race | hire_date           | term_date           | years_service | scheduled_hours | long_percent | hourly_rate | xtr_tot_hr_rate | xtr_ot_hr_rate | pm_annual_salary | pm_status | 
| ============ | ============ | ========== | ============== | ============== | =========================================== | ============ | ======================================= | ======== | ======================== | ========= | ======== | === | ==== | =================== | =================== | ============= | =============== | ============ | =========== | =============== | ============== | ================ | ========= | 
| 469394       | JOSHUA       | TIANNA     | K              | 60             | HUMAN DEVELOPMENT AND SERVICES              | 6055026      | WIA YOUTH PROGRAM                       | 801005   | PROGRAM PARTICIPANT      | 9999      | 1        | F   | B    | 2017-04-10T00:00:00 |                     | 0             | 0               | 0            | 10          | 10              | 15             | 0                | 0         | 
| 307300       | VEALS        | JAMES      | C              | 77             | DEPT OF MAINTENANCE                         | 7702002      | MAINTENANCE-LANDSCAPE MAINT             | 160105   | LABORER                  | 1040      | 5        | M   | B    | 2017-02-20T00:00:00 | 2017-02-21T00:00:00 | 0             | 80              | 0            | 9.3034      | 9.3034          | 13.9551        | 19351.02         | 5         | 
| 102261       | GEORGE       | ERNESTINE  | M              | 60             | HUMAN DEVELOPMENT AND SERVICES              | 6021066      | HEADSTART                               | 105360   | SUBSTITUTE TEACHER AIDE  | 1050      | 4        | F   | B    | 2016-09-22T00:00:00 | 2017-03-17T00:00:00 | 0             | 0               | 0            | 9.4794      | 9.4794          | 14.2191        | 19717.1          | 5         | 
| 392413       | NELSON DRUEL | ADRICA     | M              | 41             | FINANCE DEPARTMENT                          | 4120000      | FINANCE DEPARTMENT-ACCOUNTING           | 111130   | SENIOR FISCAL SPECIALIST | 1110      | 16       | F   | B    | 2012-08-20T00:00:00 |                     | 4             | 80              | 0            | 18.0058     | 18.0058         | 27.0087        | 37451.96         | 0         | 
| 498084       | ROBERTSON    | JASON      | R              | 50             | POLICE DEPARTMENT                           | 5050001      | POLICE DEPARTMENT-OPERATION SERV BUREAU | 5005     | POLICE OFFICER           | 3090      | 6        | M   | B    | 2017-04-03T00:00:00 |                     | 0             | 80              | 0            | 17.8448     | 18.8064         | 28.2096        | 37117.08         | 0         | 
| 494640       | ROGERS JR    | JOENATHAN  |                | 77             | DEPT OF MAINTENANCE                         | 7702002      | MAINTENANCE-LANDSCAPE MAINT             | 160105   | LABORER                  | 1040      | 5        | M   | B    | 2017-02-06T00:00:00 | 2017-02-24T00:00:00 | 0             | 80              | 0            | 9.3034      | 9.3034          | 13.9551        | 19351.02         | 5         | 
| 390127       | TAYLOR JR    | ERROL      | T              | 51             | FIRE DEPARTMENT                             | 5120011      | FIRE INVESTIGATIONS                     | 170155   | ASSIST CHIEF FIRE INVEST | 7060      | 21       | M   | B    | 1990-01-16T00:00:00 |                     | 27            | 80              | 0            | 41.1924     | 41.1924         | 66.1155        | 85680.14         | 0         | 
| 528790       | COLEMAN      | SHAWANDA   | M              | 76             | DEPT OF BUSINESS OPERATIONS AND CAPITAL PRO | 7601000      | BUSINESS OPS & CAPITAL - ADMINISTR.     | 100090   | ACCOUNTING ASSOCIATE I   | 1150      | 1        | F   | B    | 2016-12-06T00:00:00 | 2017-02-28T00:00:00 | 0             | 80              | 0            | 14.0476     | 14.0476         | 21.0714        | 29219.06         | 5         | 
| 478970       | HOWARD       | DENISE     |                | 78             | DEPT OF BUILDINGS AND GROUNDS               | 7803000      | BLDGS & GROUNDS-PUBLIC BLDG MAINT       | 160105   | LABORER                  | 1040      | 5        | F   | B    | 2016-06-14T00:00:00 | 2017-01-24T00:00:00 | 0             | 80              | 0            | 9.3034      | 9.3034          | 13.9551        | 19351.02         | 5         | 
| 527726       | JUMONVILLE   | BRANDON    | J              | 44             | INFORMATION SERVICES                        | 4400000      | INFORMATION SERVICES                    | 102710   | SENIOR GIS ANALYST       | 2220      | 2        | M   | W    | 2016-10-05T00:00:00 |                     | 0             | 80              | 0            | 20.3597     | 20.3597         | 30.5396        | 42348.28         | 0         | 
```