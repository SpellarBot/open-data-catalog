# NOPD In-Car Camera Metadata

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nopd-in-car-camera-metadata) |
| Metadata | [Link](https://data.nola.gov/api/views/md3v-ph3u) |
| Data: JSON | [100 Rows](https://data.nola.gov/api/views/md3v-ph3u/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.nola.gov/api/views/md3v-ph3u/rows.csv?max_rows=100) |
| Host | data.nola.gov |
| Id | md3v-ph3u |
| Name | NOPD In-Car Camera Metadata |
| Attribution | City of New Orleans Police Department |
| Category | Public Safety and Preparedness |
| Tags | police, car camera |
| Created | 2016-04-08T15:04:25Z |
| Publication Date | 2017-03-03T19:42:32Z |
| Rows Updated | 2017-03-03T19:42:19Z |

## Description

This dataset represents the metadata describing the process of transferring in-car camera videos recorded by the New Orleans Police Department from the server to DVDs in order to free up storage space. This dataset is updated monthly.Disclaimer: The New Orleans Police Department does not guarantee (either expressed or implied) the accuracy, completeness, timeliness, or correct sequencing of the information. The New Orleans Police Department will not be responsible for any error or omission, or for the use of, or the results obtained from the use of this information. All data visualizations on maps should be considered approximate and attempts to derive specific addresses are strictly prohibited. The New Orleans Police Department is not responsible for the content of any off-site pages that are referenced by or that reference this web page other than an official City of New Orleans or New Orleans Police Department web page. The user specifically acknowledges that the New Orleans Police Department is not responsible for any defamatory, offensive, misleading, or illegal conduct of other users, links, or third parties and that the risk of injury from the foregoing rests entirely with the user. Any use of the information for commercial purposes is strictly prohibited. The unauthorized use of the words "New Orleans Police Department," "NOPD," or any colorable imitation of these words or the unauthorized use of the New Orleans Police Department logo is unlawful. This web page does not, in any way, authorize such use.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type     | Render Type   |
| ======== | ============== | ================== | ================== | ============= | ============= |
| Yes      | series tag     | system_id          | system_id          | text          | number        |
| Yes      | series tag     | media_local_status | media_local_status | text          | text          |
| Yes      | series tag     | dvr_name           | dvr_name           | text          | text          |
| Yes      | numeric metric | duration           | duration           | number        | number        |
| Yes      | time           | time_media_start   | time_media_start   | calendar_date | calendar_date |
| Yes      | numeric metric | media_size_mb      | media_size_mb      | number        | number        |
```

## Time Field

```ls
Value = time_media_start
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:md3v-ph3u d:2016-03-22T07:28:31.000Z t:dvr_name=15091 t:media_local_status=Online t:system_id=265887 m:duration=0 m:media_size_mb=17

series e:md3v-ph3u d:2016-03-22T07:27:37.000Z t:dvr_name=15091 t:media_local_status=Online t:system_id=265886 m:duration=0 m:media_size_mb=19

series e:md3v-ph3u d:2016-03-22T07:00:32.000Z t:dvr_name=15091 t:media_local_status=Online t:system_id=265885 m:duration=1 m:media_size_mb=26
```

## Meta Commands

```ls
metric m:duration l:duration t:dataTypeName=number

metric m:media_size_mb p:integer l:media_size_mb t:dataTypeName=number

entity e:md3v-ph3u l:"NOPD In-Car Camera Metadata" t:attribution="City of New Orleans Police Department" t:url=https://data.nola.gov/api/views/md3v-ph3u

property e:md3v-ph3u t:meta.view v:id=md3v-ph3u v:category="Public Safety and Preparedness" v:averageRating=0 v:name="NOPD In-Car Camera Metadata" v:attribution="City of New Orleans Police Department"

property e:md3v-ph3u t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:md3v-ph3u t:meta.view.owner v:id=uqfu-rapx v:screenName="Enterprise Information Data Team" v:roleName=publisher v:displayName="Enterprise Information Data Team"

property e:md3v-ph3u t:meta.view.tableauthor v:id=uqfu-rapx v:screenName="Enterprise Information Data Team" v:roleName=publisher v:displayName="Enterprise Information Data Team"

property e:md3v-ph3u t:meta.view.metadata.custom_fields.common_core v:Contact_Email=data@nola.gov
```