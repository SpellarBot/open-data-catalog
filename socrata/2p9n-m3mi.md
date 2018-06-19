# Board of Ethics -- 2011 Monthly Board of Ethics Statistics

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/board-of-ethics-2011-monthly-board-of-ethics-statistics-f699d) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/2p9n-m3mi) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/2p9n-m3mi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/2p9n-m3mi/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | 2p9n-m3mi |
| Name | Board of Ethics -- 2011 Monthly Board of Ethics Statistics |
| Attribution | Cook County Board of Ethics |
| Category | Finance & Administration |
| Created | 2011-10-31T17:12:37Z |
| Publication Date | 2014-10-27T15:43:04Z |

## Description

Updated 11/1/2011.  Monthly file that represents Ethics Statistics on Training Seminars, Employees Trained, Inquiries (Pre-Bid Meetings included), New Investigations, Advisory Opinions Issued, Vendor Compliance Audit, Lobbyist Expense Audit, and Pplitical Contributions Audit

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type | Render Type |
| ======== | ============== | ========================== | ========================== | ========= | =========== |
| Yes      | series tag     | board_of_ethics_statistics | BOARD OF ETHICS STATISTICS | text      | text        |
| Yes      | numeric metric | dec                        | DEC                        | number    | number      |
| Yes      | numeric metric | jan                        | JAN                        | number    | number      |
| Yes      | numeric metric | feb                        | FEB                        | number    | number      |
| Yes      | numeric metric | mar                        | MAR                        | number    | number      |
| Yes      | numeric metric | apr                        | APR                        | number    | number      |
| Yes      | numeric metric | may                        | MAY                        | number    | number      |
| Yes      | numeric metric | jun                        | JUN                        | number    | number      |
| Yes      | numeric metric | jul                        | JUL                        | number    | number      |
| Yes      | numeric metric | aug                        | AUG                        | number    | number      |
| Yes      | numeric metric | sep                        | SEP                        | number    | number      |
| Yes      | series tag     | oct                        | OCT                        | text      | text        |
| Yes      | series tag     | nov                        | NOV                        | text      | text        |
| Yes      | numeric metric | ytd_totals                 | YTD Totals                 | number    | number      |
```

## Time Field

```ls
Value = 2011
Format & Zone = yyyy
```

## Data Commands

```ls
series e:2p9n-m3mi d:2011-01-01T00:00:00.000Z t:oct=- t:nov=- t:board_of_ethics_statistics="Training Seminars" m:may=2 m:apr=4 m:dec=3 m:feb=2 m:jul=2 m:sep=2 m:jun=5 m:jan=2 m:mar=3 m:aug=1 m:ytd_totals=26

series e:2p9n-m3mi d:2011-01-01T00:00:00.000Z t:oct=- t:nov=- t:board_of_ethics_statistics="Employees Trained" m:may=38 m:apr=35 m:dec=29 m:feb=26 m:jul=32 m:sep=31 m:jun=565 m:jan=29 m:mar=84 m:aug=16 m:ytd_totals=885

series e:2p9n-m3mi d:2011-01-01T00:00:00.000Z t:oct=- t:nov=- t:board_of_ethics_statistics="Inquiries (Pre-Bid Mtgs included)" m:may=21 m:apr=37 m:dec=24 m:feb=10 m:jul=29 m:sep=25 m:jun=26 m:jan=22 m:mar=17 m:aug=25 m:ytd_totals=236
```

## Meta Commands

```ls
metric m:dec p:integer l:DEC t:dataTypeName=number

metric m:jan p:integer l:JAN t:dataTypeName=number

metric m:feb p:integer l:FEB t:dataTypeName=number

metric m:mar p:integer l:MAR t:dataTypeName=number

metric m:apr p:integer l:APR t:dataTypeName=number

metric m:may p:integer l:MAY t:dataTypeName=number

metric m:jun p:integer l:JUN t:dataTypeName=number

metric m:jul p:integer l:JUL t:dataTypeName=number

metric m:aug p:integer l:AUG t:dataTypeName=number

metric m:sep p:integer l:SEP t:dataTypeName=number

metric m:ytd_totals p:integer l:"YTD Totals" t:dataTypeName=number

entity e:2p9n-m3mi l:"Board of Ethics -- 2011 Monthly  Board of Ethics Statistics" t:attribution="Cook County Board of Ethics" t:url=https://datacatalog.cookcountyil.gov/api/views/2p9n-m3mi

property e:2p9n-m3mi t:meta.view v:id=2p9n-m3mi v:category="Finance & Administration" v:averageRating=0 v:name="Board of Ethics -- 2011 Monthly  Board of Ethics Statistics" v:attribution="Cook County Board of Ethics"

property e:2p9n-m3mi t:meta.view.license v:name="Public Domain"

property e:2p9n-m3mi t:meta.view.owner v:id=8gct-yg9j v:screenName=HJF v:displayName=HJF

property e:2p9n-m3mi t:meta.view.tableauthor v:id=8gct-yg9j v:screenName=HJF v:displayName=HJF
```

## Top Records

```ls
| board_of_ethics_statistics        | dec | jan | feb | mar | apr | may | jun | jul | aug | sep | oct | nov | ytd_totals | 
| ================================= | === | === | === | === | === | === | === | === | === | === | === | === | ========== | 
| Training Seminars                 | 3   | 2   | 2   | 3   | 4   | 2   | 5   | 2   | 1   | 2   | -   | -   | 26         | 
| Employees Trained                 | 29  | 29  | 26  | 84  | 35  | 38  | 565 | 32  | 16  | 31  | -   | -   | 885        | 
| Inquiries (Pre-Bid Mtgs included) | 24  | 22  | 10  | 17  | 37  | 21  | 26  | 29  | 25  | 25  | -   | -   | 236        | 
| New Investigations Opened         | 6   | 1   | 0   | 0   | 0   | 0   | 2   | 0   | 0   | 0   | -   | -   | 9          | 
| Advisory Opinions Issued          | 1   | 1   | 2   | 0   | 0   | 2   | 1   | 6   | 6   | 1   | -   | -   | 20         | 
| Vendor Compliance Audit           | 20  | 10  | 23  | 79  | 109 | 78  | 79  | 45  | 103 | 22  | -   | -   | 568        | 
| Lobbyist Expense Audit            | 0   | 0   | 0   | 0   | 0   | 0   | 0   | 0   | 0   | 0   | -   | -   | 0          | 
| Political Contributions Audit     | 0   | 0   | 0   | 0   | 0   | 0   | 0   | 0   | 0   | 0   | -   | -   | 0          | 
```