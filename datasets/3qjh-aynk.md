# General Fund Expenditures 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/general-fund-expenditures-2010-82563) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/3qjh-aynk) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/3qjh-aynk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/3qjh-aynk/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | 3qjh-aynk |
| Name | General Fund Expenditures 2010 |
| Attribution | King County |
| Category | Budget |
| Tags | 2010 budget, expenditures |
| Created | 2010-09-21T22:55:03Z |
| Publication Date | 2011-04-17T00:03:09Z |

## Description

King County 2010 Budget General Fund Expenditures

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
| Yes      | numeric metric | account            | Account            | number    | text        |
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
series e:3qjh-aynk d:2010-01-01T00:00:00.000Z t:loworgdescription="TAX ADVISOR(1047)" t:accountdescription="52203A  HOUSEKEEPING SUPPLIES" t:deptdescription="OMBUDSMAN/TAX ADVISOR(0050)" t:funddescription="GENERAL FUND" t:fundnumber=10 m:adopted=40 m:dept=50 m:loworg=1047

series e:3qjh-aynk d:2010-01-01T00:00:00.000Z t:loworgdescription=NEWCASTLE(2068) t:accountdescription="59411  COLA BUDGET" t:deptdescription="SHERIFF (PUBLIC SAFETY)(0200)" t:funddescription="GENERAL FUND" t:fundnumber=10 m:account=59411 m:dept=200 m:loworg=2068

series e:3qjh-aynk d:2010-01-01T00:00:00.000Z t:loworgdescription="SECURITY SCREENERS(2601)" t:accountdescription="52204A  PERSONAL SUPPLIES" t:deptdescription="SECURITY SCREENERS(0450)" t:funddescription="GENERAL FUND" t:fundnumber=10 m:adopted=27100 m:dept=450 m:loworg=2601
```

## Meta Commands

```ls
metric m:dept p:integer l:Dept t:dataTypeName=number

metric m:loworg p:integer l:LowOrg t:dataTypeName=number

metric m:account p:integer l:Account t:dataTypeName=number

metric m:adopted p:integer l:Adopted t:dataTypeName=money

entity e:3qjh-aynk l:"General Fund Expenditures 2010" t:attribution="King County" t:url=https://data.kingcounty.gov/api/views/3qjh-aynk

property e:3qjh-aynk t:meta.view v:id=3qjh-aynk v:category=Budget v:attributionLink=http://www.kingcounty.gov v:averageRating=90 v:name="General Fund Expenditures 2010" v:attribution="King County"

property e:3qjh-aynk t:meta.view.license v:name="Public Domain"

property e:3qjh-aynk t:meta.view.owner v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:displayName="King County Webteam"

property e:3qjh-aynk t:meta.view.tableauthor v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:roleName=administrator v:displayName="King County Webteam"
```

## Top Records

```ls
| fundnumber | funddescription | dept | deptdescription                | loworg | loworgdescription             | account | accountdescription               | adopted | 
| ========== | =============== | ==== | ============================== | ====== | ============================= | ======= | ================================ | ======= | 
| 10         | GENERAL FUND    | 50   | OMBUDSMAN/TAX ADVISOR(0050)    | 1047   | TAX ADVISOR(1047)             |         | 52203A HOUSEKEEPING SUPPLIES     | 40      | 
| 10         | GENERAL FUND    | 200  | SHERIFF (PUBLIC SAFETY)(0200)  | 2068   | NEWCASTLE(2068)               | 59411   | 59411 COLA BUDGET                |         | 
| 10         | GENERAL FUND    | 450  | SECURITY SCREENERS(0450)       | 2601   | SECURITY SCREENERS(2601)      |         | 52204A PERSONAL SUPPLIES         | 27100   | 
| 10         | GENERAL FUND    | 470  | RECORDS & LICENSNG SERV.(0470) | 1537   | ANIMAL CONTROL PET CARE(1537) | 59412   | 59412 MERIT BUDGET               | 0       | 
| 10         | GENERAL FUND    | 500  | PROSECUTING ATTORNEY(0500)     | 9045   | CJ-TRIAL TEAMS(9045)          |         | 59999A CONTINGENCY RESERVE       | -3623   | 
| 10         | GENERAL FUND    | 500  | PROSECUTING ATTORNEY(0500)     | 9052   | CJ-JUVENILE(9052)             |         | 59999A CONTINGENCY RESERVE       | -4044   | 
| 10         | GENERAL FUND    | 510  | SUPERIOR COURT(0510)           | 6447   | Courtroom Support DTN(6447)   |         | 52204A PERSONAL SUPPLIES         | 2250    | 
| 10         | GENERAL FUND    | 510  | SUPERIOR COURT(0510)           | 6479   | Jury DTN(6479)                |         | 53113A INTERPRETATION SERVICES   | 13707   | 
| 10         | GENERAL FUND    | 510  | SUPERIOR COURT(0510)           | 6486   | Family Court Svcs DTN(6486)   |         | 59430A EFFICIENCY RESERVE TARGET | -99662  | 
| 10         | GENERAL FUND    | 535  | ELECTION DEPARTMENT(0535)      | 8390   | EO ELECTION SUPPORT(8390)     |         | 53720A RENT-FURNITURE & FIXTURES | 500     | 
```