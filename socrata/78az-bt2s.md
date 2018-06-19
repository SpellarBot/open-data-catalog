# Budget - 2013 Budget Ordinance - Positions and Salaries

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/budget-2013-budget-ordinance-positions-and-salaries-37c9e) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/78az-bt2s) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/78az-bt2s/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/78az-bt2s/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | 78az-bt2s |
| Name | Budget - 2013 Budget Ordinance - Positions and Salaries |
| Attribution | City of Chicago |
| Category | Administration & Finance |
| Tags | budget, 2013 |
| Created | 2012-11-29T16:39:20Z |
| Publication Date | 2012-11-29T16:50:40Z |

## Description

The Annual Appropriation Ordinance is the final City operating budget as approved by the City Council. It reflects the City?s operating budget at the beginning of the fiscal year on January 1, 2013.This dataset displays the positions and related salaries detailed in the budget as of January 1. It is extracted from the personnel portion of the Appropriation Ordinance. The dataset presents the position titles (without names) and salaries described in the budget, but does not provide a reflection of the current city workforce with full names and salaries. Disclaimer: the ?Total Budgeted Units? column displays either A) the number of employees AND vacancies associated with a given position, or B) the number of budgeted units (ie. hours/months) for that position. ?Position Control? determines whether Total Budgeted Units column will count employees and vacancies or hours/months. If a Position Control is 1, then employees and vacancies are displayed; if a Position Control is 0, then the total number of hours/months recorded is displayed. Owner: Budget and Management. Frequency: Data is updated annually. For information on the current city workforce, with names, positions and salaries, visit the "Current Employee Names, Salaries, and Position Titles" dataset: http://j.mp/iutKlR.

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| Yes      | series tag     | fund_type               | FUND TYPE               | text      | text        |
| Yes      | series tag     | fund_code               | FUND CODE               | text      | text        |
| Yes      | series tag     | fund_description        | FUND DESCRIPTION        | text      | text        |
| Yes      | series tag     | department_code         | DEPARTMENT CODE         | text      | number      |
| Yes      | series tag     | department_description  | DEPARTMENT DESCRIPTION  | text      | text        |
| Yes      | series tag     | organization_code       | ORGANIZATION CODE       | text      | number      |
| Yes      | series tag     | division_code           | DIVISION CODE           | text      | number      |
| Yes      | series tag     | division_description    | DIVISION DESCRIPTION    | text      | text        |
| Yes      | series tag     | section_code            | SECTION CODE            | text      | number      |
| Yes      | series tag     | section_description     | SECTION DESCRIPTION     | text      | text        |
| Yes      | series tag     | sub_section_code        | SUB-SECTION CODE        | text      | number      |
| Yes      | series tag     | sub_section_description | SUB-SECTION DESCRIPTION | text      | text        |
| Yes      | series tag     | schedule_grade          | SCHEDULE / GRADE        | text      | text        |
| Yes      | numeric metric | bargaining_unit         | BARGAINING UNIT         | number    | number      |
| Yes      | series tag     | title_code              | TITLE CODE              | text      | text        |
| Yes      | series tag     | title_description       | TITLE DESCRIPTION       | text      | text        |
| Yes      | series tag     | budgeted_unit           | BUDGETED UNIT           | text      | text        |
| Yes      | numeric metric | total_budgeted_unit     | TOTAL BUDGETED UNIT     | number    | number      |
| Yes      | numeric metric | position_control        | POSITION CONTROL        | number    | number      |
| Yes      | numeric metric | budgeted_pay_rate       | BUDGETED PAY RATE       | money     | money       |
| Yes      | numeric metric | total_budgeted_amount   | TOTAL BUDGETED AMOUNT   | money     | money       |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:78az-bt2s d:2013-01-01T00:00:00.000Z t:fund_code=100 t:fund_type=Local t:division_code=2005 t:organization_code=1005 t:budgeted_unit=Annual t:section_code=3225 t:fund_description="CORPORATE FUND" t:department_description=DOIT t:schedule_grade="1 00" t:division_description=DOIT t:title_code=9777 t:section_description=GIS t:title_description="IT Director (DoIT)" t:department_code=6 t:sub_section_code=0 m:total_budgeted_amount=93912 m:position_control=1 m:total_budgeted_unit=1 m:budgeted_pay_rate=93912 m:bargaining_unit=9

series e:78az-bt2s d:2013-01-01T00:00:00.000Z t:fund_code=100 t:fund_type=Local t:division_code=2005 t:organization_code=1005 t:budgeted_unit=Annual t:section_code=3225 t:fund_description="CORPORATE FUND" t:department_description=DOIT t:schedule_grade="BX 15" t:division_description=DOIT t:title_code=653 t:section_description=GIS t:title_description="Web Author" t:department_code=6 t:sub_section_code=0 m:total_budgeted_amount=84780 m:position_control=1 m:total_budgeted_unit=1 m:budgeted_pay_rate=84780 m:bargaining_unit=10

