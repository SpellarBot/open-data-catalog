# Maryland Male Labor Force Projections: 1970-2040

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/maryland-male-labor-force-projections-1970-2040-1eb36) |
| Metadata | [Link](https://data.maryland.gov/api/views/mrce-5khr) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/mrce-5khr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/mrce-5khr/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | mrce-5khr |
| Name | Maryland Male Labor Force Projections: 1970-2040 |
| Attribution | Maryland Department of Planning |
| Tags | male, labor force, projections, planning, mdp |
| Created | 2014-09-02T19:30:22Z |
| Publication Date | 2014-09-02T19:32:36Z |

## Description

Historical and Projected Male Labor Force in Maryland and its Jurisdictions, 1970-2040. Projected numbers are rounded to the nearest 10. Prepared by the Maryland Department of Planning, July 2014.

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
series e:mrce-5khr d:1970-01-01T00:00:00.000Z t:jurisdiction=MARYLAND m:acs_2008_12=1624930 m:projection_2020=1735900 m:projection_2035=1833600 m:census_1980=1188276 m:census_2000=1418491 m:census_1990=1401893 m:census_2010=1615040 m:projection_2040=1873080 m:projection_2030=1803640 m:projection_2025=1772890 m:projection_2015=1687470 m:census_1970=1035929

series e:mrce-5khr d:1970-01-01T00:00:00.000Z t:jurisdiction="Allegany County" m:acs_2008_12=17429 m:projection_2020=17760 m:projection_2035=18780 m:census_1980=19926 m:census_2000=17520 m:census_1990=17746 m:census_2010=17470 m:projection_2040=19160 m:projection_2030=18490 m:projection_2025=18100 m:projection_2015=17530 m:census_1970=20192

series e:mrce-5khr d:1970-01-01T00:00:00.000Z t:jurisdiction="Anne Arundel County" m:acs_2008_12=159567 m:projection_2020=167280 m:projection_2035=172830 m:census_1980=114773 m:census_2000=144505 m:census_1990=137163 m:census_2010=158780 m:projection_2040=175620 m:projection_2030=170760 m:projection_2025=168930 m:projection_2015=163730 m:census_1970=86355
```

## Meta Commands

```ls
metric m:census_1970 p:integer l:"Census, 1970" t:dataTypeName=number

metric m:census_1980 p:integer l:"Census, 1980" t:dataTypeName=number

metric m:census_1990 p:integer l:"Census, 1990" t:dataTypeName=number

metric m:census_2000 p:integer l:"Census, 2000" t:dataTypeName=number

metric m:census_2010 p:integer l:"Census, 2010" t:dataTypeName=number

metric m:acs_2008_12 p:integer l:"ACS, 2008-12" t:dataTypeName=number

metric m:projection_2015 p:integer l:"Projection, 2015" t:dataTypeName=number

metric m:projection_2020 p:integer l:"Projection, 2020" t:dataTypeName=number

metric m:projection_2025 p:integer l:"Projection, 2025" t:dataTypeName=number

metric m:projection_2030 p:integer l:"Projection, 2030" t:dataTypeName=number

metric m:projection_2035 p:integer l:"Projection, 2035" t:dataTypeName=number

metric m:projection_2040 p:integer l:"Projection, 2040" t:dataTypeName=number

entity e:mrce-5khr l:"Maryland Male Labor Force Projections: 1970-2040" t:attribution="Maryland Department of Planning" t:url=https://data.maryland.gov/api/views/mrce-5khr

property e:mrce-5khr t:meta.view v:id=mrce-5khr v:attributionLink=http://planning.maryland.gov/msdc/S3_Projection.shtml v:averageRating=0 v:name="Maryland Male Labor Force Projections: 1970-2040" v:attribution="Maryland Department of Planning"

property e:mrce-5khr t:meta.view.owner v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:displayName=MDP

property e:mrce-5khr t:meta.view.tableauthor v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:roleName=editor v:displayName=MDP
```

## Top Records

```ls
| jurisdiction        | census_1970 | census_1980 | census_1990 | census_2000 | census_2010 | acs_2008_12 | projection_2015 | projection_2020 | projection_2025 | projection_2030 | projection_2035 | projection_2040 | 
| =================== | =========== | =========== | =========== | =========== | =========== | =========== | =============== | =============== | =============== | =============== | =============== | =============== | 
| MARYLAND            | 1035929     | 1188276     | 1401893     | 1418491     | 1615040     | 1624930     | 1687470         | 1735900         | 1772890         | 1803640         | 1833600         | 1873080         | 
| Allegany County     | 20192       | 19926       | 17746       | 17520       | 17470       | 17429       | 17530           | 17760           | 18100           | 18490           | 18780           | 19160           | 
| Anne Arundel County | 86355       | 114773      | 137163      | 144505      | 158780      | 159567      | 163730          | 167280          | 168930          | 170760          | 172830          | 175620          | 
| Baltimore City      | 216069      | 185835      | 175738      | 136102      | 147990      | 148119      | 155120          | 160260          | 164240          | 168230          | 172340          | 177200          | 
| Baltimore County    | 171413      | 196051      | 203173      | 201766      | 219830      | 221540      | 226270          | 228030          | 228030          | 227940          | 229450          | 232950          | 
| Calvert County      | 4942        | 9306        | 15452       | 20820       | 25630       | 25730       | 26510           | 27340           | 27480           | 27150           | 26880           | 27060           | 
| Caroline County     | 4892        | 6050        | 7461        | 7927        | 8980        | 8982        | 9130            | 9520            | 9940            | 10260           | 10630           | 11050           | 
| Carroll County      | 17467       | 27472       | 37522       | 43139       | 48650       | 48862       | 49250           | 50700           | 50210           | 49250           | 48660           | 49370           | 
| Cecil County        | 14934       | 15942       | 20527       | 23840       | 27890       | 27874       | 28650           | 29810           | 31750           | 33390           | 35110           | 37100           | 
| Charles County      | 11647       | 19874       | 30385       | 33535       | 40850       | 41209       | 43080           | 46500           | 49300           | 50830           | 52440           | 54360           | 
```