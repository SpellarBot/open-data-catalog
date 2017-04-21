# Pet License Sales Locations NO TAGS

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/pet-license-sales-locations-no-tags-acbbf) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/q5ft-kink) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/q5ft-kink/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/q5ft-kink/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | q5ft-kink |
| Name | Pet License Sales Locations NO TAGS |
| Category | Pets |
| Created | 2012-09-26T21:15:17Z |
| Publication Date | 2016-02-03T18:45:42Z |

## Description

Locations that do NOT have physical license tags for sale, just mailers to obtain tags

## Columns

```ls
| Included | Schema Type | Field Name                | Name                       | Data Type | Render Type |
| ======== | =========== | ========================= | ========================== | ========= | =========== |
| No       | time        | :updated_at               | updated_at                 | meta_data | meta_data   |
| Yes      | series tag  | city                      | City                       | text      | text        |
| Yes      | series tag  | agency                    | Agency                     | text      | text        |
| Yes      | series tag  | suite                     | Suite                      | text      | text        |
| Yes      | series tag  | telephone                 | Telephone                  | text      | text        |
| Yes      | series tag  | license_mailers_available | License Mailers Available? | text      | text        |
| Yes      | series tag  | license_tags_available    | License Tags Available?    | text      | text        |
| Yes      | series tag  | notes                     | Notes                      | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:q5ft-kink d:2013-02-12T12:23:27.000Z t:license_tags_available=N t:license_mailers_available=Y t:agency="Animal Clinic of Kent" t:telephone=253-859-1520 t:city=Kent m:row_number.q5ft-kink=1

series e:q5ft-kink d:2013-02-12T12:23:43.000Z t:license_tags_available=N t:license_mailers_available=Y t:agency="Benson Center Veterinary and Laser Clinic" t:telephone="253 852-0580" t:city=Kent m:row_number.q5ft-kink=2

series e:q5ft-kink d:2013-02-12T12:23:43.000Z t:license_tags_available=N t:license_mailers_available=Y t:agency="Snoqualmie Valley Pet Parlor" t:telephone="425 888-3120" t:city=Snoqualmie m:row_number.q5ft-kink=3
```

## Meta Commands

```ls
metric m:row_number.q5ft-kink p:long l:"Row Number"

entity e:q5ft-kink l:"Pet License Sales Locations NO TAGS" t:url=https://data.kingcounty.gov/api/views/q5ft-kink

property e:q5ft-kink t:meta.view v:id=q5ft-kink v:category=Pets v:averageRating=0 v:name="Pet License Sales Locations NO TAGS"

property e:q5ft-kink t:meta.view.license v:name="Public Domain"

property e:q5ft-kink t:meta.view.owner v:id=ph9f-eu4i v:screenName=Cameron v:displayName=Cameron

property e:q5ft-kink t:meta.view.tableauthor v:id=ph9f-eu4i v:screenName=Cameron v:roleName=publisher v:displayName=Cameron
```

## Top Records

```ls
| :updated_at | city             | agency                                    | suite      | telephone    | license_mailers_available | license_tags_available | notes | 
| =========== | ================ | ========================================= | ========== | ============ | ========================= | ====================== | ===== | 
| 1360671807  | Kent             | Animal Clinic of Kent                     |            | 253-859-1520 | Y                         | N                      |       | 
| 1360671823  | Kent             | Benson Center Veterinary and Laser Clinic |            | 253 852-0580 | Y                         | N                      |       | 
| 1360671823  | Snoqualmie       | Snoqualmie Valley Pet Parlor              |            | 425 888-3120 | Y                         | N                      |       | 
| 1360671823  | North Bend       | Mount Si Senior Center                    | PO Box 806 | 425 888-3434 | Y                         | N                      |       | 
| 1360671823  | Lake Forest Park | Lake Forest Park Animal Hospital          |            | 206-363-5656 | Y                         | N                      |       | 
| 1360671823  | Maple Valley     | Poochie's A Cut Above Dog Salon           |            | 425 432-0191 | Y                         | N                      |       | 
| 1360671823  | Kent             | Paws and Claws Pet Salon                  | Ste 105    | 253 946-2445 | Y                         | N                      |       | 
| 1360671827  | Fall City        | Snoqualmie Valley Animal Hospital         |            | 425-222-7220 | Y                         | N                      |       | 
| 1360671827  | Enumclaw         | Cumberland Grocery                        |            | 360 886-2745 | Y                         | N                      |       | 
| 1360671827  | Kent             | McMonigle Veterinary Hospital             |            | 253 852-3565 | Y                         | N                      |       | 
```