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
| Publication Date | 2017-03-03T20:04:43Z |
| Rows Updated | 2017-03-03T20:03:47Z |

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
| Yes      | series tag     | created_date_record_start | created_date_record_start | text      | text        |
| No       |                | date_record_end           | date_record_end           | text      | text        |
| No       |                | date_deleted              | date_deleted              | text      | text        |
| Yes      | numeric metric | size_mb                   | size_mb                   | number    | number      |
| Yes      | numeric metric | duration_seconds          | duration_seconds          | number    | number      |
| Yes      | series tag     | deletion_type             | deletion_type             | text      | text        |
| No       |                | location                  | location                  | text      | text        |
| No       |                | latitude                  | latitude                  | number    | number      |
| No       |                | longitude                 | longitude                 | number    | number      |
| Yes      | series tag     | police_district           | police_district           | text      | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = location,latitude,longitude,date_uploaded,date_record_end,date_deleted
```

## Data Commands

```ls
series e:qarb-kkbj d:2016-11-04T15:10:49.000Z t:title="2424 CUMBERLAND CT" t:id_external=J-34739-16 t:police_district=4 t:status=Active t:created_date_record_start=2016-10-31T23:59:53.000-05:00 t:evidence_id=6115BE71-B124-42DD-878B-929294147540 m:duration_seconds=633 m:size_mb=290.207674026489

series e:qarb-kkbj d:2016-11-04T15:10:49.000Z t:title="12330 I 10 Service Rd" t:id_external=J-34718-16 t:police_district=7 t:status=Active t:created_date_record_start=2016-10-31T23:58:49.000-05:00 t:evidence_id=95A722B6-8071-4971-99AF-1785CAF838B6 m:duration_seconds=531 m:size_mb=212.800652503967

series e:qarb-kkbj d:2016-11-04T15:10:49.000Z t:title="3250 GEN DE GAULLE" t:id_external=J-35484-16 t:police_district=4 t:status=Active t:created_date_record_start=2016-10-31T23:58:28.000-05:00 t:evidence_id=92EDCF2A-1BCF-469C-A8E0-B7C098993781 m:duration_seconds=837 m:size_mb=376.76686668396
```

## Meta Commands

```ls
metric m:size_mb p:decimal l:size_mb t:dataTypeName=number

metric m:duration_seconds p:double l:duration_seconds t:dataTypeName=number

entity e:qarb-kkbj l:"NOPD Body Worn Camera Metadata" t:attribution="City of New Orleans Police Department" t:url=https://data.nola.gov/api/views/qarb-kkbj

property e:qarb-kkbj t:meta.view v:id=qarb-kkbj v:category="Public Safety and Preparedness" v:averageRating=0 v:name="NOPD Body Worn Camera Metadata" v:attribution="City of New Orleans Police Department"

property e:qarb-kkbj t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:qarb-kkbj t:meta.view.owner v:id=uqfu-rapx v:screenName="Enterprise Information Data Team" v:roleName=publisher v:displayName="Enterprise Information Data Team"

property e:qarb-kkbj t:meta.view.tableauthor v:id=uqfu-rapx v:screenName="Enterprise Information Data Team" v:roleName=publisher v:displayName="Enterprise Information Data Team"

property e:qarb-kkbj t:meta.view.metadata.custom_fields.common_core v:Contact_Email=data@nola.gov
```