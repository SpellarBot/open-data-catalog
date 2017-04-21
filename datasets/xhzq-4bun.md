# UNEMPLOYMENT RATE - MAUI County - Monthly - Not Seasonally Adjusted

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/unemployment-rate-maui-county-monthly-not-seasonally-adjusted-1b83a) |
| Metadata | [Link](https://data.hawaii.gov/api/views/xhzq-4bun) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/xhzq-4bun/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/xhzq-4bun/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | xhzq-4bun |
| Name | UNEMPLOYMENT RATE - MAUI County - Monthly - Not Seasonally Adjusted |
| Attribution | DLIR R&S |
| Category | Employment |
| Tags | unemployment, unemployment rate, employed, unemployed, maui, county, monthly |
| Created | 2013-10-17T02:24:31Z |
| Publication Date | 2014-04-25T01:08:56Z |

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type     | Render Type   |
| ======== | ============== | ==================== | ==================== | ============= | ============= |
| Yes      | time           | month_year           | Month/Year           | calendar_date | calendar_date |
| Yes      | series tag     | notes                | Notes                | text          | text          |
| Yes      | numeric metric | civilian_labor_force | Civilian Labor Force | number        | number        |
| Yes      | numeric metric | employed             | Employed             | number        | number        |
| Yes      | numeric metric | unemployed           | Unemployed           | number        | number        |
| Yes      | numeric metric | unemployment_rate    | Unemployment Rate    | number        | number        |
```

## Time Field

```ls
Value = month_year
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:xhzq-4bun d:1990-01-01T00:00:00.000Z m:unemployed=2250 m:unemployment_rate=4 m:civilian_labor_force=55750 m:employed=53500

series e:xhzq-4bun d:1990-02-01T00:00:00.000Z m:unemployed=2050 m:unemployment_rate=3.7 m:civilian_labor_force=55600 m:employed=53550

series e:xhzq-4bun d:1990-03-01T00:00:00.000Z m:unemployed=2150 m:unemployment_rate=3.8 m:civilian_labor_force=56000 m:employed=53850
```

## Meta Commands

```ls
metric m:civilian_labor_force p:integer l:"Civilian Labor Force" t:dataTypeName=number

metric m:employed p:integer l:Employed t:dataTypeName=number

metric m:unemployed p:integer l:Unemployed t:dataTypeName=number

metric m:unemployment_rate p:float l:"Unemployment Rate" t:dataTypeName=number

entity e:xhzq-4bun l:"UNEMPLOYMENT RATE - MAUI County - Monthly - Not Seasonally Adjusted" t:attribution="DLIR R&S" t:url=https://data.hawaii.gov/api/views/xhzq-4bun

property e:xhzq-4bun t:meta.view v:id=xhzq-4bun v:category=Employment v:averageRating=0 v:name="UNEMPLOYMENT RATE - MAUI County - Monthly - Not Seasonally Adjusted" v:attribution="DLIR R&S"

property e:xhzq-4bun t:meta.view.owner v:id=5ibs-8u6a v:profileImageUrlMedium=/api/users/5ibs-8u6a/profile_images/THUMB v:profileImageUrlLarge=/api/users/5ibs-8u6a/profile_images/LARGE v:screenName=Bill v:profileImageUrlSmall=/api/users/5ibs-8u6a/profile_images/TINY v:displayName=Bill

property e:xhzq-4bun t:meta.view.tableauthor v:id=5ibs-8u6a v:profileImageUrlMedium=/api/users/5ibs-8u6a/profile_images/THUMB v:profileImageUrlLarge=/api/users/5ibs-8u6a/profile_images/LARGE v:screenName=Bill v:profileImageUrlSmall=/api/users/5ibs-8u6a/profile_images/TINY v:roleName=editor v:displayName=Bill
```

## Top Records

```ls
| month_year          | notes | civilian_labor_force | employed | unemployed | unemployment_rate | 
| =================== | ===== | ==================== | ======== | ========== | ================= | 
| 1990-01-01T00:00:00 |       | 55750                | 53500    | 2250       | 4.0               | 
| 1990-02-01T00:00:00 |       | 55600                | 53550    | 2050       | 3.7               | 
| 1990-03-01T00:00:00 |       | 56000                | 53850    | 2150       | 3.8               | 
| 1990-04-01T00:00:00 |       | 56900                | 54750    | 2150       | 3.8               | 
| 1990-05-01T00:00:00 |       | 56950                | 54600    | 2350       | 4.1               | 
| 1990-06-01T00:00:00 |       | 59150                | 55800    | 3300       | 5.6               | 
| 1990-07-01T00:00:00 |       | 59650                | 56950    | 2750       | 4.6               | 
| 1990-08-01T00:00:00 |       | 58950                | 56550    | 2450       | 4.1               | 
| 1990-09-01T00:00:00 |       | 57700                | 54800    | 2950       | 5.1               | 
| 1990-10-01T00:00:00 |       | 57300                | 54950    | 2350       | 4.1               | 
```