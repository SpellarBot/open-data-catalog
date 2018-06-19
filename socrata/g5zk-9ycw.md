# Public Health Statistics - General fertility rates in Chicago, by year, 1999-2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/public-health-statistics-general-fertility-rates-in-chicago-by-year-1999-2009-70014) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/g5zk-9ycw) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/g5zk-9ycw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/g5zk-9ycw/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | g5zk-9ycw |
| Name | Public Health Statistics - General fertility rates in Chicago, by year, 1999-2009 |
| Attribution | Illinois Department of Public Health |
| Category | Health & Human Services |
| Created | 2011-12-28T19:58:48Z |
| Publication Date | 2012-10-05T19:21:02Z |

## Description

This dataset contains the annual general fertility rate (births per 1,000 females aged 15-44 years) with corresponding 95% confidence intervals, by Chicago community area, for the years 1999 ? 2009. See the full dataset description for more information: https://data.cityofchicago.org/api/assets/58E0620E-DF5C-4EE6-AD06-6588164ADCD4

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                         | Data Type | Render Type |
| ======== | ============== | ============================ | ============================ | ========= | =========== |
| Yes      | series tag     | community_area_number        | Community Area Number        | text      | number      |
| Yes      | series tag     | community_area_name          | Community Area Name          | text      | text        |
| Yes      | numeric metric | fertility_rate_1999          | Fertility Rate 1999          | number    | number      |
| Yes      | numeric metric | fertility_rate_1999_lower_ci | Fertility Rate 1999 Lower CI | number    | number      |
| Yes      | numeric metric | fertility_rate_1999_upper_ci | Fertility Rate 1999 Upper CI | number    | number      |
| Yes      | numeric metric | fertility_rate_2000          | Fertility Rate 2000          | number    | number      |
| Yes      | numeric metric | fertility_rate_2000_lower_ci | Fertility Rate 2000 Lower CI | number    | number      |
| Yes      | numeric metric | fertility_rate_2000_upper_ci | Fertility Rate 2000 Upper CI | number    | number      |
| Yes      | numeric metric | fertility_rate_2001          | Fertility Rate 2001          | number    | number      |
| Yes      | numeric metric | fertility_rate_2001_lower_ci | Fertility Rate 2001 Lower CI | number    | number      |
| Yes      | numeric metric | fertility_rate_2001_upper_ci | Fertility Rate 2001 Upper CI | number    | number      |
| Yes      | numeric metric | fertility_rate_2002          | Fertility Rate 2002          | number    | number      |
| Yes      | numeric metric | fertility_rate_2002_lower_ci | Fertility Rate 2002 Lower CI | number    | number      |
| Yes      | numeric metric | fertility_rate_2002_upper_ci | Fertility Rate 2002 Upper CI | number    | number      |
| Yes      | numeric metric | fertility_rate_2003          | Fertility Rate 2003          | number    | number      |
| Yes      | numeric metric | fertility_rate_2003_lower_ci | Fertility Rate 2003 Lower CI | number    | number      |
| Yes      | numeric metric | fertility_rate_2003_upper_ci | Fertility Rate 2003 Upper CI | number    | number      |
| Yes      | numeric metric | fertility_rate_2004          | Fertility Rate 2004          | number    | number      |
| Yes      | numeric metric | fertility_rate_2004_lower_ci | Fertility Rate 2004 Lower CI | number    | number      |
| Yes      | numeric metric | fertility_rate_2004_upper_ci | Fertility Rate 2004 Upper CI | number    | number      |
| Yes      | numeric metric | fertility_rate_2005          | Fertility Rate 2005          | number    | number      |
| Yes      | numeric metric | fertility_rate_2005_lower_ci | Fertility Rate 2005 Lower CI | number    | number      |
| Yes      | numeric metric | fertility_rate_2005_upper_ci | Fertility Rate 2005 Upper CI | number    | number      |
| Yes      | numeric metric | fertility_rate_2006          | Fertility Rate 2006          | number    | number      |
| Yes      | numeric metric | fertility_rate_2006_lower_ci | Fertility Rate 2006 Lower CI | number    | number      |
| Yes      | numeric metric | fertility_rate_2006_upper_ci | Fertility Rate 2006 Upper CI | number    | number      |
| Yes      | numeric metric | fertility_rate_2007          | Fertility Rate 2007          | number    | number      |
| Yes      | numeric metric | fertility_rate_2007_lower_ci | Fertility Rate 2007 Lower CI | number    | number      |
| Yes      | numeric metric | fertility_rate_2007_upper_ci | Fertility Rate 2007 Upper CI | number    | number      |
| Yes      | numeric metric | fertility_rate_2008          | Fertility Rate 2008          | number    | number      |
| Yes      | numeric metric | fertility_rate_2008_lower_ci | Fertility Rate 2008 Lower CI | number    | number      |
| Yes      | numeric metric | fertility_rate_2008_upper_ci | Fertility Rate 2008 Upper CI | number    | number      |
| Yes      | numeric metric | fertility_rate_2009          | Fertility Rate 2009          | number    | number      |
| Yes      | numeric metric | fertility_rate_2009_lower_ci | Fertility Rate 2009 Lower CI | number    | number      |
| Yes      | numeric metric | fertility_rate_2009_upper_ci | Fertility Rate 2009 Upper CI | number    | number      |
```

## Time Field

```ls
Value = 1999
Format & Zone = yyyy
```

## Data Commands

```ls
series e:g5zk-9ycw d:1999-01-01T00:00:00.000Z t:community_area_name="Rogers Park" t:community_area_number=1 m:fertility_rate_2002_lower_ci=62.9 m:fertility_rate_2009_upper_ci=66 m:fertility_rate_2000_upper_ci=78.8 m:fertility_rate_2004_lower_ci=54.2 m:fertility_rate_2001_upper_ci=75 m:fertility_rate_2008=59.3 m:fertility_rate_1999_upper_ci=76.8 m:fertility_rate_2009=62 m:fertility_rate_2005=56.6 m:fertility_rate_2004=57.9 m:fertility_rate_2007=59.7 m:fertility_rate_2006=60.2 m:fertility_rate_1999=72.7 m:fertility_rate_2001=71 m:fertility_rate_2000=74.7 m:fertility_rate_2003=63.1 m:fertility_rate_2002=66.8 m:fertility_rate_2005_lower_ci=52.9 m:fertility_rate_2009_lower_ci=58 m:fertility_rate_2005_upper_ci=60.3 m:fertility_rate_2000_lower_ci=70.6 m:fertility_rate_2007_upper_ci=63.6 m:fertility_rate_2006_lower_ci=56.3 m:fertility_rate_2008_upper_ci=63.2 m:fertility_rate_2003_lower_ci=59.2 m:fertility_rate_2003_upper_ci=67 m:fertility_rate_2004_upper_ci=61.6 m:fertility_rate_2001_lower_ci=67 m:fertility_rate_2002_upper_ci=70.7 m:fertility_rate_2006_upper_ci=64.1 m:fertility_rate_2008_lower_ci=55.4 m:fertility_rate_2007_lower_ci=55.8 m:fertility_rate_1999_lower_ci=68.6

