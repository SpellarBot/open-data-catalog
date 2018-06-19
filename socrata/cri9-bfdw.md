# Oregon Offender Forecast Oct 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/oregon-offender-forecast-oct-2010-38e95) |
| Metadata | [Link](https://data.oregon.gov/api/views/cri9-bfdw) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/cri9-bfdw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/cri9-bfdw/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | cri9-bfdw |
| Name | Oregon Offender Forecast Oct 2010 |
| Attribution | Oregon Department of Administrative Services, Office of Economic Analysis |
| Category | Public Safety |
| Tags | prison, probation, parole, pps, post-prison, supervision, forecast, population |
| Created | 2010-11-24T19:04:02Z |
| Publication Date | 2011-04-17T00:03:09Z |

## Description

10 year Forecast for Oregon Offenders in Prison, Jail, Probation, and Post-Prison Supervision.

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type     | Render Type   |
| ======== | ============== | ============= | ============= | ============= | ============= |
| Yes      | time           | date          | Date          | calendar_date | calendar_date |
| Yes      | numeric metric | inmate        | Inmate        | number        | number        |
| Yes      | numeric metric | probation     | Probation     | number        | number        |
| Yes      | numeric metric | local_control | Local Control | number        | number        |
| Yes      | numeric metric | parole_pps    | Parole/PPS    | number        | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:cri9-bfdw d:2010-05-01T00:00:00.000Z m:local_control=690 m:parole_pps=13408 m:probation=18095

series e:cri9-bfdw d:2010-06-01T00:00:00.000Z m:local_control=695 m:parole_pps=13508 m:probation=18076

series e:cri9-bfdw d:2010-07-01T00:00:00.000Z m:local_control=695 m:parole_pps=13600 m:probation=18078
```

## Meta Commands

```ls
metric m:inmate p:integer l:Inmate t:dataTypeName=number

metric m:probation p:integer l:Probation t:dataTypeName=number

metric m:local_control p:integer l:"Local Control" t:dataTypeName=number

metric m:parole_pps p:integer l:Parole/PPS t:dataTypeName=number

entity e:cri9-bfdw l:"Oregon Offender Forecast Oct 2010" t:attribution="Oregon Department of Administrative Services, Office of Economic Analysis" t:url=https://data.oregon.gov/api/views/cri9-bfdw

property e:cri9-bfdw t:meta.view v:id=cri9-bfdw v:category="Public Safety" v:attributionLink=http://www.oregon.gov/DAS/OEA/corrections.shtml#Forecast_documents v:averageRating=0 v:name="Oregon Offender Forecast Oct 2010" v:attribution="Oregon Department of Administrative Services, Office of Economic Analysis"

property e:cri9-bfdw t:meta.view.owner v:id=4d25-jqaq v:screenName="Shawn  Miller" v:displayName="Shawn  Miller"

property e:cri9-bfdw t:meta.view.tableauthor v:id=4d25-jqaq v:screenName="Shawn  Miller" v:displayName="Shawn  Miller"
```

## Top Records

```ls
| date                | inmate | probation | local_control | parole_pps | 
| =================== | ====== | ========= | ============= | ========== | 
| 2010-05-01T00:00:00 |        | 18095     | 690           | 13408      | 
| 2010-06-01T00:00:00 |        | 18076     | 695           | 13508      | 
| 2010-07-01T00:00:00 |        | 18078     | 695           | 13600      | 
| 2010-08-01T00:00:00 |        | 18070     | 705           | 13663      | 
| 2010-09-01T00:00:00 |        | 18051     | 705           | 13708      | 
| 2010-10-01T00:00:00 | 14066  | 18062     | 705           | 13758      | 
| 2010-11-01T00:00:00 | 14056  | 18048     | 705           | 13797      | 
| 2010-12-01T00:00:00 | 14076  | 18065     | 705           | 13835      | 
| 2011-01-01T00:00:00 | 14120  | 18074     | 705           | 13880      | 
| 2011-02-01T00:00:00 | 14134  | 18042     | 705           | 13924      | 
```