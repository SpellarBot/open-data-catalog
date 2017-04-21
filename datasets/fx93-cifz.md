# Salary Information for Local Authorities

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/salary-information-for-local-authorities) |
| Metadata | [Link](https://data.ny.gov/api/views/fx93-cifz) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/fx93-cifz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/fx93-cifz/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | fx93-cifz |
| Name | Salary Information for Local Authorities |
| Attribution | Individual Local Authorities submitted to Authorities Budget Office |
| Category | Transparency |
| Tags | public authority, local authority, personnel, employee, salaries/payroll |
| Created | 2014-09-10T15:07:57Z |
| Publication Date | 2016-10-12T15:59:53Z |

## Description

Public authorities are required by Section 2800 of Public Authorities Law to submit annual reports to the Authorities Budget Office that include salary and compensation data.  The dataset consists of salary data by employee reported by Local Authorities beginning with fiscal years ending in 2011.

## Columns

```ls
| Included | Schema Type    | Field Name                        | Name                              | Data Type     | Render Type   |
| ======== | ============== | ================================= | ================================= | ============= | ============= |
| Yes      | series tag     | authority_name                    | Authority Name                    | text          | text          |
| Yes      | time           | fiscal_year_end_date              | Fiscal Year End Date              | calendar_date | calendar_date |
| Yes      | series tag     | has_employees                     | Has Employees                     | text          | text          |
| Yes      | series tag     | last_name                         | Last Name                         | text          | text          |
| Yes      | series tag     | middle_initial                    | Middle Initial                    | text          | text          |
| Yes      | series tag     | first_name                        | First Name                        | text          | text          |
| Yes      | series tag     | title                             | Title                             | text          | text          |
| Yes      | series tag     | group                             | Group                             | text          | text          |
| Yes      | series tag     | department                        | Department                        | text          | text          |
| Yes      | series tag     | pay_type                          | Pay Type                          | text          | text          |
| Yes      | series tag     | exempt_indicator                  | Exempt Indicator                  | text          | text          |
| Yes      | numeric metric | base_annualized_salary            | Base Annualized Salary            | money         | money         |
| Yes      | numeric metric | actual_salary_paid                | Actual Salary Paid                | money         | money         |
| Yes      | numeric metric | overtime_paid                     | Overtime Paid                     | money         | money         |
| Yes      | numeric metric | performance_bonus                 | Performance Bonus                 | money         | money         |
| Yes      | numeric metric | extra_pay                         | Extra Pay                         | money         | money         |
| Yes      | numeric metric | other_compensation                | Other Compensation                | money         | money         |
| Yes      | numeric metric | total_compensation                | Total Compensation                | money         | money         |
| Yes      | series tag     | paid_by_another_entity            | Paid By Another Entity            | text          | text          |
| Yes      | series tag     | paid_by_state_or_local_government | Paid by State or Local Government | text          | text          |
```

## Time Field

```ls
Value = fiscal_year_end_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:fx93-cifz d:2011-12-31T00:00:00.000Z t:authority_name="Albany Community Development Agency" t:first_name=Kailin t:title="Community Development Specialist" t:pay_type=FT t:paid_by_another_entity=N t:last_name=Curtin t:exempt_indicator=N t:group=Professional m:total_compensation=26208 m:base_annualized_salary=26208 m:actual_salary_paid=26208 m:performance_bonus=0 m:overtime_paid=0 m:extra_pay=0 m:other_compensation=0

series e:fx93-cifz d:2011-12-31T00:00:00.000Z t:authority_name="Albany Community Development Agency" t:first_name=Nicole t:title="Senior Typist" t:pay_type=FT t:paid_by_another_entity=N t:last_name=DeMouth t:exempt_indicator=N t:group=Administrative/Clerical m:total_compensation=30073 m:base_annualized_salary=30073 m:actual_salary_paid=30073 m:performance_bonus=0 m:overtime_paid=0 m:extra_pay=0 m:other_compensation=0

series e:fx93-cifz d:2011-12-31T00:00:00.000Z t:authority_name="Albany Community Development Agency" t:first_name=Cameron t:title="Document Scanner" t:pay_type=FT t:paid_by_another_entity=N t:last_name=Holloway t:exempt_indicator=N t:group=Operational m:total_compensation=33277 m:base_annualized_salary=33277 m:actual_salary_paid=33277 m:performance_bonus=0 m:overtime_paid=0 m:extra_pay=0 m:other_compensation=0
```

## Meta Commands

```ls
metric m:base_annualized_salary p:double l:"Base Annualized Salary" d:"The annual base salary associated with a particular job title or position. For hourly or part-time staff, annualized salary would be the actual wages paid to the individual for the reporting period." t:dataTypeName=money

metric m:actual_salary_paid p:double l:"Actual Salary Paid" d:"The actual salary or wages paid to the individual for the reporting period. This amount could be less than the annualized salary if the individual was employed in the position for less than the full year." t:dataTypeName=money

metric m:overtime_paid p:double l:"Overtime Paid" d:"Extra cash payments to the individual for hours worked in excess of normal work week hours, as authorized by the authority?s policies, an employment contract or a collective bargaining agreement. Overtime would include holiday pay." t:dataTypeName=money

metric m:performance_bonus p:double l:"Performance Bonus" d:"A cash payment to the individual that does not become part of the base annualized salary. This payment must be linked to the individual meeting clearly defined and measurable performance goals established and approved by the Board of Directors prior to the start of the fiscal year, or detailed in a performance contract approved by the Board. These performance goals should reflect accomplishments that exceed the expected job standards of the position. The amount of the bonus payment should be calculated based on a formula defined in the authority?s performance bonus policy. A performance bonus would include a bonus earned in a prior year but deferred until the reporting year, provided that the payment is consistent with the policy governing other bonuses." t:dataTypeName=money

metric m:extra_pay p:double l:"Extra Pay" d:"Payments made to the individual for unused accrued vacation or personal time, commissions, longevity, as incentives for such purposes as excellent attendance or maintaining proper standing with professional licensure requirements; cash payments to the individual in lieu of an authority?s contribution to the individual?s pension fund or health insurance coverage; or other financial awards to the individual not based on performance goals. The terms and type of extra pay to be awarded to an individual should be defined in collectively bargained or employment contracts." t:dataTypeName=money

metric m:other_compensation p:double l:"Other Compensation" d:"Allowances, reimbursement for authorized expenses, or all other forms of taxable income not included in one of the above categories. This could include adjustments to previously paid compensation to correct payment errors." t:dataTypeName=money

metric m:total_compensation p:double l:"Total Compensation" d:"Total payments made to the individual during the year including any overtime, bonus, extra, or other compensation amounts. This field is the sum of the Actual Salary Paid, Overtime Paid, Performance Bonus, Extra Pay and Other Compensation fields." t:dataTypeName=money

entity e:fx93-cifz l:"Salary Information for Local Authorities" t:attribution="Individual Local Authorities submitted to Authorities Budget Office" t:url=https://data.ny.gov/api/views/fx93-cifz

property e:fx93-cifz t:meta.view v:id=fx93-cifz v:category=Transparency v:attributionLink=http://www.abo.ny.gov/ v:averageRating=0 v:name="Salary Information for Local Authorities" v:attribution="Individual Local Authorities submitted to Authorities Budget Office"

property e:fx93-cifz t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:fx93-cifz t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:fx93-cifz t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| authority_name                      | fiscal_year_end_date | has_employees | last_name | middle_initial | first_name | title                            | group                   | department | pay_type | exempt_indicator | base_annualized_salary | actual_salary_paid | overtime_paid | performance_bonus | extra_pay | other_compensation | total_compensation | paid_by_another_entity | paid_by_state_or_local_government | 
| =================================== | ==================== | ============= | ========= | ============== | ========== | ================================ | ======================= | ========== | ======== | ================ | ====================== | ================== | ============= | ================= | ========= | ================== | ================== | ====================== | ================================= | 
| Albany Community Development Agency | 2011-12-31T00:00:00  |               | Curtin    |                | Kailin     | Community Development Specialist | Professional            |            | FT       | N                | 26208.00               | 26208.00           | 0.00          | 0.00              | 0.00      | 0.00               | 26208.00           | N                      |                                   | 
| Albany Community Development Agency | 2011-12-31T00:00:00  |               | DeMouth   |                | Nicole     | Senior Typist                    | Administrative/Clerical |            | FT       | N                | 30073.00               | 30073.00           | 0.00          | 0.00              | 0.00      | 0.00               | 30073.00           | N                      |                                   | 
| Albany Community Development Agency | 2011-12-31T00:00:00  |               | Holloway  |                | Cameron    | Document Scanner                 | Operational             |            | FT       | N                | 33277.00               | 33277.00           | 0.00          | 0.00              | 0.00      | 0.00               | 33277.00           | N                      |                                   | 
| Albany Community Development Agency | 2011-12-31T00:00:00  |               | Campman   |                | Glen       | Maintenance Assistant            | Technical/Engineering   |            | FT       | N                | 33277.00               | 33277.00           | 0.00          | 0.00              | 0.00      | 0.00               | 33277.00           | N                      |                                   | 
| Albany Community Development Agency | 2011-12-31T00:00:00  |               | Adams     |                | Regina     | Confidential Assistant           | Administrative/Clerical |            | FT       | N                | 36435.00               | 36435.00           | 0.00          | 0.00              | 0.00      | 0.00               | 36435.00           | N                      |                                   | 
| Albany Community Development Agency | 2011-12-31T00:00:00  |               | McCoy     |                | Brian      | Clerk/Courier                    | Administrative/Clerical |            | FT       | N                | 38027.00               | 38027.00           | 0.00          | 0.00              | 0.00      | 0.00               | 38027.00           | N                      |                                   | 
| Albany Community Development Agency | 2011-12-31T00:00:00  |               | Pelletier |                | Roger      | Rehab Specialist II              | Operational             |            | FT       | N                | 39932.00               | 39932.00           | 0.00          | 0.00              | 0.00      | 0.00               | 39932.00           | N                      |                                   | 
| Albany Community Development Agency | 2011-12-31T00:00:00  |               | Lyman     |                | Daniel     | Rehabilitation Specialist        | Professional            |            | FT       | N                | 39932.00               | 39932.00           | 0.00          | 0.00              | 0.00      | 0.00               | 39932.00           | N                      |                                   | 
| Albany Community Development Agency | 2011-12-31T00:00:00  |               | Greene    |                | Michael    | Rehabilitation Specialist        | Professional            |            | FT       | N                | 39932.00               | 39932.00           | 0.00          | 0.00              | 0.00      | 0.00               | 39932.00           | N                      |                                   | 
| Albany Community Development Agency | 2011-12-31T00:00:00  |               | Coody     |                | HeideMarie | Accountant 1                     | Professional            |            | FT       | N                | 40281.00               | 40281.00           | 0.00          | 0.00              | 0.00      | 0.00               | 40281.00           | N                      |                                   | 
```