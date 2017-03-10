# Libraries State Of Hawaii

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/libraries-state-of-hawaii-a6f5d) |
| Metadata | [Link](https://data.hawaii.gov/api/views/jx86-2vch) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/jx86-2vch/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/jx86-2vch/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | jx86-2vch |
| Name | Libraries State Of Hawaii |
| Attribution | Hawaii State Public Library System |
| Category | Social Services |
| Tags | library |
| Created | 2012-06-26T23:27:22Z |
| Publication Date | 2012-06-27T01:33:29Z |
| Rows Updated | 2012-06-27T01:32:41Z |

## Description

Listing of the Public Libraries in the State of Hawaii

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type | Render Type |
| ======== | ============== | ============ | ============ | ========= | =========== |
| No       | time           | :updated_at  | updated_at   | meta_data | meta_data   |
| Yes      | series tag     | library_name | Library Name | text      | text        |
| Yes      | series tag     | county       | County       | text      | text        |
| Yes      | numeric metric | phone        | Phone        | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:jx86-2vch d:2012-06-26T16:27:31.000Z t:library_name="WAHIAWA PUBLIC LIBRARY" t:county=HONOLULU m:phone=8086226345

series e:jx86-2vch d:2012-06-26T16:27:31.000Z t:library_name="MOUNTAIN VIEW PUBLIC AND SCHOOL LIBRARY" t:county=HAWAII m:phone=8089686300

series e:jx86-2vch d:2012-06-26T16:27:31.000Z t:library_name="HILO PUBLIC LIBRARY" t:county=HAWAII m:phone=8089338888
```

## Meta Commands

```ls
metric m:phone p:long l:Phone t:dataTypeName=number

entity e:jx86-2vch l:"Libraries State Of Hawaii" t:attribution="Hawaii State Public Library System" t:url=https://data.hawaii.gov/api/views/jx86-2vch

property e:jx86-2vch t:meta.view v:id=jx86-2vch v:category="Social Services" v:attributionLink=http://hawaii.sdp.sirsi.net/custom/web/ v:averageRating=0 v:name="Libraries State Of Hawaii" v:attribution="Hawaii State Public Library System"

property e:jx86-2vch t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:jx86-2vch t:meta.view.owner v:id=4hgi-fxu8 v:screenName="Paola Saibene" v:displayName="Paola Saibene"

property e:jx86-2vch t:meta.view.tableauthor v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:roleName=publisher v:displayName="OIMT Open Data Coordinator"
```