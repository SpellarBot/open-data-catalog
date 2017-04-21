# 2011 General Fund, proposed revenues, 2011 budget

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2011-general-fund-proposed-revenues-2011-budget-584b4) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/4zqn-s6g8) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/4zqn-s6g8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/4zqn-s6g8/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | 4zqn-s6g8 |
| Name | 2011 General Fund, proposed revenues, 2011 budget |
| Attribution | King County |
| Category | Budget |
| Tags | revenue, income, 2011, general fund, budget |
| Created | 2010-09-27T16:45:28Z |
| Publication Date | 2011-04-17T00:03:09Z |

## Description

King County 2011 budget, proposed revenues within the general fund

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
series e:4zqn-s6g8 d:2011-01-01T00:00:00.000Z t:loworgdescription="POLICY & MANAGEMENT(1062)" t:accountdescription="39721A  CONTRBTN-SURF WATER MGT" t:deptdescription="BUDGET OFFICE(0140)" t:funddescription="GENERAL FUND" t:account=39721A m:11prop=11429 m:fund=10 m:dept=140 m:loworg=1062

series e:4zqn-s6g8 d:2011-01-01T00:00:00.000Z t:loworgdescription="POLICY & MANAGEMENT(1062)" t:accountdescription="39797A  CONTRBTN-SOLID WASTE" t:deptdescription="BUDGET OFFICE(0140)" t:funddescription="GENERAL FUND" t:account=39797A m:11prop=11429 m:fund=10 m:dept=140 m:loworg=1062

series e:4zqn-s6g8 d:2011-01-01T00:00:00.000Z t:loworgdescription="OPERATING & CAPITAL BDGT(1063)" t:accountdescription="36999  OTHER MISCELLANEOUS REV." t:deptdescription="BUDGET OFFICE(0140)" t:funddescription="GENERAL FUND" t:account=36999 m:11prop=80950 m:fund=10 m:dept=140 m:loworg=1063
```

## Meta Commands

```ls
metric m:fund p:integer l:Fund t:dataTypeName=number

metric m:dept p:integer l:Dept t:dataTypeName=number

metric m:loworg p:integer l:LowOrg t:dataTypeName=number

metric m:11prop p:integer l:11PROP t:dataTypeName=money

entity e:4zqn-s6g8 l:"2011 General Fund, proposed revenues, 2011 budget" t:attribution="King County" t:url=https://data.kingcounty.gov/api/views/4zqn-s6g8

property e:4zqn-s6g8 t:meta.view v:id=4zqn-s6g8 v:category=Budget v:attributionLink=http://www.kingcounty.gov v:averageRating=100 v:name="2011 General Fund, proposed revenues, 2011 budget" v:attribution="King County"

property e:4zqn-s6g8 t:meta.view.license v:name="Public Domain"

property e:4zqn-s6g8 t:meta.view.owner v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:displayName="King County Webteam"

property e:4zqn-s6g8 t:meta.view.tableauthor v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:roleName=administrator v:displayName="King County Webteam"
```

## Top Records

```ls
| fund | funddescription | dept | deptdescription     | loworg | loworgdescription              | account | accountdescription               | 11prop    | 
| ==== | =============== | ==== | =================== | ====== | ============================== | ======= | ================================ | ========= | 
| 10   | GENERAL FUND    | 140  | BUDGET OFFICE(0140) | 1062   | POLICY & MANAGEMENT(1062)      | 39721A  | 39721A CONTRBTN-SURF WATER MGT   | 11429     | 
| 10   | GENERAL FUND    | 140  | BUDGET OFFICE(0140) | 1062   | POLICY & MANAGEMENT(1062)      | 39797A  | 39797A CONTRBTN-SOLID WASTE      | 11429     | 
| 10   | GENERAL FUND    | 140  | BUDGET OFFICE(0140) | 1063   | OPERATING & CAPITAL BDGT(1063) | 36999   | 36999 OTHER MISCELLANEOUS REV.   | 80950     | 
| 10   | GENERAL FUND    | 150  | FINANCE - GF(0150)  | 7128   | FINANCE SECTION ADMIN(7128)    | 31111A  | 31111A REAL PRPTY TAXES-CURRENT  | 295305688 | 
| 10   | GENERAL FUND    | 150  | FINANCE - GF(0150)  | 7128   | FINANCE SECTION ADMIN(7128)    | 31113A  | 31113A REAL PRPTY TAXES-DELINQNT | 4300000   | 
| 10   | GENERAL FUND    | 150  | FINANCE - GF(0150)  | 7128   | FINANCE SECTION ADMIN(7128)    | 31119A  | 31119A ADVALOREM TAX REFUNDS     | -1500000  | 
| 10   | GENERAL FUND    | 150  | FINANCE - GF(0150)  | 7128   | FINANCE SECTION ADMIN(7128)    | 31130A  | 31130A SALE OF TAX TITLE PROPRTY | 2500      | 
| 10   | GENERAL FUND    | 150  | FINANCE - GF(0150)  | 7128   | FINANCE SECTION ADMIN(7128)    | 31210A  | 31210A PRIVATE TIMBER HARVEST TX | 10000     | 
| 10   | GENERAL FUND    | 150  | FINANCE - GF(0150)  | 7128   | FINANCE SECTION ADMIN(7128)    | 31310A  | 31310A LOCAL RET SALES & USE TAX | 71239876  | 
| 10   | GENERAL FUND    | 150  | FINANCE - GF(0150)  | 7128   | FINANCE SECTION ADMIN(7128)    | 31820A  | 31820A LEASEHOLD EXCISE TAX      | 1550000   | 
```