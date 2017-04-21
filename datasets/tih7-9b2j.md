# Budget - Fiscal Year 2016 Executive Recommendation - Budget Summary By Object Classification

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/budget-fiscal-year-2016-executive-recommendation-budget-summary-by-object-classification) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/tih7-9b2j) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/tih7-9b2j/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/tih7-9b2j/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | tih7-9b2j |
| Name | Budget - Fiscal Year 2016 Executive Recommendation - Budget Summary By Object Classification |
| Attribution | Cook County Department of Budget & Management Services |
| Category | Finance & Administration |
| Tags | 2016 budget executive recommendation |
| Created | 2015-10-14T02:32:24Z |
| Publication Date | 2015-10-14T02:46:32Z |

## Description

Executive Recommendation for the Fiscal Year 2016 Budget Department Line Item Budget. For more information on the budget and schedule of public hearings see http://www.cookcountyil.gov/budget/

## Columns

```ls
| Included | Schema Type    | Field Name                           | Name                                 | Data Type | Render Type |
| ======== | ============== | ==================================== | ==================================== | ========= | =========== |
| Yes      | series tag     | office                               | Office                               | text      | text        |
| Yes      | series tag     | control_officer                      | Control Officer                      | text      | text        |
| Yes      | series tag     | fund                                 | Fund                                 | text      | text        |
| Yes      | series tag     | fund_type                            | Fund Type                            | text      | text        |
| Yes      | numeric metric | fundsort                             | FundSort                             | number    | number      |
| Yes      | series tag     | general_fund_type                    | General Fund Type                    | text      | text        |
| Yes      | series tag     | bureau                               | Bureau                               | text      | text        |
| Yes      | series tag     | department_number                    | Department Number                    | text      | number      |
| Yes      | series tag     | department_title                     | Department Title                     | text      | text        |
| Yes      | numeric metric | object_classification                | Object Classification                | number    | number      |
| Yes      | series tag     | account_number                       | Account Number                       | text      | number      |
| Yes      | series tag     | object_account_number                | Object Account Number                | text      | number      |
| Yes      | series tag     | description                          | Description                          | text      | text        |
| Yes      | numeric metric | fy2015_adopted_appropriation         | FY2015 Adopted Appropriation         | money     | money       |
| Yes      | numeric metric | fy2015_adjusted_appropriation        | FY2015 Adjusted Appropriation        | money     | money       |
| Yes      | series tag     | fy2016_department_request            | FY2016 Department Request            | text      | money       |
| Yes      | numeric metric | fy2016_president_s_recommendation    | FY2016 President?s Recommendation    | money     | money       |
| Yes      | numeric metric | fy2016_approved_adopted              | FY2016 Approved & Adopted            | money     | money       |
| Yes      | numeric metric | fy2015_expenditures_as_of_09_23_2015 | FY2015 Expenditures as of 09/23/2015 | money     | money       |
```

## Time Field

```ls
Value = 2016
Format & Zone = yyyy
```

## Data Commands

