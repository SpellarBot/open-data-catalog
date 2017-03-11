# IDPH 1990-2015 STD Illinois By County Chlamydia

## Dataset

* [Dataset URL](https://data.illinois.gov/api/views/vcg3-dux6/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/idph-2000-2013-std-illinois-by-county-chlamydia)
* [Metadata URL](https://data.illinois.gov/api/views/vcg3-dux6)
* Id = vcg3-dux6
* Name = IDPH 1990-2015 STD Illinois By County Chlamydia
* Attribution = Illinois Department of Public Health STD Program
* Category = Public Health
* Tags = [std, chlamydia, county, count, rate]
* Created = 2013-11-01T15:36:00Z
* Publication Date = 2016-08-15T16:21:58Z
* Rows Updated = 2016-08-15T16:21:15Z

## Description

Illinois Chlamydia case counts and rates (per 100,000 population) by county by year (1990 to 2015).  See attachment for metadata and censoring details under the "About" link.  Null values in dataset reflect censored data.  Data Source: Illinois Department of Public Health STD Program.

## Columns

```ls
| Name                | Field Name | Data Type | Render Type | Schema Type    | Included | 
| =================== | ========== | ========= | =========== | ============== | ======== | 
| Sort                | sort       | number    | number      | numeric metric | Yes      | 
| Year                | year       | number    | text        | time           | Yes      | 
| County/Jurisdiction | county     | text      | text        | series tag     | Yes      | 
| CountyFIPS          | countyfips | text      | text        | series tag     | Yes      | 
| Count               | 2008_count | number    | number      | numeric metric | Yes      | 
| Rate                | 2009_count | number    | number      | numeric metric | Yes      | 
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = 
Annotation Fields = 
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

metric m:2009_count l:Rate t:dataTypeName=number

entity e:vcg3-dux6 l:"IDPH 1990-2015 STD Illinois By County Chlamydia" t:attribution="Illinois Department of Public Health STD Program" t:url=https://data.illinois.gov/api/views/vcg3-dux6

property e:vcg3-dux6 t:meta.view d:2017-03-08T00:56:30.958Z v:id=vcg3-dux6 v:category="Public Health" v:averageRating=0 v:name="IDPH 1990-2015 STD Illinois By County Chlamydia" v:attribution="Illinois Department of Public Health STD Program"

property e:vcg3-dux6 t:meta.view.owner d:2017-03-08T00:56:30.958Z v:id=rth8-ngz8 v:screenName="Danny Brikshavana" v:roleName=publisher v:displayName="Danny Brikshavana"

property e:vcg3-dux6 t:meta.view.tableauthor d:2017-03-08T00:56:30.958Z v:id=rth8-ngz8 v:screenName="Danny Brikshavana" v:roleName=publisher v:displayName="Danny Brikshavana"
```