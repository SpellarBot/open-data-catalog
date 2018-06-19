# Employee Survey Response Rates

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/employee-survey-response-rates) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/r2yd-k74h) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/r2yd-k74h/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/r2yd-k74h/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | r2yd-k74h |
| Name | Employee Survey Response Rates |
| Attribution | King County Human Resources Division |
| Category | Employees |
| Tags | employee survey |
| Created | 2015-09-17T22:48:05Z |
| Publication Date | 2016-11-16T23:36:40Z |

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| No       | time           | :updated_at       | updated_at        | meta_data | meta_data   |
| Yes      | series tag     | agency_department | Agency/Department | text      | text        |
| Yes      | numeric metric | response_rate     | Response rate:    | percent   | percent     |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:r2yd-k74h d:2016-10-25T04:54:59.000Z t:agency_department="King County Elections" m:response_rate=92

series e:r2yd-k74h d:2016-10-25T04:55:24.000Z t:agency_department="Department of Assessments" m:response_rate=91

series e:r2yd-k74h d:2016-10-25T04:56:05.000Z t:agency_department=KCIT m:response_rate=73
```

## Meta Commands

```ls
metric m:response_rate p:integer l:"Response rate:" t:dataTypeName=percent

entity e:r2yd-k74h l:"Employee Survey Response Rates" t:attribution="King County Human Resources Division" t:url=https://data.kingcounty.gov/api/views/r2yd-k74h

property e:r2yd-k74h t:meta.view v:id=r2yd-k74h v:category=Employees v:attributionLink=http://www.kingcounty.gov/employees v:averageRating=0 v:name="Employee Survey Response Rates" v:attribution="King County Human Resources Division"

property e:r2yd-k74h t:meta.view.license v:name="Public Domain"

property e:r2yd-k74h t:meta.view.owner v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:displayName="King County Webteam"

property e:r2yd-k74h t:meta.view.tableauthor v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:roleName=administrator v:displayName="King County Webteam"
```

## Top Records

```ls
| :updated_at | agency_department                                 | response_rate | 
| =========== | ================================================= | ============= | 
| 1477371299  | King County Elections                             | 92            | 
| 1477371324  | Department of Assessments                         | 91            | 
| 1477371365  | KCIT                                              | 73            | 
| 1477371373  | Department of Community and Human Services        | 83            | 
| 1477371400  | Department of Permitting and Environmental Review | 66            | 
| 1477371411  | Department of Judicial Administration             | 72            | 
| 1477371441  | Executive Office                                  | 88            | 
| 1477371476  | Public Defense                                    | 54            | 
| 1477371487  | Department of Transportation                      | 63            | 
| 1477371508  | Prosecuting Attorney's Office (Civil Division)    | 58            | 
```