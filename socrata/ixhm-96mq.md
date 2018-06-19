# State of Iowa Employee Counts by Month and Agency

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-of-iowa-employee-demographics-by-month-and-agency) |
| Metadata | [Link](https://data.iowa.gov/api/views/ixhm-96mq) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/ixhm-96mq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/ixhm-96mq/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | ixhm-96mq |
| Name | State of Iowa Employee Counts by Month and Agency |
| Attribution | Iowa Department of Administrative Services, Human Resource Enterprise, Human Resource Data Warehouse |
| Category | Government |
| Tags | state employees, gender |
| Created | 2014-11-10T19:46:54Z |
| Publication Date | 2017-04-18T14:47:48Z |

## Description

This dataset provides monthly counts of full-time, part-time and temporary employees for the State of Iowa.  Data is captured for the last pay period ending in a month, starting with pay period ending December 23, 2010.

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type     | Render Type   |
| ======== | ============== | =================== | =================== | ============= | ============= |
| Yes      | series tag     | function            | Function            | text          | text          |
| Yes      | series tag     | special_department  | Special Department  | text          | text          |
| Yes      | series tag     | department_number   | Department Number   | text          | text          |
| Yes      | series tag     | department          | Department          | text          | text          |
| Yes      | time           | count_date          | Count Date          | calendar_date | calendar_date |
| Yes      | numeric metric | full_time_employees | Full-Time Employees | number        | number        |
| Yes      | numeric metric | part_time_employees | Part-Time Employees | number        | number        |
| Yes      | numeric metric | temporary_employees | Temporary Employees | number        | number        |
| Yes      | numeric metric | male                | Male                | number        | number        |
| Yes      | numeric metric | female              | Female              | number        | number        |
```

## Time Field

```ls
Value = count_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:ixhm-96mq d:2010-12-23T00:00:00.000Z t:department="Administrative Services" t:department_number=005 t:special_department="Administrative Services, Department of" t:function="Administration and Regulation" m:temporary_employees=4 m:female=147 m:part_time_employees=8 m:male=217 m:full_time_employees=364

series e:ixhm-96mq d:2011-01-20T00:00:00.000Z t:department="Administrative Services" t:department_number=005 t:special_department="Administrative Services, Department of" t:function="Administration and Regulation" m:temporary_employees=4 m:female=146 m:part_time_employees=7 m:male=217 m:full_time_employees=363

series e:ixhm-96mq d:2011-02-17T00:00:00.000Z t:department="Administrative Services" t:department_number=005 t:special_department="Administrative Services, Department of" t:function="Administration and Regulation" m:temporary_employees=4 m:female=142 m:part_time_employees=7 m:male=219 m:full_time_employees=361
```

## Meta Commands

```ls
metric m:full_time_employees p:integer l:"Full-Time Employees" d:"Number of full-time employees" t:dataTypeName=number

metric m:part_time_employees p:integer l:"Part-Time Employees" d:"Number of part-time employees" t:dataTypeName=number

metric m:temporary_employees p:integer l:"Temporary Employees" d:"Number of temporary employees" t:dataTypeName=number

metric m:male p:integer l:Male d:"Number of male full-time employees" t:dataTypeName=number

metric m:female p:integer l:Female d:"Number of female full-time employees" t:dataTypeName=number

entity e:ixhm-96mq l:"State of Iowa Employee Counts by Month and Agency" t:attribution="Iowa Department of Administrative Services, Human Resource Enterprise, Human Resource Data Warehouse" t:url=https://data.iowa.gov/api/views/ixhm-96mq

property e:ixhm-96mq t:meta.view v:id=ixhm-96mq v:category=Government v:averageRating=0 v:name="State of Iowa Employee Counts by Month and Agency" v:attribution="Iowa Department of Administrative Services, Human Resource Enterprise, Human Resource Data Warehouse"

property e:ixhm-96mq t:meta.view.license v:name="Public Domain"

property e:ixhm-96mq t:meta.view.owner v:id=82ih-8gep v:profileImageUrlMedium=/api/users/82ih-8gep/profile_images/THUMB v:profileImageUrlLarge=/api/users/82ih-8gep/profile_images/LARGE v:screenName="DAS, Human Resources Enterprise" v:profileImageUrlSmall=/api/users/82ih-8gep/profile_images/TINY v:displayName="DAS, Human Resources Enterprise"

property e:ixhm-96mq t:meta.view.tableauthor v:id=82ih-8gep v:profileImageUrlMedium=/api/users/82ih-8gep/profile_images/THUMB v:profileImageUrlLarge=/api/users/82ih-8gep/profile_images/LARGE v:screenName="DAS, Human Resources Enterprise" v:profileImageUrlSmall=/api/users/82ih-8gep/profile_images/TINY v:roleName=editor v:displayName="DAS, Human Resources Enterprise"
```

## Top Records

```ls
| function                      | special_department                     | department_number | department              | count_date          | full_time_employees | part_time_employees | temporary_employees | male | female | 
| ============================= | ====================================== | ================= | ======================= | =================== | =================== | =================== | =================== | ==== | ====== | 
| Administration and Regulation | Administrative Services, Department of | 005               | Administrative Services | 2010-12-23T00:00:00 | 364                 | 8                   | 4                   | 217  | 147    | 
| Administration and Regulation | Administrative Services, Department of | 005               | Administrative Services | 2011-01-20T00:00:00 | 363                 | 7                   | 4                   | 217  | 146    | 
| Administration and Regulation | Administrative Services, Department of | 005               | Administrative Services | 2011-02-17T00:00:00 | 361                 | 7                   | 4                   | 219  | 142    | 
| Administration and Regulation | Administrative Services, Department of | 005               | Administrative Services | 2011-03-31T00:00:00 | 361                 | 7                   | 4                   | 219  | 142    | 
| Administration and Regulation | Administrative Services, Department of | 005               | Administrative Services | 2011-04-28T00:00:00 | 361                 | 6                   | 4                   | 219  | 142    | 
| Administration and Regulation | Administrative Services, Department of | 005               | Administrative Services | 2011-05-26T00:00:00 | 357                 | 6                   | 4                   | 216  | 141    | 
| Administration and Regulation | Administrative Services, Department of | 005               | Administrative Services | 2011-06-23T00:00:00 | 357                 | 7                   | 2                   | 216  | 141    | 
| Administration and Regulation | Administrative Services, Department of | 005               | Administrative Services | 2011-07-21T00:00:00 | 354                 | 7                   | 2                   | 214  | 140    | 
| Administration and Regulation | Administrative Services, Department of | 005               | Administrative Services | 2011-08-18T00:00:00 | 356                 | 6                   | 2                   | 215  | 141    | 
| Administration and Regulation | Administrative Services, Department of | 005               | Administrative Services | 2011-09-29T00:00:00 | 355                 | 6                   | 2                   | 214  | 141    | 
```