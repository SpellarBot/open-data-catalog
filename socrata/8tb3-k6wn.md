# 2011 Non-General Fund, proposed revenues, 2011 budget

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2011-non-general-fund-proposed-revenues-2011-budget-2fd65) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/8tb3-k6wn) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/8tb3-k6wn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/8tb3-k6wn/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | 8tb3-k6wn |
| Name | 2011 Non-General Fund, proposed revenues, 2011 budget |
| Attribution | King County |
| Category | Budget |
| Tags | revenue, income, 2011, budget |
| Created | 2010-09-27T16:53:05Z |
| Publication Date | 2011-04-17T00:03:09Z |

## Description

King County 2011 budget, proposed revenues outside the general fund

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
series e:8tb3-k6wn d:2011-01-01T00:00:00.000Z t:loworgdescription="REGIONAL VACTOR WASTE(1677)" t:accountdescription="38903  REV BIENNIAL BUDGET" t:deptdescription="STORMWATER DECANT PROGRAM(0726)" t:funddescription="COUNTY ROAD FUND" t:account=38903 m:11prop=773077 m:fund=1030 m:dept=726 m:loworg=1677

series e:8tb3-k6wn d:2011-01-01T00:00:00.000Z t:loworgdescription="REGIONAL VACTOR WASTE(1677)" t:accountdescription="47121A  SOLID WASTE FEES" t:deptdescription="STORMWATER DECANT PROGRAM(0726)" t:funddescription="COUNTY ROAD FUND" t:account=47121A m:11prop=757919 m:fund=1030 m:dept=726 m:loworg=1677

series e:8tb3-k6wn d:2011-01-01T00:00:00.000Z t:loworgdescription="ROADS DIVISION-WIDE(1665)" t:accountdescription="31111A  REAL PRPTY TAXES-CURRENT" t:deptdescription=ROADS(0730) t:funddescription="COUNTY ROAD FUND" t:account=31111A m:11prop=82907192 m:fund=1030 m:dept=730 m:loworg=1665
```

## Meta Commands

```ls
metric m:fund p:integer l:Fund t:dataTypeName=number

metric m:dept p:integer l:Dept t:dataTypeName=number

metric m:loworg p:integer l:LowOrg t:dataTypeName=number

metric m:11prop p:integer l:11PROP t:dataTypeName=money

entity e:8tb3-k6wn l:"2011 Non-General Fund, proposed revenues, 2011 budget" t:attribution="King County" t:url=https://data.kingcounty.gov/api/views/8tb3-k6wn

property e:8tb3-k6wn t:meta.view v:id=8tb3-k6wn v:category=Budget v:attributionLink=http://www.kingcounty.gov v:averageRating=100 v:name="2011 Non-General Fund, proposed revenues, 2011 budget" v:attribution="King County"

property e:8tb3-k6wn t:meta.view.license v:name="Public Domain"

property e:8tb3-k6wn t:meta.view.owner v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:displayName="King County Webteam"

property e:8tb3-k6wn t:meta.view.tableauthor v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:roleName=administrator v:displayName="King County Webteam"
```

## Top Records

```ls
| fund | funddescription  | dept | deptdescription                 | loworg | loworgdescription           | account | accountdescription               | 11prop   | 
| ==== | ================ | ==== | =============================== | ====== | =========================== | ======= | ================================ | ======== | 
| 1030 | COUNTY ROAD FUND | 726  | STORMWATER DECANT PROGRAM(0726) | 1677   | REGIONAL VACTOR WASTE(1677) | 38903   | 38903 REV BIENNIAL BUDGET        | 773077   | 
| 1030 | COUNTY ROAD FUND | 726  | STORMWATER DECANT PROGRAM(0726) | 1677   | REGIONAL VACTOR WASTE(1677) | 47121A  | 47121A SOLID WASTE FEES          | 757919   | 
| 1030 | COUNTY ROAD FUND | 730  | ROADS(0730)                     | 1665   | ROADS DIVISION-WIDE(1665)   | 31111A  | 31111A REAL PRPTY TAXES-CURRENT  | 82907192 | 
| 1030 | COUNTY ROAD FUND | 730  | ROADS(0730)                     | 1665   | ROADS DIVISION-WIDE(1665)   | 31210A  | 31210A PRIVATE TIMBER HARVEST TX | 253637   | 
| 1030 | COUNTY ROAD FUND | 730  | ROADS(0730)                     | 1665   | ROADS DIVISION-WIDE(1665)   | 31820A  | 31820A LEASEHOLD EXCISE TAX      | 30420    | 
| 1030 | COUNTY ROAD FUND | 730  | ROADS(0730)                     | 1665   | ROADS DIVISION-WIDE(1665)   | 33291A  | 33291A FEDERAL FOREST YIELD      | 896985   | 
| 1030 | COUNTY ROAD FUND | 730  | ROADS(0730)                     | 1665   | ROADS DIVISION-WIDE(1665)   | 33688A  | 33688A MV FUEL TAX-CAPA          | 688423   | 
| 1030 | COUNTY ROAD FUND | 730  | ROADS(0730)                     | 1665   | ROADS DIVISION-WIDE(1665)   | 33689A  | 33689A MV FUEL TAX-COUNTY ROAD   | 14398553 | 
| 1030 | COUNTY ROAD FUND | 730  | ROADS(0730)                     | 1665   | ROADS DIVISION-WIDE(1665)   | 34150A  | 34150A MAPS & PUBLICATIONS       | 3627     | 
| 1030 | COUNTY ROAD FUND | 730  | ROADS(0730)                     | 1665   | ROADS DIVISION-WIDE(1665)   | 34494A  | 34494A MPS MITIGATION ADMIN FEE  | 31878    | 
```