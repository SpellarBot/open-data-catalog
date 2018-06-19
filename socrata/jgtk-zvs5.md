# UNEMPLOYMENT RATE - HONOLULU - Annual - Not Seasonally Adjusted

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/unemployment-rate-honolulu-annual-not-seasonally-adjusted-868e3) |
| Metadata | [Link](https://data.hawaii.gov/api/views/jgtk-zvs5) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/jgtk-zvs5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/jgtk-zvs5/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | jgtk-zvs5 |
| Name | UNEMPLOYMENT RATE - HONOLULU - Annual - Not Seasonally Adjusted |
| Attribution | DLIR R&S |
| Category | Employment |
| Tags | unemployment, unemployment rate, employed, unemployed, honolulu, oahu, county, annual |
| Created | 2013-10-17T02:34:52Z |
| Publication Date | 2014-04-24T02:16:40Z |

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type     | Render Type   |
| ======== | ============== | ==================== | ==================== | ============= | ============= |
| Yes      | time           | year                 | Year                 | calendar_date | calendar_date |
| Yes      | series tag     | notes                | Notes                | text          | text          |
| Yes      | numeric metric | civilian_labor_force | Civilian Labor Force | number        | number        |
| Yes      | numeric metric | employed             | Employed             | number        | number        |
| Yes      | numeric metric | unemployed           | Unemployed           | number        | number        |
| Yes      | numeric metric | unemployment_rate    | Unemployment Rate    | number        | number        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:jgtk-zvs5 d:1990-01-01T00:00:00.000Z m:unemployed=8000 m:unemployment_rate=2 m:civilian_labor_force=409250 m:employed=401250

series e:jgtk-zvs5 d:1991-01-01T00:00:00.000Z m:unemployed=8450 m:unemployment_rate=2 m:civilian_labor_force=412000 m:employed=403600

series e:jgtk-zvs5 d:1992-01-01T00:00:00.000Z m:unemployed=11600 m:unemployment_rate=2.8 m:civilian_labor_force=418000 m:employed=406400
```

## Meta Commands

```ls
metric m:civilian_labor_force p:integer l:"Civilian Labor Force" t:dataTypeName=number

metric m:employed p:integer l:Employed t:dataTypeName=number

metric m:unemployed p:integer l:Unemployed t:dataTypeName=number

metric m:unemployment_rate p:float l:"Unemployment Rate" t:dataTypeName=number

entity e:jgtk-zvs5 l:"UNEMPLOYMENT RATE - HONOLULU - Annual - Not Seasonally Adjusted" t:attribution="DLIR R&S" t:url=https://data.hawaii.gov/api/views/jgtk-zvs5

property e:jgtk-zvs5 t:meta.view v:id=jgtk-zvs5 v:category=Employment v:averageRating=0 v:name="UNEMPLOYMENT RATE - HONOLULU - Annual - Not Seasonally Adjusted" v:attribution="DLIR R&S"

property e:jgtk-zvs5 t:meta.view.owner v:id=5ibs-8u6a v:profileImageUrlMedium=/api/users/5ibs-8u6a/profile_images/THUMB v:profileImageUrlLarge=/api/users/5ibs-8u6a/profile_images/LARGE v:screenName=Bill v:profileImageUrlSmall=/api/users/5ibs-8u6a/profile_images/TINY v:displayName=Bill

property e:jgtk-zvs5 t:meta.view.tableauthor v:id=5ibs-8u6a v:profileImageUrlMedium=/api/users/5ibs-8u6a/profile_images/THUMB v:profileImageUrlLarge=/api/users/5ibs-8u6a/profile_images/LARGE v:screenName=Bill v:profileImageUrlSmall=/api/users/5ibs-8u6a/profile_images/TINY v:roleName=editor v:displayName=Bill
```

## Top Records

```ls
| year                | notes | civilian_labor_force | employed | unemployed | unemployment_rate | 
| =================== | ===== | ==================== | ======== | ========== | ================= | 
| 1990-01-01T00:00:00 |       | 409250               | 401250   | 8000       | 2.0               | 
| 1991-01-01T00:00:00 |       | 412000               | 403600   | 8450       | 2.0               | 
| 1992-01-01T00:00:00 |       | 418000               | 406400   | 11600      | 2.8               | 
| 1993-01-01T00:00:00 |       | 423200               | 409900   | 13300      | 3.1               | 
| 1994-01-01T00:00:00 |       | 425450               | 408750   | 16700      | 3.9               | 
| 1995-01-01T00:00:00 |       | 428000               | 409550   | 18450      | 4.3               | 
| 1996-01-01T00:00:00 |       | 432000               | 411000   | 21000      | 4.9               | 
| 1997-01-01T00:00:00 |       | 433600               | 412800   | 20750      | 4.8               | 
| 1998-01-01T00:00:00 |       | 434700               | 413600   | 21100      | 4.9               | 
| 1999-01-01T00:00:00 |       | 433350               | 414300   | 19050      | 4.4               | 
```