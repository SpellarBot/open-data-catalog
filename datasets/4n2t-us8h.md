# Budget - 2012 Budget Ordinance - Positions and Salaries

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/budget-2012-budget-ordinance-positions-and-salaries-7a631) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/4n2t-us8h) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/4n2t-us8h/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/4n2t-us8h/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | 4n2t-us8h |
| Name | Budget - 2012 Budget Ordinance - Positions and Salaries |
| Attribution | City of Chicago |
| Category | Administration & Finance |
| Tags | budget, personnel, 2012 |
| Created | 2011-11-17T23:24:17Z |
| Publication Date | 2011-12-23T04:44:41Z |

## Description

The Annual Appropriation Ordinance is the final City operating budget as approved by the City Council. It reflects the City?s operating budget at the beginning of the fiscal year on January 1, 2012.This dataset displays the positions and related salaries detailed in the budget as of January 1. It is extracted from the personnel portion of the Appropriation Ordinance. The dataset presents the position titles (without names) and salaries described in the budget, but does not provide a reflection of the current city workforce with full names and salaries. Disclaimer: the ?Total Budgeted Units? column displays either A) the number of employees AND vacancies associated with a given position, or B) the number of budgeted units (ie. hours/months) for that position. ?Position Control? determines whether Total Budgeted Units column will count employees and vacancies or hours/months. If a Position Control is 1, then employees and vacancies are displayed; if a Position Control is 0, then the total number of hours/months recorded is displayed. Owner: Budget and Management. Frequency: Data is updated annually. For information on the current city workforce, with names, positions and salaries, visit the "Current Employee Names, Salaries, and Position Titles" dataset: http://j.mp/iutKlR.

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| Yes      | series tag     | fund_type               | FUND TYPE               | text      | text        |
| Yes      | series tag     | fund_code               | FUND CODE               | text      | text        |
| Yes      | series tag     | fund_description        | FUND DESCRIPTION        | text      | text        |
| Yes      | series tag     | department_number       | DEPARTMENT NUMBER       | text      | number      |
| Yes      | series tag     | department_description  | DEPARTMENT DESCRIPTION  | text      | text        |
| Yes      | series tag     | organization_code       | ORGANIZATION CODE       | text      | number      |
| Yes      | series tag     | division_code           | DIVISION CODE           | text      | number      |
| Yes      | series tag     | division_description    | DIVISION DESCRIPTION    | text      | text        |
| Yes      | series tag     | section_code            | SECTION CODE            | text      | number      |
| Yes      | series tag     | section_description     | SECTION DESCRIPTION     | text      | text        |
| Yes      | series tag     | sub_section_code        | SUB-SECTION CODE        | text      | number      |
| Yes      | series tag     | sub_section_description | SUB-SECTION DESCRIPTION | text      | text        |
| Yes      | series tag     | schedule_grade          | SCHEDULE/GRADE          | text      | text        |
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
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:4n2t-us8h d:2012-01-01T00:00:00.000Z t:fund_code=100 t:fund_type=Local t:division_code=2005 t:organization_code=1005 t:budgeted_unit=Annual t:section_code=3005 t:fund_description="CORPORATE FUND" t:department_description="OFFICE OF THE MAYOR" t:schedule_grade=100 t:division_description="OFFICE OF THE MAYOR" t:title_code=9901 t:department_number=1 t:section_description="3005 Executive" t:title_description=Mayor t:sub_section_code=0 m:total_budgeted_amount=216210 m:position_control=1 m:total_budgeted_unit=1 m:budgeted_pay_rate=216210 m:bargaining_unit=9

series e:4n2t-us8h d:2012-01-01T00:00:00.000Z t:fund_code=100 t:fund_type=Local t:division_code=2005 t:organization_code=1005 t:budgeted_unit=Annual t:section_code=3005 t:fund_description="CORPORATE FUND" t:department_description="OFFICE OF THE MAYOR" t:schedule_grade=100 t:division_description="OFFICE OF THE MAYOR" t:title_code=9637 t:department_number=1 t:section_description="3005 Executive" t:title_description="Administrative Assistant" t:sub_section_code=0 m:total_budgeted_amount=88008 m:position_control=1 m:total_budgeted_unit=2 m:budgeted_pay_rate=44004 m:bargaining_unit=0

series e:4n2t-us8h d:2012-01-01T00:00:00.000Z t:fund_code=100 t:fund_type=Local t:division_code=2005 t:organization_code=1005 t:budgeted_unit=Annual t:section_code=3005 t:fund_description="CORPORATE FUND" t:department_description="OFFICE OF THE MAYOR" t:schedule_grade=0 t:division_description="OFFICE OF THE MAYOR" t:title_code=9617 t:department_number=1 t:section_description="3005 Executive" t:title_description="Administrative Secretary" t:sub_section_code=0 m:total_budgeted_amount=74988 m:position_control=1 m:total_budgeted_unit=1 m:budgeted_pay_rate=74988 m:bargaining_unit=9
```

## Meta Commands

```ls
metric m:bargaining_unit p:integer l:"BARGAINING UNIT" t:dataTypeName=number

