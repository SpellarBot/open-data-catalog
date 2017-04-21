# Cook County Recorder of Deeds - Foreclosures - 2012 January 1 to November 29

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cook-county-recorder-of-deeds-foreclosures-2012-january-1-to-november-29) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/9br9-dhca) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/9br9-dhca/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/9br9-dhca/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | 9br9-dhca |
| Name | Cook County Recorder of Deeds - Foreclosures - 2012 January 1 to November 29 |
| Attribution | Cook County Recorder of Deeds |
| Category | Property & Taxation |
| Tags | foreclosures |
| Created | 2012-04-25T14:36:31Z |
| Publication Date | 2014-10-09T23:11:34Z |

## Description

Foreclosures recorded from January 1, 2012 through November 29, 2012

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type     | Render Type   |
| ======== | ============== | ==================== | ==================== | ============= | ============= |
| Yes      | series tag     | pin                  | Pin                  | text          | text          |
| Yes      | series tag     | doc_number           | Doc Number           | text          | text          |
| Yes      | series tag     | doc_type             | Doc Type             | text          | text          |
| Yes      | time           | recorded_date        | Recorded Date        | calendar_date | calendar_date |
| No       |                | execution_date       | Execution Date       | calendar_date | calendar_date |
| Yes      | numeric metric | consideration_amount | Consideration Amount | number        | number        |
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
metric m:consideration_amount p:float l:"Consideration Amount" t:dataTypeName=number

entity e:9br9-dhca l:"Cook County Recorder of Deeds - Foreclosures - 2012 January 1 to November 29" t:attribution="Cook County Recorder of Deeds" t:url=https://datacatalog.cookcountyil.gov/api/views/9br9-dhca

property e:9br9-dhca t:meta.view v:id=9br9-dhca v:category="Property & Taxation" v:attributionLink=http://cookrecorder.com v:averageRating=0 v:name="Cook County Recorder of Deeds - Foreclosures - 2012 January 1 to November 29" v:attribution="Cook County Recorder of Deeds"

property e:9br9-dhca t:meta.view.license v:name="Public Domain"

property e:9br9-dhca t:meta.view.owner v:id=zker-e3n4 v:profileImageUrlMedium=/api/users/zker-e3n4/profile_images/THUMB v:profileImageUrlLarge=/api/users/zker-e3n4/profile_images/LARGE v:screenName=joe.ruiz v:profileImageUrlSmall=/api/users/zker-e3n4/profile_images/TINY v:displayName=joe.ruiz

property e:9br9-dhca t:meta.view.tableauthor v:id=zker-e3n4 v:profileImageUrlMedium=/api/users/zker-e3n4/profile_images/THUMB v:profileImageUrlLarge=/api/users/zker-e3n4/profile_images/LARGE v:screenName=joe.ruiz v:profileImageUrlSmall=/api/users/zker-e3n4/profile_images/TINY v:roleName=publisher v:displayName=joe.ruiz
```

## Top Records

```ls
| pin                | doc_number | doc_type                        | recorded_date       | execution_date      | consideration_amount | 
| ================== | ========== | =============================== | =================== | =================== | ==================== | 
| 25-04-401-037-0000 | 1203945053 | LIS PENDENS FORECLOSURE         | 2012-02-08T00:00:00 | 2012-02-08T00:00:00 |                      | 
| 02-01-105-084-0000 | 1201031085 | LIS PENDENS FORECLOSURE         | 2012-01-10T00:00:00 | 2012-01-05T00:00:00 |                      | 
| 15-09-107-087-0000 | 1208331003 | LIS PENDENS FORECLOSURE         | 2012-03-23T00:00:00 | 2012-03-21T00:00:00 |                      | 
| 28-14-404-042-0000 | 1200312000 | AMENDED LIS PENDENS FORECLOSURE | 2012-01-03T00:00:00 | 2011-12-16T00:00:00 |                      | 
| 21-30-104-042-1088 | 1200312001 | LIS PENDENS FORECLOSURE         | 2012-01-03T00:00:00 | 2011-12-28T00:00:00 |                      | 
| 02-12-103-004-0000 | 1200312002 | LIS PENDENS FORECLOSURE         | 2012-01-03T00:00:00 | 2011-12-28T00:00:00 |                      | 
| 16-02-326-051-0000 | 1200312006 | LIS PENDENS FORECLOSURE         | 2012-01-03T00:00:00 | 2011-12-28T00:00:00 |                      | 
| 17-04-222-063-1050 | 1200312004 | LIS PENDENS FORECLOSURE         | 2012-01-03T00:00:00 | 2011-12-28T00:00:00 |                      | 
| 17-04-222-063-1088 | 1200312004 | LIS PENDENS FORECLOSURE         | 2012-01-03T00:00:00 | 2011-12-28T00:00:00 |                      | 
| 13-20-314-003-0000 | 1200312019 | LIS PENDENS FORECLOSURE         | 2012-01-03T00:00:00 | 2011-12-28T00:00:00 |                      | 
```