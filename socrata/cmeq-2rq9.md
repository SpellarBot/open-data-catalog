# ECY BIBI 2009 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ecy-bibi-2009-2014) |
| Metadata | [Link](https://data.wa.gov/api/views/cmeq-2rq9) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/cmeq-2rq9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/cmeq-2rq9/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | cmeq-2rq9 |
| Name | ECY BIBI 2009 2014 |
| Category | Natural Resources & Environment |
| Tags | habitat quality, state of salmon in watersheds 2016 |
| Created | 2016-12-11T20:43:28Z |
| Publication Date | 2016-12-11T20:45:45Z |

## Description

X BIBI ? This is the average (n= 1 or 2) of B-IBI scores at the site, for the round of sampling. The Benthic Index of Biotic Integrity (B-IBI) values, were retrieved on 7/13/2016 from the Puget Sound Stream Benthos web page: http://www.pugetsoundstreambenthos.org/. Values are based on genus-species level of taxonomic resolution.

## Columns

```ls
| Included | Schema Type    | Field Name | Name    | Data Type     | Render Type   |
| ======== | ============== | ========== | ======= | ============= | ============= |
| Yes      | series tag     | region     | Region  | text          | text          |
| Yes      | series tag     | round      | Round   | text          | text          |
| Yes      | time           | year       | Year    | calendar_date | calendar_date |
| Yes      | series tag     | rating     | Rating  | text          | text          |
| Yes      | numeric metric | percent    | Percent | number        | number        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:cmeq-2rq9 d:2010-01-01T00:00:00.000Z t:region="WA Coast" t:round="Round 1" t:rating=Poor m:percent=34

series e:cmeq-2rq9 d:2010-01-01T00:00:00.000Z t:region="WA Coast" t:round="Round 1" t:rating=Fair m:percent=31.9

series e:cmeq-2rq9 d:2010-01-01T00:00:00.000Z t:region="WA Coast" t:round="Round 1" t:rating=Good m:percent=34
```

## Meta Commands

```ls
metric m:percent p:float l:Percent t:dataTypeName=number

entity e:cmeq-2rq9 l:"ECY BIBI 2009 2014" t:url=https://data.wa.gov/api/views/cmeq-2rq9

property e:cmeq-2rq9 t:meta.view v:id=cmeq-2rq9 v:category="Natural Resources & Environment" v:averageRating=0 v:name="ECY BIBI 2009 2014"

property e:cmeq-2rq9 t:meta.view.license v:name="Public Domain"

property e:cmeq-2rq9 t:meta.view.owner v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:displayName="Jennifer Johnson"

property e:cmeq-2rq9 t:meta.view.tableauthor v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:roleName=publisher v:displayName="Jennifer Johnson"
```

## Top Records

```ls
| region      | round   | year                | rating | percent | 
| =========== | ======= | =================== | ====== | ======= | 
| WA Coast    | Round 1 | 2010-01-01T00:00:00 | Poor   | 34      | 
| WA Coast    | Round 1 | 2010-01-01T00:00:00 | Fair   | 31.9    | 
| WA Coast    | Round 1 | 2010-01-01T00:00:00 | Good   | 34      | 
| WA Coast    | Round 2 | 2014-01-01T00:00:00 | Poor   | 31.3    | 
| WA Coast    | Round 2 | 2014-01-01T00:00:00 | Fair   | 22.9    | 
| WA Coast    | Round 2 | 2014-01-01T00:00:00 | Good   | 45.8    | 
| Puget Sound | Round 1 | 2009-01-01T00:00:00 | Poor   | 41.3    | 
| Puget Sound | Round 1 | 2009-01-01T00:00:00 | Fair   | 26.1    | 
| Puget Sound | Round 1 | 2009-01-01T00:00:00 | Good   | 32.6    | 
| Puget Sound | Round 2 | 2013-01-01T00:00:00 | Poor   | 38.3    | 
```