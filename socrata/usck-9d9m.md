# SEALS OF QUALITY

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/seals-of-quality-2090b) |
| Metadata | [Link](https://data.hawaii.gov/api/views/usck-9d9m) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/usck-9d9m/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/usck-9d9m/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | usck-9d9m |
| Name | SEALS OF QUALITY |
| Attribution | Hawaii Department of Agriculture |
| Category | Economic Development |
| Tags | seals of quality, agriculture |
| Created | 2012-07-03T21:47:11Z |
| Publication Date | 2012-08-06T20:53:29Z |

## Description

Seals of Quality represents the cream of the crop of Hawai`i's agricultural producers. Products with this seal are genuine, Hawai`i-grown or Hawai`i-made premium products, a guarantee that is enforced by the State of Hawai`i.

## Columns

```ls
| Included | Schema Type | Field Name         | Name               | Data Type | Render Type |
| ======== | =========== | ================== | ================== | ========= | =========== |
| No       | time        | :updated_at        | updated_at         | meta_data | meta_data   |
| Yes      | series tag  | company            | Company            | text      | text        |
| Yes      | series tag  | certified_products | Certified Products | text      | text        |
| Yes      | series tag  | website            | Website            | url       | url         |
| Yes      | series tag  | island             | Island             | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:usck-9d9m d:2012-08-06T13:50:33.000Z t:certified_products="copper stem art, living vase, living wall" t:website=http://1stlookexteriors.com t:company="1st Look Exteriors" t:island=Oahu m:row_number.usck-9d9m=1

series e:usck-9d9m d:2012-08-06T13:50:33.000Z t:certified_products="chocolate covered mac nuts" t:website=http://menehunemac.com t:company="Hawaiian Candies & Nuts" t:island=Oahu m:row_number.usck-9d9m=2

series e:usck-9d9m d:2012-08-06T13:50:33.000Z t:certified_products="taro chip, sweet potato chip" t:website=http://hawaiianchipcompany.com t:company="Hawaiian Chip Company" t:island=Oahu m:row_number.usck-9d9m=3
```

## Meta Commands

```ls
metric m:row_number.usck-9d9m p:long l:"Row Number"

entity e:usck-9d9m l:"SEALS OF QUALITY" t:attribution="Hawaii Department of Agriculture" t:url=https://data.hawaii.gov/api/views/usck-9d9m

property e:usck-9d9m t:meta.view v:id=usck-9d9m v:category="Economic Development" v:attributionLink=http://hawaii.gov/agriculture v:averageRating=0 v:name="SEALS OF QUALITY" v:attribution="Hawaii Department of Agriculture"

property e:usck-9d9m t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:usck-9d9m t:meta.view.owner v:id=t6a8-bm3j v:screenName="DOA Open Data Coordinator" v:displayName="DOA Open Data Coordinator"

property e:usck-9d9m t:meta.view.tableauthor v:id=t6a8-bm3j v:screenName="DOA Open Data Coordinator" v:roleName=publisher v:displayName="DOA Open Data Coordinator"
```

## Top Records

```ls
| :updated_at | company                  | certified_products                              | website                                 | island | 
| =========== | ======================== | =============================================== | ======================================= | ====== | 
| 1344261033  | 1st Look Exteriors       | copper stem art, living vase, living wall       | [http://1stlookexteriors.com, null]     | Oahu   | 
| 1344261033  | Hawaiian Candies & Nuts  | chocolate covered mac nuts                      | [http://menehunemac.com, null]          | Oahu   | 
| 1344261033  | Hawaiian Chip Company    | taro chip, sweet potato chip                    | [http://hawaiianchipcompany.com, null]  | Oahu   | 
| 1344261033  | Hawaiian Nougat Company  | nougat                                          | [http://hawaiiannougat.com, null]       | Oahu   | 
| 1344261033  | Hawaii Nutrition Company | noni juice, noni products                       | [http://hawaiinutrition.com, null]      | Oahu   | 
| 1344261033  | Hawaiian Rainbow Bees    | honey                                           | [http://rainbowbees.com, null]          | Oahu   | 
| 1344261033  | Ho Farms                 | tomatoes, cucumbers, squashes, long beans       | [http://hofarms.com, null]              | Oahu   | 
| 1344261033  | HPC Foods                | poi, poi powder                                 | [http://hpcfoods.com, null]             | Oahu   | 
| 1344261033  | Hula Girl Foods          | sugar cane stick                                | [http://hulagirlfoods.com, null]        | Oahu   | 
| 1344261033  | Island Princess          | mac nuts, chocolate covered mac nuts, mele macs | [http://islandprincesshawaii.com, null] | Oahu   | 
```