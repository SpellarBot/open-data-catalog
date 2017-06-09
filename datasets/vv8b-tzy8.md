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

## Description

King County 2010 Budget Expenditures outside the General Fund

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| Yes      | series tag     | fundnumber         | FundNumber         | text      | number      |
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
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:vv8b-tzy8 d:2010-01-01T00:00:00.000Z t:loworgdescription="TRAFFIC SYSTEMS UNIT(1644)" t:accountdescription="59502  BIENNIAL BUDGET BALANCER" t:deptdescription=ROADS(0730) t:funddescription="COUNTY ROAD FUND" t:account=59502 t:fundnumber=1030 m:dept=730 m:loworg=1644

series e:vv8b-tzy8 d:2010-01-01T00:00:00.000Z t:loworgdescription="TRAFFIC BASIC-BURIEN(3906)" t:accountdescription="59502  BIENNIAL BUDGET BALANCER" t:deptdescription=ROADS(0730) t:funddescription="COUNTY ROAD FUND" t:account=59502 t:fundnumber=1030 m:dept=730 m:loworg=3906

series e:vv8b-tzy8 d:2010-01-01T00:00:00.000Z t:loworgdescription="TRAFFIC BASIC-SNOQUALMIE(3910)" t:accountdescription="59502  BIENNIAL BUDGET BALANCER" t:deptdescription=ROADS(0730) t:funddescription="COUNTY ROAD FUND" t:account=59502 t:fundnumber=1030 m:dept=730 m:loworg=3910
```

## Meta Commands

```ls
metric m:dept p:integer l:Dept t:dataTypeName=number

metric m:loworg p:integer l:LowOrg t:dataTypeName=number

metric m:adopted p:integer l:Adopted t:dataTypeName=money

entity e:vv8b-tzy8 l:"Non-General Fund Expenditures 2010" t:attribution="King County" t:url=https://data.kingcounty.gov/api/views/vv8b-tzy8

property e:vv8b-tzy8 t:meta.view d:2017-06-09T13:52:54.927Z v:id=vv8b-tzy8 v:category=Budget v:attributionLink=http://www.kingcounty.gov v:averageRating=100 v:name="Non-General Fund Expenditures 2010" v:attribution="King County"

property e:vv8b-tzy8 t:meta.view.license d:2017-06-09T13:52:54.927Z v:name="Public Domain"

property e:vv8b-tzy8 t:meta.view.owner d:2017-06-09T13:52:54.927Z v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:lastNotificationSeenAt=1496959418 v:displayName="King County Webteam"

property e:vv8b-tzy8 t:meta.view.tableauthor d:2017-06-09T13:52:54.927Z v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1496959418 v:displayName="King County Webteam"
```

## Top Records

```ls
| fundnumber | funddescription           | dept | deptdescription                 | loworg | loworgdescription                | account | accountdescription              | adopted | 
| ========== | ========================= | ==== | =============================== | ====== | ================================ | ======= | =============================== | ======= | 
| 1030       | COUNTY ROAD FUND          | 730  | ROADS(0730)                     | 1644   | TRAFFIC SYSTEMS UNIT(1644)       | 59502   | 59502 BIENNIAL BUDGET BALANCER  |         | 
| 1030       | COUNTY ROAD FUND          | 730  | ROADS(0730)                     | 3906   | TRAFFIC BASIC-BURIEN(3906)       | 59502   | 59502 BIENNIAL BUDGET BALANCER  |         | 
| 1030       | COUNTY ROAD FUND          | 730  | ROADS(0730)                     | 3910   | TRAFFIC BASIC-SNOQUALMIE(3910)   | 59502   | 59502 BIENNIAL BUDGET BALANCER  |         | 
| 1030       | COUNTY ROAD FUND          | 730  | ROADS(0730)                     | 3919   | TRAFFIC DISC-DES MOINES(3919)    | 59502   | 59502 BIENNIAL BUDGET BALANCER  |         | 
| 1030       | COUNTY ROAD FUND          | 730  | ROADS(0730)                     | 5633   | SURVEY UNIT(5633)                | 59502   | 59502 BIENNIAL BUDGET BALANCER  |         | 
| 1135       | MIDD                      | 883  | SHERIFF MIDD(0883)              | 8835   | CRISIS INTERVNTN TRNG PRGM(8835) | 51310   | 51310 MEDICAL/LIFE INS BENEFITS |         | 
| 1135       | MIDD                      | 984  | DISTRICT COURT MIDD(0984)       | 9530   | MNTL HLTH COURT EXPANSION(9530)  | 51320   | 51320 O A S I / FICA            |         | 
| 1260       | ALCOHOLISM/SUBSTANCE ABSE | 960  | DCHS-DASAS(0960)                | 9860   | HUMAN SRV & VETS LEVY EXP(9860)  | 51320   | 51320 O A S I / FICA            |         | 
| 1340       | DEVLPMNT & ENVRNMNT SVCS  | 325  | DEVLOPMT & ENVRNMNTL SRVS(0325) | 3419   | DDES O&M(3419)                   | 55144   | 55144 PROPERTY SERVICES         |         | 
| 1450       | PARKS SPECIAL REVENUE     | 640  | PARKS(0640)                     | 8657   | RESOURCE AREA III(8657)          | 53540   | 53540 WASTE DISPOSAL            |         | 
```