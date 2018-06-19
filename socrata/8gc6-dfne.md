# Grant Information Collection Act - 2nd Quarter 2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/grant-information-collection-act-2nd-quarter-2015) |
| Metadata | [Link](https://data.illinois.gov/api/views/8gc6-dfne) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/8gc6-dfne/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/8gc6-dfne/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 8gc6-dfne |
| Name | Grant Information Collection Act - 2nd Quarter 2015 |
| Attribution | George Tarasuk, Illinois Arts Council Agency |
| Tags | iaca, illinois, arts, council, agency, grant, 2015, second quarter |
| Created | 2015-07-13T18:35:58Z |
| Publication Date | 2015-07-13T18:39:49Z |

## Description

Grant Information Collection Act - 2nd Quarter 2015

## Columns

```ls
| Included | Schema Type    | Field Name | Name   | Data Type     | Render Type   |
| ======== | ============== | ========== | ====== | ============= | ============= |
| No       |                | fy         | FY     | number        | number        |
| Yes      | series tag     | flname     | FLName | text          | text          |
| Yes      | series tag     | title      | Title  | text          | text          |
| Yes      | numeric metric | grant      | Grant  | money         | money         |
| Yes      | time           | dvo        | Dvo    | calendar_date | calendar_date |
| No       |                | beg        | Beg    | calendar_date | calendar_date |
| No       |                | end        | End    | calendar_date | calendar_date |
```

## Time Field

```ls
Value = dvo
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = fy,beg,end
```

## Data Commands

```ls
series e:8gc6-dfne d:2015-06-08T00:00:00.000Z t:title="for an IAS Artist Project grant" t:flname="Kent B Lambert" m:grant=3000

series e:8gc6-dfne d:2015-04-08T00:00:00.000Z t:title="for an IAS Professional Development grant" t:flname="Cosima Aryee" m:grant=1000

series e:8gc6-dfne d:2015-04-30T00:00:00.000Z t:title="for Public Radio & Television Operating Grant" t:flname="WIUM-FM Western Illinois University" m:grant=4250
```

## Meta Commands

```ls
metric m:grant p:integer l:Grant t:dataTypeName=money

entity e:8gc6-dfne l:"Grant Information Collection Act - 2nd Quarter 2015" t:attribution="George Tarasuk, Illinois Arts Council Agency" t:url=https://data.illinois.gov/api/views/8gc6-dfne

property e:8gc6-dfne t:meta.view v:id=8gc6-dfne v:averageRating=0 v:name="Grant Information Collection Act - 2nd Quarter 2015" v:attribution="George Tarasuk, Illinois Arts Council Agency"

property e:8gc6-dfne t:meta.view.license v:name="Public Domain"

property e:8gc6-dfne t:meta.view.owner v:id=5ugp-negb v:screenName="George Tarasuk" v:displayName="George Tarasuk"

property e:8gc6-dfne t:meta.view.tableauthor v:id=5ugp-negb v:screenName="George Tarasuk" v:displayName="George Tarasuk"
```

## Top Records

```ls
| fy | flname                              | title                                         | grant  | dvo                 | beg                 | end                 | 
| == | =================================== | ============================================= | ====== | =================== | =================== | =================== | 
| 15 | Kent B Lambert                      | for an IAS Artist Project grant               | 3000   | 2015-06-08T00:00:00 | 2015-06-02T00:00:00 | 2015-09-30T00:00:00 | 
| 15 | Cosima Aryee                        | for an IAS Professional Development grant     | 1000   | 2015-04-08T00:00:00 | 2015-02-02T00:00:00 | 2015-02-28T00:00:00 | 
| 15 | WIUM-FM Western Illinois University | for Public Radio & Television Operating Grant | 4250   | 2015-04-30T00:00:00 | 2015-04-21T00:00:00 | 2015-08-31T00:00:00 | 
| 15 | Mendelssohn Club                    | for a performance by Quintet Attacca          | 1375   | 2015-04-03T00:00:00 | 2015-04-09T00:00:00 | 2015-04-30T00:00:00 | 
| 15 | Redmoon Theater                     | for a Youth Employment in the Arts project    | 5940   | 2015-05-05T00:00:00 | 2015-06-01T00:00:00 | 2015-08-31T00:00:00 | 
| 15 | WTTW Communications Inc             | for Public Radio & Television Operating Grant | 220150 | 2015-04-30T00:00:00 | 2015-04-17T00:00:00 | 2015-08-31T00:00:00 | 
| 15 | Springfield Area Arts Council       | for a Youth Employment in the Arts project    | 2000   | 2015-05-05T00:00:00 | 2015-06-01T00:00:00 | 2015-08-31T00:00:00 | 
| 15 | Fine Line Creative Arts Center      | for a Youth Employment in the Arts project    | 1980   | 2015-05-05T00:00:00 | 2015-06-01T00:00:00 | 2015-08-31T00:00:00 | 
| 15 | Asian Improv Arts Midwest           | for a Youth Employment in the Arts project    | 1500   | 2015-06-08T00:00:00 | 2015-06-01T00:00:00 | 2015-08-31T00:00:00 | 
| 15 | Elevarte Community Studio           | for a Youth Employment in the Arts project    | 5940   | 2015-05-05T00:00:00 | 2015-06-01T00:00:00 | 2015-08-31T00:00:00 | 
```