# Budget - 2014 Budget Ordinance - Positions and Salaries

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/budget-2014-budget-ordinance-positions-and-salaries-1c963) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/etzw-ycze) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/etzw-ycze/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/etzw-ycze/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | etzw-ycze |
| Name | Budget - 2014 Budget Ordinance - Positions and Salaries |
| Attribution | City of Chicago |
| Category | Administration & Finance |
| Tags | budget, 2014 |
| Created | 2013-12-03T18:39:50Z |
| Publication Date | 2013-12-05T00:58:32Z |

## Description

The Annual Appropriation Ordinance is the final City operating budget as approved by the City Council. It reflects the City?s operating budget at the beginning of the fiscal year on January 1, 2014.This dataset displays the positions and related salaries detailed in the budget as of January 1. It is extracted from the personnel portion of the Appropriation Ordinance. The dataset presents the position titles (without names) and salaries described in the budget, but does not provide a reflection of the current city workforce with full names and salaries. Disclaimer: the ?Total Budgeted Units? column displays either A) the number of employees AND vacancies associated with a given position, or B) the number of budgeted units (ie. hours/months) for that position. ?Position Control? determines whether Total Budgeted Units column will count employees and vacancies or hours/months. If a Position Control is 1, then employees and vacancies are displayed; if a Position Control is 0, then the total number of hours/months recorded is displayed. Owner: Budget and Management. Frequency: Data are updated annually. For information on the current city workforce, with names, positions and salaries, visit the "Current Employee Names, Salaries, and Position Titles" dataset: https://data.cityofchicago.org/id/xzkq-xp2w.

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
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:etzw-ycze d:2014-01-01T00:00:00.000Z t:fund_code=0K40 t:fund_type=CDBG t:division_code=2505 t:organization_code=1005 t:budgeted_unit=Annual t:section_code=3505 t:fund_description=CDBG t:department_description="OFFICE OF BUDGET & MANAGEMENT" t:organization_description="OFFICE OF BUDGET & MANAGEMENT" t:schedule_grade="BX 17" t:division_description="ADMINISTRATION AND MONITORING" t:title_code=1981 t:section_description="Administration and Monitoring" t:title_description="Coordinator of Economic Development" t:department_code=5 t:sub_section_code=0 m:total_budgeted_amount=84780 m:position_control=1 m:total_budgeted_unit=1 m:budgeted_pay_rate=84780 m:bargaining_unit=10

series e:etzw-ycze d:2014-01-01T00:00:00.000Z t:fund_code=0K40 t:fund_type=CDBG t:division_code=2505 t:organization_code=1005 t:budgeted_unit=Annual t:section_code=3505 t:fund_description=CDBG t:department_description="OFFICE OF BUDGET & MANAGEMENT" t:organization_description="OFFICE OF BUDGET & MANAGEMENT" t:schedule_grade="BX 15" t:division_description="ADMINISTRATION AND MONITORING" t:title_code=1302 t:section_description="Administration and Monitoring" t:title_description="Administrative Services Officer II" t:department_code=5 t:sub_section_code=0 m:total_budgeted_amount=80916 m:position_control=1 m:total_budgeted_unit=1 m:budgeted_pay_rate=80916 m:bargaining_unit=20

series e:etzw-ycze d:2014-01-01T00:00:00.000Z t:fund_code=0K40 t:fund_type=CDBG t:division_code=2505 t:organization_code=1005 t:budgeted_unit=Annual t:section_code=3505 t:fund_description=CDBG t:department_description="OFFICE OF BUDGET & MANAGEMENT" t:organization_description="OFFICE OF BUDGET & MANAGEMENT" t:schedule_grade="GY 07" t:division_description="ADMINISTRATION AND MONITORING" t:title_code=1105 t:section_description="Administration and Monitoring" t:title_description="Senior Budget Analyst" t:department_code=5 t:sub_section_code=0 m:total_budgeted_amount=80256 m:position_control=1 m:total_budgeted_unit=1 m:budgeted_pay_rate=80256 m:bargaining_unit=20
```

## Meta Commands

```ls
metric m:bargaining_unit p:integer l:"BARGAINING UNIT" t:dataTypeName=number

metric m:total_budgeted_unit p:integer l:"TOTAL BUDGETED UNIT" t:dataTypeName=number

metric m:position_control p:integer l:"POSITION CONTROL" t:dataTypeName=number

metric m:budgeted_pay_rate p:integer l:"BUDGETED PAY RATE" t:dataTypeName=money

metric m:total_budgeted_amount p:integer l:"TOTAL BUDGETED AMOUNT" t:dataTypeName=money

entity e:etzw-ycze l:"Budget - 2014 Budget Ordinance - Positions and Salaries" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/etzw-ycze

property e:etzw-ycze t:meta.view v:id=etzw-ycze v:category="Administration & Finance" v:attributionLink=http://www.cityofchicago.org/city/en/depts/obm/provdrs/city_budg/svcs/budget_documents.html v:averageRating=0 v:name="Budget - 2014 Budget Ordinance - Positions and Salaries" v:attribution="City of Chicago"

property e:etzw-ycze t:meta.view.owner v:id=vewm-vupz v:screenName="Jonathan Levy" v:displayName="Jonathan Levy"

