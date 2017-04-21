# Bicycle Green Wave Signal Timing

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/bicycle-green-wave-signal-timing) |
| Metadata | [Link](https://data.sfgov.org/api/views/2zwx-p5zf) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/2zwx-p5zf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/2zwx-p5zf/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | 2zwx-p5zf |
| Name | Bicycle Green Wave Signal Timing |
| Attribution | City and County of San Francisco |
| Category | Transportation |
| Tags | greenway bicycle signal timing |
| Created | 2016-08-18T20:19:29Z |
| Publication Date | 2016-10-12T00:46:08Z |

## Description

This dataset is created to show the locations of signals that are timed for bicycle green wave.

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type     | Render Type   |
| ======== | =========== | ================ | ================ | ============= | ============= |
| Yes      | series tag  | object_id        | Object ID        | text          | number        |
| Yes      | series tag  | cnn_id           | CNN ID           | text          | text          |
| Yes      | series tag  | street_1         | Street 1         | text          | text          |
| Yes      | series tag  | street_2         | Street 2         | text          | text          |
| Yes      | series tag  | street_3         | Street 3         | text          | text          |
| Yes      | series tag  | street_4         | Street 4         | text          | text          |
| Yes      | series tag  | signal_number    | Signal Number    | text          | text          |
| Yes      | series tag  | system_number    | System Number    | text          | text          |
| Yes      | time        | last_edited_date | Last Edited Date | calendar_date | calendar_date |
```

## Time Field

```ls
Value = last_edited_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:2zwx-p5zf d:2017-04-15T16:37:41.000Z t:street_2=VALENCIA t:street_1="24TH ST" t:signal_number=1395 t:object_id=1 t:cnn_id=24101000 t:system_number=22 m:row_number.2zwx-p5zf=1

series e:2zwx-p5zf d:2017-04-15T16:37:41.000Z t:street_2=VALENCIA t:street_1="25TH ST" t:signal_number=1465 t:object_id=2 t:cnn_id=24097000 t:system_number=22G m:row_number.2zwx-p5zf=2

series e:2zwx-p5zf d:2017-04-15T16:37:41.000Z t:street_2=VALENCIA t:street_1="21ST ST" t:signal_number=1250 t:object_id=3 t:cnn_id=24119000 t:system_number=22 m:row_number.2zwx-p5zf=3
```

## Meta Commands

```ls
metric m:row_number.2zwx-p5zf p:long l:"Row Number"

entity e:2zwx-p5zf l:"Bicycle Green Wave Signal Timing" t:attribution="City and County of San Francisco" t:url=https://data.sfgov.org/api/views/2zwx-p5zf

property e:2zwx-p5zf t:meta.view v:id=2zwx-p5zf v:category=Transportation v:attributionLink=http://www.sfgov.org v:averageRating=0 v:name="Bicycle Green Wave Signal Timing" v:attribution="City and County of San Francisco"

property e:2zwx-p5zf t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:2zwx-p5zf t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:displayName=OpenData

property e:2zwx-p5zf t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```

## Top Records

```ls
| object_id | cnn_id   | street_1 | street_2 | street_3 | street_4 | signal_number | system_number | last_edited_date | 
| ========= | ======== | ======== | ======== | ======== | ======== | ============= | ============= | ================ | 
| 1         | 24101000 | 24TH ST  | VALENCIA |          |          | 1395          | 22            |                  | 
| 2         | 24097000 | 25TH ST  | VALENCIA |          |          | 1465          | 22G           |                  | 
| 3         | 24119000 | 21ST ST  | VALENCIA |          |          | 1250          | 22            |                  | 
| 4         | 24115000 | 22ND ST  | VALENCIA |          |          | 1285          | 22            |                  | 
| 5         | 24153000 | 20TH ST  | VALENCIA |          |          | 1220          | 22            |                  | 
| 6         | 24106000 | 23RD ST  | VALENCIA |          |          | 1340          | 22            |                  | 
| 7         | 24174000 | 17TH ST  | VALENCIA |          |          | 0950          | 22            |                  | 
| 8         | 24158000 | 19TH ST  | VALENCIA |          |          | 1160          | 22            |                  | 
| 9         | 24160000 | 18TH ST  | VALENCIA |          |          | 1015          | 22            |                  | 
| 10        | 24183000 | 16TH ST  | VALENCIA |          |          | 0895          | 22            |                  | 
```