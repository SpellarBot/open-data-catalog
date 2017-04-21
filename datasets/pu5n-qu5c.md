# List of Streets and Intersections

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/list-of-streets-and-intersections-74996) |
| Metadata | [Link](https://data.sfgov.org/api/views/pu5n-qu5c) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/pu5n-qu5c/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/pu5n-qu5c/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | pu5n-qu5c |
| Name | List of Streets and Intersections |
| Attribution | San Francisco Department of Public Works |
| Category | Geographic Locations and Boundaries |
| Tags | allcnnsinorder, street, intersection, cnn, gis, basemap, all, order, cnns, in |
| Created | 2013-06-20T21:28:08Z |
| Publication Date | 2015-07-17T15:02:00Z |

## Description

A list of street segments and intersections sorted by street name and ascending address number. This data set is based on the City's GIS basemap and contains CNN id numbers for each record.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | numeric metric | cnn         | CNN        | number    | number      |
| Yes      | series tag     | streetname  | streetname | text      | text        |
| Yes      | series tag     | from_st     | from_st    | text      | text        |
| Yes      | series tag     | to_st       | to_st      | text      | text        |
| Yes      | series tag     | cardinal    | cardinal   | text      | text        |
| Yes      | series tag     | addrange    | addrange   | text      | text        |
| Yes      | series tag     | limits      | limits     | text      | text        |
| Yes      | series tag     | location    | location   | text      | text        |
| Yes      | numeric metric | theorder    | theOrder   | number    | number      |
| Yes      | numeric metric | lf_fadd     | LF_FADD    | number    | number      |
| Yes      | numeric metric | rt_fadd     | RT_FADD    | number    | number      |
| Yes      | numeric metric | lf_tadd     | LF_TADD    | number    | number      |
| Yes      | numeric metric | rt_tadd     | RT_TADD    | number    | number      |
| Yes      | numeric metric | from_cnn    | FROM_CNN   | number    | number      |
| Yes      | numeric metric | to_cnn      | TO_CNN     | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:pu5n-qu5c d:2015-07-17T08:01:04.000Z t:limits="BUSH ST \ MARKET ST intersection" t:from_st="BUSH ST \ MARKET ST" t:streetname="01ST ST" m:theorder=1 m:cnn=30731000

series e:pu5n-qu5c d:2015-07-17T08:01:04.000Z t:limits="BUSH ST \ MARKET ST to STEVENSON ST (1 - 34)" t:to_st="STEVENSON ST" t:from_st="BUSH ST \ MARKET ST" t:addrange="1 - 34" t:streetname="01ST ST" m:from_cnn=30731000 m:rt_tadd=34 m:theorder=2 m:lf_fadd=1 m:lf_tadd=19 m:rt_fadd=2 m:cnn=100000 m:to_cnn=24666000

series e:pu5n-qu5c d:2015-07-17T08:01:04.000Z t:limits="STEVENSON ST intersection" t:from_st="STEVENSON ST" t:streetname="01ST ST" m:theorder=3 m:cnn=24666000
```

## Meta Commands

```ls
metric m:cnn p:integer l:CNN t:dataTypeName=number

metric m:theorder p:integer l:theOrder t:dataTypeName=number

metric m:lf_fadd p:integer l:LF_FADD t:dataTypeName=number

metric m:rt_fadd p:integer l:RT_FADD t:dataTypeName=number

metric m:lf_tadd p:integer l:LF_TADD t:dataTypeName=number

metric m:rt_tadd p:integer l:RT_TADD t:dataTypeName=number

metric m:from_cnn p:integer l:FROM_CNN t:dataTypeName=number

metric m:to_cnn p:integer l:TO_CNN t:dataTypeName=number

entity e:pu5n-qu5c l:"List of Streets and Intersections" t:attribution="San Francisco Department of Public Works" t:url=https://data.sfgov.org/api/views/pu5n-qu5c

property e:pu5n-qu5c t:meta.view v:id=pu5n-qu5c v:category="Geographic Locations and Boundaries" v:attributionLink=http://www.sfdpw.org v:averageRating=0 v:name="List of Streets and Intersections" v:attribution="San Francisco Department of Public Works"

property e:pu5n-qu5c t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:pu5n-qu5c t:meta.view.owner v:id=rcpp-nrjq v:profileImageUrlMedium=/api/users/rcpp-nrjq/profile_images/THUMB v:profileImageUrlLarge=/api/users/rcpp-nrjq/profile_images/LARGE v:screenName="Public Works" v:profileImageUrlSmall=/api/users/rcpp-nrjq/profile_images/TINY v:displayName="Public Works"

property e:pu5n-qu5c t:meta.view.tableauthor v:id=rcpp-nrjq v:profileImageUrlMedium=/api/users/rcpp-nrjq/profile_images/THUMB v:profileImageUrlLarge=/api/users/rcpp-nrjq/profile_images/LARGE v:screenName="Public Works" v:profileImageUrlSmall=/api/users/rcpp-nrjq/profile_images/TINY v:roleName=editor v:displayName="Public Works"
```

## Top Records

```ls
| :updated_at | cnn      | streetname | from_st             | to_st         | cardinal | addrange  | limits                                       | location | theorder | lf_fadd | rt_fadd | lf_tadd | rt_tadd | from_cnn | to_cnn   | 
| =========== | ======== | ========== | =================== | ============= | ======== | ========= | ============================================ | ======== | ======== | ======= | ======= | ======= | ======= | ======== | ======== | 
| 1437120064  | 30731000 | 01ST ST    | BUSH ST \ MARKET ST |               |          |           | BUSH ST \ MARKET ST intersection             |          | 1        |         |         |         |         |          |          | 
| 1437120064  | 100000   | 01ST ST    | BUSH ST \ MARKET ST | STEVENSON ST  |          | 1 - 34    | BUSH ST \ MARKET ST to STEVENSON ST (1 - 34) |          | 2        | 1       | 2       | 19      | 34      | 30731000 | 24666000 | 
| 1437120064  | 24666000 | 01ST ST    | STEVENSON ST        |               |          |           | STEVENSON ST intersection                    |          | 3        |         |         |         |         |          |          | 
| 1437120064  | 24563000 | 01ST ST    | MISSION ST          |               |          |           | MISSION ST intersection                      |          | 9        |         |         |         |         |          |          | 
| 1437120064  | 104001   | 01ST ST    | MISSION ST          | TRANSBAY HUMP |          | 100 - 114 | MISSION ST to TRANSBAY HUMP (100 - 114)      |          | 10       | 101     | 100     | 113     | 114     | 24563000 | 54001000 | 
| 1437120064  | 54001000 | 01ST ST    | TRANSBAY HUMP       |               |          |           | TRANSBAY HUMP intersection                   |          | 11       |         |         |         |         |          |          | 
| 1437120064  | 104002   | 01ST ST    | TRANSBAY HUMP       | MINNA ST      |          | 115 - 134 | TRANSBAY HUMP to MINNA ST (115 - 134)        |          | 12       | 115     | 116     | 133     | 134     | 54001000 | 24542000 | 
| 1437120064  | 24542000 | 01ST ST    | MINNA ST            |               |          |           | MINNA ST intersection                        |          | 13       |         |         |         |         |          |          | 
| 1437120064  | 105000   | 01ST ST    | MINNA ST            | NATOMA ST     |          | 135 - 164 | MINNA ST to NATOMA ST (135 - 164)            |          | 14       | 135     | 136     | 163     | 164     | 24542000 | 24534000 | 
| 1437120064  | 24534000 | 01ST ST    | NATOMA ST           |               |          |           | NATOMA ST intersection                       |          | 15       |         |         |         |         |          |          | 
```