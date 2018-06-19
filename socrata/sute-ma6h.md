# Austin GO VIews From Different Browsers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/austin-go-views-from-different-browsers) |
| Metadata | [Link](https://data.austintexas.gov/api/views/sute-ma6h) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/sute-ma6h/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/sute-ma6h/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | sute-ma6h |
| Name | Austin GO VIews From Different Browsers |
| Category | Government |
| Tags | google analytics, browsers |
| Created | 2012-09-26T19:33:19Z |
| Publication Date | 2013-05-03T16:44:16Z |

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| No       | time           | :updated_at      | updated_at       | meta_data | meta_data   |
| Yes      | series tag     | browser          | Browser          | text      | text        |
| Yes      | numeric metric | unique_pageviews | Unique Pageviews | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:sute-ma6h d:2013-05-03T09:43:45.000Z t:browser="Internet Explorer" m:unique_pageviews=713710

series e:sute-ma6h d:2013-05-03T09:43:45.000Z t:browser=Safari m:unique_pageviews=440495

series e:sute-ma6h d:2013-05-03T09:43:45.000Z t:browser=Chrome m:unique_pageviews=399526
```

## Meta Commands

```ls
metric m:unique_pageviews p:integer l:"Unique Pageviews" t:dataTypeName=number

entity e:sute-ma6h l:"Austin GO VIews From Different Browsers" t:url=https://data.austintexas.gov/api/views/sute-ma6h

property e:sute-ma6h t:meta.view v:id=sute-ma6h v:category=Government v:averageRating=0 v:name="Austin GO VIews From Different Browsers"

property e:sute-ma6h t:meta.view.owner v:id=jkqa-55xv v:screenName="Divya Rathanlal" v:displayName="Divya Rathanlal"

property e:sute-ma6h t:meta.view.tableauthor v:id=jkqa-55xv v:screenName="Divya Rathanlal" v:roleName=publisher v:displayName="Divya Rathanlal"
```

## Top Records

```ls
| :updated_at | browser                  | unique_pageviews | 
| =========== | ======================== | ================ | 
| 1367574225  | Internet Explorer        | 713710           | 
| 1367574225  | Safari                   | 440495           | 
| 1367574225  | Chrome                   | 399526           | 
| 1367574225  | Firefox                  | 296024           | 
| 1367574225  | Android Browser          | 101670           | 
| 1367574225  | Safari (in-app)          | 23332            | 
| 1367574225  | IE with Chrome Frame     | 7792             | 
| 1367574225  | Amazon Silk              | 2840             | 
| 1367574225  | Opera                    | 2438             | 
| 1367574225  | Mozilla Compatible Agent | 1905             | 
```