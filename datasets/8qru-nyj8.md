# Historical Data Of Foreign-Born Population in New York City

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/historical-data-of-foreign-born-population-in-new-york-city-ec414) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/8qru-nyj8) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/8qru-nyj8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/8qru-nyj8/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 8qru-nyj8 |
| Name | Historical Data Of Foreign-Born Population in New York City |
| Attribution | Department of City Planning (DCP) |
| Category | City Government |
| Tags | dcp, city, planning, foreign-born, population |
| Created | 2013-02-19T15:31:32Z |
| Publication Date | 2013-06-26T17:15:12Z |

## Description

Details of foreign-born population versus total population in New York City since 1820

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| Yes      | time           | year                    | Year                    | number    | text        |
| Yes      | numeric metric | total_population        | Total Population        | number    | number      |
| Yes      | numeric metric | foreign_born_population | Foreign-Born Population | number    | text        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:8qru-nyj8 d:1790-01-01T00:00:00.000Z t:foreign_born_population=- m:total_population=33131

series e:8qru-nyj8 d:1800-01-01T00:00:00.000Z t:foreign_born_population=- m:total_population=60515

series e:8qru-nyj8 d:1810-01-01T00:00:00.000Z t:foreign_born_population=- m:total_population=96373
```

## Meta Commands

```ls
metric m:total_population p:integer l:"Total Population" t:dataTypeName=number

entity e:8qru-nyj8 l:"Historical Data Of Foreign-Born Population in New York City" t:attribution="Department of City Planning (DCP)" t:url=https://data.cityofnewyork.us/api/views/8qru-nyj8

property e:8qru-nyj8 t:meta.view v:id=8qru-nyj8 v:category="City Government" v:attributionLink=http://www.nyc.gov/html/dcp/pdf/census/1790-2000_nyc_total_foreign_birth.pdf v:averageRating=0 v:name="Historical Data Of Foreign-Born Population in New York City" v:attribution="Department of City Planning (DCP)"

property e:8qru-nyj8 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:8qru-nyj8 t:meta.view.tableauthor v:id=8b43-zkvh v:screenName="Ram S." v:displayName="Ram S."
```

## Top Records

```ls
| year | total_population | foreign_born_population | 
| ==== | ================ | ======================= | 
| 1790 | 33131            | -                       | 
| 1800 | 60515            | -                       | 
| 1810 | 96373            | -                       | 
| 1820 | 123706           | 5,390                   | 
| 1830 | 202589           | 17,773                  | 
| 1840 | 312710           | -                       | 
| 1850 | 515547           | 235,733                 | 
| 1860 | 813669           | 383,717                 | 
| 1870 | 942292           | 419,094                 | 
| 1880 | 1206299          | 478,670                 | 
```