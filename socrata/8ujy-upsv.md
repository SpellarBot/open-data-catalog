# Email Addresses for all City of Austin Employees

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/email-addresses-for-all-city-of-austin-employees) |
| Metadata | [Link](https://data.austintexas.gov/api/views/8ujy-upsv) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/8ujy-upsv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/8ujy-upsv/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | 8ujy-upsv |
| Name | Email Addresses for all City of Austin Employees |
| Attribution | City of Austin - Human Resources Department |
| Category | Business |
| Tags | email, coa email |
| Created | 2015-08-25T18:57:44Z |
| Publication Date | 2015-10-09T19:15:55Z |

## Description

Email addresses for all current active employees who currently have a COA work email address - FY2015 PN19

## Columns

```ls
| Included | Schema Type | Field Name      | Name            | Data Type | Render Type |
| ======== | =========== | =============== | =============== | ========= | =========== |
| No       | time        | :updated_at     | updated_at      | meta_data | meta_data   |
| Yes      | series tag  | emp_id          | Emp ID          | text      | number      |
| Yes      | series tag  | last            | Last            | text      | text        |
| Yes      | series tag  | first           | First           | text      | text        |
| No       |             | mi              | MI              | text      | text        |
| Yes      | series tag  | department      | Department      | text      | text        |
| Yes      | series tag  | department_name | Department Name | text      | text        |
| Yes      | series tag  | staffing_level  | Staffing Level  | text      | text        |
| Yes      | series tag  | employee_class  | Employee Class  | text      | text        |
| Yes      | series tag  | title           | Title           | text      | text        |
| Yes      | series tag  | job_status      | Job Status      | text      | text        |
| Yes      | series tag  | email_type      | Email Type      | text      | text        |
| Yes      | series tag  | email           | Email           | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = mi
```

## Data Commands

```ls
series e:8ujy-upsv d:2015-08-25T11:58:10.000Z t:title=Firefighter t:last=Spills t:staffing_level=Worker t:department=83G t:emp_id=10128127 t:employee_class="Fire Kelly" t:department_name=Fire t:job_status=A t:first=Warren m:row_number.8ujy-upsv=1

series e:8ujy-upsv d:2015-08-25T11:58:10.000Z t:title=Firefighter t:last=Gretch t:staffing_level=Worker t:department=83G t:emp_id=10128129 t:employee_class="Fire Kelly" t:department_name=Fire t:job_status=A t:first=Daniel m:row_number.8ujy-upsv=2

series e:8ujy-upsv d:2015-08-25T11:58:10.000Z t:title=Firefighter t:last=Venzant t:staffing_level=Worker t:department=83G t:emp_id=10128130 t:employee_class="Fire Kelly" t:department_name=Fire t:job_status=A t:first=Jason m:row_number.8ujy-upsv=3
```

## Meta Commands

```ls
metric m:row_number.8ujy-upsv p:long l:"Row Number"

entity e:8ujy-upsv l:"Email Addresses for all City of Austin Employees" t:attribution="City of Austin - Human Resources Department" t:url=https://data.austintexas.gov/api/views/8ujy-upsv

property e:8ujy-upsv t:meta.view v:id=8ujy-upsv v:category=Business v:attributionLink=https://opendata.bloomfire.com/posts/1013422 v:averageRating=0 v:name="Email Addresses for all City of Austin Employees" v:attribution="City of Austin - Human Resources Department"

property e:8ujy-upsv t:meta.view.license v:name="Public Domain"

property e:8ujy-upsv t:meta.view.owner v:id=q57t-cafe v:screenName="Perry Perez" v:displayName="Perry Perez"

property e:8ujy-upsv t:meta.view.tableauthor v:id=q57t-cafe v:screenName="Perry Perez" v:roleName=editor v:displayName="Perry Perez"
```

## Top Records

```ls
| :updated_at | emp_id   | last      | first  | mi      | department | department_name | staffing_level | employee_class | title       | job_status | email_type | email | 
| =========== | ======== | ========= | ====== | ======= | ========== | =============== | ============== | ============== | =========== | ========== | ========== | ===== | 
| 1440503890  | 10128127 | Spills    | Warren | Justin  | 83G        | Fire            | Worker         | Fire Kelly     | Firefighter | A          |            |       | 
| 1440503890  | 10128129 | Gretch    | Daniel | Dee     | 83G        | Fire            | Worker         | Fire Kelly     | Firefighter | A          |            |       | 
| 1440503890  | 10128130 | Venzant   | Jason  | Allen   | 83G        | Fire            | Worker         | Fire Kelly     | Firefighter | A          |            |       | 
| 1440503890  | 10128131 | Jameson   | Brian  | Tod     | 83G        | Fire            | Worker         | Fire Kelly     | Firefighter | A          |            |       | 
| 1440503890  | 10128132 | Vinson    | Justin | Gabriel | 83G        | Fire            | Worker         | Fire Kelly     | Firefighter | A          |            |       | 
| 1440503890  | 10128133 | Langhorst | Kyle   | J       | 83G        | Fire            | Worker         | Fire Kelly     | Firefighter | A          |            |       | 
| 1440503890  | 10128134 | Weir      | John   | Ross    | 83G        | Fire            | Worker         | Fire Kelly     | Firefighter | A          |            |       | 
| 1440503890  | 10128413 | Walker    | Trista | Latoya  | 83G        | Fire            | Worker         | Fire 40        | Firefighter | A          |            |       | 
| 1440503884  | 10087769 | Lamb      | Roth   | N       | 83G        | Fire            | Worker         | Fire Kelly     | Firefighter | A          |            |       | 
| 1440503884  | 10093583 | Thompson  | Iain   | L       | 83G        | Fire            | Worker         | Fire Kelly     | Firefighter | A          |            |       | 
```