# Juvenile Unemployment for 16-19 Year Olds from 2000-2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/juvenile-unemployment-for-16-19-year-olds-from-2000-2013) |
| Metadata | [Link](https://data.wa.gov/api/views/hn25-k5xm) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/hn25-k5xm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/hn25-k5xm/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | hn25-k5xm |
| Name | Juvenile Unemployment for 16-19 Year Olds from 2000-2013 |
| Created | 2015-12-01T05:06:11Z |
| Publication Date | 2016-01-21T06:15:03Z |

## Columns

```ls
| Included | Schema Type    | Field Name                    | Name                          | Data Type | Render Type |
| ======== | ============== | ============================= | ============================= | ========= | =========== |
| Yes      | time           | year                          | Year                          | number    | text        |
| Yes      | numeric metric | approximate_number_unemployed | Approximate Number Unemployed | number    | number      |
| Yes      | numeric metric | approximate_unemployment_rate | Approximate Unemployment Rate | percent   | percent     |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:hn25-k5xm d:2013-01-01T00:00:00.000Z m:approximate_unemployment_rate=30.6 m:approximate_number_unemployed=37000

series e:hn25-k5xm d:2012-01-01T00:00:00.000Z m:approximate_unemployment_rate=28.6 m:approximate_number_unemployed=36000

series e:hn25-k5xm d:2011-01-01T00:00:00.000Z m:approximate_unemployment_rate=30.4 m:approximate_number_unemployed=38000
```

## Meta Commands

```ls
metric m:approximate_number_unemployed p:integer l:"Approximate Number Unemployed" t:dataTypeName=number

metric m:approximate_unemployment_rate p:float l:"Approximate Unemployment Rate" t:dataTypeName=percent

entity e:hn25-k5xm l:"Juvenile Unemployment for 16-19 Year Olds from 2000-2013" t:url=https://data.wa.gov/api/views/hn25-k5xm

property e:hn25-k5xm t:meta.view v:id=hn25-k5xm v:averageRating=0 v:name="Juvenile Unemployment for 16-19 Year Olds from 2000-2013"

property e:hn25-k5xm t:meta.view.owner v:id=6p7r-jviv v:profileImageUrlMedium=/api/users/6p7r-jviv/profile_images/THUMB v:profileImageUrlLarge=/api/users/6p7r-jviv/profile_images/LARGE v:screenName="Alysa Kipersztok" v:profileImageUrlSmall=/api/users/6p7r-jviv/profile_images/TINY v:displayName="Alysa Kipersztok"

property e:hn25-k5xm t:meta.view.tableauthor v:id=6p7r-jviv v:profileImageUrlMedium=/api/users/6p7r-jviv/profile_images/THUMB v:profileImageUrlLarge=/api/users/6p7r-jviv/profile_images/LARGE v:screenName="Alysa Kipersztok" v:profileImageUrlSmall=/api/users/6p7r-jviv/profile_images/TINY v:roleName=viewer v:displayName="Alysa Kipersztok"
```

## Top Records

```ls
| year | approximate_number_unemployed | approximate_unemployment_rate | 
| ==== | ============================= | ============================= | 
| 2013 | 37000                         | 30.6                          | 
| 2012 | 36000                         | 28.6                          | 
| 2011 | 38000                         | 30.4                          | 
| 2010 | 45000                         | 34.1                          | 
| 2009 | 44000                         | 30.5                          | 
| 2008 | 39000                         | 25.7                          | 
| 2007 | 28000                         | 17.6                          | 
| 2006 | 31000                         | 18.0                          | 
| 2005 | 29000                         | 18.9                          | 
| 2004 | 32000                         | 21.9                          | 
```