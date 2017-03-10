# Non-General Fund Expenditures 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/non-general-fund-expenditures-2010-27947) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/vv8b-tzy8) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/vv8b-tzy8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/vv8b-tzy8/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | vv8b-tzy8 |
| Name | Non-General Fund Expenditures 2010 |
| Attribution | King County |
| Category | Budget |
| Tags | budget, 2010, expenditures |
| Created | 2010-09-21T23:00:56Z |
| Publication Date | 2011-04-17T00:03:09Z |
| Rows Updated | 2011-08-21T02:53:53Z |

## Description

King County 2010 Budget Expenditures outside the General Fund

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| No       | time           | :updated_at        | updated_at         | meta_data | meta_data   |
| Yes      | numeric metric | fundnumber         | FundNumber         | number    | number      |
| Yes      | series tag     | funddescription    | FundDescription    | text      | text        |
| Yes      | numeric metric | dept               | Dept               | number    | number      |
| Yes      | series tag     | deptdescription    | DeptDescription    | text      | text        |
| Yes      | numeric metric | loworg             | LowOrg             | number    | number      |
| Yes      | series tag     | loworgdescription  | LowOrgDescription  | text      | text        |
| Yes      | series tag     | account            | Account            | text      | text        |
| Yes      | series tag     | accountdescription | AccountDescription | text      | text        |
| Yes      | numeric metric | adopted            | Adopted            | money     | money       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:vv8b-tzy8 d:2010-09-21T16:00:57.000Z t:loworgdescription="TRAFFIC SYSTEMS UNIT(1644)" t:accountdescription="59502  BIENNIAL BUDGET BALANCER" t:deptdescription=ROADS(0730) t:funddescription="COUNTY ROAD FUND" t:account=59502 m:dept=730 m:fundnumber=1030 m:loworg=1644

series e:vv8b-tzy8 d:2010-09-21T16:00:57.000Z t:loworgdescription="TRAFFIC BASIC-BURIEN(3906)" t:accountdescription="59502  BIENNIAL BUDGET BALANCER" t:deptdescription=ROADS(0730) t:funddescription="COUNTY ROAD FUND" t:account=59502 m:dept=730 m:fundnumber=1030 m:loworg=3906

series e:vv8b-tzy8 d:2010-09-21T16:00:57.000Z t:loworgdescription="TRAFFIC BASIC-SNOQUALMIE(3910)" t:accountdescription="59502  BIENNIAL BUDGET BALANCER" t:deptdescription=ROADS(0730) t:funddescription="COUNTY ROAD FUND" t:account=59502 m:dept=730 m:fundnumber=1030 m:loworg=3910
```

## Meta Commands

```ls
metric m:fundnumber p:integer l:FundNumber t:dataTypeName=number

metric m:dept p:integer l:Dept t:dataTypeName=number

metric m:loworg p:integer l:LowOrg t:dataTypeName=number

entity e:vv8b-tzy8 l:"Non-General Fund Expenditures 2010" t:attribution="King County" t:url=https://data.kingcounty.gov/api/views/vv8b-tzy8

property e:vv8b-tzy8 t:meta.view d:2017-03-10T14:37:18.404Z v:id=vv8b-tzy8 v:category=Budget v:attributionLink=http://www.kingcounty.gov v:averageRating=100 v:name="Non-General Fund Expenditures 2010" v:attribution="King County"

property e:vv8b-tzy8 t:meta.view.license d:2017-03-10T14:37:18.404Z v:name="Public Domain"

property e:vv8b-tzy8 t:meta.view.owner d:2017-03-10T14:37:18.404Z v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:roleName=administrator v:displayName="King County Webteam"

property e:vv8b-tzy8 t:meta.view.tableauthor d:2017-03-10T14:37:18.404Z v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:roleName=administrator v:displayName="King County Webteam"
```