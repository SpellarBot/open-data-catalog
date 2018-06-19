# Budget - 2014 Budget Ordinance - Appropriations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/budget-2014-budget-ordinance-appropriations-667d7) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/ub6s-xy6e) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/ub6s-xy6e/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/ub6s-xy6e/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | ub6s-xy6e |
| Name | Budget - 2014 Budget Ordinance - Appropriations |
| Attribution | City of Chicago |
| Category | Administration & Finance |
| Tags | budget, 2014 |
| Created | 2013-12-03T18:41:12Z |
| Publication Date | 2013-12-03T21:36:57Z |

## Description

The Annual Appropriation Ordinance is the final City operating budget as approved by the City Council. It reflects the City?s operating budget at the beginning of the fiscal year on January 1. This dataset details the budgeted expenditures in the Ordinance and identifies them by department, appropriation account, and funding type: Local, Community Development Block Grant Program (CDBG), and other Grants. ?Local? funds refer to those line items that are balanced with locally generated revenue sources, including but not limited to the Corporate Fund, Water Fund, Midway and O?Hare Airport funds, Vehicle Tax Fund, Library Fund and General Obligation Bond funds. Owner: Budget and Management. Frequency: Data are updated annually. For more information about the budget process, visit the Budget Documents page: http://j.mp/lPotWf.

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
| Yes      | numeric metric | ordinance_amount_                   | 2014 ORDINANCE (AMOUNT $)           | money     | money       |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ub6s-xy6e d:2014-01-01T00:00:00.000Z t:department_description="OFFICE OF THE MAYOR" t:fund_code=0100 t:fund_type=Local t:appropriation_account=5 t:appropriation_authority_description="OFFICE OF THE MAYOR" t:appropriation_authority=2005 t:department_number=1 t:appropriation_account_description="SALARIES AND WAGES - ON PAYROLL" t:fund_description="CORPORATE FUND" m:ordinance_amount_=5511957

series e:ub6s-xy6e d:2014-01-01T00:00:00.000Z t:department_description="OFFICE OF THE MAYOR" t:fund_code=0100 t:fund_type=Local t:appropriation_account=126 t:appropriation_authority_description="OFFICE OF THE MAYOR" t:appropriation_authority=2005 t:department_number=1 t:appropriation_account_description="OFFICE CONVENIENCES" t:fund_description="CORPORATE FUND" m:ordinance_amount_=1200

series e:ub6s-xy6e d:2014-01-01T00:00:00.000Z t:department_description="OFFICE OF THE MAYOR" t:fund_code=0100 t:fund_type=Local t:appropriation_account=130 t:appropriation_authority_description="OFFICE OF THE MAYOR" t:appropriation_authority=2005 t:department_number=1 t:appropriation_account_description=POSTAGE t:fund_description="CORPORATE FUND" m:ordinance_amount_=10000
```

## Meta Commands

```ls
metric m:ordinance_amount_ p:integer l:"2014 ORDINANCE (AMOUNT $)" t:dataTypeName=money

entity e:ub6s-xy6e l:"Budget - 2014 Budget Ordinance - Appropriations" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/ub6s-xy6e

property e:ub6s-xy6e t:meta.view v:id=ub6s-xy6e v:category="Administration & Finance" v:attributionLink=http://www.cityofchicago.org/city/en/depts/obm/provdrs/city_budg.html v:averageRating=0 v:name="Budget - 2014 Budget Ordinance - Appropriations" v:attribution="City of Chicago"

property e:ub6s-xy6e t:meta.view.owner v:id=vewm-vupz v:screenName="Jonathan Levy" v:displayName="Jonathan Levy"

property e:ub6s-xy6e t:meta.view.tableauthor v:id=vewm-vupz v:screenName="Jonathan Levy" v:roleName=administrator v:displayName="Jonathan Levy"
```

## Top Records

```ls
| fund_type | fund_code | fund_description | department_number | department_description | appropriation_authority | appropriation_authority_description | appropriation_account | appropriation_account_description | ordinance_amount_ | 
| ========= | ========= | ================ | ================= | ====================== | ======================= | =================================== | ===================== | ================================= | ================= | 
| Local     | 0100      | CORPORATE FUND   | 1                 | OFFICE OF THE MAYOR    | 2005                    | OFFICE OF THE MAYOR                 | 5                     | SALARIES AND WAGES - ON PAYROLL   | 5511957           | 
| Local     | 0100      | CORPORATE FUND   | 1                 | OFFICE OF THE MAYOR    | 2005                    | OFFICE OF THE MAYOR                 | 126                   | OFFICE CONVENIENCES               | 1200              | 
| Local     | 0100      | CORPORATE FUND   | 1                 | OFFICE OF THE MAYOR    | 2005                    | OFFICE OF THE MAYOR                 | 130                   | POSTAGE                           | 10000             | 
| Local     | 0100      | CORPORATE FUND   | 1                 | OFFICE OF THE MAYOR    | 2005                    | OFFICE OF THE MAYOR                 | 150                   | PUBLICATN & REPRODT-OUT           | 1000              | 
| Local     | 0100      | CORPORATE FUND   | 1                 | OFFICE OF THE MAYOR    | 2005                    | OFFICE OF THE MAYOR                 | 157                   | RENTAL EQUIPMENT AND SERVICES     | 49500             | 
| Local     | 0100      | CORPORATE FUND   | 1                 | OFFICE OF THE MAYOR    | 2005                    | OFFICE OF THE MAYOR                 | 159                   | LEASE PURCHASE AGREEMNT           | 63500             | 
| Local     | 0100      | CORPORATE FUND   | 1                 | OFFICE OF THE MAYOR    | 2005                    | OFFICE OF THE MAYOR                 | 162                   | REPAIR/MAINT EQUIPMENT            | 6984              | 
| Local     | 0100      | CORPORATE FUND   | 1                 | OFFICE OF THE MAYOR    | 2005                    | OFFICE OF THE MAYOR                 | 166                   | DUES SUBSC & MEM                  | 18500             | 
| Local     | 0100      | CORPORATE FUND   | 1                 | OFFICE OF THE MAYOR    | 2005                    | OFFICE OF THE MAYOR                 | 169                   | TECHNICAL MEETING COSTS           | 5286              | 
| Local     | 0100      | CORPORATE FUND   | 1                 | OFFICE OF THE MAYOR    | 2005                    | OFFICE OF THE MAYOR                 | 181                   | MOBILE COMM SERVICES              | 47400             | 
```