# Biennial Funding By Source -- 8-22-2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/funding-by-source-all-12312014) |
| Metadata | [Link](https://data.wa.gov/api/views/82pq-rj7m) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/82pq-rj7m/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/82pq-rj7m/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | 82pq-rj7m |
| Name | Biennial Funding By Source -- 8-22-2016 |
| Tags | state-of-the-salmon |
| Created | 2014-11-11T20:00:24Z |
| Publication Date | 2016-09-12T22:19:33Z |

## Description

Showing biennial tally of State, Federal and Local salmon recovery funding sources administered through the WA State Recreation and Conservation Office.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type | Render Type |
| ======== | ============== | =========== | =========== | ========= | =========== |
| Yes      | series tag     | year        | Year        | text      | text        |
| Yes      | numeric metric | state       | State       | money     | money       |
| Yes      | numeric metric | federal     | Federal     | money     | money       |
| Yes      | numeric metric | local_match | Local Match | money     | money       |
| Yes      | numeric metric | total       | Total       | money     | money       |
```

## Time Field

```ls
Value = 2016
Format & Zone = yyyy
```

## Data Commands

```ls
series e:82pq-rj7m d:2016-01-01T00:00:00.000Z t:year=1997-1999 m:total=42508979 m:local_match=12659846 m:federal=12306518 m:state=17542616

series e:82pq-rj7m d:2016-01-01T00:00:00.000Z t:year=1999-2001 m:total=143476580 m:local_match=46041265 m:federal=27804140 m:state=69631175

series e:82pq-rj7m d:2016-01-01T00:00:00.000Z t:year=2001-2003 m:total=87714256 m:local_match=12376607 m:federal=23125500 m:state=52212149
```

## Meta Commands

```ls
metric m:state p:integer l:State t:dataTypeName=money

metric m:federal p:integer l:Federal t:dataTypeName=money

metric m:local_match p:integer l:"Local Match" t:dataTypeName=money

metric m:total p:integer l:Total t:dataTypeName=money

entity e:82pq-rj7m l:"Biennial Funding By Source -- 8-22-2016" t:url=https://data.wa.gov/api/views/82pq-rj7m

property e:82pq-rj7m t:meta.view v:id=82pq-rj7m v:averageRating=0 v:name="Biennial Funding By Source -- 8-22-2016"

property e:82pq-rj7m t:meta.view.owner v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:displayName="Jennifer Johnson"

property e:82pq-rj7m t:meta.view.tableauthor v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:roleName=publisher v:displayName="Jennifer Johnson"
```

## Top Records

```ls
| year      | state    | federal   | local_match | total     | 
| ========= | ======== | ========= | =========== | ========= | 
| 1997-1999 | 17542616 | 12306518  | 12659846    | 42508979  | 
| 1999-2001 | 69631175 | 27804140  | 46041265    | 143476580 | 
| 2001-2003 | 52212149 | 23125500  | 12376607    | 87714256  | 
| 2003-2005 | 47502093 | 29432394  | 30595465    | 107529951 | 
| 2005-2007 | 47418286 | 64166852  | 53502643    | 165087782 | 
| 2007-2009 | 53103579 | 74811123  | 50249552    | 178164254 | 
| 2009-2011 | 64084228 | 51130761  | 33281067    | 148496056 | 
| 2011-2013 | 54624428 | 70176216  | 23918429    | 148719072 | 
| 2013-2015 | 43492463 | 123476874 | 33425604    | 200394941 | 
| 2015-2017 | 0        | 0         | 0           | 0         | 
```