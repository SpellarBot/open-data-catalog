# Hawaii State Ethics Commission's Ethics Advice

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/hawaii-state-ethics-commissions-ethics-advice-46070) |
| Metadata | [Link](https://data.hawaii.gov/api/views/6ms4-gnxa) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/6ms4-gnxa/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/6ms4-gnxa/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | 6ms4-gnxa |
| Name | Hawaii State Ethics Commission's Ethics Advice |
| Created | 2014-01-23T20:22:52Z |
| Publication Date | 2017-03-21T02:18:18Z |

## Columns

```ls
| Included | Schema Type | Field Name  | Name        | Data Type     | Render Type   |
| ======== | =========== | =========== | =========== | ============= | ============= |
| Yes      | series tag  | advice_name | Advice Name | url           | url           |
| Yes      | series tag  | advice_type | Advice Type | text          | text          |
| No       |             | year_issued | Year Issued | number        | number        |
| Yes      | time        | date_issued | Date Issued | calendar_date | calendar_date |
| Yes      | series tag  | keywords    | Keywords    | text          | text          |
```

## Time Field

```ls
Value = date_issued
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = year_issued
```

## Data Commands

```ls
series e:6ms4-gnxa d:2012-07-18T00:00:00.000Z t:keywords="Lobbyist Law; Chapter 97; Hawaii Family Forum" t:advice_type="Resolution of Charge" t:advice_name=http://files.hawaii.gov/ethics/advice/ROC2012-1.pdf m:row_number.6ms4-gnxa=1

series e:6ms4-gnxa d:2012-07-18T00:00:00.000Z t:keywords="Lobbyist Law; Chapter 97; Hawaii Catholic Conference" t:advice_type="Resolution of Charge" t:advice_name=http://files.hawaii.gov/ethics/advice/ROC2012-2.pdf m:row_number.6ms4-gnxa=2

series e:6ms4-gnxa d:2012-08-01T00:00:00.000Z t:keywords="State Ethics Code; 84-13(4); May Ann Beamer; Private Tennis Lessons" t:advice_type="Resolution of Charge" t:advice_name=http://files.hawaii.gov/ethics/advice/ROC2012-4.pdf m:row_number.6ms4-gnxa=3
```

## Meta Commands

```ls
metric m:row_number.6ms4-gnxa p:long l:"Row Number"

entity e:6ms4-gnxa l:"Hawaii State Ethics Commission's Ethics Advice" t:url=https://data.hawaii.gov/api/views/6ms4-gnxa

property e:6ms4-gnxa t:meta.view v:id=6ms4-gnxa v:averageRating=0 v:name="Hawaii State Ethics Commission's Ethics Advice"

property e:6ms4-gnxa t:meta.view.owner v:id=ikz2-vjne v:screenName=PatrickLui v:displayName=PatrickLui

property e:6ms4-gnxa t:meta.view.tableauthor v:id=ikz2-vjne v:screenName=PatrickLui v:roleName=editor v:displayName=PatrickLui
```

## Top Records

```ls
| advice_name                                                      | advice_type          | year_issued | date_issued         | keywords                                                                                                         | 
| ================================================================ | ==================== | =========== | =================== | ================================================================================================================ | 
| [http://files.hawaii.gov/ethics/advice/ROC2012-1.pdf, ROC2012-1] | Resolution of Charge | 2012        | 2012-07-18T00:00:00 | Lobbyist Law; Chapter 97; Hawaii Family Forum                                                                    | 
| [http://files.hawaii.gov/ethics/advice/ROC2012-2.pdf, ROC2012-2] | Resolution of Charge | 2012        | 2012-07-18T00:00:00 | Lobbyist Law; Chapter 97; Hawaii Catholic Conference                                                             | 
| [http://files.hawaii.gov/ethics/advice/ROC2012-4.pdf, ROC2012-4] | Resolution of Charge | 2012        | 2012-08-01T00:00:00 | State Ethics Code; 84-13(4); May Ann Beamer; Private Tennis Lessons                                              | 
| [http://files.hawaii.gov/ethics/advice/ROC2012-5.pdf, ROC2012-5] | Resolution of Charge | 2012        | 2012-12-03T00:00:00 | Lobbyist Law; Chapter 97; Relativity Media                                                                       | 
| [http://files.hawaii.gov/ethics/advice/ROC2013-1.pdf, ROC2013-1] | Resolution of Charge | 2013        | 2013-11-20T00:00:00 | State Ethics Code; Chapter 84; Golf from State Vendors; DOT                                                      | 
| [http://files.hawaii.gov/ethics/advice/ROC2013-2.pdf, ROC2013-2] | Resolution of Charge | 2013        | 2013-11-20T00:00:00 | State Ethics Code; 84-13(3); 84-13(4); Koa Art Gallery; Director David Behlke; Kapiolani Community College (KCC) | 
| [http://files.hawaii.gov/ethics/advice/EA2013-01.pdf, EA2013-01] | Ethics Advisory      | 2013        | 2013-05-30T00:00:00 | UH Athletic Tickets                                                                                              | 
| [http://files.hawaii.gov/ethics/advice/EA2013-02.pdf, EA2013-02] | Ethics Advisory      | 2013        | 2013-07-03T00:00:00 | Complimentary Golf and Golf Tournament Fees                                                                      | 
| [http://files.hawaii.gov/ethics/advice/EA2013-03.pdf, EA2013-03] | Ethics Advisory      | 2013        | 2013-07-15T00:00:00 | Board Member Applying for Position Selected, Hired or Otherwise Subject to Approval By the Board                 | 
| [http://files.hawaii.gov/ethics/advice/EA2013-04.pdf, EA2013-04] | Ethics Advisory      | 2013        | 2013-10-15T00:00:00 | University of Hawaii Athletic Ticket Discount Policies                                                           | 
```