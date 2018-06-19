# Budget - 2011 Budget Ordinance - Appropriations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/budget-2011-budget-ordinance-appropriations-a9fb6) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/drv3-jzqp) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/drv3-jzqp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/drv3-jzqp/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | drv3-jzqp |
| Name | Budget - 2011 Budget Ordinance - Appropriations |
| Attribution | City of Chicago |
| Category | Administration & Finance |
| Tags | budget |
| Created | 2011-05-24T20:31:12Z |
| Publication Date | 2011-05-24T20:31:13Z |

## Description

The Annual Appropriation Ordinance is the final City operating budget as approved by the City Council. It reflects the City?s operating budget at the beginning of the fiscal year on January 1. This dataset details the budgeted expenditures in the Ordinance and identifies them by department, appropriation account, and funding type: Local, Community Development Block Grant Program (CDBG), and other Grants.  ?Local? funds refer to those line items that are balanced with locally generated revenue sources, including but not limited to the Corporate Fund, Water Fund, Midway and O?Hare Airport funds, Vehicle Tax Fund, Library Fund and General Obligation Bond funds. Owner: Budget and Management. Frequency: Data is updated annually. For more information about the budget process, visit the Budget Documents page: http://j.mp/lPotWf.

## Columns

```ls
| Included | Schema Type    | Field Name                          | Name                                | Data Type | Render Type |
| ======== | ============== | =================================== | =================================== | ========= | =========== |
| Yes      | series tag     | fund_type                           | FUND TYPE                           | text      | text        |
| Yes      | series tag     | fund_code                           | FUND CODE                           | text      | text        |
| Yes      | series tag     | fund_description                    | FUND DESCRIPTION                    | text      | text        |
| Yes      | series tag     | department_number                   | DEPARTMENT NUMBER                   | text      | number      |
| Yes      | series tag     | department                          | DEPARTMENT                          | text      | text        |
| Yes      | series tag     | department_description              | DEPARTMENT DESCRIPTION              | text      | text        |
| Yes      | series tag     | appropriation_authority             | APPROPRIATION AUTHORITY             | text      | number      |
| Yes      | series tag     | appropriation_authority_description | APPROPRIATION AUTHORITY DESCRIPTION | text      | text        |
| Yes      | series tag     | appropriation_account               | APPROPRIATION ACCOUNT               | text      | number      |
| Yes      | series tag     | appropriation_account_description   | APPROPRIATION ACCOUNT DESCRIPTION   | text      | text        |
| Yes      | numeric metric | amount                              | AMOUNT                              | money     | money       |
```

## Time Field

```ls
Value = 2011
Format & Zone = yyyy
```

## Data Commands

```ls
series e:drv3-jzqp d:2011-01-01T00:00:00.000Z t:department_description="POLICE BOARD" t:fund_code=100 t:fund_type=LOCAL t:appropriation_account=50 t:appropriation_authority_description="2005 - POLICE BOARD" t:department=PB t:appropriation_authority=2005 t:department_number=55 t:appropriation_account_description=STIPENDS t:fund_description="CORPORATE FUND" m:amount=145000

series e:drv3-jzqp d:2011-01-01T00:00:00.000Z t:department_description="POLICE BOARD" t:fund_code=100 t:fund_type=LOCAL t:appropriation_account=130 t:appropriation_authority_description="2005 - POLICE BOARD" t:department=PB t:appropriation_authority=2005 t:department_number=55 t:appropriation_account_description=POSTAGE t:fund_description="CORPORATE FUND" m:amount=300

series e:drv3-jzqp d:2011-01-01T00:00:00.000Z t:department_description="BOARD OF ELECTION COMMISSIONER" t:fund_code=100 t:fund_type=LOCAL t:appropriation_account=5 t:appropriation_authority_description="2005 - ELECTION AND ADMIN DIVISION" t:department=BOEC t:appropriation_authority=2005 t:department_number=39 t:appropriation_account_description="SALARIES AND WAGES - ON PAYROLL" t:fund_description="CORPORATE FUND" m:amount=6831849
```

## Meta Commands

```ls
metric m:amount p:double l:AMOUNT t:dataTypeName=money

entity e:drv3-jzqp l:"Budget - 2011 Budget Ordinance - Appropriations" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/drv3-jzqp

property e:drv3-jzqp t:meta.view v:id=drv3-jzqp v:category="Administration & Finance" v:attributionLink=http://www.cityofchicago.org/city/en/depts/obm/provdrs/city_budg.html v:averageRating=0 v:name="Budget - 2011 Budget Ordinance - Appropriations" v:attribution="City of Chicago"

property e:drv3-jzqp t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:drv3-jzqp t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| fund_type | fund_code | fund_description | department_number | department | department_description         | appropriation_authority | appropriation_authority_description | appropriation_account | appropriation_account_description        | amount     | 
| ========= | ========= | ================ | ================= | ========== | ============================== | ======================= | =================================== | ===================== | ======================================== | ========== | 
| LOCAL     | 100       | CORPORATE FUND   | 55                | PB         | POLICE BOARD                   | 2005                    | 2005 - POLICE BOARD                 | 50                    | STIPENDS                                 | 145000.00  | 
| LOCAL     | 100       | CORPORATE FUND   | 55                | PB         | POLICE BOARD                   | 2005                    | 2005 - POLICE BOARD                 | 130                   | POSTAGE                                  | 300.00     | 
| LOCAL     | 100       | CORPORATE FUND   | 39                | BOEC       | BOARD OF ELECTION COMMISSIONER | 2005                    | 2005 - ELECTION AND ADMIN DIVISION  | 5                     | SALARIES AND WAGES - ON PAYROLL          | 6831849.00 | 
| LOCAL     | 100       | CORPORATE FUND   | 39                | BOEC       | BOARD OF ELECTION COMMISSIONER | 2005                    | 2005 - ELECTION AND ADMIN DIVISION  | 15                    | SCHEDULE SALARY ADJ                      | 27342.00   | 
| LOCAL     | 100       | CORPORATE FUND   | 39                | BOEC       | BOARD OF ELECTION COMMISSIONER | 2005                    | 2005 - ELECTION AND ADMIN DIVISION  | 30                    | LESS SALARY SAVINGS FROM UNPAID TIME OFF | -607288.00 | 
| LOCAL     | 100       | CORPORATE FUND   | 39                | BOEC       | BOARD OF ELECTION COMMISSIONER | 2005                    | 2005 - ELECTION AND ADMIN DIVISION  | 130                   | POSTAGE                                  | 366256.00  | 
| LOCAL     | 100       | CORPORATE FUND   | 39                | BOEC       | BOARD OF ELECTION COMMISSIONER | 2005                    | 2005 - ELECTION AND ADMIN DIVISION  | 138                   | PROF SERV-IT MAINT                       | 703500.00  | 
| LOCAL     | 100       | CORPORATE FUND   | 39                | BOEC       | BOARD OF ELECTION COMMISSIONER | 2005                    | 2005 - ELECTION AND ADMIN DIVISION  | 140                   | PROF & TECHNICAL SERVICES                | 432800.00  | 
| LOCAL     | 100       | CORPORATE FUND   | 39                | BOEC       | BOARD OF ELECTION COMMISSIONER | 2005                    | 2005 - ELECTION AND ADMIN DIVISION  | 143                   | COURT REPORTING                          | 80000.00   | 
| LOCAL     | 100       | CORPORATE FUND   | 39                | BOEC       | BOARD OF ELECTION COMMISSIONER | 2005                    | 2005 - ELECTION AND ADMIN DIVISION  | 145                   | LEGAL EXPENSES                           | 1055200.00 | 
```