# DCEO Small Business - NOC

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dceo-small-business-noc-f0d55) |
| Metadata | [Link](https://data.illinois.gov/api/views/trfn-893d) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/trfn-893d/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/trfn-893d/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | trfn-893d |
| Name | DCEO Small Business - NOC |
| Category | Economics |
| Tags | small business |
| Created | 2012-01-27T20:42:58Z |
| Publication Date | 2012-01-27T20:44:01Z |

## Description

Calendar Year 2011

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| No       | time           | :updated_at        | updated_at         | meta_data | meta_data   |
| Yes      | series tag     | noc_activity       | NOC Activity       | text      | text        |
| Yes      | numeric metric | calendar_year_2011 | Calendar Year 2011 | money     | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:trfn-893d d:2012-01-27T12:43:04.000Z t:noc_activity="Total NOC Clients Advised:" m:calendar_year_2011=115

series e:trfn-893d d:2012-01-27T12:43:04.000Z t:noc_activity="Total NOC Consultation Hours:" m:calendar_year_2011=2503

series e:trfn-893d d:2012-01-27T12:43:04.000Z t:noc_activity="Average Hours Per Client:" m:calendar_year_2011=21.77
```

## Meta Commands

```ls
metric m:calendar_year_2011 p:long l:"Calendar Year 2011" t:dataTypeName=money

entity e:trfn-893d l:"DCEO Small Business - NOC" t:url=https://data.illinois.gov/api/views/trfn-893d

property e:trfn-893d t:meta.view v:id=trfn-893d v:category=Economics v:averageRating=0 v:name="DCEO Small Business - NOC"

property e:trfn-893d t:meta.view.owner v:id=t6h9-hze3 v:screenName=Nicole v:displayName=Nicole

property e:trfn-893d t:meta.view.tableauthor v:id=t6h9-hze3 v:screenName=Nicole v:roleName=publisher v:displayName=Nicole
```

## Top Records

```ls
| :updated_at | noc_activity                  | calendar_year_2011 | 
| =========== | ============================= | ================== | 
| 1327668184  | Total NOC Clients Advised:    | 115                | 
| 1327668184  | Total NOC Consultation Hours: | 2,503              | 
| 1327668184  | Average Hours Per Client:     | 21.77              | 
| 1327668184  | NOC Clients Trained:          | 214                | 
| 1327668184  | Minority Clients Advised:     | 10                 | 
| 1327668184  | Women Clients Advised:        | 16                 | 
| 1327668184  | NOC Jobs Created              | 27                 | 
| 1327668184  | NOC Jobs Retained             | 51                 | 
| 1327668184  | NOC $ Value of Export Sales:  | $25,794,399        | 
```