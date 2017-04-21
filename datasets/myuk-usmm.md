# Cook County Recorder of Deeds - Mortgages - 2012 January 1 to November 29

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cook-county-recorder-of-deeds-mortgages-2012-january-1-to-november-29) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/myuk-usmm) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/myuk-usmm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/myuk-usmm/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | myuk-usmm |
| Name | Cook County Recorder of Deeds - Mortgages - 2012 January 1 to November 29 |
| Attribution | Cook County Recorder of Deeds |
| Category | Property & Taxation |
| Tags | mortgages |
| Created | 2012-04-25T15:35:32Z |
| Publication Date | 2014-10-09T23:11:49Z |

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
series e:myuk-usmm d:2012-01-19T00:00:00.000Z t:doc_number=1201956019 t:pin=13-09-206-023-0000 t:doc_type=MORTGAGE m:consideration_amount=366000

series e:myuk-usmm d:2012-03-14T00:00:00.000Z t:doc_number=1207447052 t:pin=17-08-336-043-1025 t:doc_type=MORTGAGE m:consideration_amount=417000

series e:myuk-usmm d:2012-02-10T00:00:00.000Z t:doc_number=1204108277 t:pin=27-30-207-020-0000 t:doc_type=MORTGAGE m:consideration_amount=407000
```

## Meta Commands

```ls
metric m:consideration_amount p:double l:"Consideration Amount" t:dataTypeName=money

entity e:myuk-usmm l:"Cook County Recorder of Deeds - Mortgages - 2012 January 1 to November 29" t:attribution="Cook County Recorder of Deeds" t:url=https://datacatalog.cookcountyil.gov/api/views/myuk-usmm

property e:myuk-usmm t:meta.view v:id=myuk-usmm v:category="Property & Taxation" v:attributionLink=http://cookrecorder.com v:averageRating=0 v:name="Cook County Recorder of Deeds - Mortgages - 2012 January 1 to November 29" v:attribution="Cook County Recorder of Deeds"

property e:myuk-usmm t:meta.view.owner v:id=zker-e3n4 v:profileImageUrlMedium=/api/users/zker-e3n4/profile_images/THUMB v:profileImageUrlLarge=/api/users/zker-e3n4/profile_images/LARGE v:screenName=joe.ruiz v:profileImageUrlSmall=/api/users/zker-e3n4/profile_images/TINY v:displayName=joe.ruiz

property e:myuk-usmm t:meta.view.tableauthor v:id=zker-e3n4 v:profileImageUrlMedium=/api/users/zker-e3n4/profile_images/THUMB v:profileImageUrlLarge=/api/users/zker-e3n4/profile_images/LARGE v:screenName=joe.ruiz v:profileImageUrlSmall=/api/users/zker-e3n4/profile_images/TINY v:roleName=publisher v:displayName=joe.ruiz
```

## Top Records

```ls
| pin                | doc_number | doc_type | recorded_date       | execution_date      | consideration_amount | 
| ================== | ========== | ======== | =================== | =================== | ==================== | 
| 13-09-206-023-0000 | 1201956019 | MORTGAGE | 2012-01-19T00:00:00 | 2012-01-06T00:00:00 | 366000.00            | 
| 17-08-336-043-1025 | 1207447052 | MORTGAGE | 2012-03-14T00:00:00 | 2012-03-07T00:00:00 | 417000.00            | 
| 27-30-207-020-0000 | 1204108277 | MORTGAGE | 2012-02-10T00:00:00 | 2012-01-27T00:00:00 | 407000.00            | 
| 17-22-110-035-1043 | 1210326123 | MORTGAGE | 2012-04-12T00:00:00 | 2012-03-28T00:00:00 | 403000.00            | 
| 04-17-305-023-0000 | 1206042049 | MORTGAGE | 2012-02-29T00:00:00 | 2012-02-14T00:00:00 | 290000.00            | 
| 24-10-223-024-0000 | 1209456026 | MORTGAGE | 2012-04-03T00:00:00 | 2012-03-26T00:00:00 | 203200.00            | 
| 04-21-306-001-0000 | 1208234046 | MORTGAGE | 2012-03-22T00:00:00 | 2012-03-15T00:00:00 | 307500.00            | 
| 13-14-318-002-0000 | 1203329035 | MORTGAGE | 2012-02-02T00:00:00 | 2012-01-24T00:00:00 | 397100.00            | 
| 05-07-111-007-0000 | 1202326169 | MORTGAGE | 2012-01-23T00:00:00 | 2011-12-20T00:00:00 | 139000.00            | 
| 24-32-105-032-0000 | 1205910065 | MORTGAGE | 2012-02-28T00:00:00 | 2011-12-28T00:00:00 | 200000.00            | 
```