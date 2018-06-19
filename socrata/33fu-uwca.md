# Cook County Recorder of Deeds - Mortgages - 2011 Complete!

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cook-county-recorder-of-deeds-mortgages-2011-complete-467a0) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/33fu-uwca) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/33fu-uwca/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/33fu-uwca/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | 33fu-uwca |
| Name | Cook County Recorder of Deeds - Mortgages - 2011 Complete! |
| Attribution | Cook County Recorder of Deeds |
| Category | Property & Taxation |
| Created | 2012-04-24T21:17:21Z |
| Publication Date | 2014-10-09T23:12:45Z |

## Description

Mortgages recorded between January 1, 2011 and December 31, 2011

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
series e:33fu-uwca d:2011-01-05T00:00:00.000Z t:doc_number=1100503028 t:pin=18-04-121-037-1027 t:doc_type=MORTGAGE m:consideration_amount=290000

series e:33fu-uwca d:2011-01-06T00:00:00.000Z t:doc_number=1100633013 t:pin=24-21-206-087-0000 t:doc_type=MORTGAGE m:consideration_amount=70000

series e:33fu-uwca d:2011-01-12T00:00:00.000Z t:doc_number=1101212001 t:pin=22-35-203-006-0000 t:doc_type=MORTGAGE m:consideration_amount=270000
```

## Meta Commands

```ls
metric m:consideration_amount p:double l:"Consideration Amount" t:dataTypeName=money

entity e:33fu-uwca l:"Cook County Recorder of Deeds - Mortgages - 2011 Complete!" t:attribution="Cook County Recorder of Deeds" t:url=https://datacatalog.cookcountyil.gov/api/views/33fu-uwca

property e:33fu-uwca t:meta.view v:id=33fu-uwca v:category="Property & Taxation" v:attributionLink=http://cookrecorder.com/ v:averageRating=0 v:name="Cook County Recorder of Deeds - Mortgages - 2011 Complete!" v:attribution="Cook County Recorder of Deeds"

property e:33fu-uwca t:meta.view.license v:name="Public Domain"

property e:33fu-uwca t:meta.view.owner v:id=zker-e3n4 v:profileImageUrlMedium=/api/users/zker-e3n4/profile_images/THUMB v:profileImageUrlLarge=/api/users/zker-e3n4/profile_images/LARGE v:screenName=joe.ruiz v:profileImageUrlSmall=/api/users/zker-e3n4/profile_images/TINY v:displayName=joe.ruiz

property e:33fu-uwca t:meta.view.tableauthor v:id=zker-e3n4 v:profileImageUrlMedium=/api/users/zker-e3n4/profile_images/THUMB v:profileImageUrlLarge=/api/users/zker-e3n4/profile_images/LARGE v:screenName=joe.ruiz v:profileImageUrlSmall=/api/users/zker-e3n4/profile_images/TINY v:roleName=publisher v:displayName=joe.ruiz
```

## Top Records

```ls
| pin                | doc_number | doc_type | recorded_date       | execution_date      | consideration_amount | 
| ================== | ========== | ======== | =================== | =================== | ==================== | 
| 18-04-121-037-1027 | 1100503028 | MORTGAGE | 2011-01-05T00:00:00 | 2010-12-15T00:00:00 | 290000.00            | 
| 24-21-206-087-0000 | 1100633013 | MORTGAGE | 2011-01-06T00:00:00 | 2010-12-17T00:00:00 | 70000.00             | 
| 22-35-203-006-0000 | 1101212001 | MORTGAGE | 2011-01-12T00:00:00 | 2010-12-27T00:00:00 | 270000.00            | 
| 14-29-107-045-1001 | 1101326009 | MORTGAGE | 2011-01-13T00:00:00 | 2010-12-29T00:00:00 | 380000.00            | 
| 17-28-414-026-1004 | 1102726111 | MORTGAGE | 2011-01-27T00:00:00 | 2011-01-12T00:00:00 | 70000.00             | 
| 17-16-116-033-1031 | 1103233033 | MORTGAGE | 2011-02-01T00:00:00 | 2011-01-14T00:00:00 | 240000.00            | 
| 17-22-110-135-1157 | 1103808187 | MORTGAGE | 2011-02-07T00:00:00 | 2011-01-18T00:00:00 | 480000.00            | 
| 17-09-115-029-0000 | 1103919006 | MORTGAGE | 2011-02-08T00:00:00 | 2011-01-18T00:00:00 | 690000.00            | 
| 17-27-109-053-0000 | 1104112031 | MORTGAGE | 2011-02-10T00:00:00 | 2011-01-21T00:00:00 | 200000.00            | 
| 17-10-309-016-1101 | 1104511011 | MORTGAGE | 2011-02-14T00:00:00 | 2011-01-26T00:00:00 | 500000.00            | 
```