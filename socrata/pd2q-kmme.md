# King County Metro

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/king-county-metro-119f4) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/pd2q-kmme) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/pd2q-kmme/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/pd2q-kmme/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | pd2q-kmme |
| Name | King County Metro |
| Attribution | King County |
| Category | Transportation |
| Tags | metro, bus, water taxi, boat, train, streetcar, schedule, stops |
| Created | 2011-03-24T17:22:29Z |
| Publication Date | 2011-04-17T00:03:09Z |

## Description

King County Metro's data is at http://www.kingcounty.gov/transportation/kcdot/MetroTransit/Developers.aspx

## Columns

```ls
| Included | Schema Type | Field Name                                       | Name                                             | Data Type | Render Type |
| ======== | =========== | ================================================ | ================================================ | ========= | =========== |
| No       | time        | :updated_at                                      | updated_at                                       | meta_data | meta_data   |
| Yes      | series tag  | king_county_metro_data_is_stored_on_another_site | King County Metro data is stored on another site | text      | text        |
| Yes      | series tag  | metro_data_portal                                | Metro data portal                                | url       | url         |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:pd2q-kmme d:2011-03-24T10:25:52.000Z t:king_county_metro_data_is_stored_on_another_site="Visit the main King County Metro data portal for King County Metro data" t:metro_data_portal=http://www.kingcounty.gov/transportation/kcdot/MetroTransit/Developers.aspx m:row_number.pd2q-kmme=1
```

## Meta Commands

```ls
metric m:row_number.pd2q-kmme p:long l:"Row Number"

entity e:pd2q-kmme l:"King County Metro" t:attribution="King County" t:url=https://data.kingcounty.gov/api/views/pd2q-kmme

property e:pd2q-kmme t:meta.view v:id=pd2q-kmme v:category=Transportation v:attributionLink=http://www.kingcounty.gov/transportation/kcdot/MetroTransit/Developers.aspx v:averageRating=0 v:name="King County Metro" v:attribution="King County"

property e:pd2q-kmme t:meta.view.license v:name="Public Domain"

property e:pd2q-kmme t:meta.view.owner v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:displayName="King County Webteam"

property e:pd2q-kmme t:meta.view.tableauthor v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:roleName=administrator v:displayName="King County Webteam"
```

## Top Records

```ls
| :updated_at | king_county_metro_data_is_stored_on_another_site                        | metro_data_portal                                                                                                                                          | 
| =========== | ======================================================================= | ========================================================================================================================================================== | 
| 1300962352  | Visit the main King County Metro data portal for King County Metro data | [http://www.kingcounty.gov/transportation/kcdot/MetroTransit/Developers.aspx, http://www.kingcounty.gov/transportation/kcdot/MetroTransit/Developers.aspx] | 
```