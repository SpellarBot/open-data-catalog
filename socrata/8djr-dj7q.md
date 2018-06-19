# UNEMPLOYMENT RATE - HONOLULU - Monthly - Not Seasonally Adjusted

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/unemployment-rate-honolulu-monthly-not-seasonally-adjusted-d3d14) |
| Metadata | [Link](https://data.hawaii.gov/api/views/8djr-dj7q) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/8djr-dj7q/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/8djr-dj7q/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | 8djr-dj7q |
| Name | UNEMPLOYMENT RATE - HONOLULU - Monthly - Not Seasonally Adjusted |
| Attribution | DLIR R&S |
| Category | Employment |
| Tags | unemployment, unemployment rate, employed, unemployed, honolulu, oahu, monthly |
| Created | 2013-10-17T02:17:37Z |
| Publication Date | 2014-04-24T02:17:17Z |

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
series e:8djr-dj7q d:1990-01-01T00:00:00.000Z m:unemployed=8000 m:unemployment_rate=2 m:civilian_labor_force=406500 m:employed=398450

series e:8djr-dj7q d:1990-02-01T00:00:00.000Z m:unemployed=7150 m:unemployment_rate=1.8 m:civilian_labor_force=406350 m:employed=399200

series e:8djr-dj7q d:1990-03-01T00:00:00.000Z m:unemployed=7450 m:unemployment_rate=1.8 m:civilian_labor_force=409550 m:employed=402100
```

## Meta Commands

```ls
metric m:civilian_labor_force p:integer l:"Civilian Labor Force" t:dataTypeName=number

metric m:employed p:integer l:Employed t:dataTypeName=number

metric m:unemployed p:integer l:Unemployed t:dataTypeName=number

metric m:unemployment_rate p:float l:"Unemployment Rate" t:dataTypeName=number

entity e:8djr-dj7q l:"UNEMPLOYMENT RATE - HONOLULU - Monthly - Not Seasonally Adjusted" t:attribution="DLIR R&S" t:url=https://data.hawaii.gov/api/views/8djr-dj7q

property e:8djr-dj7q t:meta.view v:id=8djr-dj7q v:category=Employment v:averageRating=0 v:name="UNEMPLOYMENT RATE - HONOLULU - Monthly - Not Seasonally Adjusted" v:attribution="DLIR R&S"

property e:8djr-dj7q t:meta.view.owner v:id=5ibs-8u6a v:profileImageUrlMedium=/api/users/5ibs-8u6a/profile_images/THUMB v:profileImageUrlLarge=/api/users/5ibs-8u6a/profile_images/LARGE v:screenName=Bill v:profileImageUrlSmall=/api/users/5ibs-8u6a/profile_images/TINY v:displayName=Bill

property e:8djr-dj7q t:meta.view.tableauthor v:id=5ibs-8u6a v:profileImageUrlMedium=/api/users/5ibs-8u6a/profile_images/THUMB v:profileImageUrlLarge=/api/users/5ibs-8u6a/profile_images/LARGE v:screenName=Bill v:profileImageUrlSmall=/api/users/5ibs-8u6a/profile_images/TINY v:roleName=editor v:displayName=Bill
```

## Top Records

```ls
| month_year          | notes | civilian_labor_force | employed | unemployed | unemployment_rate | 
| =================== | ===== | ==================== | ======== | ========== | ================= | 
| 1990-01-01T00:00:00 |       | 406500               | 398450   | 8000       | 2.0               | 
| 1990-02-01T00:00:00 |       | 406350               | 399200   | 7150       | 1.8               | 
| 1990-03-01T00:00:00 |       | 409550               | 402100   | 7450       | 1.8               | 
| 1990-04-01T00:00:00 |       | 410100               | 402450   | 7650       | 1.9               | 
| 1990-05-01T00:00:00 |       | 411100               | 403200   | 7850       | 1.9               | 
| 1990-06-01T00:00:00 |       | 413400               | 403400   | 10000      | 2.4               | 
| 1990-07-01T00:00:00 |       | 414650               | 406050   | 8600       | 2.1               | 
| 1990-08-01T00:00:00 |       | 412000               | 403900   | 8100       | 2.0               | 
| 1990-09-01T00:00:00 |       | 401150               | 391900   | 9200       | 2.3               | 
| 1990-10-01T00:00:00 |       | 405500               | 397850   | 7650       | 1.9               | 
```