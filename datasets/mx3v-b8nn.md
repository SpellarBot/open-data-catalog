# Results Posting Schedule - August 2013 Primary

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/results-posting-schedule-august-2013-primary-6e1cc) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/mx3v-b8nn) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/mx3v-b8nn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/mx3v-b8nn/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | mx3v-b8nn |
| Name | Results Posting Schedule - August 2013 Primary |
| Attribution | King County Elections |
| Category | Election operations |
| Tags | elections |
| Created | 2013-07-24T20:58:03Z |
| Publication Date | 2013-07-24T21:01:55Z |

## Columns

```ls
| Included | Schema Type | Field Name                             | Name                                    | Data Type | Render Type |
| ======== | =========== | ====================================== | ======================================= | ========= | =========== |
| Yes      | series tag  | tuesday_aug_6                          |  Tuesday, Aug. 6                        | text      | text        |
| Yes      | series tag  | 8_15_p_m                               | 8:15 p.m.                               | text      | text        |
| Yes      | series tag  | election_day_results_posted_to_the_web | Election day results posted to the web. | text      | text        |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:mx3v-b8nn d:2013-01-01T00:00:00.000Z t:8_15_p_m="8:15 p.m." t:tuesday_aug_6="Tuesday, Aug. 6" t:election_day_results_posted_to_the_web="Election day results posted to the web." m:row_number.mx3v-b8nn=1

series e:mx3v-b8nn d:2013-01-01T00:00:00.000Z t:8_15_p_m="4:30 p.m." t:tuesday_aug_6="Wednesday, Aug. 7" t:election_day_results_posted_to_the_web="Results posted, including votes cast at the accessible voting centers." m:row_number.mx3v-b8nn=2

series e:mx3v-b8nn d:2013-01-01T00:00:00.000Z t:8_15_p_m="4:30 p.m." t:tuesday_aug_6="Thursday, Aug. 8" t:election_day_results_posted_to_the_web="Results posted." m:row_number.mx3v-b8nn=3
```

## Meta Commands

```ls
metric m:row_number.mx3v-b8nn p:long l:"Row Number"

entity e:mx3v-b8nn l:"Results Posting Schedule - August 2013 Primary" t:attribution="King County Elections" t:url=https://data.kingcounty.gov/api/views/mx3v-b8nn

property e:mx3v-b8nn t:meta.view v:id=mx3v-b8nn v:category="Election operations" v:attributionLink=http://kingcounty.gov/elections v:averageRating=0 v:name="Results Posting Schedule - August 2013 Primary" v:attribution="King County Elections"

property e:mx3v-b8nn t:meta.view.license v:name="Public Domain"

property e:mx3v-b8nn t:meta.view.owner v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:displayName="Kathy Gill"

property e:mx3v-b8nn t:meta.view.tableauthor v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:roleName=publisher v:displayName="Kathy Gill"
```