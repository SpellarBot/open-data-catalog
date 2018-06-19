# Maryland Male Labor Force Participation Rate Projections:1970-2040

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/maryland-male-labor-force-participation-rate-projections-1970-2040-af307) |
| Metadata | [Link](https://data.maryland.gov/api/views/8eyx-q5q3) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/8eyx-q5q3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/8eyx-q5q3/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | 8eyx-q5q3 |
| Name | Maryland Male Labor Force Participation Rate Projections:1970-2040 |
| Attribution | Maryland Department of Planning |
| Tags | male, labor, projections, planning, mdp |
| Created | 2014-09-02T19:16:21Z |
| Publication Date | 2014-09-02T19:17:56Z |

## Description

Historical and Projected Labor Force Participation Rate for Males in Maryland and its Jurisdictions, 1970-2040.
Projected participation rates are calculated from rounded (to the nearest 10) population and labor force totals.

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
series e:8eyx-q5q3 d:1970-01-01T00:00:00.000Z t:jurisdiction=MARYLAND m:acs_2008_12=74.1 m:projection_2020=72.1 m:projection_2035=69.6 m:census_1980=77.6 m:census_2000=73.3 m:census_1990=78.6 m:census_2010=73.9 m:projection_2040=69.4 m:projection_2030=70.2 m:projection_2025=71 m:projection_2015=73.1 m:census_1970=80.4

series e:8eyx-q5q3 d:1970-01-01T00:00:00.000Z t:jurisdiction="Allegany County" m:acs_2008_12=53.6 m:projection_2020=52.9 m:projection_2035=53 m:census_1980=68.4 m:census_2000=57.5 m:census_1990=64 m:census_2010=53.5 m:projection_2040=53.5 m:projection_2030=52.8 m:projection_2025=52.6 m:projection_2015=53.2 m:census_1970=72.1

series e:8eyx-q5q3 d:1970-01-01T00:00:00.000Z t:jurisdiction="Anne Arundel County" m:acs_2008_12=76.1 m:projection_2020=73.3 m:projection_2035=70.8 m:census_1980=81.6 m:census_2000=77.1 m:census_1990=82.2 m:census_2010=75.9 m:projection_2040=70.6 m:projection_2030=71.3 m:projection_2025=72 m:projection_2015=74.5 m:census_1970=83.1
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

entity e:8eyx-q5q3 l:"Maryland Male Labor Force Participation Rate Projections:1970-2040" t:attribution="Maryland Department of Planning" t:url=https://data.maryland.gov/api/views/8eyx-q5q3

property e:8eyx-q5q3 t:meta.view v:id=8eyx-q5q3 v:attributionLink=http://planning.maryland.gov/msdc/S3_Projection.shtml v:averageRating=0 v:name="Maryland Male Labor Force Participation Rate Projections:1970-2040" v:attribution="Maryland Department of Planning"

property e:8eyx-q5q3 t:meta.view.license v:name="Public Domain"

property e:8eyx-q5q3 t:meta.view.owner v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:displayName=MDP

property e:8eyx-q5q3 t:meta.view.tableauthor v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:roleName=editor v:displayName=MDP
```

## Top Records

```ls
| jurisdiction        | census_1970 | census_1980 | census_1990 | census_2000 | census_2010 | acs_2008_12 | projection_2015 | projection_2020 | projection_2025 | projection_2030 | projection_2035 | projection_2040 | 
| =================== | =========== | =========== | =========== | =========== | =========== | =========== | =============== | =============== | =============== | =============== | =============== | =============== | 
| MARYLAND            | 80.4        | 77.6        | 78.6        | 73.3        | 73.9        | 74.1        | 73.1            | 72.1            | 71.0            | 70.2            | 69.6            | 69.4            | 
| Allegany County     | 72.1        | 68.4        | 64.0        | 57.5        | 53.5        | 53.6        | 53.2            | 52.9            | 52.6            | 52.8            | 53.0            | 53.5            | 
| Anne Arundel County | 83.1        | 81.6        | 82.2        | 77.1        | 75.9        | 76.1        | 74.5            | 73.3            | 72.0            | 71.3            | 70.8            | 70.6            | 
| Baltimore City      | 74.2        | 67.5        | 67.4        | 59.1        | 63.6        | 63.8        | 64.7            | 64.9            | 64.6            | 64.8            | 64.8            | 65.0            | 
| Baltimore County    | 83.1        | 79.9        | 77.9        | 73.1        | 72.9        | 73.1        | 72.4            | 71.5            | 70.3            | 69.5            | 69.1            | 69.1            | 
| Calvert County      | 77.5        | 77.5        | 82.9        | 77.8        | 76.5        | 76.6        | 74.7            | 72.9            | 71.5            | 70.1            | 69.0            | 68.6            | 
| Caroline County     | 73.8        | 72.8        | 75.9        | 72.4        | 72.3        | 72.5        | 71.7            | 70.2            | 68.8            | 68.0            | 67.4            | 67.2            | 
| Carroll County      | 74.1        | 79.0        | 82.1        | 78.5        | 75.8        | 75.8        | 74.1            | 72.3            | 70.6            | 69.0            | 67.6            | 67.2            | 
| Cecil County        | 79.6        | 73.0        | 76.2        | 75.3        | 71.7        | 71.5        | 70.4            | 69.0            | 67.8            | 67.0            | 66.6            | 66.6            | 
| Charles County      | 81.6        | 80.5        | 83.3        | 78.2        | 76.4        | 76.6        | 74.5            | 72.9            | 71.3            | 69.6            | 68.5            | 68.1            | 
```