# Credited Job Placement Report

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/odra-job-place-trends-59b3d) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/afsf-hz68) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/afsf-hz68/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/afsf-hz68/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | afsf-hz68 |
| Name | Credited Job Placement Report |
| Attribution | Human Resources Administration (HRA) |
| Category | Social Services |
| Tags | odra job place trends, hra, human resources |
| Created | 2013-05-21T11:56:51Z |
| Publication Date | 2016-05-18T21:42:31Z |

## Description

Statistics on monthly job placement trends.

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type | Render Type |
| ======== | ============== | ====================== | ====================== | ========= | =========== |
| No       |                | year                   | Year                   | number    | number      |
| No       |                | month                  | Month                  | number    | number      |
| Yes      | numeric metric | total_self_reported    | Total Self reported    | number    | number      |
| Yes      | numeric metric | new_hires              | New Hires              | number    | number      |
| Yes      | numeric metric | total_job_placements   | Total job placements   | number    | number      |
| Yes      | numeric metric | monthly_percent_change | Monthly Percent Change | percent   | percent     |
| Yes      | numeric metric | yearly_percent_change  | Yearly Percent Change  | percent   | percent     |
```

## Time Field

```ls
Value = year-month
Format & Zone = yyyy-MM
```

## Series Fields

```ls
Excluded Fields = year,month
```

## Data Commands

```ls
series e:afsf-hz68 d:1995-01-01T00:00:00.000Z m:yearly_percent_change=22.3 m:total_self_reported=2208 m:monthly_percent_change=-1.2

series e:afsf-hz68 d:1995-02-01T00:00:00.000Z m:yearly_percent_change=26 m:total_self_reported=1913 m:monthly_percent_change=-13.4

series e:afsf-hz68 d:1995-03-01T00:00:00.000Z m:yearly_percent_change=25 m:total_self_reported=3109 m:monthly_percent_change=62.5
```

## Meta Commands

```ls
metric m:total_self_reported p:integer l:"Total Self reported" t:dataTypeName=number

metric m:new_hires p:integer l:"New Hires" t:dataTypeName=number

metric m:total_job_placements p:integer l:"Total job placements" t:dataTypeName=number

metric m:monthly_percent_change p:float l:"Monthly Percent Change" t:dataTypeName=percent

metric m:yearly_percent_change p:float l:"Yearly Percent Change" t:dataTypeName=percent

entity e:afsf-hz68 l:"Credited Job Placement Report" t:attribution="Human Resources Administration (HRA)" t:url=https://data.cityofnewyork.us/api/views/afsf-hz68

property e:afsf-hz68 t:meta.view v:id=afsf-hz68 v:category="Social Services" v:averageRating=0 v:name="Credited Job Placement Report" v:attribution="Human Resources Administration (HRA)"

property e:afsf-hz68 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:afsf-hz68 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| year | month | total_self_reported | new_hires | total_job_placements | monthly_percent_change | yearly_percent_change | 
| ==== | ===== | =================== | ========= | ==================== | ====================== | ===================== | 
| 1995 | 1     | 2208                |           |                      | -1.20                  | 22.30                 | 
| 1995 | 2     | 1913                |           |                      | -13.40                 | 26.00                 | 
| 1995 | 3     | 3109                |           |                      | 62.50                  | 25.00                 | 
| 1995 | 4     | 1443                |           |                      | -53.60                 | -31.90                | 
| 1995 | 5     | 3303                |           |                      | 128.90                 | 130.80                | 
| 1995 | 6     | 2462                |           |                      | -25.50                 | 85.10                 | 
| 1995 | 7     | 2013                |           |                      | -18.20                 | 26.00                 | 
| 1995 | 8     | 4114                |           |                      | 104.40                 | 81.40                 | 
| 1995 | 9     | 4081                |           |                      | -0.80                  | 150.50                | 
| 1995 | 10    | 2420                |           |                      | -40.70                 | 29.30                 | 
```