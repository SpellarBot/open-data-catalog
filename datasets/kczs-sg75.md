# Maryland Female Labor Force Participation Rate Projections:1970-2040

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/maryland-female-labor-force-participation-rate-projections-1970-2040-b673d) |
| Metadata | [Link](https://data.maryland.gov/api/views/kczs-sg75) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/kczs-sg75/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/kczs-sg75/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | kczs-sg75 |
| Name | Maryland Female Labor Force Participation Rate Projections:1970-2040 |
| Attribution | Maryland Department of Planning |
| Tags | female, labor, projections, planning, mdp |
| Created | 2014-09-02T19:20:30Z |
| Publication Date | 2014-09-02T19:21:53Z |

## Description

Historical and Projected Labor Force Participation Rate for Females in Maryland and its Jurisdictions, 1970-2040.
Projected participation rates are calculated from rounded (to the nearest 10) population and labor force totals

## Columns

```ls
| Included | Schema Type    | Field Name      | Name             | Data Type | Render Type |
| ======== | ============== | =============== | ================ | ========= | =========== |
| Yes      | series tag     | jurisdiction    | Jurisdiction     | text      | text        |
| Yes      | numeric metric | census_1970     | Census, 1970     | number    | number      |
| Yes      | numeric metric | census_1980     | Census, 1980     | number    | number      |
| Yes      | numeric metric | census_1990     | Census, 1990     | number    | number      |
| Yes      | numeric metric | census_2000     | Census, 2000     | number    | number      |
| Yes      | numeric metric | census_2010     | Census, 2010     | number    | number      |
| Yes      | numeric metric | acs_2008_12     | ACS, 2008-12     | number    | number      |
| Yes      | numeric metric | projection_2015 | Projection, 2015 | number    | number      |
| Yes      | numeric metric | projection_2020 | Projection, 2020 | number    | number      |
| Yes      | numeric metric | projection_2025 | Projection, 2025 | number    | number      |
| Yes      | numeric metric | projection_2030 | Projection, 2030 | number    | number      |
| Yes      | numeric metric | projection_2035 | Projection, 2035 | number    | number      |
| Yes      | numeric metric | projection_2040 | Projection, 2040 | number    | number      |
```

## Time Field

```ls
Value = 1970
Format & Zone = yyyy
```

## Data Commands

```ls
series e:kczs-sg75 d:1970-01-01T00:00:00.000Z t:jurisdiction=MARYLAND m:acs_2008_12=65.5 m:projection_2020=63.6 m:projection_2035=60.3 m:census_1980=54.7 m:census_2000=62.8 m:census_1990=63.4 m:census_2010=65.6 m:projection_2040=60 m:projection_2030=61.2 m:projection_2025=62.3 m:projection_2015=64.6 m:census_1970=44.3

series e:kczs-sg75 d:1970-01-01T00:00:00.000Z t:jurisdiction="Allegany County" m:acs_2008_12=53.9 m:projection_2020=53 m:projection_2035=51.9 m:census_1980=38.6 m:census_2000=49.7 m:census_1990=44.9 m:census_2010=54.3 m:projection_2040=52.1 m:projection_2030=52.1 m:projection_2025=52.4 m:projection_2015=53.6 m:census_1970=31.3

series e:kczs-sg75 d:1970-01-01T00:00:00.000Z t:jurisdiction="Anne Arundel County" m:acs_2008_12=66 m:projection_2020=63.3 m:projection_2035=59.9 m:census_1980=55.2 m:census_2000=65.3 m:census_1990=65.2 m:census_2010=66.2 m:projection_2040=59.7 m:projection_2030=60.8 m:projection_2025=61.9 m:projection_2015=64.5 m:census_1970=42.3
```

## Meta Commands

```ls
metric m:census_1970 p:float l:"Census, 1970" t:dataTypeName=number

metric m:census_1980 p:float l:"Census, 1980" t:dataTypeName=number

metric m:census_1990 p:float l:"Census, 1990" t:dataTypeName=number

metric m:census_2000 p:float l:"Census, 2000" t:dataTypeName=number

metric m:census_2010 p:float l:"Census, 2010" t:dataTypeName=number

metric m:acs_2008_12 p:float l:"ACS, 2008-12" t:dataTypeName=number

metric m:projection_2015 p:float l:"Projection, 2015" t:dataTypeName=number

metric m:projection_2020 p:float l:"Projection, 2020" t:dataTypeName=number

metric m:projection_2025 p:float l:"Projection, 2025" t:dataTypeName=number

metric m:projection_2030 p:float l:"Projection, 2030" t:dataTypeName=number

metric m:projection_2035 p:float l:"Projection, 2035" t:dataTypeName=number

metric m:projection_2040 p:float l:"Projection, 2040" t:dataTypeName=number

entity e:kczs-sg75 l:"Maryland Female Labor Force Participation Rate Projections:1970-2040" t:attribution="Maryland Department of Planning" t:url=https://data.maryland.gov/api/views/kczs-sg75

property e:kczs-sg75 t:meta.view v:id=kczs-sg75 v:attributionLink=http://planning.maryland.gov/msdc/S3_Projection.shtml v:averageRating=0 v:name="Maryland Female Labor Force Participation Rate Projections:1970-2040" v:attribution="Maryland Department of Planning"

property e:kczs-sg75 t:meta.view.license v:name="Public Domain"

property e:kczs-sg75 t:meta.view.owner v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:displayName=MDP

property e:kczs-sg75 t:meta.view.tableauthor v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:roleName=editor v:displayName=MDP
```

## Top Records

```ls
| jurisdiction        | census_1970 | census_1980 | census_1990 | census_2000 | census_2010 | acs_2008_12 | projection_2015 | projection_2020 | projection_2025 | projection_2030 | projection_2035 | projection_2040 | 
| =================== | =========== | =========== | =========== | =========== | =========== | =========== | =============== | =============== | =============== | =============== | =============== | =============== | 
| MARYLAND            | 44.3        | 54.7        | 63.4        | 62.8        | 65.6        | 65.5        | 64.6            | 63.6            | 62.3            | 61.2            | 60.3            | 60.0            | 
| Allegany County     | 31.3        | 38.6        | 44.9        | 49.7        | 54.3        | 53.9        | 53.6            | 53.0            | 52.4            | 52.1            | 51.9            | 52.1            | 
| Anne Arundel County | 42.3        | 55.2        | 65.2        | 65.3        | 66.2        | 66.0        | 64.5            | 63.3            | 61.9            | 60.8            | 59.9            | 59.7            | 
| Baltimore City      | 45.4        | 48.3        | 55.0        | 54.5        | 61.9        | 61.8        | 62.4            | 62.6            | 62.3            | 62.4            | 62.5            | 63.0            | 
| Baltimore County    | 42.9        | 54.3        | 60.4        | 61.0        | 63.3        | 63.2        | 62.5            | 62.0            | 60.7            | 59.7            | 59.1            | 58.9            | 
| Calvert County      | 38.8        | 49.8        | 64.3        | 65.6        | 66.4        | 66.2        | 64.5            | 62.6            | 60.3            | 58.0            | 56.3            | 55.6            | 
| Caroline County     | 39.9        | 49.5        | 58.5        | 60.3        | 62.1        | 62.1        | 61.2            | 60.5            | 59.6            | 59.0            | 58.7            | 58.9            | 
| Carroll County      | 41.7        | 53.1        | 62.9        | 64.3        | 64.6        | 64.0        | 63.1            | 61.7            | 59.7            | 57.6            | 56.1            | 55.7            | 
| Cecil County        | 41.9        | 46.9        | 60.2        | 63.6        | 62.4        | 62.5        | 60.7            | 59.4            | 58.0            | 56.6            | 55.5            | 55.1            | 
| Charles County      | 41.0        | 54.6        | 69.1        | 67.5        | 68.8        | 68.6        | 66.9            | 65.7            | 64.0            | 62.1            | 60.4            | 59.3            | 
```