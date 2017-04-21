# Comptroller - Annual Salaries - 2015 - November 24

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/comptroller-annual-salaries-2015-november-24) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/9tzu-m4zi) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/9tzu-m4zi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/9tzu-m4zi/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | 9tzu-m4zi |
| Name | Comptroller - Annual Salaries - 2015 - November 24 |
| Attribution | Cook County Office of the Comptroller |
| Category | Finance & Administration |
| Tags | salary |
| Created | 2015-12-10T16:33:36Z |
| Publication Date | 2016-01-21T18:31:45Z |

## Description

Annual salaries paid to employees by the Cook County Comptroller as of November 24, 2015. This dataset does not include salaries for Cook County Forest Preserves. This is the newest salaries dataset. 

For 2014, see https://datacatalog.cookcountyil.gov/d/hdna-35se.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type     | Render Type   |
| ======== | ============== | ================== | ================== | ============= | ============= |
| Yes      | series tag     | bureau             | Bureau             | text          | text          |
| Yes      | series tag     | department_number  | Department Number  | text          | number        |
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
series e:9tzu-m4zi d:1993-12-21T00:00:00.000Z t:employee_status=0 t:title="Human Rights Investigator II" t:job_code=71 t:name="O'CONNELL, JOHN R" t:department_number=2 t:grade=21 t:department_name="Human Rights and Ethics" t:step=423 t:bureau=COR m:annual_salary=90147.2

series e:9tzu-m4zi d:1997-10-27T00:00:00.000Z t:employee_status=0 t:title="Human Rights Investigator II" t:job_code=71 t:name="CAHN, AVIVA" t:department_number=2 t:grade=21 t:department_name="Human Rights and Ethics" t:step=406 t:bureau=COR m:annual_salary=82815.2

series e:9tzu-m4zi d:2013-09-09T00:00:00.000Z t:employee_status=0 t:title="Human Rights Investigator I" t:job_code=77 t:name="JONES, JASON P." t:department_number=2 t:grade=19 t:department_name="Human Rights and Ethics" t:step=325 t:bureau=COR m:annual_salary=55290.56
```

## Meta Commands

```ls
metric m:annual_salary p:double l:"Annual Salary" t:dataTypeName=money

entity e:9tzu-m4zi l:"Comptroller - Annual Salaries - 2015 - November 24" t:attribution="Cook County Office of the Comptroller" t:url=https://datacatalog.cookcountyil.gov/api/views/9tzu-m4zi

property e:9tzu-m4zi t:meta.view v:id=9tzu-m4zi v:category="Finance & Administration" v:attributionLink=http://www.cookcountyil.gov/office-of-the-comptroller/ v:averageRating=0 v:name="Comptroller - Annual Salaries - 2015 - November 24" v:attribution="Cook County Office of the Comptroller"

property e:9tzu-m4zi t:meta.view.license v:name="Public Domain"

property e:9tzu-m4zi t:meta.view.owner v:id=u38g-hbsa v:screenName="Cook County Open Data" v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"

property e:9tzu-m4zi t:meta.view.tableauthor v:id=u38g-hbsa v:screenName="Cook County Open Data" v:roleName=administrator v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"
```

## Top Records

```ls
| bureau | department_number | department_name         | name               | job_code | title                        | grade | step | original_hire_date  | start_date          | employee_status | annual_salary | 
| ====== | ================= | ======================= | ================== | ======== | ============================ | ===== | ==== | =================== | =================== | =============== | ============= | 
| COR    | 2                 | Human Rights and Ethics | O'CONNELL, JOHN R  | 71       | Human Rights Investigator II | 21    | 423  | 1993-12-21T00:00:00 | 2001-02-11T00:00:00 | 0               | 90147.20      | 
| COR    | 2                 | Human Rights and Ethics | CAHN, AVIVA        | 71       | Human Rights Investigator II | 21    | 406  | 1997-10-27T00:00:00 | 1997-10-27T00:00:00 | 0               | 82815.20      | 
| COR    | 2                 | Human Rights and Ethics | JONES, JASON P.    | 77       | Human Rights Investigator I  | 19    | 325  | 2013-09-09T00:00:00 | 2013-09-09T00:00:00 | 0               | 55290.56      | 
| COR    | 2                 | Human Rights and Ethics | BROWN, JARRIE L.   | 4796     | Ethics Investigator I        | 19    | 329  | 2012-03-26T00:00:00 | 2012-03-26T00:00:00 | 0               | 56403.36      | 
| COR    | 2                 | Human Rights and Ethics | FISHER, LATRECE    | 670      | Ethics Investigator II       | 21    | 359  | 2014-02-24T00:00:00 | 2014-02-24T00:00:00 | 0               | 65505.44      | 
| COR    | 2                 | Human Rights and Ethics | VALENTIN, VERONICA | 251      | Business Manager I           | 18    | 303  | 1998-07-20T00:00:00 | 1998-07-20T00:00:00 | 0               | 49543.52      | 
| COR    | 2                 | Human Rights and Ethics | HAKIM, RANJIT J.   | 81       | Director                     | 24    |      | 2013-08-07T00:00:00 | 2013-08-07T00:00:00 | 0               | 114218.00     | 
| COR    | 2                 | Human Rights and Ethics | JOHNS, KISHA M.    | 47       | Admin Assistant II           | 14    | 246  | 2014-05-05T00:00:00 | 2014-05-05T00:00:00 | 0               | 37284.00      | 
| COR    | 2                 | Human Rights and Ethics | DOLAN, MARY J.     | 5368     | Legal Counsel                | 24    |      | 2014-07-28T00:00:00 | 2014-07-28T00:00:00 | 0               | 86700.00      | 
| COR    | 7                 | Revenue                 | MASON, KELLY       | 51       | Administrative Assistant V   | 20    | 418  | 1999-07-16T00:00:00 | 2004-08-02T00:00:00 | 0               | 87921.60      | 
```