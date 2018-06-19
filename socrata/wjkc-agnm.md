# FOIA Request Log - Police

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/foia-request-log-police-23a0d) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/wjkc-agnm) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/wjkc-agnm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/wjkc-agnm/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | wjkc-agnm |
| Name | FOIA Request Log - Police |
| Attribution | Chicago Police Department |
| Category | FOIA |
| Created | 2010-04-29T17:50:59Z |
| Publication Date | 2016-01-11T15:51:45Z |

## Description

FOIA requests received by the Chicago Police Department as of May 1, 2010

## Columns

```ls
| Included | Schema Type | Field Name                          | Name                                | Data Type     | Render Type   |
| ======== | =========== | =================================== | =================================== | ============= | ============= |
| Yes      | time        | date_received                       | Date Received                       | calendar_date | calendar_date |
| Yes      | series tag  | request_number                      | Request Number                      | text          | text          |
| Yes      | series tag  | requestor_last_name                 | Requestor Last Name                 | text          | text          |
| Yes      | series tag  | requestor_first_name                | Requestor First Name                | text          | text          |
| Yes      | series tag  | requestor_middle_initial            | Requestor Middle Initial            | text          | text          |
| Yes      | series tag  | institution                         | Institution                         | text          | text          |
| Yes      | series tag  | brief_description_of_records_sought | Brief Description of Records Sought | text          | text          |
| No       |             | date_due                            | Date Due                            | calendar_date | calendar_date |
```

## Time Field

```ls
Value = date_received
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = date_due
```

## Data Commands

```ls
series e:wjkc-agnm d:2010-05-03T00:00:00.000Z t:brief_description_of_records_sought="Police report" t:request_number=10-1223 t:requestor_first_name=Thomas t:requestor_last_name=Callahan m:row_number.wjkc-agnm=1

series e:wjkc-agnm d:2010-05-03T00:00:00.000Z t:requestor_middle_initial=C t:brief_description_of_records_sought="Police report" t:request_number=10-1231 t:requestor_first_name=Larrisha t:requestor_last_name=Hunter m:row_number.wjkc-agnm=2

series e:wjkc-agnm d:2010-05-03T00:00:00.000Z t:requestor_middle_initial=J t:brief_description_of_records_sought="Arrest reports" t:request_number=10-1230 t:requestor_first_name=Rosario t:requestor_last_name=Perez m:row_number.wjkc-agnm=3
```

## Meta Commands

```ls
metric m:row_number.wjkc-agnm p:long l:"Row Number"

entity e:wjkc-agnm l:"FOIA Request Log - Police" t:attribution="Chicago Police Department" t:url=https://data.cityofchicago.org/api/views/wjkc-agnm

property e:wjkc-agnm t:meta.view v:id=wjkc-agnm v:category=FOIA v:attributionLink=https://portal.chicagopolice.org/portal/page/portal/ClearPath v:averageRating=0 v:name="FOIA Request Log - Police" v:attribution="Chicago Police Department"

property e:wjkc-agnm t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:wjkc-agnm t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| date_received       | request_number | requestor_last_name | requestor_first_name | requestor_middle_initial | institution                      | brief_description_of_records_sought        | date_due            | 
| =================== | ============== | =================== | ==================== | ======================== | ================================ | ========================================== | =================== | 
| 2010-05-03T00:00:00 | 10-1223        | Callahan            | Thomas               |                          |                                  | Police report                              | 2010-05-10T00:00:00 | 
| 2010-05-03T00:00:00 | 10-1231        | Hunter              | Larrisha             | C                        |                                  | Police report                              | 2010-05-10T00:00:00 | 
| 2010-05-03T00:00:00 | 10-1230        | Perez               | Rosario              | J                        |                                  | Arrest reports                             | 2010-05-10T00:00:00 | 
| 2010-05-03T00:00:00 | 10-1229        | James               | Tamara               |                          | Mitigation & Sentencing Services | Records on witnesses, victims and offender | 2010-05-10T00:00:00 | 
| 2010-05-03T00:00:00 | 10-1228        | Aitken              | Amanda               |                          | Stephan Zouras LLP               | Police report                              | 2010-05-10T00:00:00 | 
| 2010-05-03T00:00:00 | 10-1227        | Ivy                 | Patricia             | A                        |                                  | Event report                               | 2010-05-10T00:00:00 | 
| 2010-05-03T00:00:00 | 10-1226        | Dawson              | Doris                | J                        |                                  | Arrest report                              | 2010-05-10T00:00:00 | 
| 2010-05-03T00:00:00 | 10-1224        | Powell              | Fred                 | L                        |                                  | Arrest reports                             | 2010-05-10T00:00:00 | 
| 2010-05-03T00:00:00 | 10-1222        | Johnson             | Darren               |                          | 2009-1218096                     | Blue Light camera                          | 2010-05-10T00:00:00 | 
| 2010-05-03T00:00:00 | 10-1221        | Cruz                | Michael              |                          | 2010-0407127                     | Police report, arrest report               | 2010-05-10T00:00:00 | 
```