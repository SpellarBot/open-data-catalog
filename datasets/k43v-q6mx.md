# L&I Counties Listed On Intent

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/li-counties-listed-on-intent) |
| Metadata | [Link](https://data.wa.gov/api/views/k43v-q6mx) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/k43v-q6mx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/k43v-q6mx/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | k43v-q6mx |
| Name | L&I Counties Listed On Intent |
| Attribution | L&I |
| Category | Labor |
| Tags | intent, county |
| Created | 2015-11-13T00:54:56Z |
| Publication Date | 2015-12-04T22:36:27Z |

## Description

Counties Listed On Intent

## Columns

```ls
| Included | Schema Type | Field Name  | Name                    | Data Type | Render Type |
| ======== | =========== | =========== | ======================= | ========= | =========== |
| No       | time        | :updated_at | updated_at              | meta_data | meta_data   |
| Yes      | series tag  | intent_id   | Intent ID Number        | text      | number      |
| Yes      | series tag  | county_name | County Listed on Intent | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:k43v-q6mx d:2015-11-12T16:55:00.000Z t:intent_id=11312 t:county_name=Clark m:row_number.k43v-q6mx=1

series e:k43v-q6mx d:2015-11-12T16:55:00.000Z t:intent_id=11313 t:county_name=Snohomish m:row_number.k43v-q6mx=2

series e:k43v-q6mx d:2015-11-12T16:55:00.000Z t:intent_id=11314 t:county_name="Walla Walla" m:row_number.k43v-q6mx=3
```

## Meta Commands

```ls
metric m:row_number.k43v-q6mx p:long l:"Row Number"

entity e:k43v-q6mx l:"L&I Counties Listed On Intent" t:attribution=L&I t:url=https://data.wa.gov/api/views/k43v-q6mx

property e:k43v-q6mx t:meta.view v:id=k43v-q6mx v:category=Labor v:averageRating=0 v:name="L&I Counties Listed On Intent" v:attribution=L&I

property e:k43v-q6mx t:meta.view.owner v:id=sbxf-tc9c v:profileImageUrlMedium=/api/users/sbxf-tc9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/sbxf-tc9c/profile_images/LARGE v:screenName=Nithya v:profileImageUrlSmall=/api/users/sbxf-tc9c/profile_images/TINY v:displayName=Nithya

property e:k43v-q6mx t:meta.view.tableauthor v:id=sbxf-tc9c v:profileImageUrlMedium=/api/users/sbxf-tc9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/sbxf-tc9c/profile_images/LARGE v:screenName=Nithya v:profileImageUrlSmall=/api/users/sbxf-tc9c/profile_images/TINY v:roleName=publisher v:displayName=Nithya
```

## Top Records

```ls
| :updated_at | intent_id | county_name | 
| =========== | ========= | =========== | 
| 1447347300  | 11312     | Clark       | 
| 1447347300  | 11313     | Snohomish   | 
| 1447347300  | 11314     | Walla Walla | 
| 1447347300  | 11327     | Pierce      | 
| 1447347300  | 11328     | King        | 
| 1447347300  | 11330     | Spokane     | 
| 1447347300  | 11344     | King        | 
| 1447347300  | 11345     | Kitsap      | 
| 1447347300  | 11346     | Benton      | 
| 1447347300  | 11347     | Douglas     | 
```