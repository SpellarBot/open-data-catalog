# Libraries Internet Sessions By Year FY06 - FY11

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/libraries-internet-sessions-by-year-fy06-fy11-91283) |
| Metadata | [Link](https://data.hawaii.gov/api/views/e85y-zk7s) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/e85y-zk7s/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/e85y-zk7s/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | e85y-zk7s |
| Name | Libraries Internet Sessions By Year FY06 - FY11 |
| Attribution | Hawaii State Public Library System |
| Category | Social Services |
| Tags | internet |
| Created | 2012-06-27T00:30:25Z |
| Publication Date | 2012-06-27T00:35:34Z |

## Description

Number of internet sessions in use for Libraries throughout the State of Hawaii

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | library     | Library    | text      | text        |
| Yes      | numeric metric | fy11        | FY11       | number    | number      |
| Yes      | numeric metric | fy10        | FY10       | number    | number      |
| Yes      | numeric metric | fy09        | FY09       | number    | number      |
| Yes      | numeric metric | fy08        | FY08       | number    | number      |
| Yes      | numeric metric | fy07        | FY07       | number    | number      |
| Yes      | numeric metric | fy06        | FY06       | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:e85y-zk7s d:2012-06-26T17:30:27.000Z t:library=Hilo m:fy10=23377 m:fy11=26209 m:fy07=21164 m:fy08=25740 m:fy06=22100 m:fy09=18304

series e:e85y-zk7s d:2012-06-26T17:30:27.000Z t:library=Honokaa m:fy10=3459 m:fy11=3638 m:fy07=4472 m:fy08=2808 m:fy06=4940 m:fy09=2464

series e:e85y-zk7s d:2012-06-26T17:30:27.000Z t:library=Kailua-Kona m:fy10=8864 m:fy11=9345 m:fy07=10816 m:fy08=9464 m:fy06=9776 m:fy09=8909
```

## Meta Commands

```ls
metric m:fy11 p:integer l:FY11 t:dataTypeName=number

metric m:fy10 p:integer l:FY10 t:dataTypeName=number

metric m:fy09 p:integer l:FY09 t:dataTypeName=number

metric m:fy08 p:integer l:FY08 t:dataTypeName=number

metric m:fy07 p:integer l:FY07 t:dataTypeName=number

metric m:fy06 p:integer l:FY06 t:dataTypeName=number

entity e:e85y-zk7s l:"Libraries Internet Sessions By Year FY06 - FY11" t:attribution="Hawaii State Public Library System" t:url=https://data.hawaii.gov/api/views/e85y-zk7s

property e:e85y-zk7s t:meta.view v:id=e85y-zk7s v:category="Social Services" v:attributionLink=http://hawaii.sdp.sirsi.net/custom/web/ v:averageRating=0 v:name="Libraries Internet Sessions By Year FY06 - FY11" v:attribution="Hawaii State Public Library System"

property e:e85y-zk7s t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:e85y-zk7s t:meta.view.owner v:id=4hgi-fxu8 v:screenName="Paola Saibene" v:displayName="Paola Saibene"

property e:e85y-zk7s t:meta.view.tableauthor v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:roleName=publisher v:displayName="OIMT Open Data Coordinator"
```

## Top Records

```ls
| :updated_at | library       | fy11  | fy10  | fy09  | fy08  | fy07  | fy06  | 
| =========== | ============= | ===== | ===== | ===== | ===== | ===== | ===== | 
| 1340731827  | Hilo          | 26209 | 23377 | 18304 | 25740 | 21164 | 22100 | 
| 1340731827  | Honokaa       | 3638  | 3459  | 2464  | 2808  | 4472  | 4940  | 
| 1340731827  | Kailua-Kona   | 9345  | 8864  | 8909  | 9464  | 10816 | 9776  | 
| 1340731827  | Keaau         | 5462  | 5002  | 6834  | 7592  | 6188  | 6500  | 
| 1340731827  | Kealakekua    | 3127  | 2788  | 3074  | 3900  | 4524  | 4524  | 
| 1340731827  | Laupahoehoe   | 1618  | 1750  | 2512  | 2808  | 6240  | 6240  | 
| 1340731827  | Mountain View | 4206  | 3252  | 4343  | 5512  | 3380  | 3588  | 
| 1340731827  | Naalehu       | 3014  | 3112  | 2637  | 2080  | 2860  | 2704  | 
| 1340731827  | North Kohala  | 6258  |       |       |       |       |       | 
| 1340731827  | Pahala        | 1335  | 747   | 5275  | 7852  | 4836  | 7332  | 
```