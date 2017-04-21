# Watchable Wildlife Sites

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/watchable-wildlife-sites) |
| Metadata | [Link](https://data.ny.gov/api/views/hg7a-5ssi) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/hg7a-5ssi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/hg7a-5ssi/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | hg7a-5ssi |
| Name | Watchable Wildlife Sites |
| Attribution | New York State Department of Environmental Conservation |
| Category | Recreation |
| Tags | wildlife, watchable, viewing, outdoors |
| Created | 2013-02-14T18:50:38Z |
| Publication Date | 2013-03-01T19:03:26Z |

## Description

This data set contains point locations of wildlife viewing sites as shown in The New York Wildlife Viewing Guide. These sites are also known as Watchable Wildlife Sites.

## Columns

```ls
| Included | Schema Type | Field Name  | Name                     | Data Type | Render Type |
| ======== | =========== | =========== | ======================== | ========= | =========== |
| No       | time        | :updated_at | updated_at               | meta_data | meta_data   |
| Yes      | series tag  | booknum     | Site Number              | text      | number      |
| Yes      | series tag  | wwregion    | Region                   | text      | text        |
| Yes      | series tag  | owner       | Owner                    | text      | text        |
| Yes      | series tag  | ownership   | Ownership, Full Name     | text      | text        |
| Yes      | series tag  | name        | Site Name                | text      | text        |
| Yes      | series tag  | manager     | Property Manager         | text      | text        |
| Yes      | series tag  | brochure_n  | DEC Brochure Site Number | text      | text        |
| No       |             | point_x     | Longitude                | number    | number      |
| No       |             | point_y     | Latitude                 | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = point_x,point_y
```

## Data Commands

```ls
series e:hg7a-5ssi d:2013-02-20T19:05:11.000Z t:manager=same t:ownership="NYS DEC" t:brochure_n=NE-18 t:name="North-South Lake State Campground" t:owner=DEC t:booknum=1 t:wwregion=One:Catskills m:row_number.hg7a-5ssi=1

series e:hg7a-5ssi d:2013-02-20T19:05:11.000Z t:manager="Palisades Interstate Park Commission" t:ownership="NYS Parks" t:brochure_n=SE-03 t:name="Minnewaska State Park Preserve" t:owner=DEC t:booknum=2 t:wwregion=One:Catskills m:row_number.hg7a-5ssi=2

series e:hg7a-5ssi d:2013-02-20T19:05:11.000Z t:manager=same t:ownership="NYS DEC" t:brochure_n=SE-02 t:name="Bashakill WMA" t:owner=DEC t:booknum=3 t:wwregion=One:Catskills m:row_number.hg7a-5ssi=3
```

## Meta Commands

```ls
metric m:row_number.hg7a-5ssi p:long l:"Row Number"

entity e:hg7a-5ssi l:"Watchable Wildlife Sites" t:attribution="New York State Department of Environmental Conservation" t:url=https://data.ny.gov/api/views/hg7a-5ssi

property e:hg7a-5ssi t:meta.view v:id=hg7a-5ssi v:category=Recreation v:attributionLink=http://www.dec.ny.gov/outdoor/55423.html v:averageRating=0 v:name="Watchable Wildlife Sites" v:attribution="New York State Department of Environmental Conservation"

property e:hg7a-5ssi t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:hg7a-5ssi t:meta.view.tableauthor v:id=jtha-fqbi v:screenName="OPEN DATA NY Admin" v:roleName=publisher v:displayName="OPEN DATA NY Admin"

property e:hg7a-5ssi t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| :updated_at | booknum | wwregion                | owner | ownership                                     | name                                           | manager                              | brochure_n | point_x       | point_y      | 
| =========== | ======= | ======================= | ===== | ============================================= | ============================================== | ==================================== | ========== | ============= | ============ | 
| 1361387111  | 1       | One:Catskills           | DEC   | NYS DEC                                       | North-South Lake State Campground              | same                                 | NE-18      | -74.056191209 | 42.201922909 | 
| 1361387111  | 2       | One:Catskills           | DEC   | NYS Parks                                     | Minnewaska State Park Preserve                 | Palisades Interstate Park Commission | SE-03      | -74.204341458 | 41.735836691 | 
| 1361387111  | 3       | One:Catskills           | DEC   | NYS DEC                                       | Bashakill WMA                                  | same                                 | SE-02      | -74.510764916 | 41.54541304  | 
| 1361387111  | 4       | One:Catskills           | DEC   | NYS DEC                                       | Mongaup Valley WMA - Eagle Observation Area    | NTS DEC & Eldred Preserve            | SE-01      | -74.785694528 | 41.554608396 | 
| 1361387111  | 5       | Two: applachian Plateau | DEC   | NYS DEC                                       | Rogers Environmental Education Center          | same                                 | NE-12      | -75.529140225 | 42.695155934 | 
| 1361387111  | 6       | Two: applachian Plateau | DEC   | NYS DEC                                       | Chenango Valley State Park                     | same                                 | W-21       | -75.819293131 | 42.216497293 | 
| 1361387111  | 7       | Two: applachian Plateau | DEC   | Waterman Conservation Education Center - Inc. | Fred L. Waterman Conservation Education Center | same                                 | W-20       | -76.17032086  | 42.081758951 | 
| 1361387111  | 8       | Two: applachian Plateau | DEC   | NYS Parks                                     | Buttermilk Falls State Park                    | same                                 | W-19       | -76.523816914 | 42.417169865 | 
| 1361387111  | 9       | Two: applachian Plateau | DEC   | Spencer Crest Nature Center - Inc.            | Spencer Crest Nature Center                    | same                                 | W-14       | -77.081722635 | 42.120999929 | 
| 1361387111  | 10      | Two: applachian Plateau | DEC   | The Nature Conservency                        | Moss Lake Preserve                             | same                                 | W-09       | -78.186745162 | 42.40062915  | 
```