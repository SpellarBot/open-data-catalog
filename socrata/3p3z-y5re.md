# Budget - Fiscal Year 2016 Executive Recommendation - Budget Summary Of Positions By Business Unit

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/budget-fiscal-year-2016-executive-recommendation-budget-summary-of-positions-by-business-u) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/3p3z-y5re) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/3p3z-y5re/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/3p3z-y5re/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | 3p3z-y5re |
| Name | Budget - Fiscal Year 2016 Executive Recommendation - Budget Summary Of Positions By Business Unit |
| Attribution | Cook County Department of Budget & Management Services |
| Category | Finance & Administration |
| Tags | 2016 budget executive recommendation |
| Created | 2015-10-14T02:48:03Z |
| Publication Date | 2015-10-14T03:10:21Z |

## Description

Executive Recommendation for the Fiscal Year 2016 Budget Summary of Positions by Business Unit. For more information on the budget and schedule of public hearings see http://www.cookcountyil.gov/budget/

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type | Render Type |
| ======== | ============== | ==================== | ==================== | ========= | =========== |
| Yes      | series tag     | office               | Office               | text      | text        |
| Yes      | series tag     | control_officer      | Control Officer      | text      | text        |
| Yes      | series tag     | general_fund_type    | General Fund Type    | text      | text        |
| Yes      | series tag     | fund_type            | Fund Type            | text      | text        |
| Yes      | series tag     | fund                 | Fund                 | text      | text        |
| Yes      | series tag     | bureau               | Bureau               | text      | text        |
| Yes      | series tag     | department_number    | Department Number    | text      | number      |
| Yes      | series tag     | department_name      | Department Name      | text      | text        |
| Yes      | series tag     | business_unit_number | Business Unit Number | text      | number      |
| Yes      | series tag     | business_unit_name   | Business Unit Name   | text      | text        |
| Yes      | series tag     | job_code             | Job Code             | text      | number      |
| Yes      | series tag     | job_title            | Job Title            | text      | text        |
| Yes      | series tag     | grade                | Grade                | text      | text        |
| Yes      | numeric metric | 2015_adopted_fte     | 2015 Adopted FTE     | number    | number      |
| Yes      | numeric metric | 2015_adopted_salary  | 2015 Adopted Salary  | money     | money       |
| Yes      | numeric metric | 2016_dept_req_fte    | 2016 Dept Req FTE    | number    | number      |
| Yes      | numeric metric | 2016_dept_req_salary | 2016 Dept Req Salary | money     | money       |
| Yes      | numeric metric | 2016_pres_rec_fte    | 2016 Pres Rec FTE    | number    | number      |
| Yes      | numeric metric | 2016_pres_rec_salary | 2016 Pres Rec Salary | money     | money       |
```

## Time Field

```ls
Value = 2016
Format & Zone = yyyy
```

## Data Commands

```ls
series e:3p3z-y5re d:2016-01-01T00:00:00.000Z t:office="Offices Under the President" t:fund_type=General t:business_unit_name="Administrative Hearings" t:job_code=263 t:general_fund_type="Corporate Fund" t:department_number=26 t:job_title=Director t:control_officer="Administrative Hearings" t:business_unit_number=260101 t:grade=24 t:fund="Corporate Fund" t:department_name="Department of Administrative Hearings" t:bureau="DEPARTMENT OF ADMINISTRATIVE HEARINGS" m:2015_adopted_salary=110000 m:2016_dept_req_salary=110000 m:2016_dept_req_fte=1 m:2016_pres_rec_fte=1 m:2016_pres_rec_salary=110000 m:2015_adopted_fte=1

series e:3p3z-y5re d:2016-01-01T00:00:00.000Z t:office="Offices Under the President" t:fund_type=General t:business_unit_name="Administrative Hearings" t:job_code=292 t:general_fund_type="Corporate Fund" t:department_number=26 t:job_title="Administrative Analyst II" t:control_officer="Administrative Hearings" t:business_unit_number=260101 t:grade=19 t:fund="Corporate Fund" t:department_name="Department of Administrative Hearings" t:bureau="DEPARTMENT OF ADMINISTRATIVE HEARINGS" m:2015_adopted_salary=76116 m:2016_dept_req_salary=81574 m:2016_dept_req_fte=1 m:2016_pres_rec_fte=1 m:2016_pres_rec_salary=81574 m:2015_adopted_fte=1

series e:3p3z-y5re d:2016-01-01T00:00:00.000Z t:office="Offices Under the President" t:fund_type=General t:business_unit_name="Administrative Hearings" t:job_code=46 t:general_fund_type="Corporate Fund" t:department_number=26 t:job_title="Administrative Assistant I" t:control_officer="Administrative Hearings" t:business_unit_number=260101 t:grade=12 t:fund="Corporate Fund" t:department_name="Department of Administrative Hearings" t:bureau="DEPARTMENT OF ADMINISTRATIVE HEARINGS" m:2015_adopted_salary=64316 m:2016_dept_req_salary=101950 m:2016_dept_req_fte=3 m:2016_pres_rec_fte=3 m:2016_pres_rec_salary=101950 m:2015_adopted_fte=2
```

## Meta Commands

```ls
metric m:2015_adopted_fte p:float l:"2015 Adopted FTE" t:dataTypeName=number

metric m:2015_adopted_salary p:double l:"2015 Adopted Salary" t:dataTypeName=money

metric m:2016_dept_req_fte p:float l:"2016 Dept Req FTE" t:dataTypeName=number

metric m:2016_dept_req_salary p:double l:"2016 Dept Req Salary" t:dataTypeName=money

