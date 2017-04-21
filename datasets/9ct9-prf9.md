# AP Results

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ap-results-b65bc) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/9ct9-prf9) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/9ct9-prf9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/9ct9-prf9/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 9ct9-prf9 |
| Name | AP Results |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | ap result, nyc, lifelong learning |
| Created | 2013-02-20T22:01:14Z |
| Publication Date | 2013-02-20T22:01:26Z |

## Description

The most recent school level results for New York City on AP exams. Results are available at the school level for the 2012 school year. Records contain AP Test Taking and Passing Rates.

## Columns

```ls
| Included | Schema Type | Field Name                  | Name                        | Data Type | Render Type |
| ======== | =========== | =========================== | =========================== | ========= | =========== |
| No       | time        | :updated_at                 | updated_at                  | meta_data | meta_data   |
| Yes      | series tag  | dbn                         | DBN                         | text      | text        |
| Yes      | series tag  | school_name                 | SCHOOL NAME                 | text      | text        |
| Yes      | series tag  | num_of_ap_test_takers       | Num of AP Test Takers       | text      | text        |
| Yes      | series tag  | num_of_ap_total_exams_taken | Num of AP Total Exams Taken | text      | text        |
| Yes      | series tag  | num_of_ap_exams_passed      | Num of AP Exams Passed      | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:9ct9-prf9 d:2013-02-20T14:01:21.000Z t:school_name="HENRY STREET SCHOOL FOR INTERNATIONAL STUDIES" t:dbn=01M292 t:num_of_ap_total_exams_taken=s t:num_of_ap_test_takers=s t:num_of_ap_exams_passed=s m:row_number.9ct9-prf9=1

series e:9ct9-prf9 d:2013-02-20T14:01:21.000Z t:school_name="UNIVERSITY NEIGHBORHOOD HIGH SCHOOL" t:dbn=01M448 t:num_of_ap_total_exams_taken=53 t:num_of_ap_test_takers=37 t:num_of_ap_exams_passed=21 m:row_number.9ct9-prf9=2

series e:9ct9-prf9 d:2013-02-20T14:01:21.000Z t:school_name="EAST SIDE COMMUNITY SCHOOL" t:dbn=01M450 t:num_of_ap_total_exams_taken=12 t:num_of_ap_test_takers=12 t:num_of_ap_exams_passed=s m:row_number.9ct9-prf9=3
```

## Meta Commands

```ls
metric m:row_number.9ct9-prf9 p:long l:"Row Number"

entity e:9ct9-prf9 l:"AP Results" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/9ct9-prf9

property e:9ct9-prf9 t:meta.view v:id=9ct9-prf9 v:category=Education v:attributionLink=http://schools.nyc.gov/NR/rdonlyres/28BA85DD-81FD-4B1C-8900-94CE57BD69AD/0/2012APPUBLIC.xlsx v:averageRating=0 v:name="AP Results" v:attribution="Department of Education (DOE)"

property e:9ct9-prf9 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:9ct9-prf9 t:meta.view.tableauthor v:id=ya7g-926w v:screenName="Aakash Dalwani" v:displayName="Aakash Dalwani"
```

## Top Records

```ls
| :updated_at | dbn    | school_name                                                    | num_of_ap_test_takers | num_of_ap_total_exams_taken | num_of_ap_exams_passed | 
| =========== | ====== | ============================================================== | ===================== | =========================== | ====================== | 
| 1361368881  | 01M292 | HENRY STREET SCHOOL FOR INTERNATIONAL STUDIES                  | s                     | s                           | s                      | 
| 1361368881  | 01M448 | UNIVERSITY NEIGHBORHOOD HIGH SCHOOL                            | 37                    | 53                          | 21                     | 
| 1361368881  | 01M450 | EAST SIDE COMMUNITY SCHOOL                                     | 12                    | 12                          | s                      | 
| 1361368881  | 01M458 | FORSYTH SATELLITE ACADEMY                                      | s                     | s                           | s                      | 
| 1361368881  | 01M509 | MARTA VALLE HIGH SCHOOL                                        | 14                    | 15                          | s                      | 
| 1361368881  | 01M515 | LOWER EAST SIDE PREPARATORY HIGH SCHOOL                        | 50                    | 60                          | 54                     | 
| 1361368881  | 01M539 | NEW EXPLORATIONS INTO SCIENCE, TECHNOLOGY AND MATH HIGH SCHOOL | 306                   | 587                         | 323                    | 
| 1361368881  | 01M650 | CASCADES HIGH SCHOOL                                           | s                     | s                           | s                      | 
| 1361368881  | 01M696 | BARD HIGH SCHOOL EARLY COLLEGE                                 | s                     | s                           | s                      | 
| 1361368881  | 02M047 | 47 THE AMERICAN SIGN LANGUAGE AND ENGLISH SECONDARY SCHOOL     | s                     | s                           | s                      | 
```