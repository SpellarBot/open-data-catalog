# Lobbyist Data - Expenditures - Small

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/lobbyist-data-expenditures-small) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/eqdx-4qxd) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/eqdx-4qxd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/eqdx-4qxd/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | eqdx-4qxd |
| Name | Lobbyist Data - Expenditures - Small |
| Attribution | City of Chicago |
| Category | Ethics |
| Tags | ethics, lobbyists |
| Created | 2015-06-18T20:29:07Z |
| Publication Date | 2015-10-20T20:59:24Z |

## Description

Expenditures under $250 per transaction, summarized per three-month reporting period.  Larger expenditures are itemized in https://data.cityofchicago.org/d/xika-473c.   See http://www.cityofchicago.org/city/en/depts/ethics/provdrs/lobby.html for more information on the Board of Ethics' role in regulating and reporting on lobbying in Chicago.

## Columns

```ls
| Included | Schema Type    | Field Name                     | Name                           | Data Type     | Render Type   |
| ======== | ============== | ============================== | ============================== | ============= | ============= |
| Yes      | series tag     | compensation_id                | COMPENSATION_ID                | text          | number        |
| Yes      | time           | period_start                   | PERIOD_START                   | calendar_date | calendar_date |
| No       |                | period_end                     | PERIOD_END                     | calendar_date | calendar_date |
| Yes      | series tag     | lobbyist_id                    | LOBBYIST_ID                    | text          | number        |
| Yes      | series tag     | lobbyist_first_name            | LOBBYIST_FIRST_NAME            | text          | text          |
| Yes      | series tag     | lobbyist_middle_initial        | LOBBYIST_MIDDLE_INITIAL        | text          | text          |
| Yes      | series tag     | lobbyist_last_name             | LOBBYIST_LAST_NAME             | text          | text          |
| Yes      | numeric metric | compensation_to_others_expense | COMPENSATION_TO_OTHERS_EXPENSE | money         | money         |
| Yes      | numeric metric | office_expense                 | OFFICE_EXPENSE                 | money         | money         |
| Yes      | numeric metric | personal_sustenance_expense    | PERSONAL_SUSTENANCE_EXPENSE    | money         | money         |
| Yes      | numeric metric | public_education_expense       | PUBLIC_EDUCATION_EXPENSE       | money         | money         |
| Yes      | numeric metric | other_expenses                 | OTHER_EXPENSES                 | money         | money         |
| Yes      | numeric metric | total_expenses                 | TOTAL_EXPENSES                 | money         | money         |
| Yes      | series tag     | client_id                      | CLIENT_ID                      | text          | number        |
| Yes      | series tag     | client_name                    | CLIENT_NAME                    | text          | text          |
| No       |                | created_date                   | CREATED_DATE                   | calendar_date | calendar_date |
```

## Time Field

```ls
Value = period_start
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = period_end,created_date
```

## Data Commands

```ls
series e:eqdx-4qxd d:2014-04-01T00:00:00.000Z t:lobbyist_first_name=Jeffrey t:lobbyist_id=17144 t:client_id=12433 t:compensation_id=23619 t:client_name="Goldman, Sachs & Co" t:lobbyist_last_name=Scruggs m:compensation_to_others_expense=0 m:other_expenses=0 m:public_education_expense=0 m:office_expense=0 m:total_expenses=505.5 m:personal_sustenance_expense=505.5

series e:eqdx-4qxd d:2012-01-01T00:00:00.000Z t:lobbyist_first_name=Freda t:lobbyist_id=5807 t:client_id=12433 t:compensation_id=597 t:client_name="Goldman, Sachs & Co" t:lobbyist_last_name=Wang m:compensation_to_others_expense=0 m:other_expenses=0 m:public_education_expense=0 m:office_expense=0 m:total_expenses=423.65 m:personal_sustenance_expense=423.65

series e:eqdx-4qxd d:2012-07-01T00:00:00.000Z t:lobbyist_first_name=Scott t:lobbyist_id=10225 t:client_id=12435 t:compensation_id=14552 t:client_name="US Bancorp Investments, Inc" t:lobbyist_last_name=Verch m:compensation_to_others_expense=0 m:other_expenses=0 m:public_education_expense=0 m:office_expense=0 m:total_expenses=352.6 m:personal_sustenance_expense=352.6
```

## Meta Commands