metric m:2016_pres_rec_fte p:float l:"2016 Pres Rec FTE" t:dataTypeName=number

metric m:2016_pres_rec_salary p:double l:"2016 Pres Rec Salary" t:dataTypeName=money

entity e:3p3z-y5re l:"Budget - Fiscal Year 2016 Executive Recommendation - Budget Summary Of Positions By Business Unit" t:attribution="Cook County Department of Budget & Management Services" t:url=https://datacatalog.cookcountyil.gov/api/views/3p3z-y5re

property e:3p3z-y5re t:meta.view v:id=3p3z-y5re v:category="Finance & Administration" v:attributionLink=http://www.cookcountyil.gov/budget/ v:averageRating=0 v:name="Budget - Fiscal Year 2016 Executive Recommendation - Budget Summary Of Positions By Business Unit" v:attribution="Cook County Department of Budget & Management Services"

property e:3p3z-y5re t:meta.view.license v:name="Public Domain"

property e:3p3z-y5re t:meta.view.owner v:id=u38g-hbsa v:screenName="Cook County Open Data" v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"

property e:3p3z-y5re t:meta.view.tableauthor v:id=u38g-hbsa v:screenName="Cook County Open Data" v:roleName=administrator v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"
```

## Top Records

```ls
| office                          | control_officer         | general_fund_type | fund_type | fund           | bureau                                | department_number | department_name                       | business_unit_number | business_unit_name      | job_code | job_title                           | grade | 2015_adopted_fte | 2015_adopted_salary | 2016_dept_req_fte | 2016_dept_req_salary | 2016_pres_rec_fte | 2016_pres_rec_salary | 
| =============================== | ======================= | ================= | ========= | ============== | ===================================== | ================= | ===================================== | ==================== | ======================= | ======== | =================================== | ===== | ================ | =================== | ================= | ==================== | ================= | ==================== | 
| Offices Under the President     | Administrative Hearings | Corporate Fund    | General   | Corporate Fund | DEPARTMENT OF ADMINISTRATIVE HEARINGS | 26                | Department of Administrative Hearings | 260101               | Administrative Hearings | 263      | Director                            | 24    | 1.0              | 110000.00           | 1.0               | 110000.00            | 1.0               | 110000.00            | 
| Offices Under the President     | Administrative Hearings | Corporate Fund    | General   | Corporate Fund | DEPARTMENT OF ADMINISTRATIVE HEARINGS | 26                | Department of Administrative Hearings | 260101               | Administrative Hearings | 292      | Administrative Analyst II           | 19    | 1.0              | 76116.00            | 1.0               | 81574.00             | 1.0               | 81574.00             | 
| Offices Under the President     | Administrative Hearings | Corporate Fund    | General   | Corporate Fund | DEPARTMENT OF ADMINISTRATIVE HEARINGS | 26                | Department of Administrative Hearings | 260101               | Administrative Hearings | 46       | Administrative Assistant I          | 12    | 2.0              | 64316.00            | 3.0               | 101950.00            | 3.0               | 101950.00            | 
| Offices Under the President     | Administrative Hearings | Corporate Fund    | General   | Corporate Fund | DEPARTMENT OF ADMINISTRATIVE HEARINGS | 26                | Department of Administrative Hearings | 260101               | Administrative Hearings | 48       | Administrative Assistant III        | 16    | 1.0              | 44916.00            | 1.0               | 48801.00             | 1.0               | 48801.00             | 
| Offices Under the President     | Administrative Hearings | Corporate Fund    | General   | Corporate Fund | DEPARTMENT OF ADMINISTRATIVE HEARINGS | 26                | Department of Administrative Hearings | 260101               | Administrative Hearings | 5205     | Deputy Director                     | 24    |                  | 1.00                |                   | 1.00                 |                   | 1.00                 | 
| Offices Under the President     | Administrative Hearings | Corporate Fund    | General   | Corporate Fund | DEPARTMENT OF ADMINISTRATIVE HEARINGS | 26                | Department of Administrative Hearings | 260101               | Administrative Hearings | 5531     | Special Assistant for Legal Affairs | 24    |                  | 1.00                |                   | 1.00                 |                   | 1.00                 | 
| Offices Under the President     | Administrative Hearings | Corporate Fund    | General   | Corporate Fund | DEPARTMENT OF ADMINISTRATIVE HEARINGS | 26                | Department of Administrative Hearings | 260101               | Administrative Hearings | 5700     | Administrative Hearings Clerk       | 12    | 3.0              | 94732.00            | 2.0               | 68836.00             | 2.0               | 68836.00             | 
| Offices Under the President     | Administrative Hearings | Corporate Fund    | General   | Corporate Fund | DEPARTMENT OF ADMINISTRATIVE HEARINGS | 26                | Department of Administrative Hearings | 260101               | Administrative Hearings | 620      | Legislative Coordinator I           | 20    | 1.0              | 58305.00            | 1.0               | 63251.00             | 1.0               | 63251.00             | 
| Elected and Appointed Officials | Assessor                | Corporate Fund    | General   | Corporate Fund | ASSESSOR                              | 40                | County Assessor                       | 401420               | Administration          | 117      | Director of Technical Service       | 23    |                  | 1.00                |                   | 1.00                 |                   | 1.00                 | 
| Elected and Appointed Officials | Assessor                | Corporate Fund    | General   | Corporate Fund | ASSESSOR                              | 40                | County Assessor                       | 401420               | Administration          | 187      | Assistant to the Director           | 21    |                  | 1.00                |                   | 1.00                 |                   | 1.00                 | 
```