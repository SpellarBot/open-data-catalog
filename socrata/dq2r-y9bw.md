# IDPH 1990-2015 STD Illinois By County Gonorrhea

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idph-2000-2013-std-illinois-by-county-gonorrhea) |
| Metadata | [Link](https://data.illinois.gov/api/views/dq2r-y9bw) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/dq2r-y9bw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/dq2r-y9bw/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | dq2r-y9bw |
| Name | IDPH 1990-2015 STD Illinois By County Gonorrhea |
| Attribution | Illinois Department of Public Health STD Program |
| Category | Public Health |
| Tags | std, gonorrhea, county, count, rate |
| Created | 2013-11-01T15:59:12Z |
| Publication Date | 2016-08-15T16:16:31Z |

## Description

Illinois gonorrhea case counts and rates (per 100,000 population) by county by year (1990 to 2015).  See attachment for metadata and censoring details under the "About" link.  Null values in dataset reflect censored data.  Data Source: Illinois Department of Public Health STD Program.

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
series e:dq2r-y9bw d:1990-01-01T00:00:00.000Z t:countyfips=17001 t:county=ADAMS m:sort=1 m:2009_count=83.2 m:2008_count=55

series e:dq2r-y9bw d:1990-01-01T00:00:00.000Z t:countyfips=17003 t:county=ALEXANDER m:sort=2 m:2009_count=574.1 m:2008_count=61

series e:dq2r-y9bw d:1990-01-01T00:00:00.000Z t:countyfips=17005 t:county=BOND m:sort=3 m:2009_count=53.4 m:2008_count=8
```

## Meta Commands

```ls
metric m:sort p:integer l:Sort t:dataTypeName=number

metric m:2008_count p:integer l:Count t:dataTypeName=number

metric m:2009_count p:float l:Rate t:dataTypeName=number

entity e:dq2r-y9bw l:"IDPH 1990-2015 STD Illinois By County Gonorrhea" t:attribution="Illinois Department of Public Health STD Program" t:url=https://data.illinois.gov/api/views/dq2r-y9bw

property e:dq2r-y9bw t:meta.view v:id=dq2r-y9bw v:category="Public Health" v:averageRating=0 v:name="IDPH 1990-2015 STD Illinois By County Gonorrhea" v:attribution="Illinois Department of Public Health STD Program"

property e:dq2r-y9bw t:meta.view.owner v:id=rth8-ngz8 v:screenName="Danny Brikshavana" v:displayName="Danny Brikshavana"

property e:dq2r-y9bw t:meta.view.tableauthor v:id=rth8-ngz8 v:screenName="Danny Brikshavana" v:displayName="Danny Brikshavana"
```

## Top Records

```ls
| sort | year | county    | countyfips | 2008_count | 2009_count | 
| ==== | ==== | ========= | ========== | ========== | ========== | 
| 1    | 1990 | ADAMS     | 17001      | 55         | 83.2       | 
| 2    | 1990 | ALEXANDER | 17003      | 61         | 574.1      | 
| 3    | 1990 | BOND      | 17005      | 8          | 53.4       | 
| 4    | 1990 | BOONE     | 17007      | 11         | 35.7       | 
| 5    | 1990 | BROWN     | 17009      | 6          | 102.8      | 
| 6    | 1990 | BUREAU    | 17011      | 0          | 0.0        | 
| 7    | 1990 | CALHOUN   | 17013      | 0          | 0.0        | 
| 8    | 1990 | CARROLL   | 17015      | 0          | 0.0        | 
| 9    | 1990 | CASS      | 17017      | 3          | 22.3       | 
| 10   | 1990 | CHAMPAIGN | 17019      | 619        | 357.8      | 
```