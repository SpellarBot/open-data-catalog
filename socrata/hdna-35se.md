# Comptroller - Annual Salaries - 2014 - August 28

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/comptroller-annual-salaries-2014-august-28-05d68) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/hdna-35se) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/hdna-35se/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/hdna-35se/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | hdna-35se |
| Name | Comptroller - Annual Salaries - 2014 - August 28 |
| Attribution | Cook County Office of the Comptroller |
| Category | Finance & Administration |
| Tags | salary |
| Created | 2014-05-14T15:39:42Z |
| Publication Date | 2016-01-21T18:33:52Z |

## Description

Annual salaries paid to employees by the Cook County Comptroller as of August 28, 2014. For 2015 data see https://datacatalog.cookcountyil.gov/d/9tzu-m4zi.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type     | Render Type   |
| ======== | ============== | ================== | ================== | ============= | ============= |
| Yes      | series tag     | bureau             | Bureau             | text          | text          |
| Yes      | series tag     | department_number  | Department Number  | text          | text          |
| Yes      | series tag     | department_name    | Department Name    | text          | text          |
| Yes      | series tag     | name               | Name               | text          | text          |
| Yes      | series tag     | job_code           | Job Code           | text          | text          |
| Yes      | series tag     | title              | Title              | text          | text          |
| Yes      | series tag     | grade              | Grade              | text          | text          |
| Yes      | series tag     | step               | Step               | text          | text          |
| Yes      | time           | original_hire_date | Original Hire Date | calendar_date | calendar_date |
| No       |                | start_date         | Start Date         | calendar_date | calendar_date |
| Yes      | series tag     | employee_status    | Employee Status    | text          | text          |
| Yes      | numeric metric | annual_salary      | Annual Salary      | money         | money         |
```

## Time Field

```ls
Value = original_hire_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = start_date
```

## Data Commands

```ls
series e:hdna-35se d:1993-12-21T00:00:00.000Z t:employee_status=0 t:title="Human Rights Investigator II" t:job_code=0071 t:name="O'CONNELL, JOHN R" t:department_number=002 t:grade=21 t:department_name="Human Rights and Ethics" t:step=419 t:bureau=COR m:annual_salary=84556.16

series e:hdna-35se d:1998-07-20T00:00:00.000Z t:employee_status=0 t:title="Business Manager I" t:job_code=0251 t:name="VALENTIN, VERONICA" t:department_number=002 t:grade=18 t:department_name="Human Rights and Ethics" t:step=299 t:bureau=COR m:annual_salary=46475.51

series e:hdna-35se d:2013-09-09T00:00:00.000Z t:employee_status=0 t:title="Human Rights Investigator I" t:job_code=0077 t:name="JONES, JASON P." t:department_number=002 t:grade=19 t:department_name="Human Rights and Ethics" t:step=317 t:bureau=COR m:annual_salary=50837.27
```

## Meta Commands

```ls
metric m:annual_salary p:double l:"Annual Salary" t:dataTypeName=money

entity e:hdna-35se l:"Comptroller - Annual Salaries - 2014 - August 28" t:attribution="Cook County Office of the Comptroller" t:url=https://datacatalog.cookcountyil.gov/api/views/hdna-35se

property e:hdna-35se t:meta.view v:id=hdna-35se v:category="Finance & Administration" v:attributionLink=http://www.cookcountyil.gov/office-of-the-comptroller/ v:averageRating=0 v:name="Comptroller - Annual Salaries - 2014 - August 28" v:attribution="Cook County Office of the Comptroller"

property e:hdna-35se t:meta.view.license v:name="Public Domain"

property e:hdna-35se t:meta.view.owner v:id=d4g2-kc7i v:screenName="Cook County Webmaster" v:displayName="Cook County Webmaster"

property e:hdna-35se t:meta.view.tableauthor v:id=d4g2-kc7i v:screenName="Cook County Webmaster" v:roleName=administrator v:displayName="Cook County Webmaster"
```

## Top Records

```ls
| bureau | department_number | department_name         | name               | job_code | title                        | grade | step | original_hire_date  | start_date          | employee_status | annual_salary | 
| ====== | ================= | ======================= | ================== | ======== | ============================ | ===== | ==== | =================== | =================== | =============== | ============= | 
| COR    | 002               | Human Rights and Ethics | O'CONNELL, JOHN R  | 0071     | Human Rights Investigator II | 21    | 419  | 1993-12-21T00:00:00 | 2001-02-11T00:00:00 | 0               | 84556.16      | 
| COR    | 002               | Human Rights and Ethics | VALENTIN, VERONICA | 0251     | Business Manager I           | 18    | 299  | 1998-07-20T00:00:00 | 1998-07-20T00:00:00 | 0               | 46475.51      | 
| COR    | 002               | Human Rights and Ethics | JONES, JASON P.    | 0077     | Human Rights Investigator I  | 19    | 317  | 2013-09-09T00:00:00 | 2013-09-09T00:00:00 | 0               | 50837.27      | 
| COR    | 002               | Human Rights and Ethics | JOHNS, KISHA M.    | 0047     | Admin Assistant II           | 14    | 242  | 2014-05-05T00:00:00 | 2014-05-05T00:00:00 | 0               | 34975.19      | 
| COR    | 002               | Human Rights and Ethics | HAKIM, RANJIT J.   | 0081     | Director                     | 24    |      | 2013-08-07T00:00:00 | 2013-08-07T00:00:00 | 0               | 110355        | 
| COR    | 002               | Human Rights and Ethics | FISHER, LATRECE    | 0670     | Ethics Investigator II       | 21    | 355  | 2014-02-24T00:00:00 | 2014-02-24T00:00:00 | 0               | 61449.44      | 
| COR    | 002               | Human Rights and Ethics | DOLAN, MARY J.     | 5368     | Legal Counsel                | 24    |      | 2014-07-28T00:00:00 | 2014-07-28T00:00:00 | 0               | 85000         | 
| COR    | 002               | Human Rights and Ethics | CAHN, AVIVA        | 0071     | Human Rights Investigator II | 21    | 398  | 1997-10-27T00:00:00 | 1997-10-27T00:00:00 | 0               | 76146.72      | 
| COR    | 002               | Human Rights and Ethics | BROWN, JARRIE L.   | 4796     | Ethics Investigator I        | 19    | 325  | 2012-03-26T00:00:00 | 2012-03-26T00:00:00 | 0               | 52908.95      | 
| COR    | 007               | Revenue                 | MICHALS, GARY R.   | 5721     | Tax Compliance Adminstrator  | 23    | 413  | 2013-04-08T00:00:00 | 2013-04-08T00:00:00 | 0               | 82062.24      | 
```