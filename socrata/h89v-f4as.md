# Districts

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/districts-96eaa) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/h89v-f4as) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/h89v-f4as/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/h89v-f4as/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | h89v-f4as |
| Name | Districts |
| Category | Election operations |
| Tags | election, voter, districts |
| Created | 2012-09-03T18:24:35Z |
| Publication Date | 2012-09-03T18:34:24Z |

## Description

Districts for King County Elections

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| No       | time           | :updated_at         | updated_at          | meta_data | meta_data   |
| Yes      | series tag     | district_id         | district_id         | text      | number      |
| Yes      | series tag     | status              | status              | text      | text        |
| Yes      | series tag     | group_type          | group_type          | text      | text        |
| Yes      | series tag     | district_number     | district_number     | text      | number      |
| Yes      | series tag     | sub_district_number | sub_district_number | text      | number      |
| Yes      | series tag     | countywide          | countywide          | text      | text        |
| Yes      | series tag     | name_1              | name_1              | text      | text        |
| Yes      | series tag     | name_2              | name_2              | text      | text        |
| Yes      | series tag     | abbr                | abbr                | text      | text        |
| Yes      | series tag     | state_code          | state_code          | text      | text        |
| Yes      | series tag     | contact             | contact             | text      | text        |
| Yes      | series tag     | care_of             | care_of             | text      | text        |
| Yes      | series tag     | mail_city           | mail_city           | text      | text        |
| Yes      | series tag     | mail_state          | mail_state          | text      | text        |
| Yes      | series tag     | mail_country        | mail_country        | text      | text        |
| Yes      | series tag     | mail_zip            | mail_zip            | text      | number      |
| Yes      | numeric metric | phone_1             | phone_1             | number    | number      |
| Yes      | numeric metric | phone_2             | phone_2             | number    | number      |
| Yes      | series tag     | fax                 | fax                 | text      | number      |
| Yes      | series tag     | email               | email               | text      | text        |
| Yes      | numeric metric | newspaper           | newspaper           | number    | number      |
| Yes      | numeric metric | letter              | letter              | number    | text        |
| Yes      | series tag     | next_election       | next_election       | text      | text        |
| Yes      | series tag     | statute             | statute             | text      | text        |
| Yes      | series tag     | partisan            | partisan            | text      | text        |
| Yes      | series tag     | rotates_by          | rotates_by          | text      | text        |
| Yes      | series tag     | exceptions          | exceptions          | text      | text        |
| Yes      | series tag     | rotation_inventory  | rotation_inventory  | text      | text        |
| No       |                | address_validation  | address_validation  | text      | text        |
| Yes      | series tag     | comment_id          | comment_id          | text      | number      |
| Yes      | series tag     | district_trans_id   | district_trans_id   | text      | number      |
| Yes      | series tag     | ltd                 | ltd                 | text      | text        |
| Yes      | series tag     | timestamp           | timestamp           | text      | text        |
| Yes      | series tag     | foreign_id          | foreign_id          | text      | number      |
| Yes      | series tag     | web_site            | web_site            | text      | text        |
| Yes      | series tag     | gen_field           | gen_field           | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address_validation
```

## Data Commands

```ls
series e:h89v-f4as d:2012-09-03T11:24:41.000Z t:group_type=CC t:comment_id=0 t:partisan=N t:fax=0 t:status=A t:district_id=1 t:abbr=1 t:district_number=1 t:timestamp=000000000F14FEBC t:exceptions=N t:sub_district_number=0 t:foreign_id=0 t:name_1="COUNTY COUNCIL DISTRICT NO. 1" t:district_trans_id=439 t:ltd=04:47.3 t:countywide=N m:phone_2=0 m:phone_1=2062961020 m:newspaper=0

series e:h89v-f4as d:2012-09-03T11:24:41.000Z t:group_type=CC t:comment_id=0 t:partisan=N t:fax=0 t:status=A t:district_id=2 t:abbr=2 t:district_number=2 t:timestamp=000000000F14FEDF t:exceptions=N t:sub_district_number=0 t:foreign_id=0 t:name_1="COUNTY COUNCIL DISTRICT NO. 2" t:district_trans_id=440 t:ltd=06:20.8 t:countywide=N m:phone_2=0 m:phone_1=0 m:newspaper=0

series e:h89v-f4as d:2012-09-03T11:24:41.000Z t:group_type=CC t:comment_id=0 t:partisan=N t:fax=0 t:status=A t:district_id=3 t:abbr=3 t:district_number=3 t:timestamp=000000000F14FEE0 t:exceptions=N t:sub_district_number=0 t:foreign_id=0 t:name_1="COUNTY COUNCIL DISTRICT NO. 3" t:district_trans_id=441 t:ltd=06:26.8 t:countywide=N m:phone_2=0 m:phone_1=0 m:newspaper=0
```

## Meta Commands

```ls
metric m:phone_1 p:long l:phone_1 t:dataTypeName=number

metric m:phone_2 p:long l:phone_2 t:dataTypeName=number

metric m:newspaper p:integer l:newspaper t:dataTypeName=number

metric m:letter p:integer l:letter t:dataTypeName=number

entity e:h89v-f4as l:Districts t:url=https://data.kingcounty.gov/api/views/h89v-f4as

