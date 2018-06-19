# Total City Population by County and Year

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/total-city-population-by-county-and-year) |
| Metadata | [Link](https://data.iowa.gov/api/views/y8va-rhk9) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/y8va-rhk9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/y8va-rhk9/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | y8va-rhk9 |
| Name | Total City Population by County and Year |
| Attribution | U.S. Census Bureau, Population Division, 301-763-2422 |
| Category | Communities & People |
| Tags | decennial census, annual population estimates |
| Created | 2015-08-04T14:25:35Z |
| Publication Date | 2016-07-12T14:16:24Z |

## Description

This dataset contains city population in Iowa from 2010 to the most current year available. Data from 2010 comes from the decennial census while the proceeding years are produced annually. Aggregating the city populations in each county will provide a county total population

## Columns

```ls
| Included | Schema Type    | Field Name | Name     | Data Type     | Render Type   |
| ======== | ============== | ========== | ======== | ============= | ============= |
| Yes      | series tag     | fips       | FIPS     | text          | number        |
| Yes      | series tag     | county     | County   | text          | text          |
| Yes      | series tag     | geo_name   | City     | text          | text          |
| Yes      | time           | year       | Year     | calendar_date | calendar_date |
| Yes      | numeric metric | estimate   | Estimate | number        | number        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:y8va-rhk9 d:2010-04-01T00:00:00.000Z t:county=Adair t:geo_name="Adair (pt.)" t:fips=1900370 m:estimate=762

series e:y8va-rhk9 d:2010-07-01T00:00:00.000Z t:county=Adair t:geo_name="Adair (pt.)" t:fips=1900370 m:estimate=760

series e:y8va-rhk9 d:2011-07-01T00:00:00.000Z t:county=Adair t:geo_name="Adair (pt.)" t:fips=1900370 m:estimate=751
```

## Meta Commands

```ls
metric m:estimate p:integer l:Estimate t:dataTypeName=number

entity e:y8va-rhk9 l:"Total City Population by County and Year" t:attribution="U.S. Census Bureau, Population Division, 301-763-2422" t:url=https://data.iowa.gov/api/views/y8va-rhk9

property e:y8va-rhk9 t:meta.view v:id=y8va-rhk9 v:category="Communities & People" v:attributionLink=http://www.census.gov/popest/estimates.html v:averageRating=0 v:name="Total City Population by County and Year" v:attribution="U.S. Census Bureau, Population Division, 301-763-2422"

property e:y8va-rhk9 t:meta.view.license v:name="Public Domain"

property e:y8va-rhk9 t:meta.view.owner v:id=mznr-mts4 v:profileImageUrlMedium=/api/users/mznr-mts4/profile_images/THUMB v:profileImageUrlLarge=/api/users/mznr-mts4/profile_images/LARGE v:screenName="Gary Krob" v:profileImageUrlSmall=/api/users/mznr-mts4/profile_images/TINY v:displayName="Gary Krob"

property e:y8va-rhk9 t:meta.view.tableauthor v:id=mznr-mts4 v:profileImageUrlMedium=/api/users/mznr-mts4/profile_images/THUMB v:profileImageUrlLarge=/api/users/mznr-mts4/profile_images/LARGE v:screenName="Gary Krob" v:profileImageUrlSmall=/api/users/mznr-mts4/profile_images/TINY v:roleName=administrator v:displayName="Gary Krob"
```

## Top Records

```ls
| fips    | county | geo_name    | year                | estimate | 
| ======= | ====== | =========== | =================== | ======== | 
| 1900370 | Adair  | Adair (pt.) | 2010-04-01T00:00:00 | 762      | 
| 1900370 | Adair  | Adair (pt.) | 2010-07-01T00:00:00 | 760      | 
| 1900370 | Adair  | Adair (pt.) | 2011-07-01T00:00:00 | 751      | 
| 1900370 | Adair  | Adair (pt.) | 2012-07-01T00:00:00 | 739      | 
| 1900370 | Adair  | Adair (pt.) | 2013-07-01T00:00:00 | 732      | 
| 1900370 | Adair  | Adair (pt.) | 2014-07-01T00:00:00 | 729      | 
| 1900370 | Adair  | Adair (pt.) | 2015-07-01T00:00:00 | 709      | 
| 1908425 | Adair  | Bridgewater | 2010-04-01T00:00:00 | 182      | 
| 1908425 | Adair  | Bridgewater | 2010-07-01T00:00:00 | 182      | 
| 1908425 | Adair  | Bridgewater | 2011-07-01T00:00:00 | 180      | 
```