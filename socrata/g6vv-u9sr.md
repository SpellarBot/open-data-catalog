# Penalties

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/penalties-effb5) |
| Metadata | [Link](https://data.medicare.gov/api/views/g6vv-u9sr) |
| Data: JSON | [100 Rows](https://data.medicare.gov/api/views/g6vv-u9sr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicare.gov/api/views/g6vv-u9sr/rows.csv?max_rows=100) |
| Host | data.medicare.gov |
| Id | g6vv-u9sr |
| Name | Penalties |
| Category | Nursing Home Compare |
| Tags | nhc, nursing home, enforcement, penalties |
| Created | 2013-07-11T15:36:24Z |
| Publication Date | 2017-03-22T01:53:13Z |

## Description

A list of the fines and payment denials currently displayed on Nursing Home Compare.

## Columns

```ls
| Included | Schema Type    | Field Name                    | Name                          | Data Type     | Render Type   |
| ======== | ============== | ============================= | ============================= | ============= | ============= |
| Yes      | series tag     | federal_provider_number       | Federal Provider Number       | text          | text          |
| Yes      | series tag     | provider_name                 | Provider Name                 | text          | text          |
| No       |                | provider_address              | Provider Address              | text          | text          |
| Yes      | series tag     | provider_city                 | Provider City                 | text          | text          |
| Yes      | series tag     | provider_state                | Provider State                | text          | text          |
| Yes      | series tag     | provider_zip_code             | Provider Zip Code             | text          | text          |
| Yes      | time           | penalty_date                  | Penalty Date                  | calendar_date | calendar_date |
| Yes      | series tag     | penalty_type                  | Penalty Type                  | text          | text          |
| Yes      | numeric metric | fine_amount                   | Fine Amount                   | money         | money         |
| No       |                | payment_denial_start_date     | Payment Denial Start Date     | calendar_date | calendar_date |
| Yes      | numeric metric | payment_denial_length_in_days | Payment Denial Length in Days | number        | number        |
| No       |                | processing_date               | Processing Date               | calendar_date | calendar_date |
```

## Time Field

```ls
Value = penalty_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = provider_address,payment_denial_start_date,processing_date
```

## Data Commands

```ls
series e:g6vv-u9sr d:2014-10-02T00:00:00.000Z t:federal_provider_number=015019 t:penalty_type=Fine t:provider_zip_code=36025 t:provider_state=AL t:provider_city=ELMORE t:provider_name="MERRY WOOD LODGE CARE AND REHABILITATION CENTER" m:fine_amount=6600

series e:g6vv-u9sr d:2016-11-12T00:00:00.000Z t:federal_provider_number=015374 t:penalty_type=Fine t:provider_zip_code=36726 t:provider_state=AL t:provider_city=CAMDEN t:provider_name="CAMDEN NURSING FACILITY INC." m:fine_amount=162246

series e:g6vv-u9sr d:2016-04-01T00:00:00.000Z t:federal_provider_number=015375 t:penalty_type=Fine t:provider_zip_code=36207 t:provider_state=AL t:provider_city=ANNISTON t:provider_name="ANNISTON HEALTH AND REHAB SERVICES" m:fine_amount=135656
```

## Meta Commands

```ls
metric m:fine_amount p:integer l:"Fine Amount" t:dataTypeName=money

metric m:payment_denial_length_in_days p:integer l:"Payment Denial Length in Days" t:dataTypeName=number

entity e:g6vv-u9sr l:Penalties t:url=https://data.medicare.gov/api/views/g6vv-u9sr

property e:g6vv-u9sr t:meta.view v:id=g6vv-u9sr v:category="Nursing Home Compare" v:averageRating=0 v:name=Penalties

property e:g6vv-u9sr t:meta.view.owner v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:displayName=cms

property e:g6vv-u9sr t:meta.view.tableauthor v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:roleName=administrator v:displayName=cms

property e:g6vv-u9sr t:meta.view.metadata.custom_fields.common_core v:Publisher="Centers for Medicare & Medicaid Services (CMS)" v:Contact_Email=Edward.Mortimore@cms.hhs.gov v:Contact_Name=CMS v:Bureau_Code=009:38 v:Program_Code=009:078
```

## Top Records

```ls
| federal_provider_number | provider_name                                   | provider_address                         | provider_city | provider_state | provider_zip_code | penalty_date        | penalty_type   | fine_amount | payment_denial_start_date | payment_denial_length_in_days | processing_date     | 
| ======================= | =============================================== | ======================================== | ============= | ============== | ================= | =================== | ============== | =========== | ========================= | ============================= | =================== | 
| 015019                  | MERRY WOOD LODGE CARE AND REHABILITATION CENTER | P O BOX 130                              | ELMORE        | AL             | 36025             | 2014-10-02T00:00:00 | Fine           | 6600        |                           |                               | 2017-03-01T00:00:00 | 
| 015374                  | CAMDEN NURSING FACILITY INC.                    | 210 PONDEROSA DRIVE                      | CAMDEN        | AL             | 36726             | 2016-11-12T00:00:00 | Fine           | 162246      |                           |                               | 2017-03-01T00:00:00 | 
| 015375                  | ANNISTON HEALTH AND REHAB SERVICES              | P.O. BOX 1825                            | ANNISTON      | AL             | 36207             | 2016-04-01T00:00:00 | Fine           | 135656      |                           |                               | 2017-03-01T00:00:00 | 
| 015375                  | ANNISTON HEALTH AND REHAB SERVICES              | P.O. BOX 1825                            | ANNISTON      | AL             | 36207             | 2016-04-01T00:00:00 | Payment Denial |             | 2016-04-09T00:00:00       | 27                            | 2017-03-01T00:00:00 | 
| 015375                  | ANNISTON HEALTH AND REHAB SERVICES              | P.O. BOX 1825                            | ANNISTON      | AL             | 36207             | 2015-05-21T00:00:00 | Fine           | 715         |                           |                               | 2017-03-01T00:00:00 | 
| 025015                  | WRANGELL MEDICAL CENTER LTC                     | P.O. BOX 1081                            | WRANGELL      | AK             | 99929             | 2015-06-12T00:00:00 | Fine           | 1300        |                           |                               | 2017-03-01T00:00:00 | 
| 025015                  | WRANGELL MEDICAL CENTER LTC                     | P.O. BOX 1081                            | WRANGELL      | AK             | 99929             | 2014-08-14T00:00:00 | Fine           | 3900        |                           |                               | 2017-03-01T00:00:00 | 
| 025026                  | QUYANNA CARE CENTER                             | 1100 GREG KRUSCHEK AVENUE (P.O. BOX 966) | NOME          | AK             | 99762             | 2014-05-15T00:00:00 | Fine           | 1105        |                           |                               | 2017-03-01T00:00:00 | 
| 025037                  | YUKON KUSKOKWIM ELDER'S HOME                    | 1100 CHIEF EDDIE HOFFMAN HWY, PO BOX 528 | BETHEL        | AK             | 99559             | 2014-11-20T00:00:00 | Fine           | 6500        |                           |                               | 2017-03-01T00:00:00 | 
| 025037                  | YUKON KUSKOKWIM ELDER'S HOME                    | 1100 CHIEF EDDIE HOFFMAN HWY, PO BOX 528 | BETHEL        | AK             | 99559             | 2014-07-18T00:00:00 | Fine           | 3900        |                           |                               | 2017-03-01T00:00:00 | 
```