# General Fund Revenue

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/general-fund-revenue) |
| Metadata | [Link](https://data.lacity.org/api/views/qrkr-kfbh) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/qrkr-kfbh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/qrkr-kfbh/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | qrkr-kfbh |
| Name | General Fund Revenue |
| Category | A Prosperous City |
| Tags | budget, revenue |
| Created | 2016-07-11T14:10:40Z |
| Publication Date | 2017-05-19T01:00:36Z |

## Description

Revenue towards the City's general fund by department, program, and account.

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| No       | time           | :updated_at     | updated_at      | meta_data | meta_data   |
| Yes      | series tag     | dept_code       | Dept Code       | text      | text        |
| Yes      | series tag     | department_name | Department Name | text      | text        |
| Yes      | series tag     | program_code    | Program Code    | text      | text        |
| Yes      | series tag     | program_name    | Program Name    | text      | text        |
| Yes      | series tag     | fund_code       | Fund Code       | text      | text        |
| Yes      | series tag     | fund_name       | Fund Name       | text      | text        |
| Yes      | series tag     | account_code    | Account Code    | text      | text        |
| Yes      | series tag     | account_name    | Account Name    | text      | text        |
| Yes      | series tag     | fiscal_year     | Fiscal Year     | text      | text        |
| Yes      | numeric metric | revenue         | Revenue Amount  | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:qrkr-kfbh d:2017-05-08T16:45:36.000Z t:fiscal_year="2016-17 Adopted Budget" t:fund_name="General Fund" t:fund_code=100 t:program_code=7001 t:program_name="Field Forces" t:dept_code=70 t:account_code=4595 t:department_name=Police t:account_name="Service To Airports" m:revenue=10374958

series e:qrkr-kfbh d:2017-05-08T16:45:36.000Z t:fiscal_year="2014-15 Actuals" t:fund_name="General Fund" t:fund_code=100 t:program_code=4601 t:program_name="Office of the Mayor" t:dept_code=46 t:account_code=4595 t:department_name=Mayor t:account_name="Service To Airports" m:revenue=238611

series e:qrkr-kfbh d:2017-05-08T16:45:36.000Z t:fiscal_year="2017-18 Proposed" t:fund_name="General Fund" t:fund_code=100 t:program_code=3806 t:program_name="Fire Prevention" t:dept_code=38 t:account_code=4117 t:department_name=Fire t:account_name="MISCELLANEOUS-FIRE SERVICE" m:revenue=630000
```

## Meta Commands

```ls
metric m:revenue p:integer l:"Revenue Amount" t:dataTypeName=number

entity e:qrkr-kfbh l:"General Fund Revenue" t:url=https://data.lacity.org/api/views/qrkr-kfbh

property e:qrkr-kfbh t:meta.view d:2017-06-09T14:01:06.646Z v:id=qrkr-kfbh v:category="A Prosperous City" v:averageRating=0 v:name="General Fund Revenue"

property e:qrkr-kfbh t:meta.view.license d:2017-06-09T14:01:06.646Z v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:qrkr-kfbh t:meta.view.owner d:2017-06-09T14:01:06.646Z v:id=95pg-i79k v:profileImageUrlMedium=/api/users/95pg-i79k/profile_images/THUMB v:profileImageUrlLarge=/api/users/95pg-i79k/profile_images/LARGE v:screenName=ChelseaU v:profileImageUrlSmall=/api/users/95pg-i79k/profile_images/TINY v:lastNotificationSeenAt=1493740468 v:displayName=ChelseaU

property e:qrkr-kfbh t:meta.view.tableauthor d:2017-06-09T14:01:06.646Z v:id=95pg-i79k v:profileImageUrlMedium=/api/users/95pg-i79k/profile_images/THUMB v:profileImageUrlLarge=/api/users/95pg-i79k/profile_images/LARGE v:screenName=ChelseaU v:profileImageUrlSmall=/api/users/95pg-i79k/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1493740468 v:displayName=ChelseaU
```

## Top Records

```ls
| :updated_at | dept_code | department_name                  | program_code | program_name                               | fund_code | fund_name    | account_code | account_name                   | fiscal_year            | revenue  | 
| =========== | ========= | ================================ | ============ | ========================================== | ========= | ============ | ============ | ============================== | ====================== | ======== | 
| 1494261936  | 70        | Police                           | 7001         | Field Forces                               | 100       | General Fund | 4595         | Service To Airports            | 2016-17 Adopted Budget | 10374958 | 
| 1494261936  | 46        | Mayor                            | 4601         | Office of the Mayor                        | 100       | General Fund | 4595         | Service To Airports            | 2014-15 Actuals        | 238611   | 
| 1494261936  | 38        | Fire                             | 3806         | Fire Prevention                            | 100       | General Fund | 4117         | MISCELLANEOUS-FIRE SERVICE     | 2017-18 Proposed       | 630000   | 
| 1494261936  | 94        | Transportation                   | 9408         | District Offices                           | 100       | General Fund | 3242         | B Permits                      | 2016-17 Adopted Budget | 2100000  | 
| 1494261937  | 78        | Bureau of Engineering            | 7805         | Mobility                                   | 100       | General Fund | 4345         | COPIES OF MAP                  | 2017-18 Proposed       | 0        | 
| 1494261937  | 70        | Police                           | 7001         | Field Forces                               | 100       | General Fund | 4595         | Service To Airports            | 2015-16 Estimates      | 8977484  | 
| 1494261937  | 70        | Police                           | 7001         | Field Forces                               | 100       | General Fund | 4662         | IMPOUND FEE                    | 2017-18 Proposed       | 10750000 | 
| 1494261936  | 6         | Animal Services                  | 601          | Animal Control and Law Enforcement         | 100       | General Fund | 3209         | Comm & Ind Guard Dog Licenses  | 2015-16 Adopted Budget | 8000     | 
| 1494261936  | 43        | Housing and Community Investment | 4304         | Strategic Planning and Policy Development  | 100       | General Fund | 5341         | Home Invest Prtnrship Rel Cost | 2015-16 Adopted Budget | 141951   | 
| 1494261936  | OTHERSPF  | Other Special Purpose Funds      | 6299         | Non-Departmental General - Default Program | 100       | General Fund | 5613         | Interfd Oper Trans-Reserve     | 2015-16 Estimates      | 60312889 | 
```