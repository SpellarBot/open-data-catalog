# Presumptive Eligibility for Medicaid and CHIP Coverage

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/presumptive-eligibility-for-medicaid-and-chip-coverage) |
| Metadata | [Link](https://data.medicaid.gov/api/views/xjuw-wgmy) |
| Data: JSON | [100 Rows](https://data.medicaid.gov/api/views/xjuw-wgmy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicaid.gov/api/views/xjuw-wgmy/rows.csv?max_rows=100) |
| Host | data.medicaid.gov |
| Id | xjuw-wgmy |
| Name | Presumptive Eligibility for Medicaid and CHIP Coverage |
| Attribution | Centers for Medicare and Medicaid Services |
| Category | Eligibility |
| Tags | enrollment strategies, presumptive eligibility |
| Created | 2016-07-13T18:03:19Z |
| Publication Date | 2016-07-13T19:17:20Z |

## Description

Health care providers and Head Start programs can play a major role in finding and enrolling uninsured children through presumptive eligibility. States can authorize ?qualified entities? -- health care providers, community-based organizations, and schools, among others -- to screen for Medicaid and CHIP eligibility and immediately enroll children who appear to be eligible.

Presumptive eligibility allows children to get access to Medicaid or CHIP services without having to wait for their application to be fully processed. Qualified entities can also help families gather the documents needed to complete the full application process, thereby reducing the administrative burden on States to obtain missing information.

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | state       | State      | text      | text        |
| Yes      | series tag  | chip        | CHIP       | checkbox  | checkbox    |
| Yes      | series tag  | medicaid    | Medicaid   | checkbox  | checkbox    |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:xjuw-wgmy d:2016-07-13T12:14:42.000Z t:state=Wisconsin t:medicaid=true m:row_number.xjuw-wgmy=1

series e:xjuw-wgmy d:2016-07-13T12:16:41.000Z t:state=Missouri t:medicaid=true m:row_number.xjuw-wgmy=2

series e:xjuw-wgmy d:2016-07-13T11:03:22.000Z t:chip=true t:state=California t:medicaid=true m:row_number.xjuw-wgmy=3
```

## Meta Commands

```ls
metric m:row_number.xjuw-wgmy p:long l:"Row Number"

entity e:xjuw-wgmy l:"Presumptive Eligibility for Medicaid and CHIP Coverage" t:attribution="Centers for Medicare and Medicaid Services" t:url=https://data.medicaid.gov/api/views/xjuw-wgmy

property e:xjuw-wgmy t:meta.view v:id=xjuw-wgmy v:category=Eligibility v:attributionLink=https://www.medicaid.gov v:averageRating=0 v:name="Presumptive Eligibility for Medicaid and CHIP Coverage" v:attribution="Centers for Medicare and Medicaid Services"

property e:xjuw-wgmy t:meta.view.license v:name="Public Domain"

property e:xjuw-wgmy t:meta.view.owner v:id=nmzs-t286 v:profileImageUrlMedium=/api/users/nmzs-t286/profile_images/THUMB v:profileImageUrlLarge=/api/users/nmzs-t286/profile_images/LARGE v:screenName="Jeff Chamblee" v:profileImageUrlSmall=/api/users/nmzs-t286/profile_images/TINY v:lastNotificationSeenAt=1491332351 v:displayName="Jeff Chamblee"

property e:xjuw-wgmy t:meta.view.tableauthor v:id=nmzs-t286 v:profileImageUrlMedium=/api/users/nmzs-t286/profile_images/THUMB v:profileImageUrlLarge=/api/users/nmzs-t286/profile_images/LARGE v:screenName="Jeff Chamblee" v:profileImageUrlSmall=/api/users/nmzs-t286/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1491332351 v:displayName="Jeff Chamblee"

property e:xjuw-wgmy t:meta.view.metadata.custom_fields.common_core v:Bureau_Code=009:00 v:Program_Code=009:076
```

## Top Records

```ls
| :updated_at | state         | chip | medicaid | 
| =========== | ============= | ==== | ======== | 
| 1468412082  | Wisconsin     |      | true     | 
| 1468412201  | Missouri      |      | true     | 
| 1468407802  | California    | true | true     | 
| 1468407802  | Illinois      | true | true     | 
| 1468407802  | Iowa          | true | true     | 
| 1468407802  | Kansas        | true | true     | 
| 1468407802  | Massachusetts | true | true     | 
| 1468407802  | Michigan      | true | true     | 
| 1468407802  | Montana       | true | true     | 
| 1468407802  | New Jersey    | true | true     | 
```