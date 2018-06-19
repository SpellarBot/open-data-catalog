# Budget - 2016 Budget Ordinance - Positions and Salaries

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/budget-2016-budget-ordinance-positions-and-salaries) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/ipsp-k4xh) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/ipsp-k4xh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/ipsp-k4xh/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | ipsp-k4xh |
| Name | Budget - 2016 Budget Ordinance - Positions and Salaries |
| Attribution | City of Chicago |
| Category | Administration & Finance |
| Tags | budget, 2016 |
| Created | 2015-10-29T20:30:40Z |
| Publication Date | 2015-10-29T20:44:47Z |

## Description

The Annual Appropriation Ordinance is the final City operating budget as approved by the City Council. It reflects the City?s operating budget at the beginning of the fiscal year on January 1, 2016.This dataset displays the positions and related salaries detailed in the budget as of January 1. It is extracted from the personnel portion of the Appropriation Ordinance. The dataset presents the position titles (without names) and salaries described in the budget, but does not provide a reflection of the current city workforce with full names and salaries. Disclaimer: the ?Total Budgeted Units? column displays either A) the number of employees AND vacancies associated with a given position, or B) the number of budgeted units (ie. hours/months) for that position. ?Position Control? determines whether Total Budgeted Units column will count employees and vacancies or hours/months. If a Position Control is 1, then employees and vacancies are displayed; if a Position Control is 0, then the total number of hours/months recorded is displayed. For information on the current city workforce, with names, positions and salaries, visit the "Current Employee Names, Salaries, and Position Titles" dataset: https://data.cityofchicago.org/id/xzkq-xp2w.

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type | Render Type |
| ======== | ============== | ======================== | ======================== | ========= | =========== |
| Yes      | series tag     | fund_type                | FUND TYPE                | text      | text        |
| Yes      | series tag     | department_code          | DEPARTMENT CODE          | text      | number      |
| Yes      | series tag     | department_description   | DEPARTMENT DESCRIPTION   | text      | text        |
| Yes      | series tag     | fund_code                | FUND CODE                | text      | text        |
| Yes      | series tag     | fund_description         | FUND DESCRIPTION         | text      | text        |
| Yes      | series tag     | organization_code        | ORGANIZATION CODE        | text      | number      |
| Yes      | series tag     | organization_description | ORGANIZATION DESCRIPTION | text      | text        |
| Yes      | series tag     | division_code            | DIVISION CODE            | text      | number      |
| Yes      | series tag     | division_description     | DIVISION DESCRIPTION     | text      | text        |
| Yes      | series tag     | section_code             | SECTION CODE             | text      | number      |
| Yes      | series tag     | section_description      | SECTION DESCRIPTION      | text      | text        |
| Yes      | series tag     | sub_section_code         | SUB-SECTION CODE         | text      | number      |
| Yes      | series tag     | sub_section_description  | SUB-SECTION DESCRIPTION  | text      | text        |
| Yes      | series tag     | schedule_grade           | SCHEDULE / GRADE         | text      | text        |
| Yes      | numeric metric | bargaining_unit          | BARGAINING UNIT          | number    | number      |
| Yes      | series tag     | title_code               | TITLE CODE               | text      | text        |
| Yes      | series tag     | title_description        | TITLE DESCRIPTION        | text      | text        |
| Yes      | series tag     | budgeted_unit            | BUDGETED UNIT            | text      | text        |
| Yes      | numeric metric | total_budgeted_unit      | TOTAL BUDGETED UNIT      | number    | number      |
| Yes      | numeric metric | position_control         | POSITION CONTROL         | number    | number      |
| Yes      | numeric metric | budgeted_pay_rate        | BUDGETED PAY RATE        | money     | money       |
| Yes      | numeric metric | total_budgeted_amount    | TOTAL BUDGETED AMOUNT    | money     | money       |
```

## Time Field

```ls
Value = 2016
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ipsp-k4xh d:2016-01-01T00:00:00.000Z t:fund_code=0100 t:fund_type=Local t:division_code=2005 t:organization_code=1005 t:budgeted_unit=Annual t:section_code=3005 t:fund_description="CORPORATE FUND" t:department_description="OFFICE OF THE MAYOR" t:organization_description="OFFICE OF THE MAYOR" t:schedule_grade="1 00" t:division_description="OFFICE OF THE MAYOR" t:title_code=9901 t:section_description=Executive t:title_description=Mayor t:department_code=1 t:sub_section_code=0 m:total_budgeted_amount=216210 m:position_control=1 m:total_budgeted_unit=1 m:budgeted_pay_rate=216210 m:bargaining_unit=9

