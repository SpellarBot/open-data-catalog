# Non-General Fund Revenues 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/non-general-fund-revenues-2010-f1aaa) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/upsg-niup) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/upsg-niup/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/upsg-niup/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | upsg-niup |
| Name | Non-General Fund Revenues 2010 |
| Attribution | King County |
| Category | Budget |
| Tags | revenues, 2010, budget |
| Created | 2010-09-21T23:05:41Z |
| Publication Date | 2011-04-17T00:03:09Z |

## Description

King County 2010 budget revenues outside the general fund

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| Yes      | series tag     | funddescription    | FundDescription    | text      | text        |
| Yes      | series tag     | fundnumber         | FundNumber         | text      | number      |
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
series e:upsg-niup d:2010-01-01T00:00:00.000Z t:loworgdescription="PROV: EMS GRANTS(8030)" t:accountdescription="49578A  FALLS PREVENTION PILOT" t:deptdescription="PUBLIC HEALTH(0800)" t:funddescription="PUBLIC HEALTH" t:account=49578A t:fundnumber=1800 m:dept=800 m:loworg=8030

series e:upsg-niup d:2010-01-01T00:00:00.000Z t:loworgdescription="PROTECT: INF DIS PREV&CNTL(8036)" t:accountdescription="49585A  COST OF TB STUDY" t:deptdescription="PUBLIC HEALTH(0800)" t:funddescription="PUBLIC HEALTH" t:account=49585A t:fundnumber=1800 m:dept=800 m:loworg=8036

series e:upsg-niup d:2010-01-01T00:00:00.000Z t:loworgdescription=ORTP(5018M) t:accountdescription="33910M  RECOVERY ACT DIRECT" t:deptdescription="DOT Directors Office(5010M)" t:funddescription="PUBLIC TRANSP OPTG SUMMRY" t:account=33910M t:fundnumber=4640 m:adopted=147000
```

## Meta Commands

```ls
metric m:dept p:integer l:Dept t:dataTypeName=number

metric m:loworg p:integer l:LowOrg t:dataTypeName=number

metric m:adopted p:integer l:Adopted t:dataTypeName=money

entity e:upsg-niup l:"Non-General Fund Revenues 2010" t:attribution="King County" t:url=https://data.kingcounty.gov/api/views/upsg-niup

property e:upsg-niup t:meta.view v:id=upsg-niup v:category=Budget v:attributionLink=http://www.kingcounty.gov v:averageRating=100 v:name="Non-General Fund Revenues 2010" v:attribution="King County"

property e:upsg-niup t:meta.view.license v:name="Public Domain"

property e:upsg-niup t:meta.view.owner v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:displayName="King County Webteam"

property e:upsg-niup t:meta.view.tableauthor v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:roleName=administrator v:displayName="King County Webteam"
```

## Top Records

```ls
| funddescription           | fundnumber | dept | deptdescription                 | loworg | loworgdescription                | account | accountdescription               | adopted  | 
| ========================= | ========== | ==== | =============================== | ====== | ================================ | ======= | ================================ | ======== | 
| PUBLIC HEALTH             | 1800       | 800  | PUBLIC HEALTH(0800)             | 8030   | PROV: EMS GRANTS(8030)           | 49578A  | 49578A FALLS PREVENTION PILOT    |          | 
| PUBLIC HEALTH             | 1800       | 800  | PUBLIC HEALTH(0800)             | 8036   | PROTECT: INF DIS PREV&CNTL(8036) | 49585A  | 49585A COST OF TB STUDY          |          | 
| PUBLIC TRANSP OPTG SUMMRY | 4640       |      | DOT Directors Office(5010M)     |        | ORTP(5018M)                      | 33910M  | 33910M RECOVERY ACT DIRECT       | 147000   | 
| INMATE WELFARE FUND       | 16         | 914  | INMATE WELFARE FUND(0914)       | 2046   | INMATE SVC(2046)                 | 36999   | 36999 OTHER MISCELLANEOUS REV.   | 900000   | 
| INMATE WELFARE FUND       | 16         | 915  | JUVENILE INMATE WELFARE(0915)   | 2056   | INMATE SERVICES(2056)            | 36999   | 36999 OTHER MISCELLANEOUS REV.   | 5400     | 
| COUNTY ROAD FUND          | 1030       | 726  | STORMWATER DECANT PROGRAM(0726) | 1677   | REGIONAL VACTOR WASTE(1677)      | 38903   | 38903 REV BIENNIAL BUDGET        | 773077   | 
| COUNTY ROAD FUND          | 1030       | 726  | STORMWATER DECANT PROGRAM(0726) | 1677   | REGIONAL VACTOR WASTE(1677)      | 47121A  | 47121A SOLID WASTE FEES          | 757919   | 
| COUNTY ROAD FUND          | 1030       | 730  | ROADS(0730)                     | 1665   | ROADS DIVISION-WIDE(1665)        | 31111A  | 31111A REAL PRPTY TAXES-CURRENT  | 82907192 | 
| COUNTY ROAD FUND          | 1030       | 730  | ROADS(0730)                     | 1665   | ROADS DIVISION-WIDE(1665)        | 31210A  | 31210A PRIVATE TIMBER HARVEST TX | 253637   | 
| COUNTY ROAD FUND          | 1030       | 730  | ROADS(0730)                     | 1665   | ROADS DIVISION-WIDE(1665)        | 31820A  | 31820A LEASEHOLD EXCISE TAX      | 30420    | 
```