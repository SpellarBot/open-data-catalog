# UNEMPLOYMENT RATE - HONOLULU - Monthly - Seasonally Adjusted

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/unemployment-rate-honolulu-monthly-seasonally-adjusted-df271) |
| Metadata | [Link](https://data.hawaii.gov/api/views/8hbh-6di9) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/8hbh-6di9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/8hbh-6di9/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | 8hbh-6di9 |
| Name | UNEMPLOYMENT RATE - HONOLULU - Monthly - Seasonally Adjusted |
| Attribution | DLIR R&S |
| Category | Employment |
| Tags | unemployment, unemployment rate, employed, unemployed, honolulu, oahu, monthly |
| Created | 2013-10-17T02:06:48Z |
| Publication Date | 2014-03-26T00:53:44Z |

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type     | Render Type   |
| ======== | ============== | ==================== | ==================== | ============= | ============= |
| Yes      | time           | month_year           | Month/Year           | calendar_date | calendar_date |
| Yes      | series tag     | notes                | Notes                | text          | text          |
| Yes      | numeric metric | civilian_labor_force | Civilian Labor Force | number        | number        |
| Yes      | numeric metric | employed             | Employed             | number        | number        |
| Yes      | numeric metric | unemployed           | Unemployed           | number        | number        |
| Yes      | numeric metric | unemployment_rate    | Unemployment Rate    | percent       | percent       |
```

## Time Field

```ls
Value = month_year
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:8hbh-6di9 d:2000-01-01T00:00:00.000Z m:unemployed=17550 m:unemployment_rate=4 m:civilian_labor_force=433850 m:employed=416300

series e:8hbh-6di9 d:2000-02-01T00:00:00.000Z m:unemployed=17350 m:unemployment_rate=4 m:civilian_labor_force=433750 m:employed=416400

series e:8hbh-6di9 d:2000-03-01T00:00:00.000Z m:unemployed=17200 m:unemployment_rate=4 m:civilian_labor_force=433700 m:employed=416500
```

## Meta Commands

```ls
metric m:civilian_labor_force p:integer l:"Civilian Labor Force" t:dataTypeName=number

metric m:employed p:integer l:Employed t:dataTypeName=number

metric m:unemployed p:integer l:Unemployed t:dataTypeName=number

metric m:unemployment_rate p:float l:"Unemployment Rate" t:dataTypeName=percent

entity e:8hbh-6di9 l:"UNEMPLOYMENT RATE - HONOLULU - Monthly - Seasonally Adjusted" t:attribution="DLIR R&S" t:url=https://data.hawaii.gov/api/views/8hbh-6di9

property e:8hbh-6di9 t:meta.view v:id=8hbh-6di9 v:category=Employment v:averageRating=0 v:name="UNEMPLOYMENT RATE - HONOLULU - Monthly - Seasonally Adjusted" v:attribution="DLIR R&S"

property e:8hbh-6di9 t:meta.view.owner v:id=5ibs-8u6a v:profileImageUrlMedium=/api/users/5ibs-8u6a/profile_images/THUMB v:profileImageUrlLarge=/api/users/5ibs-8u6a/profile_images/LARGE v:screenName=Bill v:profileImageUrlSmall=/api/users/5ibs-8u6a/profile_images/TINY v:displayName=Bill

property e:8hbh-6di9 t:meta.view.tableauthor v:id=5ibs-8u6a v:profileImageUrlMedium=/api/users/5ibs-8u6a/profile_images/THUMB v:profileImageUrlLarge=/api/users/5ibs-8u6a/profile_images/LARGE v:screenName=Bill v:profileImageUrlSmall=/api/users/5ibs-8u6a/profile_images/TINY v:roleName=editor v:displayName=Bill
```

## Top Records

```ls
| month_year          | notes | civilian_labor_force | employed | unemployed | unemployment_rate | 
| =================== | ===== | ==================== | ======== | ========== | ================= | 
| 2000-01-01T00:00:00 |       | 433850               | 416300   | 17550      | 4.0               | 
| 2000-02-01T00:00:00 |       | 433750               | 416400   | 17350      | 4.0               | 
| 2000-03-01T00:00:00 |       | 433700               | 416500   | 17200      | 4.0               | 
| 2000-04-01T00:00:00 |       | 433600               | 416500   | 17100      | 3.9               | 
| 2000-05-01T00:00:00 |       | 433450               | 416400   | 17000      | 3.9               | 
| 2000-06-01T00:00:00 |       | 433200               | 416200   | 17000      | 3.9               | 
| 2000-07-01T00:00:00 |       | 432900               | 416000   | 16900      | 3.9               | 
| 2000-08-01T00:00:00 |       | 432550               | 415900   | 16700      | 3.9               | 
| 2000-09-01T00:00:00 |       | 432350               | 416050   | 16350      | 3.8               | 
| 2000-10-01T00:00:00 |       | 432400               | 416450   | 15950      | 3.7               | 
```