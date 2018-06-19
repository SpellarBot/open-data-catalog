# Statistics,Major Crimes, 2014, by Precinct and Beat

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/statisticsmajor-crimes-2014-by-precinct-and-beat) |
| Metadata | [Link](https://data.seattle.gov/api/views/88ys-gyb4) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/88ys-gyb4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/88ys-gyb4/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | 88ys-gyb4 |
| Name | Statistics,Major Crimes, 2014, by Precinct and Beat |
| Attribution | Seattle Police Department |
| Category | Public Safety |
| Tags | statistics., seattle, spd, 2014, major, crime, violent, property, vehicle, stolen, theft, homicide, rape, larceny, assault, burglary |
| Created | 2015-04-07T21:39:55Z |
| Publication Date | 2015-04-07T22:00:14Z |

## Description

2014 major crime statistics by precinct and beat.

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type     | Render Type   |
| ======== | ============== | ===================== | ===================== | ============= | ============= |
| Yes      | series tag     | precinct              | PRECINCT              | text          | text          |
| Yes      | series tag     | beat                  | BEAT                  | text          | text          |
| Yes      | numeric metric | homicide              | HOMICIDE              | number        | number        |
| Yes      | numeric metric | rape                  | RAPE                  | number        | number        |
| Yes      | numeric metric | robbery               | ROBBERY               | number        | number        |
| Yes      | numeric metric | assault               | ASSAULT               | number        | number        |
| Yes      | numeric metric | violent_crimes_total  | VIOLENT_CRIMES_TOTAL  | number        | number        |
| Yes      | numeric metric | burglary              | BURGLARY              | number        | number        |
| Yes      | numeric metric | larceny_theft         | LARCENY_THEFT         | number        | number        |
| Yes      | numeric metric | vehicle_theft         | VEHICLE_THEFT         | number        | number        |
| Yes      | numeric metric | property_crimes_total | PROPERTY_CRIMES_TOTAL | number        | number        |
| Yes      | numeric metric | major_crimes_total    | MAJOR_CRIMES_TOTAL    | number        | number        |
| Yes      | time           | report_date           | REPORT_DATE           | calendar_date | calendar_date |
```

## Time Field

```ls
Value = report_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:88ys-gyb4 d:2014-01-31T00:00:00.000Z t:precinct=CITYWIDE m:homicide=1 m:larceny_theft=1965 m:robbery=129 m:vehicle_theft=443 m:property_crimes_total=3055 m:burglary=647 m:assault=187 m:major_crimes_total=3242 m:violent_crimes_total=325 m:rape=8

series e:88ys-gyb4 d:2014-01-31T00:00:00.000Z t:precinct=UNKNOWN m:homicide=0 m:larceny_theft=6 m:robbery=0 m:vehicle_theft=0 m:property_crimes_total=7 m:burglary=1 m:assault=7 m:major_crimes_total=14 m:violent_crimes_total=7 m:rape=0

series e:88ys-gyb4 d:2014-01-31T00:00:00.000Z t:precinct=NORTH m:homicide=0 m:larceny_theft=627 m:robbery=17 m:vehicle_theft=151 m:property_crimes_total=1010 m:burglary=232 m:assault=36 m:major_crimes_total=1046 m:violent_crimes_total=53 m:rape=0
```

## Meta Commands

```ls
metric m:homicide p:integer l:HOMICIDE t:dataTypeName=number

metric m:rape p:integer l:RAPE t:dataTypeName=number

metric m:robbery p:integer l:ROBBERY t:dataTypeName=number

metric m:assault p:integer l:ASSAULT t:dataTypeName=number

metric m:violent_crimes_total p:integer l:VIOLENT_CRIMES_TOTAL t:dataTypeName=number

metric m:burglary p:integer l:BURGLARY t:dataTypeName=number

metric m:larceny_theft p:integer l:LARCENY_THEFT t:dataTypeName=number

metric m:vehicle_theft p:integer l:VEHICLE_THEFT t:dataTypeName=number

metric m:property_crimes_total p:integer l:PROPERTY_CRIMES_TOTAL t:dataTypeName=number

metric m:major_crimes_total p:integer l:MAJOR_CRIMES_TOTAL t:dataTypeName=number

entity e:88ys-gyb4 l:"Statistics,Major Crimes, 2014, by Precinct and Beat" t:attribution="Seattle Police Department" t:url=https://data.seattle.gov/api/views/88ys-gyb4

property e:88ys-gyb4 t:meta.view v:id=88ys-gyb4 v:category="Public Safety" v:attributionLink=http://www.seattle.gov/police/crime/stats.htm v:averageRating=0 v:name="Statistics,Major Crimes, 2014, by Precinct and Beat" v:attribution="Seattle Police Department"

property e:88ys-gyb4 t:meta.view.license v:name="Public Domain"

property e:88ys-gyb4 t:meta.view.owner v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:displayName="Seattle IT"

property e:88ys-gyb4 t:meta.view.tableauthor v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:roleName=administrator v:displayName="Seattle IT"
```

## Top Records

```ls
| precinct | beat | homicide | rape | robbery | assault | violent_crimes_total | burglary | larceny_theft | vehicle_theft | property_crimes_total | major_crimes_total | report_date         | 
| ======== | ==== | ======== | ==== | ======= | ======= | ==================== | ======== | ============= | ============= | ===================== | ================== | =================== | 
| CITYWIDE |      | 1        | 8    | 129     | 187     | 325                  | 647      | 1965          | 443           | 3055                  | 3242               | 2014-01-31T00:00:00 | 
| UNKNOWN  |      | 0        | 0    | 0       | 7       | 7                    | 1        | 6             | 0             | 7                     | 14                 | 2014-01-31T00:00:00 | 
| NORTH    |      | 0        | 0    | 17      | 36      | 53                   | 232      | 627           | 151           | 1010                  | 1046               | 2014-01-31T00:00:00 | 
| NORTH    | B1   | 0        | 0    | 2       | 0       | 2                    | 17       | 30            | 8             | 55                    | 55                 | 2014-01-31T00:00:00 | 
| NORTH    | B2   | 0        | 0    | 2       | 1       | 3                    | 7        | 35            | 4             | 46                    | 47                 | 2014-01-31T00:00:00 | 
| NORTH    | B3   | 0        | 0    | 1       | 1       | 2                    | 21       | 49            | 11            | 81                    | 82                 | 2014-01-31T00:00:00 | 
| NORTH    | J1   | 0        | 0    | 0       | 3       | 3                    | 8        | 51            | 8             | 67                    | 70                 | 2014-01-31T00:00:00 | 
| NORTH    | J2   | 0        | 0    | 1       | 5       | 6                    | 14       | 53            | 8             | 75                    | 80                 | 2014-01-31T00:00:00 | 
| NORTH    | J3   | 0        | 0    | 0       | 2       | 2                    | 31       | 38            | 16            | 85                    | 87                 | 2014-01-31T00:00:00 | 
| NORTH    | L1   | 0        | 0    | 4       | 2       | 6                    | 13       | 38            | 8             | 59                    | 61                 | 2014-01-31T00:00:00 | 
```