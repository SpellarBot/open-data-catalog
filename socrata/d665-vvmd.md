# Assessor

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/assessor-f97c5) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/d665-vvmd) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/d665-vvmd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/d665-vvmd/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | d665-vvmd |
| Name | Assessor |
| Attribution | King County |
| Category | Property |
| Tags | assessor, assessment, property, value, tax |
| Created | 2011-03-24T16:59:54Z |
| Publication Date | 2011-04-17T00:03:09Z |

## Description

King County Assessor's data is at http://info.kingcounty.gov/assessor/DataDownload/

## Columns

```ls
| Included | Schema Type | Field Name                                          | Name                                                | Data Type | Render Type |
| ======== | =========== | =================================================== | =================================================== | ========= | =========== |
| No       | time        | :updated_at                                         | updated_at                                          | meta_data | meta_data   |
| Yes      | series tag  | king_county_assessor_data_is_stored_on_another_site | KIng County Assessor data is stored on another site | text      | text        |
| Yes      | series tag  | assessor_data_portal                                | Assessor data portal                                | url       | url         |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:d665-vvmd d:2011-03-24T10:06:00.000Z t:king_county_assessor_data_is_stored_on_another_site="Visit the main King County  Department of Assessments data portal for County Assessor data." t:assessor_data_portal=http://info.kingcounty.gov/assessor/DataDownload/ m:row_number.d665-vvmd=1
```

## Meta Commands

```ls
metric m:row_number.d665-vvmd p:long l:"Row Number"

entity e:d665-vvmd l:Assessor t:attribution="King County" t:url=https://data.kingcounty.gov/api/views/d665-vvmd

property e:d665-vvmd t:meta.view v:id=d665-vvmd v:category=Property v:attributionLink=http://info.kingcounty.gov/assessor/DataDownload/default.aspx v:averageRating=0 v:name=Assessor v:attribution="King County"

property e:d665-vvmd t:meta.view.license v:name="Public Domain"

property e:d665-vvmd t:meta.view.owner v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:displayName="King County Webteam"

property e:d665-vvmd t:meta.view.tableauthor v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:roleName=administrator v:displayName="King County Webteam"
```

## Top Records

```ls
| :updated_at | king_county_assessor_data_is_stored_on_another_site                                        | assessor_data_portal                                                                                   | 
| =========== | ========================================================================================== | ====================================================================================================== | 
| 1300961160  | Visit the main King County Department of Assessments data portal for County Assessor data. | [http://info.kingcounty.gov/assessor/DataDownload/, http://info.kingcounty.gov/assessor/DataDownload/] | 
```