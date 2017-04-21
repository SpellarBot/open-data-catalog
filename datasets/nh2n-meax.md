# FY2015 Annual Report Infant Sleep Location

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fy2015-annual-report-infant-sleep-location) |
| Metadata | [Link](https://data.austintexas.gov/api/views/nh2n-meax) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/nh2n-meax/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/nh2n-meax/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | nh2n-meax |
| Name | FY2015 Annual Report Infant Sleep Location |
| Tags | atcems, fy2015, infant academy, annual report |
| Created | 2016-08-26T19:31:11Z |
| Publication Date | 2016-08-26T19:33:13Z |

## Description

** Static Data Set ** This table shows findings from Infant Academy survey conducted in FY2015 by the ATCEMS Community Relations section. It has been uploaded to support the ATCEMS FY2015 annual report. THE DATA IN THIS TABLE WILL NOT BE UPDATED.

## Columns

```ls
| Included | Schema Type    | Field Name | Name       | Data Type | Render Type |
| ======== | ============== | ========== | ========== | ========= | =========== |
| Yes      | series tag     | location   | Location   | text      | text        |
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
series e:nh2n-meax d:2015-01-01T00:00:00.000Z t:location=Bed m:pre_class=43.5 m:post_class=4.17

series e:nh2n-meax d:2015-01-01T00:00:00.000Z t:location=Crib m:pre_class=30 m:post_class=33.33

series e:nh2n-meax d:2015-01-01T00:00:00.000Z t:location=Bassinet m:pre_class=17.5 m:post_class=26.39
```

## Meta Commands

```ls
metric m:pre_class p:float l:Pre-Class t:dataTypeName=percent

metric m:post_class p:float l:Post-Class t:dataTypeName=percent

entity e:nh2n-meax l:"FY2015 Annual Report Infant Sleep Location" t:url=https://data.austintexas.gov/api/views/nh2n-meax

property e:nh2n-meax t:meta.view v:id=nh2n-meax v:averageRating=0 v:name="FY2015 Annual Report Infant Sleep Location"

property e:nh2n-meax t:meta.view.owner v:id=4zcf-8die v:profileImageUrlMedium=/api/users/4zcf-8die/profile_images/THUMB v:profileImageUrlLarge=/api/users/4zcf-8die/profile_images/LARGE v:screenName="Austin-Travis County EMS" v:profileImageUrlSmall=/api/users/4zcf-8die/profile_images/TINY v:displayName="Austin-Travis County EMS"

property e:nh2n-meax t:meta.view.tableauthor v:id=4zcf-8die v:profileImageUrlMedium=/api/users/4zcf-8die/profile_images/THUMB v:profileImageUrlLarge=/api/users/4zcf-8die/profile_images/LARGE v:screenName="Austin-Travis County EMS" v:profileImageUrlSmall=/api/users/4zcf-8die/profile_images/TINY v:roleName=publisher_stories v:displayName="Austin-Travis County EMS"
```

## Top Records

```ls
| location    | pre_class | post_class | 
| =========== | ========= | ========== | 
| Bed         | 43.50     | 4.17       | 
| Crib        | 30.00     | 33.33      | 
| Bassinet    | 17.50     | 26.39      | 
| Pack-n-Play | 9.00      | 36.11      | 
```