property e:h89v-f4as t:meta.view v:id=h89v-f4as v:category="Election operations" v:attributionLink=http://www.kingcounty.gov/elections v:averageRating=0 v:name=Districts

property e:h89v-f4as t:meta.view.owner v:id=bkmh-fhfb v:screenName="Asera Khatun" v:displayName="Asera Khatun"

property e:h89v-f4as t:meta.view.tableauthor v:id=bkmh-fhfb v:screenName="Asera Khatun" v:roleName=publisher v:displayName="Asera Khatun"
```

## Top Records

```ls
| :updated_at | district_id | status | group_type | district_number | sub_district_number | countywide | name_1                        | name_2 | abbr | state_code | contact | care_of | mail_city | mail_state | mail_country | mail_zip | phone_1    | phone_2 | fax | email | newspaper | letter | next_election | statute | partisan | rotates_by | exceptions | rotation_inventory | address_validation | comment_id | district_trans_id | ltd     | timestamp        | foreign_id | web_site | gen_field | 
| =========== | =========== | ====== | ========== | =============== | =================== | ========== | ============================= | ====== | ==== | ========== | ======= | ======= | ========= | ========== | ============ | ======== | ========== | ======= | === | ===== | ========= | ====== | ============= | ======= | ======== | ========== | ========== | ================== | ================== | ========== | ================= | ======= | ================ | ========== | ======== | ========= | 
| 1346671481  | 1           | A      | CC         | 1               | 0                   | N          | COUNTY COUNCIL DISTRICT NO. 1 |        | 1    |            |         |         |           |            |              |          | 2062961020 | 0       | 0   |       | 0         |        |               |         | N        |            | N          |                    |                    | 0          | 439               | 04:47.3 | 000000000F14FEBC | 0          |          |           | 
| 1346671481  | 2           | A      | CC         | 2               | 0                   | N          | COUNTY COUNCIL DISTRICT NO. 2 |        | 2    |            |         |         |           |            |              |          | 0          | 0       | 0   |       | 0         |        |               |         | N        |            | N          |                    |                    | 0          | 440               | 06:20.8 | 000000000F14FEDF | 0          |          |           | 
| 1346671481  | 3           | A      | CC         | 3               | 0                   | N          | COUNTY COUNCIL DISTRICT NO. 3 |        | 3    |            |         |         |           |            |              |          | 0          | 0       | 0   |       | 0         |        |               |         | N        |            | N          |                    |                    | 0          | 441               | 06:26.8 | 000000000F14FEE0 | 0          |          |           | 
| 1346671481  | 4           | A      | CC         | 4               | 0                   | N          | COUNTY COUNCIL DISTRICT NO. 4 |        | 4    |            |         |         |           |            |              |          | 0          | 0       | 0   |       | 0         |        |               |         | N        |            | N          |                    |                    | 0          | 442               | 06:33.2 | 000000000F14FEE3 | 0          |          |           | 
| 1346671481  | 5           | A      | CC         | 5               | 0                   | N          | COUNTY COUNCIL DISTRICT NO. 5 |        | 5    |            |         |         |           |            |              |          | 0          | 0       | 0   |       | 0         |        |               |         | N        |            | N          |                    |                    | 0          | 443               | 06:39.1 | 000000000F14FEE6 | 0          |          |           | 
| 1346671481  | 6           | A      | CC         | 6               | 0                   | N          | COUNTY COUNCIL DISTRICT NO. 6 |        | 6    |            |         |         |           |            |              |          | 0          | 0       | 0   |       | 0         |        |               |         | N        |            | N          |                    |                    | 0          | 444               | 06:44.7 | 000000000F14FEEF | 0          |          |           | 
| 1346671481  | 7           | A      | CC         | 7               | 0                   | N          | COUNTY COUNCIL DISTRICT NO. 7 |        | 7    |            |         |         |           |            |              |          | 0          | 0       | 0   |       | 0         |        |               |         | N        |            | N          |                    |                    | 0          | 445               | 06:52.6 | 000000000F14FEF1 | 0          |          |           | 
| 1346671481  | 8           | A      | CC         | 8               | 0                   | N          | COUNTY COUNCIL DISTRICT NO. 8 |        | 8    |            |         |         |           |            |              |          | 0          | 0       | 0   |       | 0         |        |               |         | N        |            | N          |                    |                    | 0          | 446               | 06:57.9 | 000000000F14FEF3 | 0          |          |           | 
| 1346671481  | 9           | A      | CC         | 9               | 0                   | N          | COUNTY COUNCIL DISTRICT NO. 9 |        | 9    |            |         |         |           |            |              |          | 0          | 0       | 0   |       | 0         |        |               |         | N        |            | N          |                    |                    | 0          | 447               | 07:03.0 | 000000000F14FEF6 | 0          |          |           | 
| 1346671481  | 14          | A      | CG         | 1               | 0                   | N          | CONGRESSIONAL DISTRICT NO. 1  |        | 1    |            |         |         |           |            |              |          | 0          | 0       | 0   |       | 0         |        |               |         | N        |            | N          |                    |                    | 0          | 432               | 03:50.4 | 000000000F14FEA2 | 0          |          |           | 
```