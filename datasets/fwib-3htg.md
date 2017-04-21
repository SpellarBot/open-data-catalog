# UNEMPLOYMENT RATE - HAWAII County - Monthly - Not Seasonally Adjusted

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/unemployment-rate-hawaii-county-monthly-not-seasonally-adjusted-5c294) |
| Metadata | [Link](https://data.hawaii.gov/api/views/fwib-3htg) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/fwib-3htg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/fwib-3htg/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | fwib-3htg |
| Name | UNEMPLOYMENT RATE - HAWAII County - Monthly - Not Seasonally Adjusted |
| Attribution | DLIR |
| Category | Employment |
| Tags | unemployment, unemployment rate, employed, unemployed, hawaii, county, monthly |
| Created | 2013-10-17T02:20:08Z |
| Publication Date | 2014-04-24T02:15:05Z |

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
series e:fwib-3htg d:1990-01-01T00:00:00.000Z m:unemployed=1900 m:unemployment_rate=3.4 m:civilian_labor_force=57150 m:employed=55200

series e:fwib-3htg d:1990-02-01T00:00:00.000Z m:unemployed=1950 m:unemployment_rate=3.4 m:civilian_labor_force=56750 m:employed=54850

series e:fwib-3htg d:1990-03-01T00:00:00.000Z m:unemployed=2150 m:unemployment_rate=3.7 m:civilian_labor_force=56850 m:employed=54750
```

## Meta Commands

```ls
metric m:civilian_labor_force p:integer l:"Civilian Labor Force" t:dataTypeName=number

metric m:employed p:integer l:Employed t:dataTypeName=number

metric m:unemployed p:integer l:Unemployed t:dataTypeName=number

metric m:unemployment_rate p:float l:"Unemployment Rate" t:dataTypeName=number

entity e:fwib-3htg l:"UNEMPLOYMENT RATE - HAWAII County - Monthly - Not Seasonally Adjusted" t:attribution=DLIR t:url=https://data.hawaii.gov/api/views/fwib-3htg

property e:fwib-3htg t:meta.view v:id=fwib-3htg v:category=Employment v:averageRating=0 v:name="UNEMPLOYMENT RATE - HAWAII County - Monthly - Not Seasonally Adjusted" v:attribution=DLIR

property e:fwib-3htg t:meta.view.owner v:id=5ibs-8u6a v:profileImageUrlMedium=/api/users/5ibs-8u6a/profile_images/THUMB v:profileImageUrlLarge=/api/users/5ibs-8u6a/profile_images/LARGE v:screenName=Bill v:profileImageUrlSmall=/api/users/5ibs-8u6a/profile_images/TINY v:displayName=Bill

property e:fwib-3htg t:meta.view.tableauthor v:id=5ibs-8u6a v:profileImageUrlMedium=/api/users/5ibs-8u6a/profile_images/THUMB v:profileImageUrlLarge=/api/users/5ibs-8u6a/profile_images/LARGE v:screenName=Bill v:profileImageUrlSmall=/api/users/5ibs-8u6a/profile_images/TINY v:roleName=editor v:displayName=Bill
```

## Top Records

```ls
| month_year          | notes | civilian_labor_force | employed | unemployed | unemployment_rate | 
| =================== | ===== | ==================== | ======== | ========== | ================= | 
| 1990-01-01T00:00:00 |       | 57150                | 55200    | 1900       | 3.4               | 
| 1990-02-01T00:00:00 |       | 56750                | 54850    | 1950       | 3.4               | 
| 1990-03-01T00:00:00 |       | 56850                | 54750    | 2150       | 3.7               | 
| 1990-04-01T00:00:00 |       | 58000                | 55550    | 2450       | 4.2               | 
| 1990-05-01T00:00:00 |       | 58250                | 55750    | 2500       | 4.3               | 
| 1990-06-01T00:00:00 |       | 59000                | 56350    | 2650       | 4.5               | 
| 1990-07-01T00:00:00 |       | 60250                | 57950    | 2350       | 3.9               | 
| 1990-08-01T00:00:00 |       | 59600                | 57650    | 1950       | 3.3               | 
| 1990-09-01T00:00:00 |       | 58350                | 56250    | 2100       | 3.6               | 
| 1990-10-01T00:00:00 |       | 58000                | 56350    | 1650       | 2.8               | 
```