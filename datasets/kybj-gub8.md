# State of Iowa Executive Branch Comp Time & Overtime Hours by Pay Period

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-of-iowa-comp-time-overtime-hours-by-pay-period) |
| Metadata | [Link](https://data.iowa.gov/api/views/kybj-gub8) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/kybj-gub8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/kybj-gub8/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | kybj-gub8 |
| Name | State of Iowa Executive Branch Comp Time & Overtime Hours by Pay Period |
| Attribution | Iowa Department of Management, Salary Projection Model |
| Category | Government |
| Tags | comp time, overtime, state employees, executive branch |
| Created | 2015-04-23T19:39:56Z |
| Publication Date | 2015-04-23T19:54:50Z |

## Description

This dataset includes hours of comp time earned and overtime paid for state employees within Executive Branch by pay period starting with pay period ending December 23, 2010.  Pay periods are two weeks long and end every other Thursday.  Comp time and overtime reflect hours worked above an employee's regular work hours. Beginning with the pay period ending December 6, 2012, holiday earned is included in the comp time earned totals.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name                     | Data Type     | Render Type   |
| ======== | ============== | ================== | ======================== | ============= | ============= |
| Yes      | series tag     | function           | Function                 | text          | text          |
| Yes      | series tag     | special_department | Special Department       | text          | text          |
| Yes      | series tag     | department_number  | Department Number        | text          | text          |
| Yes      | series tag     | department         | Department               | text          | text          |
| Yes      | numeric metric | comp_time_earned   | Comp Time Earned (Hours) | number        | number        |
| Yes      | numeric metric | over_time_paid     | Over Time Paid (Hours)   | number        | number        |
| Yes      | numeric metric | regular_hours      | Regular Hours            | number        | number        |
| Yes      | numeric metric | ct_ot              | % CT & OT                | percent       | percent       |
| Yes      | time           | pay_period_start   | Pay Period Start         | calendar_date | calendar_date |
| No       |                | pay_period_end     | Pay Period End           | calendar_date | calendar_date |
| No       |                | fiscal_year        | Fiscal Year              | number        | text          |
| Yes      | numeric metric | pay_period         | Pay Period               | number        | text          |
```

## Time Field

```ls
Value = pay_period_start
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = pay_period_end,fiscal_year
```

## Data Commands

```ls
series e:kybj-gub8 d:2015-03-13T00:00:00.000Z t:department="Consumer Advocate" t:department_number=114 t:special_department="Attorney General" t:function="Justice System" m:comp_time_earned=0 m:pay_period=20 m:ct_ot=0 m:regular_hours=1364 m:over_time_paid=0

series e:kybj-gub8 d:2015-03-13T00:00:00.000Z t:department="Auditor Of State" t:department_number=126 t:special_department="Auditor of State" t:function="Administration and Regulation" m:comp_time_earned=0 m:pay_period=20 m:ct_ot=0 m:regular_hours=7448.5 m:over_time_paid=0

series e:kybj-gub8 d:2015-03-13T00:00:00.000Z t:department="Campaign Finance Disclosure Commission" t:department_number=140 t:special_department="Iowa Ethics & Campaign Disclosure Board" t:function="Administration and Regulation" m:comp_time_earned=0 m:pay_period=20 m:ct_ot=0 m:regular_hours=512 m:over_time_paid=0
```

## Meta Commands

```ls
metric m:comp_time_earned p:float l:"Comp Time Earned (Hours)" d:"Hours of comp time earned in pay period" t:dataTypeName=number

metric m:over_time_paid p:float l:"Over Time Paid (Hours)" d:"Hours of overtime paid in pay period" t:dataTypeName=number

metric m:regular_hours p:float l:"Regular Hours" d:"Regular amount of hours worked in pay period" t:dataTypeName=number

metric m:ct_ot p:float l:"% CT & OT" d:"Sum of comp time hours and overtime hours divided by regular hours. Expressed as a percentage" t:dataTypeName=percent

metric m:pay_period p:integer l:"Pay Period" d:"Pay period record is associated with. There are 26 pay periods in a fiscal year." t:dataTypeName=number

entity e:kybj-gub8 l:"State of Iowa Executive Branch Comp Time & Overtime Hours by Pay Period" t:attribution="Iowa Department of Management, Salary Projection Model" t:url=https://data.iowa.gov/api/views/kybj-gub8

property e:kybj-gub8 t:meta.view v:id=kybj-gub8 v:category=Government v:averageRating=0 v:name="State of Iowa Executive Branch Comp Time & Overtime Hours by Pay Period" v:attribution="Iowa Department of Management, Salary Projection Model"

property e:kybj-gub8 t:meta.view.license v:name="Public Domain"

property e:kybj-gub8 t:meta.view.owner v:id=bnfb-vany v:profileImageUrlMedium=/api/users/bnfb-vany/profile_images/THUMB v:profileImageUrlLarge=/api/users/bnfb-vany/profile_images/LARGE v:screenName="IDOM, State Budget" v:profileImageUrlSmall=/api/users/bnfb-vany/profile_images/TINY v:displayName="IDOM, State Budget"

property e:kybj-gub8 t:meta.view.tableauthor v:id=bnfb-vany v:profileImageUrlMedium=/api/users/bnfb-vany/profile_images/THUMB v:profileImageUrlLarge=/api/users/bnfb-vany/profile_images/LARGE v:screenName="IDOM, State Budget" v:profileImageUrlSmall=/api/users/bnfb-vany/profile_images/TINY v:roleName=editor v:displayName="IDOM, State Budget"
```

## Top Records

```ls
| function                      | special_department                      | department_number | department                             | comp_time_earned | over_time_paid | regular_hours | ct_ot | pay_period_start    | pay_period_end      | fiscal_year | pay_period | 
| ============================= | ======================================= | ================= | ====================================== | ================ | ============== | ============= | ===== | =================== | =================== | =========== | ========== | 
| Justice System                | Attorney General                        | 114               | Consumer Advocate                      | 0.00             | 0.00           | 1364.00       | 0.00  | 2015-03-13T00:00:00 | 2015-03-26T00:00:00 | 2015        | 20         | 
| Administration and Regulation | Auditor of State                        | 126               | Auditor Of State                       | 0.00             | 0.00           | 7448.50       | 0.00  | 2015-03-13T00:00:00 | 2015-03-26T00:00:00 | 2015        | 20         | 
| Administration and Regulation | Iowa Ethics & Campaign Disclosure Board | 140               | Campaign Finance Disclosure Commission | 0.00             | 0.00           | 512.00        | 0.00  | 2015-03-13T00:00:00 | 2015-03-26T00:00:00 | 2015        | 20         | 
| Justice System                | Civil Rights Commission                 | 167               | Civil Rights Commission                | 0.00             | 0.00           | 2139.54       | 0.00  | 2015-03-13T00:00:00 | 2015-03-26T00:00:00 | 2015        | 20         | 
| Administration and Regulation | Commerce, Department of                 | 213               | Banking Division                       | 0.00             | 0.00           | 5457.00       | 0.00  | 2015-03-13T00:00:00 | 2015-03-26T00:00:00 | 2015        | 20         | 
| Administration and Regulation | Commerce, Department of                 | 214               | Credit Union Division                  | 0.00             | 0.00           | 1132.00       | 0.00  | 2015-03-13T00:00:00 | 2015-03-26T00:00:00 | 2015        | 20         | 
| Administration and Regulation | Commerce, Department of                 | 217               | Professional Licensing & Regulation    | 0.00             | 0.00           | 800.00        | 0.00  | 2015-03-13T00:00:00 | 2015-03-26T00:00:00 | 2015        | 20         | 
| Economic Development          | Economic Development Authority          | 269               | Economic Development Authority         | 0.00             | 0.00           | 9004.31       | 0.00  | 2015-03-13T00:00:00 | 2015-03-26T00:00:00 | 2015        | 20         | 
| Education                     | Education, Department of                | 282               | Education, Department of               | 0.00             | 0.00           | 21424.30      | 0.00  | 2015-03-13T00:00:00 | 2015-03-26T00:00:00 | 2015        | 20         | 
| Education                     | College Student Aid Commission          | 284               | College Student Aid Commission         | 0.00             | 0.00           | 2587.00       | 0.00  | 2015-03-13T00:00:00 | 2015-03-26T00:00:00 | 2015        | 20         | 
```