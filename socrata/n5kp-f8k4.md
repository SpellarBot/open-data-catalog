# Transportation Data Publication Log

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/transportation-data-publication-log-beta) |
| Metadata | [Link](https://data.austintexas.gov/api/views/n5kp-f8k4) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/n5kp-f8k4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/n5kp-f8k4/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | n5kp-f8k4 |
| Name | Transportation Data Publication Log |
| Attribution | Austin Transportation Department |
| Tags | transportation, transit, mobility, traffic signals, pedestrians |
| Created | 2016-09-08T19:38:29Z |
| Publication Date | 2017-01-14T15:18:41Z |

## Description

This dataset logs activities related to the automated publication of Austin Transportation datasets.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type     | Render Type   |
| ======== | ============== | ================ | ================ | ============= | ============= |
| Yes      | series tag     | event            | event            | text          | text          |
| Yes      | numeric metric | timestamp        | timestamp        | number        | number        |
| Yes      | time           | date_time        | date_time        | calendar_date | calendar_date |
| Yes      | series tag     | errors           | errors           | text          | text          |
| Yes      | numeric metric | updated          | updated          | number        | number        |
| Yes      | numeric metric | created          | created          | number        | number        |
| Yes      | numeric metric | deleted          | deleted          | number        | number        |
| Yes      | series tag     | not_processed    | not_processed    | text          | text          |
| Yes      | series tag     | response_message | response_message | text          | text          |
```

## Time Field

```ls
Value = date_time
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:n5kp-f8k4 d:2016-09-08T14:48:47.000Z t:errors=0 t:event=signal_status_update m:timestamp=1473364129 m:updated=0 m:created=0 m:deleted=0

series e:n5kp-f8k4 d:2016-09-08T14:49:00.000Z t:errors=0 t:event=signal_status_update m:timestamp=1473364143 m:updated=0 m:created=0 m:deleted=0

series e:n5kp-f8k4 d:2016-09-08T14:54:00.000Z t:errors=0 t:event=signal_status_update m:timestamp=1473364442 m:updated=0 m:created=0 m:deleted=0
```

## Meta Commands

```ls
metric m:timestamp p:integer l:timestamp t:dataTypeName=number

metric m:updated p:integer l:updated t:dataTypeName=number

metric m:created p:integer l:created t:dataTypeName=number

metric m:deleted p:integer l:deleted t:dataTypeName=number

entity e:n5kp-f8k4 l:"Transportation Data Publication Log" t:attribution="Austin Transportation Department" t:url=https://data.austintexas.gov/api/views/n5kp-f8k4

property e:n5kp-f8k4 t:meta.view v:id=n5kp-f8k4 v:averageRating=0 v:name="Transportation Data Publication Log" v:attribution="Austin Transportation Department"

property e:n5kp-f8k4 t:meta.view.license v:name="Public Domain"

property e:n5kp-f8k4 t:meta.view.owner v:id=8t3r-wq64 v:profileImageUrlMedium=/api/users/8t3r-wq64/profile_images/THUMB v:profileImageUrlLarge=/api/users/8t3r-wq64/profile_images/LARGE v:screenName="Austin Transportation" v:profileImageUrlSmall=/api/users/8t3r-wq64/profile_images/TINY v:displayName="Austin Transportation"

property e:n5kp-f8k4 t:meta.view.tableauthor v:id=8t3r-wq64 v:profileImageUrlMedium=/api/users/8t3r-wq64/profile_images/THUMB v:profileImageUrlLarge=/api/users/8t3r-wq64/profile_images/LARGE v:screenName="Austin Transportation" v:profileImageUrlSmall=/api/users/8t3r-wq64/profile_images/TINY v:roleName=editor_stories v:displayName="Austin Transportation"
```

## Top Records

```ls
| event                | timestamp  | date_time           | errors | updated | created | deleted | not_processed | response_message | 
| ==================== | ========== | =================== | ====== | ======= | ======= | ======= | ============= | ================ | 
| signal_status_update | 1473364129 | 2016-09-08T14:48:47 | 0      | 0       | 0       | 0       |               |                  | 
| signal_status_update | 1473364143 | 2016-09-08T14:49:00 | 0      | 0       | 0       | 0       |               |                  | 
| signal_status_update | 1473364442 | 2016-09-08T14:54:00 | 0      | 0       | 0       | 0       |               |                  | 
| signal_status_update | 1473364742 | 2016-09-08T14:59:00 | 0      | 0       | 0       | 0       |               |                  | 
| signal_status_update | 1473365042 | 2016-09-08T15:04:00 | 0      | 2       | 0       | 0       |               |                  | 
| signal_status_update | 1473365343 | 2016-09-08T15:09:00 | 0      | 1       | 0       | 0       |               |                  | 
| signal_status_update | 1473365643 | 2016-09-08T15:14:00 | 0      | 0       | 0       | 0       |               |                  | 
| signal_status_update | 1473365942 | 2016-09-08T15:19:00 | 0      | 0       | 0       | 0       |               |                  | 
| signal_status_update | 1473366245 | 2016-09-08T15:24:02 | 0      | 1       | 0       | 0       |               |                  | 
| signal_status_update | 1473366543 | 2016-09-08T15:29:00 | 0      | 0       | 0       | 0       |               |                  | 
```