# IDPH: STDs Nationally Ranked By County, By Case Count P&SSyp 2000-2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idph-stds-nationally-ranked-by-county-pssyp-2000-2013) |
| Metadata | [Link](https://data.illinois.gov/api/views/i8hz-ffis) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/i8hz-ffis/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/i8hz-ffis/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | i8hz-ffis |
| Name | IDPH: STDs Nationally Ranked By County, By Case Count P&SSyp 2000-2015 |
| Attribution | Centers for Disease Control and Prevention |
| Category | Public Health |
| Tags | std, nationally, ranked, nationally ranked, primary syphilis, secondary syphilis, primary and secondary syphilis, p&s, count, rate, cumulative percent |
| Created | 2013-11-01T16:16:14Z |
| Publication Date | 2016-10-20T13:11:29Z |

## Description

U.S. counties ranked nationally by cases of primary and secondary syphilis reported.  Data Source: Centers for Disease Control and Prevention 2000-2015 Surveillance Report (http://www.cdc.gov/STD/publications/default.htm)

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
series e:i8hz-ffis d:2000-01-01T00:00:00.000Z t:county_independent_city="Cook County, IL" m:rate=6.3 m:count=326 m:rankbycount=1 m:cumulative_percent=5

series e:i8hz-ffis d:2000-01-01T00:00:00.000Z t:county_independent_city="Marion County, IN" m:rate=37.1 m:count=301 m:rankbycount=2 m:cumulative_percent=10

series e:i8hz-ffis d:2000-01-01T00:00:00.000Z t:county_independent_city="Wayne County, MI" m:rate=13.7 m:count=288 m:rankbycount=3 m:cumulative_percent=15
```

## Meta Commands

```ls
metric m:rankbycount p:integer l:RankByCount t:dataTypeName=number

metric m:count p:integer l:Count t:dataTypeName=number

metric m:rate p:float l:Rate t:dataTypeName=number

metric m:cumulative_percent p:integer l:"Cumulative Percent" t:dataTypeName=number

entity e:i8hz-ffis l:"IDPH: STDs Nationally Ranked By County, By Case Count P&SSyp 2000-2015" t:attribution="Centers for Disease Control and Prevention" t:url=https://data.illinois.gov/api/views/i8hz-ffis

property e:i8hz-ffis t:meta.view v:id=i8hz-ffis v:category="Public Health" v:attributionLink=http://www.cdc.gov/STD/publications/default.htm v:averageRating=0 v:name="IDPH: STDs Nationally Ranked By County, By Case Count P&SSyp 2000-2015" v:attribution="Centers for Disease Control and Prevention"

property e:i8hz-ffis t:meta.view.owner v:id=rth8-ngz8 v:screenName="Danny Brikshavana" v:displayName="Danny Brikshavana"

property e:i8hz-ffis t:meta.view.tableauthor v:id=rth8-ngz8 v:screenName="Danny Brikshavana" v:displayName="Danny Brikshavana"
```

## Top Records

```ls
| rankbycount | year | county_independent_city | count | rate | cumulative_percent | 
| =========== | ==== | ======================= | ===== | ==== | ================== | 
| 1           | 2000 | Cook County, IL         | 326   | 6.3  | 5                  | 
| 2           | 2000 | Marion County, IN       | 301   | 37.1 | 10                 | 
| 3           | 2000 | Wayne County, MI        | 288   | 13.7 | 15                 | 
| 4           | 2000 | Shelby County, TN       | 246   | 28.2 | 19                 | 
| 5           | 2000 | Baltimore (City), MD    | 218   | 34.5 | 23                 | 
| 6           | 2000 | Fulton County, GA       | 203   | 27.3 | 26                 | 
| 7           | 2000 | Davidson County, TN     | 200   | 37.7 | 29                 | 
| 8           | 2000 | Maricopa County, AZ     | 172   | 6.0  | 32                 | 
| 9           | 2000 | Los Angeles County, CA  | 152   | 1.6  | 35                 | 
| 10          | 2000 | Dade County, FL         | 126   | 5.8  | 37                 | 
```