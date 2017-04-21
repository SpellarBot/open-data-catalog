# IDPH: STDs Nationally Ranked By County, By Case Count Chlamydia 2006-2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idph-stds-nationally-ranked-by-county-chlamydia-2006-2013) |
| Metadata | [Link](https://data.illinois.gov/api/views/xuuw-9mzb) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/xuuw-9mzb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/xuuw-9mzb/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | xuuw-9mzb |
| Name | IDPH: STDs Nationally Ranked By County, By Case Count Chlamydia 2006-2015 |
| Attribution | Center for Disease Control and Prevention |
| Category | Public Health |
| Tags | std, nationally, ranked, nationally ranked, chlamydia, count, rate, cumulative percent |
| Created | 2013-11-01T16:03:21Z |
| Publication Date | 2016-10-20T13:15:12Z |

## Description

U.S. counties ranked nationally by cases of Chlamydia reported. Data Source: Centers for Disease Control and Prevention 2006-2015 Surveillance Report (http://www.cdc.gov/STD/publications/default.htm)

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| Yes      | numeric metric | rankbycount             | RankByCount             | number    | number      |
| Yes      | time           | year                    | Year                    | number    | text        |
| Yes      | series tag     | county_independent_city | County/Independent City | text      | text        |
| Yes      | numeric metric | count                   | Count                   | number    | number      |
| Yes      | numeric metric | rate                    | Rate                    | number    | number      |
| Yes      | numeric metric | cumulative_percent      | Cumulative Percent      | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:xuuw-9mzb d:2006-01-01T00:00:00.000Z t:county_independent_city="Los Angeles County, CA" m:rate=432.2 m:count=42943 m:rankbycount=1 m:cumulative_percent=4

series e:xuuw-9mzb d:2006-01-01T00:00:00.000Z t:county_independent_city="Cook County, IL" m:rate=598.8 m:count=31757 m:rankbycount=2 m:cumulative_percent=7

series e:xuuw-9mzb d:2006-01-01T00:00:00.000Z t:county_independent_city="Philadelphia County, PA" m:rate=1175.4 m:count=17199 m:rankbycount=3 m:cumulative_percent=8
```

## Meta Commands

```ls
metric m:rankbycount p:integer l:RankByCount t:dataTypeName=number

metric m:count p:integer l:Count t:dataTypeName=number

metric m:rate p:float l:Rate t:dataTypeName=number

metric m:cumulative_percent p:integer l:"Cumulative Percent" t:dataTypeName=number

entity e:xuuw-9mzb l:"IDPH: STDs Nationally Ranked By County, By Case Count Chlamydia 2006-2015" t:attribution="Center for Disease Control and Prevention" t:url=https://data.illinois.gov/api/views/xuuw-9mzb

property e:xuuw-9mzb t:meta.view v:id=xuuw-9mzb v:category="Public Health" v:attributionLink=http://www.cdc.gov/STD/publications/default.htm v:averageRating=0 v:name="IDPH: STDs Nationally Ranked By County, By Case Count Chlamydia 2006-2015" v:attribution="Center for Disease Control and Prevention"

property e:xuuw-9mzb t:meta.view.owner v:id=rth8-ngz8 v:screenName="Danny Brikshavana" v:displayName="Danny Brikshavana"

property e:xuuw-9mzb t:meta.view.tableauthor v:id=rth8-ngz8 v:screenName="Danny Brikshavana" v:displayName="Danny Brikshavana"
```

## Top Records

```ls
| rankbycount | year | county_independent_city | count | rate   | cumulative_percent | 
| =========== | ==== | ======================= | ===== | ====== | ================== | 
| 1           | 2006 | Los Angeles County, CA  | 42943 | 432.2  | 4                  | 
| 2           | 2006 | Cook County, IL         | 31757 | 598.8  | 7                  | 
| 3           | 2006 | Philadelphia County, PA | 17199 | 1175.4 | 8                  | 
| 4           | 2006 | Maricopa County, AZ     | 14579 | 401.0  | 10                 | 
| 5           | 2006 | Kings County, NY        | 13915 | 559.7  | 11                 | 
| 6           | 2006 | Wayne County, MI        | 12213 | 611.2  | 12                 | 
| 7           | 2006 | San Diego County, CA    | 11980 | 408.4  | 14                 | 
| 8           | 2006 | Harris County, TX       | 11872 | 321.5  | 15                 | 
| 9           | 2006 | Bronx County, NY        | 10494 | 773.0  | 16                 | 
| 10          | 2006 | Milwaukee County, WI    | 9999  | 1084.9 | 17                 | 
```