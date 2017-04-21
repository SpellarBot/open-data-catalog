# Pre-2016 Lobbyist Compensation and Expenses by Source

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/draft-pre-2016-lobbyist-compensation-and-expenses-by-source) |
| Metadata | [Link](https://data.wa.gov/api/views/3v2j-kqbi) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/3v2j-kqbi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/3v2j-kqbi/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | 3v2j-kqbi |
| Name | Pre-2016 Lobbyist Compensation and Expenses by Source |
| Attribution | Public Disclosure Commission |
| Tags | political finance, lobbying, elections, contributions, campaign, political committee, disclosure |
| Created | 2017-01-17T23:28:28Z |
| Publication Date | 2017-04-18T06:15:56Z |

## Description

This dataset only contains records for reporting years 2015 and prior. In 2016, the PDC implemented a new system for managing lobbyist reports and electronic filing. The layout of these records is incompatible with the 2016 and later record layout. Please refer to the "Lobbyist Compensation and Expenses by Source" dataset for 2016 and later records.

This dataset contains summary records of monthly reports of lobbying activity. One record is included for each client that paid compensation or incurred expenses during the filing period. If the lobbyist firm themselves incurred any expenses not reimbursed by a client, a record is included summarizing the lobbyist firm's expenses. Records are included for the period from 10 years prior to the current date to the end of 2015. The date is determined as the filing period of the report, not the date received. Records are included for the full year so for example, all 2007 records will be included until the entire year 2007 falls outside the 10 year time span.

This dataset is a best-effort by the PDC to provide a complete set of records as described herewith and may contain incomplete or incorrect information. The PDC provides access to the original reports for the purpose of record verification.

Descriptions attached to this dataset do not constitute legal definitions; please consult RCW 42.17A and WAC Title 390 for legal definitions and additional information regarding political finance disclosure requirements.

CONDITION OF RELEASE: This publication and or referenced documents constitutes a list of individuals prepared by the Washington State Public Disclosure Commission and may not be used for commercial purposes. This list is provided on the condition and with the understanding that the persons receiving it agree to this statutorily imposed limitation on its use. See RCW 42.56.070(9) and AGO 1975 No. 15.

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type     | Render Type   |
| ======== | ============== | =================== | =================== | ============= | ============= |
| No       |                | id                  | id                  | text          | text          |
| Yes      | series tag     | report_number       | report_number       | text          | text          |
| Yes      | series tag     | origin              | origin              | text          | text          |
| Yes      | series tag     | filer_id            | filer_id            | text          | text          |
| Yes      | series tag     | filer_name          | filer_name          | text          | text          |
| Yes      | series tag     | type                | type                | text          | text          |
| Yes      | series tag     | funding_source_id   | funding_source_id   | text          | text          |
| Yes      | series tag     | funding_source_name | funding_source_name | text          | text          |
| Yes      | time           | filing_period       | filing_period       | calendar_date | calendar_date |
| No       |                | receipt_date        | receipt_date        | calendar_date | calendar_date |
| Yes      | series tag     | employer_id         | employer_id         | text          | text          |
| Yes      | series tag     | employer_name       | employer_name       | text          | text          |
| Yes      | numeric metric | compensation        | compensation        | money         | money         |
| Yes      | numeric metric | personal_expenses   | personal_expenses   | money         | money         |
| Yes      | numeric metric | entertainment       | entertainment       | money         | money         |
| Yes      | numeric metric | contributions       | contributions       | money         | money         |
| Yes      | numeric metric | advertising         | advertising         | money         | money         |
| Yes      | numeric metric | political_ads       | political_ads       | money         | money         |
| Yes      | numeric metric | other               | other               | money         | money         |
| Yes      | series tag     | new_filer_id        | new_filer_id        | text          | text          |
| Yes      | series tag     | new_employer_id     | new_employer_id     | text          | text          |
```

## Time Field

```ls
Value = filing_period
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = id,receipt_date
```

## Data Commands

```ls
series e:3v2j-kqbi d:2012-09-01T00:00:00.000Z t:employer_id="1000FW 1011" t:report_number=PUTNA__1041-2012-09-01 t:filer_name="APRIL PUTNEY" t:filer_id="PUTNA  1041" t:employer_name=FUTUREWISE t:origin=FL t:funding_source_name=FUTUREWISE t:new_employer_id=16054 t:type=Employer t:funding_source_id="1000FW 1011" m:compensation=191.33 m:political_ads=0 m:other=0 m:advertising=0 m:entertainment=0 m:contributions=0 m:personal_expenses=56.26

series e:3v2j-kqbi d:2012-10-01T00:00:00.000Z t:employer_id="1000FW 1011" t:report_number=PUTNA__1041-2012-10-01 t:filer_name="APRIL PUTNEY" t:filer_id="PUTNA  1041" t:employer_name=FUTUREWISE t:origin=FL t:funding_source_name=FUTUREWISE t:new_employer_id=16054 t:type=Employer t:funding_source_id="1000FW 1011" m:compensation=40.11 m:political_ads=0 m:other=0 m:advertising=0 m:entertainment=0 m:contributions=0 m:personal_expenses=148.33

series e:3v2j-kqbi d:2012-11-01T00:00:00.000Z t:employer_id="1000FW 1011" t:report_number=PUTNA__1041-2012-11-01 t:filer_name="APRIL PUTNEY" t:filer_id="PUTNA  1041" t:employer_name=FUTUREWISE t:origin=FL t:funding_source_name=FUTUREWISE t:new_employer_id=16054 t:type=Employer t:funding_source_id="1000FW 1011" m:compensation=88.24 m:political_ads=0 m:other=0 m:advertising=0 m:entertainment=0 m:contributions=0 m:personal_expenses=92.84
```

## Meta Commands

```ls
metric m:compensation p:double l:compensation d:"This is the sum total of compensation reported for this employer on this L2." t:dataTypeName=money

metric m:personal_expenses p:double l:personal_expenses d:"This is the sum total of personal expenses reported for this L2 and filing period." t:dataTypeName=money

metric m:entertainment p:double l:entertainment d:"This is the sum total of entertainment expenses reported for this L2 and filing period." t:dataTypeName=money

metric m:contributions p:double l:contributions d:"This is the sum total of contributions reported for this L2 and filing period." t:dataTypeName=money

metric m:advertising p:double l:advertising d:"This is the sum total of advertising expenses reported for this L2 and filing period." t:dataTypeName=money

metric m:political_ads p:double l:political_ads d:"This is the sum total of political ads expenses reported for this L2 and filing period." t:dataTypeName=money

metric m:other p:double l:other d:"This is the sum total of other expenses reported for this L2 and filing period." t:dataTypeName=money

entity e:3v2j-kqbi l:"Pre-2016 Lobbyist Compensation and Expenses by Source" t:attribution="Public Disclosure Commission" t:url=https://data.wa.gov/api/views/3v2j-kqbi

property e:3v2j-kqbi t:meta.view v:id=3v2j-kqbi v:attributionLink=http://www.pdc.wa.gov v:averageRating=0 v:name="Pre-2016 Lobbyist Compensation and Expenses by Source" v:attribution="Public Disclosure Commission"

property e:3v2j-kqbi t:meta.view.license v:name="Public Domain"

property e:3v2j-kqbi t:meta.view.owner v:id=6hhm-htpq v:profileImageUrlMedium=/api/users/6hhm-htpq/profile_images/THUMB v:profileImageUrlLarge=/api/users/6hhm-htpq/profile_images/LARGE v:screenName="Washington Public Disclosure Commission" v:profileImageUrlSmall=/api/users/6hhm-htpq/profile_images/TINY v:displayName="Washington Public Disclosure Commission"

property e:3v2j-kqbi t:meta.view.tableauthor v:id=6hhm-htpq v:profileImageUrlMedium=/api/users/6hhm-htpq/profile_images/THUMB v:profileImageUrlLarge=/api/users/6hhm-htpq/profile_images/LARGE v:screenName="Washington Public Disclosure Commission" v:profileImageUrlSmall=/api/users/6hhm-htpq/profile_images/TINY v:roleName=publisher v:displayName="Washington Public Disclosure Commission"
```

## Top Records

```ls
| id     | report_number          | origin | filer_id   | filer_name   | type     | funding_source_id | funding_source_name | filing_period       | receipt_date        | employer_id | employer_name | compensation | personal_expenses | entertainment | contributions | advertising | political_ads | other | new_filer_id | new_employer_id | 
| ====== | ====================== | ====== | ========== | ============ | ======== | ================= | =================== | =================== | =================== | =========== | ============= | ============ | ================= | ============= | ============= | =========== | ============= | ===== | ============ | =============== | 
| 197785 | PUTNA__1041-2012-09-01 | FL     | PUTNA 1041 | APRIL PUTNEY | Employer | 1000FW 1011       | FUTUREWISE          | 2012-09-01T00:00:00 | 2013-01-08T00:00:00 | 1000FW 1011 | FUTUREWISE    | 191.33       | 56.26             | 0.00          | 0.00          | 0.00        | 0.00          | 0.00  |              | 16054           | 
| 199355 | PUTNA__1041-2012-10-01 | FL     | PUTNA 1041 | APRIL PUTNEY | Employer | 1000FW 1011       | FUTUREWISE          | 2012-10-01T00:00:00 | 2013-01-08T00:00:00 | 1000FW 1011 | FUTUREWISE    | 40.11        | 148.33            | 0.00          | 0.00          | 0.00        | 0.00          | 0.00  |              | 16054           | 
| 200427 | PUTNA__1041-2012-11-01 | FL     | PUTNA 1041 | APRIL PUTNEY | Employer | 1000FW 1011       | FUTUREWISE          | 2012-11-01T00:00:00 | 2013-01-08T00:00:00 | 1000FW 1011 | FUTUREWISE    | 88.24        | 92.84             | 0.00          | 0.00          | 0.00        | 0.00          | 0.00  |              | 16054           | 
| 201582 | PUTNA__1041-2012-12-01 | FL     | PUTNA 1041 | APRIL PUTNEY | Employer | 1000FW 1011       | FUTUREWISE          | 2012-12-01T00:00:00 | 2013-01-08T00:00:00 | 1000FW 1011 | FUTUREWISE    | 460.89       | 0.00              | 0.00          | 0.00          | 0.00        | 0.00          | 0.00  |              | 16054           | 
| 202971 | PUTNA__1041-2013-01-01 | FL     | PUTNA 1041 | APRIL PUTNEY | Employer | 1000FW 1011       | FUTUREWISE          | 2013-01-01T00:00:00 | 2013-02-10T00:00:00 | 1000FW 1011 | FUTUREWISE    | 3250.32      | 151.01            | 0.00          | 0.00          | 0.00        | 1500.00       | 0.00  |              | 16054           | 
| 206610 | PUTNA__1041-2013-03-01 | FL     | PUTNA 1041 | APRIL PUTNEY | Employer | 1000FW 1011       | FUTUREWISE          | 2013-03-01T00:00:00 | 2013-04-14T00:00:00 | 1000FW 1011 | FUTUREWISE    | 3250.29      | 90.33             | 0.00          | 0.00          | 0.00        | 0.00          | 0.00  |              | 16054           | 
| 205428 | PUTNA__1041-2013-02-01 | FL     | PUTNA 1041 | APRIL PUTNEY | Employer | 1000FW 1011       | FUTUREWISE          | 2013-02-01T00:00:00 | 2014-02-28T00:00:00 | 1000FW 1011 | FUTUREWISE    | 3250.29      | 83.58             | 0.00          | 0.00          | 0.00        | 0.00          | 0.00  |              | 16054           | 
| 207548 | PUTNA__1041-2013-04-01 | FL     | PUTNA 1041 | APRIL PUTNEY | Employer | 1000FW 1011       | FUTUREWISE          | 2013-04-01T00:00:00 | 2014-02-28T00:00:00 | 1000FW 1011 | FUTUREWISE    | 3250.29      | 157.65            | 0.00          | 0.00          | 0.00        | 0.00          | 0.00  |              | 16054           | 
| 210013 | PUTNA__1041-2013-05-01 | FL     | PUTNA 1041 | APRIL PUTNEY | Employer | 1000FW 1011       | FUTUREWISE          | 2013-05-01T00:00:00 | 2014-02-28T00:00:00 | 1000FW 1011 | FUTUREWISE    | 3250.29      | 81.46             | 400.00        | 0.00          | 0.00        | 0.00          | 0.00  |              | 16054           | 
| 211218 | PUTNA__1041-2013-06-01 | FL     | PUTNA 1041 | APRIL PUTNEY | Employer | 1000FW 1011       | FUTUREWISE          | 2013-06-01T00:00:00 | 2014-02-28T00:00:00 | 1000FW 1011 | FUTUREWISE    | 3250.29      | 152.68            | 0.00          | 0.00          | 0.00        | 0.00          | 0.00  |              | 16054           | 
```