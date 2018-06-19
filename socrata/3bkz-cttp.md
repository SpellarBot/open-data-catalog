# Choose Maryland: Compare States - Education

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/choose-maryland-compare-states-education) |
| Metadata | [Link](https://data.maryland.gov/api/views/3bkz-cttp) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/3bkz-cttp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/3bkz-cttp/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | 3bkz-cttp |
| Name | Choose Maryland: Compare States - Education |
| Attribution | Maryland Department of Commerce |
| Category | Education |
| Tags | maryland, state, compare, expenditures, salary, education, degree, attainment |
| Created | 2013-08-20T14:38:18Z |
| Publication Date | 2017-02-10T17:33:28Z |

## Description

K-12 and higher education - expenditures, institutions, and attainment.

## Columns

```ls
| Included | Schema Type    | Field Name                       | Name                                                        | Data Type | Render Type |
| ======== | ============== | ================================ | =========================================================== | ========= | =========== |
| No       | time           | :updated_at                      | updated_at                                                  | meta_data | meta_data   |
| Yes      | series tag     | state                            | State                                                       | text      | text        |
| Yes      | numeric metric | public_student_teacher_ratio_k12 | Public School Student-Teacher Ratio, K-12                   | number    | number      |
| Yes      | numeric metric | public_pupil_expenditures_k12    | Public School Expenditures Per Pupil, K-12 ($ Dollars)      | money     | money       |
| Yes      | numeric metric | avg_salary_public_teachers_k12   | Average Salary for Public School Teachers, K-12 ($ Dollars) | money     | money       |
| Yes      | numeric metric | high_school_attainment           | High School Attainment (%)                                  | percent   | percent     |
| Yes      | numeric metric | bachelors_degree_attainment      | Bachelor's Degree Attainment (%)                            | percent   | percent     |
| Yes      | numeric metric | graduate_degree_attainment       | Graduate Degree Attainment (%)                              | percent   | percent     |
| Yes      | numeric metric | annual_college_graduates         | Annual College Graduates                                    | number    | number      |
| Yes      | numeric metric | num_2yr_colleges                 | Number of 2-Year Colleges                                   | number    | number      |
| Yes      | numeric metric | num_4yr_colleges_universities    | Number of 4-Year Colleges and Universities                  | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:3bkz-cttp d:2017-02-10T17:33:14.000Z t:state=Alabama m:public_pupil_expenditures_k12=9036 m:num_2yr_colleges=32 m:annual_college_graduates=56451 m:high_school_attainment=84.9 m:graduate_degree_attainment=8.8 m:num_4yr_colleges_universities=45 m:public_student_teacher_ratio_k12=15.8 m:bachelors_degree_attainment=24.2 m:avg_salary_public_teachers_k12=49781

series e:3bkz-cttp d:2017-02-10T17:33:14.000Z t:state=Alaska m:public_pupil_expenditures_k12=18466 m:num_2yr_colleges=3 m:annual_college_graduates=4605 m:high_school_attainment=92.6 m:graduate_degree_attainment=11 m:num_4yr_colleges_universities=6 m:public_student_teacher_ratio_k12=16.6 m:bachelors_degree_attainment=29.7 m:avg_salary_public_teachers_k12=67443

series e:3bkz-cttp d:2017-02-10T17:33:14.000Z t:state=Arizona m:public_pupil_expenditures_k12=7457 m:num_2yr_colleges=36 m:annual_college_graduates=135859 m:high_school_attainment=86.1 m:graduate_degree_attainment=10.3 m:num_4yr_colleges_universities=50 m:public_student_teacher_ratio_k12=22.8 m:bachelors_degree_attainment=27.7 m:avg_salary_public_teachers_k12=45477
```

## Meta Commands

```ls
metric m:public_student_teacher_ratio_k12 p:float l:"Public School Student-Teacher Ratio, K-12" t:dataTypeName=number

metric m:public_pupil_expenditures_k12 p:integer l:"Public School Expenditures Per Pupil, K-12 ($ Dollars)" t:dataTypeName=money

metric m:avg_salary_public_teachers_k12 p:integer l:"Average Salary for Public School Teachers, K-12 ($ Dollars)" t:dataTypeName=money

metric m:high_school_attainment p:float l:"High School Attainment (%)" t:dataTypeName=percent

metric m:bachelors_degree_attainment p:float l:"Bachelor's Degree Attainment (%)" t:dataTypeName=percent

metric m:graduate_degree_attainment p:float l:"Graduate Degree Attainment (%)" t:dataTypeName=percent

metric m:annual_college_graduates p:integer l:"Annual College Graduates" t:dataTypeName=number

metric m:num_2yr_colleges p:integer l:"Number of 2-Year Colleges" t:dataTypeName=number

metric m:num_4yr_colleges_universities p:integer l:"Number of 4-Year Colleges and Universities" t:dataTypeName=number

entity e:3bkz-cttp l:"Choose Maryland:  Compare States - Education" t:attribution="Maryland Department of Commerce" t:url=https://data.maryland.gov/api/views/3bkz-cttp

property e:3bkz-cttp t:meta.view v:id=3bkz-cttp v:category=Education v:attributionLink=http://commerce.maryland.gov v:averageRating=0 v:name="Choose Maryland:  Compare States - Education" v:attribution="Maryland Department of Commerce"

property e:3bkz-cttp t:meta.view.owner v:id=m2gt-bxeg v:screenName="Mike Grandel" v:displayName="Mike Grandel"

property e:3bkz-cttp t:meta.view.tableauthor v:id=m2gt-bxeg v:screenName="Mike Grandel" v:roleName=editor v:displayName="Mike Grandel"
```

## Top Records

```ls
| :updated_at | state       | public_student_teacher_ratio_k12 | public_pupil_expenditures_k12 | avg_salary_public_teachers_k12 | high_school_attainment | bachelors_degree_attainment | graduate_degree_attainment | annual_college_graduates | num_2yr_colleges | num_4yr_colleges_universities | 
| =========== | =========== | ================================ | ============================= | ============================== | ====================== | =========================== | ========================== | ======================== | ================ | ============================= | 
| 1486747994  | Alabama     | 15.8                             | 9036                          | 49781                          | 84.9                   | 24.2                        | 8.8                        | 56451                    | 32               | 45                            | 
| 1486747994  | Alaska      | 16.6                             | 18466                         | 67443                          | 92.6                   | 29.7                        | 11.0                       | 4605                     | 3                | 6                             | 
| 1486747994  | Arizona     | 22.8                             | 7457                          | 45477                          | 86.1                   | 27.7                        | 10.3                       | 135859                   | 36               | 50                            | 
| 1486747994  | Arkansas    | 14.0                             | 9752                          | 48220                          | 85.4                   | 21.8                        | 7.8                        | 30219                    | 27               | 26                            | 
| 1486747994  | California  | 24.3                             | 9671                          | 72842                          | 82.2                   | 32.3                        | 12.0                       | 422060                   | 184              | 264                           | 
| 1486747994  | Colorado    | 17.5                             | 9036                          | 50039                          | 91.2                   | 39.2                        | 14.5                       | 65441                    | 34               | 53                            | 
| 1486747994  | Connecticut | 12.6                             | 18401                         | 72013                          | 90.2                   | 38.3                        | 16.7                       | 40416                    | 12               | 31                            | 
| 1486747994  | Delaware    | 14.0                             | 13793                         | 59085                          | 88.9                   | 30.9                        | 12.9                       | 11814                    | 2                | 7                             | 
| 1486747994  | Florida     | 15.3                             | 8955                          | 49199                          | 87.6                   | 28.4                        | 10.2                       | 236526                   | 69               | 160                           | 
| 1486747994  | Georgia     | 15.8                             | 9236                          | 54190                          | 86.1                   | 29.9                        | 11.3                       | 89225                    | 46               | 84                            | 
```