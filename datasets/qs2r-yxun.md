# DBEDT Hawaii Electricity Consumption 1970-2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dbedt-hawaii-electricity-consumption-1970-2010-ce504) |
| Metadata | [Link](https://data.hawaii.gov/api/views/qs2r-yxun) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/qs2r-yxun/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/qs2r-yxun/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | qs2r-yxun |
| Name | DBEDT Hawaii Electricity Consumption 1970-2010 |
| Attribution | Department of Economic Development and Tourism |
| Category | Economic Development |
| Tags | electricity, energy |
| Created | 2012-08-28T19:45:23Z |
| Publication Date | 2012-08-29T01:28:30Z |

## Columns

```ls
| Included | Schema Type    | Field Name                     | Name                           | Data Type | Render Type |
| ======== | ============== | ============================== | ============================== | ========= | =========== |
| Yes      | numeric metric | x_values                       | X Values                       | number    | number      |
| Yes      | numeric metric | hawaii_electricity_consumption | Hawaii Electricity Consumption | number    | number      |
```

## Time Field

```ls
Value = 1970
Format & Zone = yyyy
```

## Data Commands

```ls
series e:qs2r-yxun d:1970-01-01T00:00:00.000Z m:hawaii_electricity_consumption=1285 m:x_values=1960

series e:qs2r-yxun d:1970-01-01T00:00:00.000Z m:hawaii_electricity_consumption=1554 m:x_values=1961

series e:qs2r-yxun d:1970-01-01T00:00:00.000Z m:hawaii_electricity_consumption=1820 m:x_values=1962
```

## Meta Commands

```ls
metric m:x_values p:integer l:"X Values" t:dataTypeName=number

metric m:hawaii_electricity_consumption p:integer l:"Hawaii Electricity Consumption" t:dataTypeName=number

entity e:qs2r-yxun l:"DBEDT Hawaii Electricity Consumption 1970-2010" t:attribution="Department of Economic Development and Tourism" t:url=https://data.hawaii.gov/api/views/qs2r-yxun

property e:qs2r-yxun t:meta.view v:id=qs2r-yxun v:category="Economic Development" v:attributionLink=http://hawaii.gov/dbedt v:averageRating=0 v:name="DBEDT Hawaii Electricity Consumption 1970-2010" v:attribution="Department of Economic Development and Tourism"

property e:qs2r-yxun t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:qs2r-yxun t:meta.view.owner v:id=uaqq-pakk v:screenName="Douglas Oshiro" v:displayName="Douglas Oshiro"

property e:qs2r-yxun t:meta.view.tableauthor v:id=uaqq-pakk v:screenName="Douglas Oshiro" v:displayName="Douglas Oshiro"
```

## Top Records

```ls
| x_values | hawaii_electricity_consumption | 
| ======== | ============================== | 
| 1960     | 1285                           | 
| 1961     | 1554                           | 
| 1962     | 1820                           | 
| 1963     | 2080                           | 
| 1964     | 2286                           | 
| 1965     | 2452                           | 
| 1966     | 2642                           | 
| 1967     | 2720                           | 
| 1968     | 3132                           | 
| 1969     | 3446                           | 
```