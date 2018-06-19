# Budget - 2011 Budget Ordinance - Positions and Salaries

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/budget-2011-budget-ordinance-positions-and-salaries-ea484) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/g398-fhbm) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/g398-fhbm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/g398-fhbm/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | g398-fhbm |
| Name | Budget - 2011 Budget Ordinance - Positions and Salaries |
| Attribution | City of Chicago |
| Category | Administration & Finance |
| Tags | budget, personnel |
| Created | 2011-05-26T13:49:44Z |
| Publication Date | 2011-05-26T13:49:44Z |

## Description

The Annual Appropriation Ordinance is the final City operating budget as approved by the City Council. It reflects the City?s operating budget at the beginning of the fiscal year on January 1, 2011.This dataset displays the positions and related salaries detailed in the budget as of January 1. It is extracted from the personnel portion of the Appropriation Ordinance. The dataset presents the position titles (without names) and salaries described in the budget, but does not provide a reflection of the current city workforce with full names and salaries. Disclaimer: the ?Total Budgeted Units? column displays either A) the number of employees AND vacancies associated with a given position, or B) the number of budgeted units (ie. hours/months) for that position. ?Position Control? determines whether Total Budgeted Units column will count employees and vacancies or hours/months. If a Position Control is 1, then employees and vacancies are displayed; if a Position Control is 0, then the total number of hours/months recorded is displayed. Owner: Budget and Management. Frequency: Data is updated annually. For information on the current city workforce, with names, positions and salaries, visit the "Current Employee Names, Salaries, and Position Titles" dataset: http://j.mp/iutKlR.

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type | Render Type |
| ======== | ============== | ===================== | ===================== | ========= | =========== |
| Yes      | series tag     | fund_type             | FUND TYPE             | text      | text        |
| Yes      | series tag     | fund_code             | FUND CODE             | text      | number      |
| Yes      | series tag     | department_code       | DEPARTMENT CODE       | text      | number      |
| Yes      | series tag     | organization_code     | ORGANIZATION CODE     | text      | number      |
| Yes      | series tag     | division_code         | DIVISION CODE         | text      | number      |
| Yes      | series tag     | section_code          | SECTION CODE          | text      | number      |
| Yes      | series tag     | subsection_code       | SUBSECTION CODE       | text      | number      |
| Yes      | series tag     | schedule              | SCHEDULE              | text      | text        |
| Yes      | series tag     | title_code            | TITLE CODE            | text      | number      |
| Yes      | series tag     | title_description     | TITLE DESCRIPTION     | text      | text        |
| Yes      | series tag     | fund_name             | FUND NAME             | text      | text        |
| Yes      | series tag     | department            | DEPARTMENT            | text      | text        |
| Yes      | series tag     | department_name       | DEPARTMENT NAME       | text      | text        |
| Yes      | series tag     | division_name         | DIVISION NAME         | text      | text        |
| Yes      | series tag     | section_name          | SECTION NAME          | text      | text        |
| Yes      | series tag     | subsection_name       | SUBSECTION NAME       | text      | text        |
| Yes      | series tag     | budgeted_unit         | BUDGETED UNIT         | text      | text        |
| Yes      | numeric metric | total_budgeted_units  | TOTAL BUDGETED UNITS  | number    | number      |
| Yes      | numeric metric | position_control      | POSITION CONTROL      | number    | number      |
| Yes      | numeric metric | budgeted_pay_rate     | BUDGETED PAY RATE     | money     | money       |
| Yes      | numeric metric | total_budgeted_amount | TOTAL BUDGETED AMOUNT | money     | money       |
```

## Time Field

```ls
Value = 2011
Format & Zone = yyyy
```

## Data Commands

```ls
series e:g398-fhbm d:2011-01-01T00:00:00.000Z t:fund_code=300 t:fund_type=Local t:division_code=2005 t:department="CITY CLERK" t:organization_code=1005 t:budgeted_unit=Annual t:subsection_code=0 t:division_name="City Clerk" t:section_name="Vehicle License Data Services" t:section_code=3030 t:fund_name="VEHICLE FUND" t:schedule=1 t:title_code=15 t:title_description="Schedule Salary Adjustments" t:department_code=25 t:department_name="CITY CLERK" m:total_budgeted_amount=2485 m:total_budgeted_units=0 m:position_control=0 m:budgeted_pay_rate=2485

series e:g398-fhbm d:2011-01-01T00:00:00.000Z t:fund_code=610 t:fund_type=Local t:division_code=2005 t:department="DEPT OF FIN" t:organization_code=1005 t:budgeted_unit=Annual t:subsection_code=0 t:division_name="City Comptroller" t:section_name=Auditing t:section_code=3030 t:fund_name="MIDWAY AIRPORT FUND" t:schedule=1 t:title_code=15 t:title_description="Schedule Salary Adjustments" t:department_code=27 t:department_name="DEPARTMENT OF FINANCE" m:total_budgeted_amount=2389 m:total_budgeted_units=0 m:position_control=0 m:budgeted_pay_rate=2389

