# 2011 General Fund, proposed expenditures, 2011 budget

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2011-general-fund-proposed-expenditures-2011-budget-e6f37) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/imfe-xrs7) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/imfe-xrs7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/imfe-xrs7/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | imfe-xrs7 |
| Name | 2011 General Fund, proposed expenditures, 2011 budget |
| Attribution | King County |
| Category | Budget |
| Tags | expenditures, expenses, 2011, general fund, budget |
| Created | 2010-09-27T16:33:23Z |
| Publication Date | 2015-05-28T23:41:02Z |

## Description

King County 2011 budget, proposed expenditures within the general fund

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| Yes      | numeric metric | fund               | Fund               | number    | number      |
| Yes      | series tag     | funddescription    | FundDescription    | text      | text        |
| Yes      | numeric metric | dept               | Dept               | number    | number      |
| Yes      | series tag     | deptdescription    | DeptDescription    | text      | text        |
| Yes      | numeric metric | loworg             | LowOrg             | number    | number      |
| Yes      | series tag     | loworgdescription  | LowOrgDescription  | text      | text        |
| Yes      | series tag     | account            | Account            | text      | text        |
| Yes      | series tag     | accountdescription | AccountDescription | text      | text        |
| Yes      | numeric metric | 11prop             | 11PROP             | money     | money       |
```

## Time Field

```ls
Value = 2011
Format & Zone = yyyy
```

## Data Commands

```ls
series e:imfe-xrs7 d:2011-01-01T00:00:00.000Z t:loworgdescription="Council Interfund Transfers(1041)" t:accountdescription="51110  REGULAR SALARIED EMPLOYEE" t:deptdescription="COUNTY COUNCIL(0010)" t:funddescription="GENERAL FUND" t:account=51110 m:11prop=208133 m:fund=10 m:dept=10 m:loworg=1041

series e:imfe-xrs7 d:2011-01-01T00:00:00.000Z t:loworgdescription="Council Interfund Transfers(1041)" t:accountdescription="51148A  AUTO ALLOWANCE" t:deptdescription="COUNTY COUNCIL(0010)" t:funddescription="GENERAL FUND" t:account=51148A m:11prop=20000 m:fund=10 m:dept=10 m:loworg=1041

series e:imfe-xrs7 d:2011-01-01T00:00:00.000Z t:loworgdescription="Council Interfund Transfers(1041)" t:accountdescription="51315  FLEX BENEFIT COMBINED CHG" t:deptdescription="COUNTY COUNCIL(0010)" t:funddescription="GENERAL FUND" t:account=51315 m:11prop=84609 m:fund=10 m:dept=10 m:loworg=1041
```

## Meta Commands

```ls
metric m:fund p:integer l:Fund t:dataTypeName=number

metric m:dept p:integer l:Dept t:dataTypeName=number

metric m:loworg p:integer l:LowOrg t:dataTypeName=number

metric m:11prop p:integer l:11PROP t:dataTypeName=money

entity e:imfe-xrs7 l:"2011 General Fund, proposed expenditures, 2011 budget" t:attribution="King County" t:url=https://data.kingcounty.gov/api/views/imfe-xrs7

property e:imfe-xrs7 t:meta.view v:id=imfe-xrs7 v:category=Budget v:attributionLink=http://www.kingcounty.gov v:averageRating=0 v:name="2011 General Fund, proposed expenditures, 2011 budget" v:attribution="King County"

property e:imfe-xrs7 t:meta.view.license v:name="Public Domain"

property e:imfe-xrs7 t:meta.view.owner v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:displayName="King County Webteam"

property e:imfe-xrs7 t:meta.view.tableauthor v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:roleName=administrator v:displayName="King County Webteam"
```

## Top Records

```ls
| fund | funddescription | dept | deptdescription      | loworg | loworgdescription                 | account | accountdescription              | 11prop | 
| ==== | =============== | ==== | ==================== | ====== | ================================= | ======= | =============================== | ====== | 
| 10   | GENERAL FUND    | 10   | COUNTY COUNCIL(0010) | 1041   | Council Interfund Transfers(1041) | 51110   | 51110 REGULAR SALARIED EMPLOYEE | 208133 | 
| 10   | GENERAL FUND    | 10   | COUNTY COUNCIL(0010) | 1041   | Council Interfund Transfers(1041) | 51148A  | 51148A AUTO ALLOWANCE           | 20000  | 
| 10   | GENERAL FUND    | 10   | COUNTY COUNCIL(0010) | 1041   | Council Interfund Transfers(1041) | 51315   | 51315 FLEX BENEFIT COMBINED CHG | 84609  | 
| 10   | GENERAL FUND    | 10   | COUNTY COUNCIL(0010) | 1041   | Council Interfund Transfers(1041) | 51330   | 51330 RETIREMENT                | 14591  | 
| 10   | GENERAL FUND    | 10   | COUNTY COUNCIL(0010) | 1041   | Council Interfund Transfers(1041) | 51340   | 51340 INDUSTRIAL INSURANCE      | 4122   | 
| 10   | GENERAL FUND    | 10   | COUNTY COUNCIL(0010) | 1041   | Council Interfund Transfers(1041) | 52110   | 52110 OFFICE SUPPLIES           | 1000   | 
| 10   | GENERAL FUND    | 10   | COUNTY COUNCIL(0010) | 1041   | Council Interfund Transfers(1041) | 52215   | 52215 BOOKS/SUBSCRIPTIONS       | 1000   | 
| 10   | GENERAL FUND    | 10   | COUNTY COUNCIL(0010) | 1041   | Council Interfund Transfers(1041) | 53104   | 53104 CONSULTING SERVICES       | 2000   | 
| 10   | GENERAL FUND    | 10   | COUNTY COUNCIL(0010) | 1041   | Council Interfund Transfers(1041) | 53105   | 53105 OTHER CONTRACT/PROF SRVCS | 35000  | 
| 10   | GENERAL FUND    | 10   | COUNTY COUNCIL(0010) | 1041   | Council Interfund Transfers(1041) | 53211   | 53211 TELCOM SERV-ONGOING CHRG  | 283    | 
```