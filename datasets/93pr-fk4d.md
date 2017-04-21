# DCEO Small Business - PTAC

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dceo-small-business-ptac-a30de) |
| Metadata | [Link](https://data.illinois.gov/api/views/93pr-fk4d) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/93pr-fk4d/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/93pr-fk4d/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 93pr-fk4d |
| Name | DCEO Small Business - PTAC |
| Category | Economics |
| Tags | small business |
| Created | 2012-01-27T20:32:02Z |
| Publication Date | 2012-01-27T20:34:02Z |

## Description

Calendar Year 2011

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| No       | time           | :updated_at        | updated_at         | meta_data | meta_data   |
| Yes      | series tag     | ptac_activity      | PTAC Activity      | text      | text        |
| Yes      | numeric metric | calendar_year_2011 | Calendar Year 2011 | money     | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:93pr-fk4d d:2012-01-27T12:32:10.000Z t:ptac_activity="Total PTAC Clients Advised:" m:calendar_year_2011=1617

series e:93pr-fk4d d:2012-01-27T12:32:10.000Z t:ptac_activity="Total PTAC Consultation Hours:" m:calendar_year_2011=9157

series e:93pr-fk4d d:2012-01-27T12:32:10.000Z t:ptac_activity="Average Hours Per Client:" m:calendar_year_2011=5.66
```

## Meta Commands

```ls
metric m:calendar_year_2011 p:long l:"Calendar Year 2011" t:dataTypeName=money

entity e:93pr-fk4d l:"DCEO Small Business - PTAC" t:url=https://data.illinois.gov/api/views/93pr-fk4d

property e:93pr-fk4d t:meta.view v:id=93pr-fk4d v:category=Economics v:averageRating=0 v:name="DCEO Small Business - PTAC"

property e:93pr-fk4d t:meta.view.owner v:id=t6h9-hze3 v:screenName=Nicole v:displayName=Nicole

property e:93pr-fk4d t:meta.view.tableauthor v:id=t6h9-hze3 v:screenName=Nicole v:roleName=publisher v:displayName=Nicole
```

## Top Records

```ls
| :updated_at | ptac_activity                       | calendar_year_2011 | 
| =========== | =================================== | ================== | 
| 1327667530  | Total PTAC Clients Advised:         | 1,617              | 
| 1327667530  | Total PTAC Consultation Hours:      | 9,157              | 
| 1327667530  | Average Hours Per Client:           | 5.66               | 
| 1327667530  | Initial PTAC Advising Sesssions     | 571                | 
| 1327667530  | Total PTAC Advising Sessions        | 5,177              | 
| 1327667530  | Minority Business Advising Sessions | 1,900              | 
| 1327667530  | Women Business Advising Sessions    | 2,012              | 
| 1327667530  | Total PTAC Clients Trained:         | 3,965              | 
| 1327667530  | PTAC Jobs Created:                  | 1,566              | 
| 1327667530  | PTAC Jobs Retained:                 | 3,582              | 
```