# Maryland Historical and Projected Households by Jurisdiction

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/maryland-historical-and-projected-households-by-jurisdiction-097f5) |
| Metadata | [Link](https://data.maryland.gov/api/views/7wje-bxqb) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/7wje-bxqb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/7wje-bxqb/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | 7wje-bxqb |
| Name | Maryland Historical and Projected Households by Jurisdiction |
| Attribution | Maryland Department of Planning |
| Category | Planning |
| Tags | households, projections, historical, planning, mdp |
| Created | 2014-09-02T20:39:40Z |
| Publication Date | 2014-09-02T20:41:09Z |

## Description

Households Projections for Maryland and the jurisdictions - historical households 1970-2010; projections out to 2040. Projections prepared by the Maryland Department of Planning, July 2014

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
series e:7wje-bxqb d:2014-09-02T13:39:43.000Z t:year=MARYLAND m:projection_2020=2360125 m:projection_2035=2639475 m:census_1980=1460865 m:census_2000=1980859 m:census_1990=1748991 m:census_2010=2156425 m:projection_2040=2698850 m:projection_2030=2567275 m:projection_2025=2470025 m:projection_2015=2247775 m:census_1970=1174933

series e:7wje-bxqb d:2014-09-02T13:39:43.000Z t:year="Allegany County" m:projection_2020=29875 m:projection_2035=31375 m:census_1980=29669 m:census_2000=29322 m:census_1990=29634 m:census_2010=29175 m:projection_2040=31600 m:projection_2030=31100 m:projection_2025=30475 m:projection_2015=29375 m:census_1970=27857

series e:7wje-bxqb d:2014-09-02T13:39:43.000Z t:year="Anne Arundel County" m:projection_2020=220500 m:projection_2035=240575 m:census_1980=121028 m:census_2000=178670 m:census_1990=149114 m:census_2010=199375 m:projection_2040=244350 m:projection_2030=235675 m:projection_2025=229100 m:projection_2015=209925 m:census_1970=81100
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

entity e:7wje-bxqb l:"Maryland Historical and Projected Households by Jurisdiction" t:attribution="Maryland Department of Planning" t:url=https://data.maryland.gov/api/views/7wje-bxqb

property e:7wje-bxqb t:meta.view v:id=7wje-bxqb v:category=Planning v:attributionLink=http://planning.maryland.gov/msdc/S3_Projection.shtml v:averageRating=0 v:name="Maryland Historical and Projected Households by Jurisdiction" v:attribution="Maryland Department of Planning"

property e:7wje-bxqb t:meta.view.owner v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:displayName=MDP

property e:7wje-bxqb t:meta.view.tableauthor v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:roleName=editor v:displayName=MDP
```

## Top Records

```ls
| :updated_at | year                | census_1970 | census_1980 | census_1990 | census_2000 | census_2010 | projection_2015 | projection_2020 | projection_2025 | projection_2030 | projection_2035 | projection_2040 | 
| =========== | =================== | =========== | =========== | =========== | =========== | =========== | =============== | =============== | =============== | =============== | =============== | =============== | 
| 1409665183  | MARYLAND            | 1174933     | 1460865     | 1748991     | 1980859     | 2156425     | 2247775         | 2360125         | 2470025         | 2567275         | 2639475         | 2698850         | 
| 1409665183  | Allegany County     | 27857       | 29669       | 29634       | 29322       | 29175       | 29375           | 29875           | 30475           | 31100           | 31375           | 31600           | 
| 1409665183  | Anne Arundel County | 81100       | 121028      | 149114      | 178670      | 199375      | 209925          | 220500          | 229100          | 235675          | 240575          | 244350          | 
| 1409665183  | Baltimore City      | 289349      | 281414      | 276484      | 257996      | 249900      | 254925          | 261975          | 270025          | 275425          | 279575          | 283900          | 
| 1409665183  | Baltimore County    | 184890      | 237371      | 268280      | 299877      | 316725      | 323625          | 333475          | 341250          | 345925          | 350775          | 357175          | 
| 1409665183  | Calvert County      | 5540        | 10731       | 16986       | 25447       | 30875       | 32225           | 34325           | 36125           | 37350           | 37950           | 38125           | 
| 1409665183  | Caroline County     | 6360        | 8219        | 9983        | 11097       | 12150       | 12550           | 13475           | 14425           | 15350           | 16250           | 17150           | 
| 1409665183  | Carroll County      | 19623       | 30631       | 42248       | 52503       | 59775       | 61325           | 65025           | 68025           | 70000           | 71125           | 72075           | 
| 1409665183  | Cecil County        | 14242       | 19364       | 24725       | 31223       | 36875       | 38525           | 40825           | 44700           | 47700           | 50425           | 52875           | 
| 1409665183  | Charles County      | 12098       | 21378       | 32950       | 41668       | 51225       | 55375           | 62350           | 69475           | 74900           | 79400           | 83275           | 
```