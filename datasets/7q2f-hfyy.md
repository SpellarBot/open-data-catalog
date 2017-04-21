# Results Schedule - August 7, 2012 Primary and Special Election

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/results-schedule-august-7-2012-primary-and-special-election-71c7f) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/7q2f-hfyy) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/7q2f-hfyy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/7q2f-hfyy/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | 7q2f-hfyy |
| Name | Results Schedule - August 7, 2012 Primary and Special Election |
| Attribution | King County Elections |
| Category | Election operations |
| Tags | elections, king county, 2012, results |
| Created | 2012-07-26T19:16:03Z |
| Publication Date | 2012-07-26T19:19:36Z |

## Columns

```ls
| Included | Schema Type | Field Name                             | Name           | Data Type | Render Type |
| ======== | =========== | ====================================== | ============== | ========= | =========== |
| Yes      | series tag  | tuesday_aug_7                          | Date           | text      | text        |
| Yes      | series tag  | p_m                                    | Time           | text      | text        |
| Yes      | series tag  | election_day_results_posted_to_the_web | Results posted | text      | text        |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:7q2f-hfyy d:2012-01-01T00:00:00.000Z t:p_m="8:15 p.m." t:tuesday_aug_7="Tuesday, Aug. 7" t:election_day_results_posted_to_the_web="Election day results posted to the web." m:row_number.7q2f-hfyy=1

series e:7q2f-hfyy d:2012-01-01T00:00:00.000Z t:p_m="4:30 p.m." t:tuesday_aug_7="Wednesday, Aug. 8" t:election_day_results_posted_to_the_web="Results posted, including votes cast at the accessible voting centers." m:row_number.7q2f-hfyy=2

series e:7q2f-hfyy d:2012-01-01T00:00:00.000Z t:p_m="4:30 p.m." t:tuesday_aug_7="Thursday, Aug. 9" t:election_day_results_posted_to_the_web="Results posted." m:row_number.7q2f-hfyy=3
```

## Meta Commands

```ls
metric m:row_number.7q2f-hfyy p:long l:"Row Number"

entity e:7q2f-hfyy l:"Results Schedule - August 7, 2012 Primary and Special Election" t:attribution="King County Elections" t:url=https://data.kingcounty.gov/api/views/7q2f-hfyy

property e:7q2f-hfyy t:meta.view v:id=7q2f-hfyy v:category="Election operations" v:attributionLink=http://kingcounty.gov/elections v:averageRating=0 v:name="Results Schedule - August 7, 2012 Primary and Special Election" v:attribution="King County Elections"

property e:7q2f-hfyy t:meta.view.license v:name="Public Domain"

property e:7q2f-hfyy t:meta.view.owner v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:displayName="Kathy Gill"

property e:7q2f-hfyy t:meta.view.tableauthor v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:roleName=publisher v:displayName="Kathy Gill"
```

## Top Records

```ls
| tuesday_aug_7      | p_m       | election_day_results_posted_to_the_web                                             | 
| ================== | ========= | ================================================================================== | 
|  Tuesday, Aug. 7   | 8:15 p.m. | Election day results posted to the web.                                            | 
| Wednesday, Aug. 8  | 4:30 p.m. | Results posted, including votes cast at the accessible voting centers.             | 
| Thursday, Aug. 9   | 4:30 p.m. | Results posted.                                                                    | 
| Friday, Aug. 10    | 4:30 p.m. | Results posted, and unofficial election day abstract of results posted to the web. | 
| Monday, Aug. 13    | 4:30 p.m. | Results posted.                                                                    | 
| Tuesday, Aug. 14   | 4:30 p.m. | Results posted.                                                                    | 
| Wednesday, Aug. 15 | 4:30 p.m. | Results posted.                                                                    | 
| Thursday, Aug. 16  | 4:30 p.m. | Results posted.                                                                    | 
| Friday, Aug. 17    | 4:30 p.m. | Results posted.                                                                    | 
| Monday, Aug. 20    | 4:30 p.m. | Results posted.                                                                    | 
```