# Data Archives

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/data-archives) |
| Metadata | [Link](https://data.medicare.gov/api/views/bdfu-yahz) |
| Data: JSON | [100 Rows](https://data.medicare.gov/api/views/bdfu-yahz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicare.gov/api/views/bdfu-yahz/rows.csv?max_rows=100) |
| Host | data.medicare.gov |
| Id | bdfu-yahz |
| Name | Data Archives |
| Created | 2014-04-15T15:55:49Z |
| Publication Date | 2017-04-12T12:19:42Z |

## Columns

```ls
| Included | Schema Type | Field Name              | Name                      | Data Type      | Render Type    |
| ======== | =========== | ======================= | ========================= | ============== | ============== |
| Yes      | series tag  | page                    | Page                      | drop_down_list | drop_down_list |
| Yes      | series tag  | dataset_title           | Dataset Title             | text           | text           |
| Yes      | series tag  | final                   | Final                     | checkbox       | checkbox       |
| Yes      | time        | archival_period         | Archival Period           | calendar_date  | calendar_date  |
| No       |             | archive_date_created_at | Archive Date / Created at | calendar_date  | calendar_date  |
| Yes      | series tag  | url                     | URL                       | url            | url            |
| Yes      | series tag  | file_format             | File Format               | text           | text           |
| Yes      | series tag  | file_size               | File Size                 | text           | text           |
```

## Time Field

```ls
Value = archival_period
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = archive_date_created_at
```

## Data Commands

```ls
series e:bdfu-yahz d:2001-06-01T00:00:00.000Z t:dataset_title=DFCArchive_20010601.zip t:file_size="303 KB" t:page=rxt6-ds8j t:file_format="Zip File" t:url=http://medicare.gov/download/DialysisFacilityCompare/2001/June/DFCArchive_20010601.zip m:row_number.bdfu-yahz=1

series e:bdfu-yahz d:2001-07-03T00:00:00.000Z t:dataset_title=DFCArchive_20010703.zip t:file_size="317 KB" t:page=rxt6-ds8j t:file_format="Zip File" t:url=http://medicare.gov/download/DialysisFacilityCompare/2001/July/DFCArchive_20010703.zip m:row_number.bdfu-yahz=2

series e:bdfu-yahz d:2001-08-08T00:00:00.000Z t:dataset_title=DFCArchive_20010808.zip t:file_size="312 KB" t:page=rxt6-ds8j t:file_format="Zip File" t:url=http://medicare.gov/download/DialysisFacilityCompare/2001/August/08/DFCArchive_20010808.zip m:row_number.bdfu-yahz=3
```

## Meta Commands

```ls
metric m:row_number.bdfu-yahz p:long l:"Row Number"

entity e:bdfu-yahz l:"Data Archives" t:url=https://data.medicare.gov/api/views/bdfu-yahz

property e:bdfu-yahz t:meta.view v:id=bdfu-yahz v:averageRating=0 v:name="Data Archives"

property e:bdfu-yahz t:meta.view.owner v:id=x5jh-tg6w v:profileImageUrlMedium=/api/users/x5jh-tg6w/profile_images/THUMB v:profileImageUrlLarge=/api/users/x5jh-tg6w/profile_images/LARGE v:screenName="Takahiko Naito" v:profileImageUrlSmall=/api/users/x5jh-tg6w/profile_images/TINY v:lastNotificationSeenAt=1491331911 v:displayName="Takahiko Naito"

property e:bdfu-yahz t:meta.view.tableauthor v:id=x5jh-tg6w v:profileImageUrlMedium=/api/users/x5jh-tg6w/profile_images/THUMB v:profileImageUrlLarge=/api/users/x5jh-tg6w/profile_images/LARGE v:screenName="Takahiko Naito" v:profileImageUrlSmall=/api/users/x5jh-tg6w/profile_images/TINY v:lastNotificationSeenAt=1491331911 v:displayName="Takahiko Naito"
```

## Top Records

```ls
| page      | dataset_title           | final | archival_period     | archive_date_created_at | url                                                                                                  | file_format | file_size | 
| ========= | ======================= | ===== | =================== | ======================= | ==================================================================================================== | =========== | ========= | 
| rxt6-ds8j | DFCArchive_20010601.zip |       | 2001-06-01T00:00:00 | 2004-03-04T00:00:00     | [http://medicare.gov/download/DialysisFacilityCompare/2001/June/DFCArchive_20010601.zip, null]       | Zip File    | 303 KB    | 
| rxt6-ds8j | DFCArchive_20010703.zip |       | 2001-07-03T00:00:00 | 2004-03-04T00:00:00     | [http://medicare.gov/download/DialysisFacilityCompare/2001/July/DFCArchive_20010703.zip, null]       | Zip File    | 317 KB    | 
| rxt6-ds8j | DFCArchive_20010808.zip |       | 2001-08-08T00:00:00 | 2004-03-04T00:00:00     | [http://medicare.gov/download/DialysisFacilityCompare/2001/August/08/DFCArchive_20010808.zip, null]  | Zip File    | 312 KB    | 
| rxt6-ds8j | DFCArchive_20010831.zip |       | 2001-08-31T00:00:00 | 2004-03-04T00:00:00     | [http://medicare.gov/download/DialysisFacilityCompare/2001/August/31/DFCArchive_20010831.zip, null]  | Zip File    | 319 KB    | 
| rxt6-ds8j | DFCArchive_20011002.zip |       | 2001-10-02T00:00:00 | 2004-03-04T00:00:00     | [http://medicare.gov/download/DialysisFacilityCompare/2001/October/02/DFCArchive_20011002.zip, null] | Zip File    | 319 KB    | 
| rxt6-ds8j | DFCArchive_20011030.zip |       | 2001-10-30T00:00:00 | 2004-03-04T00:00:00     | [http://medicare.gov/download/DialysisFacilityCompare/2001/October/30/DFCArchive_20011030.zip, null] | Zip File    | 321 KB    | 
| rxt6-ds8j | DFCArchive_20011227.zip |       | 2001-12-27T00:00:00 | 2004-03-04T00:00:00     | [http://medicare.gov/download/DialysisFacilityCompare/2001/December/DFCArchive_20011227.zip, null]   | Zip File    | 322 KB    | 
| rxt6-ds8j | DFCArchive_20020125.zip |       | 2002-01-25T00:00:00 | 2004-03-04T00:00:00     | [http://medicare.gov/download/DialysisFacilityCompare/2002/January/DFCArchive_20020125.zip, null]    | Zip File    | 323 KB    | 
| rxt6-ds8j | DFCArchive_20020225.zip |       | 2002-02-25T00:00:00 | 2004-03-04T00:00:00     | [http://medicare.gov/download/DialysisFacilityCompare/2002/February/DFCArchive_20020225.zip, null]   | Zip File    | 324 KB    | 
| rxt6-ds8j | DFCArchive_20020325.zip |       | 2002-03-25T00:00:00 | 2004-03-04T00:00:00     | [http://medicare.gov/download/DialysisFacilityCompare/2002/March/DFCArchive_20020325.zip, null]      | Zip File    | 325 KB    | 
```