series e:ipsp-k4xh d:2016-01-01T00:00:00.000Z t:fund_code=0100 t:fund_type=Local t:division_code=2005 t:organization_code=1005 t:budgeted_unit=Annual t:section_code=3005 t:fund_description="CORPORATE FUND" t:department_description="OFFICE OF THE MAYOR" t:organization_description="OFFICE OF THE MAYOR" t:schedule_grade="1 00" t:division_description="OFFICE OF THE MAYOR" t:title_code=9637 t:section_description=Executive t:title_description="Administrative Assistant" t:department_code=1 t:sub_section_code=0 m:total_budgeted_amount=62004 m:position_control=1 m:total_budgeted_unit=1 m:budgeted_pay_rate=62004 m:bargaining_unit=0

series e:ipsp-k4xh d:2016-01-01T00:00:00.000Z t:fund_code=0100 t:fund_type=Local t:division_code=2005 t:organization_code=1005 t:budgeted_unit=Annual t:section_code=3005 t:fund_description="CORPORATE FUND" t:department_description="OFFICE OF THE MAYOR" t:organization_description="OFFICE OF THE MAYOR" t:schedule_grade="1 00" t:division_description="OFFICE OF THE MAYOR" t:title_code=9637 t:section_description=Executive t:title_description="Administrative Assistant" t:department_code=1 t:sub_section_code=0 m:total_budgeted_amount=50004 m:position_control=1 m:total_budgeted_unit=1 m:budgeted_pay_rate=50004 m:bargaining_unit=0
```

## Meta Commands

```ls
metric m:bargaining_unit p:integer l:"BARGAINING UNIT" t:dataTypeName=number

metric m:total_budgeted_unit p:integer l:"TOTAL BUDGETED UNIT" t:dataTypeName=number

metric m:position_control p:integer l:"POSITION CONTROL" t:dataTypeName=number

metric m:budgeted_pay_rate p:integer l:"BUDGETED PAY RATE" t:dataTypeName=money

metric m:total_budgeted_amount p:integer l:"TOTAL BUDGETED AMOUNT" t:dataTypeName=money

entity e:ipsp-k4xh l:"Budget - 2016 Budget Ordinance - Positions and Salaries" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/ipsp-k4xh

property e:ipsp-k4xh t:meta.view v:id=ipsp-k4xh v:category="Administration & Finance" v:attributionLink=http://www.cityofchicago.org/city/en/depts/obm/provdrs/city_budg/svcs/budget_documents.html v:averageRating=0 v:name="Budget - 2016 Budget Ordinance - Positions and Salaries" v:attribution="City of Chicago"

property e:ipsp-k4xh t:meta.view.owner v:id=vewm-vupz v:screenName="Jonathan Levy" v:displayName="Jonathan Levy"

