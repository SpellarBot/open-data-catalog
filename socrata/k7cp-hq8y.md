# City Budget Expenditures by Fund by Fiscal Year

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/city-budget-expenditures-by-fund-by-fiscal-year) |
| Metadata | [Link](https://data.iowa.gov/api/views/k7cp-hq8y) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/k7cp-hq8y/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/k7cp-hq8y/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | k7cp-hq8y |
| Name | City Budget Expenditures by Fund by Fiscal Year |
| Attribution | Iowa Department of Management, Certified City Budgets |
| Category | Government |
| Tags | city, expenditures, budget, fund |
| Created | 2015-08-07T13:17:22Z |
| Publication Date | 2015-08-14T18:20:36Z |

## Description

Budgeted expenditures for all Iowa cities.

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| Yes      | series tag     | unique_line_id      | Unique Line ID      | text      | text        |
| Yes      | series tag     | code                | City ID Code        | text      | text        |
| Yes      | series tag     | gnis_feature_id     | GNIS Feature ID     | text      | number      |
| Yes      | series tag     | city_name           | City Name           | text      | text        |
| Yes      | time           | fiscal_year         | Fiscal Year         | number    | number      |
| Yes      | series tag     | expense_line_item   | Line Item           | text      | text        |
| Yes      | series tag     | expenditure_program | Expenditure Program | text      | text        |
| Yes      | series tag     | fund                | Fund                | text      | text        |
| Yes      | numeric metric | value               | Expenditure Amount  | money     | money       |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:k7cp-hq8y d:2009-01-01T00:00:00.000Z t:city_name=MANCHESTER t:unique_line_id="28G263-EXP P1-H-24-2009" t:gnis_feature_id=458752 t:expenditure_program="Health & Social Services" t:fund="Permanent Fund" t:code=28G263 t:expense_line_item="City Hospital" m:value=0

series e:k7cp-hq8y d:2014-01-01T00:00:00.000Z t:city_name=BRADDYVILLE t:unique_line_id="73G673-EXP P1-D-18-2014" t:gnis_feature_id=463554 t:expenditure_program="Public Works" t:fund="Special Revenue Fund" t:code=73G673 t:expense_line_item="Street Cleaning" m:value=0

series e:k7cp-hq8y d:2014-01-01T00:00:00.000Z t:city_name=MELROSE t:unique_line_id="68G643-EXP P2-C-54-2014" t:gnis_feature_id=458957 t:expenditure_program="Debt Service" t:fund="General Fund" t:code=68G643 t:expense_line_item="Debt Service" m:value=0
```

## Meta Commands

```ls
metric m:value p:integer l:"Expenditure Amount" d:"Amount of budgeted expenditure from the fund listed, for the line item listed." t:dataTypeName=money

entity e:k7cp-hq8y l:"City Budget Expenditures by Fund by Fiscal Year" t:attribution="Iowa Department of Management, Certified City Budgets" t:url=https://data.iowa.gov/api/views/k7cp-hq8y

property e:k7cp-hq8y t:meta.view v:id=k7cp-hq8y v:category=Government v:averageRating=0 v:name="City Budget Expenditures by Fund by Fiscal Year" v:attribution="Iowa Department of Management, Certified City Budgets"

property e:k7cp-hq8y t:meta.view.license v:name="Public Domain"

property e:k7cp-hq8y t:meta.view.owner v:id=58aa-5akg v:profileImageUrlMedium=/api/users/58aa-5akg/profile_images/THUMB v:profileImageUrlLarge=/api/users/58aa-5akg/profile_images/LARGE v:screenName="IDOM, Local Budget & Finance" v:profileImageUrlSmall=/api/users/58aa-5akg/profile_images/TINY v:displayName="IDOM, Local Budget & Finance"

property e:k7cp-hq8y t:meta.view.tableauthor v:id=58aa-5akg v:profileImageUrlMedium=/api/users/58aa-5akg/profile_images/THUMB v:profileImageUrlLarge=/api/users/58aa-5akg/profile_images/LARGE v:screenName="IDOM, Local Budget & Finance" v:profileImageUrlSmall=/api/users/58aa-5akg/profile_images/TINY v:roleName=editor v:displayName="IDOM, Local Budget & Finance"
```

## Top Records

```ls
| unique_line_id          | code   | gnis_feature_id | city_name   | fiscal_year | expense_line_item           | expenditure_program              | fund                     | value | 
| ======================= | ====== | =============== | =========== | =========== | =========================== | ================================ | ======================== | ===== | 
| 28G263-EXP P1-H-24-2009 | 28G263 | 458752          | MANCHESTER  | 2009        | City Hospital               | Health & Social Services         | Permanent Fund           | 0     | 
| 73G673-EXP P1-D-18-2014 | 73G673 | 463554          | BRADDYVILLE | 2014        | Street Cleaning             | Public Works                     | Special Revenue Fund     | 0     | 
| 68G643-EXP P2-C-54-2014 | 68G643 | 458957          | MELROSE     | 2014        | Debt Service                | Debt Service                     | General Fund             | 0     | 
| 71G660-EXP P1-D-20-2016 | 71G660 | 457297          | HARTLEY     | 2016        | Garbage (if not Enterprise) | Public Works                     | Special Revenue Fund     | 0     | 
| 28G259-EXP P1-D-32-2012 | 28G259 | 456061          | DUNDEE      | 2012        | Museum, Band and Theater    | Culture & Recreation             | Special Revenue Fund     | 0     | 
| 62G584-EXP P1-H-6-2013  | 62G584 | 454362          | BARNES CITY | 2013        | Ambulance                   | Public Safety                    | Permanent Fund           | 0     | 
| 67G639-EXP P1-H-5-2014  | 67G639 | 462506          | UTE         | 2014        | Fire Department             | Public Safety                    | Permanent Fund           | 0     | 
| 76G708-EXP P2-H-39-2010 | 76G708 | 460323          | PLOVER      | 2010        | Community Beautification    | Community & Economic Development | Permanent Fund           | 0     | 
| 61G577-EXP P1-E-23-2009 | 61G577 | 456104          | EARLHAM     | 2009        | Welfare Assistance          | Health & Social Services         | TIF Special Revenue Fund | 0     | 
| 75G700-EXP P2-I-71-2015 | 75G700 | 460584          | REMSEN      | 2015        | Enterprise CAPITAL PROJECT  | Business Type/Enterprise         | Proprietary Fund         | 0     | 
```