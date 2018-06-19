# Videos recorded in Phase 1 of the Seattle Police body worn video pilot

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/videos-recorded-in-phase-1-of-the-seattle-police-body-worn-video-pilot) |
| Metadata | [Link](https://data.seattle.gov/api/views/n6as-h2bj) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/n6as-h2bj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/n6as-h2bj/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | n6as-h2bj |
| Name | Videos recorded in Phase 1 of the Seattle Police body worn video pilot |
| Category | Public Safety |
| Created | 2015-06-08T16:39:48Z |
| Publication Date | 2015-06-08T16:43:03Z |

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                      | Data Type     | Render Type   |
| ======== | ============== | ========================= | ========================= | ============= | ============= |
| Yes      | series tag     | evidence_id               | evidence_id               | text          | text          |
| Yes      | series tag     | filename_on_s3            | filename_on_s3            | text          | text          |
| Yes      | series tag     | youtube_id                | youtube_id                | text          | text          |
| Yes      | series tag     | id_external               | id_external               | text          | text          |
| Yes      | time           | created_date_record_start | created_date_record_start | calendar_date | calendar_date |
| No       |                | date_record_end           | date_record_end           | calendar_date | calendar_date |
| Yes      | series tag     | flag_y_n                  | flag (Y/N)                | text          | text          |
| Yes      | series tag     | content_type              | content_type              | text          | text          |
| Yes      | numeric metric | size_mb                   | size_mb                   | number        | number        |
| Yes      | numeric metric | duration_seconds          | duration_seconds          | number        | number        |
| Yes      | series tag     | owner_first_name          | owner_first_name          | text          | text          |
| Yes      | series tag     | owner_last_name           | owner_last_name           | text          | text          |
| Yes      | series tag     | owner_badge_id            | owner_badge_id            | text          | text          |
| Yes      | series tag     | categories                | categories                | text          | text          |
| Yes      | series tag     | evidence_tags             | evidence_tags             | text          | text          |
```

## Time Field

```ls
Value = created_date_record_start
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = date_record_end
```

## Data Commands

```ls
series e:n6as-h2bj d:2015-03-26T18:53:00.000Z t:flag_y_n=N t:owner_last_name=PELICH t:owner_first_name=DEBRA t:evidence_id=E7477D49-FE61-4994-B341-81FE8BCEF9D4 t:owner_badge_id=5976 t:youtube_id=oba67yqFqdM t:content_type=mp4 t:filename_on_s3=E7477D49FE614994B34181FE8BCEF9D4.mp4 m:duration_seconds=30.24 m:size_mb=11.15

series e:n6as-h2bj d:2015-03-26T17:39:00.000Z t:id_external="system check" t:flag_y_n=N t:owner_last_name=PELICH t:categories="System Check" t:owner_first_name=DEBRA t:evidence_id=70B1A334-6368-4616-B760-D7534F06428C t:owner_badge_id=5976 t:youtube_id=lt4esw77lhE t:content_type=mp4 t:filename_on_s3=70B1A33463684616B760D7534F06428C.mp4 m:duration_seconds=30.56 m:size_mb=14.58

series e:n6as-h2bj d:2015-03-24T12:20:00.000Z t:id_external="Training Scenario 1-4" t:flag_y_n=N t:owner_last_name=Valenzuela t:categories=Training t:owner_first_name=Jesus t:evidence_id=D35C9C20-7ACD-4F5F-89ED-85BBA130CA0C t:owner_badge_id=7355 t:youtube_id=wk-VrzqVdOw t:content_type=mp4 t:filename_on_s3=D35C9C207ACD4F5F89ED85BBA130CA0C.mp4 m:duration_seconds=247.52 m:size_mb=86.42
```

## Meta Commands

```ls
metric m:size_mb p:float l:size_mb t:dataTypeName=number

metric m:duration_seconds p:float l:duration_seconds t:dataTypeName=number

entity e:n6as-h2bj l:"Videos recorded in Phase 1 of the Seattle Police body worn video pilot" t:url=https://data.seattle.gov/api/views/n6as-h2bj

property e:n6as-h2bj t:meta.view v:id=n6as-h2bj v:category="Public Safety" v:averageRating=0 v:name="Videos recorded in Phase 1 of the Seattle Police body worn video pilot"

property e:n6as-h2bj t:meta.view.license v:name="Public Domain"

property e:n6as-h2bj t:meta.view.owner v:id=v35j-cik3 v:screenName=timothyclemans v:displayName=timothyclemans

property e:n6as-h2bj t:meta.view.tableauthor v:id=v35j-cik3 v:screenName=timothyclemans v:displayName=timothyclemans
```

## Top Records

```ls
| evidence_id                          | filename_on_s3                       | youtube_id  | id_external           | created_date_record_start | date_record_end     | flag_y_n | content_type | size_mb | duration_seconds | owner_first_name | owner_last_name | owner_badge_id | categories   | evidence_tags | 
| ==================================== | ==================================== | =========== | ===================== | ========================= | =================== | ======== | ============ | ======= | ================ | ================ | =============== | ============== | ============ | ============= | 
| E7477D49-FE61-4994-B341-81FE8BCEF9D4 | E7477D49FE614994B34181FE8BCEF9D4.mp4 | oba67yqFqdM |                       | 2015-03-26T18:53:00       | 2015-03-26T18:54:00 | N        | mp4          | 11.15   | 30.24            | DEBRA            | PELICH          | 5976           |              |               | 
| 70B1A334-6368-4616-B760-D7534F06428C | 70B1A33463684616B760D7534F06428C.mp4 | lt4esw77lhE | system check          | 2015-03-26T17:39:00       | 2015-03-26T17:40:00 | N        | mp4          | 14.58   | 30.56            | DEBRA            | PELICH          | 5976           | System Check |               | 
| D35C9C20-7ACD-4F5F-89ED-85BBA130CA0C | D35C9C207ACD4F5F89ED85BBA130CA0C.mp4 | wk-VrzqVdOw | Training Scenario 1-4 | 2015-03-24T12:20:00       | 2015-03-24T12:24:00 | N        | mp4          | 86.42   | 247.52           | Jesus            | Valenzuela      | 7355           | Training     |               | 
| 5670922E-BC29-45DD-8A33-1851130ED07A | 5670922EBC2945DD8A331851130ED07A.mp4 | WxFZpajFMP8 | Training Scenario 1-1 | 2015-03-24T11:54:00       | 2015-03-24T11:56:00 | N        | mp4          | 40.81   | 97.34            | Jesus            | Valenzuela      | 7355           | Training     |               | 
| 9A8DE696-4F6B-47F1-A186-4E253E71C02E | 9A8DE6964F6B47F1A1864E253E71C02E.mp4 | vpVAt-CwvRs | Training NV           | 2015-03-24T11:41:00       | 2015-03-24T11:41:00 | N        | mp4          | 14.35   | 30.11            | Jesus            | Valenzuela      | 7355           | Training     |               | 
| B9E8B3ED-B1E1-4BDD-BE32-AF8A2E683A9C | B9E8B3EDB1E14BDDBE32AF8A2E683A9C.mp4 | 8KwZUDnv-54 | Training Scenario 3-4 | 2015-03-24T02:35:00       | 2015-03-24T02:37:00 | N        | mp4          | 34.21   | 155.63           | Jesus            | Valenzuela      | 7355           | Training     |               | 
| F6003C17-AE25-46DF-AF12-2DEC70F0539D | F6003C17AE2546DFAF122DEC70F0539D.mp4 | MbcxKPzeRw0 | Training Scenario 3-1 | 2015-03-22T23:26:00       | 2015-03-22T23:29:00 | N        | mp4          | 86.52   | 192.3            | Jesus            | Valenzuela      | 7355           | Training     |               | 
| 43F7EE44-5FB3-4B84-B756-7F287655CA39 | 43F7EE445FB34B84B7567F287655CA39.mp4 | 9Hjj-T9OvTo |                       | 2015-03-19T12:00:00       | 2015-03-19T12:00:00 | N        | mp4          | 16.95   | 40.28            | Jose             | Silva           | 6919           |              |               | 
| 952D0D34-1E2C-447C-87BD-7E4992D2614E | 952D0D341E2C447C87BD7E4992D2614E.mp4 | oIysQHup-vY | 2015-089852           | 2015-03-19T11:48:00       | 2015-03-19T12:10:00 | N        | mp4          | 583.55  | 1366.56          | DANIEL           | ENRIQUEZ        | 4585           | Theft        |               | 
| 3270C96F-0C75-491D-AA67-1E53CBB40B4E | 3270C96F0C75491DAA671E53CBB40B4E.mp4 | 6LluNzB04J0 | 3/19/2015             | 2015-03-19T11:30:00       | 2015-03-19T11:31:00 | N        | mp4          | 21.96   | 71.74            | DANIEL           | ENRIQUEZ        | 4585           | System Check |               | 
```