property e:ipsp-k4xh t:meta.view.tableauthor v:id=vewm-vupz v:screenName="Jonathan Levy" v:roleName=administrator v:displayName="Jonathan Levy"
```

## Top Records

```ls
| fund_type | department_code | department_description | fund_code | fund_description | organization_code | organization_description | division_code | division_description | section_code | section_description | sub_section_code | sub_section_description | schedule_grade | bargaining_unit | title_code | title_description                               | budgeted_unit | total_budgeted_unit | position_control | budgeted_pay_rate | total_budgeted_amount | 
| ========= | =============== | ====================== | ========= | ================ | ================= | ======================== | ============= | ==================== | ============ | =================== | ================ | ======================= | ============== | =============== | ========== | =============================================== | ============= | =================== | ================ | ================= | ===================== | 
| Local     | 1               | OFFICE OF THE MAYOR    | 0100      | CORPORATE FUND   | 1005              | OFFICE OF THE MAYOR      | 2005          | OFFICE OF THE MAYOR  | 3005         | Executive           | 0                |                         | 1 00           | 9               | 9901       | Mayor                                           | Annual        | 1                   | 1                | 216210            | 216210                | 
| Local     | 1               | OFFICE OF THE MAYOR    | 0100      | CORPORATE FUND   | 1005              | OFFICE OF THE MAYOR      | 2005          | OFFICE OF THE MAYOR  | 3005         | Executive           | 0                |                         | 1 00           | 0               | 9637       | Administrative Assistant                        | Annual        | 1                   | 1                | 62004             | 62004                 | 
| Local     | 1               | OFFICE OF THE MAYOR    | 0100      | CORPORATE FUND   | 1005              | OFFICE OF THE MAYOR      | 2005          | OFFICE OF THE MAYOR  | 3005         | Executive           | 0                |                         | 1 00           | 0               | 9637       | Administrative Assistant                        | Annual        | 1                   | 1                | 50004             | 50004                 | 
| Local     | 1               | OFFICE OF THE MAYOR    | 0100      | CORPORATE FUND   | 1005              | OFFICE OF THE MAYOR      | 2005          | OFFICE OF THE MAYOR  | 3005         | Executive           | 0                |                         | 1 00           | 9               | 9617       | Administrative Secretary                        | Annual        | 1                   | 1                | 82500             | 82500                 | 
| Local     | 1               | OFFICE OF THE MAYOR    | 0100      | CORPORATE FUND   | 1005              | OFFICE OF THE MAYOR      | 2005          | OFFICE OF THE MAYOR  | 3010         | Administrative      | 0                |                         | 1 00           | 9               | 9899       | Chief of Staff                                  | Annual        | 1                   | 1                | 195000            | 195000                | 
| Local     | 1               | OFFICE OF THE MAYOR    | 0100      | CORPORATE FUND   | 1005              | OFFICE OF THE MAYOR      | 2005          | OFFICE OF THE MAYOR  | 3010         | Administrative      | 0                |                         | 1 00           | 9               | 9898       | Deputy Chief of Staff                           | Annual        | 1                   | 1                | 154992            | 154992                | 
| Local     | 1               | OFFICE OF THE MAYOR    | 0100      | CORPORATE FUND   | 1005              | OFFICE OF THE MAYOR      | 2005          | OFFICE OF THE MAYOR  | 3010         | Administrative      | 0                |                         | 1 00           | 9               | 9898       | Deputy Chief of Staff                           | Annual        | 1                   | 1                | 150000            | 150000                | 
| Local     | 1               | OFFICE OF THE MAYOR    | 0100      | CORPORATE FUND   | 1005              | OFFICE OF THE MAYOR      | 2005          | OFFICE OF THE MAYOR  | 3010         | Administrative      | 0                |                         | 1 00           | 9               | 9898       | Deputy Chief of Staff                           | Annual        | 1                   | 1                | 120000            | 120000                | 
| Local     | 1               | OFFICE OF THE MAYOR    | 0100      | CORPORATE FUND   | 1005              | OFFICE OF THE MAYOR      | 2005          | OFFICE OF THE MAYOR  | 3010         | Administrative      | 0                |                         | 1 00           | 9               | 9896       | Chief Financial Officer                         | Annual        | 1                   | 1                | 169992            | 169992                | 
| Local     | 1               | OFFICE OF THE MAYOR    | 0100      | CORPORATE FUND   | 1005              | OFFICE OF THE MAYOR      | 2005          | OFFICE OF THE MAYOR  | 3010         | Administrative      | 0                |                         | 1 00           | 9               | 9891       | Administrative Assistant - Office Administrator | Annual        | 1                   | 1                | 85596             | 85596                 | 
```