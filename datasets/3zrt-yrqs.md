# Licensed Intermediate Care Facilities

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/licensed-intermediate-care-facilities-8192e) |
| Metadata | [Link](https://data.hawaii.gov/api/views/3zrt-yrqs) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/3zrt-yrqs/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/3zrt-yrqs/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | 3zrt-yrqs |
| Name | Licensed Intermediate Care Facilities |
| Attribution | Department of Health |
| Category | Health |
| Tags | mental health, retarded |
| Created | 2012-08-26T21:40:19Z |
| Publication Date | 2012-08-26T21:45:43Z |

## Description

Licensed Intermediate Care Facilities for the Mentally Retarded

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | name        | Name       | text      | text        |
| Yes      | series tag  | services    | Services   | text      | text        |
| Yes      | series tag  | house       | House      | text      | text        |
| Yes      | series tag  | zip_code    | Zip code   | text      | text        |
| Yes      | series tag  | island      | Island     | text      | text        |
| Yes      | series tag  | phone       | PHONE      | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:3zrt-yrqs d:2012-08-26T14:40:26.000Z t:phone=737-7995 t:services="Licensed Intermediate Care Facilities for the Mentally Retarded" t:zip_code=96786 t:name="THE ARC IN HAWAII          (WAHIAWA A)" t:house=140-A t:island=Oahu m:row_number.3zrt-yrqs=1

series e:3zrt-yrqs d:2012-08-26T14:40:26.000Z t:phone=622-3929 t:services="Licensed Intermediate Care Facilities for the Mentally Retarded" t:zip_code=96786 t:name="OPPORTUNITIES AND RESOURCES, INC." t:house=64-1510 t:island=Oahu m:row_number.3zrt-yrqs=2

series e:3zrt-yrqs d:2012-08-26T14:40:26.000Z t:phone=737-7995 t:services="Licensed Intermediate Care Facilities for the Mentally Retarded" t:zip_code=96706 t:name="THE ARC IN HAWAII" t:house="91-824 B" t:island=Oahu m:row_number.3zrt-yrqs=3
```

## Meta Commands

```ls
metric m:row_number.3zrt-yrqs p:long l:"Row Number"

entity e:3zrt-yrqs l:"Licensed Intermediate Care Facilities" t:attribution="Department of Health" t:url=https://data.hawaii.gov/api/views/3zrt-yrqs

property e:3zrt-yrqs t:meta.view v:id=3zrt-yrqs v:category=Health v:attributionLink=http://hawaii.gov/health v:averageRating=0 v:name="Licensed Intermediate Care Facilities" v:attribution="Department of Health"

property e:3zrt-yrqs t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:3zrt-yrqs t:meta.view.owner v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:displayName="OIMT Open Data Coordinator"

property e:3zrt-yrqs t:meta.view.tableauthor v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:roleName=publisher v:displayName="OIMT Open Data Coordinator"
```

## Top Records

```ls
| :updated_at | name                              | services                                                        | house    | zip_code | island | phone    | 
| =========== | ================================= | =============================================================== | ======== | ======== | ====== | ======== | 
| 1345992026  | THE ARC IN HAWAII (WAHIAWA A)     | Licensed Intermediate Care Facilities for the Mentally Retarded | 140-A    | 96786    | Oahu   | 737-7995 | 
| 1345992026  | OPPORTUNITIES AND RESOURCES, INC. | Licensed Intermediate Care Facilities for the Mentally Retarded | 64-1510  | 96786    | Oahu   | 622-3929 | 
| 1345992026  | THE ARC IN HAWAII                 | Licensed Intermediate Care Facilities for the Mentally Retarded | 91-824 B | 96706    | Oahu   | 737-7995 | 
| 1345992026  | THE ARC IN HAWAII                 | Licensed Intermediate Care Facilities for the Mentally Retarded | 852      | 96816    | Oahu   | 737-7995 | 
| 1345992026  | THE ARC OF MAUI (HALE KANALOA)    | Licensed Intermediate Care Facilities for the Mentally Retarded | 450 B    | 96732    | Maui   | 242-5781 | 
| 1345992026  | OPPORTUNITIES AND RESOURCES, INC. | Licensed Intermediate Care Facilities for the Mentally Retarded | 64-1510  | 96786    | Oahu   | 622-3929 | 
| 1345992026  | THE ARC IN HAWAII                 | Licensed Intermediate Care Facilities for the Mentally Retarded | 91-824 C | 96706    | Oahu   | 737-7995 | 
| 1345992026  | THE ARC IN HAWAII                 | Licensed Intermediate Care Facilities for the Mentally Retarded | 852-A    | 96816    | Oahu   | 737-7995 | 
| 1345992026  | OPPORTUNITIES AND RESOURCES, INC. | Licensed Intermediate Care Facilities for the Mentally Retarded | 64-1510  | 96786    | Oahu   | 622-3929 | 
| 1345992026  | THE ARC OF MAUI (HALE KIHEI)      | Licensed Intermediate Care Facilities for the Mentally Retarded | 179      | 96753    | Maui   | 242-5781 | 
```