# 311 Cases by Channel

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/311-cases-by-channel-ed786) |
| Metadata | [Link](https://data.sfgov.org/api/views/jz25-nkm4) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/jz25-nkm4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/jz25-nkm4/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | jz25-nkm4 |
| Name | 311 Cases by Channel |
| Category | City Infrastructure |
| Created | 2014-09-18T23:55:25Z |
| Publication Date | 2017-03-01T20:04:31Z |

## Description

These are the service requests created by 311, categorized by the channel on which they were submitted. 311 offers customers 4 channels to submit service requests: by calling 311, using the SF311 Mobile App, visiting our website, or messaging us through Twitter. This dataset is updated on a monthly basis.

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type     | Render Type   |
| ======== | ============== | =============== | =============== | ============= | ============= |
| Yes      | time           | month           | Month           | calendar_date | calendar_date |
| Yes      | numeric metric | mobile          | Mobile          | number        | number        |
| Yes      | numeric metric | web             | Web             | number        | number        |
| Yes      | series tag     | phone           | Phone           | text          | number        |
| Yes      | numeric metric | twitter         | Twitter         | number        | number        |
| Yes      | numeric metric | summry_of_cases | Summry of Cases | number        | number        |
```

## Time Field

```ls
Value = month
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:jz25-nkm4 d:2016-09-01T00:00:00.000Z t:phone=20820 m:twitter=244 m:summry_of_cases=51033 m:web=10297 m:mobile=19672

series e:jz25-nkm4 d:2016-08-01T00:00:00.000Z t:phone=20658 m:twitter=193 m:summry_of_cases=54379 m:web=11774 m:mobile=21754

series e:jz25-nkm4 d:2016-07-01T00:00:00.000Z t:phone=18749 m:twitter=165 m:summry_of_cases=46029 m:web=10490 m:mobile=16625
```

## Meta Commands

```ls
metric m:mobile p:integer l:Mobile t:dataTypeName=number

metric m:web p:integer l:Web t:dataTypeName=number

metric m:twitter p:integer l:Twitter t:dataTypeName=number

metric m:summry_of_cases p:integer l:"Summry of Cases" t:dataTypeName=number

entity e:jz25-nkm4 l:"311 Cases by Channel" t:url=https://data.sfgov.org/api/views/jz25-nkm4

property e:jz25-nkm4 t:meta.view v:id=jz25-nkm4 v:category="City Infrastructure" v:averageRating=0 v:name="311 Cases by Channel"

property e:jz25-nkm4 t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:jz25-nkm4 t:meta.view.owner v:id=di52-4dbf v:screenName="Mike Choi" v:displayName="Mike Choi"

property e:jz25-nkm4 t:meta.view.tableauthor v:id=di52-4dbf v:screenName="Mike Choi" v:displayName="Mike Choi"
```

## Top Records

```ls
| month               | mobile | web   | phone | twitter | summry_of_cases | 
| =================== | ====== | ===== | ===== | ======= | =============== | 
| 2016-09-01T00:00:00 | 19672  | 10297 | 20820 | 244     | 51033           | 
| 2016-08-01T00:00:00 | 21754  | 11774 | 20658 | 193     | 54379           | 
| 2016-07-01T00:00:00 | 16625  | 10490 | 18749 | 165     | 46029           | 
| 2016-06-01T00:00:00 | 18408  | 12145 | 19877 | 222     | 50652           | 
| 2016-05-01T00:00:00 | 19869  | 13447 | 19186 | 207     | 52709           | 
| 2016-04-01T00:00:00 | 17403  | 10088 | 18257 | 161     | 45909           | 
| 2016-03-01T00:00:00 | 17073  | 9654  | 19804 | 179     | 46710           | 
| 2016-02-01T00:00:00 | 17186  | 9580  | 17288 | 151     | 44205           | 
| 2016-01-01T00:00:00 | 17200  | 9527  | 19072 | 144     | 45943           | 
| 2015-12-01T00:00:00 | 12343  | 8582  | 18373 | 87      | 39385           | 
```