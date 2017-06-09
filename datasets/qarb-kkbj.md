# NOPD Body Worn Camera Metadata

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nopd-body-worn-camera-metadata) |
| Metadata | [Link](https://data.nola.gov/api/views/qarb-kkbj) |
| Data: JSON | [100 Rows](https://data.nola.gov/api/views/qarb-kkbj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.nola.gov/api/views/qarb-kkbj/rows.csv?max_rows=100) |
| Host | data.nola.gov |
| Id | qarb-kkbj |
| Name | NOPD Body Worn Camera Metadata |
| Attribution | City of New Orleans Police Department |
| Category | Public Safety and Preparedness |
| Tags | police, body worn camera |
| Created | 2016-03-23T16:00:41Z |
| Publication Date | 2017-06-06T20:54:59Z |

## Description

This dataset represents the metadata related to body worn camera videos recorded by the New Orleans Police Department. This dataset is updated monthly.Disclaimer: The New Orleans Police Department does not guarantee (either expressed or implied) the accuracy, completeness, timeliness, or correct sequencing of the information. The New Orleans Police Department will not be responsible for any error or omission, or for the use of, or the results obtained from the use of this information. All data visualizations on maps should be considered approximate and attempts to derive specific addresses are strictly prohibited. The New Orleans Police Department is not responsible for the content of any off-site pages that are referenced by or that reference this web page other than an official City of New Orleans or New Orleans Police Department web page. The user specifically acknowledges that the New Orleans Police Department is not responsible for any defamatory, offensive, misleading, or illegal conduct of other users, links, or third parties and that the risk of injury from the foregoing rests entirely with the user. Any use of the information for commercial purposes is strictly prohibited. The unauthorized use of the words "New Orleans Police Department," "NOPD," or any colorable imitation of these words or the unauthorized use of the New Orleans Police Department logo is unlawful. This web page does not, in any way, authorize such use.

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                      | Data Type | Render Type |
| ======== | ============== | ========================= | ========================= | ========= | =========== |
| No       | time           | :updated_at               | updated_at                | meta_data | meta_data   |
| Yes      | series tag     | evidence_id               | evidence_id               | text      | text        |
| Yes      | series tag     | status                    | status                    | text      | text        |
| Yes      | series tag     | title                     | title                     | text      | text        |
| Yes      | series tag     | id_external               | id_external               | text      | text        |
| No       |                | date_uploaded             | date_uploaded             | text      | text        |
| No       |                | created_date_record_start | created_date_record_start | text      | text        |
| No       |                | date_record_end           | date_record_end           | text      | text        |
| No       |                | date_deleted              | date_deleted              | text      | text        |
| Yes      | numeric metric | size_mb                   | size_mb                   | number    | number      |
| Yes      | numeric metric | duration_seconds          | duration_seconds          | number    | number      |
| Yes      | series tag     | deletion_type             | deletion_type             | text      | text        |
| Yes      | series tag     | location                  | location                  | text      | text        |
| Yes      | numeric metric | latitude                  | latitude                  | number    | number      |
| Yes      | numeric metric | longitude                 | longitude                 | number    | number      |
| Yes      | series tag     | police_district           | police_district           | text      | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = date_uploaded,created_date_record_start,date_record_end,date_deleted
```

## Data Commands

```ls
series e:qarb-kkbj d:2016-11-04T15:10:49.000Z t:title="2424 CUMBERLAND CT" t:id_external=J-34739-16 t:police_district=4 t:location="(29.9295015, -89.99376245)" t:status=Active t:evidence_id=6115BE71-B124-42DD-878B-929294147540 m:duration_seconds=633 m:longitude=-89.99376245 m:latitude=29.9295015 m:size_mb=290.207674026489

series e:qarb-kkbj d:2016-11-04T15:10:49.000Z t:title="12330 I 10 Service Rd" t:id_external=J-34718-16 t:police_district=7 t:location="(30.04856073, -89.95355841)" t:status=Active t:evidence_id=95A722B6-8071-4971-99AF-1785CAF838B6 m:duration_seconds=531 m:longitude=-89.95355841 m:latitude=30.04856073 m:size_mb=212.800652503967

series e:qarb-kkbj d:2016-11-04T15:10:49.000Z t:title="3250 GEN DE GAULLE" t:id_external=J-35484-16 t:police_district=4 t:location="(29.92608918, -90.02256707)" t:status=Active t:evidence_id=92EDCF2A-1BCF-469C-A8E0-B7C098993781 m:duration_seconds=837 m:longitude=-90.02256707 m:latitude=29.92608918 m:size_mb=376.76686668396
```

## Meta Commands

```ls
metric m:size_mb p:long l:size_mb t:dataTypeName=number

metric m:duration_seconds p:long l:duration_seconds t:dataTypeName=number

metric m:latitude p:long l:latitude t:dataTypeName=number

metric m:longitude p:long l:longitude t:dataTypeName=number

entity e:qarb-kkbj l:"NOPD Body Worn Camera Metadata" t:attribution="City of New Orleans Police Department" t:url=https://data.nola.gov/api/views/qarb-kkbj

property e:qarb-kkbj t:meta.view d:2017-06-09T13:53:37.355Z v:id=qarb-kkbj v:category="Public Safety and Preparedness" v:averageRating=0 v:name="NOPD Body Worn Camera Metadata" v:attribution="City of New Orleans Police Department"

property e:qarb-kkbj t:meta.view.license d:2017-06-09T13:53:37.355Z v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:qarb-kkbj t:meta.view.owner d:2017-06-09T13:53:37.355Z v:id=uqfu-rapx v:screenName="Enterprise Information Data Team" v:displayName="Enterprise Information Data Team"

property e:qarb-kkbj t:meta.view.tableauthor d:2017-06-09T13:53:37.355Z v:id=uqfu-rapx v:screenName="Enterprise Information Data Team" v:roleName=publisher v:displayName="Enterprise Information Data Team"

property e:qarb-kkbj t:meta.view.metadata.custom_fields.common_core d:2017-06-09T13:53:37.355Z v:Contact_Email=data@nola.gov
```

## Top Records

```ls
| :updated_at | evidence_id                          | status | title                   | id_external | date_uploaded                 | created_date_record_start     | date_record_end               | date_deleted | size_mb            | duration_seconds | deletion_type | location                    | latitude           | longitude           | police_district | 
| =========== | ==================================== | ====== | ======================= | =========== | ============================= | ============================= | ============================= | ============ | ================== | ================ | ============= | =========================== | ================== | =================== | =============== | 
| 1478272249  | 6115BE71-B124-42DD-878B-929294147540 | Active | 2424 CUMBERLAND CT      | J-34739-16  | 2016-11-01T07:08:53.549-05:00 | 2016-10-31T23:59:53.000-05:00 | 2016-11-01T00:10:26.000-05:00 |              | 290.20767402648897 | 633              |               | (29.9295015, -89.99376245)  | 29.929501500000001 | -89.993762450000006 | 4               | 
| 1478272249  | 95A722B6-8071-4971-99AF-1785CAF838B6 | Active | 12330 I 10 Service Rd   | J-34718-16  | 2016-11-01T07:05:45.091-05:00 | 2016-10-31T23:58:49.000-05:00 | 2016-11-01T00:07:40.000-05:00 |              | 212.800652503967   | 531              |               | (30.04856073, -89.95355841) | 30.048560729999998 | -89.953558409999999 | 7               | 
| 1478272249  | 92EDCF2A-1BCF-469C-A8E0-B7C098993781 | Active | 3250 GEN DE GAULLE      | J-35484-16  | 2016-11-01T07:47:01.896-05:00 | 2016-10-31T23:58:28.000-05:00 | 2016-11-01T00:12:25.000-05:00 |              | 376.76686668396002 | 837              |               | (29.92608918, -90.02256707) | 29.926089180000002 | -90.022567069999994 | 4               | 
| 1478272249  | 58B9C163-ED2D-4E34-A017-9F0DB44DF4E5 | Active | 3250 GEN DE GAULLE      | J-35484-16  | 2016-11-01T07:43:16.388-05:00 | 2016-10-31T23:58:28.000-05:00 | 2016-11-01T00:16:58.000-05:00 |              | 534.93937492370605 | 1110             |               | (29.92608918, -90.02256707) | 29.926089180000002 | -90.022567069999994 | 4               | 
| 1478272249  | 1C5245BC-0D52-4F24-9447-3861628E0BCC | Active | CANAL at BOURBON        | J-35494-16  | 2016-11-01T07:02:17.699-05:00 | 2016-10-31T23:56:49.000-05:00 | 2016-10-31T23:58:34.000-05:00 |              | 60.423467636108398 | 105              |               |                             |                    |                     |                 | 
| 1478272249  | 7237FE10-8519-4688-8AE6-8892652999C7 | Active | Bourbon/Canal           | J-35494-16  | 2016-11-01T08:49:30.126-05:00 | 2016-10-31T23:56:49.000-05:00 | 2016-11-01T00:16:41.000-05:00 |              | 633.74926185607899 | 1192             |               |                             |                    |                     |                 | 
| 1478272249  | 2FB1362F-EE16-4096-ACE1-75C372E1A574 | Active | 1836 bayou rd           | J-35285-16  | 2016-11-01T07:21:46.411-05:00 | 2016-10-31T23:56:30.000-05:00 | 2016-11-01T00:26:30.000-05:00 |              | 993.54000568389904 | 1800             |               | (29.96909773, -90.07164265) | 29.969097730000001 | -90.071642650000001 | 1               | 
| 1478272249  | B27B0D97-59EE-4CB7-884E-5F5F13848FCF | Active | 1501 PAULINE            | J-35487-16  | 2016-11-01T09:17:30.899-05:00 | 2016-10-31T23:56:13.000-05:00 | 2016-11-01T00:02:19.000-05:00 |              | 198.90960693359401 | 366              |               | (29.97015403, -90.03575255) | 29.97015403        | -90.035752549999998 | 5               | 
| 1478272249  | 8E4F918F-68DE-4B63-B2DB-C9DA53709520 | Active | Pauger At N Claiborne   | J-35500-16  | 2016-11-01T13:49:13.865-05:00 | 2016-10-31T23:54:38.000-05:00 | 2016-10-31T23:58:23.000-05:00 |              | 117.91436862945601 | 225              |               | (29.97338137, -90.06081319) | 29.973381369999998 | -90.060813190000005 | 5               | 
| 1478272249  | 781A60BF-D028-440B-BDA8-7BAC6D29DC78 | Active | CANAL AND ROBERT E. LEE | J-35314-16  | 2016-11-01T07:32:59.054-05:00 | 2016-10-31T23:54:14.000-05:00 | 2016-10-31T23:57:58.000-05:00 |              | 100.15054798126199 | 224              |               | (30.01947871, -90.10647196) | 30.019478710000001 | -90.106471959999993 | 3               | 
```