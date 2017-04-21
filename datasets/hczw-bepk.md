# FY2015 Annual Report Infant Co-sleep

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fy2015-annual-report-infant-co-sleep) |
| Metadata | [Link](https://data.austintexas.gov/api/views/hczw-bepk) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/hczw-bepk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/hczw-bepk/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | hczw-bepk |
| Name | FY2015 Annual Report Infant Co-sleep |
| Tags | atcems, fy2015, infant academy, annual report |
| Created | 2016-08-26T19:19:59Z |
| Publication Date | 2016-08-26T19:23:01Z |

## Description

** Static Data Set ** This table shows findings from Infant Academy survey conducted in FY2015 by the ATCEMS Community Relations section. It has been uploaded to support the ATCEMS FY2015 annual report. THE DATA IN THIS TABLE WILL NOT BE UPDATED.

## Columns

```ls
| Included | Schema Type    | Field Name | Name       | Data Type | Render Type |
| ======== | ============== | ========== | ========== | ========= | =========== |
| Yes      | series tag     | response   | Response   | text      | text        |
| Yes      | numeric metric | pre_class  | Pre-Class  | percent   | percent     |
| Yes      | numeric metric | post_class | Post-Class | percent   | percent     |
```

## Time Field

```ls
Value = 2015
Format & Zone = yyyy
```

## Data Commands

```ls
series e:hczw-bepk d:2015-01-01T00:00:00.000Z t:response=Yes m:pre_class=56 m:post_class=3

series e:hczw-bepk d:2015-01-01T00:00:00.000Z t:response=No m:pre_class=44 m:post_class=97
```

## Meta Commands

```ls
metric m:pre_class p:integer l:Pre-Class t:dataTypeName=percent

metric m:post_class p:integer l:Post-Class t:dataTypeName=percent

entity e:hczw-bepk l:"FY2015 Annual Report Infant Co-sleep" t:url=https://data.austintexas.gov/api/views/hczw-bepk

property e:hczw-bepk t:meta.view v:id=hczw-bepk v:averageRating=0 v:name="FY2015 Annual Report Infant Co-sleep"

property e:hczw-bepk t:meta.view.owner v:id=4zcf-8die v:profileImageUrlMedium=/api/users/4zcf-8die/profile_images/THUMB v:profileImageUrlLarge=/api/users/4zcf-8die/profile_images/LARGE v:screenName="Austin-Travis County EMS" v:profileImageUrlSmall=/api/users/4zcf-8die/profile_images/TINY v:displayName="Austin-Travis County EMS"

property e:hczw-bepk t:meta.view.tableauthor v:id=4zcf-8die v:profileImageUrlMedium=/api/users/4zcf-8die/profile_images/THUMB v:profileImageUrlLarge=/api/users/4zcf-8die/profile_images/LARGE v:screenName="Austin-Travis County EMS" v:profileImageUrlSmall=/api/users/4zcf-8die/profile_images/TINY v:roleName=publisher_stories v:displayName="Austin-Travis County EMS"
```

## Top Records

```ls
| response | pre_class | post_class | 
| ======== | ========= | ========== | 
| Yes      | 56        | 3          | 
| No       | 44        | 97         | 
```