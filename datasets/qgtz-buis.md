# Broadband Community Anchor Institution Listings

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/broadband-community-anchor-institution-listings-40d43) |
| Metadata | [Link](https://data.wa.gov/api/views/qgtz-buis) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/qgtz-buis/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/qgtz-buis/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | qgtz-buis |
| Name | Broadband Community Anchor Institution Listings |
| Attribution | Washington State Broadband Office |
| Category | Economics |
| Tags | broadband, community anchor |
| Created | 2015-01-27T22:33:23Z |
| Publication Date | 2015-01-27T23:22:23Z |

## Description

Broadband availability at Community Anchor Institutions, as collected by the Washington State Broadband Office for the State Broadband Initiative.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | objectid    | OBJECTID   | text      | number      |
| Yes      | series tag     | anchorname  | ANCHORNAME | text      | text        |
| Yes      | numeric metric | bldgnbr     | BLDGNBR    | number    | number      |
| Yes      | series tag     | predir      | PREDIR     | text      | text        |
| Yes      | series tag     | suffdir     | SUFFDIR    | text      | text        |
| Yes      | numeric metric | caicat      | CAICAT     | number    | number      |
| Yes      | series tag     | bbservice   | BBSERVICE  | text      | text        |
| Yes      | series tag     | publicwifi  | PublicWifi | text      | text        |
| Yes      | series tag     | url         | URL        | url       | url         |
| Yes      | numeric metric | transtech   | TRANSTECH  | number    | number      |
| Yes      | series tag     | fullfipsid  | FULLFIPSID | text      | number      |
| Yes      | series tag     | caiid       | CAIID      | text      | number      |
| Yes      | numeric metric | subscrbdow  | SubScrbDow | number    | number      |
| Yes      | numeric metric | subsrbup    | SubSrbUP   | number    | number      |
| Yes      | series tag     | datasource  | DataSource | text      | text        |
| Yes      | series tag     | bb_provide  | BB_Provide | text      | text        |
| Yes      | series tag     | district    | District   | text      | text        |
| Yes      | series tag     | updatedby   | UpdatedBy  | text      | text        |
| Yes      | series tag     | updatetitl  | UpdateTitl | text      | text        |
| Yes      | series tag     | updatephon  | UpdatePhon | text      | text        |
| Yes      | series tag     | updateemai  | UpdateEmai | email     | email       |
| Yes      | series tag     | updateorg   | UpdateOrg  | text      | text        |
| Yes      | series tag     | county      | County     | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:qgtz-buis d:2015-01-27T14:33:29.000Z t:bbservice=U t:fullfipsid=530459608003049 t:county=MASON t:anchorname="SOCK-Save Our County's Kids" t:objectid=9 t:datasource="CTC/Betty Buckley" m:caicat=7 m:transtech=-999

series e:qgtz-buis d:2015-01-27T14:33:29.000Z t:bbservice=U t:fullfipsid=530670101001044 t:county=THURSTON t:anchorname="Thurston County Literacy Network" t:objectid=13 t:datasource="CTC/Betty Buckley" m:caicat=7 m:transtech=-999

series e:qgtz-buis d:2015-01-27T14:34:57.000Z t:updateemai=miker@markreed.org t:bbservice=Y t:fullfipsid=530270006003008 t:predir=South t:county="GRAYS HARBOR" t:updatephon=360-495-3244 t:updatedby="Mike Rand" t:updateorg="Mark Reed Hospital" t:anchorname="Mark Reed Hospital" t:updatetitl="DIrector of Non Clinical Operations" t:bb_provide=ReachOne t:objectid=7 m:caicat=3 m:subscrbdow=7 m:transtech=30 m:bldgnbr=322 m:subsrbup=3
```

## Meta Commands

```ls
metric m:bldgnbr p:integer l:BLDGNBR t:dataTypeName=number

metric m:caicat p:integer l:CAICAT t:dataTypeName=number

metric m:transtech p:integer l:TRANSTECH t:dataTypeName=number

metric m:subscrbdow p:integer l:SubScrbDow t:dataTypeName=number

metric m:subsrbup p:integer l:SubSrbUP t:dataTypeName=number

entity e:qgtz-buis l:"Broadband Community Anchor Institution Listings" t:attribution="Washington State Broadband Office" t:url=https://data.wa.gov/api/views/qgtz-buis

property e:qgtz-buis t:meta.view v:id=qgtz-buis v:category=Economics v:attributionLink=http://broadband.wa.gov v:averageRating=0 v:name="Broadband Community Anchor Institution Listings" v:attribution="Washington State Broadband Office"

property e:qgtz-buis t:meta.view.license v:name="Public Domain"

property e:qgtz-buis t:meta.view.owner v:id=h2ue-vnnt v:profileImageUrlMedium=/api/users/h2ue-vnnt/profile_images/THUMB v:profileImageUrlLarge=/api/users/h2ue-vnnt/profile_images/LARGE v:screenName="OCIO-Will Saunders" v:profileImageUrlSmall=/api/users/h2ue-vnnt/profile_images/TINY v:displayName="OCIO-Will Saunders"

property e:qgtz-buis t:meta.view.tableauthor v:id=h2ue-vnnt v:profileImageUrlMedium=/api/users/h2ue-vnnt/profile_images/THUMB v:profileImageUrlLarge=/api/users/h2ue-vnnt/profile_images/LARGE v:screenName="OCIO-Will Saunders" v:profileImageUrlSmall=/api/users/h2ue-vnnt/profile_images/TINY v:roleName=publisher v:displayName="OCIO-Will Saunders"
```

## Top Records

```ls
| :updated_at | objectid | anchorname                        | bldgnbr | predir | suffdir   | caicat | bbservice | publicwifi | url          | transtech | fullfipsid      | caiid | subscrbdow | subsrbup | datasource                                         | bb_provide             | district | updatedby      | updatetitl                          | updatephon   | updateemai                 | updateorg          | county       | 
| =========== | ======== | ================================= | ======= | ====== | ========= | ====== | ========= | ========== | ============ | ========= | =============== | ===== | ========== | ======== | ================================================== | ====================== | ======== | ============== | =================================== | ============ | ========================== | ================== | ============ | 
| 1422369209  | 9        | SOCK-Save Our County's Kids       |         |        |           | 7      | U         |            | [null, null] | -999      | 530459608003049 |       |            |          | CTC/Betty Buckley                                  |                        |          |                |                                     |              |                            |                    | MASON        | 
| 1422369209  | 13       | Thurston County Literacy Network  |         |        |           | 7      | U         |            | [null, null] | -999      | 530670101001044 |       |            |          | CTC/Betty Buckley                                  |                        |          |                |                                     |              |                            |                    | THURSTON     | 
| 1422369297  | 7        | Mark Reed Hospital                | 322     | South  |           | 3      | Y         |            | [null, null] | 30        | 530270006003008 |       | 7          | 3        |                                                    | ReachOne               |          | Mike Rand      | DIrector of Non Clinical Operations | 360-495-3244 | miker@markreed.org         | Mark Reed Hospital | GRAYS HARBOR | 
| 1422369306  | 14       | TRIO Program                      | 600     | West   |           | 7      | U         |            | [null, null] | -999      | 530419707003001 |       |            |          | CTC/Betty Buckley                                  |                        |          |                |                                     |              |                            |                    | LEWIS        | 
| 1422369209  | 3        | WAHKIAKUM COUNTY SHERIFF'S OFFICE | 64      |        |           | 4      | U         |            | [null, null] | -999      | 530699501004041 |       |            |          | HSIP Freedom- 2007_11_09_WA_LawEnforcementQ407.shp |                        |          |                |                                     |              |                            |                    | WAHKIAKUM    | 
| 1422369314  | 4        | WOODLAND POLICE DEPARTMENT        | 100     |        |           | 4      | Y         |            | [null, null] | 50        | 530150015024029 |       |            |          | HSIP Freedom- 2007_11_09_WA_LawEnforcementQ407.shp | Cascade Networks, Inc. |          | Rob Stephenson | Chief                               | 3602256965   | stephensonr@woodlandpd.org | Woodland Police    | COWLITZ      | 
| 1422369321  | 17       | Longview Goodwill                 | 1362    |        |           | 7      | U         |            | [null, null] | -999      | 530150021002050 |       |            |          | CTC/Betty Buckley                                  |                        |          |                |                                     |              |                            |                    | COWLITZ      | 
| 1422369329  | 11       | Thurston County 4-H               | 720     |        | Southeast | 7      | U         |            | [null, null] | -999      | 530670112003045 |       |            |          | CTC/Betty Buckley                                  |                        |          |                |                                     |              |                            |                    | THURSTON     | 
| 1422369352  | 16       | Woodland Grange                   | 404     |        |           | 7      | U         |            | [null, null] | -999      | 530150015024016 |       |            |          | CTC/Betty Buckley                                  |                        |          |                |                                     |              |                            |                    | COWLITZ      | 
| 1422369365  | 18       | Mason County Literacy             | 133     | West   |           | 7      | U         |            | [null, null] | -999      | 530459608003056 |       |            |          | CTC/Betty Buckley                                  |                        |          |                |                                     |              |                            |                    | MASON        | 
```