```ls
series e:tih7-9b2j d:2016-01-01T00:00:00.000Z t:office="Offices Under the President" t:fund_type=General t:account_number=110 t:description="Salaries and Wages of Regular Employees" t:general_fund_type="Corporate Fund" t:department_number=2 t:control_officer="Department of Human Rights and Ethics" t:fund="Corporate Fund" t:object_account_number=501010 t:bureau="DEPARTMENT OF HUMAN RIGHTS AND ETHICS" t:department_title="Department of Human Rights and Ethics" t:fy2016_department_request=743057 m:fy2015_adopted_appropriation=747936 m:fy2016_president_s_recommendation=743057 m:object_classification=100 m:fy2015_adjusted_appropriation=736716 m:fy2015_expenditures_as_of_09_23_2015=466405.61 m:fundsort=1

series e:tih7-9b2j d:2016-01-01T00:00:00.000Z t:office="Offices Under the President" t:fund_type=General t:account_number=110 t:description="Salaries and Wages of Regular Employees" t:general_fund_type="Corporate Fund" t:department_number=7 t:control_officer="Chief Financial Officer" t:fund="Corporate Fund" t:object_account_number=501010 t:bureau="BUREAU OF FINANCE" t:department_title=Revenue t:fy2016_department_request=4518778 m:fy2015_adopted_appropriation=4075169 m:fy2016_president_s_recommendation=4518778 m:object_classification=100 m:fy2015_adjusted_appropriation=4013926 m:fy2015_expenditures_as_of_09_23_2015=2781008.84 m:fundsort=1

series e:tih7-9b2j d:2016-01-01T00:00:00.000Z t:office="Offices Under the President" t:fund_type=General t:account_number=110 t:description="Salaries and Wages of Regular Employees" t:general_fund_type="Corporate Fund" t:department_number=8 t:control_officer="Chief Financial Officer" t:fund="Corporate Fund" t:object_account_number=501010 t:bureau="BUREAU OF FINANCE" t:department_title="Risk Management" t:fy2016_department_request=1605964 m:fy2015_adopted_appropriation=1691266 m:fy2016_president_s_recommendation=1605964 m:object_classification=100 m:fy2015_adjusted_appropriation=1665894 m:fy2015_expenditures_as_of_09_23_2015=1254391.24 m:fundsort=1
```

## Meta Commands

```ls
metric m:fundsort p:integer l:FundSort t:dataTypeName=number

metric m:object_classification p:integer l:"Object Classification" t:dataTypeName=number

metric m:fy2015_adopted_appropriation p:integer l:"FY2015 Adopted Appropriation" t:dataTypeName=money

metric m:fy2015_adjusted_appropriation p:integer l:"FY2015 Adjusted Appropriation" t:dataTypeName=money

metric m:fy2016_president_s_recommendation p:integer l:"FY2016 President?s Recommendation" t:dataTypeName=money

metric m:fy2016_approved_adopted p:integer l:"FY2016 Approved & Adopted" t:dataTypeName=money

metric m:fy2015_expenditures_as_of_09_23_2015 p:double l:"FY2015 Expenditures as of 09/23/2015" t:dataTypeName=money

entity e:tih7-9b2j l:"Budget - Fiscal Year 2016 Executive Recommendation - Budget Summary By Object Classification" t:attribution="Cook County Department of Budget & Management Services" t:url=https://datacatalog.cookcountyil.gov/api/views/tih7-9b2j

property e:tih7-9b2j t:meta.view v:id=tih7-9b2j v:category="Finance & Administration" v:attributionLink=http://www.cookcountyil.gov/budget/ v:averageRating=0 v:name="Budget - Fiscal Year 2016 Executive Recommendation - Budget Summary By Object Classification" v:attribution="Cook County Department of Budget & Management Services"

property e:tih7-9b2j t:meta.view.license v:name="Public Domain"

property e:tih7-9b2j t:meta.view.owner v:id=u38g-hbsa v:screenName="Cook County Open Data" v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"

property e:tih7-9b2j t:meta.view.tableauthor v:id=u38g-hbsa v:screenName="Cook County Open Data" v:roleName=administrator v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"
```

## Top Records

