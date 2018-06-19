# DCEO Small Business - ITC

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dceo-small-business-itc-d83eb) |
| Metadata | [Link](https://data.illinois.gov/api/views/7f5c-htkk) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/7f5c-htkk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/7f5c-htkk/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 7f5c-htkk |
| Name | DCEO Small Business - ITC |
| Category | Economics |
| Tags | small business |
| Created | 2012-01-27T20:38:07Z |
| Publication Date | 2012-01-27T20:39:02Z |

## Description

Calendar Year 2011

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| No       | time           | :updated_at        | updated_at         | meta_data | meta_data   |
| Yes      | series tag     | itc_activity       | ITC Activity       | text      | text        |
| Yes      | numeric metric | calendar_year_2011 | Calendar Year 2011 | money     | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:7f5c-htkk d:2012-01-27T12:38:15.000Z t:itc_activity="Total ITC Clients Advised:" m:calendar_year_2011=747

series e:7f5c-htkk d:2012-01-27T12:38:15.000Z t:itc_activity="Total ITC Consultation Hours:" m:calendar_year_2011=7711

series e:7f5c-htkk d:2012-01-27T12:38:15.000Z t:itc_activity="Average Hours Per Client:" m:calendar_year_2011=10.32
```

## Meta Commands

```ls
metric m:calendar_year_2011 p:long l:"Calendar Year 2011" t:dataTypeName=money

entity e:7f5c-htkk l:"DCEO Small Business - ITC" t:url=https://data.illinois.gov/api/views/7f5c-htkk

property e:7f5c-htkk t:meta.view v:id=7f5c-htkk v:category=Economics v:averageRating=0 v:name="DCEO Small Business - ITC"

property e:7f5c-htkk t:meta.view.owner v:id=t6h9-hze3 v:screenName=Nicole v:displayName=Nicole

property e:7f5c-htkk t:meta.view.tableauthor v:id=t6h9-hze3 v:screenName=Nicole v:roleName=publisher v:displayName=Nicole
```

## Top Records

```ls
| :updated_at | itc_activity                    | calendar_year_2011 | 
| =========== | =============================== | ================== | 
| 1327667895  | Total ITC Clients Advised:      | 747                | 
| 1327667895  | Total ITC Consultation Hours:   | 7,711              | 
| 1327667895  | Average Hours Per Client:       | 10.32              | 
| 1327667895  | ITC Clients Trained:            | 1,106              | 
| 1327667895  | Total Minority Clients Advised: | 112                | 
| 1327667895  | Women Clients Advised:          | 119                | 
| 1327667895  | ITC Jobs Created                | 201                | 
| 1327667895  | ITC Jobs Retained               | 1,288              | 
| 1327667895  | ITC $ Value of Export Sales:    | $410,766,101       | 
```