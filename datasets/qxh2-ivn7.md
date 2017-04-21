# Budget 2012- General Fund By Service

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/budget-2012-general-fund-by-service-f943d) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/qxh2-ivn7) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/qxh2-ivn7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/qxh2-ivn7/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | qxh2-ivn7 |
| Name | Budget 2012- General Fund By Service |
| Attribution | King County |
| Category | Budget |
| Tags | budget |
| Created | 2011-09-26T03:47:07Z |
| Publication Date | 2011-09-26T03:48:13Z |

## Description

2012 Proposed budget general fund broken out by service. More at http://www.kingcounty.gov/budget

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| Yes      | series tag     | agency           | Agency           | text      | text        |
| Yes      | numeric metric | amount           | Amount           | money     | money       |
| Yes      | series tag     | service_breakout | Service breakout | html      | html        |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:qxh2-ivn7 d:2012-01-01T00:00:00.000Z t:service_breakout="<p>County Council = $1,587,015</p><p>
Council Administration = $12,450,980</p><p>
Hearing Examiner = $549,243</p><p>
County Auditor = $1,639,308</p><p>
Ombudsman/Tax Advisor = $1,133,492</p><p>
King County Civic Television = $577,574</p><p>
Board of Appeals = $709,278</p><p>
Office of Law Enforcement Oversight = $354,531</p>" t:agency=Council m:amount=19001421

series e:qxh2-ivn7 d:2012-01-01T00:00:00.000Z t:service_breakout="<p>County Executive = $243,932</p><p>
Office of the County Executive = $4,257,373</p>" t:agency=Executive m:amount=4501305

series e:qxh2-ivn7 d:2012-01-01T00:00:00.000Z t:service_breakout="Office of Performance, Strategy and Budget" t:agency="Performance, Strategy and Budget" m:amount=7104511
```

## Meta Commands

```ls
metric m:amount p:integer l:Amount t:dataTypeName=money

entity e:qxh2-ivn7 l:"Budget 2012- General Fund By Service" t:attribution="King County" t:url=https://data.kingcounty.gov/api/views/qxh2-ivn7

property e:qxh2-ivn7 t:meta.view v:id=qxh2-ivn7 v:category=Budget v:attributionLink=http://www.kingcounty.gov/exec/psb/budget v:averageRating=0 v:name="Budget 2012- General Fund By Service" v:attribution="King County"

property e:qxh2-ivn7 t:meta.view.license v:name="Public Domain"

property e:qxh2-ivn7 t:meta.view.owner v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:displayName="King County Webteam"

property e:qxh2-ivn7 t:meta.view.tableauthor v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:roleName=administrator v:displayName="King County Webteam"
```

## Top Records

```ls
| agency                           | amount    | service_breakout                                                                                                                                                                                                                                                               | 
| ================================ | ========= | ============================================================================================================================================================================================================================================================================== | 
| Council                          | 19001421  | County Council = $1,587,015
Council Administration = $12,450,980
Hearing Examiner = $549,243
County Auditor = $1,639,308
Ombudsman/Tax Advisor = $1,133,492
King County Civic Television = $577,574
Board of Appeals = $709,278
Office of Law Enforcement Oversight = $354,531 | 
| Executive                        | 4501305   | County Executive = $243,932
Office of the County Executive = $4,257,373                                                                                                                                                                                                        | 
| Performance, Strategy and Budget | 7104511   | Office of Performance, Strategy and Budget                                                                                                                                                                                                                                     | 
| Labor Relations                  | 2260772   | Office of Labor Relations                                                                                                                                                                                                                                                      | 
| Sheriff                          | 144961179 | Sheriff = $143,823,142
Drug Enforcement Forfeits = $1,138,037                                                                                                                                                                                                                  | 
| Prosecuting Attorney Office      | 58838040  | Prosecuting Attorney = $58,718,143
Prosecuting Attorney Antiprofiteering = $119,897                                                                                                                                                                                            | 
| District Court                   | 27451186  | District Court                                                                                                                                                                                                                                                                 | 
| Superior Court                   | 44528459  | Superior Court                                                                                                                                                                                                                                                                 | 
| Judicial Administration          | 19061595  | Judicial Administration                                                                                                                                                                                                                                                        | 
| Assessor                         | 21778926  | Assessments                                                                                                                                                                                                                                                                    | 
```