series e:g5zk-9ycw d:1999-01-01T00:00:00.000Z t:community_area_name="West Ridge" t:community_area_number=2 m:fertility_rate_2002_lower_ci=80.3 m:fertility_rate_2009_upper_ci=87.9 m:fertility_rate_2000_upper_ci=85.2 m:fertility_rate_2004_lower_ci=77.1 m:fertility_rate_2001_upper_ci=82.5 m:fertility_rate_2008=81.8 m:fertility_rate_1999_upper_ci=82.6 m:fertility_rate_2009=83.3 m:fertility_rate_2005=76.5 m:fertility_rate_2004=81.6 m:fertility_rate_2007=83.4 m:fertility_rate_2006=77.1 m:fertility_rate_1999=78.2 m:fertility_rate_2001=78.1 m:fertility_rate_2000=80.8 m:fertility_rate_2003=80.8 m:fertility_rate_2002=84.9 m:fertility_rate_2005_lower_ci=72.1 m:fertility_rate_2009_lower_ci=78.7 m:fertility_rate_2005_upper_ci=80.9 m:fertility_rate_2000_lower_ci=76.4 m:fertility_rate_2007_upper_ci=88 m:fertility_rate_2006_lower_ci=72.7 m:fertility_rate_2008_upper_ci=86.4 m:fertility_rate_2003_lower_ci=76.3 m:fertility_rate_2003_upper_ci=85.3 m:fertility_rate_2004_upper_ci=86.1 m:fertility_rate_2001_lower_ci=73.7 m:fertility_rate_2002_upper_ci=89.5 m:fertility_rate_2006_upper_ci=81.5 m:fertility_rate_2008_lower_ci=77.2 m:fertility_rate_2007_lower_ci=78.8 m:fertility_rate_1999_lower_ci=73.8