property e:etzw-ycze t:meta.view.tableauthor v:id=vewm-vupz v:screenName="Jonathan Levy" v:roleName=administrator v:displayName="Jonathan Levy"
```

## Top Records

```ls
| fund_type | department_code | department_description        | fund_code | fund_description | organization_code | organization_description      | division_code | division_description           | section_code | section_description           | sub_section_code | sub_section_description                            | schedule_grade | bargaining_unit | title_code | title_description                       | budgeted_unit | total_budgeted_unit | position_control | budgeted_pay_rate | total_budgeted_amount | 
| ========= | =============== | ============================= | ========= | ================ | ================= | ============================= | ============= | ============================== | ============ | ============================= | ================ | ================================================== | ============== | =============== | ========== | ======================================= | ============= | =================== | ================ | ================= | ===================== | 
| CDBG      | 5               | OFFICE OF BUDGET & MANAGEMENT | 0K40      | CDBG             | 1005              | OFFICE OF BUDGET & MANAGEMENT | 2505          | ADMINISTRATION AND MONITORING  | 3505         | Administration and Monitoring | 0                |                                                    | BX 17          | 10              | 1981       | Coordinator of Economic Development     | Annual        | 1                   | 1                | 84780             | 84780                 | 
| CDBG      | 5               | OFFICE OF BUDGET & MANAGEMENT | 0K40      | CDBG             | 1005              | OFFICE OF BUDGET & MANAGEMENT | 2505          | ADMINISTRATION AND MONITORING  | 3505         | Administration and Monitoring | 0                |                                                    | BX 15          | 20              | 1302       | Administrative Services Officer II      | Annual        | 1                   | 1                | 80916             | 80916                 | 
| CDBG      | 5               | OFFICE OF BUDGET & MANAGEMENT | 0K40      | CDBG             | 1005              | OFFICE OF BUDGET & MANAGEMENT | 2505          | ADMINISTRATION AND MONITORING  | 3505         | Administration and Monitoring | 0                |                                                    | GY 07          | 20              | 1105       | Senior Budget Analyst                   | Annual        | 1                   | 1                | 80256             | 80256                 | 
| CDBG      | 5               | OFFICE OF BUDGET & MANAGEMENT | 0K40      | CDBG             | 1005              | OFFICE OF BUDGET & MANAGEMENT | 2505          | ADMINISTRATION AND MONITORING  | 3505         | Administration and Monitoring | 0                |                                                    | BX 13          | 20              | 0366       | Staff Assistant - Excluded              | Annual        | 1                   | 1                | 64152             | 64152                 | 
| CDBG      | 5               | OFFICE OF BUDGET & MANAGEMENT | 0K40      | CDBG             | 1005              | OFFICE OF BUDGET & MANAGEMENT | 2505          | ADMINISTRATION AND MONITORING  | 3505         | Administration and Monitoring | 0                |                                                    | BX 12          | 20              | 0323       | Administrative Assistant III - Excluded | Annual        | 1                   | 1                | 60408             | 60408                 | 
| CDBG      | 5               | OFFICE OF BUDGET & MANAGEMENT | 0K40      | CDBG             | 1005              | OFFICE OF BUDGET & MANAGEMENT | 2505          | ADMINISTRATION AND MONITORING  | 3505         | Administration and Monitoring | 0                |                                                    | 3 00           | 0               | 0306       | Assistant Director                      | Annual        | 1                   | 1                | 96456             | 96456                 | 
| CDBG      | 5               | OFFICE OF BUDGET & MANAGEMENT | 0K40      | CDBG             | 1005              | OFFICE OF BUDGET & MANAGEMENT | 2505          | ADMINISTRATION AND MONITORING  | 3505         | Administration and Monitoring | 0                |                                                    | 1 00           | 0               | 0044       | Fringe Benefits                         | Annual        | 0                   | 0                | 173105            | 173105                | 
| CDBG      | 5               | OFFICE OF BUDGET & MANAGEMENT | 0K40      | CDBG             | 1005              | OFFICE OF BUDGET & MANAGEMENT | 2505          | ADMINISTRATION AND MONITORING  | 3505         | Administration and Monitoring | 0                |                                                    | 1 00           | 0               | 0015       | Schedule Salary Adjustments             | Annual        | 0                   | 0                | 4809              | 4809                  | 
| CDBG      | 27              | FINANCE                       | 0K40      | CDBG             | 1005              | FINANCE                       | 2512          | ACCOUNTING FINANCIAL REPORTING | 3512         | Grant and Project Accounting  | 4512             | Fiscal Management Accounting and Auditing Services | G 04           | 4               | 1143       | Operations Analyst                      | Annual        | 1                   | 1                | 69300             | 69300                 | 
| CDBG      | 27              | FINANCE                       | 0K40      | CDBG             | 1005              | FINANCE                       | 2512          | ACCOUNTING FINANCIAL REPORTING | 3512         | Grant and Project Accounting  | 4512             | Fiscal Management Accounting and Auditing Services | B 09           | 1               | 0665       | Senior Data Entry Operator              | Annual        | 1                   | 1                | 55212             | 55212                 | 
```