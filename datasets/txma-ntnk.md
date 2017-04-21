# Lobbyist Data - Lobbyist Major Expenditures Report (Deprecated October 2015)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/lobbyist-data-lobbyist-major-expenditures-report-d52f9) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/txma-ntnk) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/txma-ntnk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/txma-ntnk/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | txma-ntnk |
| Name | Lobbyist Data - Lobbyist Major Expenditures Report (Deprecated October 2015) |
| Attribution | City of Chicago |
| Category | Ethics |
| Tags | lobbyists, ethics, deprecated |
| Created | 2011-09-30T08:01:04Z |
| Publication Date | 2016-12-06T10:30:31Z |

## Description

OUTDATED. See similar current data at https://data.cityofchicago.org/d/xika-473c --The lobbyist expense report is part of the Lobbyist Activity Report, a notarized disclosure that must be filed twice each year (January 20th and July 20th). Lobbyists are required to report single expenditures paid by the lobbyist or charged to the client totaling $250.00 or more on Form C Part 3 Section H Question 2 (http://bit.ly/q2lRTh). All lobbyist activity reports are submitted to the Board of Ethics in paper form and are available in their entirety in the Board's offices. The Board has, since 2000, compiled and posted static lists of all lobbyists and their clients online. / Data Owner: Board of Ethics [http://j.mp/mbH9BN] / Time Period: January 1, 2011 to present/ Frequency: Data is updated daily / Related Applications: Registered Lobbyist List [http://bit.ly/FOctNY]

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type     | Render Type   |
| ======== | ============== | ======================= | ======================= | ============= | ============= |
| No       |                | filing_year             | FILING YEAR             | number        | number        |
| Yes      | series tag     | lobbyist_last_name      | LOBBYIST LAST NAME      | text          | text          |
| Yes      | series tag     | lobbyist_first_name     | LOBBYIST FIRST NAME     | text          | text          |
| Yes      | series tag     | lobbyist_middle_initial | LOBBYIST MIDDLE INITIAL | text          | text          |
| Yes      | time           | expense_date            | EXPENSE DATE            | calendar_date | calendar_date |
| Yes      | series tag     | recipient_name          | RECIPIENT NAME          | text          | text          |
| Yes      | series tag     | purpose                 | PURPOSE                 | text          | text          |
| Yes      | numeric metric | amount                  | AMOUNT                  | money         | money         |
| Yes      | series tag     | action                  | ACTION                  | text          | text          |
| Yes      | series tag     | client                  | CLIENT                  | text          | text          |
| Yes      | numeric metric | filing_period           | FILING PERIOD           | number        | text          |
```

## Time Field

```ls
Value = expense_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = filing_year
```

## Data Commands

```ls
series e:txma-ntnk d:2011-01-17T00:00:00.000Z t:lobbyist_first_name="B. John" t:client="Wal-Mart Stores, Inc." t:action="Gen. education of business in city" t:purpose=airfare t:recipient_name="American Airlines" t:lobbyist_last_name=Bisio m:amount=1038.62 m:filing_period=1

series e:txma-ntnk d:2011-01-09T00:00:00.000Z t:lobbyist_first_name="B. John" t:client="Wal-Mart Stores, Inc." t:action="Gen. education of business in city" t:purpose=lodging t:recipient_name=Doubletree t:lobbyist_last_name=Bisio m:amount=443.88 m:filing_period=1

series e:txma-ntnk d:2011-01-09T00:00:00.000Z t:lobbyist_first_name="B. John" t:client="Wal-Mart Stores, Inc." t:action="Gen. education of business in city" t:purpose=airfare t:recipient_name="American Airlines" t:lobbyist_last_name=Bisio m:amount=772.08 m:filing_period=1
```

## Meta Commands

```ls
metric m:amount p:double l:AMOUNT t:dataTypeName=money

metric m:filing_period p:integer l:"FILING PERIOD" t:dataTypeName=number

entity e:txma-ntnk l:"Lobbyist Data - Lobbyist Major Expenditures Report (Deprecated October 2015)" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/txma-ntnk

property e:txma-ntnk t:meta.view v:id=txma-ntnk v:category=Ethics v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Lobbyist Data - Lobbyist Major Expenditures Report (Deprecated October 2015)" v:attribution="City of Chicago"

property e:txma-ntnk t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:txma-ntnk t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| filing_year | lobbyist_last_name | lobbyist_first_name | lobbyist_middle_initial | expense_date        | recipient_name    | purpose | amount  | action                             | client                | filing_period | 
| =========== | ================== | =================== | ======================= | =================== | ================= | ======= | ======= | ================================== | ===================== | ============= | 
| 2011        | Bisio              | B. John             |                         | 2011-01-17T00:00:00 | American Airlines | airfare | 1038.62 | Gen. education of business in city | Wal-Mart Stores, Inc. | 1             | 
| 2011        | Bisio              | B. John             |                         | 2011-01-09T00:00:00 | Doubletree        | lodging | 443.88  | Gen. education of business in city | Wal-Mart Stores, Inc. | 1             | 
| 2011        | Bisio              | B. John             |                         | 2011-01-09T00:00:00 | American Airlines | airfare | 772.08  | Gen. education of business in city | Wal-Mart Stores, Inc. | 1             | 
| 2011        | Bisio              | B. John             |                         | 2011-01-01T00:00:00 | Doubletree        | lodging | 409.08  | Gen. education of business in city | Wal-Mart Stores, Inc. | 1             | 
| 2011        | Bisio              | B. John             |                         | 2011-01-01T00:00:00 | American Airlines | airfare | 772.08  | Gen. education of business in city | Wal-Mart Stores, Inc. | 1             | 
| 2011        | Bisio              | B. John             |                         | 2011-01-25T00:00:00 | American Airlines | airfare | 446.72  | Gen. education of business in city | Wal-Mart Stores, Inc. | 1             | 
| 2011        | Bisio              | B. John             |                         | 2011-01-19T00:00:00 | American Airlines | airfare | 1028.84 | Gen. education of business in city | Wal-Mart Stores, Inc. | 1             | 
| 2011        | Bisio              | B. John             |                         | 2011-01-11T00:00:00 | Hotel Felix       | lodging | 706.5   | Gen. education of business in city | Wal-Mart Stores, Inc. | 1             | 
| 2011        | Bisio              | B. John             |                         | 2011-01-11T00:00:00 | American Airlines | airfare | 602.38  | Gen. education of business in city | Wal-Mart Stores, Inc. | 1             | 
| 2011        | Bisio              | B. John             |                         | 2011-01-05T00:00:00 | American Airlines | airfare | 1028.84 | Gen. education of business in city | Wal-Mart Stores, Inc. | 1             | 
```