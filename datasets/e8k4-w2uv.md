# Community College Expenditures By Fund and Object Code

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/community-college-expenditures-by-fund-and-object-code) |
| Metadata | [Link](https://data.iowa.gov/api/views/e8k4-w2uv) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/e8k4-w2uv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/e8k4-w2uv/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | e8k4-w2uv |
| Name | Community College Expenditures By Fund and Object Code |
| Attribution | Iowa Department of Education, Community College Data Reporting |
| Category | Education |
| Tags | community colleges, expenditures, educational programs, property repair, property replacement |
| Created | 2015-04-07T15:17:40Z |
| Publication Date | 2015-04-07T15:26:46Z |

## Description

This dataset provides expenditure information for community colleges by fund and object code.  Information on the following funds is included in this dataset: Unrestricted General Fund, Restricted General Fund and Plant Fund.

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
series e:e8k4-w2uv d:2013-01-01T00:00:00.000Z t:fund_name="Unrestricted General Fund" t:fund_number=1 t:college_abbreviation=01-NICC t:community_college="Northeast Iowa Community College" t:class=Salaries t:object_code_name=Administrative t:object_code=510 m:amount=928925

series e:e8k4-w2uv d:2013-01-01T00:00:00.000Z t:fund_name="Unrestricted General Fund" t:fund_number=1 t:college_abbreviation=01-NICC t:community_college="Northeast Iowa Community College" t:class=Salaries t:object_code_name="Administrative - Part-time" t:object_code=511 m:amount=700

series e:e8k4-w2uv d:2013-01-01T00:00:00.000Z t:fund_name="Unrestricted General Fund" t:fund_number=1 t:college_abbreviation=01-NICC t:community_college="Northeast Iowa Community College" t:class=Salaries t:object_code_name=Instructional t:object_code=520 m:amount=6720665
```

## Meta Commands

```ls
metric m:amount p:integer l:Amount d:"Disbursements made" t:dataTypeName=money

entity e:e8k4-w2uv l:"Community College Expenditures By Fund and Object Code" t:attribution="Iowa Department of Education, Community College Data Reporting" t:url=https://data.iowa.gov/api/views/e8k4-w2uv

property e:e8k4-w2uv t:meta.view v:id=e8k4-w2uv v:category=Education v:averageRating=0 v:name="Community College Expenditures By Fund and Object Code" v:attribution="Iowa Department of Education, Community College Data Reporting"

property e:e8k4-w2uv t:meta.view.owner v:id=hthm-474y v:profileImageUrlMedium=/api/users/hthm-474y/profile_images/THUMB v:profileImageUrlLarge=/api/users/hthm-474y/profile_images/LARGE v:screenName="Iowa Department of Education" v:profileImageUrlSmall=/api/users/hthm-474y/profile_images/TINY v:displayName="Iowa Department of Education"

property e:e8k4-w2uv t:meta.view.tableauthor v:id=hthm-474y v:profileImageUrlMedium=/api/users/hthm-474y/profile_images/THUMB v:profileImageUrlLarge=/api/users/hthm-474y/profile_images/LARGE v:screenName="Iowa Department of Education" v:profileImageUrlSmall=/api/users/hthm-474y/profile_images/TINY v:roleName=editor v:displayName="Iowa Department of Education"
```

## Top Records

```ls
| fiscal_year | community_college                | college_abbreviation | fund_number | fund_name                 | class    | object_code | object_code_name                   | amount  | 
| =========== | ================================ | ==================== | =========== | ========================= | ======== | =========== | ================================== | ======= | 
| 2013        | Northeast Iowa Community College | 01-NICC              | 1           | Unrestricted General Fund | Salaries | 510         | Administrative                     | 928925  | 
| 2013        | Northeast Iowa Community College | 01-NICC              | 1           | Unrestricted General Fund | Salaries | 511         | Administrative - Part-time         | 700     | 
| 2013        | Northeast Iowa Community College | 01-NICC              | 1           | Unrestricted General Fund | Salaries | 520         | Instructional                      | 6720665 | 
| 2013        | Northeast Iowa Community College | 01-NICC              | 1           | Unrestricted General Fund | Salaries | 521         | Instructional - Part-time          | 1536203 | 
| 2013        | Northeast Iowa Community College | 01-NICC              | 1           | Unrestricted General Fund | Salaries | 522         | Instructional - Adjunct            | 1644895 | 
| 2013        | Northeast Iowa Community College | 01-NICC              | 1           | Unrestricted General Fund | Salaries | 530         | Professional                       | 3397020 | 
| 2013        | Northeast Iowa Community College | 01-NICC              | 1           | Unrestricted General Fund | Salaries | 531         | Professional - Part-time           | 284586  | 
| 2013        | Northeast Iowa Community College | 01-NICC              | 1           | Unrestricted General Fund | Salaries | 540         | Secretarial & Clerical             | 1375200 | 
| 2013        | Northeast Iowa Community College | 01-NICC              | 1           | Unrestricted General Fund | Salaries | 541         | Secretarial & Clerical - Part-time | 281809  | 
| 2013        | Northeast Iowa Community College | 01-NICC              | 1           | Unrestricted General Fund | Salaries | 550         | Service Staff                      | 492305  | 
```