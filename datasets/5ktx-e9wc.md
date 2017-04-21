# NORA Uncommitted Property Inventory

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nora-uncommitted-property-inventory) |
| Metadata | [Link](https://data.nola.gov/api/views/5ktx-e9wc) |
| Data: JSON | [100 Rows](https://data.nola.gov/api/views/5ktx-e9wc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.nola.gov/api/views/5ktx-e9wc/rows.csv?max_rows=100) |
| Host | data.nola.gov |
| Id | 5ktx-e9wc |
| Name | NORA Uncommitted Property Inventory |
| Attribution | New Orleans Redevelopment Authority (NORA) |
| Category | Housing, Land Use, and Blight |
| Tags | redevelopment, property, inventory |
| Created | 2013-03-12T16:19:37Z |
| Publication Date | 2017-04-04T19:13:12Z |

## Description

This is a listing of all properties in NORA's inventory that are not under contract.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| No       | time           | :updated_at      | updated_at       | meta_data | meta_data   |
| Yes      | series tag     | identifier       | Identifier       | text      | text        |
| Yes      | series tag     | zip_code_2       | Zip Code         | text      | number      |
| Yes      | numeric metric | geopin_2         | GEOPIN           | number    | number      |
| Yes      | series tag     | council_district | Council District | text      | text        |
| Yes      | series tag     | property_type    | Property Type    | text      | text        |
| Yes      | numeric metric | square_footage   | Square Footage   | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:5ktx-e9wc d:2017-04-04T19:11:07.000Z t:property_type="VACANT LOT" t:zip_code_2=70114 t:council_district=C t:identifier=ORA700719 m:square_footage=115684 m:geopin_2=41000622

series e:5ktx-e9wc d:2017-04-04T19:11:07.000Z t:property_type="VACANT LOT" t:zip_code_2=70114 t:council_district=C t:identifier=ORA700878 m:square_footage=5627 m:geopin_2=41008115

series e:5ktx-e9wc d:2017-04-04T19:11:07.000Z t:property_type="VACANT LOT" t:council_district=C t:identifier=ORA700896 m:square_footage=2981 m:geopin_2=41130730
```

## Meta Commands

```ls
metric m:geopin_2 p:integer l:GEOPIN t:dataTypeName=number

metric m:square_footage p:integer l:"Square Footage" t:dataTypeName=number

entity e:5ktx-e9wc l:"NORA Uncommitted Property Inventory" t:attribution="New Orleans Redevelopment Authority (NORA)" t:url=https://data.nola.gov/api/views/5ktx-e9wc

property e:5ktx-e9wc t:meta.view v:id=5ktx-e9wc v:category="Housing, Land Use, and Blight" v:averageRating=0 v:name="NORA Uncommitted Property Inventory" v:attribution="New Orleans Redevelopment Authority (NORA)"

property e:5ktx-e9wc t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:5ktx-e9wc t:meta.view.owner v:id=c4j8-jv6s v:profileImageUrlMedium=/api/users/c4j8-jv6s/profile_images/THUMB v:profileImageUrlLarge=/api/users/c4j8-jv6s/profile_images/LARGE v:screenName=ssmadden v:profileImageUrlSmall=/api/users/c4j8-jv6s/profile_images/TINY v:lastNotificationSeenAt=1491333102 v:displayName=ssmadden

property e:5ktx-e9wc t:meta.view.tableauthor v:id=c4j8-jv6s v:profileImageUrlMedium=/api/users/c4j8-jv6s/profile_images/THUMB v:profileImageUrlLarge=/api/users/c4j8-jv6s/profile_images/LARGE v:screenName=ssmadden v:profileImageUrlSmall=/api/users/c4j8-jv6s/profile_images/TINY v:roleName=editor v:lastNotificationSeenAt=1491333102 v:displayName=ssmadden

property e:5ktx-e9wc t:meta.view.metadata.custom_fields.common_core v:Contact_Email=data@nola.gov
```

## Top Records

```ls
| :updated_at | identifier | zip_code_2 | geopin_2 | council_district | property_type | square_footage | 
| =========== | ========== | ========== | ======== | ================ | ============= | ============== | 
| 1491333067  | ORA700719  | 70114      | 41000622 | C                | VACANT LOT    | 115684         | 
| 1491333067  | ORA700878  | 70114      | 41008115 | C                | VACANT LOT    | 5627           | 
| 1491333067  | ORA700896  |            | 41130730 | C                | VACANT LOT    | 2981           | 
| 1491333067  | ORA700902  | 70114      | 41192196 | C                | VACANT LOT    | 4071           | 
| 1491333067  | ORA900355  | 70117      | 41069622 | D                | VACANT LOT    | 2050           | 
| 1491333067  | ORA900381  | 70117      | 41124222 | E                | VACANT LOT    | 8164           | 
| 1491333067  | ORA900993  | 70129      | 51000148 | E                | VACANT LOT    | 6000           | 
| 1491333067  | ORL050040  | 70116      | 41072323 | D                | VACANT LOT    | 3439           | 
| 1491333069  | ORL079968  | 70129      | 51000149 | E                | VACANT LOT    | 12000          | 
| 1491333092  | ORL066014  | 70117      | 41122434 | E                | VACANT LOT    | 3273           | 
```