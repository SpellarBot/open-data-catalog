# Census 2000 and 2010 Population, Villages

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/census-2000-and-2010-population-villages) |
| Metadata | [Link](https://data.ny.gov/api/views/gxct-stum) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/gxct-stum/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/gxct-stum/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | gxct-stum |
| Name | Census 2000 and 2010 Population, Villages |
| Attribution | Empire State Development |
| Category | Government & Finance |
| Tags | census, population, municipalities |
| Created | 2013-02-26T15:28:53Z |
| Publication Date | 2013-03-03T20:25:16Z |

## Description

Total Populations of Villages - 2000 and 2010

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
| Yes      | series tag     | county                         | County                          | text      | text        |
| Yes      | series tag     | sub_county                     | Sub County                      | text      | text        |
| Yes      | numeric metric | place                          | Place                           | number    | number      |
| Yes      | series tag     | funcstat                       | FuncStat                        | text      | text        |
```

## Time Field

```ls
Value = 2000
Format & Zone = yyyy
```

## Data Commands

```ls
series e:gxct-stum d:2000-01-01T00:00:00.000Z t:population_change_number=159 t:geographic_area="Adams village" t:funcstat=A m:total_population_april_1_2010=1775 m:state=36 m:sumlev=160 m:place=199 m:population_change_percent=9.8 m:total_population_april_1_2000r=1616

series e:gxct-stum d:2000-01-01T00:00:00.000Z t:population_change_number=-34 t:geographic_area="Addison village" t:funcstat=A m:total_population_april_1_2010=1763 m:state=36 m:sumlev=160 m:place=276 m:population_change_percent=-1.9 m:total_population_april_1_2000r=1797

series e:gxct-stum d:2000-01-01T00:00:00.000Z t:population_change_number=-14 t:geographic_area="Afton village" t:funcstat=A m:total_population_april_1_2010=822 m:state=36 m:sumlev=160 m:place=342 m:population_change_percent=-1.7 m:total_population_april_1_2000r=836
```

## Meta Commands

```ls
metric m:total_population_april_1_2000r p:integer l:"Total Population April 1, 2000r" d:"r - Includes revisions due to the Census 2000 Count Question Resolution program and geographic changes since April 1, 2000" t:dataTypeName=number

metric m:total_population_april_1_2010 p:integer l:"Total Population April 1, 2010" t:dataTypeName=number

metric m:population_change_percent p:float l:"Population Change Percent" t:dataTypeName=percent

metric m:sumlev p:integer l:SUMLEV t:dataTypeName=number

metric m:state p:integer l:State t:dataTypeName=number

metric m:place p:integer l:Place t:dataTypeName=number

entity e:gxct-stum l:"Census 2000 and 2010 Population, Villages" t:attribution="Empire State Development" t:url=https://data.ny.gov/api/views/gxct-stum

property e:gxct-stum t:meta.view v:id=gxct-stum v:category="Government & Finance" v:attributionLink=http://esd.ny.gov/NYSDataCenter/Census2010.html v:averageRating=0 v:name="Census 2000 and 2010 Population, Villages" v:attribution="Empire State Development"

property e:gxct-stum t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:gxct-stum t:meta.view.tableauthor v:id=mwxm-zess v:profileImageUrlMedium=/api/users/mwxm-zess/profile_images/THUMB v:profileImageUrlLarge=/api/users/mwxm-zess/profile_images/LARGE v:screenName="Lindsey Krough" v:profileImageUrlSmall=/api/users/mwxm-zess/profile_images/TINY v:roleName=administrator v:displayName="Lindsey Krough"

property e:gxct-stum t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| geographic_area        | total_population_april_1_2000r | total_population_april_1_2010 | population_change_number | population_change_percent | sumlev | state | county | sub_county | place | funcstat | 
| ====================== | ============================== | ============================= | ======================== | ========================= | ====== | ===== | ====== | ========== | ===== | ======== | 
| Adams village          | 1616                           | 1775                          | 159                      | 9.8                       | 160    | 36    |        |            | 199   | A        | 
| Addison village        | 1797                           | 1763                          | -34                      | -1.9                      | 160    | 36    |        |            | 276   | A        | 
| Afton village          | 836                            | 822                           | -14                      | -1.7                      | 160    | 36    |        |            | 342   | A        | 
| Airmont village        | 7799                           | 8628                          | 829                      | 10.6                      | 160    | 36    |        |            | 408   | A        | 
| Akron village          | 3085                           | 2868                          | -217                     | -7.0                      | 160    | 36    |        |            | 441   | A        | 
| Albany city            | 94444                          | 97856                         | 3412                     | 3.6                       | 160    | 36    |        |            | 1000  | A        | 
| Albion village         | 5992                           | 6056                          | 64                       | 1.1                       | 160    | 36    |        |            | 1033  | A        | 
| Alden village          | 2666                           | 2605                          | -61                      | -2.3                      | 160    | 36    |        |            | 1088  | A        | 
| Alexander village      | 481                            | 509                           | 28                       | 5.8                       | 160    | 36    |        |            | 1154  | A        | 
| Alexandria Bay village | 1088                           | 1078                          | -10                      | -0.9                      | 160    | 36    |        |            | 1187  | A        | 
```