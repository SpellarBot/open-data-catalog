# Missouri Weekly Feeder Cattle Weighted Average Report

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/missouri-weekly-feeder-cattle-weighted-average-report-cf638) |
| Metadata | [Link](https://data.mo.gov/api/views/4mcy-zagg) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/4mcy-zagg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/4mcy-zagg/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | 4mcy-zagg |
| Name | Missouri Weekly Feeder Cattle Weighted Average Report |
| Attribution | Missouri Department of Agriculture |
| Category | Agriculture |
| Tags | cattle, feeder, cattle prices, weighted average, market, farmer |
| Created | 2013-04-12T15:44:00Z |
| Publication Date | 2017-04-05T15:50:45Z |

## Description

Missouri Weekly Feeder Cattle Weighted Average Report

## Columns

```ls
| Included | Schema Type    | Field Name     | Name            | Data Type     | Render Type   |
| ======== | ============== | ============== | =============== | ============= | ============= |
| Yes      | time           | date           | Date            | calendar_date | calendar_date |
| Yes      | numeric metric | 500_600_steer  | 500-600# Steer  | money         | money         |
| Yes      | numeric metric | 500_600_heifer | 500-600# Heifer | money         | money         |
| Yes      | numeric metric | 700_800_steer  | 700-800# Steer  | money         | money         |
| Yes      | numeric metric | 700_800_heifer | 700-800# Heifer | money         | money         |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:4mcy-zagg d:2003-05-30T00:00:00.000Z m:700_800_heifer=76.03 m:700_800_steer=86.75 m:500_600_steer=97.58 m:500_600_heifer=86.17

series e:4mcy-zagg d:2003-06-06T00:00:00.000Z m:700_800_heifer=80.94 m:700_800_steer=86.59 m:500_600_steer=99.91 m:500_600_heifer=89.99

series e:4mcy-zagg d:2003-06-13T00:00:00.000Z m:700_800_heifer=80.31 m:700_800_steer=85.4 m:500_600_steer=99.48 m:500_600_heifer=89.77
```

## Meta Commands

```ls
metric m:500_600_steer p:double l:"500-600# Steer" t:dataTypeName=money

metric m:500_600_heifer p:double l:"500-600# Heifer" t:dataTypeName=money

metric m:700_800_steer p:double l:"700-800# Steer" t:dataTypeName=money

metric m:700_800_heifer p:double l:"700-800# Heifer" t:dataTypeName=money

entity e:4mcy-zagg l:"Missouri Weekly Feeder Cattle Weighted Average Report" t:attribution="Missouri Department of Agriculture" t:url=https://data.mo.gov/api/views/4mcy-zagg

property e:4mcy-zagg t:meta.view v:id=4mcy-zagg v:category=Agriculture v:attributionLink=http://mda.mo.gov/Market/ v:averageRating=0 v:name="Missouri Weekly Feeder Cattle Weighted Average Report" v:attribution="Missouri Department of Agriculture"

property e:4mcy-zagg t:meta.view.owner v:id=nye7-5sqq v:screenName=John v:displayName=John

property e:4mcy-zagg t:meta.view.tableauthor v:id=nye7-5sqq v:screenName=John v:displayName=John
```

## Top Records

```ls
| date                | 500_600_steer | 500_600_heifer | 700_800_steer | 700_800_heifer | 
| =================== | ============= | ============== | ============= | ============== | 
| 2003-05-30T00:00:00 | 97.58         | 86.17          | 86.75         | 76.03          | 
| 2003-06-06T00:00:00 | 99.91         | 89.99          | 86.59         | 80.94          | 
| 2003-06-13T00:00:00 | 99.48         | 89.77          | 85.40         | 80.31          | 
| 2003-06-20T00:00:00 | 97.80         | 89.16          | 84.11         | 81.82          | 
| 2003-06-27T00:00:00 | 97.56         | 89.01          | 86.06         | 82.32          | 
| 2003-07-07T00:00:00 | 99.50         | 92.00          | 91.08         | 88.36          | 
| 2003-07-11T00:00:00 | 100.25        | 90.87          | 89.09         | 85.72          | 
| 2003-07-18T00:00:00 | 101.24        | 91.06          | 89.91         | 85.27          | 
| 2003-07-25T00:00:00 | 103.77        | 93.13          | 94.84         | 89.13          | 
| 2003-08-01T00:00:00 | 103.34        | 94.64          | 92.05         | 87.20          | 
```