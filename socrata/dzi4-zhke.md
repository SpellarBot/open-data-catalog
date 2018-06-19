# Telecom Facilities On City Property

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/telecom-facilities-on-city-property) |
| Metadata | [Link](https://data.srcity.org/api/views/dzi4-zhke) |
| Data: JSON | [100 Rows](https://data.srcity.org/api/views/dzi4-zhke/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.srcity.org/api/views/dzi4-zhke/rows.csv?max_rows=100) |
| Host | data.srcity.org |
| Id | dzi4-zhke |
| Name | Telecom Facilities On City Property |
| Category | Government |
| Tags | cell sites |
| Created | 2016-05-11T20:50:08Z |
| Publication Date | 2016-05-11T20:50:46Z |

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| No       | time           | :updated_at       | updated_at        | meta_data | meta_data   |
| Yes      | series tag     | cell_site_type    | Cell Site Type    | text      | text        |
| Yes      | series tag     | wireless_provider | Wireless Provider | text      | text        |
| Yes      | numeric metric | tower_height_ft   | Tower Height (ft) | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:dzi4-zhke d:2016-05-11T13:50:38.000Z t:cell_site_type="Macro Site" t:wireless_provider=T-Mobile m:tower_height_ft=80

series e:dzi4-zhke d:2016-05-11T13:50:39.000Z t:cell_site_type="Macro Site" t:wireless_provider=AT&T m:tower_height_ft=85

series e:dzi4-zhke d:2016-05-11T13:50:39.000Z t:cell_site_type="Macro Site" t:wireless_provider="New Cellular Wireless" m:tower_height_ft=60
```

## Meta Commands

```ls
metric m:tower_height_ft p:integer l:"Tower Height (ft)" t:dataTypeName=number

entity e:dzi4-zhke l:"Telecom Facilities On City Property" t:url=https://data.srcity.org/api/views/dzi4-zhke

property e:dzi4-zhke t:meta.view v:id=dzi4-zhke v:category=Government v:averageRating=0 v:name="Telecom Facilities On City Property"

property e:dzi4-zhke t:meta.view.owner v:id=sa6t-4jry v:profileImageUrlMedium=/api/users/sa6t-4jry/profile_images/THUMB v:profileImageUrlLarge=/api/users/sa6t-4jry/profile_images/LARGE v:screenName="McHenry, Eric" v:profileImageUrlSmall=/api/users/sa6t-4jry/profile_images/TINY v:displayName="McHenry, Eric"

property e:dzi4-zhke t:meta.view.tableauthor v:id=sa6t-4jry v:profileImageUrlMedium=/api/users/sa6t-4jry/profile_images/THUMB v:profileImageUrlLarge=/api/users/sa6t-4jry/profile_images/LARGE v:screenName="McHenry, Eric" v:profileImageUrlSmall=/api/users/sa6t-4jry/profile_images/TINY v:roleName=administrator v:displayName="McHenry, Eric"
```

## Top Records

```ls
| :updated_at | cell_site_type | wireless_provider     | tower_height_ft | 
| =========== | ============== | ===================== | =============== | 
| 1462974638  | Macro Site     | T-Mobile              | 80              | 
| 1462974639  | Macro Site     | AT&T                  | 85              | 
| 1462974639  | Macro Site     | New Cellular Wireless | 60              | 
| 1462974639  | Macro Site     | T-Mobile              | 61              | 
| 1462974639  | Macro Site     | T-Mobile USA, Inc.    |                 | 
| 1462974639  | Macro Site     | Verizon Wireless      | 61              | 
| 1462974639  | Macro Site     | AT&T                  | 82              | 
| 1462974639  | Macro Site     | AT&T                  |                 | 
| 1462974639  | Macro Site     | T-Mobile              | 76              | 
| 1462974639  | Macro Site     | Verizon Wireless      |                 | 
```