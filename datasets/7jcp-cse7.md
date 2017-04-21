# JOBCOUNT - STATE OF HAWAII - Monthly - Total Jobcount - Seasonally Adjusted

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/jobcount-state-of-hawaii-monthly-total-jobcount-seasonally-adjusted-6e936) |
| Metadata | [Link](https://data.hawaii.gov/api/views/7jcp-cse7) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/7jcp-cse7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/7jcp-cse7/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | 7jcp-cse7 |
| Name | JOBCOUNT - STATE OF HAWAII - Monthly - Total Jobcount - Seasonally Adjusted |
| Attribution | DLIR R&S |
| Category | Employment |
| Tags | jobs, jobcount, job count, state, hawaii, monthly |
| Created | 2013-10-17T01:53:36Z |
| Publication Date | 2014-05-13T20:50:56Z |

## Columns

```ls
| Included | Schema Type    | Field Name | Name       | Data Type     | Render Type   |
| ======== | ============== | ========== | ========== | ============= | ============= |
| Yes      | time           | month_year | Month/Year | calendar_date | calendar_date |
| Yes      | numeric metric | total      | Total      | number        | number        |
```

## Time Field

```ls
Value = month_year
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:7jcp-cse7 d:1990-01-01T00:00:00.000Z m:total=516900

series e:7jcp-cse7 d:1990-02-01T00:00:00.000Z m:total=521000

series e:7jcp-cse7 d:1990-03-01T00:00:00.000Z m:total=522300
```

## Meta Commands

```ls
metric m:total p:integer l:Total t:dataTypeName=number

entity e:7jcp-cse7 l:"JOBCOUNT - STATE OF HAWAII - Monthly - Total Jobcount - Seasonally Adjusted" t:attribution="DLIR R&S" t:url=https://data.hawaii.gov/api/views/7jcp-cse7

property e:7jcp-cse7 t:meta.view v:id=7jcp-cse7 v:category=Employment v:averageRating=0 v:name="JOBCOUNT - STATE OF HAWAII - Monthly - Total Jobcount - Seasonally Adjusted" v:attribution="DLIR R&S"

property e:7jcp-cse7 t:meta.view.owner v:id=5ibs-8u6a v:profileImageUrlMedium=/api/users/5ibs-8u6a/profile_images/THUMB v:profileImageUrlLarge=/api/users/5ibs-8u6a/profile_images/LARGE v:screenName=Bill v:profileImageUrlSmall=/api/users/5ibs-8u6a/profile_images/TINY v:displayName=Bill

property e:7jcp-cse7 t:meta.view.tableauthor v:id=5ibs-8u6a v:profileImageUrlMedium=/api/users/5ibs-8u6a/profile_images/THUMB v:profileImageUrlLarge=/api/users/5ibs-8u6a/profile_images/LARGE v:screenName=Bill v:profileImageUrlSmall=/api/users/5ibs-8u6a/profile_images/TINY v:roleName=editor v:displayName=Bill
```

## Top Records

```ls
| month_year          | total  | 
| =================== | ====== | 
| 1990-01-01T00:00:00 | 516900 | 
| 1990-02-01T00:00:00 | 521000 | 
| 1990-03-01T00:00:00 | 522300 | 
| 1990-04-01T00:00:00 | 526000 | 
| 1990-05-01T00:00:00 | 527200 | 
| 1990-06-01T00:00:00 | 528200 | 
| 1990-07-01T00:00:00 | 529600 | 
| 1990-08-01T00:00:00 | 530200 | 
| 1990-09-01T00:00:00 | 530600 | 
| 1990-10-01T00:00:00 | 535000 | 
```