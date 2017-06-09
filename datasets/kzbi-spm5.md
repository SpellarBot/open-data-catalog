# Budget - 2015 Budget Recommendations - Appropriations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/budget-2015-budget-recommendations-appropriations-68f61) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/kzbi-spm5) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/kzbi-spm5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/kzbi-spm5/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | kzbi-spm5 |
| Name | Budget - 2015 Budget Recommendations - Appropriations |
| Attribution | City of Chicago |
| Category | Administration & Finance |
| Tags | budget, 2015 |
| Created | 2014-10-15T15:06:10Z |
| Publication Date | 2014-10-15T15:41:22Z |

## Description

The dataset details 2015 Budget Recommendations, which is the line-item budget document proposed by the Mayor to the City Council for approval. Budgeted expenditures are identified by department, appropriation account, and funding type: Local, Community Development Block Grant Program (CDBG), and other Grants. “Local” funds refer to those line items that are balanced with locally-generated revenue sources, including but not limited to the Corporate Fund, Water Fund, Midway and O’Hare Airport funds, Vehicle Tax Fund, Library Fund and General Obligation Bond funds. Owner: Budget and Management. Frequency: Data are updated annually. For more information about the budget process, visit the Budget Documents page: http://j.mp/lPotWf.

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
| Yes      | numeric metric | appropration                        | 2014 APPROPRATION                   | money     | money       |
| Yes      | numeric metric | revised_appropriation               | 2014 REVISED APPROPRIATION          | money     | money       |
| Yes      | numeric metric | recommendation                      | 2015 RECOMMENDATION                 | money     | money       |
```

## Time Field

```ls
Value = 2015
Format & Zone = yyyy
```

## Data Commands

```ls
series e:kzbi-spm5 d:2015-01-01T00:00:00.000Z t:department_description="OFFICE OF THE MAYOR" t:fund_code=0100 t:fund_type=LOCAL t:appropriation_account=5 t:appropriation_authority_description="OFFICE OF THE MAYOR" t:appropriation_authority=2005 t:department_number=1 t:appropriation_account_description="SALARIES AND WAGES - ON PAYROLL" t:fund_description="CORPORATE FUND" m:appropration=5511957 m:recommendation=5550657 m:revised_appropriation=5511957

series e:kzbi-spm5 d:2015-01-01T00:00:00.000Z t:department_description="OFFICE OF THE MAYOR" t:fund_code=0100 t:fund_type=LOCAL t:appropriation_account=126 t:appropriation_authority_description="OFFICE OF THE MAYOR" t:appropriation_authority=2005 t:department_number=1 t:appropriation_account_description="OFFICE CONVENIENCES" t:fund_description="CORPORATE FUND" m:appropration=1200 m:recommendation=1000 m:revised_appropriation=1200

series e:kzbi-spm5 d:2015-01-01T00:00:00.000Z t:department_description="OFFICE OF THE MAYOR" t:fund_code=0100 t:fund_type=LOCAL t:appropriation_account=130 t:appropriation_authority_description="OFFICE OF THE MAYOR" t:appropriation_authority=2005 t:department_number=1 t:appropriation_account_description=POSTAGE t:fund_description="CORPORATE FUND" m:appropration=10000 m:recommendation=5019 m:revised_appropriation=10000
```

## Meta Commands

```ls
metric m:appropration p:integer l:"2014 APPROPRATION" t:dataTypeName=money

metric m:revised_appropriation p:integer l:"2014 REVISED APPROPRIATION" t:dataTypeName=money

metric m:recommendation p:integer l:"2015 RECOMMENDATION" t:dataTypeName=money

entity e:kzbi-spm5 l:"Budget - 2015 Budget Recommendations - Appropriations" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/kzbi-spm5

property e:kzbi-spm5 t:meta.view d:2017-06-09T13:59:24.306Z v:id=kzbi-spm5 v:category="Administration & Finance" v:attributionLink=http://www.cityofchicago.org/budget v:averageRating=0 v:name="Budget - 2015 Budget Recommendations - Appropriations" v:attribution="City of Chicago"

property e:kzbi-spm5 t:meta.view.owner d:2017-06-09T13:59:24.306Z v:id=vewm-vupz v:screenName="Jonathan Levy" v:lastNotificationSeenAt=1496780786 v:displayName="Jonathan Levy"

property e:kzbi-spm5 t:meta.view.tableauthor d:2017-06-09T13:59:24.306Z v:id=vewm-vupz v:screenName="Jonathan Levy" v:roleName=administrator v:lastNotificationSeenAt=1496780786 v:displayName="Jonathan Levy"
```

## Top Records

```ls
| fund_type | fund_code | fund_description | department_number | department_description | appropriation_authority | appropriation_authority_description | appropriation_account | appropriation_account_description | appropration | revised_appropriation | recommendation | 
| ========= | ========= | ================ | ================= | ====================== | ======================= | =================================== | ===================== | ================================= | ============ | ===================== | ============== | 
| LOCAL     | 0100      | CORPORATE FUND   | 1                 | OFFICE OF THE MAYOR    | 2005                    | OFFICE OF THE MAYOR                 | 5                     | SALARIES AND WAGES - ON PAYROLL   | 5511957      | 5511957               | 5550657        | 
| LOCAL     | 0100      | CORPORATE FUND   | 1                 | OFFICE OF THE MAYOR    | 2005                    | OFFICE OF THE MAYOR                 | 126                   | OFFICE CONVENIENCES               | 1200         | 1200                  | 1000           | 
| LOCAL     | 0100      | CORPORATE FUND   | 1                 | OFFICE OF THE MAYOR    | 2005                    | OFFICE OF THE MAYOR                 | 130                   | POSTAGE                           | 10000        | 10000                 | 5019           | 
| LOCAL     | 0100      | CORPORATE FUND   | 1                 | OFFICE OF THE MAYOR    | 2005                    | OFFICE OF THE MAYOR                 | 150                   | PUBLICATN & REPRODT-OUT           | 1000         | 1000                  | 1000           | 
| LOCAL     | 0100      | CORPORATE FUND   | 1                 | OFFICE OF THE MAYOR    | 2005                    | OFFICE OF THE MAYOR                 | 157                   | RENTAL EQUIPMENT AND SERVICES     | 49500        | 49500                 | 49500          | 
| LOCAL     | 0100      | CORPORATE FUND   | 1                 | OFFICE OF THE MAYOR    | 2005                    | OFFICE OF THE MAYOR                 | 159                   | LEASE PURCHASE AGREEMNT           | 63500        | 63500                 | 63500          | 
| LOCAL     | 0100      | CORPORATE FUND   | 1                 | OFFICE OF THE MAYOR    | 2005                    | OFFICE OF THE MAYOR                 | 162                   | REPAIR/MAINT EQUIPMENT            | 6984         | 6984                  | 6984           | 
| LOCAL     | 0100      | CORPORATE FUND   | 1                 | OFFICE OF THE MAYOR    | 2005                    | OFFICE OF THE MAYOR                 | 166                   | DUES, SUBSC & MEM                 | 18500        | 18500                 | 18500          | 
| LOCAL     | 0100      | CORPORATE FUND   | 1                 | OFFICE OF THE MAYOR    | 2005                    | OFFICE OF THE MAYOR                 | 169                   | TECHNICAL MEETING COSTS           | 5286         | 5286                  | 5286           | 
| LOCAL     | 0100      | CORPORATE FUND   | 1                 | OFFICE OF THE MAYOR    | 2005                    | OFFICE OF THE MAYOR                 | 181                   | MOBILE COMMUNICATION SERVICES     | 47400        | 47400                 | 37700          | 
```