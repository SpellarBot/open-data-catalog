# DCEO Small Business - TIES

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dceo-small-business-ties-bfa7f) |
| Metadata | [Link](https://data.illinois.gov/api/views/q7de-ahfk) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/q7de-ahfk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/q7de-ahfk/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | q7de-ahfk |
| Name | DCEO Small Business - TIES |
| Category | Economics |
| Tags | small business |
| Created | 2012-01-27T20:35:13Z |
| Publication Date | 2012-01-27T20:36:20Z |

## Description

Calendar Year 2011

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| No       | time           | :updated_at        | updated_at         | meta_data | meta_data   |
| Yes      | series tag     | ties_activity      | TIES Activity      | text      | text        |
| Yes      | numeric metric | calendar_year_2011 | Calendar Year 2011 | money     | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:q7de-ahfk d:2012-01-27T12:35:17.000Z t:ties_activity="Total TIES Clients Advised:" m:calendar_year_2011=174

series e:q7de-ahfk d:2012-01-27T12:35:17.000Z t:ties_activity="Total TIES Consultation Hours:" m:calendar_year_2011=2285

series e:q7de-ahfk d:2012-01-27T12:35:17.000Z t:ties_activity="Average Hours Per Client:" m:calendar_year_2011=13.13
```

## Meta Commands

```ls
metric m:calendar_year_2011 p:long l:"Calendar Year 2011" t:dataTypeName=money

entity e:q7de-ahfk l:"DCEO Small Business - TIES" t:url=https://data.illinois.gov/api/views/q7de-ahfk

property e:q7de-ahfk t:meta.view v:id=q7de-ahfk v:category=Economics v:averageRating=0 v:name="DCEO Small Business - TIES"

property e:q7de-ahfk t:meta.view.owner v:id=t6h9-hze3 v:screenName=Nicole v:displayName=Nicole

property e:q7de-ahfk t:meta.view.tableauthor v:id=t6h9-hze3 v:screenName=Nicole v:roleName=publisher v:displayName=Nicole
```

## Top Records

```ls
| :updated_at | ties_activity                  | calendar_year_2011 | 
| =========== | ============================== | ================== | 
| 1327667717  | Total TIES Clients Advised:    | 174                | 
| 1327667717  | Total TIES Consultation Hours: | 2,285              | 
| 1327667717  | Average Hours Per Client:      | 13.13              | 
| 1327667717  | TIES Training Attendees:       | 139                | 
| 1327667717  | TIES Jobs Created:             | 14                 | 
| 1327667717  | TIES Jobs Retained             | 102                | 
| 1327667717  | TIES Debt Financing #:         | 3                  | 
| 1327667717  | TIES Debt Financing $:         | $517,700           | 
| 1327667717  | TIES Non Debt Financing #:     | 8                  | 
| 1327667717  | TIES Non Debt Financing $:     | $4,612,200         | 
```