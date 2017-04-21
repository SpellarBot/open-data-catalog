# COA FUEL BY ICMA Class

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/coa-fuel-by-icma-class) |
| Metadata | [Link](https://data.austintexas.gov/api/views/vyev-yeag) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/vyev-yeag/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/vyev-yeag/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | vyev-yeag |
| Name | COA FUEL BY ICMA Class |
| Category | Environmental |
| Created | 2015-06-29T15:50:42Z |
| Publication Date | 2017-01-11T11:00:18Z |

## Description

This is a breakdown of fuel usage by ICMA class

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type | Render Type |
| ======== | ============== | ============ | ============ | ========= | =========== |
| No       | time           | :updated_at  | updated_at   | meta_data | meta_data   |
| Yes      | series tag     | icma_class   | ICMA_CLASS   | text      | text        |
| Yes      | numeric metric | propane      | PROPANE      | number    | number      |
| Yes      | numeric metric | e10_unleaded | E10_UNLEADED | number    | number      |
| Yes      | numeric metric | diesel       | DIESEL       | number    | number      |
| Yes      | numeric metric | biodiesel    | BIODIESEL    | number    | text        |
| Yes      | numeric metric | cng          | CNG          | number    | number      |
| Yes      | numeric metric | e85          | E85          | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:vyev-yeag d:2017-04-20T10:00:13.000Z t:icma_class="ICMA MED VEH 10,001-19,500" m:diesel=18203.3 m:cng=51.3 m:propane=54092 m:e10_unleaded=24862.499 m:biodiesel=252876.7 m:e85=10760.9

series e:vyev-yeag d:2017-04-20T10:00:13.000Z t:icma_class="ICMA LIGHT VEH <10,000 GVW" m:diesel=2468.1 m:cng=44.2 m:propane=20622.3 m:e10_unleaded=406462.4 m:biodiesel=35967 m:e85=196894.4

series e:vyev-yeag d:2017-04-20T10:00:13.000Z t:icma_class="NON ICMA EQUIPMENT" m:diesel=3468.9 m:propane=46.5 m:e10_unleaded=588.1 m:biodiesel=2653.9 m:e85=21
```

## Meta Commands

```ls
metric m:propane p:float l:PROPANE t:dataTypeName=number

metric m:e10_unleaded p:float l:E10_UNLEADED t:dataTypeName=number

metric m:diesel p:float l:DIESEL t:dataTypeName=number

metric m:biodiesel p:double l:BIODIESEL t:dataTypeName=number

metric m:cng p:float l:CNG t:dataTypeName=number

metric m:e85 p:float l:E85 t:dataTypeName=number

entity e:vyev-yeag l:"COA FUEL BY ICMA  Class" t:url=https://data.austintexas.gov/api/views/vyev-yeag

property e:vyev-yeag t:meta.view v:id=vyev-yeag v:category=Environmental v:averageRating=0 v:name="COA FUEL BY ICMA  Class"

property e:vyev-yeag t:meta.view.license v:name="Public Domain"

property e:vyev-yeag t:meta.view.owner v:id=bcru-v2iw v:profileImageUrlMedium=/api/users/bcru-v2iw/profile_images/THUMB v:profileImageUrlLarge=/api/users/bcru-v2iw/profile_images/LARGE v:screenName="Fleet Services" v:profileImageUrlSmall=/api/users/bcru-v2iw/profile_images/TINY v:displayName="Fleet Services"

property e:vyev-yeag t:meta.view.tableauthor v:id=bcru-v2iw v:profileImageUrlMedium=/api/users/bcru-v2iw/profile_images/THUMB v:profileImageUrlLarge=/api/users/bcru-v2iw/profile_images/LARGE v:screenName="Fleet Services" v:profileImageUrlSmall=/api/users/bcru-v2iw/profile_images/TINY v:roleName=editor v:displayName="Fleet Services"
```

## Top Records

```ls
| :updated_at | icma_class                      | propane | e10_unleaded | diesel  | biodiesel  | cng    | e85      | 
| =========== | =============================== | ======= | ============ | ======= | ========== | ====== | ======== | 
| 1492682413  | ICMA MED VEH 10,001-19,500      | 54092   | 24862.499    | 18203.3 | 252876.7   | 51.3   | 10760.9  | 
| 1492682413  | ICMA LIGHT VEH <10,000 GVW      | 20622.3 | 406462.4     | 2468.1  | 35967      | 44.2   | 196894.4 | 
| 1492682413  | NON ICMA EQUIPMENT              | 46.5    | 588.1        | 3468.9  | 2653.9     |        | 21       | 
| 1492682413  | ICMA MARKED POLICE VEHICLES     |         | 327298.7     |         |            |        | 275126.9 | 
| 1492682413  | UNCLASSIFIED                    |         |              | 1599.3  | 1221.3     | 91.6   |          | 
| 1492682413  | ICMA FIRE APPARATUS             |         | 290.7        | 12650.7 | 106446.095 |        |          | 
| 1492682413  | LIGHT EQUIPMENT OFF-ROAD        | 6129.6  | 3848.75      | 10072.8 | 12644.899  |        | 6        | 
| 1492682413  | ICMA HEAVY >=19,501             | 3162.4  | 1412.8       | 42178.8 | 377209.099 | 5419.2 | 31.5     | 
| 1492682413  | ICMA OFF ROAD & CONST >= 10,000 |         | 49.8         | 19849.7 | 19010.1    | 8559.5 |          | 
| 1492682413  | NONE-MISC, MISX                 | 3586.2  | 18332.6      | 10442.5 | 23753.6    |        | 269      | 
```