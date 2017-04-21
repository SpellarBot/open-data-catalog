# Maryland Average Household Size Projections: 1970-2040

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/maryland-average-household-size-projections-1970-2040-781f8) |
| Metadata | [Link](https://data.maryland.gov/api/views/amgh-v39p) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/amgh-v39p/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/amgh-v39p/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | amgh-v39p |
| Name | Maryland Average Household Size Projections: 1970-2040 |
| Attribution | Maryland Department of Planning |
| Category | Planning |
| Tags | household, projections, 2040, planning, mdp |
| Created | 2014-09-02T20:43:35Z |
| Publication Date | 2014-09-02T20:45:09Z |

## Description

Historical and Projected Household Size for Maryland and its Jurisdictions: 1970 - 2040. Prepared by the Maryland Department of Planning, July 2014.

## Columns

```ls
| Included | Schema Type    | Field Name      | Name             | Data Type | Render Type |
| ======== | ============== | =============== | ================ | ========= | =========== |
| Yes      | series tag     | year            | Year             | text      | text        |
| Yes      | numeric metric | census_1970     | Census, 1970     | number    | number      |
| Yes      | numeric metric | census_1980     | Census, 1980     | number    | number      |
| Yes      | numeric metric | census_1990     | Census, 1990     | number    | number      |
| Yes      | numeric metric | census_2000     | Census, 2000     | number    | number      |
| Yes      | numeric metric | census_2010     | Census, 2010     | number    | number      |
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
series e:amgh-v39p d:1970-01-01T00:00:00.000Z t:year=MARYLAND m:census_1980=2.82 m:projection_2020=2.57 m:projection_2035=2.49 m:census_1990=2.67 m:census_2000=2.61 m:census_2010=2.61 m:projection_2040=2.48 m:projection_2030=2.51 m:projection_2025=2.54 m:projection_2015=2.61 m:census_1970=3.25

series e:amgh-v39p d:1970-01-01T00:00:00.000Z t:year="Allegany County" m:census_1980=2.63 m:projection_2020=2.23 m:projection_2035=2.16 m:census_1990=2.43 m:census_2000=2.35 m:census_2010=2.3 m:projection_2040=2.15 m:projection_2030=2.18 m:projection_2025=2.2 m:projection_2015=2.26 m:census_1970=2.95

series e:amgh-v39p d:1970-01-01T00:00:00.000Z t:year="Anne Arundel County" m:census_1980=2.95 m:projection_2020=2.56 m:projection_2035=2.5 m:census_1990=2.76 m:census_2000=2.65 m:census_2010=2.63 m:projection_2040=2.5 m:projection_2030=2.51 m:projection_2025=2.52 m:projection_2015=2.6 m:census_1970=3.45
```

## Meta Commands

```ls
metric m:census_1970 p:float l:"Census, 1970" t:dataTypeName=number

metric m:census_1980 p:float l:"Census, 1980" t:dataTypeName=number

metric m:census_1990 p:float l:"Census, 1990" t:dataTypeName=number

metric m:census_2000 p:float l:"Census, 2000" t:dataTypeName=number

metric m:census_2010 p:float l:"Census, 2010" t:dataTypeName=number

metric m:projection_2015 p:float l:"Projection, 2015" t:dataTypeName=number

metric m:projection_2020 p:float l:"Projection, 2020" t:dataTypeName=number

metric m:projection_2025 p:float l:"Projection, 2025" t:dataTypeName=number

metric m:projection_2030 p:float l:"Projection, 2030" t:dataTypeName=number

metric m:projection_2035 p:float l:"Projection, 2035" t:dataTypeName=number

metric m:projection_2040 p:float l:"Projection, 2040" t:dataTypeName=number

entity e:amgh-v39p l:"Maryland Average Household Size Projections: 1970-2040" t:attribution="Maryland Department of Planning" t:url=https://data.maryland.gov/api/views/amgh-v39p

property e:amgh-v39p t:meta.view v:id=amgh-v39p v:category=Planning v:attributionLink=http://planning.maryland.gov/msdc/S3_Projection.shtml v:averageRating=0 v:name="Maryland Average Household Size Projections: 1970-2040" v:attribution="Maryland Department of Planning"

property e:amgh-v39p t:meta.view.owner v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:displayName=MDP

property e:amgh-v39p t:meta.view.tableauthor v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:roleName=editor v:displayName=MDP
```

## Top Records

```ls
| year                | census_1970 | census_1980 | census_1990 | census_2000 | census_2010 | projection_2015 | projection_2020 | projection_2025 | projection_2030 | projection_2035 | projection_2040 | 
| =================== | =========== | =========== | =========== | =========== | =========== | =============== | =============== | =============== | =============== | =============== | =============== | 
| MARYLAND            | 3.25        | 2.82        | 2.67        | 2.61        | 2.61        | 2.61            | 2.57            | 2.54            | 2.51            | 2.49            | 2.48            | 
| Allegany County     | 2.95        | 2.63        | 2.43        | 2.35        | 2.30        | 2.26            | 2.23            | 2.20            | 2.18            | 2.16            | 2.15            | 
| Anne Arundel County | 3.45        | 2.95        | 2.76        | 2.65        | 2.63        | 2.60            | 2.56            | 2.52            | 2.51            | 2.50            | 2.50            | 
| Baltimore City      | 3.07        | 2.74        | 2.59        | 2.42        | 2.38        | 2.35            | 2.32            | 2.28            | 2.26            | 2.24            | 2.21            | 
| Baltimore County    | 3.28        | 2.71        | 2.53        | 2.46        | 2.48        | 2.50            | 2.47            | 2.45            | 2.43            | 2.41            | 2.39            | 
| Calvert County      | 3.70        | 3.21        | 3.01        | 2.91        | 2.85        | 2.82            | 2.76            | 2.70            | 2.66            | 2.63            | 2.63            | 
| Caroline County     | 3.06        | 2.78        | 2.66        | 2.64        | 2.68        | 2.67            | 2.64            | 2.62            | 2.60            | 2.59            | 2.58            | 
| Carroll County      | 3.26        | 3.02        | 2.85        | 2.81        | 2.74        | 2.69            | 2.65            | 2.58            | 2.56            | 2.56            | 2.57            | 
| Cecil County        | 3.45        | 3.01        | 2.81        | 2.71        | 2.70        | 2.65            | 2.62            | 2.58            | 2.58            | 2.59            | 2.59            | 
| Charles County      | 3.90        | 3.38        | 3.03        | 2.86        | 2.83        | 2.81            | 2.77            | 2.72            | 2.67            | 2.64            | 2.62            | 
```