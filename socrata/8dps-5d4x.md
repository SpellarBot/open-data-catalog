# Budget - 2012 Budget Recommendations - Appropriations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/budget-2012-budget-recommendations-appropriations-59d7b) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/8dps-5d4x) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/8dps-5d4x/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/8dps-5d4x/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | 8dps-5d4x |
| Name | Budget - 2012 Budget Recommendations - Appropriations |
| Attribution | City of Chicago |
| Category | Administration & Finance |
| Tags | budget, 2012 |
| Created | 2011-10-11T22:22:33Z |
| Publication Date | 2011-10-13T19:10:37Z |

## Description

The dataset details 2012 Budget Recommendations, which is the line-item budget document proposed by the Mayor to the City Council for approval. Budgeted expenditures are identified by department, appropriation account, and funding type: Local, Community Development Block Grant Program (CDBG), and other Grants. ?Local? funds refer to those line items that are balanced with locally-generated revenue sources, including but not limited to the Corporate Fund, Water Fund, Midway and O?Hare Airport funds, Vehicle Tax Fund, Library Fund and General Obligation Bond funds. Owner: Budget and Management. Frequency: Data is updated annually. For more information about the budget process, visit the Budget Documents page: http://j.mp/lPotWf.

## Columns

```ls
| Included | Schema Type    | Field Name                        | Name                                | Data Type | Render Type |
| ======== | ============== | ================================= | =================================== | ========= | =========== |
| Yes      | series tag     | fund_type                         | FUND TYPE                           | text      | text        |
| Yes      | series tag     | fund_code                         | FUND CODE                           | text      | text        |
| Yes      | series tag     | fund_description                  | FUND DESCRIPTION                    | text      | text        |
| Yes      | series tag     | department_code                   | DEPARTMENT NUMBER                   | text      | number      |
| Yes      | series tag     | department_description            | DEPARTMENT DESCRIPTION              | text      | text        |
| Yes      | numeric metric | org                               | APPROPRIATION AUTHORITY             | number    | number      |
| Yes      | series tag     | org_description                   | APPROPRIATION AUTHORITY DESCRIPTION | text      | text        |
| Yes      | series tag     | appropriation_account             | APPROPRIATION ACCOUNT               | text      | number      |
| Yes      | series tag     | appropriation_account_description | APPROPRIATION ACCOUNT DESCRIPTION   | text      | text        |
| Yes      | numeric metric | appropriation                     | 2011 APPROPRIATION                  | money     | money       |
| Yes      | numeric metric | revised_appropriation             | 2011 REVISED APPROPRIATION          | money     | money       |
| Yes      | numeric metric | recommendation                    | 2012 RECOMMENDATION                 | money     | money       |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:8dps-5d4x d:2012-01-01T00:00:00.000Z t:department_description="OFFICE OF THE MAYOR" t:fund_code=100 t:fund_type=LOCAL t:appropriation_account=229 t:appropriation_account_description="TRAN/EXP ALLOWANCE" t:department_code=1 t:org_description="2005 - OFFICE OF THE MAYOR" t:fund_description="CORPORATE FUND" m:appropriation=680 m:revised_appropriation=680 m:recommendation=680 m:org=2005

series e:8dps-5d4x d:2012-01-01T00:00:00.000Z t:department_description="OFFICE OF THE MAYOR" t:fund_code=100 t:fund_type=LOCAL t:appropriation_account=270 t:appropriation_account_description="LOCAL TRANSPORTATION" t:department_code=1 t:org_description="2005 - OFFICE OF THE MAYOR" t:fund_description="CORPORATE FUND" m:appropriation=872 m:revised_appropriation=872 m:recommendation=872 m:org=2005

series e:8dps-5d4x d:2012-01-01T00:00:00.000Z t:department_description="OFFICE OF THE MAYOR" t:fund_code=100 t:fund_type=LOCAL t:appropriation_account=150 t:appropriation_account_description="PUBLICATN & REPRODT-OUT" t:department_code=1 t:org_description="2005 - OFFICE OF THE MAYOR" t:fund_description="CORPORATE FUND" m:appropriation=1242 m:revised_appropriation=1242 m:recommendation=1000 m:org=2005
```

