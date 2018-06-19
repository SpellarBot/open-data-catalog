# Maryland Veterans Unemployment Rate

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/maryland-veterans-unemployment-rate-3ea61) |
| Metadata | [Link](https://data.maryland.gov/api/views/prxf-ppu5) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/prxf-ppu5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/prxf-ppu5/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | prxf-ppu5 |
| Name | Maryland Veterans Unemployment Rate |
| Attribution | Bureau of Labor Statistics |
| Category | Business and Economy |
| Tags | veterans, unemployment, jobs, employment |
| Created | 2013-03-22T13:36:36Z |
| Publication Date | 2015-09-08T19:57:58Z |

## Description

This data set contains the veterans unemployment rate in Maryland. Figures come from the Bureau of Labor Statistics, and are subject to revision.

## Columns

```ls
| Included | Schema Type    | Field Name                          | Name                                | Data Type | Render Type |
| ======== | ============== | =================================== | =================================== | ========= | =========== |
| Yes      | time           | year                                | Year                                | number    | text        |
| Yes      | numeric metric | maryland_veterans_unemployment_rate | Maryland Veterans Unemployment Rate | percent   | percent     |
| Yes      | numeric metric | national_veterans_unemployment_rate | National Veterans Unemployment Rate | percent   | percent     |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:prxf-ppu5 d:2010-01-01T00:00:00.000Z m:maryland_veterans_unemployment_rate=5 m:national_veterans_unemployment_rate=8.7

series e:prxf-ppu5 d:2011-01-01T00:00:00.000Z m:maryland_veterans_unemployment_rate=5.9 m:national_veterans_unemployment_rate=8.3

series e:prxf-ppu5 d:2009-01-01T00:00:00.000Z m:maryland_veterans_unemployment_rate=5.6 m:national_veterans_unemployment_rate=8.1
```

## Meta Commands

```ls
metric m:maryland_veterans_unemployment_rate p:float l:"Maryland Veterans Unemployment Rate" t:dataTypeName=percent

metric m:national_veterans_unemployment_rate p:float l:"National Veterans Unemployment Rate" t:dataTypeName=percent

entity e:prxf-ppu5 l:"Maryland Veterans Unemployment Rate" t:attribution="Bureau of Labor Statistics" t:url=https://data.maryland.gov/api/views/prxf-ppu5

property e:prxf-ppu5 t:meta.view v:id=prxf-ppu5 v:category="Business and Economy" v:attributionLink=http://www.bls.gov/ v:averageRating=0 v:name="Maryland Veterans Unemployment Rate" v:attribution="Bureau of Labor Statistics"

property e:prxf-ppu5 t:meta.view.license v:name="Public Domain"

property e:prxf-ppu5 t:meta.view.owner v:id=qkre-c4b4 v:screenName="Kristen Ahearn" v:displayName="Kristen Ahearn"

property e:prxf-ppu5 t:meta.view.tableauthor v:id=qkre-c4b4 v:screenName="Kristen Ahearn" v:roleName=publisher v:displayName="Kristen Ahearn"
```

## Top Records

```ls
| year | maryland_veterans_unemployment_rate | national_veterans_unemployment_rate | 
| ==== | =================================== | =================================== | 
| 2010 | 5                                   | 8.7                                 | 
| 2011 | 5.9                                 | 8.3                                 | 
| 2009 | 5.6                                 | 8.1                                 | 
| 2012 | 5.3                                 | 7                                   | 
| 2013 | 5.9                                 | 6.6                                 | 
| 2014 | 8.5                                 | 5.3                                 | 
```