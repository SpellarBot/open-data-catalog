# Community College Revenue By Fund And Object Code

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/community-college-revenue-by-fund-and-object-code) |
| Metadata | [Link](https://data.iowa.gov/api/views/k7vg-hfw6) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/k7vg-hfw6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/k7vg-hfw6/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | k7vg-hfw6 |
| Name | Community College Revenue By Fund And Object Code |
| Attribution | Iowa Department of Education, Community College Data Reporting |
| Category | Education |
| Tags | community colleges, revenue, educational programs, property repair, property replacement |
| Created | 2015-04-07T15:29:35Z |
| Publication Date | 2015-04-07T15:37:49Z |

## Description

This dataset provides revenue information for community colleges by fund and object code.  Information on the following funds is included in this dataset: Unrestricted General Fund, Restricted General Fund and Plant Fund.

Organizational units financed through the unrestricted general fund are those which are directly related with the operation and support of the educational program of the college.  The restricted general fund is used to account for resources that are available for the operation and support of the educational program, but which are restricted as to their use.  Some examples include: Tort Liability, Unemployment Compensation, direct Federal grants, Chapter 260E Industrial New Jobs Training activities and Iowa Values Fund.

The plant fund is used for the acquisition or construction of physical property related to major repair and/or replacement of community college property.  It may also be used for interest and principal payments and other debt service charges.
 
More information regarding community college funds and object code descriptions can be found in the Iowa Community College Accounting Manual here: https://www.educateiowa.gov/sites/files/ed/documents/Final%2010ccAccounting%20ManualFinalrevisedJuly2009.pdf

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type | Render Type |
| ======== | ============== | ==================== | ==================== | ========= | =========== |
| Yes      | time           | fiscal_year          | Fiscal Year          | number    | number      |
| Yes      | series tag     | community_college    | Community College    | text      | text        |
| Yes      | series tag     | college_abbreviation | College Abbreviation | text      | text        |
| Yes      | series tag     | fund_number          | Fund Number          | text      | number      |
| Yes      | series tag     | fund_name            | Fund Name            | text      | text        |
| Yes      | series tag     | class                | Class                | text      | text        |
| Yes      | series tag     | object_code          | Object Code          | text      | number      |
| Yes      | series tag     | object_code_name     | Object Code Name     | text      | text        |
| Yes      | numeric metric | amount               | Amount               | money     | money       |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:k7vg-hfw6 d:2013-01-01T00:00:00.000Z t:fund_name="Unrestricted General Fund" t:fund_number=1 t:college_abbreviation=01-NICC t:community_college="Northeast Iowa Community College" t:class="Student Fees" t:object_code_name="Laboratory Fees" t:object_code=401 m:amount=0

series e:k7vg-hfw6 d:2013-01-01T00:00:00.000Z t:fund_name="Unrestricted General Fund" t:fund_number=1 t:college_abbreviation=01-NICC t:community_college="Northeast Iowa Community College" t:class="Student Fees" t:object_code_name="Application Fees" t:object_code=402 m:amount=0

series e:k7vg-hfw6 d:2013-01-01T00:00:00.000Z t:fund_name="Unrestricted General Fund" t:fund_number=1 t:college_abbreviation=01-NICC t:community_college="Northeast Iowa Community College" t:class="Student Fees" t:object_code_name="Graduation Fees" t:object_code=403 m:amount=0
```

## Meta Commands

```ls
metric m:amount p:integer l:Amount d:"Revenue received" t:dataTypeName=money

entity e:k7vg-hfw6 l:"Community College Revenue By Fund And Object Code" t:attribution="Iowa Department of Education, Community College Data Reporting" t:url=https://data.iowa.gov/api/views/k7vg-hfw6

property e:k7vg-hfw6 t:meta.view v:id=k7vg-hfw6 v:category=Education v:averageRating=0 v:name="Community College Revenue By Fund And Object Code" v:attribution="Iowa Department of Education, Community College Data Reporting"

property e:k7vg-hfw6 t:meta.view.owner v:id=hthm-474y v:profileImageUrlMedium=/api/users/hthm-474y/profile_images/THUMB v:profileImageUrlLarge=/api/users/hthm-474y/profile_images/LARGE v:screenName="Iowa Department of Education" v:profileImageUrlSmall=/api/users/hthm-474y/profile_images/TINY v:displayName="Iowa Department of Education"

property e:k7vg-hfw6 t:meta.view.tableauthor v:id=hthm-474y v:profileImageUrlMedium=/api/users/hthm-474y/profile_images/THUMB v:profileImageUrlLarge=/api/users/hthm-474y/profile_images/LARGE v:screenName="Iowa Department of Education" v:profileImageUrlSmall=/api/users/hthm-474y/profile_images/TINY v:roleName=editor v:displayName="Iowa Department of Education"
```

## Top Records

```ls
| fiscal_year | community_college                | college_abbreviation | fund_number | fund_name                 | class        | object_code | object_code_name                 | amount   | 
| =========== | ================================ | ==================== | =========== | ========================= | ============ | =========== | ================================ | ======== | 
| 2013        | Northeast Iowa Community College | 01-NICC              | 1           | Unrestricted General Fund | Student Fees | 401         | Laboratory Fees                  | 0        | 
| 2013        | Northeast Iowa Community College | 01-NICC              | 1           | Unrestricted General Fund | Student Fees | 402         | Application Fees                 | 0        | 
| 2013        | Northeast Iowa Community College | 01-NICC              | 1           | Unrestricted General Fund | Student Fees | 403         | Graduation Fees                  | 0        | 
| 2013        | Northeast Iowa Community College | 01-NICC              | 1           | Unrestricted General Fund | Student Fees | 404         | Transcript Fees                  | 315      | 
| 2013        | Northeast Iowa Community College | 01-NICC              | 1           | Unrestricted General Fund | Student Fees | 405         | Activity Fees                    | 0        | 
| 2013        | Northeast Iowa Community College | 01-NICC              | 1           | Unrestricted General Fund | Student Fees | 406         | Other Fees                       | 584870   | 
| 2013        | Northeast Iowa Community College | 01-NICC              | 1           | Unrestricted General Fund | Student Fees | 407         | Fee Refunds                      | 0        | 
| 2013        | Northeast Iowa Community College | 01-NICC              | 1           | Unrestricted General Fund | Tuition      | 410         | Contracted Instructional Charges | 1253230  | 
| 2013        | Northeast Iowa Community College | 01-NICC              | 1           | Unrestricted General Fund | Tuition      | 411         | Resident Tuition                 | 12933135 | 
| 2013        | Northeast Iowa Community College | 01-NICC              | 1           | Unrestricted General Fund | Tuition      | 412         | Non-Resident Tuition             | 1773984  | 
```