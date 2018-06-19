# Find a Clinic

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/find-a-clinic) |
| Metadata | [Link](https://data.oregon.gov/api/views/xa8e-pddq) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/xa8e-pddq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/xa8e-pddq/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | xa8e-pddq |
| Name | Find a Clinic |
| Category | Health & Human Services |
| Created | 2016-12-12T19:40:06Z |
| Publication Date | 2016-12-12T21:09:31Z |

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | agency      | Agency     | text      | text        |
| Yes      | series tag  | clinic      | Clinic     | url       | url         |
| Yes      | series tag  | phone       | Phone      | text      | text        |
| Yes      | series tag  | county      | County     | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:xa8e-pddq d:2016-12-12T19:40:11.000Z t:phone="(541) 682-7581" t:county=Lane t:agency="CHCs of Lane Co." m:row_number.xa8e-pddq=1

series e:xa8e-pddq d:2016-12-12T19:40:11.000Z t:phone="(541) 451-5932" t:county=Linn t:agency="Linn Co. Health Services" m:row_number.xa8e-pddq=2

series e:xa8e-pddq d:2016-12-12T19:40:11.000Z t:phone="(503) 988-5183" t:county=Multnomah t:agency="Multnomah Co. HD" m:row_number.xa8e-pddq=3
```

## Meta Commands

```ls
metric m:row_number.xa8e-pddq p:long l:"Row Number"

entity e:xa8e-pddq l:"Find a Clinic" t:url=https://data.oregon.gov/api/views/xa8e-pddq

property e:xa8e-pddq t:meta.view v:id=xa8e-pddq v:category="Health & Human Services" v:averageRating=0 v:name="Find a Clinic"

property e:xa8e-pddq t:meta.view.owner v:id=xv7a-3d5f v:profileImageUrlMedium=/api/users/xv7a-3d5f/profile_images/THUMB v:profileImageUrlLarge=/api/users/xv7a-3d5f/profile_images/LARGE v:screenName="Britt Parrott" v:profileImageUrlSmall=/api/users/xv7a-3d5f/profile_images/TINY v:displayName="Britt Parrott"

property e:xa8e-pddq t:meta.view.tableauthor v:id=xv7a-3d5f v:profileImageUrlMedium=/api/users/xv7a-3d5f/profile_images/THUMB v:profileImageUrlLarge=/api/users/xv7a-3d5f/profile_images/LARGE v:screenName="Britt Parrott" v:profileImageUrlSmall=/api/users/xv7a-3d5f/profile_images/TINY v:roleName=editor v:displayName="Britt Parrott"
```

## Top Records

```ls
| :updated_at | agency                   | clinic       | phone          | county    | 
| =========== | ======================== | ============ | ============== | ========= | 
| 1481571611  | CHCs of Lane Co.         | [null, null] | (541) 682-7581 | Lane      | 
| 1481571611  | Linn Co. Health Services | [null, null] | (541) 451-5932 | Linn      | 
| 1481571611  | Multnomah Co. HD         | [null, null] | (503) 988-5183 | Multnomah | 
| 1481571611  | PPCW                     | [null, null] | (503) 775-4931 | Multnomah | 
| 1481571611  | Waterfall Clinic Inc.    | [null, null] | (541) 756-6232 | Coos      | 
| 1481571623  | Multnomah Co. HD         | [null, null] | (503) 988-3370 | Multnomah | 
| 1481571623  | Multnomah Co. HD         | [null, null] | (503) 988-3350 | Multnomah | 
| 1481571623  | Multnomah Co. HD         | [null, null] | (503) 988-5020 | Multnomah | 
| 1481571623  | Rogue Community Health   | [null, null] | (541) 482-9741 | Jackson   | 
| 1481571623  | La Clinica del Valle     | [null, null] | (541) 494-6323 | Jackson   | 
```