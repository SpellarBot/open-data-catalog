# Budget - 2012 Budget Recommendations - Positions and Salaries

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/budget-2012-budget-recommendations-positions-and-salaries-ebc4f) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/rdd7-bjqm) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/rdd7-bjqm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/rdd7-bjqm/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | rdd7-bjqm |
| Name | Budget - 2012 Budget Recommendations - Positions and Salaries |
| Attribution | City of Chicago |
| Category | Administration & Finance |
| Tags | budget, personnel, 2012 |
| Created | 2011-10-11T22:38:34Z |
| Publication Date | 2011-10-13T21:37:25Z |

## Description

This dataset includes recommended positions and salaries for 2012 by title (without names) and salary. The dataset is excerpted from the 2012 Budget Recommendations, which is the line-item budget proposed by the Mayor to the City Council for approval. Disclaimer: the ?Total Budgeted Units? column displays either A) the number of employees AND vacancies associated with a given position, or B) the number of budgeted units (ie. hours/months) for that position. ?Position Control? determines whether Total Budgeted Units column will count employees and vacancies or hours/months. If a Position Control is 1, then employees and vacancies are displayed; if a Position Control is 0, then the total number of hours/months recorded is displayed. Owner: Budget and Management. Frequency: Data is updated annually. For more information about the budget process, visit the Budget Documents page: http://j.mp/lPotWf.

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| Yes      | series tag     | fund_type               | FUND TYPE               | text      | text        |
| Yes      | series tag     | department_code         | DEPARTMENT CODE         | text      | number      |
| Yes      | series tag     | department_description  | DEPARTMENT DESCRIPTION  | text      | text        |
| Yes      | series tag     | fund_code               | FUND CODE               | text      | text        |
| Yes      | series tag     | fund_description        | FUND DESCRIPTION        | text      | text        |
| Yes      | series tag     | organization_code       | ORGANIZATION CODE       | text      | number      |
| Yes      | series tag     | division_code           | DIVISION CODE           | text      | number      |
| Yes      | series tag     | division_description    | DIVISION DESCRIPTION    | text      | text        |
| Yes      | series tag     | section_code            | SECTION CODE            | text      | number      |
| Yes      | series tag     | section_description     | SECTION DESCRIPTION     | text      | text        |
| Yes      | series tag     | sub_section_code        | SUB-SECTION CODE        | text      | number      |
| Yes      | series tag     | sub_section_description | SUB-SECTION DESCRIPTION | text      | text        |
| Yes      | series tag     | schedule_grade          | SCHEDULE/GRADE          | text      | text        |
| Yes      | numeric metric | bargaining_unit         | BARGAINING UNIT         | number    | number      |
| Yes      | series tag     | title_code              | TITLE CODE              | text      | number      |
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
series e:rdd7-bjqm d:2012-01-01T00:00:00.000Z t:fund_code=100 t:fund_type=LOCAL t:division_code=2005 t:organization_code=1005 t:budgeted_unit=Annual t:section_code=3005 t:fund_description="CORPORATE FUND" t:department_description="OFFICE OF THE MAYOR" t:schedule_grade="1 0" t:division_description="OFFICE OF THE MAYOR" t:title_code=9901 t:section_description=Executive t:title_description=Mayor t:department_code=1 t:sub_section_code=0 m:total_budgeted_amount=216210 m:position_control=1 m:total_budgeted_unit=1 m:budgeted_pay_rate=216210 m:bargaining_unit=9

series e:rdd7-bjqm d:2012-01-01T00:00:00.000Z t:fund_code=100 t:fund_type=LOCAL t:division_code=2005 t:organization_code=1005 t:budgeted_unit=Annual t:section_code=3005 t:fund_description="CORPORATE FUND" t:department_description="OFFICE OF THE MAYOR" t:schedule_grade="1 0" t:division_description="OFFICE OF THE MAYOR" t:title_code=9637 t:section_description=Executive t:title_description="Administrative Assistant" t:department_code=1 t:sub_section_code=0 m:total_budgeted_amount=88008 m:position_control=1 m:total_budgeted_unit=2 m:budgeted_pay_rate=44004 m:bargaining_unit=0

series e:rdd7-bjqm d:2012-01-01T00:00:00.000Z t:fund_code=100 t:fund_type=LOCAL t:division_code=2005 t:organization_code=1005 t:budgeted_unit=Annual t:section_code=3005 t:fund_description="CORPORATE FUND" t:department_description="OFFICE OF THE MAYOR" t:schedule_grade="1 0" t:division_description="OFFICE OF THE MAYOR" t:title_code=9617 t:section_description=Executive t:title_description="Administrative Secretary" t:department_code=1 t:sub_section_code=0 m:total_budgeted_amount=74988 m:position_control=1 m:total_budgeted_unit=1 m:budgeted_pay_rate=74988 m:bargaining_unit=9
```

## Meta Commands

```ls
metric m:bargaining_unit p:integer l:"BARGAINING UNIT" t:dataTypeName=number

metric m:total_budgeted_unit p:integer l:"TOTAL BUDGETED UNIT" t:dataTypeName=number