series e:g5zk-9ycw d:1999-01-01T00:00:00.000Z t:community_area_name=Uptown t:community_area_number=3 m:fertility_rate_2002_lower_ci=47.9 m:fertility_rate_2009_upper_ci=54.1 m:fertility_rate_2000_upper_ci=60 m:fertility_rate_2004_lower_ci=45.6 m:fertility_rate_2001_upper_ci=59.8 m:fertility_rate_2008=49.3 m:fertility_rate_1999_upper_ci=57.6 m:fertility_rate_2009=50.5 m:fertility_rate_2005=52.5 m:fertility_rate_2004=49.1 m:fertility_rate_2007=51.4 m:fertility_rate_2006=53.8 m:fertility_rate_1999=54 m:fertility_rate_2001=56.1 m:fertility_rate_2000=56.3 m:fertility_rate_2003=50.4 m:fertility_rate_2002=51.5 m:fertility_rate_2005_lower_ci=48.9 m:fertility_rate_2009_lower_ci=46.9 m:fertility_rate_2005_upper_ci=56.1 m:fertility_rate_2000_lower_ci=52.6 m:fertility_rate_2007_upper_ci=55 m:fertility_rate_2006_lower_ci=50.1 m:fertility_rate_2008_upper_ci=52.9 m:fertility_rate_2003_lower_ci=46.8 m:fertility_rate_2003_upper_ci=54 m:fertility_rate_2004_upper_ci=52.6 m:fertility_rate_2001_lower_ci=52.4 m:fertility_rate_2002_upper_ci=55.1 m:fertility_rate_2006_upper_ci=57.5 m:fertility_rate_2008_lower_ci=45.7 m:fertility_rate_2007_lower_ci=47.8 m:fertility_rate_1999_lower_ci=50.4
```

## Meta Commands

```ls
metric m:fertility_rate_1999 p:float l:"Fertility Rate 1999" d:"Rate of live births per 1000 females aged 15-44 years in 1999" t:dataTypeName=number

metric m:fertility_rate_1999_lower_ci p:double l:"Fertility Rate 1999 Lower CI" d:"Fertility rate lower confidence interval (CI)" t:dataTypeName=number

metric m:fertility_rate_1999_upper_ci p:double l:"Fertility Rate 1999 Upper CI" d:"Fertility rate upper confidence interval (CI)" t:dataTypeName=number

metric m:fertility_rate_2000 p:float l:"Fertility Rate 2000" d:"Rate of live births per 1000 females aged 15-44 years in 2000" t:dataTypeName=number

metric m:fertility_rate_2000_lower_ci p:float l:"Fertility Rate 2000 Lower CI" d:"Fertility rate lower confidence interval (CI)" t:dataTypeName=number

metric m:fertility_rate_2000_upper_ci p:double l:"Fertility Rate 2000 Upper CI" d:"Fertility rate upper confidence interval (CI)" t:dataTypeName=number

metric m:fertility_rate_2001 p:float l:"Fertility Rate 2001" d:"Rate of live births per 1000 females aged 15-44 years in 2001" t:dataTypeName=number

metric m:fertility_rate_2001_lower_ci p:float l:"Fertility Rate 2001 Lower CI" d:"Fertility rate lower confidence interval (CI)" t:dataTypeName=number

metric m:fertility_rate_2001_upper_ci p:float l:"Fertility Rate 2001 Upper CI" d:"Fertility rate upper confidence interval (CI)" t:dataTypeName=number

