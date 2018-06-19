# UNEMPLOYMENT RATE - STATE OF HAWAII - Monthly - Seasonally Adjusted

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/unemployment-rate-state-of-hawaii-monthly-seasonally-adjusted-44eca) |
| Metadata | [Link](https://data.hawaii.gov/api/views/qxej-k2af) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/qxej-k2af/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/qxej-k2af/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | qxej-k2af |
| Name | UNEMPLOYMENT RATE - STATE OF HAWAII - Monthly - Seasonally Adjusted |
| Attribution | DLIR R&S |
| Category | Employment |
| Tags | unemployment, unemployment rate, employed, unemployed, state, hawaii, monthly |
| Created | 2013-10-17T02:04:16Z |
| Publication Date | 2014-04-24T02:22:03Z |

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
series e:qxej-k2af d:1976-01-01T00:00:00.000Z m:unemployed=40400 m:unemployment_rate=9.9 m:civilian_labor_force=406000 m:employed=365600

series e:qxej-k2af d:1976-02-01T00:00:00.000Z m:unemployed=39900 m:unemployment_rate=9.8 m:civilian_labor_force=406700 m:employed=366800

series e:qxej-k2af d:1976-03-01T00:00:00.000Z m:unemployed=39300 m:unemployment_rate=9.6 m:civilian_labor_force=407650 m:employed=368300
```

## Meta Commands

```ls
metric m:civilian_labor_force p:integer l:"Civilian Labor Force" t:dataTypeName=number

metric m:employed p:integer l:Employed t:dataTypeName=number

metric m:unemployed p:integer l:Unemployed t:dataTypeName=number

metric m:unemployment_rate p:float l:"Unemployment Rate" t:dataTypeName=percent

entity e:qxej-k2af l:"UNEMPLOYMENT RATE - STATE OF HAWAII - Monthly - Seasonally Adjusted" t:attribution="DLIR R&S" t:url=https://data.hawaii.gov/api/views/qxej-k2af

property e:qxej-k2af t:meta.view v:id=qxej-k2af v:category=Employment v:averageRating=0 v:name="UNEMPLOYMENT RATE - STATE OF HAWAII - Monthly - Seasonally Adjusted" v:attribution="DLIR R&S"

property e:qxej-k2af t:meta.view.owner v:id=5ibs-8u6a v:profileImageUrlMedium=/api/users/5ibs-8u6a/profile_images/THUMB v:profileImageUrlLarge=/api/users/5ibs-8u6a/profile_images/LARGE v:screenName=Bill v:profileImageUrlSmall=/api/users/5ibs-8u6a/profile_images/TINY v:displayName=Bill

property e:qxej-k2af t:meta.view.tableauthor v:id=5ibs-8u6a v:profileImageUrlMedium=/api/users/5ibs-8u6a/profile_images/THUMB v:profileImageUrlLarge=/api/users/5ibs-8u6a/profile_images/LARGE v:screenName=Bill v:profileImageUrlSmall=/api/users/5ibs-8u6a/profile_images/TINY v:roleName=editor v:displayName=Bill
```

## Top Records

```ls
| month_year          | notes | civilian_labor_force | employed | unemployed | unemployment_rate | 
| =================== | ===== | ==================== | ======== | ========== | ================= | 
| 1976-01-01T00:00:00 |       | 406000               | 365600   | 40400      | 9.9               | 
| 1976-02-01T00:00:00 |       | 406700               | 366800   | 39900      | 9.8               | 
| 1976-03-01T00:00:00 |       | 407650               | 368300   | 39300      | 9.6               | 
| 1976-04-01T00:00:00 |       | 408650               | 370050   | 38600      | 9.4               | 
| 1976-05-01T00:00:00 |       | 409650               | 371850   | 37800      | 9.2               | 
| 1976-06-01T00:00:00 |       | 410550               | 373450   | 37100      | 9.0               | 
| 1976-07-01T00:00:00 |       | 411250               | 374700   | 36550      | 8.9               | 
| 1976-08-01T00:00:00 |       | 411650               | 375500   | 36150      | 8.8               | 
| 1976-09-01T00:00:00 |       | 411950               | 376050   | 35900      | 8.7               | 
| 1976-10-01T00:00:00 |       | 412250               | 376500   | 35750      | 8.7               | 
```