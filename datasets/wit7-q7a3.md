# DCEO Small Business - Day Care

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dceo-small-business-day-care-fecca) |
| Metadata | [Link](https://data.illinois.gov/api/views/wit7-q7a3) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/wit7-q7a3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/wit7-q7a3/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | wit7-q7a3 |
| Name | DCEO Small Business - Day Care |
| Category | Economics |
| Tags | small business |
| Created | 2012-01-27T20:39:59Z |
| Publication Date | 2012-01-27T20:41:36Z |

## Description

Calendar Year 2011

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| No       | time           | :updated_at        | updated_at         | meta_data | meta_data   |
| Yes      | series tag     | day_care_activity  | Day Care Activity  | text      | text        |
| Yes      | numeric metric | calendar_year_2011 | Calendar Year 2011 | number    | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:wit7-q7a3 d:2012-01-27T12:40:08.000Z t:day_care_activity="Total Day Care Clients Advised" m:calendar_year_2011=66

series e:wit7-q7a3 d:2012-01-27T12:40:08.000Z t:day_care_activity="Total Day Care Consultation Hours" m:calendar_year_2011=251

series e:wit7-q7a3 d:2012-01-27T12:40:08.000Z t:day_care_activity="Average Hours Per Client:" m:calendar_year_2011=3.8
```

## Meta Commands

```ls
metric m:calendar_year_2011 p:integer l:"Calendar Year 2011" t:dataTypeName=number

entity e:wit7-q7a3 l:"DCEO Small Business - Day Care" t:url=https://data.illinois.gov/api/views/wit7-q7a3

property e:wit7-q7a3 t:meta.view v:id=wit7-q7a3 v:category=Economics v:averageRating=0 v:name="DCEO Small Business - Day Care"

property e:wit7-q7a3 t:meta.view.owner v:id=t6h9-hze3 v:screenName=Nicole v:displayName=Nicole

property e:wit7-q7a3 t:meta.view.tableauthor v:id=t6h9-hze3 v:screenName=Nicole v:roleName=publisher v:displayName=Nicole
```

## Top Records

```ls
| :updated_at | day_care_activity                 | calendar_year_2011 | 
| =========== | ================================= | ================== | 
| 1327668008  | Total Day Care Clients Advised    | 66                 | 
| 1327668008  | Total Day Care Consultation Hours | 251                | 
| 1327668008  | Average Hours Per Client:         | 3.80               | 
| 1327668008  | Day Care Clients Trained          | 72                 | 
| 1327668008  | Total Minority Clients Advised    | 56                 | 
| 1327668008  | Total Women Clients Advised       | 37                 | 
```