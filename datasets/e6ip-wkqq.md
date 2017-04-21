# WAOFM - Census - Population Density by County by Decade, 1900 to 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/waofm-census-population-density-by-county-by-decade-1900-to-2010-01f90) |
| Metadata | [Link](https://data.wa.gov/api/views/e6ip-wkqq) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/e6ip-wkqq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/e6ip-wkqq/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | e6ip-wkqq |
| Name | WAOFM - Census - Population Density by County by Decade, 1900 to 2010 |
| Attribution | Washington State Office of Financial Management, Forecasting Division |
| Category | Demographics |
| Tags | wa, washington, ofm, county, population, density, state-of-the-salmon |
| Created | 2012-02-09T01:30:34Z |
| Publication Date | 2012-02-09T01:37:14Z |

## Description

Washington state population density by county by decade 1900 to 2010.

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| No       | time           | :updated_at             | updated_at              | meta_data | meta_data   |
| Yes      | series tag     | county_name             | County Name             | text      | text        |
| Yes      | numeric metric | population_density_1900 | Population Density 1900 | number    | number      |
| Yes      | numeric metric | population_density_1910 | Population Density 1910 | number    | number      |
| Yes      | numeric metric | population_density_1920 | Population Density 1920 | number    | number      |
| Yes      | numeric metric | population_density_1930 | Population Density 1930 | number    | number      |
| Yes      | numeric metric | population_density_1940 | Population Density 1940 | number    | number      |
| Yes      | numeric metric | population_density_1950 | Population Density 1950 | number    | number      |
| Yes      | numeric metric | population_density_1960 | Population Density 1960 | number    | number      |
| Yes      | numeric metric | population_density_1970 | Population Density 1970 | number    | number      |
| Yes      | numeric metric | population_density_1980 | Population Density 1980 | number    | number      |
| Yes      | numeric metric | population_density_1990 | Population Density 1990 | number    | number      |
| Yes      | numeric metric | population_density_2000 | Population Density 2000 | number    | number      |
| Yes      | numeric metric | population_density_2010 | Population Density 2010 | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:e6ip-wkqq d:2012-02-08T17:30:42.000Z t:county_name=Adams m:population_density_1960=5.16 m:population_density_1970=6.24 m:population_density_1990=7.07 m:population_density_1980=6.89 m:population_density_2010=9.73 m:population_density_1950=3.42 m:population_density_2000=8.53 m:population_density_1940=3.23 m:population_density_1920=5 m:population_density_1900=2.51 m:population_density_1930=4.01 m:population_density_1910=5.67

series e:e6ip-wkqq d:2012-02-08T17:30:42.000Z t:county_name=Asotin m:population_density_1960=20.3 m:population_density_1970=21.7 m:population_density_1990=27.69 m:population_density_1980=26.46 m:population_density_2010=33.99 m:population_density_1950=17.11 m:population_density_2000=32.35 m:population_density_1940=13.15 m:population_density_1920=10.28 m:population_density_1900=5.29 m:population_density_1930=12.79 m:population_density_1910=9.17

series e:e6ip-wkqq d:2012-02-08T17:30:42.000Z t:county_name=Benton m:population_density_1960=36.45 m:population_density_1970=39.66 m:population_density_1990=66.09 m:population_density_1980=64.26 m:population_density_2010=103.02 m:population_density_1950=30.16 m:population_density_2000=83.66 m:population_density_1940=7.08 m:population_density_1920=6.4 m:population_density_1930=6.43 m:population_density_1910=4.66
```

## Meta Commands

```ls
metric m:population_density_1900 p:float l:"Population Density 1900" t:dataTypeName=number

metric m:population_density_1910 p:float l:"Population Density 1910" t:dataTypeName=number

metric m:population_density_1920 p:float l:"Population Density 1920" t:dataTypeName=number

metric m:population_density_1930 p:float l:"Population Density 1930" t:dataTypeName=number

metric m:population_density_1940 p:float l:"Population Density 1940" t:dataTypeName=number

metric m:population_density_1950 p:float l:"Population Density 1950" t:dataTypeName=number

metric m:population_density_1960 p:float l:"Population Density 1960" t:dataTypeName=number

metric m:population_density_1970 p:float l:"Population Density 1970" t:dataTypeName=number

metric m:population_density_1980 p:float l:"Population Density 1980" t:dataTypeName=number

metric m:population_density_1990 p:float l:"Population Density 1990" t:dataTypeName=number

metric m:population_density_2000 p:float l:"Population Density 2000" t:dataTypeName=number

metric m:population_density_2010 p:float l:"Population Density 2010" t:dataTypeName=number

entity e:e6ip-wkqq l:"WAOFM - Census - Population Density by County by Decade, 1900 to 2010" t:attribution="Washington State Office of Financial Management, Forecasting Division" t:url=https://data.wa.gov/api/views/e6ip-wkqq

property e:e6ip-wkqq t:meta.view v:id=e6ip-wkqq v:category=Demographics v:attributionLink=http://www.ofm.wa.gov/pop/popden/default.asp v:averageRating=40 v:name="WAOFM - Census - Population Density by County by Decade, 1900 to 2010" v:attribution="Washington State Office of Financial Management, Forecasting Division"

property e:e6ip-wkqq t:meta.view.license v:name="Public Domain"

property e:e6ip-wkqq t:meta.view.owner v:id=qav9-tahu v:profileImageUrlMedium=/api/users/qav9-tahu/profile_images/THUMB v:profileImageUrlLarge=/api/users/qav9-tahu/profile_images/LARGE v:screenName="Thomas Kimpel" v:profileImageUrlSmall=/api/users/qav9-tahu/profile_images/TINY v:displayName="Thomas Kimpel"

property e:e6ip-wkqq t:meta.view.tableauthor v:id=qav9-tahu v:profileImageUrlMedium=/api/users/qav9-tahu/profile_images/THUMB v:profileImageUrlLarge=/api/users/qav9-tahu/profile_images/LARGE v:screenName="Thomas Kimpel" v:profileImageUrlSmall=/api/users/qav9-tahu/profile_images/TINY v:roleName=administrator v:displayName="Thomas Kimpel"
```

## Top Records

```ls
| :updated_at | county_name | population_density_1900 | population_density_1910 | population_density_1920 | population_density_1930 | population_density_1940 | population_density_1950 | population_density_1960 | population_density_1970 | population_density_1980 | population_density_1990 | population_density_2000 | population_density_2010 | 
| =========== | =========== | ======================= | ======================= | ======================= | ======================= | ======================= | ======================= | ======================= | ======================= | ======================= | ======================= | ======================= | ======================= | 
| 1328722242  | Adams       | 2.51                    | 5.67                    | 5.00                    | 4.01                    | 3.23                    | 3.42                    | 5.16                    | 6.24                    | 6.89                    | 7.07                    | 8.53                    | 9.73                    | 
| 1328722242  | Asotin      | 5.29                    | 9.17                    | 10.28                   | 12.79                   | 13.15                   | 17.11                   | 20.30                   | 21.70                   | 26.46                   | 27.69                   | 32.35                   | 33.99                   | 
| 1328722242  | Benton      |                         | 4.66                    | 6.40                    | 6.43                    | 7.08                    | 30.16                   | 36.45                   | 39.66                   | 64.26                   | 66.09                   | 83.66                   | 103.02                  | 
| 1328722242  | Chelan      | 1.35                    | 5.17                    | 7.16                    | 10.83                   | 11.78                   | 13.45                   | 13.95                   | 14.15                   | 15.42                   | 17.88                   | 22.80                   | 24.81                   | 
| 1328722242  | Clallam     | 3.21                    | 3.87                    | 6.51                    | 11.72                   | 12.52                   | 15.12                   | 17.20                   | 19.92                   | 29.59                   | 32.20                   | 36.90                   | 41.08                   | 
| 1328722242  | Clark       | 21.37                   | 41.59                   | 52.25                   | 64.21                   | 79.39                   | 135.86                  | 149.40                  | 204.58                  | 306.14                  | 379.13                  | 549.55                  | 676.25                  | 
| 1328722242  | Columbia    | 8.20                    | 8.11                    | 7.01                    | 6.13                    | 6.39                    | 5.59                    | 5.26                    | 5.11                    | 4.67                    | 4.63                    | 4.68                    | 4.69                    | 
| 1328722242  | Cowlitz     | 6.92                    | 11.03                   | 10.35                   | 28.02                   | 35.26                   | 46.87                   | 50.76                   | 60.26                   | 69.86                   | 72.12                   | 81.63                   | 89.82                   | 
| 1328722242  | Douglas     | 1.10                    | 5.07                    | 5.16                    | 4.15                    | 4.75                    | 5.94                    | 8.18                    | 9.22                    | 12.16                   | 14.39                   | 17.91                   | 21.12                   | 
| 1328722242  | Ferry       | 2.07                    | 2.18                    | 2.33                    | 1.95                    | 2.13                    | 1.86                    | 1.76                    | 1.66                    | 2.64                    | 2.86                    | 3.29                    | 3.43                    | 
```