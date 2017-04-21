# UNEMPLOYMENT RATE - MAUI County - Annual - Not Seasonally Adjusted

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/unemployment-rate-maui-county-annual-not-seasonally-adjusted-eebda) |
| Metadata | [Link](https://data.hawaii.gov/api/views/gydz-g9uw) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/gydz-g9uw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/gydz-g9uw/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | gydz-g9uw |
| Name | UNEMPLOYMENT RATE - MAUI County - Annual - Not Seasonally Adjusted |
| Attribution | DLIR R&S |
| Category | Employment |
| Tags | unemployment, unemployment rate, employed, unemployed, maui, county, annual |
| Created | 2013-10-17T02:42:38Z |
| Publication Date | 2014-04-25T01:06:43Z |

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
series e:gydz-g9uw d:1990-01-01T00:00:00.000Z m:unemployed=2400 m:unemployment_rate=4.2 m:civilian_labor_force=57300 m:employed=54900

series e:gydz-g9uw d:1991-01-01T00:00:00.000Z m:unemployed=3250 m:unemployment_rate=5.4 m:civilian_labor_force=60350 m:employed=57100

series e:gydz-g9uw d:1992-01-01T00:00:00.000Z m:unemployed=5200 m:unemployment_rate=8 m:civilian_labor_force=64800 m:employed=59600
```

## Meta Commands

```ls
metric m:civilian_labor_force p:integer l:"Civilian Labor Force" t:dataTypeName=number

metric m:employed p:integer l:Employed t:dataTypeName=number

metric m:unemployed p:integer l:Unemployed t:dataTypeName=number

metric m:unemployment_rate p:float l:"Unemployment Rate" t:dataTypeName=number

entity e:gydz-g9uw l:"UNEMPLOYMENT RATE - MAUI County - Annual - Not Seasonally Adjusted" t:attribution="DLIR R&S" t:url=https://data.hawaii.gov/api/views/gydz-g9uw

property e:gydz-g9uw t:meta.view v:id=gydz-g9uw v:category=Employment v:averageRating=0 v:name="UNEMPLOYMENT RATE - MAUI County - Annual - Not Seasonally Adjusted" v:attribution="DLIR R&S"

property e:gydz-g9uw t:meta.view.owner v:id=5ibs-8u6a v:profileImageUrlMedium=/api/users/5ibs-8u6a/profile_images/THUMB v:profileImageUrlLarge=/api/users/5ibs-8u6a/profile_images/LARGE v:screenName=Bill v:profileImageUrlSmall=/api/users/5ibs-8u6a/profile_images/TINY v:displayName=Bill

property e:gydz-g9uw t:meta.view.tableauthor v:id=5ibs-8u6a v:profileImageUrlMedium=/api/users/5ibs-8u6a/profile_images/THUMB v:profileImageUrlLarge=/api/users/5ibs-8u6a/profile_images/LARGE v:screenName=Bill v:profileImageUrlSmall=/api/users/5ibs-8u6a/profile_images/TINY v:roleName=editor v:displayName=Bill
```

## Top Records

```ls
| year                | notes | civilian_labor_force | employed | unemployed | unemployment_rate | 
| =================== | ===== | ==================== | ======== | ========== | ================= | 
| 1990-01-01T00:00:00 |       | 57300                | 54900    | 2400       | 4.2               | 
| 1991-01-01T00:00:00 |       | 60350                | 57100    | 3250       | 5.4               | 
| 1992-01-01T00:00:00 |       | 64800                | 59600    | 5200       | 8.0               | 
| 1993-01-01T00:00:00 |       | 65500                | 62000    | 3500       | 5.4               | 
| 1994-01-01T00:00:00 |       | 66350                | 62500    | 3850       | 5.8               | 
| 1995-01-01T00:00:00 |       | 67250                | 62600    | 4600       | 6.9               | 
| 1996-01-01T00:00:00 |       | 68350                | 63750    | 4600       | 6.7               | 
| 1997-01-01T00:00:00 |       | 69950                | 65200    | 4750       | 6.8               | 
| 1998-01-01T00:00:00 |       | 71100                | 66700    | 4350       | 6.2               | 
| 1999-01-01T00:00:00 |       | 73050                | 69350    | 3700       | 5.1               | 
```