metric m:fertility_rate_2002 p:float l:"Fertility Rate 2002" d:"Rate of live births per 1000 females aged 15-44 years in 2002" t:dataTypeName=number

metric m:fertility_rate_2002_lower_ci p:float l:"Fertility Rate 2002 Lower CI" d:"Fertility rate lower confidence interval (CI)" t:dataTypeName=number

metric m:fertility_rate_2002_upper_ci p:float l:"Fertility Rate 2002 Upper CI" d:"Fertility rate upper confidence interval (CI)" t:dataTypeName=number

metric m:fertility_rate_2003 p:float l:"Fertility Rate 2003" d:"Rate of live births per 1000 females aged 15-44 years in 2003" t:dataTypeName=number

metric m:fertility_rate_2003_lower_ci p:float l:"Fertility Rate 2003 Lower CI" d:"Fertility rate lower confidence interval (CI)" t:dataTypeName=number

metric m:fertility_rate_2003_upper_ci p:float l:"Fertility Rate 2003 Upper CI" d:"Fertility rate upper confidence interval (CI)" t:dataTypeName=number

metric m:fertility_rate_2004 p:float l:"Fertility Rate 2004" d:"Rate of live births per 1000 females aged 15-44 years in 2004" t:dataTypeName=number

metric m:fertility_rate_2004_lower_ci p:float l:"Fertility Rate 2004 Lower CI" d:"Fertility rate lower confidence interval(CI)" t:dataTypeName=number

metric m:fertility_rate_2004_upper_ci p:double l:"Fertility Rate 2004 Upper CI" d:"Fertility rate upper confidence interval (CI)" t:dataTypeName=number

metric m:fertility_rate_2005 p:double l:"Fertility Rate 2005" d:"Rate of live births per 1000 females aged 15-44 years in 2005" t:dataTypeName=number

metric m:fertility_rate_2005_lower_ci p:float l:"Fertility Rate 2005 Lower CI" d:"Fertility rate lower confidence interval (CI)" t:dataTypeName=number

metric m:fertility_rate_2005_upper_ci p:float l:"Fertility Rate 2005 Upper CI" d:"Fertility rate upper confidence interval (CI)" t:dataTypeName=number

metric m:fertility_rate_2006 p:double l:"Fertility Rate 2006" d:"Rate of live births per 1000 females aged 15-44 years in 2006" t:dataTypeName=number

metric m:fertility_rate_2006_lower_ci p:float l:"Fertility Rate 2006 Lower CI" d:"Fertility rate lower confidence interval (CI)" t:dataTypeName=number

metric m:fertility_rate_2006_upper_ci p:float l:"Fertility Rate 2006 Upper CI" d:"Fertility rate upper confidence interval (CI)" t:dataTypeName=number

metric m:fertility_rate_2007 p:float l:"Fertility Rate 2007" d:"Rate of live births per 1000 females aged 15-44 years in 2007" t:dataTypeName=number

metric m:fertility_rate_2007_lower_ci p:float l:"Fertility Rate 2007 Lower CI" d:"Fertility rate lower confidence interval (CI)" t:dataTypeName=number

metric m:fertility_rate_2007_upper_ci p:float l:"Fertility Rate 2007 Upper CI" d:"Fertility rate upper confidence interval (CI)" t:dataTypeName=number

metric m:fertility_rate_2008 p:float l:"Fertility Rate 2008" d:"Rate of live births per 1000 females aged 15-44 years in 2008" t:dataTypeName=number

metric m:fertility_rate_2008_lower_ci p:float l:"Fertility Rate 2008 Lower CI" d:"Fertility rate lower confidence interval (CI)" t:dataTypeName=number

metric m:fertility_rate_2008_upper_ci p:float l:"Fertility Rate 2008 Upper CI" d:"Fertility rate upper confidence interval" t:dataTypeName=number

metric m:fertility_rate_2009 p:float l:"Fertility Rate 2009" d:"Rate of live births per 1000 females aged 15-44 years in 2009" t:dataTypeName=number

metric m:fertility_rate_2009_lower_ci p:float l:"Fertility Rate 2009 Lower CI" d:"Fertility rate lower confidence interval (CI)" t:dataTypeName=number

