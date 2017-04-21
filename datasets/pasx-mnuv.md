# Employee Indebtedness to the City of Chicago

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/employee-indebtedness-to-the-city-of-chicago-28e96) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/pasx-mnuv) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/pasx-mnuv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/pasx-mnuv/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | pasx-mnuv |
| Name | Employee Indebtedness to the City of Chicago |
| Attribution | City of Chicago |
| Category | Administration & Finance |
| Tags | personnel, debt |
| Created | 2011-10-11T23:45:30Z |
| Publication Date | 2017-02-08T22:22:35Z |

## Description

Number of employees in each department or sister agency who owe funds to the City. For each department, the dataset provides the following as of the date noted: total number of individuals employed by the department or agency, number of individuals that owe funds to the City in the department; and the total amount of debt owed by those employees. Data Owner: Revenue. Time Period: mid-October 2011 to present. Frequency: Data is updated weekly.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name                      | Data Type     | Render Type   |
| ======== | ============== | ================== | ========================= | ============= | ============= |
| Yes      | time           | date               | Date                      | calendar_date | calendar_date |
| Yes      | series tag     | department         | Department or Agency Name | text          | text          |
| Yes      | series tag     | arms_department_id | ARMS Department ID        | text          | text          |
| Yes      | numeric metric | dept_size          | Total # of Employees      | number        | number        |
| Yes      | numeric metric | employees          | # of Employees with Debt  | number        | number        |
| Yes      | numeric metric | employees_w_debt   | % Employees with Debt     | percent       | percent       |
| Yes      | numeric metric | due                | Total Amount Due          | money         | money         |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:pasx-mnuv d:2011-10-14T00:00:00.000Z t:department="Administrative Hearings" m:employees_w_debt=5.1 m:due=368 m:dept_size=39 m:employees=2

series e:pasx-mnuv d:2011-10-14T00:00:00.000Z t:department="Animal Care & Control" m:employees_w_debt=4.4 m:due=2564 m:dept_size=68 m:employees=3

series e:pasx-mnuv d:2011-10-14T00:00:00.000Z t:department=Aviation m:employees_w_debt=4.3 m:due=19092 m:dept_size=1265 m:employees=54
```

## Meta Commands

```ls
metric m:dept_size p:integer l:"Total # of Employees" t:dataTypeName=number

metric m:employees p:integer l:"# of Employees with Debt" t:dataTypeName=number

metric m:employees_w_debt p:float l:"% Employees with Debt" t:dataTypeName=percent

metric m:due p:double l:"Total Amount Due" t:dataTypeName=money

entity e:pasx-mnuv l:"Employee Indebtedness to the City of Chicago" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/pasx-mnuv

property e:pasx-mnuv t:meta.view v:id=pasx-mnuv v:category="Administration & Finance" v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Employee Indebtedness to the City of Chicago" v:attribution="City of Chicago"

property e:pasx-mnuv t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:pasx-mnuv t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| date                | department                             | arms_department_id | dept_size | employees | employees_w_debt | due       | 
| =================== | ====================================== | ================== | ========= | ========= | ================ | ========= | 
| 2011-10-14T00:00:00 | Administrative Hearings                |                    | 39        | 2         | 5.1              | 368.00    | 
| 2011-10-14T00:00:00 | Animal Care & Control                  |                    | 68        | 3         | 4.4              | 2564.00   | 
| 2011-10-14T00:00:00 | Aviation                               |                    | 1265      | 54        | 4.3              | 19092.00  | 
| 2011-10-14T00:00:00 | Board of Elections                     |                    | 112       | 5         | 4.5              | 1068.00   | 
| 2011-10-14T00:00:00 | Board of Ethics                        |                    | 6         | 0         | 0.0              | 0.00      | 
| 2011-10-14T00:00:00 | Budget & Management                    |                    | 50        | 1         | 2.0              | 400.00    | 
| 2011-10-14T00:00:00 | Buildings                              |                    | 283       | 4         | 1.4              | 861.00    | 
| 2011-10-14T00:00:00 | Business Affairs & Consumer Protection |                    | 183       | 7         | 3.8              | 3208.00   | 
| 2011-10-14T00:00:00 | Chicago Board of Education             |                    | 48796     | 2832      | 5.8              | 962067.00 | 
| 2011-10-14T00:00:00 | Chicago Housing Authority              |                    | 467       | 25        | 5.4              | 6137.00   | 
```