metric m:position_control p:integer l:"POSITION CONTROL" t:dataTypeName=number

metric m:budgeted_pay_rate p:double l:"BUDGETED PAY RATE" t:dataTypeName=money

metric m:total_budgeted_amount p:double l:"TOTAL BUDGETED AMOUNT" t:dataTypeName=money

entity e:rdd7-bjqm l:"Budget - 2012 Budget Recommendations - Positions and Salaries" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/rdd7-bjqm

property e:rdd7-bjqm t:meta.view v:id=rdd7-bjqm v:category="Administration & Finance" v:attributionLink=http://www.cityofchicago.org/budget v:averageRating=0 v:name="Budget - 2012 Budget Recommendations - Positions and Salaries" v:attribution="City of Chicago"

property e:rdd7-bjqm t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:rdd7-bjqm t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| fund_type | department_code | department_description | fund_code | fund_description | organization_code | division_code | division_description | section_code | section_description | sub_section_code | sub_section_description | schedule_grade | bargaining_unit | title_code | title_description                               | budgeted_unit | total_budgeted_unit | position_control | budgeted_pay_rate | total_budgeted_amount | 
| ========= | =============== | ====================== | ========= | ================ | ================= | ============= | ==================== | ============ | =================== | ================ | ======================= | ============== | =============== | ========== | =============================================== | ============= | =================== | ================ | ================= | ===================== | 
| LOCAL     | 1               | OFFICE OF THE MAYOR    | 100       | CORPORATE FUND   | 1005              | 2005          | OFFICE OF THE MAYOR  | 3005         | Executive           | 0                |                         | 1 0            | 9               | 9901       | Mayor                                           | Annual        | 1                   | 1                | 216210.00         | 216210.00             | 
| LOCAL     | 1               | OFFICE OF THE MAYOR    | 100       | CORPORATE FUND   | 1005              | 2005          | OFFICE OF THE MAYOR  | 3005         | Executive           | 0                |                         | 1 0            | 0               | 9637       | Administrative Assistant                        | Annual        | 2                   | 1                | 44004.00          | 88008.00              | 
| LOCAL     | 1               | OFFICE OF THE MAYOR    | 100       | CORPORATE FUND   | 1005              | 2005          | OFFICE OF THE MAYOR  | 3005         | Executive           | 0                |                         | 1 0            | 9               | 9617       | Administrative Secretary                        | Annual        | 1                   | 1                | 74988.00          | 74988.00              | 
| LOCAL     | 1               | OFFICE OF THE MAYOR    | 100       | CORPORATE FUND   | 1005              | 2005          | OFFICE OF THE MAYOR  | 3010         | Administrative      | 0                |                         | 1 0            | 9               | 9899       | Chief of Staff                                  | Annual        | 1                   | 1                | 174996.00         | 174996.00             | 
| LOCAL     | 1               | OFFICE OF THE MAYOR    | 100       | CORPORATE FUND   | 1005              | 2005          | OFFICE OF THE MAYOR  | 3010         | Administrative      | 0                |                         | 1 0            | 9               | 9898       | Deputy Chief of Staff                           | Annual        | 1                   | 1                | 120000.00         | 120000.00             | 
| LOCAL     | 1               | OFFICE OF THE MAYOR    | 100       | CORPORATE FUND   | 1005              | 2005          | OFFICE OF THE MAYOR  | 3010         | Administrative      | 0                |                         | 1 0            | 9               | 9898       | Deputy Chief of Staff                           | Annual        | 1                   | 1                | 144996.00         | 144996.00             | 
| LOCAL     | 1               | OFFICE OF THE MAYOR    | 100       | CORPORATE FUND   | 1005              | 2005          | OFFICE OF THE MAYOR  | 3010         | Administrative      | 0                |                         | 1 0            | 9               | 9896       | Chief Financial Officer                         | Annual        | 1                   | 1                | 169992.00         | 169992.00             | 
| LOCAL     | 1               | OFFICE OF THE MAYOR    | 100       | CORPORATE FUND   | 1005              | 2005          | OFFICE OF THE MAYOR  | 3010         | Administrative      | 0                |                         | 1 0            | 9               | 9891       | Administrative Assistant - Office Administrator | Annual        | 1                   | 1                | 83100.00          | 83100.00              | 
| LOCAL     | 1               | OFFICE OF THE MAYOR    | 100       | CORPORATE FUND   | 1005              | 2005          | OFFICE OF THE MAYOR  | 3010         | Administrative      | 0                |                         | 1 0            | 9               | 9889       | First Deputy Chief of Staff                     | Annual        | 1                   | 1                | 154992.00         | 154992.00             | 
| LOCAL     | 1               | OFFICE OF THE MAYOR    | 100       | CORPORATE FUND   | 1005              | 2005          | OFFICE OF THE MAYOR  | 3010         | Administrative      | 0                |                         | 1 0            | 9               | 9883       | Assistant Administrative Secretary III          | Annual        | 1                   | 1                | 60000.00          | 60000.00              | 
```