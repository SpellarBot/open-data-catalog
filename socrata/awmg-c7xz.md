# Budget Management - 2013 Budget Request by Amount and Department

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/budget-management-2013-budget-request-by-amount-and-department-ca14d) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/awmg-c7xz) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/awmg-c7xz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/awmg-c7xz/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | awmg-c7xz |
| Name | Budget Management - 2013 Budget Request by Amount and Department |
| Attribution | Cook County Department of Budget and Management Services |
| Category | Finance & Administration |
| Created | 2013-01-10T22:43:56Z |
| Publication Date | 2014-10-09T23:14:03Z |

## Description

2013 Appropriation by Department and Account. Data from 01/10/13.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| Yes      | series tag     | fundid           | FundID           | text      | text        |
| Yes      | series tag     | fundtype         | FundType         | text      | text        |
| Yes      | numeric metric | fundsort         | FundSort         | number    | text        |
| Yes      | series tag     | genfundtype      | GenFundType      | text      | text        |
| Yes      | series tag     | sort_for_summary | Sort_for_Summary | text      | text        |
| Yes      | series tag     | dept_text        | Dept_Text        | text      | text        |
| Yes      | series tag     | depttitle        | DeptTitle        | text      | text        |
| Yes      | numeric metric | acct             | Acct             | number    | text        |
| Yes      | numeric metric | intjdeobject     | intJDEObject     | number    | text        |
| Yes      | series tag     | description      | Description      | text      | text        |
| Yes      | numeric metric | origadopted      | OrigAdopted      | money     | money       |
| Yes      | numeric metric | adopted          | Adopted          | money     | money       |
| Yes      | numeric metric | presrec          | PresRec          | money     | money       |
| Yes      | numeric metric | amendment        | 2013 Amendment   | money     | money       |
| Yes      | numeric metric | expenditures     | Expenditures     | money     | money       |
| No       |                | builddate        | BuildDate        | text      | text        |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = builddate
```

## Data Commands

```ls
series e:awmg-c7xz d:2013-01-01T00:00:00.000Z t:fundtype=General t:depttitle="County Treasurer" t:dept_text=060 t:genfundtype="Corporate Fund" t:description="Furlough Day Adjustment" t:sort_for_summary="COUNTY TREASURER" t:fundid=1000 m:amendment=-9411 m:acct=108 m:intjdeobject=501035 m:presrec=-9411 m:fundsort=1

series e:awmg-c7xz d:2013-01-01T00:00:00.000Z t:fundtype=Grants t:depttitle="Planning & Development Emergency Solutions" t:dept_text=941 t:genfundtype=Restricted t:description="Salaries and Wages of Regular Employees" t:sort_for_summary="BUREAU OF ECONOMIC DEVELOPMENT - GRANTS" t:fundid=1022 m:amendment=40414 m:acct=110 m:intjdeobject=501010 m:origadopted=40414 m:fundsort=5

series e:awmg-c7xz d:2013-01-01T00:00:00.000Z t:fundtype=General t:depttitle="Contract Compliance" t:dept_text=022 t:genfundtype="Corporate Fund" t:description="Furlough Day Adjustment" t:sort_for_summary="BUREAU OF FINANCE" t:fundid=1000 m:amendment=-2609 m:acct=108 m:intjdeobject=501035 m:presrec=-2609 m:fundsort=1
```

## Meta Commands

```ls
metric m:fundsort p:integer l:FundSort t:dataTypeName=number

metric m:acct p:integer l:Acct t:dataTypeName=number

metric m:intjdeobject p:integer l:intJDEObject t:dataTypeName=number

metric m:origadopted p:integer l:OrigAdopted t:dataTypeName=money

metric m:adopted p:double l:Adopted t:dataTypeName=money

metric m:presrec p:integer l:PresRec t:dataTypeName=money

metric m:amendment p:integer l:"2013 Amendment" t:dataTypeName=money

metric m:expenditures p:decimal l:Expenditures t:dataTypeName=money

