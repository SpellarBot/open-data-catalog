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

## Description

Listing of the Public Libraries in the State of Hawaii

## Columns

```ls
| Included | Schema Type | Field Name   | Name         | Data Type | Render Type |
| ======== | =========== | ============ | ============ | ========= | =========== |
| No       | time        | :updated_at  | updated_at   | meta_data | meta_data   |
| Yes      | series tag  | library_name | Library Name | text      | text        |
| Yes      | series tag  | county       | County       | text      | text        |
| Yes      | series tag  | phone        | Phone        | text      | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:jx86-2vch d:2012-06-26T16:27:31.000Z t:phone=8086226345 t:county=HONOLULU t:library_name="WAHIAWA PUBLIC LIBRARY" m:row_number.jx86-2vch=1

series e:jx86-2vch d:2012-06-26T16:27:31.000Z t:phone=8089686300 t:county=HAWAII t:library_name="MOUNTAIN VIEW PUBLIC AND SCHOOL LIBRARY" m:row_number.jx86-2vch=2

series e:jx86-2vch d:2012-06-26T16:27:31.000Z t:phone=8089338888 t:county=HAWAII t:library_name="HILO PUBLIC LIBRARY" m:row_number.jx86-2vch=3
```

## Meta Commands

```ls
metric m:row_number.jx86-2vch p:long l:"Row Number"

entity e:jx86-2vch l:"Libraries State Of Hawaii" t:attribution="Hawaii State Public Library System" t:url=https://data.hawaii.gov/api/views/jx86-2vch

property e:jx86-2vch t:meta.view d:2017-09-25T07:31:24.169Z v:averageRating=0 v:name="Libraries State Of Hawaii" v:attribution="Hawaii State Public Library System" v:attributionLink=http://hawaii.sdp.sirsi.net/custom/web/ v:id=jx86-2vch v:category="Social Services"

property e:jx86-2vch t:meta.view.license d:2017-09-25T07:31:24.169Z v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:jx86-2vch t:meta.view.owner d:2017-09-25T07:31:24.169Z v:displayName="Paola Saibene" v:id=4hgi-fxu8 v:screenName="Paola Saibene"

property e:jx86-2vch t:meta.view.tableauthor d:2017-09-25T07:31:24.169Z v:displayName="OIMT Open Data Coordinator" v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:roleName=publisher v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:id=a5cm-ukuw v:screenName="OIMT Open Data Coordinator" v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB
```

## Top Records

```ls
| :updated_at | library_name                            | county   | phone      | 
| =========== | ======================================= | ======== | ========== | 
| 1340728051  | WAHIAWA PUBLIC LIBRARY                  | HONOLULU | 8086226345 | 
| 1340728051  | MOUNTAIN VIEW PUBLIC AND SCHOOL LIBRARY | HAWAII   | 8089686300 | 
| 1340728051  | HILO PUBLIC LIBRARY                     | HAWAII   | 8089338888 | 
| 1340728051  | AINA HAINA PUBLIC LIBRARY               | HONOLULU | 8083772456 | 
| 1340728051  | WAIANAE PUBLIC LIBRARY                  | HONOLULU | 8086964257 | 
| 1340728051  | PRINCEVILLE PUBLIC LIBRARY              | KAUAI    | 8088261545 | 
| 1340728051  | LANAI PUBLIC AND SCHOOL LIBRARY         | MAUI     | 8085656996 | 
| 1340728051  | KIHEI PUBLIC LIBRARY                    | MAUI     | 8088756833 | 
| 1340728051  | AIEA PUBLIC LIBRARY                     | HONOLULU | 8084837333 | 
| 1340728051  | HONOKAA PUBLIC LIBRARY                  | HAWAII   | 8087757798 | 
```