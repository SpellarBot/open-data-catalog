# 2011 Non-General Fund, proposed expenditures, 2011 budget

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2011-non-general-fund-proposed-expenditures-2011-budget-17ad5) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/48ub-bstr) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/48ub-bstr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/48ub-bstr/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | 48ub-bstr |
| Name | 2011 Non-General Fund, proposed expenditures, 2011 budget |
| Attribution | King County |
| Category | Budget |
| Tags | expenditures, expenses, 2011, budget |
| Created | 2010-09-27T16:48:44Z |
| Publication Date | 2011-04-17T00:03:09Z |

## Description

King County 2011 budget, proposed expenditures outside the general fund. More at http://www.kingcounty.gov/budget

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
series e:48ub-bstr d:2011-01-01T00:00:00.000Z t:loworgdescription="REGIONAL VACTOR WASTE(1677)" t:accountdescription="51191A  LOAN IN LABOR (AUTO)" t:deptdescription="STORMWATER DECANT PROGRAM(0726)" t:funddescription="COUNTY ROAD FUND" t:account=51191A m:11prop=113000 m:fund=1030 m:dept=726 m:loworg=1677

series e:48ub-bstr d:2011-01-01T00:00:00.000Z t:loworgdescription="REGIONAL VACTOR WASTE(1677)" t:accountdescription="51399A  LOAN IN/OUT BENEFTS-AUTO" t:deptdescription="STORMWATER DECANT PROGRAM(0726)" t:funddescription="COUNTY ROAD FUND" t:account=51399A m:11prop=42691 m:fund=1030 m:dept=726 m:loworg=1677

series e:48ub-bstr d:2011-01-01T00:00:00.000Z t:loworgdescription="REGIONAL VACTOR WASTE(1677)" t:accountdescription="52310  ROAD MATERIALS & SUPPLIES" t:deptdescription="STORMWATER DECANT PROGRAM(0726)" t:funddescription="COUNTY ROAD FUND" t:account=52310 m:11prop=39312 m:fund=1030 m:dept=726 m:loworg=1677
```

## Meta Commands

```ls
metric m:fund p:integer l:Fund t:dataTypeName=number

metric m:dept p:integer l:Dept t:dataTypeName=number

metric m:loworg p:integer l:LowOrg t:dataTypeName=number

metric m:11prop p:integer l:11PROP t:dataTypeName=money

entity e:48ub-bstr l:"2011 Non-General Fund, proposed expenditures, 2011 budget" t:attribution="King County" t:url=https://data.kingcounty.gov/api/views/48ub-bstr

property e:48ub-bstr t:meta.view v:id=48ub-bstr v:category=Budget v:attributionLink=http://www.kingcounty.gov/budget v:averageRating=100 v:name="2011 Non-General Fund, proposed expenditures, 2011 budget" v:attribution="King County"

property e:48ub-bstr t:meta.view.license v:name="Public Domain"

property e:48ub-bstr t:meta.view.owner v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:displayName="King County Webteam"

property e:48ub-bstr t:meta.view.tableauthor v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:roleName=administrator v:displayName="King County Webteam"
```

## Top Records

```ls
| fund | funddescription  | dept | deptdescription                 | loworg | loworgdescription           | account | accountdescription               | 11prop | 
| ==== | ================ | ==== | =============================== | ====== | =========================== | ======= | ================================ | ====== | 
| 1030 | COUNTY ROAD FUND | 726  | STORMWATER DECANT PROGRAM(0726) | 1677   | REGIONAL VACTOR WASTE(1677) | 51191A  | 51191A LOAN IN LABOR (AUTO)      | 113000 | 
| 1030 | COUNTY ROAD FUND | 726  | STORMWATER DECANT PROGRAM(0726) | 1677   | REGIONAL VACTOR WASTE(1677) | 51399A  | 51399A LOAN IN/OUT BENEFTS-AUTO  | 42691  | 
| 1030 | COUNTY ROAD FUND | 726  | STORMWATER DECANT PROGRAM(0726) | 1677   | REGIONAL VACTOR WASTE(1677) | 52310   | 52310 ROAD MATERIALS & SUPPLIES  | 39312  | 
| 1030 | COUNTY ROAD FUND | 726  | STORMWATER DECANT PROGRAM(0726) | 1677   | REGIONAL VACTOR WASTE(1677) | 53530   | 53530 WATER & RELATED            | 4923   | 
| 1030 | COUNTY ROAD FUND | 726  | STORMWATER DECANT PROGRAM(0726) | 1677   | REGIONAL VACTOR WASTE(1677) | 53547A  | 53547A RECYCLABLES DISPOSAL      | 37470  | 
| 1030 | COUNTY ROAD FUND | 726  | STORMWATER DECANT PROGRAM(0726) | 1677   | REGIONAL VACTOR WASTE(1677) | 53807   | 53807 PERMITS CERTIF & OTHER     | 46     | 
| 1030 | COUNTY ROAD FUND | 726  | STORMWATER DECANT PROGRAM(0726) | 1677   | REGIONAL VACTOR WASTE(1677) | 55201   | 55201 OVERHEAD COST ALLOCATION   | 494    | 
| 1030 | COUNTY ROAD FUND | 726  | STORMWATER DECANT PROGRAM(0726) | 1677   | REGIONAL VACTOR WASTE(1677) | 55245   | 55245 FINANCIAL MGMT SVCS S/S    | 6734   | 
| 1030 | COUNTY ROAD FUND | 726  | STORMWATER DECANT PROGRAM(0726) | 1677   | REGIONAL VACTOR WASTE(1677) | 55255   | 55255 FINANCIAL MGMT SVCS REBATE | -661   | 
| 1030 | COUNTY ROAD FUND | 726  | STORMWATER DECANT PROGRAM(0726) | 1677   | REGIONAL VACTOR WASTE(1677) | 55300   | 55300 LOAN IN/OUT INDIRECT COST  | 84378  | 
```