# Death Rate, State Of Hawaii 1900 - 2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/death-rate-state-of-hawaii-1900-2011-2db1c) |
| Metadata | [Link](https://data.hawaii.gov/api/views/xa5e-sayp) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/xa5e-sayp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/xa5e-sayp/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | xa5e-sayp |
| Name | Death Rate, State Of Hawaii 1900 - 2011 |
| Attribution | Health |
| Category | Health |
| Tags | death |
| Created | 2012-08-28T22:56:20Z |
| Publication Date | 2012-08-28T23:03:25Z |

## Description

Statistics from the Department of Health

## Columns

```ls
| Included | Schema Type    | Field Name                        | Name                              | Data Type | Render Type |
| ======== | ============== | ================================= | ================================= | ========= | =========== |
| Yes      | time           | year                              | Year                              | number    | number      |
| Yes      | numeric metric | rate_per_1000_resident_population | Rate Per 1000 Resident Population | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:xa5e-sayp d:1900-01-01T00:00:00.000Z m:rate_per_1000_resident_population=15.4

series e:xa5e-sayp d:1901-01-01T00:00:00.000Z m:rate_per_1000_resident_population=19.5

series e:xa5e-sayp d:1902-01-01T00:00:00.000Z m:rate_per_1000_resident_population=16.4
```

## Meta Commands

```ls
metric m:rate_per_1000_resident_population p:float l:"Rate Per 1000 Resident Population" t:dataTypeName=number

entity e:xa5e-sayp l:"Death Rate, State Of Hawaii 1900 - 2011" t:attribution=Health t:url=https://data.hawaii.gov/api/views/xa5e-sayp

property e:xa5e-sayp t:meta.view v:id=xa5e-sayp v:category=Health v:attributionLink=http://hawaii.gov/health v:averageRating=0 v:name="Death Rate, State Of Hawaii 1900 - 2011" v:attribution=Health

property e:xa5e-sayp t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:xa5e-sayp t:meta.view.owner v:id=8c9u-vteh v:screenName=lorrink v:displayName=lorrink

property e:xa5e-sayp t:meta.view.tableauthor v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:roleName=publisher v:displayName="OIMT Open Data Coordinator"
```

## Top Records

```ls
| year | rate_per_1000_resident_population | 
| ==== | ================================= | 
| 1900 | 15.4                              | 
| 1901 | 19.5                              | 
| 1902 | 16.4                              | 
| 1903 | 16.3                              | 
| 1904 | 16.6                              | 
| 1905 | 16.1                              | 
| 1906 | 17.1                              | 
| 1907 | 17.5                              | 
| 1908 | 15.4                              | 
| 1909 | 14.9                              | 
```