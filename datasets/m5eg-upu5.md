# Home Health Care - Zip Codes

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/home-health-care-zip-codes-0c0fb) |
| Metadata | [Link](https://data.medicare.gov/api/views/m5eg-upu5) |
| Data: JSON | [100 Rows](https://data.medicare.gov/api/views/m5eg-upu5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicare.gov/api/views/m5eg-upu5/rows.csv?max_rows=100) |
| Host | data.medicare.gov |
| Id | m5eg-upu5 |
| Name | Home Health Care - Zip Codes |
| Category | Home Health Compare |
| Tags | hhc, general information |
| Created | 2012-10-17T19:56:31Z |
| Publication Date | 2017-07-11T23:59:14Z |

## Columns

```ls
| Included | Schema Type | Field Name      | Name                            | Data Type | Render Type |
| ======== | =========== | =============== | =============================== | ========= | =========== |
| No       | time        | :updated_at     | updated_at                      | meta_data | meta_data   |
| Yes      | series tag  | state           | State                           | text      | text        |
| Yes      | series tag  | provider_number | CMS Certification Number (CCN)* | text      | text        |
| Yes      | series tag  | zip_code        | ZIP Code                        | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:m5eg-upu5 d:2017-06-26T17:38:51.000Z t:provider_number=017000 t:state=AL t:zip_code=36104 m:row_number.m5eg-upu5=1

series e:m5eg-upu5 d:2017-06-26T17:38:51.000Z t:provider_number=017008 t:state=AL t:zip_code=35005 m:row_number.m5eg-upu5=2

series e:m5eg-upu5 d:2017-06-26T17:38:51.000Z t:provider_number=017008 t:state=AL t:zip_code=35020 m:row_number.m5eg-upu5=3
```

## Meta Commands

```ls
metric m:row_number.m5eg-upu5 p:long l:"Row Number"

entity e:m5eg-upu5 l:"Home Health Care - Zip Codes" t:url=https://data.medicare.gov/api/views/m5eg-upu5

property e:m5eg-upu5 t:meta.view d:2017-09-25T07:26:56.446Z v:averageRating=0 v:name="Home Health Care - Zip Codes" v:id=m5eg-upu5 v:category="Home Health Compare"

property e:m5eg-upu5 t:meta.view.owner d:2017-09-25T07:26:56.446Z v:displayName=cms v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:id=drs7-75yr v:screenName=cms v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB

property e:m5eg-upu5 t:meta.view.tableauthor d:2017-09-25T07:26:56.446Z v:displayName=cms v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:roleName=administrator v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:id=drs7-75yr v:screenName=cms v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB

property e:m5eg-upu5 t:meta.view.metadata.custom_fields.common_core d:2017-09-25T07:26:56.446Z v:Contact_Email=HomeHealthQualityQuestions@cms.hhs.gov v:Contact_Name=CMS v:Program_Code=009:078 v:Publisher="Centers for Medicare & Medicaid Services (CMS)" v:Bureau_Code=009:38
```

## Top Records

```ls
| :updated_at | state | provider_number | zip_code | 
| =========== | ===== | =============== | ======== | 
| 1498498731  | AL    | 017000          | 36104    | 
| 1498498731  | AL    | 017008          | 35005    | 
| 1498498731  | AL    | 017008          | 35020    | 
| 1498498731  | AL    | 017008          | 35022    | 
| 1498498731  | AL    | 017008          | 35023    | 
| 1498498731  | AL    | 017008          | 35061    | 
| 1498498731  | AL    | 017008          | 35064    | 
| 1498498731  | AL    | 017008          | 35068    | 
| 1498498731  | AL    | 017008          | 35071    | 
| 1498498731  | AL    | 017008          | 35094    | 
```