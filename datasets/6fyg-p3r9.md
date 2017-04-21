# Street Address Listing

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/street-address-listing) |
| Metadata | [Link](https://data.brla.gov/api/views/6fyg-p3r9) |
| Data: JSON | [100 Rows](https://data.brla.gov/api/views/6fyg-p3r9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.brla.gov/api/views/6fyg-p3r9/rows.csv?max_rows=100) |
| Host | data.brla.gov |
| Id | 6fyg-p3r9 |
| Name | Street Address Listing |
| Attribution | Department of Information Services |
| Category | Housing and Development |
| Tags | address, street, lot, property |
| Created | 2016-06-10T02:10:59Z |
| Publication Date | 2016-06-10T19:38:31Z |

## Description

Complete listing of all street addresses in East Baton Rouge Parish.

## Columns

```ls
| Included | Schema Type | Field Name          | Name                    | Data Type | Render Type |
| ======== | =========== | =================== | ======================= | ========= | =========== |
| No       | time        | :updated_at         | updated_at              | meta_data | meta_data   |
| No       |             | address_no_complete | ADDRESS NO              | text      | text        |
| Yes      | series tag  | st_prefix_dir       | STREET PREFIX DIRECTION | text      | text        |
| Yes      | series tag  | st_name             | STREET NAME             | text      | text        |
| Yes      | series tag  | st_suffix_type      | STREET SUFFIX TYPE      | text      | text        |
| Yes      | series tag  | city                | CITY                    | text      | text        |
| Yes      | series tag  | zip                 | ZIP                     | text      | text        |
| Yes      | series tag  | district_num        | COUNCIL DISTRICT NO     | text      | number      |
| Yes      | series tag  | council_person      | COUNCILPERSON NAME      | text      | text        |
| Yes      | series tag  | lot_location        | JURISDICTION            | text      | text        |
| Yes      | series tag  | st_suffix_dir       | ST_SUFFIX_DIR           | text      | text        |
| Yes      | series tag  | st_ext              | ST_EXT                  | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address_no_complete
```

## Data Commands

```ls
series e:6fyg-p3r9 d:2016-06-09T19:18:09.000Z t:zip=70714 t:lot_location=CENTRAL t:st_suffix_type=RD t:st_name=CAREY t:council_person="Trae Welch" t:district_num=1 t:city=BAKER m:row_number.6fyg-p3r9=1

series e:6fyg-p3r9 d:2016-06-09T19:18:09.000Z t:zip=70714 t:lot_location=CENTRAL t:st_suffix_type=RD t:st_name=BLACKWATER t:council_person="Scott Wilson" t:district_num=4 t:city=BAKER m:row_number.6fyg-p3r9=2

series e:6fyg-p3r9 d:2016-06-09T19:18:09.000Z t:zip=70714 t:lot_location=CENTRAL t:st_suffix_type=RD t:st_name=BLACKWATER t:council_person="Scott Wilson" t:district_num=4 t:city=BAKER m:row_number.6fyg-p3r9=3
```

## Meta Commands

```ls
metric m:row_number.6fyg-p3r9 p:long l:"Row Number"

entity e:6fyg-p3r9 l:"Street Address Listing" t:attribution="Department of Information Services" t:url=https://data.brla.gov/api/views/6fyg-p3r9

property e:6fyg-p3r9 t:meta.view v:id=6fyg-p3r9 v:category="Housing and Development" v:attributionLink=https://brgov.com/dept/is/ v:averageRating=0 v:name="Street Address Listing" v:attribution="Department of Information Services"

property e:6fyg-p3r9 t:meta.view.license v:name="Public Domain"

property e:6fyg-p3r9 t:meta.view.owner v:id=mjn2-v86v v:profileImageUrlMedium=/api/users/mjn2-v86v/profile_images/THUMB v:profileImageUrlLarge=/api/users/mjn2-v86v/profile_images/LARGE v:screenName="Open Data BR" v:profileImageUrlSmall=/api/users/mjn2-v86v/profile_images/TINY v:displayName="Open Data BR"

property e:6fyg-p3r9 t:meta.view.tableauthor v:id=mjn2-v86v v:profileImageUrlMedium=/api/users/mjn2-v86v/profile_images/THUMB v:profileImageUrlLarge=/api/users/mjn2-v86v/profile_images/LARGE v:screenName="Open Data BR" v:profileImageUrlSmall=/api/users/mjn2-v86v/profile_images/TINY v:roleName=viewer v:displayName="Open Data BR"
```

## Top Records

```ls
| :updated_at | address_no_complete | st_prefix_dir | st_name    | st_suffix_type | city    | zip   | district_num | council_person | lot_location | st_suffix_dir | st_ext | 
| =========== | =================== | ============= | ========== | ============== | ======= | ===== | ============ | ============== | ============ | ============= | ====== | 
| 1465499889  | 14443               |               | CAREY      | RD             | BAKER   | 70714 | 1            | Trae Welch     | CENTRAL      |               |        | 
| 1465499889  | 12530               |               | BLACKWATER | RD             | BAKER   | 70714 | 4            | Scott Wilson   | CENTRAL      |               |        | 
| 1465499889  | 12400-12900 UND     |               | BLACKWATER | RD             | BAKER   | 70714 | 4            | Scott Wilson   | CENTRAL      |               |        | 
| 1465499889  | 12400-12900 UND     |               | BLACKWATER | RD             | BAKER   | 70714 | 4            | Scott Wilson   | CENTRAL      |               |        | 
| 1465499889  | 12656               |               | BLACKWATER | RD             | BAKER   | 70714 | 4            | Scott Wilson   | CENTRAL      |               |        | 
| 1465499889  | 12400-12900 UND     |               | BLACKWATER | RD             | BAKER   | 70714 | 4            | Scott Wilson   | CENTRAL      |               |        | 
| 1465499889  | 12900-13000 UND     |               | BLACKWATER | RD             | BAKER   | 70714 | 4            | Scott Wilson   | CENTRAL      |               |        | 
| 1465499889  | 14110               |               | CAREY      | RD             | BAKER   | 70714 | 1            | Trae Welch     | CENTRAL      |               |        | 
| 1465499889  | 13400-14700 UND     |               | CAREY      | RD             | BAKER   | 70714 | 1            | Trae Welch     | CENTRAL      |               |        | 
| 1465499889  | 13265               |               | LOVETT     | RD             | CENTRAL | 70818 | 4            | Scott Wilson   | CENTRAL      |               |        | 
```