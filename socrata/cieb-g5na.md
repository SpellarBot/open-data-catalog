# UNEMPLOYMENT RATE - KAUAI County - Monthly - Not Seasonally Adjusted

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/unemployment-rate-kauai-county-monthly-not-seasonally-adjusted-05c33) |
| Metadata | [Link](https://data.hawaii.gov/api/views/cieb-g5na) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/cieb-g5na/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/cieb-g5na/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | cieb-g5na |
| Name | UNEMPLOYMENT RATE - KAUAI County - Monthly - Not Seasonally Adjusted |
| Attribution | DLIR R&S |
| Category | Employment |
| Tags | unemployment, unemployment rate, employed, unemployed, kauai, county, monthly |
| Created | 2013-10-17T02:22:19Z |
| Publication Date | 2014-04-24T02:18:39Z |

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
series e:cieb-g5na d:1990-01-01T00:00:00.000Z m:unemployed=1050 m:unemployment_rate=3.9 m:civilian_labor_force=26400 m:employed=25400

series e:cieb-g5na d:1990-02-01T00:00:00.000Z m:unemployed=950 m:unemployment_rate=3.6 m:civilian_labor_force=26200 m:employed=25300

series e:cieb-g5na d:1990-03-01T00:00:00.000Z m:unemployed=1000 m:unemployment_rate=3.9 m:civilian_labor_force=26100 m:employed=25050
```

## Meta Commands

```ls
metric m:civilian_labor_force p:integer l:"Civilian Labor Force" t:dataTypeName=number

metric m:employed p:integer l:Employed t:dataTypeName=number

metric m:unemployed p:integer l:Unemployed t:dataTypeName=number

metric m:unemployment_rate p:float l:"Unemployment Rate" t:dataTypeName=number

entity e:cieb-g5na l:"UNEMPLOYMENT RATE - KAUAI County - Monthly - Not Seasonally Adjusted" t:attribution="DLIR R&S" t:url=https://data.hawaii.gov/api/views/cieb-g5na

property e:cieb-g5na t:meta.view v:id=cieb-g5na v:category=Employment v:averageRating=0 v:name="UNEMPLOYMENT RATE - KAUAI County - Monthly - Not Seasonally Adjusted" v:attribution="DLIR R&S"

property e:cieb-g5na t:meta.view.owner v:id=5ibs-8u6a v:profileImageUrlMedium=/api/users/5ibs-8u6a/profile_images/THUMB v:profileImageUrlLarge=/api/users/5ibs-8u6a/profile_images/LARGE v:screenName=Bill v:profileImageUrlSmall=/api/users/5ibs-8u6a/profile_images/TINY v:displayName=Bill

property e:cieb-g5na t:meta.view.tableauthor v:id=5ibs-8u6a v:profileImageUrlMedium=/api/users/5ibs-8u6a/profile_images/THUMB v:profileImageUrlLarge=/api/users/5ibs-8u6a/profile_images/LARGE v:screenName=Bill v:profileImageUrlSmall=/api/users/5ibs-8u6a/profile_images/TINY v:roleName=editor v:displayName=Bill
```

## Top Records

```ls
| month_year          | notes | civilian_labor_force | employed | unemployed | unemployment_rate | 
| =================== | ===== | ==================== | ======== | ========== | ================= | 
| 1990-01-01T00:00:00 |       | 26400                | 25400    | 1050       | 3.9               | 
| 1990-02-01T00:00:00 |       | 26200                | 25300    | 950        | 3.6               | 
| 1990-03-01T00:00:00 |       | 26100                | 25050    | 1000       | 3.9               | 
| 1990-04-01T00:00:00 |       | 25950                | 24900    | 1050       | 4.0               | 
| 1990-05-01T00:00:00 |       | 25800                | 24850    | 950        | 3.7               | 
| 1990-06-01T00:00:00 |       | 26150                | 25000    | 1150       | 4.4               | 
| 1990-07-01T00:00:00 |       | 26300                | 25250    | 1100       | 4.1               | 
| 1990-08-01T00:00:00 |       | 26200                | 25300    | 850        | 3.3               | 
| 1990-09-01T00:00:00 |       | 25550                | 24600    | 1000       | 3.8               | 
| 1990-10-01T00:00:00 |       | 25800                | 25050    | 750        | 3.0               | 
```