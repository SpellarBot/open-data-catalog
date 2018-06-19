# Department of Defense Hawaii Army National Guard Facility Locations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/department-of-defense-hawaii-army-national-guard-facility-locations-469e1) |
| Metadata | [Link](https://data.hawaii.gov/api/views/9ms4-cvz7) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/9ms4-cvz7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/9ms4-cvz7/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | 9ms4-cvz7 |
| Name | Department of Defense Hawaii Army National Guard Facility Locations |
| Attribution | Department of defense |
| Category | Public Safety |
| Tags | army, hiarng |
| Created | 2012-07-31T21:46:55Z |
| Publication Date | 2012-08-06T18:56:52Z |

## Description

Hawaii Army National Guard Facility Locations

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | component   | Component  | text      | text        |
| Yes      | series tag  | island      | Island     | text      | text        |
| Yes      | series tag  | none        | (none)     | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:9ms4-cvz7 d:2012-07-31T14:46:56.000Z t:component=Component t:island=Island m:row_number.9ms4-cvz7=1

series e:9ms4-cvz7 d:2012-07-31T14:46:56.000Z t:component="Hawaii Army National Guard" t:none="Kalaeloa (JFHQ only)" t:island=Oahu m:row_number.9ms4-cvz7=2

series e:9ms4-cvz7 d:2012-07-31T14:46:56.000Z t:component="Hawaii Army National Guard" t:none="Waiawa (103d TC only)" t:island=Oahu m:row_number.9ms4-cvz7=3
```

## Meta Commands

```ls
metric m:row_number.9ms4-cvz7 p:long l:"Row Number"

entity e:9ms4-cvz7 l:"Department of Defense Hawaii Army National Guard Facility Locations" t:attribution="Department of defense" t:url=https://data.hawaii.gov/api/views/9ms4-cvz7

property e:9ms4-cvz7 t:meta.view v:id=9ms4-cvz7 v:category="Public Safety" v:attributionLink=http://hawaii.gov/dod v:averageRating=0 v:name="Department of Defense Hawaii Army National Guard Facility Locations" v:attribution="Department of defense"

property e:9ms4-cvz7 t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:9ms4-cvz7 t:meta.view.owner v:id=a7ka-qy6t v:screenName="Reynold Hioki" v:displayName="Reynold Hioki"

property e:9ms4-cvz7 t:meta.view.tableauthor v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:roleName=publisher v:displayName="OIMT Open Data Coordinator"
```

## Top Records

```ls
| :updated_at | component                  | island  | none                  | 
| =========== | ========================== | ======= | ===================== | 
| 1343746016  | Component                  | Island  |                       | 
| 1343746016  | Hawaii Army National Guard | Oahu    | Kalaeloa (JFHQ only)  | 
| 1343746016  | Hawaii Army National Guard | Oahu    | Waiawa (103d TC only) | 
| 1343746016  | Hawaii Army National Guard | Oahu    | Wahiawa (1-487)       | 
| 1343746016  | Hawaii Army National Guard | Oahu    | WAAF (AASF #1 only)   | 
| 1343746016  | Hawaii Army National Guard | Oahu    |                       | 
| 1343746016  | Hawaii Army National Guard | Oahu    |                       | 
| 1343746016  | Hawaii Army National Guard | Kauai   | Hanapepe (Kauai)      | 
| 1343746016  | Hawaii Army National Guard | Maui    | Puunene (Maui)        | 
| 1343746016  | Hawaii Army National Guard | Molokai | Kaunakakai (Molokai)  | 
```