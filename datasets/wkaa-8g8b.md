# DOC Annual Statistics

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/doc-annual-statistics-37501) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/wkaa-8g8b) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/wkaa-8g8b/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/wkaa-8g8b/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | wkaa-8g8b |
| Name | DOC Annual Statistics |
| Attribution | Department of Correction (DOC) |
| Category | City Government |
| Tags | department of correction, doc, arrests, inmates, visitor, stabbing, slashing |
| Created | 2013-03-06T14:28:21Z |
| Publication Date | 2013-06-21T20:06:57Z |

## Description

This table contains the statistical record of the Inmate Population. This record is updated annually

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type | Render Type |
| ======== | ============== | ==================== | ==================== | ========= | =========== |
| No       | time           | :updated_at          | updated_at           | meta_data | meta_data   |
| Yes      | series tag     | fiscal_year          | Fiscal Year          | text      | text        |
| Yes      | series tag     | statistic_type_name  | Statistic Type Name  | text      | text        |
| Yes      | numeric metric | statistic_type_count | Statistic Type Count | number    | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:wkaa-8g8b d:2013-03-06T06:28:22.000Z t:statistic_type_name="Average Daily Inmate Population" t:fiscal_year="FY 2012" m:statistic_type_count=12287

series e:wkaa-8g8b d:2013-03-06T06:28:22.000Z t:statistic_type_name="Average Daily Inmate Population" t:fiscal_year="FY 2011" m:statistic_type_count=12789

series e:wkaa-8g8b d:2013-03-06T06:28:22.000Z t:statistic_type_name="Average Daily Inmate Population" t:fiscal_year="FY 2010" m:statistic_type_count=13049
```

## Meta Commands

```ls
metric m:statistic_type_count p:long l:"Statistic Type Count" t:dataTypeName=number

entity e:wkaa-8g8b l:"DOC Annual Statistics" t:attribution="Department of Correction (DOC)" t:url=https://data.cityofnewyork.us/api/views/wkaa-8g8b

property e:wkaa-8g8b t:meta.view v:id=wkaa-8g8b v:category="City Government" v:attributionLink=http://www.nyc.gov/html/doc/html/stats/doc_stats.shtml v:averageRating=0 v:name="DOC Annual Statistics" v:attribution="Department of Correction (DOC)"

property e:wkaa-8g8b t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:wkaa-8g8b t:meta.view.tableauthor v:id=iacr-duv5 v:screenName=Tejas.Patel v:displayName=Tejas.Patel
```

## Top Records

```ls
| :updated_at | fiscal_year | statistic_type_name             | statistic_type_count | 
| =========== | =========== | =============================== | ==================== | 
| 1362551302  | FY 2012     | Average Daily Inmate Population | 12,287               | 
| 1362551302  | FY 2011     | Average Daily Inmate Population | 12,789               | 
| 1362551302  | FY 2010     | Average Daily Inmate Population | 13,049               | 
| 1362551302  | FY 2009     | Average Daily Inmate Population | 13,362               | 
| 1362551302  | FY 2008     | Average Daily Inmate Population | 13,850               | 
| 1362551302  | FY 2007     | Average Daily Inmate Population | 13,987               | 
| 1362551302  | FY 2006     | Average Daily Inmate Population | 13,497               | 
| 1362551302  | FY 2005     | Average Daily Inmate Population | 13,576               | 
| 1362551302  | FY 2004     | Average Daily Inmate Population | 13,751               | 
| 1362551302  | FY 2003     | Average Daily Inmate Population | 14,533               | 
```