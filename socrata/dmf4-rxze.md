# Oregon Department of Forestry - Contingency Support Positions - Fire Season 2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/oregon-department-of-forestry-contingency-support-positions-fire-season-2015) |
| Metadata | [Link](https://data.oregon.gov/api/views/dmf4-rxze) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/dmf4-rxze/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/dmf4-rxze/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | dmf4-rxze |
| Name | Oregon Department of Forestry - Contingency Support Positions - Fire Season 2015 |
| Category | Administrative |
| Created | 2015-07-27T22:05:40Z |
| Publication Date | 2015-08-06T15:49:47Z |

## Description

Oregon Department of Forestry - Contingency Support Positions - Fire Season 2015

## Columns

```ls
| Included | Schema Type | Field Name               | Name                     | Data Type      | Render Type    |
| ======== | =========== | ======================== | ======================== | ============== | ============== |
| Yes      | series tag  | resource_you_can_provide | Resource You Can Provide | drop_down_list | drop_down_list |
| Yes      | series tag  | nam                      | Name of Resource         | text           | text           |
| Yes      | series tag  | agency                   | Agency                   | text           | dataset_link   |
| Yes      | series tag  | contact_phone            | Contact Phone            | phone          | phone          |
```

## Time Field

```ls
Value = 2015
Format & Zone = yyyy
```

## Data Commands

```ls
series e:dmf4-rxze d:2015-01-01T00:00:00.000Z t:nam="Jane Lee" t:phone_number="503 507 1914" t:resource_you_can_provide=bjxg-udw3 t:phone_type=Cell t:agency="Transportation Department" m:row_number.dmf4-rxze=1

series e:dmf4-rxze d:2015-01-01T00:00:00.000Z t:nam="Linda Atkin" t:phone_number="503 378 5397" t:resource_you_can_provide=56qz-rx4g t:phone_type=Work t:agency="Transportation Department" m:row_number.dmf4-rxze=2

series e:dmf4-rxze d:2015-01-01T00:00:00.000Z t:nam="Sarah Penrose" t:phone_number=5039834188 t:resource_you_can_provide=ve97-38h5 t:phone_type=Cell t:agency="Transportation Department" m:row_number.dmf4-rxze=3
```

## Meta Commands

```ls
metric m:row_number.dmf4-rxze p:long l:"Row Number"

entity e:dmf4-rxze l:"Oregon Department of Forestry - Contingency Support Positions - Fire Season 2015" t:url=https://data.oregon.gov/api/views/dmf4-rxze

property e:dmf4-rxze t:meta.view v:id=dmf4-rxze v:category=Administrative v:averageRating=0 v:name="Oregon Department of Forestry - Contingency Support Positions - Fire Season 2015"

property e:dmf4-rxze t:meta.view.owner v:id=emds-3uuf v:profileImageUrlMedium=/api/users/emds-3uuf/profile_images/THUMB v:profileImageUrlLarge=/api/users/emds-3uuf/profile_images/LARGE v:screenName="Sabrina Perez" v:profileImageUrlSmall=/api/users/emds-3uuf/profile_images/TINY v:displayName="Sabrina Perez"

property e:dmf4-rxze t:meta.view.tableauthor v:id=emds-3uuf v:profileImageUrlMedium=/api/users/emds-3uuf/profile_images/THUMB v:profileImageUrlLarge=/api/users/emds-3uuf/profile_images/LARGE v:screenName="Sabrina Perez" v:profileImageUrlSmall=/api/users/emds-3uuf/profile_images/TINY v:roleName=editor v:displayName="Sabrina Perez"
```

## Top Records

```ls
| resource_you_can_provide | nam           | agency                    | contact_phone        | 
| ======================== | ============= | ========================= | ==================== | 
| bjxg-udw3                | Jane Lee      | Transportation Department | [503 507 1914, Cell] | 
| 56qz-rx4g                | Linda Atkin   | Transportation Department | [503 378 5397, Work] | 
| ve97-38h5                | Sarah Penrose | Transportation Department | [5039834188, Cell]   | 
| ve97-38h5                | Kris Nienke   | Transportation Department | [503 986 3828, Work] | 
| 6y4n-zbyq                |               |                           | [null, null]         | 
| ve97-38h5                | Amanda Dotson | Transportation Department | [9719985038, Cell]   | 
| 3bby-xmtv                |               |                           | [null, null]         | 
| ve97-38h5                | Patty Parsons | Transportation Department | [503.986.3951, null] | 
| 6y4n-zbyq                | Mary Rooper   | Transportation Department | [503-986-3952, Work] | 
| 3bby-xmtv                | Shirley Wait  | Transportation Department | [503 986-3936, Work] | 
```