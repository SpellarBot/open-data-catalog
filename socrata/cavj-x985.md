# 2010 U.S. Census Population Counts, King County and its Cities, April 1, 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2010-u-s-census-population-counts-king-county-and-its-cities-april-1-2010-8e1e6) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/cavj-x985) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/cavj-x985/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/cavj-x985/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | cavj-x985 |
| Name | 2010 U.S. Census Population Counts, King County and its Cities, April 1, 2010 |
| Attribution | King County |
| Category | Census |
| Tags | census, population |
| Created | 2011-03-24T17:49:14Z |
| Publication Date | 2011-04-17T00:03:09Z |

## Description

Source:  U.S. Census Bureau, PL 94-171 Redistricting data, 2000 and 2010. Note: Census numbers for the cities of Burien and Kent do not include annexations that took place after March 31, 2010.  These annexations would increase Burien to 48,072, Kent to 118,565, and decrease uninc King County to 284,089.

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type | Render Type |
| ======== | ============== | ===================== | ===================== | ========= | =========== |
| Yes      | series tag     | city                  | City                  | text      | text        |
| Yes      | numeric metric | 2000_census_corrected | 2000 Census Corrected | number    | number      |
| Yes      | numeric metric | 2010_census           | 2010 Census           | number    | number      |
| Yes      | numeric metric | change_2000_2010_1    | Change 2000-2010      | number    | number      |
| Yes      | numeric metric | change_2000_2010_2    | % Change 2000-2010    | percent   | percent     |
| Yes      | series tag     | note                  | Note                  | text      | text        |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:cavj-x985 d:2010-01-01T00:00:00.000Z t:city="Cities Total" m:change_2000_2010_2=15.7 m:2000_census_corrected=1387812 m:2010_census=1606247 m:change_2000_2010_1=218435

series e:cavj-x985 d:2010-01-01T00:00:00.000Z t:note="* Census numbers for the cities of Burien and Kent do not include annexations that took place after March 31, 2010. These annexations would increase Burien to 48,072, Kent to 118,565, and decrease uninc King County to 284,089." t:city="Uninc. King County" m:change_2000_2010_2=-6.9 m:2000_census_corrected=349234 m:2010_census=325002 m:change_2000_2010_1=-24232

series e:cavj-x985 d:2010-01-01T00:00:00.000Z t:city="King County" m:change_2000_2010_2=11.2 m:2000_census_corrected=1737046 m:2010_census=1931249 m:change_2000_2010_1=194203
```

## Meta Commands

```ls
metric m:2000_census_corrected p:integer l:"2000 Census Corrected" t:dataTypeName=number

metric m:2010_census p:integer l:"2010 Census" t:dataTypeName=number

metric m:change_2000_2010_1 p:integer l:"Change 2000-2010" t:dataTypeName=number

metric m:change_2000_2010_2 p:float l:"% Change 2000-2010" t:dataTypeName=percent

entity e:cavj-x985 l:"2010 U.S. Census Population Counts, King County and its Cities, April 1, 2010" t:attribution="King County" t:url=https://data.kingcounty.gov/api/views/cavj-x985

property e:cavj-x985 t:meta.view v:id=cavj-x985 v:category=Census v:attributionLink=http://www.kingcounty.gov/ v:averageRating=0 v:name="2010 U.S. Census Population Counts, King County and its Cities, April 1, 2010" v:attribution="King County"

property e:cavj-x985 t:meta.view.license v:name="Public Domain"

property e:cavj-x985 t:meta.view.owner v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:displayName="King County Webteam"

property e:cavj-x985 t:meta.view.tableauthor v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:roleName=administrator v:displayName="King County Webteam"
```

## Top Records

```ls
| city                  | 2000_census_corrected | 2010_census | change_2000_2010_1 | change_2000_2010_2 | note                                                                                                                                                                                                                               | 
| ===================== | ===================== | =========== | ================== | ================== | ================================================================================================================================================================================================================================== | 
| Cities Total          | 1387812               | 1606247     | 218435             | 15.7               |                                                                                                                                                                                                                                    | 
| Uninc. King County    | 349234                | 325002      | -24232             | -6.9               | * Census numbers for the cities of Burien and Kent do not include annexations that took place after March 31, 2010. These annexations would increase Burien to 48,072, Kent to 118,565, and decrease uninc King County to 284,089. | 
| King County           | 1737046               | 1931249     | 194203             | 11.2               |                                                                                                                                                                                                                                    | 
| Washington State      | 5894121               | 6724540     | 830419             | 14.1               |                                                                                                                                                                                                                                    | 
| Auburn (K.C. portion) | 42901                 | 62761       | 19860              | 46.3               |                                                                                                                                                                                                                                    | 
| Algona                | 2460                  | 3014        | 554                | 22.5               |                                                                                                                                                                                                                                    | 
| Des Moines            | 29267                 | 29673       | 406                | 1.4                |                                                                                                                                                                                                                                    | 
| Hunts Point           | 443                   | 394         | -49                | -11.1              |                                                                                                                                                                                                                                    | 
| Kent *                | 79524                 | 92411       | 12887              | 16.2               | * Census numbers for the cities of Burien and Kent do not include annexations that took place after March 31, 2010. These annexations would increase Burien to 48,072, Kent to 118,565, and decrease uninc King County to 284,089. | 
| Tukwila               | 17181                 | 19107       | 1926               | 11.2               |                                                                                                                                                                                                                                    | 
```