# Champaign Population 1860-2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/champaign-population-1860-2010-46fce) |
| Metadata | [Link](https://data.illinois.gov/api/views/j5j5-zjn8) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/j5j5-zjn8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/j5j5-zjn8/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | j5j5-zjn8 |
| Name | Champaign Population 1860-2010 |
| Attribution | City of Champaign |
| Category | Municipality |
| Tags | champaign |
| Created | 2012-12-05T01:27:26Z |
| Publication Date | 2012-12-05T01:37:16Z |

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| Yes      | time           | year           | Year           | number    | number      |
| Yes      | numeric metric | population     | Population     | number    | number      |
| Yes      | numeric metric | percent_growth | Percent Growth | percent   | percent     |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:j5j5-zjn8 d:1860-01-01T00:00:00.000Z m:population=1727

series e:j5j5-zjn8 d:1870-01-01T00:00:00.000Z m:percent_growth=167.8 m:population=4625

series e:j5j5-zjn8 d:1880-01-01T00:00:00.000Z m:percent_growth=10.3 m:population=5103
```

## Meta Commands

```ls
metric m:population p:integer l:Population t:dataTypeName=number

metric m:percent_growth p:float l:"Percent Growth" t:dataTypeName=percent

entity e:j5j5-zjn8 l:"Champaign Population 1860-2010" t:attribution="City of Champaign" t:url=https://data.illinois.gov/api/views/j5j5-zjn8

property e:j5j5-zjn8 t:meta.view v:id=j5j5-zjn8 v:category=Municipality v:averageRating=0 v:name="Champaign Population 1860-2010" v:attribution="City of Champaign"

property e:j5j5-zjn8 t:meta.view.license v:name="Public Domain"

property e:j5j5-zjn8 t:meta.view.owner v:id=v5dz-wzd9 v:screenName="Patrick East" v:displayName="Patrick East"

property e:j5j5-zjn8 t:meta.view.tableauthor v:id=v5dz-wzd9 v:screenName="Patrick East" v:displayName="Patrick East"
```

## Top Records

```ls
| year | population | percent_growth | 
| ==== | ========== | ============== | 
| 1860 | 1727       |                | 
| 1870 | 4625       | 167.8          | 
| 1880 | 5103       | 10.3           | 
| 1890 | 5839       | 14.4           | 
| 1900 | 9098       | 55.8           | 
| 1910 | 12421      | 36.5           | 
| 1920 | 15873      | 27.8           | 
| 1930 | 20348      | 28.2           | 
| 1940 | 23302      | 14.5           | 
| 1950 | 39563      | 69.8           | 
```