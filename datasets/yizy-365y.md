# NYCHA Applicant Income Limits

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nycha-applicant-income-limits-68351) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/yizy-365y) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/yizy-365y/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/yizy-365y/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | yizy-365y |
| Name | NYCHA Applicant Income Limits |
| Attribution | New York City Housing Authority (NYCHA) |
| Category | Social Services |
| Tags | nycha, nyc housing, public housing, application, subsidized housing |
| Created | 2013-03-28T19:11:14Z |
| Publication Date | 2013-03-29T15:24:19Z |

## Description

Income limits by household size for public housing

## Columns

```ls
| Included | Schema Type    | Field Name       | Name                      | Data Type | Render Type |
| ======== | ============== | ================ | ========================= | ========= | =========== |
| Yes      | time           | year             | Year                      | number    | text        |
| Yes      | numeric metric | password         | Person(s) in Family       | number    | text        |
| Yes      | numeric metric | confirm_password | Gross Family Income Limit | money     | text        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:yizy-365y d:2013-01-01T00:00:00.000Z m:confirm_password=48100 m:password=1

series e:yizy-365y d:2013-01-01T00:00:00.000Z m:confirm_password=55000 m:password=2

series e:yizy-365y d:2013-01-01T00:00:00.000Z m:confirm_password=61850 m:password=3
```

## Meta Commands

```ls
metric m:password p:integer l:"Person(s) in Family" d:"# of person(s) in family" t:dataTypeName=number

metric m:confirm_password p:long l:"Gross Family Income Limit" d:"The gross income limit for the family" t:dataTypeName=money

entity e:yizy-365y l:"NYCHA Applicant Income Limits" t:attribution="New York City Housing Authority (NYCHA)" t:url=https://data.cityofnewyork.us/api/views/yizy-365y

property e:yizy-365y t:meta.view v:id=yizy-365y v:category="Social Services" v:attributionLink=http://www.nyc.gov/html/nycha/html/assistance/income.shtml v:averageRating=0 v:name="NYCHA Applicant Income Limits" v:attribution="New York City Housing Authority (NYCHA)"

property e:yizy-365y t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:yizy-365y t:meta.view.tableauthor v:id=8b43-zkvh v:screenName="Ram S." v:displayName="Ram S."
```

## Top Records

```ls
| year | password | confirm_password | 
| ==== | ======== | ================ | 
| 2013 | 1        | $48,100          | 
| 2013 | 2        | $55,000          | 
| 2013 | 3        | $61,850          | 
| 2013 | 4        | $68,700          | 
| 2013 | 5        | $74,200          | 
| 2013 | 6        | $79,700          | 
| 2013 | 7        | $85,200          | 
| 2013 | 8        | $90,700          | 
| 2013 | 9        | $96,200          | 
| 2013 | 10       | $101,700         | 
```