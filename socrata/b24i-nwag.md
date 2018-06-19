# Budget - 2013 Budget Ordinance - Appropriations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/budget-2013-budget-ordinance-appropriations-29e3a) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/b24i-nwag) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/b24i-nwag/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/b24i-nwag/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | b24i-nwag |
| Name | Budget - 2013 Budget Ordinance - Appropriations |
| Attribution | City of Chicago |
| Category | Administration & Finance |
| Tags | budget, 2013 |
| Created | 2012-11-29T15:58:40Z |
| Publication Date | 2012-11-29T16:22:09Z |

## Description

The Annual Appropriation Ordinance is the final City operating budget as approved by the City Council. It reflects the City?s operating budget at the beginning of the fiscal year on January 1. This dataset details the budgeted expenditures in the Ordinance and identifies them by department, appropriation account, and funding type: Local, Community Development Block Grant Program (CDBG), and other Grants. ?Local? funds refer to those line items that are balanced with locally generated revenue sources, including but not limited to the Corporate Fund, Water Fund, Midway and O?Hare Airport funds, Vehicle Tax Fund, Library Fund and General Obligation Bond funds. Owner: Budget and Management. Frequency: Data is updated annually. For more information about the budget process, visit the Budget Documents page: http://j.mp/lPotWf.

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
| Yes      | numeric metric | appropriation_ordinance             | 2013 APPROPRIATION ORDINANCE        | money     | money       |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:b24i-nwag d:2013-01-01T00:00:00.000Z t:department_description="OFFICE OF THE MAYOR" t:fund_code=100 t:fund_type=Local t:appropriation_account=5 t:appropriation_authority_description="OFFICE OF THE MAYOR" t:appropriation_authority=2005 t:department_number=1 t:appropriation_account_description="SALARIES AND WAGES - ON PAYROLL" t:fund_description="CORPORATE FUND" m:appropriation_ordinance=5366703

series e:b24i-nwag d:2013-01-01T00:00:00.000Z t:department_description="OFFICE OF THE MAYOR" t:fund_code=100 t:fund_type=Local t:appropriation_account=126 t:appropriation_authority_description="OFFICE OF THE MAYOR" t:appropriation_authority=2005 t:department_number=1 t:appropriation_account_description="OFFICE CONVENIENCES" t:fund_description="CORPORATE FUND" m:appropriation_ordinance=1200

series e:b24i-nwag d:2013-01-01T00:00:00.000Z t:department_description="OFFICE OF THE MAYOR" t:fund_code=100 t:fund_type=Local t:appropriation_account=130 t:appropriation_authority_description="OFFICE OF THE MAYOR" t:appropriation_authority=2005 t:department_number=1 t:appropriation_account_description=POSTAGE t:fund_description="CORPORATE FUND" m:appropriation_ordinance=18000
```

## Meta Commands

```ls
metric m:appropriation_ordinance p:integer l:"2013 APPROPRIATION ORDINANCE" t:dataTypeName=money

entity e:b24i-nwag l:"Budget - 2013 Budget Ordinance - Appropriations" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/b24i-nwag

property e:b24i-nwag t:meta.view v:id=b24i-nwag v:category="Administration & Finance" v:attributionLink=http://www.cityofchicago.org/city/en/depts/obm/provdrs/city_budg.html v:averageRating=0 v:name="Budget - 2013 Budget Ordinance - Appropriations" v:attribution="City of Chicago"

property e:b24i-nwag t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:b24i-nwag t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| fund_type | fund_code | fund_description | department_number | department_description | appropriation_authority | appropriation_authority_description | appropriation_account | appropriation_account_description | appropriation_ordinance | 
| ========= | ========= | ================ | ================= | ====================== | ======================= | =================================== | ===================== | ================================= | ======================= | 
| Local     | 100       | CORPORATE FUND   | 1                 | OFFICE OF THE MAYOR    | 2005                    | OFFICE OF THE MAYOR                 | 5                     | SALARIES AND WAGES - ON PAYROLL   | 5366703                 | 
| Local     | 100       | CORPORATE FUND   | 1                 | OFFICE OF THE MAYOR    | 2005                    | OFFICE OF THE MAYOR                 | 126                   | OFFICE CONVENIENCES               | 1200                    | 
| Local     | 100       | CORPORATE FUND   | 1                 | OFFICE OF THE MAYOR    | 2005                    | OFFICE OF THE MAYOR                 | 130                   | POSTAGE                           | 18000                   | 
| Local     | 100       | CORPORATE FUND   | 1                 | OFFICE OF THE MAYOR    | 2005                    | OFFICE OF THE MAYOR                 | 150                   | PUBLICATN & REPRODT-OUT           | 1000                    | 
| Local     | 100       | CORPORATE FUND   | 1                 | OFFICE OF THE MAYOR    | 2005                    | OFFICE OF THE MAYOR                 | 157                   | RENTAL EQUIPMENT AND SERVICES     | 49500                   | 
| Local     | 100       | CORPORATE FUND   | 1                 | OFFICE OF THE MAYOR    | 2005                    | OFFICE OF THE MAYOR                 | 159                   | LEASE PURCHASE AGREEMNT           | 63500                   | 
| Local     | 100       | CORPORATE FUND   | 1                 | OFFICE OF THE MAYOR    | 2005                    | OFFICE OF THE MAYOR                 | 162                   | REPAIR/MAINT EQUIPMENT            | 6984                    | 
| Local     | 100       | CORPORATE FUND   | 1                 | OFFICE OF THE MAYOR    | 2005                    | OFFICE OF THE MAYOR                 | 166                   | DUES SUBSC & MEM                  | 18500                   | 
| Local     | 100       | CORPORATE FUND   | 1                 | OFFICE OF THE MAYOR    | 2005                    | OFFICE OF THE MAYOR                 | 169                   | TECHNICAL MEETING COSTS           | 5286                    | 
| Local     | 100       | CORPORATE FUND   | 1                 | OFFICE OF THE MAYOR    | 2005                    | OFFICE OF THE MAYOR                 | 181                   | MOBILE COMM SERVICES              | 47400                   | 
```