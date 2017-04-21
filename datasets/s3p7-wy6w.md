# State of Iowa Salary Book

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-of-iowa-salary-book) |
| Metadata | [Link](https://data.iowa.gov/api/views/s3p7-wy6w) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/s3p7-wy6w/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/s3p7-wy6w/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | s3p7-wy6w |
| Name | State of Iowa Salary Book |
| Attribution | Iowa Department of Administrative Services, State of Iowa Salary Book |
| Category | Government |
| Tags | state employees, salaries, travel reimbursements, subsistence expense, salary book |
| Created | 2014-11-05T15:58:51Z |
| Publication Date | 2016-11-01T13:49:20Z |

## Description

The dataset contains the name, gender, county or city of residence (when possible), official title, total salary received during each fiscal year, base salary for the employee, and traveling and subsistence expense reimbursed to state personnel.

A status of "TERMINATED" in the column providing the base salary does not indicate that the employee was fired, only that the person no longer works in that position.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name                 | Data Type     | Render Type   |
| ======== | ============== | ================== | ==================== | ============= | ============= |
| No       |                | fiscal_year        | Fiscal Year          | number        | number        |
| Yes      | series tag     | department         | Department           | text          | text          |
| Yes      | series tag     | agency_institution | Agency/Institution   | text          | text          |
| Yes      | series tag     | name               | Name                 | text          | text          |
| Yes      | series tag     | gender             | Gender               | text          | text          |
| Yes      | series tag     | place_of_residence | Place of Residence   | text          | text          |
| Yes      | series tag     | position           | Position             | text          | text          |
| Yes      | series tag     | base_salary        | Base Salary          | text          | text          |
| Yes      | time           | base_salary_date   | Base Salary Date     | calendar_date | calendar_date |
| Yes      | numeric metric | total_salary_paid  | Total Salary Paid    | money         | money         |
| Yes      | numeric metric | travel_subsistence | Travel & Subsistence | money         | money         |
```

## Time Field

```ls
Value = base_salary_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = fiscal_year
```

## Data Commands

```ls
series e:s3p7-wy6w d:2007-07-01T00:00:00.000Z t:position="ADVANCED PERSONNEL MGMT" t:place_of_residence=POLK t:department="Administrative Services, Department of" t:base_salary="31.62 HR" t:name="ABELS BEVERLY J" t:gender=F m:total_salary_paid=6462.34

series e:s3p7-wy6w d:2007-07-01T00:00:00.000Z t:position="EARLY OUT POSITION" t:place_of_residence=WAPELLO t:department="Administrative Services, Department of" t:base_salary=TERMINATED t:name="ABRAMS JERRY A" t:gender=M m:total_salary_paid=4242.82

series e:s3p7-wy6w d:2007-07-01T00:00:00.000Z t:position="ADVANCED PERSONNEL MGMT" t:place_of_residence=MITCHELL t:department="Administrative Services, Department of" t:base_salary="2,212.80 BW" t:name="ADAMS CAROL L" t:gender=F m:total_salary_paid=55065.6 m:travel_subsistence=924.44
```

## Meta Commands

```ls
metric m:total_salary_paid p:double l:"Total Salary Paid" d:"Total salary paid during Fiscal Year" t:dataTypeName=money

metric m:travel_subsistence p:double l:"Travel & Subsistence" d:"Total travel & subsistance expenses reimbursed during Fiscal Year" t:dataTypeName=money

entity e:s3p7-wy6w l:"State of Iowa Salary Book" t:attribution="Iowa Department of Administrative Services, State of Iowa Salary Book" t:url=https://data.iowa.gov/api/views/s3p7-wy6w

property e:s3p7-wy6w t:meta.view v:id=s3p7-wy6w v:category=Government v:averageRating=0 v:name="State of Iowa Salary Book" v:attribution="Iowa Department of Administrative Services, State of Iowa Salary Book"

property e:s3p7-wy6w t:meta.view.license v:name="Public Domain"

property e:s3p7-wy6w t:meta.view.owner v:id=9dtn-esr4 v:profileImageUrlMedium=/api/users/9dtn-esr4/profile_images/THUMB v:profileImageUrlLarge=/api/users/9dtn-esr4/profile_images/LARGE v:screenName="Iowa Dept of Administrative Services" v:profileImageUrlSmall=/api/users/9dtn-esr4/profile_images/TINY v:displayName="Iowa Dept of Administrative Services"

property e:s3p7-wy6w t:meta.view.tableauthor v:id=9dtn-esr4 v:profileImageUrlMedium=/api/users/9dtn-esr4/profile_images/THUMB v:profileImageUrlLarge=/api/users/9dtn-esr4/profile_images/LARGE v:screenName="Iowa Dept of Administrative Services" v:profileImageUrlSmall=/api/users/9dtn-esr4/profile_images/TINY v:roleName=editor v:displayName="Iowa Dept of Administrative Services"
```

## Top Records

```ls
| fiscal_year | department                             | agency_institution | name                    | gender | place_of_residence | position                 | base_salary | base_salary_date    | total_salary_paid | travel_subsistence | 
| =========== | ====================================== | ================== | ======================= | ====== | ================== | ======================== | =========== | =================== | ================= | ================== | 
| 2007        | Administrative Services, Department of |                    | ABELS BEVERLY J         | F      | POLK               | ADVANCED PERSONNEL MGMT  | 31.62 HR    | 2007-07-01T00:00:00 | 6462.34           |                    | 
| 2007        | Administrative Services, Department of |                    | ABRAMS JERRY A          | M      | WAPELLO            | EARLY OUT POSITION       | TERMINATED  | 2007-07-01T00:00:00 | 4242.82           |                    | 
| 2007        | Administrative Services, Department of |                    | ADAMS CAROL L           | F      | MITCHELL           | ADVANCED PERSONNEL MGMT  | 2,212.80 BW | 2007-07-01T00:00:00 | 55065.60          | 924.44             | 
| 2007        | Administrative Services, Department of |                    | ADAMS JEANNIE R         | F      | POLK               | ACCOUNTING TECHNICIAN 2  | 1,226.40 BW | 2007-07-01T00:00:00 | 30800.83          | 6.80               | 
| 2007        | Administrative Services, Department of |                    | ADAMS NED J             | M      | POLK               | EARLY OUT POSITION       | TERMINATED  | 2007-07-01T00:00:00 | 10634.33          |                    | 
| 2007        | Administrative Services, Department of |                    | ADAMSON DAVID A         | M      | POLK               | CONSTRUCTION/DESIGN ENGN | TERMINATED  | 2007-07-01T00:00:00 | 77647.67          | 364.22             | 
| 2007        | Administrative Services, Department of |                    | ALLEN DANIEL S          | M      | POLK               | CUSTODIAL WORKER         | TERMINATED  | 2007-07-01T00:00:00 | 10520.28          | 7.48               | 
| 2007        | Administrative Services, Department of |                    | ALLEN ROSALIE R         | F      | CHEROKEE           | EARLY OUT POSITION       | TERMINATED  | 2007-07-01T00:00:00 | 2588.47           |                    | 
| 2007        | Administrative Services, Department of |                    | ALLEN SANDRA L          | F      | POLK               | INFO TECH SPECIALIST 2   | 2,194.40 BW | 2007-07-01T00:00:00 | 56205.58          | 65.28              | 
| 2007        | Administrative Services, Department of |                    | ALLERHEILIGEN RICHARD D | M      |                    | EARLY OUT POSITION       | TERMINATED  | 2007-07-01T00:00:00 | 1522.67           |                    | 
```