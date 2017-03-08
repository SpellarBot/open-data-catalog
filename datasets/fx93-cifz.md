# Salary Information for Local Authorities

## Dataset

* [Dataset URL](https://data.ny.gov/api/views/fx93-cifz/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/salary-information-for-local-authorities)
* [Metadata URL](https://data.ny.gov/api/views/fx93-cifz)
* Id = fx93-cifz
* Name = Salary Information for Local Authorities
* Attribution = Individual Local Authorities submitted to Authorities Budget Office
* [Attribution Link](http://www.abo.ny.gov/)
* Category = Transparency
* Tags = [public authority, local authority, personnel, employee, salaries/payroll]
* Created = 2014-09-10T15:07:57Z
* Publication Date = 2016-10-12T15:59:53Z
* Rows Updated = 2016-10-11T23:07:06Z

## Description

Public authorities are required by Section 2800 of Public Authorities Law to submit annual reports to the Authorities Budget Office that include salary and compensation data.  The dataset consists of salary data by employee reported by Local Authorities beginning with fiscal years ending in 2011.

## Columns

```ls
| Name                              | Field Name                        | Data Type     | Render Type   | Schema Type    | Included | 
| ================================= | ================================= | ============= | ============= | ============== | ======== | 
| Authority Name                    | authority_name                    | text          | text          | series tag     | Yes      | 
| Fiscal Year End Date              | fiscal_year_end_date              | calendar_date | calendar_date | time           | Yes      | 
| Has Employees                     | has_employees                     | number        | text          | numeric metric | Yes      | 
| Last Name                         | last_name                         | text          | text          | series tag     | Yes      | 
| Middle Initial                    | middle_initial                    | number        | text          | numeric metric | Yes      | 
| First Name                        | first_name                        | text          | text          | series tag     | Yes      | 
| Title                             | title                             | text          | text          | series tag     | Yes      | 
| Group                             | group                             | text          | text          | series tag     | Yes      | 
| Department                        | department                        | text          | text          | series tag     | Yes      | 
| Pay Type                          | pay_type                          | text          | text          | series tag     | Yes      | 
| Exempt Indicator                  | exempt_indicator                  | number        | text          | numeric metric | Yes      | 
| Base Annualized Salary            | base_annualized_salary            | money         | money         | numeric metric | Yes      | 
| Actual Salary Paid                | actual_salary_paid                | money         | money         | numeric metric | Yes      | 
| Overtime Paid                     | overtime_paid                     | money         | money         | numeric metric | Yes      | 
| Performance Bonus                 | performance_bonus                 | money         | money         | numeric metric | Yes      | 
| Extra Pay                         | extra_pay                         | money         | money         | numeric metric | Yes      | 
| Other Compensation                | other_compensation                | money         | money         | numeric metric | Yes      | 
| Total Compensation                | total_compensation                | money         | money         | numeric metric | Yes      | 
| Paid By Another Entity            | paid_by_another_entity            | number        | text          | numeric metric | Yes      | 
| Paid by State or Local Government | paid_by_state_or_local_government | number        | text          | numeric metric | Yes      | 
```

## Time Field

```ls
Value = fiscal_year_end_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = 
Annotation Fields = 
```

## Data Commands

```ls
series e:fx93-cifz d:2011-12-31T00:00:00.000Z t:authority_name="Albany Community Development Agency" t:first_name=Kailin t:title="Community Development Specialist" t:pay_type=FT t:paid_by_another_entity=N t:last_name=Curtin t:exempt_indicator=N t:group=Professional m:total_compensation=26208 m:base_annualized_salary=26208 m:actual_salary_paid=26208 m:performance_bonus=0 m:overtime_paid=0 m:extra_pay=0 m:other_compensation=0

series e:fx93-cifz d:2011-12-31T00:00:00.000Z t:authority_name="Albany Community Development Agency" t:first_name=Nicole t:title="Senior Typist" t:pay_type=FT t:paid_by_another_entity=N t:last_name=DeMouth t:exempt_indicator=N t:group=Administrative/Clerical m:total_compensation=30073 m:base_annualized_salary=30073 m:actual_salary_paid=30073 m:performance_bonus=0 m:overtime_paid=0 m:extra_pay=0 m:other_compensation=0

series e:fx93-cifz d:2011-12-31T00:00:00.000Z t:authority_name="Albany Community Development Agency" t:first_name=Cameron t:title="Document Scanner" t:pay_type=FT t:paid_by_another_entity=N t:last_name=Holloway t:exempt_indicator=N t:group=Operational m:total_compensation=33277 m:base_annualized_salary=33277 m:actual_salary_paid=33277 m:performance_bonus=0 m:overtime_paid=0 m:extra_pay=0 m:other_compensation=0
```

## Meta Commands

```ls
metric m:has_employees l:"Has Employees" d:"N indicates that the authority reported having no staff. All the remaining fields are blank when authorities report having no staff." t:dataTypeName=number

metric m:paid_by_state_or_local_government l:"Paid by State or Local Government" d:"?Y? indicates that the individual was paid by a State or local government to perform the work of the Authority, and is blank otherwise. This field is completed only when the Paid by Another Entity field is ?Y?." t:dataTypeName=number

entity e:fx93-cifz l:"Salary Information for Local Authorities" t:attribution="Individual Local Authorities submitted to Authorities Budget Office" t:url=https://data.ny.gov/api/views/fx93-cifz

property e:fx93-cifz t:meta.view d:2017-03-07T19:53:10.012Z v:id=fx93-cifz v:category=Transparency v:attributionLink=http://www.abo.ny.gov/ v:averageRating=0 v:name="Salary Information for Local Authorities" v:attribution="Individual Local Authorities submitted to Authorities Budget Office"

property e:fx93-cifz t:meta.view.owner d:2017-03-07T19:53:10.012Z v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:fx93-cifz t:meta.view.tableauthor d:2017-03-07T19:53:10.012Z v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:fx93-cifz t:meta.view.metadata.custom_fields.common_core d:2017-03-07T19:53:10.012Z v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```