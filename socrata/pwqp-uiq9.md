# Street Address By Precinct

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/street-address-by-precinct-18e44) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/pwqp-uiq9) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/pwqp-uiq9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/pwqp-uiq9/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | pwqp-uiq9 |
| Name | Street Address By Precinct |
| Category | Election operations |
| Tags | elcetions, king county, street, address |
| Created | 2012-09-03T18:50:24Z |
| Publication Date | 2012-09-03T23:47:33Z |

## Description

Street Address By Precinct for King County Elections

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type     | Render Type   |
| ======== | ============== | =============== | =============== | ============= | ============= |
| Yes      | series tag     | status          | status          | text          | text          |
| Yes      | series tag     | reason_id       | reason_id       | text          | number        |
| Yes      | series tag     | source          | source          | text          | text          |
| Yes      | series tag     | activate        | activate        | text          | text          |
| Yes      | series tag     | type            | type            | text          | text          |
| Yes      | series tag     | pre_dir         | pre_dir         | text          | text          |
| Yes      | series tag     | post_dir        | post_dir        | text          | text          |
| Yes      | series tag     | extra_line      | extra_line      | text          | text          |
| Yes      | numeric metric | house_from      | house_from      | number        | number        |
| Yes      | numeric metric | house_to        | house_to        | number        | number        |
| Yes      | series tag     | side            | side            | text          | text          |
| Yes      | numeric metric | building_from   | building_from   | number        | number        |
| Yes      | numeric metric | building_to     | building_to     | number        | number        |
| Yes      | series tag     | building_req    | building_req    | text          | text          |
| Yes      | numeric metric | apt_from        | apt_from        | number        | number        |
| Yes      | numeric metric | apt_to          | apt_to          | number        | number        |
| Yes      | series tag     | apt_req         | apt_req         | text          | text          |
| Yes      | series tag     | mail_req        | mail_req        | text          | text          |
| Yes      | series tag     | zip_id          | zip_id          | text          | number        |
| Yes      | series tag     | precinct_id     | precinct_id     | text          | number        |
| Yes      | series tag     | map             | map             | text          | text          |
| Yes      | series tag     | map_other_1     | map_other_1     | text          | text          |
| Yes      | series tag     | map_other_2     | map_other_2     | text          | text          |
| Yes      | series tag     | tb_guide_page   | tb_guide_page   | text          | text          |
| Yes      | series tag     | tb_guide_suffix | tb_guide_suffix | text          | text          |
| Yes      | series tag     | tb_reference    | tb_reference    | text          | text          |
| Yes      | series tag     | gis_id          | gis_id          | text          | number        |
| Yes      | time           | gis_trans_date  | gis_trans_date  | calendar_date | calendar_date |
| Yes      | series tag     | gis_user        | gis_user        | text          | text          |
| Yes      | series tag     | comment_id      | comment_id      | text          | number        |
| Yes      | series tag     | street_trans_id | street_trans_id | text          | number        |
| Yes      | series tag     | ltd             | ltd             | text          | text          |
| Yes      | series tag     | timestamp       | timestamp       | text          | text          |
| Yes      | series tag     | gen_field       | gen_field       | text          | text          |
```

## Time Field

```ls
Value = gis_trans_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:pwqp-uiq9 d:1900-01-01T00:00:00.000Z t:timestamp=000000000B308A54 t:activate=Y t:zip_id=0 t:building_req=N t:precinct_id=3196 t:comment_id=0 t:mail_req=N t:status=I t:side=B t:reason_id=0 t:street_trans_id=10105 t:gis_id=0 t:apt_req=N t:ltd=53:40.7 m:house_to=0 m:house_from=0

series e:pwqp-uiq9 d:2012-09-03T11:50:28.000Z t:comment_id=0 t:building_req=N t:status=A t:reason_id=0 t:street_trans_id=2151 t:gis_id=0 t:apt_req=N t:type=AVE t:zip_id=1 t:activate=Y t:timestamp=000000000B308A55 t:precinct_id=2205 t:post_dir=N t:mail_req=N t:side=E t:ltd=43:29.1 m:house_to=98 m:house_from=0

series e:pwqp-uiq9 d:2012-09-03T11:50:28.000Z t:comment_id=0 t:building_req=N t:status=A t:reason_id=0 t:street_trans_id=2151 t:gis_id=0 t:apt_req=N t:type=AVE t:zip_id=1 t:activate=Y t:timestamp=000000000B308A56 t:precinct_id=2306 t:post_dir=N t:mail_req=N t:side=O t:ltd=43:29.1 m:house_to=99 m:house_from=1
```

## Meta Commands

```ls
metric m:house_from p:integer l:house_from t:dataTypeName=number

metric m:house_to p:integer l:house_to t:dataTypeName=number

