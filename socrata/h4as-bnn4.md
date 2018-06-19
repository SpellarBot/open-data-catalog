# Analytics Austin GO Mobile Views

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/analytics-austin-go-mobile-views) |
| Metadata | [Link](https://data.austintexas.gov/api/views/h4as-bnn4) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/h4as-bnn4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/h4as-bnn4/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | h4as-bnn4 |
| Name | Analytics Austin GO Mobile Views |
| Category | Government |
| Tags | google analytics, statistics, mobile views |
| Created | 2012-09-26T17:38:38Z |
| Publication Date | 2013-05-03T16:34:02Z |

## Description

Mobile Views of AustinGO Site

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| No       | time           | :updated_at      | updated_at       | meta_data | meta_data   |
| Yes      | series tag     | mobile           | Mobile           | text      | text        |
| Yes      | numeric metric | unique_pageviews | Unique Pageviews | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:h4as-bnn4 d:2013-05-03T09:33:39.000Z t:mobile=No m:unique_pageviews=1578282

series e:h4as-bnn4 d:2013-05-03T09:33:39.000Z t:mobile=Yes m:unique_pageviews=414351
```

## Meta Commands

```ls
metric m:unique_pageviews p:integer l:"Unique Pageviews" t:dataTypeName=number

entity e:h4as-bnn4 l:"Analytics Austin GO Mobile Views" t:url=https://data.austintexas.gov/api/views/h4as-bnn4

property e:h4as-bnn4 t:meta.view v:id=h4as-bnn4 v:category=Government v:averageRating=0 v:name="Analytics Austin GO Mobile Views"

property e:h4as-bnn4 t:meta.view.owner v:id=jkqa-55xv v:screenName="Divya Rathanlal" v:displayName="Divya Rathanlal"

property e:h4as-bnn4 t:meta.view.tableauthor v:id=jkqa-55xv v:screenName="Divya Rathanlal" v:roleName=publisher v:displayName="Divya Rathanlal"
```

## Top Records

```ls
| :updated_at | mobile | unique_pageviews | 
| =========== | ====== | ================ | 
| 1367573619  | No     | 1578282          | 
| 1367573619  | Yes    | 414351           | 
```