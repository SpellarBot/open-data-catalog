# Compare Data And Documentation

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/compare-data-and-documentation) |
| Metadata | [Link](https://data.medicare.gov/api/views/bg9k-emty) |
| Data: JSON | [100 Rows](https://data.medicare.gov/api/views/bg9k-emty/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicare.gov/api/views/bg9k-emty/rows.csv?max_rows=100) |
| Host | data.medicare.gov |
| Id | bg9k-emty |
| Name | Compare Data And Documentation |
| Created | 2013-04-15T00:55:54Z |
| Publication Date | 2017-04-20T23:10:39Z |

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type     | Render Type   |
| ======== | ============== | ============= | ============= | ============= | ============= |
| Yes      | series tag     | page          | page          | text          | text          |
| Yes      | series tag     | resource_type | resource type | text          | text          |
| Yes      | series tag     | file          | file          | document      | document      |
| Yes      | time           | updated       | updated       | calendar_date | calendar_date |
| Yes      | series tag     | title         | title         | text          | text          |
| Yes      | series tag     | type          | type          | text          | text          |
| Yes      | series tag     | size          | size          | text          | text          |
| Yes      | numeric metric | order         | order         | number        | number        |
| Yes      | series tag     | dataset_id    | dataset ID    | text          | text          |
```

## Time Field

```ls
Value = updated
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:bg9k-emty d:2013-04-17T16:54:26.000Z t:title="Measure Dates" t:page=home-health-compare t:resource_type=supporting-documentation t:dataset_id=c886-nwpj t:type="Link to Dataset" m:order=3

series e:bg9k-emty d:2014-09-24T07:21:21.000Z t:title="View footnote crosswalk" t:page=hospital-compare t:resource_type=supporting-documentation t:dataset_id=y9us-9xdf t:type="Link to Dataset" m:order=1

series e:bg9k-emty d:2014-09-24T07:21:37.000Z t:title="Measure Dates" t:page=hospital-compare t:resource_type=supporting-documentation t:dataset_id=4j6d-yzce t:type="Link to Dataset" m:order=6
```

## Meta Commands

```ls
metric m:order p:long l:order t:dataTypeName=number

entity e:bg9k-emty l:"Compare Data And Documentation" t:url=https://data.medicare.gov/api/views/bg9k-emty

property e:bg9k-emty t:meta.view v:id=bg9k-emty v:averageRating=0 v:name="Compare Data And Documentation"

property e:bg9k-emty t:meta.view.owner v:id=x5jh-tg6w v:profileImageUrlMedium=/api/users/x5jh-tg6w/profile_images/THUMB v:profileImageUrlLarge=/api/users/x5jh-tg6w/profile_images/LARGE v:screenName="Takahiko Naito" v:profileImageUrlSmall=/api/users/x5jh-tg6w/profile_images/TINY v:lastNotificationSeenAt=1491331911 v:displayName="Takahiko Naito"

property e:bg9k-emty t:meta.view.tableauthor v:id=x5jh-tg6w v:profileImageUrlMedium=/api/users/x5jh-tg6w/profile_images/THUMB v:profileImageUrlLarge=/api/users/x5jh-tg6w/profile_images/LARGE v:screenName="Takahiko Naito" v:profileImageUrlSmall=/api/users/x5jh-tg6w/profile_images/TINY v:lastNotificationSeenAt=1491331911 v:displayName="Takahiko Naito"
```

## Top Records

```ls
| page                                      | resource_type            | file                                                                                                                              | updated             | title                                                 | type            | size   | order | dataset_id | 
| ========================================= | ======================== | ================================================================================================================================= | =================== | ===================================================== | =============== | ====== | ===== | ========== | 
| home-health-compare                       | supporting-documentation | [null, null, null, null]                                                                                                          |                     | Measure Dates                                         | Link to Dataset |        | 3     | c886-nwpj  | 
| hospital-compare                          | supporting-documentation | [null, null, null, null]                                                                                                          |                     | View footnote crosswalk                               | Link to Dataset |        | 1     | y9us-9xdf  | 
| hospital-compare                          | supporting-documentation | [null, null, null, null]                                                                                                          |                     | Measure Dates                                         | Link to Dataset |        | 6     | 4j6d-yzce  | 
| hospital-compare                          | supporting-documentation | [null, null, null, null]                                                                                                          |                     | Data Updates                                          | Link to Dataset |        | 3     | bzsr-4my4  | 
| medicare-s-helpful-contacts               | supporting-documentation | [application/pdf; charset=binary, K351c5QgH_FDO1ZUj5RAFKJtJb2jmQXNKj5oXhmLMRI, HelpfulContacts_FlatFiles.pdf, 176700]             |                     | Helpful Contacts Flat Files - Revised Format Download | PDF             | 173 KB | 2     |            | 
| nursing-home-compare                      | supporting-documentation | [application/vnd.ms-excel; charset=binary, 84e51934-7d03-4bde-b789-5360574703e9, DataMedicareGov_MetadataAllTabs_v09.xls, 180736] | 2016-01-28T00:00:00 | Downloadable Database Dictionary                      | XLS             | 150 KB | 1     |            | 
| physician-compare                         | supporting-documentation | [application/pdf; charset=binary, 2caecf35-104b-4252-b5e7-468809053abc, Physician_Compare_2014_Data_Dictionaries.pdf, 175335]     | 2016-06-30T00:00:00 | Downloadable Database Dictionary                      | PDF             | 175 KB | 1     |            | 
| inpatient-rehabilitation-facility-compare | supporting-documentation | [application/pdf; charset=binary, 09320dfa-220a-4334-9302-c7e0da298361, IRF Data Dictionary_Dec2016.pdf, 295732]                  | 2016-12-14T00:00:00 | Downloadable Database Dictionary                      | PDF             | 289 KB | 1     |            | 
| long-term-care-hospital-compare           | supporting-documentation | [application/pdf; charset=binary, a97d671e-e36d-49b8-b7a5-5a579f1e683a, LTCH Data Dictionary_Dec2016.pdf, 265119]                 | 2016-12-14T00:00:00 | Downloadable Database Dictionary                      | PDF             | 259 KB | 1     |            | 
| hospital-compare                          | csv                      | [application/zip; charset=binary, 6c902f45-e28b-42f5-9f96-ae9d1e583472, Hospital_Revised_Flatfiles.zip, 15982423]                 | 2016-12-19T00:00:00 |                                                       |                 |        |       |            | 
```