```ls
| office                          | control_officer                       | fund           | fund_type | fundsort | general_fund_type | bureau                                | department_number | department_title                                      | object_classification | account_number | object_account_number | description                             | fy2015_adopted_appropriation | fy2015_adjusted_appropriation | fy2016_department_request | fy2016_president_s_recommendation | fy2016_approved_adopted | fy2015_expenditures_as_of_09_23_2015 | 
| =============================== | ===================================== | ============== | ========= | ======== | ================= | ===================================== | ================= | ===================================================== | ===================== | ============== | ===================== | ======================================= | ============================ | ============================= | ========================= | ================================= | ======================= | ==================================== | 
| Offices Under the President     | Department of Human Rights and Ethics | Corporate Fund | General   | 1        | Corporate Fund    | DEPARTMENT OF HUMAN RIGHTS AND ETHICS | 2                 | Department of Human Rights and Ethics                 | 100                   | 110            | 501010                | Salaries and Wages of Regular Employees | 747936                       | 736716                        | 743057                    | 743057                            |                         | 466405.61                            | 
| Offices Under the President     | Chief Financial Officer               | Corporate Fund | General   | 1        | Corporate Fund    | BUREAU OF FINANCE                     | 7                 | Revenue                                               | 100                   | 110            | 501010                | Salaries and Wages of Regular Employees | 4075169                      | 4013926                       | 4518778                   | 4518778                           |                         | 2781008.84                           | 
| Offices Under the President     | Chief Financial Officer               | Corporate Fund | General   | 1        | Corporate Fund    | BUREAU OF FINANCE                     | 8                 | Risk Management                                       | 100                   | 110            | 501010                | Salaries and Wages of Regular Employees | 1691266                      | 1665894                       | 1605964                   | 1605964                           |                         | 1254391.24                           | 
| Offices Under the President     | Chief Information Officer             | Corporate Fund | General   | 1        | Corporate Fund    | BUREAU OF TECHNOLOGY                  | 9                 | Enterprise Technology                                 | 100                   | 110            | 501010                | Salaries and Wages of Regular Employees | 10990113                     | 10825259                      | 11303704                  | 11303704                          |                         | 7923452.50                           | 
| Offices Under the President     | President                             | Corporate Fund | General   | 1        | Corporate Fund    | OFFICES UNDER THE PRESIDENT           | 10                | Office of the President                               | 100                   | 110            | 501010                | Salaries and Wages of Regular Employees | 1745697                      | 1719509                       | 1952330                   | 1952330                           |                         | 1339472.69                           | 
| Offices Under the President     | Chief Administrative Officer          | Corporate Fund | General   | 1        | Corporate Fund    | BUREAU OF ADMINISTRATION              | 11                | Office of the Chief Administrative Officer            | 100                   | 110            | 501010                | Salaries and Wages of Regular Employees | 2295388                      | 2256372                       | 2281030                   | 2281030                           |                         | 1673791.41                           | 
| Offices Under the President     | Chief of Economic Development         | Corporate Fund | General   | 1        | Corporate Fund    | BUREAU OF ECONOMIC DEVELOPMENT        | 13                | Planning and Development                              | 100                   | 110            | 501010                | Salaries and Wages of Regular Employees | 1187448                      | 1169634                       | 1065056                   | 1065056                           |                         | 879700.4                             | 
| Offices Under the President     | Chief Financial Officer               | Corporate Fund | General   | 1        | Corporate Fund    | BUREAU OF FINANCE                     | 14                | Budget and Management Services                        | 100                   | 110            | 501010                | Salaries and Wages of Regular Employees | 1483049                      | 1468265                       | 1605776                   | 1605776                           |                         | 1134398.51                           | 
| Elected and Appointed Officials | Cook County Board of Commissioners    | Corporate Fund | General   | 1        | Corporate Fund    | COOK COUNTY BOARD OF COMMISSIONERS    | 18                | Office Of The Secretary To The Board of Commissioners | 100                   | 110            | 501010                | Salaries and Wages of Regular Employees | 795530                       | 783597                        | 857162                    | 857162                            |                         | 557729.31                            | 
| Offices Under the President     | Chief Financial Officer               | Corporate Fund | General   | 1        | Corporate Fund    | BUREAU OF FINANCE                     | 20                | County Comptroller                                    | 100                   | 110            | 501010                | Salaries and Wages of Regular Employees | 2978401                      | 2933723                       | 3107463                   | 3107463                           |                         | 2170932.75                           | 
```