# Number of employments employed by QHTBs, by employment status

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/number-of-employments-employed-by-qhtbs-by-employment-status) |
| Metadata | [Link](https://data.hawaii.gov/api/views/n3gs-fh9z) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/n3gs-fh9z/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/n3gs-fh9z/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | n3gs-fh9z |
| Name | Number of employments employed by QHTBs, by employment status |
| Created | 2015-02-26T05:06:30Z |
| Publication Date | 2016-02-04T01:30:21Z |

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type     | Render Type   |
| ======== | ============== | ================== | ================== | ============= | ============= |
| Yes      | time           | effective_date     | Effective Date     | calendar_date | calendar_date |
| Yes      | series tag     | industry           | Industry           | text          | text          |
| Yes      | numeric metric | total_employees    | Total Employees    | number        | number        |
| No       |                | full_time          | Full Time          | number        | number        |
| No       |                | part_time          | Part Time          | number        | number        |
| Yes      | numeric metric | temporary_seasonal | Temporary/Seasonal | number        | number        |
```

## Time Field

```ls
Value = effective_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = full_time,part_time
```

## Data Commands

```ls
series e:n3gs-fh9z d:2013-12-12T00:00:00.000Z t:industry="All Areas" m:total_employees=338 m:temporary_seasonal=23

series e:n3gs-fh9z d:2013-12-12T00:00:00.000Z t:industry="In Research Activities" m:total_employees=261 m:temporary_seasonal=14

series e:n3gs-fh9z d:2014-12-31T00:00:00.000Z t:industry="All Area" m:total_employees=297 m:temporary_seasonal=21
```

## Meta Commands

```ls
metric m:total_employees p:integer l:"Total Employees" t:dataTypeName=number

metric m:temporary_seasonal p:integer l:Temporary/Seasonal t:dataTypeName=number

entity e:n3gs-fh9z l:"Number of employments employed by QHTBs, by employment status" t:url=https://data.hawaii.gov/api/views/n3gs-fh9z

property e:n3gs-fh9z t:meta.view v:id=n3gs-fh9z v:averageRating=0 v:name="Number of employments employed by QHTBs, by employment status"

property e:n3gs-fh9z t:meta.view.owner v:id=wktp-67q4 v:screenName=karen v:displayName=karen

property e:n3gs-fh9z t:meta.view.tableauthor v:id=wktp-67q4 v:screenName=karen v:roleName=administrator v:displayName=karen
```

## Top Records

```ls
| effective_date      | industry               | total_employees | full_time | part_time | temporary_seasonal | 
| =================== | ====================== | =============== | ========= | ========= | ================== | 
| 2013-12-12T00:00:00 | All Areas              | 338             | 280       | 35        | 23                 | 
| 2013-12-12T00:00:00 | In Research Activities | 261             | 222       | 25        | 14                 | 
| 2014-12-31T00:00:00 | All Area               | 297             | 258       | 39        | 21                 | 
| 2014-12-31T00:00:00 | In Research Activities | 233             | 206       | 27        | 21                 | 
```