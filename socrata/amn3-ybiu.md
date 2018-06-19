# Microsite-rockford

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/microsite-rockford-553e2) |
| Metadata | [Link](https://data.illinois.gov/api/views/amn3-ybiu) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/amn3-ybiu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/amn3-ybiu/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | amn3-ybiu |
| Name | Microsite-rockford |
| Created | 2013-01-15T17:39:04Z |
| Publication Date | 2016-07-26T16:32:39Z |

## Description

Control dataset for Rockford microsite page

## Columns

```ls
| Included | Schema Type | Field Name           | Name                 | Data Type | Render Type |
| ======== | =========== | ==================== | ==================== | ========= | =========== |
| No       | time        | :updated_at          | updated_at           | meta_data | meta_data   |
| Yes      | series tag  | featured_stat        | featured stat        | text      | text        |
| Yes      | series tag  | featured_description | featured description | text      | text        |
| Yes      | series tag  | featured_title       | featured title       | text      | text        |
| Yes      | series tag  | featured_agency      | featured agency      | text      | text        |
| Yes      | series tag  | agency_icon          | agency icon          | photo     | photo       |
| Yes      | series tag  | featured_text        | featured text        | text      | text        |
| Yes      | series tag  | featured_thumbnail   | featured thumbnail   | photo     | photo       |
| Yes      | series tag  | featured_link        | featured link        | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:amn3-ybiu d:2013-01-17T13:11:19.000Z t:featured_description="Graffiti Reduction Over Six Years" t:featured_agency="City of Rockford" t:featured_text="Close collaboration between City Departments, quick abatement and active prosecution of offenders reduces graffiti." t:featured_stat=61% t:featured_title="Rockford Graffiti Declines" t:featured_link=u4ca-yfeq t:featured_thumbnail=BSGy7TfiOcTx8mXCTEqlzT68axj1hGzkBB3oQpa0li0 t:agency_icon=kgJX2YXHgUTXpETb2MiVSj4UQ9o67qTneGdwYKgQBss m:row_number.amn3-ybiu=1

series e:amn3-ybiu d:2013-01-17T13:11:42.000Z t:featured_description="Increase in EMS calls for service" t:featured_agency="City of Rockford Fire Department" t:featured_text="EMS calls for service continue to climb at a compounded 3.6% rate for an overall increase of 52% since 2000." t:featured_stat=52% t:featured_title="EMS calls continue to increase" t:featured_link=tp88-ynix t:featured_thumbnail=ZhXILbCXois3C6KYxHK8-k-Yl65y4u8CAU4r2LUKF-8 t:agency_icon=kgJX2YXHgUTXpETb2MiVSj4UQ9o67qTneGdwYKgQBss m:row_number.amn3-ybiu=2

series e:amn3-ybiu d:2013-01-17T13:16:53.000Z t:featured_description="Permits issued since 2009" t:featured_agency="City of Rockford Building Department" t:featured_text="Building permits issued since 2009" t:featured_stat=38,500 t:featured_title="Issued Building Permits" t:featured_link=stav-rdug t:featured_thumbnail=H4nXt_4B2CgwN4EbCkVQmKsJdBiNLEXn6VRdG_EoILc t:agency_icon=kgJX2YXHgUTXpETb2MiVSj4UQ9o67qTneGdwYKgQBss m:row_number.amn3-ybiu=3
```

## Meta Commands

```ls
metric m:row_number.amn3-ybiu p:long l:"Row Number"

entity e:amn3-ybiu l:Microsite-rockford t:url=https://data.illinois.gov/api/views/amn3-ybiu

property e:amn3-ybiu t:meta.view v:id=amn3-ybiu v:averageRating=0 v:name=Microsite-rockford

property e:amn3-ybiu t:meta.view.owner v:id=zs8p-j3v5 v:profileImageUrlMedium=/api/users/zs8p-j3v5/profile_images/THUMB v:profileImageUrlLarge=/api/users/zs8p-j3v5/profile_images/LARGE v:screenName="Darrell Cabales" v:profileImageUrlSmall=/api/users/zs8p-j3v5/profile_images/TINY v:displayName="Darrell Cabales"

property e:amn3-ybiu t:meta.view.tableauthor v:id=zs8p-j3v5 v:profileImageUrlMedium=/api/users/zs8p-j3v5/profile_images/THUMB v:profileImageUrlLarge=/api/users/zs8p-j3v5/profile_images/LARGE v:screenName="Darrell Cabales" v:profileImageUrlSmall=/api/users/zs8p-j3v5/profile_images/TINY v:displayName="Darrell Cabales"
```

## Top Records

```ls
| :updated_at | featured_stat | featured_description              | featured_title                 | featured_agency                      | agency_icon                                 | featured_text                                                                                                       | featured_thumbnail                          | featured_link | 
| =========== | ============= | ================================= | ============================== | ==================================== | =========================================== | =================================================================================================================== | =========================================== | ============= | 
| 1358428279  | 61%           | Graffiti Reduction Over Six Years | Rockford Graffiti Declines     | City of Rockford                     | kgJX2YXHgUTXpETb2MiVSj4UQ9o67qTneGdwYKgQBss | Close collaboration between City Departments, quick abatement and active prosecution of offenders reduces graffiti. | BSGy7TfiOcTx8mXCTEqlzT68axj1hGzkBB3oQpa0li0 | u4ca-yfeq     | 
| 1358428302  | 52%           | Increase in EMS calls for service | EMS calls continue to increase | City of Rockford Fire Department     | kgJX2YXHgUTXpETb2MiVSj4UQ9o67qTneGdwYKgQBss | EMS calls for service continue to climb at a compounded 3.6% rate for an overall increase of 52% since 2000.        | ZhXILbCXois3C6KYxHK8-k-Yl65y4u8CAU4r2LUKF-8 | tp88-ynix     | 
| 1358428613  | 38,500        | Permits issued since 2009         | Issued Building Permits        | City of Rockford Building Department | kgJX2YXHgUTXpETb2MiVSj4UQ9o67qTneGdwYKgQBss | Building permits issued since 2009                                                                                  | H4nXt_4B2CgwN4EbCkVQmKsJdBiNLEXn6VRdG_EoILc | stav-rdug     | 
| 1469515975  | 1,100         | City Employees                    | Employee Total Compensation    | City of Rockford                     | kgJX2YXHgUTXpETb2MiVSj4UQ9o67qTneGdwYKgQBss | Compensation of employees including base salary, overtime, health insurance and pension costs.                      | RqsdxAEah_6VGxWuadmgPUd8uSVIs5zJrYBhv0SxmqE | 7e32-cf2y     | 
```