# Maryland Births and Birth Rates, 1902-2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/maryland-births-and-birth-rates-1902-2011-3252f) |
| Metadata | [Link](https://data.maryland.gov/api/views/jc6h-tmg9) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/jc6h-tmg9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/jc6h-tmg9/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | jc6h-tmg9 |
| Name | Maryland Births and Birth Rates, 1902-2011 |
| Attribution | Vital Statistics Administration |
| Category | Health and Human Services |
| Tags | live birth, birth rate, vital statistics |
| Created | 2012-11-19T21:29:40Z |
| Publication Date | 2012-11-19T21:31:49Z |

## Description

Number of live births and birth rate per 1,000 population by year.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| Yes      | time           | year             | Year             | number    | number      |
| Yes      | numeric metric | number_of_births | Number of Births | number    | number      |
| Yes      | numeric metric | birth_rate       | Birth Rate       | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:jc6h-tmg9 d:1902-01-01T00:00:00.000Z m:birth_rate=14.8 m:number_of_births=18045

series e:jc6h-tmg9 d:1903-01-01T00:00:00.000Z m:birth_rate=14.6 m:number_of_births=17993

series e:jc6h-tmg9 d:1904-01-01T00:00:00.000Z m:birth_rate=13.6 m:number_of_births=16964
```

## Meta Commands

```ls
metric m:number_of_births p:integer l:"Number of Births" t:dataTypeName=number

metric m:birth_rate p:float l:"Birth Rate" t:dataTypeName=number

entity e:jc6h-tmg9 l:"Maryland Births and Birth Rates, 1902-2011" t:attribution="Vital Statistics Administration" t:url=https://data.maryland.gov/api/views/jc6h-tmg9

property e:jc6h-tmg9 t:meta.view v:id=jc6h-tmg9 v:category="Health and Human Services" v:attributionLink=http://dhmh.maryland.gov/vsa/SitePages/reports.aspx v:averageRating=0 v:name="Maryland Births and Birth Rates, 1902-2011" v:attribution="Vital Statistics Administration"

property e:jc6h-tmg9 t:meta.view.owner v:id=e5tx-wz6d v:screenName="Andrea Bankoski" v:displayName="Andrea Bankoski"

property e:jc6h-tmg9 t:meta.view.tableauthor v:id=e5tx-wz6d v:screenName="Andrea Bankoski" v:roleName=editor v:displayName="Andrea Bankoski"
```

## Top Records

```ls
| year | number_of_births | birth_rate | 
| ==== | ================ | ========== | 
| 1902 | 18045            | 14.8       | 
| 1903 | 17993            | 14.6       | 
| 1904 | 16964            | 13.6       | 
| 1905 | 17952            | 14.9       | 
| 1906 | 18908            | 14.7       | 
| 1907 | 18105            | 14.0       | 
| 1908 | 19397            | 14.7       | 
| 1909 | 19635            | 14.7       | 
| 1910 | 20568            | 15.9       | 
| 1911 | 19844            | 15.2       | 
```