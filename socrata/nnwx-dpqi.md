# Maryland Historical and Projected Population by Jurisdiction

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/maryland-historical-and-projected-population-by-jurisdiction-55155) |
| Metadata | [Link](https://data.maryland.gov/api/views/nnwx-dpqi) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/nnwx-dpqi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/nnwx-dpqi/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | nnwx-dpqi |
| Name | Maryland Historical and Projected Population by Jurisdiction |
| Attribution | Maryland Department of Planning |
| Category | Planning |
| Tags | population, projections, historical, planning, mdp |
| Created | 2014-09-02T20:35:37Z |
| Publication Date | 2014-09-02T20:37:36Z |

## Description

Population Projections for Maryland and the jurisdictions - historical population 1970-2010; projections out to 2040. Projections prepared by the Maryland Department of Planning, July 2014

## Columns

```ls
| Included | Schema Type    | Field Name      | Name             | Data Type | Render Type |
| ======== | ============== | =============== | ================ | ========= | =========== |
| No       | time           | :updated_at     | updated_at       | meta_data | meta_data   |
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
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:nnwx-dpqi d:2014-09-02T13:35:47.000Z t:year=MARYLAND m:projection_2020=6224550 m:projection_2035=6762300 m:census_1980=4216933 m:census_2000=5296486 m:census_1990=4780753 m:census_2010=5773552 m:projection_2040=6889700 m:projection_2030=6612200 m:projection_2025=6429750 m:projection_2015=6010150 m:census_1970=3923897

series e:nnwx-dpqi d:2014-09-02T13:35:47.000Z t:year="Allegany County" m:projection_2020=75150 m:projection_2035=76900 m:census_1980=80548 m:census_2000=74930 m:census_1990=74946 m:census_2010=75087 m:projection_2040=77050 m:projection_2030=76650 m:projection_2025=75900 m:projection_2015=74650 m:census_1970=84044

series e:nnwx-dpqi d:2014-09-02T13:35:47.000Z t:year="Anne Arundel County" m:projection_2020=580000 m:projection_2035=618200 m:census_1980=370775 m:census_2000=489656 m:census_1990=427239 m:census_2010=537656 m:projection_2040=628050 m:projection_2030=606700 m:projection_2025=593600 m:projection_2015=559600 m:census_1970=298042
```

## Meta Commands

```ls
metric m:census_1970 p:integer l:"Census, 1970" t:dataTypeName=number

metric m:census_1980 p:integer l:"Census, 1980" t:dataTypeName=number

metric m:census_1990 p:integer l:"Census, 1990" t:dataTypeName=number

metric m:census_2000 p:integer l:"Census, 2000" t:dataTypeName=number

metric m:census_2010 p:integer l:"Census, 2010" t:dataTypeName=number

metric m:projection_2015 p:integer l:"Projection, 2015" t:dataTypeName=number

metric m:projection_2020 p:integer l:"Projection, 2020" t:dataTypeName=number

metric m:projection_2025 p:integer l:"Projection, 2025" t:dataTypeName=number

metric m:projection_2030 p:integer l:"Projection, 2030" t:dataTypeName=number

metric m:projection_2035 p:integer l:"Projection, 2035" t:dataTypeName=number

metric m:projection_2040 p:integer l:"Projection, 2040" t:dataTypeName=number

entity e:nnwx-dpqi l:"Maryland Historical and Projected Population by Jurisdiction" t:attribution="Maryland Department of Planning" t:url=https://data.maryland.gov/api/views/nnwx-dpqi

property e:nnwx-dpqi t:meta.view v:id=nnwx-dpqi v:category=Planning v:attributionLink=http://planning.maryland.gov/msdc/S3_Projection.shtml v:averageRating=0 v:name="Maryland Historical and Projected Population by Jurisdiction" v:attribution="Maryland Department of Planning"

property e:nnwx-dpqi t:meta.view.owner v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:displayName=MDP

property e:nnwx-dpqi t:meta.view.tableauthor v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:roleName=editor v:displayName=MDP
```

## Top Records

```ls
| :updated_at | year                | census_1970 | census_1980 | census_1990 | census_2000 | census_2010 | projection_2015 | projection_2020 | projection_2025 | projection_2030 | projection_2035 | projection_2040 | 
| =========== | =================== | =========== | =========== | =========== | =========== | =========== | =============== | =============== | =============== | =============== | =============== | =============== | 
| 1409664947  | MARYLAND            | 3923897     | 4216933     | 4780753     | 5296486     | 5773552     | 6010150         | 6224550         | 6429750         | 6612200         | 6762300         | 6889700         | 
| 1409664947  | Allegany County     | 84044       | 80548       | 74946       | 74930       | 75087       | 74650           | 75150           | 75900           | 76650           | 76900           | 77050           | 
| 1409664947  | Anne Arundel County | 298042      | 370775      | 427239      | 489656      | 537656      | 559600          | 580000          | 593600          | 606700          | 618200          | 628050          | 
| 1409664947  | Baltimore City      | 905787      | 786741      | 736014      | 651154      | 620961      | 625000          | 634100          | 644000          | 651100          | 655650          | 659100          | 
| 1409664947  | Baltimore County    | 620409      | 655615      | 692134      | 754292      | 805029      | 832050          | 847000          | 857000          | 862200          | 869500          | 880750          | 
| 1409664947  | Calvert County      | 20682       | 34638       | 51372       | 74563       | 88737       | 91650           | 95600           | 98350           | 100200          | 101050          | 101450          | 
| 1409664947  | Caroline County     | 19781       | 23143       | 27035       | 29772       | 33066       | 33900           | 36050           | 38250           | 40450           | 42750           | 44950           | 
| 1409664947  | Carroll County      | 69006       | 96356       | 123372      | 150897      | 167134      | 168550          | 175900          | 179450          | 183250          | 186200          | 189550          | 
| 1409664947  | Cecil County        | 53291       | 60430       | 71347       | 85951       | 101108      | 103600          | 108600          | 117300          | 125250          | 132900          | 139650          | 
| 1409664947  | Charles County      | 47678       | 72751       | 101154      | 120546      | 146551      | 157100          | 174350          | 190650          | 202150          | 212300          | 220850          | 
```