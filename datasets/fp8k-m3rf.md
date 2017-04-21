# 2015 Business Licenses

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2015-business-licenses) |
| Metadata | [Link](https://data.jacksonms.gov/api/views/fp8k-m3rf) |
| Data: JSON | [100 Rows](https://data.jacksonms.gov/api/views/fp8k-m3rf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.jacksonms.gov/api/views/fp8k-m3rf/rows.csv?max_rows=100) |
| Host | data.jacksonms.gov |
| Id | fp8k-m3rf |
| Name | 2015 Business Licenses |
| Attribution | City of Jackson |
| Category | Economic Development |
| Tags | economic development, business, licenses, money, active licenses, business permits |
| Created | 2016-03-23T20:54:09Z |
| Publication Date | 2016-03-24T13:49:25Z |

## Description

This data displays all business license information for the year of 2015. This information details license classifications and status. This information will updated quarterly.

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type     | Render Type   |
| ======== | ============== | ======================= | ======================= | ============= | ============= |
| Yes      | time           | current_as_of           | Current As Of           | calendar_date | calendar_date |
| Yes      | series tag     | business_classification | Business Classification | text          | text          |
| Yes      | numeric metric | total                   | Total                   | number        | number        |
| Yes      | numeric metric | active                  | Active                  | number        | number        |
| Yes      | numeric metric | closed                  | Closed                  | number        | number        |
| Yes      | numeric metric | inactive                | Inactive                | number        | number        |
| Yes      | numeric metric | in_review_agency        | In Review Agency        | number        | number        |
| Yes      | numeric metric | payment_pending         | Payment Pending         | number        | number        |
| Yes      | numeric metric | purged                  | Purged                  | number        | number        |
| Yes      | numeric metric | renewed                 | Renewed                 | number        | number        |
```

## Time Field

```ls
Value = current_as_of
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:fp8k-m3rf d:2016-03-23T00:00:00.000Z t:business_classification="Automobile Dealer" m:total=9 m:inactive=0 m:in_review_agency=0 m:purged=0 m:renewed=0 m:payment_pending=0 m:active=9 m:closed=0

series e:fp8k-m3rf d:2016-03-23T00:00:00.000Z t:business_classification=Bank m:total=1 m:inactive=0 m:in_review_agency=0 m:purged=1 m:renewed=0 m:payment_pending=0 m:active=0 m:closed=0

series e:fp8k-m3rf d:2016-03-23T00:00:00.000Z t:business_classification="Beer Sales Retail Off Prem" m:total=14 m:inactive=0 m:in_review_agency=11 m:purged=0 m:renewed=0 m:payment_pending=2 m:active=1 m:closed=0
```

## Meta Commands

```ls
metric m:total p:integer l:Total t:dataTypeName=number

metric m:active p:integer l:Active t:dataTypeName=number

metric m:closed p:integer l:Closed t:dataTypeName=number

metric m:inactive p:integer l:Inactive t:dataTypeName=number

metric m:in_review_agency p:integer l:"In Review Agency" t:dataTypeName=number

metric m:payment_pending p:integer l:"Payment Pending" t:dataTypeName=number

metric m:purged p:integer l:Purged t:dataTypeName=number

metric m:renewed p:integer l:Renewed t:dataTypeName=number

entity e:fp8k-m3rf l:"2015 Business Licenses" t:attribution="City of Jackson" t:url=https://data.jacksonms.gov/api/views/fp8k-m3rf

property e:fp8k-m3rf t:meta.view v:id=fp8k-m3rf v:category="Economic Development" v:attributionLink=http://www.jacksonms.gov v:averageRating=0 v:name="2015 Business Licenses" v:attribution="City of Jackson"

property e:fp8k-m3rf t:meta.view.owner v:id=6ngd-c2u2 v:profileImageUrlMedium=/api/users/6ngd-c2u2/profile_images/THUMB v:profileImageUrlLarge=/api/users/6ngd-c2u2/profile_images/LARGE v:screenName="Justin Bruce" v:profileImageUrlSmall=/api/users/6ngd-c2u2/profile_images/TINY v:lastNotificationSeenAt=1492180672 v:displayName="Justin Bruce"

property e:fp8k-m3rf t:meta.view.tableauthor v:id=6ngd-c2u2 v:profileImageUrlMedium=/api/users/6ngd-c2u2/profile_images/THUMB v:profileImageUrlLarge=/api/users/6ngd-c2u2/profile_images/LARGE v:screenName="Justin Bruce" v:profileImageUrlSmall=/api/users/6ngd-c2u2/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1492180672 v:displayName="Justin Bruce"
```

## Top Records

```ls
| current_as_of       | business_classification    | total | active | closed | inactive | in_review_agency | payment_pending | purged | renewed | 
| =================== | ========================== | ===== | ====== | ====== | ======== | ================ | =============== | ====== | ======= | 
| 2016-03-23T00:00:00 | Automobile Dealer          | 9     | 9      | 0      | 0        | 0                | 0               | 0      | 0       | 
| 2016-03-23T00:00:00 | Bank                       | 1     | 0      | 0      | 0        | 0                | 0               | 1      | 0       | 
| 2016-03-23T00:00:00 | Beer Sales Retail Off Prem | 14    | 1      | 0      | 0        | 11               | 2               | 0      | 0       | 
| 2016-03-23T00:00:00 | Chiropractor               | 1     | 0      | 0      | 0        | 0                | 1               | 0      | 0       | 
| 2016-03-23T00:00:00 | Cigarettes Retail          | 52    | 42     | 1      | 1        | 0                | 6               | 1      | 1       | 
| 2016-03-23T00:00:00 | Cleaning Service           | 4     | 4      | 0      | 0        | 0                | 0               | 0      | 0       | 
| 2016-03-23T00:00:00 | Dance Hall                 | 8     | 8      | 0      | 0        | 0                | 0               | 0      | 0       | 
| 2016-03-23T00:00:00 | Daycare/PreSchool          | 5     | 5      | 0      | 0        | 0                | 0               | 0      | 0       | 
| 2016-03-23T00:00:00 | Deli                       | 5     | 5      | 0      | 0        | 0                | 0               | 0      | 0       | 
| 2016-03-23T00:00:00 | Dentist                    | 6     | 5      | 0      | 0        | 0                | 1               | 0      | 0       | 
```