## Meta Commands

```ls
metric m:org p:integer l:"APPROPRIATION AUTHORITY" t:dataTypeName=number

metric m:appropriation p:integer l:"2011 APPROPRIATION" t:dataTypeName=money

metric m:revised_appropriation p:integer l:"2011 REVISED APPROPRIATION" t:dataTypeName=money

metric m:recommendation p:integer l:"2012 RECOMMENDATION" t:dataTypeName=money

entity e:8dps-5d4x l:"Budget - 2012 Budget Recommendations - Appropriations" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/8dps-5d4x

property e:8dps-5d4x t:meta.view v:id=8dps-5d4x v:category="Administration & Finance" v:attributionLink=http://www.cityofchicago.org/budget v:averageRating=0 v:name="Budget - 2012 Budget Recommendations - Appropriations" v:attribution="City of Chicago"

property e:8dps-5d4x t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:8dps-5d4x t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| fund_type | fund_code | fund_description | department_code | department_description | org  | org_description            | appropriation_account | appropriation_account_description | appropriation | revised_appropriation | recommendation | 
| ========= | ========= | ================ | =============== | ====================== | ==== | ========================== | ===================== | ================================= | ============= | ===================== | ============== | 
| LOCAL     | 100       | CORPORATE FUND   | 1               | OFFICE OF THE MAYOR    | 2005 | 2005 - OFFICE OF THE MAYOR | 229                   | TRAN/EXP ALLOWANCE                | 680           | 680                   | 680            | 
| LOCAL     | 100       | CORPORATE FUND   | 1               | OFFICE OF THE MAYOR    | 2005 | 2005 - OFFICE OF THE MAYOR | 270                   | LOCAL TRANSPORTATION              | 872           | 872                   | 872            | 
| LOCAL     | 100       | CORPORATE FUND   | 1               | OFFICE OF THE MAYOR    | 2005 | 2005 - OFFICE OF THE MAYOR | 150                   | PUBLICATN & REPRODT-OUT           | 1242          | 1242                  | 1000           | 
| LOCAL     | 100       | CORPORATE FUND   | 1               | OFFICE OF THE MAYOR    | 2005 | 2005 - OFFICE OF THE MAYOR | 126                   | OFFICE CONVENIENCES               | 1310          | 1310                  | 1200           | 
| LOCAL     | 100       | CORPORATE FUND   | 1               | OFFICE OF THE MAYOR    | 2005 | 2005 - OFFICE OF THE MAYOR | 196                   | DATA CIRCUITS                     | 0             | 0                     | 3800           | 
| LOCAL     | 100       | CORPORATE FUND   | 1               | OFFICE OF THE MAYOR    | 2005 | 2005 - OFFICE OF THE MAYOR | 169                   | TECHNICAL MEETING COSTS           | 5286          | 5286                  | 5286           | 
| LOCAL     | 100       | CORPORATE FUND   | 1               | OFFICE OF THE MAYOR    | 2005 | 2005 - OFFICE OF THE MAYOR | 162                   | REPAIR/MAINT EQUIPMENT            | 6984          | 6984                  | 6984           | 
| LOCAL     | 100       | CORPORATE FUND   | 1               | OFFICE OF THE MAYOR    | 2005 | 2005 - OFFICE OF THE MAYOR | 166                   | DUES SUBSC & MEM                  | 0             | 0                     | 18500          | 
| LOCAL     | 100       | CORPORATE FUND   | 1               | OFFICE OF THE MAYOR    | 2005 | 2005 - OFFICE OF THE MAYOR | 245                   | REIMBURSEMENT TRAVELERS           | 23280         | 23280                 | 23280          | 
| LOCAL     | 100       | CORPORATE FUND   | 1               | OFFICE OF THE MAYOR    | 2005 | 2005 - OFFICE OF THE MAYOR | 130                   | POSTAGE                           | 30918         | 30918                 | 23400          | 
```