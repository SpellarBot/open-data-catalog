# IDPH: STDs Nationally Ranked By County, By Case Count Gonorrhea 2005-2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idph-stds-nationally-ranked-by-county-gonorrhea-2005-2013) |
| Metadata | [Link](https://data.illinois.gov/api/views/kc8y-8tqk) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/kc8y-8tqk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/kc8y-8tqk/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | kc8y-8tqk |
| Name | IDPH: STDs Nationally Ranked By County, By Case Count Gonorrhea 2005-2015 |
| Attribution | Centers for Disease Control and Prevention |
| Category | Public Health |
| Tags | std, nationally, ranked, nationally ranked, gonorrhea, count, rate, cumulative percent |
| Created | 2013-11-01T16:11:10Z |
| Publication Date | 2016-10-20T13:13:49Z |

## Description

U.S. counties ranked nationally by cases of gonorrhea reported. Data Source: Centers for Disease Control and Prevention 2005-2015 Surveillance Report (http://www.cdc.gov/STD/publications/default.htm)

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
series e:kc8y-8tqk d:2005-01-01T00:00:00.000Z t:county_independent_city="Cook County, IL" m:rate=230.8 m:count=12296 m:rankbycount=1 m:cumulative_percent=3

series e:kc8y-8tqk d:2005-01-01T00:00:00.000Z t:county_independent_city="Los Angeles County, CA" m:rate=113.8 m:count=11307 m:rankbycount=2 m:cumulative_percent=6

series e:kc8y-8tqk d:2005-01-01T00:00:00.000Z t:county_independent_city="Wayne County, MI" m:rate=457.5 m:count=9225 m:rankbycount=3 m:cumulative_percent=9
```

## Meta Commands

```ls
metric m:rankbycount p:integer l:RankByCount t:dataTypeName=number

metric m:count p:integer l:Count t:dataTypeName=number

metric m:rate p:float l:Rate t:dataTypeName=number

metric m:cumulative_percent p:integer l:"Cumulative Percent" t:dataTypeName=number

entity e:kc8y-8tqk l:"IDPH: STDs Nationally Ranked By County, By Case Count Gonorrhea 2005-2015" t:attribution="Centers for Disease Control and Prevention" t:url=https://data.illinois.gov/api/views/kc8y-8tqk

property e:kc8y-8tqk t:meta.view v:id=kc8y-8tqk v:category="Public Health" v:attributionLink=http://www.cdc.gov/STD/publications/default.htm v:averageRating=0 v:name="IDPH: STDs Nationally Ranked By County, By Case Count Gonorrhea 2005-2015" v:attribution="Centers for Disease Control and Prevention"

property e:kc8y-8tqk t:meta.view.owner v:id=rth8-ngz8 v:screenName="Danny Brikshavana" v:displayName="Danny Brikshavana"

property e:kc8y-8tqk t:meta.view.tableauthor v:id=rth8-ngz8 v:screenName="Danny Brikshavana" v:displayName="Danny Brikshavana"
```

## Top Records

```ls
| rankbycount | year | county_independent_city | count | rate               | cumulative_percent | 
| =========== | ==== | ======================= | ===== | ================== | ================== | 
| 1           | 2005 | Cook County, IL         | 12296 | 230.8              | 3                  | 
| 2           | 2005 | Los Angeles County, CA  | 11307 | 113.8              | 6                  | 
| 3           | 2005 | Wayne County, MI        | 9225  | 457.5              | 9                  | 
| 4           | 2005 | Philadelphia County, PA | 5053  | 343.7              | 11                 | 
| 5           | 2005 | Dallas County, TX       | 5034  | 219.4              | 12                 | 
| 6           | 2005 | Harris County, TX       | 4402  | 120.8              | 13                 | 
| 7           | 2005 | Cuyahoga County, OH     | 4214  | 311.89999999999998 | 15                 | 
| 8           | 2005 | Marion County, IN       | 3965  | 459.1              | 16                 | 
| 9           | 2005 | Milwaukee County, WI    | 3953  | 426                | 17                 | 
| 10          | 2005 | Kings County, NY        | 3772  | 152.4              | 18                 | 
```