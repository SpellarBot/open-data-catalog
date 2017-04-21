# DBEDT Hawaii's Clean Economy Job Growth

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dbedt-hawaiis-clean-economy-job-growth-6c189) |
| Metadata | [Link](https://data.hawaii.gov/api/views/d3e2-v3mh) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/d3e2-v3mh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/d3e2-v3mh/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | d3e2-v3mh |
| Name | DBEDT Hawaii's Clean Economy Job Growth |
| Attribution | Department of Economic Development and Tourism |
| Category | Economic Development |
| Tags | clean, job |
| Created | 2012-08-28T20:28:30Z |
| Publication Date | 2012-08-29T01:33:37Z |

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| No       | time           | :updated_at       | updated_at        | meta_data | meta_data   |
| Yes      | numeric metric | x_values          | X Values          | number    | number      |
| Yes      | numeric metric | u_s_job_growth    | U.S. Job Growth   | number    | number      |
| Yes      | numeric metric | hawaii_job_growth | Hawaii Job Growth | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:d3e2-v3mh d:2012-08-28T13:28:31.000Z m:hawaii_job_growth=100 m:u_s_job_growth=100 m:x_values=2003

series e:d3e2-v3mh d:2012-08-28T13:28:31.000Z m:hawaii_job_growth=106 m:u_s_job_growth=104 m:x_values=2004

series e:d3e2-v3mh d:2012-08-28T13:28:31.000Z m:hawaii_job_growth=110 m:u_s_job_growth=109 m:x_values=2005
```

## Meta Commands

```ls
metric m:x_values p:integer l:"X Values" t:dataTypeName=number

metric m:u_s_job_growth p:integer l:"U.S. Job Growth" t:dataTypeName=number

metric m:hawaii_job_growth p:integer l:"Hawaii Job Growth" t:dataTypeName=number

entity e:d3e2-v3mh l:"DBEDT Hawaii's Clean Economy Job Growth" t:attribution="Department of Economic Development and Tourism" t:url=https://data.hawaii.gov/api/views/d3e2-v3mh

property e:d3e2-v3mh t:meta.view v:id=d3e2-v3mh v:category="Economic Development" v:attributionLink=http://hawaii.gov/dbedt v:averageRating=0 v:name="DBEDT Hawaii's Clean Economy Job Growth" v:attribution="Department of Economic Development and Tourism"

property e:d3e2-v3mh t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:d3e2-v3mh t:meta.view.owner v:id=uaqq-pakk v:screenName="Douglas Oshiro" v:displayName="Douglas Oshiro"

property e:d3e2-v3mh t:meta.view.tableauthor v:id=uaqq-pakk v:screenName="Douglas Oshiro" v:displayName="Douglas Oshiro"
```

## Top Records

```ls
| :updated_at | x_values | u_s_job_growth | hawaii_job_growth | 
| =========== | ======== | ============== | ================= | 
| 1346160511  | 2003     | 100            | 100               | 
| 1346160511  | 2004     | 104            | 106               | 
| 1346160511  | 2005     | 109            | 110               | 
| 1346160511  | 2006     | 112            | 118               | 
| 1346160511  | 2007     | 115            | 124               | 
| 1346160511  | 2008     | 117            | 127               | 
| 1346160511  | 2009     | 126            | 155               | 
| 1346160511  | 2010     | 127            | 156               | 
```