# Budget - 2013 Budget Recommendations - Appropriations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/budget-2013-budget-recommendations-appropriations-284c8) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/d6tb-pwze) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/d6tb-pwze/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/d6tb-pwze/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | d6tb-pwze |
| Name | Budget - 2013 Budget Recommendations - Appropriations |
| Attribution | City of Chicago |
| Category | Administration & Finance |
| Tags | budget, 2013 |
| Created | 2012-10-09T17:47:19Z |
| Publication Date | 2012-10-09T17:52:13Z |

## Description

The dataset details 2013 Budget Recommendations, which is the line-item budget document proposed by the Mayor to the City Council for approval. Budgeted expenditures are identified by department, appropriation account, and funding type: Local, Community Development Block Grant Program (CDBG), and other Grants. ?Local? funds refer to those line items that are balanced with locally-generated revenue sources, including but not limited to the Corporate Fund, Water Fund, Midway and O?Hare Airport funds, Vehicle Tax Fund, Library Fund and General Obligation Bond funds. Owner: Budget and Management. Frequency: Data is updated annually. For more information about the budget process, visit the Budget Documents page: http://j.mp/lPotWf.

## Columns

```ls
| Included | Schema Type    | Field Name                          | Name                                | Data Type | Render Type |
| ======== | ============== | =================================== | =================================== | ========= | =========== |
| Yes      | series tag     | fund_type                           | FUND TYPE                           | text      | text        |
| Yes      | series tag     | fund_code                           | FUND CODE                           | text      | text        |
| Yes      | series tag     | fund_description                    | FUND DESCRIPTION                    | text      | text        |
| Yes      | series tag     | department_number                   | DEPARTMENT NUMBER                   | text      | number      |
| Yes      | series tag     | department_description              | DEPARTMENT DESCRIPTION              | text      | text        |
| Yes      | series tag     | appropriation_authority             | APPROPRIATION AUTHORITY             | text      | number      |
| Yes      | series tag     | appropriation_authority_description | APPROPRIATION AUTHORITY DESCRIPTION | text      | text        |
| Yes      | series tag     | appropriation_account               | APPROPRIATION ACCOUNT               | text      | number      |
| Yes      | series tag     | appropriation_account_description   | APPROPRIATION ACCOUNT DESCRIPTION   | text      | text        |
| Yes      | numeric metric | appropration                        | 2012 APPROPRATION                   | money     | money       |
| Yes      | numeric metric | revised_appropriation               | 2012 REVISED APPROPRIATION          | money     | money       |
| Yes      | numeric metric | recommendation                      | 2013 RECOMMENDATION                 | money     | money       |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:d6tb-pwze d:2013-01-01T00:00:00.000Z t:department_description="OFFICE OF THE MAYOR" t:fund_code=100 t:fund_type=LOCAL t:appropriation_account=5 t:appropriation_authority_description="2005 - OFFICE OF THE MAYOR" t:appropriation_authority=2005 t:department_number=1 t:appropriation_account_description="SALARIES AND WAGES - ON PAYROLL" t:fund_description="CORPORATE FUND" m:appropration=5142155 m:revised_appropriation=5142155 m:recommendation=5322699

series e:d6tb-pwze d:2013-01-01T00:00:00.000Z t:department_description="OFFICE OF THE MAYOR" t:fund_code=100 t:fund_type=LOCAL t:appropriation_account=126 t:appropriation_authority_description="2005 - OFFICE OF THE MAYOR" t:appropriation_authority=2005 t:department_number=1 t:appropriation_account_description="OFFICE CONVENIENCES" t:fund_description="CORPORATE FUND" m:appropration=1200 m:revised_appropriation=1200 m:recommendation=1200

series e:d6tb-pwze d:2013-01-01T00:00:00.000Z t:department_description="OFFICE OF THE MAYOR" t:fund_code=100 t:fund_type=LOCAL t:appropriation_account=130 t:appropriation_authority_description="2005 - OFFICE OF THE MAYOR" t:appropriation_authority=2005 t:department_number=1 t:appropriation_account_description=POSTAGE t:fund_description="CORPORATE FUND" m:appropration=23400 m:revised_appropriation=23400 m:recommendation=18000
```

