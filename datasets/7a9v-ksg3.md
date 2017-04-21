# Water Right Records -- All Document Types

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/water-right-records-all-document-types) |
| Metadata | [Link](https://data.wa.gov/api/views/7a9v-ksg3) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/7a9v-ksg3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/7a9v-ksg3/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | 7a9v-ksg3 |
| Name | Water Right Records -- All Document Types |
| Attribution | Washington Department of Ecology |
| Category | Natural Resources & Environment |
| Tags | ecology, water rights |
| Created | 2013-08-08T19:15:30Z |
| Publication Date | 2014-10-22T20:58:21Z |

## Description

Active Water Right Applications, Permits, Certificates and Claims in Washington State

## Columns

```ls
| Included | Schema Type    | Field Name                       | Name                             | Data Type     | Render Type   |
| ======== | ============== | ================================ | ================================ | ============= | ============= |
| Yes      | series tag     | wr_doc_id                        | WR_DOC_ID                        | text          | number        |
| Yes      | series tag     | document_number                  | DOCUMENT_NUMBER                  | text          | text          |
| Yes      | series tag     | document_type                    | DOCUMENT_TYPE                    | text          | text          |
| Yes      | series tag     | purpose_list                     | PURPOSE_LIST                     | text          | text          |
| Yes      | series tag     | person_last_or_organization_name | PERSON_LAST_OR_ORGANIZATION_NAME | text          | text          |
| Yes      | time           | priority_date                    | Priority_Date                    | calendar_date | calendar_date |
| Yes      | numeric metric | cfs                              | CFS                              | number        | number        |
| Yes      | numeric metric | gpm                              | GPM                              | number        | number        |
| Yes      | numeric metric | domestic_units                   | DOMESTIC_UNITS                   | number        | number        |
| Yes      | numeric metric | acre_feet                        | ACRE FEET                        | number        | number        |
| Yes      | numeric metric | acre_irr                         | ACRE IRR                         | number        | number        |
| Yes      | series tag     | county_name                      | COUNTY_NAME                      | text          | text          |
| Yes      | numeric metric | wria                             | wria                             | number        | number        |
| Yes      | series tag     | wria_nm                          | wria_nm                          | text          | text          |
| Yes      | series tag     | cert_num                         | CERT_NUM                         | text          | number        |
| Yes      | series tag     | trs                              | TRS                              | text          | text          |
| Yes      | series tag     | quad_designation                 | QUAD_DESIGNATION                 | text          | text          |
| Yes      | series tag     | source_name                      | SOURCE_NAME                      | text          | text          |
| Yes      | series tag     | tributary_name                   | TRIBUTARY_NAME                   | text          | text          |
| Yes      | series tag     | image_url                        | IMAGE_URL                        | url           | url           |
| Yes      | series tag     | map_url                          | MAP_URL                          | url           | url           |
```

## Time Field

```ls
Value = priority_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:7a9v-ksg3 d:2989-08-25T00:00:00.000Z t:wria_nm="Middle Lake Roosevelt" t:quad_designation=SE/SW t:tributary_name="COLUMBIA RIVER" t:person_last_or_organization_name="Bonneville Power Administration" t:map_url="https://fortress.wa.gov/ecy/waterresources/map/WaterResourcesExplorer.aspx?wr_doc_id=5644838" t:document_type="Superceding Permit" t:trs=T36N/R37E-27 t:document_number=S3-28684 t:image_url="https://fortress.wa.gov/ecy/wrx/wrx/columbia/imageviewer.aspx?wr_doc_id=5644838&wr_doc_file_nr=S3-28684" t:wr_doc_id=5644838 t:purpose_list=FS t:source_name="SHERMAN CREEK" t:county_name=FERRY m:wria=58

series e:7a9v-ksg3 d:2974-02-26T00:00:00.000Z t:trs=T17N/R18E-24 t:document_number=G4-064800CL t:wria_nm="Upper Yakima" t:image_url="https://fortress.wa.gov/ecy/wrx/wrx/columbia/imageviewer.aspx?wr_doc_id=2062140&wr_doc_file_nr=G4-064800CL" t:wr_doc_id=2062140 t:purpose_list=DG t:person_last_or_organization_name=JOHNSON t:county_name=KITTITAS t:map_url="https://fortress.wa.gov/ecy/waterresources/map/WaterResourcesExplorer.aspx?wr_doc_id=2062140" t:document_type="Claim Short Form" m:wria=39

series e:7a9v-ksg3 d:2073-07-02T00:00:00.000Z t:trs=T14N/R17E-24 t:document_number=G4-031991CL t:wria_nm=Naches t:image_url="https://fortress.wa.gov/ecy/wrx/wrx/columbia/imageviewer.aspx?wr_doc_id=2068459&wr_doc_file_nr=G4-031991CL" t:wr_doc_id=2068459 t:purpose_list="DG ST" t:person_last_or_organization_name=LOW t:county_name=YAKIMA t:map_url="https://fortress.wa.gov/ecy/waterresources/map/WaterResourcesExplorer.aspx?wr_doc_id=2068459" t:document_type="Claim Short Form" m:wria=38
```

## Meta Commands

```ls
metric m:cfs p:double l:CFS t:dataTypeName=number

metric m:gpm p:integer l:GPM t:dataTypeName=number

metric m:domestic_units p:integer l:DOMESTIC_UNITS t:dataTypeName=number

metric m:acre_feet p:double l:"ACRE FEET" t:dataTypeName=number

metric m:acre_irr p:double l:"ACRE IRR" t:dataTypeName=number

metric m:wria p:integer l:wria t:dataTypeName=number

entity e:7a9v-ksg3 l:"Water Right Records -- All Document Types" t:attribution="Washington Department of Ecology" t:url=https://data.wa.gov/api/views/7a9v-ksg3

property e:7a9v-ksg3 t:meta.view v:id=7a9v-ksg3 v:category="Natural Resources & Environment" v:attributionLink=http://ecy.wa.gov v:averageRating=0 v:name="Water Right Records -- All Document Types" v:attribution="Washington Department of Ecology"

property e:7a9v-ksg3 t:meta.view.license v:name="Public Domain"

property e:7a9v-ksg3 t:meta.view.owner v:id=m4wk-vfvn v:profileImageUrlMedium=/api/users/m4wk-vfvn/profile_images/THUMB v:profileImageUrlLarge=/api/users/m4wk-vfvn/profile_images/LARGE v:screenName="Jeff Marti" v:profileImageUrlSmall=/api/users/m4wk-vfvn/profile_images/TINY v:lastNotificationSeenAt=1492023518 v:displayName="Jeff Marti"

property e:7a9v-ksg3 t:meta.view.tableauthor v:id=m4wk-vfvn v:profileImageUrlMedium=/api/users/m4wk-vfvn/profile_images/THUMB v:profileImageUrlLarge=/api/users/m4wk-vfvn/profile_images/LARGE v:screenName="Jeff Marti" v:profileImageUrlSmall=/api/users/m4wk-vfvn/profile_images/TINY v:roleName=publisher v:lastNotificationSeenAt=1492023518 v:displayName="Jeff Marti"
```

## Top Records

```ls
| wr_doc_id | document_number | document_type      | purpose_list | person_last_or_organization_name | priority_date       | cfs  | gpm  | domestic_units | acre_feet | acre_irr | county_name | wria | wria_nm               | cert_num | trs          | quad_designation | source_name      | tributary_name | image_url                                                                                                              | map_url                                                                                              | 
| ========= | =============== | ================== | ============ | ================================ | =================== | ==== | ==== | ============== | ========= | ======== | =========== | ==== | ===================== | ======== | ============ | ================ | ================ | ============== | ====================================================================================================================== | ==================================================================================================== | 
| 5644838   | S3-28684        | Superceding Permit | FS           | Bonneville Power Administration  | 2989-08-25T00:00:00 |      |      |                |           |          | FERRY       | 58   | Middle Lake Roosevelt |          | T36N/R37E-27 | SE/SW            | SHERMAN CREEK    | COLUMBIA RIVER | [https://fortress.wa.gov/ecy/wrx/wrx/columbia/imageviewer.aspx?wr_doc_id=5644838&wr_doc_file_nr=S3-28684, null]        | [https://fortress.wa.gov/ecy/waterresources/map/WaterResourcesExplorer.aspx?wr_doc_id=5644838, null] | 
| 2062140   | G4-064800CL     | Claim Short Form   | DG           | JOHNSON                          | 2974-02-26T00:00:00 |      |      |                |           |          | KITTITAS    | 39   | Upper Yakima          |          | T17N/R18E-24 |                  |                  |                | [https://fortress.wa.gov/ecy/wrx/wrx/columbia/imageviewer.aspx?wr_doc_id=2062140&wr_doc_file_nr=G4-064800CL, null]     | [https://fortress.wa.gov/ecy/waterresources/map/WaterResourcesExplorer.aspx?wr_doc_id=2062140, null] | 
| 2068459   | G4-031991CL     | Claim Short Form   | DG ST        | LOW                              | 2073-07-02T00:00:00 |      |      |                |           |          | YAKIMA      | 38   | Naches                |          | T14N/R17E-24 |                  |                  |                | [https://fortress.wa.gov/ecy/wrx/wrx/columbia/imageviewer.aspx?wr_doc_id=2068459&wr_doc_file_nr=G4-031991CL, null]     | [https://fortress.wa.gov/ecy/waterresources/map/WaterResourcesExplorer.aspx?wr_doc_id=2068459, null] | 
| 5843599   | CS4-23994C@1(C) | Change/ROE         | IR           | Camacho                          | 2013-12-07T00:00:00 | 0.02 |      |                | 5.2       | 1.3      | OKANOGAN    | 49   | Okanogan              |          | T31N/R24E-25 | SW/SE            | well G4-27968(A) |                | [https://fortress.wa.gov/ecy/wrx/wrx/columbia/imageviewer.aspx?wr_doc_id=5843599&wr_doc_file_nr=CS4-23994C@1(C), null] | [https://fortress.wa.gov/ecy/waterresources/map/WaterResourcesExplorer.aspx?wr_doc_id=5843599, null] | 
| 5843745   | G2-30623        | NewApp             | MU           | Spanaway Water Co                | 2013-07-23T00:00:00 |      | 4507 |                | 11007     |          | PIERCE      | 12   | Chambers-Clover       |          | T19N/R03E-29 |                  | ***6 wells       |                | [https://fortress.wa.gov/ecy/wrx/wrx/columbia/imageviewer.aspx?wr_doc_id=5843745&wr_doc_file_nr=G2-30623, null]        | [https://fortress.wa.gov/ecy/waterresources/map/WaterResourcesExplorer.aspx?wr_doc_id=5843745, null] | 
| 5843680   | S2-30622        | NewApp             | DS           | Miner                            | 2013-07-22T00:00:00 | 0.02 |      | 1              | 0.34      |          | THURSTON    | 14   | Kennedy-Goldsborough  |          | T18N/R03W-08 |                  | SUMMIT LAKE      |                | [https://fortress.wa.gov/ecy/wrx/wrx/columbia/imageviewer.aspx?wr_doc_id=5843680&wr_doc_file_nr=S2-30622, null]        | [https://fortress.wa.gov/ecy/waterresources/map/WaterResourcesExplorer.aspx?wr_doc_id=5843680, null] | 
| 5842797   | G4-35638        | NewApp             | DM IR        | Cresto                           | 2013-07-19T00:00:00 |      | 50   | 3              | 1.241     |          | KITTITAS    | 39   | Upper Yakima          |          | T20N/R14E-20 | N2/NW            | proposed 3       |                | [https://fortress.wa.gov/ecy/wrx/wrx/columbia/imageviewer.aspx?wr_doc_id=5842797&wr_doc_file_nr=G4-35638, null]        | [https://fortress.wa.gov/ecy/waterresources/map/WaterResourcesExplorer.aspx?wr_doc_id=5842797, null] | 
| 5843148   | CS4-629CTCL@1   | Change Application | IF           | US Bureau Reclamation - Yakima   | 2013-07-17T00:00:00 | 0    |      |                | 0         |          | BENTON      | 37   | Lower Yakima          |          | T08N/R24E-02 | N2/NE            | YAKIMA RIVER     |                | [https://fortress.wa.gov/ecy/wrx/wrx/columbia/imageviewer.aspx?wr_doc_id=5843148&wr_doc_file_nr=CS4-629CTCL@1, null]   | [https://fortress.wa.gov/ecy/waterresources/map/WaterResourcesExplorer.aspx?wr_doc_id=5843148, null] | 
| 5842717   | G4-35637        | NewApp             | DM IR        | Central Cascades Land Co         | 2013-07-17T00:00:00 |      | 100  | 7              | 2.896     |          | KITTITAS    | 39   | Upper Yakima          |          | T20N/R16E-31 |                  |                  |                | [https://fortress.wa.gov/ecy/wrx/wrx/columbia/imageviewer.aspx?wr_doc_id=5842717&wr_doc_file_nr=G4-35637, null]        | [https://fortress.wa.gov/ecy/waterresources/map/WaterResourcesExplorer.aspx?wr_doc_id=5842717, null] | 
| 5842450   | G4-35635        | NewApp             | DS IR        | Berg                             | 2013-07-16T00:00:00 |      |      | 1              | 0.414     |          | KITTITAS    | 39   | Upper Yakima          |          | T20N/R16E-26 |                  | APG200           |                | [https://fortress.wa.gov/ecy/wrx/wrx/columbia/imageviewer.aspx?wr_doc_id=5842450&wr_doc_file_nr=G4-35635, null]        | [https://fortress.wa.gov/ecy/waterresources/map/WaterResourcesExplorer.aspx?wr_doc_id=5842450, null] | 
```