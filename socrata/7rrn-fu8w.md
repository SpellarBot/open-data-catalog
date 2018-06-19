# Capital Planing and Policy - Facility Locations List

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/capital-planing-and-policy-facility-locations-list-61b5e) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/7rrn-fu8w) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/7rrn-fu8w/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/7rrn-fu8w/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | 7rrn-fu8w |
| Name | Capital Planing and Policy - Facility Locations List |
| Attribution | Cook County Department of Captial Planning and Policy |
| Category | Economic Development |
| Created | 2011-08-30T18:57:09Z |
| Publication Date | 2014-10-09T21:17:02Z |

## Description

A list of Cook County facilites by address, main phone number, and 10-digit PIN. Data last updated August 30, 2011.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| No       | time           | :updated_at       | updated_at        | meta_data | meta_data   |
| Yes      | series tag     | building          | Building          | text      | text        |
| Yes      | series tag     | code              | Code              | text      | text        |
| Yes      | series tag     | node_name         | Node Name         | text      | text        |
| Yes      | series tag     | main_phone_number | Main Phone Number | text      | text        |
| Yes      | numeric metric | pin10             | PIN10             | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:7rrn-fu8w d:2011-08-30T12:37:13.000Z t:building="Markham Courthouse" t:main_phone_number=708-596-8000 t:code=C t:node_name=Markham m:pin10=2824305043

series e:7rrn-fu8w d:2011-08-30T12:37:13.000Z t:building="Chicago ? Reed Mental" t:code=H t:node_name=None m:pin10=1318409051

series e:7rrn-fu8w d:2011-08-30T12:37:14.000Z t:building="Woodlawn Health Ctr" t:code=H t:node_name=Woodlawn m:pin10=2023200029
```

## Meta Commands

```ls
metric m:pin10 p:long l:PIN10 t:dataTypeName=number

entity e:7rrn-fu8w l:"Capital Planing and Policy - Facility Locations List" t:attribution="Cook County Department of Captial Planning and Policy" t:url=https://datacatalog.cookcountyil.gov/api/views/7rrn-fu8w

property e:7rrn-fu8w t:meta.view v:id=7rrn-fu8w v:category="Economic Development" v:attributionLink=http://www.cookcountygov.com/portal/server.pt/community/economic_development%2C_bureau_of/256/bureau_of_economic_development/356 v:averageRating=0 v:name="Capital Planing and Policy - Facility Locations List" v:attribution="Cook County Department of Captial Planning and Policy"

property e:7rrn-fu8w t:meta.view.license v:name="Public Domain"

property e:7rrn-fu8w t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:7rrn-fu8w t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| :updated_at | building                       | code | node_name  | main_phone_number | pin10      | 
| =========== | ============================== | ==== | ========== | ================= | ========== | 
| 1314705434  | Adult Probation Reporting Cntr | P    |            |                   |            | 
| 1314705434  | Adult Probation Reporting Cntr | P    |            |                   |            | 
| 1314707833  | Adult Probation Admin Bldg     | P    |            |                   |            | 
| 1314707833  | Markham Courthouse             | C    | Markham    | 708-596-8000      | 2824305043 | 
| 1314707833  | Chicago ? Reed Mental          | H    | None       |                   | 1318409051 | 
| 1314707834  | Woodlawn Health Ctr            | H    | Woodlawn   |                   | 2023200029 | 
| 1314707834  | Courtroom Chgo. Police         | C    | Hawthorne  | 773-804-6120      | 1333100006 | 
| 1314707834  | Oak Forest Hospital            | H    | Oak Forest | 708-687-7200      | 2822100001 | 
| 1314707834  | Juvenile ? New Facility        | D    | Juvenile   | 312-738-8200      | 1718336022 | 
| 1314707834  | DOC/Division 1                 | J    | Jail       | 773-890-7100      | 1625306001 | 
```