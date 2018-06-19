# FY2015 Annual Report Safety Concern Categories.

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fy2015-annual-report-safety-concern-categories) |
| Metadata | [Link](https://data.austintexas.gov/api/views/4q6k-ws8w) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/4q6k-ws8w/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/4q6k-ws8w/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | 4q6k-ws8w |
| Name | FY2015 Annual Report Safety Concern Categories. |
| Tags | atcems, fy2015, annual report, safety |
| Created | 2016-09-26T18:26:49Z |
| Publication Date | 2016-09-26T18:29:27Z |

## Description

** Static Data Set ** This table shows Safety data for FY2015. It has been uploaded to support the ATCEMS FY2015 annual report. THE DATA IN THIS TABLE WILL NOT BE UPDATED.

## Columns

```ls
| Included | Schema Type    | Field Name   | Name          | Data Type | Render Type |
| ======== | ============== | ============ | ============= | ========= | =========== |
| Yes      | series tag     | concern_type | Concern Type  | text      | text        |
| Yes      | numeric metric | count        | Concern Count | number    | number      |
```

## Time Field

```ls
Value = 2015
Format & Zone = yyyy
```

## Data Commands

```ls
series e:4q6k-ws8w d:2015-01-01T00:00:00.000Z t:concern_type="Station Concern" m:count=25

series e:4q6k-ws8w d:2015-01-01T00:00:00.000Z t:concern_type="Process Concern" m:count=15

series e:4q6k-ws8w d:2015-01-01T00:00:00.000Z t:concern_type="Equipment Concern" m:count=13
```

## Meta Commands

```ls
metric m:count p:integer l:"Concern Count" t:dataTypeName=number

entity e:4q6k-ws8w l:"FY2015 Annual Report Safety Concern Categories." t:url=https://data.austintexas.gov/api/views/4q6k-ws8w

property e:4q6k-ws8w t:meta.view v:id=4q6k-ws8w v:averageRating=0 v:name="FY2015 Annual Report Safety Concern Categories."

property e:4q6k-ws8w t:meta.view.owner v:id=4zcf-8die v:profileImageUrlMedium=/api/users/4zcf-8die/profile_images/THUMB v:profileImageUrlLarge=/api/users/4zcf-8die/profile_images/LARGE v:screenName="Austin-Travis County EMS" v:profileImageUrlSmall=/api/users/4zcf-8die/profile_images/TINY v:displayName="Austin-Travis County EMS"

property e:4q6k-ws8w t:meta.view.tableauthor v:id=4zcf-8die v:profileImageUrlMedium=/api/users/4zcf-8die/profile_images/THUMB v:profileImageUrlLarge=/api/users/4zcf-8die/profile_images/LARGE v:screenName="Austin-Travis County EMS" v:profileImageUrlSmall=/api/users/4zcf-8die/profile_images/TINY v:roleName=publisher_stories v:displayName="Austin-Travis County EMS"
```

## Top Records

```ls
| concern_type      | count | 
| ================= | ===== | 
| Station Concern   | 25    | 
| Process Concern   | 15    | 
| Equipment Concern | 13    | 
| Vehicle Concern   | 7     | 
```