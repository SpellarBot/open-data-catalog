# General Fund Revenue

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/general-fund-revenue) |
| Metadata | [Link](https://data.lacity.org/api/views/qrkr-kfbh) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/qrkr-kfbh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/qrkr-kfbh/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | qrkr-kfbh |
| Name | General Fund Revenue |
| Category | A Prosperous City |
| Tags | budget, revenue |
| Created | 2016-07-11T14:10:40Z |
| Publication Date | 2017-08-04T18:35:29Z |

## Description

Revenue towards the City's general fund by department, program, and account.

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| No       | time           | :updated_at     | updated_at      | meta_data | meta_data   |
| Yes      | series tag     | dept_code       | Dept Code       | text      | text        |
| Yes      | series tag     | department_name | Department Name | text      | text        |
| Yes      | series tag     | program_code    | Program Code    | text      | text        |
| Yes      | numeric metric | program_name    | Program Name    | number    | text        |
| Yes      | series tag     | fund_code       | Fund Code       | text      | text        |
| Yes      | numeric metric | fund_name       | Fund Name       | number    | text        |
| Yes      | series tag     | account_code    | Account Code    | text      | text        |
| Yes      | series tag     | account_name    | Account Name    | text      | text        |
| Yes      | series tag     | fiscal_year     | Fiscal Year     | text      | text        |
| Yes      | numeric metric | revenue         | Revenue Amount  | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:qrkr-kfbh d:2017-08-04T18:35:07.000Z t:dept_code=10 t:program_code="Budget Formulation and Control" t:fiscal_year=2014_15_actuals t:department_name="City Administrative Officer" t:account_name=1.01001E+12 t:account_code="Contribution Fr La Marathon" t:fund_code="General Fund" m:revenue=434622 m:program_name=100 m:fund_name=5104

series e:qrkr-kfbh d:2017-08-04T18:35:07.000Z t:dept_code=10 t:program_code="Budget Formulation and Control" t:fiscal_year=2014_15_actuals t:department_name="City Administrative Officer" t:account_name=1.01001E+12 t:account_code="Miscellaneous Revenue-Others" t:fund_code="General Fund" m:revenue=30301 m:program_name=100 m:fund_name=5188

series e:qrkr-kfbh d:2017-08-04T18:35:07.000Z t:dept_code=10 t:program_code="Budget Formulation and Control" t:fiscal_year=2014_15_actuals t:department_name="City Administrative Officer" t:account_name=1.01001E+12 t:account_code="Reimb Prop F Animal Bond Fund" t:fund_code="General Fund" m:revenue=4774 m:program_name=100 m:fund_name=5319
```

## Meta Commands

```ls
metric m:program_name p:integer l:"Program Name" t:dataTypeName=number

metric m:fund_name p:integer l:"Fund Name" t:dataTypeName=number

metric m:revenue p:integer l:"Revenue Amount" t:dataTypeName=number

entity e:qrkr-kfbh l:"General Fund Revenue" t:url=https://data.lacity.org/api/views/qrkr-kfbh

property e:qrkr-kfbh t:meta.view d:2017-09-25T07:32:18.325Z v:averageRating=0 v:name="General Fund Revenue" v:id=qrkr-kfbh v:category="A Prosperous City"

property e:qrkr-kfbh t:meta.view.license d:2017-09-25T07:32:18.325Z v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:qrkr-kfbh t:meta.view.owner d:2017-09-25T07:32:18.325Z v:displayName=ChelseaU v:lastNotificationSeenAt=1500481753 v:profileImageUrlLarge=/api/users/95pg-i79k/profile_images/LARGE v:profileImageUrlSmall=/api/users/95pg-i79k/profile_images/TINY v:id=95pg-i79k v:screenName=ChelseaU v:profileImageUrlMedium=/api/users/95pg-i79k/profile_images/THUMB

property e:qrkr-kfbh t:meta.view.tableauthor d:2017-09-25T07:32:18.325Z v:displayName=ChelseaU v:lastNotificationSeenAt=1500481753 v:profileImageUrlLarge=/api/users/95pg-i79k/profile_images/LARGE v:roleName=administrator v:profileImageUrlSmall=/api/users/95pg-i79k/profile_images/TINY v:id=95pg-i79k v:screenName=ChelseaU v:profileImageUrlMedium=/api/users/95pg-i79k/profile_images/THUMB
```

## Top Records

```ls
| :updated_at | dept_code | department_name             | program_code                   | program_name | fund_code    | fund_name | account_code                    | account_name | fiscal_year     | revenue | 
| =========== | ========= | =========================== | ============================== | ============ | ============ | ========= | =============================== | ============ | =============== | ======= | 
| 1501871707  | 10        | City Administrative Officer | Budget Formulation and Control | 100          | General Fund | 5104      | Contribution Fr La Marathon     | 1.01001E+12  | 2014_15_actuals | 434622  | 
| 1501871707  | 10        | City Administrative Officer | Budget Formulation and Control | 100          | General Fund | 5188      | Miscellaneous Revenue-Others    | 1.01001E+12  | 2014_15_actuals | 30301   | 
| 1501871707  | 10        | City Administrative Officer | Budget Formulation and Control | 100          | General Fund | 5319      | Reimb Prop F Animal Bond Fund   | 1.01001E+12  | 2014_15_actuals | 4774    | 
| 1501871707  | 10        | City Administrative Officer | Budget Formulation and Control | 100          | General Fund | 5320      | Reimb Prop F Fire Bond Fund     | 1.01001E+12  | 2014_15_actuals | 4774    | 
| 1501871707  | 10        | City Administrative Officer | Budget Formulation and Control | 100          | General Fund | 5321      | Reimb Prop Q Police/Fire Fund   | 1.01001E+12  | 2014_15_actuals | 7587    | 
| 1501871707  | 10        | City Administrative Officer | Budget Formulation and Control | 100          | General Fund | 5322      | Proposition K Funds             | 1.01001E+12  | 2014_15_actuals | 97000   | 
| 1501871707  | 10        | City Administrative Officer | Budget Formulation and Control | 100          | General Fund | 5328      | Sewer Cons & Main Related Cost  | 1.01001E+12  | 2014_15_actuals | 427986  | 
| 1501871707  | 10        | City Administrative Officer | Budget Formulation and Control | 100          | General Fund | 5331      | Reimb Of Related Cost-Pr Yr     | 1.01001E+12  | 2014_15_actuals | 226651  | 
| 1501871707  | 10        | City Administrative Officer | Budget Formulation and Control | 100          | General Fund | 5340      | Prop C Antigridlock Rel Cost    | 1.01001E+12  | 2014_15_actuals | 11262   | 
| 1501871707  | 10        | City Administrative Officer | Budget Formulation and Control | 100          | General Fund | 5345      | Sanit Equip Chg Acq Fd Rel Cost | 1.01001E+12  | 2014_15_actuals | 49872   | 
```