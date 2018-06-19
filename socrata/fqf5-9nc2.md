# Census 2000 and 2010 Population, Towns

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/census-2000-and-2010-population-towns) |
| Metadata | [Link](https://data.ny.gov/api/views/fqf5-9nc2) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/fqf5-9nc2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/fqf5-9nc2/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | fqf5-9nc2 |
| Name | Census 2000 and 2010 Population, Towns |
| Attribution | Empire State Development |
| Category | Government & Finance |
| Tags | census, population, municipalities |
| Created | 2013-02-26T15:16:07Z |
| Publication Date | 2013-03-03T20:20:17Z |

## Description

Total Populations of Counties, Towns, and Cities - 2000 and 2010

## Columns

```ls
| Included | Schema Type    | Field Name                     | Name                            | Data Type | Render Type |
| ======== | ============== | ============================== | =============================== | ========= | =========== |
| Yes      | series tag     | geographic_area                | Geographic Area                 | text      | text        |
| Yes      | numeric metric | total_population_april_1_2000r | Total Population April 1, 2000r | number    | number      |
| Yes      | numeric metric | total_population_april_1_2010  | Total Population April 1, 2010  | number    | number      |
| Yes      | series tag     | population_change_number       | Population Change Number        | text      | number      |
| Yes      | numeric metric | population_change_percent      | Population Change Percent       | percent   | percent     |
| Yes      | numeric metric | sumlev                         | SUMLEV                          | number    | number      |
| Yes      | numeric metric | state                          | State                           | number    | number      |
| Yes      | numeric metric | county                         | County                          | number    | number      |
| Yes      | numeric metric | sub_county                     | Sub County                      | number    | number      |
| Yes      | numeric metric | place                          | Place                           | number    | text        |
| Yes      | series tag     | funcstat                       | FuncStat                        | text      | text        |
```

## Time Field

```ls
Value = 2000
Format & Zone = yyyy
```

## Data Commands

```ls
series e:fqf5-9nc2 d:2000-01-01T00:00:00.000Z t:population_change_number=401291 t:geographic_area="New York State" t:funcstat=A m:total_population_april_1_2010=19378102 m:state=36 m:sumlev=40 m:population_change_percent=2.1 m:total_population_april_1_2000r=18976811

series e:fqf5-9nc2 d:2000-01-01T00:00:00.000Z t:population_change_number=166447 t:geographic_area="New York City" t:funcstat=A m:total_population_april_1_2010=8175133 m:state=36 m:sumlev=160 m:place=51000 m:population_change_percent=2.1 m:total_population_april_1_2000r=8008686

series e:fqf5-9nc2 d:2000-01-01T00:00:00.000Z t:population_change_number=9633 t:geographic_area="Albany County" t:funcstat=A m:total_population_april_1_2010=304204 m:county=1 m:state=36 m:sumlev=50 m:population_change_percent=3.3 m:total_population_april_1_2000r=294571
```

## Meta Commands

```ls
metric m:total_population_april_1_2000r p:integer l:"Total Population April 1, 2000r" d:"r - Includes revisions due to the Census 2000 Count Question Resolution program and geographic changes since April 1, 2000" t:dataTypeName=number

metric m:total_population_april_1_2010 p:integer l:"Total Population April 1, 2010" t:dataTypeName=number

metric m:population_change_percent p:float l:"Population Change Percent" t:dataTypeName=percent

metric m:sumlev p:integer l:SUMLEV t:dataTypeName=number

metric m:state p:integer l:State t:dataTypeName=number

metric m:county p:integer l:County t:dataTypeName=number

metric m:sub_county p:integer l:"Sub County" t:dataTypeName=number

metric m:place p:integer l:Place t:dataTypeName=number

entity e:fqf5-9nc2 l:"Census 2000 and 2010 Population, Towns" t:attribution="Empire State Development" t:url=https://data.ny.gov/api/views/fqf5-9nc2

property e:fqf5-9nc2 t:meta.view v:id=fqf5-9nc2 v:category="Government & Finance" v:attributionLink=http://esd.ny.gov/NYSDataCenter/Census2010.html v:averageRating=0 v:name="Census 2000 and 2010 Population, Towns" v:attribution="Empire State Development"

property e:fqf5-9nc2 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:fqf5-9nc2 t:meta.view.tableauthor v:id=mwxm-zess v:profileImageUrlMedium=/api/users/mwxm-zess/profile_images/THUMB v:profileImageUrlLarge=/api/users/mwxm-zess/profile_images/LARGE v:screenName="Lindsey Krough" v:profileImageUrlSmall=/api/users/mwxm-zess/profile_images/TINY v:roleName=administrator v:displayName="Lindsey Krough"

property e:fqf5-9nc2 t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| geographic_area   | total_population_april_1_2000r | total_population_april_1_2010 | population_change_number | population_change_percent | sumlev | state | county | sub_county | place | funcstat | 
| ================= | ============================== | ============================= | ======================== | ========================= | ====== | ===== | ====== | ========== | ===== | ======== | 
| New York State    | 18976811                       | 19378102                      | 401291                   | 2.1                       | 40     | 36    |        |            |       | A        | 
| New York City     | 8008686                        | 8175133                       | 166447                   | 2.1                       | 160    | 36    |        |            | 51000 | A        | 
| Albany County     | 294571                         | 304204                        | 9633                     | 3.3                       | 50     | 36    | 1      |            |       | A        | 
| Albany city       | 94444                          | 97856                         | 3412                     | 3.6                       | 60     | 36    | 1      | 1000       |       | F        | 
| Berne town        | 2853                           | 2794                          | -59                      | -2.1                      | 60     | 36    | 1      | 6211       |       | A        | 
| Bethlehem town    | 31338                          | 33656                         | 2318                     | 7.4                       | 60     | 36    | 1      | 6354       |       | A        | 
| Coeymans town     | 8161                           | 7418                          | -743                     | -9.1                      | 60     | 36    | 1      | 16694      |       | A        | 
| Cohoes city       | 15607                          | 16168                         | 561                      | 3.6                       | 60     | 36    | 1      | 16749      |       | F        | 
| Colonie town      | 79327                          | 81591                         | 2264                     | 2.9                       | 60     | 36    | 1      | 17343      |       | A        | 
| Green Island town | 2283                           | 2620                          | 337                      | 14.8                      | 60     | 36    | 1      | 30532      |       | B        | 
```