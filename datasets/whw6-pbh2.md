# Street Names

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/street-names) |
| Metadata | [Link](https://data.brla.gov/api/views/whw6-pbh2) |
| Data: JSON | [100 Rows](https://data.brla.gov/api/views/whw6-pbh2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.brla.gov/api/views/whw6-pbh2/rows.csv?max_rows=100) |
| Host | data.brla.gov |
| Id | whw6-pbh2 |
| Name | Street Names |
| Attribution | City-Parish Planning Commission |
| Category | Transportation and Infrastructure |
| Tags | street, road, street name, transportation |
| Created | 2014-12-01T00:40:12Z |
| Publication Date | 2017-01-03T21:00:18Z |

## Description

Official public and private street name listing for East Baton Rouge Parish, Louisiana.

## Columns

```ls
| Included | Schema Type | Field Name          | Name                    | Data Type | Render Type |
| ======== | =========== | =================== | ======================= | ========= | =========== |
| No       | time        | :updated_at         | updated_at              | meta_data | meta_data   |
| Yes      | series tag  | st_name_id          | STREET NAME ID          | text      | number      |
| Yes      | series tag  | st_prefix_dir       | STREET PREFIX DIRECTION | text      | text        |
| Yes      | series tag  | st_name             | STREET NAME             | text      | text        |
| Yes      | series tag  | st_suffix_type      | STREET SUFFIX TYPE      | text      | text        |
| Yes      | series tag  | st_suffix_dir       | STREET SUFFIX DIRECTION | text      | text        |
| Yes      | series tag  | st_ext              | STREET EXTENSION        | text      | text        |
| Yes      | series tag  | postal_community    | POSTAL COMMUNITY        | text      | text        |
| Yes      | series tag  | municipal_community | MUNICIPAL COMMUNITY     | text      | text        |
| Yes      | series tag  | notation            | NOTATION                | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:whw6-pbh2 d:2017-01-09T14:14:12.000Z t:st_suffix_type=ST t:postal_community=BAKER t:st_name=TOLEDO t:st_name_id=4881 t:notation=NONE t:municipal_community=PARISH m:row_number.whw6-pbh2=1

series e:whw6-pbh2 d:2017-01-09T14:14:10.000Z t:st_prefix_dir=N t:st_suffix_type=ST t:postal_community="BATON ROUGE" t:st_name=4TH t:st_name_id=1 t:notation=NONE t:municipal_community="BATON ROUGE" m:row_number.whw6-pbh2=2

series e:whw6-pbh2 d:2017-01-09T14:14:10.000Z t:st_prefix_dir=S t:st_suffix_type=ST t:postal_community="BATON ROUGE" t:st_name=11TH t:st_name_id=10 t:notation=NONE t:municipal_community="BATON ROUGE" m:row_number.whw6-pbh2=3
```

## Meta Commands

```ls
metric m:row_number.whw6-pbh2 p:long l:"Row Number"

entity e:whw6-pbh2 l:"Street Names" t:attribution="City-Parish Planning Commission" t:url=https://data.brla.gov/api/views/whw6-pbh2

property e:whw6-pbh2 t:meta.view v:id=whw6-pbh2 v:category="Transportation and Infrastructure" v:attributionLink=http://brgov.com/dept/planning v:averageRating=0 v:name="Street Names" v:attribution="City-Parish Planning Commission"

property e:whw6-pbh2 t:meta.view.license v:name="Public Domain"

property e:whw6-pbh2 t:meta.view.owner v:id=mjn2-v86v v:profileImageUrlMedium=/api/users/mjn2-v86v/profile_images/THUMB v:profileImageUrlLarge=/api/users/mjn2-v86v/profile_images/LARGE v:screenName="Open Data BR" v:profileImageUrlSmall=/api/users/mjn2-v86v/profile_images/TINY v:displayName="Open Data BR"

property e:whw6-pbh2 t:meta.view.tableauthor v:id=mjn2-v86v v:profileImageUrlMedium=/api/users/mjn2-v86v/profile_images/THUMB v:profileImageUrlLarge=/api/users/mjn2-v86v/profile_images/LARGE v:screenName="Open Data BR" v:profileImageUrlSmall=/api/users/mjn2-v86v/profile_images/TINY v:roleName=viewer v:displayName="Open Data BR"
```

## Top Records

```ls
| :updated_at | st_name_id | st_prefix_dir | st_name       | st_suffix_type | st_suffix_dir | st_ext | postal_community | municipal_community | notation | 
| =========== | ========== | ============= | ============= | ============== | ============= | ====== | ================ | =================== | ======== | 
| 1483971252  | 4881       |               | TOLEDO        | ST             |               |        | BAKER            | PARISH              | NONE     | 
| 1483971250  | 1          | N             | 4TH           | ST             |               |        | BATON ROUGE      | BATON ROUGE         | NONE     | 
| 1483971250  | 10         | S             | 11TH          | ST             |               |        | BATON ROUGE      | BATON ROUGE         | NONE     | 
| 1483971250  | 100        |               | ADDINGTON     | AVE            |               |        | BATON ROUGE      | BATON ROUGE         | NONE     | 
| 1483971250  | 1000       | W             | CHALFONT      | DR             |               |        | BATON ROUGE      | PARISH              | NONE     | 
| 1483971250  | 1000001    |               | PRIVATE ALLEY |                |               |        | BATON ROUGE      | PARISH              | NONE     | 
| 1483971250  | 1000002    |               | PRIVATE ALLEY |                |               |        | BATON ROUGE      | PARISH              | NONE     | 
| 1483971250  | 1000003    |               | PRIVATE ALLEY |                |               |        | BATON ROUGE      | PARISH              | NONE     | 
| 1483971250  | 1000004    |               | PRIVATE ALLEY |                |               |        | BATON ROUGE      | PARISH              | NONE     | 
| 1483971250  | 1000005    |               | PRIVATE ALLEY |                |               |        | BATON ROUGE      | PARISH              | NONE     | 
```