metric m:total_budgeted_unit p:integer l:"TOTAL BUDGETED UNIT" t:dataTypeName=number

metric m:position_control p:integer l:"POSITION CONTROL" t:dataTypeName=number

metric m:budgeted_pay_rate p:double l:"BUDGETED PAY RATE" t:dataTypeName=money

metric m:total_budgeted_amount p:integer l:"TOTAL BUDGETED AMOUNT" t:dataTypeName=money

entity e:4n2t-us8h l:"Budget - 2012 Budget Ordinance - Positions and Salaries" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/4n2t-us8h

property e:4n2t-us8h t:meta.view v:id=4n2t-us8h v:category="Administration & Finance" v:attributionLink=http://www.cityofchicago.org/city/en/depts/obm/provdrs/city_budg.html v:averageRating=0 v:name="Budget - 2012 Budget Ordinance - Positions and Salaries" v:attribution="City of Chicago"

property e:4n2t-us8h t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:4n2t-us8h t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| fund_type | fund_code | fund_description | department_number | department_description | organization_code | division_code | division_description | section_code | section_description | sub_section_code | sub_section_description | schedule_grade | bargaining_unit | title_code | title_description                               | budgeted_unit | total_budgeted_unit | position_control | budgeted_pay_rate | total_budgeted_amount | 
| ========= | ========= | ================ | ================= | ====================== | ================= | ============= | ==================== | ============ | =================== | ================ | ======================= | ============== | =============== | ========== | =============================================== | ============= | =================== | ================ | ================= | ===================== | 
| Local     | 100       | CORPORATE FUND   | 1                 | OFFICE OF THE MAYOR    | 1005              | 2005          | OFFICE OF THE MAYOR  | 3005         | 3005 Executive      | 0                |                         | 100            | 9               | 9901       | Mayor                                           | Annual        | 1                   | 1                | 216210.00         | 216210                | 
| Local     | 100       | CORPORATE FUND   | 1                 | OFFICE OF THE MAYOR    | 1005              | 2005          | OFFICE OF THE MAYOR  | 3005         | 3005 Executive      | 0                |                         | 100            | 0               | 9637       | Administrative Assistant                        | Annual        | 2                   | 1                | 44004.00          | 88008                 | 
| Local     | 100       | CORPORATE FUND   | 1                 | OFFICE OF THE MAYOR    | 1005              | 2005          | OFFICE OF THE MAYOR  | 3005         | 3005 Executive      | 0                |                         | 0              | 9               | 9617       | Administrative Secretary                        | Annual        | 1                   | 1                | 74988.00          | 74988                 | 
| Local     | 100       | CORPORATE FUND   | 1                 | OFFICE OF THE MAYOR    | 1005              | 2005          | OFFICE OF THE MAYOR  | 3010         | 3010 Administrative | 0                |                         | 100            | 9               | 9899       | Chief of Staff                                  | Annual        | 1                   | 1                | 174996.00         | 174996                | 
| Local     | 100       | CORPORATE FUND   | 1                 | OFFICE OF THE MAYOR    | 1005              | 2005          | OFFICE OF THE MAYOR  | 3010         | 3010 Administrative | 0                |                         | 100            | 9               | 9898       | Deputy Chief of Staff                           | Annual        | 1                   | 1                | 144996.00         | 144996                | 
| Local     | 100       | CORPORATE FUND   | 1                 | OFFICE OF THE MAYOR    | 1005              | 2005          | OFFICE OF THE MAYOR  | 3010         | 3010 Administrative | 0                |                         | 100            | 9               | 9898       | Deputy Chief of Staff                           | Annual        | 1                   | 1                | 120000.00         | 120000                | 
| Local     | 100       | CORPORATE FUND   | 1                 | OFFICE OF THE MAYOR    | 1005              | 2005          | OFFICE OF THE MAYOR  | 3010         | 3010 Administrative | 0                |                         | 100            | 9               | 9896       | Chief Financial Officer                         | Annual        | 1                   | 1                | 169992.00         | 169992                | 
| Local     | 100       | CORPORATE FUND   | 1                 | OFFICE OF THE MAYOR    | 1005              | 2005          | OFFICE OF THE MAYOR  | 3010         | 3010 Administrative | 0                |                         | 100            | 9               | 9891       | Administrative Assistant - Office Administrator | Annual        | 1                   | 1                | 83100.00          | 83100                 | 
| Local     | 100       | CORPORATE FUND   | 1                 | OFFICE OF THE MAYOR    | 1005              | 2005          | OFFICE OF THE MAYOR  | 3010         | 3010 Administrative | 0                |                         | 100            | 9               | 9889       | First Deputy Chief of Staff                     | Annual        | 1                   | 1                | 154992.00         | 154992                | 
| Local     | 100       | CORPORATE FUND   | 1                 | OFFICE OF THE MAYOR    | 1005              | 2005          | OFFICE OF THE MAYOR  | 3010         | 3010 Administrative | 0                |                         | 100            | 9               | 9883       | Assistant Administrative Secretary III          | Annual        | 1                   | 1                | 90000.00          | 90000                 | 
```