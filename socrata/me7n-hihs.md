# Budget - Fiscal Year 2017 Executive Recommendation - Budget Summary By Object Classification

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/budget-fiscal-year-2017-executive-recommendation-budget-summary-by-object-classification) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/me7n-hihs) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/me7n-hihs/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/me7n-hihs/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | me7n-hihs |
| Name | Budget - Fiscal Year 2017 Executive Recommendation - Budget Summary By Object Classification |
| Attribution | Cook County Department of Budget & Management Services |
| Category | Finance & Administration |
| Tags | 2017 budget executive recommendation, 2017 budget |
| Created | 2016-10-18T04:10:25Z |
| Publication Date | 2016-11-08T17:05:56Z |

## Description

Executive Recommendation for the Fiscal Year 2017 Budget Department Line Item Budget. For more information on the budget and schedule of public hearings see http://www.cookcountyil.gov/budget/

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
| Yes      | numeric metric | fy2016_adopted_appropriation         | FY2016 Adopted Appropriation         | money     | money       |
| Yes      | numeric metric | fy2016_adjusted_appropriation        | FY2016 Adjusted Appropriation        | money     | money       |
| Yes      | series tag     | fy2017_department_request            | FY2017 Department Request            | text      | money       |
| Yes      | numeric metric | fy2017_president_s_recommendation    | FY2017 President?s Recommendation    | money     | money       |
| Yes      | numeric metric | fy2017_approved_adopted              | FY2017 Approved & Adopted            | money     | money       |
| Yes      | numeric metric | fy2016_expenditures_as_of_09_26_2016 | FY2016 Expenditures as of 09/26/2016 | money     | money       |
```

## Time Field

```ls
Value = 2017
Format & Zone = yyyy
```

## Data Commands

```ls
series e:me7n-hihs d:2017-01-01T00:00:00.000Z t:office="Offices Under the President" t:fund_type=General t:account_number=110 t:description="Salaries and Wages of Regular Employees" t:general_fund_type="Corporate Fund" t:department_number=26 t:control_officer="Administrative Hearings" t:fy2017_department_request=471049 t:fund="Corporate Fund" t:object_account_number=501010 t:bureau="DEPARTMENT OF ADMINISTRATIVE HEARINGS" t:department_title="Department of Administrative Hearings" m:fy2016_adopted_appropriation=455443 m:fy2017_president_s_recommendation=471049 m:fy2016_expenditures_as_of_09_26_2016=355146 m:fy2016_adjusted_appropriation=451479 m:object_classification=100 m:fundsort=1

series e:me7n-hihs d:2017-01-01T00:00:00.000Z t:office="Offices Under the President" t:fund_type=General t:account_number=170 t:description="Mandatory  Medicare Costs" t:general_fund_type="Corporate Fund" t:department_number=26 t:control_officer="Administrative Hearings" t:fy2017_department_request=6831 t:fund="Corporate Fund" t:object_account_number=501510 t:bureau="DEPARTMENT OF ADMINISTRATIVE HEARINGS" t:department_title="Department of Administrative Hearings" m:fy2016_adopted_appropriation=6672 m:fy2017_president_s_recommendation=6831 m:fy2016_expenditures_as_of_09_26_2016=5102 m:fy2016_adjusted_appropriation=6651 m:object_classification=100 m:fundsort=1

series e:me7n-hihs d:2017-01-01T00:00:00.000Z t:office="Offices Under the President" t:fund_type=General t:account_number=175 t:description="Life Insurance Program" t:general_fund_type="Corporate Fund" t:department_number=26 t:control_officer="Administrative Hearings" t:fy2017_department_request=0.0 t:fund="Corporate Fund" t:object_account_number=501590 t:bureau="DEPARTMENT OF ADMINISTRATIVE HEARINGS" t:department_title="Department of Administrative Hearings" m:fy2016_adopted_appropriation=0 m:fy2017_president_s_recommendation=777 m:fy2016_expenditures_as_of_09_26_2016=0 m:fy2016_adjusted_appropriation=0 m:object_classification=100 m:fundsort=1
```

## Meta Commands

```ls
metric m:fundsort p:integer l:FundSort t:dataTypeName=number

metric m:object_classification p:integer l:"Object Classification" t:dataTypeName=number

metric m:fy2016_adopted_appropriation p:double l:"FY2016 Adopted Appropriation" t:dataTypeName=money

metric m:fy2016_adjusted_appropriation p:double l:"FY2016 Adjusted Appropriation" t:dataTypeName=money

metric m:fy2017_president_s_recommendation p:double l:"FY2017 President?s Recommendation" t:dataTypeName=money

metric m:fy2017_approved_adopted p:double l:"FY2017 Approved & Adopted" t:dataTypeName=money

metric m:fy2016_expenditures_as_of_09_26_2016 p:double l:"FY2016 Expenditures as of 09/26/2016" t:dataTypeName=money

entity e:me7n-hihs l:"Budget - Fiscal Year 2017 Executive Recommendation - Budget Summary By Object Classification" t:attribution="Cook County Department of Budget & Management Services" t:url=https://datacatalog.cookcountyil.gov/api/views/me7n-hihs