entity e:awmg-c7xz l:"Budget Management - 2013 Budget Request by Amount and Department" t:attribution="Cook County Department of Budget and Management Services" t:url=https://datacatalog.cookcountyil.gov/api/views/awmg-c7xz

property e:awmg-c7xz t:meta.view v:id=awmg-c7xz v:category="Finance & Administration" v:attributionLink=http://home.cookcountyil.gov/budget/ v:averageRating=0 v:name="Budget Management - 2013 Budget Request by Amount and Department" v:attribution="Cook County Department of Budget and Management Services"

property e:awmg-c7xz t:meta.view.license v:name="Public Domain"

property e:awmg-c7xz t:meta.view.owner v:id=5nsp-mk24 v:screenName="Kara Hakos" v:displayName="Kara Hakos"

property e:awmg-c7xz t:meta.view.tableauthor v:id=5nsp-mk24 v:screenName="Kara Hakos" v:displayName="Kara Hakos"
```

## Top Records

```ls
| fundid | fundtype | fundsort | genfundtype        | sort_for_summary                                 | dept_text | depttitle                                      | acct | intjdeobject | description                             | origadopted | adopted | presrec | amendment | expenditures       | builddate | 
| ====== | ======== | ======== | ================== | ================================================ | ========= | ============================================== | ==== | ============ | ======================================= | =========== | ======= | ======= | ========= | ================== | ========= | 
| 1000   | General  | 1        | Corporate Fund     | COUNTY TREASURER                                 | 060       | County Treasurer                               | 108  | 501035       | Furlough Day Adjustment                 |             |         | -9411   | -9411     |                    |           | 
| 1022   | Grants   | 5        | Restricted         | BUREAU OF ECONOMIC DEVELOPMENT - GRANTS          | 941       | Planning & Development Emergency Solutions     | 110  | 501010       | Salaries and Wages of Regular Employees | 40414       |         |         | 40414     |                    | 08-Jan-13 | 
| 1000   | General  | 1        | Corporate Fund     | BUREAU OF FINANCE                                | 022       | Contract Compliance                            | 108  | 501035       | Furlough Day Adjustment                 |             |         | -2609   | -2609     |                    |           | 
| 1002   | General  | 3        | Public Safety Fund | CHIEF JUDGE                                      | 305       | Public Guardian                                | 225  | 520260       | Postage                                 | 45000       | 43650   | 45000   | 45000     | 43444.67           | 08-Jan-13 | 
| 1022   | Grants   | 5        | Restricted         | CHIEF JUDGE - Grants                             | 683       | Adult Probation Mental Health                  | 170  | 501510       | Mandatory Medicare Costs                | 23132       | 23132   |         |           | 23049.250000000004 | 08-Jan-13 | 
| 1022   | Grants   | 5        | Restricted         | CHIEF JUDGE - Grants                             | 775       | Chief Judge Family Drug Court                  | 174  | 501570       | Pension                                 | 26683       | 26683   |         | 26683     |                    | 08-Jan-13 | 
| 1022   | Grants   | 5        | Restricted         | COOK COUNTY HEALTH AND HOSPITALS SYSTEM - Grants | 948       | Public Health Genetics Education And Follow-Up | 174  | 501570       | Pension                                 | 8177        | 8177    |         |           | 3206.1             | 08-Jan-13 | 
| 1022   | Grants   | 5        | Restricted         | BUREAU OF ECONOMIC DEVELOPMENT - GRANTS          | 941       | Planning & Development Emergency Solutions     | 175  | 501590       | Life Insurance Program                  | 118         |         |         | 118       |                    | 08-Jan-13 | 
| 1000   | General  | 1        | Corporate Fund     | ASSESSOR                                         | 040       | County Assessor                                | 108  | 501035       | Furlough Day Adjustment                 |             |         | -79278  | -79278    |                    |           | 
| 1022   | Grants   | 5        | Restricted         | SHERIFF - Grants                                 | 645       | Sheriff Human Trafficking Anti-Demand Campaign | 172  | 501540       | Workers' Compensation                   | 968         | 968     |         |           | 0                  | 08-Jan-13 | 
```