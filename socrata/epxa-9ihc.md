# Cook County Recorder of Deeds - Foreclosures - 2011 Complete!

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cook-county-recorder-of-deeds-foreclosures-2011-complete-b1f16) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/epxa-9ihc) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/epxa-9ihc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/epxa-9ihc/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | epxa-9ihc |
| Name | Cook County Recorder of Deeds - Foreclosures - 2011 Complete! |
| Attribution | Cook County Recorder of Deeds |
| Category | Property & Taxation |
| Created | 2012-04-25T14:28:05Z |
| Publication Date | 2014-10-09T23:13:19Z |

## Description

Foreclosures recorded from January 1, 2011 through December 31, 2011

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type     | Render Type   |
| ======== | ============== | ==================== | ==================== | ============= | ============= |
| Yes      | series tag     | pin                  | Pin                  | text          | text          |
| Yes      | series tag     | doc_number           | Doc Number           | text          | text          |
| Yes      | series tag     | doc_type             | Doc Type             | text          | text          |
| Yes      | time           | recorded_date        | Recorded Date        | calendar_date | calendar_date |
| No       |                | execution_date       | Execution Date       | calendar_date | calendar_date |
| Yes      | numeric metric | consideration_amount | Consideration Amount | money         | money         |
```

## Time Field

```ls
Value = recorded_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = execution_date
```

## Data Commands

```ls
```

## Meta Commands

```ls
metric m:consideration_amount p:double l:"Consideration Amount" t:dataTypeName=money

entity e:epxa-9ihc l:"Cook County Recorder of Deeds - Foreclosures - 2011 Complete!" t:attribution="Cook County Recorder of Deeds" t:url=https://datacatalog.cookcountyil.gov/api/views/epxa-9ihc

property e:epxa-9ihc t:meta.view v:id=epxa-9ihc v:category="Property & Taxation" v:attributionLink=http://cookrecorder.com/ v:averageRating=0 v:name="Cook County Recorder of Deeds - Foreclosures - 2011 Complete!" v:attribution="Cook County Recorder of Deeds"

property e:epxa-9ihc t:meta.view.license v:name="Public Domain"

property e:epxa-9ihc t:meta.view.owner v:id=zker-e3n4 v:profileImageUrlMedium=/api/users/zker-e3n4/profile_images/THUMB v:profileImageUrlLarge=/api/users/zker-e3n4/profile_images/LARGE v:screenName=joe.ruiz v:profileImageUrlSmall=/api/users/zker-e3n4/profile_images/TINY v:displayName=joe.ruiz

property e:epxa-9ihc t:meta.view.tableauthor v:id=zker-e3n4 v:profileImageUrlMedium=/api/users/zker-e3n4/profile_images/THUMB v:profileImageUrlLarge=/api/users/zker-e3n4/profile_images/LARGE v:screenName=joe.ruiz v:profileImageUrlSmall=/api/users/zker-e3n4/profile_images/TINY v:roleName=publisher v:displayName=joe.ruiz
```

## Top Records

```ls
| pin                | doc_number | doc_type                | recorded_date       | execution_date      | consideration_amount | 
| ================== | ========== | ======================= | =================== | =================== | ==================== | 
| 20-03-103-043-1001 | 1110912180 | LIS PENDENS FORECLOSURE | 2011-04-19T00:00:00 |                     |                      | 
| 17-04-220-082-0000 | 1122234077 | LIS PENDENS FORECLOSURE | 2011-08-10T00:00:00 |                     |                      | 
| 20-08-427-048-0000 | 1127140071 | LIS PENDENS FORECLOSURE | 2011-09-28T00:00:00 |                     |                      | 
| 07-10-101-039-1073 | 1100312179 | LIS PENDENS FORECLOSURE | 2011-01-03T00:00:00 | 2010-12-21T00:00:00 |                      | 
| 17-10-316-033-1155 | 1100312180 | LIS PENDENS FORECLOSURE | 2011-01-03T00:00:00 | 2010-12-20T00:00:00 |                      | 
| 07-10-101-039-1254 | 1100312181 | LIS PENDENS FORECLOSURE | 2011-01-03T00:00:00 | 2010-12-20T00:00:00 |                      | 
| 16-01-413-060-1003 | 1100312183 | LIS PENDENS FORECLOSURE | 2011-01-03T00:00:00 | 2010-12-20T00:00:00 |                      | 
| 10-16-222-036-1042 | 1100312185 | LIS PENDENS FORECLOSURE | 2011-01-03T00:00:00 |                     |                      | 
| 20-06-100-123-1234 | 1100412186 | LIS PENDENS FORECLOSURE | 2011-01-04T00:00:00 | 2010-12-29T00:00:00 |                      | 
| 20-06-100-123-1010 | 1100412186 | LIS PENDENS FORECLOSURE | 2011-01-04T00:00:00 | 2010-12-29T00:00:00 |                      | 
```