metric m:building_from p:long l:building_from t:dataTypeName=number

metric m:building_to p:long l:building_to t:dataTypeName=number

metric m:apt_from p:integer l:apt_from t:dataTypeName=number

metric m:apt_to p:integer l:apt_to t:dataTypeName=number

entity e:pwqp-uiq9 l:"Street Address By Precinct" t:url=https://data.kingcounty.gov/api/views/pwqp-uiq9

property e:pwqp-uiq9 t:meta.view v:id=pwqp-uiq9 v:category="Election operations" v:averageRating=0 v:name="Street Address By Precinct"

property e:pwqp-uiq9 t:meta.view.license v:name="Public Domain"

property e:pwqp-uiq9 t:meta.view.owner v:id=bkmh-fhfb v:screenName="Asera Khatun" v:displayName="Asera Khatun"

property e:pwqp-uiq9 t:meta.view.tableauthor v:id=bkmh-fhfb v:screenName="Asera Khatun" v:roleName=publisher v:displayName="Asera Khatun"
```

## Top Records

```ls
| status | reason_id | source | activate | type | pre_dir | post_dir | extra_line | house_from | house_to | side | building_from | building_to | building_req | apt_from | apt_to | apt_req | mail_req | zip_id | precinct_id | map | map_other_1 | map_other_2 | tb_guide_page | tb_guide_suffix | tb_reference | gis_id | gis_trans_date      | gis_user | comment_id | street_trans_id | ltd     | timestamp        | gen_field | 
| ====== | ========= | ====== | ======== | ==== | ======= | ======== | ========== | ========== | ======== | ==== | ============= | =========== | ============ | ======== | ====== | ======= | ======== | ====== | =========== | === | =========== | =========== | ============= | =============== | ============ | ====== | =================== | ======== | ========== | =============== | ======= | ================ | ========= | 
| I      | 0         |        | Y        |      |         |          |            | 0          | 0        | B    |               |             | N            |          |        | N       | N        | 0      | 3196        |     |             |             |               |                 |              | 0      | 1900-01-01T00:00:00 |          | 0          | 10105           | 53:40.7 | 000000000B308A54 |           | 
| A      | 0         |        | Y        | AVE  |         | N        |            | 0          | 98       | E    |               |             | N            |          |        | N       | N        | 1      | 2205        |     |             |             |               |                 |              | 0      |                     |          | 0          | 2151            | 43:29.1 | 000000000B308A55 |           | 
| A      | 0         |        | Y        | AVE  |         | N        |            | 1          | 99       | O    |               |             | N            |          |        | N       | N        | 1      | 2306        |     |             |             |               |                 |              | 0      |                     |          | 0          | 2151            | 43:29.1 | 000000000B308A56 |           | 
| A      | 0         |        | Y        | AVE  |         | N        |            | 100        | 198      | E    |               |             | N            |          |        | N       | N        | 1      | 2205        |     |             |             |               |                 |              | 0      |                     |          | 0          | 2151            | 43:29.1 | 000000000B308A57 |           | 
| A      | 0         |        | Y        | AVE  |         | N        |            | 101        | 199      | O    |               |             | N            |          |        | N       | N        | 1      | 2306        |     |             |             |               |                 |              | 0      |                     |          | 0          | 2151            | 43:29.1 | 000000000B308A58 |           | 
| A      | 0         |        | Y        | AVE  |         | N        |            | 200        | 398      | E    |               |             | N            |          |        | N       | N        | 1      | 2205        |     |             |             |               |                 |              | 0      |                     |          | 0          | 2151            | 43:29.1 | 000000000B308A59 |           | 
| A      | 0         |        | Y        | AVE  |         | N        |            | 201        | 299      | O    |               |             | N            |          |        | N       | N        | 1      | 2306        |     |             |             |               |                 |              | 0      |                     |          | 0          | 2151            | 43:29.1 | 000000000B308A5A |           | 
| A      | 0         |        | Y        | AVE  |         | N        |            | 402        | 498      | E    |               |             | N            |          |        | N       | N        | 1      | 2205        |     |             |             |               |                 |              | 0      |                     |          | 0          | 2151            | 43:29.1 | 000000000B308A5B |           | 
| A      | 0         |        | Y        | AVE  |         | N        |            | 401        | 499      | O    |               |             | N            |          |        | N       | N        | 1      | 2204        |     |             |             |               |                 |              | 0      |                     |          | 0          | 2151            | 43:29.1 | 000000000B308A5C |           | 
| A      | 0         |        | Y        | ST   |         | SW       |            | 500        | 598      | E    |               |             | N            |          |        | N       | N        | 2      | 2210        |     |             |             |               |                 |              | 0      |                     |          | 0          | 0               | 45:41.6 | 000000000B308A5D |           | 
```