property e:me7n-hihs t:meta.view v:id=me7n-hihs v:category="Finance & Administration" v:attributionLink=http://www.cookcountyil.gov/budget/ v:averageRating=0 v:name="Budget - Fiscal Year 2017 Executive Recommendation - Budget Summary By Object Classification" v:attribution="Cook County Department of Budget & Management Services"

property e:me7n-hihs t:meta.view.license v:name="Public Domain"

property e:me7n-hihs t:meta.view.owner v:id=u38g-hbsa v:screenName="Cook County Open Data" v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"

property e:me7n-hihs t:meta.view.tableauthor v:id=u38g-hbsa v:screenName="Cook County Open Data" v:roleName=administrator v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"
```

## Top Records

```ls
| office                      | control_officer         | fund           | fund_type | fundsort | general_fund_type | bureau                                | department_number | department_title                      | object_classification | account_number | object_account_number | description                                            | fy2016_adopted_appropriation | fy2016_adjusted_appropriation | fy2017_department_request | fy2017_president_s_recommendation | fy2017_approved_adopted | fy2016_expenditures_as_of_09_26_2016 | 
| =========================== | ======================= | ============== | ========= | ======== | ================= | ===================================== | ================= | ===================================== | ===================== | ============== | ===================== | ====================================================== | ============================ | ============================= | ========================= | ================================= | ======================= | ==================================== | 
| Offices Under the President | Administrative Hearings | Corporate Fund | General   | 1        | Corporate Fund    | DEPARTMENT OF ADMINISTRATIVE HEARINGS | 26                | Department of Administrative Hearings | 100                   | 110            | 501010                | Salaries and Wages of Regular Employees                | 455443                       | 451479                        | 471049                    | 471049                            |                         | 355146                               | 
| Offices Under the President | Administrative Hearings | Corporate Fund | General   | 1        | Corporate Fund    | DEPARTMENT OF ADMINISTRATIVE HEARINGS | 26                | Department of Administrative Hearings | 100                   | 170            | 501510                | Mandatory Medicare Costs                               | 6672                         | 6651                          | 6831                      | 6831                              |                         | 5102                                 | 
| Offices Under the President | Administrative Hearings | Corporate Fund | General   | 1        | Corporate Fund    | DEPARTMENT OF ADMINISTRATIVE HEARINGS | 26                | Department of Administrative Hearings | 100                   | 175            | 501590                | Life Insurance Program                                 | 0.0                          | 0.0                           | 0.0                       | 777                               |                         | 0.0                                  | 
| Offices Under the President | Administrative Hearings | Corporate Fund | General   | 1        | Corporate Fund    | DEPARTMENT OF ADMINISTRATIVE HEARINGS | 26                | Department of Administrative Hearings | 100                   | 176            | 501610                | Health Insurance                                       | 0.0                          | 0.0                           | 0.0                       | 76717                             |                         | 0.0                                  | 
| Offices Under the President | Administrative Hearings | Corporate Fund | General   | 1        | Corporate Fund    | DEPARTMENT OF ADMINISTRATIVE HEARINGS | 26                | Department of Administrative Hearings | 100                   | 177            | 501640                | Dental Insurance Plan                                  | 0.0                          | 0.0                           | 0.0                       | 2271                              |                         | 0.0                                  | 
| Offices Under the President | Administrative Hearings | Corporate Fund | General   | 1        | Corporate Fund    | DEPARTMENT OF ADMINISTRATIVE HEARINGS | 26                | Department of Administrative Hearings | 100                   | 178            | 501660                | Unemployment Compensation                              | 0.0                          | 0.0                           | 0.0                       | 378                               |                         | 0.0                                  | 
| Offices Under the President | Administrative Hearings | Corporate Fund | General   | 1        | Corporate Fund    | DEPARTMENT OF ADMINISTRATIVE HEARINGS | 26                | Department of Administrative Hearings | 100                   | 179            | 501690                | Vision Care Insurance                                  | 0.0                          | 0.0                           | 0.0                       | 874                               |                         | 0.0                                  | 
| Offices Under the President | Administrative Hearings | Corporate Fund | General   | 1        | Corporate Fund    | DEPARTMENT OF ADMINISTRATIVE HEARINGS | 26                | Department of Administrative Hearings | 100                   | 181            | 501715                | Group Pharmacy Insurance                               | 0.0                          | 0.0                           | 0.0                       | 23801                             |                         | 0.0                                  | 
| Offices Under the President | Administrative Hearings | Corporate Fund | General   | 1        | Corporate Fund    | DEPARTMENT OF ADMINISTRATIVE HEARINGS | 26                | Department of Administrative Hearings | 100                   | 190            | 501970                | Transportation and Other Travel Expenses for Employees | 1500                         | 3993                          | 2000                      | 2000                              |                         | 2373                                 | 
| Offices Under the President | Administrative Hearings | Corporate Fund | General   | 1        | Corporate Fund    | DEPARTMENT OF ADMINISTRATIVE HEARINGS | 26                | Department of Administrative Hearings | 200                   | 220            | 520150                | Communication Services                                 | 1369                         | 1262                          | 1300                      | 1300                              |                         | 476                                  | 
```