## Meta Commands

```ls
metric m:appropration p:long l:"2012 APPROPRATION" t:dataTypeName=money

metric m:revised_appropriation p:long l:"2012 REVISED APPROPRIATION" t:dataTypeName=money

metric m:recommendation p:long l:"2013 RECOMMENDATION" t:dataTypeName=money

entity e:d6tb-pwze l:"Budget - 2013 Budget Recommendations - Appropriations" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/d6tb-pwze

property e:d6tb-pwze t:meta.view v:id=d6tb-pwze v:category="Administration & Finance" v:attributionLink=http://www.cityofchicago.org/budget v:averageRating=0 v:name="Budget - 2013 Budget Recommendations - Appropriations" v:attribution="City of Chicago"

property e:d6tb-pwze t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:d6tb-pwze t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| fund_type | fund_code | fund_description | department_number | department_description | appropriation_authority | appropriation_authority_description | appropriation_account | appropriation_account_description | appropration | revised_appropriation | recommendation | 
| ========= | ========= | ================ | ================= | ====================== | ======================= | =================================== | ===================== | ================================= | ============ | ===================== | ============== | 
| LOCAL     | 100       | CORPORATE FUND   | 1                 | OFFICE OF THE MAYOR    | 2005                    | 2005 - OFFICE OF THE MAYOR          | 5                     | SALARIES AND WAGES - ON PAYROLL   | 5142155      | 5142155               | 5322699        | 
| LOCAL     | 100       | CORPORATE FUND   | 1                 | OFFICE OF THE MAYOR    | 2005                    | 2005 - OFFICE OF THE MAYOR          | 126                   | OFFICE CONVENIENCES               | 1200         | 1200                  | 1200           | 
| LOCAL     | 100       | CORPORATE FUND   | 1                 | OFFICE OF THE MAYOR    | 2005                    | 2005 - OFFICE OF THE MAYOR          | 130                   | POSTAGE                           | 23400        | 23400                 | 18000          | 
| LOCAL     | 100       | CORPORATE FUND   | 1                 | OFFICE OF THE MAYOR    | 2005                    | 2005 - OFFICE OF THE MAYOR          | 150                   | PUBLICATN & REPRODT-OUT           | 1000         | 1000                  | 1000           | 
| LOCAL     | 100       | CORPORATE FUND   | 1                 | OFFICE OF THE MAYOR    | 2005                    | 2005 - OFFICE OF THE MAYOR          | 157                   | RENTAL EQUIPMENT AND SERVICES     | 49500        | 49500                 | 49500          | 
| LOCAL     | 100       | CORPORATE FUND   | 1                 | OFFICE OF THE MAYOR    | 2005                    | 2005 - OFFICE OF THE MAYOR          | 159                   | LEASE PURCHASE AGREEMNT           | 63500        | 63500                 | 63500          | 
| LOCAL     | 100       | CORPORATE FUND   | 1                 | OFFICE OF THE MAYOR    | 2005                    | 2005 - OFFICE OF THE MAYOR          | 162                   | REPAIR/MAINT EQUIPMENT            | 6984         | 6984                  | 6984           | 
| LOCAL     | 100       | CORPORATE FUND   | 1                 | OFFICE OF THE MAYOR    | 2005                    | 2005 - OFFICE OF THE MAYOR          | 166                   | DUES SUBSC & MEM                  | 18500        | 18500                 | 18500          | 
| LOCAL     | 100       | CORPORATE FUND   | 1                 | OFFICE OF THE MAYOR    | 2005                    | 2005 - OFFICE OF THE MAYOR          | 169                   | TECHNICAL MEETING COSTS           | 5286         | 5286                  | 5286           | 
| LOCAL     | 100       | CORPORATE FUND   | 1                 | OFFICE OF THE MAYOR    | 2005                    | 2005 - OFFICE OF THE MAYOR          | 181                   | MOBILE COMM SERVICES              | 39730        | 39730                 | 47400          | 
```