# IDPH 1990-2015 STD Illinois By County Chlamydia

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idph-2000-2013-std-illinois-by-county-chlamydia) |
| Metadata | [Link](https://data.illinois.gov/api/views/vcg3-dux6) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/vcg3-dux6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/vcg3-dux6/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | vcg3-dux6 |
| Name | IDPH 1990-2015 STD Illinois By County Chlamydia |
| Attribution | Illinois Department of Public Health STD Program |
| Category | Public Health |
| Tags | std, chlamydia, county, count, rate |
| Created | 2013-11-01T15:36:00Z |
| Publication Date | 2016-08-15T16:21:58Z |
| Rows Updated | 2016-08-15T16:21:15Z |

## Description

Illinois Chlamydia case counts and rates (per 100,000 population) by county by year (1990 to 2015).  See attachment for metadata and censoring details under the "About" link.  Null values in dataset reflect censored data.  Data Source: Illinois Department of Public Health STD Program.

## Columns

```ls
| Included | Schema Type    | Field Name | Name                | Data Type | Render Type |
| ======== | ============== | ========== | =================== | ========= | =========== |
| Yes      | numeric metric | sort       | Sort                | number    | number      |
| Yes      | time           | year       | Year                | number    | text        |
| Yes      | series tag     | county     | County/Jurisdiction | text      | text        |
| Yes      | series tag     | countyfips | CountyFIPS          | text      | text        |
| Yes      | numeric metric | 2008_count | Count               | number    | number      |
| Yes      | numeric metric | 2009_count | Rate                | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:vcg3-dux6 d:1990-01-01T00:00:00.000Z t:countyfips=17001 t:county=ADAMS m:sort=1 m:2009_count=166.4 m:2008_count=110

series e:vcg3-dux6 d:1990-01-01T00:00:00.000Z t:countyfips=17003 t:county=ALEXANDER m:sort=2 m:2009_count=395.3 m:2008_count=42

series e:vcg3-dux6 d:1990-01-01T00:00:00.000Z t:countyfips=17005 t:county=BOND m:sort=3 m:2009_count=33.4 m:2008_count=5
```

## Meta Commands

```ls
metric m:sort p:integer l:Sort t:dataTypeName=number

metric m:2008_count p:integer l:Count t:dataTypeName=number

metric m:2009_count p:float l:Rate t:dataTypeName=number

entity e:vcg3-dux6 l:"IDPH 1990-2015 STD Illinois By County Chlamydia" t:attribution="Illinois Department of Public Health STD Program" t:url=https://data.illinois.gov/api/views/vcg3-dux6

property e:vcg3-dux6 t:meta.view v:id=vcg3-dux6 v:category="Public Health" v:averageRating=0 v:name="IDPH 1990-2015 STD Illinois By County Chlamydia" v:attribution="Illinois Department of Public Health STD Program"

property e:vcg3-dux6 t:meta.view.owner v:id=rth8-ngz8 v:screenName="Danny Brikshavana" v:roleName=publisher v:displayName="Danny Brikshavana"

property e:vcg3-dux6 t:meta.view.tableauthor v:id=rth8-ngz8 v:screenName="Danny Brikshavana" v:roleName=publisher v:displayName="Danny Brikshavana"
```