metric m:fertility_rate_2009_upper_ci p:float l:"Fertility Rate 2009 Upper CI" d:"Fertility rate upper confidence interval" t:dataTypeName=number

entity e:g5zk-9ycw l:"Public Health Statistics - General fertility rates in Chicago, by year, 1999-2009" t:attribution="Illinois Department of Public Health" t:url=https://data.cityofchicago.org/api/views/g5zk-9ycw

property e:g5zk-9ycw t:meta.view v:id=g5zk-9ycw v:category="Health & Human Services" v:averageRating=0 v:name="Public Health Statistics - General fertility rates in Chicago, by year, 1999-2009" v:attribution="Illinois Department of Public Health"

property e:g5zk-9ycw t:meta.view.owner v:id=is6y-5c5n v:screenName=Jamyia v:displayName=Jamyia

property e:g5zk-9ycw t:meta.view.tableauthor v:id=is6y-5c5n v:screenName=Jamyia v:displayName=Jamyia
```

## Top Records

```ls
| community_area_number | community_area_name | fertility_rate_1999 | fertility_rate_1999_lower_ci | fertility_rate_1999_upper_ci | fertility_rate_2000 | fertility_rate_2000_lower_ci | fertility_rate_2000_upper_ci | fertility_rate_2001 | fertility_rate_2001_lower_ci | fertility_rate_2001_upper_ci | fertility_rate_2002 | fertility_rate_2002_lower_ci | fertility_rate_2002_upper_ci | fertility_rate_2003 | fertility_rate_2003_lower_ci | fertility_rate_2003_upper_ci | fertility_rate_2004 | fertility_rate_2004_lower_ci | fertility_rate_2004_upper_ci | fertility_rate_2005 | fertility_rate_2005_lower_ci | fertility_rate_2005_upper_ci | fertility_rate_2006 | fertility_rate_2006_lower_ci | fertility_rate_2006_upper_ci | fertility_rate_2007 | fertility_rate_2007_lower_ci | fertility_rate_2007_upper_ci | fertility_rate_2008 | fertility_rate_2008_lower_ci | fertility_rate_2008_upper_ci | fertility_rate_2009 | fertility_rate_2009_lower_ci | fertility_rate_2009_upper_ci | 
| ===================== | =================== | =================== | ============================ | ============================ | =================== | ============================ | ============================ | =================== | ============================ | ============================ | =================== | ============================ | ============================ | =================== | ============================ | ============================ | =================== | ============================ | ============================ | =================== | ============================ | ============================ | =================== | ============================ | ============================ | =================== | ============================ | ============================ | =================== | ============================ | ============================ | =================== | ============================ | ============================ | 
| 1                     | Rogers Park         | 72.7                | 68.6                         | 76.8                         | 74.7                | 70.6                         | 78.8                         | 71                  | 67                           | 75                           | 66.8                | 62.9                         | 70.7                         | 63.1                | 59.2                         | 67                           | 57.9                | 54.2                         | 61.6                         | 56.6                | 52.9                         | 60.3                         | 60.2                | 56.3                         | 64.1                         | 59.7                | 55.8                         | 63.6                         | 59.3                | 55.4                         | 63.2                         | 62                  | 58                           | 66                           | 
| 2                     | West Ridge          | 78.2                | 73.8                         | 82.6                         | 80.8                | 76.4                         | 85.2                         | 78.1                | 73.7                         | 82.5                         | 84.9                | 80.3                         | 89.5                         | 80.8                | 76.3                         | 85.3                         | 81.6                | 77.1                         | 86.1                         | 76.5                | 72.1                         | 80.9                         | 77.1                | 72.7                         | 81.5                         | 83.4                | 78.8                         | 88                           | 81.8                | 77.2                         | 86.4                         | 83.3                | 78.7                         | 87.9                         | 
| 3                     | Uptown              | 54                  | 50.4                         | 57.6                         | 56.3                | 52.6                         | 60                           | 56.1                | 52.4                         | 59.8                         | 51.5                | 47.9                         | 55.1                         | 50.4                | 46.8                         | 54                           | 49.1                | 45.6                         | 52.6                         | 52.5                | 48.9                         | 56.1                         | 53.8                | 50.1                         | 57.5                         | 51.4                | 47.8                         | 55                           | 49.3                | 45.7                         | 52.9                         | 50.5                | 46.9                         | 54.1                         | 
| 4                     | Lincoln Square      | 57.9                | 53.6                         | 62.2                         | 56.1                | 51.8                         | 60.4                         | 52.1                | 48                           | 56.2                         | 55.4                | 51.1                         | 59.7                         | 57.7                | 53.3                         | 62.1                         | 53.2                | 49                           | 57.4                         | 52.2                | 48                           | 56.4                         | 55.6                | 51.3                         | 59.9                         | 52                  | 47.8                         | 56.2                         | 57.4                | 53                           | 61.8                         | 61                  | 56.4                         | 65.6                         | 
| 5                     | North Center        | 52.5                | 47.9                         | 57.1                         | 62.1                | 57.1                         | 67.1                         | 57                  | 52.2                         | 61.8                         | 58.1                | 53.2                         | 63                           | 62.4                | 57.3                         | 67.5                         | 63.8                | 58.7                         | 68.9                         | 65.7                | 60.5                         | 70.9                         | 71                  | 65.6                         | 76.4                         | 68.3                | 63                           | 73.6                         | 73.2                | 67.7                         | 78.7                         | 76.2                | 70.6                         | 81.8                         | 
| 6                     | Lake View           | 31.1                | 29.2                         | 33                           | 32.2                | 30.3                         | 34.1                         | 31.5                | 29.6                         | 33.4                         | 32.8                | 30.8                         | 34.8                         | 34.1                | 32.1                         | 36.1                         | 34.2                | 32.2                         | 36.2                         | 33.9                | 31.9                         | 35.9                         | 32.5                | 30.6                         | 34.4                         | 35.6                | 33.6                         | 37.6                         | 35.7                | 33.7                         | 37.7                         | 38.7                | 36.6                         | 40.8                         | 
| 7                     | Lincoln Park        | 38                  | 35.4                         | 40.6                         | 37.4                | 34.9                         | 39.9                         | 38.2                | 35.6                         | 40.8                         | 39.1                | 36.5                         | 41.7                         | 40.3                | 37.7                         | 42.9                         | 39.4                | 36.8                         | 42                           | 35.7                | 33.2                         | 38.2                         | 38.2                | 35.6                         | 40.8                         | 37.5                | 34.9                         | 40.1                         | 35.8                | 33.3                         | 38.3                         | 38.7                | 36.1                         | 41.3                         | 
| 8                     | Near North Side     | 35.3                | 32.7                         | 37.9                         | 37                  | 34.4                         | 39.6                         | 38.3                | 35.7                         | 40.9                         | 35.8                | 33.3                         | 38.3                         | 37                  | 34.4                         | 39.6                         | 37.1                | 34.6                         | 39.6                         | 34.4                | 32                           | 36.8                         | 34.6                | 32.2                         | 37                           | 32.8                | 30.5                         | 35.1                         | 35.1                | 32.7                         | 37.5                         | 35.9                | 33.5                         | 38.3                         | 
| 9                     | Edison Park         | 59.7                | 49.6                         | 69.8                         | 64.6                | 54.1                         | 75.1                         | 55.1                | 45.4                         | 64.8                         | 65.3                | 54.7                         | 75.9                         | 58.4                | 48.3                         | 68.5                         | 66.9                | 56.1                         | 77.7                         | 60                  | 49.7                         | 70.3                         | 60.3                | 50                           | 70.6                         | 58.4                | 48.2                         | 68.6                         | 67.1                | 56.1                         | 78.1                         | 59.5                | 49.2                         | 69.8                         | 
| 10                    | Norwood Park        | 61.2                | 55.4                         | 67                           | 60.5                | 54.7                         | 66.3                         | 62                  | 56.1                         | 67.9                         | 64.8                | 58.8                         | 70.8                         | 65.9                | 59.8                         | 72                           | 64.8                | 58.7                         | 70.9                         | 63.1                | 57.1                         | 69.1                         | 64.8                | 58.7                         | 70.9                         | 64.4                | 58.3                         | 70.5                         | 59.5                | 53.6                         | 65.4                         | 59.6                | 53.6                         | 65.6                         | 
```