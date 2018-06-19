# Cook County Recorder of Deeds - Quit Claim Deeds - 2011 Complete!

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cook-county-recorder-of-deeds-quit-claim-deeds-2011-complete-6f181) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/dskn-nj3p) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/dskn-nj3p/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/dskn-nj3p/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | dskn-nj3p |
| Name | Cook County Recorder of Deeds - Quit Claim Deeds - 2011 Complete! |
| Attribution | Cook County Recorder of Deeds |
| Category | Property & Taxation |
| Created | 2012-04-24T21:14:12Z |
| Publication Date | 2014-10-09T23:13:47Z |

## Description

Quit Claim Deeds recorded from January 1, 2011 through December 31, 2011

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
series e:dskn-nj3p d:2011-01-03T00:00:00.000Z t:doc_number=1100334054 t:pin=25-14-100-016-0000 t:doc_type="CORRECTED QUIT CLAIM DEED" m:consideration_amount=500000

series e:dskn-nj3p d:2011-01-03T00:00:00.000Z t:doc_number=1100334054 t:pin=25-14-100-005-0000 t:doc_type="CORRECTED QUIT CLAIM DEED" m:consideration_amount=500000

series e:dskn-nj3p d:2011-01-03T00:00:00.000Z t:doc_number=1100334054 t:pin=25-14-100-038-0000 t:doc_type="CORRECTED QUIT CLAIM DEED" m:consideration_amount=500000
```

## Meta Commands

```ls
metric m:consideration_amount p:double l:"Consideration Amount" t:dataTypeName=number

entity e:dskn-nj3p l:"Cook County Recorder of Deeds - Quit Claim Deeds - 2011 Complete!" t:attribution="Cook County Recorder of Deeds" t:url=https://datacatalog.cookcountyil.gov/api/views/dskn-nj3p

property e:dskn-nj3p t:meta.view v:id=dskn-nj3p v:category="Property & Taxation" v:attributionLink=http://cookrecorder.com/ v:averageRating=0 v:name="Cook County Recorder of Deeds - Quit Claim Deeds - 2011 Complete!" v:attribution="Cook County Recorder of Deeds"

property e:dskn-nj3p t:meta.view.license v:name="Public Domain"

property e:dskn-nj3p t:meta.view.owner v:id=zker-e3n4 v:profileImageUrlMedium=/api/users/zker-e3n4/profile_images/THUMB v:profileImageUrlLarge=/api/users/zker-e3n4/profile_images/LARGE v:screenName=joe.ruiz v:profileImageUrlSmall=/api/users/zker-e3n4/profile_images/TINY v:displayName=joe.ruiz

property e:dskn-nj3p t:meta.view.tableauthor v:id=zker-e3n4 v:profileImageUrlMedium=/api/users/zker-e3n4/profile_images/THUMB v:profileImageUrlLarge=/api/users/zker-e3n4/profile_images/LARGE v:screenName=joe.ruiz v:profileImageUrlSmall=/api/users/zker-e3n4/profile_images/TINY v:roleName=publisher v:displayName=joe.ruiz
```

## Top Records

```ls
| pin                | doc_number | doc_type                  | recorded_date       | execution_date      | consideration_amount | 
| ================== | ========== | ========================= | =================== | =================== | ==================== | 
| 28-14-316-019-0000 | 1118746023 | QUIT CLAIM DEED           | 2011-07-06T00:00:00 | 2011-06-29T00:00:00 |                      | 
| 19-11-422-030-0000 | 1110928011 | QUIT CLAIM DEED           | 2011-04-19T00:00:00 | 2010-12-14T00:00:00 |                      | 
| 17-18-215-019-1005 | 1100312266 | QUIT CLAIM DEED           | 2011-01-03T00:00:00 | 2010-12-07T00:00:00 |                      | 
| 16-01-326-059-1004 | 1100313007 | QUIT CLAIM DEED           | 2011-01-03T00:00:00 |                     |                      | 
| 17-09-418-014-1104 | 1100318021 | QUIT CLAIM DEED           | 2011-01-03T00:00:00 | 2010-11-15T00:00:00 |                      | 
| 16-26-228-025-0000 | 1100329110 | QUIT CLAIM DEED           | 2011-01-03T00:00:00 | 2010-11-29T00:00:00 |                      | 
| 13-28-407-006-0000 | 1100329090 | QUIT CLAIM DEED           | 2011-01-03T00:00:00 | 2010-10-30T00:00:00 |                      | 
| 32-21-415-041-0000 | 1100313034 | QUIT CLAIM DEED           | 2011-01-03T00:00:00 |                     |                      | 
| 17-20-414-015-0000 | 1100322135 | CORRECTED QUIT CLAIM DEED | 2011-01-03T00:00:00 | 2010-12-07T00:00:00 |                      | 
| 17-04-435-034-1107 | 1100331103 | QUIT CLAIM DEED           | 2011-01-03T00:00:00 | 2010-11-10T00:00:00 |                      | 
```