# NYC Greenthumb Community Gardens

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nyc-greenthumb-community-gardens-66d35) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/ajxm-kzmj) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/ajxm-kzmj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/ajxm-kzmj/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | ajxm-kzmj |
| Name | NYC Greenthumb Community Gardens |
| Attribution | Department of Parks and Recreation (DPR) |
| Category | Environment |
| Tags | dpr, nyc greenthumb community gardens, sustainability, green, market, community, mayors office, healthy living |
| Created | 2012-06-27T16:59:38Z |
| Publication Date | 2013-06-21T19:42:47Z |

## Description

Listing of NYC Greenthumb community gardens

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type | Render Type |
| ======== | =========== | ================ | ================ | ========= | =========== |
| No       | time        | :updated_at      | updated_at       | meta_data | meta_data   |
| Yes      | series tag  | propid           | PropID           | text      | text        |
| Yes      | series tag  | boro             | Boro             | text      | text        |
| Yes      | series tag  | community_board  | Community Board  | text      | text        |
| Yes      | series tag  | council_district | Council District | text      | number      |
| Yes      | series tag  | garden_name      | Garden Name      | text      | text        |
| No       |             | address          | Address          | text      | text        |
| Yes      | series tag  | size             | Size             | text      | text        |
| Yes      | series tag  | jurisdiction     | Jurisdiction     | text      | text        |
| Yes      | series tag  | neighborhoodname | NeighborhoodName | text      | text        |
| Yes      | series tag  | cross_streets    | Cross Streets    | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:ajxm-kzmj d:2012-06-27T09:59:40.000Z t:cross_streets="Avenues B & C" t:boro=M t:neighborhoodname="East Village" t:garden_name="11 BC Serenity Garden" t:council_district=2 t:propid=NA t:jurisdiction=DPR t:community_board=M03 t:size=0.054 m:row_number.ajxm-kzmj=1

series e:ajxm-kzmj d:2012-06-27T09:59:40.000Z t:cross_streets="Nostrand & New York Avenues" t:boro=B t:neighborhoodname="Crown Heights" t:garden_name="1100 Bergen Street Community Garden" t:council_district=36 t:propid=NA t:jurisdiction=PRI t:community_board=B08 t:size=0.207 m:row_number.ajxm-kzmj=2

series e:ajxm-kzmj d:2012-06-27T09:59:40.000Z t:cross_streets=Active t:boro=M t:neighborhoodname="East Harlem" t:garden_name="110th Street Block Association" t:council_district=9 t:propid=M382 t:jurisdiction=DPR t:community_board=M11 t:size=0.043 m:row_number.ajxm-kzmj=3
```

## Meta Commands

```ls
metric m:row_number.ajxm-kzmj p:long l:"Row Number"

entity e:ajxm-kzmj l:"NYC Greenthumb Community Gardens" t:attribution="Department of Parks and Recreation (DPR)" t:url=https://data.cityofnewyork.us/api/views/ajxm-kzmj

property e:ajxm-kzmj t:meta.view v:id=ajxm-kzmj v:category=Environment v:averageRating=0 v:name="NYC Greenthumb Community Gardens" v:attribution="Department of Parks and Recreation (DPR)"

property e:ajxm-kzmj t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:ajxm-kzmj t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | propid | boro | community_board | council_district | garden_name                                                  | address                   | size  | jurisdiction | neighborhoodname | cross_streets                      | 
| =========== | ====== | ==== | =============== | ================ | ============================================================ | ========================= | ===== | ============ | ================ | ================================== | 
| 1340791180  | NA     | M    | M03             | 2                | 11 BC Serenity Garden                                        | 626 East 11th Street      | 0.054 | DPR          | East Village     | Avenues B & C                      | 
| 1340791180  | NA     | B    | B08             | 36               | 1100 Bergen Street Community Garden                          | 1101 & 1105 Bergen Street | 0.207 | PRI          | Crown Heights    | Nostrand & New York Avenues        | 
| 1340791180  | M382   | M    | M11             | 9                | 110th Street Block Association                               | 1651 Madison Avenue       | 0.043 | DPR          | East Harlem      | Active                             | 
| 1340791180  | M331   | M    | M11             | 8                | 117th Street Community Garden                                | 172 E 117th Street        | 0.080 | DPR          | East Harlem      | Active                             | 
| 1340791180  | NA     | M    | M03             | 2                | 11th Street Community Garden                                 | 422 East 11th Street      | 0.054 | TPL          | East Village     | 1st Avenue & Avenue A              | 
| 1340791180  | NA     | X    | X12             | 15               | 211th Street Block Association.                              | Carlisle Place            | 0.182 | NYRP         |                  | At E. 211th Street                 | 
| 1340791180  | NA     | X    | X06             | 15               | 2120 Mapes Avenue HDFC                                       | 2124 Mapes Avenue         | 0.151 | TPL          |                  | At E. 181st Street                 | 
| 1340791180  | B535   | B    | B05             | 42               | 400 Montauk Avenue Block Association. (Ismael Vega y Amigos) | New Lots Avenue           | 0.091 | DPR          | East New York    | Active                             | 
| 1340791180  | M313A  | M    | M03             | 1                | 5th Street Slope Garden Club                                 | 626-27 East 5th Street    | 0.031 | DPR          | East Village     | Active                             | 
| 1340791180  | NA     | B    | B07             | 38               | 6/15 Green                                                   | 274 15th Street           | 0.287 | TPL          | Park Slope       | corner of 6th Avenue & 15th Street | 
```