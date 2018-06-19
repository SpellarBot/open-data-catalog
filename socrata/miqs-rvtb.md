# Projected Median Age By Borough 2000-2030

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/projected-median-age-by-borough-2000-2030-ecb68) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/miqs-rvtb) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/miqs-rvtb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/miqs-rvtb/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | miqs-rvtb |
| Name | Projected Median Age By Borough 2000-2030 |
| Attribution | Department of City Planning (DCP) |
| Category | City Government |
| Tags | dcp, projected median age, nyc population |
| Created | 2011-10-25T17:40:03Z |
| Publication Date | 2013-06-26T17:14:29Z |

## Description

Median Age of the population of New York City in total and by Borough: unadjusted decennial census data from 1950-2000 and projected figures from 2010-2030.

## Columns

```ls
| Included | Schema Type | Field Name | Name    | Data Type | Render Type |
| ======== | =========== | ========== | ======= | ========= | =========== |
| Yes      | series tag  | borough    | Borough | text      | text        |
| No       |             | _1         | 1950    | number    | number      |
| No       |             | _2         | 1960    | number    | number      |
| No       |             | _3         | 1970    | number    | number      |
| No       |             | _4         | 1980    | number    | number      |
| No       |             | _5         | 1990    | number    | number      |
| No       |             | _6         | 2000    | number    | number      |
| No       |             | _7         | 2010    | number    | number      |
| No       |             | _8         | 2020    | number    | number      |
| No       |             | _9         | 2030    | number    | number      |
```

## Time Field

```ls
Value = 2000
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = _1,_2,_3,_4,_5,_6,_7,_8,_9
```

## Data Commands

```ls
series e:miqs-rvtb d:2000-01-01T00:00:00.000Z t:borough=Bronx m:row_number.miqs-rvtb=1

series e:miqs-rvtb d:2000-01-01T00:00:00.000Z t:borough=Brooklyn m:row_number.miqs-rvtb=2

series e:miqs-rvtb d:2000-01-01T00:00:00.000Z t:borough=Manhattan m:row_number.miqs-rvtb=3
```

## Meta Commands

```ls
metric m:row_number.miqs-rvtb p:long l:"Row Number"

entity e:miqs-rvtb l:"Projected Median Age By Borough 2000-2030" t:attribution="Department of City Planning (DCP)" t:url=https://data.cityofnewyork.us/api/views/miqs-rvtb

property e:miqs-rvtb t:meta.view v:id=miqs-rvtb v:category="City Government" v:averageRating=0 v:name="Projected Median Age By Borough 2000-2030" v:attribution="Department of City Planning (DCP)"

property e:miqs-rvtb t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:miqs-rvtb t:meta.view.tableauthor v:id=rnig-m3uj v:profileImageUrlMedium=/api/users/rnig-m3uj/profile_images/THUMB v:profileImageUrlLarge=/api/users/rnig-m3uj/profile_images/LARGE v:screenName="Jorge J." v:profileImageUrlSmall=/api/users/rnig-m3uj/profile_images/TINY v:displayName="Jorge J."
```

## Top Records

```ls
| borough                      | _1   | _2                 | _3   | _4                 | _5                 | _6                 | _7                 | _8                 | _9                 | 
| ============================ | ==== | ================== | ==== | ================== | ================== | ================== | ================== | ================== | ================== | 
| Bronx                        | 34.4 | 34.4               | 29.6 | 30.3               | 30.9               | 31.2               | 31.5               | 31.7               | 33.299999999999997 | 
| Brooklyn                     | 33.1 | 33.5               | 30.1 | 30.8               | 32.299999999999997 | 33.1               | 34.299999999999997 | 35.200000000000003 | 37.1               | 
| Manhattan                    | 36.6 | 37.6               | 35.4 | 34.6               | 35.9               | 35.799999999999997 | 37.700000000000003 | 38.5               | 39.5               | 
| Queens                       | 34.4 | 35.700000000000003 | 35.5 | 34.9               | 35.200000000000003 | 35.4               | 36.200000000000003 | 36.5               | 37.799999999999997 | 
| Staten Island                | 31.9 | 31.5               | 28.2 | 30.7               | 33.299999999999997 | 36                 | 38                 | 38.4               | 39.700000000000003 | 
| New York City (all boroughs) | 34.5 | 35.1               | 32.4 | 32.700000000000003 | 33.700000000000003 | 34.200000000000003 | 35.299999999999997 | 35.799999999999997 | 37.4               | 
```