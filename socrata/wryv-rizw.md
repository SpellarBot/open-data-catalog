# Salary Information for Local Development Corporations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/salary-information-for-local-development-corporations) |
| Metadata | [Link](https://data.ny.gov/api/views/wryv-rizw) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/wryv-rizw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/wryv-rizw/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | wryv-rizw |
| Name | Salary Information for Local Development Corporations |
| Attribution | Individual Local Development Corporations submitted to the Authorities Budget Office |
| Category | Transparency |
| Tags | public authority, local development corporation, personnel, employee, salaries/payroll |
| Created | 2014-10-09T18:37:15Z |
| Publication Date | 2016-10-12T15:59:49Z |

## Description

Public authorities are required by Section 2800 of Public Authorities Law to submit annual reports to the Authorities Budget Office that include salary and compensation data.  The dataset consists of salary data by employee reported by Local Development Corporations beginning with fiscal years ending 2011.

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
series e:wryv-rizw d:2011-12-31T00:00:00.000Z t:paid_by_state_or_local_government=Y t:authority_name="ATC of Buffalo and Erie County, Inc." t:first_name=Bernice t:title="Senior Bookkeeper" t:pay_type=PT t:paid_by_another_entity=Y t:last_name=Stevenson t:exempt_indicator=Y t:group=Administrative/Clerical m:total_compensation=0 m:base_annualized_salary=0 m:actual_salary_paid=0 m:performance_bonus=0 m:overtime_paid=0 m:extra_pay=0 m:other_compensation=0

series e:wryv-rizw d:2011-12-31T00:00:00.000Z t:paid_by_state_or_local_government=Y t:authority_name="ATC of Buffalo and Erie County, Inc." t:first_name=Carrie t:title="Adminstrative Assistant" t:pay_type=FT t:paid_by_another_entity=Y t:last_name=Hocieniec t:exempt_indicator=Y t:group=Administrative/Clerical m:total_compensation=0 m:base_annualized_salary=0 m:actual_salary_paid=0 m:performance_bonus=0 m:overtime_paid=0 m:extra_pay=0 m:other_compensation=0

series e:wryv-rizw d:2011-12-31T00:00:00.000Z t:paid_by_state_or_local_government=Y t:authority_name="ATC of Buffalo and Erie County, Inc." t:first_name=Al t:title="Chief Operating Officer" t:pay_type=FT t:paid_by_another_entity=Y t:last_name=Culliton t:exempt_indicator=Y t:group=Executive m:total_compensation=0 m:base_annualized_salary=0 m:actual_salary_paid=0 m:performance_bonus=0 m:overtime_paid=0 m:extra_pay=0 m:other_compensation=0
```

## Meta Commands

```ls
metric m:base_annualized_salary p:double l:"Base Annualized Salary" d:"The annual base salary associated with a particular job title or position For hourly or part-time staff, annualized salary would be the actual wages paid to the individual for the reporting period." t:dataTypeName=money

metric m:actual_salary_paid p:double l:"Actual Salary Paid" d:"The actual salary or wages paid to the individual for the reporting period. This amount could be less than the annualized salary if the individual was employed in the position for less than the full year." t:dataTypeName=money

metric m:overtime_paid p:double l:"Overtime Paid" d:"Extra cash payments to the individual for hours worked in excess of normal work week hours, as authorized by the authority?s policies, an employment contract or a collective bargaining agreement. Overtime would include holiday pay." t:dataTypeName=money

metric m:performance_bonus p:double l:"Performance Bonus" d:"A cash payment to the individual that does not become part of the base annualized salary. This payment must be linked to the individual meeting clearly defined and measurable performance goals established and approved by the Board of Directors prior to the start of the fiscal year, or detailed in a performance contract approved by the Board. These performance goals should reflect accomplishments that exceed the expected job standards of the position. The amount of the bonus payment should be calculated based on a formula defined in the authority?s performance bonus policy. A performance bonus would include a bonus earned in a prior year but deferred until the reporting year, provided that the payment is consistent with the policy governing other bonuses." t:dataTypeName=money

metric m:extra_pay p:double l:"Extra Pay" d:"Payments made to the individual for unused accrued vacation or personal time, commissions, longevity, as incentives for such purposes as excellent attendance or maintaining proper standing with professional licensure requirements; cash payments to the individual in lieu of an authority?s contribution to the individual?s pension fund or health insurance coverage; or other financial awards to the individual not based on performance goals. The terms and type of extra pay to be awarded to an individual should be defined in collectively bargained or employment contracts." t:dataTypeName=money

metric m:other_compensation p:double l:"Other Compensation" d:"Allowances, reimbursement for authorized expenses, or all other forms of taxable income not included in one of the above categories. This could include adjustments to previously paid compensation to correct payment errors." t:dataTypeName=money

metric m:total_compensation p:double l:"Total Compensation" d:"Total payments made to the individual during the year including any overtime, bonus, extra, or other compensation amounts. This field is the sum of the Actual Salary Paid, Overtime Paid, Performance Bonus, Extra Pay and Other Compensation fields." t:dataTypeName=money

entity e:wryv-rizw l:"Salary Information for Local Development Corporations" t:attribution="Individual Local Development Corporations submitted to the Authorities Budget Office" t:url=https://data.ny.gov/api/views/wryv-rizw

property e:wryv-rizw t:meta.view v:id=wryv-rizw v:category=Transparency v:attributionLink=http://www.abo.ny.gov/ v:averageRating=0 v:name="Salary Information for Local Development Corporations" v:attribution="Individual Local Development Corporations submitted to the Authorities Budget Office"

property e:wryv-rizw t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:wryv-rizw t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:wryv-rizw t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| authority_name                                 | fiscal_year_end_date | has_employees | last_name  | middle_initial | first_name | title                      | group                   | department | pay_type | exempt_indicator | base_annualized_salary | actual_salary_paid | overtime_paid | performance_bonus | extra_pay | other_compensation | total_compensation | paid_by_another_entity | paid_by_state_or_local_government | 
| ============================================== | ==================== | ============= | ========== | ============== | ========== | ========================== | ======================= | ========== | ======== | ================ | ====================== | ================== | ============= | ================= | ========= | ================== | ================== | ====================== | ================================= | 
| ATC of Buffalo and Erie County, Inc.           | 2011-12-31T00:00:00  |               | Stevenson  |                | Bernice    | Senior Bookkeeper          | Administrative/Clerical |            | PT       | Y                | 0.00                   | 0.00               | 0.00          | 0.00              | 0.00      | 0.00               | 0.00               | Y                      | Y                                 | 
| ATC of Buffalo and Erie County, Inc.           | 2011-12-31T00:00:00  |               | Hocieniec  |                | Carrie     | Adminstrative Assistant    | Administrative/Clerical |            | FT       | Y                | 0.00                   | 0.00               | 0.00          | 0.00              | 0.00      | 0.00               | 0.00               | Y                      | Y                                 | 
| ATC of Buffalo and Erie County, Inc.           | 2011-12-31T00:00:00  |               | Culliton   |                | Al         | Chief Operating Officer    | Executive               |            | FT       | Y                | 0.00                   | 0.00               | 0.00          | 0.00              | 0.00      | 0.00               | 0.00               | Y                      | Y                                 | 
| ATC of Buffalo and Erie County, Inc.           | 2011-12-31T00:00:00  |               | Schoeppich |                | Andrew     | Chief Financial Officer    | Executive               |            | FT       | Y                | 0.00                   | 0.00               | 0.00          | 0.00              | 0.00      | 0.00               | 0.00               | Y                      | Y                                 | 
| ATC of Buffalo and Erie County, Inc.           | 2011-12-31T00:00:00  |               | Stebbins   |                | Dave       | Senior Project Manager     | Professional            |            | FT       | Y                | 0.00                   | 0.00               | 0.00          | 0.00              | 0.00      | 0.00               | 0.00               | Y                      | Y                                 | 
| ATC of Buffalo and Erie County, Inc.           | 2011-12-31T00:00:00  |               | Boudreau   |                | Dawn       | Compliance Officer         | Professional            |            | FT       | Y                | 0.00                   | 0.00               | 0.00          | 0.00              | 0.00      | 0.00               | 0.00               | Y                      | Y                                 | 
| ATC of Buffalo and Erie County, Inc.           | 2011-12-31T00:00:00  |               | Riggs      |                | Phil       | Facilities Site Management | Technical/Engineering   |            | FT       | Y                | 0.00                   | 0.00               | 0.00          | 0.00              | 0.00      | 0.00               | 0.00               | Y                      | Y                                 | 
| Albany County Business Development Corporation | 2011-12-31T00:00:00  |               | Heller     | R              | Lindsay    | Administrative Assistant   | Administrative/Clerical |            | PT       | N                | 0.00                   | 0.00               | 0.00          | 0.00              | 0.00      | 0.00               | 0.00               | Y                      |                                   | 
| Albany County Business Development Corporation | 2011-12-31T00:00:00  |               | Thompson   | J              | Christine  | Staff Accountant           | Professional            |            | PT       | Y                | 0.00                   | 0.00               | 0.00          | 0.00              | 0.00      | 0.00               | 0.00               | Y                      |                                   | 
| Albany County Business Development Corporation | 2011-12-31T00:00:00  |               | Catalano   | P              | Kevin      | Loan Portfolio Manager     | Professional            |            | PT       | Y                | 0.00                   | 0.00               | 0.00          | 0.00              | 0.00      | 0.00               | 0.00               | Y                      |                                   | 
```