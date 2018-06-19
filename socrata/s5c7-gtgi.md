# Bus Routes

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/bus-routes) |
| Metadata | [Link](https://data.honolulu.gov/api/views/s5c7-gtgi) |
| Data: JSON | [100 Rows](https://data.honolulu.gov/api/views/s5c7-gtgi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.honolulu.gov/api/views/s5c7-gtgi/rows.csv?max_rows=100) |
| Host | data.honolulu.gov |
| Id | s5c7-gtgi |
| Name | Bus Routes |
| Category | Transportation |
| Created | 2015-05-23T02:08:05Z |
| Publication Date | 2015-05-23T02:08:46Z |

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type | Render Type |
| ======== | =========== | ================ | ================ | ========= | =========== |
| No       | time        | :updated_at      | updated_at       | meta_data | meta_data   |
| Yes      | series tag  | route_long_name  | route_long_name  | text      | text        |
| Yes      | series tag  | route_id         | route_id         | text      | number      |
| Yes      | series tag  | route_type       | route_type       | text      | number      |
| Yes      | series tag  | route_text_color | route_text_color | text      | text        |
| Yes      | series tag  | agency_id        | agency_id        | text      | number      |
| Yes      | series tag  | route_color      | route_color      | text      | text        |
| Yes      | series tag  | route_url        | route_url        | text      | text        |
| Yes      | series tag  | route_desc       | route_desc       | text      | text        |
| Yes      | series tag  | route_short_name | route_short_name | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:s5c7-gtgi d:2015-05-22T19:08:09.000Z t:agency_id=1 t:route_type=3 t:route_id=132 t:route_short_name=2L t:route_long_name="Waikiki-School-Middle Limited" m:row_number.s5c7-gtgi=1

series e:s5c7-gtgi d:2015-05-22T19:08:09.000Z t:agency_id=1 t:route_type=3 t:route_id=131 t:route_short_name=62 t:route_long_name=Honolulu-Wahiawa m:row_number.s5c7-gtgi=2

series e:s5c7-gtgi d:2015-05-22T19:08:09.000Z t:agency_id=1 t:route_type=3 t:route_id=130 t:route_short_name=55 t:route_long_name=Honolulu-Kaneohe-Wahiawa m:row_number.s5c7-gtgi=3
```

## Meta Commands

```ls
metric m:row_number.s5c7-gtgi p:long l:"Row Number"

entity e:s5c7-gtgi l:"Bus Routes" t:url=https://data.honolulu.gov/api/views/s5c7-gtgi

property e:s5c7-gtgi t:meta.view v:id=s5c7-gtgi v:category=Transportation v:averageRating=0 v:name="Bus Routes"

property e:s5c7-gtgi t:meta.view.owner v:id=b4zr-4dtj v:screenName="Karl Sueyoshi" v:displayName="Karl Sueyoshi"

property e:s5c7-gtgi t:meta.view.tableauthor v:id=b4zr-4dtj v:screenName="Karl Sueyoshi" v:roleName=administrator v:displayName="Karl Sueyoshi"
```

## Top Records

```ls
| :updated_at | route_long_name               | route_id | route_type | route_text_color | agency_id | route_color | route_url | route_desc | route_short_name | 
| =========== | ============================= | ======== | ========== | ================ | ========= | =========== | ========= | ========== | ================ | 
| 1432321689  | Waikiki-School-Middle Limited | 132      | 3          |                  | 1         |             |           |            | 2L               | 
| 1432321689  | Honolulu-Wahiawa              | 131      | 3          |                  | 1         |             |           |            | 62               | 
| 1432321689  | Honolulu-Kaneohe-Wahiawa      | 130      | 3          |                  | 1         |             |           |            | 55               | 
| 1432321689  | Lanikai-Maunawili             | 41       | 3          |                  | 1         |             |           |            | 70               | 
| 1432321689  | Tripler-Mapunapuna            | 24       | 3          |                  | 1         |             |           |            | 31               | 
| 1432321689  | Kalihi-Pearlridge             | 25       | 3          |                  | 1         |             |           |            | 32               | 
| 1432321689  | Honolulu-Makaha               | 26       | 3          |                  | 1         |             |           |            | 40               | 
| 1432321689  | Kapolei-Ewa Beach             | 27       | 3          |                  | 1         |             |           |            | 41               | 
| 1432321689  | Beach Bus                     | 21       | 3          |                  | 1         |             |           |            | 22               | 
| 1432321689  | City Express! A               | 22       | 3          |                  | 1         |             |           |            | A                | 
```