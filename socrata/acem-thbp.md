# Total City Population by Year

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/total-city-population-by-year) |
| Metadata | [Link](https://data.iowa.gov/api/views/acem-thbp) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/acem-thbp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/acem-thbp/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | acem-thbp |
| Name | Total City Population by Year |
| Attribution | U.S. Census Bureau, Population Division, 301-763-2422 |
| Category | Communities & People |
| Tags | decennial census, annual population estimates |
| Created | 2015-07-31T18:33:17Z |
| Publication Date | 2016-07-12T14:30:11Z |

## Description

This dataset contains city population in Iowa from 1990 to the most current year available. Data from 1990, 2000, and 2010 comes from the decennial censuses while the years in between are produced annually.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name       | Data Type     | Render Type   |
| ======== | ============== | ============== | ========== | ============= | ============= |
| Yes      | series tag     | fips           | FIPS       | text          | number        |
| Yes      | series tag     | geographicname | City       | text          | text          |
| Yes      | time           | year           | Year       | calendar_date | calendar_date |
| Yes      | numeric metric | population     | Population | number        | number        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:acem-thbp d:1999-07-01T00:00:00.000Z t:geographicname=Ackley t:fips=1900190 m:population=1669

series e:acem-thbp d:1998-07-01T00:00:00.000Z t:geographicname=Ackley t:fips=1900190 m:population=1675

series e:acem-thbp d:1997-07-01T00:00:00.000Z t:geographicname=Ackley t:fips=1900190 m:population=1673
```

## Meta Commands

```ls
metric m:population p:integer l:Population t:dataTypeName=number

entity e:acem-thbp l:"Total City Population by Year" t:attribution="U.S. Census Bureau, Population Division, 301-763-2422" t:url=https://data.iowa.gov/api/views/acem-thbp

property e:acem-thbp t:meta.view v:id=acem-thbp v:category="Communities & People" v:attributionLink=http://www.census.gov/popest/estimates.html v:averageRating=0 v:name="Total City Population by Year" v:attribution="U.S. Census Bureau, Population Division, 301-763-2422"

property e:acem-thbp t:meta.view.license v:name="Public Domain"

property e:acem-thbp t:meta.view.owner v:id=mznr-mts4 v:profileImageUrlMedium=/api/users/mznr-mts4/profile_images/THUMB v:profileImageUrlLarge=/api/users/mznr-mts4/profile_images/LARGE v:screenName="Gary Krob" v:profileImageUrlSmall=/api/users/mznr-mts4/profile_images/TINY v:displayName="Gary Krob"

property e:acem-thbp t:meta.view.tableauthor v:id=mznr-mts4 v:profileImageUrlMedium=/api/users/mznr-mts4/profile_images/THUMB v:profileImageUrlLarge=/api/users/mznr-mts4/profile_images/LARGE v:screenName="Gary Krob" v:profileImageUrlSmall=/api/users/mznr-mts4/profile_images/TINY v:roleName=administrator v:displayName="Gary Krob"
```

## Top Records

```ls
| fips    | geographicname | year                | population | 
| ======= | ============== | =================== | ========== | 
| 1900190 | Ackley         | 1999-07-01T00:00:00 | 1669       | 
| 1900190 | Ackley         | 1998-07-01T00:00:00 | 1675       | 
| 1900190 | Ackley         | 1997-07-01T00:00:00 | 1673       | 
| 1900190 | Ackley         | 1996-07-01T00:00:00 | 1674       | 
| 1900190 | Ackley         | 1995-07-01T00:00:00 | 1677       | 
| 1900190 | Ackley         | 1994-07-01T00:00:00 | 1680       | 
| 1900190 | Ackley         | 1993-07-01T00:00:00 | 1688       | 
| 1900190 | Ackley         | 1992-07-01T00:00:00 | 1697       | 
| 1900190 | Ackley         | 1991-07-01T00:00:00 | 1709       | 
| 1900190 | Ackley         |                     | 1696       | 
```