```ls
metric m:compensation_to_others_expense p:double l:COMPENSATION_TO_OTHERS_EXPENSE t:dataTypeName=money

metric m:office_expense p:double l:OFFICE_EXPENSE t:dataTypeName=money

metric m:personal_sustenance_expense p:double l:PERSONAL_SUSTENANCE_EXPENSE t:dataTypeName=money

metric m:public_education_expense p:double l:PUBLIC_EDUCATION_EXPENSE t:dataTypeName=money

metric m:other_expenses p:double l:OTHER_EXPENSES t:dataTypeName=money

metric m:total_expenses p:double l:TOTAL_EXPENSES d:"Sum of the expense columns." t:dataTypeName=money

entity e:eqdx-4qxd l:"Lobbyist Data - Expenditures - Small" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/eqdx-4qxd

property e:eqdx-4qxd t:meta.view v:id=eqdx-4qxd v:category=Ethics v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Lobbyist Data - Expenditures - Small" v:attribution="City of Chicago"

property e:eqdx-4qxd t:meta.view.owner v:id=vewm-vupz v:screenName="Jonathan Levy" v:displayName="Jonathan Levy"

property e:eqdx-4qxd t:meta.view.tableauthor v:id=vewm-vupz v:screenName="Jonathan Levy" v:roleName=administrator v:displayName="Jonathan Levy"
```

## Top Records

```ls
| compensation_id | period_start        | period_end          | lobbyist_id | lobbyist_first_name | lobbyist_middle_initial | lobbyist_last_name | compensation_to_others_expense | office_expense | personal_sustenance_expense | public_education_expense | other_expenses | total_expenses | client_id | client_name                        | created_date        | 
| =============== | =================== | =================== | =========== | =================== | ======================= | ================== | ============================== | ============== | =========================== | ======================== | ============== | ============== | ========= | ================================== | =================== | 
| 23619           | 2014-04-01T00:00:00 | 2014-06-30T00:00:00 | 17144       | Jeffrey             |                         | Scruggs            | 0                              | 0              | 505.5                       | 0                        | 0              | 505.5          | 12433     | Goldman, Sachs & Co                | 2014-07-07T00:00:00 | 
| 597             | 2012-01-01T00:00:00 | 2012-06-30T00:00:00 | 5807        | Freda               |                         | Wang               | 0                              | 0              | 423.65                      | 0                        | 0              | 423.65         | 12433     | Goldman, Sachs & Co                | 2012-08-21T00:00:00 | 
| 14552           | 2012-07-01T00:00:00 | 2012-09-30T00:00:00 | 10225       | Scott               |                         | Verch              | 0                              | 0              | 352.6                       | 0                        | 0              | 352.6          | 12435     | US Bancorp Investments, Inc        | 2013-10-03T00:00:00 | 
| 487             | 2012-01-01T00:00:00 | 2012-06-30T00:00:00 | 5809        | Richard             | E                       | Kolman             | 0                              | 0              | 61.74                       | 0                        | 0              | 61.74          | 12435     | US Bancorp Investments, Inc        | 2012-08-14T00:00:00 | 
| 21084           | 2014-01-01T00:00:00 | 2014-03-31T00:00:00 | 16611       | Richard             | E                       | Kolman             | 0                              | 0              | 470                         | 0                        | 0              | 470            | 12436     | US Bank Municipal Securities Group | 2014-04-14T00:00:00 | 
| 2488            | 2012-01-01T00:00:00 | 2012-06-30T00:00:00 | 9241        | Richard             | E                       | Kolman             | 0                              | 0              | 61.74                       | 0                        | 0              | 61.74          | 12436     | US Bank Municipal Securities Group | 2012-09-27T00:00:00 | 
| 8916            | 2013-01-01T00:00:00 | 2013-03-31T00:00:00 | 11103       | B. John             |                         | Bisio              | 0                              | 0              | 480.44                      | 0                        | 0              | 480.44         | 12443     | Wal-Mart Stores, Inc.              | 2013-04-18T00:00:00 | 
| 28130           | 2014-07-01T00:00:00 | 2014-09-30T00:00:00 | 20187       | Ann                 | T                       | Moroney            | 0                              | 4418.36        | 0                           | 0                        | 0              | 4418.36        | 12469     | Swedish Covenant Hospital          | 2014-10-15T00:00:00 | 
| 25866           | 2014-01-01T00:00:00 | 2014-03-31T00:00:00 | 20383       | Bernard             | I                       | Citron             | 0                              | 75             | 0                           | 0                        | 0              | 75             | 12470     | Imperial Realty Co.                | 2014-07-31T00:00:00 | 
| 38061           | 2015-04-01T00:00:00 | 2015-06-30T00:00:00 | 22834       | David               | R                       | Hill               | 0                              | 5.75           | 0                           | 0                        | 0              | 5.75           | 12474     | Celadon Holdings LLC               | 2015-06-16T00:00:00 | 
```