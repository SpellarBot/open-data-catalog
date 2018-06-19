# Seattle Police body worn videos recorded in phase 1 of Seattle Police BWV pilot Dec 19, 2014 to Mar 26, 2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/seattle-police-body-worn-videos-recorded-in-phase-1-of-seattle-police-bwv-pilot-dec-19-26-) |
| Metadata | [Link](https://data.seattle.gov/api/views/5rka-m6jr) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/5rka-m6jr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/5rka-m6jr/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | 5rka-m6jr |
| Name | Seattle Police body worn videos recorded in phase 1 of Seattle Police BWV pilot Dec 19, 2014 to Mar 26, 2015 |
| Attribution | Seattle Police |
| Category | Public Safety |
| Created | 2015-06-04T15:28:36Z |
| Publication Date | 2015-06-04T15:34:59Z |

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                      | Data Type     | Render Type   |
| ======== | ============== | ========================= | ========================= | ============= | ============= |
| Yes      | series tag     | evidence_id               | evidence_id               | text          | text          |
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
series e:5rka-m6jr d:2015-01-14T14:04:04.000Z t:flag_y_n=N t:owner_last_name=Walczak t:owner_first_name=Joseph t:evidence_id=E9E5F148-E719-45CB-8B5A-3B1D6BB27CAB t:owner_badge_id=7828 t:content_type=mp4 m:duration_seconds=98.39 m:size_mb=21.75

series e:5rka-m6jr d:2014-12-29T02:32:54.000Z t:flag_y_n=N t:owner_last_name=James t:owner_first_name=Christopher t:evidence_id=7AA70D0F-FD34-42BD-897A-40D113D90BCA t:owner_badge_id=7684 t:content_type=mp4 m:duration_seconds=116.29 m:size_mb=25.48

series e:5rka-m6jr d:2015-03-26T18:53:46.000Z t:flag_y_n=N t:owner_last_name=PELICH t:owner_first_name=DEBRA t:evidence_id=E7477D49-FE61-4994-B341-81FE8BCEF9D4 t:owner_badge_id=5976 t:content_type=mp4 m:duration_seconds=30.24 m:size_mb=11.15
```

## Meta Commands

```ls
metric m:size_mb p:float l:size_mb t:dataTypeName=number

metric m:duration_seconds p:float l:duration_seconds t:dataTypeName=number

entity e:5rka-m6jr l:"Seattle Police body worn videos recorded in phase 1 of Seattle Police BWV pilot Dec 19, 2014 to Mar 26, 2015" t:attribution="Seattle Police" t:url=https://data.seattle.gov/api/views/5rka-m6jr

property e:5rka-m6jr t:meta.view v:id=5rka-m6jr v:category="Public Safety" v:averageRating=0 v:name="Seattle Police body worn videos recorded in phase 1 of Seattle Police BWV pilot Dec 19, 2014 to Mar 26, 2015" v:attribution="Seattle Police"

property e:5rka-m6jr t:meta.view.license v:name="Public Domain"

property e:5rka-m6jr t:meta.view.owner v:id=v35j-cik3 v:screenName=timothyclemans v:displayName=timothyclemans

property e:5rka-m6jr t:meta.view.tableauthor v:id=v35j-cik3 v:screenName=timothyclemans v:displayName=timothyclemans
```

## Top Records

```ls
| evidence_id                          | id_external           | created_date_record_start | date_record_end     | flag_y_n | content_type | size_mb | duration_seconds | owner_first_name | owner_last_name | owner_badge_id | categories   | evidence_tags | 
| ==================================== | ===================== | ========================= | =================== | ======== | ============ | ======= | ================ | ================ | =============== | ============== | ============ | ============= | 
| E9E5F148-E719-45CB-8B5A-3B1D6BB27CAB |                       | 2015-01-14T14:04:04       | 2015-01-14T14:05:42 | N        | mp4          | 21.75   | 98.39            | Joseph           | Walczak         | 7828           |              |               | 
| 7AA70D0F-FD34-42BD-897A-40D113D90BCA |                       | 2014-12-29T02:32:54       | 2014-12-29T02:34:50 | N        | mp4          | 25.48   | 116.29           | Christopher      | James           | 7684           |              |               | 
| E7477D49-FE61-4994-B341-81FE8BCEF9D4 |                       | 2015-03-26T18:53:46       | 2015-03-26T18:54:16 | N        | mp4          | 11.15   | 30.24            | DEBRA            | PELICH          | 5976           |              |               | 
| 70B1A334-6368-4616-B760-D7534F06428C | system check          | 2015-03-26T17:39:44       | 2015-03-26T17:40:14 | N        | mp4          | 14.58   | 30.56            | DEBRA            | PELICH          | 5976           | System Check |               | 
| D35C9C20-7ACD-4F5F-89ED-85BBA130CA0C | Training Scenario 1-4 | 2015-03-24T12:20:36       | 2015-03-24T12:24:43 | N        | mp4          | 86.42   | 247.52           | Jesus            | Valenzuela      | 7355           | Training     |               | 
| 5670922E-BC29-45DD-8A33-1851130ED07A | Training Scenario 1-1 | 2015-03-24T11:54:30       | 2015-03-24T11:56:07 | N        | mp4          | 40.81   | 97.34            | Jesus            | Valenzuela      | 7355           | Training     |               | 
| 9A8DE696-4F6B-47F1-A186-4E253E71C02E | Training NV           | 2015-03-24T11:41:28       | 2015-03-24T11:41:58 | N        | mp4          | 14.35   | 30.11            | Jesus            | Valenzuela      | 7355           | Training     |               | 
| B9E8B3ED-B1E1-4BDD-BE32-AF8A2E683A9C | Training Scenario 3-4 | 2015-03-24T02:35:18       | 2015-03-24T02:37:53 | N        | mp4          | 34.21   | 155.63           | Jesus            | Valenzuela      | 7355           | Training     |               | 
| F6003C17-AE25-46DF-AF12-2DEC70F0539D | Training Scenario 3-1 | 2015-03-22T23:26:30       | 2015-03-22T23:29:42 | N        | mp4          | 86.52   | 192.3            | Jesus            | Valenzuela      | 7355           | Training     |               | 
| 43F7EE44-5FB3-4B84-B756-7F287655CA39 |                       | 2015-03-19T12:00:06       | 2015-03-19T12:00:46 | N        | mp4          | 16.95   | 40.28            | Jose             | Silva           | 6919           |              |               | 
```