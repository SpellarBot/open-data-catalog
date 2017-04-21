# Comptroller - Annual Salaries - 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/comptroller-annual-salaries-2013-63261) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/fxa5-tdd8) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/fxa5-tdd8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/fxa5-tdd8/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | fxa5-tdd8 |
| Name | Comptroller - Annual Salaries - 2013 |
| Attribution | Cook County Office of the Comptroller |
| Category | Finance & Administration |
| Created | 2013-05-02T20:28:28Z |
| Publication Date | 2014-10-09T22:39:41Z |

## Description

Annual salaries paid to employees by the Cook County Comptroller as of March 5, 2013. Does not include deduction for furlough or closure days for employees subject to furloughs and closures. Does not include amounts paid by other governmental entities. For 2014 salaries see https://datacatalog.cookcountyil.gov/resource/hdna-35se

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type     | Render Type   |
| ======== | ============== | ================== | ================== | ============= | ============= |
| Yes      | series tag     | department_number  | Department Number  | text          | number        |
| Yes      | series tag     | department_name    | Department Name    | text          | text          |
| Yes      | series tag     | name               | Name               | text          | text          |
| Yes      | series tag     | title              | Title              | text          | text          |
| Yes      | numeric metric | annual_salary      | Annual Salary      | money         | money         |
| Yes      | time           | original_hire_date | Original Hire Date | calendar_date | calendar_date |
| No       |                | start_date         | Start Date         | calendar_date | calendar_date |
| No       |                | date_in_position   | Date In Position   | calendar_date | calendar_date |
```

## Time Field

```ls
Value = original_hire_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = start_date,date_in_position
```

## Data Commands

```ls
series e:fxa5-tdd8 d:2005-10-03T00:00:00.000Z t:title=Director t:name="HORNE, PATRICIA  J." t:department_number=211 t:department_name="Dept. of Admin/Support Ser" m:annual_salary=90000

series e:fxa5-tdd8 d:1993-02-01T00:00:00.000Z t:title="Clerk V" t:name="DAILY, STEPHEN W" t:department_number=240 t:department_name="Cermak Health Services" m:annual_salary=46492.16

series e:fxa5-tdd8 d:2006-09-05T00:00:00.000Z t:title="Chief Correctional Psych" t:name="JONES, NNEKA S." t:department_number=240 t:department_name="Cermak Health Services" m:annual_salary=120000
```

## Meta Commands

```ls
metric m:annual_salary p:double l:"Annual Salary" t:dataTypeName=money

entity e:fxa5-tdd8 l:"Comptroller - Annual Salaries - 2013" t:attribution="Cook County Office of the Comptroller" t:url=https://datacatalog.cookcountyil.gov/api/views/fxa5-tdd8

property e:fxa5-tdd8 t:meta.view v:id=fxa5-tdd8 v:category="Finance & Administration" v:attributionLink=http://www.cookcountygov.com/portal/server.pt/community/comptroller%2C_office_of_the/266/comptroller%2C_office_of_the v:averageRating=0 v:name="Comptroller - Annual Salaries - 2013" v:attribution="Cook County Office of the Comptroller"

property e:fxa5-tdd8 t:meta.view.license v:name="Public Domain"

property e:fxa5-tdd8 t:meta.view.owner v:id=d4g2-kc7i v:screenName="Cook County Webmaster" v:displayName="Cook County Webmaster"

property e:fxa5-tdd8 t:meta.view.tableauthor v:id=d4g2-kc7i v:screenName="Cook County Webmaster" v:roleName=administrator v:displayName="Cook County Webmaster"
```

## Top Records

```ls
| department_number | department_name                | name               | title                      | annual_salary      | original_hire_date  | start_date          | date_in_position    | 
| ================= | ============================== | ================== | ========================== | ================== | =================== | =================== | =================== | 
| 211               | Dept. of Admin/Support Ser     | HORNE, PATRICIA J. | Director                   | 90000              | 2005-10-03T00:00:00 | 2005-10-03T00:00:00 | 2007-08-27T00:00:00 | 
| 240               | Cermak Health Services         | DAILY, STEPHEN W   | Clerk V                    | 46492.160000000003 | 1993-02-01T00:00:00 | 1993-02-01T00:00:00 | 2003-03-23T00:00:00 | 
| 240               | Cermak Health Services         | JONES, NNEKA S.    | Chief Correctional Psych   | 120000             | 2006-09-05T00:00:00 | 2006-09-05T00:00:00 | 2010-08-16T00:00:00 | 
| 240               | Cermak Health Services         | REYES, PATRICIA P  | Clerk V                    | 44279.040000000001 | 1995-02-21T00:00:00 | 1995-02-21T00:00:00 | 1995-02-21T00:00:00 | 
| 240               | Cermak Health Services         | UDE, PAULINE       | Clinical Nurse I           | 85415.2            | 2003-06-30T00:00:00 | 2003-06-30T00:00:00 | 2003-06-30T00:00:00 | 
| 280               | Adult Probation Dept.          | ESTRADA, YOBETT    | Clerk V                    | 43411.68           | 2000-01-18T00:00:00 | 2008-06-23T00:00:00 | 2008-06-23T00:00:00 | 
| 300               | Judiciary                      | FLYNN, PETER       | Judge of the Circuit Court | 500                | 1999-05-17T00:00:00 | 1999-05-17T00:00:00 | 1999-05-17T00:00:00 | 
| 313               | Social Casework Services       | GARCIA, CARMEN     | Clerk V                    | 46492.160000000003 | 1975-08-08T00:00:00 | 1975-08-08T00:00:00 | 2003-04-06T00:00:00 | 
| 501               | MFT Illinois First (Ist)       | CHAPMAN, ANDREW S  | Machinist                  | 90584              | 1988-04-01T00:00:00 | 1988-04-01T00:00:00 | 1993-04-17T00:00:00 | 
| 893               | Ambulatory/Community Hlth Ntwk | BOWDEN, VICTORIA M | Clerk V                    | 43411.68           | 2000-07-31T00:00:00 | 2000-07-31T00:00:00 | 2003-07-14T00:00:00 | 
```