series e:78az-bt2s d:2013-01-01T00:00:00.000Z t:fund_code=100 t:fund_type=Local t:division_code=2005 t:organization_code=1005 t:budgeted_unit=Annual t:section_code=3225 t:fund_description="CORPORATE FUND" t:department_description=DOIT t:schedule_grade="3 00" t:division_description=DOIT t:title_code=648 t:section_description=GIS t:title_description="Web Developer" t:department_code=6 t:sub_section_code=0 m:total_budgeted_amount=79464 m:position_control=1 m:total_budgeted_unit=1 m:budgeted_pay_rate=79464 m:bargaining_unit=10
```

## Meta Commands

```ls
metric m:bargaining_unit p:integer l:"BARGAINING UNIT" t:dataTypeName=number

metric m:total_budgeted_unit p:integer l:"TOTAL BUDGETED UNIT" t:dataTypeName=number

metric m:position_control p:integer l:"POSITION CONTROL" t:dataTypeName=number

metric m:budgeted_pay_rate p:integer l:"BUDGETED PAY RATE" t:dataTypeName=money

metric m:total_budgeted_amount p:integer l:"TOTAL BUDGETED AMOUNT" t:dataTypeName=money

entity e:78az-bt2s l:"Budget - 2013 Budget Ordinance - Positions and Salaries" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/78az-bt2s

property e:78az-bt2s t:meta.view v:id=78az-bt2s v:category="Administration & Finance" v:attributionLink=http://author.cityofchicago.org/content/city/en/depts/obm/provdrs/city_budg/svcs/budget_documents.html v:averageRating=0 v:name="Budget - 2013 Budget Ordinance - Positions and Salaries" v:attribution="City of Chicago"

property e:78az-bt2s t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:78az-bt2s t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| fund_type | fund_code | fund_description | department_code | department_description | organization_code | division_code | division_description | section_code | section_description | sub_section_code | sub_section_description | schedule_grade | bargaining_unit | title_code | title_description        | budgeted_unit | total_budgeted_unit | position_control | budgeted_pay_rate | total_budgeted_amount | 
| ========= | ========= | ================ | =============== | ====================== | ================= | ============= | ==================== | ============ | =================== | ================ | ======================= | ============== | =============== | ========== | ======================== | ============= | =================== | ================ | ================= | ===================== | 
| Local     | 100       | CORPORATE FUND   | 6               | DOIT                   | 1005              | 2005          | DOIT                 | 3225         | GIS                 | 0                |                         | 1 00           | 9               | 9777       | IT Director (DoIT)       | Annual        | 1                   | 1                | 93912             | 93912                 | 
| Local     | 100       | CORPORATE FUND   | 6               | DOIT                   | 1005              | 2005          | DOIT                 | 3225         | GIS                 | 0                |                         | BX 15          | 10              | 653        | Web Author               | Annual        | 1                   | 1                | 84780             | 84780                 | 
| Local     | 100       | CORPORATE FUND   | 6               | DOIT                   | 1005              | 2005          | DOIT                 | 3225         | GIS                 | 0                |                         | 3 00           | 10              | 648        | Web Developer            | Annual        | 1                   | 1                | 79464             | 79464                 | 
| Local     | 100       | CORPORATE FUND   | 56              | IPRA                   | 1005              | 2005          | IPRA                 | 3005         | Administration      | 0                |                         | B 10           | 1               | 431        | Clerk IV                 | Annual        | 1                   | 1                | 63456             | 63456                 | 
| Local     | 100       | CORPORATE FUND   | 56              | IPRA                   | 1005              | 2005          | IPRA                 | 3010         | Investigations      | 0                |                         | B 13           | 1               | 1617       | Paralegal II             | Annual        | 1                   | 1                | 49788             | 49788                 | 
| CDBG      | 0K39      | CDBG             | 31              | DEPARTMENT OF LAW      | 1005              | 2515          | CODE ENFORCEMENT     | 3515         | Code Enforcement    | 0                |                         | B 09           | 1               | 1692       | Court File Clerk         | Annual        | 1                   | 1                | 55212             | 55212                 | 
| Local     | 100       | CORPORATE FUND   | 1               | OFFICE OF THE MAYOR    | 1005              | 2005          | OFFICE OF THE MAYOR  | 3010         | Administrative      | 0                |                         | 1 00           | 9               | 9876       | Scheduler                | Annual        | 1                   | 1                | 50004             | 50004                 | 
| Local     | 100       | CORPORATE FUND   | 1               | OFFICE OF THE MAYOR    | 1005              | 2005          | OFFICE OF THE MAYOR  | 3005         | Executive           | 0                |                         | 1 00           | 9               | 9901       | Mayor                    | Annual        | 1                   | 1                | 216210            | 216210                | 
| Local     | 100       | CORPORATE FUND   | 1               | OFFICE OF THE MAYOR    | 1005              | 2005          | OFFICE OF THE MAYOR  | 3005         | Executive           | 0                |                         | 1 00           | 0               | 9637       | Administrative Assistant | Annual        | 1                   | 1                | 48000             | 48000                 | 
| Local     | 100       | CORPORATE FUND   | 1               | OFFICE OF THE MAYOR    | 1005              | 2005          | OFFICE OF THE MAYOR  | 3005         | Executive           | 0                |                         | 1 00           | 0               | 9637       | Administrative Assistant | Annual        | 1                   | 1                | 44004             | 44004                 | 
```