series e:g398-fhbm d:2011-01-01T00:00:00.000Z t:fund_code=610 t:fund_type=Local t:division_code=2005 t:department="DEPT OF FIN" t:organization_code=1005 t:budgeted_unit=Annual t:subsection_code=0 t:division_name="City Comptroller" t:section_name=Auditing t:section_code=3030 t:fund_name="MIDWAY AIRPORT FUND" t:schedule=G t:title_code=102 t:title_description="Accountant II" t:department_code=27 t:department_name="DEPARTMENT OF FINANCE" m:total_budgeted_amount=73932 m:total_budgeted_units=1 m:position_control=1 m:budgeted_pay_rate=73932
```

## Meta Commands

```ls
metric m:total_budgeted_units p:integer l:"TOTAL BUDGETED UNITS" t:dataTypeName=number

metric m:position_control p:integer l:"POSITION CONTROL" t:dataTypeName=number

metric m:budgeted_pay_rate p:integer l:"BUDGETED PAY RATE" t:dataTypeName=money

metric m:total_budgeted_amount p:integer l:"TOTAL BUDGETED AMOUNT" t:dataTypeName=money

entity e:g398-fhbm l:"Budget - 2011 Budget Ordinance - Positions and Salaries" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/g398-fhbm

property e:g398-fhbm t:meta.view v:id=g398-fhbm v:category="Administration & Finance" v:attributionLink=http://www.cityofchicago.org/city/en/depts/obm/provdrs/city_budg.html v:averageRating=0 v:name="Budget - 2011 Budget Ordinance - Positions and Salaries" v:attribution="City of Chicago"

property e:g398-fhbm t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:g398-fhbm t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| fund_type | fund_code | department_code | organization_code | division_code | section_code | subsection_code | schedule | title_code | title_description            | fund_name           | department  | department_name       | division_name               | section_name                  | subsection_name | budgeted_unit | total_budgeted_units | position_control | budgeted_pay_rate | total_budgeted_amount | 
| ========= | ========= | =============== | ================= | ============= | ============ | =============== | ======== | ========== | ============================ | =================== | =========== | ===================== | =========================== | ============================= | =============== | ============= | ==================== | ================ | ================= | ===================== | 
| Local     | 300       | 25              | 1005              | 2005          | 3030         | 0               | 1        | 15         | Schedule Salary Adjustments  | VEHICLE FUND        | CITY CLERK  | CITY CLERK            | City Clerk                  | Vehicle License Data Services |                 | Annual        | 0                    | 0                | 2485              | 2485                  | 
| Local     | 610       | 27              | 1005              | 2005          | 3030         | 0               | 1        | 15         | Schedule Salary Adjustments  | MIDWAY AIRPORT FUND | DEPT OF FIN | DEPARTMENT OF FINANCE | City Comptroller            | Auditing                      |                 | Annual        | 0                    | 0                | 2389              | 2389                  | 
| Local     | 610       | 27              | 1005              | 2005          | 3030         | 0               | G        | 102        | Accountant II                | MIDWAY AIRPORT FUND | DEPT OF FIN | DEPARTMENT OF FINANCE | City Comptroller            | Auditing                      |                 | Annual        | 1                    | 1                | 73932             | 73932                 | 
| Local     | 100       | 28              | 1005              | 2005          | 3015         | 0               | G        | 104        | Accountant IV                | CORPORATE FUND      | TREAS       | CITY TREASURER        | City Treasurer              | Financial Reporting           |                 | Annual        | 1                    | 1                | 76536             | 76536                 | 
| Local     | 100       | 28              | 1005              | 2005          | 3015         | 0               | G        | 104        | Accountant IV                | CORPORATE FUND      | TREAS       | CITY TREASURER        | City Treasurer              | Financial Reporting           |                 | Annual        | 1                    | 1                | 88140             | 88140                 | 
| Local     | 100       | 32              | 1005              | 2005          | 3010         | 0               | GY       | 1367       | Assistant Compliance Officer | CORPORATE FUND      | COMP        | OFFICE OF COMPLIANCE  | Office of Compliance        | Law Compliance                |                 | Annual        | 0                    | 0                | 53844             | 0                     | 
| Local     | 100       | 3               | 1005              | 2005          | 3020         | 0               | 3        | 152        | Senior Auditor - IG          | CORPORATE FUND      | IG          | INSPECTOR GENERAL     | Office of Inspector General | Investigations                |                 | Annual        | 1                    | 1                | 76500             | 76500                 | 
| Local     | 314       | 3               | 1005              | 2005          | 3320         | 0               | 1        | 15         | Schedule Salary Adjustments  | SEWER FUND          | IG          | INSPECTOR GENERAL     | Office of Inspector General | Investigations                |                 | Annual        | 0                    | 0                | 1512              | 1512                  | 
| Local     | 314       | 3               | 1005              | 2005          | 3320         | 0               | BX       | 1255       | Investigator                 | SEWER FUND          | IG          | INSPECTOR GENERAL     | Office of Inspector General | Investigations                |                 | Annual        | 1                    | 1                | 54492             | 54492                 | 
| Local     | 314       | 3               | 1005              | 2005          | 3320         | 0               | 3        | 1260       | Chief Investigator - IGO     | SEWER FUND          | IG          | INSPECTOR GENERAL     | Office of Inspector General | Investigations                |                 | Annual        | 1                    | 1                | 102552            | 102552                | 
```