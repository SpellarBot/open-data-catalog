# AustinGO Keyword Search

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/austingo-keyword-search) |
| Metadata | [Link](https://data.austintexas.gov/api/views/sswp-u5uh) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/sswp-u5uh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/sswp-u5uh/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | sswp-u5uh |
| Name | AustinGO Keyword Search |
| Category | Government |
| Tags | google analytics, keywords, statistics |
| Created | 2012-09-26T19:49:46Z |
| Publication Date | 2013-05-03T16:30:35Z |

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| No       | time           | :updated_at      | updated_at       | meta_data | meta_data   |
| Yes      | series tag     | keyword          | Keyword          | text      | text        |
| Yes      | numeric metric | unique_pageviews | Unique Pageviews | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:sswp-u5uh d:2013-05-03T09:30:17.000Z t:keyword="austin public library" m:unique_pageviews=28950

series e:sswp-u5uh d:2013-05-03T09:30:17.000Z t:keyword="city of austin" m:unique_pageviews=19183

series e:sswp-u5uh d:2013-05-03T09:30:17.000Z t:keyword="austin police department" m:unique_pageviews=16989
```

## Meta Commands

```ls
metric m:unique_pageviews p:integer l:"Unique Pageviews" t:dataTypeName=number

entity e:sswp-u5uh l:"AustinGO Keyword Search" t:url=https://data.austintexas.gov/api/views/sswp-u5uh

property e:sswp-u5uh t:meta.view v:id=sswp-u5uh v:category=Government v:averageRating=0 v:name="AustinGO Keyword Search"

property e:sswp-u5uh t:meta.view.owner v:id=jkqa-55xv v:screenName="Divya Rathanlal" v:displayName="Divya Rathanlal"

property e:sswp-u5uh t:meta.view.tableauthor v:id=jkqa-55xv v:screenName="Divya Rathanlal" v:roleName=publisher v:displayName="Divya Rathanlal"
```

## Top Records

```ls
| :updated_at | keyword                  | unique_pageviews | 
| =========== | ======================== | ================ | 
| 1367573417  | austin public library    | 28950            | 
| 1367573417  | city of austin           | 19183            | 
| 1367573417  | austin police department | 16989            | 
| 1367573417  | austin fire department   | 13944            | 
| 1367573417  | austin animal shelter    | 8791             | 
| 1367573417  | austin library           | 6726             | 
| 1367573417  | austin texas             | 5816             | 
| 1367573417  | city of austin jobs      | 4289             | 
| 1367573417  | austin animal center     | 3960             | 
| 1367573417  | barton springs pool      | 3271             | 
```